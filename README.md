# Caleb Kwabena Kyere Boateng

**Embedded Systems Engineering Student · Electronics & Microelectronics**

I'm a Master's student in Embedded Systems and Nanotechnology at JUNIA ISEN in Lille, coming from a Computer Science background at KNUST in Ghana. I build electronic systems end to end: circuit simulation, PCB design in KiCad, assembly and soldering, firmware, then testing and debugging until the board behaves the way the simulation said it would.

[Portfolio](https://www.kyere.tech) · [LinkedIn](https://www.linkedin.com/in/caleb-kyere-boateng) · [Email](mailto:caleb-kwabena.kyere@student.junia.com)

## Engineering projects

**[ESP32-C3 Smart USB-C Charge Controller](https://github.com/cLLeB/usb-c-charge-controller)**: a smart USB-C charge controller built around the ESP32-C3, with its own PCB and embedded firmware. C++ firmware gives wireless control over Wi-Fi and Bluetooth and takes firmware updates over the air. I designed the board in KiCad, assembled and soldered it, then tested and debugged the complete system, with Android and Windows companion apps.
*ESP32-C3 · C++ · KiCad · Wi-Fi · Bluetooth · OTA*

**[Optical Lock-In Amplifier for Photodiode Sensing](https://github.com/cLLeB/lock-in-amplifier)**: detects a modulated LED with a BPW34 photodiode despite ambient light and low frequency interference. Transimpedance amplifier, filtering and gain stages, synchronous demodulation and a low pass output, with a 1,024 Hz reference from a 32.768 kHz crystal. Simulated in LTspice and ngspice at about 0.522 mV/nA, then built on a PCB with two layers and tested: 0.00 mV with the LED covered, 362 mV with it close.
*Analog electronics · KiCad · LTspice · ngspice*

**Low Power CMOS Amplifier Design**: a transistor level analog CMOS amplifier in Cadence Virtuoso on a 45 nm process, covering the schematic, transistor sizing, biasing and simulation. It reaches 85 dB of voltage gain and 66 dB of CMRR in simulation while drawing under 70 µW.
*Cadence Virtuoso · 45 nm CMOS · Analog design*

## Software

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

## Education

- **Master's in Embedded Systems and Nanotechnology**, JUNIA ISEN, Lille, France · September 2026 to present
- **BSc Computer Science**, Kwame Nkrumah University of Science and Technology (KNUST), Ghana · 2024 to 2027

## Experience

- **Security Intern**, Information Security and Technology Assurance Division, KNUST · September to November 2025. Analysed student portal traffic in Wireshark, ran Nmap host discovery and port scans, and supported vulnerability assessment, penetration testing and security policy documentation.
- **Africa Hall Representative**, KNUST Peer Counsellors (volunteer) · September 2025 to September 2026. Supported students' emotional and psychological well-being with the KNUST Counselling Centre.

## Research

**[AFL-LightGBM: Adaptive Focal-Loss LightGBM for Mobile Money Fraud Detection in Ghana](https://github.com/cLLeB/AFL-LightGBM-MoMo-Fraud)** · [DOI 10.5281/zenodo.20838286](https://doi.org/10.5281/zenodo.20838286)  
An adaptive focal-loss objective inside LightGBM for highly imbalanced fraud data (under 0.5% fraud), with SHAP explainability aligned to Ghana's Data Protection Act. Supervised by Eric Opoku Osei (PhD), Department of Computer Science, KNUST.

## Certifications

- **Certified Network Security Practitioner (CNSP)**, The SecOps Group, Nov 2025
- **Certified Cybersecurity Educator Professional (CCEP)**, Red Team Leaders, Nov 2025
- **Network Technician Career Path**, Cisco Networking Academy, Jan 2026
- **Research Methodologies in Strategy & Product Development**, Institute of Management, Technology and Finance, Jul 2025

## Toolbox

- **Embedded systems:** ESP32-C3, Arduino, C++ firmware, Wi-Fi, Bluetooth, OTA updates
- **Electronics & hardware:** analog circuit design, CMOS design at transistor level, sensor interfaces, signal conditioning, PCB design, soldering, prototyping, hardware debugging and testing
- **EDA & simulation:** KiCad, Cadence Virtuoso, LTspice, ngspice
- **Languages:** C++, Rust, TypeScript, JavaScript, Python, Kotlin, Java
- **Frameworks:** Tauri, React, React Native, Node.js, Socket.IO, FastAPI, Spring Boot
- **Security & networking:** Wireshark, Nmap, TCP/IP, WebSocket security, biometric liveness

## Open to

Internships in embedded systems, electronic design and microelectronics, plus research collaboration.
