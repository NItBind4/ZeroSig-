# ZeroSig-# ZeroSig — *Silence is Security*

> Privacy is not a privilege. It's a right.  
> Built for whistleblowers, journalists, and digital ghosts.  
> Engineered by **Nicolo Binda** | Code by Jake // CODE 🥷

---

## What is ZeroSig?

ZeroSig is a cross-platform, stealth-grade, paranoid-mode-ready personal defense suite.  
It monitors your network, logs every IP that touches you, sets bait (honeypots), wipes your logs with a keystroke, and can upload your data through encrypted Tor channels — all while hiding in plain sight.

**ZeroSig is not antivirus. It's anti-detection.**

---

## Core Features

- **Real-time IP monitoring**  
- **Honeypot trap on port 8088** — bait & autoblock
- **Cross-platform firewall blocking** (Linux + Windows)
- **Encrypted local log storage**
- **Stealth mode** — no console, disguised process
- **Panic hotkey** — Ctrl+Alt+Shift+Z = total log wipe
- **Metadata scrubber** — scans images, PDFs, videos
- **Tor-ready log uploader (stubbed, Elite Tier)**
- **GUI available** — launch via `zerosig_gui.py`
- **Docker container ready**
- **GitHub Pages landing site auto-deploys**

---

## Installation

```bash
git clone https://github.com/nicolobinda/zerosig.git
cd zerosig
pip install -r requirements.txt
python3 zerosig.py
