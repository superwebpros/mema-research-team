# MEMA Research Team AI Workshop
## April 14, 2026 | 9:00am - 12:00pm ET
## MEMA Office: 25925 Telegraph Road, Ste. 350, Southfield, MI 48033

**Audience:** 3-5 members of MEMA's Strategy & Research team (Mike Jackson + team)
**Host:** Jesse Flores, Super Web Pros
**Format:** Hands-on workshop — participants work in their own ChatGPT Enterprise instances

---

## The Workshop Arc

**Discover → Frame → Build → Take Home**

Four phases. Each builds on the last. We listen first, introduce the map and diagnostic questions second, work through them hands-on third, then translate it into an action plan they own.

The Compound Sprint Framework (Signal → Source → Design → Build → Deliver → Compound) is the philosophical backdrop for how we structure AI work — it's in the air, not on every slide.

---

## Pre-Workshop Setup Checklist

- [ ] Confirm attendees have ChatGPT Enterprise access on their laptops
- [ ] Confirm ChatGPT Enterprise admin has "Skills" enabled (beta — may need admin toggle)
- [ ] Confirm whether they have Microsoft 365 Copilot licenses (affects presentation discussion)
- [ ] Have the October 2025 MEMA Market Update PDF accessible for demos
- [ ] Jesse: ChatGPT Business account logged in, Claude Pro account logged in, NotebookLM open
- [ ] Bring printed leave-behinds (see /leave-behinds/ folder):
  - 01 — AI Periodic Table Reference
  - 02 — Skills Quick-Start Guide
  - 03 — RAG Primer
  - 04 — Document Hygiene Cheat Sheet
  - 05 — Prompt Engineering Guide
  - 06 — AI Tools Landscape Reference
- [ ] Presentation deck ready (see /deck/ folder)
- [ ] Confirm WiFi access at MEMA office
- [ ] Pre-build a NotebookLM notebook with the October Market Update loaded (saves demo time)
- [ ] Pre-load all demo browser tabs (see deck outline for links)

---

## Phase 1: DISCOVER (9:00 - 9:30) — 30 min
*Listening. Understanding their world before teaching anything.*

### Goals
- Build rapport, understand where each person is with AI today
- Map team roles, current process, tools, data organization
- Surface pain points — what dissatisfies them about the current way?
- Understand current workarounds (what have they already tried?)
- This shapes everything that follows

### Flow

**9:00 - 9:05 | Quick Introductions (5 min)**
- Round the table: name, role, what AI tools you've used, one thing you hope to walk away with today
- Listen for: comfort levels, skepticism vs. enthusiasm, who's most/least technical

**9:05 - 9:30 | Team Discovery — Deep Dive (25 min)**

Capture on a whiteboard or notepad as you go.

- **Roles & responsibilities**
  - Who writes the market report? Who designs slides?
  - Who handles social/comms? Who manages data/sources?
  - Are there specialists or is it shared?

- **The current process**
  - Walk me through how the monthly market update gets made
  - Where do sources come from? Who curates? Who writes?
  - Who reviews? Who publishes? Where?
  - How long does the full process take?

- **Tools & data organization**
  - What's in your stack? SharePoint? Google Drive? PowerPoint? Canva?
  - What do you use for surveys? For social media?
  - How are documents organized? Folders? Tags? Naming conventions?
  - What AI tools has your org given you access to?

- **What dissatisfies you about the current process?**
  - Which steps are most tedious? Which are error-prone?
  - Where do things break down or get stuck?
  - What do you wish took less time?
  - What have you already tried to fix, and what happened?

- **What are your current workarounds?**
  - Manual copy-pastes? Templates? Recurring meetings to coordinate?
  - Where have you tried AI already and it didn't stick?

> **Why this matters:** You can't automate what you don't understand. The rest of the day is only valuable if we know what's worth automating. Listen more than you talk.

---

## Phase 2: FRAME (9:30 - 10:00) — 30 min
*Give them the map and the diagnostic questions before we build anything.*

### Goals
- Introduce the AI Periodic Table as the "you are here" map of the landscape
- Introduce the 5 diagnostic questions — the lens they'll hold while building
- Cover skills, connectors, and document discipline as the foundations
- By end of this phase, they have frameworks in hand — then we work through them

### Flow

**9:30 - 9:35 | The Map: AI Periodic Table (5 min)**
- "Before we dive in, here's a map of the territory."
- Show the periodic table — highlight the 5 elements we'll work with today:
  - **Prompts (Pr):** Instructions we give AI. Skills are packaged prompts.
  - **RAG (Rg):** How AI retrieves your documents. Why connectors exist.
  - **Context Windows:** How much AI can "see" at once. Why long docs get lost.
  - **Agents (Ag):** AI that takes action, not just responds.
  - **Guardrails (Gr):** Why output needs human review. Where AI breaks.
- "We won't go deep on all of these. But when I say 'retrieval' or 'context window,' you'll know where it fits."
- Leave the printed periodic table on the table.

**9:35 - 9:45 | The Diagnostic Questions (10 min)**

"When you hit any AI problem, these 5 questions tell you what to do. Hold these while we build today."

1. **What's the outcome?** → What does success look like? Skills automate processes, not just tasks. Outcome thinking ("help me produce next month's market update") beats task thinking ("summarize this article").

2. **What does it need?** → What knowledge, context, and judgment does the work require? What sources? What format? What voice?

3. **Where does the data live?** → Upload, connector, or custom pipeline? Different answers, different tradeoffs.

4. **What could break?** → Hallucination? Privacy? Wrong format? Inconsistent output?

5. **What lever do you tweak?** → Instructions, examples, model, source docs, metadata. When something doesn't work, one of these is your fix.

> "These aren't abstract. You're going to experience every one of them hands-on. By noon, this framework won't feel like a list — it'll feel like a reflex."

**9:45 - 9:52 | Projects: The Organizing Container (7 min)**
- "Skills don't float in space — they live inside Projects."
- A Project is a workspace with its own files, conversations, custom instructions, and skills. Think of it like a folder with superpowers.
- Examples for MEMA:
  - **"Monthly Market Report" Project** — contains past reports as reference files, a Market Report skill, a LinkedIn Post Generator skill
  - **"Member Surveys" Project** — contains survey design skill, analysis skill, reference examples
  - **"Policy Research" Project** — contains source docs, research synthesizer skill, briefing generator
- "This is how a 'purpose-specific agent' actually works in practice — a Project scoped to one domain, with skills that automate the key workflows."
- Both ChatGPT and Claude have Projects. Same concept, slightly different implementations.

**9:52 - 9:58 | Skills: Anatomy & Authoring Tips (6 min)**
- What a skill is: reusable workflow = instructions + examples + steps
- Both ChatGPT and Claude have built-in skill wizards (skill-creator in ChatGPT; Claude understands the format natively)
- Skills are an **open standard** (agentskills.io) — portable across tools
- Key authoring tips (from agentskills.io):
  - Be concise — the AI is already smart
  - Show don't tell — one example > a page of rules
  - Match specificity to risk (strict for format, flexible for creative)
  - Add accuracy guardrails ("Never fabricate statistics")
- Where data lives: Skills on OpenAI servers, Enterprise DPA, not used for training

**9:58 - 10:00 | Connectors, Retrieval & Document Discipline (2 min)**
- Connectors (Apps) link SharePoint, Drive, etc.
- How retrieval works: chunk → embed → semantic search
- Its limits: no metadata filtering, fixed chunking, periodic sync
- The zero-code fix: metadata headers + consistent file naming

---

## Phase 3: BUILD (10:00 - 11:15 with 10-min break) — 75 min
*Hands-on. We build a Project with 2 skills — explicitly answering Mike's outcomes #1 and #3. Every moment implicitly answers one of the 5 diagnostic questions.*

### Goals
- Create a **Project** (the container for purpose-specific agents)
- Build **Skill #1: Monthly Market Report** (Mike's outcome #1)
- Build **Skill #2: Social Media Content Agent** (Mike's outcome #3 — exactly as described in his email)
- Demo NotebookLM as a source-grounded alternative (supports slide generation for outcome #4)
- Compare Claude side-by-side (Mike's outcome #2)
- Address all of Mike's four outcomes through hands-on work

### Flow

**10:00 - 10:10 | Create Your Project (10 min)**
- Everyone creates a new Project in their ChatGPT Enterprise workspace
- Name it "Monthly Market Report"
- Upload reference files: October 2025 Market Update PDF, any other example reports
- Add initial custom instructions (voice, audience, quality standards)
- **Why this first:** Skills live inside Projects. Setting up the Project right = better retrieval + better skill output.

> Reinforces question 3 (where does data live? — inside the Project).

**10:10 - 10:25 | Demo + Build: Market Report Skill (Mike's #1) (15 min)**
- Jesse demos in his ChatGPT Business account inside his Project
- Show the Skills page, skill-creator, conversational creation
- Live-build: "Create a skill that produces monthly market updates matching the uploaded example"
- Install, test with raw bullet points
- **Then everyone builds their own version** in their Projects
- **Teaching moments as they arise:**
  - Output matches the format? → Few-shot learning
  - Made up a statistic? → Hallucination / guardrails
  - Wrong output? → Tweak the instructions — that's the lever

> Addresses Mike's outcome #1. Reinforces diagnostic questions 1 (outcome), 4 (what breaks), 5 (what lever).

**10:25 - 10:35 | Connectors Deep Dive (10 min)**
- Show connectors (Apps) in ChatGPT Enterprise
- Explain the chunking/retrieval flow
- Surface the limitations honestly
- Show the metadata header workaround
- Show a Claude connector briefly — different approach (on-demand into context)

> Addresses Mike's outcome #2 (tool comparison). Reinforces question 3 (where does data live?).

---

### BREAK (10:35 - 10:45) — 10 min

---

**10:45 - 11:05 | Build: Social Media Content Agent (Mike's #3) (20 min)**

This is the exact agent Mike described in his email: "an agent to scan, curate, synthesize and draft text for reference and approval for social media content, i.e., LinkedIn."

- **Jesse demos first (5 min):**
  - Take the Market Report skill's output (or a past report)
  - Build a new skill: "Take a monthly market update and generate 3-5 LinkedIn posts highlighting key findings, in MEMA's voice, flagged for human review before posting"
  - Install, test, show the output
  - **Key framing:** "This is a purpose-specific agent. It scans your research, curates the highlights, synthesizes the insights, and drafts for your review. Exactly what Mike asked for — and you built it in 5 minutes."

- **Then everyone builds their own (15 min):**
  - In their same Project (or a new "Social Media" Project)
  - Build a LinkedIn content skill using MEMA's voice
  - Add guardrails: "Flag any claims that need verification. Mark as 'Ready for Review' not 'Ready to Post'."
  - Test it on a real past market update
  - Share with the team

> Addresses Mike's outcome #3 directly. Reinforces all 5 diagnostic questions — they're now internalizing the framework.

**11:05 - 11:15 | NotebookLM Demo: Source-Grounded Research + Slides (10 min)**
- Open NotebookLM with the pre-loaded October Market Update
- Ask questions → show grounded citations (no hallucination)
- **Generate a slide deck from sources** → .pptx export (supports "slide content creation" from Mike's topic list)
- Show the audio overview feature
- **Why it matters:** Free, source-grounded, best slide generation for a research team

> Addresses the "slide content creation" request implicitly named in Mike's email. Reinforces question 4 (what could break: NotebookLM eliminates hallucination by grounding).

---

## Phase 4: TAKE HOME (11:15 - 12:00) — 45 min
*Synthesize. Own. Plan. Seed what's next.*

### Goals
- Reinforce the 5 diagnostic questions now that they've experienced them
- Quick tool comparison (ChatGPT vs. Claude — same task, different results)
- Show the honest presentation tool landscape
- Give them a concrete action plan
- Paint the bigger picture (member-facing AI — light upsell)

### Flow

**11:15 - 11:25 | Claude Side-by-Side + Tool Landscape (10 min)**
- Live demo: Claude doing the same task they did in ChatGPT
- What's different: 200K context, nuanced writing, Projects
- **Key takeaway:** "Concepts (Pr, Rg, Ag) transfer. Implementations differ. You're not locked in."
- Quick tool landscape:
  - NotebookLM — best for source-grounded content
  - Claude — best for nuanced writing
  - ChatGPT — best for skills + connectors ecosystem
  - Copilot in PowerPoint — best if licensed, metadata-aware
  - Gamma — best visual design, export issues

**11:25 - 11:35 | The 5 Questions Revisited (10 min)**
- Return to the diagnostic questions:
  1. What's the outcome?
  2. What does it need?
  3. Where does the data live?
  4. What could break?
  5. What lever do you tweak?
- "You've now experienced every one of these hands-on. This isn't abstract anymore."
- **Troubleshooting framework:**
  - Retrieval wrong? → Check sources, add metadata
  - Format wrong? → Update skill instructions
  - Content inaccurate? → Add examples, use source-grounded tools
  - Inconsistent? → Add structured steps
- "You now know which lever to pull."

**11:35 - 11:45 | The Bigger Picture: What About Your Members? (10 min)**
- "Everything today = internal productivity. What about your members?"
- Paint the picture:
  - Members chat with 5 years of your research
  - Filtered by topic, date, region — proper chunking + metadata
  - Grounded answers with citations from YOUR reports
  - Your branding, your guardrails, your data
- "Built-in connectors can't do this. Custom builds can."
- Light touch — plant the seed, don't pitch hard

**11:45 - 11:55 | Action Plan — Your Sprint Backlog (10 min)**
- **This week:**
  1. Refine the Market Report + Social Media skills with real data
  2. Share the Project with the team
  3. Add metadata headers to your next 5 documents
  4. Try NotebookLM with your last 3 monthly reports
- **This month — more skills to build in this Project or new ones:**
  5. **Survey Question Designer** (Mike's topic list: Member Surveys)
  6. **Source Summarizer** — 5 articles in, categorized summary out (Mike's topic list: Market Summaries / Curated News Feeds)
  7. **Presentation Outliner** — report in, slide structure + speaker notes out (Mike's topic list: Slide Content Creation)
  8. **Member Briefing Generator** — curated updates for specific member segments
- **Also:**
  9. Audit document organization (naming, folders, metadata)
  10. Explore Claude Pro ($20/month) — compare output

**11:55 - 12:00 | Close (5 min)**
- Leave-behinds distributed (6 guides)
- Round the table: one takeaway each
- "The frameworks don't change. The tools will. You now have both."
- Contact info, next conversation

---

## Appendix: Mike's Four Outcomes — Where They're Addressed

From Mike's original email request (March 23, 2026):

| Outcome | Where Addressed |
|---|---|
| **#1 — Monthly market report using AI** | Phase 3: Skill #1 "Monthly Market Report" (explicit build); Phase 3 NotebookLM demo (source-grounded alternative) |
| **#2 — Best use cases for AI tools** (Claude, ChatGPT, Gemini, Copilot, etc.) | Phase 2 (tool landscape intro); Phase 3 (Claude connector demo); Phase 4 (Claude side-by-side demo, honest tool comparison table) |
| **#3 — Build purpose-specific agents** (scan, curate, synthesize, draft social content) | Phase 2 (Projects framing — agents are Projects + Skills); Phase 3: Skill #2 "Social Media Content Agent" — **built explicitly as Mike described it** |
| **#4 — AI for team productivity** | Throughout — Projects + Skills sharing model, connectors, document discipline, action plan with additional skills to build |

## Appendix: Mike's Topic List — Where They're Addressed

From Mike's email, he listed specific topics of interest. Each is covered:

| Topic | Where Addressed |
|---|---|
| **Slide Content Creation** | Phase 3 NotebookLM demo (generates slides from sources); Phase 4 tool landscape; Action plan: "Presentation Outliner" skill |
| **Market Summaries / Curated News Feeds** | Phase 3 Skill #1 (Market Report) — this IS a market summary skill; Action plan: "Source Summarizer" skill as extension |
| **Member Surveys** | Action plan: "Survey Question Designer" skill; Mentioned in Phase 2 Projects framing (Member Surveys project example) |
| **Creation & Use of Agents** | Phase 2 (Projects + Skills as agent architecture); Phase 3 (building two purpose-specific agents hands-on) |

## Appendix: Key Concepts to Weave In (Not Lecture On)

These come up naturally during demos and hands-on work:

- **Chunking:** When connector doesn't surface a doc → "here's why, and here's the metadata workaround"
- **Context windows:** When comparing Claude (200K) vs ChatGPT (128K)
- **Hallucination:** When a skill generates a fake stat → "this is why source-grounding matters"
- **Few-shot learning:** When a skill produces better output with examples → "you taught it by showing"
- **Temperature:** If someone asks about creativity vs. consistency → "there's a dial for that"
- **Outcome vs. task:** Every time a skill works well, it's because the outcome was clear
- **RAG vs. context window:** Claude loads docs into context; ChatGPT pre-indexes

## Appendix: Upsell Talking Points (Light Touch)

- Member-facing research chat tool
- Custom data pipeline with structured chunking for their report format
- Metadata filtering (topic, date, region, document type)
- Branded web experience for members
- "Your research is your competitive advantage. Right now it lives in PDFs. What if members could interact with it?"

## Appendix: The Compound Framework (Philosophical Backdrop)

The workshop doesn't lecture on these, but they structure how the day flows:

- **Signal** (what problem to solve) — Discover phase
- **Source** (map the work) — Discover phase
- **Design** (who does what) — Frame phase (human vs. skill)
- **Build** (deploy into existing workflows) — Build phase
- **Deliver** (measure what changed) — Build phase (testing skills)
- **Compound** (carry it forward) — Take Home phase (sprint backlog)
