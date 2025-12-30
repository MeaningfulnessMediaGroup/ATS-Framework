# Authorship Transparency Statement (ATS) Framework v1.0

![Zenodo DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.placeholder-blue)
![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)
![Protocol Status](https://img.shields.io/badge/Status-Public%20Standardization%20Proposal-green)

**Protocol ID:** `ATS-FRAMEWORK-1.0`  
**Latest Version:** v1.0 (Released January 2026)  
**Stewards:** Meaningfulness Media Group

---

## 📌 Overview

The **Authorship Transparency Statement (ATS)** is a technical protocol designed to replace the primitive binary question *"Did you use AI?"* with a nuanced, multi-tiered lexicon for creative synthesis. 

As generative AI matures, the line between augmentation and generation has blurred. The ATS Framework provides the "paperwork of becoming"—an objective, mechanical method for creators to disclose their methodology and for institutions to make informed assessments regarding authorship, copyright, and creative integrity.

### The "Bright Line" Principle
The entire framework is anchored on the **origin of the first complete draft of prose** (or modality equivalent). 
* **Reactive Use (ATS-1):** AI reacts to, analyzes, or refines human-authored content.
* **Generative Use (ATS-2+):** AI generates the initial "first-pass" token sequences based on human prompts.

---

## 📊 The ATS Tiers (0–5)

| Tier | Name | Human Role | Key Definition |
| :--- | :--- | :--- | :--- |
| **ATS-0** | **Unaugmented** | Traditional Artisan | No generative functions used. |
| **ATS-1** | **Augmented** | Architect | AI used for refinement, analysis, or research. |
| **ATS-1T** | **Transformative** | Translator | AI used only for 1:1 translation of human source text. |
| **ATS-2** | **Co-Creative** | Producer | AI drafts local fragments (sentences/paragraphs). |
| **ATS-3** | **Directed** | Director | AI drafts structural units (scenes/chapters) from outlines. |
| **ATS-4** | **Agent-Driven** | Systems Architect | Custom AI agent executes a high-level creative brief. |
| **ATS-5** | **Conceptual** | Patron | AI generates plot, characters, and prose from high-level concepts. |

---

## 🚀 Quick Start for Creators

To disclose your work, follow the **ATS Decision Matrix**:

1. **Did any final-use prose begin as AI drafts?**  
   * No $\rightarrow$ **ATS-0/1**
   * Yes $\rightarrow$ **Go to 2**
2. **Was the generation based on a detailed structural outline?**  
   * No $\rightarrow$ **ATS-5**
   * Yes $\rightarrow$ **Go to 3**
3. **Was AI use confined to local prompts (sentence/paragraph)?**  
   * Yes $\rightarrow$ **ATS-2**
   * No $\rightarrow$ **Go to 4**
4. **Was generation executed via autonomous agentic system(s)?**  
   * Yes $\rightarrow$ **ATS-4**
   * No $\rightarrow$ **ATS-3**

**Example Disclosure:** `Text ATS-2 [E1]; Research ATS-1 [E2]`

---

## 💻 Developer Implementation

The ATS Framework is designed to be machine-readable and interoperable with standards like **C2PA**.

### Repository Structure
```text
/
├── latex/
│   ├── main.tex             # LaTeX source of the technical standard
│   └── references.bib       # Bibliography
├── schemas/
│   ├── minimal-v1.0.json    # Minimal metadata schema
│   ├── extended-v1.0.jsonld # JSON-LD full audit schema
│   └── ats-v1.0.schema.json # JSON Schema for programmatic validation
├── templates/
│   └── intake-template.csv  # Publisher intake form template
├── CHANGELOG.md             # Version history
├── CONTRIBUTING.md          # Contribution guidelines
├── LICENSE                  # CC-BY-4.0
└── README.md                # This landing page
```

### Metadata Schemas
The `/schemas` directory contains raw JSON and JSON-LD templates for embedding ATS data into digital files:
* [Minimal JSON Header](./schemas/minimal-v1.0.json) - For XMP and file properties.
* [Extended JSON-LD](./schemas/extended-v1.0.jsonld) - For institutional archives and full audit trails.

---

## 🤝 Contributing & Evolution

Standardization is a collaborative process. We welcome input from creators, publishers, and developers to refine v1.1 and beyond.

### How to Contribute:
*   **Propose New Modalities:** Have a specific workflow (e.g., VR, Spatial Computing, or Fashion Design) not yet covered? Help us draft the modality-specific interpretation.
*   **Submit Edge Cases:** Found a "grey area" or a scenario that challenges the current logic? Open an issue to propose a new **Official Ruling**.
*   **Improve Metadata:** Help us refine the JSON-LD schemas for better integration with existing library and database systems.

### The RFC Process:
1.  **Open an Issue:** Use the "Proposal" tag to suggest a change.
2.  **Discussion:** The community and stewards will review the proposal for logical consistency with the "Bright Line" principle.
3.  **Pull Request:** Once consensus is reached, submit a PR to update the `/latex` source files or `/schemas`.

---

## 📜 Citation

If you utilize this framework in your research or platform, please cite it as follows:

> Bee, D. (2026). *Authorship Transparency Statement (ATS) Framework v1.0: A Technical Standard for the Multi-Tiered Disclosure of Generative AI in Creative Works*. Meaningfulness Media Group. Protocol ID: ATS-FRAMEWORK-1.0. [Zenodo DOI Link]

---

**License:** This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
