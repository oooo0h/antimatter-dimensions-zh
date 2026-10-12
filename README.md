# 反物质维度 · 简体中文版

基于官方开源游戏和 Steam 社区汉化资源的非官方浏览器版，通过 GitHub Pages 运行。无需安装 Steam，不提供 Steam 成就或 Steam 云存档。

`site/` 包含完整的静态游戏、中文词库、翻译脚本及字体。推送到 `main` 后，GitHub Actions 自动部署 GitHub Pages。所有资源使用相对路径，可用于项目站点。

## 存档

游戏进度存放在当前浏览器、当前站点地址的本地存储中。从本地版迁移时，请在本地游戏的“选项 → 存档”中导出，再到线上版本导入。发布仓库不包含玩家存档。

## 来源与许可

- 官方源码：[IvarK/AntimatterDimensionsSourceCode](https://github.com/IvarK/AntimatterDimensionsSourceCode)，版本 `5409e320cecef96a917cca1dfb68f1f183e499ca`，MIT 许可。
- 社区汉化：[Smirk1921/AD-Zh-CN-Patch](https://github.com/Smirk1921/AD-Zh-CN-Patch)，版本 `51f4268c9c273abf8d9cf14806d910954f472bd1`，MIT 许可；译文沿用 aquamarine309/ADChinese 等社区成果。
- 霞鹜文楷字体：OFL 1.1，完整许可位于 [site/localization/fonts/OFL.txt](site/localization/fonts/OFL.txt)。
- 完整许可和鸣谢位于 [site/licenses](site/licenses)。编译脚本的第三方许可文件也随资源保留。

本版本接入展示层翻译，并补充中文窄屏布局。内部游戏标识与存档格式保持原样。部分新文本和成就图片中的英文仍可能保留。

## 更新

本地完整安装中运行 `node 工具/准备GitHubPages.mjs` 更新发布目录，再在本仓库提交并推送变更。静态文件已经构建，Actions 无需下载 npm 依赖。
