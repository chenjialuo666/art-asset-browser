# 美术资源管理器

Unity编辑器本地资源浏览工具。本仓库仅提供发行文件和下载说明，不包含工具源码或项目美术资源。

## 下载

[下载最新版本及查看更新说明](https://github.com/chenjialuo666/art-asset-browser/releases/latest)

首次安装请选择名称以 `-installer.zip` 结尾的安装包。

## 安装和使用

1. 解压安装包，运行 `ArtAssetBrowserInstaller.exe`，选择需要使用工具的Unity项目。
2. 默认安装位置为项目内 `Assets/Editor/com.artasset.browser`。
3. 在Unity菜单中打开 `Art Tools / 美术资源管理器`。
4. 已安装用户在管理器内点击“检查更新”，按提示下载、确认更新或卸载，无需每次重新安装。

如更新提示等待Unity关闭，请先保存工作并正常关闭Unity，完成后重新打开项目。
更新包、维护组件包及 `update.json` 供工具读取，不需要手动覆盖。

## 验证范围

- 已验证环境：Windows x64、Unity2022.3.62f2c1；其他版本与超长项目路径尚未完成验收。
- 工具在本地运行；联网检查更新不等于上传项目资源。
- 发布前执行隔离验收和公开下载校验。用户项目中的实际在线升级结果仍需使用者确认，不把“已是最新版”当作完整升级验收。

## 反馈

[提交问题](https://github.com/chenjialuo666/art-asset-browser/issues)

反馈时请提供工具版本、Unity版本和错误信息；不要上传凭据或未经授权的项目资源。
