---
name: competitor-intel-report
description: "Generate professional competitive intelligence reports. Input a company, product, or brand name and get a structured analysis covering: market positioning, product comparison, pricing strategy, strengths/weaknesses, content/SEO strategy, customer sentiment, and strategic recommendations. Use this skill when user wants to: analyze competitors, compare products, do market research, understand competitive landscape, benchmark against rivals, write competitive analysis, 竞品分析, 竞争对手调研, 市场分析, or any task involving understanding what competitors are doing and how to beat them. Works for SaaS, e-commerce, crypto projects, apps, or any industry. Bilingual output (English/Chinese)."
---

# Competitor Intel Report

Company/product name → Professional-grade competitive intelligence report.

## Language Detection

- Chinese input → Report in 中文
- English input → Report in English
- Mixed → Match dominant language, can switch if requested

## Input Processing

Accept:
- Company name: "Notion", "Stripe", "字节跳动"
- Product name: "ChatGPT", "Figma", "飞书"
- Comparison request: "Notion vs Obsidian", "compare Shopify and WooCommerce"
- Your company + competitors: "I'm building [X], analyze my competitors [A, B, C]"
- Industry request: "who are the top players in [industry]?"

From input, determine:
- **Mode A — Single Target**: Deep analysis of one competitor
- **Mode B — Head-to-Head**: Detailed comparison of 2-3 competitors
- **Mode C — Landscape**: Overview of 5-8 players in a market

## Report Structure

### Cover Page

```
╔═══════════════════════════════════════════════════════╗
║  COMPETITIVE INTELLIGENCE REPORT                     ║
║                                                       ║
║  Target: [Company/Product Name]                       ║
║  Industry: [Industry/Category]                        ║
║  Analysis Date: [Date]                                ║
║  Report Type: [Deep Dive / Comparison / Landscape]    ║
╚═══════════════════════════════════════════════════════╝
```

---

### Section 1: Executive Summary / 执行摘要

3-5 bullet points covering:
- Who they are and what they do (one sentence)
- Current market position (leader/challenger/niche/emerging)
- Key competitive advantage (what they do better than anyone)
- Primary vulnerability (where they can be beaten)
- Strategic outlook (growing/stable/declining, and why)

---

### Section 2: Company Profile / 公司画像

| Field | Detail |
|-------|--------|
| Founded | [Year] |
| HQ | [Location] |
| Employees | [Est. number] |
| Funding | [Total raised, last round, key investors] |
| Revenue | [Est. ARR/revenue if available] |
| Valuation | [Last known or estimated] |
| Key People | [CEO, CTO, notable leaders] |
| Business Model | [SaaS/Marketplace/Freemium/etc.] |

**Growth Timeline:**
- [Year]: [Milestone]
- [Year]: [Milestone]
- [Year]: [Milestone]

---

### Section 3: Product Analysis / 产品分析

**Core Product Offering:**
[2-3 sentence description of what the product does and who it's for]

**Feature Matrix (for Mode B comparison):**

| Feature | [Competitor A] | [Competitor B] | [Your Product] |
|---------|---------------|---------------|----------------|
| [Feature 1] | ✅ Full | ⚠️ Partial | ❌ Missing |
| [Feature 2] | ✅ | ✅ | ✅ |
| [Feature 3] | ❌ | ✅ | ✅ |
| [Feature 4] | ✅ | ❌ | ⚠️ |

**Product Strengths:**
1. [Strength with evidence]
2. [Strength with evidence]
3. [Strength with evidence]

**Product Weaknesses:**
1. [Weakness with evidence/user complaints]
2. [Weakness with evidence]
3. [Weakness with evidence]

**Tech Stack (if known):**
- Frontend: [Technologies]
- Backend: [Technologies]
- Infrastructure: [Cloud provider, notable tech choices]

---

### Section 4: Pricing & Monetization / 定价策略

**Pricing Model:**
| Tier | Price | Key Limits | Target Segment |
|------|-------|-----------|----------------|
| Free | $0 | [Limits] | Individual/Trial |
| Pro | $X/mo | [Features] | SMB |
| Enterprise | Custom | [Features] | Enterprise |

**Pricing Strategy Analysis:**
- Pricing psychology: [What tactics do they use? Anchoring? Decoy tier?]
- vs. market average: [Cheaper/Pricier/On par]
- Value metric: [What do they charge per? Seat/usage/feature?]
- Discount patterns: [Annual discount %, seasonal promos?]
- Free tier strategy: [How generous? Conversion funnel?]

**Revenue Estimate:**
- Estimated customers: [X]
- Estimated ARPU: $[X]/mo
- Estimated ARR: $[X]M
- Revenue growth rate: [X]% YoY (estimated)

---

### Section 5: Go-to-Market Strategy / 获客策略

**Marketing Channels (ranked by estimated investment):**

| Channel | Investment Level | Strategy |
|---------|-----------------|----------|
| Content/SEO | 🔴🔴🔴 High | [What they publish, blog topics, keyword targets] |
| Paid Ads | 🟡🟡 Medium | [Platforms, estimated spend, ad types] |
| Social Media | 🔴🔴🔴 High | [Platforms, posting frequency, engagement style] |
| Community | 🟡🟡 Medium | [Discord/Slack, community size, engagement] |
| Partnerships | 🟢 Low | [Integration partners, co-marketing] |
| Events | 🟢 Low | [Conferences, webinars] |
| PLG (Product-Led) | 🔴🔴🔴 High | [Free tier, viral loops, referral programs] |

**Content Strategy Analysis:**
- Blog posting frequency: [X posts/week]
- Top-performing content topics: [themes]
- SEO keyword focus: [primary keyword clusters]
- Estimated organic traffic: [X visits/mo]
- Content format: [Long-form / short / video / podcast]

**Social Media Presence:**

| Platform | Followers | Posting Freq | Engagement | Tone |
|----------|-----------|-------------|------------|------|
| Twitter/X | [X]K | [X]/week | [Low/Med/High] | [Description] |
| LinkedIn | [X]K | [X]/week | [Low/Med/High] | [Description] |
| 小红书 | [X]K | [X]/week | [Low/Med/High] | [Description] |

---

### Section 6: Customer Intelligence / 客户洞察

**Target Customer Profile:**
- Company size: [SMB/Mid-market/Enterprise]
- Industry verticals: [Top 3 industries]
- Buyer persona: [Role, pain points, decision drivers]
- Geographic focus: [Regions]

**Customer Sentiment Analysis:**
Based on reviews, social mentions, and community discussions:

| Aspect | Sentiment | Evidence |
|--------|-----------|----------|
| Product Quality | 😊/😐/😞 | [Summary of reviews] |
| Customer Support | 😊/😐/😞 | [Common complaints/praise] |
| Pricing Fairness | 😊/😐/😞 | [Value perception] |
| Onboarding | 😊/😐/😞 | [Ease of getting started] |
| Reliability | 😊/😐/😞 | [Uptime, bug complaints] |

**Common Customer Complaints (Top 3):**
1. [Complaint — source]
2. [Complaint — source]
3. [Complaint — source]

**What Customers Love Most (Top 3):**
1. [Praise — source]
2. [Praise — source]
3. [Praise — source]

**Churn Signals:**
- Why customers leave: [Top reasons]
- Where they go: [Alternative products mentioned]

---

### Section 7: SWOT Matrix / SWOT分析

```
┌─────────────────────┬─────────────────────┐
│    STRENGTHS 💪     │   WEAKNESSES ⚠️    │
│                     │                     │
│ • [S1]              │ • [W1]              │
│ • [S2]              │ • [W2]              │
│ • [S3]              │ • [W3]              │
│                     │                     │
├─────────────────────┼─────────────────────┤
│  OPPORTUNITIES 🚀   │    THREATS 🔥       │
│                     │                     │
│ • [O1]              │ • [T1]              │
│ • [O2]              │ • [T2]              │
│ • [O3]              │ • [T3]              │
│                     │                     │
└─────────────────────┴─────────────────────┘
```

---

### Section 8: Strategic Recommendations / 战略建议

**How to Compete Against [Competitor]:**

**DO — Attack Their Weaknesses:**
1. [Specific actionable recommendation targeting their #1 weakness]
2. [Specific recommendation targeting their #2 weakness]
3. [Specific recommendation targeting underserved customer segment]

**DON'T — Avoid Their Strengths:**
1. [What NOT to compete on directly, and why]
2. [Where you'd waste resources trying to match them]

**Positioning Strategy:**
```
Their positioning: "[How they describe themselves]"
Recommended counter-positioning: "[How to position against them]"
Key differentiator to emphasize: "[Your unique angle]"
```

**Quick Wins (next 30 days):**
1. [Fast, actionable step]
2. [Fast, actionable step]
3. [Fast, actionable step]

**Long-term Moat Building (6-12 months):**
1. [Strategic investment]
2. [Strategic investment]
3. [Strategic investment]

---

### Section 9: Monitoring Plan / 持续监控方案

Set up ongoing competitive monitoring:

| Signal | Tool/Method | Frequency |
|--------|------------|-----------|
| Pricing changes | Wayback Machine / manual check | Monthly |
| New features | Changelog, Product Hunt, social | Weekly |
| Hiring patterns | LinkedIn jobs page | Bi-weekly |
| SEO movements | Keyword rank tracking | Weekly |
| Social sentiment | Social listening tool | Real-time |
| Funding/M&A | Crunchbase alerts | Real-time |
| Content strategy | Blog RSS, newsletter signup | Weekly |

---

## Quality Standards

1. **Evidence-based**: Every claim should reference a source or data point
2. **Actionable**: Recommendations must be specific enough to execute
3. **Balanced**: Present competitor strengths honestly, not just weaknesses
4. **Current**: Flag any data points that may be outdated
5. **Honest**: If information is unavailable or estimated, label it clearly

## Limitations Disclaimer

> ⚠️ This competitive analysis is based on publicly available information and AI reasoning. Revenue figures, customer counts, and market share estimates may not be accurate. For critical business decisions, validate findings with primary research. This is not financial or legal advice.
>
> ⚠️ 本竞品分析基于公开信息和AI推理。收入数据、客户数量和市场份额为估算值，可能存在偏差。重大商业决策请以实际调研为准。本报告不构成财务或法律建议。

## Reference Files

- `references/analysis-frameworks.md` — Porter's Five Forces, Jobs-to-be-Done, Blue Ocean templates
