# Layout-first UI

> Avoid unnecessary secondary labels and descriptions. Let the layout do the explaining.

为看板、表格和表单设计或审查界面的 Agent Skill。先用位置、分组、对齐和视觉层级表达关系，再删掉重复说明。保留会影响理解或操作的信息，例如单位、对比基准、数据来源和无障碍标签。

## 安装

如果你的工具会扫描 `~/.agents/skills`，可直接安装到该目录：

```sh
git clone https://github.com/foliageSea/layout-first-ui.git ~/.agents/skills/layout-first-ui
```

如果工具使用其他技能目录，把 [SKILL.md](SKILL.md) 放到该目录下的 `layout-first-ui/` 中。若新技能未出现在目录中，刷新技能列表或开启新会话。

## 使用

> 用 layout-first-ui 审查这个性能看板：删去重复说明，保留理解数据所需的信息，并检查窄屏布局。

例如，有明确名称的 KPI 卡片不需要再加「核心指标概览」标题；响应时间图不需要一句重复标题的说明，但应保留 `ms` 单位和 P95 / P99 图例。
