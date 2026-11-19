# Mira Mobile: Corporate Profile

> **Fictional document.** Mira Mobile and Mediland are invented for training business cases. All data is synthetic.
>
> 📄 **PDF version:** [03_mira_mobile.pdf](03_mira_mobile.pdf) · Country: [01_country.md](01_country.md) · Market: [02_telecom_market.md](02_telecom_market.md)

Version 1.1 · November 19, 2026

This profile is a snapshot of the company at the end of 2026; business cases are described separately. All figures are case assumptions, built from the [Mediland Economic Review](01_country.md) and the [Mediland Telecom Market Review](02_telecom_market.md). If figures differ, the Market Review wins. Counts are active SIMs (Activity Base 90) at the end of 2026 (estimate).

## Contents

1. [Who we are](#1-who-we-are)
2. [Where we operate: Mediland](#2-where-we-operate-mediland)
3. [The market](#3-the-market)
4. [Our position in the market](#4-our-position-in-the-market)
5. [Products and services](#5-products-and-services)
6. [Competitors](#6-competitors)
7. [SWOT](#7-swot)
8. [Strategy 2027-2031 and business goals](#8-strategy-2027-2031-and-business-goals)
9. [Technology stack](#9-technology-stack)
10. [How data helps us reach our goals](#10-how-data-helps-us-reach-our-goals)

---

## 1. Who we are

Mira Mobile JSC is the second-largest mobile operator in Mediland. We give good quality at median prices, and we lead the market in bundles for families and homes. Our tagline is **"Together, at home and on the go"**: the phone and the home on one plan and one bill.

| Item | Value (end 2026, estimate) |
| --- | --- |
| Founded | Licence 2005, commercial launch 2006 |
| Head office | Port Selen (R02); regional hubs in Veridan (R01), Teral (R17), Ferron (R19) |
| Owners | Selen Group, a local trade and logistics holding (70%); Corvane investment fund (30%) |
| Mobile SIMs | 7.08 M, 29.8% of the market (#2 after Sunline, 35.2%) |
| Revenue | USD 453 M (2024: 393; 2025: 424), 23.8% of market revenue |
| EBITDA | USD 181 M, 40% margin |
| Capex | USD 91 M, 20% of revenue |
| ASPU / ARPU (mobile) | USD 4.39 / 4.78 per SIM per month |
| Mobile churn | 2.7% per month (market 2.6%, Sunline 2.1%) |
| NPS | +24 |
| Staff | 3,900 (USD 116,000 revenue per employee, the best among large operators) |
| Sales network | 160 own shops, 2,400 dealer points, online shop, self-care app with 3.0 M users |
| Network | 3,500 sites; 4G for 87% of people, 5G for 27% (6 cities), any signal for 95%, signal on 55% of land |

**Milestones**

| Year | Event |
| --- | --- |
| 2006 | Launch: 2G in Port Selen, Veridan and Karvost; prepaid pay-per-use only |
| 2008 | Postpaid plans |
| 2009 | 3G |
| 2011 | B2B unit for SMEs and corporate lines |
| 2013 | Family groups |
| 2014-2016 | 4G in big cities, then in towns and regions; M2M product |
| 2019-2020 | New convergent billing and CRM; mobile home internet (ROUTER) |
| 2021 | Router + Plan: home router and phones on one plan and one bill |
| 2023 | 5G with Nokia; data pipelines on Python and Airflow |
| 2024 | RAN sharing with Nova Wave; eSIM |
| 2025 | Self-care app reaches 3 M users |

---

## 2. Where we operate: Mediland

### 2.1 The country in brief

Mediland is a lower-middle-income country of **22.0 million people** between the steppe and the Selen Sea. It is a presidential republic of 20 regions (R01-R20) with its capital in Veridan. Full details: [01_country.md](01_country.md).

| Indicator | Value |
| --- | --- |
| Population, 2026 | 22.0 M, growing 1.6% a year |
| Households | 5.3 M, 4.2 people on average |
| Median age | 27 years; 32% of people are under 15 |
| Urban population | 60% (52% in 2010) |
| GDP, 2026 | USD 106 bn; USD 4,820 per person |
| Real GDP growth | 7.0% a year in 2021-2025; about 6.8% a year to 2030 |
| Inflation, 2026 | 5.8% |
| Household income | USD 950 a month on average (USD 520 in High Tavar, USD 1,420 in Nova Lume) |
| Time zones | UTC+5 (16 regions); UTC+6 (eastern steppe, R12-R15) |
| Calling code | +888 |

Economy: farming, mining, energy and industry make 55% of GDP. ICT is only 5% of GDP, but it grew 18% in 2025. Transit to landlocked neighbors, tourism (3.1 M visitors in 2025) and a new air hub are growing quickly.

### 2.2 Geography: why it matters for a mobile operator

Half the people live on the central river plains, which are only a fifth of the land. Mountains and steppe cover two thirds of the land but hold only a fifth of the people. About 19% of the land has no permanent settlements.

| Terrain | People, M (share) | Share of land | Mira SIMs share | What it means for us |
| --- | --- | --- | --- | --- |
| River plain | 11.12 (51%) | 19% | about 57% | Our core: capital, industrial cities, dense demand |
| Coast | 5.02 (23%) | 11% | about 27% | Strong: Port Selen (our home city), summer tourist peak |
| Hills | 1.30 (6%) | 3% | about 5% | On par with population |
| Steppe | 2.43 (11%) | 35% | about 6% | Weak: long distances, no 900 MHz spectrum |
| Mountains | 2.13 (10%) | 32% | about 5% | Weak: valleys block signal, passes close in winter |

**Our strong regions:** river plains and coast (R01-R03, R05-R08, R16-R20).

**Our weak regions:** mountains and steppe (R04, R09-R15).

### 2.3 The regions that drive demand

Five regions (Veridan, Port Selen, Nova Lume, Karvost, Dorhan) produce 65% of GDP with 43% of the people. These are also the places where data use, 5G and home internet grow fastest.

- **Port Selen (R02):** financial capital and main seaport, 3.0 M people, our head office.
- **Veridan (R01):** political capital, planned city, universities.
- **Nova Lume (R05):** tech city, the richest and youngest region; Nova Wave's home base.
- **Karvost (R03) and Ferrum Belt (R19):** manufacturing and worker districts.
- **Teral (R17):** logistics hub and dry port; one of our regional hubs.
- **Coral Bay (R06):** beach resort; population nearly doubles in June-September.

### 2.4 National programs that create demand

- **Digital Mediland 2030:** ICT from 5% to 9% of GDP; e-government (70% of services online), digital ID (8 M users), e-wallets (6.1 M users), online school, telemedicine.
- **Green Growth Strategy 2035:** smart grid, smart meters, environmental sensors; demand for M2M and connectivity in remote areas.
- **Transit and tourism:** the East-West rail corridor (electrified by 2029), the Kesh tunnel to Kordana (2030), Mira Gateway airport; more roaming and short-term SIMs.
- **A growing middle class:** about 1.2 M households (24%) in the big cities; they buy on credit, pay cashless and travel abroad.

### 2.5 The year in a customer's life

Mediland has strong seasons, and they shape how customers use and pay for mobile service:

- **June-September:** herders go up to the high pastures and leave coverage (R09-R11); the coast fills with tourists and seasonal workers.
- **September:** students move to Veridan, Nova Lume and Port Selen.
- **October-November:** seasonal and Belmora workers leave the country.
- **All year:** mine rotation of two weeks on, two weeks off (Dorhan, Qasra).
- **Peaks:** Spring Day (March 21-24) and New Year, with travel and top-ups.

---

## 3. The market

Full details: [02_telecom_market.md](02_telecom_market.md).

### 3.1 Size and growth

| Metric | End 2026 (estimate) | Trend |
| --- | --- | --- |
| Service revenue | USD 1.91 bn (1.8% of GDP) | +7.9% a year in 2023-2026; about 2.20 bn in 2028 |
| Active mobile SIMs | 23.8 M (108 per 100 people) | +5.8% a year |
| Unique mobile users | 15.0 M (68% of people) | 1.41 SIMs per user |
| Smartphones | 79% of phone SIMs | |
| 5G SIMs | 2.2 M (10% of phone SIMs) | 5.4 M expected in 2028 |
| Data per smartphone | 9.6 GB a month | +25% a year |
| Mobile home routers | 1.12 M | +29% a year, the fastest-growing service |
| M2M SIMs | 1.55 M | +25% a year |
| Homes with broadband | 2.25 M (42% of households) | wired lines reach only a quarter of homes |
| Fixed voice | 3.0 M lines | -2.5% a year |
| Prepaid share | 72% of SIMs | |
| Mobile churn | 2.6% a month | prepaid 3.2%, postpaid 1.1% |

Real prices fall about 5% a year: prices stay flat while plans include more data. Price wars are rare; operators compete on bundles, 5G and service.

### 3.2 Revenue by service, 2026

| Service | USD M | Share |
| --- | --- | --- |
| B2C mobile (phones and routers) | 992 | 52.1% |
| Wired broadband | 274 | 14.4% |
| Enterprise data and ICT | 220 | 11.5% |
| B2B mobile | 175 | 9.2% |
| Wholesale | 130 | 6.8% |
| Fixed voice | 100 | 5.2% |
| M2M | 15 | 0.8% |
| **Total** | **1,906** | **100%** |

### 3.3 Rules of the market

- Regulator: Mediland Communications Authority (MCA); 15-year technology-neutral licences.
- **Number portability** since 2022: a port takes one working day; about 0.5 M numbers move a year.
- SIM registration with digital ID since 2023, at most 10 SIMs per person.
- Operators close prepaid numbers after 120-180 days without paid activity and reuse numbers after 6 months.
- **Expected in 2027:** a 700 MHz spectrum auction for rural coverage and rules for low-cost brands without their own network (MVNOs).
- Universal Service Fund: 1% of revenue, spent on remote towers and social tariffs.

---

## 4. Our position in the market

### 4.1 The five operators

| Operator | Since | Focus | Mobile SIMs, M (share 2023 -> 2026) | Revenue, USD M | Churn, %/month | NPS | EBITDA margin |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Sunline | 1998 | Mass B2C, premium, large B2B | 8.36 (38.5% -> 35.2%) | 534 | 2.1 | +32 | 44% |
| **Mira Mobile** | 2006 | Families, Router + Plan, SME | **7.08 (30.5% -> 29.8%)** | **453** | **2.7** | **+24** | **40%** |
| MedTel | 1962 / 2004 | Fixed lines, rural and social tariffs, wholesale | 3.81 (19.5% -> 16.0%) | 474 | 3.3 | +5 | 28% |
| Nova Wave | 2021 | Data-first, young urban, 5G home internet | 2.39 (3.5% -> 10.0%) | 160 | 3.8 | +38 | 12% |
| TransMed | 1999 | Large enterprise, business internet | 2.12 (8.0% -> 8.9%) | 284 | 1.2 | +20 (B2B) | 38% |

Sunline and Mira Mobile together hold 65% of mobile SIMs. By total revenue MedTel is second because of fixed lines; in mobile, Mira Mobile is clearly second.

**Our growth, 2024-2026:** SIMs 6.41 M -> 7.08 M (+10.5%), twice as fast as Sunline; revenue USD 393 M -> 453 M (+15%). But our share slipped from 30.5% to 29.8% since 2023, mostly to Nova Wave.

### 4.2 Shares by segment, 2026

| Segment | Market size | Mira share | Leader |
| --- | --- | --- | --- |
| B2C Router + Plan | 0.95 M SIMs | **56%** | **Mira Mobile** |
| B2C family groups | 1.80 M SIMs | 39% | Sunline (41%) |
| B2C M2M | 0.20 M SIMs | 34% | Sunline (46%) |
| B2C plans | 10.30 M SIMs | 31% | Sunline (38%) |
| B2C pay-per-use | 6.60 M SIMs | 26% | Sunline (33%) |
| B2B mobile | 1.75 M SIMs | 25% | Sunline (34%) |
| B2C standalone home routers | 0.70 M SIMs | 24% | Nova Wave (35%) |
| 5G SIMs | 2.2 M SIMs | 23% | Sunline (42%) |
| Wholesale | USD 130 M | 22% | MedTel (32%) |
| B2B standalone routers | 0.11 M SIMs | 20% | TransMed (35%) |
| B2B M2M | 1.35 M SIMs | 18% | TransMed (35%) |
| Enterprise data and ICT | USD 220 M | 16% | TransMed (45%) |
| Wired broadband (resold on MedTel's network) | 1.45 M lines | 9% | MedTel (60%) |

- **Where we win:** Router + Plan, family groups, B2C plans on the plains and the coast.
- **Where we are exposed:** pay-per-use users in the mountains and steppe (MedTel is cheaper, Sunline covers more); young urban data users and standalone 5G home routers (Nova Wave).
- **Where we are weak:** large enterprise, B2B M2M and wired broadband.

---

## 5. Products and services

### 5.1 B2C

- **Mobile plans (PLAN):** packages of minutes, SMS and data for a fixed fee.
- **Pay-per-use (PPU):** no fee; each minute, SMS and MB is charged.
- **Family groups (GROUP):** one Payer pays the group fee, Members share the package.
- **Home internet (ROUTER):** 4G/5G router with an internet-only plan, for homes without fiber.
- **Router + Plan (ROUTER_PLAN):** home router and up to 4 phones on one plan and one bill. Our flagship product.
- **Add-ons:** extra data, unlimited social apps and messengers, roaming packs, international minutes.
- **M2M for consumers:** car GPS trackers, home alarms.
- **Digital:** self-care app, eSIM, online shop, top-ups in the app.

### 5.2 B2B

- Corporate lines and SME groups with pooled data.
- Router + Plan and routers for shops and offices.
- M2M and IoT: utility meters, fleet trackers, POS terminals, vending machines.
- Account managers for large clients; online business portal.

### 5.3 Key plans (USD per month)

| Plan | Price | What the customer gets |
| --- | --- | --- |
| Mira Go (PPU) | no fee | minute 0.02-0.04, SMS 0.02, 1 GB 6.00 |
| Mira Start | 2.50 | 3 GB, 100 min |
| Mira Smart | 5.00 | 12 GB, 300 min, 100 SMS |
| Mira Max | 9.00 | 40 GB, 600 min, unlimited on-net calls |
| Mira 5G Unlimited | 14.50 | unlimited data (slower after 200 GB) |
| Mira Family | 14.00 | Payer + up to 4 Members, 60 GB shared |
| Mira Home 4G / 5G | 12.00 / 17.00 | 150 GB / unlimited at lower speed |
| Mira Home+ (Router + Plan) | 22.00 | home router + 3 phones with 10 GB each |
| Business Line | 8.00 | 20 GB, 500 min, priority support |
| Business Team | 6.00 per line | pooled data, from 5 lines |
| M2M Meter / Tracker | 0.55 / 1.20 | small data pool, no voice |

### 5.4 Our customer base, end 2026

| Group | Active SIMs, thousand |
| --- | --- |
| B2C plans and pay-per-use | 4,910 |
| B2C phones on family and Router + Plan groups | 1,094 |
| Home routers (B2C 308, B2B 37) | 345 |
| B2B lines and groups | 420 |
| M2M (B2C 68, B2B 243) | 311 |
| **Total** | **7,080** (B2C 6,380; B2B 700) |

About 75% of our SIMs are prepaid. Pay-per-use is 100% prepaid; groups, Router + Plan and B2B are mostly postpaid.

---

## 6. Competitors

**Sunline: the leader we chase.** Best coverage (4G for 91% of people, signal on 64% of land), strongest brand, prices 8% above the median, 5G in 9 cities. It is building a fintech ecosystem (SunPay e-wallet, micro-loans) and tests satellite-to-phone service. Threat to us: price moves and better coverage in the regions. Our answer: equal 4G on the plains and coast, 700 MHz for the regions, stronger home bundles.

**Nova Wave: the fast newcomer.** Launched in 2021, now 10% of SIMs. Data-first, digital-only, the first 5G standalone core, the lowest cost per GB and the highest NPS (+38). About 40% of its SIMs are second SIMs. It leads standalone home routers and wants 0.5 M 5G home routers by 2031. Threat to us: young urban users and home internet. It is also our partner: we share radio networks in Veridan and Port Selen suburbs.

**MedTel: the old national operator.** Owns fixed lines, the national backbone and most rural towers; prices about 15% below the median with state support. Strong with older and rural customers. Threat to us: cheap pay-per-use in the mountains and steppe. We also rent fiber from MedTel and resell its wired internet.

**TransMed: the business operator.** Owns 9,000 km of fiber along railways and pipelines, runs private 5G for mines and the port, and leads enterprise data. Lowest churn (1.2%). We compete with it for B2B, and we rent its fiber.

**Coming in 2027: low-cost brands (MVNOs).** Banks and e-wallet brands are interested. They would target the mass B2C market, our core.

### Competitive forces for Mira Mobile

| Force | Level for us | Why |
| --- | --- | --- |
| Rivalry | High | We fight on two fronts: Sunline on quality, Nova Wave on data and home internet |
| New entrants | Medium | MVNO rules expected in 2027 |
| Substitutes | Medium | Messengers replace paid voice and SMS; satellite internet in remote areas |
| Buyers | High | Price-sensitive families, multi-SIM use, one-day number porting |
| Suppliers | Medium | Few radio vendors; spectrum from the state; we rent fiber from rivals |

---

## 7. SWOT

| | |
| --- | --- |
| **Strengths** | Leader in Router + Plan and close second in family groups; good quality at median prices; strong on the plains and the coast; strong SME base; most efficient large operator |
| **Weaknesses** | Weaker coverage in mountains and steppe (no 900 MHz); small in large enterprise; rents fiber from rivals; churn above Sunline |
| **Opportunities** | 700 MHz auction in 2027; home internet where fiber is missing; SME digitalization; analytics-driven retention; more network sharing |
| **Threats** | Nova Wave in 5G home internet and among young users; Sunline price cuts; MVNOs from 2027; cost of replacing the old radio network |

---

## 8. Strategy 2027-2031 and business goals

Our strategy has three pillars.

**1. Close the gap with Sunline.**
- Equal 4G coverage on the plains and the coast.
- 5G in 12 cities by 2029 (6 today); 5G standalone, cloud-native core by 2029.
- Win 700 MHz in the 2027 auction to close the rural gap.
- About 900 new sites (4,400 in total), 250 of them on shared towers in the steppe.
- 3G off in 2027, its spectrum moved to 4G.

**2. Win the household.**
- Router + Plan and family groups as the main products.
- The home, not the SIM, is the unit of sale.
- Home internet where there is no fiber, before Nova Wave takes it.

**3. Keep customers with data.**
- Targeted offers and better care, based on what we know about customers.
- Bring monthly churn from **2.7%** down to Sunline's level, **about 2.1%**.

### Goals and how we measure them

| Goal | Main measure | 2026 | Target |
| --- | --- | --- | --- |
| Lower churn | Monthly mobile churn | 2.7% | about 2.1% |
| Defend share | Mobile SIM share | 29.8% | hold and grow |
| Win the household | Share of Router + Plan / family groups | 56% / 39% | lead both |
| Better network | 5G cities | 6 | 12 by 2029 |
| Better network | Sites | 3,500 | about 4,400 by 2031 |
| Better service | NPS | +24 | closer to Sunline (+32) |

---

## 9. Technology stack

### 9.1 Network

| Layer | Now (2026) | Target (2031) |
| --- | --- | --- |
| Spectrum | 800, 1800, 2100, 2600 MHz; 3.5 GHz (80 MHz); no 900 MHz | + 700 MHz for rural coverage |
| Radio | 2G/3G/4G from Huawei; 5G from Nokia; RAN sharing with Nova Wave | 4G/5G only; gradual swap of old Huawei radio |
| Core | 4G core with VoLTE; 5G non-standalone | 5G standalone, cloud-native, by 2029 |
| Transport | Own fiber in Port Selen, microwave, fiber leased from MedTel and TransMed | More own fiber in big cities; shared towers in the steppe |
| 5G cities | Port Selen, Veridan, Nova Lume, Karvost, Teral, Coral Bay | 12 cities by 2029 |

### 9.2 IT systems

| System | What it does |
| --- | --- |
| Convergent billing (since 2019) | Accounts, numbers, tariffs, balances, charges and invoices for mobile, routers and groups |
| CRM (since 2020) | Customers, contracts, segments, groups, addresses, consents, campaigns |
| Mediation | Usage records: calls, SMS, data, roaming, cells, devices |
| Payments gateway | Top-ups and invoice payments through banks, cash terminals and e-wallets |
| Sales and number management | Dealer portal, activations, SIM and number stock, number portability |
| Customer care and digital | Contact center, tickets, self-care app |
| Network operations (OSS) | Sites, cells, quality measures, outages |
| External data | Regions, holidays, weather, natural disasters |

### 9.3 Data and analytics platform

- **Now:** data warehouse (since 2012) plus data lake (since 2021); nightly batch pipelines in Python and Apache Airflow (since 2023).
- **Target (2031):** one lakehouse instead of two platforms; one shared customer and subscriber view for all reports; a feature store for models.
- **Serving:** model services through an API (FastAPI); dashboards for marketing, care and network teams.
- **AI:** LLM models for topics and sentiment of care tickets, and a RAG assistant over internal documentation.

---

## 10. How data helps us reach our goals

| Business goal | Question for the data | Possible data or ML product | Main sources | How we know it works |
| --- | --- | --- | --- | --- |
| Lower churn to about 2.1% | Which customers are at risk, and why? | Risk scores and early signals | Billing, usage, payments, care, network | Churn rate falls |
| Spend retention money well | Which offer keeps which customer? | Next best offer; campaign tests | CRM campaigns, billing, usage | Offer acceptance; churn of contacted vs not contacted |
| Win the household | Which customers are ready for Family or Router + Plan? | Household view; upsell scoring | CRM groups, billing, usage | Growth in group and Router + Plan SIMs |
| Close the gap with Sunline | Where do we lose customers because of the network? | Network-quality impact on churn; site planning | Network KPIs, outages, usage by cell | Lower churn in regions after new sites |
| Plan capacity | Where will traffic grow, incl. holidays and weather? | Traffic forecast by cell and region | Cell traffic, holidays, weather, disasters | Fewer congested cells at peaks |
| Better care | What do customers complain about? | Ticket topics and sentiment (LLM) | Care tickets | Fewer repeat contacts; higher NPS |
| Fight Nova Wave and MVNOs | Which young or urban users are moving away? | Segment and port-out analysis | Sales, number portability, usage | Share held in young urban segments |

The [Accounting Policy](05_accounting_policy.md) defines how we count customers, activity and churn, so every report and model uses the same rules.

---

## Sources

- [Mediland Economic Review, November 2026](01_country.md)
- [Mediland Telecom Market Review, November 2026](02_telecom_market.md)
- [Mira Mobile: Data Architecture](04_data_architecture.md), technology stack only
