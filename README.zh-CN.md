# Eddie Zhou

[English](https://github.com/junwei529/junwei529/blob/main/README.md) | **简体中文**

**让 AI 辅助的软件交付更实用、更可靠。**

我围绕与 AI Agent 协作时的日常问题构建工具：
让项目能跨对话持续推进，让分工更清晰，让文档保持有用，
并帮助命令正确执行。

## 重点 Codex Skills

### [Work Charter](https://github.com/junwei529/work-charter)
**让复杂的 AI 项目接得住，也交得出。**

提供 L0–L4 五档协作方案，覆盖从单次任务到多阶段项目的工作需要。
通过清晰的角色分工，组织项目统筹、规划、执行和独立审阅。

默认模型与推理等级可以自由调整。这些默认值依据我的私有评测结果设置；
评测集来自实际代码仓库，并针对各角色的职责分别设计。

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

- [Session Coordinator](https://github.com/junwei529/session-coordinator-dsh)
  ——关联相关会话，保存协作记录，支持工作中断后的恢复。
- [Work Charter for DSH](https://github.com/junwei529/work-charter-dsh)
  ——把 Work Charter 的角色、决定、证据和恢复机制带入 DeepSeek Harness，
  并使用 Session Coordinator 完成跨会话协作。

两个插件目前均有公开的 GitHub 预发布版本。
安装方法与兼容性说明见各自仓库。

## 我的开发方式

- 从真实项目中反复出现的问题出发。
- 保持工具聚焦，让职责清晰。
- 让结果可以验证，让中断的工作能够恢复。
- 通过评测确定默认方案，再根据实际使用持续调整。

每个项目独立维护。文档、源码、发布信息和当前状态请查看对应仓库。
