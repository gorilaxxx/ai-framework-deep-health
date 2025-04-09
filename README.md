# AI Framework: Deep Health Diagnosis Framework (DHDF)

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)
[![Integrity](https://img.shields.io/badge/integrity-sha256-blue)](./version.json)
![Last Commit](https://img.shields.io/github/last-commit/gorilaxxx/ai-framework-deep-health)
![Contributors](https://img.shields.io/github/contributors/gorilaxxx/ai-framework-deep-health)
![Issues](https://img.shields.io/github/issues/gorilaxxx/ai-framework-deep-health)
![Stars](https://img.shields.io/github/stars/gorilaxxx/ai-framework-deep-health)

**Version:** v1.0<br>
**Status:** Stable (v1.0)<br>
**Repository:** `ai-framework-deep-health`<br>
**Author:** [@gorilaxxx](https://github.com/gorilaxxx)

---

## Overview

The **Deep Health Diagnosis Framework (DHDF)** is a structured and interactive AI-based health diagnosis framework.  
It is designed to guide the medical diagnostic process using a systematic, iterative, and validation-oriented approach.

This framework is ideal for:
- AI developers building prompt-based diagnostic systems
- IT and HealthTech practitioners
- Researchers in medicine and AI

---

## Core Principles

Fundamental principles that define the behavior of DHDF:

- **Modular & Iterative:** Diagnosis is performed in 10 interactive and layered steps.
- **Double Validation:** The system performs 2–3 internal checks before producing any diagnosis or recommendation.
- **Legal-Aware:** Tailored for healthcare regulation compliance (Indonesia as the initial baseline).
- **Context-Efficient:** Offers a compact version for AI models with limited context/token capacity.

---

## Directory Structure

```bash
//ai-framework-deep-health/
├── docs/                                # Project documentation
│   └── examples/                        # Sample diagnosis cases
│       └── flu-diagnosis.md             # Example case: flu diagnosis
│       └── mild-gad-esa-reflection.md   # Example case: mild gad
│   ├── dhdf-flowchart.mmd               # Mermaid diagram (diagnosis workflow)
│   ├── dhdf-v1.md                       # Main version of the DHDF
│   ├── esa-reflection.md                # Personal Insight After Health Diagnosis
├── AUTHORS.md                           # Information about project contributors
├── COMMERCIAL-LICENSE.md                # Commercial License Agreement
├── CONTRIBUTING.md                      # Contribution guidelines for this project
├── LICENSE                              # Project license (CC BY-NC 4.0)
├── README.md                            # Main project documentation
├── index.md                             # Index file for documentation
└── version.json                         # Contains framework version info, release date, and SHA256 hashes
```

---

## How to Use

To use DHDF in an AI environment such as ChatGPT or any LLM system:

1. Get the **raw file URL** from GitHub:  
   https://raw.githubusercontent.com/gorilaxxx/ai-framework-deep-health/main/docs/dhdf-v1.md

2. Input the content into the prompt or load it as a reference file before starting diagnosis.

3. The AI will follow the entire diagnostic structure defined in the framework.

---

## Activation

To automatically trigger this framework within AI systems that support **pre-prompting**, use the keyword:

```bash
AI Health:
```

> Make sure the `dhdf-v1.md` file is already loaded into the AI system's context or memory.  
> This trigger only works in environments that support pre-prompting (e.g., ChatGPT with custom instructions or API setup).

---

## Prompt Example

```bash
AI Health: "I've been having a headache and slight fever. What should I check?"
```

The AI will begin guiding you using the structured flow in DHDF.

---

## ⚖️ License

This framework is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.  
You may use, share, and adapt the materials for **non-commercial** purposes, provided that proper attribution is given.

> ⚠️ For **commercial licensing**, please refer to the [COMMERCIAL-LICENSE.md](./COMMERCIAL-LICENSE.md) for detailed terms and contact instructions.

🔗 [View the full license text »](https://creativecommons.org/licenses/by-nc/4.0/)

---

## Disclaimer

This framework is intended for **educational, prototyping, and research** purposes only.  
It is **not** meant to replace professional medical diagnosis.  
Use of the framework is entirely at the user's own risk and discretion.

---

## Ownership & Originality

This framework — **Deep Health Diagnosis Framework (DHDF)** — was originally conceptualized and developed by **[@gorilaxxx](https://github.com/gorilaxxx)**.

All files, structures, and ideas are publicly versioned in this GitHub repository since **April 2025**.  
Any use, reference, or derivative work must properly credit the original source.

For questions or contributions, please contact via GitHub or open an issue.

---
