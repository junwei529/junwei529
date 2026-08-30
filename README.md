# Eddie Zhou

I build focused tools for making agentic software work easier to govern, verify, and resume.

This profile is a navigation hub for five independently governed projects. Each project owns its source and lifecycle, including its own versioning and release decisions where applicable; this repository does not bundle or install them.

## Projects

- [manage-project-docs](https://github.com/junwei529/manage-project-docs) — **Released: v0.3.0.** A Codex Skill for auditing, adopting, maintaining, and recovering project documentation without inventing authority.
- [work-charter](https://github.com/junwei529/work-charter) — **Released: v0.3.0.** A Codex Skill for bounding consequential work by outcome, authority, evidence, recovery, and proportional coordination.
- [use-powershell-safely](https://github.com/junwei529/use-powershell-safely) — **Released: v0.3.0.** A Codex Skill for diagnosing and safely executing boundary-sensitive Windows shell workflows across PowerShell, native executables, and WSL.
- [session-coordinator-dsh](https://github.com/junwei529/session-coordinator-dsh) — **[Pre-release: v0.1.1-alpha.1](https://github.com/junwei529/session-coordinator-dsh/releases/tag/v0.1.1-alpha.1).** An MIT-licensed external DeepSeek Harness plugin for Workstream identity and cross-Session coordination. Its public source and GitHub pre-release are available; the npm package remains private and unpublished.
- [work-charter-dsh](https://github.com/junwei529/work-charter-dsh) — **[Pre-release: v0.1.0-alpha.1](https://github.com/junwei529/work-charter-dsh/releases/tag/v0.1.0-alpha.1).** An MIT-licensed external DeepSeek Harness plugin that adapts Work Charter policy semantics through a Host policy service and read-only browser surfaces. Its public source and GitHub pre-release are available; the npm package remains private and unpublished.

## Relationship

`work-charter-dsh` relies on `session-coordinator-dsh` for Workstream identity, Session addressing, cross-Session coordination transport/state, and recovery. They remain separate projects with independent source, versions, releases, status, and verification; this relationship does not aggregate source, install dependencies implicitly, or claim a broad compatibility range.
