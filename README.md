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

Desarrollador Fullstack y Data Engineer enfocado en llevar datos y aplicaciones desde la idea hasta producción.

En mi paso más reciente por **Dronesky** (proyecto para Solidaridad) diseñé y mantuve un pipeline ETL en Python orquestado con Apache Airflow para el procesamiento de datos geoespaciales, siendo responsable de **más del 80% del código** del proyecto. Ahí mismo rediseñé un proceso de carga masiva que pasó de tomar horas a minutos — lo cuento más abajo 👇.

Antes de eso construí aplicaciones de punta a punta: un sistema de inventarios con Laravel + Angular, integración de facturación electrónica con la API de Factus, y una plataforma educativa interactiva para niños.

Actualmente avanzando hacia el **5to semestre de Ingeniería de Software**. Java ☕ fue mi primer lenguaje y sigue siendo el que más disfruto escribir, aunque hoy me muevo cómodo entre Python, Angular y Spring Boot. Fuera del código, practico Karate desde hace 6 años 🥋.

---

## 🧰 Stack tecnológico

| Área | Tecnologías |
|---|---|
| **Frontend** | ![](https://skillicons.dev/icons?i=angular,ts,tailwind,bootstrap) |
| **Backend** | ![](https://skillicons.dev/icons?i=java,spring,laravel,php) |
| **Datos & Cloud** | ![](https://skillicons.dev/icons?i=py,aws,postgres,mysql,docker) |
| **Herramientas** | ![](https://skillicons.dev/icons?i=git,github,linux) |

<p>
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/ArcGIS-2C7AC3?style=flat-square&logo=esri&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20Glue%20%7C%20Athena%20%7C%20Lambda%20%7C%20ECS%20%7C%20EC2%20%7C%20CloudFormation-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
</p>

---

## ⚡ De 2 horas a 3-4 minutos: optimizando una carga masiva

En Geo-Data heredé un script de Selenium que subía informes en PDF ubicando cada uno por ID mediante **paginación manual y en orden aleatorio** — un registro podía estar en la página 1 o en la 400. Para un lote de apenas 5 archivos, el proceso completo (incluyendo arranque del navegador e inicio de sesión) tardaba cerca de **2 horas**.

Lo rediseñé usando **endpoints REST directos** en lugar de navegación por páginas, y lo integré como un DAG propio dentro del pipeline de Airflow. El mismo lote pasó a tomar **3-4 minutos**, y la solución escaló sin problema a producción con más de **1.000 archivos**.

---

## 📈 Línea de tiempo

```mermaid
gantt
    title Experiencia y proyectos
    dateFormat  YYYY-MM-DD
    axisFormat  %Y
    section Empleo
    Dronesky - Geo-Data (Solidaridad)      :2025-09-15, 2026-08-31
    section Proyectos
    Dr. Stock (grado + retomado)           :2024-03-01, 2026-08-31
    Juego educativo (freelance)            :2024-03-01, 2024-11-30
    Integración API Factus                 :2025-06-01, 2025-06-30
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

**Ingeniería de Software** — Fundación Escuela Tecnológica de Neiva (FET), Rivera-Huila — *en curso, 5to semestre*
Ciclo propedéutico: Tecnología en Desarrollo de Sistemas de Información y Redes (2026) · Técnico Profesional en Soporte de Sistemas Informáticos y Redes (2025)

---

## 📊 Actividad en GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=JuanJo24S&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JuanJo24S&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

<div align="center">

📫 **¿Hablamos?** [LinkedIn](https://www.linkedin.com/in/juan-jose-valbuena-camacho-848549278) · [Email](mailto:Juanjosecodes24@gmail.com)

![Visitas al perfil](https://komarev.com/ghpvc/?username=JuanJo24S&label=Visitas%20al%20perfil&color=0f766e&style=flat)

</div>