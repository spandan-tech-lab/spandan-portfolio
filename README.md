# FlowDesk 🖥️

> **A browser-based desktop environment built from scratch with HTML, CSS and vanilla JavaScript.**

FlowDesk explores a simple question: **what if a web app behaved more like a desktop operating system?**

It combines movable and resizable windows, an app launcher, persistent notes, a system dashboard, search, keyboard controls and responsive UI into one dependency-free project.

## ✨ Highlights

- 🪟 Draggable, resizable windows with focus management
- 🚀 App launcher with live filtering
- 📊 Dynamic system dashboard prototype
- 📝 Persistent Notes powered by `localStorage`
- 📁 File-manager interface
- 🌐 Browser workspace with search handoff
- ⚙️ Personalization controls
- 🕐 Live clock and date
- ⌨️ `Ctrl/Cmd + K` launcher shortcut
- 🔔 Lightweight toast notifications
- 📱 Responsive desktop-to-mobile layout
- ♿ Keyboard-friendly controls and ARIA labels
- 📦 PWA manifest included
- 🧩 Zero external dependencies

## 🧠 Engineering focus

This project is intentionally built without a framework so the underlying browser APIs and UI mechanics stay visible.

### Interaction model

```text
User input
   ↓
Window manager
   ├── drag
   ├── resize
   ├── focus / z-index
   └── minimize / close
          ↓
      App surfaces
   ├── Dashboard
   ├── Notes
   ├── Files
   ├── Browser
   └── Settings
```

### Persistence

The Notes app stores its content locally in the browser using `localStorage`, so a refresh does not immediately wipe the workspace.

## 🛠️ Tech stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic application structure |
| CSS3 | Responsive layout, glass UI and interactions |
| Vanilla JavaScript | Window management and app behavior |
| Web Storage API | Local note persistence |
| Web App Manifest | Installable-app foundation |

## ▶️ Run locally

No package manager, build system or dependencies are required.

1. Clone the repository.
2. Open `index.html` in a modern browser.
3. Press **Ctrl/Cmd + K** to open the app launcher.
4. Drag or resize windows and try the Notes app.

## 🎯 Why I built it

I wanted a project that goes beyond a static portfolio page and demonstrates **interaction design, browser APIs, responsive UI engineering and iterative problem solving**.

The project is also an experiment in designing a desktop-class experience for the web while keeping the implementation small enough to understand from end to end.

## 🗺️ Roadmap

- [x] Draggable windows
- [x] Resizable windows
- [x] Multiple app surfaces
- [x] Persistent notes
- [x] App search
- [x] Keyboard shortcuts
- [x] Responsive layout
- [x] PWA manifest foundation
- [ ] Service worker and offline caching
- [ ] Real multi-window taskbar
- [ ] File-system integration where browser permissions allow it
- [ ] Plugin-style mini-app architecture
- [ ] Automated UI testing
- [ ] Performance profiling and optimization

## 📐 Design principles

**Originality:** FlowDesk is an original concept. It does not use Samsung proprietary branding, assets or code.

**Progressive enhancement:** Core functionality works with plain browser technologies before adding richer behavior.

**Clarity:** The UI is designed to feel familiar without reproducing another company's product interface.

## 👨‍💻 Author

**Spandan — `spandan-tech-lab`**

Student developer exploring software engineering, UI/UX and practical web development.

---

*Built as an independent student engineering project.*