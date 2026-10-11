# 𓋹 HEX AI Key Generator & Converter

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform: Web Browser](https://img.shields.io/badge/Platform-Web%20Browser-success.svg)](https://hexsleuth.github.io/HEX-AI-key-generator-and-converter/)
[![Crypto: Web Crypto API](https://img.shields.io/badge/Crypto-Web%20Crypto%20API-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API)

A comprehensive, lightning-fast, 100% client-side developer toolkit built for local security operations, encoding/decoding, key generation, and cryptographic primitives. Running entirely in the browser with zero external server requests or API dependencies.

🔗 **Live Demo:** [https://hexsleuth.github.io/HEX-AI-key-generator-and-converter/](https://hexsleuth.github.io/HEX-AI-key-generator-and-converter/)

---

## ✨ Core Features

### 1. HEX AI Key Generator & Heuristic Model
* **Deterministic Heuristic Planner:** Simulates AI-assisted key generation locally using client-side keyword-intent parsing.
* **Real Entropy:** Backed strictly by `crypto.getRandomValues()` for cryptographically secure randomness.
* **Zero API Dependency:** No external network requests or paid keys required.

### 2. Multi-Format Encoder / Decoder
Execute instant client-side transformations across dozens of formats:
* **Numeric Bases:** ASCII decimal, 8-bit binary, hexadecimal bytes, octal bytes.
* **Case & Order:** UPPERCASE, lowercase, random case, and full string reverser.
* **Unicode Styles & Typography:** Upside-down, superscript, subscript, Zalgo (mini/normal/big), Braille, Wingdings, Leetspeak (`1337`), and Unicode escapes (`\uXXXX`).
* **Ciphers & Alphabets:** Caesar shift, ROT-13, Atbash, NATO phonetic alphabet, and International Morse code.
* **Transport Encodings:** Base32 (RFC 4648), Base64, Base85/ASCII85, URL percent-encoding, and HTML entities.
* **Language Games:** Pig Latin with case preservation and reverse parsing.

### 3. Token & Identifier Generator
Generate secure cryptographically random strings for keys, IDs, salts, and tokens:
* HEX (lowercase / UPPERCASE)
* Alphanumeric, Base62, Base58 (Bitcoin alphabet), and URL-safe Base64
* UUID v4
* GitHub Personal Access Tokens (`ghp_`) and Fine-Grained tokens (`github_pat_`)

### 4. Advanced Encryption Key Generators (Web Crypto API)
Equipped with modern algorithms and live runtime feature detection (`SubtleCrypto.supports()`):
* **Symmetric:** AES (GCM/CBC/CTR/OCB), ChaCha20-Poly1305, and AES-KW key wrapping.
* **Key Derivation & Secrets:** HKDF, PBKDF2, Argon2 (where supported), and HMAC.
* **Asymmetric & Secure Curves:** RSA, ECC, EdDSA, Ed25519, Ed448, X25519, and X448.
* **Post-Quantum Cryptography:** ML-KEM (512/768/1024) and ML-DSA hybrid encapsulation and signature schemes.
* **SSH, VPN & PGP Key Formats:** Support for raw, spki, pkcs8, and jwk key structures.

### 5. Hash & Cryptographic Digest Generator
Compute digests locally with zero latency:
* **Classic Digests:** SHA-1, SHA-2, SHA-3, and MD5 (legacy).
* **XOF (Extendable-Output Functions):** cSHAKE128/256, KangarooTwelve, and TurboSHAKE.
* **Password Hashing:** PBKDF2-HMAC-SHA256 with adjustable iterations (OWASP 210k+ default).
* **File Hashing:** Instant client-side file checksum computation.

### 6. Secure Password Generator
* Built exclusively on `crypto.getRandomValues()` with rejection sampling to eliminate modulo bias.
* Highly customizable character sets, symbol toggles, and length sliders.

### 7. JWT Tooling & Reference Guide
* Sign and verify **HS256**, **HS384**, and **HS512** tokens locally using HMAC via the Web Crypto API.
* Comprehensive built-in guides for multi-language JWT libraries (Node.js, Python, Java, C#, PHP, Go) and security best practices.
### 8.🔒Privacy & Security
100% Client-Side: All keys, encodings, hashes, and tokens are generated entirely within your browser runtime.
Zero Telemetry: No data is logged, tracked, or transmitted to any external servers.
Standards Compliant: Utilizes native browser cryptographic standards (crypto.getRandomValues() and SubtleCrypto) to guarantee maximum entropy and security.
### 9.👤Author
Developed by HexSleuth (𓋹•ʰᵉˣˢˡᵉᵘᵗʰ•𓃠).
### 10.📄License
Distributed under the MIT License. See LICENSE for more information.
<FollowUp label="Want me to generate a custom configuration script or deploy guide for this repository?" query="How can I configure GitHub Pages and automate deployment for this repository?"/>
---

## 🚀 Getting Started

Because this project is a purely static, client-side web application, you can run it instantly without complex build pipelines or backend servers.

### Running Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/HexSleuth/HEX-AI-key-generator-and-converter.git](https://github.com/HexSleuth/HEX-AI-key-generator-and-converter.git)
2. Navigate into the directory:
   ```bash
   cd HEX-AI-key-generator-and-converter
   
3.Open index.html directly in any modern web browser, or serve it using a local static server:
  ```bash
  npx serve .


