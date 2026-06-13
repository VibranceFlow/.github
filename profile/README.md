# 🌊 Welcome to the VibranceFlow Ecosystem

VibranceFlow is a modern, ultra-lightweight, and 100% open-source alternative to vibranceGUI. It is designed to automate and control your PC's display settings (Digital Vibrance, Gamma, Brightness) seamlessly, with a Zero-Trust architecture and a mobile-first remote control experience.

🌐 **[Official Website & Downloads](https://vibranceflow.vercel.app/)** · Latest release: **v1.1.0** (Windows `.exe` + 5 Android APKs)

---

### 📦 Our Repositories

The VibranceFlow architecture is split into three main modules:

* 🖥️ **[VibranceFlow-core](https://github.com/VibranceFlow/VibranceFlow-core)**
  The heart of the application for Windows. Handles background process monitoring and native Win32/NVAPI display calls with 0% CPU usage. Hosts the local WebSocket server.
  
* 📱 **[VibranceFlow-mobile](https://github.com/VibranceFlow/VibranceFlow-mobile)**
  The companion app for Android/iOS. Pairs via a local QR Code to control your PC's display settings on the fly without ever alt-tabbing out of your games.

* 🕸️ **[VibranceFlow-web](https://github.com/VibranceFlow/VibranceFlow-web)**
  The official landing page, built with Astro and Tailwind CSS for maximum speed and SEO performance.

---

### 🛡️ Security First

As a project built with a strict security mindset:
- **Zero Telemetry:** We do not track, collect, or send any analytics.
- **Local Network Only:** The mobile app communicates directly with the PC via local Wi-Fi. No cloud servers or accounts are required.
- **Transparent CI/CD:** Our release binaries (`.exe` and `.apk`) are built directly via GitHub Actions from the source code.

---

### ☕ Support the Development

To keep this project 100% free and to help us purchase official Developer Code Signing Certificates (to remove antivirus false positives), consider supporting the project:

👉 **[Support on Ko-fi](https://ko-fi.com/fabio_monreal)**

*Contributions, bug reports, and feature requests are always welcome in their respective repositories!*
