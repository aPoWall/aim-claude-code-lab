# Claude Code Lab — AI Mindset

Interactive Claude Code course with a live terminal emulator in the browser.

**Live:** [aim-cc-lab.netlify.app](https://aim-cc-lab.netlify.app)

## What is this

A web-based interactive course that teaches Claude Code through hands-on terminal experience. Built for the AI Mindset team with real vault structure, working skills, and guided onboarding.

## Features

- **xterm.js terminal** — real terminal emulator (same as VS Code) with ANSI colors, cursor, scrollback
- **Virtual filesystem** — actual AI Mindset vault structure with `ls`, `cd`, `cat`, `tree`, `grep`, `find`
- **16+ working skills** — `/pos-audit`, `/vox`, `/AIM-pm`, `/research`, `/calendar` and more
- **13 lessons** in 5 modules — from installation to Personal Operating System
- **Guided onboarding** — step-by-step hints for new users
- **Progress tracking** — localStorage remembers completed lessons
- **Tab completion** — Tab for skills and paths, arrows for history

## Quick Start

### Web (demo terminal)
Open [aim-cc-lab.netlify.app](https://aim-cc-lab.netlify.app) and type `help`.

### Real Claude Code
```bash
# Install
npm install -g @anthropic-ai/claude-code

# Authenticate
claude login

# Clone and run
git clone https://github.com/aPoWall/aim-claude-code-lab
cd aim-claude-code-lab
claude
```

Then type: `lesson 1`

## Terminal Commands

| Command | Description |
|---------|-------------|
| `help` | All commands and skills |
| `ls [path]` | List directory |
| `cd <path>` | Change directory |
| `cat <file>` | Read file |
| `tree` | Directory tree |
| `grep <text>` | Search in files |
| `find <name>` | Find paths |
| `claude` | Launch Claude Code |
| `setup` | Installation guide |
| `lesson <n>` | Open lesson |
| `next` | Next lesson |
| `progress` | Show completion |
| `/skill-name` | Run a skill |

## Course Structure

| Module | Topic | Lessons |
|--------|-------|---------|
| 00 Setup | Installation, terminal basics | 2 |
| 01 Fundamentals | Agent dialog, files, CLAUDE.md | 3 |
| 02 Skills & MCP | Creating skills, MCP servers | 2 |
| 03 Team Workflows | Morning brief, Linear, Telegram | 3 |
| 04 Advanced | Sub-agents, hooks, POS | 3 |

## Tech

- Single-file HTML (no build step)
- [xterm.js](https://xtermjs.org/) v5.5 terminal emulator
- [xterm-addon-fit](https://www.npmjs.com/package/@xterm/addon-fit) for responsive sizing
- IBM Plex Mono + Space Grotesk fonts
- AI Mindset teal grid design system
- Deployed on Netlify

## Credits

Built by [AI Mindset](https://aimindset.org) team with Claude Code.

Inspired by [ccforpms.com](https://ccforpms.com/) (Claude Code for PMs by Carl Vellotti).

---

*AI Mindset · 2026*
