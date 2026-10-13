# Reusable Prompt System

Use these prompts in ChatGPT, Claude, or Gemini. Replace bracketed inputs with verified information. Never ask the model to invent business facts or keyword metrics.

## Prompt 1 — Business Context
```text
Act as an SEO content strategist. Use only the verified business facts below.
Business: [BUSINESS NAME]
Location/service area: [VERIFIED LOCATION]
Services/products: [VERIFIED LIST]
Audience: [AUDIENCE]
Official URLs: [URLS]
Brand voice: friendly, useful, clear, factual.
Goal: plan helpful SEO content for people in the stated service area.

Separate verified facts from assumptions. Do not invent prices, opening hours, menu items,
facilities, reviews, awards, statistics, or URLs. Ask questions if important information is missing.
Return: business summary, audience needs, content opportunities, facts to verify, and exclusions.
```

## Prompt 2 — Keyword and Intent Map
```text
Create a qualitative keyword hypothesis list for [BUSINESS TYPE] in [LOCATION].
For every phrase include: topic, likely search intent, audience question, recommended page,
and what evidence should be checked in live search results.
Do not fabricate search volume, keyword difficulty, ranking, traffic, or trend statistics.
Mark every phrase as a hypothesis until validated.
Return a Markdown table and a short validation checklist.
```

## Prompt 3 — Content Cluster
```text
Using the approved keyword and intent map, propose one pillar article and 4 supporting articles.
For each page provide: working title, reader problem, primary and secondary keyword hypotheses,
search intent, unique angle, H2 sections, CTA recommendation, and relevant internal links.
Avoid keyword cannibalization: each page must have a distinct purpose.
Do not invent URLs; use [URL TO ADD AFTER PUBLISHING] placeholders.
```

## Prompt 4 — H1–H3 Blog Outline
```text
Create an SEO-friendly outline for this article:
Title: [TITLE]
Target audience: [AUDIENCE]
Primary keyword hypothesis: [KEYWORD]
Search intent: [INTENT]
Verified facts: [FACTS]
Required length: [WORD COUNT RANGE]

Include one H1, a logical H2/H3 hierarchy, the reader's key questions, a concise introduction plan,
examples or checklists where useful, a conclusion, and a natural CTA.
Use the keyword naturally; do not stuff it. Flag claims requiring sources. Do not invent facts.
Return Markdown only.
```

## Prompt 5 — Long-form Draft
```text
Write a helpful first draft from the approved outline.
Requirements:
- Satisfy the stated search intent before promoting the business.
- Use clear, natural language and short paragraphs.
- Use H2/H3 headings and practical examples.
- Avoid unsupported superlatives, fake statistics, fake quotes, and fabricated local details.
- Clearly mark missing business facts as [VERIFY BEFORE PUBLISHING].
- Include a meta title, meta description, suggested slug, and one primary keyword hypothesis.
- Suggest internal links using descriptive anchor text and placeholder URLs only.
- Do not claim the article guarantees rankings.
Return Markdown.
```

## Prompt 6 — Internal Links
```text
Given the article list below, suggest relevant contextual internal links.
For each link provide source article, destination article/page, suggested anchor text, and why it helps readers.
Use only URLs provided by me. If URLs are not available, use page titles and [URL TO ADD].
Avoid repetitive exact-match anchors and links that do not fit the paragraph.
```

## Prompt 7 — SEO and Accuracy QA
```text
Audit the draft below for:
1. Search intent match
2. H1-H3 structure
3. Natural keyword use
4. Readability and usefulness
5. Local relevance
6. Internal-link opportunities
7. Unsupported claims or invented business details
8. Repetition, fluff, and spelling
9. Missing verification/source requirements

Return a table with issue, severity, evidence/section, and recommended fix.
Do not claim that content will rank. Do not add new facts unless sourced.
```

## Prompt Workflow
Business context → keyword hypotheses → live validation → intent mapping → cluster plan → outline → draft → internal links → factual review → final publication pack.
