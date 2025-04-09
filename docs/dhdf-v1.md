# DHDF v1.1 — Deep Health Diagnosis Framework

## Version Information
**Version:** 1.1  
**Release Date:** April 5, 2025  
**Status:** Stable  
**Previous Version:** [1.0](./dhdf-v1.0.md)  
**Change Log:**
- Added versioning information and file integrity control
- Enhanced logical validation and emergency triage
- Integrated Esa Framework for optional reflection
- Improved traceability and input validation mechanisms

---

## Purpose

The Deep Health Diagnosis Framework (DHDF) is designed to assist AI systems in processing user-submitted health complaints through a structured, logical, and step-by-step approach. DHDF integrates clinical protocols, legal and ethical compliance, and an optional spiritual reflection path to provide comprehensive user support.

---

## Framework Structure

### 1. User Initiation
- **Start:** User submits a health complaint.
- **Clarity Check:** System evaluates clarity of complaint.
  - *If unclear:* Prompt for clarification, then re-evaluate.
  - *If clear:* Proceed to symptom identification.

### 2. Initial Psychological Disorder Detection
- **Symptom Analysis:** Determine if symptoms relate to mental/emotional health.
  - *If Yes:* Redirect to Mental Health Screening.
  - *If No:* Continue with follow-up questioning.

### 3. Mental Health Screening (Optional: PHQ-9 / GAD-7)
- **Execute Screening:** Conduct PHQ-9 or GAD-7.
- **Evaluate Distress:**
  - *If distress detected:* Suggest referral to mental health specialist.
  - *If no distress:* Continue to data collection.

### 4. Additional Information Gathering
- **Ask Follow-Ups:** Based on previous responses.
- **Collect Data:** Risk factors, medical history.

### 5. Input Sufficiency Validation
- **Evaluate Completeness:**
  - *If insufficient:* Ask user to reframe or restart complaint.
  - *If sufficient:* Continue to temporary diagnosis.

### 6. Temporary Diagnosis Mapping
- **Build Map:** Create temporary diagnostic view.
- **Consistency Check:**
  - *If inconsistent:* Re-analyze for contradictions.
  - *If consistent:* Proceed to conclusion validation.

### 7. High-Risk Symptom Detection
- **Risk Screening:** Identify signs of urgent conditions.
  - *If high-risk:* Trigger medical alert or referral.
  - *If life-threatening:* Prompt user to call emergency service.
  - *If not high-risk:* Proceed to compliance check.

### 8. Legal & Ethical Compliance
- **Scope Review:**
  - *If outside AI boundaries:* Escalate to human medical professional.
  - *If compliant:* Prepare summary and recommendations.

### 9. Final Validation & Output
- **Validation:** Final review before output.
- **Delivery:** Present output to user.

### 10. Logging for Audit
- **Traceability:** Log decisions for future audits and integrity checks.

### 11. Optional Spiritual Reflection (Non-Clinical)
- **User Request:** Check if user wants reflection.
  - *If yes:* Offer optional non-clinical reflection as outlined in `esa-reflection.md`.
  - *If no:* End process.

---

## Logging & Audit

Each step is logged internally to support:

- **Quality Assurance**
- **Professional Review**
- **Transparent AI Diagnostics**

---

## Optional Path: Spiritual Reflection

After medical diagnosis, users may optionally explore **non-clinical spiritual reflection** via the **Esa Framework**.  
This layer offers:

- Broader inner perspective
- Non-religious spiritual alignment
- Deeper meaning exploration

**See:** [`esa-reflection.md`](./esa-reflection.md)

---

## Legal Disclaimer

This framework:

- Does **not replace** professional diagnosis
- Is **not for emergency use**
- Is a structured **support tool**, not a definitive system

---

## License

This framework is licensed under the **Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)** license.  
For commercial use, refer to [`COMMERCIAL-LICENSE.md`](./COMMERCIAL-LICENSE.md).
