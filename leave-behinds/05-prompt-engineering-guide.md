# Prompt Engineering — Practical Guide
### How to get better results from any AI tool

---

## The Core Insight

A great prompt on a cheap model often beats a lazy prompt on an expensive model. The AI is only half the equation — your skill as a prompter is the other half.

**The AI brings:** parameters, training data, capabilities
**You bring:** clarity, context, examples, iteration

---

## 7 Principles That Work Across Every Tool

### 1. Be Clear and Direct

Tell the AI exactly what you want. Vague prompts get vague results.

| Instead of... | Try... |
|---|---|
| "Write a market update" | "Write a 2-page market update with sections for Market, Policy, Technology, and Strategy. Each section should have 4-6 bullet points with source citations." |
| "Make this better" | "Rewrite this paragraph to be more concise, use active voice, and include a specific data point." |

### 2. Use Examples (Few-Shot Learning)

Show the AI what good output looks like. One strong example teaches more than a page of rules.

```
Write a LinkedIn post about our latest market findings.
Use a tone based on this example:

[paste an actual LinkedIn post you've written that you like]
```

The AI picks up your voice, format, and style from the example — without you having to describe them.

### 3. Invite Participation

Work WITH the AI, not AT it. Ask it to collaborate rather than just execute.

```
I need to put together our monthly market update. 
Please ask me questions so we can build a high-quality 
report together.
```

The AI will ask about your audience, key themes, data sources — and the resulting output will be more tailored than a one-shot prompt.

### 4. Use Chains of Thought

Ask the AI to think through a problem step by step before answering.

```
Think step-by-step through the implications of the new 
tariff policy for aftermarket suppliers. Consider supply 
chain, pricing, and competitive positioning. Then summarize 
the top 3 implications.
```

This produces deeper analysis than "What are the implications of the new tariff policy?"

### 5. Separate Instructions from Data

Keep your instructions clear by separating them from the content you want processed.

```
INSTRUCTIONS:
Summarize the following article into 3 bullet points for 
our monthly market update. Focus on implications for 
automotive suppliers.

ARTICLE:
[paste article text here]
```

### 6. Assign Roles

Give the AI a persona that shapes its perspective and expertise.

```
You are a research analyst specializing in automotive 
aftermarket trends. You write for an audience of industry 
executives who need concise, data-driven insights.
```

Roles reduce your work — the AI adopts the right tone, depth, and vocabulary without you specifying each one.

### 7. Tweak Parameters (Temperature)

Most AI tools have a "temperature" or "creativity" setting:
- **Low temperature (0.2):** More consistent, predictable, factual — good for reports and data summaries
- **High temperature (0.8-1.0):** More creative, varied — good for brainstorming and marketing copy

Match the setting to the task. Market reports want low temperature. LinkedIn posts might want higher.

---

## The Outcome Mindset

The biggest shift in effective prompting: think about **outcomes**, not tasks.

| Task thinking | Outcome thinking |
|---|---|
| "Summarize this article" | "Extract the 3 insights our members need to act on this week" |
| "Write a social media post" | "Create a LinkedIn post that positions MEMA as the go-to source for aftermarket intelligence" |
| "Reformat this data" | "Turn this raw data into a format our team can use in the monthly report without further editing" |

Skills work best when directed at outcomes. They automate not just a task, but a process.

---

## Common Patterns for Research Teams

### Source Summarization
```
ROLE: You are a research analyst for an automotive industry 
association.

TASK: Summarize the following 3 articles into a single 
briefing for our monthly market update.

FORMAT: 
- One paragraph summary per article (3-4 sentences)
- A "Key Implications" section with 2-3 bullet points
- Source citation for each article

RULES:
- Only use facts from the provided articles
- Never fabricate statistics
- Flag any claims that seem unverified

ARTICLES:
[paste articles]
```

### Report Section Drafting
```
Using the following raw notes, draft the "Policy" section 
of our monthly market update.

Match the format and tone of this example:
[paste a previous Policy section]

Raw notes:
[paste notes]

Important: Only include facts from the provided notes. 
If a statistic is mentioned, include the source.
```

### Content Repurposing
```
Take our monthly market update (attached) and create:
1. Three LinkedIn posts highlighting key findings
2. A 5-bullet executive summary for email
3. Three discussion questions for our next member meeting

Maintain our professional but accessible tone. 
Each LinkedIn post should be under 200 words.
```

---

## When to Prompt vs. When to Build a Skill

| Situation | Approach |
|---|---|
| One-time task | Write a prompt |
| You do it monthly | Build a skill |
| Multiple people do it | Build and share a skill |
| It should run the same way every time | Skill with structured steps |
| It requires judgment each time | Prompt with a template |

---

## Quick Troubleshooting

| Problem | Likely Cause | Fix |
|---|---|---|
| Output is too generic | Prompt is too vague | Add specifics: audience, format, constraints |
| Output misses the point | No context about your situation | Add role + background context |
| Tone is wrong | No examples | Add 1-2 examples of good output |
| Results are inconsistent | No structured format | Add explicit format requirements |
| AI makes things up | No accuracy guardrails | Add: "Only use provided sources. Never fabricate." |
| Output is too long/short | No length guidance | Specify: "3-4 sentences per section" or "under 200 words" |

---

## Resources

- **agentskills.io** — Open standard for AI skills (best practices for structured prompts)
- **Anthropic's prompt engineering docs** — claude.ai/docs
- **OpenAI's prompt engineering guide** — platform.openai.com/docs

---

*Super Web Pros | superwebpros.com | Jesse Flores — jesse@superwebpros.com*
