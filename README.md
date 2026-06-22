# 🖥️ BenyVK CMD

> **Coming Soon** — A modern, cross-platform terminal shell built with Go.

![Status](https://img.shields.io/badge/status-coming%20soon-orange)
![Language](https://img.shields.io/badge/language-Go-00ADD8?logo=go)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-blue)
![License](https://img.shields.io/badge/license-BVK-yellow)

---

## 🚀 What is BenyVK CMD?

**BenyVK CMD** is a feature-rich, TUI-based command shell written in Go. It brings a clean, colorful terminal interface to your desktop — combining familiar shell commands with a polished, keyboard-friendly experience — and runs natively on **Windows, Linux, and macOS**.

---

## ✨ Features (Preview)

- 🎨 **Colorful TUI** — built with [tview](https://github.com/rivo/tview) for a rich terminal UI
- 📁 **Full File Management** — `ls`, `mkdir`, `rm`, `cp`, `mv`, `cat` and more
- 🖱️ **Mouse Support** — scroll through output with your mouse wheel
- 📋 **Clipboard Integration** — copy all output instantly with `Ctrl+Y` or the `clip` command
- 💽 **Drive Switching** — navigate between drives/mount points with `nd` / `nextdrive`
- 🖥️ **System Info** — built-in `sysinfo` command for a quick system overview
- ⚡ **System Command Passthrough** — run any native system command (`ping`, `ipconfig`, `top`, etc.)
- 🕐 **Timestamped History** — every command is logged with its execution time
- 🌍 **Cross-Platform** — works on Windows, Linux (reads `/proc/mounts`), and macOS (`/Volumes`)

---

## 📦 Built With

| Package | Purpose |
|---|---|
| [tview](https://github.com/rivo/tview) | Terminal UI framework |
| [tcell](https://github.com/gdamore/tcell) | Low-level terminal handling |
| [clipboard](https://github.com/atotto/clipboard) | OS clipboard access |

---

## 🗺️ Roadmap

- [ ] Initial public release
- [ ] Command history with arrow-key navigation
- [ ] Tab completion
- [ ] Theming / color customization
- [ ] Config file support
- [ ] Plugin system

---

## ⭐ Stay Tuned

Star this repo to get notified when the first release drops!

> _"Good tools deserve a good shell."_
