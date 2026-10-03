# FunkinARM64
A port of the well-known rhythm game made by the @FunkinCrew with HaxeFlixel for Linux ARM64 and other platforms


# Friday Night Funkin' V-Slice (v0.8.6) — Linux ARM64


Official native Linux ARM64 build for **Friday Night Funkin' V-Slice**, optimized for 64-bit ARM single-board computers (like the Raspberry Pi 4/5 running a 64-bit OS), ARM Linux handhelds, and 64-bit ARM desktop environments.

---

## 📥 Downloads


* **`fnf-vslice_<version-name>_arm64.deb`** — Debian/Ubuntu package installer (Recommended)

---

## 🚀 Installation Instructions


### Method 1: Using `dpkg` (Recommended for Debian/Ubuntu-based distros)

1. Download the `.deb` file from the assets below or directly via terminal:
   ```bash
   wget [https://github.com/Miiyamoto255/FunkinARM64/releases/download/v<version-name>/fnf-vslice_<version-name>_arm64.deb](https://github.com/Miiyamoto255/FunkinARM64/releases/download/v<version-name>/fnf-vslice_<version-name>_arm64.deb)

 * Install the package using dpkg:
   sudo dpkg -i fnf-vslice_<version-name>_arm64.deb

 * Automatically resolve and install any missing system dependencies:
   sudo apt-get install -f -y

## Don't forget to replace <version-name> with the actual version!!!


📦 Dependencies & Requirements
This build relies on standard Linux multimedia and graphics runtimes. If you encounter missing library errors, ensure the following core dependencies are installed on your system:
sudo apt-get update && sudo apt-get install -y \
    libgl1 \
    libasound2 \
    libvlc5 \
    libvlccore9 \
    libpng16-16 \
    libsoundio2 \
    libvorbisfile3


🎮 How to Play
 * From your Desktop Environment: Look for Friday Night Funkin' (V-Slice) in your application launcher under the Games category.
 * From the Terminal: Simply type:
   fnf-vslice


🐛 Bug Reports & Feedback
If you encounter any graphical glitches, performance drops, or audio stuttering on your specific ARM device, please open an issue on the Issues Tracker with your device details and OS version.
