# 🐞 Bug Report Log

This file contains a list of bugs or issues encountered during manual testing of the Money Transfer Web App.

---

## 🔴 BUG-001: No inline error for missing “To Account”

- **Area:** Transfer to Own Account
- **Steps:**
  1. Go to Transfer → Own Account
  2. Leave “To Account” blank
  3. Click “Next”
- **Expected:** Inline error under “To Account” field
- **Actual:** Page reloads, no error shown
- **Severity:** Medium
- **Status:** Open

---

## 🔴 BUG-002: "Invalid Amount" allows submission

- **Area:** Transfer - All types
- **Steps:** Enter `abc123` in Amount → click “Next”
- **Expected:** Input blocked or error
- **Actual:** Transaction proceeds to confirmation
- **Severity:** High
- **Status:** Open

---

## 🔴 BUG-003: “Cancel” button does not clear form

- **Area:** PromptPay > Mobile Phone
- **Expected:** Clears all fields and resets form
- **Actual:** Phone number remains filled
- **Severity:** Low
- **Status:** Open

---

## 🔴 BUG-004: No confirmation for large amounts

- **Area:** Transfer to Other Account
- **Input:** Amount = 999,999.99
- **Expected:** Confirm with additional dialog
- **Actual:** Proceeds directly
- **Severity:** Medium
- **Status:** Open

---

## 🟡 BUG-005: Transaction complete message overlaps "Back" button

- **Screen:** Confirmation
- **Expected:** Message and button spacing is clear
- **Actual:** Overlap occurs
- **Severity:** Minor
- **Status:** Open
