# Awesome-Code-Review-Automation

## Top Code Review Automation Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on AI Pull Request Review, Static Analysis, Quality Gates, Automated Feedback & Developer Workflow Acceleration*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Code Review Automation**. These systems automatically analyze pull/merge requests — suggesting improvements, catching bugs and security issues, enforcing standards, and reducing the manual burden on human reviewers.

**Examples** include Graphite, CodeRabbit, CodeScene, Codacy, SonarQube, Reviewable, PullRequest.com, Qodo (CodiumAI), DeepSource, and related AI review tools (the category leaders).

**Open-source emphasis**: Code review automation has excellent open-source options. **PR-Agent**, **SonarQube Community**, **Semgrep**, **CodeQL**, **Danger**, **Reviewdog**, and multi-agent review projects provide strong self-hosted and CI-native capabilities. This section is expanded with these tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Graphite](https://graphite.dev/)** | Developer productivity platform focused on stacked PRs with integrated AI review — optimized for fast, low-noise feedback in modern Git workflows. | Free forever tier; Paid plans start at **$20/user/month** (Starter) or **$40/user/month** (Team, billed annually) | **Hobby Plan (Free forever):** Free for personal repos with Graphite CLI, VS Code extension, and limited AI review/Graphite Agent runs.<br>**Trial:** 30-day free trial of Team plan (no credit card required). |
| **[CodeRabbit](https://www.coderabbit.ai/)** | Widely adopted AI code review GitHub/GitLab app that posts inline comments and PR summaries with minimal setup and continuous incremental review. | Free forever tier; Paid plans start at **$24/contributing developer/month** (Pro, billed annually) or **$30/month** (monthly) | **Free Forever Plan:** Free PR summaries on public/private repos; IDE/CLI review with rate limits; Free Pro+ features for Open Source.<br>**Trial:** 14-day free trial of Pro+ plan (no credit card required). |
| **[CodeScene](https://codescene.com/)** | Behavioral code analysis and technical-debt platform that surfaces hotspots and prioritizes review attention based on how code actually evolves. | Paid plans start at **€18/active author/month** (Standard, billed annually) or **€27/active author/month** (Pro, billed annually) | **Community Edition (Free forever):** Unlimited public/open-source repositories with Code Health insights and PR quality gates.<br>**Trial:** 14-day full-featured free trial for Standard or Pro (no credit card required). |
| **[Codacy](https://www.codacy.com/)** | Automated code review and static analysis platform with quality and security checks, plus AI-assisted review modes across many languages. | Free forever tier; Paid plans start at **$18/developer/month** (Team, billed annually) | **Developer / Open Source Plan (Free forever):** Free for open-source repositories and individual IDE extension use.<br>**Trial:** 14-day full-featured free trial for private repos (no credit card required). |
| **[SonarQube / SonarCloud](https://www.sonarsource.com/)** | Industry-standard static analysis and quality-gate platform (Cloud and self-hosted) used to enforce reliability, security, and maintainability policies at merge time. | Free forever tier; Paid plans start at **$32–$34/month** (Team tier on SonarCloud for up to 100k lines of code) | **Free Forever Tier:** Free for up to 50,000 LOC on private projects (up to 5 team members) and unlimited LOC for open-source public repositories.<br>**Self-hosted:** SonarQube Community Edition is 100% free and open-source. |
| **[Reviewable](https://reviewable.io/)** | Structured code review platform designed for thorough human + tool-assisted review workflows on GitHub. | Free forever tier; Paid plans start at **$16/contributor/month** (Business, billed annually) | **Free Forever Plan:** Free for all public repositories and personal private repositories on individual user accounts (unlimited reviews, 10MB file upload limit).<br>**Trial:** 30-day free trial of Business plan for organizations (no credit card required). |
| **[PullRequest.com](https://www.pullrequest.com/)** | On-demand expert code review service combined with tooling to improve review coverage and quality (now HackerOne Code). | Automated analysis starts at **$9/seat/month**; Managed review packages start at **$129/month** or custom quotes | **Free Code Quality Metrics:** Free dashboard metrics for teams.<br>**Trial / POC:** No self-serve trial; offers custom Proof-of-Concept (POC) and interactive guided product walkthroughs on request. |
| **[Qodo (CodiumAI)](https://www.qodo.ai/)** | AI code review and test-generation platform (including open-source PR-Agent lineage) focused on bugs, quality, security, and automated tests. | Free forever tier; Pro Team credit packs start at **$30/month** (~2,500 credits pool at $0.012/credit) | **Developer Plan (Free forever):** Free IDE plugins with ~250 credits/month; Free Open Source Plan for active GitHub public repos (100+ stars).<br>**Trial:** 14-day free trial with full feature access and unlimited usage. |
| **[DeepSource](https://deepsource.com/)** | Automated code review platform with static analysis, security rules, and Autofix capabilities across many languages. | Free forever tier; Paid plans start at **$24/active contributor/month** (Team, billed annually) or **$30/month** (monthly) | **Free Forever Plan:** Up to 3 private repositories, 3 team members, and 3 SCA targets; Free for public/open-source repos.<br>**Trial:** 14-day free trial of Team plan with full features and bundled AI Review credits. |

## Open-Source GitHub Projects
- **[PR-Agent (Qodo)](https://github.com/qodo-ai/pr-agent)**  
  Popular open-source AI pull request review agent — self-hostable with your own LLM keys, supports GitHub/GitLab/Bitbucket, and provides configurable review, improvement, and description generation.

- **[SonarQube Community Edition](https://www.sonarsource.com/open-source-editions/)**  
  Free, self-hosted static analysis and quality-gate engine with broad language support — the foundation of many automated review pipelines.

- **[Semgrep](https://github.com/semgrep/semgrep)**  
  Fast open-source static analysis for 30+ languages; runs in CI and on PRs to enforce security and coding standards with custom rules.

- **[CodeQL](https://github.com/github/codeql)**  
  Semantic code analysis engine with open queries; powers GitHub code scanning and advanced automated review for security and correctness.

- **[Danger](https://danger.systems/)**  
  Open-source tool that runs custom Ruby/JS/Python rules on PRs to enforce team conventions and leave automated review comments.

- **[Reviewdog](https://github.com/reviewdog/reviewdog)**  
  Automated code review dog that posts findings from any linter or analyzer as PR comments across GitHub, GitLab, and Bitbucket.

- **[Multi-agent open code reviewers](https://github.com/)**  
  Community LangGraph and multi-agent projects that run parallel specialist agents (security, quality, tests, docs) on pull requests.

- **[ESLint, Ruff, and language linters in CI](https://github.com/)**  
  Open linters wired into PR checks to provide the first layer of automated style and bug feedback.

- **[GitHub Actions / GitLab CI review templates](https://github.com/)**  
  Reusable workflows that combine Semgrep, SonarQube CE, secret scanners, and AI agents into one review pipeline.

- **[AI-surface and specialized PR governors](https://github.com/)**  
  Open tools that flag high-risk changes (e.g. new LLM/agent surfaces) at PR time for extra review.

### Additional Strong Open-Source Options
- Combining PR-Agent + Semgrep + SonarQube CE for AI narrative review plus deterministic quality/security gates.
- Using Reviewdog to unify any CLI analyzer output into consistent PR annotations.
- Local LLM-backed review bots for air-gapped or high-privacy environments.
- Custom Danger rules encoding org-specific architecture and style policies.
- Open dashboard aggregation of historical PR review metrics.

**Frameworks for building custom systems**: Run **Semgrep** and **SonarQube CE** (or CodeQL) as required CI checks, add **PR-Agent** or a multi-agent reviewer for natural-language feedback, and use **Danger**/**Reviewdog** for team-specific policy comments. Keep everything self-hosted or in your own runners for full control of code and models. Commercial platforms (CodeRabbit, Graphite, DeepSource, Codacy, Qodo Cloud, SonarCloud) still excel at zero-config AI review, cross-repo policy, polished UX, and managed scaling for large engineering organizations.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Automated review tools can miss issues and produce false positives. They should augment, not replace, human judgment—especially for security-critical and architectural changes. AI reviewers may send code snippets to third-party models unless self-hosted; verify data-handling policies for proprietary codebases.
- Always keep analyzers and rule packs updated.

---
**Made for engineering teams who want faster, more consistent, and higher-signal code review.**
Let's keep automated review open, tunable, and under developer control.
