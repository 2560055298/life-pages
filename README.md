# Life Pages · 平生素记

本地加密日记，数据只保存在自己的设备上。

这里只发布安装包，不包含源码和任何日记数据。

## 下载 · v0.1.0

| 平台 | 安装包 |
| --- | --- |
| iPhone | [平生素记-iOS.ipa](v0.1.0/平生素记-iOS.ipa) |
| macOS Apple Silicon | [平生素记-macOS-arm64.dmg](v0.1.0/平生素记-macOS-arm64.dmg) |
| Windows x64 | [平生素记-windows-x64.zip](v0.1.0/平生素记-windows-x64.zip) |
| Android | [平生素记.apk](v0.1.0/平生素记.apk) |

校验文件：[SHA256SUMS.txt](v0.1.0/SHA256SUMS.txt)

## 安装说明

- **iPhone**：IPA 需要通过 AltStore、SideStore 或 Xcode 等方式侧载。
- **macOS**：打开 DMG，把「平生素记」拖进 Applications。当前为 Apple Silicon 版本。
- **Windows**：解压 zip，运行 `平生素记.exe`。系统需要 WebView2（Windows 10/11 通常已自带）。
- **Android**：直接安装 APK；首次安装需允许「安装未知来源应用」。

## 校验

```bash
cd v0.1.0
shasum -a 256 -c SHA256SUMS.txt
```
