# Telemetry Data Integration & Real-Time Dashboard Simulation

This repository contains my completed submissions for the **Technology Job Simulation** — a real-world engineering simulation hosted by *Deloitte Australia*.

I built solutions for real industrial data challenges, including unifying heterogeneous telemetry formats and drafting a development proposal for a real-time manufacturing dashboard.

---

## Completion Certificate

I completed the simulation and earned this certificate:

👉 [Deloitte_Australia_Technology_Job_Simulation_Certificate_Shreeja_Hebbar.pdf](https://www.theforage.com/completion-certificates/9PBTqmSxAf6zZTseP/udmxiyHeqYQLkTPvf_9PBTqmSxAf6zZTseP_69a1bc8dde4e0a7538878d3f_1772383844442_completion_certificate.pdf)

---

## Project Overview

Modern manufacturing systems generate high volumes of machine telemetry across distributed facilities. This project demonstrates:

* Data consolidation of heterogeneous telemetry models
* Real-time system design thinking
* Backend data transformation logic
* Formal proposal writing for engineering solutions

The simulation was completed as part of a virtual job experience aimed at improving practical engineering skills relevant to industry environments.

---

## Skills Practiced

| Category             | Skills                                              |
| -------------------- | --------------------------------------------------- |
| Engineering          | Data Modeling, Backend Logic, System Design         |
| Programming          | Python, JSON Handling, Unit Testing                 |
| Software Development | Modular Architecture, Test-Driven Validation        |
| Professional         | Proposal Writing, Project Estimation, Documentation |

---

## Repository Structure

```plaintext
technology-job-simulation/
│
├── task-1-data-model-unification/
│   ├── main.py
│   ├── data-1.json
│   ├── data-2.json
│   ├── data-result.json
│
├── task-2-proposal/
│   ├── Software Development Proposal.pdf
│   ├── Model Submission.pdf
│
└── README.md
```

---

## Task 1 – Data Model Unification

### Objective

Design an algorithm to unify two different telemetry JSON formats into a single standardized output schema.

### Description

Industrial IoT devices at Daikibo report machine status in two heterogeneous JSON formats. The program reads both formats and produces a consistent schema with:

* Normalized device metadata
* Nested location breakdown
* Timestamp normalization to epoch milliseconds
* Device operational status and temperature

### Implementation

The code was implemented in Python using modular functions:

* `convertFromFormat1()`
* `convertFromFormat2()`
* `main()` routes input to correct converter

Automated unit tests validate correctness across both formats.

### Replit Submission

The working solution is publicly available here:

👉 [Telemetry Data Integration](https://replit.com/@hebbarshree855/technology-job-simulation)

---

## Task 2 – Development Proposal

### Objective

Draft a formal software development proposal for a *private, real-time manufacturing health dashboard* showing the operational status of machines across Daikibo’s four factories.

### Summary

The proposal includes:

1) Project overview
2) Scope of work and features
3) Security requirements (intranet + authentication)
4) Man-hour estimates
5) Milestones and timeline
6) Post-deployment support plan

The proposal was authored using the official simulation template and included realistic estimates and architecture planning.

(See `Software Development Proposal.pdf` in this repo.)

---

## Architecture Overview

The solution design (for the proposed dashboard) includes:

### 🔹 Data Ingestion Layer

Real-time telemetry streaming from IIoT devices using APIs or streaming protocols.

### 🔹 Processing Layer

Backend service to validate, normalize, and process incoming telemetry.

### 🔹 Storage Layer

Time-series or relational database for historical status data.

### 🔹 Backend API

Python backend (e.g., FastAPI) exposing data to the frontend.

### 🔹 Frontend Dashboard

Single-page interface with collapsible views for factories and devices.

### 🔹 Alerting

Smart alerts on status changes or anomalies.

---

## What I Learned

This simulation helped me develop:

* Practical skills in data normalization and transformation
* Real-world engineering thinking
* Architecture design and proposal writing
* Effective communication of technical solutions

---

## What’s Next

Potential future expansions include:

1) Predictive analytics for machine failures
2) Historical reporting and dashboards
3) User roles and granular access control
4) Mobile or cross-platform UI

---

## Acknowledgements

Completed as part of the Deloitte Australia Technology Virtual Job Simulation — designed to bridge academic learning with industry practice.
