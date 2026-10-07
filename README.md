# 📺 TVBox / FongMi 影视源与网盘播放加速公开订阅发布中心

[![Release](https://img.shields.io/github/v/release/lublue147-netizen/subscription-release?color=brightgreen&label=Release)](https://github.com/lublue147-netizen/subscription-release/releases)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Active-success)](https://lublue147-netizen.github.io/subscription-release/)
[![jsDelivr CDN](https://img.shields.io/badge/jsDelivr-CDN%20Global-orange)](https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

> 本仓库为 **TVBox / FongMi 影视源与网盘播放加速代理 (GoProxy / Native SO)** 的官方公开发布仓。  
> 版本号与源码工程保持 **100% 实时同步一致**。支持 jsDelivr 全球 CDN 加速与 GitHub Pages 直连，**免登录、免 Token、开箱即用**。

---

## 🚀 订阅源链接汇总 (直接复制填入 TVBox / FongMi)

### 🔄 1. 最新动态订阅接口 (推荐日常使用 · 自动同步最新更新)
配置以下链接后，每次订阅发布更新时电视端将自动平滑静默升级：

| 接口类型 | jsDelivr CDN 全球极速直连 (首选) | GitHub Pages 线路 | 说明 |
| :--- | :--- | :--- | :--- |
| 🌟 **开源原生极速源** *(推荐)* | https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/accelerated_open.json | https://lublue147-netizen.github.io/subscription-release/accelerated_open.json | 100% Java 开源 Spider，内置扫码授权与秒搜 |
| 🚀 **全功能聚合源** | https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/aiwex.json | https://lublue147-netizen.github.io/subscription-release/aiwex.json | 96+ 优质影视站点，全网资源一网打尽 |
| 🌐 **精简核心源** | https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/custom.json | https://lublue147-netizen.github.io/subscription-release/custom.json | 17 个精选低延迟纯净站点 |
| ⚡ **网盘加速极速源** | https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/accelerated.json | https://lublue147-netizen.github.io/subscription-release/accelerated.json | 深度集成 GoProxy 预加载与 Range 多协程并发 |
| 📺 **高清直播源** | https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/live/iptv.m3u | https://lublue147-netizen.github.io/subscription-release/live/iptv.m3u | 央视/卫视/地方台 IPTV 直播源 |

---

### ⭐ 2. 2.0.0 独立固定版本 (永久锁定 2.0.0 · 稳定不随更新变动)
若电视端不希望受后续大版本迭代影响，推荐使用永久锁定的 2.0.0 专属线路：

- **开源原生极速源 (2.0.0 锁定版)**:
  `	ext
  https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/v2.0.0/accelerated_open.json
  `
- **全功能聚合源 (2.0.0 锁定版)**:
  `	ext
  https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/v2.0.0/aiwex.json
  `
- **精简核心源 (2.0.0 锁定版)**:
  `	ext
  https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/v2.0.0/custom.json
  `
- **网盘加速极速源 (2.0.0 锁定版)**:
  `	ext
  https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/v2.0.0/accelerated.json
  `

---

## 📖 导入与使用教程

### 电视端 TVBox / FongMi 影视配置：
1. 打开 **TVBox** 或 **FongMi (蜂蜜) 影视** 客户端。
2. 进入 设置 -> 配置地址（或 接口配置）。
3. 将上述任一订阅链接（推荐使用 **开源原生极速源**）粘贴至输入框中。
4. 点击 确定 保存，等待主页站点数据加载完成即可畅享观影！

---

## ⚡ 网盘加速引擎 (GoProxy) 下载

针对夸克、阿里、115、百度网盘的 Range 多协程并发加速程序：

| 平台 / 架构 | 类型 | 下载地址 | 说明 |
| :--- | :--- | :--- | :--- |
| **Android ARM64** | ELF 执行档 | [下载](https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/bin/goproxy-android-arm64) | 适合 64位智能电视盒 / 手机 |
| **Android ARMv7** | ELF 执行档 | [下载](https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/bin/goproxy-android-armv7) | 适合 32位老旧电视盒 / 投影仪 |
| **Android Native SO** | JNI 动态库 | [libgoproxy.so](https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/bin/arm64-v8a/libgoproxy.so) | 原生 SO 库 |
| **Linux x86_64** | 可执行程序 | [下载](https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/bin/goproxy-linux-amd64) | 软路由 / NAS / Docker |
| **Windows x86_64** | EXE 程序 | [下载](https://cdn.jsdelivr.net/gh/lublue147-netizen/subscription-release@gh-pages/bin/goproxy-windows-amd64.exe) | Windows 电脑端本地加速 |

---

## 📦 版本发布规范

- 本发布仓的 GitHub Releases 包含各版本编译好的 Spider JAR (spider_open.jar, spider.jar)、全套 JSON 订阅配置与 GoProxy 二进制文件。
- 版本号严格与源码构建流程同步（如 2.0.5, 2.0.4...）。
- 所有历史版本资源均在 gh-pages 分支各版本目录永久归档，历史链接永不失效。
