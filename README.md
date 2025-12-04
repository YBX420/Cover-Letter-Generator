# Cover Letter Generator

A single-page, browser-based cover letter builder.  
It lets you tweak text on the left and see a live typeset preview on the right, then print or export as PDF.

No backend, no build step — just open the HTML file in a browser.

---

## Features

- **Three visual themes**
  - `Modern` – Google-style accent bar and Roboto typography  
  - `Classic` – Serif layout with centered header  
  - `Minimal` – Bold, high-contrast, editorial layout

- **Live preview**
  - Left sidebar for inputs (name, contact info, paragraphs, recipient)
  - Right side A4 page preview with real typography and spacing
  - Date auto-fills based on the user’s current date

- **Structured content blocks**
  - Personal info (name, subtitle, email, phone)
  - Recipient / company
  - Opening, body, and closing paragraphs
  - Signature automatically syncs with your name field

- **Autosave**
  - Uses `localStorage` to remember your latest content and selected theme
  - Refresh or close/open the tab and your text is still there

- **Print-ready**
  - Dedicated print styles via `@media print`
  - Hides the editor sidebar, removes shadows
  - Designed for A4 export (Print → Save as PDF)

---

## Tech Stack

- **HTML/CSS/JavaScript** only
- **Fonts**
  - [Inter](https://fonts.google.com/specimen/Inter)
  - [Roboto](https://fonts.google.com/specimen/Roboto)
  - [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) (reserved if needed)
  - [Crimson Pro](https://fonts.google.com/specimen/Crimson+Pro) for the classic theme
- **No dependencies**
  - No frameworks, no bundler, no build tools

---

## Getting Started

1. Clone or download the project.
2. Open the HTML file in a modern browser (Chrome / Edge / Firefox / Safari).
3. Start typing in the left panel — the right panel updates in real time.

```bash
# Example
git clone <your-repo-url>
cd cover-letter-generator
open index.html    # or double-click in your file explorer
```

4. Save it as PDF by Clicking "Print/Save as PDF", unclick Headers and footers , and make sure the margin is the Minimum value
