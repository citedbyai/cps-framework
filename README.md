# Citation Probability Score® (CPS®) Framework

**The CPS® framework is a block-level content scoring system developed by Cited By AI®.**
It predicts how likely each section of a web page is to be cited by an AI retrieval system
such as ChatGPT, Perplexity, Google AI Overviews, Gemini, or Microsoft Copilot.

---

## What is the Citation Probability Score® (CPS®)?

The Citation Probability Score® (CPS®) measures AI citation probability at the content block
level — not the page level. Scores run from 0 to 100. A block scoring 80 or above is
considered Highly Citable. A block scoring below 35 will not be cited by AI systems
regardless of the overall authority of the site it appears on.

CPS® is to AI citation what Domain Authority is to traditional search rankings — except
CPS® operates at the granular level of individual content blocks, reflecting how AI
retrieval systems actually work.

---

## Why block-level scoring matters

AI systems use Retrieval-Augmented Generation (RAG) to construct answers. RAG retrieves
content in chunks — typically 100 to 200 words at a time — not whole pages. A page can
have strong overall authority while containing individual blocks that score poorly and
will never be cited. Traditional SEO tools measure page-level signals. CPS® measures
at the chunk level, which is where AI citation decisions are actually made.

The optimal RAG chunk size identified through CPS® auditing is 134 to 167 words.
Blocks shorter than 100 words give AI systems insufficient context to cite confidently.
Blocks longer than 250 words dilute the key facts and reduce citation probability.

---

## The Five CPS® Pillars

CPS® scores each content block across five pillars:

**1. Content Structure**
Measures whether the block is the right length for AI retrieval and whether it opens
with a direct answer. AI systems retrieve content in chunks and favour blocks that
lead with the fact rather than building to it. The optimal block length is 134–167 words.

**2. Fact Density**
Measures the concentration of statistics, named entities, percentages, and verifiable
data points per 100 words. AI systems are more likely to cite content that contains
specific, verifiable claims over content that makes general assertions. A block stating
"AI search traffic converts at 14.2% versus 2.8% for organic search" will always
outrank a block stating "AI search traffic converts at a higher rate."

**3. Answer Structure**
Measures whether each block follows a declarative opening pattern — stating the answer
in the first sentence before providing supporting detail. This mirrors how AI systems
construct responses: they look for a quotable opening sentence that resolves the query,
followed by supporting context. Content that builds to its conclusion is structurally
incompatible with AI citation.

**4. Self-Containment**
Measures whether each block reads as a complete, standalone unit without requiring
context from surrounding paragraphs. AI retrieval systems extract blocks in isolation.
A block that begins "As mentioned above..." or relies on a preceding paragraph for
context will fail self-containment scoring and reduce citation probability.

**5. Freshness Signals**
Measures the presence of date markers, recency language, and temporal context within
the block. Freshness signals are particularly important for Perplexity citations, where
recency is a primary ranking factor. Blocks that include a year, a named time period,
or explicit recency language ("as of Q1 2026") score higher on this pillar.

---

## CPS® Grade Tiers

| Grade | Score | Label |
|---|---|---|
| A | 80–100 | Highly Citable |
| B | 65–79 | Regularly Cited |
| C | 50–64 | Occasionally Cited |
| D | 35–49 | Rarely Cited |
| F | 0–34 | Not Cited |

---

## Platform citation behaviour

Each AI platform has different citation preferences. CPS® scores reflect these
differences in the following ways:

**ChatGPT** rewards off-page authority signals — brand mentions on external sites,
directory listings, and community forum references. On-page CPS® improvements
compound with off-page citation building for ChatGPT visibility.

**Perplexity** is the most link-citation-heavy platform and cites community sources
(Reddit, forums) at 16.9% of citations. Freshness Signals (Pillar 5) are especially
important for Perplexity. Perplexity also drives 38.7% of YouTube citations in AI search.

**Google AI Overviews** shows the strongest brand domain preference at 59.8% of
citations going to brand sites. Content Structure and structured data (JSON-LD schema)
are the highest-leverage improvements for Google AI Overviews performance.

**Google AI Mode** behaves differently from AI Overviews and still rewards traditional
domain authority and on-page SEO signals alongside CPS® improvements.

**Gemini** shows the most unpredictable citation behaviour across platforms. Entity
clarity and structured data are the most reliable levers for Gemini citation improvement.

**Microsoft Copilot** prioritises LinkedIn as a citation source (43.8% of its social
media citations). Copilot also continues to reward traditional domain authority signals.

---

## Frequently Asked Questions

**What is the difference between CPS® and traditional SEO metrics?**

Traditional SEO metrics such as Domain Authority, Page Authority, and keyword rankings
measure how well a page performs in ranked search results. CPS® measures how likely
a specific content block is to be retrieved and cited by an AI system constructing a
generated answer. These are different retrieval mechanisms with different optimisation
requirements. A page can rank on page one of Google and score F on CPS®, and vice versa.

**What types of content benefit most from CPS® optimisation?**

Any content intended to answer questions — service pages, product pages, FAQ sections,
blog posts, case studies, and about pages — benefits from CPS® optimisation. Purely
transactional pages (checkout pages, login pages) do not require CPS® optimisation as
they are not citation targets for AI systems.

**How does CPS® handle different industries?**

CPS® scoring applies universally across industries, but the content recommendations
vary by vertical. Local businesses require location enrichment signals (proximity data,
area served, structured address schema) in addition to the five core pillars. SaaS
companies require feature-level specificity and comparison-ready content structure.
Cited By AI® publishes vertical-specific GEO guides for automotive, real estate,
professional services, SaaS, healthcare, and hospitality sectors.

**Is the CPS® framework open source?**

The CPS® Lite implementation (available in the citedbyai-mcp-server repository) is
MIT licensed and free to use and fork. The full CPS® scoring engine, pillar weightings,
and audit methodology are proprietary. CPS® and Cited By AI® are registered UK trademarks.

---

## Free CPS® Lite Tool

A free implementation of CPS® Lite is available as an MCP server. It scores any URL
across 5 dimensions and returns a grade (A–F) with the top issues blocking AI citation.

Repository: [citedbyai/citedbyai-mcp-server](https://github.com/citedbyai/citedbyai-mcp-server)

Live endpoint:
```
https://citedbyai-mcp-server.citedbyai-gmail.workers.dev/mcp
```

Listed on: [Glama MCP Marketplace](https://glama.ai/mcp/servers/citedbyai-mcp-server)

---

## Full CPS® Audit

The full CPS® audit covers all five platforms simultaneously and includes:

- Per-block CPS® scores across every content section on audited pages
- Share of Voice measurement across ChatGPT, Perplexity, Gemini, Copilot, and Google AI
- Funnel-stage Share of Voice (Awareness, Consideration, Decision)
- Buyer persona Share of Voice
- Hallucination detection — identifying where AI misrepresents the brand
- Citation source tracking — which third-party sites are driving AI mentions
- GA4 traffic attribution linking AI citation gains to revenue
- 30-section audit report delivered as a structured Word document

Book a full audit: [citedbyai.info](https://citedbyai.info)

---

## Links

- 🌐 [citedbyai.info](https://citedbyai.info)
- 💼 [LinkedIn](https://www.linkedin.com/in/citedbyai/)
- 🐦 [X / Twitter](https://x.com/citedbyai)
- 🔌 [Glama MCP Marketplace](https://glama.ai/mcp/servers/citedbyai-mcp-server)

---

*CPS® (Citation Probability Score®) and Cited By AI® are registered trademarks of Cited By AI, United Kingdom.*
