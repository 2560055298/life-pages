<div align="center">

<img src="./assets/hedgehog.png" width="220" alt="Life Pages 刺猬" />

# Life Pages · 平生素记

**一个人的一生，是一本书。**

本地加密日记 · 数据只留在自己的设备 · 没有广告 · 没有云端账号

<br />

![platforms](https://img.shields.io/badge/platform-iOS%20%7C%20macOS%20%7C%20Windows%20%7C%20Android-1f6feb?style=flat-square)
![local](https://img.shields.io/badge/storage-local--only-2ea44f?style=flat-square)
![encrypted](https://img.shields.io/badge/encryption-AES--256--GCM-8957e5?style=flat-square)
![ads](https://img.shields.io/badge/ads-none-6e7781?style=flat-square)

</div>

---

## 下载

当前版本：**v0.1.0**

| 平台 | 安装包 | 大小 | 说明 |
| --- | --- | ---: | --- |
| iPhone | [平生素记-iOS.ipa](v0.1.0/平生素记-iOS.ipa) | 4.5 MB | 需要侧载安装 |
| macOS | [平生素记-macOS-arm64.dmg](v0.1.0/平生素记-macOS-arm64.dmg) | 7.4 MB | Apple Silicon |
| Windows | [平生素记-windows-x64.zip](v0.1.0/平生素记-windows-x64.zip) | 3.7 MB | 解压即用，x64 |
| Android | [平生素记.apk](v0.1.0/平生素记.apk) | 44 MB | 通用 APK，已签名 |

校验文件：[SHA256SUMS.txt](v0.1.0/SHA256SUMS.txt)

---

## 这是什么

Life Pages 是一本只属于自己的日记。

- **只存本地**：日记、图片和设置都保存在自己的设备里。
- **加密保存**：正文与图片以密文形式存储，口令错误无法打开。
- **没有广告**：不靠广告，也不做推荐流。
- **不要求联网**：写作本身不需要网络。
- **手机和电脑各自可用**：通过加密备份在设备之间迁移。
- **自动锁定**：离开一段时间后重新要求口令。

它不试图成为社交产品，也不试图收集你的生活。

---

## 安装

### iPhone

IPA 需要通过 AltStore、SideStore、Xcode 等方式侧载安装。

### macOS

打开 DMG，把「平生素记」拖进 Applications。

当前提供的是 **Apple Silicon（M 系列）** 版本。首次打开如果被系统拦截，可在「系统设置 → 隐私与安全性」中允许。

### Windows

解压 zip，运行 `平生素记.exe`。

需要 WebView2。Windows 10/11 通常已自带；如果提示缺失，安装微软的 WebView2 Runtime 即可。

### Android

直接安装 APK。首次安装需要允许浏览器或文件管理器「安装未知来源应用」。

---

## 校验安装包

macOS / Linux：

```bash
cd v0.1.0
shasum -a 256 -c SHA256SUMS.txt
```

Windows PowerShell：

```powershell
cd v0.1.0
Get-FileHash .\平生素记-windows-x64.zip -Algorithm SHA256
```

---

## 常见问题

**日记会上传到服务器吗？**

不会。正文和图片保存在本地；本仓库也不包含任何用户数据。

**为什么这里只有安装包？**

这是发布仓库。源码暂未公开，这里只提供可直接安装的版本和校验文件。

**换电脑或手机怎么办？**

在旧设备里生成加密备份，在新设备里选择备份文件恢复。备份文件本身是密文，请和口令分开保管。

**支持 Intel Mac 吗？**

当前只提供 Apple Silicon 版本。

**如何升级？**

安装新版本覆盖旧版本即可。升级前建议先做一次备份。

---

## 版本

历史版本见 [Tags](https://github.com/2560055298/life-pages/tags)。

<div align="center">

<img src="./assets/hedgehog.png" width="72" alt="" />

<sub>Life Pages · 把一生写成一本书</sub>

</div>
