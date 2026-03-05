---
name: seo-article-architect
description: "Generate SEO-optimized long-form articles with proper structure, keyword placement, meta tags, schema markup suggestions, and internal linking strategy. Input a target keyword or topic, get a publish-ready article with full SEO metadata. Use this skill when user wants to: write a blog post, create SEO content, optimize an article for search, generate long-form content with keywords, write a ranking article, 写SEO文章, 优化搜索排名, create pillar content, write product reviews for SEO, or any content that needs to rank on Google/Baidu. Supports English (Google-optimized) and Chinese (Baidu/Google CN optimized)."
---

# SEO Article Architect

One keyword → Publish-ready, SEO-optimized long-form article with complete metadata.

## Language & Search Engine Detection

- English keyword/topic → Google SEO optimization
- Chinese keyword/topic → Baidu + Google CN dual optimization
- User can specify target engine: "optimize for Baidu" or "optimize for Google"

## Input Processing

Accept:
- Target keyword: `"best project management tools 2026"`
- Topic description: `"write about how AI is changing healthcare"`
- URL to outrank: `"write a better version of [competitor URL]"`
- Chinese: `"写一篇关于远程办公工具的SEO文章"`

From input, extract/generate:
- Primary keyword
- 5-10 secondary keywords (LSI / semantically related)
- Search intent: Informational / Commercial / Transactional / Navigational
- Target word count based on intent and competition

## Article Generation Process

### Phase 1: Keyword & Intent Analysis

```
┌─────────────────────────────────────────────┐
│  SEO BRIEF                                  │
│  Primary Keyword: [keyword]                 │
│  Search Intent: [type]                      │
│  Difficulty Estimate: [Low/Med/High]        │
│  Target Word Count: [X-Y words]             │
│  Content Type: [Guide/List/Review/How-to]   │
│  Target Audience: [Description]             │
└─────────────────────────────────────────────┘

Secondary Keywords:
1. [keyword] — [est. volume] — [use in: H2/body/meta]
2. [keyword] — [est. volume] — [use in: H2/body]
3. ...

Long-tail Variations:
1. [question format keyword]
2. [comparison keyword]
3. [location-based keyword if applicable]
```

### Phase 2: Content Structure (Outline)

Generate a detailed outline before writing:

```
# [H1 Title — includes primary keyword, <60 chars]

## [H2 Section 1 — includes secondary keyword]
### [H3 Subsection if needed]

## [H2 Section 2]

## [H2 Section 3]

## [H2 FAQ Section — targets "People Also Ask"]
### [FAQ Q1 — exact question from PAA]
### [FAQ Q2]
### [FAQ Q3]

## [H2 Conclusion with CTA]
```

**Outline rules:**
- H1: One per article, includes primary keyword naturally
- H2s: 4-8 sections, each targets a secondary keyword
- H3s: Use when H2 section exceeds 300 words
- FAQ: 3-5 questions targeting "People Also Ask" featured snippets
- Content flows logically (reader shouldn't need to jump around)

### Phase 3: Full Article

Write the complete article following these SEO content rules:

**Keyword Placement (Critical):**
- Primary keyword in: H1, first paragraph (first 100 words), one H2, meta title, meta description, URL slug, image alt text
- Keyword density: 0.5-1.5% (natural, never forced)
- Secondary keywords: distributed naturally across H2s and body
- Semantic variations: use synonyms and related terms throughout
- NO keyword stuffing — if it reads unnaturally, rewrite

**Content Quality Signals:**
- **E-E-A-T compliance**: Show Experience, Expertise, Authority, Trust
  - Include first-hand experience language ("In our testing...", "Based on X years of...")
  - Cite credible sources with context
  - Acknowledge limitations and counterpoints
- **Comprehensiveness**: Cover the topic more thoroughly than current top-3 results
- **Freshness signals**: Reference current year, recent data, latest updates
- **Readability**: Short paragraphs (2-4 sentences), varied sentence length, transition words
- **Scannable**: Bold key phrases, use bullet points for lists, tables for comparisons

**Engagement Elements:**
- TL;DR / Key Takeaways box at the top (helps featured snippets)
- Comparison tables (for commercial intent keywords)
- Step-by-step instructions (for how-to intent)
- Expert quotes or data citations (E-E-A-T)
- Internal linking placeholders: `[INTERNAL LINK: anchor text → suggested target page topic]`
- External citations: link to authoritative sources (gov, edu, major publications)

**Content Length Guidelines by Intent:**
- Informational/Guide: 1,500-3,000 words
- Commercial comparison: 2,000-4,000 words
- How-to: 1,000-2,000 words
- Product review: 1,500-2,500 words
- News/Update: 800-1,200 words

### Phase 4: SEO Metadata Package

Append complete metadata after the article:

```
═══════════════════════════════════════════════════
SEO METADATA PACKAGE
═══════════════════════════════════════════════════

META TITLE (50-60 chars):
[Primary keyword + modifier + brand if applicable]
Character count: [X]

META DESCRIPTION (150-160 chars):
[Compelling summary with primary keyword + CTA]
Character count: [X]

URL SLUG:
/[keyword-separated-by-hyphens]

OG TITLE (for social sharing):
[Can be slightly different/more clickable than meta title]

OG DESCRIPTION:
[Social-optimized description]

SCHEMA MARKUP SUGGESTION:
- Article schema (headline, author, datePublished, dateModified)
- FAQ schema (if FAQ section present — boosts SERP real estate)
- HowTo schema (if step-by-step content)
- Review schema (if product review with rating)

IMAGE ALT TEXTS:
- Hero image: "[primary keyword] — [descriptive context]"
- Image 2: "[secondary keyword] [description]"
- ...

INTERNAL LINKING SUGGESTIONS:
1. "[anchor text]" → link to [topic/page about X]
2. "[anchor text]" → link to [topic/page about Y]
3. "[anchor text]" → link to [topic/page about Z]

EXTERNAL CITATION LINKS:
1. [Source name] — [URL] — used for [what claim]
2. ...

TARGET FEATURED SNIPPET:
Type: [Paragraph / List / Table]
Target query: "[question]"
Optimized answer (40-60 words):
[Concise answer formatted for snippet extraction]
```

### Phase 5: Baidu-Specific Optimization (Chinese content only)

Additional metadata for Baidu:

```
百度SEO补充优化：

百度标题 (max 30 Chinese chars):
[标题 — 包含核心关键词]

百度描述 (max 78 Chinese chars):
[描述文案]

百度关键词标签:
[关键词1], [关键词2], [关键词3]

百度特色内容建议:
- 百家号同步发布版本（800字精简版）
- 百度知道/贴吧问答植入建议
- 百度百科引用机会

注意事项:
- 百度偏好：原创声明、发布时间、更新频率
- 避免：过度堆砌关键词、隐藏文字、大量外链
- 移动优先：百度移动端流量>70%，确保移动友好
```

## Quality Checklist

Before final output:
- [ ] Primary keyword appears in H1, first 100 words, one H2, meta title, meta description
- [ ] No keyword stuffing (reads naturally when read aloud)
- [ ] All H2s serve both readers and search engines
- [ ] FAQ section targets real "People Also Ask" questions
- [ ] Content is more comprehensive than a typical top-3 result
- [ ] E-E-A-T signals present (experience, expertise, citations)
- [ ] Current year referenced for freshness
- [ ] Internal linking opportunities identified
- [ ] Meta title ≤60 chars, meta description ≤160 chars
- [ ] Featured snippet opportunity identified and optimized
- [ ] Content matches search intent perfectly
- [ ] Readability: short paragraphs, headers every 200-300 words

## Reference Files

- `references/seo-checklist.md` — Technical SEO checklist for published articles
