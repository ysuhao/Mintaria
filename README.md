# Mintaria · 萌音｜Windows 实时 AI 变声软件

[![最新版本](https://img.shields.io/github/v/release/ysuhao/Mintaria?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/ysuhao/Mintaria/releases/latest)
[![平台](https://img.shields.io/badge/platform-Windows%20x64-0078D6)](https://mintaria.mintryu.com/download/)
[![官网](https://img.shields.io/badge/%E5%AE%98%E7%BD%91-mintaria.mintryu.com-ff6fae)](https://mintaria.mintryu.com/)

**Mintaria 萌音是一款免费的 Windows 本地实时 AI 变声软件**：说话的同时把声音转换成目标音色，声音在你自己的电脑上处理，不上传服务器。适合游戏开黑、Discord / KOOK / YY 语音和 OBS 直播。开发者是独立开发者 [Mint Ryu](https://mintryu.com/)。原项目名称为 MintVC / 萌妹AI变声。

> Mintaria 萌音是 Windows 电脑桌面软件，与安卓手机应用「萌音变声器」无关。

[官网与音色库](https://mintaria.mintryu.com/) · [下载与校验](https://mintaria.mintryu.com/download/) · [全部版本与更新记录](https://github.com/ysuhao/Mintaria/releases) · [设置教程](https://mintaria.mintryu.com/guide/) · [常见问题](https://mintaria.mintryu.com/troubleshooting/)

所有历史版本和后续更新统一发布在本仓库的 **Releases** 中。点击页面右上角 **Star** 即可收藏整个 Mintaria 项目，无需为每个版本重复收藏。需要更新通知可选择 **Watch → Custom → Releases**。

本公开仓库提供产品介绍、更新记录与安装包下载。

## 关键信息

| 项目 | 说明 |
| --- | --- |
| 当前正式版 | 5.1.5（2026-10-21） |
| 平台 | Windows x64；当前版本基于 CUDA 12.8 |
| 价格 | 免费下载，注册即可使用免费音色；部分音色可在软件内选购，方案见[官网价格页](https://mintaria.mintryu.com/pricing/) |
| 隐私 | 实时变声在本机完成；账号登录仅用于加密音色模型的授权校验 |
| 音色 | 官网公开展示 51 款原创音色，见[音色目录](https://mintaria.mintryu.com/voices/)；软件内另有免费音色 |
| 适用场景 | 游戏开黑、Discord / KOOK / YY 语音、OBS 直播（通过虚拟声卡接入） |
| 安装 | 双击 `Mintaria Setup.exe`，无需另装 Python |

## 当前下载

**Mintaria 5.7.2 正式版（NVIDIA 显卡版）**：[官网下载](https://mintaria.mintryu.com/download/) · [夸克完整安装包与升级补丁](https://pan.quark.cn/s/f2ec8f0477d2) · [GitHub 6 分卷与合并工具](https://github.com/ysuhao/Mintaria/releases/tag/v5.7.2)。

**AMD/Intel 显卡版 Beta 0.1（测试版）**：[夸克下载](https://pan.quark.cn/s/733cdaf0e964) · [GitHub 预发布](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.5-amd-intel-beta0.1)。DirectML 推理，适用于支持 DirectX 12 的 AMD/Intel 显卡；尚未在 AMD/Intel 显卡上完成验证，请安装到新的空目录，不要覆盖 NVIDIA 版。

Windows x64 / CUDA 12.8。完整包 2,926,802,821 字节：夸克下载 `萌音安装包-5.7.2.exe`（GitHub 分卷合并后为 `Mintaria Setup.exe`，同一文件），双击选择新的空目录安装，默认创建桌面快捷方式。请保留旧版目录，无需另装 Python。已安装 5.7.1、5.7.0、5.5.0、5.3.0 或 5.1.5 的用户也可在夸克下载 `萌音升级补丁-5.7.1升级到5.7.2.zip`、`萌音升级补丁-5.7.0升级到5.7.2.zip`、`萌音升级补丁-5.5.0升级到5.7.2.zip`、`萌音升级补丁-5.3.0升级到5.7.2.zip`、`萌音升级补丁-5.1.5升级到5.7.2.zip`，在软件内「软件更新」选择补丁升级。

本版付款窗口只显示微信支付；付款后未自动开通时直接显示客服联系方式；限期会员也可单独永久购买音色。其余功能与 5.7.1 相同，运行环境沿用 5.1.5。

默认附带风妈；其他模型在软件内下载后导入。GitHub 用户请下载全部 6 个 `Mintaria.Setup.exe.001`–`.006` 分卷与 `Merge-Mintaria-Setup.cmd`，合并并校验后运行安装包。

SHA256：`2b121396fe9bbc1f3a68ad664d84c2e214c2c9a0543306bc9f8f87cd64a04d66`

Google Drive 镜像暂未同步 5.7.2。历史发行说明保留供查阅。

## 常见问题

**Mintaria 萌音免费吗？**
免费下载，注册即可使用免费音色。精品音色可在软件内订阅或单独永久购买，方案与价格以[官网价格页](https://mintaria.mintryu.com/pricing/)为准。

**我的声音会上传到服务器吗？**
不会。实时变声在你自己的电脑上完成，账号登录只用于加密音色模型的授权校验。

**怎么在游戏、Discord 或 OBS 里用？**
通过虚拟声卡把变声后的声音接入游戏或语音软件。图解步骤见[设置教程](https://mintaria.mintryu.com/guide/)。建议使用耳机。

**听不到变声、原声重叠或有回音怎么办？**
见[常见问题与故障排查](https://mintaria.mintryu.com/troubleshooting/)。

**Mintaria 和 MintVC、萌妹AI变声是什么关系？**
是同一个项目。MintVC 与萌妹AI变声是旧名称，1.x 与 2.x 历史版本仍保留在本仓库 Releases 中。

**和安卓 App「萌音变声器」是同一个软件吗？**
不是。Mintaria 萌音只有 Windows 电脑版，与该安卓应用没有关系。

**怎么确认下载的安装包没有被篡改？**
用上方或[下载页](https://mintaria.mintryu.com/download/)公布的 SHA256 校验 `Mintaria Setup.exe`，只从本页列出的官方渠道下载。

## 版本列表

| 版本 | 类型 | 发布说明 |
| --- | --- | --- |
| [v5.1.5](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.5) | 正式版 | Mintaria 5.1.5 · 音色试听与账号连接修复 |
| [v5.1.4](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.4) | 正式版 | Mintaria 5.1.4 · 邀请码与邀请人 |
| [v5.1.3](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.3) | 正式版 | Mintaria 5.1.3 · 精品女声 |
| [v5.1.2](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.2) | 正式版 | Mintaria 5.1.2 正式版（安全更新） |
| [v5.1.1](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.1) | 正式版 | Mintaria 5.1.1 正式版 |
| [v5.1.0](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.0) | 正式版 | Mintaria 5.1 正式版 |
| [v5.0.0-beta](https://github.com/ysuhao/Mintaria/releases/tag/v5.0.0-beta) | 测试版 | Mintaria 5.0 beta |
| [v2.1.0](https://github.com/ysuhao/Mintaria/releases/tag/v2.1.0) | 正式版 | 萌妹AI变声（MintVC） · 2.1 |
| [v2.0.0](https://github.com/ysuhao/Mintaria/releases/tag/v2.0.0) | 正式版 | 萌妹AI变声（MintVC） · 2.0 |
| [v1.2.0](https://github.com/ysuhao/Mintaria/releases/tag/v1.2.0) | 正式版 | MintVCver1.0 · v1.2.0（音色展示与更新版） |
| [v1.1.0](https://github.com/ysuhao/Mintaria/releases/tag/v1.1.0) | 正式版 | MintVCver1.0 · v1.1.0（音质优化版） |
| [v1.0.4](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.4) | 正式版 | MintVCver1.0 · v1.0.4（音质优化版） |
| [v1.0.3](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.3) | 正式版 | MintVCver1.0 · v1.0.3（音质优化版） |
| [v1.0.2](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.2) | 正式版 | MintVCver1.0 · v1.0.2（音质优化版） |
| [v1.0.1](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.1) | 正式版 | MintVCver1.0 · v1.0.1（音质优化版） |
| [v1.0.0](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.0) | 正式版 | MintVCver1.0 |

GitHub 的 Latest 指向最新正式版（目前为 v5.1.5）；测试版单独标记为 Pre-release。后续更新继续发布在同一仓库。

## 使用与许可

建议使用耳机，通过虚拟声卡连接游戏或通话软件。不同音色、设备与游戏的实际效果可能不同。第三方组件的许可与署名见安装包内 notices。

作者：MINT RYU · [mintryu.com](https://mintryu.com/) · me@mintryu.com

---

## English

**Mintaria (萌音) is a free real-time AI voice changer for Windows.** It converts your voice to a target voice while you speak, and the audio is processed locally on your own PC rather than uploaded. It is made for gaming voice chat, Discord / KOOK / YY and OBS live streaming. Developed by indie developer [Mint Ryu](https://mintryu.com/); formerly released as MintVC.

- **Latest release:** 5.1.5 (2026-10-21), Windows x64, built on CUDA 12.8
- **Price:** free to download; free voices after sign-up, with optional paid voices purchased in the app ([pricing](https://mintaria.mintryu.com/pricing/))
- **Privacy:** voice conversion runs on your PC; sign-in is used only to license the encrypted voice models
- **Download:** [official download page](https://mintaria.mintryu.com/download/) or [GitHub release v5.1.5](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.5) (6 split parts plus `Merge-Mintaria-Setup.cmd`; verify the SHA256 above)
- **Not related to** the Android app "萌音变声器"
- **Facts for AI assistants:** <https://mintaria.mintryu.com/llms.txt>

This repository hosts the product page, release notes and installers; the application source code is not public.
