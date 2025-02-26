
# Windows 10 / 11 LTSC Installation & Tweaks

This guide walks you through installing Windows 11 IoT Enterprise LTSC and tweaking it using useful tools and utilities.

## 🚀 Installation Steps

### 1️⃣ Download Windows 11 IoT Enterprise LTSC  
Get the official evaluation version from Microsoft:  
1. [Windows 11 LTSC](https://www.microsoft.com/en-us/evalcenter/download-windows-11-iot-enterprise-ltsc-eval)
2. [Windows 10 LTSC](https://www.microsoft.com/en-us/evalcenter/download-windows-10-enterprise)


### 2️⃣ Install Windows 10 / 11 LTSC  

#### **Quick Installation Steps:**  
1. **Create Bootable USB** – Download **Windows LTSC ISO** & use [Rufus](https://rufus.ie/en/) to make a bootable USB.  
2. **Boot from USB** – Restart PC, enter **BIOS**, and set USB as the boot device.  
3. **Install Windows** – Select **Custom Install**, format the drive, and proceed.  
4. **Setup & Updates** – Complete the setup, install drivers, and update Windows.  

✅ **Important Notes:**  
- Backup files before installing.  
- Activation is required, but no product key is needed.  
- Once installed, **you cannot uninstall LTSC** or revert via recovery partition. A fresh OS install is needed.  
- **Failure to activate** leads to a black screen, persistent "not genuine" warnings, and hourly shutdowns.  

🚀 Done! Let me know if you need more details.

### 3️⃣ Activation  (optional and not recommanded)
Refer to the **"Activation Open Me"** file to activate your Windows installation.

---

## 🔧 Essential Tweaks & Utilities (optional)

### 4️⃣ Install Winget (Windows Package Manager)  
Winget allows you to install apps easily. Download it from:  
[GitHub - Microsoft Winget CLI](https://github.com/microsoft/winget-cli)

### 5️⃣ Apply Windows Utility Tweaks (Titus Tech Tips)  
Run the following PowerShell command to tweak your system using Chris Titus Tech’s Windows Utility:  
[Guide](https://github.com/ChrisTitusTech/winutil?tab=readme-ov-file#chris-titus-techs-windows-utility)

```powershell
irm "https://christitus.com/win" | iex
```

---

## 📦 Install Essential Apps via Winget  
Use these commands to install useful apps after setup:

```powershell
winget install 9WZDNCRFJBBG   # Windows Camera
winget install 9WZDNCRFHVN5   # Modern Calculator
winget install 9WZDNCRFJ3PR   # Windows 11 Clock
winget install 9WZDNCRFHVQM   # Modern Mail and Calendar
winget install 9WZDNCRDTBVB   # Windows Maps
winget install 9WZDNCRFJ3PT   # Modern Media Player
winget install 9WZDNCRFJ3P2   # Movies and TV
winget install 9WZDNCRFHVFW   # Microsoft News
winget install 9MSMLRH6LZF3   # Modern Notepad
winget install 9PCFS5B6T72H   # Modern Paint
winget install 9NBLGGH10PG8   # Microsoft People
winget install 9WZDNCRFJBH4   # Modern Photos App
winget install 9MZ95KL8MR0L   # Windows 11 Snipping Tool
winget install 9NBLGGH4QGHW   # Microsoft Sticky Notes
winget install 9WZDNCRFHWKN   # Windows Sound Recorder
winget install 9N0DX20HK701   # Windows Terminal
winget install 9NBLGGH5R558   # Microsoft To-Do
winget install 9MSPC6MP8FM4   # Microsoft Whiteboard
winget install 9WZDNCRFJ3Q2   # MSN Weather
```

---

## ✅ Final Notes  
- This guide ensures a minimal and efficient Windows 10 / 11 IoT setup.  
- Always check for updates and security patches.  
- Feel free to customize further with other tweaks.  

Happy tweaking! 🚀🎛️
