<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.47″ TFT 172×320 (GC9307 · SPI)</h1>

<p align="center"><b>TFT module · SPI · GC9307</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English</p>

<p align="center">
  <img alt="Size: 1.47 inch" src="https://img.shields.io/badge/Size-1.47%22-3498DB?style=flat-square" />
  <img alt="Resolution: 172x320" src="https://img.shields.io/badge/Resolution-172%C3%97320-8E44AD?style=flat-square" />
  <img alt="Interface: SPI" src="https://img.shields.io/badge/Interface-SPI-27AE60?style=flat-square" />
  <img alt="Driver: GC9307" src="https://img.shields.io/badge/Driver-GC9307-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.47″ 172×320 TFT SPI module (GC9307) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **1.47″ 172×320 TFT** is a **SPI** color display module driven by **GC9307**. Suited to handheld devices, narrow information bars, and compact portrait HMI.

Spec ID (repository name): `1.47-tft-172x320-spi-gc9307`

Current module version: **YDP147H009-V2**. Electrical and mechanical details follow [`docs/YDP147H009-V2.pdf`](./docs/YDP147H009-V2.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 1.47 inch |
| Type | TFT / IPS (color) |
| Resolution | 172×320 |
| Interface | SPI (4-wire) |
| Driver IC | GC9307 |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-C3 · GC9307 SPI + LVGL8 | [`examples/esp32c3-idf_gc9307_lvgl/`](./examples/esp32c3-idf_gc9307_lvgl/) |

## Repository layout

```text
1.47-tft-172x320-spi-gc9307/
├── README.md
├── README_EN.md
├── MODULE_VERSION.md
├── LICENSE
├── images/          # README assets
├── docs/            # datasheets, init
└── examples/        # sample projects
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP147H009-V2) | [`docs/YDP147H009-V2.pdf`](./docs/YDP147H009-V2.pdf) |
| Driver IC datasheet (GC9307) | [`docs/GC9307_DS_V1.01(1).pdf`](./docs/GC9307_DS_V1.01(1).pdf) |
| Init sequence (text) | [`docs/GC9307+HSD1.47(HSD015BPW2-C)_IPS_AN_VCI=3.3V_V2.txt`](./docs/GC9307+HSD1.47(HSD015BPW2-C)_IPS_AN_VCI=3.3V_V2.txt) |

### Samples

- [ESP32-C3 GC9307 SPI + LVGL8](./examples/esp32c3-idf_gc9307_lvgl/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group (China): **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository if you have any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
