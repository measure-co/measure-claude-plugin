---
name: fix-ai-citations
description: Diagnose why a page or brand isn't cited by AI engines and produce concrete fixes using Measure's audit and content tools. Use when the user asks why competitors get cited instead, wants a GEO page audit, or a content brief to win AI citations.
---

# Fix AI citations (Measure)

1. `get_content_gaps` / `get_top_category_questions` — prompts where competitors are cited and the brand isn't.
2. `audit_page` on the user's best-matching URL (GEO readiness: structure, answerability, schema, crawlability); `technical_check` for robots/llms.txt/AI-crawler access.
3. `serp_gap` and `content_brief` for the target query to see what the cited pages cover.
4. Output a fix list ordered by impact; offer `save_draft` for any rewritten content.

Never invent metrics — quote only tool results, and note when a tool reports data as unavailable.
