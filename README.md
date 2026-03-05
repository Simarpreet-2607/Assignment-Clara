# Assignment-Clara 
### Zero-Cost Automation Pipeline for Retell Agent Generation

This project implements a fully automated, zero-cost pipeline that processes demo call transcripts to generate preliminary Retell agent configurations and then updates those configurations based on onboarding inputs.

The system extracts structured business information from transcripts, generates an agent prompt specification, and maintains versioned updates (v1 → v2) while tracking changes.

---

# Project Overview

The goal of this project is to demonstrate automation design, data extraction, prompt generation, and version-controlled agent configuration updates using only free-tier tools.

The pipeline performs two main workflows:

Pipeline A:  
Demo Call → Structured Account Memo → Retell Agent Draft (v1)

Pipeline B:  
Onboarding Input → Updated Account Memo → Updated Agent Draft (v2) + Changelog

The system runs on a dataset of demo calls and onboarding calls and generates outputs per account.

---

