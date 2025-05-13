# Talent Atmos
This project aims to develop a public database for youth empowering, business, and social
 activities through the web application ”Talents Atmos,” which collects information about
 events, job opportunities, and youth organization data in one place. The platform addresses
 the problem of scattered information and difficult access.
 
## Deployment
This project's deployment is divided into five main parts:
- Frontend Website (Containerized)
- Admin Console Site 
- Backend Service (Containerized)
- Kafaka Consumer CDC (Containerized)
- Recommendation Service (Containerized)
<br />
You can go and see the docker compose file in the Docker-Compose-File's repository to deploy this project.

## Talent Atmos Frontend
The official frontend repository for Talent Atmos Frontend <br />
In the project's repository it contains Dockerfile for building the docker image and it needs environment variables show in .env.example for deployment
### __Technology Stack__
- Framework: Nextjs
- Language: TypeScript
- Styling: Tailwind CSS
- Continuous Integration: GitHub Action
- Continuous Delivery: Netlify

## Talent Atmos Admin
The official frontend repository for Talent Atmos Admin <br />
It needs environment variables show in .env.example for deployment
### __Technology Stack__
- Framework: Nextjs
- Language: TypeScript
- UI Components: Shadcn
- Styling: Tailwind CSS
- Continuous Integration: GitHub Action
- Continuous Delivery: Netlify

## Talent Atmos Backend
The official backend repository for Talent Atmos Backend <br />
In the project's repository it contains Dockerfile for building the docker image and it needs environment variables show in .env.example for deployment
### __Technology Stack__
- Framework: GO Fiber
- Language: GO
- Database: PostgreSQL & Opensearch & AWS S3
- Authentication: JWT & Google OAuth
- API Document: Swagger
- Searching: Opensearch
- RBAC: Casbin
- Continuous Integration: GitHub Action
- Continuous Delivery: Jenkins

## Kafka-Consumer-CDC
The repository for consumer that will process the data change from PostgreSQL to Opensearch/Elasticsearch <br />
In the project's repository it contains Dockerfile for building the docker image and it needs environment variables show in .env.example for deployment
### __Technology Stack__
- Language: GO
- Message Queue: Apache Kafka
- Database: PostgreSQL & Opensearch
- CDC connector: Debezium
- Continuous Integration: GitHub Action

## Talent Atmos Rec
The repository for ML model that will be used for inferencing (Recommendation Service).
### __Technology Stack__
- Framework: FastAPI & Pytorch
- Language: Python
- Database: PostgreSQL
- Continuous Integration: GitHub Action
- Continuous Delivery: Jenkins

<!--
**Here are some ideas to get you started:**
---
### Link
- Talent Atmos Frontend: You can visit our site via this link: [Talent-Atmos-Frontend](https://talent-atmos.netlify.app)
- Talent Atmos Admin Console: You can visit the admin console site via this link: [Talent-Atmos-Admin](https://ta-mgmt-cons.netlify.app)
<br />
Talent Atmos is dedicated to empowering youth through development events.

🙋‍♀️ A short introduction - We are Talent Atmos, we strive to be a centric of youth development events platform.
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
