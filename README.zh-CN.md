# Eddie Zhou

[English](README.md) | **简体中文**

我在一家大型能源企业负责战略规划、投资和产业研究，也用 AI 开发和维护自己的长期项目。

我主要使用 Codex 和 Claude Code，也会用 DeepSeek Harness 和 OpenCode。模型在不同 Harness 下的表现有差异，我会按任务选组合。做架构设计时，我会请不同的前沿模型独立评估同一套前后端方案，再对照它们发现的问题和提出的设计建议。

我为这种工作方式做了两个 Skill。

## Work Charter

Work Charter 管理跨会话的开发、审查和交付。单条工作线由一位负责人从实现跟到交付。多个分支或功能并行时，由 Orchestrator 协调优先级、接口依赖和集成顺序，各条线在自己的会话里推进。

[Work Charter](https://github.com/junwei529/work-charter)

## Project Docs

Project Docs 把接手项目需要的信息留在仓库里。项目入口指向当前进度、关键决定和验证记录。阶段收尾时，把验证过的做法补进原有指南，把已确认的变更写回项目规则。换一个 Agent 或 Harness 时，可以从项目文档恢复上下文。

[Project Docs](https://github.com/junwei529/manage-project-docs)

## 两个非公开项目

### 知识库

文档解析、政策材料处理和检索最初各自开发，后来又加入了官方统计图表和 Wiki。随着模块增多，我希望能在同一个工作流里导入扫描材料、整理政策、检索资料，再把研究结果写入 Wiki。统计图表保留专用入口。

整合时，我们先统一入口和接口，再沿实际使用流程逐段接入，同时保留模块独立维护的余地。并行开发时，Orchestrator 负责协调哪些接口要先定、各条线什么时候能合起来验证。换到 Claude Code 或其他 Harness 接手时，项目文档要能回答三个问题：**为什么分阶段整合，哪段流程已经跑通，接下来该接哪个模块。**

### 股票研究工具

项目覆盖个股分析、持仓分析、研究回测，以及交易行为记录和复盘。开发、数据和来源各有一个并行会话，由 Orchestrator 协调不同阶段的依赖和交付。

项目同时使用本地环境和云服务器。接手一项工作前，需要确认本地开发分支和云端运行版本、这轮分析使用哪一版数据，以及备份放在哪里。比如要复跑一次回测，接手的人得能找到当时的代码和数据版本，再决定是复现原结果，还是用新版本继续验证。

## 其他工具

**Use PowerShell Safely** 是给 Codex 用的 Windows 命令执行和排障 Skill。处理 PowerShell 调用外部程序时的参数、路径、编码和 WSL 问题，也帮助核对进程退出状态和实际输出。 [查看仓库](https://github.com/junwei529/use-powershell-safely)

**Work Charter for DeepSeek Harness · Inactive** 基于 Work Charter 0.9.1，适配 DeepSeek Harness `0.1.7-rc.2` 的原生 Team。暂无后续开发计划，源码和历史预发布版本供参考。 [查看仓库](https://github.com/junwei529/work-charter-dsh) · [v0.2.0-alpha.1](https://github.com/junwei529/work-charter-dsh/releases/tag/v0.2.0-alpha.1)
