## Hi, I'm Eliot 👋

I build small research and developer tools in Python and JavaScript.

### Paper Radar

**[Paper Radar](https://github.com/Eliot5566/JEV-Paper-Radar)** turns plain-English
research interests into ranked paper reports and RSS feeds. It supports Jev and
Claude backends, with a CLI, GitHub Action and an uploadable Claude skill.
Python 3.11+, MIT, no runtime dependencies.

- **[Try the public examples](https://eliot5566.github.io/JEV-Paper-Radar/try/)** · **[繁體中文](https://eliot5566.github.io/JEV-Paper-Radar/try/?lang=zh)** — browse reports before installing, choose a research interest, and copy a ready-to-use prompt.
- **[Install in Claude](https://github.com/Eliot5566/JEV-Paper-Radar/blob/main/docs/claude-install.md)** · **[Download the upload ZIP](https://github.com/Eliot5566/JEV-Paper-Radar/releases/download/claude-skill-v0.1.0/paper-radar-claude.zip)** — upload and enable to try the offline demo or rank supplied abstracts in the current conversation, with no pip or separate API key. Normal Claude plan usage applies.
- [Claude API quickstart](https://github.com/Eliot5566/JEV-Paper-Radar/blob/main/docs/claude-quickstart.md) · [繁體中文教學](https://github.com/Eliot5566/JEV-Paper-Radar/blob/main/docs/claude-quickstart.zh-TW.md)
- [Ready-to-fork Claude example](https://github.com/Eliot5566/paper-radar-claude-example)
- [Read the public Jev feeds](https://eliot5566.github.io/JEV-Paper-Radar/public/) — no setup or key
- Try the fictional, offline demo: `python -m pip install paper-radar==0.2.0`, then `paper-radar demo`

The upload bundle was tested in a Claude web conversation with Opus 5.5:
a 44-paper fictional demo and a three-paper conversation report with HTML,
CSV, JSON and RSS. These are functionality checks, not accuracy benchmarks.
Scheduled CLI judging uses the separately billed Anthropic API. Claude scores
are self-reported; the Jev benchmark does not establish Claude accuracy.
Version 0.2.0 adds judging-request usage auditing, including repair and failed
attempts, and reports unknown costs when usage or rates are missing.

### Other projects

**[s1kit](https://github.com/Eliot5566/s1kit)** provides confidence-based routing
with Jev, local tests and threshold fitting. Check fitted thresholds on a separate
labelled batch before relying on their accuracy.

**[app-xray](https://github.com/Eliot5566/app-xray)** inspects Electron
applications and renders saved scan evidence. Installation currently uses the
documented source build.

Setup questions and concrete experience reports are welcome in each project's
issues or discussions.

[LinkedIn](https://www.linkedin.com/in/eliot-su-6a834227b) · [CakeResume](https://www.cakeresume.com/siang-yu-su)
