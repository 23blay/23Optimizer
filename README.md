# 23 Optimizer

**Universal Windows Performance Optimizer – v1.0**  
by **23 Studios**

A powerful, all-in-one Windows tuning utility designed for gamers and power users. It offers fine-grained control over system performance, privacy, and visual effects, with a strong focus on safety through automatic restore points and built-in rollback.

---

## ✨ Key Features

- **90+ performance tweaks** across 9 categories:
  - ⚡ Power & CPU – plans, core parking, throttling
  - 🖥 GPU & Display – scheduling, TDR, VRR, flip queue
  - 🧠 RAM & Memory – SysMain, compression, paging
  - 🌐 Network – Nagle, throttling, DNS, RSS
  - 🎮 Gaming – Game Bar, Game Mode, HPET, DVR
  - 🎨 Visual & UI – animations, transparency, shadows
  - ⚙ Services – telemetry, Xbox, maps, fax
  - 🔒 Privacy & Telemetry – Cortana, advertising, feedback
  - 💾 Storage – TRIM, defrag, write caching
- **Automatic system restore point** before applying changes (Windows API + PowerShell fallback)
- **Smart compatibility checks** – WDDM version, NVIDIA/AMD GPU, service existence
- **One‑click "Apply All"** per category
- **High‑risk warnings** for potentially dangerous tweaks
- **Built‑in rollback** – every tweak saves its original state
- **Real‑time GPU & OS detection** (WDDM version, build number)
- **Modern dark UI** with customtkinter
- **License validation** to protect the tool

---

## 🚀 Getting Started

### Requirements
- Windows 10 or 11 (64‑bit)
- Administrator privileges (auto‑elevates)
- Python 3.9+ (if running from source)

### Run from source
```bash
git clone https://github.com/23blay/23Optimizer.git
cd C:\Program Files\23Optimizer
pip install customtkinter pillow
python 23.py
