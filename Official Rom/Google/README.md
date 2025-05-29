# 🌈 Google Pixel & Nexus Boot Animations

This folder contains boot animations extracted from various **Google Pixel** and **Nexus** devices.

---

## 📁 Structure

```
.
├── Pixel/
│   ├── Android 13/
│   │   └── bootanimation.zip  (e.g., dark, light, alt versions if applicable)
│   └── Android 14/
│       └── bootanimation.zip
└── Nexus/
    ├── Nexus_5X/
    │   ├── Android 6.0/
    │   │   └── bootanimation.zip
    │   └── Android 7.0/
    │       └── bootanimation.zip
    └── Nexus_6P/
        ├── Android 6.0/
        │   └── bootanimation.zip
        └── Android 7.0/
            └── bootanimation.zip
    # ...and so on for other Nexus devices like Nexus 5, Nexus 6, etc.
```

**Pixel** boot animations are grouped **solely by Android version**, reflecting their high consistency across different Pixel models within the same Android version.
**Nexus** boot animations are organized first by **device model**, then by **Android version**, to account for potential variations across different Nexus devices even on the same Android version.

Each subfolder contains one or more `bootanimation.zip` files. If multiple styles exist, they are provided with descriptive filenames like `dark` (for dark mode), `light` (for light mode), `alt` (for alternative versions), etc.

---

## ⚙️ Notes

* **Resolution** may vary depending on the device model and region.
* If the animation looks distorted, you can edit the `desc.txt` file inside the zip to match your screen resolution (e.g., `1080 2340`).
* All boot animations belong to their respective original sources: **Google Inc.**

---

### 💡 Regarding Nexus & Pixel Boot Animation Characteristics:

* **Pixel** boot animations emphasize **brand consistency**. For the same Android version, the **boot animation content is highly consistent across different Pixel models**. Files may be optimized or have variants to suit different device screen resolutions or system dark mode settings.
* **Nexus** boot animations, for the same Android version, while often sharing **primary visual elements and style**, could exhibit **minor adjustments or variations** across different Nexus device models due to their diverse hardware manufacturers.

