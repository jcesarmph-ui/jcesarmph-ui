<p align="center">
  <b>🌐 Choose your language · Escolha o idioma</b><br/><br/>
  <a href="https://github.com/jcesarmph-ui">
    <img src="https://img.shields.io/badge/English-click_to_read_→-1F6FEB?style=for-the-badge" alt="Read in English"/>
  </a>
  <img src="https://img.shields.io/badge/✓_Português-atual-2EA043?style=for-the-badge" alt="Português (atual)"/>
</p>

---

# Engenharia de Controle e Automação | Ciência de Dados e Inteligência Artificial

<p align="center">
  <a href="https://www.linkedin.com/in/jcmp7/">
    <img src="https://img.shields.io/badge/LinkedIn-Perfil_Profissional-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/jcesarmph-ui?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositórios-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositórios"/>
  </a>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/foco-Engenharia_de_Dados-E25A1C?style=flat-square" alt="Foco em Engenharia de Dados"/>
  <img src="https://img.shields.io/badge/área-Ciência_de_Dados_e_IA-6A1B9A?style=flat-square" alt="Ciência de Dados e IA"/>
  <img src="https://img.shields.io/badge/área-Automação_e_Integrações-0E7490?style=flat-square" alt="Automação e Integrações"/>
  <img src="https://img.shields.io/badge/formação-Controle_e_Automação-1E3A8A?style=flat-square" alt="Engenharia de Controle e Automação"/>
</p>

<p align="center">
  Portfólio de soluções que vão do dado bruto à decisão: <b>pipelines de dados</b>, <b>Machine Learning</b>,
  <b>automação de atendimento com IA</b> e <b>aplicações para a indústria</b>, incluindo sistemas em uso
  real em ambiente industrial.
</p>

<p align="center">
  <b>📄 Currículo</b><br/>
  <a href="https://github.com/jcesarmph-ui/jcesarmph-ui/blob/main/curriculo/Resume_Julio_Cesar_Moreira_Pereira_EN.pdf"><img src="https://img.shields.io/badge/Resume-English_(PDF)-1F6FEB?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume in English (PDF)"/></a>
  <a href="https://github.com/jcesarmph-ui/jcesarmph-ui/blob/main/curriculo/Curriculo_Julio_Cesar_Moreira_Pereira_PT.pdf"><img src="https://img.shields.io/badge/Currículo-Português_(PDF)-2EA043?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Currículo em português (PDF)"/></a>
</p>

<p align="center">
  <a href="#-em-números">Em números</a> •
  <a href="#-visão-geral">Visão geral</a> •
  <a href="#-projetos">Projetos</a> •
  <a href="#-tecnologias-e-ferramentas">Tecnologias</a> •
  <a href="#-competências">Competências</a> •
  <a href="#-estatísticas">Estatísticas</a>
</p>

---

## 📊 Em números

| Indicador | Valor | Contexto |
|---|---|---|
| Projetos de software publicados | **9** | Dados, Machine Learning, IA aplicada, automação e aplicações desktop e web |
| Sistemas em uso na empresa | **2** | Gestão de Calibração (v1.4.1) e Classificação de Aços Planos (v1.0.0) |
| Testes automatizados | **410** | Suíte pytest do Sistema de Gestão de Calibração |
| Linguagens principais | **3** | Python, JavaScript (Node.js) e SQL |
| Artigos publicados | **3** | IA, IoT e ética, no blog Crescendo Juntos (FESA) |

## 🧭 Visão geral

Cada etapa do ciclo de dados aparece em pelo menos um dos projetos:

```mermaid
flowchart LR
    A["Coleta<br/>WhatsApp · MQTT · planilhas"] --> B["Integração<br/>webhooks · Kafka · APIs"]
    B --> C["Armazenamento<br/>SQLite · MongoDB · PostgreSQL · Parquet"]
    C --> D["Processamento<br/>ETL · Airflow · Spark · DuckDB"]
    D --> E["Inteligência<br/>Random Forest · NLP · LLM"]
    E --> F["Entrega<br/>apps desktop · API · dashboards"]

    A -.- P1(["Conserta Fácil · Smart City"])
    B -.- P2(["Data Analytics"])
    E -.- P3(["SmartPredict · Classificação de Aços · Leitor de Certificados"])
    F -.- P4(["Gestão de Calibração · Profits"])

    classDef etapa fill:#E0F2FE,stroke:#0284C7,color:#0C4A6E
    classDef projeto fill:#F1F5F9,stroke:#64748B,color:#1E293B
    class A,B,C,D,E,F etapa
    class P1,P2,P3,P4 projeto
```

## 🚀 Projetos

### 🔎 Visão rápida

| Projeto | Área | Tecnologias principais | Status |
|---|---|---|---|
| [Sistema de Gestão de Calibração](https://github.com/jcesarmph-ui/SistemaCalibracao) | Qualidade industrial | Python, PySide6, SQLite, pytest | ![Em uso](https://img.shields.io/badge/em_uso_na_empresa-brightgreen?style=flat-square) |
| [Classificação de Aços Planos](https://github.com/jcesarmph-ui/SistemaDeClassificacao) | Qualidade industrial | Python, PySide6, scikit-learn, Pydantic | ![Em uso](https://img.shields.io/badge/em_uso_na_empresa-brightgreen?style=flat-square) |
| [Leitor de Certificados com IA](https://github.com/jcesarmph-ui/LeitorCertificadosIA) | IA aplicada e metrologia | scikit-learn, OCR, PySide6 | ![Em uso](https://img.shields.io/badge/em_uso_no_sistema_de_calibração-brightgreen?style=flat-square) |
| [Conserta Fácil](https://github.com/jcesarmph-ui/conserta-facil) | Atendimento e IA | Node.js, WhatsApp Cloud API, OpenAI API | ![Em desenvolvimento](https://img.shields.io/badge/em_desenvolvimento-yellow?style=flat-square) |
| [Data Analytics](https://github.com/jcesarmph-ui/DataAnalytics) | Engenharia de Dados | Kafka, Airflow, MongoDB, Spark, Power BI | ![Concluído](https://img.shields.io/badge/versão_inicial_concluída-blue?style=flat-square) |
| [SmartPredict](https://github.com/jcesarmph-ui/SmartPredict) | Machine Learning | Scikit-learn, SHAP, Pandas | ![Concluído](https://img.shields.io/badge/concluído-blue?style=flat-square) |
| [Smart City Data Platform](https://github.com/jcesarmph-ui/SmartCityDataPlatform) | Dados urbanos e IoT | MQTT, DuckDB, Parquet, FastAPI | ![Em desenvolvimento](https://img.shields.io/badge/em_desenvolvimento-yellow?style=flat-square) |
| [Profits](https://github.com/jcesarmph-ui/Profits) | Finanças pessoais | Python, PySide6, Qt Charts, SQLite | ![Em desenvolvimento](https://img.shields.io/badge/em_desenvolvimento-yellow?style=flat-square) |
| [Plataforma Web de Análise Sensorial](https://github.com/jcesarmph-ui/PlataformaWeb-AnaliseSensorial) | Aplicação web (TCC) | JavaScript, Supabase, PostgreSQL | ![TCC nota máxima](https://img.shields.io/badge/TCC-nota_máxima-brightgreen?style=flat-square) |

<details open>
<summary><b>🏭 Sistemas em uso na indústria</b></summary>
<br/>
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📏 <a href="https://github.com/jcesarmph-ui/SistemaCalibracao">Sistema de Gestão de Calibração</a></h3>
      Aplicativo desktop que substituiu uma planilha de cronograma de calibração: cadastro de instrumentos e
      planos, <b>avaliação automática pela incerteza de medição</b>, cronograma mensal, certificados em PDF,
      painel de indicadores e relatórios mensais automáticos, com uso simultâneo em pasta de rede.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6"/>
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
      <img src="https://img.shields.io/badge/pytest-410_testes-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest"/>
      <img src="https://img.shields.io/badge/PyInstaller-.exe-4B8BBE?style=flat-square&logo=python&logoColor=white" alt="PyInstaller"/>
    </td>
    <td width="50%" valign="top">
      <h3>🔩 <a href="https://github.com/jcesarmph-ui/SistemaDeClassificacao">Classificação de Aços Planos</a></h3>
      Aplicação desktop que <b>classifica aços planos</b> (laminados a frio, a quente e zincados) a partir das
      propriedades mecânicas e químicas, com motor de regras baseado nas normas ABNT, histórico compartilhado
      e avisos de <b>Machine Learning</b> aprendidos com o próprio histórico.
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
<summary><b>🤖 Automação e IA aplicada</b></summary>
<br/>
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💬 <a href="https://github.com/jcesarmph-ui/conserta-facil">Conserta Fácil</a></h3>
      Chatbot de atendimento no <b>WhatsApp</b> para uma assistência técnica fictícia: orçamento, consulta de
      reparo por protocolo, agendamento e encaminhamento para a equipe. A IA interpreta mensagens em texto
      livre com <b>saída estruturada em JSON Schema</b>, e o webhook valida cada evento com HMAC SHA-256.
      <br/><br/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
      <img src="https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp Cloud API"/>
      <img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI API"/>
      <img src="https://img.shields.io/badge/Webhooks-555555?style=flat-square" alt="Webhooks"/>
    </td>
    <td width="50%" valign="top">
      <h3>💰 <a href="https://github.com/jcesarmph-ui/Profits">Profits</a></h3>
      Aplicativo desktop de <b>gestão de carteira de investimentos</b> que substitui uma planilha: patrimônio por
      classe de ativo, alocação atual e desejada, fechamento mensal com conferências e cotações do dólar e do
      Bitcoin consultadas automaticamente por API.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6"/>
      <img src="https://img.shields.io/badge/Qt_Charts-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt Charts"/>
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🧾 <a href="https://github.com/jcesarmph-ui/LeitorCertificadosIA">Leitor de Certificados com IA</a></h3>
      Modelo de <b>machine learning</b> que lê certificados de calibração em PDF, digitais ou escaneados
      (<b>OCR</b> local), encontra número do certificado, data, padrões e pontos medidos e confere o
      <b>erro ± U</b> com a tolerância do plano. Treinado com certificados fictícios e melhorado com correções
      reais (campos essenciais de 77% para 96%). Em uso dentro do Sistema de Gestão de Calibração.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
      <img src="https://img.shields.io/badge/OCR-RapidOCR-555555?style=flat-square" alt="RapidOCR"/>
      <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6"/>
      <img src="https://img.shields.io/badge/pyHanko-assinatura_digital-4B5563?style=flat-square" alt="pyHanko"/>
    </td>
  </tr>
</table>
</details>

<details open>
<summary><b>🗄️ Engenharia de Dados e Machine Learning</b></summary>
<br/>
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📈 <a href="https://github.com/jcesarmph-ui/DataAnalytics">Data Analytics</a></h3>
      Pipeline de avaliações de produtos com <b>mensageria, classificação de sentimentos, armazenamento NoSQL,
      orquestração e BI</b>: Kafka transmite os dados, o MongoDB armazena, o Airflow agenda o ETL e o Power BI
      apresenta os indicadores.
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
      <b>Manutenção preditiva industrial</b> com o dataset AI4I 2020 (10.000 registros): ETL, análise
      exploratória, Random Forest, otimização com RandomizedSearchCV, testes de estresse e interpretabilidade
      com <b>SHAP</b>.
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
      Plataforma de <b>dados urbanos</b> com sensores simulados de clima, qualidade do ar e mobilidade: publicação
      via MQTT, validação das leituras, cópia analítica em Parquet, consultas com DuckDB, API FastAPI e
      dashboard web local, sem necessidade de hardware físico.
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
<summary><b>🌐 Aplicações web e publicações</b> (clique para expandir)</summary>
<br/>
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🍽️ <a href="https://github.com/jcesarmph-ui/PlataformaWeb-AnaliseSensorial">Plataforma Web de Análise Sensorial</a></h3>
      Trabalho de Conclusão de Curso, <b>avaliado com nota máxima</b>, sobre uma plataforma web que <b>automatiza a
      análise sensorial de alimentos</b>, validada com 26 voluntários, com redução de 45,65% no tempo de execução no cenário comparativo do estudo.
      <br/><br/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"/>
    </td>
    <td width="50%" valign="top">
      <h3>✍️ <a href="https://github.com/jcesarmph-ui/Textos-Publicados">Artigos de Tecnologia</a></h3>
      Artigos técnicos sobre <b>Inteligência Artificial, Internet das Coisas e cidades inteligentes</b>,
      publicados no blog Crescendo Juntos da Faculdade Engenheiro Salvador Arena.
      <br/><br/>
      <img src="https://img.shields.io/badge/IA-6A1B9A?style=flat-square" alt="IA"/>
      <img src="https://img.shields.io/badge/IoT-00979D?style=flat-square" alt="IoT"/>
      <img src="https://img.shields.io/badge/Ética-555555?style=flat-square" alt="Ética"/>
    </td>
  </tr>
</table>
</details>

## 🧰 Tecnologias e ferramentas

Somente tecnologias aplicadas em pelo menos um dos projetos acima.

<details open>
<summary><b>🐍 Linguagens</b></summary>
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
<summary><b>🔗 Engenharia de Dados e Big Data</b></summary>
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
<summary><b>💾 Bancos de dados</b></summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase"/>
</p>
</details>

<details open>
<summary><b>🧪 Machine Learning e IA</b></summary>
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

- Classificação e modelagem preditiva com Random Forest e Regressão Logística
- Processamento de Linguagem Natural: TF-IDF, Bag of Words e análise de sentimentos
- Interpretabilidade de modelos com SHAP
- LLM com saída estruturada (JSON Schema) para extrair dados de texto livre
- Extração de informações de PDFs com OCR local e classificador de palavras

</details>

<details open>
<summary><b>🔌 APIs, integrações e aplicações</b></summary>
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
<summary><b>🛠️ Qualidade de software, empacotamento e ferramentas</b></summary>
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
<summary><b>✨ IA como ferramenta de desenvolvimento</b> (clique para expandir)</summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code"/>
  <img src="https://img.shields.io/badge/Codex-000000?style=for-the-badge&logo=openai&logoColor=white" alt="Codex"/>
</p>

Assistentes de IA usados no desenvolvimento, com regras de negócio, arquitetura e revisão de cada etapa
definidas manualmente.

</details>

## 🧠 Competências

```mermaid
mindmap
  root((Competências))
    Engenharia de Dados
      Pipelines ETL
      Kafka e Airflow
      Spark e DuckDB
      Parquet
    Ciência de Dados e ML
      Análise exploratória
      Random Forest
      NLP e sentimentos
      SHAP
    IA aplicada
      LLM com saída estruturada
      Chatbot no WhatsApp
      Fallback sem IA
      OCR e extração de documentos
    Integrações
      Webhooks
      APIs REST e FastAPI
      HMAC SHA-256
      MQTT
    Desenvolvimento
      Aplicações desktop PySide6
      Node.js
      Aplicações web
    Qualidade de software
      Testes com pytest
      Validação com Pydantic
      Empacotamento para Windows
    Indústria
      Gestão de calibração
      Incerteza de medição
      Normas ABNT
      Manutenção preditiva
```

## 📈 Estatísticas

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jcesarmph-ui&show_icons=true&theme=tokyonight" alt="Estatísticas do GitHub" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jcesarmph-ui&layout=compact&theme=tokyonight" alt="Linguagens mais usadas" height="165"/>
</p>

---

<p align="center">
  <b>Projetos práticos que aplicam dados, IA e automação a problemas reais, da indústria ao atendimento.</b>
</p>

<p align="center">
  🌐 <a href="https://github.com/jcesarmph-ui">Read this page in English</a>
</p>
