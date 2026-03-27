# Software Tools

The following tools are referenced throughout the *Digital Forensics Cookbook*. Each tool is listed with its maintainer, classification, and primary investigative purpose.

## ⭐ Core Toolkit (Recommended Starting Point)

The following tools represent a practical baseline for performing the majority of digital forensic tasks covered in this book:

- **FTK Imager** → Evidence acquisition and triage  
- **Autopsy** → Primary forensic analysis platform  
- **Volatility 3** → Memory forensics analysis
- **DB Browser for SQLite** → Database analysis  
- **HxD** → Hex-level validation and data inspection  

---

## 🔍 Tool Classification

- **Commercial** → Developed and maintained by a company  
- **Open-source (Organization)** → Community-driven or foundation-backed  
- **Open-source (Individual)** → Maintained primarily by a single developer  
- **Freeware** → Free to use but not open-source  

> [!TIP]
> Hold the **CTRL** key when clicking links to open them in a new tab

---

## 💾 Acquisition & Imaging

### [FTK Imager](https://go.exterro.com/l/43312/2023-05-03/fc4b78)
**Type:** Commercial  
**Maintainer:** Exterro  
**Purpose:** Evidence triage, acquisition, exporting, and analysis  

### [Magnet ACQUIRE](https://www.magnetforensics.com/resources/magnet-acquire/)
**Type:** Commercial  
**Maintainer:** Magnet Forensics  
**Purpose:** Digital evidence acquisition for storage media and mobile devices (*Requires business e-mail)  

### [Live RAM Capturer](https://belkasoft.com/trial)
**Type:** Commercial  
**Maintainer:** Belkasoft  
**Purpose:** RAM acquisition from a live Microsoft Windows system  

### [RAM Capture](https://www.magnetforensics.com/resources/magnet-ram-capture/)
**Type:** Commercial  
**Maintainer:** Magnet Forensics  
**Purpose:** RAM acquisition from a live Microsoft Windows system  

### [UFADE](https://github.com/prosch88/UFADE/releases)
**Type:** Open-source (Individual)  
**Maintainer:** prosch88  
**Purpose:** Apple iOS forensic acquisition  

---

## 🧠 Analysis & Parsing

### [Autopsy](https://www.autopsy.com/download/)
**Type:** Open-source (Organization)  
**Maintainer:** Sleuth Kit Labs  
**Purpose:** Digital forensic analysis suite  

### [Velociraptor](https://github.com/Velocidex/velociraptor/releases/)
**Type:** Open-source (Organization)  
**Maintainer:** Rapid7 (originally developed by Mike Cohen)  
**Purpose:** Scaled endpoint monitoring and DFIR data collection  

### [Volatility 3](https://github.com/volatilityfoundation/volatility3/releases)
**Type:** Open-source (Organization)  
**Maintainer:** Volatility Foundation  
**Purpose:** Memory forensics analysis for Windows, Linux, and macOS  

### [mac_apt](https://github.com/ydkhatri/mac_apt/releases)
**Type:** Open-source (Individual)  
**Maintainer:** Yogesh Khatri  
**Purpose:** Apple macOS artifact parsing and analysis  

### [iLEAPP](https://github.com/abrignoni/iLEAPP/releases/)
**Type:** Open-source (Individual)  
**Maintainer:** Alexis Brignoni  
**Purpose:** Automated parsing of acquired data from Apple iOS devices  

### [aLEAPP](https://github.com/abrignoni/aLEAPP/releases/)
**Type:** Open-source (Individual)  
**Maintainer:** Alexis Brignoni  
**Purpose:** Automated parsing of acquired data from Android devices  

### [Bulk Extractor](https://github.com/simsong/bulk_extractor/wiki/Installing-bulk_extractor)
**Type:** Open-source (Individual)  
**Maintainer:** Simson L. Garfinkel  
**Purpose:** Bulk data carving and artifact extraction  

### [KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape)
**Type:** Commercial  
**Maintainer:** Kroll (developed by Eric Zimmerman)  
**Purpose:** Triage and data collection from live Microsoft Windows systems  

### [gMetaDataParse](https://github.com/00010111/gMetaDataParse)
**Type:** Open-source (Individual)  
**Maintainer:** Graham Sutherland  
**Purpose:** Google Drive metadata extraction and analysis  

### [Plaso / log2timeline](https://github.com/log2timeline/plaso/releases)
**Type:** Open-source (Organization)  
**Maintainer:** Plaso Team  
**Purpose:** Timeline generation and event correlation  

---

## 📦 Artifact-Specific Tools

### [FSEventsParser](https://github.com/dlcowen/FSEventsParser/releases/)
**Type:** Open-source (Individual)  
**Maintainer:** David Cowen  
**Purpose:** Parser for Apple macOS file system event logs  

### [Thumbcache Viewer](https://thumbcacheviewer.github.io/)
**Type:** Open-source (Individual)  
**Maintainer:** Eric Kutcher  
**Purpose:** Parser for Microsoft Windows thumbcache databases  

### [ChromeCacheView](http://www.nirsoft.net/utils/chrome_cache_view.html)
**Type:** Freeware  
**Maintainer:** NirSoft  
**Purpose:** Parser for Google Chrome and Chromium browser cache  

### [MZCacheView](http://www.nirsoft.net/utils/mozilla_cache_viewer.html)
**Type:** Freeware  
**Maintainer:** NirSoft  
**Purpose:** Parser for Mozilla Firefox browser cache  

---

## 🛠️ Utilities & Supporting Tools

### [HxD](https://mh-nexus.de/en/hxd/)
**Type:** Freeware  
**Maintainer:** Maël Hörz  
**Purpose:** Hex-level viewing, editing, and data validation  

### [Notepad++](https://notepad-plus-plus.org/downloads/)
**Type:** Open-source (Organization)  
**Maintainer:** Don Ho & contributors  
**Purpose:** Advanced text editor with plugin support  

### [DB Browser for SQLite](https://sqlitebrowser.org/dl/)
**Type:** Open-source (Organization)  
**Maintainer:** SQLiteBrowser Team  
**Purpose:** SQLite database examination and queries  

### [EXIFTool](https://exiftool.org/index.html)
**Type:** Open-source (Individual)  
**Maintainer:** Phil Harvey  
**Purpose:** Metadata extraction and analysis  

### [DCode](https://www.digital-detective.net/dcode/)
**Type:** Freeware  
**Maintainer:** Digital Detective  
**Purpose:** Convert epoch timestamps to human-readable formats  

### [IrfanView](https://www.irfanview.com/main_download_engl.htm)
**Type:** Freeware  
**Maintainer:** Irfan Skiljan  
**Purpose:** Image viewing with metadata and GPS support  

---

## 🌐 System & Network Tools

### [Android SDK Platform Tools](https://developer.android.com/tools/releases/platform-tools)
**Type:** Open-source (Organization)  
**Maintainer:** Google  
**Purpose:** Android device communication, debugging, and acquisition support  

### [Fing Desktop](https://www.fing.com/fing-desktop/)
**Type:** Commercial  
**Maintainer:** Fing  
**Purpose:** Network scanning and device identification  

---

## 🔐 Security & Password Tools

### [John the Ripper](https://www.openwall.com/john/)
**Type:** Open-source (Organization)  
**Maintainer:** Openwall  
**Purpose:** Password recovery and auditing  

### [SecLists](https://github.com/danielmiessler/SecLists)
**Type:** Open-source (Individual)  
**Maintainer:** Daniel Miessler  
**Purpose:** Collection of security and wordlist datasets  

---

## 💽 Disk & Boot Utilities

### [Active@ KillDisk](https://www.killdisk.com/killdisk-freeware.htm)
**Type:** Commercial  
**Maintainer:** LSoft Technologies  
**Purpose:** Storage drive sanitization  

### [Arsenal Image Mounter](https://arsenalrecon.com/downloads)
**Type:** Commercial  
**Maintainer:** Arsenal Recon  
**Purpose:** Mounting disk images and volume shadow copies  

### [Paladin LTS](https://sumuri.com/product/paladin-lts/)
**Type:** Commercial  
**Maintainer:** Sumuri  
**Purpose:** Bootable forensic OS for triage and acquisition  

### [Rufus](https://rufus.ie/en/)
**Type:** Open-source (Individual)  
**Maintainer:** Pete Batard  
**Purpose:** Create bootable USB devices  

---

## 📁 File & Email Viewers

### [EML Viewer](https://www.systoolsgroup.com/eml-viewer.html)
**Type:** Freeware  
**Maintainer:** SysTools  
**Purpose:** EML email viewing and analysis  

### [MSG Viewer](https://www.systoolsgroup.com/msg-viewer.html)
**Type:** Freeware  
**Maintainer:** SysTools  
**Purpose:** MSG email viewing and analysis  

### [MBOX Viewer](https://www.systoolsgroup.com/mbox-viewer.html)
**Type:** Freeware  
**Maintainer:** SysTools  
**Purpose:** MBOX email viewing and analysis  

---

## ⚙️ Specialized Tools

### [Forensic7z](https://www.tc4shell.com/en/7zip/forensic7z/)
**Type:** Freeware  
**Maintainer:** Thomas Diot  
**Purpose:** Forensic image browsing plugin for 7-Zip  

### [Encrypted Disk Detector](https://www.magnetforensics.com/resources/encrypted-disk-detector/)
**Type:** Commercial  
**Maintainer:** Magnet Forensics  
**Purpose:** Detect encrypted drives on a live system  

### [Event Log Explorer](https://eventlogxp.com/)
**Type:** Commercial  
**Maintainer:** FSPro Labs  
**Purpose:** View and analyze Windows Event Logs  

### [Sigcheck](https://learn.microsoft.com/en-us/sysinternals/downloads/sigcheck)
**Type:** Freeware  
**Maintainer:** Microsoft Sysinternals  
**Purpose:** File signature verification and metadata inspection  

### [USB Write Blocker](https://github.com/digitalsleuth/Registry-Write-Block)
**Type:** Open-source (Individual)  
**Maintainer:** Digital Sleuth  
**Purpose:** Registry-based USB write-blocking  

### [XPlist](https://github.com/ic005k/Xplist/releases)
**Type:** Open-source (Individual)  
**Maintainer:** ic005k  
**Purpose:** Viewer for Apple property list (.plist) files  

### [Z-Tools](https://ericzimmerman.github.io/#!index.md)
**Type:** Freeware  
**Maintainer:** Eric Zimmerman  
**Purpose:** Collection of tools for Windows artifact analysis  

---

## ⭐ Additional Recommended Tools

The following tools are not explicitly required for the exercises in this book but are commonly used in digital forensic investigations and may provide additional capabilities.

### [LiME](https://github.com/504ensicsLabs/LiME)
**Type:** Open-source (Organization)  
**Maintainer:** 504ensics Labs  
**Purpose:** Linux memory acquisition  

### [WinPmem](https://github.com/Velocidex/WinPmem)
**Type:** Open-source (Organization)  
**Maintainer:** Velocidex  
**Purpose:** Windows memory acquisition  

### [The Sleuth Kit (TSK)](https://www.sleuthkit.org/)
**Type:** Open-source (Organization)  
**Maintainer:** Sleuth Kit Labs  
**Purpose:** Low-level disk and file system analysis  

### [Wireshark](https://www.wireshark.org/download.html)
**Type:** Open-source (Organization)  
**Maintainer:** Wireshark Foundation  
**Purpose:** Network traffic capture and analysis  

### [Chainsaw](https://github.com/WithSecureLabs/chainsaw)
**Type:** Open-source (Organization)  
**Maintainer:** WithSecure Labs  
**Purpose:** Fast artifact triage and log analysis  

### [libimobiledevice](https://libimobiledevice.org/)
**Type:** Open-source (Organization)  
**Maintainer:** libimobiledevice Project  
**Purpose:** iOS device communication and data access (cross-platform)
