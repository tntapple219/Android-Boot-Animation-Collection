# <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/e616dbdc-d838-4249-8e98-79af324b584d" />

# ⬆️ ArrowOS Boot Animations

This folder contains boot animations extracted from various versions of **ArrowOS**, the Android skin developed by ArrowOS.

---

## 📁 Structure

| Folder       | Description                        |
|--------------|------------------------------------|
| `v9.0/`    | Boot animations from ArrowOS v9.x builds |
| `v13.1`    | Boot animations from ArrowOS v13.1 builds |
| ...          | Other ArrowOS versions |

Each subfolder contains one or more `bootanimation.zip` files.  
If multiple styles exist, they are provided with descriptive filenames like `dark`, `light`, `alt`, etc.

---

## 📝 Resolutions

| Version       | Resolution                        |
|---------------|-----------------------------------|
| v9.0          | 1080x1920                         |
| v13.1         | Multiple                          |
---

## ⚙️ Notes

- Some folders contain multiple resolutions. As such, they are named accordingly (e.g `bootanimation-1080.zip`). To apply, download the animation and remove
  the **-1080** from the filename.
- Resolution may vary depending on device model and region.
- If the animation looks distorted, edit `desc.txt` to fit your screen resolution (e.g. `1080 2340, 720 1280, 480 854`) etc.
- All content belongs to their original source: **ArrowOS**

---

## 📚 Sources
- v9.0: Extracted from ArrowOS v9.0 for the Moto G4 Plus https://xdaforums.com/t/rom-eol-9-0-arm64-official-arrowos-9-x.3859849/
- v13.1: Copied from https://github.com/ArrowOS/android_vendor_arrow/tree/8623df9497f3dab1869c4f1e56e055d30756dce4/prebuilt/common/bootanimation
