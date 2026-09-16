<h1 align="center">Sarra Bouden</h1>

<p align="center">
  <b>Data Engineer</b> · Bac+5 ESPRIT (CTI / EUR-ACE) · 6-month internship at Mercedes-Benz AG, Sindelfingen
</p>

<p align="center">
  <i>I build the data infrastructure — and because I built the evaluation harness for a<br/>
  production LLM system at Mercedes-Benz, I can also prove the AI layer on top of it works.</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sarra-bouden/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sarrabouden1@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Data%20Engineering%20roles%20in%20Europe-2ea44f?style=for-the-badge" alt="Open to work"/>
</p>

---

### What I build

```mermaid
flowchart LR
    I["<b>Ingest</b>"]
    M["<b>Model</b>"]
    O["<b>Orchestrate</b>"]
    P["<b>Serve</b>"]
    E["<b>Measure</b>"]

    I --> M --> O --> P
    E -.->|instruments every stage| O

    style I fill:#1f6feb,color:#fff,stroke:none
    style M fill:#1f6feb,color:#fff,stroke:none
    style O fill:#1f6feb,color:#fff,stroke:none
    style P fill:#1f6feb,color:#fff,stroke:none
    style E fill:#8957e5,color:#fff,stroke:none
```

Get data in, model it so it means something, run it on a schedule that can be trusted, and put it where people can use it. The purple box is the one most people skip: **whatever sits on top — a dashboard, a model, an LLM system — I want a way to tell whether it's actually working.**

---

### Stack

**Core**
<p>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white"/>
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
</p>

**Streaming & platform**
<p>
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/Debezium-D9411E?style=flat-square&logo=redhat&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pub%2FSub-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
</p>

**AI engineering**
<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG%20%2F%20GraphRAG-8957e5?style=flat-square"/>
  <img src="https://img.shields.io/badge/LLM%20evaluation-8957e5?style=flat-square"/>
</p>

---

### Mercedes-Benz AG — Sindelfingen · 6-month internship

<table>
<tr>
<td width="25%" align="center"><b>500+</b><br/><sub>modules ingested</sub></td>
<td width="25%" align="center"><b>11</b><br/><sub>agent LangGraph pipeline</sub></td>
<td width="25%" align="center"><b>31</b><br/><sub>tests on the MCP server</sub></td>
<td width="25%" align="center"><b>81%</b><br/><sub>retrieval precision, measured</sub></td>
</tr>
</table>

Multi-format document ingestion (PDF · HTML · C · SVG · Simulink) feeding a multi-agent GraphRAG system, exposed through an MCP server (fastmcp, FastAPI, SSE). The part I care about most is the last column: a RetrievalTrace instrumentation layer, a 35-question gold-standard dataset and LLM-as-judge scoring — so the 81% is a measurement, not an impression.

---

### Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🔵 [realtime-cdc-pipeline](https://github.com/sarahbouden/realtime-cdc-pipeline)
Postgres WAL → analytical warehouse via change data capture.

`Debezium` `Kafka` `Flink` `DuckDB` `dbt` `Airflow` `Grafana` `Terraform`

</td>
<td width="50%" valign="top">

#### 🔵 [financial-transactions-platform](https://github.com/sarahbouden/financial-transactions-platform)
Dual-write streaming ingestion into a 3-layer warehouse, **28 dbt tests**, CI on every PR.

`Kafka` `Pub/Sub` `S3` `BigQuery` `dbt` `Airflow` `Actions` `Prometheus`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🟣 [fake-news-detection](https://github.com/sarahbouden/fake-news-detection)
Multi-agent claim verification graph with conditional routing and an explicit error path.

`LangGraph` `Groq` `FastAPI` `sentence-transformers`

</td>
<td width="50%" valign="top">

#### 🟣 [ContractScan](https://github.com/sarahbouden/ContractScan)
Clause-level contract comparison, human-in-the-loop, LLM fully local — no document leaves the machine.

`Ollama/Mistral` `LangChain` `Streamlit` `FPDF2`

</td>
</tr>
</table>

> Both data engineering projects are self-built portfolio systems, not production systems operated under load. Each README says so explicitly, and lists its own limits.

---

### Currently working on

`timed SQL` &nbsp;·&nbsp; `dimensional modelling write-ups` &nbsp;·&nbsp; `streaming semantics — ordering, delivery guarantees, schema evolution, replay`

<p align="center">
  <sub>Open to Data Engineering and Analytics Engineering roles in Europe · visa sponsorship required</sub>
</p>
