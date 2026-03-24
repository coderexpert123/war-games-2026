# Neon Gas — Deep Resource Analysis

## Why This Matters
Neon is the buffer gas in excimer lasers used for DUV (deep ultraviolet) lithography — the workhorse process for manufacturing the vast majority of the world's semiconductors. Over 95% of the gas mix in ArF excimer lasers is neon. Unlike helium and bromine, neon supply is **not directly disrupted** by the Iran war. But neon is the third leg of a potential triple-constraint on chip fabrication: if helium (33% offline from Qatar strikes), bromine (65-70% at risk from Dead Sea proximity), and neon all tighten simultaneously, the semiconductor crisis becomes far worse than any single-resource model predicts.

## Disruption Scale: LOW (Direct) / MODERATE (Indirect via Triple Constraint)

Neon itself is not produced in the Iran/Gulf conflict zone in meaningful quantities. The risk is:
1. **Indirect energy cost pressure** on air separation units globally
2. **Supply chain still fragile** after post-Ukraine reshuffling — not yet stress-tested
3. **Compounding effect** with helium and bromine shortages already underway

---

## Global Production

Neon is a trace component of air (~18.2 ppm). It is extracted as a byproduct of cryogenic air separation units (ASUs), which are typically co-located with steel mills that need large volumes of oxygen for basic oxygen steelmaking. Only the largest ASUs include neon capture systems because the concentration is so low.

### Production Landscape (Pre-2022 vs. 2026)

| Source | Pre-2022 Share | 2026 Status | Notes |
|--------|---------------|-------------|-------|
| **Ukraine (Ingas, Cryoin)** | ~50% of global, near-monopoly on semiconductor-grade | **Largely offline / relocated** | Ingas (Mariupol) destroyed; Cryoin (Odesa) partially relocated to South Korea |
| **China** | ~30% crude, growing purification | **Largest producer, expanding** | Air Liquide opened new extraction plant (2M m3/yr) in 2023; multiple domestic expansions |
| **United States** | ~10% | **Expanding** | New ASU investments by Linde and Air Products |
| **South Korea (Cryoin Korea JV)** | 0% | **New entrant — online ~mid-2025** | JI Tech (51%) + Cryoin JV; produces semiconductor-grade Ne, Kr, Xe |
| **EU / Japan** | Minor | Stable | Some ASU byproduct capture |
| **Gulf States** | Negligible neon capture | Minimal | ASUs exist (Oman, Kuwait) for steel oxygen supply but rare-gas capture not standard |

**Total global production capacity**: ~45 million cubic meters/year (2023 estimate)
**Global market value**: ~$350-370M (2025)

### Key Structural Change Since 2022
The Ukraine crisis forced a geographic redistribution of neon supply. China has become the dominant producer, but questions remain about semiconductor-grade purity (impurities as low as 1 ppm can degrade lithography performance). Western fabs have diversified but the new supply network has never been tested under a simultaneous multi-resource crisis.

---

## Ukraine Neon: What Happened

### Pre-2022 Dominance
- **Ingas** (Mariupol): 15,000-20,000 m3/month; ~75% went to chip industry; customers in Taiwan, Korea, China, US, Germany
- **Cryoin** (Odesa): 10,000-15,000 m3/month
- Combined: supplied ~50% of global neon and nearly all ultra-high-purity semiconductor-grade neon imported by the US
- Legacy of Soviet steel industry — massive ASUs at Ukrainian steel mills produced crude neon; Ingas/Cryoin purified it to semiconductor grade (99.9999% purity)

### Destruction and Displacement
- **March 2022**: Both companies halted production when Russian invasion began
- **Ingas**: Mariupol plant destroyed during siege; partially resumed in another Ukrainian region (limited capacity)
- **Cryoin**: Odesa plant survived but operated intermittently; company accused of treason for relocating technology; launched **Cryoin Korea JV** with JI Tech (51% Korean ownership)
- **Cryoin Korea**: Construction began 2023, facility expected operational by mid-2024 to 2025; produces all rare gases (Ne, Kr, Xe) for semiconductor processes

### Recovery Assessment (March 2026)
Ukrainian neon production has not returned to pre-war levels and likely never will in its previous form. The production knowledge has partially migrated to South Korea. China has filled much of the crude volume gap but Western fabs remain cautious about semiconductor-grade Chinese neon due to purity concerns and geopolitical risk.

---

## Semiconductor Use: How Neon Powers Chip Manufacturing

### The Physics
DUV lithography uses excimer lasers to project circuit patterns onto silicon wafers:
- **ArF (Argon Fluoride) lasers**: 193nm wavelength — the dominant lithography tool for most chip nodes
- **KrF (Krypton Fluoride) lasers**: 248nm wavelength — older nodes, still widely used
- Gas charge composition: **~96-98% neon**, with small amounts of Ar/Kr and F2
- Neon serves as the **buffer gas** — its high ionization potential stabilizes the plasma discharge; its inert nature enables predictable, repeatable laser performance

### Consumption
- ~70% of global neon supply goes to semiconductor manufacturing
- Excimer lasers consume neon continuously during operation; gas charges must be periodically refreshed
- A large fab may consume thousands of cubic meters of neon annually
- Laser manufacturers (Cymer/ASML, Gigaphoton) have achieved **25-70% reduction** in neon consumption through software optimization and gas management improvements since 2022

### EUV vs. DUV: The Critical Distinction
| | DUV (193nm / 248nm) | EUV (13.5nm) |
|---|---|---|
| Light source | Excimer laser (ArF/KrF) | **Tin plasma** (CO2 laser vaporizes tin droplets) |
| Neon requirement | **Critical — 96%+ of gas mix** | **None — uses hydrogen ambient** |
| Current status | Workhorse for majority of production | Leading edge only (sub-7nm) |
| Installed base | Thousands of tools globally | ~200+ ASML EUV tools |

**Key insight**: The industry's migration toward EUV lithography structurally reduces neon dependency at the leading edge. However, DUV remains essential for the vast majority of semiconductor production (mature nodes, memory, analog, power chips, MEMS). Even advanced fabs use DUV for non-critical layers. **DUV is not going away — neon demand persists.**

---

## Recycling: The Game-Changer

Post-Ukraine, the semiconductor industry invested heavily in neon recycling. Since neon does not chemically decompose during laser operation, it can be captured, separated, purified, and reused.

| Company | Program | Recovery Rate | Savings | Status |
|---------|---------|--------------|---------|--------|
| **SK Hynix + TEMC** | Industry-first neon recycling (April 2024) | **72.7%** (target: 77%) | KRW 40B ($30M)/year | Operational |
| **Samsung** | World's first recycled neon in mass production | Not disclosed | Significant | Announced March 2024; deployment from 2025 |
| **EFC Gases** | Neon Gas Recycling System for fabs | High | 1M+ metric tons CO2 reduction per fab over 20 years | Commercial product (June 2024) |
| **TSMC** | Helium recovery systems (>70% of fabs); neon likely similar | Estimated 70-80% | Not disclosed | Operational |

### Impact on Supply-Demand Balance
- If major fabs achieve 70-80% neon recovery, **effective demand drops by roughly half**
- This is the single largest factor preventing a neon crisis in 2026
- Recycling has transformed neon from a consumable to a semi-recyclable input
- However: recycling systems require capital investment, retrofitting time (6-12 months), and operational expertise — not all fabs globally have them

---

## Price Trajectory

| Period | Price Trend | Driver |
|--------|------------|--------|
| Pre-2022 | Stable; ~$3-5/liter for semiconductor grade | Ukraine supplied abundantly |
| Q1-Q2 2022 | **Quadrupled** in China; surged globally | Ukraine production halted overnight |
| 2014 precedent | +60% after Crimea annexation | Showed market sensitivity to Ukraine supply |
| H2 2022 - 2023 | Gradual decline from peak | Chinese capacity expansion; inventory drawdowns; demand softened |
| Q4 2023 | Neon gas costs for wafer fab "started to decline" | New supply sources online; recycling adoption |
| 2024-2025 | **Normalized but elevated** vs. pre-2022 | Production costs +20% (IMF, 2023) due to energy prices; new supply geography established |
| **March 2026** | **Stable but watchful** | Not directly disrupted by Iran war; market ~$350-370M globally |

**Current assessment**: Neon prices have largely recovered from the 2022 spike. The market is in approximate balance, supported by Chinese capacity expansion, Korean JV production, recycling adoption, and laser efficiency improvements. However, the supply chain has not been stress-tested under the current multi-resource crisis conditions.

---

## Iran War Impact: Indirect but Real

### What's NOT Happening
- No major neon production in the Gulf conflict zone
- No direct supply disruption from Hormuz closure or Gulf strikes
- Neon supply chain is geographically distant from the war

### What IS Happening

**1. Energy Cost Pressure on Air Separation**
- ASUs are energy-intensive (electricity for cryogenic cooling)
- Gulf energy disruption → global energy price increase → higher ASU operating costs
- Particularly affects European ASUs already stressed by post-2022 energy prices
- Could marginally reduce neon output if steel mills curtail production due to energy costs

**2. The Triple Constraint on Semiconductors**
This is the real risk. Three independent semiconductor inputs are under simultaneous pressure:

| Input | Status (March 2026) | Fab Impact |
|-------|---------------------|------------|
| **Helium** | 33% global supply offline (Qatar Ras Laffan struck) | EUV stops without it; wafer cooling degraded |
| **Bromine** | 65-70% at risk (Dead Sea region in/near conflict) | PCB flame retardants; Samsung/SK Hynix 90% dependent on Israeli supply |
| **Neon** | Stable but fragile post-Ukraine supply chain | DUV lithography buffer gas; recycling provides buffer |

**If all three constrain simultaneously**: Chip production faces compounding bottlenecks across different process steps. Helium constrains EUV and cooling. Bromine constrains PCB production. Neon would constrain DUV lithography. No single recycling or substitution strategy addresses all three.

**3. Shipping and Insurance**
- Neon transport (compressed gas cylinders, cryogenic containers) relies on global shipping
- Insurance rates for Gulf-transit shipping have spiked (see `shipping-insurance.md`)
- Korean and Taiwanese fabs importing neon from China or new Korean JV are less affected
- European fabs importing from any source via disrupted routes face delivery risk

### Scenario: Neon Tightening (Low Probability, High Impact)
If a secondary shock hits neon supply — e.g., Chinese export controls on neon (as leverage, mirroring gallium/germanium restrictions), or major European steel mill closures due to energy crisis — the semiconductor industry loses its "safe" third input. Combined with helium and bromine stress, this could reduce global chip output by 30-50% within 6 months.

---

## Gulf ASU Infrastructure

Air separation units exist in Gulf states but are configured for oxygen/nitrogen supply to steel and industrial operations, not rare gas capture:

| Location | Operator | Capacity | Neon Capture |
|----------|----------|----------|-------------|
| Oman (Jindal Shadeed) | Air Products / SARGAS | 2.4M tonnes steel/yr; multiple ASUs | **No** — configured for O2/N2 |
| Kuwait (Shuaiba) | Shuaiba Oxygen | 1,500 tonnes/day O2 | **No** — steel/welding supply |
| Saudi Arabia | Various | Large steel sector | **Minimal** rare gas recovery |

**Assessment**: Gulf ASU infrastructure could theoretically be retrofitted for neon capture (12-18 month timeline), but this is not currently planned and would produce crude neon requiring purification elsewhere. Not a factor in this conflict's timeframe.

---

## China's Strategic Position

China's growing dominance in neon production mirrors its position in other critical minerals:

- **Capacity expansion**: Air Liquide's 2023 China plant added 2M m3/year; domestic producers expanding
- **Quality question**: Semiconductor-grade neon requires 99.9999% purity (6N). Chinese producers are improving but Western fabs have historically been cautious
- **Leverage potential**: China has already restricted gallium and germanium exports (see `gallium-germanium.md`). Neon could be added to export control lists as additional coercive leverage, particularly around the **November 2026** deadline
- **SMIC advantage**: Chinese fabs have preferential access to domestic neon supply, compounding their helium advantage (see `helium.md` — SMIC sourcing from multiple Chinese helium suppliers)

**Risk**: If China restricts neon exports, Western fabs lose the supply source that replaced Ukrainian production. Combined with helium and bromine constraints, this would be catastrophic for non-Chinese semiconductor manufacturing.

---

## Key Uncertainties

1. **Chinese neon quality**: Can Chinese 6N-grade neon fully substitute for former Ukrainian supply in the most demanding lithography applications? Unverified at scale.
2. **Recycling ceiling**: Current recovery rates of 70-77%. Can this reach 90%+? Unknown.
3. **Cryoin Korea JV**: Is it fully operational at target capacity by March 2026? Incomplete information.
4. **Chinese export control risk**: No current restrictions on neon, but the precedent exists (gallium/germanium). Probability unclear.
5. **Steel production trajectory**: If global steel demand drops (recession from war-driven economic disruption), ASU throughput drops, reducing neon byproduct volume — a perverse supply reduction during a demand-stable period.

---

## Comparison: Neon vs. Helium vs. Bromine

| Dimension | Neon | Helium | Bromine |
|-----------|------|--------|---------|
| Direct war disruption | **No** | **Yes** (33% offline) | **Yes** (65-70% at risk) |
| Recycling available | **Yes** (70-77%) | **Yes** (90-95% in best fabs) | **Limited** |
| Substitutes | None for DUV lithography | None for EUV/cooling | None for flame retardants |
| Supply diversification since 2022 | **Significant** (China, Korea) | **Limited** | **Minimal** |
| Current price stress | Low | **High** (doubled+) | Moderate |
| China leverage risk | **Yes** | Moderate | Low |
| Threat timeline | Latent / conditional | **Immediate** | Weeks to months |

---

## Bottom Line

Neon is the **least disrupted** of the three critical semiconductor gas/chemical inputs in the current conflict, but it is also the **least stress-tested** in its new post-Ukraine supply configuration. The real danger is not neon alone — it is the **combinatorial effect** of helium + bromine + neon constraining simultaneously. Recycling technology has bought significant breathing room, but the industry's neon security rests heavily on Chinese goodwill and continued supply, which is a strategic vulnerability that could be weaponized at any point during this conflict.

**Watch for**: Chinese neon export restrictions, European steel mill closures, and any disruption to the Cryoin Korea JV ramp-up.

---

## Sources
- USITC, "Ukraine, Neon, and Semiconductors" (2022)
- CNBC, "Chip industry under threat with neon production set to fall off a cliff" (March 2022)
- CNN, "Ukraine halts half of world's neon output for chips" (March 2022)
- The Register, "Chip world's major suppliers of neon gas shutter in Ukraine" (March 2022)
- NV Ukraine, "Neon manufacturer Cryoin Engineering accused of treason moves production to Korean" (2023)
- OpenPR / Cryoin Korea JV, "Scaling Global Rare Gas Production Beyond Ukraine" (2023)
- SK Hynix, "SK hynix teams up with local partners to develop pioneering neon gas recycling tech" (April 2024)
- KED Global, "SK Hynix, TEMC develop industry's first neon gas recycling technology" (April 2024)
- KED Global, "Samsung to use recycled neon gas in chip manufacturing" (March 2024)
- Semiconductor Digest, "The Growing Demand for Laser-Grade Gases in Semiconductor Manufacturing Process"
- ASML, "Light & lasers — Lithography principles"
- SPIE Photonics Focus, "Noble gases and the shock of war" (May/June 2023)
- IMARC Group, "Neon Gas Price Trend, Chart, Index, News and Forecast"
- Air Products, "Air Products and SARGAS announce agreement to build additional ASU at Jindal Shadeed" (March 2022)
- Air Liquide, "Air Liquide in Kuwait"
- Research Nester, "Neon Gas Market Size, Share & Trends Report 2035"
- Expert Market Research, "Neon Gas Market Size, Share & Industry Growth — 2034"
- Gasworld, "Industry's first neon gas recycling technology announced by SK Hynix, TEMC" (2024)
- Asianometry, "Neon Shortages in Semiconductor Manufacturing?" (2022)
- LogicFortress, "Neon Shortage Averted Amid Russia-Ukraine War"
