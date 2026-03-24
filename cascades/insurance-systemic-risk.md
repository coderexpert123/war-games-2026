# Insurance Systemic Risk — Cascade Analysis

**Date**: March 24, 2026 (Day 24 of conflict)
**Status**: ACTIVE CRISIS — Market capacity contracting, government backstop deployed, contagion vectors open

---

## Executive Summary

The 2026 Iran War has triggered the most severe marine insurance crisis since the 1980s Tanker War, and potentially the worst systemic stress on Lloyd's of London since the Names crisis of the early 1990s. War risk premiums have spiked +3,000%, P&I clubs have issued cancellation notices across the Gulf, and ~$25 billion in vessel hull value sits in the war zone. But the real systemic risk is not the direct losses — it is the withdrawal of underwriting capacity. Every dollar of marine insurance supports roughly $100-200 of trade. If capacity contracts by $10 billion, $1-2 trillion of trade becomes uninsurable. The U.S. government has already deployed a $20 billion DFC/Chubb reinsurance facility — an unprecedented wartime intervention that simultaneously reveals how serious the gap is and creates new moral hazard.

---

## Current State Assessment

### The War Risk Market Before and After February 28

| Metric | Pre-War (Feb 27) | Current (Mar 24) | Change |
|--------|------------------|-------------------|--------|
| War risk premium (% of hull value) | 0.15-0.25% | 2.5-7.5% | +1,500-3,000% |
| VLCC ($100M) per-voyage premium | ~$200K | ~$1M-7.5M | +5x to +37x |
| LNG carrier ($150M) per-voyage | ~$375K | ~$1.5M+ | +4x |
| Hormuz daily crossings | 100-135 | ~2/day | -92% |
| Vessels damaged/sunk | 0 | ~20 damaged, multiple sunk | Active war zone |
| Seafarer deaths | 0 | 6+ confirmed | Rising |
| Vessels stranded in Gulf | 0 | ~150 | ~$25B hull value trapped |
| P&I club Gulf coverage | Active | Cancelled (all 12 IG clubs) | Binary withdrawal |
| Global war risk premium pool | ~$1B/year | Repricing in real-time | Potentially $5-10B annualized |

**Source**: Lloyd's List, S&P Global, CNBC, Al Jazeera, Insurance Journal — March 2026

### What Has Actually Been Lost

As of Day 24, confirmed losses include:
- **Honduran-flagged Nova**: burning in Strait after two IRGC drone strikes
- **Stena Imperative** (US-flagged): damaged by aerial impacts while berthed
- **Safeen Prestige tugboat**: struck by two missiles, sank; 3 crew missing
- **~20 vessels total**: damaged by mines, missiles, or drone strikes
- **6+ seafarer deaths confirmed**
- **150 vessels stranded**: hull value ~$25 billion, generating holding costs but not revenue

Estimated insured losses to date: $2-5 billion (hull damage, cargo, business interruption, crew). This is already a large loss year for the marine war risk market, which collected only ~$1 billion in premiums globally in 2025.

---

## The Insurance Architecture — How It Breaks

### Lloyd's Chain of Security

Lloyd's operates a three-tier capital structure designed to prevent systemic contagion:

```
TIER 1: Syndicate Premiums Trust Funds (PTFs)
        £92.5 billion in syndicate-level assets
        ↓ If exhausted...
TIER 2: Members' Funds at Lloyd's (FAL)
        £31.1 billion — posted by capital providers
        ↓ If exhausted...
TIER 3: Central Fund (mutual)
        £2.9 billion — shared safety net
        ↓ If exhausted...
        Lloyd's must call on members for additional capital
        or seek external support
```

**Total Lloyd's market resources**: ~£126 billion ($160 billion)
**2026 forecast gross premium income**: ~£66 billion ($84 billion)

The chain of security means a single syndicate failure does not cascade — the Central Fund mutualizes the loss. But the chain was designed for one-off catastrophes, not a sustained war that generates ongoing, correlated losses across multiple syndicates simultaneously.

### The Solvency Capital Requirement (SCR)

Each syndicate must hold capital at 99.5% confidence level, plus a 35% uplift imposed by Lloyd's. This means syndicates are capitalized to survive a 1-in-200 year event. The question is: does a multi-month Gulf war that simultaneously disrupts 20% of global oil trade, strands $25 billion in vessels, and triggers correlated losses across hull, cargo, P&I, political violence, aviation, and cyber lines — does that exceed the 1-in-200 threshold? For war risk specialists, almost certainly yes.

### P&I Clubs — The Overlooked Vulnerability

The 12 clubs of the International Group of P&I Clubs represent:
- **Free reserves**: $5.96 billion (rose 4.81% in 2025)
- **Coverage**: ~90% of global ocean-going tonnage
- **2024/25 underwriting loss**: $312 million (reversing two surplus years)
- **Net claims in 2024/25**: $3.1 billion (up 25% YoY, 16% above 5-year average)

All 12 IG clubs issued 72-hour cancellation notices for Gulf war cover. The cancellations are technically limited to "charterers' liability risk extensions," with "buyback" replacement products being negotiated. But this is a distinction that matters to lawyers, not to ship operators trying to decide whether to transit Hormuz.

**The P&I stress scenario**: If even 5 of the ~150 stranded vessels become constructive total losses ($200-300M each), that is $1-1.5 billion in hull claims alone — before crew injury, pollution liability, wreck removal, and cargo losses. P&I reserves of $5.96 billion sound large until you realize the clubs were already running a $312 million underwriting loss before the war started.

### The Reinsurance Chain

Who reinsures the war risk underwriters?

```
Primary layer:    Lloyd's syndicates, marine specialists
                         ↓ cede to
Treaty reinsurance: Swiss Re, Munich Re, Hannover Re,
                    Berkshire Hathaway, SCOR
                         ↓ cede to
Retrocession:     ILS funds, catastrophe bonds,
                  sidecars, collateralized reinsurers
                         ↓ ultimate risk sits with
Capital markets:  Pension funds, sovereign wealth funds,
                  hedge funds
```

**Top 5 reinsurers control ~30% of global reinsurance market** (Swiss Re #1, Munich Re #2, Hannover Re #3, Berkshire Hathaway #4).

The critical question: reinsurance treaties typically contain **war exclusion clauses**. If losses are classified as "war" rather than "terrorism" or "civil commotion," reinsurers may deny coverage, leaving primary underwriters holding the full loss. This is precisely the scenario now unfolding — there is no ambiguity about whether this is a war. The classification question that plagued Ukraine/Russia Black Sea claims does not apply here.

**Implication**: Primary war risk syndicates may be operating with far less reinsurance protection than their balance sheets suggest. The reinsurance "net" may have holes in exactly the scenario where it is needed most.

---

## Contagion Map — How Insurance Failure Propagates

### Scenario: A Major War Risk Syndicate Fails

```
TRIGGER: Cumulative Gulf losses exceed syndicate capital
              │
              ▼
   ┌─────────────────────┐
   │ SYNDICATE FAILURE    │
   │ (war risk specialist)│
   └──────┬──────────────┘
          │
    ┌─────┴──────────────────────────────────────────┐
    │                                                 │
    ▼                                                 ▼
┌──────────────┐                          ┌──────────────────┐
│ LLOYD'S      │                          │ CAPACITY          │
│ CENTRAL FUND │                          │ WITHDRAWAL        │
│ absorbs loss │                          │ Other syndicates  │
│ (£2.9B pool) │                          │ reduce war risk   │
└──────┬───────┘                          │ appetite          │
       │                                  └────────┬─────────┘
       │                                           │
       ▼                                           ▼
┌──────────────┐                     ┌────────────────────────┐
│ RATING AGENCY│                     │ PREMIUM SPIRAL          │
│ REVIEW       │                     │ Remaining capacity      │
│ (AM Best,    │                     │ reprices ALL marine war │
│  S&P, Fitch) │                     │ risk — not just Gulf    │
└──────┬───────┘                     └────────┬───────────────┘
       │                                      │
       ▼                                      ▼
┌──────────────┐                     ┌────────────────────────┐
│ LLOYD'S      │                     │ BLACK SEA / RED SEA /   │
│ DOWNGRADE    │                     │ SOUTH CHINA SEA         │
│ (currently   │                     │ premiums spike in       │
│  AA-/A+)     │                     │ sympathy — contagion    │
└──────┬───────┘                     │ to ALL war zones        │
       │                             └────────┬───────────────┘
       ▼                                      │
┌──────────────┐                              ▼
│ BROAD MARKET │                     ┌────────────────────────┐
│ CONFIDENCE   │                     │ TRADE FREEZE            │
│ CRISIS       │◄────────────────────│ Vessels cannot sail     │
│              │                     │ without insurance.      │
└──────────────┘                     │ Global trade contracts. │
                                     └────────────────────────┘
```

### Scenario: Beyond Marine — Multi-Line Contagion

The Iran War is generating correlated losses across insurance lines that are normally independent:

```
IRAN WAR
   │
   ├──→ MARINE WAR RISK: Hull, cargo, freight ($2-5B losses and rising)
   │
   ├──→ AVIATION WAR RISK: Airlines rerouting, premiums +10%+
   │         Middle East routes: significantly higher increases
   │         60+ threat groups active (Palo Alto Unit 42)
   │
   ├──→ POLITICAL VIOLENCE: Forced abandonment claims as
   │         Western firms evacuate Gulf operations
   │         Terrorism & PV market capacity: >$2B standalone
   │
   ├──→ CYBER INSURANCE: Amazon data centers in UAE/Bahrain
   │         hit by IRGC drones. War exclusion clauses
   │         triggered? Cyber market in coverage crisis.
   │
   ├──→ TRADE CREDIT: Manufacturing delays → payment defaults
   │         → cascading credit losses across supply chains
   │
   ├──→ BUSINESS INTERRUPTION: Gulf port shutdowns (Jebel Ali),
   │         factory closures, supply chain disruption
   │
   ├──→ ENERGY: Offshore platforms, pipelines, refineries
   │         in expanded war zone. Ras Laffan strike = $B claim.
   │
   └──→ INFRASTRUCTURE / PROPERTY: Desalination plants struck.
            Water infrastructure = humanitarian + insurance crisis.
```

**The correlation problem**: Insurance pricing models assume these lines are largely independent. A hurricane hits marine and property but not cyber and aviation. A pandemic hits BI and life but not marine and energy. This war hits ALL of them simultaneously. When losses are correlated across lines, the diversification benefit that underpins reinsurer solvency models evaporates.

---

## The $20 Billion Government Backstop

### What the DFC/Chubb Facility Is

On March 7, the U.S. International Development Finance Corporation (DFC) announced a $20 billion maritime reinsurance facility. On March 11, Chubb was named lead underwriter. On March 20-23, the structure was detailed:

- **Coverage**: War hull risk, war P&I, war cargo insurance
- **Scope**: Vessels transiting Strait of Hormuz, under certain conditions
- **Structure**: Public-private partnership — DFC provides reinsurance backing, Chubb underwrites, prices, issues policies, and manages claims
- **Capacity**: Up to $20 billion on a rolling basis
- **Other participants**: "Name-brand American insurance companies" as co-reinsurers

### What It Reveals

The mere existence of this facility tells you several things:

1. **The private market cannot handle this risk alone.** If it could, the government would not need to intervene. The $20B facility is larger than the entire annual global marine war risk premium pool by an order of magnitude.

2. **The U.S. needs Hormuz open for strategic reasons.** This is not charity — it is a wartime economic weapon. The insurance facility is the economic complement to naval operations.

3. **Moral hazard is embedded.** If the government backstops war risk, underwriters have less incentive to price risk accurately. Vessels may transit when the risk does not justify it. Losses may be socialized.

4. **It may not be enough.** The facility was initially criticized for lacking liability cover, which was only added on March 20-23. If losses exceed $20B — plausible if multiple VLCCs are sunk or a major LNG carrier is destroyed — the facility exhausts and we are back to the private market gap.

### Historical Precedent for Government Backstops

| Program | Country | Risk | Capacity | Funded By |
|---------|---------|------|----------|-----------|
| Pool Re | UK | Terrorism | £6.9B reserves + £2.5B reinsurance + unlimited HM Treasury guarantee | Industry premiums (50% to Treasury) |
| TRIA | US | Terrorism | Treasury reimburses 80% above deductible; program authorized through 2027 | Industry deductibles + taxpayer |
| DFC Gulf Facility | US | Marine war risk | $20B rolling | Taxpayer via DFC + Chubb premiums |
| Equitas (1996) | UK | Lloyd's legacy liabilities | £3.2B debt written off | Lloyd's members + reserves |

**Notable gap**: Neither Pool Re nor TRIA covers war risk — only terrorism. The DFC facility is an improvised wartime measure with no statutory authorization comparable to TRIA. If it generates large losses, Congressional authorization may be needed to continue.

---

## Historical Comparison

### Three Precedents for Today

| Factor | Tanker War (1980-88) | Lloyd's Names Crisis (1988-92) | Black Sea / Ukraine (2022-25) | Gulf War 2026 |
|--------|---------------------|-------------------------------|------------------------------|---------------|
| **Duration** | 8 years | 4 years of losses | 3+ years ongoing | 24 days (and counting) |
| **Vessels attacked** | 451 | N/A | Dozens | ~20 (Day 24) |
| **Ships sunk/CTL** | 55 tankers + others | N/A | Several | Multiple (rising) |
| **Seamen killed** | 400+ | N/A | Several | 6+ |
| **Premium spike** | +300% (initial) | N/A | +250% (Black Sea) to 10% of hull value | +1,500-3,000% |
| **Traffic impact** | Never fully stopped | N/A | Reduced but continued | -92% (near-total halt) |
| **Market losses** | Absorbed over 8 years | £9B ($26B adj.) over 4 years | War risk market profitable 2022 (62% profit margin) | $2-5B in 24 days; trajectory unsustainable |
| **Systemic impact** | High premiums but market adapted | Near-collapse; Equitas bailout; 1,500+ bankruptcies; 15+ suicides | Manageable — losses spread over time | UNKNOWN — loss velocity unprecedented |
| **Government intervention** | US Navy escort (Op Earnest Will) | Reconstruction of Lloyd's governance | None needed | $20B DFC/Chubb facility on Day 7 |

**Key difference from the Tanker War**: In the 1980s, attacks were spread over 8 years and the market adapted. Iran even lowered oil prices to offset insurance costs. In 2026, the loss velocity is orders of magnitude higher — $2-5 billion in 24 days vs. hundreds of millions over years. The market has not had time to adapt.

**Key difference from the Names Crisis**: The 1990s crisis was driven by long-tail asbestos/pollution liabilities and the LMX reinsurance spiral — slow-moving, structural problems. The 2026 crisis is acute and kinetic. But the structural vulnerability is similar: concentrated exposure in specialized syndicates, with potential for losses to exceed capital.

---

## Escalation Scenarios

### Scenario 1: Contained (Probability: 30%)

War ends or de-escalates within 60 days. Losses remain at $5-10 billion total. Lloyd's Central Fund absorbs syndicate failures if any. Premium normalization takes 6-12 months. DFC facility winds down. Market recovers.

**Insurance impact**: Significant but manageable. War risk premiums remain elevated for 1-2 years. Some specialist syndicates exit the line. Capacity contracts 20-30% but trade continues.

### Scenario 2: Prolonged Attrition (Probability: 40%)

War continues 3-6 months. Monthly losses of $1-3 billion. Total insured losses: $10-30 billion. Multiple syndicate failures. Lloyd's Central Fund drawn down. Rating agencies review Lloyd's rating. P&I club reserves depleted by 30-50%. DFC facility strained.

**Insurance impact**: Severe. War risk capacity contracts 50%+. Contagion to Black Sea and South China Sea pricing. Global marine insurance premiums rise 20-40% across all lines. Trade credit defaults spike. Some trade routes become uninsurable without government backstop.

### Scenario 3: Catastrophic Escalation (Probability: 20%)

Major vessel sinking (VLCC or LNG carrier = $150-300M single loss). Multiple vessels mined simultaneously. Cumulative losses exceed $30 billion. Lloyd's rating downgraded. Central Fund exhausted. P&I clubs issue cash calls on members. Reinsurers invoke war exclusions en masse.

**Insurance impact**: Systemic crisis. Underwriting capacity for ALL marine war risk — not just Gulf — collapses. The insurance gap spreads from Hormuz to global routes as underwriters reassess exposure models. Government backstops become the only game in town. Global trade contracts 5-15% as uninsurable cargo sits in port.

### Scenario 4: Black Swan — Insurance Market Failure (Probability: 10%)

Combination of: (a) Gulf losses exceed $50B, (b) simultaneous cyber attack on financial infrastructure disrupts claims processing, (c) reinsurance market freezes as war exclusions are tested in court, (d) Lloyd's requires emergency recapitalization. A modern analog of the Names crisis, compressed into months instead of years.

**Insurance impact**: Existential. The global insurance architecture — built over 300 years — proves inadequate for a 21st-century great-power conflict. Governments must step in as insurers of last resort across multiple lines. The precedent permanently changes the relationship between state and market in risk transfer.

---

## The Multiplier Effect — Insurance and the Real Economy

### How Much Trade Rests on Insurance?

Global marine insurance premiums: ~$36 billion/year (2025).
Global seaborne trade value: ~$14 trillion/year.

**Implied multiplier: Every $1 of marine insurance premium supports ~$390 of trade.**

This multiplier is not theoretical — it is mechanical. A vessel cannot legally sail without hull insurance. A cargo cannot be financed without cargo insurance. A letter of credit requires insurance documentation. Remove the insurance, and the entire trade finance chain breaks.

### The Capacity Withdrawal Cascade

```
Insurance capacity withdraws from Gulf
              │
              ▼
    Vessels cannot transit Hormuz
    (even those willing to accept risk)
              │
              ▼
    Oil/LNG/cargo reroutes or stops
              │
              ├──→ Oil price spike (+$30-50/bbl sustained)
              ├──→ LNG spot price spike (+300-500%)
              ├──→ Container rates spike (+$1,500-3,500/TEU)
              └──→ Port congestion at alternative routes
              │
              ▼
    Reinsurers reassess ALL war zone exposure
              │
              ├──→ Black Sea premiums spike (Ukraine trade)
              ├──→ Red Sea premiums spike (Houthi residual risk)
              ├──→ South China Sea premiums spike (Taiwan contingency)
              └──→ West Africa premiums spike (piracy recalibration)
              │
              ▼
    Global underwriting capacity contracts
              │
              ▼
    Trade that has NOTHING to do with Iran
    becomes more expensive or uninsurable
              │
              ▼
    Global GDP impact: -0.5% to -2.0%
    (depending on duration and severity)
```

### The Cyber Insurance Wild Card

Iran's IRGC struck Amazon Web Services data centers in UAE and Bahrain with drones on March 1. This is the first military strike on hyperscale cloud infrastructure in history. The implications for cyber insurance are profound:

- **War exclusion activation**: Most cyber policies exclude losses arising from war. If Iranian cyber attacks on Western infrastructure are classified as acts of war (they are), cyber insurers may deny claims across the board. Lloyd's already issued guidance in 2023 requiring war exclusions in cyber policies.
- **Correlation shock**: The same conflict generating marine losses is generating cyber losses. Reinsurers who thought marine and cyber were independent risks now face correlated claims.
- **Cloud concentration risk**: AWS, Azure, and Google Cloud host critical infrastructure for banks, hospitals, logistics firms. A sustained Iranian cyber campaign against cloud infrastructure would generate claims that dwarf the marine losses.

**Estimated global cyber insurance premium pool**: ~$15-20 billion (2025). If war exclusions are invoked and litigated, the cyber insurance market could enter a coverage crisis reminiscent of 2001 (when terrorism exclusions were imposed post-9/11).

---

## What Would a Government "Insurer of Last Resort" Look Like?

The DFC/Chubb $20B facility is an improvised first step. If the crisis deepens, governments will face pressure to create broader backstops:

### Requirements for an Effective Wartime Insurance Backstop

1. **Scope**: Must cover hull, cargo, P&I, and liability — not just hull (initial DFC facility gap, since corrected)
2. **Capacity**: Must exceed plausible loss scenarios. $20B may not be enough for a 6-month war.
3. **Pricing**: Must be expensive enough to discourage unnecessary risk-taking (moral hazard) but cheap enough to keep trade flowing
4. **Claims speed**: Military conflicts generate claims daily. Processing must be faster than peacetime.
5. **International coordination**: A US-only facility creates competitive distortion. Chinese-flagged vessels transiting with PICC coverage operate under different risk calculus.

### The China Asymmetry

Chinese-flagged vessels are transiting Hormuz more freely, insured by state-backed PICC (People's Insurance Company of China). This is not a market-based insurance decision — it is a strategic one. China's state insurance capacity is functionally unlimited because the Chinese government can absorb any loss. Western insurers cannot compete with a state that treats insurance as a tool of geopolitical influence rather than a business.

This asymmetry means that even if the Western insurance market cracks, Chinese trade through Hormuz may continue — reinforcing China's position as the winner of the conflict's economic dimension (see `simulation/russia-china-incentives.md`).

---

## Key Uncertainties

1. **Loss trajectory**: Are we at the beginning or the peak? If Iran deploys its remaining 4,000-5,000 mines, losses could increase by an order of magnitude.
2. **War exclusion litigation**: Will courts uphold war exclusions in cyber and political violence policies? Litigation will take years, but market behavior changes immediately based on expectations.
3. **DFC facility adequacy**: Can the $20B facility handle sustained losses? What happens politically if taxpayer money flows to cover vessel losses?
4. **Reinsurance market response at renewal**: Treaty renewals (January 2027) will be the first opportunity for reinsurers to reprice or exit war risk. The Jan 2027 renewal could be a second crisis point.
5. **Contagion to sovereign credit**: If Gulf states' infrastructure (desalination, ports, oil facilities) sustains heavy damage, sovereign risk reprices, affecting all insurance and lending in the region.
6. **Shadow fleet expansion**: As insured vessels withdraw, uninsured or fraudulently insured vessels fill the gap. This transfers risk from the insurance market to the environment (pollution), crews (safety), and port states (liability).

---

## Connections to Other Analyses

- **Shipping & Insurance** (`resources/shipping-insurance.md`): Raw data on traffic collapse, premium spikes, P&I cancellations
- **Oil & Gas** (`resources/oil-gas.md`): 20M bpd disruption; uninsured tankers = unfinanced oil
- **Semiconductors/AI** (`industries/semiconductors-ai.md`): Data center strikes → cyber insurance crisis → cloud infrastructure risk repricing
- **Combinatorial Matrix** (`cascades/combinatorial-matrix.md`): Insurance failure amplifies every other cascade
- **China Analysis** (`countries/china.md`): PICC state-backed insurance as strategic advantage
- **Scenarios & Opportunities** (`simulation/scenarios-and-opportunities.md`): Insurance market stress as structural shift indicator

---

## Bottom Line

The insurance market is not a passive observer of this war — it is a combatant. Insurance withdrawal has done more to halt Hormuz traffic than any Iranian mine or missile. The 92% traffic collapse is primarily an insurance event, not a military one. Ships that could physically transit choose not to because they cannot obtain coverage.

The systemic risk is that this dynamic spreads beyond the Gulf. If war risk specialists fail, if the Central Fund is drawn down, if rating agencies downgrade Lloyd's, the contagion reaches every insured trade route on Earth. The $20 billion DFC/Chubb facility is a tourniquet, not a cure. And the simultaneous stress on cyber, aviation, political violence, and trade credit insurance means the war is testing the entire global risk transfer architecture — not just one line of business.

The last time Lloyd's faced losses of this magnitude and velocity, it nearly ceased to exist. The chain of security is stronger now than in the 1990s (£126 billion vs. far less then), but the losses are also arriving faster and across more correlated lines than anything the market has faced before.

---

## Sources

- Lloyd's of London, "Capital Structure" and "Full Year Results 2025" — lloyds.com, 2025-2026
- Lloyd's of London, "Capital Guidance — April 2025" — assets.lloyds.com, April 2025
- S&P Global, "Marine war insurance for Hormuz dries up as Middle East war intensifies" — spglobal.com, March 2026
- Al Jazeera, "Maritime insurers cancel war risk cover in Gulf" — aljazeera.com, March 3, 2026
- CNBC, "Oil supertanker rates soar as insurers drop war risk protection" — cnbc.com, March 3, 2026
- Insurance Journal, "Chubb Outlines Structure of $20B Gulf Reinsurance Facility" — insurancejournal.com, March 23, 2026
- DFC, "DFC Announces $20B Plan for Maritime Reinsurance in the Gulf" — dfc.gov, March 2026
- CNBC, "Chubb set as main U.S. insurer for Persian Gulf shipping amid Iran war" — cnbc.com, March 11, 2026
- Insurance Business Magazine, "Gulf conflict strands 20,000 seafarers — and tests marine insurance limits" — insurancebusinessmag.com, March 2026
- Lloyd's List, "No, P&I clubs have not 'cancelled war risk cover'" — lloydslist.com, March 2026
- Lloyd's List, "How a prolonged Gulf conflict could squeeze P&I clubs" — lloydslist.com, March 2026
- Lockton, "Marine P&I clubs face decade-high claims and sustained pressure" — lockton.com, 2025
- Kennedys Law, "Iran War triggers a reshaped marine insurance risk landscape" — kennedyslaw.com, March 2026
- Kennedys Law, "Aviation war-risk insurance and the Iran conflict" — kennedyslaw.com, March 2026
- Kennedys Law, "Iran's cyber warfare: legal implications for businesses" — kennedyslaw.com, March 2026
- Insurance Journal, "Iran War Could Raise Exposures for Global Terrorism, Political Violence Underwriters" — insurancejournal.com, March 18, 2026
- Insurance Journal, "Insurance Gaps Leave Airlines Exposed as Iran Conflict Widens" — insurancejournal.com, March 3, 2026
- Global Reinsurance, "Iran conflict: War amplifies specialty insurance tail risk, says Moody's" — globalreinsurance.com, March 2026
- Moody's, via Global Reinsurance — specialty insurance tail risk assessment, March 2026
- Fortune, "Iranian attacks on Amazon data centers in UAE, Bahrain signal a new kind of war" — fortune.com, March 9, 2026
- Palo Alto Networks Unit 42, "Threat Brief: March 2026 Escalation of Cyber Risk Related to Iran" — unit42.paloaltonetworks.com, March 2026
- Actuaries Institute, "Back from the Brink: The near collapse of Lloyd's of London" — actuaries.asn.au, 2015
- Pool Reinsurance Company, "How Pool Re Works" — poolre.co.uk
- WTW, "The future of TRIA: What policyholders need to know for 2027 and beyond" — wtwco.com, November 2025
- ASIS International, "War Risk Insurance Market Grows Amid Global Volatility" — asisonline.org, September 2025
- Reinsurance News, "Swiss Re and Berkshire Hathaway top global reinsurer rankings" — reinsurancene.ws, 2025
- Reinsurance News, "War risks return to the seas as reinsurance faces a new era of uncertainty: Willis Re" — reinsurancene.ws, 2025
- IUMI, "Stats Report 2025" — iumi.com, 2025
- Strauss Center, "Strait of Hormuz — Insurance Market" and "Tanker War" — strausscenter.org
- Beinsure, "Global Marine Insurance Rate Hikes for 2025" and "Gulf war-risk insurance withdrawal" — beinsure.com, 2025-2026
- Insurance Journal, "Black Sea War Risk Insurance Soars 250% After Ship Attacks" — insurancejournal.com, December 2025
- CNN, "The Tanker War: How history is repeating itself on the Strait of Hormuz" — cnn.com, March 22, 2026
- Wikipedia, "List of ships attacked during the 2026 Iran war" and "2026 Strait of Hormuz crisis" — en.wikipedia.org
