<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <img src="banner-light.svg" alt="Carlos Rueda, Full Stack Engineer for e-commerce and fintech" width="100%">
</picture>

**Full Stack Engineer** building e-commerce and fintech products with React, Next.js, TypeScript and Node.js, with Python and Django on the backend. Nearly 5 years in production, more than 3 of them on VTEX IO. In my latest role I shipped with AI agents: I design the workflow and own the decisions, and the agents do the repetitive work.

Open to **remote** roles as Full Stack or Senior Frontend Engineer, especially in e-commerce, fintech and teams that already work with agents.

[LinkedIn](https://www.linkedin.com/in/carlos-rueda-calier) · [arturorueda88@gmail.com](mailto:arturorueda88@gmail.com) · Versión en español al final

## Featured work

<table>
<tr>
<td width="50%" valign="top">

**[Job Tracker](https://github.com/CarlosDev88/Job-Tracker)**<br>
Turns raw job posts from four sources into a short, ranked list. Normalization, deduplication (SHA-256 plus text similarity), intent classification, section-aware scoring and idempotent storage. A [Chrome extension](https://github.com/CarlosDev88/job-scraper-extension) handles ingestion.<br>
**Real run:** 1,017 posts down to 74 relevant ones. 32 automated tests.<br>
<sub>Python · FastAPI · SQLite · React · Docker</sub>

</td>
<td width="50%" valign="top">

**[Agent harness](https://github.com/CarlosDev88/agent-harness)**<br>
Reconstruction of the workflow I used to take 4 scraper tickets to production in parallel: one git worktree per ticket, separate agents to execute, audit and test, a state file that survives context compaction, and human approval at every gate.<br>
**Rule:** the agent answers only from the task, the repo or a logged question.<br>
<sub>Claude Code · Shell · Git worktrees</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Case-law scraper (JSF/ViewState)](https://github.com/CarlosDev88/jurisprudence-jsf-viewstate-scraper)**<br>
Browserless HTTP scraper for a legacy government portal. Reproduces the JSF/RichFaces protocol, recovers expired sessions, backs off on HTTP 429 and resumes from checkpoints without losing or duplicating documents.<br>
**Quality:** 18 unit and 3 integration tests, multi-stage Docker image.<br>
<sub>TypeScript · Node.js · Axios · Cheerio · Docker</sub>

</td>
<td width="50%" valign="top">

**[BuildSync](https://github.com/CarlosDev88/buildsync)**<br>
Modular ERP and CRM backend for real-estate construction companies, from the public catalog of projects and units to on-site cost control. It comes from the 7 years I spent inside construction finance before moving into software.<br>
<sub>Python · Django</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[E-commerce data pipeline](https://github.com/CarlosDev88/ecommerce-data-pipeline)** · <sub>in progress</sub><br>
Real product catalogs from public VTEX store APIs, deduplicated by EAN, plus synthetic users, sessions, transactions, XML invoices, returns and fraud signals, all driven by business rules in one settings file. Storage sits behind a single interface.<br>
**Next:** Pub/Sub events, BigQuery, dbt and a public dashboard.<br>
<sub>Python · Pandas · PyArrow · Faker</sub>

</td>
<td width="50%" valign="top">

**[VTEX IO full-stack sample](https://github.com/CarlosDev88/vtex-react-app-fortune-cookie)**<br>
A small feature built across the whole VTEX IO stack: a [store theme](https://github.com/CarlosDev88/store-theme-fortune-cookie), a storefront React app, an [Admin app](https://github.com/CarlosDev88/admin-app-cookie-fortune) with create and delete flows, and a [Node.js service](https://github.com/CarlosDev88/service-vtex-fortune-cookie) backed by Master Data.<br>
<sub>TypeScript · React · Node.js · VTEX IO · Master Data</sub>

</td>
</tr>
</table>

Also: [real-estate-credit-backoffice](https://github.com/CarlosDev88/real-estate-credit-backoffice), a Django REST Framework MVP for Colombian real-estate credit applications, and [deteccion-neumonia-cnn](https://github.com/CarlosDev88/deteccion-neumonia-cnn), a CNN trained from scratch in TensorFlow/Keras and evaluated once on a held-out test set (coursework).

## Experience

| When | Where | Role | What I did |
|---|---|---|---|
| 2026 | Magnar (legal tech, Chile) | Web scraper developer, data ingestion (contract) | Scrapers for legal documents, 4 tickets in parallel with an agent workflow |
| 2025–2026 | Valtech | Senior Frontend Engineer | Carrefour checkout audit that met the client's +40 Lighthouse points target; VTEX AdminX app for 5,000 coupons per batch |
| 2024–2025 | LQN | Frontend Developer | Sole frontend of a digital banking platform in 4 countries; fixed the month-end overload with on-demand GraphQL |
| 2022–2024 | ITGlobers | Full Stack Developer | Cencosud subscription discounts (AWS Lambda and Master Data), gift cards, compliance flows for regulated products |
| 2022 | Cadastra | Frontend Developer | VTEX IO components for La Rebaja, Lo Pido and Crocs Ecuador |

Before software I spent 7 years as administrative and financial coordinator on construction projects, so I read a product through its business numbers too.

## How I work with AI agents

- Each ticket gets its own git worktree, agent session and state file, so several tickets move at once without stepping on each other.
- The agent answers only from three sources: the task, the repository or a logged question with its link. Anything else becomes a question.
- Separate agents execute, audit and test. I approve the design and every fix plan before code changes.
- Every mistake goes into a shared log that the next tickets read.

## Stack

**Frontend:** React, Next.js, TypeScript, Redux, React Query, Apollo Client, React Hook Form, Material UI, Tailwind CSS<br>
**Backend and APIs:** Node.js, Express, Koa, GraphQL, REST, BFF, FastAPI, Django REST Framework<br>
**E-commerce:** VTEX IO (Store Framework, AdminX, Master Data, FastStore)<br>
**Data and cloud:** PostgreSQL, SQLite, MongoDB, Pandas, AWS (Lambda, S3, Amplify), Docker<br>
**Testing:** Jest, React Testing Library<br>
**AI:** Claude Code, multi-agent workflows

## Now

- Finishing a Specialization in Big Data and Data Analytics at Universidad de Cataluña (December 2026).
- Taking the e-commerce data pipeline to BigQuery, dbt and a public dashboard.

---

<details>
<summary><b>En español</b></summary>

<br>

**Full Stack Engineer** que construye productos de e-commerce y fintech con React, Next.js, TypeScript y Node.js, con Python y Django en el backend. Casi 5 años en producción, más de 3 sobre VTEX IO. En mi último trabajo entregué con agentes de IA: yo diseño el flujo y tomo las decisiones, y los agentes hacen el trabajo repetitivo.

Busco trabajo **remoto** como Full Stack o Senior Frontend Engineer, sobre todo en e-commerce, fintech y equipos que ya trabajan con agentes.

**Proyectos destacados**

- **[Job Tracker](https://github.com/CarlosDev88/Job-Tracker):** convierte publicaciones de empleo de cuatro fuentes en una lista corta y ordenada. En una corrida real pasó de 1.017 publicaciones a 74 relevantes. 32 tests.
- **[Arnés de agentes](https://github.com/CarlosDev88/agent-harness):** el flujo con el que llevé 4 tickets de scrapers a producción en paralelo, con un worktree por ticket, agentes que ejecutan, auditan y prueban, y aprobación humana en cada paso.
- **[Scraper de jurisprudencia](https://github.com/CarlosDev88/jurisprudence-jsf-viewstate-scraper):** scraper HTTP sin navegador para un portal legacy, con recuperación de sesión, backoff y checkpoint/resume. 21 tests.
- **[BuildSync](https://github.com/CarlosDev88/buildsync):** backend modular de ERP y CRM para constructoras, que sale de mis 7 años en finanzas de obra.
- **[Pipeline de datos de e-commerce](https://github.com/CarlosDev88/ecommerce-data-pipeline)** (en construcción): catálogos reales de tiendas VTEX y datos sintéticos guiados por reglas de negocio. Lo siguiente es Pub/Sub, BigQuery, dbt y un dashboard.
- **[Ejemplo full stack en VTEX IO](https://github.com/CarlosDev88/vtex-react-app-fortune-cookie):** tema de tienda, app React, app de Admin y servicio Node.js con Master Data.

**Experiencia:** Magnar (2026, scrapers de ingesta de datos con agentes), Valtech (2025–2026, Senior Frontend Engineer: checkout de Carrefour con la meta de +40 puntos en Lighthouse cumplida y cupones masivos en AdminX), LQN (2024–2025, único frontend de una banca digital en 4 países), ITGlobers (2022–2024, Full Stack en clientes de Cencosud) y Cadastra (2022, componentes VTEX IO). Antes, 7 años como coordinador administrativo y financiero de obra.

**Ahora:** terminando la Especialización en Big Data y Analítica de Datos (Universidad de Cataluña, diciembre de 2026) y llevando el pipeline de e-commerce a BigQuery y dbt.

[LinkedIn](https://www.linkedin.com/in/carlos-rueda-calier) · [arturorueda88@gmail.com](mailto:arturorueda88@gmail.com)

</details>
