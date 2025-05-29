# 📱 Android Bootanimation Collection

Welcome to the **Android Bootanimation Collection** repository!  
This project is a curated collection of various `bootanimation.zip` files for Android devices.  
Whether you're a ROM developer, a theming enthusiast, or just want to spice up your phone's boot screen, this repo is for you!

---

## 📦 How to Replace Your Boot Animation

> ⚠️ *Root access or custom recovery is typically required.*

### 🔧 Method 1: Manually via File Manager (Root)
1. Download the desired `bootanimation.zip` from this repo.
2. Use a root-enabled file manager (e.g. Root Explorer, MiXplorer).
3. Navigate to:
   - `/system/media/` (for system-level boot animation) **OR**
   - `/data/local/` (for user-level override; no need to modify system files).
4. Replace the existing `bootanimation.zip` with your new one.
5. Set file permissions to `rw-r--r--` (`0644`).
6. Reboot your device and enjoy! 🚀

💡 **If the animation looks distorted or doesn't fit your screen:**  
Please open `desc.txt` inside the `.zip` and modify the resolution (e.g. `1080 2340`) to match your device.  
This is especially important for phones with unusual aspect ratios.

---

## 🧰 Tools You Might Like

Looking for tools to manage or create boot animations? Check out my other projects!

* **[Android Boot Animation Viewer](https://github.com/tntapple219/Android-Bootanimation-Viewer)**: A Python tool to easily preview `bootanimation.zip` files on your computer. No need to flash and reboot – see it instantly!
* **[ROM Extractor (sdat2img + Brotli Support)](https://github.com/tntapple219/sdat2img_brotli)**: A powerful Python script to extract and convert Android OTA update files (`.dat.br` and `.transfer.list`) into usable `.img` disk images.
* **[Original sdat2img by labrusca](https://github.com/labrusca/sdat2img)**: (Note: This is **NOT** my project.) The original Python script for converting Android system `.dat` and `.transfer.list` files to `.img` format. (Often used as a base for other tools.)
* **[payload-dumper-go](https://github.com/ssut/payload-dumper-go/tree/1.3.0)**: (Note: This is **NOT** my project.) An android OTA payload dumper written in Go.
---
## 🚀 Contributing

Want to share your own boot animation or submit one from your favorite ROM?

1. Fork this repo and create a new folder inside `animations/`.
2. Include the following in your folder:
   - `bootanimation.zip`
   - `README.md` — include at least:
     - Title
     - Resolution
     - Source or author
     - Frame rate (optional)
   - (Optional) a GIF or image preview in the `previews/` folder
3. Submit a Pull Request (PR).

**Alternatively**, you can open an Issue with:
- Download link
- Animation info
- Preview image

---

## ❌ Requesting Removal

If you're the original author or legal copyright holder of a boot animation in this repository and wish for it to be removed, please open an Issue or contact the repository maintainer.

We will remove it as soon as possible after verifying the request. 🙇

---

## ⚖️ Disclaimer & Copyright

All boot animations in this repository belong to their **original authors**, **ROM developers**, or **official Android firmware sources**.  
This project is for **educational and archival purposes only**.  
**I do not claim ownership of any boot animation file unless explicitly stated.**

If you are a content creator and see your work here without permission, please contact me — I fully respect your rights and will take action immediately.

---
