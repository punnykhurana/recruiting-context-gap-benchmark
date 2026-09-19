# The Recruiting Context Gap — Signal-Loss Benchmark

An open, reproducible measurement of how much of a job description survives the translation into a hand-built Boolean search string.

**Author:** Pankaj Khurana (firki.ai)
**Study date:** September 19, 2026 · **n = 100** job descriptions

## Headline finding

> Across 100 job descriptions averaging 19.6 discrete signals each, a realistic hand-built Boolean search captured just **31%** of them. **More than two-thirds of the JD's signal never made it into the search.**

## The data

`data/signal-study.csv` — per-JD results: role, company, signal count, Boolean term count, signals captured, coverage %, JD type (fetched vs. representative), source URL.

Aggregate: 1,965 signals scored · 612 captured · mean coverage **31.1%** (median 30.0%, range 16–45%) · mean signal loss **68.9%** · mean signals/JD **19.6** · mean Boolean terms **10.1**.

Full per-JD working (numbered signals, the reconstructed Boolean, captured-vs-lost lists, one-line rationale) is in `methodology.md`.

## Methodology (summary)

1. **JD collection** — 100 postings: 10 fetched in full from public job boards (Greenhouse-hosted, Sep 19, 2026; source URL recorded per JD) plus 90 representative postings across tech and non-tech roles. Cohort is roughly 43% tech / 57% non-tech.
2. **Signal extraction** — each JD reduced to discrete, searchable facts ("signals"): hard skills, tools, seniority indicators, domain/industry terms, qualifications, meaningful qualifiers. One analyst's consistent scheme, applied uniformly.
3. **Hand-built Boolean** — for each JD, the Boolean a competent sourcer would plausibly hand-build in a few minutes (~10 terms, title variants, core skills, obvious OR-expansions). Realistic, not a strawman.
4. **Coverage scoring** — signals captured by the Boolean counted generously (clear synonyms and strong implications count). Coverage = captured ÷ total signals.

## Limitations

- The hand-built Booleans are researcher-reconstructed, not observed from working sourcers — the study's biggest caveat.
- "Captured, even loosely" involves judgment calls; the per-JD working is published so calls can be audited.
- The keyword string is not the whole search — LinkedIn filters (title, location, years) capture some signals outside the Boolean. This benchmark measures the string only.
- 90 of the 100 JDs are representative postings scored with the same scheme, not same-day fetched listings. Directional, not definitive.

## Why this exists

This benchmark quantifies the **recruiting context gap**: the meaning lost between a job description and the search built from it. It is the empirical companion to the research note ["Two-Thirds of Every Job Description Never Makes It into the Search"](https://firki.ai/resources/signal-loss) and the motivation behind [Firki](https://firki.ai), a free Chrome extension that extracts structured signals from job descriptions and generates recruiter-reviewable Boolean searches.

## Reproduce / extend

1. Pick a recent public JD; record its URL.
2. List its discrete signals (skills, tools, seniority, domain, qualifiers) — number them.
3. Write the Boolean a competent sourcer would hand-build in ~5 minutes.
4. Count captured signals (generous: synonyms and strong implications count).
5. Report coverage % and add a row to `data/signal-study.csv`.

## Citation

Khurana, P. (2026). *The Recruiting Context Gap: Signal-Loss Benchmark.* Firki. Dataset and methodology: this repository.

## Related

- Microsoft Tech Community: ["Closing the Recruiting Context Gap with Microsoft Foundry"](https://techcommunity.microsoft.com/blog/azurearchitectureblog/closing-the-recruiting-context-gap-with-microsoft-foundry/4556469) (Gaurav Bhardwaj, Sep 2026) — cites Firki as a related product example in this problem space.
