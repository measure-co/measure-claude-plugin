# Measure for Claude

The [Measure](https://www.measure.co) plugin for Claude. Track and improve how your brand appears in AI search — ChatGPT, Perplexity, Gemini, Claude and Google AI Overviews.

## What you get
- **Remote MCP server** `https://www.measure.co/api/mcp` (OAuth 2.1 — sign in with your Measure account, no API keys)
- **Skills:** `ai-visibility-report`, `fix-ai-citations`
- **Command:** `/measure:ai-visibility [brand]`

Tools include visibility summary/history, share of voice vs competitors, citation trends, content gaps, LLM mentions, GA4 AI-referral traffic, Search Console performance, GEO page/site audits, content briefs, SERP gaps, reports and drafts.

## Install
```
/plugin marketplace add measure-co/measure-claude-plugin
/plugin install measure@measure
```
Then run `/mcp`, choose **measure**, and sign in. Claude Desktop / claude.ai users can instead add a custom connector with URL `https://www.measure.co/api/mcp`.

## Requirements
A Measure account (free plan available). Data access is scoped to your workspace; tools are read-only except saving reports/drafts and brand facts.

## Support & privacy
- Docs: https://www.measure.co/app/mcp
- Privacy: https://www.measure.co/privacy · Terms: https://www.measure.co/terms
- Contact: maveninnovationltd@gmail.com

MIT © Measure (Maven Innovation Ltd)
