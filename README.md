# Simple PO-Invoice Matcher 🧾✅

This is a lightweight web app that helps you compare **quote (PO)** and **invoice** images by automatically extracting and matching:

- 📌 **PO Numbers**
- 💵 **Total Amounts**

It uses **Tesseract.js** (a browser-based OCR library) to read text from uploaded images and matches them using simple JavaScript—no backend or AI setup required.

---

## 🔧 How It Works

1. Upload a quote (used as the PO) and an invoice.
2. The app extracts the PO number and total amount from each file.
3. It compares both fields and tells you if they match or not.

---

## 🛠️ Built With

- HTML, CSS, JavaScript
- [Tesseract.js](https://github.com/naptha/tesseract.js) for OCR
- Canvas API to generate dummy test images (optional)

---

## 🚀 Getting Started

### Option 1: Run Locally

1. Clone or download the repo.
2. Open `index.html` in your browser.
3. Use `dummy.html` to generate test images, or upload your own quote/invoice images.

### Option 2: View Live on GitHub Pages (if deployed)

```bash
https://yourusername.github.io/simple-po-invoice-matcher/
