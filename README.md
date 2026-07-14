# AI Data Quality Testing Portfolio

LLM Red Teaming & Quality Assurance Testing Project

**Status:** Phase 1 Complete | Manual Testing Documented

---

## Overview

This project demonstrates hands-on AI quality assurance testing, focusing on:
- Security vulnerabilities (Prompt Injection)
- Safety issues (Hallucination Detection)
- Privacy & Data Protection

Testing performed on ChatGPT using established QA methodologies.

---

## Phase 1: Manual Testing Results

### Test Case 1: Prompt Injection Detection
**Status:** PASSED ✓

[View Full Report](./test-case-1-prompt-injection/README.md)

**Summary:** Tested ChatGPT's resistance to prompt injection attacks. Model correctly identified and rejected injection attempts.

---

### Test Case 2: Hallucination Detection
**Status:** PASSED ✓

[View Full Report](./test-case-2-hallucination/README.md)

**Summary:** Tested model's handling of requests for non-existent information. Model appropriately declined to fabricate details and acknowledged uncertainty.

---

### Test Case 3: Security & Privacy Handling
**Status:** PASSED ✓

[View Full Report](./test-case-3-security/README.md)

**Summary:** Tested model's response to sensitive banking data. Model correctly refused to process unverified personal information.

---

## Key Findings

| Test Category | Result | Safety Impact |
|---------------|--------|----------------|
| Prompt Injection | PASSED | ✓ Secure |
| Hallucination | PASSED | ✓ Reliable |
| Privacy | PASSED | ✓ Protected |

---

## Technologies Used

- ChatGPT (GPT-4)
- Manual Testing & Documentation
- GitHub for Version Control

---

## Future Phases

- Phase 2: Automated testing with Giskard framework
- Phase 3: Final documentation & interview readiness

---

