<div align="center">
  <img src="icons/icon128.png" alt="WCAGI Logo" width="128" />
  
  # WCAG Inspector (WCAGI)
  **A powerful, privacy-first accessibility DevTools extension for Google Chrome.**
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
  [![Axe-Core](https://img.shields.io/badge/Powered%20By-axe--core-red)](https://github.com/dequelabs/axe-core)
  [![Manifest V3](https://img.shields.io/badge/Manifest-V3-brightgreen)](#)
</div>

---

**Web Content Accessibility Guidelines (WCAG) Inspector** is a comprehensive, single-purpose Chrome Extension powered by the industry-standard `axe-core` engine. Designed for developers, designers, and QA testers, WCAGI makes it incredibly easy to identify, debug, and resolve accessibility issues directly within your browser.

## ✨ Key Features

- 🛡️ **Automated WCAG Auditing:** Run comprehensive checks against WCAG 2.1 and 2.2 standards (Levels A, AA, and AAA).
- 🎛️ **Dedicated DevTools Panel:** Easily navigate through categorized accessibility modules:
  - Page Structure
  - Tables & Grids
  - Forms & Labels
  - Images (Alt text)
  - Links & ARIA
  - Color Contrast
- 👁️ **Visual Assist Overlays:** Inject CSS directly into the page to visually debug issues:
  - **Linearize:** Collapse layout to verify logical reading order.
  - **Text Spacing:** Test if layout breaks when spacing is overridden (WCAG 1.4.12).
  - **Enhanced Focus:** Inject high-visibility focus indicators.
  - **Target Size:** Visualize actionable target boundaries (WCAG 2.5.8).
- ⚡ **Live Scan Mode:** Automatically rescan the page on load or refresh—perfect for rapid development cycles.
- 🚀 **On-Page Widget:** Launch a lightweight widget directly on the page for a quick accessibility summary without opening DevTools.
- 📊 **CSV Export:** Export full audit reports for issue tracking and team collaboration.

## 🚀 Installation

*(Note: The official Chrome Web Store link will be added here once the extension is published.)*

1. **Install** [WCAGI Chrome Extension](https://chromewebstore.google.com/) from the official Chrome Web Store.
2. **Pin for Easy Access:** After installation, click the puzzle piece icon in your Chrome toolbar and **Pin** WCAGI so it's always available when you need to run an audit.
## 🛠️ How to Use

1. **Quick Summary:** Click the WCAGI icon in your Chrome toolbar to launch the on-page Widget.
2. **Deep Dive Analysis:** Open Chrome Developer Tools (F12 or `Ctrl+Shift+I` / `Cmd+Opt+I`) and navigate to the dedicated **WCAGI** tab.
3. Navigate between modules in the sidebar to view categorized issues.
4. Click on any issue in the table to open the details drawer and highlight the failing element directly on the page.

## 🧪 Demo & Testing

Want to see WCAGI in action? We have a purposefully inaccessible demo site available to help you explore the extension's capabilities:
👉 **[Launch WCAGI Test Site](https://sucom.github.io/wcagi/test-site/)**

## 🔒 Privacy First

This extension respects your privacy. 
- **Zero Data Collection:** Absolutely no data is collected, tracked, or transferred.
- **Local Processing:** All scans are performed locally within your browser using the embedded axe-core engine.
- **No External Servers:** It does not communicate with external servers or require cloud processing.
- **No Browsing History Access:** It only runs on the specific page you choose to inspect.

## ⚠️ Limitations & Known Issues

- **Automated Scope:** Like all automated accessibility scanners, WCAGI can only detect roughly 30% to 40% of WCAG violations. Manual testing (e.g., keyboard-only navigation and screen reader testing) is still strictly required to achieve full compliance.
- **Restricted Pages:** Chrome security policies prevent this extension from scanning internal browser pages (e.g., `chrome://`, `chrome-extension://`) or the Chrome Web Store itself.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). 
Powered by the open-source [axe-core](https://github.com/dequelabs/axe-core) accessibility engine.
