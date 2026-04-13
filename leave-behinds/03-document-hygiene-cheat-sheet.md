# Document Hygiene for AI — Cheat Sheet
### Small changes that make AI retrieval dramatically better

---

## The Problem

When you connect SharePoint or Google Drive to an AI tool, it:
1. **Chunks** your documents into ~800-token pieces
2. **Embeds** those chunks as numbers (vectors)
3. **Searches** semantically when you ask a question

This process is automatic and opaque. You can't control how it chunks. But you CAN make your documents easier for AI to find and understand.

---

## The #1 Thing You Can Do Today

### Add a Metadata Header to Every Document

At the top of each document, add a structured block:

```
---
Document Type: Market Update
Topic: Tariffs, Trade Policy, Aftermarket
Region: North America
Period: October 2025
Author: MEMA Insights Team
Keywords: EV incentives, USMCA, government shutdown, supply chain
Summary: Monthly market update covering GDP projections, tariff changes,
  EV market trends, and technology developments in automotive supply chain.
---
```

**Why this works:** AI tools index the full text of your documents. This header becomes searchable context — even when the AI connector doesn't support metadata filtering natively.

**When to add it:** Every new document, starting now. Backfill your most important existing documents when you have time.

---

## File Naming Conventions

### Use Descriptive, Consistent Names

**Bad:**
- `Report_Final_v3.pdf`
- `Copy of Market Update.docx`
- `Untitled document`

**Good:**
- `Market-Update_2025-10_Tariffs-EV-Supply-Chain.pdf`
- `Policy-Brief_2026-Q1_USMCA-Renegotiation.docx`
- `Member-Survey_2025-12_EV-Readiness-Results.pdf`

### Pattern: `{Type}_{Date}_{Topic}.{ext}`

Types: `Market-Update`, `Policy-Brief`, `Member-Survey`, `Presentation`, `Research-Note`

---

## Folder Structure

### Organize by Type and Date

```
/Research
  /Market Updates
    /2025
    /2026
  /Policy Briefs
    /2025
    /2026
  /Member Surveys
  /Presentations
/Sources
  /News Articles
  /Government Documents
  /Industry Reports
```

**Why this helps:** While most AI connectors don't filter by folder, folder paths are often included in indexed metadata. And it helps your team find things without AI.

---

## Document Structure Best Practices

### Use Clear Headings
AI chunks break on headings more reliably than on arbitrary character counts. Clear headings = cleaner chunks.

### Keep Documents Focused
A 5-page focused brief retrieves better than a 100-page omnibus report. If a document covers multiple topics, consider splitting it.

### Don't Bury Key Info in Tables or Images
Most AI connectors extract text only. If critical data lives in a chart, add a text summary nearby.

### Add a Summary at the Top
Start every document with a 2-3 sentence summary. This gives the AI (and your team) a quick way to assess relevance.

---

## Tool-Specific Notes

| Tool | What It Indexes | Metadata Support | Sync Frequency |
|---|---|---|---|
| **ChatGPT Enterprise + SharePoint** | Full text of docs | Does NOT filter by SharePoint managed metadata | Every few hours |
| **ChatGPT Enterprise + Google Drive** | Full text of docs | Does NOT filter by Drive labels | Every few hours |
| **Claude + Google Drive** | Google Docs only (not PDFs!) | No metadata filtering | On-demand |
| **Microsoft 365 Copilot + SharePoint** | Full text + metadata | YES — uses managed metadata, term stores, content types | Near real-time |
| **NotebookLM** | Uploaded sources only | You control exactly which sources | Manual (you upload) |

**Key takeaway:** The metadata header workaround works with ALL of these tools because they all index text. Invest in SharePoint managed metadata if you use (or plan to use) Microsoft 365 Copilot.

---

## Quick Wins Checklist

- [ ] Add metadata headers to your next 5 documents
- [ ] Establish a file naming convention (share with team)
- [ ] Add a summary paragraph to the top of each new report
- [ ] Avoid publishing critical data only in images/charts — add text summaries
- [ ] Review folder structure — does it help AI (and humans) find things?

---

*Super Web Pros | superwebpros.com | Jesse Flores — jesse@superwebpros.com*
