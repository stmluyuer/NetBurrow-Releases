# NetBurrow

适用于《以撒的结合：忏悔+》的 Windows 好友联机工具。

本仓库用于发布编译后的客户端、更新说明和收集问题反馈，不包含项目源码。

## 下载与使用

从 [最新 Release](https://github.com/stmluyuer/NetBurrow-Releases/releases/latest) 下载 `NetBurrow-<版本>-win-x64.zip`。GitHub 自动生成的 Source code 压缩包不是客户端，请不要下载错。

1. 将 ZIP 完整解压到固定目录，保持 `NetBurrow.exe`、`netburrow-injector.exe`、`netburrow_hook.dll` 在同一目录。
2. 打开 `NetBurrow.exe`，填写你与朋友使用的 Relay 地址，确认游戏路径指向实际的 `isaac-ng.exe`。本工具需要可用的 Relay，不包含公共服务器或预设连接信息。
3. 创建联机组，将组码私下分享给朋友；双方使用相同的服务器和完整组码。
4. 点击“启用联机”，等待连接成功后，从 Steam 正常启动游戏，按游戏原有流程邀请朋友。

客户端适用于 Windows x64，目标游戏程序为 32 位《忏悔+》。无法读取 EXE 文件版本不代表游戏版本错误，也不代表已经验证游戏兼容性。

## 更新

“关于”页可手动检查更新，查看版本说明并在浏览器下载新版。

“自动检测更新”默认关闭。开启时检查一次，以后每次启动检查一次，不定时轮询。检查失败可手动重试，不影响联机。

下载新版后，先退出游戏和 NetBurrow，将完整 ZIP 解压到新文件夹，再启动新版。不要混用不同版本的客户端、注入器和 Hook，也不要在游戏仍运行时覆盖 DLL。工具不会自动安装更新。

本机设置保存在 `%LOCALAPPDATA%\NetBurrow`，正常更新不会清除设置。发行包不包含个人设置、组码、服务器地址或日志。

## 问题反馈

在 [Issues](https://github.com/stmluyuer/NetBurrow-Releases/issues) 中说明客户端版本、问题现象和复现步骤。

组码是加入联机组的凭据，请勿公开。不要上传 `settings.json`、令牌或未经检查的日志。提供诊断材料前请检查其中是否包含个人信息。
