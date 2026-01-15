# Healthcare Documentation QA System (AI-Assisted)

This project reviews physical therapy SOAP notes using a structured checklist
and outputs standardized quality feedback in Excel format.

## What it does
- Converts PT notes into structured review prompts
- Evaluates documentation completeness and quality
- Produces consulting-ready Excel reports
- No API key required (manual AI workflow)

## Outputs
- reviewed_notes_clean.xlsx
- reviewed_notes_scored.xlsx

## Why This Project Exist 

Clinical documentation is a well-documented operational burden in rehabilitation settings. Outpatient rehabilitation therapists report documentation demands comparable to those of physicians and nurses, with manual data entry significantly reducing time available for patient care (Schwartz-Dillard et al., 2024/2025). The American Physical Therapy Association has further noted that administrative documentation requirements negatively impact patient care and contribute to clinician burnout, with many practices hiring additional staff solely to manage documentation workloads (American Physical Therapy Association, 2019; 2025).

This project explores how AI-assisted, decision-support workflows can improve SOAP note completeness, consistency, and clarity by providing structured feedback and early identification of documentation gaps—while preserving clinician oversight and clinical judgment. The goal is to support documentation quality and workflow efficiency without replacing clinical reasoning.

## Workflow Overview 
- Ingests raw clinical notes (CSV / Excel)
- Converts notes into structured review prompts
- Uses AI (manual-in-the-loop) to evaluate documentation quality
- Outputs standardized QA feedback and scores to Excel
- Designed for consulting, QA, and clinical review use cases

## Why Manual AI
The system is intentionally designed with a human-in-the-loop AI workflow to ensure clinical judgment, reduce hallucination risk, and maintain compliance in healthcare settings.

## Intended Users
- Physical therapy clinic owners
- Rehabilitation directors and managers
- Documentation and compliance teams
- Sports performance and outpatient rehab practices

## Use case
Designed for healthcare QA, documentation review, and AI health consulting workflows.


## Status
V1 – Manual prompt-based review (stable)
