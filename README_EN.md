# 3.95" 480×480 TFT MIPI module (ST7102) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 3.95-inch **TFT** panel, **480×480** resolution |
| Interface | **MIPI** |
| Driver IC | **ST7102** |
| Spec ID | **`3.95-tft-480x480-mipi-st7102`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, initialization notes, adapter schematics |
| `examples/` | **Sample projects** by category |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF代码** (esp-lvgl-port + LVGL9) |
| `with-te/` | **屏幕防撕裂代码** |
| `jpg-decoder/` | **jpeg解码** |
| `mjpeg/` | **mjpeg代码** |

### Sample project paths

#### Baseline (`examples/` root)

| Description | Path |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/esp32p4-idf5_st7102-mipi_esp-lvgl-port_lvgl9/` |

#### Tear avoidance (`with-te/`)

| Description | Path |
|:--|:--|
| LVGL9 common demo | `examples/with-te/esp32p4-idf5_st7102-mipi_lvgl9-common-demo/` |

#### JPEG decode (`jpg-decoder/`)

| Description | Path |
|:--|:--|
| JPEG decode | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode/` |
| JPEG decode + LVGL9 | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9/` |
| JPEG decode + digital clock + LVGL9 | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_digital-clock_lvgl-v9/` |
| JPEG batch loop display | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_batch-loop-display/` |
| JPEG batch loop display + LVGL9 | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9_batch-loop-display/` |

#### MJPEG (`mjpeg/`)

| Description | Path |
|:--|:--|
| MJPEG decode | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode/` |
| MJPEG decode + LVGL9 | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9/` |
| MJPEG batch loop display | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display/` |
| MJPEG batch loop display + LVGL9 | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display_lvgl-v9/` |
| MJPEG decode (dual-core) | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_dual-core/` |
| MJPEG decode + LVGL9 (dual-core) | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9_dual-core/` |
