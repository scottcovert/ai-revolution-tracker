# AI Revolution Tracker

**A structured knowledge base tracking AI expert predictions, deployment evidence, and industry impacts with outcome validation.**

190 entries | 1,287 tracked claims | 1,062 key facts | 106 named experts | 15 claim categories

---

## Why This Exists

The AI revolution is generating thousands of predictions, claims, and projections daily. Most are:
- **Scattered** across interviews, podcasts, keynotes, and papers with no central tracking
- **Unverified** — bold predictions made in 2023 are forgotten by 2025
- **Context-free** — "AI will transform healthcare" means nothing without specifics
- **Hype-contaminated** — no distinction between evidence-backed claims and marketing

This database tracks **specific, attributable claims** from named experts with:
- What exactly was predicted
- Who said it and when
- What category it falls into
- What timeframe was given
- What actually happened (outcome tracking)

## What's Inside

### 1,287 Individual Claims Tracked

Each claim is extracted, categorized, and tracked:

```json
{
  "claim": "AI will automate 30% of current work hours by 2030",
  "category": "labor",
  "industries": ["all"],
  "timeframe": "2025-2030",
  "outcome": "pending",
  "outcomeDate": null,
  "outcomeNote": "McKinsey estimate; early indicators suggest pace is accelerating"
}
```

### Claim Categories

| Category | Claims | Description |
|----------|--------|-------------|
| Capability | 326 | What AI can or will be able to do |
| Economics | 186 | Market size, revenue, cost impacts |
| Adoption | 141 | Deployment rates, enterprise uptake |
| Labor | 117 | Job displacement, creation, transformation |
| Timeline | 82 | When milestones will be reached |
| Risk | 79 | Safety, alignment, existential concerns |
| Competition | 73 | Company/country positioning, market dynamics |
| Deployment | 70 | Real-world implementation evidence |
| Infrastructure | 57 | Data centers, compute, energy requirements |
| Investment | 45 | Funding flows, valuations, VC activity |
| Regulation | 43 | Policy, governance, legal frameworks |
| Scientific | 27 | Research breakthroughs, benchmarks |
| Energy | 20 | Power consumption, sustainability |
| Benchmark | 12 | Performance metrics, test results |
| Geopolitical | 9 | US-China dynamics, national strategy |

### 106 Named Experts Tracked

Including: Eric Schmidt, Dario Amodei, Demis Hassabis, Sam Altman, Jensen Huang, Geoffrey Hinton, Ray Kurzweil, Nick Bostrom, Francois Chollet, Yoshua Bengio, and 96 others.

Each expert's claims can be filtered and their prediction accuracy assessed over time.

## Data Sources

**190 entries** curated from 695 video summaries covering:
- Expert interviews and keynotes
- Industry analysis and deployment reports
- Economic impact assessments
- AI safety and alignment discussions
- Technology capability demonstrations
- Investment and market analysis

Sources span 2023-2026, with claims dated and attributed to specific experts.

## Schema

Each entry contains:

| Field | Type | Description |
|-------|------|-------------|
| `source` | string | Source title |
| `channel` | string | YouTube channel or publication |
| `expert` | string | Primary expert featured |
| `expertAngle` | string | Expert's known perspective/bias |
| `publishDate` | string | When the source was published |
| `url` | string | Source URL |
| `summary` | string | Overview of the source content |
| `claims` | object[] | Individual claims with category, timeframe, outcome |
| `keyFacts` | string[] | Verified facts and data points |
| `tags` | string[] | Searchable topic tags |

### Claim Object

| Field | Type | Description |
|-------|------|-------------|
| `claim` | string | The specific prediction or assertion |
| `category` | string | One of 15 categories (see above) |
| `industries` | string[] | Which industries are affected |
| `timeframe` | string | When the claim applies |
| `outcome` | string | pending, confirmed, partially-confirmed, wrong |
| `outcomeDate` | string | When outcome was determined |
| `outcomeNote` | string | Context on the outcome |

## Quick Start

The entire database is a single JSON file: [`ai-revolution-tracker.json`](ai-revolution-tracker.json)

### Load in Python
```python
import json

with open('ai-revolution-tracker.json') as f:
    db = json.load(f)

entries = db['entries']

# Get all claims by category
from collections import Counter
claims = [c for e in entries for c in e.get('claims', [])]
cats = Counter(c['category'] for c in claims)
for cat, count in cats.most_common():
    print(f"{cat}: {count} claims")
```

### Filter by Expert
```python
# What has Jensen Huang predicted?
huang_claims = []
for entry in entries:
    if 'Huang' in entry.get('expert', ''):
        huang_claims.extend(entry.get('claims', []))

for c in huang_claims:
    print(f"[{c['category']}] {c['claim']}")
    print(f"  Timeframe: {c.get('timeframe', 'unspecified')}")
    print(f"  Outcome: {c.get('outcome', 'pending')}")
```

### Track Prediction Accuracy
```python
# Which predictions have been confirmed vs wrong?
outcomes = Counter(c.get('outcome', 'pending') for c in claims)
for outcome, count in outcomes.most_common():
    print(f"{outcome}: {count}")
```

### Filter by Industry
```python
# What do experts predict for healthcare?
healthcare = [c for c in claims
              if any('health' in i.lower() for i in c.get('industries', []))]
print(f"{len(healthcare)} claims about healthcare AI")
```

## Use Cases

- **Investors**: Track which AI predictions are materializing and which are hype
- **Journalists**: Find specific, attributed expert claims with dates
- **Researchers**: Analyze prediction accuracy patterns across experts and categories
- **Developers**: Build prediction tracking dashboards or AI trend analysis tools
- **Educators**: Teach about technology forecasting with real data

## Stats at a Glance

- **190** source entries
- **1,287** individual tracked claims
- **1,062** verified key facts
- **106** named experts
- **15** claim categories
- **Sources span** 2023-2026

## Contributing

Found a claim that's been confirmed or proven wrong? Have an expert prediction to add? Open an issue or PR.

**Guidelines:**
- Claims must be specific and attributable (who said what, when)
- Include the source URL
- Use existing category taxonomy
- Track outcomes when verifiable

## License

This data is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to use, share, and adapt it for any purpose with attribution.

---

*Built with [VidBrainz](https://github.com/scottcovert) research intelligence. Data extracted and structured using AI from curated video sources.*
