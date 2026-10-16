# 遇见写作 · Mac 试用版

遇见写作是一款 macOS 写作与资料整理应用。本仓库用于发布安装包、更新说明和接收试用反馈，不包含应用源码。

## 下载与安装

前往 [Releases 下载页](https://github.com/shenchao890216/unclechao-writer-release/releases)。下载下方 Assets 中的 .dmg 文件即可安装。打开后将“遇见写作”拖入“Applications”。

- 支持 Apple 芯片 Mac（M1 及后续型号）。
- 需要 macOS 14 或更新版本；暂不支持 Intel Mac。
- 当前为测试版本。使用重要文档前请自行保留备份。

## 首次使用

基础写作使用本机文档，不要求配置 AI。AI 助手需要你自己的服务账号或 API Key，模型服务可能另行收费。使用 AI 时，问题及选中的笔记、资料等上下文会发送至对应服务商；请避免提交敏感内容。

部分外部服务与技能依赖用户自行安装和认证的 CLI；安装包不包含这些工具、账号或凭据。支持在“设置 → 文件与存储”启用 iCloud 文档同步；其他 Mac 请登录同一 Apple 账户，开启 iCloud 云盘并选择“使用云端已有文档…”。当前设备的容器访问和读取已验证，真实跨设备同步仍待验收。暂不提供自动更新。

## 反馈

请在 [Issues](https://github.com/shenchao890216/unclechao-writer-release/issues) 提交问题，附应用版本、macOS 版本和复现步骤。Issues 为公开内容，请勿附 API Key、账号授权、私人笔记或未脱敏日志。

## 校验下载

Release 提供 `SHA256SUMS.txt`。在下载目录执行 `shasum -a 256 -c SHA256SUMS.txt` 可校验安装包完整性。

## 使用说明

应用未开源；公开提供安装包不代表授予源码或第三方素材的使用权。测试版可能存在缺陷，目前没有可用性或数据恢复保证。
