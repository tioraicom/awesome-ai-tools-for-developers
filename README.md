# Awesome AI Tools for Developers

**English** · [العربية](README.ar.md)

> A curated list of AI tools for coding, debugging, testing, DevOps, APIs, and software development.

<!-- counts:start -->
![Tools](https://img.shields.io/badge/tools-104-informational)
![Categories](https://img.shields.io/badge/categories-13-informational)
<!-- counts:end -->
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](LICENSE)

Every general AI list tells developers about the same chat assistant. This one does not. The
test for inclusion was whether a tool plugs into an actual development workflow: an editor, a
terminal, a pull request, a pipeline, or a running system. If its integration story is "paste
your code into the chat box", it is not here.

The categories follow the working day rather than the marketing category, which is why code
review, testing, and observability get as much room as code generation. Names change fast in
this space, and products that were renamed, absorbed, or retired are listed under what they
are called now, or not at all.

Maintained by [TiorAI](https://tiorai.com/), which catalogues AI tools for a living.

<!-- last-reviewed:start -->
**Last reviewed:** 2026-08-26
<!-- last-reviewed:end -->

## Contents

- [Editors and IDEs](#editors-and-ides)
- [Coding assistants](#coding-assistants)
- [Coding agents](#coding-agents)
- [Code review](#code-review)
- [Testing](#testing)
- [Debugging and observability](#debugging-and-observability)
- [Documentation](#documentation)
- [API development](#api-development)
- [Databases and SQL](#databases-and-sql)
- [DevOps and infrastructure](#devops-and-infrastructure)
- [Application security](#application-security)
- [Terminal and shell](#terminal-and-shell)
- [Frontend and UI generation](#frontend-and-ui-generation)
- [How tools are selected](#how-tools-are-selected)
- [Suggest a tool](#suggest-a-tool)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)
- [License](#license)
- [About TiorAI](#about-tiorai)

## Editors and IDEs

Development environments built around a model rather than bolting one on.

- **[Antigravity](https://antigravity.google/)** — Google's agent-first development environment, where the editor is one surface onto a working agent. `Freemium` `Windows` `macOS` `Linux`
- **[Cursor](https://cursor.com/)** — Editor built around codebase-aware chat and multi-file edits, and the most widely adopted of these. `Freemium` `Windows` `macOS` `Linux` · [free vs paid](https://tiorai.com/compare/cursor-ai-free-vs-paid/)
- **[Devin Desktop](https://devin.ai/)** — Cognition's desktop environment, formerly Windsurf, pairing an editor with its autonomous agent. `Paid` `Windows` `macOS` `Linux`
- **[Firebase Studio](https://firebase.studio/)** — Google's browser workspace for building and deploying full-stack applications with an agent attached. `Freemium` `Web`
- **[JetBrains AI Assistant](https://www.jetbrains.com/ai-ides/)** — Assistant wired into JetBrains IDEs, using the same index that powers their refactoring tools. `Freemium` `JetBrains` · [vs Copilot](https://tiorai.com/compare/copilot-vs-jetbrains-ai/)
- **[Kiro](https://kiro.dev/)** — AWS editor that works from written specifications, generating requirements and design before code. `Freemium` `Windows` `macOS` `Linux`
- **[Replit](https://replit.com/)** — Browser development environment where an agent can build, run, and deploy a project end to end. `Freemium` `Web` `iOS` `Android` · [vs Bolt](https://tiorai.com/compare/replit-ai-vs-bolt-new/)
- **[Trae](https://www.trae.ai/)** — ByteDance editor with a builder mode that scaffolds a project from a description. `Freemium` `Windows` `macOS` `Linux`
- **[Zed](https://zed.dev/)** — Native editor written in Rust, with agent panels and collaborative editing built into the core. `Open Source` `Windows` `macOS` `Linux`

## Coding assistants

Completion and chat inside the editor you already use.

- **[Amazon Q Developer](https://aws.amazon.com/q/developer/)** — AWS assistant for completion, upgrades, and reasoning about resources in an AWS account. `Freemium` `CLI` `VS Code` `JetBrains`
- **[Augment Code](https://www.augmentcode.com/)** — Assistant built around indexing very large repositories, aimed at codebases too big to fit in context. `Paid` `CLI` `VS Code` `JetBrains`
- **[Continue](https://continue.dev/)** — Open-source completion and chat you point at any model, hosted or running locally. `Open Source` `VS Code` `JetBrains`
- **[GitHub Copilot](https://github.com/features/copilot)** — Completion, chat, and pull request assistance across common editors and on GitHub itself. `Freemium` `CLI` `VS Code` `JetBrains` · [free vs pro](https://tiorai.com/compare/github-copilot-free-vs-pro/)
- **[Pieces](https://pieces.app/)** — Local snippet and context manager that remembers what you were working on across tools. `Freemium` `Windows` `macOS` `Linux` `VS Code` `JetBrains`
- **[Qodo](https://www.qodo.ai/)** — Generates tests and reviews pull requests, with the free tier aimed at individual developers. `Freemium` `Web` `VS Code` `JetBrains`
- **[Sourcegraph Cody](https://sourcegraph.com/docs/cody)** — Enterprise assistant grounded in a whole-organisation code index rather than one repository. `Paid` `Web` `VS Code` `JetBrains`
- **[Tabnine](https://www.tabnine.com/)** — Completion with a self-hosted deployment option, which is often the deciding factor for regulated teams. `Freemium` `VS Code` `JetBrains` · [vs GitHub Copilot](https://tiorai.com/compare/tabnine-vs-github-copilot/)

## Coding agents

Given a task and a repository, these work through it and come back with a diff.

- **[Aider](https://aider.chat/)** — Terminal agent that edits files in a local repository and commits each change separately. `Open Source` `CLI` · [vs Cursor](https://tiorai.com/compare/cursor-ai-vs-aider/)
- **[Amp](https://ampcode.com/)** — Agentic coding tool from the original Sourcegraph founders, now an independent product. `Paid` `CLI` `VS Code`
- **[Claude Code](https://www.claude.com/product/claude-code)** — Anthropic's terminal agent, which explores a codebase, edits files, and runs the tests. `Paid` `CLI` `VS Code` `JetBrains` · [vs GitHub Copilot](https://tiorai.com/compare/github-copilot-vs-claude-code/)
- **[Cline](https://cline.bot/)** — VS Code agent that shows a plan, runs commands, and asks before each file write. `Open Source` `VS Code`
- **[Codex CLI](https://learn.chatgpt.com/docs/codex/cli)** — OpenAI's terminal agent, running locally against your repository with a sandboxed execution mode. `Open Source` `CLI`
- **[Jules](https://jules.google/)** — Google's asynchronous agent, which clones a repository into a cloud VM and returns a diff. `Freemium` `Web`
- **[OpenHands](https://www.openhands.dev/)** — Open-source agent that opens files, runs tests, and iterates inside a sandbox you control. `Open Source` `Web` `CLI`
- **[Roo Code](https://github.com/RooCodeInc/Roo-Code)** — VS Code agent with distinct modes for architecture, implementation, and debugging. `Open Source` `VS Code`
- **[SWE-agent](https://swe-agent.com/)** — Research agent for fixing GitHub issues, and the implementation most benchmarks are measured against. `Open Source` `CLI`

## Code review

Review that runs on the pull request, before a human opens it.

- **[Bito](https://bito.ai/)** — Pull request reviewer with static analysis and dependency checks folded into the same comment thread. `Freemium` `Web` `CLI` `VS Code`
- **[Codacy](https://www.codacy.com/)** — Quality and security gate across many languages, now with model-assisted fix suggestions. `Freemium` `Web`
- **[CodeAnt AI](https://www.codeant.ai/)** — Flags defects and policy violations on incoming pull requests, deployable inside your own network. `Paid` `Web`
- **[CodeRabbit](https://www.coderabbit.ai/)** — Leaves inline review comments on every pull request, with a summary of what changed and why. `Freemium` `Web` `VS Code`
- **[Ellipsis](https://www.ellipsis.dev/)** — Opens a follow-up pull request that fixes what its review found, rather than only commenting. `Paid` `Web`
- **[Greptile](https://www.greptile.com/)** — Reviews pull requests using a graph of the whole codebase, so it can flag cross-file breakage. `Paid` `Web` `API`
- **[PR-Agent](https://github.com/The-PR-Agent/pr-agent)** — Answers describe, review, and improve commands on a pull request, run from your own CI or a shell. `Open Source` `CLI`
- **[Sourcery](https://sourcery.ai/)** — Suggests refactors in the editor and on pull requests, with a strong focus on Python. `Freemium` `Web` `VS Code` `JetBrains`

*More: [AI code review tools on TiorAI](https://tiorai.com/tool-category/ai-code-review/)*

## Testing

Generating tests, and keeping end-to-end suites from breaking on every layout change.

- **[Antithesis](https://antithesis.com/)** — Deterministic simulation testing that hunts for rare concurrency and state bugs, then replays them exactly. `Paid` `Web` `API`
- **[Applitools](https://applitools.com/)** — Visual regression testing that compares rendered pages the way a person would, not pixel by pixel. `Freemium` `Web` `API` `CLI`
- **[Diffblue Cover](https://www.diffblue.com/)** — Writes Java unit tests automatically, aimed at legacy codebases with no coverage at all. `Freemium` `CLI` `JetBrains`
- **[Meticulous](https://www.meticulous.ai/)** — Records real user sessions and replays them to catch visual and behavioural regressions. `Paid` `Web`
- **[Momentic](https://momentic.ai/)** — End-to-end tests written in plain language, which survive selector changes better than scripted ones. `Freemium` `Web` `CLI`
- **[QA Wolf](https://www.qawolf.com/)** — End-to-end coverage delivered as a service, with test maintenance handled rather than left to you. `Paid` `Web`
- **[Qodo Cover](https://github.com/qodo-ai/qodo-cover)** — Generates tests and keeps only those that actually raise measured coverage. `Open Source` `CLI`
- **[Reflect](https://reflect.run/)** — Browser-recorded regression tests that a non-engineer can create and an engineer can trust. `Paid` `Web`

*More: [AI software testing tools on TiorAI](https://tiorai.com/tool-category/software-testing/)*

## Debugging and observability

Working out what broke in production, and why.

- **[Datadog Bits AI](https://www.datadoghq.com/product/ai/bits-ai-agents/)** — Investigates incidents across Datadog telemetry and drafts a summary of what it found. `Paid` `Web`
- **[Grafana Assistant](https://grafana.com/products/cloud/ai-tools-for-grafana/)** — Builds dashboards and queries from a description, inside a stack many teams already run. `Freemium` `Web`
- **[Honeycomb](https://www.honeycomb.io/)** — Observability built for high-cardinality data, with natural-language querying over traces. `Freemium` `Web` `API`
- **[Incident.io](https://incident.io/)** — Incident management that drafts updates and post-incident reviews from the response timeline. `Freemium` `Web` `API`
- **[Jam](https://jam.dev/)** — Captures a bug report with console logs, network calls, and reproduction steps in one click. `Freemium` `Web` `Browser Extension`
- **[Sentry](https://sentry.io/)** — Error tracking with automated root-cause analysis and suggested fixes on incoming issues. `Freemium` `Web` `API`
- **[Traversal](https://www.traversal.com/)** — Traces an incident back through service dependencies to the change that most likely caused it. `Paid` `Web`

## Documentation

Writing docs, and keeping them true after the code changes.

- **[Docusaurus](https://docusaurus.io/)** — Documentation site generator with search and versioning, and the default for many open-source projects. `Open Source` `Web` `CLI`
- **[Fern](https://buildwithfern.com/)** — Generates SDKs and API documentation from an OpenAPI specification, keeping both in step. `Freemium` `Web` `CLI`
- **[GitBook](https://www.gitbook.com/)** — Hosts documentation and reports which reader questions the published pages failed to answer. `Freemium` `Web` `API`
- **[Kapa.ai](https://www.kapa.ai/)** — Answers developer questions from your existing docs, and reports which questions it could not answer. `Paid` `Web` `API`
- **[Mintlify](https://mintlify.com/)** — Documentation platform whose built-in assistant answers from your published pages, with usage analytics. `Freemium` `Web` `CLI`
- **[readme.so](https://readme.so/)** — Assembles a project README from standard sections, useful for getting a first version out. `Free` `Web`
- **[Scalar](https://scalar.com/)** — Open-source API reference and client generated from an OpenAPI document. `Open Source` `Web` `CLI`
- **[Swimm](https://swimm.io/)** — Ties documentation to specific code so it fails a check when the code moves underneath it. `Freemium` `Web` `VS Code` `JetBrains`

*More: [AI developer documentation tools on TiorAI](https://tiorai.com/tool-category/ai-developer-docs/)*

## API development

Designing, testing, and shipping APIs.

- **[Apidog](https://apidog.com/)** — Design, mock, test, and document an API in one tool rather than four. `Freemium` `Web` `Windows` `macOS` `Linux`
- **[Bruno](https://www.usebruno.com/)** — Offline API client that stores collections as plain files in your repository, so they diff. `Open Source` `Windows` `macOS` `Linux` `CLI`
- **[Hoppscotch](https://hoppscotch.io/)** — Lightweight open-source API client that runs in a browser tab and can be self-hosted. `Open Source` `Web` `CLI`
- **[Postman](https://www.postman.com/)** — The long-standing API platform, with generated tests, documentation, and collection assistance. `Freemium` `Web` `Windows` `macOS` `Linux`
- **[Redocly](https://redocly.com/)** — Lints OpenAPI documents against a style guide and publishes reference docs from them. `Freemium` `Web` `CLI`
- **[Speakeasy](https://www.speakeasy.com/)** — Generates idiomatic client SDKs in several languages from an OpenAPI specification. `Freemium` `Web` `CLI`
- **[Stainless](https://www.stainless.com/)** — SDK generation used by several major model providers for their own official client libraries. `Freemium` `Web` `CLI`
- **[Zuplo](https://zuplo.com/)** — Programmable API gateway with documentation and key management generated from the same spec. `Freemium` `Web` `API`

*More: [AI API tools on TiorAI](https://tiorai.com/tool-category/ai-api/)*

## Databases and SQL

Writing queries, shaping schemas, and not dropping the production table.

- **[AI2sql](https://www.ai2sql.io/)** — Turns a plain description into SQL for several dialects, aimed at occasional query writers. `Freemium` `Web`
- **[Bytebase](https://www.bytebase.com/)** — Schema migration and access control for databases, with review policies applied before a change lands. `Freemium` `Web` `CLI`
- **[Chat2DB](https://chat2db.ai/)** — Database client that turns plain descriptions into SQL and explains query plans. `Freemium` `Web` `Windows` `macOS` `Linux`
- **[DBeaver](https://dbeaver.io/)** — Universal database client with query assistance, and the open-source edition covers most needs. `Open Source` `Windows` `macOS` `Linux`
- **[Neon](https://neon.com/)** — Serverless Postgres with instant branching, which makes agent-generated migrations safe to try. `Freemium` `Web` `API` `CLI`
- **[pgAdmin](https://www.pgadmin.org/)** — The long-standing Postgres administration client, with query tooling and a visual explain plan. `Open Source` `Web` `Windows` `macOS` `Linux`
- **[Supabase](https://supabase.com/)** — Postgres platform with auth, storage, and an assistant that writes SQL and row-level security policies. `Freemium` `Web` `API` `CLI`
- **[Vanna](https://vanna.ai/)** — Open-source text-to-SQL you train on your own schema and past queries. `Open Source` `API` `CLI`

## DevOps and infrastructure

Pipelines, containers, and infrastructure as code.

- **[Dagger](https://dagger.io/)** — Defines CI pipelines as code that runs identically on a laptop and on the CI runner. `Open Source` `API` `CLI`
- **[Depot](https://depot.dev/)** — Remote container and CI builds with persistent caching, aimed squarely at build times. `Freemium` `Web` `CLI`
- **[Kubiya](https://www.kubiya.ai/)** — Answers infrastructure questions and runs approved operational tasks from within Slack. `Paid` `Web` `API`
- **[Pulumi](https://www.pulumi.com/)** — Infrastructure as code in general-purpose languages, with an assistant that generates the resources. `Freemium` `Web` `CLI`
- **[Railway](https://railway.com/)** — Deployment platform that infers build and runtime configuration instead of asking for it. `Freemium` `Web` `CLI`
- **[Spacelift](https://spacelift.io/)** — Infrastructure-as-code orchestration with policy checks that run before a plan is applied. `Freemium` `Web` `CLI`
- **[Terramate](https://terramate.io/)** — Orchestration and drift detection over existing Terraform and OpenTofu stacks. `Freemium` `Web` `CLI`

*More: [AI DevOps tools on TiorAI](https://tiorai.com/tool-category/ai-devops-tools/)*

## Application security

Finding vulnerabilities in code and dependencies, and fixing them.

- **[Aikido Security](https://www.aikido.dev/)** — Consolidates code, dependency, container, and cloud scanning, with noise filtering as the main selling point. `Freemium` `Web` `CLI`
- **[Corgea](https://corgea.com/)** — Triages static analysis findings and proposes patches, cutting the false-positive queue down. `Freemium` `Web` `CLI`
- **[Endor Labs](https://www.endorlabs.com/)** — Dependency analysis that checks whether a vulnerable function is actually reachable from your code. `Paid` `Web` `CLI`
- **[GitGuardian](https://www.gitguardian.com/)** — Detects committed secrets across repositories and history, with remediation workflows attached. `Freemium` `Web` `CLI`
- **[Semgrep](https://semgrep.dev/)** — Pattern-based static analysis with rules that read like the code they match. `Open Source` `Web` `CLI` `VS Code`
- **[Snyk](https://snyk.io/)** — Scans code, dependencies, containers, and infrastructure as code, with generated fix pull requests. `Freemium` `Web` `CLI` `VS Code` `JetBrains`
- **[Socket](https://socket.dev/)** — Watches dependency updates for supply-chain behaviour changes rather than only known advisories. `Freemium` `Web` `CLI`
- **[Trivy](https://trivy.dev/)** — Open-source scanner for containers, filesystems, and repositories, easy to drop into any pipeline. `Open Source` `CLI`

## Terminal and shell

The command line, with a model behind it.

- **[aichat](https://github.com/sigoden/aichat)** — Single-binary command-line client for many model providers, with shell command generation built in. `Open Source` `CLI`
- **[Butterfish](https://butterfi.sh/)** — Wraps your existing shell so a prompt and a command share the same session and history. `Open Source` `macOS` `Linux` `CLI`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** — Google's open-source terminal agent, with a generous free tier for personal accounts. `Open Source` `CLI`
- **[mods](https://github.com/charmbracelet/mods)** — Pipes command output through a model, so it composes with everything else in a shell. `Open Source` `CLI`
- **[Nexus Shell](https://nexusshell.app/)** — Native macOS SSH workspace with optional terminal AI for explaining remote command output alongside SFTP, Docker, and server monitoring. `Freemium` `macOS`
- **[OpenCode](https://opencode.ai/)** — Terminal coding agent with a client-server split, so you can drive a remote session from anywhere. `Open Source` `CLI`
- **[Shell GPT](https://github.com/TheR1D/shell_gpt)** — Generates and runs shell commands from a description, without leaving the prompt. `Open Source` `CLI`
- **[Warp](https://www.warp.dev/)** — Terminal with block-based output, command search, and an agent that can run multi-step work. `Freemium` `Windows` `macOS` `Linux`
- **[Wave Terminal](https://www.waveterm.dev/)** — Open-source terminal with inline file previews, graphs, and an assistant in the same pane. `Open Source` `Windows` `macOS` `Linux`

## Frontend and UI generation

Turning a design or a description into interface code you can keep.

- **[Bolt](https://bolt.new/)** — Prompt to a running web application in the browser, with the project editable and deployable. `Freemium` `Web`
- **[Builder.io](https://www.builder.io/)** — Converts Figma frames into components in your own framework and design system. `Freemium` `Web` `API`
- **[Locofy](https://www.locofy.ai/)** — Turns Figma designs into React, Next.js, or React Native code with responsive behaviour preserved. `Freemium` `Web`
- **[Lovable](https://lovable.dev/)** — Builds full-stack applications from conversation, with the generated repository synced to GitHub. `Freemium` `Web`
- **[Magic Patterns](https://www.magicpatterns.com/)** — Generates React components from a prompt or a screenshot, with a diff against your design system. `Freemium` `Web`
- **[Onlook](https://onlook.com/)** — Open-source visual editor for React projects, editing the real code behind the rendered page. `Open Source` `Web` `Windows` `macOS`
- **[Subframe](https://www.subframe.com/)** — Visual editor that outputs React and Tailwind matching your own component library. `Freemium` `Web`
- **[v0](https://v0.app/)** — Vercel's generator for React interfaces, producing shadcn/ui and Tailwind components you can paste. `Freemium` `Web` · [vs Replit](https://tiorai.com/compare/replit-ai-vs-v0/)

## How tools are selected

A tool qualifies when a developer would use it while building, testing, shipping, or
operating software, and when it plugs into a place that work already happens: an editor, the
terminal, a pull request, a CI pipeline, or a production system.

The third requirement matters most: the tool's value has to come from a model doing something
a rule-based tool could not. A linter is not listed because it is fast. A review tool is
listed when it catches things a linter structurally cannot.

What does not qualify, regardless of quality: a general chat assistant with no
development-specific integration, a writing or design tool that developers happen to use, a
model provider whose product is inference rather than development, and a no-code builder
aimed at people who are not writing software.

Open source is labelled where the licence is OSI-approved. A great deal of developer tooling
is source-available under a licence with a commercial restriction, which is not the same
thing and does not get the label.

Entries are ordered alphabetically inside each category. Position carries no meaning, and
there is no paid placement, sponsorship, or affiliate link anywhere in this repository.

## Suggest a tool

- [Suggest a tool](../../issues/new?template=suggest-a-tool.yml)
- [Report a broken link](../../issues/new?template=report-a-broken-link.yml)

The most useful correction in this repository is a rename. Products in this space get
acquired and rebranded constantly, and a list carrying a dead product name is worse than one
missing the product entirely.

If you work on a tool you are suggesting, say so in the form. It will not count against the
submission.

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) for the entry format and what gets declined. The
question that decides most submissions: where in a developer's workflow does this run? If the
answer is "in a browser tab, separately", it will usually be declined.

## Disclaimer

Everything listed is built and operated by a third party, not by TiorAI. Pricing, free tiers,
licences, and product names change without notice. Check the current licence before you build
on anything labelled `Open Source`, and check the current pricing before you commit a team to
anything. Listing here is editorial selection, not endorsement.

Tools that execute code, open pull requests, or act on infrastructure do so with whatever
access you grant them. Nothing here has been audited, and the usual review applies before you
give any of it write access to a repository or a production system.

## License

[CC BY 4.0](LICENSE). You may copy, adapt, and redistribute this list, including
commercially, as long as you credit TiorAI and indicate what you changed.

The licence covers the curation, the categories, and the descriptions. It does not cover the
TiorAI name and logo, and it does not cover the linked products, their trademarks, or their
code, which carry their own licences.

## About TiorAI

[TiorAI](https://tiorai.com/) is an AI tools directory covering far more products than this
list does, with profiles, comparisons, and alternatives pages.

This repository is its developer-facing slice, scoped to the working day of someone writing
software rather than to the AI market as a whole.

- [AI tools directory](https://tiorai.com/tools/)
- [Coding and development tools](https://tiorai.com/tool-category/coding-development/)
