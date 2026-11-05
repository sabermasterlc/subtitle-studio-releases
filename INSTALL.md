# 安装与更新

## Windows

1. 下载 `Windows-Setup.exe`，确认来自本仓库。
2. 关闭已运行的字幕校对台 Studio，双击安装包，按提示安装。默认安装到当前用户目录。
3. 系统要求 Windows 10 / 11 x64、Microsoft Edge WebView2 Runtime。若电脑缺少 WebView2，请从[微软官方下载页](https://developer.microsoft.com/microsoft-edge/webview2/)安装 Evergreen Runtime 后重试。

预览版尚未签名。若系统提示无法识别发布者，先核对来源与 SHA-256，再决定是否继续安装；不要关闭系统安全保护。

## Mac M 系列

1. 下载 `Mac-M-Series.dmg`，打开后把 `SubtitleStudio.app` 拖入「Applications / 应用程序」。
2. 从「应用程序」启动，更新前先退出旧版，再替换应用。
3. 需要 macOS 14 或更新系统及 M 系列芯片；不提供 Intel 版本。

预览版尚未取得 Apple Developer ID 签名或公证。如果系统拦截启动，核对下载来源后，按照 macOS「系统设置 → 隐私与安全性」中的提示决定是否允许。若系统提示文件损坏或不提供允许选项，请保留提示截图并反馈，不要关闭 Gatekeeper 或其他安全功能。

## 数据保留

- 新版继续使用 Studio 的本机数据目录。卸载程序不会主动删除用户数据。
- Windows Studio 数据：`%LOCALAPPDATA%\com.dog17.subtitle-studio`。
- Mac Studio 数据：`~/Library/Application Support/com.dog17.subtitle-studio`。
- 个人接口密钥单独保存在系统凭据库。
- 旧版「字幕校对台」与「字幕校对台 Studio」属于不同应用，旧版记录不会自动迁入 Studio。请保留旧版及原文件。
- 首次跨版本更新前建议备份上述数据目录；团队规则更新时软件另外生成规则备份。

## 下载校验

两端安装包的 SHA-256 与文件大小记录在[更新信息](updates/studio.json)。软件内下载会自动校验；直接下载可用系统文件校验工具核对。

## 问题反馈

请提供：操作系统及芯片、软件版本、重现步骤、截图。截图上传前请遮盖 API 密钥、个人资料和未授权的剧本内容。不要在公开问题中粘贴密钥。
