# Caleb Kwabena Kyere Boateng

**Software & Security Engineer · Embedded Systems**

I build software end to end: native desktop apps in Rust and TypeScript, real-time and privacy-first web systems, biometric verification, and firmware that runs on real hardware. Security runs through all of it. I design for on-device processing, zero persistence and least trust, and I'm certified in network security.

[Portfolio](https://portfolio.kyere.me) · [LinkedIn](https://www.linkedin.com/in/caleb-kyere-boateng-6736092b4) · [Email](mailto:kyereboatengcaleb@gmail.com)

## Featured work

**[Ephemeral Chat](https://github.com/1iammyself/ephemeral-chat)**: private messaging on a RAM-only server, so nothing is written to disk and there is no history to leak. End-to-end encryption built on HPKE with post-quantum ML-KEM, message size padding against traffic analysis, and optional Oblivious HTTP so the server never sees who is talking. Voice calls, video messages and synced watch parties. An Android app with screenshot blocking and root detection, and desktop apps for Windows, macOS and Linux. Around 790 commits.
*React · Node.js · Rust/WebAssembly · HPKE · Capacitor · Electron · Tauri*

**[Gear](https://github.com/cLLeB/gear)**: a native developer workbench for macOS, Linux and Windows, built around the terminal. Split terminals, a code editor with language servers, Git, a debugger, Docker and Kubernetes, a database console, an HTTP client, notebooks and 57 built-in tool panes, with AI help across all of it. Installs through Homebrew, winget, apt, rpm and Nix.
*Rust · Tauri 2 · React 19 · TypeScript*

**[Contactless Verification System](https://github.com/cLLeB/verification-system)**: proves who someone is with just a phone camera, by face or palm, with active liveness checks. It confirms a claimed identity or finds who a person is, works fully offline, and keeps only an irreversible template, never the photo. Ships as an API, an Android app and ready-made integrations for attendance, exams, clinics and welfare de-duplication. [Live](https://verify.kyere.me)
*Python · InsightFace · MediaPipe · ONNX · Android*

**[Bible App](https://github.com/cLLeB/bible-app)**: a Windows projection app for churches that catches verse references as the preacher speaks them, using Whisper on the device, ready to put on screen. Also projects songs, slides and media, with a stage display, a phone remote and projector control. Fully offline, with builds for CPU, Vulkan and CUDA.
*Rust · Tauri · React · Whisper*

**[Ephdrops](https://github.com/cLLeB/ephdrops)**: encrypted, self-destructing drops of text, images, audio or files up to 2 GB, only for the recipients you name. Content is encrypted on the device with AES-256-GCM, so the server only ever holds ciphertext and hashed usernames. Share by link, QR code, a four-word code or an `.eph` file, on the web, Windows, macOS, Linux and Android. [Live](https://beternow-ephdrops.hf.space)
*React · Node.js · Tauri · Capacitor*

**[Stegno](https://github.com/cLLeB/stegno)**: an offline steganography toolkit. Hide encrypted secrets in photos, audio, video, text or any file, with decoys, multiple recipients and secrets split across several covers. One Rust engine runs the browser (WebAssembly), desktop and native Android apps. [Live](https://stegno-omega.vercel.app)
*Rust · WebAssembly · Tauri · Kotlin*

**[UniMatch Ghana](https://github.com/cLLeB/Unimatch)**: shows WASSCE graduates every university programme they qualify for and why, and what would change it where they fall short. Cut-off point browser, what-if simulator, comparisons, an advisor answered from the data, and deadline reminders. [Live](https://unimatchgh.app)
*TypeScript · React · PostgreSQL*

**[Smart Socket](https://github.com/cLLeB/embedded-system)**: an Arduino socket that watches a charger's current, cuts mains power once the device is full so it never trickle-charges, and schedules around time-of-use tariffs. Running on real 230 V with 123 tests passing, and controlled over Bluetooth from Android and desktop apps. Built with a team of ten.
*C++ · Arduino · Bluetooth LE · Android*

**[Sidepage](https://github.com/cLLeB/sidepage)**: a reader for books, documents and slide decks with notes, drawings and mind maps beside the page, plus study tools such as highlights, read-along and teach-it-back.
*TypeScript · JavaScript*

**Looply**, a mobile financial and food delivery platform, took 1st runner-up at KNUST CodeFest '25. I was the principal frontend developer ([source](https://github.com/cLLeB/HubtelClone-Public)).

## Research

**[AFL-LightGBM: Adaptive Focal-Loss LightGBM for Mobile Money Fraud Detection in Ghana](https://github.com/cLLeB/AFL-LightGBM-MoMo-Fraud)** · [DOI 10.5281/zenodo.20838286](https://doi.org/10.5281/zenodo.20838286)  
An adaptive focal-loss objective inside LightGBM for highly imbalanced fraud data (under 0.5% fraud), with SHAP explainability aligned to Ghana's Data Protection Act. Supervised by Eric Opoku Osei (PhD), Department of Computer Science, KNUST.

## Certifications

- **Certified Network Security Practitioner (CNSP)**, The SecOps Group, Nov 2025
- **Certified Cybersecurity Educator Professional (CCEP)**, Red Team Leaders, Nov 2025
- **Network Technician Career Path**, Cisco Networking Academy, Jan 2025
- **Research Methodologies in Strategy & Product Development**, Institute of Management, Technology and Finance, Jul 2025

## Toolbox

- **Languages:** Rust, TypeScript, JavaScript, Python, C++, Kotlin, Java
- **Frameworks:** Tauri, React, React Native, Node.js, Socket.IO, FastAPI, Spring Boot
- **Security & networking:** Wireshark, Nmap, TCP/IP, WebSocket security, biometric liveness
- **Hardware:** Arduino, mains power control, sensor-driven firmware

## Open to

Internships and entry-level roles in software engineering, security or embedded systems, plus research collaboration.
