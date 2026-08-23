<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,100:1F4E5F&height=200&section=header&text=Juan%20Jose%20Valbuena%20Camacho&fontSize=38&fontColor=ffffff&animation=fadeIn&desc=Fullstack%20Developer%20%2F%20Data%20Engineer&descAlignY=62&descSize=18" width="100%"/>

<a href="https://readme-typing-svg.demolab.com/">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1200&color=0F766E&center=true&vCenter=true&width=650&lines=Desarrollador+Fullstack+y+Data+Engineer;Python+-+Apache+Airflow+-+AWS;De+pipelines+ETL+a+interfaces+con+Angular;Java+fue+mi+primer+lenguaje+y+lo+sigue+siendo" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.linkedin.com/in/juan-jose-valbuena-camacho-848549278"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/JuanJo24S"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:Juanjosecodes24@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

</div>

## 👋 Sobre mí

Soy Juan, desarrollador Fullstack y Data Engineer. Me gusta trabajar en proyectos donde los datos y el código se cruzan — llevar algo desde una idea hasta que corre en producción.

He trabajado tanto del lado de datos (pipelines, automatización, nube) como construyendo aplicaciones completas de punta a punta: un sistema de inventarios, facturación electrónica, una plataforma educativa para niños. Java sigue siendo mi lenguaje preferido, aunque me muevo cómodo en varios más.

Actualmente voy en el **8vo semestre de Ingeniería de Software** en la FET. Fuera del código, practico Karate desde hace 8 años 🥋 — la misma disciplina de repetir hasta que algo funcione bien la aplico aprendiendo tecnología nueva.

---

## 🧰 Stack tecnológico

| Área | Tecnologías |
|---|---|
| **Lenguajes** | ![](https://skillicons.dev/icons?i=java,c,cpp,cs,php,py,js,ts,html,css,bash) |
| **Frontend** | ![](https://skillicons.dev/icons?i=angular,tailwind,bootstrap) |
| **Backend** | ![](https://skillicons.dev/icons?i=spring,laravel) |
| **Datos & Cloud** | ![](https://skillicons.dev/icons?i=aws,postgres,mysql,docker) |
| **Herramientas** | ![](https://skillicons.dev/icons?i=git,github,linux) |

<p>
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/ArcGIS-2C7AC3?style=flat-square&logo=esri&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20Glue%20%7C%20Athena%20%7C%20Lambda%20%7C%20ECS%20%7C%20EC2%20%7C%20CloudFormation-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
</p>

---

## 💼 Experiencia

**Ingeniería de Datos y Automatización Cloud — Dronesky** (proyecto para Solidaridad)
*Septiembre 2025 – Agosto 2026*

Diseñé y mantuve un pipeline ETL en Python orquestado con Apache Airflow para el procesamiento de datos geoespaciales, siendo responsable de **más del 80% del código** del proyecto.

El flujo completo arrancaba con la carga de datos desde **Google Drive hacia S3**, seguía por varias etapas de **ETL** — generando informes en cada paso intermedio — y cerraba con la carga de los resultados a **PostGIS** para el análisis geoespacial. Ahí también migré los scripts de **Selenium** que subían esos informes, integrándolos como tareas propias dentro del pipeline. Sobre AWS trabajé de punta a punta: **Glue** para las transformaciones, **Athena** para consultas, **Lambda, ECS y EC2** para cómputo, **IAM y Secrets Manager** para el control de acceso, y **CloudFormation** para la infraestructura como código — todo administrado también vía **AWS CLI**.

---

## ⚡ De 2 horas a 3-4 minutos: optimizando una carga masiva

En Geo-Data heredé un script de Selenium que subía informes en PDF ubicando cada uno por ID mediante **paginación manual y en orden aleatorio** — un registro podía estar en la página 1 o en la 400. Para un lote de apenas 5 archivos, el proceso completo (incluyendo arranque del navegador e inicio de sesión) tardaba cerca de **2 horas**.

Lo rediseñé usando **endpoints REST directos** en lugar de navegación por páginas, y lo integré como un DAG propio dentro del pipeline de Airflow. El mismo lote pasó a tomar **3-4 minutos**, y la solución escaló sin problema a producción con más de **1.000 archivos**.

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
    dateFormat  YYYY-MM-DD
    axisFormat  %Y
    section Empleo
    Dronesky - Geo-Data (Solidaridad)      :done, 2025-09-15, 2026-08-31
    section Formación
    Curso SQL - Guayerd + Beta Hub         :done, 2023-04-01, 2023-06-30
    Técnico Profesional (FET)              :done, 2023-02-01, 2024-11-30
    Tecnología en Desarrollo (FET)         :done, 2025-02-01, 2025-11-30
    Ingeniería de Software (FET)           :active, 2026-02-01, 2029-06-01
    section Proyectos
    Dr. Stock (grado + retomado)           :done, 2024-03-01, 2026-08-31
    Juego educativo (freelance)            :done, 2024-03-01, 2024-11-30
    Integración API Factus                 :done, 2025-06-01, 2025-06-30
```

---

## 📌 Proyectos destacados

**🗂️ Dr. Stock — Sistema de Gestión de Inventarios**
Sistema web de inventarios con autenticación, control de productos y stock en tiempo real.
`Laravel` `MySQL` `Angular 18` `Bootstrap`
🔗 [Demo en vivo](https://dr-stock-gules.vercel.app/auth) · Proyecto de grado, retomado — marzo 2024 – agosto 2026

**🧾 Integración API Factus**
Facturación electrónica automatizada dentro de una aplicación Angular.
`Angular` `API REST`
📅 Junio 2025

**🎮 Juego Educativo en Angular**
Plataforma interactiva de aprendizaje para niños de 4 a 10 años sobre diseño y estructura de computadores.
`Angular`
📅 Marzo – noviembre 2024 (freelance)

---

## 🎓 Educación

**Ingeniería de Software** — Fundación Escuela Tecnológica de Neiva (FET), Rivera-Huila — *en curso, 8vo semestre*
Ciclo propedéutico: Tecnología en Desarrollo de Sistemas de Información y Redes (2026) · Técnico Profesional en Soporte de Sistemas Informáticos y Redes (2025)

---

<div align="center">

📫 **¿Hablamos?** [LinkedIn](https://www.linkedin.com/in/juan-jose-valbuena-camacho-848549278) · [Email](mailto:Juanjosecodes24@gmail.com)

![Visitas al perfil](https://komarev.com/ghpvc/?username=JuanJo24S&label=Visitas%20al%20perfil&color=0f766e&style=flat)

</div>
