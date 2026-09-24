# PixcraftAI - Adobe Stock & Microstock Batch SEO Metadata Generator

An intelligent, high-throughput microstock SEO metadata generator designed specifically for **Adobe Stock**, **Shutterstock**, **Freepik**, **Vecteezy**, and other stock photography marketplaces.

![PixcraftAI](https://img.shields.io/badge/Platform-Adobe%20Stock%20%7C%20Shutterstock%20%7C%20Freepik-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-2.0.0-emerald?style=for-the-badge)

---

## 🌟 Key Features

- **Top 10 Weighting Engine for Adobe Stock**:
  - Automatically curates and highlights the top 10 most critical commercial keywords (which carry **80% of search ranking weight** on Adobe Stock).
  - Promotes subject, core visual action, and setting to prime positions.
  - Reorder, promote, and delete tags with single-click actions.

- **Batch Processing (Up to 500 Images)**:
  - Parallel queue processing for large batches of JPG, PNG, WEBP, and AVIF assets.
  - Live progress bar, individual thumbnail status indicators, and keyboard navigation (`Alt + Left/Right Arrow`).

- **Flexible AI & Built-in Engine**:
  - **Vision AI Mode**: Integrates with Google Gemini Vision models (`gemini-2.5-flash`, `gemini-2.0-flash`, `gemini-1.5-flash`) for deep visual recognition of subjects, setting, lighting, and composition.
  - **Fast Built-in Heuristic Mode**: Works instantly offline/without an API key to produce compliant stock titles and 48 ranked tags.
  - **Built-in API Tester**: Test your connection directly from the settings dialog.

- **Microstock Compliance & Quality Score**:
  - Real-time **SEO Quality Score** meter (0–100%).
  - Real-time validation of title length (55–75 chars optimal).
  - Detection and warning for prohibited spam buzzwords (`isolated on white`, `stunning`, `4k`, `copyspace`, etc.).
  - Recommended tag count tracking (35–49 tags).

- **Multi-Agency Export Options**:
  - **Adobe Stock CSV** (`Filename,Title,Keywords,Category,Releases`)
  - **Shutterstock CSV** (`Filename,Description,Keywords,Categories`)
  - **Universal Microstock CSV** (`Filename,Title,Description,Keywords`)
  - One-click copy for individual rows or all batch rows to clipboard.
  - Full project ZIP download.

- **Bulk Editing Tools**:
  - **Apply Tag to All**: Quickly inject campaign tags (e.g. `summer`, `travel`, `paris`) to every image in your batch.
  - **Paste Support**: Paste comma-separated keyword lists to automatically split, sanitize, and import.
  - **Single Item Removal**: Delete individual photos from the queue without resetting your session.
  - **Visual Image Inspection**: Click on any preview thumbnail for a high-resolution inspection modal.

---

## 🚀 How to Run

No build step or complex dependencies required. Simply:

1. Double-click [index.html](file:///c:/Users/RAFIQULISLAM/Desktop/All%20Apps/10-%20APPS%20GENERATE/40-Metadata-Create/index.html) (or `stock_metadata_ai_generator.html`) to open it in any modern browser (Chrome, Edge, Firefox, Safari).
2. (Optional) Click the **AI Mode / Key** button in the top navigation to add your free Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
3. Drag & drop your images into the upload zone.
4. Review, refine, and export your CSV ready for upload to Adobe Stock Contributor portal.

---

## 📁 Project Structure

```
├── index.html                       # Main web application entry point
├── stock_metadata_ai_generator.html # Standalone application file
└── README.md                        # Documentation and guides
```

---

## 📄 License

MIT License. Free for personal and commercial stock photography workflows.
