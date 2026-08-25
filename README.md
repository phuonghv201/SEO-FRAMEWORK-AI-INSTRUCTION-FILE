# SEO Framework — AI Instruction File

An AI system-prompt file that turns an LLM into an SEO strategist operating under the **Persona → Pillar → Spoke → Cluster** framework. Paste it into a system prompt, custom GPT, or Claude Project, then supply your project's info — the AI will generate a full SEO content plan following a fixed set of rules (no freelancing on structure).

## Files

| File | Language | Use for |
|---|---|---|
| [`seo.md`](seo.md) | Vietnamese (original) | Vietnamese-market projects / Vietnamese content teams |
| [`seo.en.md`](seo.en.md) | English (translation) | English-market projects, or feeding to English-only tools |

Both files are functionally identical — same rules, same output formats. Keep them in sync: if you edit the ruleset in one, port the change to the other.

## How to use

1. Copy the full contents of the file matching your target language into your AI tool's system prompt / project instructions.
2. In the same conversation, provide the 5 required inputs the framework asks for:
   - Industry / product / service
   - Target market & language
   - Business goal (leads / sales / awareness) + KPI if available
   - Current site state (new vs. existing — with a URL list/sitemap if existing)
   - Who will produce the content (brand team, agency, etc.)
3. The AI outputs, in order: a Persona table → Pillar/Spoke/Cluster plan → a Cannibalization Map — each as a fixed markdown table (Formats A/B/C in the file).

## What the framework enforces

- **Persona-first**: personas are named by buying situation, not demographics — always generated before any keyword or article.
- **Three-tier content structure**: 1 Pillar (King Page) → 4–6 Spokes (T1 solution articles) → 4–6 Cluster articles per Spoke (T2 knowledge articles), ~25–35 URLs per cluster.
- **One intent, one URL**: every new URL is checked against a Cannibalization Map before being added, to prevent two pages competing for the same search intent.
- **Fixed priority order**: Pillar + all Spokes are P0 (must-ship) before any Cluster article ships.
- **A self-check pass**: the AI validates its own plan against the hard rules before handing it back.

See either file for the full rule set (R1–R13), the on-page SEO checklist, and the exact output table formats.
