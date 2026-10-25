# 美术资源管理器

Unity编辑器本地资源浏览工具。本仓库仅提供发行文件和下载说明，不包含工具源码或项目美术资源。

## 下载

### [点击下载 Windows 安装包（V0.7.10，59.1 MB）](https://github.com/chenjialuo666/art-asset-browser/releases/download/v0.7.10/ArtAssetBrowser-0.7.10-installer.zip)

**首次使用：下载上面这一个 ZIP 即可。** 解压后运行 `ArtAssetBrowserInstaller.exe`，选择你的Unity项目进行安装。

**已经安装：打开美术资源管理器，点击“检查更新 → 下载并更新”。无需重新下载安装包。**

若检查更新或下载失败，可使用上方安装包手动更新。部分国内网络访问 GitHub 可能较慢或无法连接；若网页也打不开，请换用可访问 GitHub 的网络后重试。

更新包、维护组件包、`update.json` 和GitHub自动生成的“Source code（源码）”压缩包，都不是普通用户需要下载安装的文件。

## 安装和使用

1. 下载上方安装包并解压，运行 `ArtAssetBrowserInstaller.exe`。
2. 在安装管理器中选择需要使用工具的Unity项目。
3. 默认安装位置为项目内 `Assets/Editor/com.artasset.browser`。
4. 在Unity菜单中打开 `Art Tools / 美术资源管理器`。
5. 后续更新和卸载均可在管理器内操作。

如更新提示等待Unity关闭，请先保存工作并正常关闭Unity，完成后重新打开项目。不要手动覆盖更新文件。

## 图解使用教程

### [查看可视化使用教程](docs/使用教程.md)

资源筛选、收藏、模型放大预览、线框与法线、引用关系、组合导出及更新维护，都配有界面或流程示意图。

![资源浏览界面操作示意](docs/images/browse.png)

*图为操作示意，不是真实项目截图。旧版没有“使用教程”按钮时，也可以直接从这里阅读。*

## 更新说明与历史版本

[查看更新记录和历史版本](https://github.com/chenjialuo666/art-asset-browser/releases)

此入口用于查看版本变化；普通用户下载请使用页面顶部的安装包链接。

## 验证范围

- 已验证环境：Windows x64、Unity2022.3.62f2c1；其他版本与超长项目路径尚未完成验收。
- 工具在本地运行；联网检查更新不等于上传项目资源。
- 发布前执行隔离验收和公开下载校验。用户项目中的实际在线升级结果仍需使用者确认，不把“已是最新版”当作完整升级验收。

## 反馈

[提交问题](https://github.com/chenjialuo666/art-asset-browser/issues)

反馈时请提供工具版本、Unity版本和错误信息；不要上传凭据或未经授权的项目资源。
