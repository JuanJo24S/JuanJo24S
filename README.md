<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,100:1F4E5F&height=200&section=header&text=Juan%20Jos%C3%A9%20Valbuena%20Camacho&fontSize=38&fontColor=ffffff&animation=fadeIn&desc=Data%20Engineer%20%C2%B7%20Fullstack%20Developer&descAlignY=62&descSize=18" width="100%"/>

<a href="https://readme-typing-svg.demolab.com/">
<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1200&color=0F766E&center=true&vCenter=true&width=650&lines=Data+Engineer+%C2%B7+Fullstack+Developer;Python+-+SQL+-+Apache+Airflow+-+AWS;De+2+horas+a+4+minutos%3A+pipelines+que+escalan;Java+fue+mi+primer+lenguaje+y+lo+sigue+siendo" alt="Typing SVG" />
</a>

<p>
<a href="https://www.linkedin.com/in/juan-jose-valbuena-camacho-848549278"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/JuanJo24S"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="mailto:juanjosecodes24@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<img src="https://img.shields.io/badge/Disponible-remoto%20%C2%B7%20Neiva%2C%20Colombia-0F766E?style=flat-square" />
<img src="https://img.shields.io/badge/Idiomas-Espa%C3%B1ol%20nativo%20%C2%B7%20Ingl%C3%A9s%20conversacional-1F4E5F?style=flat-square" />

</div>

> **EN:** Data engineer and fullstack developer from Colombia. I build Python ETL pipelines orchestrated with Apache Airflow on AWS, and full applications with Java/Spring Boot and Angular. Open to remote roles.

## 👋 Sobre mí

Soy Juan, Data Engineer y desarrollador Fullstack. Me gusta trabajar donde los datos y el código se cruzan: llevar algo desde una idea hasta que corre en producción, y que siga corriendo cuando crece.

Del lado de datos he construido pipelines ETL, automatización y nube; del lado de aplicaciones, sistemas completos de punta a punta: un sistema de inventario y punto de venta, facturación electrónica y una plataforma educativa para niños. Java sigue siendo mi lenguaje preferido; en datos, mi día a día es Python y SQL.

Voy en el **8vo semestre de Ingeniería de Software** en la FET. Fuera del código practico karate desde hace 8 años 🥋: la misma disciplina de repetir hasta que algo funcione bien la aplico al aprender tecnología nueva.

---

## 🧰 Stack tecnológico

| Área | Tecnologías |
|---|---|
| **Datos & Cloud** | ![](https://skillicons.dev/icons?i=py,aws,postgres,mysql,docker) |
| **Lenguajes** | ![](https://skillicons.dev/icons?i=java,py,ts,js,c,cpp,cs,php,bash) |
| **Backend** | ![](https://skillicons.dev/icons?i=spring,laravel) |
| **Frontend** | ![](https://skillicons.dev/icons?i=angular,tailwind,bootstrap,html,css) |
| **Herramientas** | ![](https://skillicons.dev/icons?i=git,github,linux) |

<p>
<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
<img src="https://img.shields.io/badge/ArcGIS-2C7AC3?style=flat-square&logo=esri&logoColor=white" />
<img src="https://img.shields.io/badge/AWS%20Glue%20%7C%20S3%20%7C%20Athena%20%7C%20Lambda%20%7C%20ECS%20%7C%20CloudFormation-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />
</p>

---

## 💼 Experiencia

**Data Engineer — confidential client** · Neiva, híbrido
*Noviembre 2025 – Agosto 2026*

Diseñé y mantuve un pipeline ETL en Python orquestado con Apache Airflow para el procesamiento de datos geoespaciales, siendo responsable de **más del 80% del código** del proyecto en un equipo de cinco desarrolladores.

El flujo arrancaba con la carga de datos desde **Google Drive hacia S3**, seguía por varias etapas de **ETL** —generando informes en cada paso intermedio— y cerraba con la carga de los resultados a **PostGIS** para el análisis geoespacial. Migré los scripts de **Selenium** que subían esos informes a tareas propias dentro del pipeline. Sobre AWS trabajé de punta a punta: **Glue** para las transformaciones, **Athena** para consultas, **Lambda, ECS y EC2** para cómputo, **IAM y Secrets Manager** para el control de acceso y **CloudFormation** para la infraestructura como código, todo administrado también vía **AWS CLI**.

### ⚡ De 2 horas a 3-4 minutos: optimizando una carga masiva

Heredé un script de Selenium que subía informes en PDF ubicando cada uno por ID mediante **paginación manual y en orden aleatorio**: un registro podía estar en la página 1 o en la 400. Para un lote de apenas 5 archivos, el proceso completo (incluyendo arranque del navegador e inicio de sesión) tardaba cerca de **2 horas**.

Lo rediseñé usando **endpoints REST directos** en lugar de navegar por páginas, y lo integré como un DAG propio dentro de Airflow. El mismo lote pasó a tomar **3-4 minutos** (unas 30 veces más rápido), y la solución escaló a producción con más de **1.000 archivos**.

---

## 📌 Proyectos destacados

**🤖 [claude-develop-skills — Herramientas para agentes de IA](https://github.com/JuanJo24S/claude-develop-skills)**
Skills y un hook de seguridad (*git-guard*) para que los agentes de IA trabajen con Pull Requests ordenados: flujo de Git con Conventional Commits, PR con autorrevisión, manejo de secretos y código limpio. El hook bloquea push a `main`, force push, archivos `.env` y secretos antes de que el agente los ejecute.
`Claude Code` `OpenCode` `Bash` `Git`
Open source · documentación en español e inglés · 2025 – actualidad

**🗂️ [Dr. Stock — Inventario y Punto de Venta](dr-stock.md)**
Sistema de inventario y punto de venta para pequeños negocios: control de stock con alertas de reposición, ventas con recibo en PDF y gestión de usuarios por rol.
`Angular 17` `Tailwind` `Spring Boot 3.3` `Java 17` `PostgreSQL` `Flyway` `JWT` `Docker`
API REST sin estado, arquitectura en capas con DTOs y 70 pruebas automatizadas.
🔗 [Demo en vivo](https://dr-stock-gules.vercel.app/auth) · 📄 [Capturas y detalle](dr-stock.md)
Proyecto de grado, marzo – noviembre 2024 · reescrito en Spring Boot, agosto 2026

**🎮 [HarSimuVerse — Juego Educativo en Angular](harsimuverse.md)**
Seis minijuegos para que niños de 4 a 12 años aprendan las partes del computador, pensados para tablet: interacción táctil, áreas de toque de 56 px o más y retroalimentación que no depende solo del color. Eliminé el backend original para quitar el costo de hosting y el arranque lento: hoy es una SPA estática.
`Angular 19` `Tailwind 4` `TypeScript` `Vercel`
🔗 [Demo en vivo](https://har-simu-verse.vercel.app/home) · 📄 [Capturas y detalle](harsimuverse.md)
Freelance para docentes universitarios, marzo – noviembre 2024 · refactorizado agosto 2026

**🧾 Integración API Factus**
Facturación electrónica automatizada dentro de una aplicación Angular.
`Angular` `API REST`
🏅 [Certificación de HALLTEC S.A.S](images/factus/certificado-factus.png) — enero 2025

---

## 📈 Línea de tiempo

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
title Experiencia, formación y proyectos
dateFormat YYYY-MM-DD
axisFormat %Y
section Empleo
confidential client - Data Engineer (confidential client) :done, 2025-11-01, 2026-08-31
section Formación
Curso SQL - Guayerd + Beta Hub :done, 2023-04-01, 2023-06-30
Técnico Profesional (FET) :done, 2023-02-01, 2024-11-30
Tecnología en Desarrollo (FET) :done, 2025-02-01, 2025-11-30
Ingeniería de Software (FET) :active, 2026-02-01, 2029-06-01
section Proyectos
Dr. Stock (grado) :done, 2024-03-01, 2024-11-22
Dr. Stock - Spring Boot :done, 2026-08-01, 2026-08-31
HarSimuVerse - freelance :done, 2024-03-01, 2024-11-30
HarSimuVerse - retomado :done, 2026-08-01, 2026-08-31
Integración API Factus :done, 2025-06-01, 2025-06-30
```

---

## 🎓 Educación

**Ingeniería de Software** — Fundación Escuela Tecnológica de Neiva (FET), Rivera-Huila — *en curso, 8vo semestre*
Ciclo propedéutico: Tecnología en Desarrollo de Sistemas de Información y Redes (2026) · Técnico Profesional en Soporte de Sistemas Informáticos y Redes (2025)

---

<div align="center">

📫 **¿Hablamos?** [LinkedIn](https://www.linkedin.com/in/juan-jose-valbuena-camacho-848549278) · [juanjosecodes24@gmail.com](mailto:juanjosecodes24@gmail.com)

![Visitas al perfil](https://komarev.com/ghpvc/?username=JuanJo24S&label=Visitas%20al%20perfil&color=0f766e&style=flat)

</div>
