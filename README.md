# Walter Skills

12 drop-in Claude project skills. Free, no signup. Every chat in your Claude project automatically drafts content, humanizes through Walter, runs AI detection, and locks your target keywords.

## What this is

A Claude Skill is a markdown file you paste once into your Claude project's instructions. After that, every chat in that project knows how to use [Walter Writes](https://walterwrites.ai) for humanization, detection, and keyword protection. No more rewriting the same brief every time.

## The 12 skills

| # | Skill | For |
|---|---|---|
| SK-01 | [SEO Content Writer](./skills/seo-writer/) | Anyone producing SEO content with Claude |
| SK-02 | [Agency QC Pipeline](./skills/agency-qc/) | Agencies running content through a team of writers |
| SK-03 | [Local SEO Machine](./skills/local-seo/) | Local agencies and multi-location businesses |
| SK-04 | [Content Repurposer](./skills/repurposer/) | Content teams turning one post into many formats |
| SK-05 | [E-commerce Product Writer](./skills/ecommerce/) | Stores writing product descriptions at scale |
| SK-06 | [Newsletter Writer](./skills/newsletter-writer/) | Newsletter operators producing weekly content |
| SK-07 | [Programmatic SEO](./skills/programmatic-seo/) | Teams building large numbers of templated pages |
| SK-08 | [Brand Voice Adapter](./skills/brand-voice-adapter/) | In-house teams and agencies serving multiple clients |
| SK-09 | [Content Refresh](./skills/content-refresh/) | Sites updating old content for new ranking potential |
| SK-10 | [Lead Magnet Writer](./skills/lead-magnet-writer/) | B2B teams producing gated content |
| SK-11 | [Social Media](./skills/social-media/) | Social teams adapting copy for each platform |
| SK-12 | [Docs Writer](./skills/docs-writer/) | Product teams writing help center articles |

## How to install one

1. **Open your Claude project** (or create a new one).
2. **Open Project Instructions**.
3. **Pick a skill folder** above. Open its `SKILL.md`.
4. **Copy the entire markdown** into your project instructions.
5. **Install [Walter MCP](https://walterwrites.ai/humanize-ai-text-inside-claude/)** so Claude can actually call Walter's humanizer, detector, and keyword preservation tools.

Once both are in place, every chat in that project knows to draft, humanize, detect, and protect keywords automatically. You just describe what you want.

## Why you need Walter MCP for these to work

The skills tell Claude what to do. Walter MCP gives Claude the tools to actually do it (humanize text, run AI detection, lock keywords). Without Walter MCP, Claude will follow the prompts but can't perform the humanization or detection steps. [Install Walter MCP →](https://walterwrites.ai/humanize-ai-text-inside-claude/)

## Use cases at a glance

Every skill is built around a real workflow we've seen content teams running through Claude. The structure is consistent across all 12:

- **What Claude does by default** — the standard behavior once the skill is loaded
- **Humanization modes** — when to use Light, Balanced, or Aggressive
- **Edge cases** — what to do when content is pasted in, when keywords are mentioned, when something looks off
- **Output format** — what the user sees at the end

If you find yourself wanting to modify a skill, fork the repo and adjust. The whole point of markdown skills is they're readable and editable.

## License

MIT. Use, modify, share. See [LICENSE](./LICENSE).

## Made by

[Walter Writes AI](https://walterwrites.ai) — the humanizer SEO teams use to ship AI content that passes detection and keeps keywords intact.

For a community guide with one-click skill copy, install walkthroughs, and live demos, see [waltermcp.com](https://waltermcp.com).
