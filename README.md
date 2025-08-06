# ApplyEasy
*Stress‑free, breezy resume autofiller by Eric Hilerio*

**ApplyEasy** autofills common job application fields on Greenhouse, Lever, and LinkedIn Easy Apply. It includes a Resume Vault and one‑click Attach Resume button, plus optional PDF→Profile suggestions.

## ✨ Features
- Autofill for common ATS fields (Greenhouse/Lever/LinkedIn Easy Apply)
- **Resume Vault**: store multiple resumes and attach fast
- **Attach Resume** button next to file inputs
- **Optional** PDF→Profile suggestions (extracts contact info from your resume)
- Update checker (set your repo under Options → Updates)

## 🧩 Install (Unpacked)
1. Download the **latest release ZIP**
2. Unzip it
3. Go to `chrome://extensions` → toggle **Developer mode**
4. Click **Load unpacked** and select the unzipped folder

> Safari: Use Xcode → *File → New → Project… → Safari Web Extension App* → point to this folder, then build and enable in Safari.

## 🔎 PDF Parsing (optional)
To enable PDF→Profile suggestions, add **pdf.js** files locally:
- Place `lib/pdf.min.js` and `lib/pdf.worker.min.js` in the extension folder
- Reload the extension

> Download from Mozilla’s pdf.js releases. If these files are missing, ApplyEasy still works; it just skips parsing.

## 🔧 Usage
- Open a job application page → click **ApplyEasy → Fill this page**
- For resume inputs, click **Attach Resume** and pick one from your Vault
- Manage your profile/resumes under **Options**

## 🔒 Notes & Limits
- Browsers block true auto‑attaching files; ApplyEasy downloads your chosen resume and opens the picker for you to confirm
- Parsing is heuristic and works best on text‑based PDFs (not scanned images)

## 🗺 Roadmap
- Workday / iCIMS / Taleo / SuccessFactors selectors
- Per‑role resume tagging
- Optional OCR for scanned PDFs

## 🆕 Changelog
- **v0.2.2** — PDF→Profile suggestions (optional pdf.js), improvements
- **v0.2.1** — Rebrand to ApplyEasy
- **v0.2.0** — Resume Vault + Update checker

## 📜 License
MIT — see [LICENSE](LICENSE)
