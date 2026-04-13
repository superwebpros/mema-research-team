# Bonus: The "AI + Filesystem" Paradigm
### For when apps aren't enough

---

## Three Paradigms of Working with AI

Most of today's workshop focused on **Paradigm 1** — AI inside apps like ChatGPT and Claude. That's the right starting point for most teams. But it's worth knowing the landscape:

| Paradigm | What It Is | Best For |
|---|---|---|
| **1. AI in apps** | Skills + Projects in ChatGPT, Claude, NotebookLM | Getting started. Team productivity. Most workflows. |
| **2. AI + filesystem** | Claude Code, Cursor, similar tools — AI that reads/writes files directly on your machine | Heavy knowledge workers. Cross-document work. Research libraries. |
| **3. AI in your products** | Custom-built member-facing tools, embedded chat, branded experiences | Strategic investment. Competitive differentiation. |

This leave-behind is about **Paradigm 2** — a brief orientation, not a tutorial.

---

## The Meta-Moment

This entire workshop — the agenda, slide deck, leave-behinds, diagrams, even the excalidraw graphics you saw — was built using the AI + filesystem paradigm. One AI collaborator with access to the full file system, working across past presentations, research notes, and reference materials to produce a coherent output.

The difference from ChatGPT:
- **ChatGPT:** "Upload a file. Ask a question. Get an answer."
- **Claude Code:** "Here's my whole project directory. Let's work on it together."

---

## When This Paradigm Makes Sense

Consider it if:
- You're regularly working across dozens or hundreds of documents
- Your knowledge lives in local files (Markdown notes, Obsidian vaults, project folders)
- You want AI that can create, edit, and organize files — not just read them
- You're comfortable with a terminal / command line
- You've hit the limits of "upload a few files and chat"

**Don't bother if:**
- Your workflows are already well-served by ChatGPT / Claude Projects
- You're not comfortable with a command line
- Your team is just getting started with AI — master the first paradigm first

---

## Tools in This Paradigm

### Claude Code
AI agent that lives in your terminal. Full filesystem access within a project. Can read, write, edit, search, and run commands. Built by Anthropic.
- **Website:** claude.ai/code
- **Best for:** Working across entire projects or knowledge bases

### Cursor
AI-native code editor. Same paradigm, IDE interface. Originally for developers but now used by many knowledge workers for writing and research.
- **Website:** cursor.com
- **Best for:** Those who want an editor UI instead of a terminal

### GitHub Copilot / Other IDE assistants
Older generation, more focused on code completion than agentic work.

---

## Obsidian + Claude Code

If your team uses Obsidian (or any Markdown-based knowledge tool), the filesystem paradigm maps naturally:

- Obsidian vaults are just folders of Markdown files
- Claude Code can read and write those files directly
- You can ask it to cross-reference notes, summarize across documents, generate new entries, or restructure your vault

Example prompts you could run in a Claude Code session on your Obsidian vault:

> "Find all my notes about tariff policy and summarize the key themes."
>
> "Create a new monthly market update draft using the last six months of policy briefs in this vault."
>
> "Audit my tag structure — suggest consolidations where tags are redundant."

This is what "research library + AI collaborator" looks like in practice.

---

## The Honest Tradeoffs

| What You Gain | What You Trade |
|---|---|
| Full filesystem access | Terminal / command-line comfort required |
| Cross-document work at scale | More setup than opening ChatGPT |
| AI can create AND edit files | Less hand-holding, more "just do the thing" |
| Version control via git | Learning curve on git |
| Works with your existing tools (Obsidian, VS Code, etc.) | Not a GUI-first experience |

---

## The Path If You're Curious

1. **Start with Paradigm 1** (what we did today). Get comfortable with skills + projects.
2. **If you hit limits** — specifically, if you find yourself wanting AI to work across many files without uploading them — look into Claude Code.
3. **If you use Obsidian** for research notes, that's a natural starting point for this paradigm.
4. **If any of this is interesting**, that's a conversation to have with Super Web Pros.

---

## Where This Leads

Paradigm 2 is the bridge to Paradigm 3.

Once you understand how AI can work with a full knowledge base — across your entire research library, with proper chunking, metadata, and retrieval — you start seeing what's possible for your members:

- A custom chat tool built on 5+ years of MEMA research
- Filtered by topic, region, date, document type
- Branded, embedded in the MEMA portal
- Your data, your guardrails, your competitive advantage

That's Paradigm 3. And that's a different kind of conversation.

---

*Super Web Pros | superwebpros.com | Jesse Flores — jesse@superwebpros.com*
