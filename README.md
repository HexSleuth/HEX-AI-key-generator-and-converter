<div align="center">

# 𓋹 • HEX AI Key Generator & Converter • 𓃠

[![GitHub Pages](https://img.shields.io/badge/Status-Live%20on%20GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)](https://hexsleuth.github.io/HEX-AI-key-generator-and-converter/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Vanilla JS](https://img.shields.io/badge/Tech-Vanilla%20JS%20%2F%2F%20HTML5-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A lightning-fast, client-side utility suite featuring a deterministic heuristic AI key generator, robust base converters, time-synchronization tools, color pickers, and a multi-format encoder/decoder—running 100% locally in your browser with zero server dependencies.

[**Explore Live Demo**](https://hexsleuth.github.io/HEX-AI-key-generator-and-converter/)

</div>

---

## 🚀 Key Features

### 1. 🧠 HEX AI Key Generator
* **Client-Side Heuristic Generator:** Runs entirely inside your browser using a keyword-intent planner combined with `crypto.getRandomValues()` for real cryptographic entropy.
* **Zero API Keys Required:** Generate, test, and prototype instantly without leaking keys or making external network requests.
* **Batch Generation:** Quickly generate multiple keys simultaneously (1, 2, 3, 5, 10, or 25 keys).

### 2. 🎨 Android-Style Color Picker
* **HSV Color Picker:** Interactive color swatch dialog with live previews.
* **Multiple Formats:** Instant readout for HEX (`#33B5E5`) and RGB values (`rgb(51, 181, 229)`).
* **One-Tap Copy:** Built-in copy triggers utilizing system toasts and clean UX feedback.

### 3. 🌐 Free Coding Model Providers
* **Curated Offline Catalogue:** Browse an embedded database of free coding model providers and APIs directly in your browser.
* **Simulated Stream:** Test loading states and view structured provider cards without hitting live endpoints.

### 4. ⏱️ Advanced Time & Epoch Utilities
* **Unix Epoch Clock:** Real-time second counter tracking seconds elapsed since `00:00:00 UTC on January 1, 1970`.
* **Tomillis Tool:** Convert dates into Unix milliseconds and hex with a pick-a-date workflow ported from native Android patterns.
* **Unix Hex Timestamp Converter:** Seamless conversion between decimal timestamps, hexadecimal, and human-readable ISO/UTC dates.
* **Epoch in Code Snippets:** Quick reference code snippets in multiple programming languages to fetch epoch times and parse timestamps.

### 5. 🔢 Comprehensive Number System Converters
* **Decimal to Hexadecimal:** Full division-by-16 remainder step-by-step breakdown, little/big-endian byte views, and conversion tables. Supports scientific notation (e.g., `572 = 5.72e2`).
* **Base Converter (Hex ⇄ Binary ⇄ Decimal ⇄ Octal ⇄ Text):** Universal cross-base converter supporting custom prefixes (`0b`, `0o`, `0x`), digit grouping (4, 8, 16 digits), and UTF-8 text round-trips.

### 6. 🔤 Multi-Format Encoder / Decoder
An all-in-one text transformation suite supporting:
* ASCII, Binary, HEX, Octal
* Base32, Base64, Base85
* URL Encoding/Decoding
* Case Transformers (UPPER, lower, Reverser)
* Stylized Fonts (Upside-Down, Superscript, Subscript)
* Morse Code & Zalgo Text Generators (mini, normal, big)

---

## 🛠️ Tech Stack

* **HTML5 / CSS3:** Responsive layouts, custom UI components, and modern CSS variables.
* **Vanilla JavaScript (ES6+):** Modular, lightweight scripts utilizing browser crypto APIs (`crypto.getRandomValues`) and high-precision timing.
* **GitHub Pages:** Fast, reliable static hosting.

---

## 📂 Project Structure

```text
├── index.html            # Main application layout & UI markup
├── assets/               # Stylesheets, icons, and static assets
└── js/                   # Core application logic & converters
