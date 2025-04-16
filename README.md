# Simple PO-Invoice Matcher 🧾✅

A lightweight, browser-based web app that compares **quote (PO)** and **invoice** images by automatically extracting and matching:

- 📌 **PO Numbers**
- 💵 **Total Amounts**

It uses **Tesseract.js** (a client-side OCR library) to extract text and performs direct field matching using JavaScript—no backend, no server, no AI APIs required.

---

## 💡 Project Motivation

This project was developed to demonstrate that accounts payable workflows—specifically matching quotes and invoices—can be dramatically simplified. At my current organization, invoice payments are frequently delayed for months due to inefficient manual processes. This MVP was built to prove that:

- Basic PO/invoice validation can be automated with minimal tools
- A streamlined AP process doesn't require a large team or complex systems
- A single motivated contributor can build a reliable, no-cost solution

---

## 🔧 How It Works

1. Upload a quote (used as the PO) and an invoice image.
2. The app extracts the PO number and total amount from each.
3. It compares both values and flags any mismatches for review.

---

## 🛠️ Tech Stack

- HTML, CSS, JavaScript
- [Tesseract.js](https://github.com/naptha/tesseract.js) for OCR
- Canvas API (used for generating test images via `dummy.html`)

---

## 🚀 Getting Started

### Run Locally

1. Clone or download the repository.
2. Open `index.html` in your browser.
3. (Optional) Use `dummy.html` to generate sample PO and invoice images.

### Deploy

This app is fully static and can be deployed using GitHub Pages or any static site host (e.g., Netlify, Vercel).
