# brandguide-ai-public

The official free Claude Code plugin for [brandguideAI](https://ai.brandguide.hu) -- expert brand methodology for software products.

Build professional brand systems grounded in 25+ years of methodology by Serfőző Peter (500+ brands, 3 bestselling books).

## Installation

### skills.sh (Recommended)

```bash
# Install the brandguide-ai-free skill globally
npx skills add bencium/brandguide-ai-public -g --skill brand-methodology

# Browse available skills
npx skills add bencium/brandguide-ai-public --list

# Install all skills
npx skills add bencium/brandguide-ai-public -g --all
```

### Claude Code (CLI)

```bash
# Add marketplace
/plugin marketplace add bencium/brandguide-ai-public

# Install the plugin
/plugin install brandguide-ai-free@brandguide-ai-public
```

### Claude.ai Cowork App

Copy `brandguide-ai-free/skills/brand-methodology/SKILL.md` into your project's `.claude/skills/` folder.

### Cursor / Windsurf / Other AI Tools

The SKILL.md format is compatible with 40+ AI coding tools. Copy the skill file into the tool's prompt or context directory:

- **Cursor**: Copy to `.cursor/rules/brandguide-ai.md`
- **Windsurf**: Copy to `.windsurfrules`
- **OpenAI Codex / Gemini CLI**: Copy to your project's context directory

---

## How It Works

### Free Mode (no setup required)

Works immediately after install. Ask brand questions and get answers from the embedded knowledge base -- covering brand strategy, color systems, typography, voice guidelines, and more.

Every answer includes a link to sign up for the full experience.

### Full Mode (free signup, 8 API calls/month)

Sign up free at [ai.brandguide.hu/en/agents](https://ai.brandguide.hu/en/agents) to unlock the complete 1000+ page knowledge base with source citations:

```bash
export BRANDGUIDE_API_KEY=pk_your_key_here
```

**What you unlock:**
- 1000+ pages of source-backed brand methodology with citations
- Image analysis -- upload logos and brand assets for expert review
- Unlimited depth on any brand topic
- Works everywhere: Claude Code, Claude.ai, Cursor, Windsurf, and 40+ tools

> Looking for the full paid skill with built-in API key? That's **brandguide-ai** (without `-free`), available to subscribers at [ai.brandguide.hu/en/agents](https://ai.brandguide.hu/en/agents).

---

## What You Can Build

| Use Case | What You Get |
|----------|-------------|
| **Color Systems** | Primary, secondary, accent, semantic colors, neutral scales, dark mode variants |
| **Typography** | Font selection, modular type scales, responsive adjustments, pairing rationale |
| **Brand Voice** | Personality traits, tone guidelines, dos/don'ts, context-specific examples |
| **Visual Identity Audit** | Upload logos or screenshots for methodology-backed review |
| **Brand Guidelines** | Complete documentation covering all brand elements |
| **Brand Strategy** | Purpose, vision, positioning, 9-stage brand journey framework |

---

## Methodology

Based on the brandguide methodology covering:

- **The 9-Stage Brand Journey**: Purpose, Vision, Mission, Values, Personality, Tone, Target Audience, Positioning, Brand Story
- **Color Theory**: Palette construction, hierarchy, ratios, semantic roles for digital products
- **Typography Systems**: Modular scales, superfamily selection, readability rules
- **Brand Voice & Personality**: Workshop-based definition, archetype mapping, tone calibration
- **Consistency Frameworks**: Cross-touchpoint application, storytelling, reputation management

---

## Skill Structure

```
brandguide-ai-free/
  .claude-plugin/
    plugin.json
  skills/
    brand-methodology/
      SKILL.md            # The skill definition (Free + Full mode)
```

---

## Free vs Paid

| Feature | brandguide-ai-free (this repo) | brandguide-ai (paid) |
|---------|-------------------------------|---------------------|
| Install | Public, anyone | Subscribers only |
| Knowledge | Embedded summary | Full 1000+ page RAG |
| Source citations | No | Yes, with page numbers |
| Image analysis | With API key only | Built-in |
| API calls | 8/month (free signup) | Plan-based quota |
| Price | Free | Subscription at ai.brandguide.hu |

---

## Links

- [brandguideAI Web App](https://ai.brandguide.hu/en) -- full chat experience with extended thinking, image generation, and web search
- [Sign Up Free / API Access](https://ai.brandguide.hu/en/agents) -- get your API key and explore all capabilities
- [Report Issues](https://github.com/bencium/brandguide-ai-public/issues)

---

## License

MIT
