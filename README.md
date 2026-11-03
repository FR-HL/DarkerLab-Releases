# DarkerLab Releases

本仓库只提供用户下载的 Windows 启动器，不包含源码、游戏文件或其他构建产物。

## 下载

最新版本：

[DarkerLab.Launcher.Gui.exe](https://github.com/FR-HL/DarkerLab-Releases/releases/latest/download/DarkerLab.Launcher.Gui.exe)

历史版本请在 [Releases](https://github.com/FR-HL/DarkerLab-Releases/releases) 中选择对应版本。

## 系统要求

- Windows 10/11 x64
- 已安装受支持版本的《Dark and Darker》本地游戏文件
- 启动器不需要单独安装 .NET 或 Node.js

## 更新

1. 关闭正在运行的 DarkerLab 和游戏。
2. 下载新的 `DarkerLab.Launcher.Gui.exe`。
3. 覆盖原启动器 EXE，保持启动器所在目录不变。
4. 重新启动启动器；如果版本说明要求，执行一次“安装/修复”。

不要删除已有的训练副本目录或 `%LOCALAPPDATA%\DarkerLab` 运行缓存，除非排障文档明确要求。

## 版本与校验

每个 Release 的说明包含：

- 版本号
- 更新内容
- 适用游戏版本
- EXE 的文件大小和 SHA256

下载后可自行校验：

```powershell
Get-FileHash .\DarkerLab.Launcher.Gui.exe -Algorithm SHA256
```

## 发布说明

- 本仓库只承载 Release 附件，不提交 EXE 到 Git 历史。
- 源码仓库保持私有。
- 旧版本保留用于回滚；请下载与当前游戏版本匹配的发布版本。

## 许可证与声明

使用前请阅读启动器内附的使用说明和免责声明。本仓库不提供游戏本体或游戏资源。
