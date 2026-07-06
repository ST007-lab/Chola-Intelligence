# CHOLA Intelligence Platform v1.4

CHOLA is a responsive, high-fidelity flagship AI workspace interface configured for contextual text conversations, deep multi-modal document analysis, and native AI image generation pipelines. 

Built with an elegant dark-theme design layout (and a daytime toggle option), CHOLA features a cross-chat persistent memory layer and an integrated canvas downloader for media workflows.

## 🚀 Key Features

- **Dual Interaction Modalities:** Supports seamless text/document processing via Llama-4 or direct image generation utilizing the FLUX rendering cluster via Pollinations AI.
- **High-Fidelity PDF Parsing:** Embedded structural matrix text extraction via viewport text-node layer analysis (powered by `PDF.js`), bypassing standard web-scraping limitations.
- **Cross-Conversational Memory Bank:** Localized persistent context metrics track cross-chat background metrics sequentially.
- **Real-Time Knowledge Expansion:** Instant contextual feed fetching integrated natively through open-namespace search API fallbacks (e.g., Wikipedia).
- **Dual Language Architecture:** Dynamic interface transformation switching between comprehensive English and localized Tamil (தமிழ்) UI rules.

---

## 🛠️ Tech Stack & Dependencies

- **Frontend Core:** Pure HTML5, CSS3 Custom Properties (CSS variables), and asynchronous vanilla JavaScript.
- **Typography Matrix Processing:** [PDF.js v3.4.120](https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.4.120/pdf.min.js) (Cloudflare CDN distribution).
- **Core LLM Orchestration:** `meta-llama/llama-4-scout-17b-16e-instruct` hosted via Groq Cloud API endpoints.
- **Media Engine:** FLUX-1 architecture layers provided by Pollinations AI.

---

## 💻 Local Setup & Deployment

Since CHOLA is entirely self-contained within an asynchronous client-side structure, it does not require an active Node.js server to deploy locally.
