# Eddie Zhou

[English](https://github.com/junwei529/junwei529/blob/main/README.md) | **简体中文**

**让 AI 辅助的软件交付更实用、更可靠。**

我围绕与 AI Agent 协作时的日常问题构建工具：
让项目能跨对话持续推进，让分工更清晰，让文档保持有用，
并帮助命令正确执行。

## 重点 Codex Skills

### [Work Charter](https://github.com/junwei529/work-charter)
**让复杂的 AI 项目接得住，也交得出。**

通过关于成果、真实约束、独立审查、恢复和自主推进范围的条件式问答，
选择 **Direct、Team 或 Phased** 工作方式。

保持执行与审查独立，在相关工作间复用可靠 Reviewer，让授权内修复连续推进，
减少重复审批。模型与推理档位可按实际职责和工作方式配置。

[**v0.9.1**](https://github.com/junwei529/work-charter/releases/tag/v0.9.1)
支持在稳定工作节点明确迁移，同时保留既有批准、findings、预算和冻结模型设置。

### [Project Docs](https://github.com/junwei529/manage-project-docs)
**让项目文档跟得上项目。**

审计、整理、维护和恢复项目文档。
明确关键决定与当前状态应记录在哪里，保留已有的有效结构，
让文档随着软件的实际变化持续更新。

### [Use PowerShell Safely](https://github.com/junwei529/use-powershell-safely)
**帮助 AI 在 Windows 上把命令执行对。**

处理 PowerShell、原生程序、文本编码、路径和 WSL 之间的实际边界。
诊断执行失败，并核对命令究竟完成了什么。

## DeepSeek Harness 插件

- [Work Charter for DSH](https://github.com/junwei529/work-charter-dsh)
  ——基于 DSH 原生 Team，提供 Work Charter 0.9.1 的 Direct、Team、Phased
  安排，以及审查、验收和恢复机制。
  [v0.2.0-alpha.1](https://github.com/junwei529/work-charter-dsh/releases/tag/v0.2.0-alpha.1)
  已移除独立的 Session Coordinator 运行依赖。
- [Session Coordinator](https://github.com/junwei529/session-coordinator-dsh)
  ——已退役并归档。保留源码和旧 release，供历史 profile 查阅与恢复；
  新 WCDP profile 不再依赖它。

WCDP 仍为 GitHub 预发布版本，目标 DSH 为 0.1.7-rc.2。
协作范围限于同一原生 Team，不代表任意独立 Session 的跨会话协调已被替代。
请使用新的 profile/store，安装步骤与验证限制见项目仓库。

## 我的开发方式

- 从真实项目中反复出现的问题出发。
- 保持工具聚焦，让职责清晰。
- 让结果可以验证，让中断的工作能够恢复。
- 通过评测确定默认方案，再根据实际使用持续调整。

活跃项目独立维护。文档、源码、发布信息和当前状态请查看对应仓库。

