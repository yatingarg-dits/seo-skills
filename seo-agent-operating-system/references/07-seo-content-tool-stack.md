# SEO and Content Tool Stack

## Purpose

Maintain the approved SEO, analytics, technical, backlink, content, social, publishing, and validation tools used by the team.

Use this file as the central tool-control layer. Other workflow files should reference this file for tool selection instead of creating independent tool lists.

## System companions

Use [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md) when tool findings are being interpreted against Google ranking/core/spam systems. Use [09-ai-llm-discovery-visibility.md](09-ai-llm-discovery-visibility.md) when tools are used to test AI/LLM discovery, citations, crawlers, or referrals.

## Tool-use rules

1. Select a tool by task and evidence need; do not create one universal "best tool".
2. Prefer first-party property data for actual performance: Google Search Console, Google Analytics, Bing Webmaster Tools, and configured platform analytics.
3. Treat Ahrefs, Semrush, Moz, Similarweb, SEOquake, SEOptimer/SEO audit tools, and other third-party metrics as provider-specific estimates/signals.
4. Store tool/provider, metric name, geography, date range, and checked date with material data.
5. Do not average differently defined authority, difficulty, traffic, or visibility metrics.
6. Tool severity/score never replaces SEO, content, business, or human judgment.
7. AI-detection scores are probabilistic warning signals, not proof that a person or AI wrote content.
8. Content optimization scores are guidance, not targets that justify keyword stuffing or competitor imitation.
9. Paid backlink/guest-post tools are discovery/execution sources only; every domain still needs qualification and commercial approval.
10. Revalidate product availability, plan limits, APIs, and features before automating a tool.

## SEO, analytics, technical, backlink, and social tools

### Google Analytics (GA4)
- Does: Measures website/app sessions, users, acquisition, engagement, events, key events/conversions, landing-page behavior, and downstream business performance.
- Process: Verify property/tag -> confirm events/conversions -> segment Organic Search or required channel -> review landing pages/journeys -> compare periods -> connect SEO/content change to user/conversion behavior -> record date range and filters.
- Use for: Traffic/conversion outcome evidence. Do not use GA4 as the source of Google query/ranking data.

### Google Search Console
- Does: Provides first-party Google Search clicks, impressions, CTR, average position, queries/pages, indexation signals, URL Inspection, sitemaps, and search issues.
- Process: Verify property -> Performance analysis -> query/page/country/device analysis -> Pages/Indexing review -> URL Inspection for priority URLs -> sitemap checks -> export evidence -> route issue to keyword/content/technical workflow.
- Use for: Primary evidence of actual Google organic property performance.

### Ahrefs
- Does: Keyword research, competitor research, backlink analysis, Site Audit, rank tracking, content research, content gaps, and link prospecting.
- Process: Select correct country/index -> Site Explorer for domain/pages/backlinks -> Keywords Explorer for demand/KD/topic ideas -> Site Audit for technical issues -> Content/Gap/Intersect as needed -> Rank Tracker for monitoring -> export source/date.
- Use for: Third-party research and discovery. Keep DR/KD/traffic estimates labelled as Ahrefs metrics.

### Semrush
- Does: Keyword research, competitor analysis, Site Audit, backlink research, position tracking, content research/optimization, and broader search/AI visibility workflows.
- Process: Create/select project -> Domain/Organic research -> Keyword Magic/Gap -> Site Audit -> Backlink Analytics/Audit -> Position Tracking -> Content tools where relevant -> validate important recommendations against live SERP/first-party data.
- Use for: Cross-functional SEO research and monitoring. Keep Semrush metrics provider-labelled.

### Google Trends
- Does: Shows relative search interest over time, geography, related topics/queries, and trending demand.
- Process: Compare search terms/topics -> set geography/time/category/search type -> review trend direction/seasonality -> inspect regions and related queries -> export/capture observation -> combine with volume/performance evidence.
- Use for: Trend/seasonality evidence, not absolute search volume.

### Screaming Frog SEO Spider
- Does: Crawls sites for response codes, redirects, indexability, canonicals, metadata, headings, duplicates, directives, links, images, structured data, and custom extraction.
- Process: Configure crawl scope/user-agent/rendering -> crawl -> review status/indexability -> canonicals/directives -> titles/H1/content -> internal links/orphans -> images/schema as needed -> export issue sets -> prioritize outside the tool.
- Use for: Primary crawl/audit support. Do not copy the tool's issue severity directly into business priority.

### PageSpeed Insights / Lighthouse
- Does: Evaluates page performance and Core Web Vitals using available field and lab data and provides diagnostics.
- Process: Test representative URL on mobile/desktop -> separate field vs lab findings -> inspect LCP/INP/CLS and diagnostics -> identify template/resource/root cause -> implement -> retest -> monitor field data when available.
- Use for: Performance diagnosis. Do not optimize only for the headline score.

### Microsoft Clarity
- Does: Session recordings, click/scroll heatmaps, behavioral insights, and user-friction analysis.
- Process: Install/verify Clarity tag (direct or GTM) -> collect sufficient sessions -> filter by landing page/device/source/campaign -> inspect heatmaps and recordings -> identify friction -> validate impact with GA4/conversion data -> create UX/content recommendation.
- Use for: Behavioral evidence explaining what users do after landing.

### Similarweb
- Does: Estimates competitor traffic, channel mix, geographies, search keywords, referrals, engagement, and market/competitive patterns.
- Process: Enter competitor/domain -> select market/timeframe -> compare traffic/channel mix -> inspect search/referrals/geographies -> identify opportunities -> validate critical findings through first-party/live sources where possible.
- Use for: Competitive intelligence; treat figures as estimates.

### SEOquake
- Does: Browser-based on-page/SERP inspection, page diagnosis, keyword analysis, internal/external link examination, and quick domain/URL comparison.
- Process: Open target page/SERP -> run Diagnosis/SEObar/SERP overlay -> inspect metadata/headings/links/parameters -> export useful observations -> verify important issues with crawl/source data.
- Use for: Fast manual screening, not a replacement for a full crawl/audit.

### Google Keyword Planner
- Does: Generates keyword ideas and Google Ads metrics such as average monthly searches, advertiser competition, and bid ranges.
- Process: Set account/market/language -> seed with keywords/URL -> discover ideas -> filter business relevance/intent -> collect volume/competition/bids -> export -> combine with organic SERP/KD evidence for SEO decisions.
- Use for: Paid planning and demand support. `Competition` means advertiser competition, not organic SEO difficulty.

### Moz Pro
- Does: Keyword research, Link Explorer, Domain Authority, Page Authority, Spam Score, rank tracking, and site-crawl support.
- Process: Analyze domain/page -> collect DA/PA/Spam Score with date -> Link Explorer for referring domains/anchors -> Keyword Explorer when needed -> use crawl/ranking features as supporting data -> apply team qualification rules.
- Use for: Provider-specific link/authority signals; never approve/reject a site from one Moz metric alone.

### Yoast SEO
- Does: WordPress SEO plugin for titles/meta, content/readability checks, XML sitemaps, schema framework, index controls, and internal-link assistance depending on plan.
- Process: Configure site representation/index settings -> verify sitemap/schema -> edit page title/meta/social data -> review SEO/readability suggestions -> validate against brief/intent -> publish -> verify live metadata/schema/indexability.
- Use for: WordPress implementation support. Yoast recommendations are not search-engine rules.

### Bing Webmaster Tools
- Does: Bing search performance, keyword research, Site Scan, URL/site exploration, backlinks, sitemaps, URL submission/IndexNow-related workflows, and SEO recommendations.
- Process: Verify site -> connect/import where approved -> review Search Performance -> inspect Site Explorer/Site Scan -> keyword/backlink research as needed -> submit/monitor sitemap/URLs -> record Bing-specific evidence.
- Use for: First-party Bing data and supplementary technical/backlink discovery.

### Google Tag Manager
- Does: Manages analytics/marketing tags, triggers, variables, and event deployment without direct code releases for every change.
- Process: Define tracking requirement -> build tag/trigger/variables -> Preview/Debug -> verify events/parameters and consent behavior -> publish version -> verify in GA4/target platform -> document container version.
- Use for: Measurement implementation, not analysis by itself.

### Rich Results Test
- Does: Tests whether supported structured data can be read for Google rich-result eligibility and shows relevant errors/warnings.
- Process: Test URL/code -> inspect detected rich-result types -> fix implementation/data issues -> retest -> deploy -> test live URL.
- Use for: Google rich-result validation; it does not validate every Schema.org vocabulary rule.

### Schema.org Markup Validator
- Does: Validates Schema.org structured data syntax/graph across JSON-LD, Microdata, and RDFa.
- Process: Enter URL/code -> inspect extracted entities/properties -> fix syntax/relationship issues -> retest -> separately use Rich Results Test for Google-specific eligibility where relevant.
- Use for: General Schema.org validation.

### Google Mobile-Friendly Test
- Status: `RETIRED` since December 2023.
- Process: Do not use for new work. Replace with responsive/manual mobile QA, Lighthouse/PageSpeed Insights, crawl/render checks, and other current mobile diagnostics.
- Use for: Historical reference only.

### SEOOptimizer
- Status: `EXACT_PROVIDER_NEEDS_CONFIRMATION` because multiple products use similar names.
- Process: Until the team records the exact vendor/URL, use only as a manual supporting optimizer/audit: enter URL/focus topic -> review prioritized suggestions -> verify against crawl/SERP/property evidence -> approve only justified changes.
- Use for: Supporting recommendations only; do not automate based on an unidentified product.

### SEOmator
- Does: Automated SEO auditing across technical, on-page, content, links, performance, structured data, mobile, and related checks.
- Process: Enter site/page -> run audit -> review failed checks by category -> confirm material issues with primary/crawl evidence -> prioritize -> fix -> rerun audit.
- Use for: Secondary audit/checklist support.

### Schema Markup Generator
- Does: Generates JSON-LD/schema templates from supplied entity/page data.
- Process: Choose correct schema type -> enter only verified facts -> generate JSON-LD -> review relationships/URLs -> validate with Schema.org Validator -> test eligible types with Rich Results Test -> implement -> retest live page.
- Use for: Faster markup creation. The generator does not decide which schema is appropriate.

### GuestPostLinks
- Does: Paid guest-post/link-placement discovery/service for publisher opportunities.
- Process: Search/filter opportunities -> capture candidate domain/URL/niche/price/claims -> route through historical check and backlink qualification -> classify as paid/commercial -> require configured human approval -> place/order/outreach -> verify live URL/anchor/rel/indexability -> update history/feedback.
- Use for: Paid discovery/execution only. Never trust marketplace metrics or pay before qualification/approval.

### Buffer
- Does: Plans, drafts, approves, schedules/publishes, and analyzes social-media content across supported channels.
- Process: Connect approved channels -> define calendar/tags -> create/adapt post per network -> internal approval when required -> schedule/publish -> verify post -> review Buffer Insights and native platform metrics -> feed learning back to content planning.
- Use for: Social publishing/monitoring. Prefer current `Insights` analytics rather than legacy workflows.

## Writing, research, and content tools

### Grammarly
- Does: Grammar, spelling, clarity, tone, style, and optional plagiarism/AI-related review depending on plan.
- Process: Run after substantive draft -> review suggestions selectively -> preserve client terminology/meaning -> recheck factual claims after rewrites -> final proofreading.
- Use for: Language QA, not factual validation or SEO strategy.

### QuillBot
- Does: Paraphrasing, grammar checking, summarization, and related writing assistance.
- Process: Use only on approved/source-backed text -> paraphrase/summarize -> compare against original meaning -> restore citations/qualifiers -> revalidate claims and tone.
- Use for: Controlled rewriting. Do not use to disguise copied content or manufacture originality.

### ZeroGPT
- Does: Provides AI-text detection and related writing-analysis utilities.
- Process: Run only as an optional QA signal -> record flagged sections -> manually inspect for generic/repetitive/unsupported writing -> revise based on quality issues, not solely on detector percentage.
- Use for: `WARNING` signal only. Never treat an AI-detection score as proof of authorship.

### ChatGPT
- Does: Supports research planning, source synthesis, ideation, briefs, outlining, drafting, rewriting, validation assistance, and structured analysis when provided with the required context/evidence.
- Process: Load client/property/rule context -> define audience/objective/intent -> research with sources when facts are needed -> generate options/brief/draft -> validate evidence/brand/SEO -> human review where configured -> preserve audit trail.
- Use for: Agentic research/content assistance; never use generated claims as evidence without verification.

### Hemingway Editor
- Does: Readability/style review, highlighting hard-to-read sentences and language that reduces clarity.
- Process: Paste final/substantive draft -> review readability and sentence issues -> simplify only when it improves the intended audience experience -> preserve technical accuracy/brand voice -> reread manually.
- Use for: Clarity/readability, not SEO or factual correctness.

### Surfer SEO
- Does: SERP-based keyword/content research, Content Editor guidance, topical/content optimization, content auditing, and internal-link/coverage assistance.
- Process: Set target keyword/location -> review selected SERP competitors -> inspect terms/topics/gaps -> use guidance while writing/updating -> reject irrelevant recommendations -> audit live page -> monitor impact separately in GSC/GA4.
- Use for: Content optimization support. Do not chase Content Score by inserting unnatural terms.

### Frase
- Does: SERP/content research, content briefs/outlines, question/topic extraction, drafting, and optimization support.
- Process: Set query/market -> inspect ranking-page research -> create/edit brief -> define unique angle/evidence needs -> draft -> validate against live SERP and client rules -> do not copy competitor headings blindly.
- Use for: Briefing/research acceleration, not final strategy authority.

### BuzzSumo
- Does: Content research, trending/evergreen topic discovery, competitor content analysis, social-engagement research, questions, mentions, backlinks, and alerts.
- Process: Search topic/domain -> choose timeframe/market -> inspect top content/formats/questions/trends -> compare competitors -> extract ideas/gaps -> validate business/search relevance -> feed topic research/PR/outreach workflows.
- Use for: Content/market intelligence and idea discovery.

### AnswerThePublic
- Does: Surfaces search-question and query patterns around a seed topic for audience/problem discovery and content ideation.
- Process: Enter seed -> choose market/language where available -> group questions/prepositions/comparisons -> map to intent/cluster -> validate important queries with keyword/SERP data -> use as questions/subtopics.
- Use for: Ideation/coverage discovery, not standalone demand or priority proof.

### Copyscape
- Does: Checks web content for duplicate/copied text and plagiarism-like matches.
- Process: Check draft/live URL -> inspect matched passages and original sources -> distinguish legitimate quotations/common language from copying -> rewrite or cite where needed -> rerun when required.
- Use for: Duplication/plagiarism screening; originality still requires useful information gain.

### Canva
- Does: Creates and edits social graphics, infographics, presentations, PDFs, simple video/visual assets, and collaborative creative content.
- Process: Select approved brand template -> apply brand assets -> create visual from approved content/data -> verify facts/numbers/rights/accessibility -> stakeholder approval -> export/publish through the relevant workflow.
- Use for: Visual production, not factual/source validation.

## Tool routing by activity

| Activity | Primary tools | Supporting tools |
| --- | --- | --- |
| Organic performance | Search Console | GA4, Bing Webmaster Tools |
| Conversion/user behavior | GA4 | Clarity |
| Keyword research | Search Console, Keyword Planner, Ahrefs, Semrush | Trends, Moz, Similarweb, AnswerThePublic |
| Competitor/market research | Ahrefs, Semrush, Similarweb | SEOquake, BuzzSumo |
| Technical audit | Screaming Frog | Ahrefs/Semrush audits, SEOmator, SEOquake, Bing Site Scan |
| Performance/mobile | PageSpeed Insights/Lighthouse | Screaming Frog rendering, Clarity, manual responsive QA |
| Schema | Schema Generator + Schema.org Validator | Rich Results Test, Yoast |
| Backlinks | Ahrefs, Semrush, Moz | Bing Backlinks, GuestPostLinks after qualification |
| Content research/brief | Live SERP + first-party/client sources | ChatGPT, Ahrefs, Semrush, BuzzSumo, AnswerThePublic, Frase |
| Content drafting/editing | ChatGPT/manual writing | Grammarly, Hemingway, QuillBot |
| Content optimization | Human brief + live SERP | Surfer, Semrush Content, Yoast, Frase |
| Originality/AI quality | Human/content validator | Copyscape, ZeroGPT as warning only, Grammarly |
| Social publishing | Buffer | Canva, native platforms |
| WordPress publishing | CMS + approved workflow | Yoast |
| Measurement implementation | Google Tag Manager | GA4, Clarity |
| Indexation/search monitoring | Search Console, Bing Webmaster Tools | Ahrefs/Semrush rank tracking |

## Output requirement

Whenever a tool materially affects a decision, record:

`tool/provider + feature/report + property/domain + market/device + date range + checked date + metric/finding + limitation + decision + next action`
