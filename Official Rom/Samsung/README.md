# 🌈 Samsung Boot Animations

This folder contains boot animations extracted from various **Samsung Galaxy** devices.

---

## 📁 Structure

```
.
├── OneUI/
│   ├── OneUI 6.0/
│   │   ├── bootsamsung.qmg
│   │   └── bootsamsungloop.qmg
│   ├── OneUI 5.0/
│   │   ├── bootsamsung.qmg
│   │   └── bootsamsungloop.qmg
│   └── OneUI 4.0/
│       ├── bootsamsung.qmg
│       └── bootsamsungloop.qmg
│   # ...and so on for other OneUI versions like OneUI 3.x, etc.
└── TouchWiz/
    ├── TouchWiz Nature UX/
    │   ├── Android 4.0.4/
    │   │   ├── bootsamsung.qmg
    │   │   └── bootsamsungloop.qmg
    │   ├── Android 4.1.2/
    │   │   ├── bootsamsung.qmg
    │   │   └── bootsamsungloop.qmg
    │   └── Android 4.3/
    │       ├── bootsamsung.qmg
    │       └── bootsamsungloop.qmg
    # ...and so on for other TouchWiz versions like TouchWiz 4.0, etc.
```

**One UI** boot animations are grouped **solely by One UI version**, as their design is highly consistent across different Samsung models running the same One UI iteration.
**TouchWiz** boot animations are organized first by **TouchWiz version (e.g., Nature UX)**, then by **Android version**, to account for the evolution of the UI across different underlying Android builds.

Each subfolder contains one or more `.qmg` files.

---

## ⚙️ Notes

* **File Format & Conversion Challenge:** All boot animations in this collection are in **Samsung's proprietary `.qmg` (Quick Mobile Graphics) format**. I've **attempted various methods to convert these `.qmg` files into standard `bootanimation.zip` format (e.g., by extracting PNG sequences), but these attempts have been unsuccessful.** Due to their proprietary nature and the lack of widely available, reliable conversion tools, these files remain in their original `.qmg` state.
* **Resolution** may vary significantly depending on the device model and regional firmware.
* All boot animations belong to their respective original sources: **Samsung Electronics Co., Ltd.**

---

### 💡 Regarding Samsung Boot Animation Characteristics:

* **Samsung's Unique Approach:** Unlike most Android devices that use the standard `bootanimation.zip` for animated bootscreens, Samsung extensively uses its custom `.qmg` files. These files are typically composed of two parts: `bootsamsung.qmg` for the initial animation and `bootsamsungloop.qmg` for the looping animation until the system fully loads.
* **Consistency within Versions:** Boot animations are highly consistent across devices running the same **One UI version**, reflecting Samsung's unified design language.
* **Evolution of TouchWiz:** In the older **TouchWiz** era, while the general style (`Nature UX`, `TouchWiz 4.0`, etc.) was a primary identifier, minor variations could exist across device models or Android versions, often due to hardware capabilities or specific Android feature implementations.