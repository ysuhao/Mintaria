# Mintaria · 萌音

Windows 实时 AI 变声，声音在本机处理。原项目名称为 MintVC / 萌妹AI变声。

[官网与音色库](https://mintaria.mintryu.com/) · [全部版本与更新记录](https://github.com/ysuhao/Mintaria/releases)


所有历史版本和后续更新统一发布在本仓库的 **Releases** 中。点击页面右上角 **Star** 即可收藏整个 Mintaria 项目，无需为每个版本重复收藏。需要更新通知可选择 **Watch → Custom → Releases**。

本公开仓库提供产品介绍、更新记录与安装包下载。

## 当前下载

**Mintaria 5.1.5 正式版**：[官网下载](https://mintaria.mintryu.com/download/) · [夸克完整安装包与升级补丁](https://pan.quark.cn/s/8310913db556) · [GitHub 6 分卷与合并工具](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.5) · [Google Drive 完整包镜像](https://drive.google.com/drive/folders/1v4eDxKA7s9Da9a18TjcE-luahkp1EE2w)。

Windows x64 / CUDA 12.8。完整包 2,861,433,245 字节，双击 `Mintaria Setup.exe`，选择新的空目录安装，默认创建桌面快捷方式。请保留旧版目录，无需另装 Python。已安装 5.1.4 的用户也可在夸克下载 `Mintaria-5.1.4-to-5.1.5.zip`，在软件内「软件更新」选择补丁升级。

本版修复部分电脑注册或登录时「无法获取验证码：账号服务安全连接失败」，并新增 7 款 abbott 音色试听（FFmpeg 后端，LGPL 许可见发行页附件）。音频引擎与 224 款音色目录沿用 5.1.4。

默认附带风妈；其他模型在软件内下载后导入。GitHub 用户请下载全部 6 个 `Mintaria.Setup.exe.001`–`.006` 分卷与 `Merge-Mintaria-Setup.cmd`，合并并校验后运行安装包。

SHA256：`0b22466ae69ceadb1d8bcbfe0062c7cb0aa9038be27cf4ab04aa56c323d142fa`

Google Drive 镜像提供与夸克相同的完整安装包（含 SHA256SUMS 与 FFmpeg 许可说明）。历史发行说明保留供查阅。

## 版本列表

| 版本 | 类型 | 发布说明 |
| --- | --- | --- |
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

测试版单独标记为 Pre-release，后续更新继续发布在同一仓库。GitHub 的 Latest 指向最新正式发行版，因此目前仍为 2.1；需要 5.0 beta 请使用上面的测试版入口。

## 使用与许可

建议使用耳机，通过虚拟声卡连接游戏或通话软件。不同音色、设备与游戏的实际效果可能不同。第三方组件的许可与署名见安装包内 notices。

作者：MINT RYU · [mintryu.com](https://mintryu.com/) · me@mintryu.com
