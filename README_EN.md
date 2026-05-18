# 1.47" 172×320 TFT SPI module (GC9307) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 1.47-inch **TFT** panel, **172×320** resolution |
| Interface | **SPI** |
| Driver IC | **GC9307** |
| Spec ID | **`1.47-tft-172x320-spi-gc9307`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, initialization documentation |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | Root-level **`esp32c3-idf_gc9307_lvgl`** project from the source package |

### Sample project paths

| Description | Path |
|:--|:--|
| GC9307 SPI + LVGL | `examples/esp32c3-idf_gc9307_lvgl/` |
