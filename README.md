# Eddie Zhou

**English** | [简体中文](README.zh-CN.md)

I lead strategic planning, investment, and industry research at a large energy company. I also build and maintain long-running projects with coding agents.

I work mainly in Codex and Claude Code, and also use DeepSeek Harness and OpenCode. The same model can behave differently across harnesses, so I choose the pair for the task. For architecture work, I sometimes ask different frontier models to assess the same frontend and backend design independently, then compare their findings and proposals.

I built two skills for this way of working.

## Work Charter

Work Charter organizes development, review, and delivery across sessions. A single workstream has one owner from implementation through delivery. When several branches or features move in parallel, an orchestrator coordinates priorities, interface dependencies, and integration order. Each workstream advances in its own session.

[Work Charter](https://github.com/junwei529/work-charter)

## Project Docs

Project Docs keeps the information needed for a handoff in the repository. The project entry point links to current progress, key decisions, and verification records. At the end of a phase, I add verified procedures to the existing guides and update project rules once the changes are agreed. A new agent or harness can pick up from those documents.

[Project Docs](https://github.com/junwei529/manage-project-docs)

## Two private projects

### Knowledge base

Document parsing, policy material processing, and retrieval began as separate tools. The project later added charts for official statistics and a wiki. I wanted one workflow for importing scans, organizing policy materials, finding sources, and writing research notes in the wiki, with a dedicated entry point for statistics.

We aligned the entry points and interfaces first, then integrated the modules along real workflows while keeping them independently maintainable. During parallel development, an orchestrator coordinates which interfaces need to be settled first and when the branches can be tested together. When another harness picks up the project, the docs explain why we staged the integration, which part is working, and which module comes next.

### Stock research tools

This project covers individual stock and portfolio analysis, backtesting, and recording and reviewing trading decisions. Development, data, and source research run in parallel sessions. An orchestrator coordinates the dependencies and deliverables for each phase.

The project spans local environments and cloud servers. A handoff needs to identify the local development branch, the version running in the cloud, the data version used for the analysis, and the backup locations. For a backtest, that gives the next agent what it needs to reproduce the original run or test a newer version.

## Other tools

**Use PowerShell Safely** helps Codex run and troubleshoot Windows commands. It covers arguments, paths, encodings, and WSL, and checks process exit status and actual output. [Repository](https://github.com/junwei529/use-powershell-safely)

**Work Charter for DeepSeek Harness · Inactive** adapts Work Charter 0.9.1 to native Teams in DeepSeek Harness `0.1.7-rc.2`. Development is paused. The source and pre-release are available for reference. [Repository](https://github.com/junwei529/work-charter-dsh) · [v0.2.0-alpha.1](https://github.com/junwei529/work-charter-dsh/releases/tag/v0.2.0-alpha.1)
