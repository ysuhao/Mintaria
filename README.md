# Mintaria · 萌音

Windows 实时 AI 变声，声音在本机处理。原项目名称为 MintVC / 萌妹AI变声。

[官网与音色库](https://mintaria.mintryu.com/) · [全部版本与更新记录](https://github.com/ysuhao/Mintaria/releases)

## 一个项目，持续更新

所有历史版本和后续更新统一发布在本仓库的 **Releases** 中。点击页面右上角 **Star** 即可收藏整个 Mintaria 项目，无需为每个版本重复收藏。需要更新通知可选择 **Watch → Custom → Releases**。

本公开仓库提供产品介绍、更新记录与安装包下载。

## 当前下载

**Mintaria 5.1.2 · Mintaria Setup**：[官网下载](https://mintaria.mintryu.com/download/) · [夸克完整安装包](https://pan.quark.cn/s/518991319dae) · [GitHub 六分卷与合并工具](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.2)。Google Drive 镜像暂缓同步。

Windows x64 / CUDA12.8，完整包 2,810,785,176 字节（约 2.62 GiB）。双击 `Mintaria Setup.exe`，选择新的空目录安装，默认创建桌面 Mintaria 快捷方式；无需另装 Python，请保留旧版目录。

GitHub 用户下载六个 `Mintaria.Setup.exe.001`–`.006` 分卷和 `Merge-Mintaria-Setup.cmd` 到同一文件夹，运行合并工具校验后生成 `Mintaria Setup.exe`，再双击安装。完整包校验见 `Mintaria-Setup-SHA256SUMS.txt`。

SHA256：`7bbadacf625e576928d0cb684dc337ad78afd5fa39ba312c0a56b4fc11945587`

新版安装向导支持品牌插画、按钮动画与可关闭的音效。软件内容仍为已验证的 5.1.2：修复本机服务身份认证、引擎访问控制、验证码限流及到期授权同步，保留 5.1.1 音频稳定性改进。默认附带免费音色风妈，其他音色单独下载。

旧版公开安装包已由新版替代，历史发行说明保留供查阅。`Source code.zip` 不是可运行客户端。

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

## 旧链接与旧客户端

原 `ysuhao/MintVC` 网页地址由 GitHub 跳转到本项目。部分旧客户端会严格校验旧仓库的更新元数据路径，改名后可能忽略更新信息；遇到这种情况，请从本页或官网下载完整包。5.0 beta 未发布自动更新。

## 使用与许可

建议使用耳机，通过虚拟声卡连接游戏或通话软件。不同音色、设备与游戏的实际效果可能不同。第三方组件的许可与署名见安装包内 notices。

作者：MINT RYU · [mintryu.com](https://mintryu.com/) · me@mintryu.com
