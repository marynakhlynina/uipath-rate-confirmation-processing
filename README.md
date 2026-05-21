# AI-Powered Rate Confirmation Processing Automation

## Overview

An end-to-end UiPath automation designed to streamline logistics rate confirmation processing through AI-powered document extraction, mileage enrichment, validation logic, and structured spreadsheet reporting.

The workflow automates repetitive operational tasks while improving reporting efficiency, data consistency, and scalability.

---

## Business Context

Carrier operations teams process large volumes of broker rate confirmations daily. Manual handling of shipment documents, mileage lookup, and spreadsheet reporting created repetitive operational bottlenecks and limited scalability.

---

## Automation Solution

The automation workflow:
- Retrieves rate confirmations from email
- Stores documents in Google Drive
- Extracts shipment data using Document Understanding
- Calculates mileage using AI enrichment
- Validates extracted data quality
- Generates structured spreadsheet output
- Sends alerts for incomplete or low-confidence data

---

## Technologies Used

- UiPath
- Document Understanding
- Generative Extractor
- AI / LLM Integration
- Google Drive
- Google Sheets
- Validation Logic
- Logging & Monitoring

---

## Key Outcomes

- ~70–80% reduction in manual processing
- Automated handling of dozens of confirmations
- Faster RPM reporting
- Improved operational visibility
- Reduced repetitive data entry

---

## Workflow Architecture

![Workflow Architecture](assets/workflow-architecture.png)

---

## Document Understanding Pipeline

![DU Pipeline](assets/document-understanding-pipeline.png)

---

## Custom Extraction Fields

![Custom Extraction](assets/custom-extraction-fields.png)

---

## AI-Based Mileage Enrichment

![AI Mileage](assets/ai-based-mileage-enrichment.png)

---

## Data Quality Validation

![Validation Logic](assets/data-quality-validation-logic.png)

---

## Validation & Monitoring

![Monitoring Logs](assets/validation-monitoring-logs.png)

---

## Structured Spreadsheet Output

![Spreadsheet Output](assets/structured-spreadsheet-output.png)

---

## Documentation

Additional project documentation is available in the `/docs` folder.