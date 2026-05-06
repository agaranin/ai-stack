# ai-stack

Personal APM package with AI agent tools.

## Tools

- Perplexity MCP Server: web research via `@perplexity-ai/mcp-server`. Requires `PERPLEXITY_API_KEY`.
- Context7 MCP Server: up-to-date code documentation via `@upstash/context7-mcp@latest`.
- Playwright MCP Server: browser automation via `@playwright/mcp@latest`, configured for headed mode.
- Obsidian CLI Skill: vault search, notes, backlinks, tags, tasks, properties, daily notes, bases, and templates via `obsidian` CLI.

## Setup

Replace `your_key_here` with your Perplexity API key.

### macOS

```sh
brew install apm
echo 'export PERPLEXITY_API_KEY="your_key_here"' >> ~/.zshrc
source ~/.zshrc
apm install agaranin/ai-stack
```

For reproducible installs, pin the package to a tag or commit SHA:

```sh
apm install agaranin/ai-stack#<tag-or-sha>
```

### Linux

```sh
echo 'export PERPLEXITY_API_KEY="your_key_here"' >> ~/.bashrc
source ~/.bashrc
apm install agaranin/ai-stack
```

### Windows PowerShell

```powershell
[Environment]::SetEnvironmentVariable("PERPLEXITY_API_KEY", "your_key_here", "User")
$env:PERPLEXITY_API_KEY = "your_key_here"
apm install agaranin/ai-stack
```

For Obsidian support, install the Obsidian CLI and check it with `obsidian version`.
