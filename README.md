# Hi, I'm Dileep Varada

**Software Engineer | Applied AI, Data and Test Automation**  
Toronto, ON, Canada · Master of Applied Computing, Wilfrid Laurier University  
[Portfolio](https://dileep5.github.io) · [LinkedIn](https://linkedin.com/in/dileep-varada-6a6b9b1a0) · [Email](mailto:saidileep52job@gmail.com)

---

## About me

Software engineer with 4+ years of experience at Wayfair, Accenture and Virtusa, working across Python development, test automation and data. I build LLM applications, RAG systems and data pipelines, and I test software seriously: UI and API automation with Playwright and Selenium, SQL data validation, and evaluation and adversarial testing for AI systems.

- Open to **AI Engineer**, **Data Engineer**, **SDET** and **QA Automation Engineer** roles in Canada
- Ask me about: Playwright, RAG evaluation, LangGraph agents, text-to-SQL safety, PySpark and dbt pipelines

---

## Featured projects

### [TestForge AI: SDET and Intelligent Test Automation Platform](https://github.com/Dileep5/testforge-ai-sdet-automation)
Playwright TypeScript framework for a full-stack React, FastAPI and PostgreSQL order-management app, with UI, API, OpenAPI contract, PostgreSQL, security, accessibility and k6 performance testing in a 14-job GitHub Actions pipeline with retries off.
- 154 API tests, 100 contract tests, 44 PostgreSQL tests, 114 authorization and IDOR tests, 148 accessibility and keyboard tests
- 666 Docker-based Playwright tests passed, plus a separate 650-test WebKit soak with no flaky tests
- AI failure-triage classifier scoring 33/36 on a held-out labelled benchmark

`Playwright` `TypeScript` `FastAPI` `PostgreSQL` `Ajv` `axe-core` `k6` `Docker` `GitHub Actions`

### [Enterprise AI Research Agent](https://github.com/Dileep5/enterprise-ai-research-agent)
LangGraph agent with FastAPI and MCP interfaces that routes each question to hybrid document retrieval, text-to-SQL on PostgreSQL, or both, and returns cited answers or abstains.
- Guarded LLM-generated SQL (sqlglot AST validation, read-only transactions, timeouts) and fixed a bypass found by a 25-statement adversarial probe
- Top-1 retrieval accuracy 75% → 85%, false refusals on paraphrased questions 70% → 20%
- 160 automated tests in GitHub Actions CI

`LangGraph` `FastAPI` `MCP` `PostgreSQL` `ChromaDB` `BM25` `sqlglot` `pytest`

### [WLU Hybrid RAG Assistant](https://github.com/Dileep5/wlu-chatbot-rag) · [Live demo](https://wlu-hybrid-rag-assistant.streamlit.app)
Hybrid RAG assistant for Wilfrid Laurier University with SQL-first routing, BM25 and embedding retrieval, cross-encoder reranking and citation-grounded answers.
- 202/202 correct on a 202-question development benchmark, declining all 22 out-of-scope questions
- 235 automated regression checks, with weekly data refresh through GitHub Actions

`Python` `ChromaDB` `SQLite` `BM25` `GPT-4o-mini` `Streamlit` `Docker`

### [Retail Data Lakehouse and Analytics Platform](https://github.com/Dileep5/retail-data-lakehouse)
Medallion pipeline from CSV and PostgreSQL sources into Bronze and Silver Parquet layers and a PostgreSQL warehouse, with incremental dbt models and SCD Type 2 history.
- Great Expectations checks, 40 dbt tests, 14 reconciliation checks per batch and 59 automated tests
- Verified idempotent reruns across all 9 warehouse tables

`PySpark` `dbt` `Apache Airflow` `Great Expectations` `PostgreSQL` `Parquet`

---

## Tech stack

**Languages:** Python, TypeScript, Java, JavaScript, SQL  
**Test automation:** Playwright, Selenium WebDriver, Cucumber BDD, TestNG, pytest, Postman, axe-core, k6  
**AI and LLMs:** RAG, LangGraph, LangChain, MCP, LLM evaluation, hybrid retrieval, OpenAI API, PyTorch, scikit-learn  
**Data:** PySpark, dbt, Apache Airflow, Pandas, Great Expectations, PostgreSQL, Oracle, IBM DB2  
**Cloud and DevOps:** AWS, Azure, Google Cloud, Docker, GitHub Actions, GitLab CI, Jenkins

---

## Certifications

| Certification | Issuer |
|---|---|
| Azure AI Engineer Associate | Microsoft |
| Azure Data Engineer Associate | Microsoft |
| Azure Data Scientist Associate | Microsoft |
| Power BI Data Analyst Associate | Microsoft |
| AWS Certified Developer – Associate | Amazon Web Services |
| AWS Certified Cloud Practitioner | Amazon Web Services |
| Professional Cloud Architect | Google Cloud |
| Associate Cloud Engineer | Google Cloud |

---

## Publications

- **DNA Sequencing using Machine Learning and Deep Learning Algorithms**, IJITEE, September 2022
- **Fake News Detection Using Various Algorithms**, IJSREM, December 2021
