# 以日为鉴 · 决策方法 Skill

基于分析师Boden《以日为鉴：衰退时代生存指南》，使用 [cangjie-skill](https://github.com/kangarooking/cangjie-skill) 蒸馏的中文 Agent Skill。

将书中的历史机制整理为比较选择、检查前提和安排调查的方法。包含一个入口和九张能力卡。

## 使用

下载或克隆本仓库，将整个文件夹放到你的 Agent 支持的 Skills 目录中，保留 references 和 resources。也可以直接让支持本地文件的 Agent 读取 SKILL.md：

> 请读取这个仓库的 SKILL.md，用《以日为鉴》的框架比较我的两个工作选项。A：……；B：……。我的目标是……，必要支出和家庭约束是……。请区分已知事实、推断和待核查信息，给出下一步调查事项。

## 能力范围

| 场景 | 能力卡 |
|---|---|
| 岗位质量与职业积累 | [employment-entry](references/capabilities/employment-entry.md) |
| 升学与目标岗位匹配 | [education-demand](references/capabilities/education-demand.md) |
| 留城、返乡与需求持续性 | [location-demand](references/capabilities/location-demand.md) |
| 稳定职业的条件审查 | [public-career](references/capabilities/public-career.md) |
| 人口变化与教师岗位 | [education-demography](references/capabilities/education-demography.md) |
| 医疗需求与支付约束 | [health-payment](references/capabilities/health-payment.md) |
| 行业增长到个人收益 | [industry-job](references/capabilities/industry-job.md) |
| 出海与本土化能力 | [overseas-localization](references/capabilities/overseas-localization.md) |
| 历史经验迁移前提 | [historical-transfer](references/capabilities/historical-transfer.md) |

入口：[SKILL.md](SKILL.md)。来源及边界：[overview](references/overview.md)。

## 来源与范围

原书：分析师Boden，开明出版社，2025年8月，ISBN 9787513196093。原书版权归相应权利人所有。本仓库不包含原书全文、EPUB或PDF；少量短引文保留出处，其余为方法整理和转述。步骤和模板属于蒸馏过程中的操作化整理，并非作者逐字给出的标准流程。

书中的历史判断、争议数字及预测未完成独立外部核查，不能作为当前就业、投资或医疗决策的保证。具体岗位、政策和个人约束需要另外核实。

## 验证情况

本地格式及相对引用校验通过。固定合成测试共22题，有Skill组审阅为21通过、1部分通过：两处篇名使用简称，随后已修正文件并检查。没有重跑该题的模型回答，不宣称22题全部通过。未测量真实宿主自动发现、长期现实效果或性能提升。

本仓库暂未指定开源许可证；公开可见不等于对全部材料授予开源许可。
