ApplyEasy – Stress-Free, Breezy Resume Autofiller
by Eric Hilerio

A lightweight browser extension that autofills job application forms using a profile you set once.
Works on Greenhouse, Lever, and Workday — with support for more ATS coming soon.

🚀 Features
🔄 Auto-Run (New in v0.3.0)
Instantly fills supported application forms when the page loads:

Greenhouse

Lever

Workday

⚡ One-Click Fill Anywhere
Right-click context menu: ApplyEasy → Fill this page

Keyboard shortcut: Alt+F (customizable in your browser)

Popup button for manual fill on any supported site

🧠 Smarter Autofill Engine
Detects fields inside shadow DOM and iframes

Matches by label, placeholder, aria-label, autocomplete, and more

Fires proper input and change events for compatibility with React, Vue, Angular, etc.

🎯 Custom Field Mappings
Map site-specific labels to your profile fields
(Example: "Preferred Name" → firstName)

📦 Profile Import / Export
Backup your settings to JSON

Restore or migrate to another browser instantly

📂 Resume Vault
Store multiple resumes securely inside the extension

Quickly download them to your Downloads folder when file pickers appear

📥 Installation
Chrome / Edge (Unpacked)
Download the latest .zip from Releases.

Extract it somewhere on your computer.

Open chrome://extensions or edge://extensions.

Toggle Developer mode on.

Click Load unpacked and select the extracted folder.

🛠 Usage
Click the ApplyEasy icon → Options → Fill in your profile details.

(Optional) Upload your resumes to the Resume Vault.

Visit a supported job application page:

Auto-run: ApplyEasy will fill it automatically.

Manual: Use the popup, context menu, or shortcut Alt+F.

Select your resume in the file picker when prompted.

📝 Supported Sites
Greenhouse

Lever

Workday
(More ATS coming soon — see Contributing)

⚠ Notes & Limitations
File uploads cannot be automated due to browser security restrictions — you must select the file manually when prompted.

Auto-run is only enabled for listed supported sites.

Fields are matched heuristically — always review before submitting.

🤝 Contributing
Want to add support for more Applicant Tracking Systems (ATS)?

Fork the repo.

Add the site’s domain to manifest.json → host_permissions.

Extend the form-filling logic in content.js.

Submit a Pull Request.

📄 License
MIT License © Eric Hilerio


## 📜 License
MIT — see [LICENSE](LICENSE)
