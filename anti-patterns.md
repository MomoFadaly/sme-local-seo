# Anti-Patterns — Local SEO

Numbered failures. Each anti-pattern has the symptom, the cause, and the correction. Drawn from Sterling Sky's live audit corpus, Whitespark's analysis, and Darren Shaw's case studies.

## 1. The Umbrella-Category Mistake

**Symptom:** Business invisible for the queries customers actually search.

**Cause:** Primary GBP category set too broadly ("law firm" instead of "personal injury attorney"; "HVAC contractor" instead of "furnace repair"). Google filters businesses out of eligible results when their primary category doesn't match the query, even if all other factors are strong.

**Correction:** Change primary category to the most specific available option that matches your highest-intent service. For multi-service businesses, pick the highest-revenue service as primary. Test category change for 2-4 weeks, then reassess.

## 2. The GBP-Name-Stuffing Suspension

**Symptom:** GBP suspended (hard or soft); rankings vaporize overnight.

**Cause:** Adding keywords directly to GBP business name ("<City> Pest Control LLC" when the legal entity is "Acme Pest Inc"). Google's 2024-2026 spam updates aggressively target this; auto-detection now catches keyword-stuffed names.

**Correction:** Either accept the legal name as-is, OR formally rebrand: change business registry → bank statements → signage → website → all citations → THEN update GBP last. Stuffing the GBP directly without legal-entity changes is the trap.

## 3. The Quarterly Review Blast

**Symptom:** Reviews disappear shortly after publishing; "review manipulation" warning surfaces.

**Cause:** Sending mass review-request emails to past customers in quarterly batches (e.g., 100 review requests in 24 hours). Google's spike-detection flags the unusual velocity pattern; legitimate reviews get filtered out alongside potential manipulation.

**Correction:** Sustainable cadence — 1-3 reviews/week steady. Branded-search-prompt path (not direct review links). Engagement-first (reviewer interacts with GBP before reviewing). Spread requests over months, not days.

## 4. The Direct-Review-Link Trap

**Symptom:** Reviews submitted by happy customers don't publish or disappear days later.

**Cause:** Using Google's provided review link or QR code. These bypass GBP engagement; Google detects "review-without-prior-engagement" pattern and filters.

**Correction:** Send branded-search prompt: "Search '<your business> <city>' on Google, click on our profile, then leave a review." This forces engagement (Google sees clicks/calls before review submission) → review sticks.

## 5. The Regis / Virtual-Office Suspension

**Symptom:** Newly-created GBP at office location gets suspended within days, won't reinstate.

**Cause:** Office at Regis-brand virtual location, or other coworking space on Google's heightened-flag list. Regis is specifically flagged at near-100% suspension rate.

**Correction:** Don't use Regis or similar virtual offices for GBP. Get a real staffed office, OR run as a service-area business with hidden address. Reinstating from a Regis-flagged suspension is essentially impossible.

## 6. The Shared-Address Cannibalization

**Symptom:** Two of your business locations at the same address — one ranks, the other is invisible.

**Cause:** Local filter (Possum-era) suppresses similar businesses at the same address sharing primary category. Google picks the stronger one; the weaker is hidden.

**Correction:** Distinct addresses required for each location. If sharing address, ensure: distinct entrances, distinct external signage, distinct phone numbers, distinct services (not overlapping categories). Even with all these, filter risk persists.

## 7. The Address-Hide Ranking Crash

**Symptom:** SAB hides address per Google guidelines; rankings drop to zero or relocate to another city entirely.

**Cause:** Google's pin-placement behavior when address is hidden. Pin reverts to original verification address (often wrong city) OR Google's pin-placement bug puts pin in random locations. This is documented but not officially acknowledged.

**Correction:** When required to hide address, expect 2-8 weeks of ranking volatility. Use grid-rank to identify where Google has placed your pin. File pin-correction request via Google Maps if pin is misplaced. Plan for the volatility before triggering the change.

## 8. The Cross-State Move Suspension

**Symptom:** Successfully moved business to new state, video verification passed, then suspension hit days later — appeal fails.

**Cause:** Business not legally registered in new state. Google requires government-body proof of new-state eligibility (LLC registration, business license) before reinstating after a state move.

**Correction:** Register LLC in new state BEFORE updating GBP address. Update website + citations + signage to new address before GBP. Have proof ready (LLC docs, utility bill at new address) for potential appeal.

## 9. The Account-Level Cascade

**Symptom:** Multiple GBP listings owned by one user account all suspended on the same day.

**Cause:** Account-level restriction. Often triggered by: email spam-flag (mass marketing emails from same Gmail), suspicious account behavior, or one bad listing tainting all listings owned by that account.

**Correction:** Domain-email Google Workspace account, not random Gmail. Use Agency Dashboard for managing multiple listings. If hit by account-level suspension, may need to remove the user from listings + transfer ownership before reinstating.

## 10. The Third-Party-Tool Listing Deletion

**Symptom:** GBP listing vanishes entirely (not suspended — gone). Google support says they can't help.

**Cause:** Third-party tool using GBP API performed a delete operation (often accidentally — clicking "remove from tool" deletes the listing entirely, not just disconnects it). Common with citation tools, review-management tools, agency dashboards.

**Correction:** Contact Google support persistently — they CAN restore deleted listings despite what front-line support says. Escalate to Google Business Profile Community if support refuses. Audit third-party tool integrations carefully. Don't grant GBP API access casually.

## 11. The Template-Spun Service-Area Pages

**Symptom:** Service-area pages for outer cities don't rank, may have triggered Helpful Content penalty.

**Cause:** City pages built by duplicating service page and swapping city name. No real local context. Google's Helpful Content system identifies template-duplicate content as "low-quality" and applies site-wide signal.

**Correction:** Each city page must have: unique photos from that area, real team or project examples for that city, local landmarks/neighborhoods mentioned, distinct testimonials per city. AI-drafted content is fine but must be augmented with real local depth.

## 12. The Owner-Response-As-Ranking Misallocation

**Symptom:** Operator spends hours weekly on owner responses expecting ranking lift; rankings don't move.

**Cause:** Traditional view (LSRF) ranks owner responses as conversion signal, not ranking signal. The work is justified by other reasons.

**Correction:** Continue responding (it matters for AI search visibility — LLMs read responses for entity understanding — and for conversion). But don't expect direct local pack ranking lift. Allocate hours accordingly.

## 13. The Inconsistent NAP From Call Tracking

**Symptom:** GBP rankings drop after implementing call tracking. Citations show NAP variance across the web.

**Cause:** Call tracking software replaced primary phone with tracked numbers, both on website and on citations. Now Google sees inconsistent NAP across the web — flagged as low-trust signal.

**Correction:** Use Dynamic Number Insertion (DNI) on website only — DNI displays tracked numbers per session without changing the static phone Google sees. Or use Google's call tracking inside Maps (preserves NAP). Never change GBP phone for tracking purposes.

## 14. The Empty-Profile Set-And-Forget

**Symptom:** GBP set up properly years ago, never updated; rankings slowly decline over 12 months.

**Cause:** Engagement signals are now a major ranking factor. Profiles that don't get fresh photos, posts, services updates, attribute additions lose ground to actively-managed competitors.

**Correction:** Weekly photo upload, weekly post, monthly services-list audit, quarterly attribute review. 30 minutes a week beats 8-hour quarterly updates.

## 15. The Q&A Negligence

**Symptom:** GBP Q&A populated with competitor-posted misleading questions; no owner responses; converting users see negative content.

**Cause:** Operators don't monitor Q&A. Anyone can post questions. Competitors and trolls do.

**Correction:** Until full deprecation completes (ongoing 2025-2026), monitor Q&A weekly, answer all real questions truthfully, flag fake/misleading ones. Post-deprecation: pivot effort to website FAQ + Ask Maps optimization (substantive content + reviews).

## 16. The DBA-As-Listing Justification

**Symptom:** Tried to create second GBP using a DBA (doing-business-as) name — got suspended.

**Cause:** DBAs do not entitle a business to a separate GBP. Google requires separate legal business registrations for separate listings. Common confusion area.

**Correction:** If you genuinely operate as two distinct businesses with shared ownership: register them as separate legal entities with separate addresses and phones. Otherwise: one listing per legal business. DBAs can be mentioned in the description; they cannot anchor a separate listing.

## 17. The Satellite-Office Misnomer

**Symptom:** GBP at satellite office repeatedly suspended even after passing video verification.

**Cause:** Calling the location a "satellite office" on the website. Google reads "satellite office" as "virtual office" — not staffed, customers can't show up.

**Correction:** Don't call your secondary location a "satellite office" anywhere on the website. If it's truly staffed and customer-accessible, call it a "branch" or "second location" or just by the city name. If it's not staffed: you're not eligible for a separate GBP listing.

## 18. The Pin-Adversarial-Edit Vulnerability

**Symptom:** Rankings crashed overnight; investigation reveals pin moved to a desert / ocean / random field.

**Cause:** Competitor (or scammer) submitted "suggest an edit" to Google Maps moving the pin. Google often accepts these edits without owner notification.

**Correction:** Monitor pin placement weekly via Google Maps "edit profile" view. Whitespark sells $1/month profile-change-monitoring software. If pin moved: edit GBP and reset pin. Repeat as needed.

## 19. The Solo-Practitioner Confusion

**Symptom:** Insurance agent (State Farm, Allstate) listing repeatedly suspended; support agents say "you can't have State Farm in your name."

**Cause:** Google's solo-practitioner allowance (insurance agents, financial advisors, real estate agents) is real but front-line Google support agents don't understand it. They reject what guidelines actually allow.

**Correction:** Escalate to Google Business Profile Community. Product experts there know the solo-practitioner rules and can intervene. State Farm, Allstate, Edward Jones brand names ARE allowed in solo-practitioner business names — just not in keyword-stuffed positioning.

## 20. The Helpful-Content Reset After Recovery

**Symptom:** Rebuilt thin city pages with substantive content; ranking still suppressed months later.

**Cause:** Helpful Content is a site-wide signal; partial fixes don't always trigger reassessment. Google's reassessment happens at irregular intervals.

**Correction:** Patient. Continue adding substantive content. Audit ALL pages (not just the ones you suspect were thin). Consider noindex on hopeless legacy thin pages. 4-6 month recovery timeline; some sites take longer.

## 21. The Bing/Apple Skip

**Symptom:** Operator allocates marketing time to Bing Places and Apple Business Connect, sees minimal ROI.

**Cause:** Most local industries get <5% of search traffic from Bing; Apple Business Connect is growing but still small in 2026.

**Correction:** Set both up once correctly (NAP + categories + photos + hours). Don't iterate or invest weekly time. Focus 95% of local SEO effort on Google.

## 22. The LSA Rejection of Local SEO

**Symptom:** Operator decides "LSAs are easier — I'll skip local SEO." Lead volume drops as LSA bidding cap hits.

**Cause:** LSAs scale by spend; once you hit budget cap, no more leads. Local SEO scales by quality and is uncapped. LSA without local SEO underperforms LSA WITH local SEO (LSA pulls reviews from GBP; strong GBP improves LSA conversion).

**Correction:** Run both. LSA for immediate paid leads with controlled budget. Local SEO for sustainable growth and LSA quality lift.

## 23. The Aggregator-Outranks-Brand Surrender

**Symptom:** Yelp and BBB outrank your own website for branded queries ("<your brand> <city>"). Operator gives up on owning their brand search.

**Cause:** Your own site is under-optimized for branded queries. Aggregators have stronger SEO foundations.

**Correction:** Audit your branded-query optimization: title tag prominence of brand, schema with sameAs to social/aggregator profiles, internal links to brand-anchored pages, brand-anchor backlinks. Your site CAN outrank aggregators for your own brand — most don't because they neglect this.

## 24. The Hours-Misrepresentation Suspension

**Symptom:** GBP suspended for "deceptive content"; investigation reveals hours don't match actual operations.

**Cause:** Posting fictional hours to game the new "open at time of search" ranking factor. Customers arrive, find closed door, leave negative reviews. Google detects discrepancy from review content + operational signals.

**Correction:** Hours must accurately reflect actual operations. To capture the open-hours ranking signal: ACTUALLY extend hours (staff member late, weekend coverage, 24/7 call answering for SAB). For seasonal closures, use Google's "temporarily closed" feature — preserves rankings.

## 25. The Review-Filter-Recovery-Wait

**Symptom:** Reviews missing after suspension reinstatement; operator waits 6+ months expecting them to come back.

**Cause:** Reviews aren't deleted — they're disconnected. Google retains the data but doesn't re-attach to listings automatically.

**Correction:** Don't wait. Within 48 hours of reinstatement, if reviews haven't returned: contact Google support with screenshots of missing reviews. Escalate to product expert if support refuses. Sterling Sky has recovered reviews missing for 8+ months via product expert escalation. Time matters — earlier is easier.
