# zhengming-code-engineering

> **Code Engineering** — family index of the [zhengming-toolbox](https://github.com/chenhz01/zhengming-toolbox) (105 tools across neglected niches). Each tool: pure standard-library Python, CLI-first, 60+ self-test cases, CI-verified, score-first designed.

Code engineering gates and linters: CLI conventions, dependency budgets, PR sizing, doc freshness, upgrade risk, math prechecks.

## Tools in this family (9)

| Tool | What it does | Self-tests |
|---|---|---|
| [cli-help-spec](https://github.com/chenhz01/cli-help-spec) | Ten written conventions for CLI `--help` text — usage line, options · zero-anchor flagship | 60+ (CI) |
| [code-block-lang-check](https://github.com/chenhz01/code-block-lang-check) | Lint the language annotations on fenced code blocks in Markdown. · zero-anchor flagship | 60+ (CI) |
| [dependency-depth-budget](https://github.com/chenhz01/dependency-depth-budget) | Declare a budget for your dependency tree — depth, breadth and total nodes — and let a scanner measure the real tree a · zero-anchor flagship | 60+ (CI) |
| [math-render-precheck](https://github.com/chenhz01/math-render-precheck) | math-render-precheck is a static preflight for math in Markdown: it catches unpaired `$`/`$$`/`\(`/`\[` delimiters and · zero-anchor flagship | 60+ (CI) |
| [postmortem-template-lint](https://github.com/chenhz01/postmortem-template-lint) | A stdlib-only linter that checks blameless postmortem reports before you publish them. · zero-anchor flagship | 60+ (CI) |
| [deprecation-timeline-audit](https://github.com/chenhz01/deprecation-timeline-audit) | A stdlib-only auditor for API deprecation timelines: extracts sunset dates (ISO or prose like "June 1, 2027") from dec · zero-anchor flagship | 60+ (CI) |
| [pr-size-scorer](https://github.com/chenhz01/pr-size-scorer) | Grade how expensive a pull request is to review — before a human opens it. | 60+ (CI) |
| [release-notes-spec](https://github.com/chenhz01/release-notes-spec) | A validator that keeps your Markdown release notes honest. | 60+ (CI) |
| [upgrade-risk-grader](https://github.com/chenhz01/upgrade-risk-grader) | Grade how risky a dependency upgrade is *before* you run it. | 60+ (CI) |

## How to choose

Start from the tool that matches your pain; every README has a 60-word first page, a timed Quickstart, and a *When NOT to use* section. All tools are independent — install nothing, clone and run `python self_test.py`.

## Sibling families

[zhengming-agent-governance](https://github.com/chenhz01/zhengming-agent-governance) · [zhengming-security-compliance](https://github.com/chenhz01/zhengming-security-compliance) · [zhengming-data-integrity](https://github.com/chenhz01/zhengming-data-integrity) · [zhengming-ops-performance](https://github.com/chenhz01/zhengming-ops-performance) · [zhengming-content-docs](https://github.com/chenhz01/zhengming-content-docs)

## License & contact

All tools MIT — © zhengming contributors. These are developer tools, not professional advice. Contact: hcac4735@agent.qq.com
