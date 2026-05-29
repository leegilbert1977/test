# Marketing OS — CLAUDE.md

> This file is the shared brain for all Marketing OS agents.
> Every agent reads this before acting. Keep it under 150 lines.
> Update it whenever you correct an agent's behavior.

---

## 1. What this system does

This is a Marketing OS built with Claude Code. It automates and accelerates:
- Content creation across all channels
- Campaign planning and execution
- Market and competitor research
- Performance analytics and reporting
- Cross-tool workflow automation

All agents operate within the rules defined in this file.

---

## 2. Company context

**Company name:** [YOUR COMPANY NAME]
**Industry:** [e.g. B2B SaaS / eCommerce / Professional Services]
**Stage:** [e.g. Series A / Growth / Enterprise]
**Primary market:** [e.g. US mid-market companies, 100–1000 employees]
**Website:** [yourcompany.com]

---

## 3. Ideal customer profile (ICP)

**Primary persona:** [e.g. VP of Marketing at a B2B SaaS company]
- **Role:** [Job title and function]
- **Company size:** [e.g. 50–500 employees]
- **Pain points:** [Top 2–3 problems they face]
- **Goals:** [What success looks like for them]
- **Objections:** [Common reasons they hesitate to buy]

**Secondary persona (optional):** [e.g. Marketing Manager executing day-to-day]
- **Role:** [Job title and function]
- **Key motivation:** [What drives their decisions]

---

## 4. Brand voice

### Core personality
[Describe your brand in 3–5 adjectives, e.g.: "Direct, warm, confident, a little witty — never corporate or jargon-heavy."]

### Voice rules
- **DO:** [e.g. Use active voice. Lead with the benefit. Use short sentences.]
- **DO:** [e.g. Speak to the reader as "you". Use concrete examples over abstractions.]
- **DO:** [e.g. Acknowledge complexity when it's real — don't oversimplify.]
- **DON'T:** [e.g. Use buzzwords like "synergy", "leverage", "holistic", "paradigm".]
- **DON'T:** [e.g. Write passive headlines. Don't bury the lead.]
- **DON'T:** [e.g. Use exclamation points more than once per piece.]

### Tone by channel
| Channel     | Tone                          | Notes                                  |
|-------------|-------------------------------|----------------------------------------|
| Blog        | [e.g. Thoughtful, expert]     | [e.g. Long-form, cite sources, POV]    |
| Email       | [e.g. Direct, conversational] | [e.g. Short paragraphs, single CTA]    |
| LinkedIn    | [e.g. Professional, insight-led] | [e.g. Hook-heavy, avoid self-promo]  |
| Twitter/X   | [e.g. Punchy, opinionated]    | [e.g. < 280 chars, strong take]        |
| Paid ads    | [e.g. Benefit-first, urgent]  | [e.g. Outcome in headline, proof]      |

---

## 5. Messaging hierarchy

### Primary value proposition
[One sentence: What you do, for whom, and the core outcome. e.g. "We help B2B marketing teams cut campaign production time in half without sacrificing quality."]

### Proof points (use these in content)
1. [e.g. "Customers see 40% faster time-to-publish"]
2. [e.g. "Rated #1 for ease of use in G2's 2025 report"]
3. [e.g. "Used by 500+ marketing teams across 30 countries"]

### Key differentiators vs competitors
- **vs [Competitor A]:** [How you're different / better]
- **vs [Competitor B]:** [How you're different / better]
- **vs doing nothing:** [Cost of inaction]

---

## 6. Content strategy

### Content pillars (use these to guide topic selection)
1. **[Pillar 1]** — [e.g. Marketing Operations — how-to, process, efficiency]
2. **[Pillar 2]** — [e.g. Industry trends — thought leadership, POVs]
3. **[Pillar 3]** — [e.g. Customer stories — proof, outcomes, social proof]
4. **[Pillar 4]** — [e.g. Product education — features, use cases, tutorials]

### SEO focus
- **Primary keywords:** [list 3–5 core terms you want to rank for]
- **Avoid:** [e.g. Don't use "AI-powered" in headlines — too generic]

### Content calendar location
- Notion database: [link or name of your Notion content calendar]
- Approval workflow: [e.g. Draft → Review → Approved → Scheduled]

---

## 7. Campaign defaults

When planning any campaign, default to these unless instructed otherwise:

- **Primary goal:** [e.g. Pipeline generation / brand awareness / retention]
- **Default CTA:** [e.g. "Book a demo" for bottom-funnel; "Read the guide" for top-funnel]
- **Campaign naming convention:** `[YEAR]-[QUARTER]-[CAMPAIGN-NAME]` e.g. `2026-Q2-summer-launch`
- **UTM structure:** `utm_source=[channel]&utm_medium=[type]&utm_campaign=[name]`
- **Budget approval threshold:** [e.g. Flag any spend recommendation over $5,000 for human review]

---

## 8. Tool integrations

These MCP-connected tools are available to all agents:

| Tool         | Primary use in this OS                          |
|--------------|-------------------------------------------------|
| HubSpot      | CRM data, lead scoring, email sequences         |
| Notion       | Content calendar, campaign briefs, knowledge base |
| Asana        | Campaign task management, approvals             |
| Linear       | Product marketing issue tracking                |
| Gmail        | Outbound sequences, internal comms              |
| Canva        | Asset creation briefs and design outputs        |
| Figma        | Design system reference, mockups                |
| Miro         | Strategy workshops, campaign planning boards    |
| Monday.com   | Project timelines, workload tracking            |
| Intercom     | In-app messaging, lifecycle triggers            |
| Box          | Asset storage and file management               |
| Atlassian    | Confluence docs, Jira marketing tickets         |

---

## 9. Agent rules (apply to all agents)

- **Always ground recommendations in data** — cite sources, link to reports, reference real numbers when possible.
- **Flag uncertainty clearly** — if you're not sure, say so. Don't invent metrics or quotes.
- **Never publish directly** — always write to draft/queue state. A human approves before anything goes live.
- **Respect budget limits** — any recommendation involving spend over the threshold in Section 7 must include a flag for human review.
- **Keep brand voice consistent** — refer back to Section 4 before writing any customer-facing copy.
- **Log campaign decisions** — after any significant output (brief, strategy doc, report), create a dated entry in `data/` for future reference.
- **Ask before deleting** — never delete records, files, or tasks without explicit confirmation.

---

## 10. Known corrections (update as you go)

> Add a bullet here every time you correct an agent. This prevents the same mistake from repeating.

- [Date] [Agent]: [What went wrong → what the correct behavior is]
- [Date] [Agent]: [What went wrong → what the correct behavior is]

---

## 11. Glossary

> Define any internal terms, abbreviations, or product names agents should know.

- **[TERM]:** [Definition]
- **[TERM]:** [Definition]
- **MQL:** Marketing Qualified Lead — [your specific definition/threshold]
- **SQL:** Sales Qualified Lead — [your specific definition/threshold]

---

*Last updated: [DATE] · Owner: [YOUR NAME/TEAM]*
