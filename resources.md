# 🧰 Resources: where to find skills, plugins & connectors

A **skill** is a packaged workflow Claude follows. A **plugin** is a bundle you install once (it can include skills, commands, and MCP connectors). A **connector (MCP)** lets Claude use your tools and data. Here's where to get the good ones.

> ⚠️ Plugins can run code on your machine. **Only install from sources you trust**, and prefer official/verified ones.

---

## How to install anything (3 commands)

```
# 1. Add a marketplace (one time)
/plugin marketplace add anthropics/skills

# 2. Install what you want
/plugin install document-skills@anthropic-agent-skills

# 3. Browse & manage everything
/plugin
```

The official directory is built in, install from it directly:

```
/plugin install github@claude-plugins-official
```

---

## ⭐ Best skills to start with

| Skill | What it does | Where |
|---|---|---|
| **pptx** | beautiful slide decks | `anthropics/skills` |
| **docx · xlsx · pdf** | documents & spreadsheets | `anthropics/skills` |
| **frontend-design** | stunning websites (900k+ installs) | [claude.com/plugins](https://claude.com/plugins) |
| **frontend-slides** | web decks + a live URL | `zarazhangrui/frontend-slides` |
| **PitchCraft** | cinematic decks | [github.com/fnusatvik07/pitchcraft](https://github.com/fnusatvik07/pitchcraft) |
| **portfolio-pro** | resume → live website | [github.com/fnusatvik07/portfolio-pro-plugin](https://github.com/fnusatvik07/portfolio-pro-plugin) |
| **Skill Creator** | build your own skill | [claude.com/plugins](https://claude.com/plugins) |

---

## 🔌 Best connectors (official, MCP-backed)

Install in one line from the built-in `claude-plugins-official` marketplace, e.g. `/plugin install notion@claude-plugins-official`.

| Connector | For |
|---|---|
| **github** / **gitlab** | your code & pull requests |
| **notion** | your notes & docs |
| **slack** | your team messages |
| **google drive** | your files & folders |
| **figma** | your designs |
| **linear** / **atlassian** | your tasks (Jira/Confluence) |

---

## 🗺️ Where to discover more

**Skills & plugins**
- Official skills → [github.com/anthropics/skills](https://github.com/anthropics/skills)
- Official plugin directory → [claude.com/plugins](https://claude.com/plugins) (verified, one-click)
- Community plugins → `anthropics/claude-plugins-community`
- Awesome Claude Skills (huge curated catalog) → [awesome-skills.com](https://awesome-skills.com)

**MCP servers / connectors**
- Official MCP registry → [modelcontextprotocol.io](https://modelcontextprotocol.io)
- Directories → [glama.ai/mcp](https://glama.ai/mcp/servers) · [mcp.so](https://mcp.so) · [smithery.ai](https://smithery.ai)

> Rule of thumb: **official first** for safety, **community catalogs** for breadth. Always check a plugin's homepage before installing.
