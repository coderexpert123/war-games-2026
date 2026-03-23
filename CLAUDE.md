# Iran War 2026 Analysis — Project Brain

## What This Project Is
A comprehensive geopolitical and resource-level simulation of the 2026 Iran War (US/Israel vs Iran, started Feb 28 2026). Built from parallel research agents, resource-by-resource deep dives, and combinatorial cascade modeling.

---

## The Brain

### Intelligence Layers

Knowledge is organized bottom-up. Each layer cites the layer below it.

| Layer | Abstraction | Directory | Contents |
|-------|------------|-----------|----------|
| 1. Raw Data | Ground truth | `/resources/` | Production figures, prices, trade flows, stockpile levels. Each resource file is self-contained with sourced data points. |
| 2. Actor Analysis | First synthesis | `/countries/` | Per-country incentive maps: wants, fears, actions, paradoxes. Built from raw resource data + news reporting. |
| 3. Industry Impact | Domain synthesis | `/industries/` | How resource disruptions hit specific sectors (chips, AI, defense, food). Draws from multiple resource files. |
| 4. Cascade Modeling | Cross-domain synthesis | `/cascades/` | How disruptions compound across resources, industries, and countries simultaneously. The analytical core. |
| 5. Integrated Simulation | Prediction | `/simulation/` | Phase-by-phase predictions and scenarios. Built from all layers below. |
| 6. Gaps & Uncertainties | Meta-analysis | `/blind-spots/` | What we don't know, underweighted actors, wrong assumptions, unmodeled dynamics. |

**Citation chain**: Simulation cites cascades. Cascades cite industries + resources. Industries cite resources. Countries cite resources + news. Resources cite primary sources (news, think tanks, government data).

### Brain Files

These are navigational indexes. They help you find knowledge, not hold it. Each has a "when to consult" purpose.

| Brain File | When to Consult | Location |
|-----------|-----------------|----------|
| **Resource Index** | Starting any resource-level research; checking what's been covered vs gaps | `resources/00-resource-index.md` |
| **Country Index** | Starting any country analysis; checking actor coverage | `countries/00-country-index.md` |
| **Incentive Map** | Quick reference for any actor's wants/fears/position | `simulation/incentive-map.md` |
| **Combinatorial Matrix** | Understanding how a change in one resource cascades to others | `cascades/combinatorial-matrix.md` |
| **Blind Spots** | Before claiming simulation completeness; planning next research phase | `blind-spots/analysis.md` |
| **Master Simulation** | The current integrated prediction — the "answer" | `simulation/master-simulation.md` |
| **This file (CLAUDE.md)** | Orientation; how the brain works; conventions; priorities | You're here |

### Connections — Dependency Graph

```
resources/oil-gas.md ──────────┬──→ cascades/combinatorial-matrix.md ──→ simulation/master-simulation.md
resources/helium.md ───────────┤
resources/rare-earths.md ──────┤
resources/fertilizers.md ──────┤
resources/munitions.md ────────┤
resources/shipping-insurance.md┤
                               │
countries/united-states.md ────┤
countries/israel.md ───────────┤
countries/iran.md ─────────────┤
countries/china.md ────────────┤
countries/russia.md ───────────┤
countries/india.md ────────────┤
countries/european-union.md ───┤
countries/gulf-states.md ──────┘

industries/semiconductors-ai.md ──→ cascades/combinatorial-matrix.md
                                      │
                                      ├──→ simulation/master-simulation.md
                                      └──→ simulation/incentive-map.md

blind-spots/analysis.md ◄── (reads all files; identifies gaps)
```

**Cascade propagation rules:**
- A change to any `/resources/` file may invalidate `/cascades/` and `/simulation/`
- A change to any `/countries/` file may invalidate `/simulation/incentive-map.md`
- New data should propagate: raw data → resource file → affected cascades → simulation update
- **Follow the dominoes**: when you update one file, trace all downstream effects in a single pass

---

## Working Principles

### Research Methodology
- Deploy parallel sub-agents per resource or country for maximum depth
- All claims must be sourced with publication name and date
- Distinguish verified facts from reasonable inferences from speculation
- Update simulation as new data becomes available
- When updating, follow the dominoes: resource → cascade → simulation

### Conventions
- Dates in ISO format or "Month Day, Year"
- All prices in USD unless noted
- Oil production in barrels per day (bpd)
- Minerals in metric tonnes
- Gas in million tonnes per annum (mtpa) for LNG, billion cubic meters (bcm) for pipeline
- Sources at bottom of each file with publication name and date

### When Adding New Content
1. Determine which intelligence layer it belongs to
2. Create or update the appropriate file
3. Update the relevant brain file (index)
4. Trace downstream: does this change any cascade? Does it change the simulation?
5. If it reveals a gap, add to `blind-spots/analysis.md`
6. Log the change below

---

## Priority Research Gaps

From `blind-spots/analysis.md` — work through these systematically:

1. **Underweighted actors**: Pakistan, North Korea, Japan, South Korea — nuclear dimensions
2. **Cyber warfare**: Escalation scenarios in both directions
3. **Water crisis**: Desalination attacks could be defining humanitarian disaster
4. **Pharmaceutical supply chains**: Completely unresearched
5. **November 2026 convergence**: Midterms + Chinese leverage + winter energy crunch
6. **Insurance systemic risk**: If Lloyd's cracks, global trade freezes
7. **Migration cascade**: 10M+ Gulf workers returning; $125B remittance collapse
8. **Polyethylene downstream**: Food packaging shortage compounds food crisis

---

## Change Log

| Date | Change | Files Affected | Why |
|------|--------|---------------|-----|
| 2026-03-23 | Initial brain creation | All 23 files | First comprehensive build from conversation research |
| 2026-03-23 | Full brain architecture | CLAUDE.md | Intelligence layers, brain files, connections, propagation rules |
| 2026-03-23 | Gap fill: conversation content captured | 9 new files | War overview, wild cards, supply exhaustion, Russia/China incentives, bromine, sulphur, gallium-germanium, defense industrial base, food agriculture |
| 2026-03-23 | Scenarios & opportunities document | scenarios-and-opportunities.md | 5 probability-weighted scenarios, structural shifts, 4-tier opportunity framework, key dates calendar |
| | | | |

---

## File Inventory (23 files)

### Root
- `README.md` — Public-facing project description
- `CLAUDE.md` — This file. Brain architecture and project instructions.

### `/resources/` (10 files)
- `00-resource-index.md` — Brain file: resource coverage index
- `oil-gas.md` — Oil & natural gas: 20M bpd disruption, prices, pipelines, LNG, reserves
- `helium.md` — 33% global supply offline; semiconductor fabrication dependency
- `rare-earths.md` — Chinese dominance; weapons dependency; gallium/germanium Nov 2026 deadline
- `fertilizers.md` — 1/3 of global trade via Hormuz; food crisis locked in
- `munitions.md` — 5,197 in 96 hours; cost asymmetry; production bottlenecks
- `shipping-insurance.md` — 92% traffic collapse; insurance as weapon; mine warfare

### `/countries/` (9 files)
- `00-country-index.md` — Brain file: actor coverage index
- `united-states.md` — Domestic politics, military sustainability, exit strategy
- `israel.md` — Two-front war, 93% support, strategic goals
- `iran.md` — Post-Khamenei leadership, asymmetric tools, internal fragility
- `china.md` — Resource dominance, mediation, SMIC advantage, Nov 2026 leverage
- `russia.md` — Oil windfall, Ukraine exploitation, intelligence sharing
- `india.md` — Energy vulnerability, diaspora risk, zero leverage
- `european-union.md` — Second energy crisis, divided response, autonomy failure
- `gulf-states.md` — Saudi, UAE, Qatar, Bahrain, Iraq, Turkey, Egypt, Jordan

### `/industries/` (3 files)
- `semiconductors-ai.md` — Triple input crisis, memory prices, TSMC vulnerability, data center attacks
- `defense-industrial-base.md` — Munitions burn rate, production ramp, single-point failures, Ukraine competition
- `food-agriculture.md` — Fertilizer shortage, crop yield timeline, water desalination, 1B+ at risk

### `/cascades/` (1 file)
- `combinatorial-matrix.md` — Brain file: 5 major cascade models, meta-cascade (China)

### `/simulation/` (7 files)
- `master-simulation.md` — Brain file: 4-phase prediction model, winners/losers
- `incentive-map.md` — Brain file: every actor's wants/fears/actions
- `war-overview.md` — Timeline of key events, day-by-day from Feb 25 to March 23
- `iran-wild-cards.md` — 7 creative asymmetric scenarios Iran could pursue
- `supply-exhaustion-analysis.md` — Can US/Israel deplete Iran's military? Analysis of conventional vs asymmetric
- `russia-china-incentives.md` — Deep analysis of what Russia and China actually want from this war
- `scenarios-and-opportunities.md` — **Brain file**: 5 scenarios with probabilities, structural shifts, economic opportunities matrix, key dates

### `/blind-spots/` (1 file)
- `analysis.md` — Brain file: 6 categories of unmodeled risks

---

## Missing Files (To Be Created)

### `/resources/` — Indexed but not yet written
- `lithium.md`, `cobalt.md`, `copper.md`, `titanium.md`, `uranium.md`, `neon.md`, `polyethylene.md`

### `/industries/` — Referenced but not yet written
- `automotive.md`
- `energy-transition.md`

### `/countries/` — Identified as gaps
- `pakistan.md`, `north-korea.md`, `japan.md`, `south-korea.md`

### `/cascades/` — Potential additions
- `november-2026-convergence.md`
- `cyber-escalation-scenarios.md`
- `water-crisis-model.md`
