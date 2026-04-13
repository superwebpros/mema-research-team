# AI Skills — Quick Start Guide
### Build reusable, shareable workflows for your team

---

## What Is a Skill?

A skill is a folder of instructions, examples, and resources that tells an AI agent how to do a specific task — accurately and consistently, every time.

Think of it as a recipe: what to do, how to do it, and what good output looks like.

Skills are part of an **open standard** (agentskills.io) — meaning the same skill concepts work across ChatGPT, Claude, and other AI tools. You're not locked into one platform.

---

## Both ChatGPT and Claude Have Skill Wizards

You don't need to write skills from scratch. Both platforms have built-in skill creation assistants:

**ChatGPT:** Every account includes a `skill-creator` skill. Just ask ChatGPT to create a skill in conversation — it will ask you questions, draft the skill, and let you install it.

**Claude:** Claude understands the skill format natively. Ask Claude to create a skill and it generates properly structured content. You can also use Claude Projects to organize skills by topic.

**The best way to create a skill:**
1. Do the task once with the AI, providing context as you go
2. Notice what information you repeatedly provide
3. Ask the AI: "Create a skill that captures this workflow"
4. Review, test, iterate

---

## How to Create a Skill in ChatGPT

### Method 1: In Conversation (Easiest)
1. Start a new chat
2. Describe the skill you want: *"Create a skill that takes raw news articles and produces a 2-page market update in MEMA's format"*
3. ChatGPT will ask follow-up questions — answer based on your actual workflow
4. Click **Install**
5. Test it in a new chat

### Method 2: Skills Editor
1. Click your **profile icon** (bottom-left) → **Skills**
2. Click **New skill** → **Create with editor**
3. Write instructions, add examples, define steps
4. Save and install

### Sharing Skills with Your Team
1. Profile → **Skills** → hover over skill → **...** → **Share**
2. Share with people, groups, or copy link
3. Set permissions: **Can use** vs. **Can edit**

One person builds it. The whole team uses it consistently.

---

## Tips for Writing Better Skills

*From agentskills.io — the open standard for AI skills*

### 1. Be Concise — The AI Is Already Smart
Only add context the AI doesn't already have. Challenge each piece of information:
- "Does the AI really need this explanation?"
- "Can I assume the AI knows this?"

**Good:** A specific example of your output format
**Bad:** A paragraph explaining what a PDF is

### 2. Show, Don't Tell — Use Examples
One strong example teaches more than a page of rules. Provide input/output pairs:

```
Input: Three articles about EV tariff changes
Output: [paste your actual October market update as the example]
```

### 3. Match Specificity to Risk

**High freedom** (multiple valid approaches): "Review the article and identify key policy implications"

**Low freedom** (consistency critical): "Use exactly these sections: Market, Policy, Technology, Strategy. Each section must have 4-6 bullet points with source citations in parentheses."

Use low freedom for formats that must be consistent. Use high freedom when creative judgment helps.

### 4. Add Guardrails Where It Matters
For a research team, accuracy guardrails are critical:
- "Only use data from provided sources. Never fabricate statistics."
- "Include source citations for every factual claim."
- "If data is unavailable, state 'data not available' rather than estimating."

### 5. Test and Iterate
1. Run the skill with real inputs
2. Note what's wrong (format? tone? hallucinated data?)
3. Edit the skill instructions to fix it
4. Test again — each round gets better

### 6. Use Consistent Terminology
Pick one term and stick with it throughout:
- Always "market update" (not "report" sometimes, "newsletter" other times)
- Always "source citation" (not "reference" sometimes, "link" other times)

---

## Skill Ideas for Your Team

| Skill | What It Does | Who Uses It |
|---|---|---|
| **Market Report Generator** | Raw sources in → formatted 2-page report out | Research team |
| **LinkedIn Post Creator** | Market update in → 3-5 social posts out | Comms/social |
| **Source Summarizer** | 5 articles in → categorized summary out | Researchers |
| **Member Briefing Outliner** | Report in → presentation outline + speaker notes out | Presenters |
| **Survey Question Designer** | Research topic in → survey questions out | Survey leads |
| **Design Pass** | Generated slides in → formatted slides with consistent typography/colors out | Anyone |

---

## The Open Standard: agentskills.io

Skills follow an open standard developed by Anthropic and adopted across the industry. This means:

- **Portable:** Skills built for one tool can inform skills on another
- **Version-controlled:** Skills are just files — put them in Git, share them, track changes
- **Team knowledge:** Capture institutional knowledge in reusable packages

The full spec, best practices, and example skills are at **agentskills.io**

---

## Where Your Data Lives

| What | Where | Training? |
|---|---|---|
| Skills | ChatGPT workspace / Claude Projects | Not used for training (Enterprise/Team plans) |
| Conversations | Platform servers | Not used for training (Enterprise/Team plans) |
| Uploaded files | Processed and indexed by platform | Covered by your plan's DPA |

---

## Resources

- **Agent Skills open standard:** agentskills.io
- **Best practices (detailed):** agentskills.io → "What are skills?" and the best practices guide
- **Example skills:** github.com/anthropics/skills
- **ChatGPT Skills docs:** help.openai.com/en/articles/20001066-skills-in-chatgpt
- **Claude Skills docs:** support.claude.com/en/articles/12512176-what-are-skills

---

*Super Web Pros | superwebpros.com | Jesse Flores — jesse@superwebpros.com*
