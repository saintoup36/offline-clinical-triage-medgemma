# Offline Clinical Triage Assistant using MedGemma

This repository contains the code and documentation for an offline clinical triage
and summarization assistant built using **MedGemma**, an open-weight model from the
**HAI-DEF** collection.

The project demonstrates how healthcare-oriented foundation models can be adapted
for local, privacy-preserving clinical decision support without reliance on cloud
services or external APIs.

---

## Overview

Clinical environments often require rapid, structured decision support, yet many
settings cannot depend on cloud-based AI due to privacy constraints or limited
connectivity. This project addresses that gap by demonstrating a fully offline
assistant designed for clinical triage and summarization tasks.

The system is intended strictly for **decision support** and does **not replace
clinical judgment**.

---

## Repository Contents

- `run_inference.py` — Entry point for offline inference
- `prompts/` — Prompt templates used to guide structured model output
- `examples/` — Synthetic sample clinical inputs
- `requirements.txt` — Python dependencies required to run the system

---

## Setup

```bash
pip install -r requirements.txt

python run_inference.py --input examples/sample_case.txt
