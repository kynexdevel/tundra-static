<div align="center">
  <h1>🏔️ Tundra Static Assets</h1>
  <p><b>Frontend infrastructure and media repository for TundraRoms.</b></p>
  
  [![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
  [![CDN](https://img.shields.io/badge/CDN-Photon_(WP)-blue?style=flat-square)](https://jetpack.com/support/site-accelerator/)
  [![Website](https://img.shields.io/badge/Site-tundraroms.pages.dev-orange?style=flat-square)](https://tundraroms.pages.dev)
</div>

---

## ⚡ Overview
This repository hosts static assets for the **TundraRoms** project. We utilize the **Photon CDN (by Automattic/WordPress)** to deliver heavily cached, on-the-fly optimized media directly from enterprise-grade edge nodes.

## ⚖️ Legal Disclaimer & Credits
TundraRoms is a **non-profit, community-driven project** made with ❤️ for the Android community. 

* **Ownership:** Most banners, logos, and screenshots used here are the intellectual property of their respective owners (Device manufacturers, ROM developers, and original artists). 
* **Fair Use:** These assets are used here for **identification and educational purposes only**, under the principles of "Fair Use". No copyright infringement is intended.
* **Removal:** If you are the owner of an asset and wish for its removal, please contact us, and we will comply immediately.

## 🛠️ Implementation
Assets are routed through the Photon proxy to strip metadata and enforce dynamic compression and format conversion for maximum performance.

**Production Endpoint:**
```text
https://i0.wp.com/raw.githubusercontent.com/kynexdevel/tundra-static/main/path/to/image.jpg?quality=90&strip=all
