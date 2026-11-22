<p align="center">
  <b>🌐 Choose your language · Escolha o idioma</b><br/><br/>
  <img src="https://img.shields.io/badge/✓_English-current-1F6FEB?style=for-the-badge" alt="English (current)"/>
  <a href="https://github.com/jcesarmph-ui/jcesarmph-ui/blob/main/README.pt-BR.md">
    <img src="https://img.shields.io/badge/Português-clique_para_ler_→-2EA043?style=for-the-badge" alt="Ler em português"/>
  </a>
</p>

---

# Control and Automation Engineering | Data Science and Artificial Intelligence

<p align="center">
  <a href="https://www.linkedin.com/in/jcmp7/">
    <img src="https://img.shields.io/badge/LinkedIn-Professional_Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/jcesarmph-ui?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/>
  </a>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/focus-Data_Engineering-E25A1C?style=flat-square" alt="Focus on Data Engineering"/>
  <img src="https://img.shields.io/badge/field-Data_Science_and_AI-6A1B9A?style=flat-square" alt="Data Science and AI"/>
  <img src="https://img.shields.io/badge/field-Automation_and_Integrations-0E7490?style=flat-square" alt="Automation and Integrations"/>
  <img src="https://img.shields.io/badge/degree-Control_and_Automation-1E3A8A?style=flat-square" alt="Control and Automation Engineering"/>
</p>

<p align="center">
  Portfolio of solutions that go from raw data to decisions: <b>data pipelines</b>, <b>Machine Learning</b>,
  <b>AI-powered customer service automation</b> and <b>industrial applications</b>, including systems in
  real use in an industrial environment.
</p>

<p align="center">
  <a href="#-in-numbers">In numbers</a> •
  <a href="#-overview">Overview</a> •
  <a href="#-projects">Projects</a> •
  <a href="#-technologies-and-tools">Technologies</a> •
  <a href="#-skills">Skills</a> •
  <a href="#-statistics">Statistics</a>
</p>

---

## 📊 In numbers

| Indicator | Value | Context |
|---|---|---|
| Published software projects | **9** | Data, Machine Learning, applied AI, automation, and desktop and web applications |
| Systems in use at the company | **2** | Calibration Management (v1.4.1) and Flat Steel Classification (v1.0.0) |
| Automated tests | **410** | pytest suite of the Calibration Management System |
| Main languages | **3** | Python, JavaScript (Node.js) and SQL |
| Published articles | **3** | AI, IoT and ethics, on the Crescendo Juntos blog (FESA) |

## 🧭 Overview

Each stage of the data lifecycle appears in at least one of the projects:

```mermaid
flowchart LR
    A["Collection<br/>WhatsApp · MQTT · spreadsheets"] --> B["Integration<br/>webhooks · Kafka · APIs"]
    B --> C["Storage<br/>SQLite · MongoDB · PostgreSQL · Parquet"]
    C --> D["Processing<br/>ETL · Airflow · Spark · DuckDB"]
    D --> E["Intelligence<br/>Random Forest · NLP · LLM"]
    E --> F["Delivery<br/>desktop apps · API · dashboards"]

    A -.- P1(["EasyFix · Smart City"])
    B -.- P2(["Data Analytics"])
    E -.- P3(["SmartPredict · Steel Classification · Certificate Reader"])
    F -.- P4(["Calibration Management · Profits"])

    classDef etapa fill:#E0F2FE,stroke:#0284C7,color:#0C4A6E
    classDef projeto fill:#F1F5F9,stroke:#64748B,color:#1E293B
    class A,B,C,D,E,F etapa
    class P1,P2,P3,P4 projeto
```

## 🚀 Projects

### 🔎 Quick view

| Project | Area | Main technologies | Status |
|---|---|---|---|
| [Calibration Management System](https://github.com/jcesarmph-ui/SistemaCalibracao) | Industrial quality | Python, PySide6, SQLite, pytest | ![In use](https://img.shields.io/badge/in_use_at_the_company-brightgreen?style=flat-square) |
| [Flat Steel Classification](https://github.com/jcesarmph-ui/SistemaDeClassificacao) | Industrial quality | Python, PySide6, scikit-learn, Pydantic | ![In use](https://img.shields.io/badge/in_use_at_the_company-brightgreen?style=flat-square) |
| [AI Certificate Reader](https://github.com/jcesarmph-ui/LeitorCertificadosIA) | Applied AI and metrology | scikit-learn, OCR, PySide6 | ![In use](https://img.shields.io/badge/in_use_in_the_calibration_system-brightgreen?style=flat-square) |
| [EasyFix](https://github.com/jcesarmph-ui/conserta-facil) | Customer service and AI | Node.js, WhatsApp Cloud API, OpenAI API | ![In development](https://img.shields.io/badge/in_development-yellow?style=flat-square) |
| [Data Analytics](https://github.com/jcesarmph-ui/DataAnalytics) | Data Engineering | Kafka, Airflow, MongoDB, Spark, Power BI | ![Completed](https://img.shields.io/badge/initial_version_completed-blue?style=flat-square) |
| [SmartPredict](https://github.com/jcesarmph-ui/SmartPredict) | Machine Learning | Scikit-learn, SHAP, Pandas | ![Completed](https://img.shields.io/badge/completed-blue?style=flat-square) |
| [Smart City Data Platform](https://github.com/jcesarmph-ui/SmartCityDataPlatform) | Urban data and IoT | MQTT, DuckDB, Parquet, FastAPI | ![In development](https://img.shields.io/badge/in_development-yellow?style=flat-square) |
| [Profits](https://github.com/jcesarmph-ui/Profits) | Personal finance | Python, PySide6, Qt Charts, SQLite | ![In development](https://img.shields.io/badge/in_development-yellow?style=flat-square) |
| [Sensory Analysis Web Platform](https://github.com/jcesarmph-ui/PlataformaWeb-AnaliseSensorial) | Web application (thesis) | JavaScript, Supabase, PostgreSQL | ![Thesis top grade](https://img.shields.io/badge/thesis-top_grade-brightgreen?style=flat-square) |

<details open>
<summary><b>🏭 Systems in industrial use</b></summary>
<br/>
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📏 <a href="https://github.com/jcesarmph-ui/SistemaCalibracao">Calibration Management System</a></h3>
      Desktop application that replaced a calibration schedule spreadsheet: registry of instruments and plans,
      <b>automatic evaluation based on measurement uncertainty</b>, monthly schedule, PDF certificates, KPI
      dashboard and automatic monthly reports, with simultaneous use from a shared network folder.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6"/>
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
      <img src="https://img.shields.io/badge/pytest-410_tests-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest"/>
      <img src="https://img.shields.io/badge/PyInstaller-.exe-4B8BBE?style=flat-square&logo=python&logoColor=white" alt="PyInstaller"/>
    </td>
    <td width="50%" valign="top">
      <h3>🔩 <a href="https://github.com/jcesarmph-ui/SistemaDeClassificacao">Flat Steel Classification</a></h3>
      Desktop application that <b>classifies flat steel</b> (cold-rolled, hot-rolled and galvanized) from its
      mechanical and chemical properties, with a rules engine based on Brazilian ABNT standards, a shared history
      and <b>Machine Learning</b> warnings learned from that history.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6"/>
      <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
      <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic"/>
      <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="Pytest"/>
    </td>
  </tr>
</table>
</details>

<details open>
<summary><b>🤖 Automation and applied AI</b></summary>
<br/>
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💬 <a href="https://github.com/jcesarmph-ui/conserta-facil">EasyFix</a></h3>
      <b>WhatsApp</b> customer service chatbot for a fictitious phone repair shop: quotes, repair tracking by
      protocol number, scheduling and handoff to the team. The AI interprets free-text messages with
      <b>structured output in JSON Schema</b>, and the webhook validates every event with HMAC SHA-256.
      <br/><br/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
      <img src="https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp Cloud API"/>
      <img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI API"/>
      <img src="https://img.shields.io/badge/Webhooks-555555?style=flat-square" alt="Webhooks"/>
    </td>
    <td width="50%" valign="top">
      <h3>💰 <a href="https://github.com/jcesarmph-ui/Profits">Profits</a></h3>
      Desktop application for <b>investment portfolio management</b> that replaces a spreadsheet: net worth by
      asset class, current versus target allocation, monthly closing with validation checks, and dollar and
      Bitcoin quotes fetched automatically from an API.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6"/>
      <img src="https://img.shields.io/badge/Qt_Charts-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt Charts"/>
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🧾 <a href="https://github.com/jcesarmph-ui/LeitorCertificadosIA">AI Certificate Reader</a></h3>
      <b>Machine learning</b> model that reads calibration certificates in PDF, digital or scanned (local
      <b>OCR</b>), finds the certificate number, date, reference standards and measured points, and checks
      <b>error ± U</b> against the plan's tolerance. Trained on fictitious certificates and improved with real
      corrections (essential fields from 77% to 96%). In use inside the Calibration Management System.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
      <img src="https://img.shields.io/badge/OCR-RapidOCR-555555?style=flat-square" alt="RapidOCR"/>
      <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6"/>
      <img src="https://img.shields.io/badge/pyHanko-digital_signature-4B5563?style=flat-square" alt="pyHanko"/>
    </td>
  </tr>
</table>
</details>

<details open>
<summary><b>🗄️ Data Engineering and Machine Learning</b></summary>
<br/>
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📈 <a href="https://github.com/jcesarmph-ui/DataAnalytics">Data Analytics</a></h3>
      Product review pipeline with <b>messaging, sentiment classification, NoSQL storage, orchestration and
      BI</b>: Kafka streams the data, MongoDB stores it, Airflow schedules the ETL and Power BI presents the
      indicators.
      <br/><br/>
      <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka"/>
      <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" alt="Apache Airflow"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB"/>
      <img src="https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI"/>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ <a href="https://github.com/jcesarmph-ui/SmartPredict">SmartPredict</a></h3>
      <b>Industrial predictive maintenance</b> with the AI4I 2020 dataset (10,000 records): ETL, exploratory
      analysis, Random Forest, optimization with RandomizedSearchCV, stress tests and interpretability with
      <b>SHAP</b>.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
      <img src="https://img.shields.io/badge/SHAP-8A2BE2?style=flat-square" alt="SHAP"/>
      <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white" alt="Google Colab"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🏙️ <a href="https://github.com/jcesarmph-ui/SmartCityDataPlatform">Smart City Data Platform</a></h3>
      <b>Urban data</b> platform with simulated weather, air quality and mobility sensors: publishing via MQTT,
      reading validation, an analytical copy in Parquet, queries with DuckDB, a FastAPI API and a local web
      dashboard, with no physical hardware required.
      <br/><br/>
      <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT"/>
      <img src="https://img.shields.io/badge/Mosquitto-3C5280?style=flat-square&logo=eclipsemosquitto&logoColor=white" alt="Eclipse Mosquitto"/>
      <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB"/>
      <img src="https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white" alt="Apache Parquet"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
    </td>
  </tr>
</table>
</details>

<details>
<summary><b>🌐 Web applications and publications</b> (click to expand)</summary>
<br/>
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🍽️ <a href="https://github.com/jcesarmph-ui/PlataformaWeb-AnaliseSensorial">Sensory Analysis Web Platform</a></h3>
      Undergraduate thesis, <b>awarded the top grade</b>, on a web platform that <b>automates sensory analysis
      of food</b>, validated with 26 volunteers, with a 45.65% reduction in execution time in the study's
      comparative scenario.
      <br/><br/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"/>
    </td>
    <td width="50%" valign="top">
      <h3>✍️ <a href="https://github.com/jcesarmph-ui/Textos-Publicados">Technology Articles</a></h3>
      Technical articles on <b>Artificial Intelligence, the Internet of Things and smart cities</b>, published
      on the Crescendo Juntos blog of Faculdade Engenheiro Salvador Arena (in Portuguese).
      <br/><br/>
      <img src="https://img.shields.io/badge/AI-6A1B9A?style=flat-square" alt="AI"/>
      <img src="https://img.shields.io/badge/IoT-00979D?style=flat-square" alt="IoT"/>
      <img src="https://img.shields.io/badge/Ethics-555555?style=flat-square" alt="Ethics"/>
    </td>
  </tr>
</table>
</details>

## 🧰 Technologies and tools

Only technologies applied in at least one of the projects above.

<details open>
<summary><b>🐍 Languages</b></summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
</p>
</details>

<details open>
<summary><b>🔗 Data Engineering and Big Data</b></summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Apache Kafka"/>
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Apache Airflow"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark"/>
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB"/>
  <img src="https://img.shields.io/badge/Apache_Parquet-50ABF1?style=for-the-badge&logo=apacheparquet&logoColor=white" alt="Apache Parquet"/>
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" alt="MQTT"/>
</p>
</details>

<details open>
<summary><b>💾 Databases</b></summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase"/>
</p>
</details>

<details open>
<summary><b>🧪 Machine Learning and AI</b></summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/NLTK-154F5B?style=for-the-badge&logo=python&logoColor=white" alt="NLTK"/>
  <img src="https://img.shields.io/badge/SHAP-8A2BE2?style=for-the-badge" alt="SHAP"/>
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API"/>
  <img src="https://img.shields.io/badge/OCR-RapidOCR-555555?style=for-the-badge" alt="RapidOCR"/>
</p>

- Classification and predictive modeling with Random Forest and Logistic Regression
- Natural Language Processing: TF-IDF, Bag of Words and sentiment analysis
- Model interpretability with SHAP
- LLM with structured output (JSON Schema) to extract data from free text
- Information extraction from PDFs with local OCR and a token classifier

</details>

<details open>
<summary><b>🔌 APIs, integrations and applications</b></summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Cloud API"/>
  <img src="https://img.shields.io/badge/PySide6-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PySide6"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/>
</p>
</details>

<details open>
<summary><b>🛠️ Software quality, packaging and tools</b></summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic"/>
  <img src="https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black" alt="Ruff"/>
  <img src="https://img.shields.io/badge/PyInstaller-4B8BBE?style=for-the-badge&logo=python&logoColor=white" alt="PyInstaller"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Visual Studio Code"/>
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab"/>
</p>
</details>

<details>
<summary><b>✨ AI as a development tool</b> (click to expand)</summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code"/>
  <img src="https://img.shields.io/badge/Codex-000000?style=for-the-badge&logo=openai&logoColor=white" alt="Codex"/>
</p>

AI assistants used during development, with business rules, architecture and the review of each stage
defined manually.

</details>

## 🧠 Skills

```mermaid
mindmap
  root((Skills))
    Data Engineering
      ETL pipelines
      Kafka and Airflow
      Spark and DuckDB
      Parquet
    Data Science and ML
      Exploratory analysis
      Random Forest
      NLP and sentiment
      SHAP
    Applied AI
      LLM with structured output
      WhatsApp chatbot
      Fallback without AI
      OCR and document extraction
    Integrations
      Webhooks
      REST APIs and FastAPI
      HMAC SHA-256
      MQTT
    Development
      PySide6 desktop apps
      Node.js
      Web applications
    Software quality
      Testing with pytest
      Validation with Pydantic
      Packaging for Windows
    Industry
      Calibration management
      Measurement uncertainty
      ABNT standards
      Predictive maintenance
```

## 📈 Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jcesarmph-ui&show_icons=true&theme=tokyonight" alt="GitHub statistics" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jcesarmph-ui&layout=compact&theme=tokyonight" alt="Most used languages" height="165"/>
</p>

---

<p align="center">
  <b>Hands-on projects applying data, AI and automation to real problems, from industry to customer service.</b>
</p>

<p align="center">
  🌐 <a href="https://github.com/jcesarmph-ui/jcesarmph-ui/blob/main/README.pt-BR.md">Ler esta página em português</a>
</p>
