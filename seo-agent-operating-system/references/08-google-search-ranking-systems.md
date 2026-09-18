# Google Search Ranking Systems and Algorithm Update Controls
## Purpose
Use this file as the operating reference for Google Search ranking systems, major algorithm-update classes, spam systems, and the SEO/content actions that follow from them.
Do not treat this as a reverse-engineered ranking formula. Google does not publish every signal, weight, classifier, or experiment. This file covers the notable systems and update classes Google publicly documents, plus the practical controls the SEO/content workflow should apply.
## Contents
- Source-of-truth rule
- Active/notable Google ranking systems
- Retired/integrated systems
- Core, spam, Discover, and reviews updates
- SEO/content controls by system
- Practices that are not standalone algorithms
- Algorithm-change diagnosis workflow
- Output record
## Source-of-truth rule
For current behavior, prefer:
1. Google Search Central ranking-systems documentation
2. Google Search Status Dashboard ranking-update history
3. Google Search Essentials and spam policies
4. Google Search Central core-update guidance
5. Google Search Central people-first and generative-AI guidance
Revalidate these sources before making time-sensitive claims because Google continuously changes ranking systems.
## Active/notable ranking systems documented by Google
### BERT
Purpose: Understand how combinations of words express meaning and intent.
SEO/content controls:
- Write naturally for the user's intent.
- Do not force exact-match phrasing where a clearer synonym/explanation is better.
- Cover the concept and context, not only the literal query string.
- Validate intent in the live SERP before creating or optimizing a page.
### Crisis information systems
Purpose: Surface timely, trusted information during personal or widespread crises.
SEO/content controls:
- Use authoritative, current sources for crisis/safety topics.
- Avoid sensational or unsupported emergency claims.
- Treat health, safety, legal, financial, or public-welfare content as high-risk and require stronger evidence/human review.
### Deduplication systems
Purpose: Reduce repeated/near-identical results and avoid showing unnecessary duplicate listings.
SEO/content controls:
- Avoid creating multiple pages with substantially the same intent and value.
- Consolidate or differentiate overlapping pages.
- Use canonicals correctly for legitimate duplicates.
- Check cannibalization before approving new content.
### Exact match domain system
Purpose: Prevent domains that exactly match a query from receiving excessive credit merely because of the domain name.
SEO/content controls:
- Never select or recommend a domain solely for keyword-match benefit.
- Judge pages on usefulness, relevance, authority, technical health, and business fit.
### Freshness systems
Purpose: Surface fresher results when the query deserves freshness.
SEO/content controls:
- Determine whether freshness is part of intent before updating content.
- Update facts, dates, screenshots, pricing, regulations, statistics, or examples only when meaningfully changed.
- Do not change dates to make unchanged content look fresh.
- Monitor time-sensitive topics more frequently.
### Link analysis systems and PageRank
Purpose: Use links and relationships among pages as signals to understand pages and helpfulness; PageRank remains part of core ranking systems.
SEO/content controls:
- Prioritize relevant, editorially useful links rather than volume.
- Maintain strong internal linking to important pages.
- Avoid paid/manipulative link patterns, excessive exact-match anchors, link schemes, and mass low-quality placements.
- Treat third-party authority metrics as estimates, not PageRank.
### Local news systems
Purpose: Identify and surface local sources when local news is relevant.
SEO/content controls:
- Use accurate local entities, locations, dates, authorship, and first-hand/local reporting when relevant.
- Do not manufacture location pages or local claims solely for ranking coverage.
### MUM
Purpose: AI system used for specific Search applications; Google states it is not currently used for general ranking.
SEO/content controls:
- Do not build a separate “MUM optimization” checklist.
- Follow entity clarity, useful multimodal content, accurate sourcing, and general SEO best practices.
### Neural matching
Purpose: Match concepts in queries with concepts in pages even when wording differs.
SEO/content controls:
- Build semantically complete topic coverage.
- Use natural language, related concepts, examples, and entities where genuinely relevant.
- Do not create pages for every keyword variation.
### Original content systems
Purpose: Surface original content, including original reporting, ahead of pages that merely repeat/cite it.
SEO/content controls:
- Require information gain: first-hand experience, original research, proprietary data, expert analysis, examples, or a distinct framework.
- Credit original sources when referencing external work.
- Use canonicalization for legitimate duplicate/syndicated versions.
- Avoid derivative rewrites that add little value.
### Removal-based demotion systems
Purpose: Use high volumes of certain valid removal actions as signals that can affect other content from a site.
SEO/content controls:
- Maintain copyright, privacy, safety, and legal-content governance.
- Escalate patterns of removals/complaints rather than treating them as isolated SEO issues.
### Passage ranking system
Purpose: Understand individual passages/sections of a page to assess relevance.
SEO/content controls:
- Use clear sections/headings for readers.
- Answer subquestions directly where relevant.
- Do not “chunk” content artificially into tiny sections only for algorithms.
- Keep each section coherent and useful in the context of the whole page.
### RankBrain
Purpose: Understand relationships between words and concepts so relevant content can rank without containing every exact query term.
SEO/content controls:
- Optimize for intent and concept coverage.
- Avoid keyword stuffing and exact-match repetition.
- Prefer useful examples, definitions, comparisons, and context over density targets.
### Reliable information systems
Purpose: Surface more reliable/authoritative information and apply additional quality handling where information quality is uncertain.
SEO/content controls:
- Match evidence strength to claim risk.
- Use primary/authoritative sources for material factual claims.
- Make authorship, expertise, evidence, update dates, and limitations clear where useful.
- Apply stronger review to YMYL/high-impact subjects.
### Reviews system
Purpose: Reward high-quality reviews with insightful analysis, original research, and demonstrated expertise/experience.
SEO/content controls:
- Show first-hand evidence/testing where applicable.
- Explain methodology, pros/cons, comparisons, decision criteria, and who a product/service is for.
- Do not publish manufacturer-description rewrites as “reviews”.
- Disclose incentives/relationships as required.
### Site diversity system
Purpose: Reduce excessive domination of top results by one site for many queries.
SEO/content controls:
- Do not assume publishing many similar pages will occupy multiple top positions.
- Differentiate pages by real user intent and business purpose.
### Spam detection systems / SpamBrain
Purpose: Detect content and behaviors violating Google spam policies.
SEO/content controls:
- Apply Google spam-policy checks before publishing or off-page execution.
- Reject scaled content created mainly to manipulate rankings or generative AI responses.
- Reject cloaking, doorway abuse, hidden-text/link abuse, scraping without value, link spam, user-generated spam, expired-domain abuse, site-reputation abuse, and policy circumvention.
- Paid/exchanged links require appropriate qualification, disclosure/rel handling where applicable, and human approval under team policy.
## Retired or integrated named systems
These names remain useful historically but should not be treated as separate current optimization algorithms.
### Helpful content system
Status: Retired as a standalone system; integrated into Google's core ranking systems in March 2024.
Take care:
- Create helpful, reliable, people-first content.
- Provide original value and satisfying answers.
- Avoid mass production, search-engine-first pages, arbitrary word-count targets, fake freshness, and low-value summaries.
### Hummingbird
Status: Historical major ranking-system improvement from 2013.
Take care:
- Focus on meaning, intent, and topic relevance rather than literal keyword matching.
### Panda
Status: Historical quality system; became part of core ranking systems.
Take care:
- Avoid thin, duplicate, low-effort, low-originality, or mass-produced content.
- Improve site-wide quality rather than trying to “fix a Panda score”.
### Penguin
Status: Historical link-spam system; integrated into core ranking systems.
Take care:
- Avoid manipulative links and anchors.
- Evaluate link relevance, editorial value, traffic/audience fit, and spam risk before authority metrics.
## Ranking-update classes
### Core updates
Core updates are broad changes to Google's ranking systems, not penalties aimed at one site.
When a core update overlaps a traffic/ranking change:
1. Confirm the update start/end on the Search Status Dashboard.
2. Wait until rollout is complete; for analysis use a stable post-update comparison window.
3. Compare affected queries/pages/search types in Search Console.
4. Separate small normal movements from large sustained drops.
5. For large drops, assess the whole site and the most-affected pages against helpful/reliable/people-first quality.
6. Avoid reactive “quick fixes” based on rumors.
7. Make durable improvements to usefulness, evidence, structure, originality, UX, and technical eligibility.
8. Record that correlation with an update is not proof of a specific cause.
### Spam updates
When a spam update overlaps a loss:
- Review Search Console Manual Actions/Security issues.
- Review current Google spam policies.
- Inspect scaled content, link acquisition, third-party content, expired domains, redirects/cloaking, scraping, and UGC abuse.
- Correct the underlying practice rather than trying to “recover the old signal”.
### Discover updates
When Discover performance changes:
- Separate Discover from Web Search performance.
- Review freshness, image quality, headline accuracy, topic/audience fit, policy compliance, and overall content quality.
- Do not assume Discover traffic is stable or guaranteed.
### Reviews updates / reviews system changes
For review-heavy sites/pages:
- Audit evidence of first-hand experience/testing.
- Improve comparative analysis, methodology, original media/data, and expert explanation.
- Remove thin affiliate/review content with no additional value.
## Not standalone ranking algorithms
Do not teach the agent that the following are single algorithms or direct scores:
- E-E-A-T: concept/framework reflected through multiple signals; not one ranking factor.
- Search Quality Rater scores: used to evaluate systems, not direct page-ranking inputs.
- DA/DR/PA/Authority Score: third-party metrics, not Google metrics.
- Core Web Vitals/Page experience: useful quality/experience inputs, not the whole ranking system.
- AI detector scores: not Google ranking metrics.
- “Content score” from SEO tools: workflow guidance only.
- llms.txt: Google states it neither helps nor harms Google Search visibility/rankings.
## SEO/content pre-publication algorithm check
Before approving SEO content, confirm:
- Clear user/search intent
- Helpful answer and satisfying depth
- Original information/value beyond commodity summaries
- Evidence appropriate to claim risk
- Accurate authorship/brand/entity context
- No duplicate/cannibalizing page without a reason
- Natural topic/keyword use; no stuffing
- Useful internal links
- External citations where material facts need support
- Crawl/index/snippet eligibility for search-targeted pages
- Good page experience and usable mobile rendering
- No spam-policy conflict
- No manipulative scaled-content pattern
- No deceptive freshness/date changes
- Correct structured data only where applicable
## Algorithm-change diagnosis workflow
Use:
`Search Status Dashboard -> Search Console comparison -> technical/index checks -> spam/manual-action checks -> intent/SERP change -> content-quality review -> backlink/link-pattern review -> market/seasonality check -> decision`
Possible decisions:
- `NORMAL_VOLATILITY`
- `ALGORITHM_UPDATE_CORRELATION`
- `CORE_QUALITY_REVIEW_REQUIRED`
- `SPAM_POLICY_REVIEW_REQUIRED`
- `TECHNICAL_CAUSE_LIKELY`
- `INTENT_OR_SERP_SHIFT`
- `DEMAND_OR_SEASONALITY_SHIFT`
- `MULTIFACTOR_DIAGNOSIS_REQUIRED`
- `NEEDS_HUMAN_REVIEW`
Never claim an algorithm caused a loss merely because dates overlap.
## Official references
- https://developers.google.com/search/docs/appearance/ranking-systems-guide
- https://developers.google.com/search/docs/appearance/core-updates
- https://developers.google.com/search/docs/essentials/spam-policies
- https://developers.google.com/search/docs/fundamentals/creating-helpful-content
- https://developers.google.com/search/docs/fundamentals/using-gen-ai-content
- https://status.search.google.com/products/rGHU1u87FJnkP6W2GwMi/history
## Output record
When a ranking-system/update consideration affects a recommendation, record:
- System/update class
- Official-source check date
- Affected property/URL/query group
- Observed change and date range
- Search type/device/country
- Evidence
- Alternative explanations checked
- SEO/content risk
- Recommended action
- Confidence
- Human-review status
