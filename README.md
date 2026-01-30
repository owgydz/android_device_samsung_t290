# Device Tree for Samsung Galaxy Tab A 8.0 (2019)

This repository contains the Android device configuration for the **Samsung Galaxy Tab A 8.0 (2019)**.

It is intended for use with **AOSP-based custom ROMs** (such as LineageOS) and was generated directly from **stock Samsung firmware**.

---

## Device Information

| Item | Details |
|-----|--------|
| Device | Samsung Galaxy Tab A 8.0 (2019) |
| Model | SM-T290 |
| Codename | t290 |
| SoC | Qualcomm Snapdragon 429 (SDM429) |
| CPU | Quad-core ARM Cortex-A53 |
| GPU | Adreno 504 |
| Architecture | arm64 |
| Manufacturer | Samsung |

---

## Extraction Methodology

All hardware values, partition sizes, and proprietary blobs were extracted directly from official Samsung firmware:

- Firmware source: Samsung stock ROM (`.tar.md5`)
- Images inspected: `boot`, `system`, `vendor`
- No values were copied from other devices
- No placeholders or guessed values

This ensures accuracy and reproducibility.

---

## Status

- [x] Firmware extraction
- [x] Device tree skeleton
- [x] Proprietary blob list (initial)
- [ ] Vendor tree generation
- [ ] Kernel source integration
- [ ] Bootable recovery
- [ ] ROM build

This device tree is **work in progress** and **not official**.

---

## Disclaimer

This repository is provided for **development and educational purposes** only.

- I am **not affiliated with Samsung**
- I am **not claiming LineageOS official support**
- Flashing custom software may **void warranties** or **brick devices**
- Use at your own risk

---

## Credits

- LineageOS Project  
- Android Open Source Project (AOSP)  
- Samsung (original firmware)

