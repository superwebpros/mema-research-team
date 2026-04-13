# MEMA Research Team AI Workshop
## April 14, 2026 | 9:00am - 12:00pm ET
## MEMA Office: 25925 Telegraph Road, Ste. 350, Southfield, MI 48033

**Audience:** 3-5 members of MEMA's Strategy & Research team (Mike Jackson + team)
**Host:** Jesse Flores, Super Web Pros
**Format:** Hands-on workshop — participants work in their own ChatGPT Enterprise instances

---

## Pre-Workshop Setup Checklist

- [ ] Confirm attendees have ChatGPT Enterprise access on their laptops
- [ ] Confirm ChatGPT Enterprise admin has "Skills" enabled (beta — may need admin toggle)
- [ ] Confirm whether they have Microsoft 365 Copilot licenses (affects presentation discussion)
- [ ] Have the October 2025 MEMA Market Update PDF accessible for demos
- [ ] Jesse: ChatGPT Business account logged in, Claude Pro account logged in, NotebookLM open
- [ ] Bring printed leave-behinds (see /leave-behinds/ folder):
  - AI Periodic Table one-pager
  - Skills Quick-Start Guide
  - Document Hygiene Cheat Sheet
  - AI Tools Landscape Reference
- [ ] Presentation deck ready (see /deck/ folder)
- [ ] Confirm WiFi access at MEMA office
- [ ] Pre-build a NotebookLM notebook with the October Market Update loaded (saves demo time)

---

## Block 1: SIGNAL + SOURCE (9:00 - 9:30) — 30 min
*Compound Stages 1-2: Find the one problem worth solving. Map what the work requires.*

### Goals
- Build rapport, understand where each person is with AI today
- Discover team roles, process, tools, data organization (Signal)
- Map the knowledge, context, and judgment the work requires (Source)
- Set the map: AI Periodic Table as a 5-minute orientation
- Introduce both frameworks: Periodic Table (what) + Compound stages (how)
- Connect today's agenda to Mike's four outcomes

### Flow

**9:00 - 9:15 | Introductions & Team Discovery (15 min)**
- Round the table: name, role, what AI tools you've used, one thing you hope to walk away with today
- **Team inventory — capture on a whiteboard or notepad:**
  - **Roles:** Who does what? Who writes the market report? Who designs slides? Who handles social/comms? Who manages data/sources?
  - **Process:** Walk me through how the monthly market update gets made. Where do sources come from? Who curates? Who writes? Who reviews? Who publishes?
  - **Tools:** What's in your stack? SharePoint? Google Drive? PowerPoint? Canva? Survey tools? What do you use for social media?
  - **Data organization:** How are your documents organized? Folders? Tags? Naming conventions?
- Listen for: comfort levels, specific pain points, who's the most/least technical
- This shapes everything — which skills to build, which connectors matter, whether to cover image generation (fal.ai) for a visual/design person, etc.

**9:15 - 9:20 | The Map: AI Periodic Table (5 min)**
- "Before we dive in, here's a map of the territory"
- Show the periodic table — point to the ~5 elements we'll touch today:
  - **Prompts (Pr):** The instructions we give AI — skills are packaged prompts
  - **RAG (Rg):** How AI retrieves your documents — why connectors exist
  - **Context Windows:** How much AI can "see" at once — why long docs get lost
  - **Agents (Ag):** AI that takes action, not just responds — skills that do things
  - **Guardrails (Gr):** Why output needs human review — where AI breaks
- "We won't go deep on all of these. But now when I say 'retrieval' or 'context window,' you'll know where it fits."
- Leave the printed periodic table on the table as a reference

**9:20 - 9:28 | What's Changed Since December (8 min)**
- Quick recap of the MEMA Sales Leaders presentation (Custom GPTs, Agents, RAG)
- "In December I showed you what's possible. Today we're going to actually build it for your workflows."
- What's new since then:
  - ChatGPT now has **Skills** — reusable, shareable workflows (exactly what Mike asked for in outcome #3)
  - ChatGPT now has **Connectors** (Apps) — connect to SharePoint, Google Drive, etc.
  - Claude has matured significantly — worth seeing as a comparison
  - NotebookLM has become a powerful free research tool
- Frame the day: "By noon, you'll have working skills in your ChatGPT instance, you'll understand the frameworks behind them, and you'll know what levers to tweak when something isn't working."

**9:28 - 9:30 | Logistics (2 min)**
- Everyone logged into ChatGPT Enterprise? Skills enabled?
- Break at ~10:30
- "This is a working session — interrupt me, ask questions, try things"

---

## Block 2: DESIGN + BUILD (9:30 - 10:30) — 60 min
*Compound Stages 3-4: Decide who does what. Deploy it into the workflow that already exists.*

### Goals
- Design: Clarify what stays human vs. what moves to a skill (Hybrid Accountability)
- Build: Everyone builds a working skill in their own ChatGPT Enterprise instance
- Understand what information is stored where and how
- Introduce connectors and their limitations (chunking, context windows)
- Address Mike's outcomes #1 (market report) and #3 (purpose-specific agents)

### Flow

**9:30 - 9:45 | Demo: Anatomy of a Skill (15 min)**
- Jesse demos in his ChatGPT Business account
- Show the Skills page (profile icon → Skills)
- Show the built-in `skill-creator` skill — "Both ChatGPT and Claude have built-in wizards that help you create skills. You don't write them from scratch."
- Walk through what a skill contains:
  - Instructions (the "system prompt" — what it knows and how it behaves)
  - Examples (few-shot learning — show it what good output looks like)
  - Steps (structured workflow — runs the same way every time)
- **Mention the open standard:** "Skills are actually an open standard (agentskills.io) — the same concepts work across ChatGPT, Claude, and other tools. You're learning a transferable skill, not a vendor feature."
- **Live demo:** Ask ChatGPT to create a skill in conversation
  - Prompt: "Create a skill that takes a collection of news articles and industry data and produces a 2-page market update newsletter in the style of MEMA's monthly market report"
  - Show how ChatGPT asks follow-up questions
  - Install the skill
- **Key concept — connect to the periodic table:**
  - "A skill is basically a packaged **Prompt (Pr)**. The instructions are the system prompt. The examples are few-shot learning. The steps are an agent workflow."
- **Key authoring tips (weave in during demo):**
  - Be concise — the AI is already smart, only add what it doesn't know
  - Show don't tell — one good example > a page of rules
  - Add guardrails for accuracy: "Only use data from provided sources. Never fabricate statistics."
  - Match specificity to risk — strict format for your report template, flexible for creative tasks

**9:45 - 10:05 | Hands-On: Build Your Own Market Report Skill (20 min)**
- Everyone builds a skill in their own ChatGPT Enterprise instance
- Use the October 2025 Market Update PDF as the reference/example
- Suggested approach:
  1. Upload the October PDF to the conversation
  2. "Create a skill that produces monthly market updates in this exact format and style"
  3. Let ChatGPT ask questions — answer them based on your team's actual workflow
  4. Install the skill
  5. Test it: "Using the following raw notes, create this month's market update: [paste some bullet points]"
- Jesse circulates, helps troubleshoot
- **Key teaching moments as they arise:**
  - "Notice how it matched the section structure? That's because we gave it an example — few-shot learning"
  - "Notice how it made up a statistic? That's a hallucination — this is why Guardrails (Gr) matter"
  - If output is wrong: "What lever do we tweak? The instructions in the skill."

**10:05 - 10:15 | Sharing Skills + Data/Privacy Discussion (10 min)**
- Demo: How to share a skill with your workspace
  - Skills page → hover → ⋯ → Share
  - Share with specific people, groups, or copy link
  - Permissions: who can edit vs. use
- "Now one person builds the Market Report skill, and the whole team uses it consistently"
- **Where does your data live?**
  - Skills: stored in ChatGPT's workspace (OpenAI servers, covered by Enterprise DPA)
  - Conversations: same — not used for training on Enterprise plans
  - Uploaded files: processed and indexed by OpenAI
  - "Your Enterprise plan has contractual guarantees — but know what's where"

**10:15 - 10:30 | Connectors: Linking Your Data Sources (15 min)**
- Show how connectors (Apps) work in ChatGPT Enterprise
  - SharePoint, Google Drive, etc.
  - "Developer mode" needed for custom connectors
- **Key concept — RAG and its limits:**
  - "When you connect SharePoint, ChatGPT indexes your documents. It chunks them into ~800-token pieces and searches them semantically."
  - "This is great for finding information. But it has limits:"
    - Fixed chunking can break tables and structured content
    - No metadata filtering — it doesn't use your SharePoint tags/taxonomies
    - Sync is periodic (hours, not real-time)
  - "If you ask 'find my Q1 policy brief' and it doesn't surface it — now you know why. The chunking may have split the relevant section, or the semantic match wasn't strong enough."
- **Practical workaround they can do today:**
  - Add a metadata header block at the top of every document:
    ```
    Document Type: Market Update
    Topic: Tariffs, Trade Policy
    Period: Q1 2026
    Keywords: aftermarket, EV, USMCA
    ```
  - "Every AI tool indexes full text. This header becomes searchable context. No pipeline needed — just document discipline."
  - Consistent file naming: `Market-Update_Q1-2026_Tariffs-EV.pdf`
- **Context windows — why it matters:**
  - "ChatGPT can 'see' about 128K tokens at once. Claude can see 200K. If your document collection is larger than that, the AI has to choose which pieces to look at. That's retrieval. And retrieval isn't perfect."
- **Quick Claude comparison** (if time):
  - Show Claude's Google Drive connector — different approach (on-demand into context window vs. pre-indexed)
  - "Different tools, different tradeoffs. Now you know the framework to evaluate them."

---

## BREAK (10:30 - 10:40) — 10 min

---

## Block 3: DELIVER (10:40 - 11:30) — 50 min
*Compound Stage 5: Run it and measure what actually changed.*

### Goals
- Test what we built, try different tools on the same task, see what works
- Build a second skill (role-based, tailored to each person)
- Introduce NotebookLM as a research synthesis + presentation tool
- Claude comparison — same task, different tool, observe differences
- Address Mike's outcomes #2 (AI tool comparison) and #4 (team productivity)

### Flow

**10:40 - 10:55 | Demo: NotebookLM for Research Synthesis (15 min)**
- "Let me show you a free tool that's tailor-made for what your team does"
- Live demo:
  1. Open NotebookLM
  2. Create a new notebook
  3. Upload the October 2025 Market Update PDF + 2-3 other source docs if available
  4. Show the automatic source summaries
  5. Ask it questions: "What are the key policy changes affecting aftermarket suppliers?"
  6. Show the grounded citations (it points to specific sources — no hallucination)
  7. **Generate a slide deck** from the sources
  8. Show the .pptx export
- **Key selling points for their team:**
  - Free
  - Source-grounded — won't fabricate statistics (critical for a research team)
  - Audio overview feature — "imagine sending members a 10-minute audio briefing alongside the PDF"
  - Slide generation from actual source material
- **Connect to the map:** "NotebookLM is doing RAG under the hood — retrieving from your uploaded sources and generating grounded answers. Same concept as the connectors, but you control exactly which sources go in."

**10:55 - 11:10 | Hands-On: Role-Based Skill Building (15 min)**
- Based on the team discovery in Block 1, have each person build a skill tailored to their role/workflow
- Suggested options (adapt based on what you learned about the team):
  - **Writer/Editor:** Social Media Content Curator — "Create a skill that takes our market update and generates 3-5 LinkedIn posts highlighting key findings, in MEMA's voice"
  - **Researcher/Analyst:** Source Summarizer — "Create a skill that takes 3-5 raw articles and produces a curated summary with key takeaways, organized by Market/Policy/Technology/Strategy"
  - **Designer/Visual:** Presentation Outliner — "Create a skill that takes our monthly market update and generates a slide-by-slide outline with speaker notes and image suggestions"
  - **Project/Survey Lead:** Survey Question Designer — "Create a skill that takes a research topic and generates a set of member survey questions following best practices"
- Everyone builds in their own instance, tests with real content, shares with the team
- **If there's a visual/design role:** Quick demo of fal.ai for image generation — show how AI can generate custom graphics for reports/presentations instead of relying on stock photos
- **Bonus skill concept: "Design Pass"** — a skill that takes a generated slide deck and applies formatting rules (typography hierarchy, consistent color scheme, layout principles). "The AI generates the content; a second pass polishes the design. Two skills, one pipeline."

**11:10 - 11:25 | Claude Side-by-Side: Same Task, Different Tool (15 min)**
- Jesse demos Claude on the same task they just did in ChatGPT
- "Same prompt, different model — watch what's different"
- Show Claude's strengths:
  - Longer context window (200K tokens)
  - Often better at nuanced writing and analysis
  - Projects feature for organizing ongoing work
  - Connectors to Google Drive, etc.
- Show Claude's skills (if applicable to their use case)
- **Key framework takeaway:**
  - "This is why understanding the periodic table matters. The concepts (Pr, Rg, Ag) are the same across tools. The implementations differ. You're not locked into one platform — you're learning transferable frameworks."
  - "Great prompting on any tool beats lazy prompting on the best tool"
- Quick mention of other tools worth knowing:
  - Microsoft Copilot — best for PowerPoint if they have M365 Copilot licenses (respects SharePoint metadata)
  - Gemini — strong if in Google ecosystem
  - "The landscape changes fast. The frameworks don't."

**11:25 - 11:30 | Presentations: The Landscape (5 min)**
- **Slide generation quality ranking (be honest):**
  - **NotebookLM** — best overall. Source-grounded content (no hallucinated stats), decent design, .pptx export, free
  - **Claude** — strong content quality, good structure, but no native slide generation (outputs outlines/markdown)
  - **ChatGPT** — can generate .pptx files, but basic formatting, limited design, content may hallucinate
  - **Copilot in PowerPoint** — best if they have M365 Copilot licenses (stays in their workflow, uses brand templates from SharePoint), but verify every number
  - **Gamma.app** — best-looking visual design out of the box, but .pptx export has formatting issues
- **Recommended workflow:** NotebookLM for source-grounded first draft → export .pptx → polish in PowerPoint (or run through a "Design Pass" skill)
- "The content accuracy matters more than the design for your team. You can fix ugly slides. You can't un-publish a fabricated statistic."

---

## Block 4: COMPOUND (11:30 - 12:00) — 30 min
*Compound Stage 6: Run the next sprint on the infrastructure you just built.*

### Goals
- Consolidate what they've learned into frameworks they can use independently
- Give them a concrete "what to do Monday" action plan — their next sprint backlog
- Seed the conversation about member-facing AI experiences (upsell)
- Address any remaining questions

### Flow

**11:30 - 11:40 | Framework Review: How to Think About AI Problems (10 min)**
- Return to the periodic table: "You've now worked with 4-5 of these elements hands-on"
- **The problem-solving framework they're taking home:**
  1. **What's the outcome?** → What does success look like? Skills automate processes, not just tasks.
  2. **What data does it need?** → Determines retrieval strategy (upload, connector, or custom pipeline)
  3. **How repeatable is it?** → One-off = prompt. Recurring = skill. Automated = agent.
  4. **What could go wrong?** → Hallucination risk, data privacy, quality control
  5. **What levers can you tweak?** → Instructions, examples, temperature, model choice, source docs, metadata
- "When something doesn't work, you now know which lever to pull. Is the retrieval wrong? Check your sources and metadata. Is the output format wrong? Update the skill instructions. Is the content inaccurate? Add examples of good output."

**11:40 - 11:50 | The Bigger Picture: What's Possible (10 min)**
- "Everything we did today — skills, connectors, NotebookLM — is you and your team using AI internally. What about your members?"
- Paint the picture:
  - "Imagine a member logs into the MEMA portal and can chat with 5 years of your market research"
  - "They ask: 'What's the tariff exposure for aftermarket brake suppliers in Q1 2026?' and get a grounded answer with citations from YOUR reports"
  - "They can filter by topic, time period, region — because the data is properly structured"
  - "They can generate their own custom briefing from your research library"
- "The tools we used today are great for your team's internal productivity. But a member-facing experience requires something different:"
  - Custom data pipeline with proper chunking (respects your report structure)
  - Metadata filtering (topic, date, region)
  - A web interface your members can access
  - Your branding, your guardrails, your data
- "That's the difference between the built-in connectors and a custom build. And that's a conversation we'd love to have with you when you're ready."
- Keep it light — plant the seed, don't pitch hard

**11:50 - 12:00 | Action Plan & Close (10 min)**
- **What to do this week:**
  1. Refine the Market Report skill you built today — test it on real data, iterate on the instructions
  2. Share it with the team — get everyone using the same skill
  3. Add metadata headers to your next 5 documents — start building the retrieval habit
  4. Try NotebookLM with your last 3 monthly reports — see what patterns it finds
- **What to do this month:**
  5. Build 2-3 more skills for your recurring workflows (survey design, LinkedIn content, etc.)
  6. Audit your SharePoint/Drive document organization — consistent naming, folder structure
  7. Explore Claude Pro ($20/month) — try the same skills/tasks, compare output quality
- **Resources:**
  - AI Periodic Table (printed leave-behind)
  - ChatGPT Skills documentation
  - NotebookLM (free)
  - Jesse's contact info for follow-up
- Round the table: one takeaway each
- "The frameworks don't change. The tools will. You now have both."

---

## Appendix: Mike's Four Outcomes — Where They're Addressed

| Outcome | Where Addressed |
|---|---|
| #1 — Monthly market report using AI | Block 2 (build Market Report skill), Block 3 (NotebookLM demo) |
| #2 — Best use cases for AI tools (Claude, ChatGPT, Gemini, Copilot) | Block 1 (landscape), Block 3 (Claude comparison, presentation tools overview) |
| #3 — Build purpose-specific agents | Block 2 (first skill), Block 3 (second skill) |
| #4 — AI for team productivity | Throughout — skills sharing, connectors, document discipline, action plan |

## Appendix: Key Concepts to Weave In (Not Lecture On)

These should come up naturally during demos and hands-on work, not as standalone teaching moments:

- **Chunking:** When connector doesn't surface a doc → "here's why, and here's the metadata workaround"
- **Context windows:** When comparing Claude (200K) vs ChatGPT (128K) → "this is how much it can 'see' at once"
- **Hallucination:** When a skill generates a fake stat → "this is why NotebookLM's source-grounding matters"
- **Few-shot learning:** When a skill produces better output with examples → "you just taught it by showing, not telling"
- **Temperature:** If someone asks about creativity vs. consistency → "there's a dial for that"
- **RAG vs. context window:** Claude loads docs into context; ChatGPT pre-indexes. Different tradeoffs.

## Appendix: Upsell Talking Points (Light Touch)

- Member-facing research chat tool
- Custom data pipeline with structured chunking for their report format
- Metadata filtering (topic, date, region, document type)
- Branded web experience for members
- "Your research is your competitive advantage. Right now it lives in PDFs. What if members could interact with it?"
