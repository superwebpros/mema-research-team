# AI Tools Landscape — Reference Guide
### For MEMA's Research Team (April 2026)

---

## The Core Platforms

### ChatGPT (OpenAI)
- **Your plan:** Enterprise
- **Best for:** Skills (reusable workflows), broad general tasks, SharePoint/Drive connectors
- **Skills:** Yes — create, share, install across your workspace
- **Connectors:** SharePoint, Google Drive, and more (admin-configured)
- **Strengths:** Most popular, largest ecosystem, skills sharing across team
- **Watch out for:** Hallucinated statistics, opaque retrieval, no metadata filtering on connectors
- **Cost:** Enterprise pricing (custom)

### Claude (Anthropic)
- **Best for:** Long document analysis, nuanced writing, research synthesis
- **Skills:** Yes — via Projects with custom instructions
- **Connectors:** Google Drive (Docs only), Gmail, Google Calendar
- **Strengths:** 200K token context window (largest), strong analytical writing, Projects for organized work
- **Watch out for:** Google Docs only on Drive connector (no PDFs), smaller connector ecosystem
- **Cost:** Pro $20/month, Team $25/user/month

### NotebookLM (Google)
- **Best for:** Source-grounded research, slide generation, audio summaries
- **Skills:** No — but notebooks serve as focused research workspaces
- **Connectors:** Upload sources directly (PDFs, Docs, websites, YouTube)
- **Strengths:** Free, never hallucinates (grounded in your sources), generates slides + audio overviews, citations built in
- **Watch out for:** Limited to uploaded sources (no live search), basic slide design
- **Cost:** Free

### Microsoft 365 Copilot
- **Best for:** Working within Microsoft Office (PowerPoint, Word, Excel, Outlook)
- **Skills:** No — but integrates deeply with Office apps
- **Connectors:** Native SharePoint, OneDrive, Outlook, Teams
- **Strengths:** Only AI tool that respects SharePoint managed metadata, brand templates in PowerPoint, stays in your existing workflow
- **Watch out for:** Fabricates statistics (always verify), requires M365 Copilot license
- **Cost:** ~$30/user/month on top of M365

---

## Specialized Tools Worth Knowing

### For Presentations
| Tool | Quality | Accuracy | Cost | Best For |
|---|---|---|---|---|
| **NotebookLM** | Good | Excellent (source-grounded) | Free | Content-accurate first drafts |
| **Copilot in PowerPoint** | Good | Risky (verify everything) | $30/user/mo | Staying in PowerPoint workflow |
| **Gamma.app** | Best design | Generic AI text | Free tier / $15/mo Pro | Beautiful-looking decks quickly |
| **ChatGPT .pptx** | Basic | Variable | Included in plan | Quick outlines only |

**Recommended workflow:** NotebookLM for source-grounded first draft → export .pptx → polish in PowerPoint

### For Images
- **fal.ai** — AI image generation (custom graphics for reports/presentations)
- **Midjourney** — highest quality AI images, but requires Discord
- **DALL-E** — built into ChatGPT, convenient but less control

### For Research
- **Perplexity** — AI-powered search with citations (good for sourcing articles)
- **Elicit** — academic/research paper search and synthesis

---

## How to Choose the Right Tool

```
Is this a recurring task I do the same way each time?
  → Build a ChatGPT Skill

Am I analyzing a specific set of documents?
  → NotebookLM (upload sources, ask questions, generate slides)

Am I writing something that needs nuance and depth?
  → Claude (large context window, strong writing)

Am I working in PowerPoint/Word/Outlook?
  → Microsoft 365 Copilot (if licensed)

Do I need to search across my team's document library?
  → ChatGPT Enterprise connectors (SharePoint/Drive)
  → Microsoft 365 Copilot (if you need metadata filtering)

Am I creating a visual or presentation?
  → NotebookLM for content → PowerPoint for polish
  → Gamma for quick, attractive decks
  → fal.ai for custom images
```

---

## Key Concepts to Remember

**Skills** = Packaged prompts. Reusable. Shareable. Build once, use every time.

**Connectors** = Links to your data sources. Convenient but limited — no metadata filtering (except Copilot).

**Context Window** = How much the AI can "see" at once. Bigger = more document, less retrieval error. Claude (200K) > ChatGPT (128K).

**RAG (Retrieval-Augmented Generation)** = How AI searches your documents. Chunks them, searches semantically, returns relevant pieces. Not perfect — help it with good metadata and document structure.

**Hallucination** = When AI makes up plausible-sounding information. Use source-grounded tools (NotebookLM) for accuracy-critical work. Always verify statistics.

**Few-Shot Learning** = Teaching AI by showing examples, not just giving instructions. One good example > a page of rules.

---

## Links & Resources

- **ChatGPT Skills docs:** help.openai.com/en/articles/20001066-skills-in-chatgpt
- **NotebookLM:** notebooklm.google.com (free)
- **Claude:** claude.ai
- **Gamma:** gamma.app
- **fal.ai:** fal.ai
- **AI Periodic Table:** (see printed reference)

---

*Super Web Pros | superwebpros.com | Jesse Flores — jesse@superwebpros.com*
