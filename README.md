# An Empirical Evaluation of Fault-Tolerance Mechanisms in Low-Code Workflow Automation Systems  
## A Case Study Using n8n

This repository contains the full implementation artefacts, workflow definitions, experimental datasets, and supporting materials for the dissertation project:

**An Empirical Evaluation of Fault-Tolerance Mechanisms in Low-Code Workflow Automation Systems: A Case Study Using n8n**

The project investigates the impact of fault-tolerance mechanisms on workflow reliability and performance within a low-code automation environment using **n8n** as the experimental platform.

---

## Research Objective

The primary aim of this study is:

> To evaluate the impact of fault-tolerance mechanisms on workflow reliability and execution performance in a low-code automation environment.

The project specifically investigates:

- successful execution rate
- failure rate
- recovery rate
- retry effectiveness
- execution latency overhead

---

## Experimental Environment

The original implementation was developed on a **self-hosted Debian Linux environment** running on:

- **CPU:** Intel(R) Celeron(R) N5105
- **OS:** Debian Linux
- **Containerization:** Docker / Portainer
- **Workflow Engine:** n8n
- **HTTP Simulation:** httpbin
- **Logging:** Notion

---

## Running the Project

1. Clone the repository
2. Navigate to project root folder
3. Modify .env file to your liking
4. Initiate services via "docker compose up -d"
5. Manually import the workflows from the workflow folder into n8n
5. Import Notion api key via the graphical interface for logging
6. Create a Notion database page following the provided schema
7. Start workflows

- **n8n:** `http://localhost:5678'
- **httpbin** 'http://localhost:8082'