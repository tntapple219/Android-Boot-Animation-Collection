# <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/23dc59cb-ae17-42ac-93ba-0f1028c966f5" />
# 𓂀  crDroid Boot Animations

This folder contains boot animations extracted from various versions of **crDroid**, the Android skin developed by crDroid.

---

## 📁 Structure

| Folder       | Description                        |
|--------------|------------------------------------|
| `v11/`    | Boot animations from crDroid v11 builds |
| `v12/`    | Boot animations from crDroid v11 builds |
| ...          | Other crDroid versions |

Each subfolder contains one or more `bootanimation.zip` files.  
If multiple styles exist, they are provided with descriptive filenames like `dark`, `light`, `alt`, etc.

---

## 📝 Resolutions

| Version       | Resolutions                       |
|---------------|-----------------------------------|
| v11           | 680x680                           |
| v12           | Multiple                          |

---

## ⚙️ Notes

- Some folders contain multiple resolutions. As such, they are named accordingly (e.g bootanimation-1080.zip). To apply, download the animation and remove
the -1080 from the filename.
- Resolution may vary depending on device model and region.
- If the animation looks distorted, edit `desc.txt` to fit your screen resolution (e.g. `1080 2340, 720 1280, 480 854`) etc.
- All content belongs to their original source: **crDroid**

---

## 📚 Sources

- v11: Extracted from crDroid 11.2 for the Nokia 6.1.
- v12: Extracted the  `.tar` files from here https://github.com/crdroidandroid/android_vendor_addons/tree/16.0/prebuilt/bootanimation , added a `desc.txt` to each animation and then repackaged the bootanimations to a `.zip` file.

---
