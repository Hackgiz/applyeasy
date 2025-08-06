## ApplyEasy v0.2.2
- PDF → Profile suggestions: when you add a PDF resume to the Vault, ApplyEasy extracts contact details and offers to update your profile
- Graceful fallback if pdf.js is not present
- Includes Resume Vault, Attach Resume button, and update checker

**Install (unpacked)**
1) Download the ZIP
2) `chrome://extensions` → Developer mode → **Load unpacked**
3) Options → Resume Vault → upload your PDF. (For parsing, add `lib/pdf.min.js` + `lib/pdf.worker.min.js`.)
