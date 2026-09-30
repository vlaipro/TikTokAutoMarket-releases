# TikTokAutoMarket 安装说明

当前发布版本：0.1.14。安装文件：`Setup-TikTokAutoMarket-0.1.14.exe`。目标系统为 Windows 10/11 x64。

1. 在 [Releases](../../releases) 中下载 EXE 和 `SHA256SUMS.txt`，核对 SHA-256。PowerShell 命令：`Get-FileHash -Algorithm SHA256 -LiteralPath '下载文件的完整路径'`。
2. 双击 EXE，按安装向导完成安装，再从开始菜单启动。
3. 按应用中的首次配置流程完成授权与账号设置。涉及外部账号发送的功能，请先在测试账号下核对配置与结果。

该安装包没有 Windows 发布者代码签名，系统可能提示“未知发布者”。请确认下载地址位于 `github.com/vlaipro/TikTokAutoMarket-releases`，且文件校验值一致后再安装。

安装包与实际账号、云端服务的联动需要在客户环境验证；发布附件的完整性校验不等同于实发流程验收。
