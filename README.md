# 🤖 roboGen-LLM

**roboGen-LLM** is an experimental framework for **LLM-driven generation of robot models** from technical documentation.  
It automatically extracts geometric, mass, and material data from PDFs, and generates models for simulators like **Webots**, **MuJoCo**, and **URDF/RDF** formats.

---

## 🚀 Features

- 🧩 **Automated Information Extraction** — Parses robot documentation PDFs to extract dimensions, mass, color, and material data.
- 🧠 **LLM-Powered Reasoning** — Uses large language models to interpret unstructured technical text and diagrams.
- ⚙️ **Multi-Simulator Support** — Exports models for Webots (`.wbt`), MuJoCo (`.xml`), and RDF/URDF.
- 🧱 **CAD Engineer Guidance** — Generates human-readable CAD assembly instructions.
- 💬 **Prompt Library** — Modular prompts for different tasks: extraction, simulation, CAD generation.

---

## 🗂️ Repository Structure

roboGen-LLM/
├── data/          # Raw PDFs, extracted JSON, images
├── prompts/       # Prompt templates for different LLM tasks
├── src/           # Core Python scripts and generators
├── notebooks/     # Interactive examples and experiments
├── tests/         # Unit tests for parsing and generation
└── docs/          # Documentation and design notes
