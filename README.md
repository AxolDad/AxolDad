<div align="center">

# AxolDad

**CEO & Founder, Code Pause Inc.** · Rust and TypeScript systems engineer · 25-year EMT and crisis responder

Building privacy-first infrastructure for clinical care teams, live media, and confidential analytics.

[![OutsideINsights](https://img.shields.io/badge/Product-OutsideINsights-0E7C86?style=flat-square)](https://outsideinsights.health)
[![Voxi.Live](https://img.shields.io/badge/Product-Voxi.Live-7C3AED?style=flat-square)](https://voxi.live)
[![Code Pause](https://img.shields.io/badge/Company-Code%20Pause%20Inc.-1F2937?style=flat-square)](https://codepause.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-ioio.dev-0A66C2?style=flat-square)](https://ioio.dev)
[![GitHub](https://img.shields.io/badge/GitHub-AxolDad-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AxolDad)

</div>

---

## About

I work at the intersection of clinical care, crisis response, and systems engineering, with a focus on infrastructure where the data never has to be trusted to the operator.

- **Founder and CEO of [Code Pause Inc.](https://codepause.com)**, building **[OutsideINsights](https://outsideinsights.health)**, clinical intelligence for care teams, and **[Voxi.Live](https://voxi.live)**, an avatar-driven live broadcast platform for the open web.
- **Rust systems engineer** building encrypted-first analytical infrastructure: confidential computing, envelope cryptography, and query engines that return answers without exposing the dataset.
- **Full-stack engineer** in React, Bun, Hono, and PostgreSQL, with deep experience in HIPAA-compliant architecture and isolated infrastructure.
- **Space communications engineer** with **Pale Blue Systems**, applying QUIC, HTTP/3, and advanced multiplexing to space-to-ground links.
- **EMT and crisis responder for 25 years**, currently volunteering on 988 crisis lines.
- **Background in psychology and behavioral health**, which shapes how I design systems that bridge clinical rigor and human compassion.

---

## Current Work

### [OutsideINsights](https://outsideinsights.health) · Clinical Intelligence
*What happens outside the visit belongs inside the record.*

- Clinical intelligence for care teams: connected-device data plus home context, delivered into the chart
- EHR-native integration with Epic, Oracle Health, and athenahealth, no new login required
- FDA-cleared monitoring devices, no home internet required
- Capture → Validate → Integrate pipeline with VR-12-aligned continuous monitoring
- Care Circle: "Better, Same, Worse" check-ins by text or app from the patient's care circle
- OUTsights Gateway for device and EMR connectivity, including Rhapsody Health
- Outcome monitoring for Medicare Advantage plans and payers

### Encrypted-First Analytical Infrastructure · Rust
*Data goes in. Analysis comes out. The dataset doesn't.*

- No-plaintext invariant: no application path returns an unrestricted dataset
- Rust workspace of twelve crates, `unsafe_code = "deny"`
- Client-side encryption with non-extractable browser keys
- HPKE envelope-key hierarchy (X25519, HKDF-SHA256, AES-256-GCM) with context binding
- Attested AMD SEV-SNP enclaves for connector pipelines, buffers zeroized after write
- Apache DataFusion with a plan-level aggregate-only gate
- Keyed blind indexes for equality filters over ciphertext
- Steward-to-researcher grants: cohort suppression, monotonic query budgets, priced catalog

### [Voxi.Live](https://voxi.live) · Live Broadcast
*Go live as you. Or anyone. Anywhere.*

- Avatar platform for the open web, currently in alpha
- Browser-native studio: camera, microphone, screen, guests, preview, backstage
- Media over QUIC primary delivery with LL-HLS fallback
- Ingest via browser contribution, MoQ, WHIP, and RTMPS/SRT adapters
- Semantic avatars and multi-format output from one production
- Multi-destination delivery, unified chat and moderation, live captions and translation

### Pale Blue Systems · Space Communications

- QUIC and HTTP/3 transport for space-to-ground links
- Spatial multiplexing and spectral tensor encoding for optical transmission
- DWDM optical systems and CCSDS packetization
- Riccati-based signal processing and control
- Network architectures for extreme environments

### Crisis Intervention

- Peer-to-peer de-escalation tools grounded in the Taft Method
- 25 years of EMT and crisis counseling experience, distilled into training and technology

### Applied AI

- Fine-tuning and evaluation of fast/slow model architectures for clinical intelligence

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

**Domains:** confidential computing (AMD SEV-SNP) · applied cryptography (HPKE, AES-GCM, blind indexing) · encrypted columnar storage · HIPAA-compliant system design · secure and isolated infrastructure · EHR and EMR integration · Media over QUIC and low-latency streaming · transport protocols (QUIC, HTTP/3) · optical transmission and signal processing

---

## Currently

- Building the encrypted analytics engine in Rust, from the crypto and enclave layers up through the query gate
- Shipping the Voxi.Live alpha: browser studio, Media over QUIC delivery, and the native audience experience
- Raising a funding round for OutsideINsights
- Building market intelligence on Medicare Advantage payers, including UnitedHealth, Humana, and CVS Health
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

- OutsideINsights: [outsideinsights.health](https://outsideinsights.health)
- Voxi.Live: [voxi.live](https://voxi.live)
- Company: [codepause.com](https://codepause.com)
- Portfolio: [ioio.dev](https://ioio.dev)
- GitHub: [@AxolDad](https://github.com/AxolDad)

<div align="center">

*Build with purpose. Stay curious.*

</div>

<!---
AxolDad/AxolDad is a special repository because its README.md (this file) appears on your GitHub profile.
--->
