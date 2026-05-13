# ClawNanny

> agentic shenanigans, with adult supervision, for normal people

ClawNanny is a desktop application for Windows or Mac that runs entirely on your own local machine.  It puts a friendly Web UI in front of one or more agent backends (currently OpenClaw and Hermes-Agent with II-Agent in development), so day-to-day users can drive AI agents without learning a terminal, an SDK, or a config file format.

## Status

**Alpha &mdash; friends-and-family build**  Things will change.  Feedback welcome.

## What you get

- A unified Web UI for chatting with one or more AI agents
- Session history that survives across runs, across agents, with search, tagging, and pattern analysis
- A skills + capability layer so you can teach the agent reusable workflows
- A capability designer takes your workflow-problem-solution idea and materializes a task sequence with skills and tools.
- Telemetry and cost tracking per conversation, per model, per day
- Local-first: Your conversations stay on your PC.  No cloud account is required to run the app locally.

## Download

The latest Windows installer is at https://ClawNanny.com/download.

A copy of each release is also attached to this repo's [Releases](https://github.com/ClawNanny/clawnanny/releases) tab, so you can browse the version history and download any past build.

## License

ClawNanny is **proprietary freeware**.  Free to download and use; source is not open.  See [LICENSE](LICENSE) for full terms.

## Why a closed-source repo on GitHub?

Two reasons:

1. **Releases hosting.**  GitHub Releases is a free, fast, world-wide CDN for the installer.  Hosting builds here means downloads stay fast even during traffic spikes, and every release has a stable URL.
2. **A real issue tracker and discussion forum.**  We'd rather hear bug reports as GitHub Issues and feature requests as GitHub Discussions than as scattered e-mails.

The application source itself is not published.  ClawNanny depends on a number of excellent open-source projects (OpenClaw, Hermes-Agent, and others); credit and links to those projects appear in the application's About dialog.

## Support

- **Bug reports:** open a new [Issue](https://github.com/ClawNanny/clawnanny/issues).
- **Questions, ideas, "how do I":** start a thread in [Discussions](https://github.com/ClawNanny/clawnanny/discussions).
- **Security vulnerabilities:** please use the private channel described in [SECURITY.md](SECURITY.md).
- **Everything else:** admin@ClawNanny.com

## Publisher

ClawNanny is published by **Open System Applications LLC** (United States).  The Windows installer is code-signed.
