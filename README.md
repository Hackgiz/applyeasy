# ApplyEasy-Ready

One-click autofill for common job portals.

**Supports:** Greenhouse · Lever · Workday (external/myworkdayjobs) · iCIMS · Taleo  
**Extras:** Resume/Cover upload helper · Theme toggle · Keyboard shortcut (Alt+Shift+A)

## Install (unpacked)
1. Download the latest zip from **Releases**.
2. Unzip → `chrome://extensions` → enable **Developer Mode** → **Load unpacked** → select the folder with `manifest.json`.
3. Open the popup, enter your profile, **Save**, then use **Autofill Page** or press **Alt+Shift+A**.

## Using the upload helper
Click **Attach Resume** / **Attach Cover** in the popup. We highlight the right file input and open the chooser (you pick the file).

## Theme
Toggle Light/Dark in the popup header. Choice is saved and used for small on-page toasts, too.

## Roadmap
- SAP SuccessFactors adapter
- BrassRing adapter
- Workday per-employer tweaks

## Contributing
- File issues with: portal type, URL pattern (domain), screenshot, and which fields weren’t filled.
- PRs welcome! Keep adapters lean and add sites under `adapters/`.

## Dev quickstart
```bash
# clone and run
git clone https://github.com/<you>/applyeasy-ready.git
cd applyeasy-ready
# edit in src; load the root folder as unpacked in chrome://extensions
📄 License
MIT License © Eric Hilerio


## 📜 License
MIT — see [LICENSE](LICENSE)
