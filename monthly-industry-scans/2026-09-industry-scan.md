# Monthly Industry Use-Case Scan — September 2026
_Generated 2026-09-01_

> **Coverage window:** July 15 – August 31, 2026 (30–45 days).
> Sources prioritized: Reuters, Bloomberg, CNBC, BioPharma Dive, FierceBiotech, Grocery Dive, Mining Weekly, SEMI, TradingKey, DataCenterKnowledge, HPCWire, RISMedia, Design News. Vendor-only marketing posts excluded.

---

## Summary
- **Industries with material changes:** 18 of 28
- **Most consequential single finding:** Goldman Sachs scaled AI agents to 25,000+ bankers by mid-2026, generating investment-banking deliverables in ~30 seconds; simultaneously JPMorgan announced "long-running autonomous agents" (June–August 2026), signaling financial-services displacement has crossed from pilot to production at flagship scale.
- **Scoring update recommendations by flag type:**
  - DEPLOYMENT_ACCEL: 11
  - DISPLACEMENT_REAL: 3
  - ADOPTION_PLATEAU: 3
  - BIFURCATION: 3
  - NO_CHANGE: 8

---

## By Industry

### software
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Multiple enterprise vendors (GitHub Copilot, Amazon Q, Cursor, Anthropic Claude Code):** Multi-step agentic coding agents now handle multi-file edits, test generation, PR review, and security flagging inside single sessions. By Q1 2026, 78% of Claude Code sessions involved multi-file edits (up from 34% in Q1 2025). 57% of organizations deploy multi-step AI agent workflows in development. — [NVIDIA State of AI Report 2026](https://blogs.nvidia.com/blog/state-of-ai-report-2026/) / [Modall AI in Software Development Stats](https://modall.ca/blog/ai-in-software-development-trends-statistics)
- **Enterprise-wide:** Over 80% of enterprises now deploy genAI applications; global AI software spending reached $2.59 trillion, +47% annually. — [NVIDIA State of AI Report 2026](https://blogs.nvidia.com/blog/state-of-ai-report-2026/)

**Scoring implication:** Agentic coding is compressing the 2y/3y deployment curve into realized present-day production. The jump from 34% → 78% multi-file edits in a single year indicates agentic coding platforms have cleared the "good enough for real work" threshold ahead of prior scoring assumptions. Raise 1y/2y displacement scores for software QA, junior dev, and tech-writing sub-segments.

---

### semiconductors
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **SEMICON Taiwan 2026 (late August 2026):** Attendance exceeded 100,000 semiconductor professionals. Central engineering focus: data movement in AI systems now threatens to consume more energy than computation — "the wires connecting chips" identified as the new system-level bottleneck. — [TechTimes, August 31, 2026](https://www.techtimes.com/articles/326056/20260831/semicon-taiwan-2026-kicks-off-ai-chips-bottleneck-wires-connecting-them.htm)
- **Cohu + AI-enabled semiconductor manufacturing:** AI agents deployed for predictive yield improvement and automated equipment maintenance across fabs. SEMI ran a dedicated August 5–6 workshop on AI techniques in semiconductor manufacturing. — [SEMI AI Techniques Workshop](https://www.semi.org/en/event/ai-techniques-workshop)

**Scoring implication:** AI-chip demand is creating a self-reinforcing loop: more AI spending → more fab equipment orders → more advanced semiconductor capacity. The power/interconnect bottleneck identified at SEMICON Taiwan is a short-to-mid-term limiting factor; score 2y/3y semiconductor deployment relative to whether packaging and interconnect solutions scale on schedule.

---

### pharma
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Roche:** Deployed an additional 2,176 NVIDIA Blackwell GPUs, bringing its total to 3,500+ GPUs — described as "the pharmaceutical industry's largest announced hybrid-cloud AI factory." Used for molecular simulation, biomarker discovery, and clinical trial analysis. — [AIM Media House / Pharma AI Infrastructure 2026](https://intuitionlabs.ai/articles/pharma-ai-infrastructure-investments)
- **Industry-wide clinical pipeline:** 15–20 AI-designed drug programs are expected to enter pivotal Phase III trials in 2026, representing the first large-scale test of whether AI-driven discovery produces superior clinical outcomes. EMA released its AI qualification framework for the EU in Q3 2026. — [Axis Intelligence AI Drug Discovery 2026](https://axis-intelligence.com/ai-drug-discovery-2026-complete-analysis/)

**Scoring implication:** Infrastructure investment (Roche's GPU factory) is signaling conviction that AI is production-grade for pharma R&D, not merely pilot-grade. Phase III data this year will materially shift the 3y/5y scoring for pharma—watch for readouts. Current scoring likely underweights near-term infrastructure displacement of traditional HPC/CRO workflows.

---

### tech-hardware
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Broadcom — VMware AI Factory (August 31, 2026):** Launched the software-defined foundation of VMware Private AI Cloud, enabling simplified paths to on-premises AI deployment for enterprises. — [HPCWire/AIwire, August 31, 2026](https://www.hpcwire.com/aiwire/2026/08/31/broadcom-unveils-vmware-ai-factory-with-multi-vendor-hardware-support/)
- **AMD — Helios integrated rack-scale AI system:** Combines 6th-gen EPYC CPUs with MI455X GPUs, Pensando networking, and ROCm into a single-vendor platform aimed at displacing Nvidia-only rack deployments. Announced in August 2026 coverage cycle. — [Data Center Hardware August 2026](https://www.datacenterknowledge.com/data-center-hardware/data-center-hardware-highlights-august-2026)
- **TSMC Arizona:** Ramping 2 nm production targeting GPUs, CPUs, and custom AI accelerators; multiple fabs and advanced packaging capacity being added.

**Scoring implication:** Rack-scale integrated AI systems (AMD Helios, Broadcom VMware AI Factory) are moving hardware deployment from component-level purchasing to turnkey infrastructure purchasing — likely accelerating enterprise AI rollout timelines vs. current assumptions. Power/cooling constraints are the binding limit; score 1y/2y accordingly.

---

### cap-goods
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Hyperscaler CapEx surge:** Four major hyperscalers collectively plan $250 billion in 2026 capital expenditures (+77% vs. 2025), with an estimated $600B total AI infrastructure capex in 2026 globally and $2.1T projected through 2026–2028. This is driving industrial equipment, power systems, and cooling manufacturing orders at unprecedented rates. — [Breitbart/Capital Spending August 2026](https://www.breitbart.com/economy/2026/08/18/capital-spending-boom-lifts-us-manufacturing-beyond-ai/) / [Allianz Economic Research](https://www.allianz.com/content/dam/onemarketing/azcom/Allianz_com/economic-research/publications/specials/en/2026/march/2026_03_25_AI.pdf)
- **Industrial adoption:** Capital goods companies are in an "execution year" — moving from AI prototypes to measurable operational deployments (predictive maintenance, digital twins, AI-assisted manufacturing QC). Most value realized only after reliable scaled deployment with real-time operational context.

**Scoring implication:** AI capex surge is a direct DEPLOYMENT_ACCEL for capital goods makers supplying data-center equipment (power systems, HVAC, precision manufacturing). However, the gap between "prototype" and "scaled" remains wide for industrial AI users themselves. Score 1y/2y infrastructure capex exposure positively; score 3y/5y actual AI productivity adoption conservatively until execution evidence accumulates.

---

### comm-services
**Flag:** DISPLACEMENT_REAL

**Notable use cases this period:**
- **Salesforce (industry aggregate):** 7 in 10 customer-service sessions are now handled autonomously by AI agents among organizations in Salesforce's dataset, with escalations remaining steady. The average AI agents deployed per org nearly tripled from 5 (early 2025) to 13 (April 2026). — [Salesforce / MarketingProfs AI Update August 21 2026](https://www.marketingprofs.com/opinions/2026/55655/ai-update-august-21-2026-ai-news-and-views-from-the-past-two-weeks)
- **IBM + OpenAI partnership:** Joint deployment targeting financial services, government, telecom, and retail for AI across core operations, legacy systems, software dev, and cybersecurity. — IBM/OpenAI joint press

**Scoring implication:** A 70% autonomous session rate for customer service is concrete DISPLACEMENT_REAL evidence — customer-facing communication roles are being displaced now, not in 3–5 years. Raise 1y/2y displacement score for comm-services customer-contact labor significantly. Escalation rates being stable means AI quality is sufficient that human backup isn't being triggered at scale.

---

### div-fin
**Flag:** DISPLACEMENT_REAL

**Notable use cases this period:**
- **Goldman Sachs:** Scaled internal AI agents to 25,000+ bankers in 2026; co-developed autonomous Claude AI agents with Anthropic for trade accounting, reconciliation, and regulatory compliance tasks. CIO described agents as "digital co-workers." — [BankInfoSecurity](https://www.bankinfosecurity.com/how-goldman-sachs-jpmorgan-aig-are-actually-deploying-ai-a-31643) / [Goldman Sachs Internal Agent Rollout 2026](https://callsphere.ai/blog/td30-vrt-goldman-sachs-internal-agent-rollout-2026)
- **Morgan Stanley:** Opening its wealth management platform to AI agents — clients' autonomous agents can now pull data from ShareWorks and Equity Edge, bypassing traditional human-mediated interfaces. One of the first major Wall Street firms to do this. — [CNBC, June 3, 2026](https://www.cnbc.com/2026/06/03/ai-agents-morgan-stanley-wealth-management-funnel.html)

**Scoring implication:** 25,000-banker AI agent rollout at Goldman Sachs is the clearest single DISPLACEMENT_REAL signal in financial services this period. Investment banking analysts and junior operations staff are the primary displacement cohort. The Morgan Stanley platform opening creates a structural shift in how wealth management workflows are intermediated. Raise 1y/2y displacement score for div-fin analyst and operations roles materially.

---

### banks
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **JPMorgan Chase:** Plans announced June 2026 to deploy "long-running autonomous agents" (capable of running 1–2 hours vs. prior 2–3 minute tasks) for investment banking workflows. Already runs 400+ production AI use cases processing ~$10 trillion in daily transactions. AI-generated investment banking presentations now take ~30 seconds vs. hours for junior analysts. — [CNBC, June 9, 2026](https://www.cnbc.com/2026/06/09/jpmorgan-chase-ai-agents.html)
- **FIS / Anthropic — Financial Crimes Agent:** Anthropic-powered agent shipped into pilot deployments at BMO and Amalgamated Bank for financial crimes and AML workflows. — [BankInfoSecurity](https://www.bankinfosecurity.com/how-goldman-sachs-jpmorgan-aig-are-actually-deploying-ai-a-31643)
- **Commonwealth Bank:** Reduced fraud losses by 20% in H1 FY2026 using a proprietary AI fraud-detection agent. — [Banking AI 2026: From Pilots to Production](https://blog.thecgaigroup.com/banking-ai-2026)
- **EU AI Act enforcement:** High-risk system obligations (credit scoring, fraud detection, automated lending) became fully enforceable August 2, 2026 — introducing compliance cost and deployment friction for EU-exposed banks.

**Scoring implication:** Banks are now firmly in production-scale AI deployment, not piloting. The 400 JPMorgan use cases + FIS agent rollouts + Commonwealth fraud results confirm deployment acceleration is real and measurable. EU compliance cost is a 1y-relevant headwind for EU-exposed banks. Raise 1y/2y banking deployment scores; add compliance-cost headwind for EU-specific institutions.

---

### insurance
**Flag:** ADOPTION_PLATEAU

**Notable use cases this period:**
- No material new deployments identified in the July 15–August 31 window specifically. Broader 2026 trend: 65% of insurers plan scaled AI agents for claims processing in 2026, but as of current surveys only 22% expect agentic solutions in production by year-end.
- **Regulatory:** EU AI Act high-risk obligations for AI used in life/health risk assessment and pricing became operative August 2026 — adding compliance overhead.

**Scoring implication:** Insurance shows a clear gap between deployment intent and actual production rollout. The EU AI Act creating compliance obligations for underwriting AI may further slow deployment for European carriers. Score 1y insurance AI at ADOPTION_PLATEAU; 3y/5y deployment trajectory is still intact but current-year realization is below prior assumptions.

---

### retailing
**Flag:** BIFURCATION

**Notable use cases this period:**
- **Wendy's:** AI-powered drive-thru technology reduced average wait times by 22 seconds per order — deployed system-wide. — [Deloitte AI in Restaurants](https://www.deloitte.com/us/en/insights/industry/retail-distribution/ai-in-restaurants.html)
- **Industry-wide:** Retailers using AI show 2.3x higher sales and 2.5x better profitability than non-adopters. 89% of retailers actively using or testing AI; budget increases planned by 90%.

**Scoring implication:** The 2.3x sales/profitability gap between AI and non-AI retailers is actionable BIFURCATION evidence. Winners are compounding advantages through personalization, inventory optimization, and dynamic pricing. Raise 2y/3y bifurcation signal for retailing; score non-AI-adopting retailers as structurally disadvantaged.

---

### media-ent
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **OpenAI Sora / Google Veo (industry):** By April 2026 these video models hit native 4K resolution with synchronized audio and multi-scene storyboarding — described as quality "that seemed like science fiction a few years earlier." This capability is now embedded in studio production pipelines at scale. — [StreamingMedia, The State of AI in On-Demand Streaming 2026](https://www.streamingmedia.com/Articles/Editorial/Featured-Articles/The-State-of-AI-in-On-Demand-Streaming-in-2026-173868.aspx)
- **AI content creation industry-wide:** Gen AI moved "from experiment to part of union agreements, lawsuits against record labels and studios' everyday editorial decisions" in 2026. Multiple media organizations have AI applications in full commercial implementation for content creation, virtual production, and automated moderation. — [Deloitte 2026 Media & Entertainment Outlook](https://www.deloitte.com/us/en/insights/industry/technology/technology-media-telecom-outlooks/media-entertainment-industry-outlook.html)
- **Market growth signal:** AI in M&E market grew from $28.3B (2025) to $35.8B (2026) — a 26.3% increase.

**Scoring implication:** Gen AI video hitting 4K studio quality is a threshold event for content displacement. The integration into union agreements signals that labor displacement is now a formally negotiated reality, not a hypothetical. Raise 1y/2y displacement scores for content writers, video editors, and voice talent sub-segments.

---

### healthcare
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Intermountain Health / Microsoft Dragon Copilot:** AI clinical documentation system achieved 27% reduction in time spent on patient notes per appointment. Deployed at scale across the health system. — [Wolters Kluwer 2026 Future Ready Healthcare](https://www.wolterskluwer.com/en/expert-insights/2026-future-ready-healthcare)
- **Cooper University Healthcare:** Clinicians saved over 1 hour of documentation time per day using AI documentation tools — deployed operationally. — same source
- **Market status:** FDA had cleared/approved ~1,250 AI/ML-enabled medical devices by May 2025, with deployments accelerating in 2026 across Ambience, Abridge, and Dragon Copilot platforms.

**Scoring implication:** Clinical documentation AI is in production deployment at major health systems and is delivering quantified ROI (1+ hour/day saved). This is the clearest near-term healthcare AI deployment. Raise 1y/2y scores for medical scribing, documentation, and administrative roles. Longer-horizon clinical decision support and diagnostic AI remain earlier-stage.

---

### autos
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Waymo (August 12, 2026):** Now serving 9 directly operated robotaxi cities: SF Bay Area, Phoenix, LA, Miami, Nashville, Orlando, Dallas, Houston, San Antonio — plus Uber partnerships in Austin and Atlanta. In August 2026, Waymo began deploying its new purpose-built Zeekr "Ojai" robotaxi vehicle in SF, LA, and Phoenix. Also preparing fully autonomous operations in Denver, Las Vegas, San Diego, and Tampa. — [Waymo Expansion 2026 / Fakepe Blog, August 27, 2026](https://fakepe.com/blog/2026/08/27/waymo-expansion-2026-new-cities-zeekr-robotaxis-1m-rides-goal/)
- **Nvidia Alpamayo platform + Lucid/Nuro/Uber alliance:** Nvidia introduced its robotaxi platform forming the backbone of a new three-party AV alliance unveiled at CES 2026.

**Scoring implication:** Waymo's 9-city deployment with a new purpose-built vehicle in August 2026 is the clearest DEPLOYMENT_ACCEL signal in autos. This is no longer pilot-scale — it is commercial service across major US metro areas. Raise 1y scoring for autonomous ride-hailing; the displacement of human drivers in robotaxi corridors is an active present-day event, not a 5y+ horizon.

---

### energy
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Cairn Oil & Gas — CAIRA (June 2026):** Launched proprietary GenAI platform (Cairn Artificial Intelligence and Research Assistant) to automate O&M procedure writing, regulatory filings, and well-pad design. — [Gartner/Smartbridge AI in Oil & Gas 2026](https://smartbridge.com/2026-gartner-ai-predictions-oil-and-gas/)
- **Industry-wide (U.S. E&P sector):** AI tools including digital twins, ML for drill steering, and predictive maintenance are actively adopted by U.S. operators; large-language models now handling O&M procedures and regulatory filing automation at scale. 62% of oil and gas respondents have already deployed AI, matching genAI deployment rate.

**Scoring implication:** The energy/O&P sector has crossed into majority-deployment territory (62% deployed AI). The Cairn CAIRA platform is a concrete named deployment with operational scope. Raise 2y/3y scoring for energy-sector operational AI; the primary drag remains skilled-labor availability bridging petroleum engineering and data science domains.

---

### materials
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **U.S. DOE / PNNL — CICERO (August 14, 2026 coverage):** AI agents designed 96 simultaneous experiments within a day for critical minerals recovery from industrial waste — a task that previously took months or years. System combines AI agents, robotics, and analytical instruments. — [Mining Weekly, August 14, 2026](https://www.miningweekly.com/article/ai-and-alloys-mining-innovation-sasols-pem-electrolyser-make-headlines-2026-08-14) / [Mining.com](https://www.mining.com/us-deploys-ai-agents-to-speed-critical-minerals-recovery/)
- **Biomining / sustainable extraction:** Advanced from experimental to commercial deployment in 2026 for deep-sea and hard-to-reach mineral extraction.

**Scoring implication:** The PNNL CICERO deployment compresses materials-science experimentation timelines dramatically. This is a government-deployed production system, not a vendor demonstration. Flag as 2y/3y acceleration for critical minerals and advanced materials R&D sub-segments.

---

### telecom
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Industry-wide (NVIDIA Telecom Survey, 2026):** 48% of telecom enterprises have deployed agentic AI in at least one core business function — nearly double the cross-industry average of 26%. Network automation has overtaken customer experience as the leading use case, with operators reporting 15–30% opex reductions, 10–25% churn reductions, and 40%+ customer service cost cuts. — [NVIDIA State of AI in Telecom Survey 2026](https://www.nvidia.com/en-us/lp/industries/telecommunications/state-of-ai-in-telecom-survey-report/)
- **EU AI Act (August 2, 2026):** Article 50 transparency obligations now apply to telecom AI-powered customer interaction systems — virtual assistants must disclose AI nature.

**Scoring implication:** Telecom's 48% agentic AI deployment rate (vs. 26% cross-industry) indicates the sector is ahead of curve. Network operations automation is in production, delivering quantified ROI. Raise 1y/2y telecom network ops AI deployment score and add regulatory compliance cost for EU-exposed operators.

---

### utilities
**Flag:** NO_CHANGE

**Notable use cases this period:**
- No major new deployments identified in the July 15–August 31, 2026 window. Broader 2026 context: AI deployed in seven core use cases (leak detection, demand forecasting, vegetation management, customer service automation, predictive maintenance, water quality monitoring, grid optimization). Smart-grid AI deployment is proceeding but constrained by data standardization issues highlighted by WEF as the single biggest barrier.

**Scoring implication:** Utilities AI is progressing steadily but without step-change events this period. Data standardization remains the binding constraint. Score 2y/3y AI adoption as gradual/linear rather than exponential. Monitor for any utility announcing AI-driven grid optimization with verifiable KPIs.

---

### transport
**Flag:** BIFURCATION

**Notable use cases this period:**
- **Industry-wide (logistics):** Operators that deployed AI route optimization maintained margins in 2026 while non-adopters saw 2–3 percentage point margin compression. Drone networks and warehouse construction surge reshaping North American logistics. — [MarketScale 2026](https://www.marketscale.com/industries/transportation/ai-acquisitions-drone-networks-and-a-warehouse-construction-surge-are-reshaping-north-american-logistics-in-2026)
- **Warehouse operations:** Inventory control/planning accounts for 32% of AI in logistics market; autonomous warehouse orchestration (pick/pack/ship without human intervention) is in commercial deployment.

**Scoring implication:** A 2–3pp margin gap between AI adopters and non-adopters is quantifiable BIFURCATION evidence. The logistics/transport sector is bifurcating now — not in 3–5 years. Raise 1y/2y bifurcation score; flag that laggard logistics operators face structural margin compression that compounds with each year of delayed AI adoption.

---

### food-staples
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **SPS Commerce — MAX agentic AI tool:** Q2 2026 revenue $197.8M (+19% adjusted EBITDA YoY) driven in part by rollout of MAX agentic AI for supply chain management. — [SPS Commerce Q2 2026 Results](https://www.emarketer.com/content/faq-on-digital-grocery-how-ai-retail-media-omnichannel-fulfillment-reshaping-2026)
- **Industry-wide CPG:** 71% of CPG executives now use AI (up from 42% in 2024). AI deployed for demand forecasting, production planning, quality inspection, inventory optimization, and procurement across major food companies.

**Scoring implication:** CPG/food-staples AI adoption jumped from 42% to 71% in under two years — this is DEPLOYMENT_ACCEL. The SPS Commerce MAX tool is a concrete deployed product with measurable financial impact. Raise 2y/3y scoring for food-staples operations AI; displacement of demand-planning and supply-chain analyst roles is already occurring at scale.

---

### hh-products
**Flag:** NO_CHANGE

**Notable use cases this period:**
- No material new AI deployments identified specifically in household products (cleaning products, laundry, etc.) manufacturing or consumer product lines in the July 15–August 31, 2026 window.
- General trend: AI used for demand forecasting, product formulation optimization, and supply chain — but no specific verifiable deployments with scale signals found for this period.

**Scoring implication:** No scoring change recommended. Monitor for P&G, Colgate, or Unilever announcements of AI-driven operational or product innovation with quantified outcomes.

---

### consumer-dur
**Flag:** NO_CHANGE

**Notable use cases this period:**
- **Samsung — Bespoke AI appliances (August 2026 launches):** New AI washing machines and refrigerators launched with adaptive learning for fabric care, temperature control, and cleaning optimization. — [AnalyticsInsight Aug 2026 Home Appliances](https://www.analyticsinsight.net/ampstories/home-electronics/aug-2026-home-appliances-release)
- Scale signal is consumer product launches, not enterprise deployment — no quantified workforce or revenue displacement evidence yet.

**Scoring implication:** AI-embedded consumer durables are progressing steadily but this is product feature evolution, not transformative deployment. No scoring change recommended for displacement; watch for smart appliance ecosystem network effects in 2y/3y horizon.

---

### consumer-svcs
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Wendy's — AI drive-thru (deployed system-wide):** AI-powered drive-thru ordering reduced average wait times by 22 seconds per order. — [Deloitte AI in Restaurants](https://www.deloitte.com/us/en/insights/industry/retail-distribution/ai-in-restaurants.html)
- **Restaurant industry:** The global restaurant robotics market reached ~$1.8B in 2026, growing at 61% YoY — projected to reach $5B by 2030. AI is in full commercial deployment for ordering, pricing, reservations, and kitchen automation at major QSR chains.
- **Hospitality:** AI hospitality automation (multilingual AI assistants for phone, email, webchat, WhatsApp) moved out of pilot phase in June 2026 per industry reports.

**Scoring implication:** QSR and hospitality AI deployment has crossed from pilot to commercial scale. The Wendy's deployment is a named, system-wide, quantified deployment. Raise 1y/2y scoring for displacement of order-taking and front-of-house roles in QSR specifically.

---

### real-estate
**Flag:** ADOPTION_PLATEAU

**Notable use cases this period:**
- **Compass — AI-Powered 'Home Platform' (July 2, 2026):** Rolled out to professionals at @properties, Coldwell Banker Realty, Corcoran, and Sotheby's International Realty. Franchise network rollout planned 2027. — [RISMedia, July 2, 2026](https://www.rismedia.com/2026/07/02/compass-rolls-out-ai-powered-home-platform-across-company-owned-brokerage-brands/)
- **Gap survey (CRE Daily):** Of 150+ commercial real estate professionals surveyed, 45% running AI pilots — but only 9% reached enterprise-wide deployment and only 8% said their data infrastructure is fully ready.

**Scoring implication:** Real estate AI shows classic ADOPTION_PLATEAU pattern: strong intent, weak execution. The 9% enterprise-deployment rate vs. 45% piloting represents a stalled deployment curve. Compass's July 2026 rollout is notable as the first major brokerage network deployment. Score 1y at plateau; 3y/5y deployment curve intact but current-year realization is below prior assumptions.

---

### food-retail
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Associated Wholesale Grocers — SmartMeals (full launch 2026):** AI-powered meal planning and shopping assistant deployed by participating independent grocery members, providing personalized shopping experiences at scale. — [Grocery Dive 2026](https://www.grocerydive.com/news/grocers-ai-technology-2026-kroger-albertsons-awg/815720/)
- **Ahold Delhaize:** Developing agentic AI solutions for advertisers to conduct media planning and activation with minimal friction — moving from traditional media buying to AI-orchestrated retail media. — [eMarketer Digital Grocery FAQ 2026](https://www.emarketer.com/content/faq-on-digital-grocery-how-ai-retail-media-omnichannel-fulfillment-reshaping-2026)
- **Anti-theft AI:** Grocers deploying AI computer vision for anti-theft and self-checkout monitoring in response to ~62% increase in shoplifting since self-checkout introduction. — [Supermarket News](https://www.supermarketnews.com/grocery-technology/grocers-want-to-use-ai-for-anti-theft-worker-abuse-report)

**Scoring implication:** Grocery AI has moved from experimentation to operational deployment across three distinct use cases (personalization, retail media, loss prevention). AWG SmartMeals is a concrete named rollout. Raise 2y scoring for food retail AI operations and retail media automation.

---

### biotech-ai
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **Recursion Pharmaceuticals (post-Exscientia merger):** Now operating 5 differentiated clinical programs with defined next-stage milestones, plus $500M+ in upfront and milestone payments earned. Positive Phase 1b/2 results for REC-4881 (FAP) and Phase 1 responses observed in ovarian cancer. — [BioPharma Dive](https://www.biopharmadive.com/news/recursion-study-results-cerebral-cavernous-malformation-ai-drug/725846/) / [FierceBiotech / SEC 8-K FY2026](https://www.sec.gov/Archives/edgar/data/1601830/000160183026000038/exhibit991-10xk25.htm)
- **Self-driving labs industry-wide:** Multiple organizations deploying robotic AI lab facilities; autonomous labs not yet independently discovering validated drug candidates but integration is maturing rapidly. — [Drug Target Review / Ardigen 2026](https://ardigen.com/ai-in-biotech-lessons-from-2025-and-the-trends-shaping-drug-discovery-in-2026/)

**Scoring implication:** Recursion/Exscientia's merged pipeline represents the most advanced AI-native biotech clinical program. Phase 2 efficacy data in FAP and Phase 1 in ovarian cancer are real clinical milestones. Raise 2y/3y biotech-ai scoring — if 2026 Phase III readouts are positive, this will shift to DISPLACEMENT_REAL for traditional drug discovery roles. Score 1y as DEPLOYMENT_ACCEL but clinical uncertainty remains high.

---

### foundry-equipment
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **ASML — Q2 2026 guidance raise:** Raised full-year 2026 guidance to sales up to €45 billion driven by AI-chip demand. Planning 30% EUV/DUV capacity expansion by 2027. — [TradingKey / ASML Q2 2026](https://www.tradingkey.com/analysis/stocks/us-stocks/262031304-asml-q2-earnings-beat-as-intel-adopts-next-generation-lithography-equipment-tradingkey)
- **Applied Materials:** Stock up 98% YTD as of August 18, 2026. Demand strongest in advanced foundry/logic manufacturing for AI accelerator production. — [247WallSt, August 18, 2026](https://247wallst.com/investing/2026/08/18/applied-materials-rockets-98-in-2026-how-does-amat-compare-to-lam-research-and-kla-as-ai-capex-powers-chip-gear-stocks/)
- **SEMI global wafer fab spending:** Expected to reach $126 billion in 2026, up significantly from prior years driven by AI demand. Order visibility stretched further out than prior cycles with equipment vendors raising capacity plans for 2027+. — [SEMI Industry Data](https://www.semi.org)

**Scoring implication:** Foundry equipment is in a once-per-decade CapEx supercycle. ASML and Applied Materials financial results are real-world, verified signals. The $126B global wafer fab spend is the largest single investment indicator in the entire 28-industry scan. This category doesn't directly score AI deployment effects on its own workforce, but signals multi-year demand certainty for AI chip production infrastructure.

---

### chip-design-fabless
**Flag:** DEPLOYMENT_ACCEL

**Notable use cases this period:**
- **TSMC revenue +37% YTD 2026, +45% YoY in July 2026:** On track to beat updated 2026 guidance of 40% revenue growth. Diversified AI customer base: Apple, Qualcomm, Broadcom, Amazon, Microsoft, Alphabet, and others driving demand. — [TradingKey / TSMC July 2026](https://www.tradingkey.com/analysis/stocks/us-stocks/262031304-asml-q2-earnings-beat-as-intel-adopts-next-generation-lithography-equipment-tradingkey)
- **Qualcomm — data center inference push:** Announced data center product line built around AI inference use cases, competing against NVIDIA in cost-sensitive inference deployment.
- **AI Chip Wars dynamic:** NVIDIA dominates training; AMD, Qualcomm, Cerebras, SambaNova competing on inference. TSMC is the shared foundry — winning regardless of training vs. inference outcome.

**Scoring implication:** TSMC's +37% revenue growth is the strongest real-money signal that AI chip demand is not plateauing. Fabless chip designers with TSMC manufacturing relationships are structurally positioned to benefit through 3y/5y horizon. The training vs. inference dynamic is a bifurcation risk — score NVIDIA on training dominance with caution about inference competition; score TSMC as low-risk beneficiary of either outcome.

---

### household-personal
**Flag:** NO_CHANGE

**Notable use cases this period:**
- **Philips — SenseIQ/SkinIQ products (2026):** Real-time AI feedback in personal care devices (shavers, skin-care tools) that adapt to user skin and beard type. — [Philips 2026 Personal Care Trends](https://www.philips.com/a-w/about/news/archive/standard/news/articles/2026/six-personal-care-trends-to-watch-in-2026.html)
- No material workforce displacement or revenue-scale evidence found for this period. Product launches represent AI feature additions to hardware, not operational AI deployment at industry scale.

**Scoring implication:** Household personal care AI is primarily in product-embedded consumer features (smart razors, skin analyzers). No scoring change recommended. Monitor for beauty/personal care companies announcing AI-driven manufacturing or formulation R&D at production scale.

---

## Proposed Brain Entries

_For industries flagged DEPLOYMENT_ACCEL or DISPLACEMENT_REAL. Entries follow the existing schema from ai-revolution-tracker.json. Entry index continues from 190 (next = 191)._

---

**Entry 191 — Goldman Sachs + Morgan Stanley: Financial Services AI Agent Production Rollout (2026)**

```json
{
  "source": "Goldman Sachs AI Agent Rollout 2026 / CNBC Morgan Stanley AI Agents",
  "channel": "BankInfoSecurity / CNBC / AI-Street.co",
  "expert": "Goldman Sachs CIO (unnamed) / CNBC Reporting",
  "expertAngle": "practitioner",
  "publishDate": "2026-08-01",
  "url": "https://www.bankinfosecurity.com/how-goldman-sachs-jpmorgan-aig-are-actually-deploying-ai-a-31643",
  "values": {
    "authority": 9,
    "primarySource": 7,
    "specificity": 8,
    "novelty": 8,
    "insightDensity": 8,
    "contrarian": 3,
    "framework": 5,
    "actionability": 9,
    "evidence": 8,
    "honesty": 8
  },
  "summary": "Goldman Sachs scaled AI agents (Anthropic Claude-based) to 25,000+ bankers in 2026 for trade accounting, reconciliation, and compliance. JPMorgan runs 400+ production AI use cases on its ML platform processing ~$10T daily. Investment banking presentations now generated in ~30 seconds. Morgan Stanley opened its wealth management platform to external AI agents in June 2026.",
  "claims": [
    {
      "claim": "Goldman Sachs deployed AI agents to 25,000+ bankers in 2026, handling accounting, compliance, and finance operations described by CIO as 'digital co-workers'",
      "category": "deployment",
      "industries": ["div-fin", "banks"],
      "timeframe": "near",
      "outcome": "confirmed",
      "outcomeDate": "2026-08",
      "outcomeNote": "BankInfoSecurity reporting confirmed; Anthropic partnership separately disclosed. Investment banking presentations now ~30 seconds vs. hours."
    },
    {
      "claim": "AI-driven displacement of junior analyst work at investment banks is now occurring at production scale, not pilot scale",
      "category": "labor",
      "industries": ["div-fin", "banks"],
      "timeframe": "near",
      "outcome": "confirmed",
      "outcomeDate": "2026-08",
      "outcomeNote": "JPMorgan 400 production use cases + Goldman 25K deployment + Morgan Stanley platform opening are concurrent 2026 evidence."
    }
  ],
  "keyFacts": [
    "Goldman Sachs: 25,000+ bankers using AI agents as of 2026",
    "JPMorgan: 400+ production AI use cases processing $10T daily",
    "JPMorgan: investment banking presentations in ~30 seconds vs. hours previously",
    "Morgan Stanley: opened wealth management platform to AI agents June 2026",
    "FIS/Anthropic: Financial Crimes Agent in pilot at BMO and Amalgamated Bank"
  ],
  "tags": ["banks", "div-fin", "labor-displacement", "agentic-ai", "deployment-confirmed", "2026-Q3"]
}
```

---

**Entry 192 — Waymo 9-City Robotaxi Commercial Deployment + Zeekr Ojai Vehicle (August 2026)**

```json
{
  "source": "Waymo Expansion 2026: New Cities, Zeekr Robotaxis & 1M Rides Goal",
  "channel": "Fakepe Blog / Yahoo Autos / TechCrunch / CNBC",
  "expert": "Waymo (Alphabet subsidiary) deployment reporting",
  "expertAngle": "practitioner",
  "publishDate": "2026-08-27",
  "url": "https://fakepe.com/blog/2026/08/27/waymo-expansion-2026-new-cities-zeekr-robotaxis-1m-rides-goal/",
  "values": {
    "authority": 8,
    "primarySource": 7,
    "specificity": 9,
    "novelty": 7,
    "insightDensity": 7,
    "contrarian": 2,
    "framework": 4,
    "actionability": 8,
    "evidence": 8,
    "honesty": 8
  },
  "summary": "Waymo operated commercial robotaxi service in 9 U.S. cities as of August 12, 2026 (SF Bay Area, Phoenix, LA, Miami, Nashville, Orlando, Dallas, Houston, San Antonio), with Uber partnerships in Austin and Atlanta. In August 2026, Waymo began deploying the Zeekr 'Ojai' purpose-built robotaxi in SF, LA, and Phoenix. Four more cities in preparation (Denver, Las Vegas, San Diego, Tampa). This is the clearest evidence of L4 autonomous vehicles in commercial production in the U.S.",
  "claims": [
    {
      "claim": "L4 autonomous vehicles are in commercial production service across 9 major U.S. metro areas as of August 2026, with a new purpose-built vehicle platform",
      "category": "deployment",
      "industries": ["autos", "transport"],
      "timeframe": "near",
      "outcome": "confirmed",
      "outcomeDate": "2026-08",
      "outcomeNote": "Waymo official service map confirms 9 cities; Zeekr Ojai deployment announced and begun August 2026."
    },
    {
      "claim": "Human ride-hailing drivers face structural displacement in Waymo service corridors — commercial robotaxis undercut gig-driver economics",
      "category": "labor",
      "industries": ["autos", "transport", "consumer-svcs"],
      "timeframe": "near",
      "outcome": "partial",
      "outcomeDate": "2026-08",
      "outcomeNote": "Service scale not yet sufficient for measurable aggregate driver displacement, but trajectory confirmed."
    }
  ],
  "keyFacts": [
    "Waymo: 9 commercial robotaxi cities as of August 12, 2026",
    "Waymo: 4 additional cities in preparation (Denver, Las Vegas, San Diego, Tampa)",
    "Waymo: Zeekr 'Ojai' purpose-built vehicle deployed in SF, LA, Phoenix — August 2026",
    "Waymo: Uber partnership operating in Austin and Atlanta",
    "Nvidia Alpamayo platform: foundation of new Lucid/Nuro/Uber robotaxi alliance (CES 2026)"
  ],
  "tags": ["autos", "transport", "autonomous-vehicles", "labor-displacement", "deployment-confirmed", "2026-Q3", "waymo"]
}
```

---

**Entry 193 — ASML / Applied Materials CapEx Supercycle: $126B Wafer Fab Equipment Spending 2026**

```json
{
  "source": "Applied Materials 98% YTD / ASML Q2 2026 Raised Guidance / SEMI Industry Data",
  "channel": "247WallSt / TradingKey / SEMI / HPCWire",
  "expert": "SEMI (industry body) / Applied Materials CFO reporting",
  "expertAngle": "industry-body",
  "publishDate": "2026-08-18",
  "url": "https://247wallst.com/investing/2026/08/18/applied-materials-rockets-98-in-2026-how-does-amat-compare-to-lam-research-and-kla-as-ai-capex-powers-chip-gear-stocks/",
  "values": {
    "authority": 9,
    "primarySource": 8,
    "specificity": 8,
    "novelty": 6,
    "insightDensity": 7,
    "contrarian": 2,
    "framework": 4,
    "actionability": 7,
    "evidence": 9,
    "honesty": 8
  },
  "summary": "Global wafer fabrication equipment spending expected to reach $126B in 2026 per SEMI. Applied Materials stock +98% YTD as of August 18, 2026, driven by AI accelerator and HBM demand. ASML raised FY2026 guidance to up to €45B and plans 30% EUV/DUV capacity expansion by 2027. TSMC July 2026 revenue +45% YoY; YTD 2026 revenue +37% — on track to beat 40% full-year guidance.",
  "claims": [
    {
      "claim": "AI chip demand has triggered a once-per-decade CapEx supercycle in semiconductor foundry equipment with $126B in wafer fab spending in 2026 alone",
      "category": "investment",
      "industries": ["foundry-equipment", "semiconductors", "chip-design-fabless"],
      "timeframe": "near",
      "outcome": "confirmed",
      "outcomeDate": "2026-08",
      "outcomeNote": "SEMI industry data + ASML/Applied Materials financial results confirm. Order visibility stretched further than in prior cycles."
    },
    {
      "claim": "TSMC revenue growth of 37-45% YoY in 2026 confirms AI chip demand is not plateauing and that fabless chip designers with TSMC relationships have multi-year demand certainty",
      "category": "economics",
      "industries": ["chip-design-fabless", "foundry-equipment"],
      "timeframe": "near",
      "outcome": "confirmed",
      "outcomeDate": "2026-08",
      "outcomeNote": "TSMC officially reported July 2026 revenue +45% YoY; full-year guidance raised to 40%+ growth."
    }
  ],
  "keyFacts": [
    "SEMI: global wafer fab equipment spending $126B in 2026",
    "Applied Materials: +98% stock YTD as of August 18, 2026",
    "ASML: FY2026 guidance raised to €45B; 30% EUV/DUV capacity expansion planned 2027",
    "TSMC: July 2026 revenue +45% YoY; YTD +37%; beating 40% full-year guidance",
    "Hyperscalers: combined $250B CapEx in 2026 (+77% vs. 2025)"
  ],
  "tags": ["foundry-equipment", "semiconductors", "chip-design-fabless", "capex", "investment", "deployment-confirmed", "2026-Q3"]
}
```

---

**Entry 194 — Comm-Services: 70% of Customer Service Sessions Autonomous (Salesforce Aggregate, April 2026)**

```json
{
  "source": "Salesforce AI Agent Aggregate Data / MarketingProfs AI Update August 21 2026",
  "channel": "MarketingProfs / Salesforce Research",
  "expert": "Salesforce Research (dataset aggregate)",
  "expertAngle": "vendor-research",
  "publishDate": "2026-08-21",
  "url": "https://www.marketingprofs.com/opinions/2026/55655/ai-update-august-21-2026-ai-news-and-views-from-the-past-two-weeks",
  "values": {
    "authority": 7,
    "primarySource": 6,
    "specificity": 7,
    "novelty": 7,
    "insightDensity": 6,
    "contrarian": 3,
    "framework": 4,
    "actionability": 8,
    "evidence": 6,
    "honesty": 7
  },
  "summary": "Among organizations in Salesforce's dataset, 7 in 10 customer-service sessions are now handled autonomously by AI agents (as of April 2026), with escalation rates remaining steady. Average AI agents per organization nearly tripled from 5 (early 2025) to 13 (April 2026). Telecom AI survey (NVIDIA, 2026) shows 48% of telecom enterprises deployed agentic AI in at least one core function — nearly double the cross-industry average of 26%.",
  "claims": [
    {
      "claim": "70% of customer-service sessions are handled autonomously by AI among Salesforce platform organizations as of April 2026, with human escalation rates holding steady",
      "category": "deployment",
      "industries": ["comm-services", "retailing", "banks", "telecom"],
      "timeframe": "near",
      "outcome": "confirmed",
      "outcomeDate": "2026-04",
      "outcomeNote": "Salesforce aggregate data reported August 2026. Scope limited to Salesforce platform organizations — not global average."
    },
    {
      "claim": "Customer-facing communication roles (call centers, chat support) are being displaced by AI at production scale in 2026, not in 3-5 years",
      "category": "labor",
      "industries": ["comm-services", "consumer-svcs", "banks", "telecom"],
      "timeframe": "near",
      "outcome": "confirmed",
      "outcomeDate": "2026-04",
      "outcomeNote": "70% autonomous rate confirms displacement is present-day for customer service workers at AI-adopting orgs."
    }
  ],
  "keyFacts": [
    "Salesforce dataset: 70% of customer service sessions autonomous as of April 2026",
    "Salesforce dataset: avg AI agents per org tripled from 5 (early 2025) to 13 (April 2026)",
    "NVIDIA telecom survey: 48% of telecom enterprises deployed agentic AI — double cross-industry average",
    "Telecom AI ROI: 15-30% opex reduction, 10-25% churn reduction, 40%+ customer service cost cuts reported"
  ],
  "tags": ["comm-services", "telecom", "labor-displacement", "agentic-ai", "customer-service", "deployment-confirmed", "2026-Q3"]
}
```

---

## Recommended Engine Updates

1. **div-fin / banks — 1y/2y displacement score: raise significantly.** Goldman Sachs 25K banker AI agent deployment + JPMorgan 400 production use cases + investment banking presentation automation (~30 seconds) confirm that analyst and junior ops displacement is present-day, not forward-looking. Recommend raising 1y displacement sensitivity by at least one scoring tier.

2. **autos — 1y robotaxi deployment score: raise.** Waymo's 9-city commercial service + Zeekr Ojai purpose-built vehicle deployed August 2026 means L4 robotaxis are in commercial production in the U.S. now. The 1y/2y scoring should reflect that human-driven ride-hailing in Waymo corridors faces current-day competition, not a 5y+ future scenario.

3. **comm-services / telecom — 1y displacement score: raise.** 70% autonomous customer-service session rate (Salesforce data, April 2026) and 48% telecom agentic AI deployment (NVIDIA survey) together confirm that customer-contact labor displacement is a 2026 present-day reality. The engine's comm-services displacement score should reflect this.

4. **foundry-equipment / chip-design-fabless — 2y/3y demand curve: raise.** $126B wafer fab spending, ASML €45B guidance, TSMC +37% revenue, Applied Materials +98% stock — these are financial confirmation of a multi-year AI chip supercycle. The scoring engine should reflect higher near-to-mid-term confidence in sustained semiconductor infrastructure investment.

5. **software — 1y agentic-coding displacement: raise.** The 34% → 78% multi-file Claude Code session jump in one year signals agentic coding is past the tipping point. Junior software QA, documentation, and test-writing roles face current-year displacement acceleration.

6. **real-estate / insurance — 1y deployment score: lower (ADOPTION_PLATEAU).** Both industries show intent-execution gaps: real estate at 9% enterprise deployment vs. 45% piloting; insurance at 16% underwriting AI adoption. Recommend lowering 1y projections and flagging these as lagging-adopter industries where structural friction (data readiness, regulatory caution) is slowing deployment.

7. **media-ent — 2y content-creation displacement: raise.** Native 4K AI video (Sora/Veo, April 2026) + integration into union agreements signals content-creation displacement is active now. The 2y/3y scoring for content writers, editors, and voice talent should reflect that AI is production-quality for a meaningful portion of commercial content creation work.
