# 美术资源管理器

Unity 编辑器本地资源浏览工具。本仓库提供发行文件和下载说明，不包含工具源码或项目美术资源。

## 下载

### [点击下载 Windows 安装包（V0.7.17，约 59 MB）](https://github.com/chenjialuo666/art-asset-browser/releases/download/v0.7.17/ArtAssetBrowser-0.7.17-installer.zip)

**首次使用：下载上面这一个 ZIP 即可。** 完整解压后运行 `ArtAssetBrowserInstaller.exe`，选择 Unity 项目。不要单独复制 EXE，随包文件需要保留。

**已经安装：打开美术资源管理器，点击“检查更新 → 下载并更新”，按界面提示操作。** 如果 GitHub 连接失败，也可以下载上面的安装包进行更新。

旧版首次过渡可能需要保存工作并关闭 Unity；支持在线维护的版本在满足条件时可以保持 Unity 开启。安装和卸载是否需要关闭 Unity，以界面提示为准。不要手动覆盖程序文件。

更新包、维护组件包、`update.json` 和 GitHub 自动生成的“Source code”压缩包，都不是普通用户需要单独下载的文件。

## 安装和使用

1. 下载上方安装包并完整解压，运行 `ArtAssetBrowserInstaller.exe`。
2. 选择需要使用工具的 Unity 项目，默认安装到 `Assets/Editor/com.artasset.browser`。
3. 在 Unity 菜单中打开 `美术资源管理器 / 打开管理器`。
4. 后续更新和卸载可从管理器操作；旧版首次升级请根据维护窗口提示操作。

## 图解使用教程

### [查看可视化使用教程](docs/使用教程.md)

资源筛选、收藏、模型预览、引用关系、组合导出及更新维护，都配有操作说明和图解。安装包内也包含可离线阅读的 `使用教程.html`。

![资源浏览界面操作示意](docs/images/browse.png)

*图为操作示意，不是真实项目截图。*

## 更新记录与反馈

[查看更新记录和历史版本](https://github.com/chenjialuo666/art-asset-browser/releases) · [提交问题](https://github.com/chenjialuo666/art-asset-browser/issues)

已验证环境：Windows x64、Unity 2022.3.62f2c1；其他版本请先在测试项目中确认兼容性。反馈时请提供工具版本、Unity 版本和错误信息，不要上传凭据或未经授权的项目资源。
