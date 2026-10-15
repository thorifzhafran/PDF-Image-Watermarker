# Secure Client-Side PDF & Image Watermarker

> A privacy-first, zero-upload utility designed to watermark sensitive credentials (passports, certificates, and ID documents) directly inside your browser. Built with a unified interface and styled using the Bento Quiet design system.

[![Try Here](https://img.shields.io/badge/🚀%20Try%20Here-thorifzhafran.github.io%2FPDF--Image--Watermarker-3552d4?style=for-the-badge&logoColor=white)](https://thorifzhafran.github.io/PDF-Image-Watermarker/)

![PDF & Image Watermarker Thumbnail](https://raw.githubusercontent.com/thorifzhafran/PDF-Image-Watermarker/main/pdf-image-watermarker-thumbnail.webp)

---

## 🔒 Why Frontend-Only?

Existing watermarking tools often require uploading your confidential files to third-party cloud servers. This application processes everything **100% locally in your browser** using HTML5 Canvas, `pdf-lib`, and PDF.js. Your sensitive documents never leave your device.

---

## ✨ Features

* **Unified File Support:** Seamlessly handle both PDF documents and image files (`.png`, `.jpg`, `.jpeg`) in a single application.
* **Real-Time Live Preview:** Watch your watermark settings update instantly over your actual document content before exporting.
* **Customizable Watermark Controls:**
  * **Text Customization:** Enter custom verification text, dates, or reference numbers.
  * **Percentage Opacity:** Fine-tune transparency from `5%` to `100%`.
  * **Font Size & Grid Spacing:** Adjust scaling and tile spacing across the entire page grid.
  * **Full Rotation (0°–360°):** Rotate text at any precise angle.
  * **Color Picker:** Choose custom ink colors for your watermark.
* **Drag & Drop Upload:** Quick, friction-free file input.
* **Mobile Friendly:** Fully responsive layout optimized for mobile browsers.

---

## 🛠️ Built With

* **HTML5 Canvas & File API** — Local document rendering and manipulation.
* **[pdf-lib](https://pdf-lib.js.org/)** — Client-side PDF modification and multi-page watermarking.
* **[PDF.js](https://mozilla.github.io/pdf.js/)** — In-browser PDF page rendering for live previews.
* **Design System** — Styled with **Bento Quiet**, featuring Plus Jakarta Sans and JetBrains Mono typography.

---

## 📂 Project Structure

```text
├── index.html       # Complete single-file PWA / web application
└── README.md        # Project documentation
