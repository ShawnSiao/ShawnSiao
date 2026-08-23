<div align="center">

# Shawn Siao

### Local-first AI Product Builder

Building practical AI software for Windows with Rust, TypeScript and Python.

[![Windows](https://img.shields.io/badge/Windows-local--first-0078D4?style=flat-square&logo=windows11&logoColor=white)](https://github.com/ShawnSiao?tab=repositories)
[![Rust](https://img.shields.io/badge/Rust-desktop%20core-000000?style=flat-square&logo=rust&logoColor=white)](https://github.com/ShawnSiao?tab=repositories&q=&type=source&language=rust)
[![TypeScript](https://img.shields.io/badge/TypeScript-product%20UI-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/ShawnSiao?tab=repositories&q=&type=source&language=typescript)
[![Python](https://img.shields.io/badge/Python-automation-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/ShawnSiao?tab=repositories&q=&type=source&language=python)

</div>

## Selected products

<table>
<tr>
<td width="50%" valign="top">

### [SiaoCut](https://github.com/ShawnSiao/siao-cut)

A Windows-local-first AI video editing workbench. It combines transcription, subtitle editing, translation and review while keeping remote AI output under explicit human control.

[Repository](https://github.com/ShawnSiao/siao-cut) · [Live browser demo](https://shawnsiao.github.io/siao-cut-hackathon-demo/)

</td>
<td width="50%" valign="top">

### [SiaoVPlay](https://github.com/ShawnSiao/siao-vplay)

A cross-language intelligent video player for Windows, built around local media libraries, subtitles, translation and learning workflows.

[Repository](https://github.com/ShawnSiao/siao-vplay) · [Live browser demo](https://shawnsiao.github.io/siao-vplay-hackathon-demo/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [VoiceVault](https://github.com/ShawnSiao/voicevault)

A local-first public-content archive and evidence-grounded personal knowledge base, with explicit data and security boundaries.

[Repository](https://github.com/ShawnSiao/voicevault)

</td>
<td width="50%" valign="top">

### [China ICH Map](https://github.com/ShawnSiao/intangible-cultural-heritage-static)

A static, public-facing map for exploring China's intangible cultural heritage by place, designed with a reviewed public-data boundary.

[Repository](https://github.com/ShawnSiao/intangible-cultural-heritage-static) · [Explore the map](https://shawnsiao.github.io/intangible-cultural-heritage-static/)

</td>
</tr>
</table>

## Open-source contributions

I contribute code, documentation and Chinese localization to projects I actually use:

- [OpenAI Agents SDK for Python](https://github.com/openai/openai-agents-python/pulls?q=is%3Apr+author%3AShawnSiao) — documentation and example fixes
- [Hugging Face Agents Course](https://github.com/huggingface/agents-course/pulls?q=is%3Apr+author%3AShawnSiao) — Simplified Chinese translation and documentation improvements
- [Apache ShenYu](https://github.com/apache/shenyu/pulls?q=is%3Apr+author%3AShawnSiao) — client, integration-test and code improvements
- [LeRobot documentation](https://github.com/tc-huang/lerobot/pulls?q=is%3Apr+author%3AShawnSiao) — Simplified Chinese simulation and inference guides

## Issue reports & security-tooling reliability

I also file reproducible issue reports with deterministic evidence, then follow fixes through review and release:

- [openai/codex-security#31](https://github.com/openai/codex-security/issues/31) — found queued full session-tree rescans that could delay cost-budget enforcement; closed as completed with a contributor fix
- [openai/codex-security#30](https://github.com/openai/codex-security/issues/30) — reported corrupted multiscan artifacts being treated as completed and skipped; currently an open P1 bug
- [openai/codex-security#211](https://github.com/openai/codex-security/issues/211) — reported cleanup failures that can mask a scan outcome and suppress its repository receipt; currently an open P1 bug
- [openai/codex-security#32](https://github.com/openai/codex-security/issues/32) — reproduced a Windows CRLF package-validation failure; the fix landed in PR #436 and I verified it in the published 0.1.17 package
- [OpenAI Codex issue reports](https://github.com/openai/codex/issues?q=is%3Aissue+author%3AShawnSiao) — documentation drift, runtime requirements and compatibility regressions

## More work

- [siao-skills](https://github.com/ShawnSiao/siao-skills) — reusable Agent Skills for research, writing, visualization and automation
- [Personal Knowledge Site](https://shawnsiao.github.io/personal-knowledge-site/) — practical notes and reusable engineering knowledge
- [Village of a Thousand Words](https://shawnsiao.github.io/village-of-a-thousand-words/) — an interactive Chinese learning experience

## How I build

- Start from a real user workflow and ship something runnable.
- Prefer local-first architecture when privacy, large media or user control matters.
- Keep AI suggestions reviewable instead of silently applying model output.
- Treat demos, tests, documentation and release boundaries as part of the product.

<div align="center">

Building useful software, documenting the decisions, and contributing the fixes back.

</div>
