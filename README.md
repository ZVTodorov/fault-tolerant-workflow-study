# Fault-Tolerant Workflow Design in Low-Code Automation Systems  
## A Comparative Study Using n8n

This repository contains the full implementation artefacts, workflow definitions, experimental datasets, and supporting materials for the dissertation project:

**Fault-Tolerant Workflow Design in Low-Code Automation Systems: A Comparative Study Using n8n**

The project investigates the impact of fault-tolerance mechanisms on workflow reliability and performance within a low-code automation environment using **n8n** as the experimental platform.

---

## Project Overview

Low-code workflow platforms are increasingly used for business process automation, API orchestration, and event-driven system integration.

This study evaluates how progressively enhanced fault-tolerance mechanisms affect workflow reliability under controlled HTTP response conditions.

Three workflow variants were implemented and experimentally evaluated:

- **Baseline workflow**
- **Failure-aware workflow**
- **Retry-enhanced workflow**

A total of **210 controlled workflow executions** were performed.

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

The workflows may be reproduced on any system capable of running Docker.
