# BGI-GatherCombatCDManager

作者：冷漠

当前版本：1.0.1

这是 BetterGI 脚本「采集CD管理——冷漠」的源码仓库。

脚本本体在：

```text
repo/js/GatherCombatCDManager
```

## 怎么用

把 `repo/js/GatherCombatCDManager` 整个文件夹复制到 BetterGI 的脚本目录：

```text
C:\BetterGI\User\JsScript\GatherCombatCDManager
```

回到 BetterGI 的「JS 脚本」页刷新列表，选脚本运行。

第一次运行会在脚本目录里生成 `采集CD管理配置文件\`。里面是面板配置和每个账号的路线 CD，属于本机数据，不会进仓库。

跑图时按 F7 开配置面板。默认会先弹一次面板，不想看可以在面板里关掉。目标、队伍、快捷键、悬浮窗位置这些都在面板里改。

完整的安装、目标写法、数量扣减、CD 和队伍说明，看 [`repo/js/GatherCombatCDManager/README.md`](repo/js/GatherCombatCDManager/README.md)。

## 说明

这是自己的源码仓库。别人要是在 BetterGI 在线仓库里直接搜到并订阅，还是得往 `babalae/bettergi-scripts-list` 提 PR 合并。

## 更新日志

版本号规则：小修改加 `0.0.1`，大更新加 `0.1.0`。

### 1.0.1

- 同步脚本 README 的删改。

### 1.0.0

- 仓库首次整理上传，源码放在 `repo/js/GatherCombatCDManager`。
- 说明文档按现在的面板和运行流程重写。
- 版本号统一从 1.0.0 开始。
