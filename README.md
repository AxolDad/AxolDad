<div align="center">

# AxolDad

**CEO & Founder, Code Pause Inc.** · Rust and TypeScript systems engineer · 25-year EMT and crisis responder

Building privacy-first infrastructure for healthcare, live media, and the 63 million unpaid caregivers who form America's largest invisible workforce.

[![Portfolio](https://img.shields.io/badge/Portfolio-ioio.dev-0A66C2?style=flat-square)](https://ioio.dev)
[![Code Pause](https://img.shields.io/badge/Company-Code%20Pause%20Inc.-1F2937?style=flat-square)](https://codepause.com)
[![Voxi.Live](https://img.shields.io/badge/Product-Voxi.Live-7C3AED?style=flat-square)](https://voxi.live)
[![GitHub](https://img.shields.io/badge/GitHub-AxolDad-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AxolDad)

</div>

---

## About

I work at the intersection of clinical care, crisis response, and systems engineering, with a focus on infrastructure where the data never has to be trusted to the operator.

- **Founder and CEO of [Code Pause Inc.](https://codepause.com)**, where I lead development of **OutsideINsights**, a clinical intelligence platform that validates the observations of unpaid home health caregivers, and **[Voxi.Live](https://voxi.live)**, an avatar-driven live broadcast platform for the open web.
- **Rust systems engineer** building encrypted-first analytical infrastructure: confidential computing, envelope cryptography, and query engines that return answers without ever exposing the underlying dataset.
- **Full-stack engineer** in modern React, Bun, Hono, and PostgreSQL, with deep experience in HIPAA-compliant architecture and isolated infrastructure.
- **Space communications engineer** with **Pale Blue Systems**, applying QUIC, HTTP/3, and advanced multiplexing to space-to-ground links.
- **EMT and crisis responder for 25 years**, currently volunteering on 988 crisis lines.
- **Background in psychology and behavioral health**, which shapes how I design systems that bridge clinical rigor and human compassion.

---

## Current Work

### Encrypted-First Analytical Infrastructure · Rust
A confidential analytics platform built around a single invariant: there is no application path by which an analytics user can retrieve a plaintext dataset. Data enters encrypted, rests encrypted, is processed inside a protected execution boundary, and leaves only as authorized, disclosure-controlled results.

- Rust workspace of twelve crates with `unsafe_code = "deny"` across the board
- Client-side encryption in the browser with non-extractable keys, so the server never holds a key that decrypts user data
- Envelope-key hierarchy using HPKE (X25519, HKDF-SHA256, AES-256-GCM) with versioned framing and context binding
- Connector pipelines that decrypt only inside attested AMD SEV-SNP enclaves, then zeroize buffers after writing ciphertext
- Apache DataFusion query execution with a plan-level aggregate-only gate that rejects row dumps before they run
- Keyed blind-index columns for equality filtering over ciphertext without revealing values
- Steward-to-researcher grants with cohort suppression, monotonic query budgets, and a priced dataset catalog

### Voxi.Live · Live Broadcast
[Voxi.Live](https://voxi.live) is an avatar platform for the open web: go live as yourself, or as anyone, anywhere. It is Code Pause's first commercial surface and the proving ground for the company's privacy-first architecture at entertainment scale.

- Browser-native studio with camera, microphone, screen, guests, preview, and backstage
- Media over QUIC as the primary delivery path, with LL-HLS and destination-specific egress as fallbacks
- Ingest compatibility across browser contribution, MoQ, WHIP, and RTMPS/SRT boundary adapters
- Semantic avatars and multi-format program output from a single production
- Multi-destination delivery, unified chat and moderation, live captions and translation, and creator monetization
- Currently in alpha

### OutsideINsights · Healthcare
Clinical intelligence tools for unpaid home health caregivers, built for Medicare Advantage plans.

- VR-12-aligned continuous monitoring that validates caregiver observations
- "Better, Same, Worse" survey methodology for tracking patient trajectory
- Real-time patient outcome monitoring for Medicare Advantage payers
- TanStack ecosystem for data handling and UI
- Rhapsody Health integration for EMR connectivity

### Pale Blue Systems · Space Communications
Next-generation communications infrastructure for space applications.

- QUIC and HTTP/3 transport for low-latency, resilient space-to-ground communication
- Spatial multiplexing and spectral tensor encoding for high-bandwidth optical transmission
- DWDM optical systems and CCSDS packetization for efficient data delivery
- Riccati-based signal processing and control systems
- Network architectures designed for extreme environments

### Crisis Intervention
Peer-to-peer de-escalation tools grounded in the Taft Method, distilling 25 years of EMT and crisis counseling experience into training and technology.

### Applied AI
Fine-tuning and evaluating fast/slow model architectures for clinical intelligence systems.

---

## Technical Expertise

**Systems and backend**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Apache DataFusion](https://img.shields.io/badge/Apache%20DataFusion-D22128?style=flat-square&logo=apache&logoColor=white)
![Apache Parquet](https://img.shields.io/badge/Apache%20Parquet-50ABF1?style=flat-square&logo=apache&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Web and application**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle%20ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)

**Also working with**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Domains:** confidential computing (AMD SEV-SNP) · applied cryptography (HPKE, AES-GCM, blind indexing) · encrypted columnar storage · HIPAA-compliant system design · secure and isolated infrastructure · EMR integration · Media over QUIC and low-latency streaming · transport protocols (QUIC, HTTP/3) · optical transmission and signal processing

---

## Currently

- Building the encrypted analytics engine in Rust, from the crypto and enclave layers up through the query gate
- Shipping the Voxi.Live alpha: browser studio, Media over QUIC delivery, and the native audience experience
- Raising a funding round for OutsideINsights
- Building market intelligence on Medicare Advantage payers, including UnitedHealth, Humana, and CVS Health
- Positioning the $600B unpaid caregiver workforce as the answer to Medicare's patient-monitoring gap
- Advancing multiplexing and optical transmission work with Pale Blue Systems

---

## Beyond Engineering

- A modern adaptation of Ann Radcliffe's *The Mysteries of Udolpho*
- Rare book collecting: first editions, classics, children's literature, and signed copies
- Numismatics, with a focus on commemorative coinage
- Freshwater aquascaping
- TIG, MIG, and stick welding

---

## Contact

I welcome conversations with collaborators, investors, and anyone working on confidential computing, healthcare, live media, crisis response, or space communications.

- Portfolio: [ioio.dev](https://ioio.dev)
- Company: [codepause.com](https://codepause.com)
- Voxi.Live: [voxi.live](https://voxi.live)
- GitHub: [@AxolDad](https://github.com/AxolDad)

<div align="center">

*Build with purpose. Stay curious.*

</div>

<!---
AxolDad/AxolDad is a special repository because its README.md (this file) appears on your GitHub profile.
--->
