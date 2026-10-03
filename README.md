<!-- ============================ HEADER ============================ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=210&section=header&text=Kazi%20Hasebul%20Islam&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%E2%80%A2%20Applied%20AI%20%26%20Intelligent%20Automation&descAlignY=57&descSize=17&animation=fadeIn" width="100%" alt="Kazi Hasebul Islam" />
</p>

<p align="center">
  <a href="https://github.com/Hasebul47">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2F81F7&center=true&vCenter=true&width=640&lines=AI+Developer+%40+Ha-Meem+Group;16%2B+production+AI+systems+shipped;LLM+Document+Intelligence+%7C+OCR+%7C+Vision;Agentic+RAG+%7C+Text-to-SQL+%7C+Multi-Model+LLMs;FastAPI+%7C+Docker+%7C+Oracle+%7C+CI%2FCD" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/hasebulislam"><img src="https://img.shields.io/badge/LinkedIn-hasebulislam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hasebulislam47@gmail.com"><img src="https://img.shields.io/badge/Email-hasebulislam47%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://doi.org/10.1109/STI64222.2024.10951130"><img src="https://img.shields.io/badge/IEEE-Publication-00629B?style=for-the-badge&logo=ieee&logoColor=white" alt="IEEE Publication" /></a>
  <img src="https://komarev.com/ghpvc/?username=Hasebul47&style=for-the-badge&color=2F81F7&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## 👋 About Me

```python
class HasebulIslam:
    role        = "AI Engineer / AI Developer"
    company     = "Ha-Meem Group"            # one of Bangladesh's largest garment manufacturers
    location    = "Dhaka, Bangladesh 🇧🇩"
    education   = "B.Sc. in Computer Science & Engineering — Green University of Bangladesh"

    focus = [
        "LLM-powered document extraction (PDFs, scans, IDs)",
        "OCR & computer vision with vision-language models",
        "Agentic RAG and Text-to-SQL over live ERP data",
        "Multi-model LLM routing with automatic failover",
        "Production deployment: FastAPI · Docker · CI/CD",
    ]

    shipped    = "16+ AI & automation systems running in production"
    published  = "2 IEEE papers on ensemble machine learning"

    def say_hi(self):
        return "Let's build AI that actually ships. 🚀"
```

---

## 🧠 What I Build

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📄 Intelligent Document Processing</h3>
      LLM extraction pipelines that turn Purchase Orders, CVs and National IDs — from PDFs and scanned images — into validated Oracle ERP records, with OCR and vision-model fallback for image-only files.
    </td>
    <td width="50%" valign="top">
      <h3>💬 AI Chatbot (Agentic RAG)</h3>
      A RAG chatbot that answers natural-language business questions on live ERP data, using agentic schema retrieval and Text-to-SQL.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔀 Multi-Model Architecture</h3>
      A provider-independent LLM layer with automatic failover across cloud and on-premise models (OpenAI, Gemini, OpenRouter, Ollama), cutting inference cost and vendor lock-in.
    </td>
    <td width="50%" valign="top">
      <h3>👁️ Multimodal AI</h3>
      Integrated computer vision, NLP and RAG for multimodal, knowledge-driven AI systems.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🕸️ Web Scraping & Alerting</h3>
      Concurrent multi-source scrapers with a background worker that pushes real-time alerts over WhatsApp, Telegram and email.
    </td>
    <td width="50%" valign="top">
      <h3>🚢 Deployment</h3>
      Every system shipped as containerised FastAPI + Streamlit services with automated CI/CD to Linux hosts.
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

> Click a project to expand it.

<details>
<summary><b>📦 PO Extraction & ERP Sync Platform</b> &nbsp;<code>Production</code></summary>
<br/>

- Extraction engine with buyer-specific parsers for **40+ international buyers**, converting heterogeneous PO PDFs into normalised Excel and Oracle records.
- Integrated offline **Japanese→English** and **Russian→English** neural machine translation to process foreign-language orders without external API calls.
- Constraint validation on upload and continuous deployment via GitHub Actions.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
</details>

<details>
<summary><b>🪪 Intelligent Document Processing Microservice (CV / NID / PO)</b> &nbsp;<code>Production</code></summary>
<br/>

- Stateless microservice extracting structured data from resume and identity documents.
- Pages are rasterised and sent to a **vision-language model** when no text layer exists; output is constrained by **Pydantic** schemas before being written to Oracle HR tables.
- Pluggable provider (Gemini ⇄ OpenAI) behind a single engine interface.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_Vision-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
</details>

<details>
<summary><b>🤖 ERP AI Chatbot — Agentic RAG</b> &nbsp;<code>Production</code></summary>
<br/>

```mermaid
flowchart LR
    Q([User question]) --> A[LLM agent]
    A -- search_tables --> C[(Oracle catalogue)]
    A -- get_columns --> C
    A -- run_sql --> D[(Live ERP data)]
    C --> A
    D --> A
    A --> R([Grounded answer])
```

- Searches the Oracle catalogue for relevant tables, fetches column schemas, then generates and executes SQL over bounded multi-round tool calls.
- Injects only relevant schema to stay within token limits, with enforced join paths and soft-delete filters.
- OpenAI-compatible tool definitions — runs on cloud models or locally on **Ollama**, keeping ERP data on-premise.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
</details>

<details>
<summary><b>📬 MailPilot AI — Executive Email Briefing Agent</b> &nbsp;<code>Production</code></summary>
<br/>

- Connects to the corporate mail server over IMAP and generates executive summaries, action items and draft replies.
- Multi-provider LLM layer fails over automatically across OpenRouter, OpenAI and Gemini, with a **15-worker parallel scheduler** for high-volume mailboxes.

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Llama](https://img.shields.io/badge/Llama_3.1-0467DF?style=flat-square&logo=meta&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
</details>

<details>
<summary><b>📦 Pre-Pack & Carton EDI Automation</b> &nbsp;<code>Production</code></summary>
<br/>

- Multi-tier parser converting EDI packing plans, carton stickers and UPC tickets into standard CARTON and UPC reports across six packaging classifications.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
</details>

<details>
<summary><b>🧑‍💼 AI Recruitment Automation Platform (BDJobs)</b> &nbsp;<code>R&D</code></summary>
<br/>

- Posts jobs from an Excel spec, auto-downloads applicant CVs and ranks candidates using a multi-model LLM ensemble.

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
</details>

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,pytorch,tensorflow,sklearn,opencv,docker,linux,nginx,githubactions,git,github,postgres,sqlite,aws,vscode&perline=8" alt="Tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
</p>

<details>
<summary><b>🔍 Full skill breakdown</b></summary>
<br/>

| Area | Skills |
|---|---|
| **Generative AI** | LLMs, RAG, Agentic AI, prompt engineering, structured output, tool calling, multi-model routing |
| **Computer Vision & OCR** | Vision-language models, OCR, PDF rasterisation, OpenCV, PyMuPDF, pdfplumber |
| **Machine Learning** | Classification, regression, ensemble & stacking models, XGBoost, cross-validation, model evaluation, EDA |
| **Deep Learning** | PyTorch, TensorFlow, Keras, transfer learning, fine-tuning |
| **Backend & Data** | FastAPI, Streamlit, REST APIs, Oracle, PostgreSQL, SQLite, Pydantic |
| **Automation** | Web scraping (BeautifulSoup, Requests), Playwright, RPA, scheduled pipelines |
| **DevOps** | Docker, Docker Compose, Podman, Nginx, GitHub Actions CI/CD, Linux |
| **Infrastructure** | Active Directory (ADDS), Group Policy, VLAN routing, server administration |

</details>

---

## 📚 Publications

| | Paper | Venue |
|---|---|---|
| 📄 | **ThyroStack: A Stacking Model for Thyroid Disease Prediction** | IEEE STI 2024 · [DOI: 10.1109/STI64222.2024.10951130](https://doi.org/10.1109/STI64222.2024.10951130) |
| 📄 | **A Stacking Ensemble Model for Thyroid Disease Prediction** | IEEE CS BDC Symposium 2024 |

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Hasebul47&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hasebul47&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Hasebul47&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Hasebul47&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" />
</p>

<!-- Snake animation: generated daily by .github/workflows/snake.yml -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hasebul47/Hasebul47/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Hasebul47/Hasebul47/output/github-snake.svg" />
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/Hasebul47/Hasebul47/output/github-snake.svg" />
  </picture>
</p>

---

## 🤝 Let's Connect

<p align="center">
  I'm open to <b>AI Engineer</b> roles and collaboration on applied AI, document intelligence and LLM systems.<br/>
  <a href="https://linkedin.com/in/hasebulislam">LinkedIn</a> ·
  <a href="mailto:hasebulislam47@gmail.com">Email</a> ·
  <a href="https://github.com/Hasebul47">GitHub</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer" width="100%" alt="footer" />
</p>
