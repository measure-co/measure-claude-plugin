---
name: ai-visibility-report
description: Build an AI search visibility report for the user's brand with the Measure connector — visibility, share of voice vs competitors, citations, trend and top fixes. Use when the user asks how their brand shows up in ChatGPT, Perplexity, Gemini, Claude or Google AI Overviews, or wants a GEO/AEO report.
---

# AI visibility report (Measure)

1. `list_projects` — confirm which brand/project; pass `projectId` on later calls if not the primary one.
2. `get_visibility_summary` then `get_visibility_history` for trend; `compare_share_of_voice` for competitors.
3. `get_citations_trend` and `get_content_gaps` for which sources engines cite and where the brand is missing.
4. Optional: `get_ai_referral_traffic` (GA4) and `get_ai_accuracy` if connected.

Rules:
- Say which data you cite: **own-scan** (this workspace's tracked prompts) vs **industry corpus** (market-wide). They differ legitimately.
- Citations (answer links the domain) ≠ mentions (answer names the brand).
- `null` means not measured — never report it as 0.
- End with 3–5 prioritised fixes, each tied to a number above. Offer `save_report` to store it in Measure.
