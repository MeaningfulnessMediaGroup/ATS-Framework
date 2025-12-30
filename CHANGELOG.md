# Changelog

All notable changes to the **Authorship Transparency Statement (ATS) Framework** will be documented in this file. This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] - 2026-01-01

### Added
- **Foundational Principle:** Introduced the "Bright Line of Prose Origin" as the mechanical threshold for AI disclosure.
- **The Tiers:** Defined the 6-tier hierarchy (ATS-0 to ATS-5) based on the gradient of AI autonomy.
- **ATS-1T Modifier:** Introduced the "Transformative Rendering" carve-out to handle 1:1 machine translation of human-authored text.
- **The E-Scale (Extent):** Added the Extent Axis (E0–E4) to disclose the volume of AI involvement per work.
- **Multi-modal Interpretations:** Added specific guidelines (Appendix C) for:
    - Research (`ats_level_research`)
    - Visual Arts (`ats_level_image`)
    - Audio and Music (`ats_level_audio`)
    - Video and Moving Image (`ats_level_video`)
    - 3D and Spatial Design (`ats_level_data`)
    - Software Development (`ats_level_code`)
    - Structured Data Assets (`ats_level_data`)
- **Metadata Schemas:** Released the Minimal JSON and Extended JSON-LD (Schema.org compatible) specifications.
- **JSON Schema:** Provided `ats-v1.0.schema.json` for programmatic validation of metadata.
- **Institutional Tools:** Added the Institutional Intake Template and pseudo-code for automated triage/routing.
- **Edge Case Rulings:** Introduced Appendix E to provide official rulings on Grammarly, dictation, autocomplete, and "found footage."
- **Conformance Language:** Integrated RFC 2119 (MUST/SHOULD/MAY) to formalize compliance requirements.

### Changed
- **Logic Hardening:** Refined the boundary between ATS-2 and ATS-3 to be strictly defined by the "Unit of Generation" (Local fragments vs. Structural units).
- **Redundancy Reduction:** Streamlined the main-body tier definitions to focus on normative rules, moving descriptive analogies to Appendix A.
- **Glossary Expansion:** Significantly expanded the Glossary of Terms to define critical technical and ethical concepts (HITL, Token Sequence, De Minimis, etc.).

---

## [0.9.0] - 2025-10-27
### Added
- Initial internal draft and standardization proposal (pre-Zenodo).
- Conceptual definitions for "Augmented" vs. "Co-Creative" workflows.
- Basic JSON header structure.

---

## Note on Versioning
- **Major Versions (1.0, 2.0):** Indicate fundamental logic shifts or changes to the Bright Line.
- **Minor Versions (1.1, 1.2):** Indicate new modalities, refined metadata fields, or additional edge-case rulings.
- **Patch Releases (1.0.1):** Typo fixes and non-substantive documentation improvements.