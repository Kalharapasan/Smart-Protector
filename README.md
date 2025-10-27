# Smart Protector 2019

**Smart Protector 2019** is a Windows desktop utility developed in **Visual Basic .NET (VB.NET)** designed to optimize and protect your computer.  
It provides quick and full system scans, junk cleanup, performance boost tools, and basic privacy protection.
<img width="798" height="493" alt="Capture" src="https://github.com/user-attachments/assets/158cde65-2813-4270-b408-bad622f054ca" />

---

## ⚙️ Features

- **Quick Scan:** Fast system inspection for common issues  
- **Full Check:** Deep analysis of system files and performance  
- **Cleanup Tool:** Removes temporary files and unnecessary data  
- **Speed Up Utility:** Optimizes startup and system performance  
- **Settings Panel:** Customize application behavior  
- **Modern UI:** Built with Bunifu UI Framework components  

---

## 🧰 Technologies Used

- **Language:** Visual Basic .NET (VB.NET)  
- **Framework:** .NET Framework 4.x  
- **UI Library:** [Bunifu UI v1.52](https://bunifuframework.com/)  
- **IDE:** Visual Studio 2019 (compatible with VS 2015+)  
- **Dependencies:**  
  - `Bunifu_UI_v1.52.dll`  
  - `Microsoft.VisualBasic.PowerPacks.Vs.dll`  

---

## 🗂️ Project Structure

```
Smart Protector 2019/
├── Smart Protector 2019.sln                  # Visual Studio solution
├── Smart Protector 2019/
│   ├── App.config
│   ├── Smart Protector 2019.vbproj           # VB.NET project file
│   ├── welcome.vb / scan.vb / cleanup.vb     # Forms for different modules
│   ├── settings.vb / speedup.vb              # Settings and optimization
│   ├── My Project/                           # Auto-generated VS files
│   └── bin/Debug/                            # Compiled binaries and DLLs
│       ├── Smart Protector 2019.exe
│       ├── Bunifu_UI_v1.52.dll
│       ├── Microsoft.VisualBasic.PowerPacks.Vs.dll
│       └── *.config / *.pdb / *.manifest
└── License.log                               # License information
```

---

## ▶️ How to Run

1. Open the solution file (`Smart Protector 2019.sln`) in **Visual Studio 2019 or newer**.  
2. Ensure all dependencies (especially `Bunifu_UI_v1.52.dll`) are referenced correctly.  
3. Build and run the solution (`Ctrl + F5`).  
4. The main window (`welcome.vb`) will open automatically.

---

## 🧩 Main Components

| Form Name | Function |
|------------|-----------|
| `welcome.vb` | Startup screen and app overview |
| `scan.vb` | Main scanning module |
| `quick scan.vb` | Lightweight scan form |
| `full check.vb` | Deep scan process |
| `cleanup.vb` | Removes junk and temporary files |
| `speedup.vb` | System optimization and performance tuning |
| `settings.vb` | User preferences and app configuration |
| `close.vb` | Graceful shutdown or confirmation form |

---

## 💡 Developer Notes

- The project uses the **Bunifu UI framework**, so make sure the DLL is located in the `bin/Debug` directory or added as a reference.  
- Some functionality (e.g., cleanup and speedup) may require **administrator privileges**.  
- You can modify the UI via `.Designer.vb` files and logic via `.vb` files.

---

## 🧾 License

📄 [License](./LICENSE.md): Proprietary – Permission Required

---


