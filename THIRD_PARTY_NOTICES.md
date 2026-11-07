# 原作者署名与许可说明

本仓库的订阅是对现有 GKD 规则的筛选与整理。规则原作者保留各自版权；未对整个汇编统一指定新的许可证。

本次实际采用的规则来源：

| 来源 | 原作者 | 仓库 | 使用内容 |
| --- | --- | --- | --- |
| Lin-arm，订阅版本 627 | 👻 及原仓库贡献者 | https://github.com/Lin-arm/GKD_subscription | 大部分应用广告规则与通用开屏规则 |
| 梦念逍遥，订阅版本 79 | 梦念逍遥及原仓库贡献者 | https://github.com/MengNianxiaoyao/gkd-subscription | 闲鱼开屏、QQ 弹窗及个人主页广告规则 |
| 甘霖，订阅版本 72 | ganlinte 及原仓库贡献者 | https://github.com/ganlinte/GKD-subscription | U净广告规则 |

整理修改包括：按应用包名筛选、排除非广告功能、去重、重映射规则标识和依赖、调整默认启用状态、将通用规则收窄到应用白名单，以及从订阅文件中移除参考字段。

Lin-arm 的 README 记载其规则继承自 AIsouler/GKD_subscription 和 gkd-kit/subscription。本次获取的 Lin-arm 仓库未提供独立 LICENSE 文件，package.json 也没有许可证声明；本说明不据此宣称其规则属于公共领域。

梦念逍遥仓库的 package.json 声明 MIT，但本次未取得独立 LICENSE 文件。甘霖仓库提供 MIT 许可证，完整原文保存在 [licenses/ganlin-MIT.txt](./licenses/ganlin-MIT.txt)。各来源的适用许可条件应分别保留。
