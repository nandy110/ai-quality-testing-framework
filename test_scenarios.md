# AI Testing Scenarios

## What Are We Testing?

Every AI system needs to be tested for safety, accuracy, and compliance before it goes live.

## Testing Categories

### 1. Prompt Injection Testing
**What is it?** Can someone trick the AI into doing harmful things?

**Example:**
**What we check:**
- Can user override AI guidelines?
- Can we make AI reveal secrets?
- Can we make AI behave badly?

**Result:** ✅ Pass / ❌ Fail

---

### 2. Bias Detection Testing
**What we check:**
- Gender bias
- Racial bias
- Age bias
- Religious bias

**Result:** ✅ Pass / ❌ Fail

---

### 3. Hallucination Testing
**What is it?** Does the AI make up false information?

**Example:**
**What is it?** Does the AI treat everyone fairly?

**Example:**
**What we check:**
- Does AI provide accurate facts?
- Does AI admit when it doesn't know?
- Does AI make up sources or citations?

**Result:** ✅ Pass / ❌ Fail

---

### 4. Sensitive Data Leakage Testing
**What is it?** Does the AI accidentally reveal private information?

**Example:**
**What we check:**
- Does AI reveal passwords?
- Does AI share personal information?
- Does AI expose confidential data?

**Result:** ✅ Pass / ❌ Fail

---

### 5. Compliance & Safety Testing
**What is it?** Does the AI follow legal and ethical guidelines?

**Example:**
**What we check:**
- Does AI refuse harmful requests?
- Does it follow GDPR/privacy laws?
- Does it avoid illegal instructions?
- Does it handle healthcare/finance compliance?

**Result:** ✅ Pass / ❌ Fail

---

## Summary

| Test Type | Purpose | Pass Means |
|-----------|---------|-----------|
| Prompt Injection | Security | AI cannot be manipulated |
| Bias Detection | Fairness | AI treats everyone equally |
| Hallucination | Accuracy | AI provides correct info |
| Data Privacy | Security | AI doesn't leak secrets |
| Compliance | Legal | AI follows rules & laws |

---

## Next Steps
- See `prompt_injection_tests.md` for detailed examples
- See `bias_detection_tests.md` for detailed examples
- See Giskard reports in `results/` folder
