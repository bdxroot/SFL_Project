# 🧵 Cutting & OC Planning Tool — Sewtech Fashion Limited

An elegant, fast, and responsive web-based utility tool built specially for the **Cutting Department** at **Sewtech Fashion Limited**. This tool helps production managers, planners, and operators quickly look up Style Codes, view registered Order Contract (OC) badges, and inspect the Bill of Materials (BOM) components (including PDM and Trackwel codes) in real-time.

---

## 🌐 Live Project Link

You can access and test the deployed version of the application directly here:
👉 **[Live Demo — Cutting & OC Planning Tool](https://bdxroot.github.io/SFL_Project/)**

---

## ✨ Features


* **🔍 Instant Search/Filter:** Filter complex Style Codes instantly as you type.
* **📊 Complete BOM Overview:** Organized, clean tables highlighting Component Names, PDM Codes, and Trackwel Trackings.
* **📱 Fully Responsive:** Adaptive split-screen layout for desktops and an optimized scrollable layout for mobile devices.

---

## 🛠️ Code Structure

The project is packed as a self-contained single-page application (SPA) to ensure lightning-fast loads and zero server dependency.

```html
├── index.html        # Main HTML structure
├── css (embedded)    # Custom CSS with responsive breakdowns and keyframe animations
└── js (embedded)     # In-memory datasets (Style Matrix & BOM Dictionary) and DOM handlers
