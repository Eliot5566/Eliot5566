## Hi, I'm Eliot 👋

I build small research and developer tools in Python and JavaScript.

### Paper Radar

**[Paper Radar](https://github.com/Eliot5566/JEV-Paper-Radar)** turns plain-English
research interests into a daily paper page and RSS feed. It supports Jev and
Claude backends, with a CLI, GitHub Action and an optional Claude Code skill.
Python 3.11+, MIT, no runtime dependencies.

- [Claude quickstart](https://github.com/Eliot5566/JEV-Paper-Radar/blob/main/docs/claude-quickstart.md) · [繁體中文教學](https://github.com/Eliot5566/JEV-Paper-Radar/blob/main/docs/claude-quickstart.zh-TW.md)
- [Ready-to-fork Claude example](https://github.com/Eliot5566/paper-radar-claude-example)
- [Read the public Jev feeds](https://eliot5566.github.io/JEV-Paper-Radar/public/) — no setup or key
- Try the fictional, offline demo: `python -m pip install paper-radar==0.2.0`, then `paper-radar demo`

Claude judging uses the separately billed Anthropic API. Its scores are
self-reported; the Jev benchmark does not establish Claude accuracy.
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
