# Mental Models — Local SEO

Frameworks the canon depends on. Each model is named, sourced, and operator-actionable.

## 1. Eligibility-Then-Ranking (Claudia Tomina via Sterling Sky)

Google's local algorithm runs an **eligibility filter before any ranking calculation**. The filter is dominantly determined by:
- Primary GBP category
- Business name (combined with category to scope the entity)

A "kids dance studio" with that primary category may rank for child-related dance queries but be **excluded entirely from generic dance queries** — the eligibility gate excluded it before ranking ever happened.

**Operator implication:** If you can't see your business in any results for a given query, the diagnosis isn't ranking — it's eligibility. Check primary category + business name FIRST before chasing ranking factors.

## 2. The Three R's — Relevance, Distance, Prominence (Google's documented framework)

Google publicly states three pillars of local ranking:
- **Relevance** — how well the business matches the query (category, name, content)
- **Distance** — how close the business is to the searcher
- **Prominence** — how well-known the business is (reviews, mentions, links, online + offline)

Post-Vicinity (2021), Distance is heavily weighted. Most businesses rank in ~10-mile radius around their pin. Prominence expands the radius.

**Operator implication:** You optimize relevance to be eligible. You optimize prominence to expand reach. Distance is structural — can't fight it without opening another location.

## 3. Pin-As-Anchor (Darren Shaw, Whitespark)

The map pin is the geographic origin from which Google calculates ranking radius. When a business hides its address (SAB), pin behavior gets weird:
- Pin reverts to original verification address (often wrong city)
- OR Google's pin-placement bug puts pin in random locations (including ocean, desert)

**Operator implication:** If you must hide an address, expect 2-8 weeks of ranking volatility. Use grid-rank to find where Google has actually placed your pin. If pin is in the wrong place, file pin-correction request via Google Maps.

## 4. Website-As-Database (Darren Shaw, Whitespark)

Google's GBP is a "mini taster" of your business. Your website is the full database. When you change the GBP, Google **immediately re-crawls your entire website** to validate. The reverse is NOT true — website changes don't trigger GBP re-crawl.

**Operator implication:**
- Update website FIRST (services, hours, address) before updating GBP.
- GBP changes effectively force-feed Google your website — use this when launching new content.
- Your website is your highest-leverage local SEO asset, not your GBP.

## 5. Diversity Update (Joy Hawkins, Sterling Sky)

Google avoids displaying the same URL twice on a single SERP. If your GBP website URL = homepage AND your homepage ranks organically, Google suppresses one of them. You see local pack OR you see organic homepage, not both.

**Operator implication:** Either point GBP to a dedicated landing page (preserves both ranks), OR optimize service pages to rank organically while homepage gets the GBP slot. Don't put homepage URL on GBP if you want homepage to also rank organically for the same queries.

## 6. Vicinity-Era Radius Expansion (Whitespark 2026 LSRF)

Most businesses can rank in ~10-mile radius around their pin. To expand:
- Build prominence (reviews, links, citations)
- Build genuine service-area pages for outer cities (substantive, not template-spun)
- Pursue lower-competition variant queries
- Build branded search in outer cities (PR, sponsorships, community)

You CANNOT shortcut this with a Regis-tier virtual office — they're auto-flagged.

**Operator implication:** Single-location SAB at Vicinity-era can rank well in their immediate area but expansion requires either real second location or 12+ months of prominence-building.

## 7. Reachability-As-Ranking (Whitespark observation, mid-2020s)

Google's Local Service Ads use call-answer rate, response time, and call-handling quality as ranking factors. The "Have AI Get Prices" feature actively calls businesses on behalf of searchers. Whitespark hypothesizes this is migrating to organic local rankings.

**Operator implication:** Phone answer rate matters. Have someone answering the phone during business hours. Train AI receptionist if using one. Publish prices where possible (LSAs and AI tools both use price as filter).

## 8. The 5-Layer Review System (Sterling Sky + Whitespark consensus)

Reviews matter at five distinct layers:
1. **Quantity** — total review count (diminishing returns above ~200)
2. **Recency** — reviews in last 30-90 days; sustained cadence beats burst
3. **Velocity** — reviews per week; industry-relative; spikes trigger filter
4. **Content** — what reviews say (AI reads the text now); descriptive > generic
5. **Distribution** — across platforms (Google + industry-specific); breadth matters for AI visibility

**Operator implication:** Build a review system that produces 1-3 weekly reviews via branded-search-prompt path with engagement-first reviewers. Don't gate, don't pressure on-premises, don't request specific content, don't incentivize.

## 9. The Brand Migration (Claudia Tomina, "Stop Chasing the Local 3-Pack")

Local SEO is migrating from "rank in the 3-pack" to "build an entity that ranks beyond it." The 3-pack is being squeezed by:
- LSAs occupying above-the-fold
- Ads expanding
- AI Overview / Ask Maps changing search behavior

The work expanding to fill this: ad management, short-form video, social presence, Reddit engagement, third-party reviews, industry publications, press releases, local community engagement.

**Operator implication:** Pure GBP-optimization is no longer sufficient at the operator level. Brand-building is becoming load-bearing. Single-location SAB needs to invest in local press / community presence as much as GBP.

## 10. The Eligibility-Erosion Trade-off (Niching the Business Name)

Niching down too hard with the business name ("Bob's HVAC Air Conditioning Repair") narrows the entity in Google's eyes — you may rank great for "AC repair" but become ineligible for "HVAC service" because Google decides you only do AC.

**Operator implication:** Business names need balance. Too generic = nothing ranks well. Too specific = ineligible for adjacent queries. The middle ground is a brand name + 1 generic descriptor (e.g., "Acme Plumbing" — never the umbrella but never single-service-only).

## 11. The Account-Tower Risk Model

GBP suspensions can cascade up the account level. If one user account is restricted, ALL listings that account has access to are at risk. Sterling Sky observation: agency dashboards (using domain emails) have never been seen to suffer account-level suspensions; random Gmail accounts have.

**Operator implication:** Set up GBP with a Google Workspace account using a domain email. Use the Agency Dashboard for managing multiple listings. Never use a personal Gmail to own a real business listing.

## 12. The 6-Stage Recovery Curve (Algorithm Hits)

Local SEO recovery from algorithm hits follows a predictable shape:
1. **Detection** — when did rankings drop? Cross-reference Google's update calendar.
2. **Diagnosis** — match symptom to update (Vicinity = proximity issue; Helpful Content = thin pages; Spam = name/citations)
3. **Remediation** — fix per update type
4. **Indexing** — Google needs to re-crawl and re-evaluate (1-4 weeks)
5. **Recovery** — ranking improvement (Vicinity 3-6 months; Helpful Content 2-4 months; Spam variable)
6. **Stabilization** — sustained at new equilibrium

Some hits never fully recover (some spam-flagged listings are permanently suppressed).

**Operator implication:** Set 6-month recovery expectations after major hits. Don't panic-rebuild during weeks 1-4 (that confuses Google further). Steady remediation + monitoring.

## 13. The Citations Asymmetry (Whitespark 2026 LSRF)

Citations dropped in importance for traditional local pack rankings. But they re-rose for **AI search visibility** — LLMs lean on the broader web (industry directories, BBB, Chambers of Commerce, Facebook, LinkedIn) to identify prominent businesses.

**Operator implication:** Stop investing in mass-citation services beyond ~30 quality citations (diminishing returns). Do invest in industry-specific top-tier citations. AI search visibility = citation breadth on quality sites.

## 14. The Best-Of-List Anchor (Darren Shaw, 2026 LSRF AI section)

Expert-curated "best of" lists are the highest-impact AI search visibility signal. LLMs latch onto these because they're hard to manipulate (you can't just ask to be added). Examples: "Best [Service] in [City]" articles by industry publications, local press "Top 10" features, professional association recommendations.

**Operator implication:** Allocate marketing time to earning these placements (not paying for them — paid inclusions like Forbes lose AI weight). PR, sponsorships, community awards, industry publication outreach. 12-18 month investment horizon.

## 15. The Engagement-As-Rank Loop

GBP engagement (clicks, photo views, post reads, review reads, dwell time) is now a ranking signal — confirmed by 2026 LSRF and indirectly via DOJ trial revelations of Google's NavBoost system.

**Operator implication:** Make the GBP "sticky":
- Multiple high-quality photos updated weekly
- Posts updated weekly
- Video added (highly engaging)
- Review velocity sustained (drives review-reading engagement)
- Product/service descriptions rich enough to scroll

Engagement → ranking → more engagement. Operators who set up GBP and abandon it lose to those who maintain it actively.
