# OPC 个人 AI 工作台

这套说明给用户「17」使用。17 只对接总助。总助再调度客户经理、产品经理、开发者、质检员，以及按需出场的逆向工程师，把一件事从需求做到上线。

17 可以从两个入口找到总助：已经接通的微信（ClawBot/iLink 桥），或 Grok Bot 主窗口。日程目前记在 Notion「项目总台账」。「项目事项」是目标结构。提醒写到滴答清单「17项目日程」。

## 仓库是唯一源

改工作流时先改本仓库，提 PR，合并之后再把 `SKILL.md` 同步到 Grok Bot 里名为 `opc-ai-workbench` 的 skill。两边不一致时，以本仓库为准覆盖 Bot。同步步骤见 [SKILL.md](SKILL.md)。

## 17 怎么开口

直接对总助说要做的事，例如新需求、改方案、排期、拍板、演示、验收，或请总助拆解别人的公开作品。总助会按 [docs/pipeline.md](docs/pipeline.md) 推进，并在四个确认点停下来等 17。

四个确认点是：需求定义、方案设计、MVP 演示、最终验收。确认用语和回退方式见 [SKILL.md](SKILL.md) 与 [docs/rules.md](docs/rules.md)。

## 目录

| 路径 | 内容 |
| --- | --- |
| [SKILL.md](SKILL.md) | 总助技能正文，十章 |
| [CHANGELOG.md](CHANGELOG.md) | 版本记录 |
| [docs/roles.md](docs/roles.md) | 角色职责与交接 |
| [docs/pipeline.md](docs/pipeline.md) | 需求到上线，含流程图 |
| [docs/schedule.md](docs/schedule.md) | 项目总台账、项目事项目标结构、滴答提醒 |
| [docs/connectors.md](docs/connectors.md) | Notion、滴答、GitHub、云端开发 agent、Codex、微信桥 |
| [docs/rules.md](docs/rules.md) | 密钥、对外发送、验收标准 |
| [templates/requirement.md](templates/requirement.md) | 需求说明 |
| [templates/solution.md](templates/solution.md) | 方案 |
| [templates/task.md](templates/task.md) | 任务 |
| [templates/mvp-demo.md](templates/mvp-demo.md) | MVP 演示 |
| [templates/acceptance.md](templates/acceptance.md) | 验收清单 |
| [templates/project-profile.md](templates/project-profile.md) | 项目档案 |
| [templates/decision.md](templates/decision.md) | 待拍板 |
| [templates/handoff.md](templates/handoff.md) | 交接 |
| [examples/xiju-liaoyu/README.md](examples/xiju-liaoyu/README.md) | 戏剧疗愈小程序脱敏示意 |

真实项目的文档放在该项目自己的仓库里，从 `templates/` 复制后填写。本仓库只保留工作流说明和示意样例。

## 版本

当前版本 0.1.1，见 [CHANGELOG.md](CHANGELOG.md)。
