<div align="center">

<img src="images/banner/header-pipeline.svg" width="100%" alt="Juan José Valbuena Camacho — Data Engineer"/>

<a href="https://readme-typing-svg.demolab.com/">
<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&pause=1100&color=0F766E&center=true&vCenter=true&width=700&lines=I+build+data+pipelines+that+scale;From+2+hours+to+4+minutes+%E2%80%94+30%C3%97+faster;Python+%C2%B7+SQL+%C2%B7+Apache+Airflow+%C2%B7+AWS;Construyo+pipelines+de+datos+que+escalan" alt="Typing SVG" />
</a>

<a href="https://www.linkedin.com/in/juan-jose-valbuena-camacho-848549278"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:juanjosecodes24@gmail.com"><img src="https://img.shields.io/badge/juanjosecodes24@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Open%20to%20remote%20work-22c55e?style=for-the-badge&logo=checkmarx&logoColor=white" />

**Data engineer from Colombia who turns slow, fragile data processes into fast, traceable pipelines in production.**<br>
<sub><i>Data Engineer en Colombia: convierto procesos de datos lentos y frágiles en pipelines rápidos y trazables en producción.</i></sub>

</div>

## ⚡ Impact · Impacto

<table>
<tr>
<td align="center" width="25%"><h1>30×</h1><b>faster ingestion</b><br><sub>2 h → 3–4 min per batch<br><i>carga 30 veces más rápida</i></sub></td>
<td align="center" width="25%"><h1>1,000+</h1><b>files per run</b><br><sub>in production on AWS<br><i>archivos por corrida en producción</i></sub></td>
<td align="center" width="25%"><h1>80%+</h1><b>of the codebase</b><br><sub>principal contributor, 5-dev team<br><i>del código, equipo de 5</i></sub></td>
<td align="center" width="25%"><h1>1,400+</h1><b>lines of AWS Glue</b><br><sub>production ETL jobs<br><i>líneas de jobs ETL en producción</i></sub></td>
</tr>
</table>

## 🛰️ A production data pipeline I built · Un pipeline en producción que construí

**Data Engineer** · geospatial data platform for a client · plataforma de datos geoespaciales para un cliente

```mermaid
flowchart LR
    A[📁 Google Drive] -->|ingest| B[(S3 · raw)]
    B --> C[⚙️ AWS Glue<br/>ETL jobs]
    C --> D[(S3 · curated)]
    D --> E[🔎 Athena]
    D --> F[(🗺️ PostGIS)]
    D --> G[📄 Reports · pandas<br/>Word / Excel]
    G --> H[🤖 Selenium DAG<br/>2 h → 4 min]
    O{{🌀 Apache Airflow<br/>orchestration · retries · traceability}} -.-> B
    O -.-> C
    O -.-> H
```

<sub>Also: Lambda · ECS · EC2 · IAM · Secrets Manager · CloudFormation/SAM · pandas · geopandas · automated tests with mocking · schema and geometry validation</sub>

## 📌 Featured projects · Proyectos destacados

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/JuanJo24S/claude-develop-skills"><img src="https://opengraph.githubassets.com/1/JuanJo24S/claude-develop-skills" width="100%"/></a>
<h3>🤖 claude-develop-skills</h3>
Skills and a <b>git-guard</b> hook so AI agents ship clean Pull Requests: it blocks pushes to <code>main</code>, force pushes, <code>.env</code> files and secrets before the agent runs them.<br>
<sub><i>Skills y un hook para que los agentes de IA trabajen con PR ordenados y seguros.</i></sub><br><br>
<code>Claude Code</code> <code>OpenCode</code> <code>Bash</code> <code>Git</code><br>
<a href="https://github.com/JuanJo24S/claude-develop-skills">Repo →</a>
</td>
<td width="50%" valign="top">
<a href="dr-stock.md"><img src="images/dr-stock/inventory.png" width="100%"/></a>
<h3>🗂️ Dr. Stock</h3>
Inventory and point-of-sale system: stock alerts, PDF receipts and role-based users. Stateless REST API, layered architecture, <b>70 automated tests</b>.<br>
<sub><i>Inventario y punto de venta · proyecto de grado, reescrito en Spring Boot.</i></sub><br><br>
<code>Spring Boot 3.3</code> <code>Java 17</code> <code>Angular 17</code> <code>PostgreSQL</code> <code>Flyway</code> <code>JWT</code> <code>Docker</code><br>
<a href="https://dr-stock-gules.vercel.app/auth">Live demo →</a> · <a href="dr-stock.md">Details (ES) →</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="harsimuverse.md"><img src="images/harsimuverse/kids-3-assembly.png" width="100%"/></a>
<h3>🎮 HarSimuVerse</h3>
Six Angular mini-games that teach kids aged 4–12 the parts of a computer, built for tablets. Removed the backend to cut hosting cost: now a static SPA.<br>
<sub><i>Juego educativo · freelance para docentes universitarios.</i></sub><br><br>
<code>Angular 19</code> <code>Tailwind 4</code> <code>TypeScript</code> <code>Vercel</code><br>
<a href="https://har-simu-verse.vercel.app/home">Play →</a> · <a href="harsimuverse.md">Details (ES) →</a>
</td>
<td width="50%" valign="top">
<a href="images/factus/certificado-factus.png"><img src="images/factus/certificado-factus.png" width="100%"/></a>
<h3>🧾 Factus API integration</h3>
Automated electronic invoicing inside an Angular application, certified by <b>HALLTEC S.A.S</b> (January 2025).<br>
<sub><i>Facturación electrónica automatizada con la API de Factus.</i></sub><br><br>
<code>Angular</code> <code>REST API</code><br>
<a href="images/factus/certificado-factus.png">Certificate →</a>
</td>
</tr>
</table>

## 🧰 Tech stack

<p align="center">
<img src="https://skillicons.dev/icons?i=py,java,ts,postgres,aws,docker,spring,angular,githubactions,linux&perline=10" />
</p>

<details>
<summary><b>Full stack · Stack completo</b></summary>
<br>

| Area · Área | Technologies · Tecnologías |
|---|---|
| **Languages** | Java · Python · SQL · TypeScript · JavaScript · C · C++ · C# · PHP · Bash · HTML · CSS |
| **Data** | Apache Airflow (DAGs, orchestration, retries, traceability) · PostgreSQL · PostGIS · MySQL · Amazon Athena · DynamoDB · pandas · geopandas · Flyway · ArcGIS · Selenium · docxtpl/Jinja2 · openpyxl |
| **Cloud (AWS)** | Glue · S3 · Athena · Lambda · ECS · EC2 · DynamoDB · IAM · Secrets Manager · CloudFormation · SAM · AWS CLI |
| **Backend** | Spring Boot 3.x · Laravel · REST APIs · JWT · layered architecture with DTOs · JUnit |
| **Frontend** | Angular 17–19 · Ionic · Tailwind · Bootstrap |
| **DevOps & tools** | Docker · GitHub Actions (CI/CD) · Git · GitHub · Bitbucket · Linux · Claude Code |
| **Practices** | SOLID · Clean Code · RBAC · automated testing with mocking · performance optimisation (SQL, HTTP/REST, build and run times) · technical documentation |

</details>

## 👋 About me · Sobre mí

<details>
<summary><b>🇬🇧 Read in English</b></summary>
<br>

I'm Juan, a data engineer and fullstack developer. I like working where data and code meet: taking something from an idea to production, and keeping it running as it grows.

In my last role I designed and maintained a Python ETL pipeline orchestrated with Apache Airflow for geospatial data, and wrote more than 80% of the project's code in a five-developer team. My best-known fix: a Selenium script located each PDF report by walking **randomly ordered pages** (a record could be on page 1 or page 400), so 5 files took about **2 hours**. I rewrote it against **direct REST endpoints** as its own Airflow DAG: the same batch took **3–4 minutes**, and it scaled to **1,000+ files** in production.

Before that I built complete applications end to end: an inventory and point-of-sale system, electronic invoicing and an educational platform for children. Java is still my favourite language; for data work, my day to day is Python and SQL.

I'm in the **8th semester of a BSc in Software Engineering** at FET (Colombia), with Professional Technician and Technologist degrees already awarded. Outside of code I've practised karate for 8 years 🥋: the same discipline of repeating something until it works well is how I learn new technology.

**Looking for:** remote roles in data engineering or backend. Native Spanish, conversational English.

</details>

<details>
<summary><b>🇪🇸 Leer en español</b></summary>
<br>

Soy Juan, Data Engineer y desarrollador Fullstack. Me gusta trabajar donde los datos y el código se cruzan: llevar algo desde una idea hasta que corre en producción, y que siga corriendo cuando crece.

En mi último rol diseñé y mantuve un pipeline ETL en Python orquestado con Apache Airflow para datos geoespaciales, y escribí más del 80% del código del proyecto en un equipo de cinco desarrolladores. Mi arreglo más conocido: un script de Selenium ubicaba cada informe PDF recorriendo **páginas en orden aleatorio** (un registro podía estar en la página 1 o en la 400), así que 5 archivos tardaban cerca de **2 horas**. Lo reescribí con **endpoints REST directos** como un DAG propio en Airflow: el mismo lote pasó a **3–4 minutos** y escaló a **más de 1.000 archivos** en producción.

Antes construí aplicaciones completas de punta a punta: un sistema de inventario y punto de venta, facturación electrónica y una plataforma educativa para niños. Java sigue siendo mi lenguaje preferido; en datos, mi día a día es Python y SQL.

Voy en el **8vo semestre de Ingeniería de Software** en la FET, con los títulos de Técnico Profesional y Tecnólogo ya obtenidos. Fuera del código practico karate desde hace 8 años 🥋: la misma disciplina de repetir hasta que algo funcione bien la aplico al aprender tecnología nueva.

**Busco:** oportunidades remotas en ingeniería de datos o backend. Español nativo, inglés conversacional.

</details>

## 📈 Timeline · Línea de tiempo

```mermaid
%%{init: { 'themeVariables': {
'doneTaskBkgColor': '#065f46',
'doneTaskBorderColor': '#047857',
'activeTaskBkgColor': '#22c55e',
'activeTaskBorderColor': '#15803d',
'taskTextColor': '#ffffff',
'taskTextLightColor': '#ffffff',
'taskTextOutsideColor': '#ffffff'
}}}%%
gantt
dateFormat YYYY-MM-DD
axisFormat %Y
section Education
SQL course - Guayerd :done, 2023-04-01, 2023-06-30
Professional Technician (FET) :done, 2023-02-01, 2024-11-30
Technologist Degree (FET) :done, 2025-02-01, 2025-11-30
BSc Software Engineering (FET) :active, 2026-02-01, 2029-06-01
section Projects
Dr. Stock :done, 2024-03-01, 2024-11-22
Dr. Stock - Spring Boot :done, 2026-08-01, 2026-08-31
HarSimuVerse :done, 2024-03-01, 2024-11-30
HarSimuVerse - revisited :done, 2026-08-01, 2026-08-31
Factus API :done, 2025-06-01, 2025-06-30
```

## 🎓 Education · Educación

**BSc Software Engineering · Ingeniería de Software** — Fundación Escuela Tecnológica de Neiva (FET), Colombia — *8th semester · 8vo semestre*  
Technologist Degree in Information Systems & Networks Development (2026) · Professional Technician in IT Systems & Network Support (2025)

<div align="center">

<br>

**Let's talk · ¿Hablamos?** → [LinkedIn](https://www.linkedin.com/in/juan-jose-valbuena-camacho-848549278) · [juanjosecodes24@gmail.com](mailto:juanjosecodes24@gmail.com)

<img src="https://komarev.com/ghpvc/?username=JuanJo24S&label=Visitas%20%7C%20Views&color=0f766e&style=flat-square" alt="Profile views"/>

<img src="images/banner/footer-pipeline.svg" width="100%" alt="Thanks for visiting · Gracias por la visita"/>

</div>
