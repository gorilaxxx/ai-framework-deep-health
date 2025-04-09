# AI Framework: Deep Health Diagnosis Framework (DHDF)

![License](https://img.shields.io/github/license/gorilaxxx/ai-framework-deep-health)
![Last Commit](https://img.shields.io/github/last-commit/gorilaxxx/ai-framework-deep-health)
![Contributors](https://img.shields.io/github/contributors/gorilaxxx/ai-framework-deep-health)
![Issues](https://img.shields.io/github/issues/gorilaxxx/ai-framework-deep-health)
![Stars](https://img.shields.io/github/stars/gorilaxxx/ai-framework-deep-health)

**Version:** v1.0  
**Status:** In Development  
**Repository:** `ai-framework-deep-health`  
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
│   ├── dhdf-v1.md                       # Main version of the DHDF
│   ├── dhdf-flowchart.mmd               # Mermaid diagram (diagnosis workflow)
│   └── examples/                        # Sample diagnosis cases
│       └── flu-diagnosis.md             # Example case: flu diagnosis
│       └── mild-gad-esa-reflection.md   # Example case: mild gad
├── AUTHORS.md                           # Information about project contributors
├── CONTRIBUTING.md                      # Contribution guidelines for this project
├── LICENSE                              # Project license (MIT License)
├── README.md                            # Main project documentation
└── index.md                             # Index file for documentation
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

```
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

## License

This project is licensed under the MIT License. See the LICENSE file for details.

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
