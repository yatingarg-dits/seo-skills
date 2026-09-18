# Content Topic Research and Validation

## Purpose

Turn a keyword, cluster, topic seed, or campaign requirement into an approved topic direction without duplicating existing content.


## Contents

- Inputs and keyword/context check
- Existing-content check
- Topic research
- Uniqueness/information-gain check
- Topic selection
- Output
## Inputs

Load:

- [03-client-context.md](03-client-context.md)
- [04-property-context.md](04-property-context.md)
- [06-client-content-style-rules.md](06-client-content-style-rules.md)
- [15-keyword-validation-output.md](15-keyword-validation-output.md) for keyword-led SEO content
- [14-keyword-clustering-mapping.md](14-keyword-clustering-mapping.md) when URL mapping/cannibalization is relevant

## Step 1: Keyword/context check

Confirm:

- Intent
- Audience/ICP
- Geography/language
- Business relevance
- Business objective
- Funnel/use context when relevant
- Existing target URL or new-page need

Return `KEYWORD_VALIDATED` only when enough context exists to proceed.

## Step 2: Existing-content check

Search/retrieve existing site content and identify:

- Same topic
- Same search intent
- Same keyword cluster
- Closely overlapping article/page
- Existing high-performing asset
- Cannibalization risk
- Opportunity to refresh/expand instead of creating new content

Use one action:

- CREATE_NEW
- REFRESH_EXISTING
- EXPAND_EXISTING
- CONSOLIDATE
- DIFFERENTIATE
- DO_NOT_CREATE
- NEEDS_HUMAN_REVIEW

## Step 3: Topic research

Generate options using the available evidence from:

- Keyword/cluster
- Audience needs
- Client/business priorities
- Existing content gaps
- SERP competitors
- Current SERP formats/subtopics/questions
- Trends when relevant
- Product/service context

Do not choose a topic only because competitors cover it.

## Step 4: Uniqueness/information-gain check

Ask:

`What useful contribution will this content add that existing site/SERP content does not?`

Possible contribution types include:

- Original expertise
- Better synthesis
- Proprietary data
- Different framework
- Industry experience
- Examples
- Product knowledge
- Contrarian analysis
- Better explanation
- Unique research

If no meaningful contribution exists, return `WARNING_LOW_INFORMATION_GAIN`.

## Step 5: Topic selection

Select the topic/title direction that best balances:

- User need
- Search intent where relevant
- Business objective
- Audience fit
- Differentiation
- Evidence availability
- Existing-content conflict
- Realistic content depth

## Output

Return:

- Input keyword/topic
- Context status
- Existing-content result
- Cannibalization/duplication risk
- Topic options
- Differentiation angle for each serious option
- Selected topic/title direction
- Reason
- SERP research requirement
- Source research requirement
- Human review status
