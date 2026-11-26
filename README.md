# BGI-GatherCombatCDManager

作者：冷漠

BetterGI 的 JavaScript 脚本「采集CD管理——冷漠」源码仓库。

脚本本体位于：

```text
repo/js/GatherCombatCDManager
```

## 安装

把 `repo/js/GatherCombatCDManager` 整个文件夹复制到 BetterGI 的脚本目录：

```text
C:\BetterGI\User\JsScript\GatherCombatCDManager
```

然后在 BetterGI 的「JS 脚本」页面刷新脚本列表。

脚本第一次运行会在自己的目录下创建 `采集CD管理配置文件\`，用来保存面板配置和各账号的路线 CD 记录。这个文件夹属于本机运行数据，不进入仓库。

## 功能

- 按采集目标自动跑图，拾取时实时扣减剩余数量；
- 支持地方特产、矿物、食材与炼金、敌人与魔物路线；
- 每条路线独立记录刷新 CD，未到时间自动跳过；
- 游戏内配置面板，默认快捷键 F7，可在面板内修改；
- 采集悬浮窗显示已运行时间、北京时间、当前路径和目标剩余；
- 必须读取到 9 位账号 UID 才会执行；
- 配置与采集记录长期保存在脚本目录。

完整使用说明见 [`repo/js/GatherCombatCDManager/README.md`](repo/js/GatherCombatCDManager/README.md)。

## 说明

这个仓库用于保存和分发脚本源码。若要让脚本出现在 BetterGI 在线脚本仓库中供所有人直接订阅，仍需向 `babalae/bettergi-scripts-list` 提交。
