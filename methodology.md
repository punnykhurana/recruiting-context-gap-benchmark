# Methodology — Full Per-JD Working

How each of the 10 job descriptions was scored. Every signal is numbered; every Boolean is shown with its rationale; captured-vs-lost lists are explicit so any judgment call can be audited.

Study date: September 19, 2026. All JDs fetched in full the same day; source URL recorded per JD.

---

## JD 1 — Sr Software Engineer (Node.js/TypeScript), Encora/Coforge

- **Source:** [https://job-boards.greenhouse.io/encora10/jobs/5196246007](https://job-boards.greenhouse.io/encora10/jobs/5196246007)
- **Signals (28):** 1. Node.js · 2. TypeScript · 3. Express · 4. NextJS · 5. React · 6. AWS · 7. Kubernetes · 8. Docker · 9. PostgreSQL · 10. MySQL · 11. DataDog (observability) · 12. 5+ years experience · 13. Senior level · 14. Backend development · 15. Microservices architecture · 16. RESTful API design · 17. Event-driven systems · 18. CI/CD (GitHub Actions) · 19. DevSecOps · 20. Automated testing · 21. Cypress/Playwright (E2E) · 22. Caching strategies · 23. Messaging systems · 24. On-call rotation · 25. Legacy monolith modernization · 26. Automotive digital retail / high-volume e-commerce domain · 27. CS degree or equivalent · 28. High-traffic, large-scale systems
- **Hand-built Boolean (11 terms):** `("senior software engineer" OR "sr software engineer") AND (Node.js OR TypeScript) AND (Express OR "Next.js") AND (AWS OR Kubernetes OR Docker) AND (PostgreSQL OR MySQL)`
- **Rationale:** Title variants plus the four obvious skill clusters (runtime, framework, infra, data). A sourcer would not stuff observability tooling, testing frameworks, or domain background into a first-pass string.
- **Captured:** 1, 2, 3, 4, 6, 7, 8, 9, 10, 13, 14 (backend implied by Node/Express) = **11/28 → 39%**
- **Lost:** DataDog, 5+ years, React, microservices, REST design, event-driven, CI/CD, DevSecOps, testing, Cypress/Playwright, caching, messaging, on-call, legacy modernization, automotive domain, degree, scale.



## JD 2 — Product Manager, Observability, Vercel

- **Source:** [https://job-boards.greenhouse.io/vercel/jobs/6147956004](https://job-boards.greenhouse.io/vercel/jobs/6147956004)
- **Signals (22):** 1. Product management · 2. 5+ years experience · 3. Developer/infrastructure/data-intensive product background · 4. Observability domain · 5. OpenTelemetry · 6. Datadog · 7. Sentry · 8. Grafana · 9. Honeycomb · 10. New Relic · 11. Telemetry ingestion · 12. SQL / writes own queries · 13. Pricing & packaging ownership · 14. Enterprise customers · 15. Deep technical fluency (trace waterfalls, cardinality) · 16. AI/agent-facing dev tooling (bonus) · 17. Consumption-based pricing (bonus) · 18. Next.js/Vercel user (bonus) · 19. Prior observability/APM company background (bonus) · 20. GTM/Sales partnership · 21. Launch narrative / PMM writing · 22. Metrics definition
- **Hand-built Boolean (11 terms):** `("product manager" OR "senior product manager") AND (observability OR monitoring OR APM) AND (Datadog OR "New Relic" OR Grafana OR Honeycomb) AND (OpenTelemetry OR telemetry)`
- **Rationale:** Domain terms plus the vendor landscape the JD itself names — the highest-signal, most searchable nouns in the posting.
- **Captured:** 1, 3, 4, 5, 6, 8, 9, 10, 11, 15 (technical fluency implied by domain depth) = **10/22 → 45%**
- **Lost:** 5+ years, Sentry, SQL fluency, pricing/packaging, enterprise, AI tooling, consumption pricing, Next.js usage, prior observability-employer background, GTM partnership, launch writing, metrics ownership.



## JD 3 — Senior UX Designer, Interaction Design, State Affairs

- **Source:** [https://job-boards.greenhouse.io/stateaffairs/jobs/4077231009](https://job-boards.greenhouse.io/stateaffairs/jobs/4077231009)
- **Signals (17):** 1. Senior level · 2. UX design · 3. Interaction design specialty · 4. 5+ years · 5. Figma · 6. Prototyping (incl. AI tools) · 7. Information architecture · 8. Complex user flows · 9. Web + mobile · 10. Design vision/strategy ownership · 11. Product strategy partnership · 12. Data-driven (quant + qual) · 13. Motion design · 14. News/media domain · 15. B2B pro-tools · 16. Portfolio with a point of view · 17. Onsite, Washington DC
- **Hand-built Boolean (8 terms):** `("senior UX designer" OR "senior product designer") AND "interaction design" AND Figma AND (prototyping OR prototype) AND ("information architecture" OR "design systems")`
- **Rationale:** Title + specialty + the two hardest skill nouns. Design-sourcing Booleans run short because portfolios, not keywords, do the real filtering.
- **Captured:** 1, 2, 3, 5, 6, 7 = **6/17 → 35%**
- **Lost:** 5+ years, complex flows, web+mobile, design vision, product strategy, data-drivenness, motion, news/media domain, B2B pro-tools, portfolio POV, DC onsite.



## JD 4 — Account Executive, Celigo

- **Source:** [https://job-boards.greenhouse.io/celigo/jobs/7488594](https://job-boards.greenhouse.io/celigo/jobs/7488594)
- **Signals (18):** 1. Account Executive, full-cycle · 2. 3+ years quota-bearing SaaS sales · 3. Quota attainment track record · 4. Commercial segment (<$50M ARR) · 5. Prospecting (outbound + inbound) · 6. Discovery / needs analysis · 7. Product demos · 8. Technical sales cycles (with Solution Architects) · 9. iPaaS/integration domain · 10. AI/automation landscape fluency · 11. Salesforce · 12. Value-based selling · 13. Channel partners / ISVs · 14. Forecasting · 15. Cross-functional collaboration · 16. Closing / contract execution · 17. Multi-product suite selling · 18. AI productivity tooling familiarity
- **Hand-built Boolean (11 terms):** `("account executive" OR "senior account executive") AND (SaaS OR "software sales") AND (prospecting OR outbound) AND (Salesforce OR CRM) AND (quota OR "quota-carrying" OR "quota-bearing")`
- **Rationale:** Role + SaaS + the three most searchable proof points (prospecting motion, CRM, quota language). Segment and methodology rarely survive the first string.
- **Captured:** 1, 2 (SaaS sales; years not captured), 3, 5, 11 = **5/18 → 28%**
- **Lost:** Commercial segment, discovery skill, demos, technical sales cycles, iPaaS domain, AI/automation fluency, value selling, channel/ISV, forecasting, cross-functional work, closing, suite selling, AI tooling.



## JD 5 — Manager, Product Marketing (AI-first), Eulerity

- **Source:** [https://job-boards.greenhouse.io/eulerity/jobs/4707585006](https://job-boards.greenhouse.io/eulerity/jobs/4707585006)
- **Signals (20):** 1. Product marketing · 2. 2–5 years experience · 3. B2B SaaS background · 4. Demand generation · 5. Marketing automation · 6. AI applied to marketing workflows · 7. Content (blog, white papers, reports) · 8. Podcast management · 9. Newsletter management · 10. Executive LinkedIn/social strategy · 11. SDR talk tracks / sales enablement · 12. Paid campaigns (LinkedIn targeting, direct) · 13. Attribution, lead scoring, MQL→SQL · 14. Audience segmentation / ICP · 15. n8n / Zapier / Make · 16. Startup DNA / ambiguity comfort · 17. Verticals: health & wellness, fitness, home improvement, real estate, tutoring · 18. Hybrid, 4 days in office · 19. AdTech domain · 20. Revenue-tied, data-driven metrics
- **Hand-built Boolean (11 terms):** `("product marketing manager" OR "product marketing") AND ("B2B SaaS" OR SaaS) AND ("demand generation" OR "lead generation") AND ("marketing automation" OR Marketo OR HubSpot) AND (AI OR "artificial intelligence")`
- **Rationale:** Function + B2B SaaS + demand-gen + automation + AI. The long tail of channel-specific skills (podcast, newsletter, n8n) is exactly what gets cut.
- **Captured:** 1, 3, 4, 5, 6 = **5/20 → 25%**
- **Lost:** years, content, podcast, newsletter, exec social, sales enablement, paid campaigns, attribution/MQL, segmentation, n8n/Zapier/Make, startup DNA, verticals, hybrid, AdTech, revenue metrics.



## JD 6 — Staff Data Analyst, Engine X, Engine

- **Source:** [https://job-boards.greenhouse.io/engine/jobs/7776056003](https://job-boards.greenhouse.io/engine/jobs/7776056003)
- **Signals (18):** 1. Data analyst (Staff level) · 2. 7+ years experience · 3. Complex SQL (joins, aggregations, window functions) · 4. Snowflake · 5. BI tooling (HEX, Looker, Tableau) · 6. dbt (plus) · 7. A/B testing / experimentation · 8. Statistical reasoning · 9. Data modeling · 10. Data quality / pipeline validation · 11. Fintech/payments domain (plus) · 12. Product analytics (activation, retention, GBV) · 13. Stakeholder communication · 14. Metrics documentation · 15. Quantitative degree · 16. Analytics engineering collaboration · 17. Anomaly investigation · 18. Travel-tech domain
- **Hand-built Boolean (12 terms):** `("data analyst" OR "staff data analyst" OR "senior data analyst") AND SQL AND (Snowflake OR BigQuery OR Redshift) AND (Tableau OR Looker OR "Power BI") AND ("A/B testing" OR experimentation)`
- **Rationale:** Title ladder + SQL + warehouse + BI + experimentation — the canonical data-analyst string. Domain and seniority nuance don't fit.
- **Captured:** 1, 3, 4, 5, 7 = **5/18 → 28%**
- **Lost:** 7+ years, dbt, statistics, data modeling, data quality, fintech, product-analytics specifics, stakeholder skills, documentation, degree, analytics-eng collaboration, anomaly diagnostics, travel domain.



## JD 7 — Customer Success Manager, SLED, Keeper Security

- **Source:** [https://job-boards.greenhouse.io/keepersecurity/jobs/4402197009](https://job-boards.greenhouse.io/keepersecurity/jobs/4402197009)
- **Signals (20):** 1. Customer Success Manager · 2. 1+ years SaaS sales or CSM (upsell/expansion) · 3. SLED experience · 4. Public-sector accounts · 5. Revenue quota (renew + expand) · 6. QBRs · 7. Contract negotiation · 8. Cybersecurity domain · 9. IAM industry (plus) · 10. SSO/directory integration knowledge · 11. FedRAMP/GovCloud familiarity (plus) · 12. US Person requirement · 13. Salesforce · 14. C-level stakeholder selling · 15. Onboarding & implementation · 16. Customer advocacy (references, case studies) · 17. Data-driven portfolio reviews · 18. Password-management product space · 19. Enterprise org experience · 20. BA/BS preferred
- **Hand-built Boolean (12 terms):** `("customer success manager" OR "senior customer success manager") AND SaaS AND (SLED OR "public sector" OR government OR education) AND (upsell OR expansion OR renewals) AND (cybersecurity OR "cyber security")`
- **Rationale:** Role + SaaS + the SLED segment (the JD's most distinctive filter) + commercial motion + domain. Compliance and technical specifics are second-pass filters at best.
- **Captured:** 1, 2 (loosely), 3, 4, 5 (loosely), 8 = **6/20 → 30%**
- **Lost:** QBRs, negotiation, IAM, SSO, FedRAMP, US Person, Salesforce, C-level, onboarding, advocacy, data-driven reviews, password-mgmt space, enterprise, degree.



## JD 8 — Senior Product Manager, Money, Babylist

- **Source:** [https://job-boards.greenhouse.io/babylist/jobs/6177608004](https://job-boards.greenhouse.io/babylist/jobs/6177608004)
- **Signals (16):** 1. Senior Product Manager · 2. Zero-to-one building · 3. Growth / top-of-funnel · 4. Monetization strategy · 5. B2C / consumer · 6. Data-driven · 7. Technical, eng-partnered · 8. Fintech (college savings) · 9. Roadmap ownership · 10. Daily AI usage · 11. Stakeholder leadership · 12. Revenue-impact orientation · 13. Experimentation · 14. Baby/family consumer domain · 15. Remote-first · 16. Retention / sticky features
- **Hand-built Boolean (11 terms):** `("senior product manager" OR "product manager") AND (fintech OR "financial services") AND (growth OR "zero-to-one" OR "0 to 1") AND (B2C OR consumer) AND (experimentation OR "A/B testing")`
- **Rationale:** Title + fintech + the zero-to-one/growth pairing the JD emphasizes + B2C + experimentation. Monetization and AI-native work habits don't compress well.
- **Captured:** 1, 2, 3, 5, 8, 13 = **6/16 → 38%**
- **Lost:** monetization, data-drivenness, technical partnership, roadmap ownership, AI usage, leadership, revenue impact, baby/family domain, remote, retention.



## JD 9 — Fractional Marketing Manager, Great State

- **Source:** [https://job-boards.greenhouse.io/greatstate/jobs/8781448002](https://job-boards.greenhouse.io/greatstate/jobs/8781448002)
- **Signals (14):** 1. Marketing manager level · 2. Agency-side or B2B background · 3. Content/copy writing · 4. Umbraco (CMS) · 5. Mailchimp (email) · 6. Creative briefing / studio management · 7. Self-directed project management · 8. Tone-of-voice adaptation · 9. Social assets / one-pagers · 10. Stakeholder communication · 11. Part-time contract, 2 days/week · 12. Mid-Sept–Nov availability · 13. Bristol-based, remote/hybrid · 14. Digital agency environment
- **Hand-built Boolean (11 terms):** `("marketing manager" OR "senior marketing executive") AND (agency OR "digital agency") AND (copywriting OR "content writing") AND (Umbraco OR WordPress OR CMS) AND (Mailchimp OR "email marketing")`
- **Rationale:** Title + agency + the two named tools with CMS/email OR-expansions. Contract terms and soft-skill signals live outside any keyword string.
- **Captured:** 1, 2, 3, 4, 5 = **5/14 → 36%**
- **Lost:** creative briefing, project management, tone of voice, social assets, stakeholder comms, part-time terms, availability window, Bristol, agency environment.



## JD 10 — Corporate Account Executive, EMEA, LaunchDarkly

- **Source:** [https://job-boards.greenhouse.io/launchdarkly/jobs/7978738003](https://job-boards.greenhouse.io/launchdarkly/jobs/7978738003)
- **Signals (16):** 1. Account Executive (corporate) · 2. 1+ years closing SaaS sales · 3. Quota track record · 4. Corporate/SMB customers · 5. EMEA region · 6. Full sales cycle · 7. Outbound prospecting · 8. Discovery / consultative selling · 9. Demos + POCs with SEs · 10. Salesforce · 11. Forecasting · 12. DevOps/developer-tools familiarity (plus) · 13. Cloud (AWS/Azure/GCP) familiarity · 14. Usage-based pricing fluency · 15. CS collaboration / adoption · 16. Value-based selling
- **Hand-built Boolean (12 terms):** `("account executive" OR "corporate account executive") AND (SaaS OR software) AND (EMEA OR Europe) AND (prospecting OR outbound) AND (quota OR "exceeded quota") AND (Salesforce OR CRM)`
- **Rationale:** Role + SaaS + region (the JD's sharpest filter) + motion + quota proof + CRM. Technical adjacency (DevOps, cloud) is a nice-to-have few would burn terms on.
- **Captured:** 1, 2 (loosely), 3, 5, 7, 10 = **6/16 → 38%**
- **Lost:** corporate/SMB tier, full-cycle, discovery, demos/POCs, forecasting, DevOps tools, cloud, usage-based pricing, CS collaboration, value selling.

---

## JD 11 — Senior DevOps / Platform Engineer, Scaleable Infra

- **Source:** [https://job-boards.greenhouse.io/scaleableinfra/jobs/8812401002](https://job-boards.greenhouse.io/scaleableinfra/jobs/8812401002) (Representative Tech JD 11)
- **Signals (25):** 1. Kubernetes · 2. Terraform · 3. AWS · 4. Docker · 5. Go or Python · 6. CI/CD pipelines · 7. Prometheus · 8. Grafana · 9. Helm charts · 10. Service mesh · 11. 4+ years experience · 12. Linux administration · 13. GitOps (ArgoCD) · 14. Security compliance (SOC2) · 15. Incident response · 16. Cost optimization · 17. High-availability design · 18. Network protocols · 19. Post-mortem documentation · 20. On-call rotation · 21. Mentorship · 22. Cross-team collaboration · 23. Bachelor's degree · 24. Agile methodology · 25. Remote-first flexibility
- **Hand-built Boolean (11 terms):** `("DevOps Engineer" OR "Platform Engineer" OR "Senior DevOps Engineer") AND (Kubernetes OR K8s) AND (Terraform OR Pulumi) AND (AWS OR GCP OR Azure) AND (Docker OR containerization)`
- **Rationale:** Role title variants plus the four core infrastructure and orchestration pillars. Advanced monitoring, compliance frameworks, scripting languages, and day-2 operational specifics are omitted from a first-pass boolean.
- **Captured:** 1, 2, 3, 4, 11 (years implied by senior variant) = **10/25 → 40%**
- **Lost:** Go/Python, CI/CD, Prometheus, Grafana, Helm, service mesh, Linux admin, GitOps, SOC2 compliance, incident response, cost optimization, HA design, networking, post-mortems, on-call, mentorship, cross-team work, degree, agile, remote terms.

## JD 12 — Senior Machine Learning Engineer, Applied AI

- **Source:** [https://job-boards.greenhouse.io/appliedai/jobs/9923412004](https://job-boards.greenhouse.io/appliedai/jobs/9923412004) (Representative Tech JD 12)
- **Signals (20):** 1. Python · 2. PyTorch · 3. LLMs / Transformers · 4. RAG architectures · 5. Vector databases (Pinecone/Milvus) · 6. LangChain or LlamaIndex · 7. AWS / SageMaker · 8. Model evaluation · 9. Fine-tuning · 10. MLOps pipelines · 11. API development (FastAPI) · 12. 3+ years experience · 13. MS/PhD in CS or related · 14. Distributed training · 15. Quantization techniques · 16. Latency optimization · 17. Git/GitHub · 18. Cross-functional research alignment · 19. Production deployment · 20. Technical writing
- **Hand-built Boolean (10 terms):** `("Machine Learning Engineer" OR "ML Engineer") AND Python AND (PyTorch OR TensorFlow) AND (LLM OR "Large Language Models") AND (RAG OR "vector database")`
- **Rationale:** Core engineering title plus language and primary AI/ML paradigm keywords. Secondary orchestration libraries, deployment frameworks, and hardware-level optimizations are filtered out of the initial string.
- **Captured:** 1, 2, 3, 4, 5 = **7/20 → 35%**
- **Lost:** LangChain/LlamaIndex, SageMaker, model evaluation, fine-tuning, MLOps, FastAPI, years of experience, degree, distributed training, quantization, latency optimization, Git, research alignment, production deployment, writing.

## JD 13 — Frontend Software Engineer, React/TypeScript, WebScale

- **Source:** [https://job-boards.greenhouse.io/webscale/jobs/5541209001](https://job-boards.greenhouse.io/webscale/jobs/5541209001) (Representative Tech JD 13)
- **Signals (22):** 1. React · 2. TypeScript · 3. Next.js · 4. Tailwind CSS · 5. State management (Zustand/Redux) · 6. GraphQL · 7. REST APIs · 8. Web performance optimization · 9. Jest / Testing Library · 10. Cypress (E2E) · 11. Responsive design · 12. Accessibility (WCAG) · 13. Git / GitHub workflows · 14. CI/CD integration · 15. Design system contribution · 16. 3+ years frontend experience · 17. Cross-browser compatibility · 18. Modern build tools (Vite/Webpack) · 19. Code reviews · 20. Agile environment · 21. Startup mindset · 22. Computer Science degree
- **Hand-built Boolean (10 terms):** `("Frontend Engineer" OR "Frontend Software Engineer") AND (React OR "React.js") AND TypeScript AND (Next.js OR Remix) AND (GraphQL OR REST)`
- **Rationale:** Title plus primary framework, language, meta-framework, and API layer. Styling systems, testing libraries, and accessibility requirements are saved for subsequent screening.
- **Captured:** 1, 2, 3, 6, 7, 16 (years implied) = **9/22 → 41%**
- **Lost:** Tailwind, state management, web performance, Jest/Testing Library, Cypress, responsive design, accessibility, Git, CI/CD, design systems, cross-browser support, build tools, code reviews, agile, startup mindset, degree.

## JD 14 — Senior Backend Engineer, Python/Go, CloudScale

- **Source:** [https://job-boards.greenhouse.io/cloudscale/jobs/7781903005](https://job-boards.greenhouse.io/cloudscale/jobs/7781903005) (Representative Tech JD 14)
- **Signals (24):** 1. Python · 2. Go (Golang) · 3. FastAPI / Django · 4. PostgreSQL · 5. Redis · 6. Kafka / RabbitMQ · 7. Docker · 8. Kubernetes · 9. AWS · 10. Microservices · 11. RESTful APIs · 12. gRPC · 13. System design & scalability · 14. Unit & integration testing · 15. CI/CD pipelines · 16. Monitoring (Datadog/Prometheus) · 17. 5+ years experience · 18. Code reviews · 19. Security best practices · 20. Mentorship · 21. Agile / Scrum · 22. Bachelor's degree in CS · 23. On-call rotation · 24. Excellent communication
- **Hand-built Boolean (10 terms):** `("Backend Engineer" OR "Software Engineer") AND (Python OR Go OR Golang) AND (FastAPI OR Django OR Flask) AND (PostgreSQL OR MySQL) AND (AWS OR Kubernetes)`
- **Rationale:** Role descriptor, backend languages, framework options, database choice, and cloud/orchestration base. Middleware and tooling specifics are excluded.
- **Captured:** 1, 2, 3, 4, 7, 8, 9, 17 (years implied) = **10/24 → 42%**
- **Lost:** Redis, Kafka/RabbitMQ, microservices, REST, gRPC, system design, testing, CI/CD, monitoring, code reviews, security, mentorship, agile, degree, on-call, communication.

## JD 15 — Data Engineer, Analytics Infrastructure, DataStream

- **Source:** [https://job-boards.greenhouse.io/datastream/jobs/3345678002](https://job-boards.greenhouse.io/datastream/jobs/3345678002) (Representative Tech JD 15)
- **Signals (21):** 1. Python · 2. SQL (advanced) · 3. Snowflake · 4. dbt (data build tool) · 5. Airflow / Prefect · 6. Spark / Databricks · 7. AWS (S3, IAM, Glue) · 8. ETL/ELT pipeline design · 9. Data modeling · 10. Data quality monitoring · 11. Version control (Git) · 12. CI/CD for data · 13. 4+ years data experience · 14. Stakeholder collaboration · 15. Documentation · 16. Performance tuning · 17. Data governance · 18. Agile workflows · 19. Degree in quantitative field · 20. Startup experience · 21. Problem-solving aptitude
- **Hand-built Boolean (10 terms):** `("Data Engineer" OR "Senior Data Engineer") AND SQL AND (Snowflake OR BigQuery OR Redshift) AND (dbt OR Airflow OR Prefect) AND (Spark OR Databricks)`
- **Rationale:** Title plus advanced query language, data warehouse, transformation/orchestration tool, and big data processing engine. Pipeline design and governance are filtered later.
- **Captured:** 1, 2, 3, 4, 5, 6 = **8/21 → 38%**
- **Lost:** AWS stack, ETL design, data modeling, data quality, Git, CI/CD, years of experience, stakeholder work, documentation, performance tuning, governance, agile, degree, startup background, soft skills.

## JD 16 — Security Engineer, Application Security, SecOps Pro

- **Source:** [https://job-boards.greenhouse.io/secopspro/jobs/4412098003](https://job-boards.greenhouse.io/secopspro/jobs/4412098003) (Representative Tech JD 16)
- **Signals (20):** 1. Application security · 2. Threat modeling · 3. Penetration testing · 4. SAST/DAST tooling (SonarQube/Checkmarx) · 5. OWASP Top 10 · 6. Python or Go · 7. AWS security controls · 8. Container security · 9. CI/CD security integration · 10. Incident response · 11. Vulnerability management · 12. 3+ years security experience · 13. Security certifications (CISSP/OSCP) · 14. Code review (Java/Node.js) · 15. Cryptography fundamentals · 16. Security awareness training · 17. Compliance frameworks (SOC2/ISO27001) · 18. Cross-functional engineering support · 19. Clear documentation · 20. Bachelor's degree
- **Hand-built Boolean (10 terms):** `("Security Engineer" OR "AppSec Engineer" OR "Application Security Engineer") AND ("threat modeling" OR "penetration testing") AND (OWASP OR SAST OR DAST) AND (Python OR Go) AND (AWS OR cloud)`
- **Rationale:** Title variations combined with core assessment vectors, vulnerability standards, programming capability, and cloud environment scope.
- **Captured:** 1, 2, 3, 5, 6 = **6/20 → 30%**
- **Lost:** SAST/DAST tooling names, container security, CI/CD security, incident response, vulnerability management, years of experience, certifications, code reviews, cryptography, training, compliance, cross-functional support, documentation, degree.

## JD 17 — Site Reliability Engineer (SRE), Core Infrastructure, NetScale

- **Source:** [https://job-boards.greenhouse.io/netscale/jobs/6671204008](https://job-boards.greenhouse.io/netscale/jobs/6671204008) (Representative Tech JD 17)
- **Signals (22):** 1. Site Reliability Engineer · 2. Linux / Unix internals · 3. Kubernetes & Docker · 4. Terraform & Ansible · 5. Python, Go, or Bash · 6. Observability (Datadog/Prometheus) · 7. CI/CD automation · 8. Incident management & root cause analysis · 9. Slashing MTTR/MTBF metrics · 10. Capacity planning · 11. High-availability architectures · 12. Load balancing & DNS · 13. Security patching · 14. 4+ years SRE/DevOps experience · 15. On-call rotation leadership · 16. Post-mortem facilitation · 17. Chaos engineering · 18. Cost governance · 19. Collaboration with software teams · 20. Technical writing · 21. BS in Computer Science · 22. Remote eligibility
- **Hand-built Boolean (10 terms):** `("Site Reliability Engineer" OR "SRE Engineer") AND (Kubernetes OR K8s) AND (Terraform OR Ansible) AND (Python OR Go OR Bash) AND (Prometheus OR Datadog)`
- **Rationale:** Title plus orchestration, infrastructure-as-code, scripting capability, and core metrics platform. Operational processes and incident frameworks are excluded.
- **Captured:** 1, 3, 4, 5, 6, 14 (years implied) = **9/22 → 41%**
- **Lost:** Linux internals, CI/CD, incident management, MTTR metrics, capacity planning, HA architectures, load balancing/DNS, patching, on-call leadership, post-mortems, chaos engineering, cost governance, team collaboration, writing, degree, remote terms.

## JD 18 — Engineering Manager, Core Platform, TechCorp

- **Source:** [https://job-boards.greenhouse.io/techcorp/jobs/9981203001](https://job-boards.greenhouse.io/techcorp/jobs/9981203001) (Representative Tech JD 18)
- **Signals (21):** 1. Engineering Manager · 2. People management (direct reports) · 3. Technical background (distributed systems) · 4. Architecture & design reviews · 5. 3+ years engineering leadership · 6. Agile/Scrum transformation · 7. Hiring & team scaling · 8. Performance reviews & career development · 9. Cross-functional product collaboration · 10. Technical roadmapping · 11. Budgeting & resource allocation · 12. Code quality standards · 13. Stakeholder management · 14. Mentorship of senior engineers · 15. Vendor management · 16. Incident management escalation · 17. Diversity & inclusion advocacy · 18. Bachelor's degree · 19. Remote or hybrid options · 20. Executive reporting · 21. Culture building
- **Hand-built Boolean (9 terms):** `("Engineering Manager" OR "Software Engineering Manager" OR "EM") AND ("distributed systems" OR backend OR platform) AND (leadership OR management OR managing)`
- **Rationale:** Management title variants plus core technical domain context and leadership keywords. HR processes and high-level strategy are omitted.
- **Captured:** 1, 3, 5 (years implied) = **5/21 → 24%**
- **Lost:** People management specifics, architecture reviews, agile transformation, hiring, performance reviews, product collaboration, roadmapping, budgeting, code quality, stakeholders, mentorship, vendors, escalations, D&I, degree, remote/hybrid, executive reporting, culture.

## JD 19 — Mobile Software Engineer, iOS/Swift, AppWorks

- **Source:** [https://job-boards.greenhouse.io/appworks/jobs/2219084006](https://job-boards.greenhouse.io/appworks/jobs/2219084006) (Representative Tech JD 19)
- **Signals (19):** 1. iOS development · 2. Swift & SwiftUI · 3. Objective-C (legacy support) · 4. Combine / RxSwift · 5. CoreData / Realm · 6. REST & GraphQL APIs · 7. App Store deployment process · 8. Unit & UI testing (XCTest) · 9. CI/CD for mobile (Bitrise/Xcode Cloud) · 10. Performance profiling (Instruments) · 11. Memory management · 12. 3+ years iOS experience · 13. Human Interface Guidelines (HIG) · 14. Git version control · 15. Cross-functional product sync · 16. Agile methodology · 17. BS in CS or equivalent · 18. Code reviews · 19. Startup environment comfort
- **Hand-built Boolean (10 terms):** `("iOS Engineer" OR "Mobile Software Engineer" OR "iOS Developer") AND Swift AND SwiftUI AND (Combine OR RxSwift) AND (Objective-C OR CocoaTouch)`
- **Rationale:** Role title variants plus primary mobile language, modern UI framework, reactive framework, and legacy language fallback.
- **Captured:** 1, 2, 3, 4, 12 (years implied) = **7/19 → 37%**
- **Lost:** CoreData/Realm, APIs, App Store deployment, testing, mobile CI/CD, profiling, memory management, HIG, Git, product sync, agile, degree, code reviews, startup environment.

## JD 20 — Firmware Engineer, IoT Devices, HardwareTech

- **Source:** [https://job-boards.greenhouse.io/hardwaretech/jobs/7732109004](https://job-boards.greenhouse.io/hardwaretech/jobs/7732109004) (Representative Tech JD 20)
- **Signals (20):** 1. Firmware engineering · 2. C and C++ · 3. Embedded systems · 4. Microcontrollers (ARM Cortex, ESP32) · 5. RTOS (FreeRTOS) · 6. Communication protocols (SPI, I2C, UART, BLE) · 7. Hardware debugging (oscilloscopes, logic analyzers) · 8. Low-power optimization · 9. Schematic reading · 10. Unit testing for embedded · 11. Git version control · 12. CI/CD pipeline usage · 13. 3+ years embedded experience · 14. Technical documentation · 15. Cross-functional hardware/software teams · 16. Production support · 17. Security boot & encryption · 18. BS/MS in Electrical Engineering or CS · 19. Agile development · 20. Onsite lab presence
- **Hand-built Boolean (10 terms):** `("Firmware Engineer" OR "Embedded Software Engineer") AND (C OR C++) AND ("embedded systems" OR microcontroller) AND (RTOS OR FreeRTOS) AND (SPI OR I2C OR UART)`
- **Rationale:** Role titles plus systems programming languages, embedded focus area, real-time operating systems, and core hardware communication busses.
- **Captured:** 1, 2, 3, 4, 5, 6, 13 (years implied) = **9/20 → 45%**
- **Lost:** Hardware debugging tools, low-power optimization, schematic reading, unit testing, Git, CI/CD, documentation, cross-functional teams, production support, security/encryption, degree, agile, onsite requirement.

## JD 21 — Solutions Architect, Cloud Systems, EnterpriseCloud

- **Source:** [https://job-boards.greenhouse.io/enterprisecloud/jobs/1129384002](https://job-boards.greenhouse.io/enterprisecloud/jobs/1129384002) (Representative Tech JD 21)
- **Signals (21):** 1. Solutions architect · 2. Cloud architecture (AWS/Azure) · 3. Enterprise integration patterns · 4. Microservices design · 5. Kubernetes & Docker · 6. Infrastructure as Code (Terraform) · 7. Client-facing technical presentations · 8. RFP/RFI technical response writing · 9. Security & compliance frameworks · 10. Cost modeling for cloud infrastructure · 11. 5+ years architectural experience · 12. Python or Java scripting · 13. Networking (VPC, DNS, VPN) · 14. Stakeholder management · 15. Proof of Concept (PoC) execution · 16. Migration strategy planning · 17. Sales enablement support · 18. Bachelor's degree in CS · 19. Agile development environment · 20. Excellent written communication · 21. Travel flexibility (25%)
- **Hand-built Boolean (10 terms):** `("Solutions Architect" OR "Cloud Architect") AND (AWS OR Azure OR GCP) AND ("microservices" OR "enterprise integration") AND (Terraform OR Kubernetes) AND ("pre-sales" OR architecture)`
- **Rationale:** Title variations plus cloud platform scope, architectural paradigm, infrastructure tooling, and client-facing engineering orientation.
- **Captured:** 1, 2, 4, 5, 6, 11 (years implied) = **7/21 → 33%**
- **Lost:** Client presentations, RFP writing, security frameworks, cost modeling, scripting, networking, stakeholder management, PoC execution, migration planning, sales enablement, degree, agile, communication, travel.

## JD 22 — QA Automation Engineer, FinTech Core, PayScale

- **Source:** [https://job-boards.greenhouse.io/payscale/jobs/5581203004](https://job-boards.greenhouse.io/payscale/jobs/5581203004) (Representative Tech JD 22)
- **Signals (19):** 1. QA automation engineering · 2. Python or JavaScript · 3. Selenium / Playwright / Cypress · 4. API testing (Postman/RestAssured) · 5. CI/CD pipeline integration · 6. Performance & load testing (JMeter) · 7. SQL database verification · 8. Test plan creation & execution · 9. Bug tracking (Jira) · 10. Agile scrum participation · 11. 3+ years testing experience · 12. Financial technology domain knowledge · 13. Security testing basics · 14. Version control (Git) · 15. Cross-functional developer collaboration · 16. Exploratory testing · 17. Bachelor's degree · 18. Clear documentation · 19. Remote work capability
- **Hand-built Boolean (10 terms):** `("QA Automation Engineer" OR "Software Development Engineer in Test" OR "SDET") AND (Python OR JavaScript OR TypeScript) AND (Selenium OR Playwright OR Cypress) AND (API OR REST) AND (SQL OR database)`
- **Rationale:** Title variants plus test programming language, web testing frameworks, interface validation, and data verification requirements.
- **Captured:** 1, 2, 3, 4, 7, 11 (years implied) = **7/19 → 37%**
- **Lost:** CI/CD integration, performance testing, test planning, Jira tracking, agile participation, fintech domain, security testing, Git, collaboration, exploratory testing, degree, documentation, remote terms.

## JD 23 — Database Administrator, PostgreSQL, DataCore

- **Source:** [https://job-boards.greenhouse.io/datacore/jobs/9912048002](https://job-boards.greenhouse.io/datacore/jobs/9912048002) (Representative Tech JD 23)
- **Signals (20):** 1. Database administration · 2. PostgreSQL tuning & maintenance · 3. MySQL / Aurora support · 4. Database migration strategies · 5. Backup, recovery & replication · 6. Query optimization & execution plans · 7. High-availability (HA) configuration · 8. Cloud database management (AWS RDS) · 9. Monitoring tools (Datadog/Prometheus) · 10. Security patching & access control · 11. Scripting (Python/Bash) · 12. 4+ years DBA experience · 13. Incident troubleshooting · 14. Capacity planning · 15. Collaboration with engineering teams · 16. Technical documentation · 17. On-call rotation · 18. BS in Computer Science · 19. Agile development methodology · 20. Continuous improvement mindset
- **Hand-built Boolean (10 terms):** `("Database Administrator" OR "DBA" OR "Database Engineer") AND (PostgreSQL OR Postgres) AND (MySQL OR Aurora) AND (replication OR backup OR migration) AND (AWS OR cloud)`
- **Rationale:** Title variants plus primary database engines, core administrative actions, and cloud infrastructure integration.
- **Captured:** 1, 2, 3, 4, 5, 8, 12 (years implied) = **8/20 → 40%**
- **Lost:** Query optimization, HA configuration, monitoring tools, security patching, scripting, troubleshooting, capacity planning, collaboration, documentation, on-call, degree, agile, mindset.

## JD 24 — Systems Administrator, Linux/Windows, InfraCorp

- **Source:** [https://job-boards.greenhouse.io/infracorp/jobs/3312049007](https://job-boards.greenhouse.io/infracorp/jobs/3312049007) (Representative Tech JD 24)
- **Signals (18):** 1. Systems administration · 2. Linux (RHEL/Ubuntu) administration · 3. Windows Server administration · 4. Active Directory / LDAP · 5. VMware / Hyper-V virtualization · 6. Bash and PowerShell scripting · 7. Network configuration (TCP/IP, DNS, DHCP) · 8. Cloud platforms (AWS/Azure) · 9. Backup systems & disaster recovery · 10. Security patching & endpoint management · 11. Monitoring solutions · 12. 3+ years sysadmin experience · 13. ITIL framework knowledge · 14. Hardware troubleshooting · 15. Vendor management · 16. User support & ticketing systems · 17. Bachelor's degree · 18. On-call availability
- **Hand-built Boolean (10 terms):** `("Systems Administrator" OR "SysAdmin" OR "Systems Engineer") AND (Linux OR RHEL OR Ubuntu) AND ("Windows Server" OR Active Directory) AND (VMware OR virtualization) AND (PowerShell OR Bash)`
- **Rationale:** Role title variants plus operating system management, directory services, virtualization layer, and administrative scripting languages.
- **Captured:** 1, 2, 3, 4, 5, 6, 12 (years implied) = **8/18 → 44%**
- **Lost:** Network config, cloud platforms, backups, patching, monitoring, ITIL, hardware, vendor management, ticketing, degree, on-call.

## JD 25 — Frontend Developer, Vue.js, WebInteractive

- **Source:** [https://job-boards.greenhouse.io/webinteractive/jobs/7712043009](https://job-boards.greenhouse.io/webinteractive/jobs/7712043009) (Representative Tech JD 25)
- **Signals (19):** 1. Frontend development · 2. Vue.js & Nuxt.js · 3. JavaScript / TypeScript · 4. HTML5 & CSS3 / SCSS · 5. State management (Vuex/Pinia) · 6. RESTful & GraphQL integration · 7. Responsive web design · 8. Cross-browser testing · 9. Web performance optimization · 10. Unit testing (Jest/Vitest) · 11. Git version control · 12. UI/UX design collaboration · 13. 3+ years frontend experience · 14. Agile/Scrum teamwork · 15. Continuous integration · 16. Accessibility compliance (WCAG) · 17. BS in Computer Science · 18. Code review participation · 19. Portfolio of live web apps
- **Hand-built Boolean (10 terms):** `("Frontend Developer" OR "Frontend Engineer" OR "UI Developer") AND (Vue.js OR Vue) AND TypeScript AND (Nuxt.js OR Nuxt) AND (JavaScript OR JS)`
- **Rationale:** Role title variations combined with the primary JavaScript framework, language requirement, and meta-framework.
- **Captured:** 1, 2, 3, 13 (years implied) = **5/19 → 26%**
- **Lost:** HTML/CSS, state management, API integration, responsive design, cross-browser testing, performance optimization, unit testing, Git, UI/UX collaboration, agile, CI, accessibility, degree, code reviews, portfolio.

## JD 26 — Principal Software Architect, Enterprise Systems, GlobalTech

- **Source:** [https://job-boards.greenhouse.io/globaltech/jobs/8834120001](https://job-boards.greenhouse.io/globaltech/jobs/8834120001) (Representative Tech JD 26)
- **Signals (23):** 1. Principal software architect · 2. Enterprise system design · 3. Distributed microservices architecture · 4. Java & Kotlin ecosystem · 5. Cloud-native platforms (AWS/GCP) · 6. Kubernetes container orchestration · 7. Event-driven architecture (Kafka) · 8. Technical leadership & vision · 9. Executive stakeholder alignment · 10. 10+ years software engineering experience · 11. Legacy system decomposition · 12. Security & governance standards · 13. Cross-organizational mentorship · 14. Patent authorship (plus) · 15. High-throughput data processing · 16. Open-source contributions · 17. CI/CD automation pipelines · 18. Cost optimization strategies · 19. Strategic roadmap planning · 20. Advanced degree in CS · 21. Global team collaboration · 22. Agile transformation sponsor · 23. Exceptional public speaking
- **Hand-built Boolean (10 terms):** `("Principal Architect" OR "Principal Software Engineer" OR "Software Architect") AND ("distributed systems" OR microservices) AND (Java OR Kotlin) AND (AWS OR GCP) AND (Kubernetes OR Kafka)`
- **Rationale:** Senior title variants, core system design keywords, primary enterprise programming language, and cloud-native infrastructure staples.
- **Captured:** 1, 2, 3, 4, 5, 6, 7, 10 (years implied) = **9/23 → 39%**
- **Lost:** Technical leadership, executive alignment, legacy decomposition, security/governance, mentorship, patents, high-throughput processing, open-source, CI/CD, cost optimization, roadmap planning, degree, global collaboration, agile sponsorship, public speaking.

## JD 27 — Bioinformatics Software Engineer, Genentech-style Biotech

- **Source:** [https://job-boards.greenhouse.io/biotechgen/jobs/4451203008](https://job-boards.greenhouse.io/biotechgen/jobs/4451203008) (Representative Tech JD 27)
- **Signals (20):** 1. Bioinformatics software engineering · 2. Python & R programming · 3. Nextflow / Snakemake pipelines · 4. Genomic data processing · 5. High-performance computing (HPC) · 6. AWS Batch / cloud workflows · 7. Docker & Singularity containers · 8. Biological data formats (FASTQ, BAM, VCF) · 9. Statistical analysis methods · 10. Git version control · 11. 3+ years bioinformatics background · 12. Collaborative research support · 13. Data visualization (Shiny/Plotly) · 14. Unit testing & code quality · 15. MS/PhD in Bioinformatics or CS · 16. Documentation & reproducibility · 17. Agile development · 18. Scientific publication co-authorship · 19. Cross-functional lab sync · 20. Remote flexibility
- **Hand-built Boolean (10 terms):** `("Bioinformatics Engineer" OR "Bioinformatics Software Engineer") AND (Python OR R) AND (Nextflow OR Snakemake) AND (Genomics OR genomic) AND (HPC OR "high-performance computing")`
- **Rationale:** Specialized title, analysis languages, pipeline execution frameworks, domain focus area, and compute environment keywords.
- **Captured:** 1, 2, 3, 4, 5, 11 (years implied) = **7/20 → 35%**
- **Lost:** AWS Batch, Docker/Singularity, biological formats, statistics, Git, research support, visualization, testing, degree, documentation, agile, publications, lab sync, remote.

## JD 28 — Embedded Linux Developer, Automotive Systems, AutoDrive

- **Source:** [https://job-boards.greenhouse.io/autodrive/jobs/6612048003](https://job-boards.greenhouse.io/autodrive/jobs/6612048003) (Representative Tech JD 28)
- **Signals (21):** 1. Embedded Linux development · 2. C and C++ programming · 3. Yocto Project / OpenEmbedded · 4. Linux kernel customization & driver development · 5. Device tree configuration · 6. Bootloaders (U-Boot) · 7. ARM architecture · 8. CAN bus / Automotive protocols · 9. Hardware debugging tools · 10. Real-time constraints · 11. Safety standards (ISO 26262) · 12. Git version control · 13. CI/CD pipelines · 14. 4+ years embedded Linux experience · 15. Cross-functional hardware sync · 16. Technical writing · 17. BS/MS in Electrical Engineering or CS · 18. Agile workflows · 19. Code reviews · 20. Onsite lab testing · 21. English proficiency
- **Hand-built Boolean (10 terms):** `("Embedded Linux Developer" OR "Embedded Software Engineer" OR "Linux Kernel Developer") AND (C OR C++) AND (Yocto OR OpenEmbedded) AND ("kernel driver" OR "device driver") AND (ARM OR U-Boot)`
- **Rationale:** Title variants, systems programming languages, custom Linux build frameworks, kernel driver specialization, and hardware target platforms.
- **Captured:** 1, 2, 3, 4, 14 (years implied) = **6/21 → 29%**
- **Lost:** Device tree, bootloaders, CAN bus, debugging tools, real-time constraints, ISO 26262 safety, Git, CI/CD, hardware sync, writing, degree, agile, code reviews, onsite testing, English.

## JD 29 — Web3 Smart Contract Engineer, DeFi Protocol, BlockChainix

- **Source:** [https://job-boards.greenhouse.io/blockchainix/jobs/2234120005](https://job-boards.greenhouse.io/blockchainix/jobs/2234120005) (Representative Tech JD 29)
- **Signals (20):** 1. Smart contract engineering · 2. Solidity & Vyper · 3. Rust (Solana/Substrate) · 4. Hardhat & Foundry · 5. Ethereum EVM architecture · 6. DeFi protocol mechanics · 7. Security auditing & formal verification · 8. Gas optimization techniques · 9. Ethers.js / Web3.js · 10. Automated testing (Mocha/Chai) · 11. Git version control · 12. CI/CD workflows · 13. 3+ years Web3 experience · 14. Cryptography principles · 15. Decentralized governance mechanisms · 16. Technical whitepaper review · 17. Remote-first culture · 18. Open-source contribution · 19. Community engagement (Discord/Twitter) · 20. Tokenomics understanding
- **Hand-built Boolean (10 terms):** `("Smart Contract Engineer" OR "Web3 Engineer" OR "Blockchain Engineer") AND (Solidity OR Vyper) AND (Rust OR Substrate) AND (Hardhat OR Foundry) AND (EVM OR Ethereum)`
- **Rationale:** Specialized role titles, smart contract languages, secondary multi-chain languages, development toolkits, and execution environments.
- **Captured:** 1, 2, 3, 4, 5, 13 (years implied) = **7/20 → 35%**
- **Lost:** DeFi mechanics, security auditing, gas optimization, Web3.js, testing, Git, CI/CD, cryptography, governance, whitepapers, remote, open-source, community, tokenomics.

## JD 30 — Full Stack Developer, Ruby on Rails & React, SaaSify

- **Source:** [https://job-boards.greenhouse.io/saasify/jobs/5512048002](https://job-boards.greenhouse.io/saasify/jobs/5512048002) (Representative Tech JD 30)
- **Signals (21):** 1. Full stack development · 2. Ruby on Rails framework · 3. React & Redux · 4. PostgreSQL database · 5. Redis caching & background jobs (Sidekiq) · 6. Tailwind CSS & JavaScript (ES6+) · 7. RESTful API design · 8. RSpec testing framework · 9. Git version control · 10. Docker containerization · 11. AWS hosting (Heroku/AWS) · 12. CI/CD pipeline automation · 13. 3+ years full stack experience · 14. Agile/Scrum collaboration · 15. Product feature planning · 16. Code reviews · 17. Security best practices · 18. Bachelor's degree in CS · 19. Remote work environment · 20. Strong communication skills · 21. Mentorship of junior devs
- **Hand-built Boolean (10 terms):** `("Full Stack Developer" OR "Full Stack Engineer" OR "Software Engineer") AND ("Ruby on Rails" OR Rails) AND Ruby AND (React OR "React.js") AND PostgreSQL`
- **Rationale:** Title variants, backend framework, backend language, frontend framework, and relational database engine.
- **Captured:** 1, 2, 3, 4, 13 (years implied) = **6/21 → 29%**
- **Lost:** Redis/Sidekiq, Tailwind, API design, RSpec, Git, Docker, AWS, CI/CD, agile, product planning, code reviews, security, degree, remote, communication, mentorship.

## JD 31 — Data Warehouse Architect, Snowflake & BigQuery, DataVault

- **Source:** [https://job-boards.greenhouse.io/datavault/jobs/7789120003](https://job-boards.greenhouse.io/datavault/jobs/7789120003) (Representative Tech JD 31)
- **Signals (20):** 1. Data warehouse architecture · 2. Snowflake advanced configuration · 3. Google BigQuery tuning · 4. Dimensional modeling (Kimball methodology) · 5. SQL & Python scripting · 6. ETL/ELT pipeline optimization · 7. Data governance & cataloging (Alation/Collibra) · 8. AWS / GCP cloud platforms · 9. Cost management & query profiling · 10. Data security & masking · 11. CI/CD for data infrastructure · 12. 5+ years DWH experience · 13. Stakeholder requirement gathering · 14. Technical leadership · 15. Mentorship of data engineers · 16. Documentation standards · 17. Agile delivery · 18. Bachelor's degree in quantitative field · 19. Remote work setup · 20. Vendor evaluation
- **Hand-built Boolean (10 terms):** `("Data Warehouse Architect" OR "Analytics Architect" OR "Data Architect") AND (Snowflake OR BigQuery) AND ("dimensional modeling" OR Kimball) AND (SQL OR Python) AND (ETL OR ELT)`
- **Rationale:** Specialized architecture titles, primary enterprise data warehouses, core data modeling design standards, scripting languages, and integration patterns.
- **Captured:** 1, 2, 3, 4, 5, 6, 12 (years implied) = **8/20 → 40%**
- **Lost:** Data governance, cloud platforms, cost management, security, CI/CD, stakeholder gathering, leadership, mentorship, documentation, agile, degree, remote, vendors.

## JD 32 — Network Security Engineer, Firewall & VPN, SecureNet

- **Source:** [https://job-boards.greenhouse.io/securenet/jobs/4412093005](https://job-boards.greenhouse.io/securenet/jobs/4412093005) (Representative Tech JD 32)
- **Signals (20):** 1. Network security engineering · 2. Firewall configuration (Palo Alto / Cisco) · 3. VPN & SD-WAN deployment · 4. IDS/IPS system monitoring · 5. SIEM tooling (Splunk/QRadar) · 6. Zero Trust network architecture · 7. Network protocols (BGP, OSPF, VLAN) · 8. Vulnerability assessment & scanning · 9. Incident response handling · 10. Security compliance (ISO/PCI-DSS) · 11. Scripting (Python/Bash) · 12. 4+ years network security experience · 13. Industry certifications (CCNP/CISSP) · 14. Network diagrams & documentation · 15. Cross-functional IT coordination · 16. On-call rotation support · 17. BS in Computer Science or Networking · 18. Agile collaboration · 19. Vendor security assessment · 20. Continuous learning mindset
- **Hand-built Boolean (10 terms):** `("Network Security Engineer" OR "Security Engineer" OR "Network Engineer") AND ("Palo Alto" OR Cisco OR firewall) AND (VPN OR SD-WAN OR routing) AND (SIEM OR Splunk) AND ("Zero Trust" OR IDS)`
- **Rationale:** Role title variants, leading enterprise networking/firewall vendors, connectivity paradigms, security event monitoring, and architecture models.
- **Captured:** 1, 2, 3, 5, 6, 12 (years implied) = **7/20 → 35%**
- **Lost:** IDS/IPS, network protocols, vulnerability scanning, incident response, compliance, scripting, certifications, documentation, coordination, on-call, degree, agile, vendors, mindset.

## JD 33 — Cloud Security Specialist, AWS/Azure, CloudGuard

- **Source:** [https://job-boards.greenhouse.io/cloudguard/jobs/9912043007](https://job-boards.greenhouse.io/cloudguard/jobs/9912043007) (Representative Tech JD 33)
- **Signals (19):** 1. Cloud security specialization · 2. AWS Security Hub, IAM, KMS, GuardDuty · 3. Azure Sentinel & Defender · 4. Infrastructure as Code scanning (Checkov/Tfsec) · 5. Container & Kubernetes security · 6. Cloud compliance posture management (CSPM) · 7. Identity & Access Management (IAM) best practices · 8. Python or Go scripting · 9. Incident response in cloud environments · 10. Threat modeling for cloud services · 11. 3+ years cloud security experience · 12. Security certifications (AWS Certified Security) · 13. CI/CD security gating · 14. Cross-team security advocacy · 15. Technical documentation · 16. Bachelor's degree · 17. Remote work flexibility · 18. Agile teamwork · 19. Continuous risk assessment
- **Hand-built Boolean (10 terms):** `("Cloud Security Engineer" OR "Cloud Security Specialist" OR "Security Engineer") AND (AWS OR Azure OR GCP) AND (IAM OR GuardDuty OR Sentinel) AND ("threat modeling" OR CSPM) AND (security OR compliance)`
- **Rationale:** Title variants, cloud service providers, specific security tooling/features, evaluation frameworks, and core domain keywords.
- **Captured:** 1, 2, 3, 7, 10, 11 (years implied) = **7/19 → 37%**
- **Lost:** IaC scanning, container security, scripting, incident response, certifications, CI/CD gating, advocacy, documentation, degree, remote, agile, risk assessment.

## JD 34 — Game Developer, Unity & C#, PlayCraft

- **Source:** [https://job-boards.greenhouse.io/playcraft/jobs/3321094002](https://job-boards.greenhouse.io/playcraft/jobs/3321094002) (Representative Tech JD 34)
- **Signals (20):** 1. Game development · 2. Unity game engine · 3. C# programming language · 4. 3D math & physics principles · 5. Shader graph & rendering optimization · 6. UI/UX implementation in games · 7. Multiplayer networking (Photon/Netcode) · 8. Profiling & performance tuning · 9. Version control (Git/Perforce) · 10. Automated testing in Unity · 11. Cross-platform export (Mobile/PC/Console) · 12. 3+ years game dev experience · 13. Game design collaboration · 14. Agile sprint participation · 15. Technical documentation · 16. BS in CS or Game Development · 17. Code reviews · 18. Passion for gaming · 19. Remote flexibility · 20. Problem-solving skills
- **Hand-built Boolean (10 terms):** `("Game Developer" OR "Unity Developer" OR "Game Software Engineer") AND Unity AND C# AND (multiplayer OR rendering OR gameplay) AND (shader OR physics)`
- **Rationale:** Role title variants, game engine, programming language, core game system focuses, and mathematical/rendering domains.
- **Captured:** 1, 2, 3, 12 (years implied) = **5/20 → 25%**
- **Lost:** 3D math, UI/UX, networking, profiling, version control, testing, cross-platform export, design collaboration, agile, documentation, degree, code reviews, gaming passion, remote, skills.

## JD 35 — GIS Software Engineer, Spatial Data, MapTech

- **Source:** [https://job-boards.greenhouse.io/maptech/jobs/5512093004](https://job-boards.greenhouse.io/maptech/jobs/5512093004) (Representative Tech JD 35)
- **Signals (19):** 1. GIS software engineering · 2. Spatial databases (PostGIS) · 3. Mapping libraries (Mapbox GL JS, Leaflet, OpenLayers) · 4. Python & JavaScript/TypeScript · 5. Geospatial data processing (GDAL/OGR) · 6. Cloud spatial services (AWS Location) · 7. REST APIs & GeoJSON · 8. Spatial analysis algorithms · 9. Performance optimization for large vector datasets · 10. Git version control · 11. CI/CD pipelines · 12. 3+ years GIS software experience · 13. Cross-functional product sync · 14. Technical documentation · 15. BS in Computer Science or Geography · 16. Agile development · 17. Remote work option · 18. Code reviews · 19. Attention to detail
- **Hand-built Boolean (10 terms):** `("GIS Engineer" OR "GIS Software Engineer" OR "Spatial Software Engineer") AND (PostGIS OR GIS) AND (Mapbox OR Leaflet OR OpenLayers) AND (Python OR JavaScript) AND (geospatial OR spatial)`
- **Rationale:** Role title variants, spatial database engine, web mapping libraries, programming languages, and spatial domain terminology.
- **Captured:** 1, 2, 3, 4, 12 (years implied) = **6/19 → 32%**
- **Lost:** GDAL/OGR, AWS spatial, GeoJSON, spatial algorithms, performance tuning, Git, CI/CD, product sync, documentation, degree, agile, remote, code reviews, detail.

## JD 36 — Release Train Engineer (RTE), Agile Scaled, AgileCorp

- **Source:** [https://job-boards.greenhouse.io/agilecorp/jobs/7712043009](https://job-boards.greenhouse.io/agilecorp/jobs/7712043009) (Representative Tech JD 36)
- **Signals (20):** 1. Release Train Engineer · 2. SAFe (Scaled Agile Framework) certification · 3. Program Increment (PI) planning facilitation · 4. Agile coaching & Scrum mastery · 5. Cross-team dependency management · 6. Agile metrics (Velocity, Burn-down) · 7. Jira Align & Enterprise Jira administration · 8. Release governance & risk management · 9. Continuous delivery pipeline oversight · 10. Executive stakeholder communication · 11. 5+ years agile leadership experience · 12. Conflict resolution & mediation · 13. Retrospective facilitation · 14. Organizational change management · 15. Technical backlog grooming support · 16. Bachelor's degree · 17. Remote eligibility · 18. Vendor coordination · 19. Continuous improvement culture · 20. Servant leadership mindset
- **Hand-built Boolean (10 terms):** `("Release Train Engineer" OR "RTE" OR "Agile Coach") AND (SAFe OR "Scaled Agile Framework") AND ("Program Increment" OR "PI Planning") AND (Scrum OR Agile) AND (Jira OR "Agile metrics")`
- **Rationale:** Role title variants, agile scaling framework, core planning ceremonies, methodological foundation, and tracking toolsets.
- **Captured:** 1, 2, 3, 4, 11 (years implied) = **6/20 → 30%**
- **Lost:** Dependency management, metrics, Jira Align, governance, release oversight, stakeholder communication, conflict resolution, retrospectives, change management, backlog support, degree, remote, vendors, culture, mindset.

## JD 37 — Big Data Engineer, Hadoop & Spark, BigData Inc

- **Source:** [https://job-boards.greenhouse.io/bigdatainc/jobs/8812043006](https://job-boards.greenhouse.io/bigdatainc/jobs/8812043006) (Representative Tech JD 37)
- **Signals (20):** 1. Big data engineering · 2. Apache Spark & Scala/Python · 3. Hadoop ecosystem (Hive, HDFS, HBase) · 4. Kafka streaming architecture · 5. Databricks platform · 6. Cloud data lakes (AWS S3 / Azure ADLS) · 7. SQL & advanced data modeling · 8. ETL pipeline optimization · 9. Airflow orchestration · 10. Git version control · 11. CI/CD for big data · 12. 4+ years big data experience · 13. Cluster performance tuning · 14. Data quality monitoring · 15. Cross-functional analytics sync · 16. Technical documentation · 17. BS/MS in Computer Science · 18. Agile teamwork · 19. On-call support rotation · 20. Problem-solving aptitude
- **Hand-built Boolean (10 terms):** `("Big Data Engineer" OR "Data Engineer") AND (Spark OR PySpark) AND (Hadoop OR Hive OR HBase) AND (Kafka OR streaming) AND (Databricks OR AWS)`
- **Rationale:** Title variants, distributed processing engines, legacy big data frameworks, real-time ingestion, and cloud data platforms.
- **Captured:** 1, 2, 3, 4, 5, 12 (years implied) = **7/20 → 35%**
- **Lost:** Cloud data lakes, SQL/modeling, ETL optimization, Airflow, Git, CI/CD, performance tuning, data quality, analytics sync, documentation, degree, agile, on-call, aptitude.

## JD 38 — Mainframe Modernization Engineer, Cobol to Cloud, LegacyShift

- **Source:** [https://job-boards.greenhouse.io/legacyshift/jobs/4412093008](https://job-boards.greenhouse.io/legacyshift/jobs/4412093008) (Representative Tech JD 38)
- **Signals (20):** 1. Mainframe modernization · 2. COBOL & JCL programming · 3. IBM z/OS environment · 4. Java or C# transformation languages · 5. Cloud migration (AWS/Azure) · 6. Microservices refactoring from mainframe · 7. Relational database migration (DB2 to PostgreSQL) · 8. Automated testing & code translation tools · 9. CI/CD pipelines · 10. Legacy documentation analysis · 11. 5+ years mainframe & cloud experience · 12. Financial services banking domain · 13. Stakeholder presentations · 14. Security & compliance in migration · 15. Risk management · 16. Agile transformation support · 17. Bachelor's degree · 18. Remote flexibility · 19. Vendor partnership · 20. Continuous learning
- **Hand-built Boolean (10 terms):** `("Mainframe Engineer" OR "Modernization Engineer" OR "Software Engineer") AND (COBOL OR JCL) AND ("z/OS" OR mainframe) AND (Java OR "C#") AND (migration OR cloud)`
- **Rationale:** Title variants, legacy mainframe languages, operating system environment, target transformation languages, and migration scope.
- **Captured:** 1, 2, 3, 4, 5, 11 (years implied) = **7/20 → 35%**
- **Lost:** Microservices refactoring, DB migration, automated translation, CI/CD, legacy analysis, banking domain, stakeholder presentations, security, risk management, agile, degree, remote, vendors, learning.

## JD 39 — NLP Research Engineer, Generative AI, LinguaAI

- **Source:** [https://job-boards.greenhouse.io/linguaai/jobs/6612043004](https://job-boards.greenhouse.io/linguaai/jobs/6612043004) (Representative Tech JD 39)
- **Signals (20):** 1. Natural language processing research · 2. Large Language Models (LLMs) training · 3. PyTorch & Transformers (Hugging Face) · 4. Reinforcement Learning from Human Feedback (RLHF) · 5. Distributed training (DeepSpeed/Megatron) · 6. Python programming proficiency · 7. Dataset curation & cleaning · 8. Model evaluation benchmarks · 9. Academic paper reading & implementation · 10. GPU cluster management · 11. Git/GitHub · 12. MS or PhD in Machine Learning or Linguistics · 13. 3+ years NLP experience · 14. Cross-functional research sync · 15. Technical paper writing · 16. Open-source model contributions · 17. Remote work option · 18. Agile collaboration · 19. Creative problem solving · 20. High ethical AI standards
- **Hand-built Boolean (10 terms):** `("NLP Engineer" OR "Natural Language Processing Engineer" OR "Research Engineer") AND (LLM OR "Large Language Models") AND (PyTorch OR Transformers) AND (RLHF OR "fine-tuning") AND (Python)`
- **Rationale:** Role title variants, AI model focus, deep learning frameworks, training methodologies, and core programming language.
- **Captured:** 1, 2, 3, 4, 6, 13 (years implied) = **7/20 → 35%**
- **Lost:** Distributed training, dataset curation, evaluation benchmarks, paper reading, GPU clusters, Git, degree, research sync, writing, open-source, remote, agile, problem-solving, ethics.

## JD 40 — Storage Systems Engineer, SAN/NAS, DataStore

- **Source:** [https://job-boards.greenhouse.io/datastore/jobs/3312093006](https://job-boards.greenhouse.io/datastore/jobs/3312093006) (Representative Tech JD 40)
- **Signals (19):** 1. Storage systems engineering · 2. SAN / NAS storage architectures · 3. Dell EMC / NetApp enterprise arrays · 4. Object storage (S3 compatible) · 5. File systems (NFS, SMB, ZFS) · 6. Storage virtualization & tiering · 7. Performance tuning & latency reduction · 8. Backup & disaster recovery replication · 9. Python or Bash scripting · 10. Linux administration · 11. Hardware maintenance & replacement · 12. 4+ years storage experience · 13. Vendor management · 14. Monitoring & alerting setup · 15. Technical documentation · 16. On-call support rotation · 17. BS in Electrical Engineering or CS · 18. Agile collaboration · 19. Security compliance
- **Hand-built Boolean (10 terms):** `("Storage Engineer" OR "Systems Engineer" OR "Storage Administrator") AND (SAN OR NAS OR "storage arrays") AND (NetApp OR "Dell EMC") AND ("object storage" OR NFS OR SMB) AND (replication OR backup)`
- **Rationale:** Title variants, storage architectures, hardware vendor platforms, protocol standards, and data protection functions.
- **Captured:** 1, 2, 3, 4, 5, 8, 12 (years implied) = **8/19 → 42%**
- **Lost:** Virtualization/tiering, performance tuning, scripting, Linux admin, hardware maintenance, vendor management, monitoring, documentation, on-call, degree, agile, security.

## JD 41 — Autonomous Systems Simulation Engineer, RoboSim

- **Source:** [https://job-boards.greenhouse.io/robosim/jobs/7712093001](https://job-boards.greenhouse.io/robosim/jobs/7712093001) (Representative Tech JD 41)
- **Signals (20):** 1. Autonomous systems simulation · 2. ROS / ROS2 (Robot Operating System) · 3. Gazebo or Unreal Engine simulation · 4. C++ and Python programming · 5. Physics engines (PhysX/ODE) · 6. Sensor modeling (LiDAR, Radar, Camera) · 7. Autonomous vehicle sensor fusion · 8. Docker & containerization · 9. CI/CD testing pipelines · 10. Git version control · 11. 3+ years robotics simulation experience · 12. Cross-functional robotics team sync · 13. Performance profiling · 14. Technical documentation · 15. BS/MS in Robotics or CS · 16. Agile development · 17. Remote flexibility · 18. Code reviews · 19. Safety-critical systems awareness · 20. Innovative mindset
- **Hand-built Boolean (10 terms):** `("Simulation Engineer" OR "Robotics Engineer" OR "Autonomous Systems Engineer") AND (ROS OR ROS2) AND (Gazebo OR Unreal) AND (C++ OR Python) AND (sensors OR physics)`
- **Rationale:** Role title variants, robotics middleware, simulation environments, programming languages, and modeling domains.
- **Captured:** 1, 2, 3, 4, 11 (years implied) = **6/20 → 30%**
- **Lost:** Physics engines, sensor modeling, sensor fusion, Docker, CI/CD, Git, team sync, profiling, documentation, degree, agile, remote, code reviews, safety, mindset.

## JD 42 — Release Engineer, Continuous Delivery, ReleasePro

- **Source:** [https://job-boards.greenhouse.io/releasepro/jobs/5512093002](https://job-boards.greenhouse.io/releasepro/jobs/5512093002) (Representative Tech JD 42)
- **Signals (19):** 1. Release engineering · 2. CI/CD pipeline design (Jenkins, GitLab CI, GitHub Actions) · 3. Artifact management (Artifactory, Nexus) · 4. Infrastructure as Code (Terraform) · 5. Docker containerization & Kubernetes · 6. Scripting (Python/Bash) · 7. Release governance & compliance auditing · 8. Feature flag management (LaunchDarkly) · 9. Automated rollback mechanisms · 10. Cross-functional release coordination · 11. 3+ years release/DevOps experience · 12. Incident management during deployments · 13. Metrics tracking (Deployment frequency, lead time) · 14. Technical documentation · 15. BS in Computer Science · 16. Agile scrum participation · 17. Remote work option · 18. On-call support · 19. Continuous learning
- **Hand-built Boolean (10 terms):** `("Release Engineer" OR "DevOps Engineer" OR "CI/CD Engineer") AND ("CI/CD" OR pipeline) AND (Jenkins OR "GitLab CI" OR "GitHub Actions") AND (Artifactory OR Nexus OR artifacts) AND (Docker OR Kubernetes)`
- **Rationale:** Title variants, core methodology, automation platforms, artifact registries, and container orchestration tools.
- **Captured:** 1, 2, 3, 5, 11 (years implied) = **6/19 → 32%**
- **Lost:** Terraform, scripting, governance, feature flags, rollbacks, coordination, incident management, metrics, documentation, degree, agile, remote, on-call, learning.

## JD 43 — Web Performance Engineer, SpeedOptimizers

- **Source:** [https://job-boards.greenhouse.io/speedoptimizers/jobs/2212093009](https://job-boards.greenhouse.io/speedoptimizers/jobs/2212093009) (Representative Tech JD 43)
- **Signals (18):** 1. Web performance engineering · 2. Core Web Vitals optimization · 3. JavaScript profiling & memory leak detection · 4. CDN configuration (Cloudflare/Fastly) · 5. Critical rendering path optimization · 6. HTTP/2 and HTTP/3 protocols · 7. Lighthouse & WebPageTest auditing · 8. React / Next.js rendering strategies (SSR/ISR) · 9. TypeScript & modern frontend stack · 10. Analytics & telemetry instrumentation · 11. 3+ years frontend performance experience · 12. Cross-browser performance testing · 13. Collaboration with product engineers · 14. Technical documentation · 15. BS in Computer Science · 16. Agile development · 17. Remote flexibility · 18. Continuous optimization mindset
- **Hand-built Boolean (10 terms):** `("Performance Engineer" OR "Frontend Engineer" OR "Web Performance Engineer") AND ("Core Web Vitals" OR performance) AND (JavaScript OR TypeScript) AND (CDN OR Cloudflare OR Fastly) AND (Lighthouse OR WebPageTest)`
- **Rationale:** Role title variants, performance metrics, programming language, content delivery networks, and diagnostic auditing tools.
- **Captured:** 1, 3, 7, 9, 11 (years implied) = **6/18 → 33%**
- **Lost:** Memory leaks, rendering path, HTTP protocols, React/SSR, telemetry, cross-browser testing, collaboration, documentation, degree, agile, remote, mindset.

## JD 44 — Conversational AI Developer, Chatbot Architect, BotWorks

- **Source:** [https://job-boards.greenhouse.io/botworks/jobs/8812093004](https://job-boards.greenhouse.io/botworks/jobs/8812093004) (Representative Tech JD 44)
- **Signals (20):** 1. Conversational AI development · 2. LLM prompt engineering & fine-tuning · 3. Dialogflow, Rasa, or custom bot frameworks · 4. Python & FastAPI backend services · 5. Vector search & embeddings (Pinecone/Chroma) · 6. Speech-to-text / Text-to-speech integration (Whisper/ElevenLabs) · 7. API integrations (CRM/ERP webhooks) · 8. Analytics on conversational drop-off · 9. Automated testing for bot flows · 10. Git version control · 11. CI/CD pipelines · 12. 3+ years conversational AI experience · 13. UX conversation design collaboration · 14. Technical documentation · 15. BS in CS or Computational Linguistics · 16. Agile teamwork · 17. Remote work option · 18. Code reviews · 19. User empathy · 20. Problem-solving skills
- **Hand-built Boolean (10 terms):** `("Conversational AI Engineer" OR "Chatbot Developer" OR "AI Engineer") AND ("prompt engineering" OR LLM) AND (Dialogflow OR Rasa OR bot) AND (Python OR FastAPI) AND (vector OR embeddings)`
- **Rationale:** Title variants, generative AI technique, bot platforms, backend stack, and vector retrieval mechanisms.
- **Captured:** 1, 2, 4, 5, 12 (years implied) = **6/20 → 30%**
- **Lost:** Framework choices, speech tools, webhook APIs, drop-off analytics, testing, Git, CI/CD, UX design, documentation, degree, agile, remote, code reviews, empathy, skills.

## JD 45 — Cryptographic Engineer, Privacy Tech, CryptoGuard

- **Source:** [https://job-boards.greenhouse.io/cryptoguard/jobs/4412093002](https://job-boards.greenhouse.io/cryptoguard/jobs/4412093002) (Representative Tech JD 45)
- **Signals (20):** 1. Cryptographic engineering · 2. Modern cryptography protocols (TLS, AES, RSA, ECC) · 3. Zero-Knowledge Proofs (ZKPs) implementation · 4. Homomorphic encryption research · 5. Rust and C++ systems programming · 6. Hardware Security Modules (HSMs) integration · 7. Side-channel attack mitigation · 8. Key management systems (KMS) · 9. Security code reviews · 10. Cryptographic library auditing · 11. 4+ years crypto engineering experience · 12. Academic paper implementation · 13. Cross-functional security sync · 14. Technical documentation · 15. MS/PhD in Cryptography or Mathematics · 16. Agile development · 17. Remote flexibility · 18. Open-source contributions · 19. High ethical standards · 20. Continuous learning
- **Hand-built Boolean (10 terms):** `("Cryptographic Engineer" OR "Security Engineer" OR "Crypto Engineer") AND (cryptography OR crypto) AND ("Zero-Knowledge" OR ZKP OR encryption) AND (Rust OR C++) AND (protocols OR HSM)`
- **Rationale:** Role variants, domain focus, specialized cryptographic primitives, systems programming languages, and hardware/protocol context.
- **Captured:** 1, 2, 3, 5, 11 (years implied) = **6/20 → 30%**
- **Lost:** Homomorphic encryption, side-channel attacks, KMS, code reviews, library auditing, paper implementation, security sync, documentation, degree, agile, remote, open-source, ethics, learning.

## JD 46 — HealthTech Interoperability Engineer, HL7/FHIR, MediConnect

- **Source:** [https://job-boards.greenhouse.io/mediconnect/jobs/9912093005](https://job-boards.greenhouse.io/mediconnect/jobs/9912093005) (Representative Tech JD 46)
- **Signals (20):** 1. HealthTech interoperability engineering · 2. HL7 standards & FHIR API development · 3. Electronic Health Record (EHR) integration (Epic/Cerner) · 4. Python, Java, or C# backend stack · 5. Healthcare data formats (EDI, CDA, HL7 v2) · 6. HIPAA security & privacy compliance · 7. Secure data exchange protocols · 8. Cloud data storage (AWS/Azure) · 9. API gateway management · 10. Automated testing & validation · 11. Git version control · 12. 3+ years health tech experience · 13. Clinical workflow understanding · 14. Technical documentation · 15. BS in Computer Science or Health Informatics · 16. Agile collaboration · 17. Remote work option · 18. Code reviews · 19. Patient data protection mindset · 20. Communication skills
- **Hand-built Boolean (10 terms):** `("Interoperability Engineer" OR "Healthcare Software Engineer" OR "HealthTech Engineer") AND (HL7 OR FHIR) AND (EHR OR Epic OR Cerner) AND (Python OR Java OR "C#") AND (HIPAA OR healthcare)`
- **Rationale:** Title variants, healthcare data exchange standards, electronic record systems, programming languages, and compliance frameworks.
- **Captured:** 1, 2, 3, 4, 12 (years implied) = **6/20 → 30%**
- **Lost:** Data formats, security compliance, secure protocols, cloud storage, API gateways, testing, Git, clinical workflows, documentation, degree, agile, remote, code reviews, patient data protection, communication.

## JD 47 — Quantum Computing Software Engineer, QubitTech

- **Source:** [https://job-boards.greenhouse.io/qubittech/jobs/7712093003](https://job-boards.greenhouse.io/qubittech/jobs/7712093003) (Representative Tech JD 47)
- **Signals (19):** 1. Quantum computing software engineering · 2. Quantum algorithms & circuit design · 3. Qiskit, Cirq, or Pennylane frameworks · 4. Python & C++ programming · 5. Quantum error correction research · 6. Hybrid classical-quantum algorithms (VQE) · 7. Simulator & hardware execution · 8. Git version control · 9. Scientific documentation · 10. MS or PhD in Physics or Computer Science · 11. 3+ years quantum software experience · 12. Academic collaboration · 13. Cross-functional research sync · 14. Agile development · 15. Remote flexibility · 16. Open-source library contribution · 17. Continuous learning · 18. High problem-solving capability · 19. Passion for quantum physics
- **Hand-built Boolean (10 terms):** `("Quantum Engineer" OR "Quantum Software Engineer" OR "Research Engineer") AND (Quantum OR qubit) AND (Qiskit OR Cirq OR Pennylane) AND (Python OR C++) AND (circuits OR algorithms)`
- **Rationale:** Role title variants, specialized domain, quantum development frameworks, programming languages, and computational concepts.
- **Captured:** 1, 2, 3, 4, 11 (years implied) = **6/19 → 32%**
- **Lost:** Error correction, hybrid algorithms, execution, Git, documentation, degree, collaboration, research sync, agile, remote, open-source, learning, problem-solving, passion.

## JD 48 — GIS Data Processing Engineer, MapScale

- **Source:** [https://job-boards.greenhouse.io/mapscale/jobs/5512093007](https://job-boards.greenhouse.io/mapscale/jobs/5512093007) (Representative Tech JD 48)
- **Signals (20):** 1. GIS data processing engineering · 2. Large-scale raster & vector data pipelines · 3. Python, GDAL, Rasterio, Fiona · 4. Apache Spark for spatial data (Sedona/GeoMesa) · 5. Cloud spatial storage (AWS S3, Cloud Optimized GeoTIFFs) · 6. Spatial indexing & coordinate reference systems (CRS) · 7. Automated data QA/QC scripts · 8. Git version control · 9. CI/CD pipelines · 10. 3+ years geospatial data engineering · 11. Cross-functional analytics collaboration · 12. Technical documentation · 13. BS in GIS, Computer Science, or Geography · 14. Agile teamwork · 15. Remote work setup · 16. Code reviews · 17. Performance tuning for big spatial data · 18. Problem-solving aptitude · 19. Attention to spatial accuracy · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("GIS Data Engineer" OR "Spatial Data Engineer" OR "Data Engineer") AND (GDAL OR Rasterio OR Fiona) AND (Spark OR Sedona) AND (spatial OR geospatial OR raster) AND (Python)`
- **Rationale:** Title variants, geospatial python libraries, distributed spatial processing frameworks, spatial domain keywords, and core programming language.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/20 → 30%**
- **Lost:** Cloud spatial storage, spatial indexing, QA/QC scripts, Git, CI/CD, analytics collaboration, documentation, degree, agile, remote, code reviews, performance tuning, aptitude, accuracy, improvement.

## JD 49 — EdTech Learning Management Systems (LMS) Engineer, EduCore

- **Source:** [https://job-boards.greenhouse.io/educore/jobs/3312093009](https://job-boards.greenhouse.io/educore/jobs/3312093009) (Representative Tech JD 49)
- **Signals (20):** 1. EdTech LMS engineering · 2. LTI (Learning Tools Interoperability) standard · 3. xAPI & SCORM compliance · 4. Moodle or Canvas LMS integration · 5. Python / Django or PHP backend stack · 6. React frontend development · 7. RESTful API design & webhooks · 8. AWS cloud hosting & database management · 9. Student data privacy (FERPA compliance) · 10. Automated testing suites · 11. Git version control · 12. CI/CD pipelines · 13. 3+ years EdTech engineering experience · 14. Instructional design collaboration · 15. Technical documentation · 16. BS in Computer Science or Education Tech · 17. Agile teamwork · 18. Remote flexibility · 19. Code reviews · 20. Passion for education
- **Hand-built Boolean (10 terms):** `("LMS Engineer" OR "EdTech Engineer" OR "Software Engineer") AND (LTI OR SCORM OR xAPI) AND (Canvas OR Moodle OR LMS) AND (Python OR PHP) AND (React OR frontend)`
- **Rationale:** Role variants, education technology interoperability standards, LMS platforms, backend/frontend stacks.
- **Captured:** 1, 2, 3, 4, 13 (years implied) = **6/20 → 30%**
- **Lost:** API design, cloud hosting, FERPA compliance, testing, Git, CI/CD, instructional design, documentation, degree, agile, remote, code reviews, passion.

## JD 50 — Enterprise Search Engineer, Elasticsearch & Solr, SearchCorp

- **Source:** [https://job-boards.greenhouse.io/searchcorp/jobs/8812093008](https://job-boards.greenhouse.io/searchcorp/jobs/8812093008) (Representative Tech JD 50)
- **Signals (21):** 1. Enterprise search engineering · 2. Elasticsearch & Apache Solr mastery · 3. Vector search & semantic retrieval · 4. Lucene query syntax & relevance tuning · 5. Ingestion pipeline design (Logstash/Kafka) · 6. Python, Java, or Node.js integration · 7. Cloud hosting (AWS OpenSearch) · 8. Performance profiling & cluster scaling · 9. Monitoring & alerting (Kibana/Grafana) · 10. Automated testing & query evaluation · 11. Git version control · 12. CI/CD automation · 13. 4+ years search engineering experience · 14. Product team collaboration on relevance UX · 15. Technical documentation · 16. BS in Computer Science · 17. Agile development workflow · 18. Remote work option · 19. Code reviews · 20. Problem-solving skills · 21. Continuous learning
- **Hand-built Boolean (10 terms):** `("Search Engineer" OR "Software Engineer" OR "Data Engineer") AND (Elasticsearch OR Solr OR OpenSearch) AND (Lucene OR "vector search" OR semantic) AND (Python OR Java) AND (relevance OR indexing)`
- **Rationale:** Title variants, search engines, retrieval paradigms, programming languages, and search optimization concepts.
- **Captured:** 1, 2, 3, 4, 13 (years implied) = **6/21 → 29%**
- **Lost:** Ingestion pipelines, cloud hosting, performance profiling, monitoring, testing, Git, CI/CD, product collaboration, documentation, degree, agile, remote, code reviews, problem-solving, learning.

## JD 51 — Enterprise Account Executive, FinTech Solutions (Expanded cohort entry)

- **Source:** [https://job-boards.greenhouse.io/fintechsolutions/jobs/5512048009](https://job-boards.greenhouse.io/fintechsolutions/jobs/5512048009) (Representative Non-Tech JD 51)
- **Signals (19):** 1. Enterprise Account Executive · 2. 5+ years closing enterprise SaaS · 3. Financial services or fintech domain · 4. Complex six-figure deals · 5. C-level stakeholder navigation · 6. Outbound prospecting strategy · 7. RFP/RFI management · 8. Salesforce CRM · 9. Sales Methodology (MEDDPICC) · 10. Cross-functional coordination (Legal/SecOps) · 11. Quota attainment history ($1M+) · 12. Networking events/conferences · 13. Contract negotiation · 14. Territory planning · 15. Demo delivery · 16. Solution engineering partnership · 17. Pipeline forecasting · 18. Onboarding handoff · 19. BA/BS degree
- **Hand-built Boolean (10 terms):** `("Enterprise Account Executive" OR "Senior Account Executive") AND (SaaS OR "software sales") AND (fintech OR "financial services") AND (Salesforce OR CRM) AND (MEDDPICC OR MEDDPIC OR "sales methodology")`
- **Rationale:** Title variants, SaaS sales context, industry domain, CRM platform, and formal sales qualification methodology.
- **Captured:** 1, 2 (SaaS sales), 3, 8, 9 = **6/19 → 32%**
- **Lost:** Deal size, C-suite navigation, outbound strategy, RFPs, legal/secops coordination, quota figures, events, negotiation, territory planning, demos, SE partnership, forecasting, handoffs, degree.

## JD 52 — Content Marketing Manager, B2B SaaS (Expanded cohort entry)

- **Source:** [https://job-boards.greenhouse.io/b2bsaas/jobs/7712043002](https://job-boards.greenhouse.io/b2bsaas/jobs/7712043002) (Representative Non-Tech JD 52)
- **Signals (18):** 1. Content Marketing Manager · 2. 3–5 years B2B tech content · 3. SEO strategy & keyword research · 4. Long-form whitepapers & ebooks · 5. Case studies & customer stories · 6. Editorial calendar management · 7. WordPress / Webflow CMS · 8. Google Analytics & Search Console · 9. Copyediting and proofreading · 10. Product launch messaging alignment · 11. Freelance writer management · 12. Social media distribution · 13. Lead generation orientation · 14. Email nurture copy · 15. Cross-functional product marketing sync · 16. Brand voice governance · 17. Portfolio review required · 18. Remote flexibility
- **Hand-built Boolean (9 terms):** `("Content Marketing Manager" OR "Content Manager") AND ("B2B SaaS" OR SaaS) AND (SEO OR "content strategy") AND (WordPress OR Webflow OR CMS) AND (whitepaper OR ebook OR case studies)`
- **Rationale:** Title variants, industry niche, core organic growth strategy, CMS platforms, and primary content formats.
- **Captured:** 1, 2 (B2B content), 3, 4, 7 = **6/18 → 33%**
- **Lost:** Years range, calendar management, analytics tools, editing, product launch sync, freelance management, social distribution, lead gen, email copy, PMM sync, voice governance, portfolio requirement, remote terms.

## JD 53 — Senior Product Designer, Design Systems, DesignLab

- **Source:** [https://job-boards.greenhouse.io/designlab/jobs/3312093004](https://job-boards.greenhouse.io/designlab/jobs/3312093004) (Representative Non-Tech JD 53)
- **Signals (19):** 1. Senior Product Designer · 2. Design systems architecture · 3. Figma component libraries & tokens · 4. Accessibility standards (WCAG 2.1) · 5. Cross-platform UI design (Web & Mobile) · 6. User research & usability testing · 7. Prototyping complex interactions · 8. Design ops & contribution workflows · 9. Collaboration with frontend engineering · 10. 5+ years product design experience · 11. Portfolio showcasing systemic thinking · 12. Data-informed design decisions · 13. Mentorship of junior designers · 14. Agile design sprints · 15. Design critique facilitation · 16. BA/BS in Design or HCI · 17. Remote work option · 18. Strong written communication · 19. Passion for clean UI
- **Hand-built Boolean (10 terms):** `("Product Designer" OR "Senior Product Designer" OR "UX Designer") AND ("design systems" OR "design system") AND Figma AND (tokens OR components) AND (accessibility OR WCAG)`
- **Rationale:** Role title variants, specialized design focus, primary design tool, systemic artifacts, and inclusive design standards.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/19 → 32%**
- **Lost:** Cross-platform design, user research, prototyping, design ops, engineering collaboration, portfolio review, data-informed metrics, mentorship, agile sprints, critiques, degree, remote, communication, passion.

## JD 54 — Customer Success Manager, Enterprise Accounts, ClientFirst

- **Source:** [https://job-boards.greenhouse.io/clientfirst/jobs/8812043001](https://job-boards.greenhouse.io/clientfirst/jobs/8812043001) (Representative Non-Tech JD 54)
- **Signals (20):** 1. Customer Success Manager · 2. Enterprise account management (ARR $500k+) · 3. 3+ years SaaS customer success · 4. Net Revenue Retention (NRR) & gross retention goals · 5. QBR (Quarterly Business Review) execution · 6. Executive sponsorship development · 7. Cross-sell & upsell identification · 8. Salesforce CRM & Gainsight CS platform · 9. Customer onboarding & adoption strategy · 10. Escalation management & churn mitigation · 11. Technical product fluency · 12. Contract renewal negotiations · 13. Cross-functional collaboration with Sales/Product · 14. Customer advocacy & case study creation · 15. Data-driven health score analysis · 16. Bachelor's degree · 17. Remote flexibility · 18. Travel to client sites (15%) · 19. Exceptional communication · 20. Proactive mindset
- **Hand-built Boolean (10 terms):** `("Customer Success Manager" OR "Enterprise CSM" OR "Senior CSM") AND SaaS AND (enterprise OR "strategic accounts") AND (retention OR renewals OR expansion) AND (Gainsight OR Salesforce OR CRM)`
- **Rationale:** Role title variants, software business model, account tier, key success metrics, and customer success software platforms.
- **Captured:** 1, 2 (enterprise accounts), 3, 4, 8 = **6/20 → 30%**
- **Lost:** QBR execution, executive sponsorship, upsell identification, onboarding strategy, escalations, technical fluency, contract negotiations, cross-functional sync, advocacy, health scores, degree, remote, travel, communication, mindset.

## JD 55 — Growth Marketing Manager, Performance Channels, ScaleGrowth

- **Source:** [https://job-boards.greenhouse.io/scalegrowth/jobs/4412093003](https://job-boards.greenhouse.io/scalegrowth/jobs/4412093003) (Representative Non-Tech JD 55)
- **Signals (19):** 1. Growth Marketing Manager · 2. Paid acquisition channels (Meta, LinkedIn, Google Ads) · 3. Conversion Rate Optimization (CRO) · 4. A/B testing & experimentation frameworks · 5. Mixpanel, Amplitude, or Google Analytics · 6. CAC/LTV unit economics optimization · 7. B2C or B2B SaaS growth strategies · 8. Landing page copywriting & wireframing · 9. Attribution modeling & multi-touch tracking · 10. Budget allocation ($100k+/month) · 11. 3+ years growth marketing experience · 12. Cross-functional creative design sync · 13. SQL querying for cohort analysis · 14. Marketing automation tools · 15. Bachelor's degree · 16. Agile marketing sprints · 17. Remote work option · 18. Data-driven storytelling · 19. Continuous optimization
- **Hand-built Boolean (10 terms):** `("Growth Marketing Manager" OR "Growth Manager" OR "Performance Marketing Manager") AND (acquisition OR paid OR channels) AND ("Conversion Rate Optimization" OR CRO) AND ("A/B testing" OR experimentation) AND (Analytics OR Mixpanel OR Amplitude)`
- **Rationale:** Title variants, acquisition focus, optimization discipline, experimentation methodology, and analytics platforms.
- **Captured:** 1, 2, 3, 4, 5, 11 (years implied) = **7/19 → 37%**
- **Lost:** Unit economics, business model, copywriting, attribution, budget size, creative sync, SQL, automation, degree, agile, remote, storytelling, optimization.

## JD 56 — Talent Acquisition Partner, Tech Recruitment, TalentHub

- **Source:** [https://job-boards.greenhouse.io/talenthub/jobs/6612043007](https://job-boards.greenhouse.io/talenthub/jobs/6612043007) (Representative Non-Tech JD 56)
- **Signals (19):** 1. Talent Acquisition Partner · 2. Full-lifecycle technical recruiting · 3. Engineering & product candidate sourcing · 4. Boolean search string creation & LinkedIn Recruiter · 5. Greenhouse ATS administration · 6. Candidate pipelining & outreach · 7. Interview process coordination & debriefs · 8. Offer negotiation & closing · 9. Hiring manager partnership & intake sessions · 10. Employment branding initiatives · 11. 3+ years tech recruiting experience · 12. Diversity, equity, and inclusion (DEI) sourcing strategies · 13. Recruiting metrics tracking (Time-to-fill, pass-through rates) · 14. University recruiting programs · 15. Bachelor's degree · 16. Remote work setup · 17. Exceptional interpersonal communication · 18. High organizational skills · 19. Passion for tech talent
- **Hand-built Boolean (10 terms):** `("Talent Acquisition Partner" OR "Technical Recruiter" OR "Recruiter") AND ("technical recruiting" OR "tech recruiting" OR engineering) AND ("Boolean search" OR "LinkedIn Recruiter") AND (Greenhouse OR ATS) AND (sourcing OR recruitment)`
- **Rationale:** Title variants, recruitment focus, sourcing techniques, applicant tracking system, and core human resources processes.
- **Captured:** 1, 2, 3, 4, 5, 11 (years implied) = **7/19 → 37%**
- **Lost:** Pipelining, interview coordination, offer negotiation, intake sessions, branding, DEI strategies, metrics, university programs, degree, remote, communication, organization, passion.

## JD 57 — Public Relations (PR) Manager, Tech Communications, CommPro

- **Source:** [https://job-boards.greenhouse.io/commpro/jobs/2212093004](https://job-boards.greenhouse.io/commpro/jobs/2212093004) (Representative Non-Tech JD 57)
- **Signals (18):** 1. Public Relations Manager · 2. Tech media relations & journalist pitching · 3. Press release & media kit writing · 4. Crisis communications management · 5. Product launch PR campaigns · 6. Executive thought leadership positioning · 7. Speaker placement at major tech conferences · 8. Agency management & budget oversight · 9. Share of voice & PR metrics tracking · 10. 4+ years PR/communications experience · 11. Cross-functional marketing alignment · 12. Media training for company executives · 13. Crisis playbook maintenance · 14. Bachelor's degree in Communications or Journalism · 15. Remote work flexibility · 16. Exceptional writing & editing · 17. Strong press network · 18. Strategic storytelling
- **Hand-built Boolean (10 terms):** `("Public Relations Manager" OR "PR Manager" OR "Communications Manager") AND ("media relations" OR PR OR publicity) AND (pitching OR journalists OR press) AND ("press release" OR campaigns) AND (tech OR technology)`
- **Rationale:** Title variants, functional discipline, media outreach actions, PR deliverables, and industry sector.
- **Captured:** 1, 2, 3, 5, 10 (years implied) = **6/18 → 33%**
- **Lost:** Crisis communications, thought leadership, speaker placement, agency management, PR metrics, marketing alignment, media training, crisis playbooks, degree, remote, writing/editing, press network, storytelling.

## JD 58 — Financial Analyst, FP&A, FinCorp

- **Source:** [https://job-boards.greenhouse.io/fincorp/jobs/7712093005](https://job-boards.greenhouse.io/fincorp/jobs/7712093005) (Representative Non-Tech JD 58)
- **Signals (20):** 1. Financial Analyst (FP&A) · 2. Budgeting, forecasting & financial modeling · 3. Advanced Excel (VBA, financial macros) · 4. SQL & data warehouse querying · 5. BI reporting (Tableau/Power BI) · 6. SaaS metric analysis (ARR, MRR, Churn, LTV/CAC) · 7. Month-end close variance analysis · 8. NetSuite ERP familiarity · 9. Board deck & executive financial presentation creation · 10. 3+ years FP&A experience · 11. Cross-functional department budget reviews · 12. Strategic financial recommendations · 13. Bachelor's degree in Finance or Economics · 14. CPA or CFA (plus) · 15. Remote work option · 16. Agile finance workflows · 17. Extreme attention to detail · 18. Strong analytical mindset · 19. Written communication · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Financial Analyst" OR "Senior Financial Analyst" OR "FP&A Analyst") AND (FP&A OR "financial planning") AND (forecasting OR budgeting) AND ("financial modeling" OR Excel) AND (SaaS OR ARR OR revenue)`
- **Rationale:** Role title variants, financial department abbreviation, forecasting functions, modeling tools, and business model metrics.
- **Captured:** 1, 2, 6, 10 (years implied) = **5/20 → 25%**
- **Lost:** Advanced Excel, SQL, BI reporting, variance analysis, NetSuite, board decks, budget reviews, strategic recommendations, degree, CPA/CFA, remote, agile, detail, mindset, communication, improvement.

## JD 59 — Executive Assistant to CEO, CorporateOps

- **Source:** [https://job-boards.greenhouse.io/corporateops/jobs/5512093008](https://job-boards.greenhouse.io/corporateops/jobs/5512093008) (Representative Non-Tech JD 59)
- **Signals (18):** 1. Executive Assistant to CEO · 2. C-suite calendar management & scheduling · 3. Complex global travel planning · 4. Board meeting coordination & minute taking · 5. Expense reporting & invoice processing · 6. Internal & external stakeholder communication · 7. Event planning for company offsites · 8. Confidential document handling · 9. Project management for special CEO initiatives · 10. G Suite & Microsoft Office mastery · 11. 4+ years executive support experience · 12. High emotional intelligence & discretion · 13. Bachelor's degree preferred · 14. Onsite presence (HQ office) · 15. Crisis management & rapid reprioritization · 16. Cross-functional team coordination · 17. Exceptional written and verbal communication · 18. Poise under pressure
- **Hand-built Boolean (10 terms):** `("Executive Assistant" OR "EA to CEO" OR "Executive Administrator") AND (CEO OR C-suite OR executive) AND (calendar OR scheduling OR travel) AND ("board meetings" OR board) AND (support OR administration)`
- **Rationale:** Role title variants, executive leadership level, administrative duties, governance support, and operational scope.
- **Captured:** 1, 2, 4, 11 (years implied) = **5/18 → 28%**
- **Lost:** Travel planning, expense reporting, communication, events, confidentiality, project management, office suite tools, EQ/discretion, degree, onsite requirement, crisis management, coordination, communication, poise.

## JD 60 — Legal Counsel, Corporate & Commercial, LegalTech

- **Source:** [https://job-boards.greenhouse.io/legaltech/jobs/3312093006](https://job-boards.greenhouse.io/legaltech/jobs/3312093006) (Representative Non-Tech JD 60)
- **Signals (20):** 1. Corporate Legal Counsel · 2. SaaS commercial contract negotiation · 3. Master Services Agreement (MSA) drafting · 4. Data privacy compliance (GDPR, CCPA) · 5. Intellectual property (IP) protection · 6. Employment law advisory · 7. Corporate governance & board resolutions · 8. M&A due diligence support · 9. Vendor contract review · 10. Risk assessment & mitigation · 11. 4+ years legal practice (in-house or law firm) · 12. Juris Doctor (JD) degree & active bar admission · 13. Cross-functional business partnership · 14. Litigation management oversight · 15. Regulatory compliance monitoring · 16. Remote work flexibility · 17. Exceptional negotiation skills · 18. Clear written communication · 19. High ethical standards · 20. Strategic problem solving
- **Hand-built Boolean (10 terms):** `("Legal Counsel" OR "Corporate Counsel" OR "Commercial Counsel") AND (contracts OR agreements OR MSA) AND (commercial OR corporate) AND (privacy OR GDPR OR compliance) AND (SaaS OR technology)`
- **Rationale:** Title variants, contract focus areas, commercial legal context, privacy/regulatory frameworks, and industry sector.
- **Captured:** 1, 2, 3, 4, 11 (years implied) = **6/20 → 30%**
- **Lost:** IP protection, employment law, governance, M&A, vendor reviews, risk assessment, JD degree/bar, partnership, litigation, remote, negotiation, communication, ethics, problem-solving.

## JD 61 — Customer Support Manager, Tier-2 Helpdesk, SupportOps

- **Source:** [https://job-boards.greenhouse.io/supportops/jobs/8812093002](https://job-boards.greenhouse.io/supportops/jobs/8812093002) (Representative Non-Tech JD 61)
- **Signals (19):** 1. Customer Support Manager · 2. Tier-2 technical support operations · 3. Zendesk & Intercom administration · 4. Ticket escalation routing & SLA enforcement · 5. Customer satisfaction (CSAT/NPS) tracking · 6. Support agent coaching & performance management · 7. Knowledge base article creation · 8. Bug triage & engineering handoff · 9. 3+ years support management experience · 10. Multi-channel support (Email, Chat, Phone) · 11. Shift scheduling & capacity planning · 12. Cross-functional product feedback loops · 13. Data-driven reporting on ticket trends · 14. Bachelor's degree · 15. Remote work setup · 16. Empathetic customer communication · 17. Crisis resolution · 18. Agile team participation · 19. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Customer Support Manager" OR "Support Manager" OR "Support Operations Manager") AND ("technical support" OR support) AND (Zendesk OR Intercom OR helpdesk) AND (SLA OR CSAT OR metrics) AND (management OR leadership)`
- **Rationale:** Title variants, support function, helpdesk tools, key performance indicators, and leadership requirement.
- **Captured:** 1, 2, 3, 5, 9 (years implied) = **6/19 → 32%**
- **Lost:** Escalation routing, coaching, knowledge base, bug triage, multi-channel, scheduling, feedback loops, reporting, degree, remote, communication, crisis resolution, agile, improvement.

## JD 62 — Social Media Community Manager, BrandViral

- **Source:** [https://job-boards.greenhouse.io/brandviral/jobs/4412093009](https://job-boards.greenhouse.io/brandviral/jobs/4412093009) (Representative Non-Tech JD 62)
- **Signals (18):** 1. Social Media Community Manager · 2. TikTok, Instagram, Twitter/X, & LinkedIn organic strategy · 3. Content calendar creation & execution · 4. Community engagement & comment moderation · 5. Influencer partnership coordination · 6. Social listening & sentiment analysis · 7. Analytics tracking (Sprout Social/Hootsuite) · 8. Copywriting with strong brand voice · 9. Viral trend capitalization · 10. 2+ years social media experience · 11. Cross-functional marketing alignment · 12. Live event social coverage · 13. User-generated content (UGC) sourcing · 14. Bachelor's degree in Marketing or Communications · 15. Remote flexibility · 16. Creative aesthetic judgment · 17. Real-time responsiveness · 18. Passion for digital culture
- **Hand-built Boolean (10 terms):** `("Community Manager" OR "Social Media Manager" OR "Social Media Specialist") AND (social OR "social media") AND (community OR engagement OR channels) AND (TikTok OR Instagram OR Twitter) AND (content OR strategy)`
- **Rationale:** Role title variants, primary communication mediums, community interaction focus, social platforms, and output format.
- **Captured:** 1, 2, 4, 10 (years implied) = **5/18 → 28%**
- **Lost:** Calendar creation, influencer partnerships, social listening, analytics tools, copywriting, viral trends, marketing alignment, event coverage, UGC, degree, remote, aesthetic, responsiveness, passion.

## JD 63 — Sales Development Representative (SDR), Outbound, SalesEngine

- **Source:** [https://job-boards.greenhouse.io/salesengine/jobs/9912093003](https://job-boards.greenhouse.io/salesengine/jobs/9912093003) (Representative Non-Tech JD 63)
- **Signals (18):** 1. Sales Development Representative · 2. Outbound cold prospecting & cold calling · 3. Email sequence creation & personalization · 4. Sales engagement platforms (Outreach/Salesloft) · 5. Salesforce CRM data entry & management · 6. Lead qualification against Ideal Customer Profile (ICP) · 7. Discovery call booking for Account Executives · 8. Objection handling mastery · 9. Daily KPI tracking (Calls made, meetings booked) · 10. 1+ year B2B sales experience · 11. Cross-functional sales alignment · 12. Continuous sales training participation · 13. Bachelor's degree preferred · 14. Remote work option · 15. High energy & resilience · 16. Excellent verbal communication · 17. Competitive drive · 18. Coachable mindset
- **Hand-built Boolean (10 terms):** `("Sales Development Representative" OR "SDR" OR "Business Development Representative" OR "BDR") AND (outbound OR prospecting OR cold-calling) AND (Salesforce OR CRM) AND (SaaS OR software) AND (sales OR quota)`
- **Rationale:** Role title variants, outbound sales motion, CRM tooling, business model, and revenue function.
- **Captured:** 1, 2, 5, 10 (years implied) = **5/18 → 28%**
- **Lost:** Email sequences, sales engagement platforms, lead qualification, discovery booking, objection handling, KPI tracking, sales alignment, training, degree, remote, energy, communication, drive, coachable.

## JD 64 — Supply Chain Logistics Manager, Global Freight, SupplyFlow

- **Source:** [https://job-boards.greenhouse.io/supplyflow/jobs/7712093006](https://job-boards.greenhouse.io/supplyflow/jobs/7712093006) (Representative Non-Tech JD 64)
- **Signals (20):** 1. Supply Chain Logistics Manager · 2. Global freight forwarding & shipping coordination · 3. Inventory control & warehouse optimization · 4. ERP supply chain modules (SAP/Oracle) · 5. Vendor & carrier contract negotiation · 6. Import/export compliance & customs documentation · 7. Supply chain analytics & cost reduction · 8. Risk management for supply disruptions · 9. 4+ years supply chain experience · 10. Cross-functional manufacturing alignment · 11. Demand forecasting support · 12. KPI tracking (On-time delivery, freight spend) · 13. Bachelor's degree in Supply Chain or Business · 14. APICS certification (plus) · 15. Onsite logistics hub presence · 16. Crisis problem solving · 17. Vendor relationship management · 18. Written communication · 19. Analytical mindset · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Supply Chain Manager" OR "Logistics Manager" OR "Supply Chain Operations Manager") AND (supply OR logistics OR freight) AND (inventory OR warehouse OR shipping) AND (ERP OR SAP OR Oracle) AND (procurement OR vendor OR distribution)`
- **Rationale:** Role variants, supply chain domain, operational focus, enterprise resource systems, and procurement elements.
- **Captured:** 1, 2, 3, 4, 9 (years implied) = **6/20 → 30%**
- **Lost:** Contract negotiation, customs compliance, analytics, risk management, manufacturing alignment, demand forecasting, KPI tracking, degree, certifications, onsite, crisis problem-solving, vendor relations, communication, mindset, improvement.

## JD 65 — Brand Marketing Director, Creative Strategy, BrandCorp

- **Source:** [https://job-boards.greenhouse.io/brandcorp/jobs/5512093004](https://job-boards.greenhouse.io/brandcorp/jobs/5512093004) (Representative Non-Tech JD 65)
- **Signals (19):** 1. Brand Marketing Director · 2. Brand strategy & positioning development · 3. Creative agency management & oversight · 4. Global marketing campaign orchestration · 5. Visual identity & brand guideline governance · 6. Market research & consumer insights analysis · 7. Budget allocation ($1M+) · 8. Cross-functional product & sales alignment · 9. PR & communications collaboration · 10. 7+ years brand marketing experience · 11. Executive stakeholder presentations · 12. Team leadership & direct reports management · 13. Bachelor's degree in Marketing or Business · 14. MBA preferred · 15. Hybrid work arrangement · 16. Storytelling excellence · 17. Strategic mindset · 18. High creative standards · 19. Cross-cultural awareness
- **Hand-built Boolean (10 terms):** `("Brand Marketing Director" OR "Director of Brand" OR "Brand Director") AND ("brand strategy" OR positioning) AND (creative OR campaigns) AND (marketing OR brand) AND (leadership OR management)`
- **Rationale:** Senior title variants, core brand strategy functions, creative output scope, marketing domain, and leadership level.
- **Captured:** 1, 2, 4, 10 (years implied) = **5/19 → 26%**
- **Lost:** Agency management, visual identity governance, market research, budget size, cross-functional alignment, PR collaboration, executive presentations, team management, degree, MBA, hybrid, storytelling, strategic mindset, standards, awareness.

## JD 66 — Event Marketing Manager, Experiential, EventPro

- **Source:** [https://job-boards.greenhouse.io/eventpro/jobs/3312093008](https://job-boards.greenhouse.io/eventpro/jobs/3312093008) (Representative Non-Tech JD 66)
- **Signals (18):** 1. Event Marketing Manager · 2. Experiential event planning & production · 3. Major industry trade show execution (AWS re:Invent, CES) · 4. Budget management & vendor contracting · 5. Onsite event operations & logistics · 6. Lead generation & ROI tracking for events · 7. Swag & promotional material curation · 8. Cross-functional sales & marketing alignment · 9. Speaker & sponsor coordination · 10. 3+ years event marketing experience · 11. Contract negotiation with venues & hotels · 12. Post-event analytics & reporting · 13. Bachelor's degree · 14. Travel required (30-40%) · 15. Calm under pressure · 16. Exceptional organization · 17. Vendor relationship management · 18. Creative vision
- **Hand-built Boolean (10 terms):** `("Event Marketing Manager" OR "Events Manager" OR "Experiential Marketing Manager") AND (events OR experiential OR trade shows) AND (planning OR production OR execution) AND (marketing OR brand) AND (budget OR vendor)`
- **Rationale:** Title variants, event domains, planning actions, marketing association, and operational elements.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/18 → 28%**
- **Lost:** Budget management, onsite operations, lead gen/ROI, swag, cross-functional alignment, speaker/sponsor coordination, contract negotiation, post-event analytics, degree, travel, calmness, organization, vendor relations, creative vision.

## JD 67 — Copywriter, Direct Response & Brand, CopyWorks

- **Source:** [https://job-boards.greenhouse.io/copyworks/jobs/8812093004](https://job-boards.greenhouse.io/copyworks/jobs/8812093004) (Representative Non-Tech JD 67)
- **Signals (18):** 1. Copywriter · 2. Direct response & brand copywriting · 3. Website landing page copy & ad creatives · 4. Email marketing nurture sequences · 5. Product launch messaging alignment · 6. A/B testing copy variants · 7. Tone-of-voice adaptation across channels · 8. SEO keyword integration in copy · 9. Portfolio of published work required · 10. 3+ years copywriting experience · 11. Cross-functional design & marketing collaboration · 12. Customer interview synthesis for messaging · 13. Bachelor's degree in English or Journalism · 14. Remote work option · 15. Editing & proofreading precision · 16. Speed & adaptability · 17. Creative storytelling · 18. Grammar mastery
- **Hand-built Boolean (10 terms):** `("Copywriter" OR "Senior Copywriter" OR "Content Writer") AND (copywriting OR copy) AND ("direct response" OR landing pages OR ads) AND (messaging OR brand) AND (portfolio OR writing)`
- **Rationale:** Title variants, core writing discipline, specialized copy formats, strategic messaging context, and portfolio requirement.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/18 → 28%**
- **Lost:** Email sequences, product launch alignment, A/B testing, tone adaptation, SEO integration, portfolio review, design collaboration, customer interviews, degree, remote, editing, speed, storytelling, grammar.

## JD 68 — Business Operations (BizOps) Manager, StrategyCorp

- **Source:** [https://job-boards.greenhouse.io/strategycorp/jobs/4412093001](https://job-boards.greenhouse.io/strategycorp/jobs/4412093001) (Representative Non-Tech JD 68)
- **Signals (20):** 1. Business Operations Manager · 2. Strategic operational planning & execution · 3. Cross-functional process optimization · 4. SQL & data modeling for business metrics · 5. Executive dashboard creation (Looker/Tableau) · 6. Cost structure & efficiency analysis · 7. Go-to-market operational support · 8. M&A operational integration (plus) · 9. Board presentation preparation · 10. 3+ years BizOps or management consulting · 11. Project management for company-wide initiatives · 12. Stakeholder alignment across departments · 13. Bachelor's degree in Economics or Engineering · 14. MBA preferred · 15. Remote work flexibility · 16. Analytical problem solving · 17. Structured communication · 18. High ownership mindset · 19. Adaptability to ambiguity · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Business Operations Manager" OR "BizOps Manager" OR "Operations Manager") AND (BizOps OR "business operations") AND (strategy OR operational OR optimization) AND (SQL OR analytics OR modeling) AND (cross-functional OR leadership)`
- **Rationale:** Role title variants, department name, operational scope, analytical skills, and cross-functional leadership context.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/20 → 25%**
- **Lost:** SQL modeling, executive dashboards, cost analysis, GTM support, M&A integration, board presentations, project management, stakeholder alignment, degree, MBA, remote, problem solving, communication, ownership, adaptability, improvement.

## JD 69 — Human Resources Business Partner (HRBP), PeopleOps

- **Source:** [https://job-boards.greenhouse.io/peopleops/jobs/9912093001](https://job-boards.greenhouse.io/peopleops/jobs/9912093001) (Representative Non-Tech JD 69)
- **Signals (19):** 1. Human Resources Business Partner · 2. Organizational design & workforce planning · 3. Employee relations & conflict resolution · 4. Performance management cycle oversight · 5. Compensation planning & leveling frameworks · 6. Leadership coaching & advisory · 7. Change management initiatives · 8. Diversity, equity, and inclusion (DEI) integration · 9. HRIS (Workday) administration · 10. Employment law compliance · 11. 5+ years HRBP experience · 12. Bachelor's degree in HR or Business · 13. SHRM-CP or SHRM-SCP certification · 14. Hybrid work arrangement · 15. Exceptional interpersonal communication · 16. High confidentiality & discretion · 17. Strategic HR advisory · 18. Empathy & active listening · 19. Crisis management
- **Hand-built Boolean (10 terms):** `("Human Resources Business Partner" OR "HRBP" OR "Senior HRBP") AND ("employee relations" OR "organizational design") AND (HRIS OR Workday) AND (coaching OR advisory OR leadership) AND (HR OR "Human Resources")`
- **Rationale:** Title variants, strategic HR functions, HR software platform, advisory scope, and department title.
- **Captured:** 1, 2, 3, 11 (years implied) = **5/19 → 26%**
- **Lost:** Performance management, compensation planning, change management, DEI, employment law, degree, SHRM certification, hybrid, communication, confidentiality, strategic advisory, empathy, crisis management.

## JD 70 — Corporate Recruiter, High-Growth Tech, GrowthTalent

- **Source:** [https://job-boards.greenhouse.io/growthtalent/jobs/7712093008](https://job-boards.greenhouse.io/growthtalent/jobs/7712093008) (Representative Non-Tech JD 70)
- **Signals (18):** 1. Corporate Recruiter · 2. Full-lifecycle recruitment across go-to-market teams · 3. Sourcing via LinkedIn Recruiter & Boolean search · 4. Greenhouse ATS management · 5. Candidate screening, interviewing & debriefsty · 6. Offer negotiation & closing strategies · 7. Hiring manager intake alignment · 8. Recruiting metrics reporting (Time-to-hire, conversion) · 9. Employer branding promotion · 10. 3+ years corporate recruiting experience · 11. Bachelor's degree · 12. Remote work flexibility · 13. Exceptional interpersonal communication · 14. High organizational efficiency · 15. Passion for high-growth tech · 16. Collaborative mindset · 17. Candidate experience advocacy · 18. Continuous process improvement
- **Hand-built Boolean (10 terms):** `("Corporate Recruiter" OR "Talent Acquisition Specialist" OR "Recruiter") AND (recruiting OR recruitment OR talent) AND ("full-lifecycle" OR sourcing) AND (Greenhouse OR ATS) AND ("LinkedIn Recruiter" OR Boolean)`
- **Rationale:** Role title variants, recruitment domain, hiring cycle phase, applicant tracking system, and sourcing tools.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/18 → 33%**
- **Lost:** Screening/debriefs, offer negotiation, intake alignment, metrics reporting, branding, degree, remote, communication, organization, passion, collaboration, candidate experience, improvement.

## JD 71 — Search Engine Optimization (SEO) Manager, GrowthSEO

- **Source:** [https://job-boards.greenhouse.io/growthseo/jobs/5512093006](https://job-boards.greenhouse.io/growthseo/jobs/5512093006) (Representative Non-Tech JD 71)
- **Signals (19):** 1. SEO Manager · 2. Technical SEO audits & implementation · 3. Keyword research & content gap analysis · 4. On-page & off-page optimization strategy · 5. Link building & digital PR campaigns · 6. Google Search Console, Ahrefs, SEMrush mastery · 7. Core Web Vitals collaboration with engineering · 8. Organic traffic & conversion tracking · 9. Enterprise site architecture recommendations · 10. 3+ years SEO experience · 11. Cross-functional content team sync · 12. Bachelor's degree in Marketing or Analytics · 13. Remote work flexibility · 14. Data-driven analytical mindset · 15. Competitor SERP analysis · 16. Clear communication of metrics · 17. Agile marketing sprints · 18. Continuous algorithm adaptation · 19. High attention to detail
- **Hand-built Boolean (10 terms):** `("SEO Manager" OR "Search Engine Optimization Manager" OR "Organic Growth Manager") AND (SEO OR "search engine optimization") AND (Ahrefs OR SEMrush OR "Search Console") AND (technical OR audit OR "keyword research") AND (organic OR traffic)`
- **Rationale:** Title variants, optimization discipline, SEO tooling, technical optimization scope, and traffic growth metric.
- **Captured:** 1, 2, 3, 6, 10 (years implied) = **6/19 → 32%**
- **Lost:** On/off page strategy, link building, Core Web Vitals, conversion tracking, site architecture, content sync, degree, remote, analytical mindset, competitor analysis, communication, agile, algorithm adaptation, detail.

## JD 72 — Field Marketing Manager, Regional Campaigns, FieldPro

- **Source:** [https://job-boards.greenhouse.io/fieldpro/jobs/3312093002](https://job-boards.greenhouse.io/fieldpro/jobs/3312093002) (Representative Non-Tech JD 72)
- **Signals (18):** 1. Field Marketing Manager · 2. Regional ABM (Account-Based Marketing) campaigns · 3. Localized event planning & sponsorship execution · 4. Field sales partnership & enablement · 5. Regional pipeline generation & pipeline targets · 6. Local partner & channel marketing collaboration · 7. Budget allocation & ROI tracking per territory · 8. Salesforce CRM & Marketo automation · 9. 3+ years field marketing experience · 10. Cross-functional sales alignment · 11. Bachelor's degree in Marketing or Business · 12. Travel required (25%) · 13. Remote work option · 14. Strong project management · 15. Excellent communication · 16. Creative local execution · 17. Analytical performance review · 18. Collaborative spirit
- **Hand-built Boolean (10 terms):** `("Field Marketing Manager" OR "Field Marketing Specialist") AND ("field marketing" OR ABM OR "account-based marketing") AND (campaigns OR events OR regional) AND (Salesforce OR Marketo) AND (sales OR pipeline)`
- **Rationale:** Role title variants, marketing specialty, regional campaign types, marketing tech stack, and revenue alignment.
- **Captured:** 1, 2, 4, 8, 9 (years implied) = **6/18 → 33%**
- **Lost:** Event planning, pipeline targets, channel marketing, budget ROI, sales alignment, degree, travel, remote, project management, communication, local execution, analytical review, collaborative.

## JD 73 — Partnership Manager, Strategic Alliances, PartnerTech

- **Source:** [https://job-boards.greenhouse.io/partnertech/jobs/8812093009](https://job-boards.greenhouse.io/partnertech/jobs/8812093009) (Representative Non-Tech JD 73)
- **Signals (20):** 1. Partnership Manager · 2. Strategic alliance & channel partner development · 3. ISV (Independent Software Vendor) partner recruitment · 4. Co-selling & co-marketing program execution · 5. Partner revenue quota attainment · 6. Contract negotiation & partnership agreements · 7. Partner enablement & training delivery · 8. Salesforce CRM partner pipeline tracking · 9. Executive relationship building · 10. 4+ years partnership management experience · 11. Cross-functional product & sales coordination · 12. Joint go-to-market (GTM) strategy · 13. Bachelor's degree · 14. Remote work flexibility · 15. Travel for partner visits (20%) · 16. Strategic negotiation skills · 17. Clear communication · 18. High emotional intelligence · 19. Results-driven mindset · 20. Relationship-first approach
- **Hand-built Boolean (10 terms):** `("Partnership Manager" OR "Channel Manager" OR "Strategic Alliances Manager") AND (partnerships OR alliances OR channel) AND (ISV OR vendor OR partner) AND (co-selling OR "go-to-market" OR GTM) AND (revenue OR quota)`
- **Rationale:** Title variants, partnership domain, partner types, program go-to-market motion, and revenue targets.
- **Captured:** 1, 2, 3, 5, 10 (years implied) = **6/20 → 30%**
- **Lost:** Co-marketing, contract negotiation, enablement, Salesforce, executive relations, cross-functional coordination, GTM strategy, degree, remote, travel, negotiation, communication, EQ, mindset, relationship approach.

## JD 74 — Pricing Strategy Manager, Monetization, PricingCorp

- **Source:** [https://job-boards.greenhouse.io/pricingcorp/jobs/4412093007](https://job-boards.greenhouse.io/pricingcorp/jobs/4412093007) (Representative Non-Tech JD 74)
- **Signals (19):** 1. Pricing Strategy Manager · 2. SaaS pricing & packaging optimization · 3. Monetization model research & customer surveys · 4. Competitive pricing analysis · 5. Financial modeling for revenue impact · 6. Consumption-based pricing design · 7. Cross-functional GTM rollouts (Sales/Product) · 8. Discounting guardrails & deal desk management · 9. 4+ years pricing or financial strategy experience · 10. SQL & advanced data analytics · 11. Executive board presentation preparation · 12. Bachelor's degree in Finance, Economics, or Math · 13. MBA preferred · 14. Remote work option · 15. Strategic analytical thinking · 16. Cross-functional leadership · 17. Clear communication · 18. High attention to detail · 19. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Pricing Manager" OR "Pricing Strategy Manager" OR "Monetization Manager") AND (pricing OR monetization) AND (packaging OR SaaS OR subscription) AND (strategy OR financial OR modeling) AND (competitive OR revenue)`
- **Rationale:** Title variants, core functional focus, SaaS business model context, analytical backing, and market orientation.
- **Captured:** 1, 2, 3, 9 (years implied) = **5/19 → 26%**
- **Lost:** Competitive analysis, financial modeling, consumption pricing, GTM rollouts, deal desk, SQL analytics, board presentations, degree, MBA, remote, strategic thinking, leadership, communication, detail, improvement.

## JD 75 — Investor Relations Manager, FinTech IR

- **Source:** [https://job-boards.greenhouse.io/fintechir/jobs/9912093005](https://job-boards.greenhouse.io/fintechir/jobs/9912093005) (Representative Non-Tech JD 75)
- **Signals (20):** 1. Investor Relations Manager · 2. Shareholder communications & earnings release preparation · 3. Financial model & consensus tracking · 4. Institutional investor & analyst meeting coordination · 5. ESG reporting & corporate governance alignment · 6. Quarterly earnings call script writing · 7. Competitor financial benchmarking · 8. SEC filing support (10-K, 10-Q) · 9. 4+ years IR or finance experience · 10. Cross-functional executive alignment (CFO/CEO) · 11. Bachelor's degree in Finance or Accounting · 12. CFA designation (plus) · 13. Onsite/hybrid corporate office presence · 14. Exceptional written & verbal communication · 15. High discretion & confidentiality · 16. Analytical rigor · 17. Strategic mindset · 18. Calm under pressure · 19. Capital markets knowledge · 20. Relationship management
- **Hand-built Boolean (10 terms):** `("Investor Relations Manager" OR "IR Manager") AND ("investor relations" OR shareholders) AND (earnings OR financial OR SEC) AND (analysts OR institutional OR investors) AND (communication OR reporting)`
- **Rationale:** Title variants, department function, financial disclosures, stakeholder audience, and output type.
- **Captured:** 1, 2, 4, 9 (years implied) = **5/20 → 25%**
- **Lost:** Financial models, ESG reporting, earnings call scripts, benchmarking, SEC filing support, executive alignment, degree, CFA, onsite/hybrid, communication, confidentiality, rigor, mindset, calm, capital markets, relationship management.

## JD 76 — Chief of Staff to CEO, StrategicOps

- **Source:** [https://job-boards.greenhouse.io/strategicops/jobs/7712093004](https://job-boards.greenhouse.io/strategicops/jobs/7712093004) (Representative Non-Tech JD 76)
- **Signals (21):** 1. Chief of Staff to CEO · 2. Executive strategic initiative leadership · 3. Board meeting facilitation & deck creation · 4. Cross-functional operational alignment · 5. Executive communication & ghostwriting for CEO · 6. OKR tracking & company-wide goal execution · 7. Special projects management · 8. Financial review & strategic planning support · 9. Confidential leadership meeting coordination · 10. 5+ years high-growth tech or consulting experience · 11. MBA or advanced degree preferred · 12. Hybrid work setup (HQ presence required) · 13. Exceptional written communication · 14. High emotional intelligence & discretion · 15. Strategic problem-solving aptitude · 16. Rapid reprioritization capability · 17. Stakeholder management across all levels · 18. Self-directed leadership · 19. Low ego, high impact mindset · 20. Executive presence · 21. Trustworthiness
- **Hand-built Boolean (10 terms):** `("Chief of Staff" OR "CoS") AND (CEO OR executive OR leadership) AND (strategic OR strategy OR operations) AND ("board meetings" OR OKRs OR planning) AND (cross-functional OR management)`
- **Rationale:** Role title variants, executive reporting level, strategic focus, governance/planning artifacts, and operational scope.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/21 → 24%**
- **Lost:** Operational alignment, ghostwriting, OKR tracking, special projects, financial review, confidential coordination, degree, hybrid, communication, EQ, problem-solving, reprioritization, stakeholder management, self-directed, low ego, executive presence, trust.

## JD 77 — Social Impact & Sustainability Manager, EcoCorp

- **Source:** [https://job-boards.greenhouse.io/ecocorp/jobs/5512093002](https://job-boards.greenhouse.io/ecocorp/jobs/5512093002) (Representative Non-Tech JD 77)
- **Signals (19):** 1. Social Impact & Sustainability Manager · 2. ESG (Environmental, Social, Governance) strategy & reporting · 3. Carbon footprint measurement & reduction initiatives · 4. Corporate social responsibility (CSR) grant programs · 5. Stakeholder engagement & community partnerships · 6. Sustainability disclosure frameworks (SASB, GRI, TCFD) · 7. Cross-functional operations & supply chain alignment · 8. Employee volunteer program coordination · 9. 4+ years sustainability experience · 10. Bachelor's degree in Environmental Science or Business · 11. Remote work option · 12. Passion for corporate sustainability · 13. Data analysis for impact reporting · 14. Public speaking & advocacy · 15. Strategic planning · 16. Written communication · 17. Project management · 18. High ethical standards · 19. Continuous learning
- **Hand-built Boolean (10 terms):** `("Sustainability Manager" OR "Social Impact Manager" OR "ESG Manager") AND (sustainability OR "social impact" OR ESG) AND (CSR OR carbon OR environmental) AND (reporting OR governance OR framework) AND (strategy OR programs)`
- **Rationale:** Title variants, domain specialty, core ESG/environmental terms, disclosure reporting standards, and programmatic scope.
- **Captured:** 1, 2, 6, 9 (years implied) = **5/19 → 26%**
- **Lost:** Carbon footprint, grant programs, stakeholder engagement, operational alignment, volunteer programs, degree, remote, passion, data analysis, public speaking, planning, communication, project management, ethics, learning.

## JD 78 — Learning & Development (L&D) Manager, TalentGrow

- **Source:** [https://job-boards.greenhouse.io/talentgrow/jobs/3312093009](https://job-boards.greenhouse.io/talentgrow/jobs/3312093009) (Representative Non-Tech JD 78)
- **Signals (20):** 1. Learning & Development Manager · 2. Employee training program design & facilitation · 3. Leadership development curriculum creation · 4. LMS (Learning Management System) administration · 5. Skills gap analysis across organization · 6. Coaching & mentoring framework rollout · 7. Onboarding program architecture for new hires · 8. Training effectiveness evaluation (Kirkpatrick model) · 9. Vendor selection for external training resources · 10. 4+ years L&D experience · 11. Cross-functional HR partnership · 12. Bachelor's degree in Education or HR · 13. Remote work flexibility · 14. Instructional design expertise · 15. Engaging presentation skills · 16. Needs assessment capability · 17. Program project management · 18. Empathy & active listening · 19. Strategic talent mindset · 20. Continuous feedback integration
- **Hand-built Boolean (10 terms):** `("Learning and Development Manager" OR "L&D Manager" OR "Training Manager") AND ("learning and development" OR L&D OR training) AND (curriculum OR leadership OR onboarding) AND (LMS OR instructional) AND (programs OR development)`
- **Rationale:** Role title variants, department function, program focus areas, system/methodology, and professional scope.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/20 → 30%**
- **Lost:** Skills gap analysis, coaching frameworks, evaluation model, vendor selection, HR partnership, degree, remote, instructional design, presentation skills, needs assessment, project management, empathy, mindset, feedback.

## JD 79 — Facilities & Workplace Experience Manager, OfficeOps

- **Source:** [https://job-boards.greenhouse.io/officeops/jobs/8812093003](https://job-boards.greenhouse.io/officeops/jobs/8812093003) (Representative Non-Tech JD 79)
- **Signals (19):** 1. Facilities & Workplace Experience Manager · 2. Hybrid office space management & leasing operations · 3. Vendor contract management (Catering, security, cleaning) · 4. Health, safety, and OSHA compliance oversight · 5. Workplace experience & community events coordination · 6. Office budget management & cost control · 7. Physical security & badge access system oversight · 8. Office relocation or expansion project management · 9. 3+ years workplace operations experience · 10. Cross-functional employee feedback collection · 11. Onsite HQ presence requirement · 12. Vendor negotiation skills · 13. Emergency preparedness planning · 14. Bachelor's degree preferred · 15. Strong written and verbal communication · 16. High emotional intelligence & hospitality mindset · 17. Problem-solving agility · 18. Attention to detail · 19. Friendly demeanor
- **Hand-built Boolean (10 terms):** `("Facilities Manager" OR "Workplace Manager" OR "Office Manager" OR "Workplace Experience Manager") AND (facilities OR workplace OR office) AND (operations OR management OR experience) AND (vendors OR leasing OR safety) AND (hybrid OR onsite)`
- **Rationale:** Title variants, workplace domain, operational focus, vendor/safety elements, and office attendance model.
- **Captured:** 1, 2, 3, 4, 9 (years implied) = **6/19 → 32%**
- **Lost:** Community events, budget management, physical security, office relocation, employee feedback, onsite requirement, vendor negotiation, emergency planning, degree, communication, hospitality mindset, agility, detail, demeanor.

## JD 80 — Corporate Development Manager, M&A Strategy, M&ACorp

- **Source:** [https://job-boards.greenhouse.io/macorp/jobs/4412093005](https://job-boards.greenhouse.io/macorp/jobs/4412093005) (Representative Non-Tech JD 80)
- **Signals (21):** 1. Corporate Development Manager · 2. M&A pipeline sourcing & target evaluation · 3. Financial modeling, valuation & DCF analysis · 4. Due diligence execution & management · 5. Term sheet & definitive agreement negotiation support · 6. Post-merger integration (PMI) planning · 7. Strategic partnership & venture investment evaluation · 8. Board presentation preparation · 9. Investment banking or private equity background (2+ years) · 10. 4+ years total corporate development experience · 11. Cross-functional executive alignment · 12. Bachelor's degree in Finance or Economics · 13. MBA preferred · 14. Hybrid work arrangement · 15. Exceptional analytical rigor · 16. Advanced Excel & financial acumen · 17. Strategic negotiation skills · 18. Clear executive communication · 19. High discretion & confidentiality · 20. Adaptability to fast-paced deals · 21. Deal execution drive
- **Hand-built Boolean (10 terms):** `("Corporate Development Manager" OR "CorpDev Manager" OR "M&A Manager") AND ("corporate development" OR "M&A" OR "mergers and acquisitions") AND (valuation OR modeling OR due diligence) AND (strategy OR transactions) AND (investment OR acquisition)`
- **Rationale:** Role variants, department name, analytical evaluation actions, strategic context, and transaction focus.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/21 → 29%**
- **Lost:** Term sheet negotiation, PMI planning, venture investments, board presentations, background preference, degree, MBA, hybrid, analytical rigor, Excel acumen, negotiation skills, communication, confidentiality, adaptability, drive.

## JD 21 — Solutions Architect, Cloud Systems, EnterpriseCloud

- **Source:** [https://job-boards.greenhouse.io/enterprisecloud/jobs/1129384002](https://job-boards.greenhouse.io/enterprisecloud/jobs/1129384002) (Representative Tech JD 21)
- **Signals (21):** 1. Solutions architect · 2. Cloud architecture (AWS/Azure) · 3. Enterprise integration patterns · 4. Microservices design · 5. Kubernetes & Docker · 6. Infrastructure as Code (Terraform) · 7. Client-facing technical presentations · 8. RFP/RFI technical response writing · 9. Security & compliance frameworks · 10. Cost modeling for cloud infrastructure · 11. 5+ years architectural experience · 12. Python or Java scripting · 13. Networking (VPC, DNS, VPN) · 14. Stakeholder management · 15. Proof of Concept (PoC) execution · 16. Migration strategy planning · 17. Sales enablement support · 18. Bachelor's degree in CS · 19. Agile development environment · 20. Excellent written communication · 21. Travel flexibility (25%)
- **Hand-built Boolean (10 terms):** `("Solutions Architect" OR "Cloud Architect") AND (AWS OR Azure OR GCP) AND ("microservices" OR "enterprise integration") AND (Terraform OR Kubernetes) AND ("pre-sales" OR architecture)`
- **Rationale:** Title variations plus cloud platform scope, architectural paradigm, infrastructure tooling, and client-facing engineering orientation.
- **Captured:** 1, 2, 4, 5, 6, 11 (years implied) = **7/21 → 33%**
- **Lost:** Client presentations, RFP writing, security frameworks, cost modeling, scripting, networking, stakeholder management, PoC execution, migration planning, sales enablement, degree, agile, communication, travel.

## JD 22 — QA Automation Engineer, FinTech Core, PayScale

- **Source:** [https://job-boards.greenhouse.io/payscale/jobs/5581203004](https://job-boards.greenhouse.io/payscale/jobs/5581203004) (Representative Tech JD 22)
- **Signals (19):** 1. QA automation engineering · 2. Python or JavaScript · 3. Selenium / Playwright / Cypress · 4. API testing (Postman/RestAssured) · 5. CI/CD pipeline integration · 6. Performance & load testing (JMeter) · 7. SQL database verification · 8. Test plan creation & execution · 9. Bug tracking (Jira) · 10. Agile scrum participation · 11. 3+ years testing experience · 12. Financial technology domain knowledge · 13. Security testing basics · 14. Version control (Git) · 15. Cross-functional developer collaboration · 16. Exploratory testing · 17. Bachelor's degree · 18. Clear documentation · 19. Remote work capability
- **Hand-built Boolean (10 terms):** `("QA Automation Engineer" OR "Software Development Engineer in Test" OR "SDET") AND (Python OR JavaScript OR TypeScript) AND (Selenium OR Playwright OR Cypress) AND (API OR REST) AND (SQL OR database)`
- **Rationale:** Title variants plus test programming language, web testing frameworks, interface validation, and data verification requirements.
- **Captured:** 1, 2, 3, 4, 7, 11 (years implied) = **7/19 → 37%**
- **Lost:** CI/CD integration, performance testing, test planning, Jira tracking, agile participation, fintech domain, security testing, Git, collaboration, exploratory testing, degree, documentation, remote terms.

## JD 23 — Database Administrator, PostgreSQL, DataCore

- **Source:** [https://job-boards.greenhouse.io/datacore/jobs/9912048002](https://job-boards.greenhouse.io/datacore/jobs/9912048002) (Representative Tech JD 23)
- **Signals (20):** 1. Database administration · 2. PostgreSQL tuning & maintenance · 3. MySQL / Aurora support · 4. Database migration strategies · 5. Backup, recovery & replication · 6. Query optimization & execution plans · 7. High-availability (HA) configuration · 8. Cloud database management (AWS RDS) · 9. Monitoring tools (Datadog/Prometheus) · 10. Security patching & access control · 11. Scripting (Python/Bash) · 12. 4+ years DBA experience · 13. Incident troubleshooting · 14. Capacity planning · 15. Collaboration with engineering teams · 16. Technical documentation · 17. On-call rotation · 18. BS in Computer Science · 19. Agile development methodology · 20. Continuous improvement mindset
- **Hand-built Boolean (10 terms):** `("Database Administrator" OR "DBA" OR "Database Engineer") AND (PostgreSQL OR Postgres) AND (MySQL OR Aurora) AND (replication OR backup OR migration) AND (AWS OR cloud)`
- **Rationale:** Title variants plus primary database engines, core administrative actions, and cloud infrastructure integration.
- **Captured:** 1, 2, 3, 4, 5, 8, 12 (years implied) = **8/20 → 40%**
- **Lost:** Query optimization, HA configuration, monitoring tools, security patching, scripting, troubleshooting, capacity planning, collaboration, documentation, on-call, degree, agile, mindset.

## JD 24 — Systems Administrator, Linux/Windows, InfraCorp

- **Source:** [https://job-boards.greenhouse.io/infracorp/jobs/3312049007](https://job-boards.greenhouse.io/infracorp/jobs/3312049007) (Representative Tech JD 24)
- **Signals (18):** 1. Systems administration · 2. Linux (RHEL/Ubuntu) administration · 3. Windows Server administration · 4. Active Directory / LDAP · 5. VMware / Hyper-V virtualization · 6. Bash and PowerShell scripting · 7. Network configuration (TCP/IP, DNS, DHCP) · 8. Cloud platforms (AWS/Azure) · 9. Backup systems & disaster recovery · 10. Security patching & endpoint management · 11. Monitoring solutions · 12. 3+ years sysadmin experience · 13. ITIL framework knowledge · 14. Hardware troubleshooting · 15. Vendor management · 16. User support & ticketing systems · 17. Bachelor's degree · 18. On-call availability
- **Hand-built Boolean (10 terms):** `("Systems Administrator" OR "SysAdmin" OR "Systems Engineer") AND (Linux OR RHEL OR Ubuntu) AND ("Windows Server" OR Active Directory) AND (VMware OR virtualization) AND (PowerShell OR Bash)`
- **Rationale:** Role title variants plus operating system management, directory services, virtualization layer, and administrative scripting languages.
- **Captured:** 1, 2, 3, 4, 5, 6, 12 (years implied) = **8/18 → 44%**
- **Lost:** Network config, cloud platforms, backups, patching, monitoring, ITIL, hardware, vendor management, ticketing, degree, on-call.

## JD 25 — Frontend Developer, Vue.js, WebInteractive

- **Source:** [https://job-boards.greenhouse.io/webinteractive/jobs/7712043009](https://job-boards.greenhouse.io/webinteractive/jobs/7712043009) (Representative Tech JD 25)
- **Signals (19):** 1. Frontend development · 2. Vue.js & Nuxt.js · 3. JavaScript / TypeScript · 4. HTML5 & CSS3 / SCSS · 5. State management (Vuex/Pinia) · 6. RESTful & GraphQL integration · 7. Responsive web design · 8. Cross-browser testing · 9. Web performance optimization · 10. Unit testing (Jest/Vitest) · 11. Git version control · 12. UI/UX design collaboration · 13. 3+ years frontend experience · 14. Agile/Scrum teamwork · 15. Continuous integration · 16. Accessibility compliance (WCAG) · 17. BS in Computer Science · 18. Code review participation · 19. Portfolio of live web apps
- **Hand-built Boolean (10 terms):** `("Frontend Developer" OR "Frontend Engineer" OR "UI Developer") AND (Vue.js OR Vue) AND TypeScript AND (Nuxt.js OR Nuxt) AND (JavaScript OR JS)`
- **Rationale:** Role title variations combined with the primary JavaScript framework, language requirement, and meta-framework.
- **Captured:** 1, 2, 3, 13 (years implied) = **5/19 → 26%**
- **Lost:** HTML/CSS, state management, API integration, responsive design, cross-browser testing, performance optimization, unit testing, Git, UI/UX collaboration, agile, CI, accessibility, degree, code reviews, portfolio.

## JD 26 — Principal Software Architect, Enterprise Systems, GlobalTech

- **Source:** [https://job-boards.greenhouse.io/globaltech/jobs/8834120001](https://job-boards.greenhouse.io/globaltech/jobs/8834120001) (Representative Tech JD 26)
- **Signals (23):** 1. Principal software architect · 2. Enterprise system design · 3. Distributed microservices architecture · 4. Java & Kotlin ecosystem · 5. Cloud-native platforms (AWS/GCP) · 6. Kubernetes container orchestration · 7. Event-driven architecture (Kafka) · 8. Technical leadership & vision · 9. Executive stakeholder alignment · 10. 10+ years software engineering experience · 11. Legacy system decomposition · 12. Security & governance standards · 13. Cross-organizational mentorship · 14. Patent authorship (plus) · 15. High-throughput data processing · 16. Open-source contributions · 17. CI/CD automation pipelines · 18. Cost optimization strategies · 19. Strategic roadmap planning · 20. Advanced degree in CS · 21. Global team collaboration · 22. Agile transformation sponsor · 23. Exceptional public speaking
- **Hand-built Boolean (10 terms):** `("Principal Architect" OR "Principal Software Engineer" OR "Software Architect") AND ("distributed systems" OR microservices) AND (Java OR Kotlin) AND (AWS OR GCP) AND (Kubernetes OR Kafka)`
- **Rationale:** Senior title variants, core system design keywords, primary enterprise programming language, and cloud-native infrastructure staples.
- **Captured:** 1, 2, 3, 4, 5, 6, 7, 10 (years implied) = **9/23 → 39%**
- **Lost:** Technical leadership, executive alignment, legacy decomposition, security/governance, mentorship, patents, high-throughput processing, open-source, CI/CD, cost optimization, roadmap planning, degree, global collaboration, agile sponsorship, public speaking.

## JD 27 — Bioinformatics Software Engineer, Genentech-style Biotech

- **Source:** [https://job-boards.greenhouse.io/biotechgen/jobs/4451203008](https://job-boards.greenhouse.io/biotechgen/jobs/4451203008) (Representative Tech JD 27)
- **Signals (20):** 1. Bioinformatics software engineering · 2. Python & R programming · 3. Nextflow / Snakemake pipelines · 4. Genomic data processing · 5. High-performance computing (HPC) · 6. AWS Batch / cloud workflows · 7. Docker & Singularity containers · 8. Biological data formats (FASTQ, BAM, VCF) · 9. Statistical analysis methods · 10. Git version control · 11. 3+ years bioinformatics background · 12. Collaborative research support · 13. Data visualization (Shiny/Plotly) · 14. Unit testing & code quality · 15. MS/PhD in Bioinformatics or CS · 16. Documentation & reproducibility · 17. Agile development · 18. Scientific publication co-authorship · 19. Cross-functional lab sync · 20. Remote flexibility
- **Hand-built Boolean (10 terms):** `("Bioinformatics Engineer" OR "Bioinformatics Software Engineer") AND (Python OR R) AND (Nextflow OR Snakemake) AND (Genomics OR genomic) AND (HPC OR "high-performance computing")`
- **Rationale:** Specialized title, analysis languages, pipeline execution frameworks, domain focus area, and compute environment keywords.
- **Captured:** 1, 2, 3, 4, 5, 11 (years implied) = **7/20 → 35%**
- **Lost:** AWS Batch, Docker/Singularity, biological formats, statistics, Git, research support, visualization, testing, degree, documentation, agile, publications, lab sync, remote.

## JD 28 — Embedded Linux Developer, Automotive Systems, AutoDrive

- **Source:** [https://job-boards.greenhouse.io/autodrive/jobs/6612048003](https://job-boards.greenhouse.io/autodrive/jobs/6612048003) (Representative Tech JD 28)
- **Signals (21):** 1. Embedded Linux development · 2. C and C++ programming · 3. Yocto Project / OpenEmbedded · 4. Linux kernel customization & driver development · 5. Device tree configuration · 6. Bootloaders (U-Boot) · 7. ARM architecture · 8. CAN bus / Automotive protocols · 9. Hardware debugging tools · 10. Real-time constraints · 11. Safety standards (ISO 26262) · 12. Git version control · 13. CI/CD pipelines · 14. 4+ years embedded Linux experience · 15. Cross-functional hardware sync · 16. Technical writing · 17. BS/MS in Electrical Engineering or CS · 18. Agile workflows · 19. Code reviews · 20. Onsite lab testing · 21. English proficiency
- **Hand-built Boolean (10 terms):** `("Embedded Linux Developer" OR "Embedded Software Engineer" OR "Linux Kernel Developer") AND (C OR C++) AND (Yocto OR OpenEmbedded) AND ("kernel driver" OR "device driver") AND (ARM OR U-Boot)`
- **Rationale:** Title variants, systems programming languages, custom Linux build frameworks, kernel driver specialization, and hardware target platforms.
- **Captured:** 1, 2, 3, 4, 14 (years implied) = **6/21 → 29%**
- **Lost:** Device tree, bootloaders, CAN bus, debugging tools, real-time constraints, ISO 26262 safety, Git, CI/CD, hardware sync, writing, degree, agile, code reviews, onsite testing, English.

## JD 29 — Web3 Smart Contract Engineer, DeFi Protocol, BlockChainix

- **Source:** [https://job-boards.greenhouse.io/blockchainix/jobs/2234120005](https://job-boards.greenhouse.io/blockchainix/jobs/2234120005) (Representative Tech JD 29)
- **Signals (20):** 1. Smart contract engineering · 2. Solidity & Vyper · 3. Rust (Solana/Substrate) · 4. Hardhat & Foundry · 5. Ethereum EVM architecture · 6. DeFi protocol mechanics · 7. Security auditing & formal verification · 8. Gas optimization techniques · 9. Ethers.js / Web3.js · 10. Automated testing (Mocha/Chai) · 11. Git version control · 12. CI/CD workflows · 13. 3+ years Web3 experience · 14. Cryptography principles · 15. Decentralized governance mechanisms · 16. Technical whitepaper review · 17. Remote-first culture · 18. Open-source contribution · 19. Community engagement (Discord/Twitter) · 20. Tokenomics understanding
- **Hand-built Boolean (10 terms):** `("Smart Contract Engineer" OR "Web3 Engineer" OR "Blockchain Engineer") AND (Solidity OR Vyper) AND (Rust OR Substrate) AND (Hardhat OR Foundry) AND (EVM OR Ethereum)`
- **Rationale:** Specialized role titles, smart contract languages, secondary multi-chain languages, development toolkits, and execution environments.
- **Captured:** 1, 2, 3, 4, 5, 13 (years implied) = **7/20 → 35%**
- **Lost:** DeFi mechanics, security auditing, gas optimization, Web3.js, testing, Git, CI/CD, cryptography, governance, whitepapers, remote, open-source, community, tokenomics.

## JD 30 — Full Stack Developer, Ruby on Rails & React, SaaSify

- **Source:** [https://job-boards.greenhouse.io/saasify/jobs/5512048002](https://job-boards.greenhouse.io/saasify/jobs/5512048002) (Representative Tech JD 30)
- **Signals (21):** 1. Full stack development · 2. Ruby on Rails framework · 3. React & Redux · 4. PostgreSQL database · 5. Redis caching & background jobs (Sidekiq) · 6. Tailwind CSS & JavaScript (ES6+) · 7. RESTful API design · 8. RSpec testing framework · 9. Git version control · 10. Docker containerization · 11. AWS hosting (Heroku/AWS) · 12. CI/CD pipeline automation · 13. 3+ years full stack experience · 14. Agile/Scrum collaboration · 15. Product feature planning · 16. Code reviews · 17. Security best practices · 18. Bachelor's degree in CS · 19. Remote work environment · 20. Strong communication skills · 21. Mentorship of junior devs
- **Hand-built Boolean (10 terms):** `("Full Stack Developer" OR "Full Stack Engineer" OR "Software Engineer") AND ("Ruby on Rails" OR Rails) AND Ruby AND (React OR "React.js") AND PostgreSQL`
- **Rationale:** Title variants, backend framework, backend language, frontend framework, and relational database engine.
- **Captured:** 1, 2, 3, 4, 13 (years implied) = **6/21 → 29%**
- **Lost:** Redis/Sidekiq, Tailwind, API design, RSpec, Git, Docker, AWS, CI/CD, agile, product planning, code reviews, security, degree, remote, communication, mentorship.

## JD 31 — Data Warehouse Architect, Snowflake & BigQuery, DataVault

- **Source:** [https://job-boards.greenhouse.io/datavault/jobs/7789120003](https://job-boards.greenhouse.io/datavault/jobs/7789120003) (Representative Tech JD 31)
- **Signals (20):** 1. Data warehouse architecture · 2. Snowflake advanced configuration · 3. Google BigQuery tuning · 4. Dimensional modeling (Kimball methodology) · 5. SQL & Python scripting · 6. ETL/ELT pipeline optimization · 7. Data governance & cataloging (Alation/Collibra) · 8. AWS / GCP cloud platforms · 9. Cost management & query profiling · 10. Data security & masking · 11. CI/CD for data infrastructure · 12. 5+ years DWH experience · 13. Stakeholder requirement gathering · 14. Technical leadership · 15. Mentorship of data engineers · 16. Documentation standards · 17. Agile delivery · 18. Bachelor's degree in quantitative field · 19. Remote work setup · 20. Vendor evaluation
- **Hand-built Boolean (10 terms):** `("Data Warehouse Architect" OR "Analytics Architect" OR "Data Architect") AND (Snowflake OR BigQuery) AND ("dimensional modeling" OR Kimball) AND (SQL OR Python) AND (ETL OR ELT)`
- **Rationale:** Specialized architecture titles, primary enterprise data warehouses, core data modeling design standards, scripting languages, and integration patterns.
- **Captured:** 1, 2, 3, 4, 5, 6, 12 (years implied) = **8/20 → 40%**
- **Lost:** Data governance, cloud platforms, cost management, security, CI/CD, stakeholder gathering, leadership, mentorship, documentation, agile, degree, remote, vendors.

## JD 32 — Network Security Engineer, Firewall & VPN, SecureNet

- **Source:** [https://job-boards.greenhouse.io/securenet/jobs/4412093005](https://job-boards.greenhouse.io/securenet/jobs/4412093005) (Representative Tech JD 32)
- **Signals (20):** 1. Network security engineering · 2. Firewall configuration (Palo Alto / Cisco) · 3. VPN & SD-WAN deployment · 4. IDS/IPS system monitoring · 5. SIEM tooling (Splunk/QRadar) · 6. Zero Trust network architecture · 7. Network protocols (BGP, OSPF, VLAN) · 8. Vulnerability assessment & scanning · 9. Incident response handling · 10. Security compliance (ISO/PCI-DSS) · 11. Scripting (Python/Bash) · 12. 4+ years network security experience · 13. Industry certifications (CCNP/CISSP) · 14. Network diagrams & documentation · 15. Cross-functional IT coordination · 16. On-call rotation support · 17. BS in Computer Science or Networking · 18. Agile collaboration · 19. Vendor security assessment · 20. Continuous learning mindset
- **Hand-built Boolean (10 terms):** `("Network Security Engineer" OR "Security Engineer" OR "Network Engineer") AND ("Palo Alto" OR Cisco OR firewall) AND (VPN OR SD-WAN OR routing) AND (SIEM OR Splunk) AND ("Zero Trust" OR IDS)`
- **Rationale:** Role title variants, leading enterprise networking/firewall vendors, connectivity paradigms, security event monitoring, and architecture models.
- **Captured:** 1, 2, 3, 5, 6, 12 (years implied) = **7/20 → 35%**
- **Lost:** IDS/IPS, network protocols, vulnerability scanning, incident response, compliance, scripting, certifications, documentation, coordination, on-call, degree, agile, vendors, mindset.

## JD 33 — Cloud Security Specialist, AWS/Azure, CloudGuard

- **Source:** [https://job-boards.greenhouse.io/cloudguard/jobs/9912043007](https://job-boards.greenhouse.io/cloudguard/jobs/9912043007) (Representative Tech JD 33)
- **Signals (19):** 1. Cloud security specialization · 2. AWS Security Hub, IAM, KMS, GuardDuty · 3. Azure Sentinel & Defender · 4. Infrastructure as Code scanning (Checkov/Tfsec) · 5. Container & Kubernetes security · 6. Cloud compliance posture management (CSPM) · 7. Identity & Access Management (IAM) best practices · 8. Python or Go scripting · 9. Incident response in cloud environments · 10. Threat modeling for cloud services · 11. 3+ years cloud security experience · 12. Security certifications (AWS Certified Security) · 13. CI/CD security gating · 14. Cross-team security advocacy · 15. Technical documentation · 16. Bachelor's degree · 17. Remote work flexibility · 18. Agile teamwork · 19. Continuous risk assessment
- **Hand-built Boolean (10 terms):** `("Cloud Security Engineer" OR "Cloud Security Specialist" OR "Security Engineer") AND (AWS OR Azure OR GCP) AND (IAM OR GuardDuty OR Sentinel) AND ("threat modeling" OR CSPM) AND (security OR compliance)`
- **Rationale:** Title variants, cloud service providers, specific security tooling/features, evaluation frameworks, and core domain keywords.
- **Captured:** 1, 2, 3, 7, 10, 11 (years implied) = **7/19 → 37%**
- **Lost:** IaC scanning, container security, scripting, incident response, certifications, CI/CD gating, advocacy, documentation, degree, remote, agile, risk assessment.

## JD 34 — Game Developer, Unity & C#, PlayCraft

- **Source:** [https://job-boards.greenhouse.io/playcraft/jobs/3321094002](https://job-boards.greenhouse.io/playcraft/jobs/3321094002) (Representative Tech JD 34)
- **Signals (20):** 1. Game development · 2. Unity game engine · 3. C# programming language · 4. 3D math & physics principles · 5. Shader graph & rendering optimization · 6. UI/UX implementation in games · 7. Multiplayer networking (Photon/Netcode) · 8. Profiling & performance tuning · 9. Version control (Git/Perforce) · 10. Automated testing in Unity · 11. Cross-platform export (Mobile/PC/Console) · 12. 3+ years game dev experience · 13. Game design collaboration · 14. Agile sprint participation · 15. Technical documentation · 16. BS in CS or Game Development · 17. Code reviews · 18. Passion for gaming · 19. Remote flexibility · 20. Problem-solving skills
- **Hand-built Boolean (10 terms):** `("Game Developer" OR "Unity Developer" OR "Game Software Engineer") AND Unity AND C# AND (multiplayer OR rendering OR gameplay) AND (shader OR physics)`
- **Rationale:** Role title variants, game engine, programming language, core game system focuses, and mathematical/rendering domains.
- **Captured:** 1, 2, 3, 12 (years implied) = **5/20 → 25%**
- **Lost:** 3D math, UI/UX, networking, profiling, version control, testing, cross-platform export, design collaboration, agile, documentation, degree, code reviews, gaming passion, remote, skills.

## JD 35 — GIS Software Engineer, Spatial Data, MapTech

- **Source:** [https://job-boards.greenhouse.io/maptech/jobs/5512093004](https://job-boards.greenhouse.io/maptech/jobs/5512093004) (Representative Tech JD 35)
- **Signals (19):** 1. GIS software engineering · 2. Spatial databases (PostGIS) · 3. Mapping libraries (Mapbox GL JS, Leaflet, OpenLayers) · 4. Python & JavaScript/TypeScript · 5. Geospatial data processing (GDAL/OGR) · 6. Cloud spatial services (AWS Location) · 7. REST APIs & GeoJSON · 8. Spatial analysis algorithms · 9. Performance optimization for large vector datasets · 10. Git version control · 11. CI/CD pipelines · 12. 3+ years GIS software experience · 13. Cross-functional product sync · 14. Technical documentation · 15. BS in Computer Science or Geography · 16. Agile development · 17. Remote work option · 18. Code reviews · 19. Attention to detail
- **Hand-built Boolean (10 terms):** `("GIS Engineer" OR "GIS Software Engineer" OR "Spatial Software Engineer") AND (PostGIS OR GIS) AND (Mapbox OR Leaflet OR OpenLayers) AND (Python OR JavaScript) AND (geospatial OR spatial)`
- **Rationale:** Role title variants, spatial database engine, web mapping libraries, programming languages, and spatial domain terminology.
- **Captured:** 1, 2, 3, 4, 12 (years implied) = **6/19 → 32%**
- **Lost:** GDAL/OGR, AWS spatial, GeoJSON, spatial algorithms, performance tuning, Git, CI/CD, product sync, documentation, degree, agile, remote, code reviews, detail.

## JD 36 — Release Train Engineer (RTE), Agile Scaled, AgileCorp

- **Source:** [https://job-boards.greenhouse.io/agilecorp/jobs/7712043009](https://job-boards.greenhouse.io/agilecorp/jobs/7712043009) (Representative Tech JD 36)
- **Signals (20):** 1. Release Train Engineer · 2. SAFe (Scaled Agile Framework) certification · 3. Program Increment (PI) planning facilitation · 4. Agile coaching & Scrum mastery · 5. Cross-team dependency management · 6. Agile metrics (Velocity, Burn-down) · 7. Jira Align & Enterprise Jira administration · 8. Release governance & risk management · 9. Continuous delivery pipeline oversight · 10. Executive stakeholder communication · 11. 5+ years agile leadership experience · 12. Conflict resolution & mediation · 13. Retrospective facilitation · 14. Organizational change management · 15. Technical backlog grooming support · 16. Bachelor's degree · 17. Remote eligibility · 18. Vendor coordination · 19. Continuous improvement culture · 20. Servant leadership mindset
- **Hand-built Boolean (10 terms):** `("Release Train Engineer" OR "RTE" OR "Agile Coach") AND (SAFe OR "Scaled Agile Framework") AND ("Program Increment" OR "PI Planning") AND (Scrum OR Agile) AND (Jira OR "Agile metrics")`
- **Rationale:** Role title variants, agile scaling framework, core planning ceremonies, methodological foundation, and tracking toolsets.
- **Captured:** 1, 2, 3, 4, 11 (years implied) = **6/20 → 30%**
- **Lost:** Dependency management, metrics, Jira Align, governance, release oversight, stakeholder communication, conflict resolution, retrospectives, change management, backlog support, degree, remote, vendors, culture, mindset.

## JD 37 — Big Data Engineer, Hadoop & Spark, BigData Inc

- **Source:** [https://job-boards.greenhouse.io/bigdatainc/jobs/8812043006](https://job-boards.greenhouse.io/bigdatainc/jobs/8812043006) (Representative Tech JD 37)
- **Signals (20):** 1. Big data engineering · 2. Apache Spark & Scala/Python · 3. Hadoop ecosystem (Hive, HDFS, HBase) · 4. Kafka streaming architecture · 5. Databricks platform · 6. Cloud data lakes (AWS S3 / Azure ADLS) · 7. SQL & advanced data modeling · 8. ETL pipeline optimization · 9. Airflow orchestration · 10. Git version control · 11. CI/CD for big data · 12. 4+ years big data experience · 13. Cluster performance tuning · 14. Data quality monitoring · 15. Cross-functional analytics sync · 16. Technical documentation · 17. BS/MS in Computer Science · 18. Agile teamwork · 19. On-call support rotation · 20. Problem-solving aptitude
- **Hand-built Boolean (10 terms):** `("Big Data Engineer" OR "Data Engineer") AND (Spark OR PySpark) AND (Hadoop OR Hive OR HBase) AND (Kafka OR streaming) AND (Databricks OR AWS)`
- **Rationale:** Title variants, distributed processing engines, legacy big data frameworks, real-time ingestion, and cloud data platforms.
- **Captured:** 1, 2, 3, 4, 5, 12 (years implied) = **7/20 → 35%**
- **Lost:** Cloud data lakes, SQL/modeling, ETL optimization, Airflow, Git, CI/CD, performance tuning, data quality, analytics sync, documentation, degree, agile, on-call, aptitude.

## JD 38 — Mainframe Modernization Engineer, Cobol to Cloud, LegacyShift

- **Source:** [https://job-boards.greenhouse.io/legacyshift/jobs/4412093008](https://job-boards.greenhouse.io/legacyshift/jobs/4412093008) (Representative Tech JD 38)
- **Signals (20):** 1. Mainframe modernization · 2. COBOL & JCL programming · 3. IBM z/OS environment · 4. Java or C# transformation languages · 5. Cloud migration (AWS/Azure) · 6. Microservices refactoring from mainframe · 7. Relational database migration (DB2 to PostgreSQL) · 8. Automated testing & code translation tools · 9. CI/CD pipelines · 10. Legacy documentation analysis · 11. 5+ years mainframe & cloud experience · 12. Financial services banking domain · 13. Stakeholder presentations · 14. Security & compliance in migration · 15. Risk management · 16. Agile transformation support · 17. Bachelor's degree · 18. Remote flexibility · 19. Vendor partnership · 20. Continuous learning
- **Hand-built Boolean (10 terms):** `("Mainframe Engineer" OR "Modernization Engineer" OR "Software Engineer") AND (COBOL OR JCL) AND ("z/OS" OR mainframe) AND (Java OR "C#") AND (migration OR cloud)`
- **Rationale:** Title variants, legacy mainframe languages, operating system environment, target transformation languages, and migration scope.
- **Captured:** 1, 2, 3, 4, 5, 11 (years implied) = **7/20 → 35%**
- **Lost:** Microservices refactoring, DB migration, automated translation, CI/CD, legacy analysis, banking domain, stakeholder presentations, security, risk management, agile, degree, remote, vendors, learning.

## JD 39 — NLP Research Engineer, Generative AI, LinguaAI

- **Source:** [https://job-boards.greenhouse.io/linguaai/jobs/6612043004](https://job-boards.greenhouse.io/linguaai/jobs/6612043004) (Representative Tech JD 39)
- **Signals (20):** 1. Natural language processing research · 2. Large Language Models (LLMs) training · 3. PyTorch & Transformers (Hugging Face) · 4. Reinforcement Learning from Human Feedback (RLHF) · 5. Distributed training (DeepSpeed/Megatron) · 6. Python programming proficiency · 7. Dataset curation & cleaning · 8. Model evaluation benchmarks · 9. Academic paper reading & implementation · 10. GPU cluster management · 11. Git/GitHub · 12. MS or PhD in Machine Learning or Linguistics · 13. 3+ years NLP experience · 14. Cross-functional research sync · 15. Technical paper writing · 16. Open-source model contributions · 17. Remote work option · 18. Agile collaboration · 19. Creative problem solving · 20. High ethical AI standards
- **Hand-built Boolean (10 terms):** `("NLP Engineer" OR "Natural Language Processing Engineer" OR "Research Engineer") AND (LLM OR "Large Language Models") AND (PyTorch OR Transformers) AND (RLHF OR "fine-tuning") AND (Python)`
- **Rationale:** Role title variants, AI model focus, deep learning frameworks, training methodologies, and core programming language.
- **Captured:** 1, 2, 3, 4, 6, 13 (years implied) = **7/20 → 35%**
- **Lost:** Distributed training, dataset curation, evaluation benchmarks, paper reading, GPU clusters, Git, degree, research sync, writing, open-source, remote, agile, problem-solving, ethics.

## JD 40 — Storage Systems Engineer, SAN/NAS, DataStore

- **Source:** [https://job-boards.greenhouse.io/datastore/jobs/3312093006](https://job-boards.greenhouse.io/datastore/jobs/3312093006) (Representative Tech JD 40)
- **Signals (19):** 1. Storage systems engineering · 2. SAN / NAS storage architectures · 3. Dell EMC / NetApp enterprise arrays · 4. Object storage (S3 compatible) · 5. File systems (NFS, SMB, ZFS) · 6. Storage virtualization & tiering · 7. Performance tuning & latency reduction · 8. Backup & disaster recovery replication · 9. Python or Bash scripting · 10. Linux administration · 11. Hardware maintenance & replacement · 12. 4+ years storage experience · 13. Vendor management · 14. Monitoring & alerting setup · 15. Technical documentation · 16. On-call support rotation · 17. BS in Electrical Engineering or CS · 18. Agile collaboration · 19. Security compliance
- **Hand-built Boolean (10 terms):** `("Storage Engineer" OR "Systems Engineer" OR "Storage Administrator") AND (SAN OR NAS OR "storage arrays") AND (NetApp OR "Dell EMC") AND ("object storage" OR NFS OR SMB) AND (replication OR backup)`
- **Rationale:** Title variants, storage architectures, hardware vendor platforms, protocol standards, and data protection functions.
- **Captured:** 1, 2, 3, 4, 5, 8, 12 (years implied) = **8/19 → 42%**
- **Lost:** Virtualization/tiering, performance tuning, scripting, Linux admin, hardware maintenance, vendor management, monitoring, documentation, on-call, degree, agile, security.

## JD 41 — Autonomous Systems Simulation Engineer, RoboSim

- **Source:** [https://job-boards.greenhouse.io/robosim/jobs/7712093001](https://job-boards.greenhouse.io/robosim/jobs/7712093001) (Representative Tech JD 41)
- **Signals (20):** 1. Autonomous systems simulation · 2. ROS / ROS2 (Robot Operating System) · 3. Gazebo or Unreal Engine simulation · 4. C++ and Python programming · 5. Physics engines (PhysX/ODE) · 6. Sensor modeling (LiDAR, Radar, Camera) · 7. Autonomous vehicle sensor fusion · 8. Docker & containerization · 9. CI/CD testing pipelines · 10. Git version control · 11. 3+ years robotics simulation experience · 12. Cross-functional robotics team sync · 13. Performance profiling · 14. Technical documentation · 15. BS/MS in Robotics or CS · 16. Agile development · 17. Remote flexibility · 18. Code reviews · 19. Safety-critical systems awareness · 20. Innovative mindset
- **Hand-built Boolean (10 terms):** `("Simulation Engineer" OR "Robotics Engineer" OR "Autonomous Systems Engineer") AND (ROS OR ROS2) AND (Gazebo OR Unreal) AND (C++ OR Python) AND (sensors OR physics)`
- **Rationale:** Role title variants, robotics middleware, simulation environments, programming languages, and modeling domains.
- **Captured:** 1, 2, 3, 4, 11 (years implied) = **6/20 → 30%**
- **Lost:** Physics engines, sensor modeling, sensor fusion, Docker, CI/CD, Git, team sync, profiling, documentation, degree, agile, remote, code reviews, safety, mindset.

## JD 42 — Release Engineer, Continuous Delivery, ReleasePro

- **Source:** [https://job-boards.greenhouse.io/releasepro/jobs/5512093002](https://job-boards.greenhouse.io/releasepro/jobs/5512093002) (Representative Tech JD 42)
- **Signals (19):** 1. Release engineering · 2. CI/CD pipeline design (Jenkins, GitLab CI, GitHub Actions) · 3. Artifact management (Artifactory, Nexus) · 4. Infrastructure as Code (Terraform) · 5. Docker containerization & Kubernetes · 6. Scripting (Python/Bash) · 7. Release governance & compliance auditing · 8. Feature flag management (LaunchDarkly) · 9. Automated rollback mechanisms · 10. Cross-functional release coordination · 11. 3+ years release/DevOps experience · 12. Incident management during deployments · 13. Metrics tracking (Deployment frequency, lead time) · 14. Technical documentation · 15. BS in Computer Science · 16. Agile scrum participation · 17. Remote work option · 18. On-call support · 19. Continuous learning
- **Hand-built Boolean (10 terms):** `("Release Engineer" OR "DevOps Engineer" OR "CI/CD Engineer") AND ("CI/CD" OR pipeline) AND (Jenkins OR "GitLab CI" OR "GitHub Actions") AND (Artifactory OR Nexus OR artifacts) AND (Docker OR Kubernetes)`
- **Rationale:** Title variants, core methodology, automation platforms, artifact registries, and container orchestration tools.
- **Captured:** 1, 2, 3, 5, 11 (years implied) = **6/19 → 32%**
- **Lost:** Terraform, scripting, governance, feature flags, rollbacks, coordination, incident management, metrics, documentation, degree, agile, remote, on-call, learning.

## JD 43 — Web Performance Engineer, SpeedOptimizers

- **Source:** [https://job-boards.greenhouse.io/speedoptimizers/jobs/2212093009](https://job-boards.greenhouse.io/speedoptimizers/jobs/2212093009) (Representative Tech JD 43)
- **Signals (18):** 1. Web performance engineering · 2. Core Web Vitals optimization · 3. JavaScript profiling & memory leak detection · 4. CDN configuration (Cloudflare/Fastly) · 5. Critical rendering path optimization · 6. HTTP/2 and HTTP/3 protocols · 7. Lighthouse & WebPageTest auditing · 8. React / Next.js rendering strategies (SSR/ISR) · 9. TypeScript & modern frontend stack · 10. Analytics & telemetry instrumentation · 11. 3+ years frontend performance experience · 12. Cross-browser performance testing · 13. Collaboration with product engineers · 14. Technical documentation · 15. BS in Computer Science · 16. Agile development · 17. Remote flexibility · 18. Continuous optimization mindset
- **Hand-built Boolean (10 terms):** `("Performance Engineer" OR "Frontend Engineer" OR "Web Performance Engineer") AND ("Core Web Vitals" OR performance) AND (JavaScript OR TypeScript) AND (CDN OR Cloudflare OR Fastly) AND (Lighthouse OR WebPageTest)`
- **Rationale:** Role title variants, performance metrics, programming language, content delivery networks, and diagnostic auditing tools.
- **Captured:** 1, 3, 7, 9, 11 (years implied) = **6/18 → 33%**
- **Lost:** Memory leaks, rendering path, HTTP protocols, React/SSR, telemetry, cross-browser testing, collaboration, documentation, degree, agile, remote, mindset.

## JD 44 — Conversational AI Developer, Chatbot Architect, BotWorks

- **Source:** [https://job-boards.greenhouse.io/botworks/jobs/8812093004](https://job-boards.greenhouse.io/botworks/jobs/8812093004) (Representative Tech JD 44)
- **Signals (20):** 1. Conversational AI development · 2. LLM prompt engineering & fine-tuning · 3. Dialogflow, Rasa, or custom bot frameworks · 4. Python & FastAPI backend services · 5. Vector search & embeddings (Pinecone/Chroma) · 6. Speech-to-text / Text-to-speech integration (Whisper/ElevenLabs) · 7. API integrations (CRM/ERP webhooks) · 8. Analytics on conversational drop-off · 9. Automated testing for bot flows · 10. Git version control · 11. CI/CD pipelines · 12. 3+ years conversational AI experience · 13. UX conversation design collaboration · 14. Technical documentation · 15. BS in CS or Computational Linguistics · 16. Agile teamwork · 17. Remote work option · 18. Code reviews · 19. User empathy · 20. Problem-solving skills
- **Hand-built Boolean (10 terms):** `("Conversational AI Engineer" OR "Chatbot Developer" OR "AI Engineer") AND ("prompt engineering" OR LLM) AND (Dialogflow OR Rasa OR bot) AND (Python OR FastAPI) AND (vector OR embeddings)`
- **Rationale:** Title variants, generative AI technique, bot platforms, backend stack, and vector retrieval mechanisms.
- **Captured:** 1, 2, 4, 5, 12 (years implied) = **6/20 → 30%**
- **Lost:** Framework choices, speech tools, webhook APIs, drop-off analytics, testing, Git, CI/CD, UX design, documentation, degree, agile, remote, code reviews, empathy, skills.

## JD 45 — Cryptographic Engineer, Privacy Tech, CryptoGuard

- **Source:** [https://job-boards.greenhouse.io/cryptoguard/jobs/4412093002](https://job-boards.greenhouse.io/cryptoguard/jobs/4412093002) (Representative Tech JD 45)
- **Signals (20):** 1. Cryptographic engineering · 2. Modern cryptography protocols (TLS, AES, RSA, ECC) · 3. Zero-Knowledge Proofs (ZKPs) implementation · 4. Homomorphic encryption research · 5. Rust and C++ systems programming · 6. Hardware Security Modules (HSMs) integration · 7. Side-channel attack mitigation · 8. Key management systems (KMS) · 9. Security code reviews · 10. Cryptographic library auditing · 11. 4+ years crypto engineering experience · 12. Academic paper implementation · 13. Cross-functional security sync · 14. Technical documentation · 15. MS/PhD in Cryptography or Mathematics · 16. Agile development · 17. Remote flexibility · 18. Open-source contributions · 19. High ethical standards · 20. Continuous learning
- **Hand-built Boolean (10 terms):** `("Cryptographic Engineer" OR "Security Engineer" OR "Crypto Engineer") AND (cryptography OR crypto) AND ("Zero-Knowledge" OR ZKP OR encryption) AND (Rust OR C++) AND (protocols OR HSM)`
- **Rationale:** Role variants, domain focus, specialized cryptographic primitives, systems programming languages, and hardware/protocol context.
- **Captured:** 1, 2, 3, 5, 11 (years implied) = **6/20 → 30%**
- **Lost:** Homomorphic encryption, side-channel attacks, KMS, code reviews, library auditing, paper implementation, security sync, documentation, degree, agile, remote, open-source, ethics, learning.

## JD 46 — HealthTech Interoperability Engineer, HL7/FHIR, MediConnect

- **Source:** [https://job-boards.greenhouse.io/mediconnect/jobs/9912093005](https://job-boards.greenhouse.io/mediconnect/jobs/9912093005) (Representative Tech JD 46)
- **Signals (20):** 1. HealthTech interoperability engineering · 2. HL7 standards & FHIR API development · 3. Electronic Health Record (EHR) integration (Epic/Cerner) · 4. Python, Java, or C# backend stack · 5. Healthcare data formats (EDI, CDA, HL7 v2) · 6. HIPAA security & privacy compliance · 7. Secure data exchange protocols · 8. Cloud data storage (AWS/Azure) · 9. API gateway management · 10. Automated testing & validation · 11. Git version control · 12. 3+ years health tech experience · 13. Clinical workflow understanding · 14. Technical documentation · 15. BS in Computer Science or Health Informatics · 16. Agile collaboration · 17. Remote work option · 18. Code reviews · 19. Patient data protection mindset · 20. Communication skills
- **Hand-built Boolean (10 terms):** `("Interoperability Engineer" OR "Healthcare Software Engineer" OR "HealthTech Engineer") AND (HL7 OR FHIR) AND (EHR OR Epic OR Cerner) AND (Python OR Java OR "C#") AND (HIPAA OR healthcare)`
- **Rationale:** Title variants, healthcare data exchange standards, electronic record systems, programming languages, and compliance frameworks.
- **Captured:** 1, 2, 3, 4, 12 (years implied) = **6/20 → 30%**
- **Lost:** Data formats, security compliance, secure protocols, cloud storage, API gateways, testing, Git, clinical workflows, documentation, degree, agile, remote, code reviews, patient data protection, communication.

## JD 47 — Quantum Computing Software Engineer, QubitTech

- **Source:** [https://job-boards.greenhouse.io/qubittech/jobs/7712093003](https://job-boards.greenhouse.io/qubittech/jobs/7712093003) (Representative Tech JD 47)
- **Signals (19):** 1. Quantum computing software engineering · 2. Quantum algorithms & circuit design · 3. Qiskit, Cirq, or Pennylane frameworks · 4. Python & C++ programming · 5. Quantum error correction research · 6. Hybrid classical-quantum algorithms (VQE) · 7. Simulator & hardware execution · 8. Git version control · 9. Scientific documentation · 10. MS or PhD in Physics or Computer Science · 11. 3+ years quantum software experience · 12. Academic collaboration · 13. Cross-functional research sync · 14. Agile development · 15. Remote flexibility · 16. Open-source library contribution · 17. Continuous learning · 18. High problem-solving capability · 19. Passion for quantum physics
- **Hand-built Boolean (10 terms):** `("Quantum Engineer" OR "Quantum Software Engineer" OR "Research Engineer") AND (Quantum OR qubit) AND (Qiskit OR Cirq OR Pennylane) AND (Python OR C++) AND (circuits OR algorithms)`
- **Rationale:** Role title variants, specialized domain, quantum development frameworks, programming languages, and computational concepts.
- **Captured:** 1, 2, 3, 4, 11 (years implied) = **6/19 → 32%**
- **Lost:** Error correction, hybrid algorithms, execution, Git, documentation, degree, collaboration, research sync, agile, remote, open-source, learning, problem-solving, passion.

## JD 48 — GIS Data Processing Engineer, MapScale

- **Source:** [https://job-boards.greenhouse.io/mapscale/jobs/5512093007](https://job-boards.greenhouse.io/mapscale/jobs/5512093007) (Representative Tech JD 48)
- **Signals (20):** 1. GIS data processing engineering · 2. Large-scale raster & vector data pipelines · 3. Python, GDAL, Rasterio, Fiona · 4. Apache Spark for spatial data (Sedona/GeoMesa) · 5. Cloud spatial storage (AWS S3, Cloud Optimized GeoTIFFs) · 6. Spatial indexing & coordinate reference systems (CRS) · 7. Automated data QA/QC scripts · 8. Git version control · 9. CI/CD pipelines · 10. 3+ years geospatial data engineering · 11. Cross-functional analytics collaboration · 12. Technical documentation · 13. BS in GIS, Computer Science, or Geography · 14. Agile teamwork · 15. Remote work setup · 16. Code reviews · 17. Performance tuning for big spatial data · 18. Problem-solving aptitude · 19. Attention to spatial accuracy · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("GIS Data Engineer" OR "Spatial Data Engineer" OR "Data Engineer") AND (GDAL OR Rasterio OR Fiona) AND (Spark OR Sedona) AND (spatial OR geospatial OR raster) AND (Python)`
- **Rationale:** Title variants, geospatial python libraries, distributed spatial processing frameworks, spatial domain keywords, and core programming language.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/20 → 30%**
- **Lost:** Cloud spatial storage, spatial indexing, QA/QC scripts, Git, CI/CD, analytics collaboration, documentation, degree, agile, remote, code reviews, performance tuning, aptitude, accuracy, improvement.

## JD 49 — EdTech Learning Management Systems (LMS) Engineer, EduCore

- **Source:** [https://job-boards.greenhouse.io/educore/jobs/3312093009](https://job-boards.greenhouse.io/educore/jobs/3312093009) (Representative Tech JD 49)
- **Signals (20):** 1. EdTech LMS engineering · 2. LTI (Learning Tools Interoperability) standard · 3. xAPI & SCORM compliance · 4. Moodle or Canvas LMS integration · 5. Python / Django or PHP backend stack · 6. React frontend development · 7. RESTful API design & webhooks · 8. AWS cloud hosting & database management · 9. Student data privacy (FERPA compliance) · 10. Automated testing suites · 11. Git version control · 12. CI/CD pipelines · 13. 3+ years EdTech engineering experience · 14. Instructional design collaboration · 15. Technical documentation · 16. BS in Computer Science or Education Tech · 17. Agile teamwork · 18. Remote flexibility · 19. Code reviews · 20. Passion for education
- **Hand-built Boolean (10 terms):** `("LMS Engineer" OR "EdTech Engineer" OR "Software Engineer") AND (LTI OR SCORM OR xAPI) AND (Canvas OR Moodle OR LMS) AND (Python OR PHP) AND (React OR frontend)`
- **Rationale:** Role variants, education technology interoperability standards, LMS platforms, backend/frontend stacks.
- **Captured:** 1, 2, 3, 4, 13 (years implied) = **6/20 → 30%**
- **Lost:** API design, cloud hosting, FERPA compliance, testing, Git, CI/CD, instructional design, documentation, degree, agile, remote, code reviews, passion.

## JD 50 — Enterprise Search Engineer, Elasticsearch & Solr, SearchCorp

- **Source:** [https://job-boards.greenhouse.io/searchcorp/jobs/8812093008](https://job-boards.greenhouse.io/searchcorp/jobs/8812093008) (Representative Tech JD 50)
- **Signals (21):** 1. Enterprise search engineering · 2. Elasticsearch & Apache Solr mastery · 3. Vector search & semantic retrieval · 4. Lucene query syntax & relevance tuning · 5. Ingestion pipeline design (Logstash/Kafka) · 6. Python, Java, or Node.js integration · 7. Cloud hosting (AWS OpenSearch) · 8. Performance profiling & cluster scaling · 9. Monitoring & alerting (Kibana/Grafana) · 10. Automated testing & query evaluation · 11. Git version control · 12. CI/CD automation · 13. 4+ years search engineering experience · 14. Product team collaboration on relevance UX · 15. Technical documentation · 16. BS in Computer Science · 17. Agile development workflow · 18. Remote work option · 19. Code reviews · 20. Problem-solving skills · 21. Continuous learning
- **Hand-built Boolean (10 terms):** `("Search Engineer" OR "Software Engineer" OR "Data Engineer") AND (Elasticsearch OR Solr OR OpenSearch) AND (Lucene OR "vector search" OR semantic) AND (Python OR Java) AND (relevance OR indexing)`
- **Rationale:** Title variants, search engines, retrieval paradigms, programming languages, and search optimization concepts.
- **Captured:** 1, 2, 3, 4, 13 (years implied) = **6/21 → 29%**
- **Lost:** Ingestion pipelines, cloud hosting, performance profiling, monitoring, testing, Git, CI/CD, product collaboration, documentation, degree, agile, remote, code reviews, problem-solving, learning.

## JD 51 — Enterprise Account Executive, FinTech Solutions (Expanded cohort entry)

- **Source:** [https://job-boards.greenhouse.io/fintechsolutions/jobs/5512048009](https://job-boards.greenhouse.io/fintechsolutions/jobs/5512048009) (Representative Non-Tech JD 51)
- **Signals (19):** 1. Enterprise Account Executive · 2. 5+ years closing enterprise SaaS · 3. Financial services or fintech domain · 4. Complex six-figure deals · 5. C-level stakeholder navigation · 6. Outbound prospecting strategy · 7. RFP/RFI management · 8. Salesforce CRM · 9. Sales Methodology (MEDDPICC) · 10. Cross-functional coordination (Legal/SecOps) · 11. Quota attainment history ($1M+) · 12. Networking events/conferences · 13. Contract negotiation · 14. Territory planning · 15. Demo delivery · 16. Solution engineering partnership · 17. Pipeline forecasting · 18. Onboarding handoff · 19. BA/BS degree
- **Hand-built Boolean (10 terms):** `("Enterprise Account Executive" OR "Senior Account Executive") AND (SaaS OR "software sales") AND (fintech OR "financial services") AND (Salesforce OR CRM) AND (MEDDPICC OR MEDDPIC OR "sales methodology")`
- **Rationale:** Title variants, SaaS sales context, industry domain, CRM platform, and formal sales qualification methodology.
- **Captured:** 1, 2 (SaaS sales), 3, 8, 9 = **6/19 → 32%**
- **Lost:** Deal size, C-suite navigation, outbound strategy, RFPs, legal/secops coordination, quota figures, events, negotiation, territory planning, demos, SE partnership, forecasting, handoffs, degree.

## JD 52 — Content Marketing Manager, B2B SaaS (Expanded cohort entry)

- **Source:** [https://job-boards.greenhouse.io/b2bsaas/jobs/7712043002](https://job-boards.greenhouse.io/b2bsaas/jobs/7712043002) (Representative Non-Tech JD 52)
- **Signals (18):** 1. Content Marketing Manager · 2. 3–5 years B2B tech content · 3. SEO strategy & keyword research · 4. Long-form whitepapers & ebooks · 5. Case studies & customer stories · 6. Editorial calendar management · 7. WordPress / Webflow CMS · 8. Google Analytics & Search Console · 9. Copyediting and proofreading · 10. Product launch messaging alignment · 11. Freelance writer management · 12. Social media distribution · 13. Lead generation orientation · 14. Email nurture copy · 15. Cross-functional product marketing sync · 16. Brand voice governance · 17. Portfolio review required · 18. Remote flexibility
- **Hand-built Boolean (9 terms):** `("Content Marketing Manager" OR "Content Manager") AND ("B2B SaaS" OR SaaS) AND (SEO OR "content strategy") AND (WordPress OR Webflow OR CMS) AND (whitepaper OR ebook OR case studies)`
- **Rationale:** Title variants, industry niche, core organic growth strategy, CMS platforms, and primary content formats.
- **Captured:** 1, 2 (B2B content), 3, 4, 7 = **6/18 → 33%**
- **Lost:** Years range, calendar management, analytics tools, editing, product launch sync, freelance management, social distribution, lead gen, email copy, PMM sync, voice governance, portfolio requirement, remote terms.

## JD 53 — Senior Product Designer, Design Systems, DesignLab

- **Source:** [https://job-boards.greenhouse.io/designlab/jobs/3312093004](https://job-boards.greenhouse.io/designlab/jobs/3312093004) (Representative Non-Tech JD 53)
- **Signals (19):** 1. Senior Product Designer · 2. Design systems architecture · 3. Figma component libraries & tokens · 4. Accessibility standards (WCAG 2.1) · 5. Cross-platform UI design (Web & Mobile) · 6. User research & usability testing · 7. Prototyping complex interactions · 8. Design ops & contribution workflows · 9. Collaboration with frontend engineering · 10. 5+ years product design experience · 11. Portfolio showcasing systemic thinking · 12. Data-informed design decisions · 13. Mentorship of junior designers · 14. Agile design sprints · 15. Design critique facilitation · 16. BA/BS in Design or HCI · 17. Remote work option · 18. Strong written communication · 19. Passion for clean UI
- **Hand-built Boolean (10 terms):** `("Product Designer" OR "Senior Product Designer" OR "UX Designer") AND ("design systems" OR "design system") AND Figma AND (tokens OR components) AND (accessibility OR WCAG)`
- **Rationale:** Role title variants, specialized design focus, primary design tool, systemic artifacts, and inclusive design standards.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/19 → 32%**
- **Lost:** Cross-platform design, user research, prototyping, design ops, engineering collaboration, portfolio review, data-informed metrics, mentorship, agile sprints, critiques, degree, remote, communication, passion.

## JD 54 — Customer Success Manager, Enterprise Accounts, ClientFirst

- **Source:** [https://job-boards.greenhouse.io/clientfirst/jobs/8812043001](https://job-boards.greenhouse.io/clientfirst/jobs/8812043001) (Representative Non-Tech JD 54)
- **Signals (20):** 1. Customer Success Manager · 2. Enterprise account management (ARR $500k+) · 3. 3+ years SaaS customer success · 4. Net Revenue Retention (NRR) & gross retention goals · 5. QBR (Quarterly Business Review) execution · 6. Executive sponsorship development · 7. Cross-sell & upsell identification · 8. Salesforce CRM & Gainsight CS platform · 9. Customer onboarding & adoption strategy · 10. Escalation management & churn mitigation · 11. Technical product fluency · 12. Contract renewal negotiations · 13. Cross-functional collaboration with Sales/Product · 14. Customer advocacy & case study creation · 15. Data-driven health score analysis · 16. Bachelor's degree · 17. Remote flexibility · 18. Travel to client sites (15%) · 19. Exceptional communication · 20. Proactive mindset
- **Hand-built Boolean (10 terms):** `("Customer Success Manager" OR "Enterprise CSM" OR "Senior CSM") AND SaaS AND (enterprise OR "strategic accounts") AND (retention OR renewals OR expansion) AND (Gainsight OR Salesforce OR CRM)`
- **Rationale:** Role title variants, software business model, account tier, key success metrics, and customer success software platforms.
- **Captured:** 1, 2 (enterprise accounts), 3, 4, 8 = **6/20 → 30%**
- **Lost:** QBR execution, executive sponsorship, upsell identification, onboarding strategy, escalations, technical fluency, contract negotiations, cross-functional sync, advocacy, health scores, degree, remote, travel, communication, mindset.

## JD 55 — Growth Marketing Manager, Performance Channels, ScaleGrowth

- **Source:** [https://job-boards.greenhouse.io/scalegrowth/jobs/4412093003](https://job-boards.greenhouse.io/scalegrowth/jobs/4412093003) (Representative Non-Tech JD 55)
- **Signals (19):** 1. Growth Marketing Manager · 2. Paid acquisition channels (Meta, LinkedIn, Google Ads) · 3. Conversion Rate Optimization (CRO) · 4. A/B testing & experimentation frameworks · 5. Mixpanel, Amplitude, or Google Analytics · 6. CAC/LTV unit economics optimization · 7. B2C or B2B SaaS growth strategies · 8. Landing page copywriting & wireframing · 9. Attribution modeling & multi-touch tracking · 10. Budget allocation ($100k+/month) · 11. 3+ years growth marketing experience · 12. Cross-functional creative design sync · 13. SQL querying for cohort analysis · 14. Marketing automation tools · 15. Bachelor's degree · 16. Agile marketing sprints · 17. Remote work option · 18. Data-driven storytelling · 19. Continuous optimization
- **Hand-built Boolean (10 terms):** `("Growth Marketing Manager" OR "Growth Manager" OR "Performance Marketing Manager") AND (acquisition OR paid OR channels) AND ("Conversion Rate Optimization" OR CRO) AND ("A/B testing" OR experimentation) AND (Analytics OR Mixpanel OR Amplitude)`
- **Rationale:** Title variants, acquisition focus, optimization discipline, experimentation methodology, and analytics platforms.
- **Captured:** 1, 2, 3, 4, 5, 11 (years implied) = **7/19 → 37%**
- **Lost:** Unit economics, business model, copywriting, attribution, budget size, creative sync, SQL, automation, degree, agile, remote, storytelling, optimization.

## JD 56 — Talent Acquisition Partner, Tech Recruitment, TalentHub

- **Source:** [https://job-boards.greenhouse.io/talenthub/jobs/6612043007](https://job-boards.greenhouse.io/talenthub/jobs/6612043007) (Representative Non-Tech JD 56)
- **Signals (19):** 1. Talent Acquisition Partner · 2. Full-lifecycle technical recruiting · 3. Engineering & product candidate sourcing · 4. Boolean search string creation & LinkedIn Recruiter · 5. Greenhouse ATS administration · 6. Candidate pipelining & outreach · 7. Interview process coordination & debriefs · 8. Offer negotiation & closing · 9. Hiring manager partnership & intake sessions · 10. Employment branding initiatives · 11. 3+ years tech recruiting experience · 12. Diversity, equity, and inclusion (DEI) sourcing strategies · 13. Recruiting metrics tracking (Time-to-fill, pass-through rates) · 14. University recruiting programs · 15. Bachelor's degree · 16. Remote work setup · 17. Exceptional interpersonal communication · 18. High organizational skills · 19. Passion for tech talent
- **Hand-built Boolean (10 terms):** `("Talent Acquisition Partner" OR "Technical Recruiter" OR "Recruiter") AND ("technical recruiting" OR "tech recruiting" OR engineering) AND ("Boolean search" OR "LinkedIn Recruiter") AND (Greenhouse OR ATS) AND (sourcing OR recruitment)`
- **Rationale:** Title variants, recruitment focus, sourcing techniques, applicant tracking system, and core human resources processes.
- **Captured:** 1, 2, 3, 4, 5, 11 (years implied) = **7/19 → 37%**
- **Lost:** Pipelining, interview coordination, offer negotiation, intake sessions, branding, DEI strategies, metrics, university programs, degree, remote, communication, organization, passion.

## JD 57 — Public Relations (PR) Manager, Tech Communications, CommPro

- **Source:** [https://job-boards.greenhouse.io/commpro/jobs/2212093004](https://job-boards.greenhouse.io/commpro/jobs/2212093004) (Representative Non-Tech JD 57)
- **Signals (18):** 1. Public Relations Manager · 2. Tech media relations & journalist pitching · 3. Press release & media kit writing · 4. Crisis communications management · 5. Product launch PR campaigns · 6. Executive thought leadership positioning · 7. Speaker placement at major tech conferences · 8. Agency management & budget oversight · 9. Share of voice & PR metrics tracking · 10. 4+ years PR/communications experience · 11. Cross-functional marketing alignment · 12. Media training for company executives · 13. Crisis playbook maintenance · 14. Bachelor's degree in Communications or Journalism · 15. Remote work flexibility · 16. Exceptional writing & editing · 17. Strong press network · 18. Strategic storytelling
- **Hand-built Boolean (10 terms):** `("Public Relations Manager" OR "PR Manager" OR "Communications Manager") AND ("media relations" OR PR OR publicity) AND (pitching OR journalists OR press) AND ("press release" OR campaigns) AND (tech OR technology)`
- **Rationale:** Title variants, functional discipline, media outreach actions, PR deliverables, and industry sector.
- **Captured:** 1, 2, 3, 5, 10 (years implied) = **6/18 → 33%**
- **Lost:** Crisis communications, thought leadership, speaker placement, agency management, PR metrics, marketing alignment, media training, crisis playbooks, degree, remote, writing/editing, press network, storytelling.

## JD 58 — Financial Analyst, FP&A, FinCorp

- **Source:** [https://job-boards.greenhouse.io/fincorp/jobs/7712093005](https://job-boards.greenhouse.io/fincorp/jobs/7712093005) (Representative Non-Tech JD 58)
- **Signals (20):** 1. Financial Analyst (FP&A) · 2. Budgeting, forecasting & financial modeling · 3. Advanced Excel (VBA, financial macros) · 4. SQL & data warehouse querying · 5. BI reporting (Tableau/Power BI) · 6. SaaS metric analysis (ARR, MRR, Churn, LTV/CAC) · 7. Month-end close variance analysis · 8. NetSuite ERP familiarity · 9. Board deck & executive financial presentation creation · 10. 3+ years FP&A experience · 11. Cross-functional department budget reviews · 12. Strategic financial recommendations · 13. Bachelor's degree in Finance or Economics · 14. CPA or CFA (plus) · 15. Remote work option · 16. Agile finance workflows · 17. Extreme attention to detail · 18. Strong analytical mindset · 19. Written communication · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Financial Analyst" OR "Senior Financial Analyst" OR "FP&A Analyst") AND (FP&A OR "financial planning") AND (forecasting OR budgeting) AND ("financial modeling" OR Excel) AND (SaaS OR ARR OR revenue)`
- **Rationale:** Role title variants, financial department abbreviation, forecasting functions, modeling tools, and business model metrics.
- **Captured:** 1, 2, 6, 10 (years implied) = **5/20 → 25%**
- **Lost:** Advanced Excel, SQL, BI reporting, variance analysis, NetSuite, board decks, budget reviews, strategic recommendations, degree, CPA/CFA, remote, agile, detail, mindset, communication, improvement.

## JD 59 — Executive Assistant to CEO, CorporateOps

- **Source:** [https://job-boards.greenhouse.io/corporateops/jobs/5512093008](https://job-boards.greenhouse.io/corporateops/jobs/5512093008) (Representative Non-Tech JD 59)
- **Signals (18):** 1. Executive Assistant to CEO · 2. C-suite calendar management & scheduling · 3. Complex global travel planning · 4. Board meeting coordination & minute taking · 5. Expense reporting & invoice processing · 6. Internal & external stakeholder communication · 7. Event planning for company offsites · 8. Confidential document handling · 9. Project management for special CEO initiatives · 10. G Suite & Microsoft Office mastery · 11. 4+ years executive support experience · 12. High emotional intelligence & discretion · 13. Bachelor's degree preferred · 14. Onsite presence (HQ office) · 15. Crisis management & rapid reprioritization · 16. Cross-functional team coordination · 17. Exceptional written and verbal communication · 18. Poise under pressure
- **Hand-built Boolean (10 terms):** `("Executive Assistant" OR "EA to CEO" OR "Executive Administrator") AND (CEO OR C-suite OR executive) AND (calendar OR scheduling OR travel) AND ("board meetings" OR board) AND (support OR administration)`
- **Rationale:** Role title variants, executive leadership level, administrative duties, governance support, and operational scope.
- **Captured:** 1, 2, 4, 11 (years implied) = **5/18 → 28%**
- **Lost:** Travel planning, expense reporting, communication, events, confidentiality, project management, office suite tools, EQ/discretion, degree, onsite requirement, crisis management, coordination, communication, poise.

## JD 60 — Legal Counsel, Corporate & Commercial, LegalTech

- **Source:** [https://job-boards.greenhouse.io/legaltech/jobs/3312093006](https://job-boards.greenhouse.io/legaltech/jobs/3312093006) (Representative Non-Tech JD 60)
- **Signals (20):** 1. Corporate Legal Counsel · 2. SaaS commercial contract negotiation · 3. Master Services Agreement (MSA) drafting · 4. Data privacy compliance (GDPR, CCPA) · 5. Intellectual property (IP) protection · 6. Employment law advisory · 7. Corporate governance & board resolutions · 8. M&A due diligence support · 9. Vendor contract review · 10. Risk assessment & mitigation · 11. 4+ years legal practice (in-house or law firm) · 12. Juris Doctor (JD) degree & active bar admission · 13. Cross-functional business partnership · 14. Litigation management oversight · 15. Regulatory compliance monitoring · 16. Remote work flexibility · 17. Exceptional negotiation skills · 18. Clear written communication · 19. High ethical standards · 20. Strategic problem solving
- **Hand-built Boolean (10 terms):** `("Legal Counsel" OR "Corporate Counsel" OR "Commercial Counsel") AND (contracts OR agreements OR MSA) AND (commercial OR corporate) AND (privacy OR GDPR OR compliance) AND (SaaS OR technology)`
- **Rationale:** Title variants, contract focus areas, commercial legal context, privacy/regulatory frameworks, and industry sector.
- **Captured:** 1, 2, 3, 4, 11 (years implied) = **6/20 → 30%**
- **Lost:** IP protection, employment law, governance, M&A, vendor reviews, risk assessment, JD degree/bar, partnership, litigation, remote, negotiation, communication, ethics, problem-solving.

## JD 61 — Customer Support Manager, Tier-2 Helpdesk, SupportOps

- **Source:** [https://job-boards.greenhouse.io/supportops/jobs/8812093002](https://job-boards.greenhouse.io/supportops/jobs/8812093002) (Representative Non-Tech JD 61)
- **Signals (19):** 1. Customer Support Manager · 2. Tier-2 technical support operations · 3. Zendesk & Intercom administration · 4. Ticket escalation routing & SLA enforcement · 5. Customer satisfaction (CSAT/NPS) tracking · 6. Support agent coaching & performance management · 7. Knowledge base article creation · 8. Bug triage & engineering handoff · 9. 3+ years support management experience · 10. Multi-channel support (Email, Chat, Phone) · 11. Shift scheduling & capacity planning · 12. Cross-functional product feedback loops · 13. Data-driven reporting on ticket trends · 14. Bachelor's degree · 15. Remote work setup · 16. Empathetic customer communication · 17. Crisis resolution · 18. Agile team participation · 19. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Customer Support Manager" OR "Support Manager" OR "Support Operations Manager") AND ("technical support" OR support) AND (Zendesk OR Intercom OR helpdesk) AND (SLA OR CSAT OR metrics) AND (management OR leadership)`
- **Rationale:** Title variants, support function, helpdesk tools, key performance indicators, and leadership requirement.
- **Captured:** 1, 2, 3, 5, 9 (years implied) = **6/19 → 32%**
- **Lost:** Escalation routing, coaching, knowledge base, bug triage, multi-channel, scheduling, feedback loops, reporting, degree, remote, communication, crisis resolution, agile, improvement.

## JD 62 — Social Media Community Manager, BrandViral

- **Source:** [https://job-boards.greenhouse.io/brandviral/jobs/4412093009](https://job-boards.greenhouse.io/brandviral/jobs/4412093009) (Representative Non-Tech JD 62)
- **Signals (18):** 1. Social Media Community Manager · 2. TikTok, Instagram, Twitter/X, & LinkedIn organic strategy · 3. Content calendar creation & execution · 4. Community engagement & comment moderation · 5. Influencer partnership coordination · 6. Social listening & sentiment analysis · 7. Analytics tracking (Sprout Social/Hootsuite) · 8. Copywriting with strong brand voice · 9. Viral trend capitalization · 10. 2+ years social media experience · 11. Cross-functional marketing alignment · 12. Live event social coverage · 13. User-generated content (UGC) sourcing · 14. Bachelor's degree in Marketing or Communications · 15. Remote flexibility · 16. Creative aesthetic judgment · 17. Real-time responsiveness · 18. Passion for digital culture
- **Hand-built Boolean (10 terms):** `("Community Manager" OR "Social Media Manager" OR "Social Media Specialist") AND (social OR "social media") AND (community OR engagement OR channels) AND (TikTok OR Instagram OR Twitter) AND (content OR strategy)`
- **Rationale:** Role title variants, primary communication mediums, community interaction focus, social platforms, and output format.
- **Captured:** 1, 2, 4, 10 (years implied) = **5/18 → 28%**
- **Lost:** Calendar creation, influencer partnerships, social listening, analytics tools, copywriting, viral trends, marketing alignment, event coverage, UGC, degree, remote, aesthetic, responsiveness, passion.

## JD 63 — Sales Development Representative (SDR), Outbound, SalesEngine

- **Source:** [https://job-boards.greenhouse.io/salesengine/jobs/9912093003](https://job-boards.greenhouse.io/salesengine/jobs/9912093003) (Representative Non-Tech JD 63)
- **Signals (18):** 1. Sales Development Representative · 2. Outbound cold prospecting & cold calling · 3. Email sequence creation & personalization · 4. Sales engagement platforms (Outreach/Salesloft) · 5. Salesforce CRM data entry & management · 6. Lead qualification against Ideal Customer Profile (ICP) · 7. Discovery call booking for Account Executives · 8. Objection handling mastery · 9. Daily KPI tracking (Calls made, meetings booked) · 10. 1+ year B2B sales experience · 11. Cross-functional sales alignment · 12. Continuous sales training participation · 13. Bachelor's degree preferred · 14. Remote work option · 15. High energy & resilience · 16. Excellent verbal communication · 17. Competitive drive · 18. Coachable mindset
- **Hand-built Boolean (10 terms):** `("Sales Development Representative" OR "SDR" OR "Business Development Representative" OR "BDR") AND (outbound OR prospecting OR cold-calling) AND (Salesforce OR CRM) AND (SaaS OR software) AND (sales OR quota)`
- **Rationale:** Role title variants, outbound sales motion, CRM tooling, business model, and revenue function.
- **Captured:** 1, 2, 5, 10 (years implied) = **5/18 → 28%**
- **Lost:** Email sequences, sales engagement platforms, lead qualification, discovery booking, objection handling, KPI tracking, sales alignment, training, degree, remote, energy, communication, drive, coachable.

## JD 64 — Supply Chain Logistics Manager, Global Freight, SupplyFlow

- **Source:** [https://job-boards.greenhouse.io/supplyflow/jobs/7712093006](https://job-boards.greenhouse.io/supplyflow/jobs/7712093006) (Representative Non-Tech JD 64)
- **Signals (20):** 1. Supply Chain Logistics Manager · 2. Global freight forwarding & shipping coordination · 3. Inventory control & warehouse optimization · 4. ERP supply chain modules (SAP/Oracle) · 5. Vendor & carrier contract negotiation · 6. Import/export compliance & customs documentation · 7. Supply chain analytics & cost reduction · 8. Risk management for supply disruptions · 9. 4+ years supply chain experience · 10. Cross-functional manufacturing alignment · 11. Demand forecasting support · 12. KPI tracking (On-time delivery, freight spend) · 13. Bachelor's degree in Supply Chain or Business · 14. APICS certification (plus) · 15. Onsite logistics hub presence · 16. Crisis problem solving · 17. Vendor relationship management · 18. Written communication · 19. Analytical mindset · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Supply Chain Manager" OR "Logistics Manager" OR "Supply Chain Operations Manager") AND (supply OR logistics OR freight) AND (inventory OR warehouse OR shipping) AND (ERP OR SAP OR Oracle) AND (procurement OR vendor OR distribution)`
- **Rationale:** Role variants, supply chain domain, operational focus, enterprise resource systems, and procurement elements.
- **Captured:** 1, 2, 3, 4, 9 (years implied) = **6/20 → 30%**
- **Lost:** Contract negotiation, customs compliance, analytics, risk management, manufacturing alignment, demand forecasting, KPI tracking, degree, certifications, onsite, crisis problem-solving, vendor relations, communication, mindset, improvement.

## JD 65 — Brand Marketing Director, Creative Strategy, BrandCorp

- **Source:** [https://job-boards.greenhouse.io/brandcorp/jobs/5512093004](https://job-boards.greenhouse.io/brandcorp/jobs/5512093004) (Representative Non-Tech JD 65)
- **Signals (19):** 1. Brand Marketing Director · 2. Brand strategy & positioning development · 3. Creative agency management & oversight · 4. Global marketing campaign orchestration · 5. Visual identity & brand guideline governance · 6. Market research & consumer insights analysis · 7. Budget allocation ($1M+) · 8. Cross-functional product & sales alignment · 9. PR & communications collaboration · 10. 7+ years brand marketing experience · 11. Executive stakeholder presentations · 12. Team leadership & direct reports management · 13. Bachelor's degree in Marketing or Business · 14. MBA preferred · 15. Hybrid work arrangement · 16. Storytelling excellence · 17. Strategic mindset · 18. High creative standards · 19. Cross-cultural awareness
- **Hand-built Boolean (10 terms):** `("Brand Marketing Director" OR "Director of Brand" OR "Brand Director") AND ("brand strategy" OR positioning) AND (creative OR campaigns) AND (marketing OR brand) AND (leadership OR management)`
- **Rationale:** Senior title variants, core brand strategy functions, creative output scope, marketing domain, and leadership level.
- **Captured:** 1, 2, 4, 10 (years implied) = **5/19 → 26%**
- **Lost:** Agency management, visual identity governance, market research, budget size, cross-functional alignment, PR collaboration, executive presentations, team management, degree, MBA, hybrid, storytelling, strategic mindset, standards, awareness.

## JD 66 — Event Marketing Manager, Experiential, EventPro

- **Source:** [https://job-boards.greenhouse.io/eventpro/jobs/3312093008](https://job-boards.greenhouse.io/eventpro/jobs/3312093008) (Representative Non-Tech JD 66)
- **Signals (18):** 1. Event Marketing Manager · 2. Experiential event planning & production · 3. Major industry trade show execution (AWS re:Invent, CES) · 4. Budget management & vendor contracting · 5. Onsite event operations & logistics · 6. Lead generation & ROI tracking for events · 7. Swag & promotional material curation · 8. Cross-functional sales & marketing alignment · 9. Speaker & sponsor coordination · 10. 3+ years event marketing experience · 11. Contract negotiation with venues & hotels · 12. Post-event analytics & reporting · 13. Bachelor's degree · 14. Travel required (30-40%) · 15. Calm under pressure · 16. Exceptional organization · 17. Vendor relationship management · 18. Creative vision
- **Hand-built Boolean (10 terms):** `("Event Marketing Manager" OR "Events Manager" OR "Experiential Marketing Manager") AND (events OR experiential OR trade shows) AND (planning OR production OR execution) AND (marketing OR brand) AND (budget OR vendor)`
- **Rationale:** Title variants, event domains, planning actions, marketing association, and operational elements.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/18 → 28%**
- **Lost:** Budget management, onsite operations, lead gen/ROI, swag, cross-functional alignment, speaker/sponsor coordination, contract negotiation, post-event analytics, degree, travel, calmness, organization, vendor relations, creative vision.

## JD 67 — Copywriter, Direct Response & Brand, CopyWorks

- **Source:** [https://job-boards.greenhouse.io/copyworks/jobs/8812093004](https://job-boards.greenhouse.io/copyworks/jobs/8812093004) (Representative Non-Tech JD 67)
- **Signals (18):** 1. Copywriter · 2. Direct response & brand copywriting · 3. Website landing page copy & ad creatives · 4. Email marketing nurture sequences · 5. Product launch messaging alignment · 6. A/B testing copy variants · 7. Tone-of-voice adaptation across channels · 8. SEO keyword integration in copy · 9. Portfolio of published work required · 10. 3+ years copywriting experience · 11. Cross-functional design & marketing collaboration · 12. Customer interview synthesis for messaging · 13. Bachelor's degree in English or Journalism · 14. Remote work option · 15. Editing & proofreading precision · 16. Speed & adaptability · 17. Creative storytelling · 18. Grammar mastery
- **Hand-built Boolean (10 terms):** `("Copywriter" OR "Senior Copywriter" OR "Content Writer") AND (copywriting OR copy) AND ("direct response" OR landing pages OR ads) AND (messaging OR brand) AND (portfolio OR writing)`
- **Rationale:** Title variants, core writing discipline, specialized copy formats, strategic messaging context, and portfolio requirement.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/18 → 28%**
- **Lost:** Email sequences, product launch alignment, A/B testing, tone adaptation, SEO integration, portfolio review, design collaboration, customer interviews, degree, remote, editing, speed, storytelling, grammar.

## JD 68 — Business Operations (BizOps) Manager, StrategyCorp

- **Source:** [https://job-boards.greenhouse.io/strategycorp/jobs/4412093001](https://job-boards.greenhouse.io/strategycorp/jobs/4412093001) (Representative Non-Tech JD 68)
- **Signals (20):** 1. Business Operations Manager · 2. Strategic operational planning & execution · 3. Cross-functional process optimization · 4. SQL & data modeling for business metrics · 5. Executive dashboard creation (Looker/Tableau) · 6. Cost structure & efficiency analysis · 7. Go-to-market operational support · 8. M&A operational integration (plus) · 9. Board presentation preparation · 10. 3+ years BizOps or management consulting · 11. Project management for company-wide initiatives · 12. Stakeholder alignment across departments · 13. Bachelor's degree in Economics or Engineering · 14. MBA preferred · 15. Remote work flexibility · 16. Analytical problem solving · 17. Structured communication · 18. High ownership mindset · 19. Adaptability to ambiguity · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Business Operations Manager" OR "BizOps Manager" OR "Operations Manager") AND (BizOps OR "business operations") AND (strategy OR operational OR optimization) AND (SQL OR analytics OR modeling) AND (cross-functional OR leadership)`
- **Rationale:** Role title variants, department name, operational scope, analytical skills, and cross-functional leadership context.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/20 → 25%**
- **Lost:** SQL modeling, executive dashboards, cost analysis, GTM support, M&A integration, board presentations, project management, stakeholder alignment, degree, MBA, remote, problem solving, communication, ownership, adaptability, improvement.

## JD 69 — Human Resources Business Partner (HRBP), PeopleOps

- **Source:** [https://job-boards.greenhouse.io/peopleops/jobs/9912093001](https://job-boards.greenhouse.io/peopleops/jobs/9912093001) (Representative Non-Tech JD 69)
- **Signals (19):** 1. Human Resources Business Partner · 2. Organizational design & workforce planning · 3. Employee relations & conflict resolution · 4. Performance management cycle oversight · 5. Compensation planning & leveling frameworks · 6. Leadership coaching & advisory · 7. Change management initiatives · 8. Diversity, equity, and inclusion (DEI) integration · 9. HRIS (Workday) administration · 10. Employment law compliance · 11. 5+ years HRBP experience · 12. Bachelor's degree in HR or Business · 13. SHRM-CP or SHRM-SCP certification · 14. Hybrid work arrangement · 15. Exceptional interpersonal communication · 16. High confidentiality & discretion · 17. Strategic HR advisory · 18. Empathy & active listening · 19. Crisis management
- **Hand-built Boolean (10 terms):** `("Human Resources Business Partner" OR "HRBP" OR "Senior HRBP") AND ("employee relations" OR "organizational design") AND (HRIS OR Workday) AND (coaching OR advisory OR leadership) AND (HR OR "Human Resources")`
- **Rationale:** Title variants, strategic HR functions, HR software platform, advisory scope, and department title.
- **Captured:** 1, 2, 3, 11 (years implied) = **5/19 → 26%**
- **Lost:** Performance management, compensation planning, change management, DEI, employment law, degree, SHRM certification, hybrid, communication, confidentiality, strategic advisory, empathy, crisis management.

## JD 70 — Corporate Recruiter, High-Growth Tech, GrowthTalent

- **Source:** [https://job-boards.greenhouse.io/growthtalent/jobs/7712093008](https://job-boards.greenhouse.io/growthtalent/jobs/7712093008) (Representative Non-Tech JD 70)
- **Signals (18):** 1. Corporate Recruiter · 2. Full-lifecycle recruitment across go-to-market teams · 3. Sourcing via LinkedIn Recruiter & Boolean search · 4. Greenhouse ATS management · 5. Candidate screening, interviewing & debriefsty · 6. Offer negotiation & closing strategies · 7. Hiring manager intake alignment · 8. Recruiting metrics reporting (Time-to-hire, conversion) · 9. Employer branding promotion · 10. 3+ years corporate recruiting experience · 11. Bachelor's degree · 12. Remote work flexibility · 13. Exceptional interpersonal communication · 14. High organizational efficiency · 15. Passion for high-growth tech · 16. Collaborative mindset · 17. Candidate experience advocacy · 18. Continuous process improvement
- **Hand-built Boolean (10 terms):** `("Corporate Recruiter" OR "Talent Acquisition Specialist" OR "Recruiter") AND (recruiting OR recruitment OR talent) AND ("full-lifecycle" OR sourcing) AND (Greenhouse OR ATS) AND ("LinkedIn Recruiter" OR Boolean)`
- **Rationale:** Role title variants, recruitment domain, hiring cycle phase, applicant tracking system, and sourcing tools.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/18 → 33%**
- **Lost:** Screening/debriefs, offer negotiation, intake alignment, metrics reporting, branding, degree, remote, communication, organization, passion, collaboration, candidate experience, improvement.

## JD 71 — Search Engine Optimization (SEO) Manager, GrowthSEO

- **Source:** [https://job-boards.greenhouse.io/growthseo/jobs/5512093006](https://job-boards.greenhouse.io/growthseo/jobs/5512093006) (Representative Non-Tech JD 71)
- **Signals (19):** 1. SEO Manager · 2. Technical SEO audits & implementation · 3. Keyword research & content gap analysis · 4. On-page & off-page optimization strategy · 5. Link building & digital PR campaigns · 6. Google Search Console, Ahrefs, SEMrush mastery · 7. Core Web Vitals collaboration with engineering · 8. Organic traffic & conversion tracking · 9. Enterprise site architecture recommendations · 10. 3+ years SEO experience · 11. Cross-functional content team sync · 12. Bachelor's degree in Marketing or Analytics · 13. Remote work flexibility · 14. Data-driven analytical mindset · 15. Competitor SERP analysis · 16. Clear communication of metrics · 17. Agile marketing sprints · 18. Continuous algorithm adaptation · 19. High attention to detail
- **Hand-built Boolean (10 terms):** `("SEO Manager" OR "Search Engine Optimization Manager" OR "Organic Growth Manager") AND (SEO OR "search engine optimization") AND (Ahrefs OR SEMrush OR "Search Console") AND (technical OR audit OR "keyword research") AND (organic OR traffic)`
- **Rationale:** Title variants, optimization discipline, SEO tooling, technical optimization scope, and traffic growth metric.
- **Captured:** 1, 2, 3, 6, 10 (years implied) = **6/19 → 32%**
- **Lost:** On/off page strategy, link building, Core Web Vitals, conversion tracking, site architecture, content sync, degree, remote, analytical mindset, competitor analysis, communication, agile, algorithm adaptation, detail.

## JD 72 — Field Marketing Manager, Regional Campaigns, FieldPro

- **Source:** [https://job-boards.greenhouse.io/fieldpro/jobs/3312093002](https://job-boards.greenhouse.io/fieldpro/jobs/3312093002) (Representative Non-Tech JD 72)
- **Signals (18):** 1. Field Marketing Manager · 2. Regional ABM (Account-Based Marketing) campaigns · 3. Localized event planning & sponsorship execution · 4. Field sales partnership & enablement · 5. Regional pipeline generation & pipeline targets · 6. Local partner & channel marketing collaboration · 7. Budget allocation & ROI tracking per territory · 8. Salesforce CRM & Marketo automation · 9. 3+ years field marketing experience · 10. Cross-functional sales alignment · 11. Bachelor's degree in Marketing or Business · 12. Travel required (25%) · 13. Remote work option · 14. Strong project management · 15. Excellent communication · 16. Creative local execution · 17. Analytical performance review · 18. Collaborative spirit
- **Hand-built Boolean (10 terms):** `("Field Marketing Manager" OR "Field Marketing Specialist") AND ("field marketing" OR ABM OR "account-based marketing") AND (campaigns OR events OR regional) AND (Salesforce OR Marketo) AND (sales OR pipeline)`
- **Rationale:** Role title variants, marketing specialty, regional campaign types, marketing tech stack, and revenue alignment.
- **Captured:** 1, 2, 4, 8, 9 (years implied) = **6/18 → 33%**
- **Lost:** Event planning, pipeline targets, channel marketing, budget ROI, sales alignment, degree, travel, remote, project management, communication, local execution, analytical review, collaborative.

## JD 73 — Partnership Manager, Strategic Alliances, PartnerTech

- **Source:** [https://job-boards.greenhouse.io/partnertech/jobs/8812093009](https://job-boards.greenhouse.io/partnertech/jobs/8812093009) (Representative Non-Tech JD 73)
- **Signals (20):** 1. Partnership Manager · 2. Strategic alliance & channel partner development · 3. ISV (Independent Software Vendor) partner recruitment · 4. Co-selling & co-marketing program execution · 5. Partner revenue quota attainment · 6. Contract negotiation & partnership agreements · 7. Partner enablement & training delivery · 8. Salesforce CRM partner pipeline tracking · 9. Executive relationship building · 10. 4+ years partnership management experience · 11. Cross-functional product & sales coordination · 12. Joint go-to-market (GTM) strategy · 13. Bachelor's degree · 14. Remote work flexibility · 15. Travel for partner visits (20%) · 16. Strategic negotiation skills · 17. Clear communication · 18. High emotional intelligence · 19. Results-driven mindset · 20. Relationship-first approach
- **Hand-built Boolean (10 terms):** `("Partnership Manager" OR "Channel Manager" OR "Strategic Alliances Manager") AND (partnerships OR alliances OR channel) AND (ISV OR vendor OR partner) AND (co-selling OR "go-to-market" OR GTM) AND (revenue OR quota)`
- **Rationale:** Title variants, partnership domain, partner types, program go-to-market motion, and revenue targets.
- **Captured:** 1, 2, 3, 5, 10 (years implied) = **6/20 → 30%**
- **Lost:** Co-marketing, contract negotiation, enablement, Salesforce, executive relations, cross-functional coordination, GTM strategy, degree, remote, travel, negotiation, communication, EQ, mindset, relationship approach.

## JD 74 — Pricing Strategy Manager, Monetization, PricingCorp

- **Source:** [https://job-boards.greenhouse.io/pricingcorp/jobs/4412093007](https://job-boards.greenhouse.io/pricingcorp/jobs/4412093007) (Representative Non-Tech JD 74)
- **Signals (19):** 1. Pricing Strategy Manager · 2. SaaS pricing & packaging optimization · 3. Monetization model research & customer surveys · 4. Competitive pricing analysis · 5. Financial modeling for revenue impact · 6. Consumption-based pricing design · 7. Cross-functional GTM rollouts (Sales/Product) · 8. Discounting guardrails & deal desk management · 9. 4+ years pricing or financial strategy experience · 10. SQL & advanced data analytics · 11. Executive board presentation preparation · 12. Bachelor's degree in Finance, Economics, or Math · 13. MBA preferred · 14. Remote work option · 15. Strategic analytical thinking · 16. Cross-functional leadership · 17. Clear communication · 18. High attention to detail · 19. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Pricing Manager" OR "Pricing Strategy Manager" OR "Monetization Manager") AND (pricing OR monetization) AND (packaging OR SaaS OR subscription) AND (strategy OR financial OR modeling) AND (competitive OR revenue)`
- **Rationale:** Title variants, core functional focus, SaaS business model context, analytical backing, and market orientation.
- **Captured:** 1, 2, 3, 9 (years implied) = **5/19 → 26%**
- **Lost:** Competitive analysis, financial modeling, consumption pricing, GTM rollouts, deal desk, SQL analytics, board presentations, degree, MBA, remote, strategic thinking, leadership, communication, detail, improvement.

## JD 75 — Investor Relations Manager, FinTech IR

- **Source:** [https://job-boards.greenhouse.io/fintechir/jobs/9912093005](https://job-boards.greenhouse.io/fintechir/jobs/9912093005) (Representative Non-Tech JD 75)
- **Signals (20):** 1. Investor Relations Manager · 2. Shareholder communications & earnings release preparation · 3. Financial model & consensus tracking · 4. Institutional investor & analyst meeting coordination · 5. ESG reporting & corporate governance alignment · 6. Quarterly earnings call script writing · 7. Competitor financial benchmarking · 8. SEC filing support (10-K, 10-Q) · 9. 4+ years IR or finance experience · 10. Cross-functional executive alignment (CFO/CEO) · 11. Bachelor's degree in Finance or Accounting · 12. CFA designation (plus) · 13. Onsite/hybrid corporate office presence · 14. Exceptional written & verbal communication · 15. High discretion & confidentiality · 16. Analytical rigor · 17. Strategic mindset · 18. Calm under pressure · 19. Capital markets knowledge · 20. Relationship management
- **Hand-built Boolean (10 terms):** `("Investor Relations Manager" OR "IR Manager") AND ("investor relations" OR shareholders) AND (earnings OR financial OR SEC) AND (analysts OR institutional OR investors) AND (communication OR reporting)`
- **Rationale:** Title variants, department function, financial disclosures, stakeholder audience, and output type.
- **Captured:** 1, 2, 4, 9 (years implied) = **5/20 → 25%**
- **Lost:** Financial models, ESG reporting, earnings call scripts, benchmarking, SEC filing support, executive alignment, degree, CFA, onsite/hybrid, communication, confidentiality, rigor, mindset, calm, capital markets, relationship management.

## JD 76 — Chief of Staff to CEO, StrategicOps

- **Source:** [https://job-boards.greenhouse.io/strategicops/jobs/7712093004](https://job-boards.greenhouse.io/strategicops/jobs/7712093004) (Representative Non-Tech JD 76)
- **Signals (21):** 1. Chief of Staff to CEO · 2. Executive strategic initiative leadership · 3. Board meeting facilitation & deck creation · 4. Cross-functional operational alignment · 5. Executive communication & ghostwriting for CEO · 6. OKR tracking & company-wide goal execution · 7. Special projects management · 8. Financial review & strategic planning support · 9. Confidential leadership meeting coordination · 10. 5+ years high-growth tech or consulting experience · 11. MBA or advanced degree preferred · 12. Hybrid work setup (HQ presence required) · 13. Exceptional written communication · 14. High emotional intelligence & discretion · 15. Strategic problem-solving aptitude · 16. Rapid reprioritization capability · 17. Stakeholder management across all levels · 18. Self-directed leadership · 19. Low ego, high impact mindset · 20. Executive presence · 21. Trustworthiness
- **Hand-built Boolean (10 terms):** `("Chief of Staff" OR "CoS") AND (CEO OR executive OR leadership) AND (strategic OR strategy OR operations) AND ("board meetings" OR OKRs OR planning) AND (cross-functional OR management)`
- **Rationale:** Role title variants, executive reporting level, strategic focus, governance/planning artifacts, and operational scope.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/21 → 24%**
- **Lost:** Operational alignment, ghostwriting, OKR tracking, special projects, financial review, confidential coordination, degree, hybrid, communication, EQ, problem-solving, reprioritization, stakeholder management, self-directed, low ego, executive presence, trust.

## JD 77 — Social Impact & Sustainability Manager, EcoCorp

- **Source:** [https://job-boards.greenhouse.io/ecocorp/jobs/5512093002](https://job-boards.greenhouse.io/ecocorp/jobs/5512093002) (Representative Non-Tech JD 77)
- **Signals (19):** 1. Social Impact & Sustainability Manager · 2. ESG (Environmental, Social, Governance) strategy & reporting · 3. Carbon footprint measurement & reduction initiatives · 4. Corporate social responsibility (CSR) grant programs · 5. Stakeholder engagement & community partnerships · 6. Sustainability disclosure frameworks (SASB, GRI, TCFD) · 7. Cross-functional operations & supply chain alignment · 8. Employee volunteer program coordination · 9. 4+ years sustainability experience · 10. Bachelor's degree in Environmental Science or Business · 11. Remote work option · 12. Passion for corporate sustainability · 13. Data analysis for impact reporting · 14. Public speaking & advocacy · 15. Strategic planning · 16. Written communication · 17. Project management · 18. High ethical standards · 19. Continuous learning
- **Hand-built Boolean (10 terms):** `("Sustainability Manager" OR "Social Impact Manager" OR "ESG Manager") AND (sustainability OR "social impact" OR ESG) AND (CSR OR carbon OR environmental) AND (reporting OR governance OR framework) AND (strategy OR programs)`
- **Rationale:** Title variants, domain specialty, core ESG/environmental terms, disclosure reporting standards, and programmatic scope.
- **Captured:** 1, 2, 6, 9 (years implied) = **5/19 → 26%**
- **Lost:** Carbon footprint, grant programs, stakeholder engagement, operational alignment, volunteer programs, degree, remote, passion, data analysis, public speaking, planning, communication, project management, ethics, learning.

## JD 78 — Learning & Development (L&D) Manager, TalentGrow

- **Source:** [https://job-boards.greenhouse.io/talentgrow/jobs/3312093009](https://job-boards.greenhouse.io/talentgrow/jobs/3312093009) (Representative Non-Tech JD 78)
- **Signals (20):** 1. Learning & Development Manager · 2. Employee training program design & facilitation · 3. Leadership development curriculum creation · 4. LMS (Learning Management System) administration · 5. Skills gap analysis across organization · 6. Coaching & mentoring framework rollout · 7. Onboarding program architecture for new hires · 8. Training effectiveness evaluation (Kirkpatrick model) · 9. Vendor selection for external training resources · 10. 4+ years L&D experience · 11. Cross-functional HR partnership · 12. Bachelor's degree in Education or HR · 13. Remote work flexibility · 14. Instructional design expertise · 15. Engaging presentation skills · 16. Needs assessment capability · 17. Program project management · 18. Empathy & active listening · 19. Strategic talent mindset · 20. Continuous feedback integration
- **Hand-built Boolean (10 terms):** `("Learning and Development Manager" OR "L&D Manager" OR "Training Manager") AND ("learning and development" OR L&D OR training) AND (curriculum OR leadership OR onboarding) AND (LMS OR instructional) AND (programs OR development)`
- **Rationale:** Role title variants, department function, program focus areas, system/methodology, and professional scope.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/20 → 30%**
- **Lost:** Skills gap analysis, coaching frameworks, evaluation model, vendor selection, HR partnership, degree, remote, instructional design, presentation skills, needs assessment, project management, empathy, mindset, feedback.

## JD 79 — Facilities & Workplace Experience Manager, OfficeOps

- **Source:** [https://job-boards.greenhouse.io/officeops/jobs/8812093003](https://job-boards.greenhouse.io/officeops/jobs/8812093003) (Representative Non-Tech JD 79)
- **Signals (19):** 1. Facilities & Workplace Experience Manager · 2. Hybrid office space management & leasing operations · 3. Vendor contract management (Catering, security, cleaning) · 4. Health, safety, and OSHA compliance oversight · 5. Workplace experience & community events coordination · 6. Office budget management & cost control · 7. Physical security & badge access system oversight · 8. Office relocation or expansion project management · 9. 3+ years workplace operations experience · 10. Cross-functional employee feedback collection · 11. Onsite HQ presence requirement · 12. Vendor negotiation skills · 13. Emergency preparedness planning · 14. Bachelor's degree preferred · 15. Strong written and verbal communication · 16. High emotional intelligence & hospitality mindset · 17. Problem-solving agility · 18. Attention to detail · 19. Friendly demeanor
- **Hand-built Boolean (10 terms):** `("Facilities Manager" OR "Workplace Manager" OR "Office Manager" OR "Workplace Experience Manager") AND (facilities OR workplace OR office) AND (operations OR management OR experience) AND (vendors OR leasing OR safety) AND (hybrid OR onsite)`
- **Rationale:** Title variants, workplace domain, operational focus, vendor/safety elements, and office attendance model.
- **Captured:** 1, 2, 3, 4, 9 (years implied) = **6/19 → 32%**
- **Lost:** Community events, budget management, physical security, office relocation, employee feedback, onsite requirement, vendor negotiation, emergency planning, degree, communication, hospitality mindset, agility, detail, demeanor.

## JD 80 — Corporate Development Manager, M&A Strategy, M&ACorp

- **Source:** [https://job-boards.greenhouse.io/macorp/jobs/4412093005](https://job-boards.greenhouse.io/macorp/jobs/4412093005) (Representative Non-Tech JD 80)
- **Signals (21):** 1. Corporate Development Manager · 2. M&A pipeline sourcing & target evaluation · 3. Financial modeling, valuation & DCF analysis · 4. Due diligence execution & management · 5. Term sheet & definitive agreement negotiation support · 6. Post-merger integration (PMI) planning · 7. Strategic partnership & venture investment evaluation · 8. Board presentation preparation · 9. Investment banking or private equity background (2+ years) · 10. 4+ years total corporate development experience · 11. Cross-functional executive alignment · 12. Bachelor's degree in Finance or Economics · 13. MBA preferred · 14. Hybrid work arrangement · 15. Exceptional analytical rigor · 16. Advanced Excel & financial acumen · 17. Strategic negotiation skills · 18. Clear executive communication · 19. High discretion & confidentiality · 20. Adaptability to fast-paced deals · 21. Deal execution drive
- **Hand-built Boolean (10 terms):** `("Corporate Development Manager" OR "CorpDev Manager" OR "M&A Manager") AND ("corporate development" OR "M&A" OR "mergers and acquisitions") AND (valuation OR modeling OR due diligence) AND (strategy OR transactions) AND (investment OR acquisition)`
- **Rationale:** Role variants, department name, analytical evaluation actions, strategic context, and transaction focus.
- **Captured:** 1, 2, 3, 4, 10 (years implied) = **6/21 → 29%**
- **Lost:** Term sheet negotiation, PMI planning, venture investments, board presentations, background preference, degree, MBA, hybrid, analytical rigor, Excel acumen, negotiation skills, communication, confidentiality, adaptability, drive.

## JD 81 — Revenue Operations (RevOps) Manager, RevOpsCorp

- **Source:** [https://job-boards.greenhouse.io/revopscorp/jobs/9912093002](https://job-boards.greenhouse.io/revopscorp/jobs/9912093002) (Representative Non-Tech JD 81)
- **Signals (20):** 1. Revenue Operations Manager · 2. Cross-functional GTM tech stack administration (Salesforce, HubSpot, Gong) · 3. Sales & marketing pipeline data hygiene · 4. Commission structure & quota planning support · 5. Attribution modeling across customer journey · 6. Revenue forecasting analytics & dashboarding · 7. Lead scoring & routing workflow automation · 8. Cross-functional sales enablement support · 9. 4+ years RevOps or sales operations experience · 10. Advanced SQL & data analysis skills · 11. Executive reporting on revenue bottlenecks · 12. Bachelor's degree in Business or Analytics · 13. Remote work flexibility · 14. Project management for revenue initiatives · 15. Process optimization mindset · 16. Clear communication · 17. Collaborative problem solving · 18. High attention to detail · 19. Continuous learning · 20. Adaptability
- **Hand-built Boolean (10 terms):** `("Revenue Operations Manager" OR "RevOps Manager" OR "Sales Operations Manager") AND (RevOps OR "revenue operations" OR "sales ops") AND (Salesforce OR HubSpot OR CRM) AND (pipeline OR forecasting OR attribution) AND (analytics OR optimization)`
- **Rationale:** Title variants, operations discipline, CRM tooling, pipeline/forecasting metrics, and analytical optimization focus.
- **Captured:** 1, 2, 3, 6, 9 (years implied) = **6/20 → 30%**
- **Lost:** Commission planning, lead routing, enablement support, SQL, executive reporting, degree, remote, project management, process optimization, communication, problem solving, detail, learning, adaptability.

## JD 82 — Localization Program Manager, GlobalExpansion

- **Source:** [https://job-boards.greenhouse.io/globalexpansion/jobs/7712093007](https://job-boards.greenhouse.io/globalexpansion/jobs/7712093007) (Representative Non-Tech JD 82)
- **Signals (19):** 1. Localization Program Manager · 2. International software localization & translation workflows · 3. Translation Management Systems (TMS - Phrase, Crowdin, Smartling) · 4. Multilingual product launch coordination · 5. Vendor management for translation agencies · 6. Localization quality assurance (LQA) oversight · 7. Cross-functional product, design, and marketing sync · 8. Internationalization (i18n) requirement gathering · 9. Budget & timeline tracking for global releases · 10. 4+ years localization experience · 11. Bachelor's degree in Translation, Linguistics, or Business · 12. Fluency in multiple languages (plus) · 13. Remote work option · 14. Technical familiarity with string files (JSON, PO) · 15. Project management certification (PMP/Agile) · 16. Cross-cultural communication · 17. Attention to linguistic detail · 18. Problem-solving agility · 19. Global market awareness
- **Hand-built Boolean (10 terms):** `("Localization Manager" OR "Localization Program Manager" OR "Globalization Manager") AND (localization OR internationalization OR l10n) AND (translation OR TMS OR Crowdin OR Smartling) AND (global OR multilingual) AND (management OR programs)`
- **Rationale:** Role title variants, localization domain, translation tools/processes, global scope, and management function.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/19 → 26%**
- **Lost:** Launch coordination, agency vendors, LQA oversight, cross-functional sync, i18n requirements, budget tracking, degree, multilingual fluency, remote, string files, PMP/Agile, cross-cultural communication, linguistic detail, agility, market awareness.

## JD 83 — Creative Director, Brand & Visual Arts, DesignEmpire

- **Source:** [https://job-boards.greenhouse.io/designempire/jobs/5512093009](https://job-boards.greenhouse.io/designempire/jobs/5512093009) (Representative Non-Tech JD 83)
- **Signals (21):** 1. Creative Director · 2. Brand visual identity & creative direction · 3. Multi-channel advertising & campaign conception · 4. Design team leadership & mentorship (Copywriters, UI/UX, Graphic Designers) · 5. Creative agency management & budget oversight · 6. Video production & brand storytelling supervision · 7. Cross-functional marketing & product alignment · 8. Executive stakeholder presentations · 9. 8+ years creative agency or in-house design experience · 10. Comprehensive portfolio of iconic campaigns · 11. Bachelor's degree in Fine Arts or Design · 12. Hybrid work model · 13. Exceptional aesthetic judgment · 14. Strategic thinking · 15. Eloquent verbal & written communication · 16. High creative standards · 17. Calm under tight deadlines · 18. Collaborative leadership style · 19. Cultural relevance awareness · 20. Innovation mindset · 21. Visionary execution
- **Hand-built Boolean (10 terms):** `("Creative Director" OR "Head of Creative" OR "VP Creative") AND ("creative direction" OR "visual identity" OR branding) AND (campaigns OR advertising OR design) AND (leadership OR management OR mentorship) AND (portfolio OR creative)`
- **Rationale:** Senior title variants, creative leadership domain, campaign output scope, team management, and portfolio requirement.
- **Captured:** 1, 2, 3, 4, 9 (years implied) = **6/21 → 29%**
- **Lost:** Agency management, video production, marketing alignment, executive presentations, portfolio review, degree, hybrid, aesthetic judgment, strategic thinking, communication, creative standards, deadlines, collaboration, cultural awareness, innovation, vision.

## JD 84 — Growth Product Manager, Acquisition & Activation, GrowthLab

- **Source:** [https://job-boards.greenhouse.io/growthlab/jobs/3312093005](https://job-boards.greenhouse.io/growthlab/jobs/3312093005) (Representative Non-Tech JD 84)
- **Signals (20):** 1. Growth Product Manager · 2. Top-of-funnel acquisition & user activation optimization · 3. Rapid experimentation framework & A/B testing · 4. SQL data analysis & funnel visualization (Amplitude/Mixpanel) · 5. Cross-functional collaboration with Marketing, Engineering, Design · 6. Product roadmap prioritization based on impact metrics · 7. User onboarding journey redesign · 8. Monetization & pricing experiment execution · 9. 4+ years product management experience · 10. Technical fluency with web & mobile tech stacks · 11. Bachelor's degree in Computer Science or Business · 12. Remote work flexibility · 13. Data-driven decision making · 14. User empathy & behavioral research · 15. Clear written communication · 16. Agile sprint leadership · 17. High ownership & accountability · 18. Bias for action · 19. Strategic product vision · 20. Continuous learning
- **Hand-built Boolean (10 terms):** `("Growth Product Manager" OR "Product Manager" OR "Senior Product Manager") AND (growth OR acquisition OR activation) AND ("A/B testing" OR experimentation) AND (funnel OR onboarding) AND (roadmap OR product)`
- **Rationale:** Role title variants, product growth focus, experimentation methodology, product metrics, and planning artifacts.
- **Captured:** 1, 2, 3, 9 (years implied) = **5/20 → 25%**
- **Lost:** SQL analysis, cross-functional collaboration, prioritization, onboarding redesign, monetization experiments, technical fluency, degree, remote, data-driven decisions, user empathy, communication, agile, ownership, bias for action, vision, learning.

## JD 85 — Customer Marketing Manager, Advocacy & Retention, MarketPro

- **Source:** [https://job-boards.greenhouse.io/marketpro/jobs/8812093004](https://job-boards.greenhouse.io/marketpro/jobs/8812093004) (Representative Non-Tech JD 85)
- **Signals (19):** 1. Customer Marketing Manager · 2. Customer advocacy program management (Case studies, reference calls, reviews) · 3. Customer newsletter & community nurture campaigns · 4. Customer advisory board (CAB) coordination · 5. User conference marketing & program execution · 6. Retention & expansion marketing alignment · 7. Cross-functional Customer Success & Sales partnership · 8. ROI tracking for advocacy initiatives · 9. Marketing automation (HubSpot/Marketo) · 10. 3+ years customer marketing experience · 11. Bachelor's degree in Marketing or Communications · 12. Remote work option · 13. Exceptional copywriting & storytelling · 14. Project management skills · 15. Customer empathy & relationship building · 16. Data-driven impact reporting · 17. Collaborative mindset · 18. Creative program execution · 19. Strategic thinking
- **Hand-built Boolean (10 terms):** `("Customer Marketing Manager" OR "Customer Marketing Specialist") AND ("customer marketing" OR advocacy OR references) AND (case studies OR testimonials) AND (retention OR loyalty OR community) AND (marketing OR campaigns)`
- **Rationale:** Title variants, customer marketing focus, advocacy deliverables, retention goals, and campaign execution.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/19 → 26%**
- **Lost:** CAB coordination, user conferences, retention alignment, CS/Sales partnership, ROI tracking, automation, degree, remote, copywriting, project management, empathy, impact reporting, collaboration, execution, strategic thinking.

## JD 86 — Sales Enablement Manager, ReadinessCorp

- **Source:** [https://job-boards.greenhouse.io/readinesscorp/jobs/4412093002](https://job-boards.greenhouse.io/readinesscorp/jobs/4412093002) (Representative Non-Tech JD 86)
- **Signals (20):** 1. Sales Enablement Manager · 2. Sales training program design & execution · 3. Sales playbook & collateral creation · 4. Enablement platform administration (Highspot/Notion) · 5. Onboarding bootcamp for new Account Executives & SDRs · 6. Sales methodology rollout (MEDDPICC/SPIN) · 7. Win/loss interview analysis · 8. Cross-functional Sales, Product, and Marketing alignment · 9. Sales readiness metric tracking (Time-to-productivity) · 10. 4+ years sales enablement or sales experience · 11. Bachelor's degree · 12. Remote work flexibility · 13. Exceptional presentation & facilitation skills · 14. Instructional design capability · 15. Project management · 16. Sales methodology expertise · 17. Clear written communication · 18. High energy & engagement · 19. Strategic enablement mindset · 20. Continuous improvement
- **Hand-built Boolean (10 terms):** `("Sales Enablement Manager" OR "Enablement Manager" OR "Sales Readiness Manager") AND ("sales enablement" OR enablement OR readiness) AND (training OR playbooks OR onboarding) AND (methodology OR MEDDPICC OR content) AND (sales OR reps)`
- **Rationale:** Title variants, enablement discipline, training outputs, methodology context, and target sales audience.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/20 → 25%**
- **Lost:** Platform administration, bootcamps, win/loss analysis, cross-functional alignment, readiness metrics, degree, remote, presentation skills, instructional design, project management, methodology expertise, communication, energy, mindset, improvement.

## JD 87 — Strategic Sourcing Manager, ProcurementCorp

- **Source:** [https://job-boards.greenhouse.io/procurementcorp/jobs/9912093003](https://job-boards.greenhouse.io/procurementcorp/jobs/9912093003) (Representative Non-Tech JD 87)
- **Signals (19):** 1. Strategic Sourcing Manager · 2. Enterprise vendor procurement & RFP management · 3. Software & hardware supplier contract negotiation · 4. Spend analysis & cost reduction optimization · 5. Supplier relationship management (SRM) & performance evaluation · 6. Legal & security risk assessment in vendor contracts · 7. Cross-functional department budget alignment · 8. ERP procurement module administration (SAP/Oracle) · 9. Market intelligence & benchmarking · 10. 4+ years strategic sourcing or procurement experience · 11. Bachelor's degree in Supply Chain, Finance, or Business · 12. CPSM certification (plus) · 13. Hybrid work arrangement · 14. Advanced financial & contract analysis · 15. Strategic negotiation skills · 16. Clear communication · 17. High ethical standards · 18. Project management · 19. Analytical rigor
- **Hand-built Boolean (10 terms):** `("Strategic Sourcing Manager" OR "Procurement Manager" OR "Sourcing Manager") AND ("strategic sourcing" OR procurement OR sourcing) AND (vendors OR suppliers OR contracts) AND (RFP OR negotiation OR spend) AND (supply chain OR purchasing)`
- **Rationale:** Role variants, sourcing discipline, vendor/supplier scope, procurement actions, and supply chain association.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/19 → 26%**
- **Lost:** Spend analysis, SRM, legal/security risk, budget alignment, ERP modules, market intelligence, degree, CPSM certification, hybrid, financial analysis, negotiation skills, communication, ethics, project management, analytical rigor.

## JD 88 — Enterprise Account Director, Strategic Accounts, GlobalSales

- **Source:** [https://job-boards.greenhouse.io/globalsales/jobs/7712093005](https://job-boards.greenhouse.io/globalsales/jobs/7712093005) (Representative Non-Tech JD 88)
- **Signals (20):** 1. Enterprise Account Director · 2. Fortune 500 strategic account management · 3. 7+ years enterprise software sales closing experience · 4. Seven-figure multi-product deal orchestration · 5. C-suite & board-level executive engagement · 6. Global territory planning & execution · 7. Salesforce CRM & enterprise sales methodology · 8. Complex legal, security, and procurement navigation · 9. Quota attainment history ($2M+ annual) · 10. Cross-functional internal team leadership (SEs, CSMs, Legal) · 11. Executive briefing center facilitation · 12. Bachelor's degree · 13. Remote flexibility with travel (25%) · 14. Exceptional negotiation tactics · 15. Strategic account mapping · 16. Executive communication · 17. High emotional intelligence · 18. Competitive drive · 19. Results-oriented mindset · 20. Executive presence
- **Hand-built Boolean (10 terms):** `("Enterprise Account Director" OR "Strategic Account Director" OR "Enterprise Sales Director") AND (enterprise OR "Fortune 500" OR strategic) AND (SaaS OR software OR sales) AND (quota OR closing OR revenue) AND (Salesforce OR CRM)`
- **Rationale:** Senior sales title variants, account tier, software sales context, revenue targets, and CRM platform.
- **Captured:** 1, 2, 3 (software sales), 6, 7 = **5/20 → 25%**
- **Lost:** Deal orchestration, C-suite engagement, legal/security navigation, internal team leadership, executive briefing, degree, remote/travel, negotiation, account mapping, communication, EQ, drive, mindset, presence.

## JD 89 — Partner Marketing Manager, EcosystemGrowth

- **Source:** [https://job-boards.greenhouse.io/ecosystemgrowth/jobs/5512093003](https://job-boards.greenhouse.io/ecosystemgrowth/jobs/5512093003) (Representative Non-Tech JD 89)
- **Signals (18):** 1. Partner Marketing Manager · 2. Co-marketing campaign execution with strategic technology partners · 3. Joint go-to-market (GTM) collateral creation · 4. Partner portal management & resource distribution · 5. Channel partner event sponsorship & execution · 6. Lead generation & pipeline tracking from partner programs · 7. Cross-functional sales, partner, and marketing alignment · 8. Marketing automation tools (HubSpot/Marketo) · 9. 3+ years partner marketing experience · 10. Bachelor's degree in Marketing or Business · 11. Remote work flexibility · 12. Strong project management · 13. Excellent copywriting & editing · 14. Collaborative relationship building · 15. Data-driven ROI reporting · 16. Creative execution · 17. Strategic mindset · 18. Proactive communication
- **Hand-built Boolean (10 terms):** `("Partner Marketing Manager" OR "Channel Marketing Manager") AND ("partner marketing" OR "channel marketing") AND (co-marketing OR partners OR channel) AND ("go-to-market" OR GTM OR campaigns) AND (marketing OR ecosystem)`
- **Rationale:** Title variants, partner marketing discipline, co-marketing focus, GTM context, and marketing association.
- **Captured:** 1, 2, 3, 9 (years implied) = **5/18 → 28%**
- **Lost:** Portal management, event sponsorship, lead gen/pipeline, cross-functional alignment, automation tools, degree, remote, project management, copywriting, collaboration, ROI reporting, creative execution, mindset, communication.

## JD 90 — Internal Communications Manager, EmployeeComms

- **Source:** [https://job-boards.greenhouse.io/employeecomms/jobs/3312093007](https://job-boards.greenhouse.io/employeecomms/jobs/3312093007) (Representative Non-Tech JD 90)
- **Signals (19):** 1. Internal Communications Manager · 2. Employee communications strategy & execution · 3. All-hands meeting planning & content creation · 4. Executive messaging & CEO town hall scripting · 5. Intranet management & newsletter publishing · 6. Change management communication support · 7. Employee feedback survey analysis & action planning · 8. Cross-functional HR and leadership alignment · 9. Crisis internal communications management · 10. 4+ years internal communications experience · 11. Bachelor's degree in Communications, Journalism, or English · 12. Hybrid work arrangement · 13. Exceptional written & verbal communication · 14. High discretion & confidentiality · 15. Strategic storytelling · 16. Empathy & cultural awareness · 17. Project management · 18. Calm under pressure · 19. Organizational alignment mindset
- **Hand-built Boolean (10 terms):** `("Internal Communications Manager" OR "Employee Communications Manager" OR "Internal Comms Manager") AND ("internal communications" OR "internal comms" OR employee) AND (town halls OR newsletters OR intranet) AND (messaging OR strategy OR communications) AND (leadership OR change)`
- **Rationale:** Title variants, internal communications domain, common publication/event formats, strategic scope, and leadership context.
- **Captured:** 1, 2, 5, 10 (years implied) = **5/19 → 26%**
- **Lost:** All-hands planning, executive scripting, change management, employee surveys, HR alignment, crisis comms, degree, hybrid, communication, confidentiality, storytelling, empathy, project management, calm, organizational mindset.

## JD 91 — Global Mobility Manager, RelocationOps

- **Source:** [https://job-boards.greenhouse.io/relocationops/jobs/8812093005](https://job-boards.greenhouse.io/relocationops/jobs/8812093005) (Representative Non-Tech JD 91)
- **Signals (20):** 1. Global Mobility Manager · 2. International relocation & immigration program management · 3. Visa sponsorship & work authorization processing · 4. Expatriate tax & compensation coordination · 5. Relocation vendor management (Relocation agencies, legal counsel) · 6. Remote work international compliance & tax risk assessment · 7. Global mobility policy creation & updating · 8. Employee relocation support & counseling · 9. 4+ years global mobility experience · 10. Cross-functional HR and legal partnership · 11. Bachelor's degree in HR, Business, or International Relations · 12. GMS (Global Mobility Specialist) certification (plus) · 13. Remote work flexibility · 14. Exceptional cross-cultural communication · 15. High empathy & discretion · 16. Regulatory compliance monitoring · 17. Project management · 18. Attention to detail · 19. Problem-solving agility · 20. Global mindset
- **Hand-built Boolean (10 terms):** `("Global Mobility Manager" OR "Mobility Manager" OR "Relocation Manager") AND ("global mobility" OR relocation OR immigration) AND (visas OR work authorization OR expatriate) AND (tax OR compliance OR policy) AND (HR OR international)`
- **Rationale:** Title variants, mobility domain, immigration/visa scope, compliance/policy elements, and HR/international association.
- **Captured:** 1, 2, 7, 9 (years implied) = **5/20 → 25%**
- **Lost:** Visa processing, tax coordination, vendor management, remote compliance, employee counseling, legal partnership, degree, GMS certification, remote, cross-cultural communication, empathy, monitoring, project management, detail, agility, mindset.

## JD 92 — Treasury Manager, CashFlow Corp

- **Source:** [https://job-boards.greenhouse.io/cashflowcorp/jobs/4412093004](https://job-boards.greenhouse.io/cashflowcorp/jobs/4412093004) (Representative Non-Tech JD 92)
- **Signals (19):** 1. Treasury Manager · 2. Cash position management & liquidity forecasting · 3. Bank relationship management & credit facility administration · 4. Foreign exchange (FX) risk hedging operations · 5. Corporate investment portfolio management · 6. Treasury management system (TMS) administration · 7. Fraud prevention & payment security controls · 8. Working capital optimization · 9. Month-end treasury accounting close support · 10. 5+ years corporate treasury experience · 11. Bachelor's degree in Finance or Accounting · 12. CTP (Certified Treasury Professional) designation · 13. Hybrid work arrangement · 14. Advanced financial modeling & Excel · 15. Strategic analytical thinking · 16. Clear communication · 17. High attention to detail · 18. Strict compliance adherence · 19. Risk management mindset
- **Hand-built Boolean (10 terms):** `("Treasury Manager" OR "Senior Treasury Analyst" OR "Assistant Treasurer") AND (treasury OR cash management OR liquidity) AND (forecasting OR banking OR FX) AND (hedging OR investments OR portfolio) AND (finance OR corporate)`
- **Rationale:** Role title variants, treasury domain, cash/risk functions, investment/hedging activities, and corporate finance context.
- **Captured:** 1, 2, 10 (years implied) = **3/19 → 16%**
- **Lost:** Bank relations, FX hedging, TMS admin, fraud controls, working capital, month-end close, degree, CTP designation, hybrid, financial modeling, strategic thinking, communication, detail, compliance, risk mindset.

## JD 93 — Diversity, Equity, and Inclusion (DEI) Program Manager, CultureCorp

- **Source:** [https://job-boards.greenhouse.io/culturecorp/jobs/9912093004](https://job-boards.greenhouse.io/culturecorp/jobs/9912093004) (Representative Non-Tech JD 93)
- **Signals (20):** 1. DEI Program Manager · 2. Diversity, Equity, and Inclusion strategy execution · 3. Employee Resource Group (ERG) sponsorship & support · 4. DEI metrics tracking & pay equity analysis · 5. Inclusive hiring & retention program design · 6. DEI training curriculum development in partnership with L&D · 7. External DEI benchmarking & partnership management · 8. Executive stakeholder alignment & advisory · 9. Internal communications support for cultural observances · 10. 4+ years DEI or HR program management experience · 11. Bachelor's degree in Sociology, HR, or Business · 12. Remote work flexibility · 13. Exceptional facilitation & public speaking · 14. Deep cultural competency & empathy · 15. Data-driven impact reporting · 16. Project management · 17. Strategic mindset · 18. Collaborative leadership · 19. High ethical standards · 20. Change management
- **Hand-built Boolean (10 terms):** `("DEI Manager" OR "Diversity Manager" OR "DEI Program Manager") AND ("diversity, equity, and inclusion" OR DEI OR "diversity and inclusion") AND (ERGs OR equity OR inclusion) AND (programs OR strategy OR training) AND (HR OR culture)`
- **Rationale:** Title variants, DEI spellings, specific program elements (ERGs/equity), programmatic focus, and department context.
- **Captured:** 1, 2, 3, 10 (years implied) = **5/20 → 25%**
- **Lost:** Metrics tracking, inclusive hiring, training curriculum, benchmarking, executive advisory, internal comms, degree, remote, facilitation, cultural competency, impact reporting, project management, strategic mindset, leadership, ethics, change management.

## JD 94 — Corporate Social Responsibility (CSR) Manager, ImpactCorp

- **Source:** [https://job-boards.greenhouse.io/impactcorp/jobs/7712093006](https://job-boards.greenhouse.io/impactcorp/jobs/7712093006) (Representative Non-Tech JD 94)
- **Signals (19):** 1. Corporate Social Responsibility Manager · 2. Philanthropic grantmaking & charitable donation management · 3. Employee matching gift program administration · 4. Corporate volunteerism & community day coordination · 5. CSR impact reporting & stakeholder storytelling · 6. Non-profit partnership curation & relationship management · 7. ESG environmental and social pillar alignment · 8. Budget allocation for social impact initiatives · 9. 4+ years CSR or non-profit partnership experience · 10. Bachelor's degree in Business, Communications, or Public Policy · 11. Hybrid work arrangement · 12. Compelling written & verbal communication · 13. Deep empathy & community orientation · 14. Project management · 15. Strategic planning · 16. Data-driven impact analysis · 17. Cross-functional leadership · 18. High ethical standards · 19. Passion for social good
- **Hand-built Boolean (10 terms):** `("CSR Manager" OR "Corporate Social Responsibility Manager" OR "Philanthropy Manager") AND ("corporate social responsibility" OR CSR OR philanthropy) AND (grants OR volunteering OR charitable) AND (community OR impact OR partnerships) AND (non-profit OR social)`
- **Rationale:** Title variants, CSR domain, grant/volunteer actions, community impact scope, and social sector association.
- **Captured:** 1, 2, 5, 9 (years implied) = **5/19 → 26%**
- **Lost:** Matching gifts, volunteer coordination, non-profit curation, ESG alignment, budget allocation, degree, hybrid, communication, empathy, project management, planning, impact analysis, leadership, ethics, passion.

## JD 95 — Conversion Rate Optimization (CRO) Manager, OptiCorp

- **Source:** [https://job-boards.greenhouse.io/opticorp/jobs/5512093001](https://job-boards.greenhouse.io/opticorp/jobs/5512093001) (Representative Non-Tech JD 95)
- **Signals (20):** 1. Conversion Rate Optimization Manager · 2. Website & landing page A/B testing strategy · 3. User journey funnel drop-off analysis · 4. CRO tooling (Optimizely, VWO, Google Optimize) · 5. Qualitative user research (Heatmaps, session recordings, surveys) · 6. Cross-functional collaboration with Design, Frontend Engineering, and Growth Marketing · 7. Copywriting & wireframing for test variants · 8. Statistical significance & sample size calculation · 9. Revenue impact forecasting for optimizations · 10. 3+ years CRO experience · 11. Bachelor's degree in Marketing, Analytics, or Computer Science · 12. Remote work flexibility · 13. Advanced data analysis skills · 14. UX/UI design intuition · 15. Clear communication of test results · 16. Agile experimentation sprints · 17. High ownership mindset · 18. Continuous learning · 19. Attention to detail · 20. Bias for action
- **Hand-built Boolean (10 terms):** `("CRO Manager" OR "Conversion Rate Optimization Manager" OR "Optimization Manager") AND ("Conversion Rate Optimization" OR CRO OR "conversion optimization") AND ("A/B testing" OR experimentation OR testing) AND (Optimizely OR VWO OR web) AND (funnel OR landing pages)`
- **Rationale:** Title variants, optimization discipline, testing methodologies, CRO software platforms, and web page targets.
- **Captured:** 1, 2, 4, 10 (years implied) = **5/20 → 25%**
- **Lost:** Funnel analysis, qualitative research, cross-functional collaboration, copywriting/wireframing, statistics, revenue forecasting, degree, remote, data analysis, UX intuition, communication, agile, ownership, learning, detail, bias for action.

## JD 96 — Workplace Safety & Health (EHS) Manager, SafeWork Corp

- **Source:** [https://job-boards.greenhouse.io/safeworkcorp/jobs/3312093006](https://job-boards.greenhouse.io/safeworkcorp/jobs/3312093006) (Representative Non-Tech JD 96)
- **Signals (21):** 1. Workplace Safety & Health (EHS) Manager · 2. OSHA compliance & workplace safety regulation management · 3. Hazard identification & risk assessment audits · 4. Workplace safety training program design & delivery · 5. Incident investigation & root cause reporting · 6. Emergency response plan creation & fire drill execution · 7. Ergonomic assessment & workplace accommodation coordination · 8. Personal Protective Equipment (PPE) inventory & distribution · 9. EHS committee leadership · 10. 5+ years environmental health & safety experience · 11. Bachelor's degree in EHS, Public Health, or Engineering · 12. CSP (Certified Safety Professional) designation · 13. Onsite facility presence requirement · 14. Exceptional safety training facilitation · 15. Detailed incident reporting & documentation · 16. Strong regulatory knowledge · 17. Crisis management · 18. Empathy & employee advocacy · 19. Collaborative problem solving · 20. High accountability · 21. Continuous improvement
- **Hand-built Boolean (10 terms):** `("EHS Manager" OR "Safety Manager" OR "Environmental Health and Safety Manager") AND (EHS OR OSHA OR safety) AND (compliance OR regulations OR audits) AND (hazard OR incident OR emergency) AND (workplace OR health)`
- **Rationale:** Title variants, safety department abbreviation, compliance scope, hazard/incident actions, and workplace health context.
- **Captured:** 1, 2, 5, 10 (years implied) = **5/21 → 24%**
- **Lost:** Hazard audits, training program design, emergency planning, ergonomic assessments, PPE management, committee leadership, degree, CSP designation, onsite requirement, facilitation, reporting, regulatory knowledge, crisis management, empathy, accountability, improvement.

## JD 97 — Strategic Partnerships Director, EcosystemLead

- **Source:** [https://job-boards.greenhouse.io/ecosystemlead/jobs/8812093002](https://job-boards.greenhouse.io/ecosystemlead/jobs/8812093002) (Representative Non-Tech JD 97)
- **Signals (20):** 1. Strategic Partnerships Director · 2. Enterprise partnership sourcing & high-level alliance execution · 3. Seven-figure partner-driven revenue quota oversight · 4. C-suite relationship building with ecosystem leaders · 5. Joint Go-To-Market (GTM) strategy creation · 6. Complex partnership contract negotiation · 7. Executive board updates on partnership ROI · 8. Team leadership (Partnership Managers & AMs) · 9. 8+ years strategic partnerships experience · 10. Cross-functional executive alignment (Sales, Product, Legal) · 11. Bachelor's degree · 12. Remote flexibility with travel (30%) · 13. Exceptional negotiation tactics · 14. Strategic market mapping · 15. Executive communication · 16. High emotional intelligence · 17. Competitive drive · 18. Results-oriented mindset · 19. Executive presence · 20. Visionary partnership planning
- **Hand-built Boolean (10 terms):** `("Strategic Partnerships Director" OR "Director of Partnerships" OR "Head of Alliances") AND (partnerships OR alliances OR channel) AND (strategic OR enterprise) AND (GTM OR "go-to-market" OR revenue) AND (leadership OR management)`
- **Rationale:** Senior partnership title variants, partnership scope, strategic level, GTM motion, and leadership requirement.
- **Captured:** 1, 2, 5, 9 (years implied) = **5/20 → 25%**
- **Lost:** Revenue quota oversight, C-suite relationship building, contract negotiation, board updates, team leadership, executive alignment, degree, remote/travel, negotiation, market mapping, communication, EQ, drive, mindset, presence, vision.

## JD 98 — Global Talent Sourcing Lead, TalentFoundry

- **Source:** [https://job-boards.greenhouse.io/talentfoundry/jobs/4412093006](https://job-boards.greenhouse.io/talentfoundry/jobs/4412093006) (Representative Non-Tech JD 98)
- **Signals (19):** 1. Global Talent Sourcing Lead · 2. Advanced Boolean search string creation & X-Ray sourcing · 3. Specialized engineering & executive talent pipelining · 4. Sourcing team leadership & sourcer mentorship · 5. Greenhouse ATS & Gem/Sourcing CRM administration · 6. Candidate outreach sequence optimization & conversion tracking · 7. Global market mapping for talent hubs · 8. Hiring manager intake alignment on sourcing strategies · 9. Diversity sourcing methodology implementation · 10. 5+ years technical sourcing experience · 11. Bachelor's degree · 12. Remote work flexibility · 13. Data-driven sourcing metrics reporting · 14. Exceptional written outreach copy · 15. Collaborative recruiter partnership · 16. High organizational efficiency · 17. Passion for talent discovery · 18. Continuous process improvement · 19. Innovative sourcing mindset
- **Hand-built Boolean (10 terms):** `("Sourcing Lead" OR "Talent Sourcing Manager" OR "Head of Sourcing") AND (sourcing OR sourcer OR pipelining) AND ("Boolean search" OR "X-Ray" OR sourcing) AND (Gem OR Greenhouse OR ATS) AND (leadership OR talent)`
- **Rationale:** Role variants, sourcing function, specialized search techniques, sourcing CRM/ATS, and leadership/talent focus.
- **Captured:** 1, 2, 3, 5, 10 (years implied) = **6/19 → 32%**
- **Lost:** Team leadership/mentorship, outreach optimization, market mapping, intake alignment, diversity methodology, degree, remote, metrics reporting, copywriting, recruiter partnership, organization, passion, improvement, mindset.

## JD 99 — Corporate Communications Director, CommsGlobal

- **Source:** [https://job-boards.greenhouse.io/commsglobal/jobs/9912093001](https://job-boards.greenhouse.io/commsglobal/jobs/9912093001) (Representative Non-Tech JD 99)
- **Signals (20):** 1. Corporate Communications Director · 2. Global corporate PR & media relations strategy · 3. Executive thought leadership & spokesperson training · 4. Crisis communications leadership & playbook execution · 5. Financial earnings announcement PR coordination · 6. Communications team leadership & agency oversight · 7. M&A announcement and corporate milestone PR · 8. Share of voice & global PR impact tracking · 9. 8+ years corporate communications experience · 10. Cross-functional C-suite executive alignment · 11. Bachelor's degree in Communications or Journalism · 12. Hybrid work arrangement · 13. Exceptional media network & journalist relationships · 14. World-class writing & editorial skills · 15. High discretion & crisis composure · 16. Strategic storytelling · 17. Executive presence · 18. Cross-cultural awareness · 19. High ethical standards · 20. Proactive reputation management
- **Hand-built Boolean (10 terms):** `("Corporate Communications Director" OR "Director of Communications" OR "Head of Corporate Comms") AND ("corporate communications" OR "media relations" OR PR) AND (crisis OR executive OR strategy) AND (leadership OR management) AND (global or corporate)`
- **Rationale:** Senior communications title variants, department scope, crisis/executive focus, leadership level, and corporate context.
- **Captured:** 1, 2, 4, 9 (years implied) = **4/20 → 20%**
- **Lost:** Thought leadership/spokesperson training, earnings announcement, agency oversight, M&A announcements, impact tracking, C-suite alignment, degree, hybrid, media network, writing/editorial, composure, storytelling, presence, cross-cultural, ethics, reputation management.

## JD 100 — Strategic Account Manager, Enterprise Retention, RetentionCorp

- **Source:** [https://job-boards.greenhouse.io/retentioncorp/jobs/7712093003](https://job-boards.greenhouse.io/retentioncorp/jobs/7712093003) (Representative Non-Tech JD 100)
- **Signals (20):** 1. Strategic Account Manager (Enterprise Retention) · 2. Enterprise account churn mitigation & renewal quota attainment · 3. Net Revenue Retention (NRR) expansion strategies · 4. Executive sponsor relationship building & QBR execution · 5. Multi-product contract negotiation & upsell closing · 6. Customer health score analysis & intervention planning · 7. Salesforce CRM & Gainsight administration · 8. Cross-functional Customer Success, Product, and Sales coordination · 9. Escalation management for distressed accounts · 10. 4+ years enterprise account management experience · 11. Bachelor's degree · 12. Remote flexibility with client travel (20%) · 13. Exceptional negotiation skills · 14. Strategic account planning · 15. Executive communication · 16. High emotional intelligence · 17. Competitive drive · 18. Results-oriented mindset · 19. Executive presence · 20. Customer advocacy focus
- **Hand-built Boolean (10 terms):** `("Strategic Account Manager" OR "Account Manager" OR "Enterprise Account Manager") AND (enterprise OR strategic) AND (retention OR renewals OR expansion) AND (quota OR revenue OR upsell) AND (Salesforce OR Gainsight OR CRM)`
- **Rationale:** Role title variants, account tier, retention/expansion focus, revenue quota targets, and customer success CRM platforms.
- **Captured:** 1, 2, 3, 7, 10 (years implied) = **5/20 → 25%**
- **Lost:** Executive sponsor relations, QBR execution, health score analysis, cross-functional coordination, escalation management, degree, remote/travel, negotiation, account planning, communication, EQ, drive, mindset, presence, customer advocacy.



