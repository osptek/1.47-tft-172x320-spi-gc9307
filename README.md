<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.47″ TFT 172×320（GC9307 · SPI）</h1>

<p align="center"><b>TFT 模组 · SPI · GC9307</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文</p>

<p align="center">
  <img alt="Size: 1.47 inch" src="https://img.shields.io/badge/Size-1.47%22-3498DB?style=flat-square" />
  <img alt="Resolution: 172x320" src="https://img.shields.io/badge/Resolution-172%C3%97320-8E44AD?style=flat-square" />
  <img alt="Interface: SPI" src="https://img.shields.io/badge/Interface-SPI-27AE60?style=flat-square" />
  <img alt="Driver: GC9307" src="https://img.shields.io/badge/Driver-GC9307-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.47 寸 172×320 TFT SPI 模组（GC9307）宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [产品简介](#产品简介)
- [规格参数](#规格参数)
- [示例工程](#示例工程)
- [仓库结构](#仓库结构)
- [相关资料](#相关资料)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 产品简介

OSPTEK **1.47 寸 172×320 TFT** 是一款 **SPI** 接口彩色显示模组，显示驱动为 **GC9307**。适合手持终端、窄条信息显示与小型竖屏 HMI 等场景。

规格标识（仓库名）：`1.47-tft-172x320-spi-gc9307`

当前模组版本：**YDP147H009-V2**。电气与外形细节以 [`docs/YDP147H009-V2.pdf`](./docs/YDP147H009-V2.pdf) 为准。

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 1.47 英寸 |
| 类型 | TFT / IPS（彩色） |
| 分辨率 | 172×320 |
| 接口 | SPI（4-wire） |
| 驱动 IC | GC9307 |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 示例工程

| 说明 | 路径 |
| ---- | ---- |
| ESP32-C3 · GC9307 SPI + LVGL8 | [`examples/esp32c3-idf_gc9307_lvgl/`](./examples/esp32c3-idf_gc9307_lvgl/) |

## 仓库结构

```text
1.47-tft-172x320-spi-gc9307/
├── README.md
├── README_EN.md
├── MODULE_VERSION.md
├── LICENSE
├── images/          # README 用图
├── docs/            # 规格书、驱动手册、初始化等
└── examples/        # 示例工程
```

## 相关资料

### 本产品资料

| 资料 | 链接 |
| ---- | ---- |
| 产品规格书（YDP147H009-V2） | [`docs/YDP147H009-V2.pdf`](./docs/YDP147H009-V2.pdf) |
| 驱动 IC 数据手册（GC9307） | [`docs/GC9307_DS_V1.01(1).pdf`](./docs/GC9307_DS_V1.01(1).pdf) |
| 初始化序列（文本） | [`docs/GC9307+HSD1.47(HSD015BPW2-C)_IPS_AN_VCI=3.3V_V2.txt`](./docs/GC9307+HSD1.47(HSD015BPW2-C)_IPS_AN_VCI=3.3V_V2.txt) |

### 示例工程

- [ESP32-C3 GC9307 SPI + LVGL8](./examples/esp32c3-idf_gc9307_lvgl/)

## 购买链接

<p align="center">
  <a href="https://shop110742373.taobao.com/"><img alt="淘宝官方店铺" src="https://img.shields.io/badge/淘宝-官方店铺-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="速卖通官方店铺" src="https://img.shields.io/badge/速卖通-官方店铺-FF6A00?style=for-the-badge" /></a>
</p>

**国内（淘宝）**

- 店铺：[鱼鹰光电工厂店](https://shop110742373.taobao.com/)

**海外（AliExpress）**

- 店铺：[OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

## 技术支持

- 技术支持 / 产品咨询：<luyu@osptek.com>
- QQ 技术交流群：**985881096**
- 公司官网：<https://osptek.com/>
- 有任何问题，都可以在本仓库 Issues 中提问

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
