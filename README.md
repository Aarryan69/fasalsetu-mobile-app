# FasalSetu AI — Mandi Mobile Application
**Team AgriSetu · Delhi Technological University · SEVA FIRST 2026 (NAT-004-OP)**

An intelligent post-harvest decision-support mobile application designed for on-foot field operation at vegetable mandis across India.

🌐 **Live Web App:** [https://aarryan69.github.io/fasalsetu-mobile-app/](https://aarryan69.github.io/fasalsetu-mobile-app/)

---

## 🌟 Key Features

1. **📸 Live Camera Quality Scanner (Edge AI):**
   * Uses the phone's camera to inspect tomato crates in real time.
   * Runs an edge-optimized **MobileNetV3 ONNX model directly inside the phone's browser processor** (using WebAssembly) — zero server calls needed.
   * Grades produce into **Grade A (Fresh Retail)**, **Grade B (Processing/Puree)**, or **Subgrade (Damaged)**.

2. **🛡️ Food Safety Shield:**
   * Automated compliance gate: any lot with visible fungal decay or $<85\%$ model confidence is locked out from human-food channels and routed to organic bio-recovery (compost/biogas).
   * Spoken audio alerts (`Web Speech API`) and alert tone.

3. **⚡ Perishability Urgency Queue (P0 / P1 / P2):**
   * Real-time countdown timers sorted dynamically by spoilage rate rather than First-In, First-Out (FIFO).
   * Flags urgent batches ($<12\text{ hours}$ shelf-life) for immediate priority clearance.

4. **🚛 Smart Lot Aggregation & Pooling:**
   * Dynamic truck capacity gauge (500kg target).
   * Models shared transport bundling, achieving $+₹200$ net profit per farmer in logistics savings compared to independent pickups.

5. **📴 100% Offline Capability:**
   * Pre-cached via Service Worker. Works inside remote mandi sheds with zero cellular reception.
   * Local data persistence via `localStorage`.

6. **🇮🇳 Bilingual Interface:**
   * Instant toggle between **English** and **हिंदी (Hindi)**.

---

## 📱 How to Install on Any Phone

1. Open **[https://aarryan69.github.io/fasalsetu-mobile-app/](https://aarryan69.github.io/fasalsetu-mobile-app/)** in your mobile browser.
2. Tap **Share → "Add to Home Screen"** (iPhone Safari) or **⋮ → "Install App"** (Android Chrome).
3. The app opens full-screen like a native app and works even in Airplane Mode.
