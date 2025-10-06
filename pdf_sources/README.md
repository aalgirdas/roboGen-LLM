# 📁 pdf_sources

This directory contains **original PDF documents** used as source material for automated data extraction, analysis, and CAD reconstruction.

Each PDF in this folder serves as an input for the LLM-based extraction pipeline located in [`../llm_structured_outputs/`](../llm_structured_outputs/), which produces structured JSON files describing robot geometry, mass properties, and construction details.

---

## 📘 Contents

| File | Description | Source / Notes |
|------|--------------|----------------|
| `Pioneer3AT-P3AT-RevA-datasheet.pdf` | Official Adept Pioneer 3-AT mobile robot datasheet | Used for physical specs extraction |


---

## 📂 Folder Purpose

- Serve as **ground-truth reference** for extracted structured data  
- Maintain version control of official **datasheets and manuals**  
- Enable **reproducible LLM or OCR extractions**  
- Support **CAD and simulation model reconstruction**

---

