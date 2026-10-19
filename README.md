<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Amina Salamatolla: data science and AI engineering" src="assets/header-dark.svg" width="100%">
</picture>

Data Science with an AI concentration at New York University, class of 2028: NYU Shanghai, studying in New York this year. I build the data layer and the AI that runs on top of it: Postgres schemas with row-level security, LLM services that answer only from permission-filtered data, and pipelines that turn messy multi-source data into something people can query. Before that, data science at NCOC, the operator of the Kashagan oil field, and research at the NYU Shanghai Center for Data Science.

[as20312@nyu.edu](mailto:as20312@nyu.edu) · [LinkedIn](https://www.linkedin.com/in/amina-salamatolla) · [github.com/amina-sb](https://github.com/amina-sb)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/section-experience-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/section-experience-light.svg">
  <img alt="Experience" src="assets/section-experience-dark.svg" width="100%">
</picture>

<table>
  <tr>
    <th align="left">Date</th>
    <th align="left">Role</th>
  </tr>
  <tr>
    <td valign="top">May 2026 – now<br><sub>Remote</sub></td>
    <td>
      <a href="https://app.aidencare.space"><b>AidenCare</b></a> · AI &amp; Data Engineering Intern<br>
      Bilingual dental clinic portal with an integrated AI assistant, built by a three-person team on Next.js, TypeScript and Supabase. Designed the PostgreSQL data model: <b>13 tables, 18 SQL functions and 33 row-level security policies</b> isolating patient records, with audit logging and 2FA. Indexed the most-used filter and sort columns on a 100,000-row dataset, making patient and appointment queries <b>about 90× faster</b> (18 ms to 0.2 ms). Built an LLM service on serverless Edge Functions that switches across <b>5 providers</b> by config and answers only from permission-filtered Postgres data (RAG). A 40-case bilingual test suite I wrote <b>caught a critical escalation bug before launch</b> and became the go-live gate.
    </td>
  </tr>
  <tr>
    <td valign="top">Sep 2025 – May 2026<br><sub>Shanghai</sub></td>
    <td>
      <b>NYU Shanghai Center for Data Science</b> · Research Assistant<br>
      Built a reusable pandas pipeline that standardized and quality-checked 55 survey variables, handled missing responses and merged records into one analysis-ready dataset, <b>cutting data-preparation time by 70%</b>. Designed a 40-item branching survey answered by <b>125 faculty at 20 universities</b>, and coded 280 open-text responses with a 20-code hierarchical codebook.
    </td>
  </tr>
  <tr>
    <td valign="top">Jun – Aug 2025<br><sub>Atyrau, Kazakhstan</sub></td>
    <td>
      <b>North Caspian Operating Company (NCOC)</b> · Data Science &amp; Analytics Intern<br>
      Built a Python pipeline on the Claude and GPT-4 APIs, with structured prompt templates and regex validation, that standardized 50+ job description records and <b>cut editing time by 67%</b>. Automated cleaning and validation of multi-source Excel exports in pandas before loading them into relational SQL tables, and built a Power BI model joining cost, headcount and supplier data from <b>3 source systems</b>. Traced cost-allocation variances in SQL to isolate the top expenditure drivers by department.
    </td>
  </tr>
  <tr>
    <td valign="top">Oct 2024 – Jun 2025<br><sub>Remote</sub></td>
    <td>
      <b>Telegram EdTech Platform</b> · Lead Data Analyst<br>
      Ran SQL cohort analysis across 5 learner groups, pinpointing low-engagement modules and redesigning workflows to <b>lift retention by 22%</b>. Designed an 8-module Python and SQL curriculum on data cleaning, exploratory analysis and statistical modeling, delivered across <b>70 sessions to 200 students</b>.
    </td>
  </tr>
</table>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/section-projects-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/section-projects-light.svg">
  <img alt="Projects" src="assets/section-projects-dark.svg" width="100%">
</picture>

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">Description</th>
  </tr>
  <tr>
    <td valign="top"><b>HSSE Management System</b><br><sub>SPFx · React · TypeScript</sub></td>
    <td>Led development of a SharePoint Online app for NCOC that parses Visio (VSDX) and Word (DOCX) process documents into interactive BPMN flowcharts with swimlanes, PDF export and permission-based admin access. <b>Shipped through v2.13</b>.</td>
  </tr>
  <tr>
    <td valign="top"><b>CSI 500 Stock Selection</b><br><sub>Python · XGBoost · pandas</sub></td>
    <td>5-seed XGBoost ensemble ranking CSI 500 stocks into a weighted 60-stock portfolio. <b>Placed 10th of 65</b> in a course competition, with full marks.</td>
  </tr>
  <tr>
    <td valign="top"><b>Causal Inference Replication</b><br><sub>Python · linearmodels</sub></td>
    <td>Replicated an American Economic Review (2014) paper, matching published estimates <b>within 0.2%</b> using difference-in-differences, event-study and IV (2SLS) models on an 8,466-observation panel.</td>
  </tr>
</table>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/section-stack-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/section-stack-light.svg">
  <img alt="Stack" src="assets/section-stack-dark.svg" width="100%">
</picture>

**Languages** · Python, SQL, TypeScript, JavaScript, C++<br>
**Data and ML** · pandas, NumPy, scikit-learn, XGBoost, PyTorch, statsmodels, causal inference (DiD, IV/2SLS)<br>
**AI** · LLM APIs (OpenAI, Anthropic, Gemini), RAG, LLM evaluation<br>
**Product and infrastructure** · Next.js, React, Tailwind CSS, Supabase, PostgreSQL, Edge Functions, pg_cron, Vercel, Git<br>
**Analytics** · Power BI, Power Query, Tableau, Excel<br>
**Spoken** · English, Kazakh, Russian, Mandarin Chinese
