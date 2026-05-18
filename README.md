# 3.95 寸 480×480 TFT MIPI 模组（ST7102）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 3.95 英寸 **TFT**，分辨率 **480×480** |
| 接口 | **MIPI** |
| 驱动芯片 | **ST7102** |
| 规格标识 | 产品资料中常用 **`3.95-tft-480x480-mipi-st7102`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、初始化与转接板原理图等 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **ESP-IDF代码**（esp-lvgl-port + LVGL9） |
| `with-te/` | **屏幕防撕裂代码** |
| `jpg-decoder/` | **jpeg解码** |
| `mjpeg/` | **mjpeg代码** |

### 示例工程路径

#### 基础（`examples/` 根目录）

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/esp32p4-idf5_st7102-mipi_esp-lvgl-port_lvgl9/` |

#### 屏幕防撕裂代码（`with-te/`）

| 说明 | 路径 |
|:--|:--|
| LVGL9 通用演示 | `examples/with-te/esp32p4-idf5_st7102-mipi_lvgl9-common-demo/` |

#### jpeg解码（`jpg-decoder/`）

| 说明 | 路径 |
|:--|:--|
| JPEG 解码 | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode/` |
| JPEG 解码 + LVGL9 | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9/` |
| JPEG 解码 + 数字时钟 + LVGL9 | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_digital-clock_lvgl-v9/` |
| JPEG 批量循环显示 | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_batch-loop-display/` |
| JPEG 批量循环显示 + LVGL9 | `examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9_batch-loop-display/` |

#### mjpeg代码（`mjpeg/`）

| 说明 | 路径 |
|:--|:--|
| MJPEG 解码 | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode/` |
| MJPEG 解码 + LVGL9 | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9/` |
| MJPEG 批量循环显示 | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display/` |
| MJPEG 批量循环显示 + LVGL9 | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display_lvgl-v9/` |
| MJPEG 解码（双核） | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_dual-core/` |
| MJPEG 解码 + LVGL9（双核） | `examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9_dual-core/` |
