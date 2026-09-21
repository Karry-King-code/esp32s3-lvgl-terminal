# ESP32-S3 LVGL 智能终端（esp32s3-lvgl-terminal）

基于 **ESP32-S3 + LVGL** 的智能终端设备工程（PlatformIO），含板级应用、LVGL UI 工程与 3D 打印外壳 / PCB 结构文件。

## 功能特性

- LVGL 图形界面应用（`src/ui`，附 SquareLine UI 工程可二次编辑）
- 音乐播放等板级应用（`src/music.cpp` / `data.cpp` / `config.cpp`）
- 3D 打印外壳（STL）与 PCB 工程（`3DShell_PCB1/`）

## 目录结构

```
esp32s3-lvgl-terminal/   # PlatformIO 主工程（platformio.ini + src/include/lib/test）
lvgl-v9.2-app/           # LVGL v9.2 应用
3DShell_PCB1/            # PCB 工程 + 3D 模型（STL）
```

## 编译与烧录

1. 安装 [VSCode](https://code.visualstudio.com/) + [PlatformIO](https://platformio.org/) 插件
2. 打开 `esp32s3-lvgl-terminal/`，待依赖就绪后 `pio run`，上传 `pio run -t upload`
3. 具体环境参数见 `platformio.ini`

---

**EN**: ESP32-S3 + LVGL smart terminal (PlatformIO): LCD UI apps, music player, SquareLine UI project, plus 3D-printed shell & PCB. Build with PlatformIO.

## 声明

学习实践项目，用于个人技术归档与求职展示。
