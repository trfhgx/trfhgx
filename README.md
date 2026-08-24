# Mahy B.

`I build tools and systems around AI, mostly where the models are already good enough but the software around them isn't.`

`That usually means agents, automation, infrastructure, developer tools, and products that remove setup, wasted model work, or repetitive human work.`

## Selected work

### [Byto](https://github.com/trfhgx/byto)

`Turns the usual Google Cloud + Vertex AI setup into one command.`

`Byto handles the setup, exposes Gemini through an OpenAI-compatible API, and lets existing tools switch over without rebuilding their integration.`

`Built in Go with streaming, automatic model discovery, concurrency control, load testing, and Cloud Run deployment.`

### [Codex PR Debate Bot](https://github.com/trfhgx/codex-pr-debate-bot)

`Makes coding agents defend their approach before touching the code.`

`It grills the plan first: challenges assumptions, catches blind spots, and forces vague requirements into the open inside the pull request.`

`Instead of letting an agent run blindly, you get to challenge its reasoning before implementation and learn from the decisions it makes.`

### [nginxconf-wizard](https://github.com/trfhgx/nginxconf-wizard)

`Generate and harden Nginx configurations without rebuilding the same deployment setup by hand.`

`Handles common presets, TLS, reverse proxies, security headers, rate limiting, compression, and configuration checks.`

## Building now

`I'm especially interested in agents that become more useful the longer you run them.`

`I'm building systems that review ongoing engineering and product work, catch gaps, research better approaches, and surface useful next moves without needing every step prompted manually.`

`I'm also experimenting with agents that build and revise reusable skills as they work, so useful behavior can accumulate during normal use rather than requiring another training run.`

`Another direction is writing. Models can imitate a style, but they tend to drift back toward the same generic voice. I'm working on ways to make writing systems explicit, reusable, and persistent enough for agents to actually stick to them.`

### RepoTracer

`RepoTracer is an MCP repository explorer for coding agents based on the FastContext approach.`

`The primary model delegates repository search to cheaper models, which explore the codebase and return the relevant files, line ranges, and findings. This keeps more of the expensive model's context and inference budget focused on reasoning and implementation.`

`Early benchmarks show up to 60% lower model cost with no measurable quality loss.`

**Public soon.**

---

`Most of my systems work is in Go, Rust, Python, TypeScript, and Swift.`

[X](https://x.com/_mahybe)
