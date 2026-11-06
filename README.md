# 红果短剧 Android · 官方项目发布页

适配车机、Android TV 和手机的项目安装包与更新清单。此项目不是红果官方客户端。

**[下载最新版本](https://github.com/hiscatwang/hongguo-android-releases/releases/latest)**

当前发布基线为 **0.28.0（28）**，包名 `cn.local.hongguocar`，最低 Android 8.0 / API 26。使用原签名，可覆盖本项目已有安装。
一个 APK 支持 x86、x86_64、ARMv7、ARM64，媒体播放取决于设备解码能力和平台实时响应。

## 文件命名

| 文件 | 用途 |
| --- | --- |
| `hongguo-android-X.Y.Z.apk` | 安装包 |
| `hongguo-android-X.Y.Z-source.zip` | 该版本对应的完整干净源码 |
| `SHA256SUMS` | APK 与源码 SHA-256 校验 |
| `latest.json` | 后续应用内检查更新使用的稳定清单 |

发布标签统一为 `vX.Y.Z`，默认分支 `main`。发布后的版本与附件不替换，新修复使用新版本。
当前 0.28.0 **尚未接入应用内更新**；本仓库先提供下载和更新清单，为后续功能准备。
车机、电视读取此公开仓库无需登录，不应在 APK 中保存任何 GitHub 访问令牌。GitHub 可访问性取决于设备网络。

## 源码与许可

项目按 GPL-3.0-only 提供，详见 [LICENSE](LICENSE)。每个 Release 同时提供对应完整源码 ZIP、构建说明和上游来源声明。
日常开发仓库为私有；公开 APK 所需源码可以直接从对应 Release 下载，无需访问私有仓库。
签名密钥、密码、开发缓存、个人数据和私人迁移备份不会发布。

0.28.0 已完成构建、完整 Lint 和桌面/有限媒体样本回归，未做 Android/车机真实解码或长期连播验证。
