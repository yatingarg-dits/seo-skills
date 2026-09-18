# AI and LLM Discovery, Retrieval, Citation, and Visibility Controls
## Purpose
Use this file for website/content visibility in generative AI search, answer engines, LLM web search, retrieval-augmented generation, and citation-based experiences.
Do not claim to know proprietary model-ranking or citation algorithms. Most AI/LLM platforms do not publish a complete ranking formula. Work from documented crawler/index/retrieval behavior, source-quality principles, platform controls, and observed evidence.
## Contents
- Cross-platform principles
- Google AI Overviews and AI Mode
- ChatGPT Search
- Perplexity
- Microsoft Copilot / Bing-grounded experiences
- Claude web search
- Gemini/other LLM surfaces
- Technical crawler/control checks
- Content controls for AI visibility
- Measurement and monitoring
- Unsupported myths/hacks
- Output record
## Cross-platform operating principles
Prioritize:
1. Crawl/discovery eligibility where the platform documents it.
2. Search-engine/index eligibility where the AI product relies on search results.
3. Clear, accurate, well-structured, source-backed information.
4. Original information gain and first-hand/expert value.
5. Entity/brand/author consistency across the site and reputable external sources.
6. Freshness where the query requires current information.
7. Useful headings, tables, lists, definitions, examples, and direct answers when they improve the human experience.
8. High-quality images/video/data when relevant.
9. Transparent citations and primary-source evidence.
10. Monitoring actual referrals/citations rather than assuming visibility.
Do not build a separate low-quality “AI SEO” content farm.
## Google AI Overviews and AI Mode
Documented basis:
- Google states generative AI Search features are rooted in core Search ranking and quality systems.
- Google documents retrieval-augmented generation/grounding and query fan-out as techniques used by these experiences.
- Pages must meet Search technical requirements, be indexed, and be eligible to show with a snippet.
- Google says no special AI markup or llms.txt file is required for Google Search.
SEO/content process:
1. Apply [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md).
2. Ensure crawl/index/snippet eligibility.
3. Create non-commodity content with a distinct point of view, expertise, first-hand evidence, original data/research, or better synthesis.
4. Cover the user's broader information need rather than manufacturing a page for every fan-out query.
5. Add useful images/video and valid structured data where appropriate for normal Search features.
6. Avoid scaled content created to manipulate Search or generative AI responses.
7. Monitor Google Search generative-AI visibility through Search Console reports where available.
Google-specific non-requirements:
- No special schema is required for AI Overviews/AI Mode.
- No special “AI writing style” is required.
- No mandatory tiny “chunks” are required.
- llms.txt does not help or hurt Google Search according to Google.
## ChatGPT Search
Documented basis:
- Public websites can appear in ChatGPT Search.
- OpenAI says OAI-SearchBot access helps content be discovered, surfaced, cited, and linked.
- ChatGPT Search ranks results using multiple factors intended to surface relevant, reliable information; placement is not guaranteed.
- GPTBot controls potential training crawling and is separate from OAI-SearchBot search discovery.
- OpenAI referral links can be measured through `utm_source=chatgpt.com`.
Process:
1. Confirm important public pages are accessible to users.
2. Review `robots.txt`, CDN/WAF/bot rules, and server responses for OAI-SearchBot.
3. Do not confuse GPTBot training preferences with OAI-SearchBot search visibility.
4. Keep important facts, product/service details, author/entity information, and update dates clear and current.
5. Use primary sources, evidence, and unique information that is worth citing.
6. Track ChatGPT referral traffic separately in analytics.
7. Periodically test representative brand/non-brand questions and record whether the site is cited, linked, absent, or misrepresented.
Do not promise inclusion or a specific citation position.
## Perplexity
Documented basis:
- Perplexity describes search as using multiple web searches and synthesizing information from diverse/high-quality sources with citations.
- Perplexity provides robots/crawling guidance in its help resources, but it does not publish a complete publisher-ranking formula.
Process:
1. Maintain crawlable public pages and clean robots/CDN behavior based on current Perplexity guidance.
2. Publish primary, specific, current, and citation-worthy information.
3. Make claims easy to verify through clear source links/data/methodology.
4. Prefer original research, expert commentary, comparisons, and first-hand evidence over generic summaries.
5. Test representative queries and record citations/source position without assuming one test is stable.
6. Track referral traffic separately when identifiable.
## Microsoft Copilot and Bing-grounded experiences
Documented basis:
- Microsoft Copilot products can use Bing search services to ground responses in current web information.
- Bing ranking/search systems therefore remain important for public-web visibility in those experiences.
Process:
1. Apply Bing Webmaster guidelines and maintain Bing indexability.
2. Verify the site in Bing Webmaster Tools.
3. Maintain sitemaps and use IndexNow/URL submission where appropriate and approved.
4. Ensure important pages have discoverable internal links.
5. Optimize for relevance, quality, freshness when appropriate, and strong user value.
6. Diagnose Copilot visibility first as a Bing discovery/index/relevance problem unless Microsoft documents a separate publisher control.
7. Monitor Bing search performance plus identifiable Copilot referral/citation evidence.
Do not infer a separate Copilot ranking algorithm without official evidence.
## Claude web search
Documented basis:
- Anthropic's web-search tooling can retrieve current web content and provide cited sources.
- Anthropic publishes information about ClaudeBot for general-purpose/training crawling; that crawler should not automatically be treated as the ranking mechanism for Claude web-search citations.
- Anthropic does not publish a complete SEO/citation ranking formula for Claude web search.
Process:
1. Keep public content technically accessible through normal web/search discovery paths.
2. Maintain high-quality source-backed information that can support a cited answer.
3. Use clear page structure and direct factual support for important claims.
4. Test representative current-information queries and record citation behavior.
5. Separate training-crawler controls from web-search visibility assumptions.
## Gemini and other LLM surfaces
For Gemini or another LLM/product:
1. Identify whether the response is grounded in Google Search, Bing, a proprietary index, a connected knowledge base, or no live retrieval.
2. If grounded in Google Search, apply [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md) and the Google AI section above.
3. If grounded in Bing, apply Bing indexing/search controls.
4. If the platform publishes a crawler/user agent, record it and verify current robots/CDN handling.
5. If no publisher guidance exists, do not invent special markup, word-count, schema, “prompt-shaped” content, or keyword-density rules.
## Technical AI-discovery checks
For every platform being targeted, record where known:
- Platform/product
- Retrieval source/search engine
- Search crawler/user agent
- Training crawler/user agent if separate
- robots.txt rule
- CDN/WAF allow/block status
- HTTP status
- `noindex`/snippet controls
- Canonical/indexability
- JavaScript/rendering dependency
- Structured-data relevance
- Last verified date
Treat crawler controls separately by purpose. Allowing a training crawler is not automatically required for search/citation visibility, and blocking training does not necessarily mean blocking search where separate controls exist.
## Content controls for AI/LLM visibility
### Citation-worthiness
Prefer content containing:
- Original data/research
- First-hand experience
- Expert commentary
- Clear definitions
- Specific procedures
- Useful comparisons
- Evidence-backed recommendations
- Current product/service facts
- Unique examples/case evidence
- Transparent methodology
### Entity clarity
Keep consistent:
- Company/brand name
- Product/service names
- Author names and bios
- Location/market information
- Organization/contact/about information
- SameAs/social/profile references where appropriate
Do not create fake authors, fake expert credentials, or artificial mentions.
### Answerability
Make important pages easy for people and retrieval systems to understand:
- Clear page purpose/title/H1
- Logical H2/H3 structure
- Direct answers where appropriate
- Tables/lists only when they improve comprehension
- Definitions before advanced detail when needed
- Explicit units, dates, geographies, and conditions
- Primary-source links for material claims
### Freshness
For time-sensitive content:
- Track factual review date.
- Update only when material information changes.
- Remove/qualify stale claims.
- Avoid fake freshness through date changes alone.
### Multimodal content
Use relevant original/high-quality images, video, charts, downloadable data, or demonstrations when they improve the answer. Provide descriptive surrounding text and accessibility metadata.
## AI/LLM visibility monitoring
Record by platform/query set:
- Query/prompt
- Country/language/device/context when relevant
- Date tested
- Answer engine/platform
- Was web search/retrieval used?
- Brand/domain mentioned?
- URL cited/linked?
- Which page was cited?
- Claim supported correctly?
- Competing sources cited
- Referral traffic where measurable
- Change vs previous test
Use test sets by intent rather than one vanity prompt:
- Brand/entity
- Category/service
- Problem/solution
- Comparison
- How-to
- Local
- Research/statistic
- Product/review
## Unsupported myths/hacks
Do not automatically recommend:
- Creating hundreds of fan-out-query pages
- Keyword stuffing for LLMs
- Fake Reddit/forum/PR mentions
- Fake citations or fabricated statistics
- “AI detector” score optimization
- Exact word-count targets
- Rewriting everything into FAQs
- Adding schema that does not match visible content
- Treating llms.txt as a universal ranking requirement
- Assuming training-crawler access guarantees citation visibility
- Assuming one citation test proves stable ranking
- Buying mentions/links purely to manipulate answer engines
## AI visibility decision
Return one:
- `DISCOVERABLE`
- `CRAWLER_OR_ACCESS_ISSUE`
- `SEARCH_INDEX_ISSUE`
- `LOW_CITATION_WORTHINESS`
- `ENTITY_CLARITY_ISSUE`
- `FRESHNESS_OR_SOURCE_GAP`
- `PLATFORM_GUIDANCE_UNCLEAR`
- `MONITOR_VISIBILITY`
- `HUMAN_REVIEW_REQUIRED`
## Official references
Google:
- https://developers.google.com/search/docs/fundamentals/ai-optimization-guide
- https://developers.google.com/search/docs/fundamentals/using-gen-ai-content
- https://developers.google.com/search/docs/appearance/ranking-systems-guide
OpenAI:
- https://help.openai.com/en/articles/12627856
- https://help.openai.com/en/articles/9237897
Microsoft:
- https://learn.microsoft.com/en-us/microsoft-365/copilot/manage-public-web-access
- https://learn.microsoft.com/en-us/microsoft-copilot-studio/guidance/generative-ai-public-websites
Perplexity:
- https://www.perplexity.ai/help-center/en/articles/10352903-what-is-pro-search
Anthropic:
- https://docs.anthropic.com/en/docs/agents-and-tools/tool-use/web-search-tool
- https://www.anthropic.com/transparency
## Output record
When AI/LLM visibility materially affects a recommendation, record:
- Platform/product
- Retrieval/search basis when known
- Crawler/control check date
- Query/prompt set
- Visibility/citation observation
- Source page cited
- Evidence quality
- Technical issue if any
- Content/entity issue if any
- Recommendation
- Confidence
- Human-review status
