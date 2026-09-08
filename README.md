<h1 align="center">Murat Kubekov</h1>

<p align="center">
  <b>Test Automation Engineer / SDET</b> &nbsp;·&nbsp; Python &nbsp;·&nbsp; 5+ years in QA
</p>

<p align="center">
  <a href="https://t.me/aqapro"><img src="https://img.shields.io/badge/Telegram-%40aqapro-26A5E4?style=flat&logo=telegram&logoColor=white" alt="Telegram @aqapro"></a>
  <a href="mailto:mkubekov@gmail.com"><img src="https://img.shields.io/badge/Email-mkubekov%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Remote-UTC%2B7-555555?style=flat" alt="Remote, UTC+7">
  <img src="https://img.shields.io/badge/Open%20to-remote%20roles-2EA043?style=flat" alt="Open to remote roles">
</p>

## About

- I build test automation from scratch and take it to production grade: frameworks, CI/CD, contract and load testing, quality gates.
- Currently at **Napoleon IT** I own quality for a big-data platform: validation of calculation logic over **90+ billion rows in PostgreSQL**, Kafka ingest, and Locust load tests orchestrated as Kubernetes jobs.
- Before that, at **Maximum Education**, I wrote **600+ UI and API tests** (pytest + Playwright) that cut a full regression from **3 days to 1** and brought automation to three products.
- I like growing people: mentored **5 junior QA engineers** into automation engineers and ran 10+ internal workshops on autotests, GitLab CI and Allure TestOps.

## Featured project

| Project | What it is | Stack |
|---|---|---|
| [**performance_tests**](https://github.com/Clorhexidinum/performance_tests) [![CI](https://github.com/mkubekov/performance_tests/actions/workflows/ci.yml/badge.svg)](https://github.com/mkubekov/performance_tests/actions/workflows/ci.yml) | Load-testing template on Locust for **HTTP, gRPC and Kafka**: typed clients that report every request the same way, reusable load profiles (constant RPS, ramp, spike, step), mocks, Docker Compose with Kafka, Prometheus and Grafana, GitLab CI and GitHub Actions, 50+ unit tests. | Python 3.12 · Locust · httpx · grpcio / protobuf · confluent-kafka · pydantic · Docker · Grafana |

Earlier repositories ([qa_guru_oop](https://github.com/mkubekov/qa_guru_oop), [qa_guru_mobile](https://github.com/mkubekov/qa_guru_mobile)) are 2023 course work on Selene, Appium, Selenoid, Jenkins and Allure; they are being refreshed.

## Tech stack

| Area | Tools |
|---|---|
| **Languages & test frameworks** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![pytest-xdist](https://img.shields.io/badge/pytest--xdist-0A9EDC?style=flat) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white) ![Selene](https://img.shields.io/badge/Selene-43B02A?style=flat) ![Appium](https://img.shields.io/badge/Appium-662D91?style=flat&logo=appium&logoColor=white) |
| **API, data & messaging** | ![httpx](https://img.shields.io/badge/httpx-000000?style=flat) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white) ![REST](https://img.shields.io/badge/REST%20API-005571?style=flat) ![Swagger](https://img.shields.io/badge/Swagger%20%2F%20OpenAPI-85EA2D?style=flat&logo=swagger&logoColor=black) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white) |
| **Performance** | ![Locust](https://img.shields.io/badge/Locust-1BAA4A?style=flat) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) |
| **CI/CD & infrastructure** | ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat&logo=gitlab&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Selenoid / Moon](https://img.shields.io/badge/Selenoid%20%2F%20Moon-555555?style=flat) ![ruff](https://img.shields.io/badge/ruff-D7FF64?style=flat&logo=ruff&logoColor=black) ![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?style=flat&logo=precommit&logoColor=black) |
| **Reporting & test management** | ![Allure Report](https://img.shields.io/badge/Allure%20Report-9C27B0?style=flat) ![Allure TestOps](https://img.shields.io/badge/Allure%20TestOps-9C27B0?style=flat) ![Zephyr Scale](https://img.shields.io/badge/Zephyr%20Scale-0052CC?style=flat&logo=jira&logoColor=white) ![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat&logo=kibana&logoColor=white) |

## Experience

| Period | Company | Role | Highlights |
|---|---|---|---|
| Dec 2025 – present | **Napoleon IT** · digital products and AI solutions for enterprise · remote | Test Automation Engineer | Designed the automation framework for a highload system with 90+ billion rows in PostgreSQL; modular checkers for calculation formulas with batch verification and detailed Allure reports; connection pooling, batching, session reuse and pytest-xdist to keep the suite fast; GitLab CI pipeline with Allure reports on GitLab Pages and Zephyr Scale integration; Locust load tests for the Kafka-to-PostgreSQL ingest path, run as Kubernetes jobs. |
| May 2022 – Dec 2025 | **Maximum Education** · EdTech · remote | Test Automation Engineer | 600+ UI and API tests on pytest + Playwright; full regression down from 3 days to 1 through parallelisation and prioritised runs; automation coverage up to 70%; automation rolled out to LMS, CRM and the web platform with Moon, GitLab CI and Allure TestOps; 10+ workshops that grew the automation team to 6; testing of an AI support chatbot (dialogue scenarios, business rules, integrations). |
| Apr 2020 – May 2022 | **Mentorama** · EdTech · remote | QA Engineer (manual + automation) | Post-release defects down 30% after introducing static testing; CRM migration and the Vue-to-Nuxt frontend switch shipped without regressions; structured test documentation (cases, checklists, plans) that cut QA onboarding time by 30%; Selene, pytest, Selenoid, Allure, GitLab CI. |

## Education & courses

- **Moscow Pedagogical State University**, Faculty of Pedagogy and Psychology, 2008–2011
- **Yandex Practicum**, QA Engineer programme
- **qa.guru**, test automation in Python

## Contact

Open to remote Test Automation / SDET roles (B2B contracts welcome).
Telegram [@aqapro](https://t.me/aqapro) · [mkubekov@gmail.com](mailto:mkubekov@gmail.com)
