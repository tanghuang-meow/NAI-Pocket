# NAI Pocket Endfield 0.7.10-endfield.6

这是一次个人发布版的小更新，保留 .5 的全部功能。

- 仓库正式改名为 **NAI-Pocket-Endfield**，应用显示名继续使用 **NAI Pocket Endfield**。
- 设置 → ENDFIELD 新增「项目主页」「下载与更新」，直接打开本仓库及 Releases。
- 补充 **14 张实际界面截图、4 张功能总览图**，展示配色、画廊导入、标签多选、批量下载、缩放、回收站、失败队列和下载偏好。
- 个人仓库入口仅存在于 `endfield-release`，没有加入上游 PR 的代码。

## 安装

下载 `NAI-Pocket-Endfield-0.7.10-endfield.6.apk`。已安装旧版 Endfield 的用户可以直接覆盖，**不要先卸载**。
包名和签名不变，versionCode 从 37 升至 38；与作者原版仍可并存。

## 看图了解功能

![四套配色](https://github.com/tanghuang-meow/NAI-Pocket-Endfield/raw/refs/heads/endfield-release/docs/endfield/themes-overview.jpg)

![画廊与导入](https://github.com/tanghuang-meow/NAI-Pocket-Endfield/raw/refs/heads/endfield-release/docs/endfield/gallery-guide.jpg)

![图库、缩放与回收站](https://github.com/tanghuang-meow/NAI-Pocket-Endfield/raw/refs/heads/endfield-release/docs/endfield/library-guide.jpg)

![标签、队列与下载](https://github.com/tanghuang-meow/NAI-Pocket-Endfield/raw/refs/heads/endfield-release/docs/endfield/workflow-guide.jpg)

[完整图集与单张截图](https://github.com/tanghuang-meow/NAI-Pocket-Endfield/blob/endfield-release/docs/endfield/FEATURES.md)。
截图里的图片和账号均为合成演示数据。动效和手势不能靠静态图片完整展示。

## 来源与验证

基于 [MayRain-Meow / NAI-Pocket](https://github.com/MayRain-Meow/NAI-Pocket)，不是官方发布。
功能改进已提交 [上游 PR #3](https://github.com/MayRain-Meow/NAI-Pocket/pull/3)，作者方便时再评审，不催合并。
画廊参考 [Aaalice233 / ComfyUI-Aaalice-Nodes](https://github.com/Aaalice233/ComfyUI-Aaalice-Nodes) 的 BooruGalleryNode，按本项目重新实现；详细署名保留在 README 和 DANBOORU.md。

本次完成普通／独立版构建、390px 手机界面与外部入口检查、Android 编译、签名和包内资源核验。
未调用付费生成；手机实际覆盖安装与系统授权仍需设备验证。
唐璜负责需求、使用反馈与体验选择，Yukino（Codex）协助实现和检查。
更多折腾过程与 token 账单的哭哭猫，继续留在[项目首页](https://github.com/tanghuang-meow/NAI-Pocket-Endfield) (´･ω･`)。
