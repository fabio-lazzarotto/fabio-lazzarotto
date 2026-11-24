# Fábio Lazzarotto

**Python Full Stack Developer | Process Automation and AI (LLMs, agents, RAG)**
São Paulo, Brazil · Open to remote roles

I build internal systems, automations and AI assistants that replace manual, spreadsheet-heavy work, and that people actually use every day. Over 5 years working between business areas and IT in renewable energy, technology and automotive companies, I learned to understand the process first and then write the code.

## Selected work

Most of my production work belongs to employers and clients, so the code is private. The case studies below describe the problem, the architecture and the result.

### Procurement management system
Full stack web system that manages the purchase requisition pipeline of a procurement team, from ERP approval to the purchase order. It replaced a set of macro-driven spreadsheets and became the team's standard daily tool.

- Imports ERP exports (Excel), applies the business rules and keeps the full history
- SLA in business days (with holidays), stage schedule, traffic-light status and deadline renegotiation workflow
- Dashboard with backlog, lead time, SLA adherence and ranking, plus Excel exports and scheduled HTML e-mail reports
- Role-based access, bcrypt passwords, session control, audit trail, structured logging and scheduled backups
- AI assistant built on an LLM API with tool use, able to read attached PDF, Excel and Word files, answering within each user's permissions
- Served in production with Waitress behind a reverse proxy
- About 23k lines of code, 77 routes and 353 automated tests

`Python` `Flask` `Jinja` `SQLite` `SQL` `pandas` `openpyxl` `XlsxWriter` `pypdf` `bcrypt` `Waitress` `LLM API` `unittest`

### Payment slip automation
Scheduled robot that checks when monthly payment slips are released, downloads them, consolidates the amounts in Excel, flags errors, organizes the folders and sends everything to the people responsible. It removed about 4 hours of manual work per day.

`Python` `requests` `pandas` `PDF` `SMTP` `Task Scheduler`

### AI prospecting agent
Agent built with Python and LLM APIs that researches companies by region, identifies decision makers and writes personalized outreach scripts. Prospecting moved to the agent and the SDR team moved to closing deals.

`Python` `LLM APIs` `RAG` `CRM integration` `WhatsApp`

### [Pontua](https://github.com/fabio-lazzarotto/pontua) (public)
Event platform where invitations, RSVPs and check-ins happen on WhatsApp, with points, a ranking and rewards for the most engaged members. Navigable prototype with fictional data.

`PostgreSQL` `n8n` `Docker Compose` `WhatsApp API` `JavaScript`

## What I work on

- **Full stack apps:** Flask back-ends, REST APIs, server-side templates, React and JavaScript front-ends for internal tools
- **Automation and RPA:** Python pipelines integrating ERPs, Excel, PDFs, web portals, e-mail and network folders, plus low-code flows in Power Automate and n8n
- **Applied AI:** assistants and agents with LLMs, tool use, RAG and MCP, cloud or local models, with control over what the AI can access
- **Data and BI:** SQL, dimensional modeling, pipelines and Power BI dashboards for leadership

## How I build

- Business rules in code, covered by automated tests
- Role-based access, password hashing, audit trails and structured logs from day one
- Scheduled jobs and automatic backups, so the process does not depend on one person
- AI with guardrails: the model only reaches data through functions that enforce each user's permissions

## Tech stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white) ![VBA](https://img.shields.io/badge/VBA-217346?style=for-the-badge&logoColor=white) ![Batch](https://img.shields.io/badge/Batch-4D4D4D?style=for-the-badge&logoColor=white)

**Back-end and front-end**  
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![Jinja](https://img.shields.io/badge/Jinja-B41717?style=for-the-badge&logo=jinja&logoColor=white) ![Werkzeug](https://img.shields.io/badge/Werkzeug-2C3E50?style=for-the-badge&logoColor=white) ![Waitress](https://img.shields.io/badge/Waitress-5A5A5A?style=for-the-badge&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST%20APIs-005571?style=for-the-badge&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**Python libraries**  
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![openpyxl](https://img.shields.io/badge/openpyxl-217346?style=for-the-badge&logoColor=white) ![XlsxWriter](https://img.shields.io/badge/XlsxWriter-217346?style=for-the-badge&logoColor=white) ![pypdf](https://img.shields.io/badge/pypdf-B30B00?style=for-the-badge&logoColor=white) ![requests](https://img.shields.io/badge/requests-2F6F9F?style=for-the-badge&logoColor=white) ![bcrypt](https://img.shields.io/badge/bcrypt-6D4C41?style=for-the-badge&logoColor=white) ![unittest](https://img.shields.io/badge/unittest-3776AB?style=for-the-badge&logoColor=white) ![logging](https://img.shields.io/badge/logging-3776AB?style=for-the-badge&logoColor=white)

**AI and LLMs**  
![LLM APIs](https://img.shields.io/badge/LLM%20APIs-412991?style=for-the-badge&logoColor=white) ![Tool use](https://img.shields.io/badge/Tool%20use-5A29E4?style=for-the-badge&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge&logoColor=white) ![AI Agents](https://img.shields.io/badge/AI%20Agents-0A66C2?style=for-the-badge&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-111111?style=for-the-badge&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) ![Copilot Studio](https://img.shields.io/badge/Copilot%20Studio-0078D4?style=for-the-badge&logoColor=white) ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Automation and RPA**  
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white) ![Power Apps](https://img.shields.io/badge/Power%20Apps-742774?style=for-the-badge&logo=powerapps&logoColor=white) ![SMTP e-mail](https://img.shields.io/badge/SMTP%20e--mail-2E7D32?style=for-the-badge&logoColor=white) ![Task Scheduler](https://img.shields.io/badge/Task%20Scheduler-0078D4?style=for-the-badge&logoColor=white)

**Data and BI**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logoColor=black) ![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=for-the-badge&logoColor=white) ![Dataverse](https://img.shields.io/badge/Dataverse-742774?style=for-the-badge&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white) ![Looker](https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=looker&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Cloud and DevOps**  
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logoColor=white) ![Azure Functions](https://img.shields.io/badge/Azure%20Functions-0062AD?style=for-the-badge&logo=azurefunctions&logoColor=white) ![Logic Apps](https://img.shields.io/badge/Logic%20Apps-0078D4?style=for-the-badge&logoColor=white) ![Microsoft Graph](https://img.shields.io/badge/Microsoft%20Graph-0078D4?style=for-the-badge&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**ERPs**  
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white) ![Protheus](https://img.shields.io/badge/Protheus-1A1A1A?style=for-the-badge&logoColor=white)

## Education

- Systems Analysis and Development, Grupo Anchieta (expected 2027)
- Production Engineering (final year)

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fabio-lazzarotto-ai)

Open to remote roles as a Python developer, AI engineer or automation engineer.
