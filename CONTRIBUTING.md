# Contributing to the ATS Framework

Thank you for your interest in improving the Authorship Transparency Statement (ATS) protocol. As generative AI continues to evolve, this framework requires community input to remain technically rigorous and practically useful for creators and institutions.

## 🛠 Areas of Contribution

We welcome contributions in the following categories:

1. **Modality Interpretations:** Proposing specific "Deep-Dive" interpretations for emerging creative fields (e.g., Spatial Computing, Fashion Design, or Architecture) to be added to Appendix C.
2. **Official Rulings (Edge Cases):** Identifying "grey areas" in AI usage and proposing clear rulings to be added to Appendix E.
3. **Technical Schemas:** Improving the JSON and JSON-LD schemas in the `/schemas` directory for better interoperability with library systems and provenance standards like C2PA.
4. **Documentation & LaTeX:** Fixing typos or improving the clarity of the prose in the primary technical standard located in the `/latex` directory.

---

## 🚦 The RFC (Request for Comments) Process

To ensure the framework remains stable and consistent with the "Bright Line" principle, all substantive changes follow a formal process:

### 1. Open an Issue
Before submitting a Pull Request, please open a GitHub Issue using the **Proposal** template. Describe the change, the reasoning behind it, and how it aligns with the existing ATS logic.

### 2. Community Discussion
The proposal will be open for community feedback. We aim for a 30-day discussion period for major changes to allow for diverse perspectives from authors, developers, and legal experts.

### 3. Steward Review
The protocol stewards (Meaningfulness Media Group) will review the consensus. Proposals that contradict the "Bright Line" or "Unit of Generation" principles will generally be rejected to prevent framework fragmentation.

### 4. Pull Request (PR)
Once a proposal is approved in concept, you may submit a PR. 
*   Edits to the technical standard MUST be made to the `.tex` files in the `/latex` directory.
*   Changes to the machine-readable protocol MUST be reflected in the `/schemas` directory.

---

## 📜 Submission Guidelines

### Labels
Please use the following labels for your issues:
*   `proposal`: For new modalities or tier refinements.
*   `edge-case`: For Appendix E additions.
*   `bug`: For errors in LaTeX formatting or JSON syntax.
*   `documentation`: For non-substantive text improvements.

### Pull Request Requirements
*   **Atomic Changes:** Keep PRs focused on a single issue or modality.
*   **Version Consistency:** Substantive changes will be bundled into **Minor Versions** (v1.x). Do not update the version number in your PR; stewards will handle versioning during the release cycle.

---

## ⚖️ License

By contributing to this repository, you agree that your contributions will be licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

---

**Contact:** For sensitive inquiries or institutional partnership proposals, please email: info@meaningfulness.com.au