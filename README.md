# MEMA Research Team — AI Workshop Materials

Workshop hosted by [Jesse Flores](https://superwebpros.com) of Super Web Pros for MEMA's Strategy & Research team on **April 14, 2026**.

This repo contains everything from the workshop — leave-behinds, the agenda, the participant workbook, reusable AI skills, and reference materials. Feel free to download, share with your team, and use it as a foundation for your own AI implementation work.

---

## Start Here

- **[agenda.md](agenda.md)** — The full workshop agenda (Discover → Frame → Build → Take Home)
- **[discovery-worksheet.md](discovery-worksheet.md)** — Discovery script we used to map your team's roles, process, tools, and pain points
- **[docs/workbook/](docs/workbook/)** — The 8-page participant workbook you filled in during the session

---

## Leave-Behinds (Reference Guides)

Six one-pagers plus one bonus guide:

| # | Guide | What It Covers |
|---|---|---|
| [01](leave-behinds/01-ai-periodic-table-reference.md) | **AI Periodic Table Reference** | Your map of the AI landscape — the 5 elements we used and the full framework |
| [02](leave-behinds/02-skills-quick-start.md) | **Skills Quick-Start Guide** | How to create, share, and iterate on skills (ChatGPT + Claude) |
| [03](leave-behinds/03-rag-primer.md) | **RAG Primer** | How AI finds your documents — chunking, embeddings, semantic search |
| [04](leave-behinds/04-document-hygiene-cheat-sheet.md) | **Document Hygiene Cheat Sheet** | Metadata headers, file naming, folder structure — zero-code retrieval fixes |
| [05](leave-behinds/05-prompt-engineering-guide.md) | **Prompt Engineering Guide** | 7 principles, outcome thinking, patterns for research teams |
| [06](leave-behinds/06-ai-tools-landscape.md) | **AI Tools Landscape** | ChatGPT vs Claude vs NotebookLM vs Copilot — when to use what |
| [07](leave-behinds/07-bonus-ai-filesystem-paradigm.md) | **Bonus: AI + Filesystem Paradigm** | For power users — Claude Code, Obsidian, and what's beyond chat |

---

## Reusable Skills

The `skills/` directory contains two pre-built AI skills you can use in ChatGPT, Claude, or any platform that supports the [Agent Skills open standard](https://agentskills.io):

| Skill | Purpose |
|---|---|
| [`compound-discovery-facilitator-01`](skills/compound-discovery-facilitator-01/) | Runs a structured AI discovery session — problem inventory, knowledge mapping, tool assessment |
| [`compound-solution-designer-02`](skills/compound-solution-designer-02/) | Helps design AI solutions for the problems surfaced during discovery |

### How to Use These Skills

**ChatGPT (Business / Enterprise / Edu):**
1. Zip the skill folder you want to use (e.g., right-click the `compound-discovery-facilitator-01` folder → Compress)
2. In ChatGPT, click your profile icon → **Skills**
3. Click **New skill** → **Upload from your computer**
4. Select the zip file
5. Install and use — ChatGPT will auto-invoke it when relevant, or you can call it directly

**Claude (Pro / Team / Enterprise):**
1. Zip the skill folder
2. In Claude, go to **Settings** → **Skills** → **Upload skill**
3. Select the zip file
4. Install and use in any Project or conversation

**The skills are portable** — they follow an open standard, so you can use them across tools and modify them as your workflows evolve. Think of them as starter templates, not finished products.

---

## Workshop Structure

```
Discover  →  Frame  →  Build  →  Take Home
 (30 min)   (30 min)   (75 min)   (45 min)
```

- **Discover** — Listening first. Roles, process, tools, pain points, workarounds.
- **Frame** — The AI Periodic Table + 5 diagnostic questions as the lens for the day.
- **Build** — Hands-on: create a Project, build the Market Report skill and the Social Media Content Agent.
- **Take Home** — Tool comparison, troubleshooting framework, action plan, what's possible next.

Visual roadmap: [`docs/diagrams/workshop-roadmap.excalidraw`](docs/diagrams/workshop-roadmap.excalidraw)

---

## The 5 Diagnostic Questions

When you hit any AI workflow problem, walk through these:

1. **What's the outcome?** — What does success look like? (Think outcomes, not tasks.)
2. **What does it need?** — Knowledge, context, judgment, sources, format?
3. **Where does the data live?** — Upload, connector, or custom pipeline?
4. **What could break?** — Hallucination, privacy, wrong format, inconsistency?
5. **What lever do you tweak?** — Instructions, examples, model, sources, metadata.

If something isn't working, one of these five levers is your fix.

---

## Reference Materials

- **[docs/diagrams/](docs/diagrams/)** — Excalidraw + PNG visuals (periodic table, workshop roadmap, embedding diagrams, Compound sprint cycle)
- **[files/](files/)** — Reference documents used during the workshop
- **[deck/](deck/)** — Deck outline

---

## Your Action Plan (From the Workshop)

**This week:**
1. Refine the Market Report + Social Media skills with real data
2. Share the Project with your team
3. Add metadata headers to your next 5 documents
4. Try NotebookLM with your last 3 monthly reports

**This month — more skills to build:**
5. **Survey Question Designer** — research topic in, member survey out
6. **Source Summarizer** — 5 articles in, categorized summary out
7. **Presentation Outliner** — report in, slide structure + speaker notes out
8. **Member Briefing Generator** — curated updates for specific segments

**Also:**
9. Audit document organization (naming, folders, metadata)
10. Explore Claude Pro ($20/month) — compare output to ChatGPT

---

## Questions?

If anything comes up as you put this into practice — reach out.

**Jesse Flores** | Super Web Pros
- [jesse@superwebpros.com](mailto:jesse@superwebpros.com)
- [superwebpros.com](https://superwebpros.com)
- [compoundorg.com](https://compoundorg.com)

---

## About the "What's Possible for Members" Conversation

The workshop focused on your team's internal productivity. The next conversation — if you're interested — is about what becomes possible when you turn your research library into a member-facing experience:

- Members chatting with 5+ years of your research
- Filtered by topic, region, date, document type
- Grounded answers with citations from YOUR reports
- Branded, embedded in the MEMA portal

That's a custom build, and it's a different kind of engagement. When you're ready, that's a conversation.

---

*The frameworks don't change. The tools will. You now have both.*
