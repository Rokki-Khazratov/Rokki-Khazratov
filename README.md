# Shamshodbek Khazratov — Python Backend Engineer

I build business systems where the backend has to reflect real operations: permissions, deadlines, documents, audit trails, background jobs, reporting, and decision-making. Based in Vienna; studying Statistics and Data Analytics at the University of Vienna; available for a working-student role (20–30 hours/week), starting immediately.

## Featured projects

### [ExamTwin — adaptive exam-preparation platform](https://github.com/Rokki-Khazratov/portfolio-case-studies/tree/main/examtwin)

An exam simulation product designed to turn preparation into a measurable feedback loop. A student selects a subject and context, configures a mock exam, completes a focused session, then receives review and analytics.

- **Product flow:** subject and context → exam configuration → timed attempt → answers and review → performance analytics
- **Backend focus:** FastAPI APIs, PostgreSQL with `pgvector`, Redis, Dramatiq workers, and object storage for asynchronous artifact generation
- **AI boundary:** optional grounded evaluation using curated materials; the core exam flow remains usable without the AI component
- **Why it matters:** makes weak areas visible through structured practice rather than only showing a final score

### [Tender ERP — tender operations and workflow system](https://github.com/Rokki-Khazratov/portfolio-case-studies/tree/main/tender-erp)

A role-aware ERP case study for teams running tenders with clients, suppliers, finance, documents, deadlines, and approvals in one operational workflow.

- **Business problem:** tender work becomes unreliable when ownership, documents, calculations, and deadlines live across spreadsheets and chats
- **System design:** React + TypeScript client, Django REST API, relational domain model, RBAC, audit events, Celery background work, notification boundary, and reporting layer
- **Operational capabilities:** deal and stakeholder records, task/deadline tracking, document handling, financial context, permission-scoped views, and traceable changes
- **Engineering principle:** the public repository contains a safe presentation of the architecture and product decisions; sensitive source and business data are intentionally excluded

### [MenuMargin AI — restaurant margin decision support](https://github.com/Rokki-Khazratov/portfolio-case-studies/tree/main/menumargin-ai)

A decision-support prototype for restaurant operators: forecast cost pressure, test a menu-price scenario, and see the potential impact on gross margin before making a change.

- **Product flow:** capture menu economics → obtain forecast/context inputs → run a price scenario → compare baseline and proposed margin
- **System design:** Next.js dashboard, FastAPI decision service, scenario layer, forecast-service boundary, and external economic-cost context
- **Decision output:** transparent assumptions and scenario comparison rather than a black-box recommendation
- **Scope note:** this is a demo/prototype using illustrative data; it is not production financial advice

## Portfolio case studies

Every case study is written as a technical product brief: business context, core workflows, system design, stack choices, and an editable Excalidraw architecture diagram.

→ [Open all project case studies](https://github.com/Rokki-Khazratov/portfolio-case-studies)

## Engineering focus

`Python` · `Django REST Framework` · `FastAPI` · `PostgreSQL` · `Redis` · `Celery` · `Docker` · `REST APIs` · `RBAC` · `React` · `Next.js` · `TypeScript`

I am especially interested in backend roles where a clear domain model and reliable workflow automation materially improve how a team operates.

## Contact

- LinkedIn: [bek-khazratov](https://www.linkedin.com/in/bek-khazratov-751954225/)
- Portfolio: [Rokki-Khazratov/portfolio-case-studies](https://github.com/Rokki-Khazratov/portfolio-case-studies)
