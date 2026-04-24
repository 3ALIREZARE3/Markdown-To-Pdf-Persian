# Farsimd 🖋️📄
**A simple, browser-based Markdown editor focused on Persian (فارسی) typography with PDF and Word export.**

Most Markdown editors are designed for English and struggle with Right-to-Left (RTL) scripts, leading to broken layouts or poor font rendering. **Farsimd** is a single-file solution that provides a native RTL environment and high-quality Persian web fonts.

## ✨ Features
- **Full RTL Support:** Automatically aligns Persian text to the right.
- **Persian Typography:** Built-in support for popular fonts:
  - **Vazirmatn:** Modern and clean (Standard UI).
  - **Amiri:** Classical and elegant (Book style).
  - **Lalezar:** Bold and decorative (Headlines).
- **Export Options:**
  - 📄 **PDF:** High-quality export using the browser's print engine.
  - 📘 **MS Word:** Downloadable `.doc` files that preserve RTL and Persian encoding.
- **Code LTR Auto-fix:** Programming code blocks are automatically forced to Left-to-Right (LTR) for readability.
- **Page Breaks:** Support for manual page breaks in PDF using `<div class="page-break"></div>`.
- **Zero Installation:** Runs entirely in your browser. No server, no Node.js, no dependencies to install.

## 🚀 How to Use
1. **Download** the `index.html` file from this repository.
2. **Open** the file in any modern web browser (Chrome, Edge, or Firefox).
3. **Write** your content in Markdown.
4. **Customize** the font and size using the top toolbar.
5. **Export:**
   - Click **Save PDF** and choose "Save as PDF" in the print destination.
   - Click **Save Word** to instantly download a Word-compatible document.

## 🛠️ Built With
- [marked.js](https://github.com/markedjs/marked) - High-speed Markdown parsing.
- [Google Fonts](https://fonts.google.com/) - Persian web font delivery.
- **Vanilla JS & CSS3** - Lightweight logic and RTL styling.

## 💡 Pro-Tips for Persian Users
- **Bilingual Text:** The app handles mixed Persian and English sentences well. 
- **Coding:** When writing code, use triple backticks (\` \` \`). The editor will ensure the code remains LTR while your Persian descriptions stay RTL.
- **Word Formatting:** If you open the exported Word file on a PC without the "Vazirmatn" font installed, it will automatically fall back to **Tahoma** to ensure the text remains readable.

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

---
*Created to make Persian content creation easier.*
