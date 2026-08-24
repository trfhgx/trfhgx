# Mahy B.

I build AI systems, agent tooling, and developer infrastructure used by other engineers.

Most of my work is around making agents more useful in real workflows. Giving them better ways to review work, find what was missed, reuse what they learn, follow a specific writing system, and work across large codebases without wasting context.

## Selected work

### [Byto](https://github.com/trfhgx/byto)

Turns the usual Google Cloud + Vertex AI setup into one command.

Byto configures what you need, exposes Gemini through an OpenAI-compatible API, and lets existing tools switch over without changing their integration.

Built in Go with streaming, automatic model discovery, concurrency control, load testing, and Cloud Run deployment.

### [Codex PR Debate Bot](https://github.com/trfhgx/codex-pr-debate-bot)

Turns pull requests into a debate before the agent starts coding.

Instead of letting an agent rush straight into implementation, it grills the plan first: challenges assumptions, exposes blind spots, forces unclear requirements into the open, and keeps the reasoning inside the PR.

You get better decisions, fewer dumb mistakes, and a much better understanding of the code you're about to change.

### [nginxconf-wizard](https://github.com/trfhgx/nginxconf-wizard)

Tooling for generating, validating, and hardening Nginx configurations for VPS and bare-metal deployments.

## Building now

I'm mostly interested in agents that get more useful the longer you run them.

That currently means systems that review ongoing engineering and product work, catch gaps, research better approaches, and surface useful next moves.

I'm also working on agents that build and revise their own reusable skills during normal use, and on better ways to make models reliably follow a writing system instead of drifting back toward generic AI output.

**RepoTracer** is a repository-exploration mcp for coding agents

A stronger coding model delegates repository search to smaller models, which explore the codebase and return only the relevant files, line ranges, and findings. This keeps broad search out of the primary model's context and lets it spend more of its budget on reasoning and implementation. (up to -60% cost reduction with no quality loss)


Most of my systems work is in Go, Rust, Python, TypeScript, and Swift.

[X](https://x.com/_mahybe)
