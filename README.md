# ClawNanny&trade;
*Agentic shenanigans, with adult supervision, for normal people*

ClawNanny is a desktop application for Windows or macOS that runs entirely on your own computer.&nbsp;  It puts a single, friendly web UI in front of one or more agent backends.&nbsp;  Day-to-day users can drive intelligent agents without learning about terminals, CLIs, SDKs, cloning repos, or config-file formats.

Agent backends supported in this release:&nbsp; **OpenClaw** and **Claude Code** (Anthropic subscription required).&nbsp;  **Hermes-Agent** and **II-Agent** are in development.

For a guided introduction, see [Baby Steps](https://ClawNanny.com/Baby_steps), a page of guided exercises you'll see right after setting up the app, the [Agent User's Guide for Normies](https://ClawNanny.com/MD_doc?file=/static/docs/ClawNanny_Guide_Introduction.md) and the [Glossary](https://ClawNanny.com/MD_doc?file=/static/docs/ClawNanny_Glossary.md).

## Status

**Beta &mdash; a friends-and-family build**

We're still sweeping for bugs in the dark corners.&nbsp;  Things will change.&nbsp;  If you're evaluating ClawNanny for enterprise use, the beta label means the application's user-visible surface is still settling &mdash; a feature you rely on today may move or be reshaped before the first stable release.

We welcome your [feedback](https://ClawNanny.com/Feedback).

## What you get

Local-first by default:&nbsp; Your conversations stay on your computer.&nbsp;  No cloud account is required to run the application.

- A unified web UI for interacting with one or more intelligent agents
- A self-help learning environment that moves through the application at your pace and is available on every page
- Free support from a human to get you up and going.&nbsp; We're serious about making a difference in enabling normal people to have their own intelligent agent and to use its capabilities.
- A skills and capability layer so you can teach the agent reusable workflows &mdash; and it can teach you
- **Desi**, the [capability designer](https://ClawNanny.com/Capability_designer), interviews you conversationally, then takes your workflow idea and materializes it as a task sequence with the skills and tools to execute it.
- **Amiga**, the in-app [support agent](https://ClawNanny.com/Support_agent), knows the system better than any human.
- Cost reporting per conversation, per model, per day
- Session history survives across runs and across agents with topic search, tagging, and pattern analysis.

## Download

If you arrived via clawnanny.com, the recommended path is the [client onboarding](https://ClawNanny.com/Client_onboarding) form.&nbsp; Once your request is accepted, you'll be guided to the same installer and through the first-run setup.

The latest installer is attached to this repo's [Releases](https://github.com/ClawNanny/clawnanny/releases) tab.&nbsp;  Each release ships a signed `.exe` for Windows and a signed, notarized `.dmg` for macOS.

## Editions

ClawNanny ships in three editions:

- **Community** &mdash; fee-free with free support.&nbsp;  In exchange, you commit to mentor one other person who wants to get started with their own intelligent agent.
- **Pro** &mdash; Same feature set as Community, but you pay a license fee instead of mentoring.
- **Enterprise** &mdash; Separate edition with additional features for organizations.&nbsp;  [Contact us](mailto:admin@ClawNanny.com) for details.

## License

ClawNanny is **proprietary freeware**.&nbsp;  The Community and Pro editions are free to download, install, and use under the terms above **with free support**.&nbsp;  The pre-paid Enterprise edition license fee gets additional functionality and support.

The source code is **not** open.&nbsp;  See [LICENSE](LICENSE) for full terms.

## Why a closed-source repo on GitHub?

1.&nbsp; **Open source invites everyone to change the source code.** &nbsp;  Open System Applications LLC is a small team.&nbsp; We can't sustain the review and triage overhead of a fully-public source tree.&nbsp;  That's not where we want to focus our attention.
2.&nbsp; **Releases hosting.** &nbsp;  GitHub Releases is a free, fast, worldwide CDN for the installer.&nbsp;  Hosting downloadable builds here means downloads stay fast even during traffic spikes, and every release has a stable URL.
3.&nbsp; **A real issue tracker and discussion forum.** &nbsp;  You can [report bugs and submit change requests](https://ClawNanny.com/Change_request), and you're free to discuss ClawNanny on [GitHub Discussions](https://github.com/ClawNanny/clawnanny/discussions).

The application source itself is not published.&nbsp;  ClawNanny depends on a number of excellent open-source projects (OpenClaw, Hermes-Agent, and others).&nbsp; Credit and links to those projects appear in the application's About dialog.

## Support

- **Bug reports and change requests:** [Submit a change request](https://ClawNanny.com/Change_request) on ClawNanny.com.
- **Security vulnerabilities:**&nbsp; Please use the private channel described in [SECURITY.md](SECURITY.md).
- **Everything else:** `admin@ClawNanny.com`.

## Publisher

ClawNanny is published by [**Open System Applications LLC**](https://ClawNanny.com/MD_doc?file=/static/docs/OpenSystemApps.md) (United States).&nbsp;  The Windows installer is code-signed via Azure Trusted Signing.&nbsp;  The macOS installer is signed with an Apple Developer ID and notarized.
