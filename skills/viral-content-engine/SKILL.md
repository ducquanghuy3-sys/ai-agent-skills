---
name: viral-content-engine
description: "Multi-platform viral content generator. Creates high-engagement content optimized for Xiaohongshu (小红书), Twitter/X, LinkedIn, WeChat Official Account (公众号), and Threads. Input a topic/idea, get platform-specific content with hooks, formatting, hashtags, and engagement optimization. Use this skill when user wants to: write viral posts, create social media content, generate 小红书笔记, write tweets/threads, craft LinkedIn posts, write 公众号文章, make content go viral, get more engagement, 写爆款内容, 写种草笔记, 写推文, or any social content creation task. Supports Chinese and English content natively."
---

# Viral Content Engine

One topic → Multi-platform optimized viral content, ready to post.

## Language & Platform Detection

From user input, determine:
1. **Language**: Chinese input → Chinese platforms first (小红书, 公众号), English → Twitter, LinkedIn
2. **Platform**: If specified, generate for that platform only. If not specified, generate for the 2-3 most relevant platforms based on topic.
3. **Always ask**: If ambiguous, confirm which platforms before generating.

## Platform Matrix

| Platform | Audience | Tone | Length | Visual? |
|----------|----------|------|--------|---------|
| 小红书 (Xiaohongshu) | 18-35 F, lifestyle | Personal, 种草, emotional | 300-800 chars | Required: image/carousel description |
| Twitter/X | Tech, crypto, global | Sharp, provocative, concise | 280 chars or thread | Optional |
| LinkedIn | Professional, B2B | Authoritative, story-driven | 1000-1500 chars | Optional |
| 公众号 (WeChat) | Mixed CN audience | Deep, narrative, 反转 | 1500-3000 chars | Recommended |
| Threads | Gen Z, casual | Conversational, relatable | 500 chars | Optional |

## Content Generation Process

### Step 1: Topic Analysis

Extract from user input:
- **Core topic**: What is this about?
- **Angle**: What's the unique perspective?
- **Target emotion**: Aspiration / Fear / Curiosity / Outrage / FOMO / Validation
- **Content type**: Educational / Story / Opinion / Review / How-to / List

### Step 2: Hook Engineering

Every platform post lives or dies on the hook. Generate 3 hook options per platform:

**小红书 Hook Formulas:**
```
1. [数字] + [反常识结论] → "用了3年才发现，XX根本不需要XXX"
2. [身份认同] + [痛点] → "打工人别再XX了！这个方法省了我XXX"
3. [对比冲击] + [好奇] → "月薪3K vs 月薪3W的人，区别竟然在XXX"
4. [情绪爆点] + [共鸣] → "后悔没早知道！XX真的太太太好用了"
5. [反转预告] + [悬念] → "所有人都说XX好，直到我发现了这个真相..."
```

**Twitter/X Hook Formulas:**
```
1. Bold claim: "Hot take: [controversial opinion that's actually reasonable]"
2. Thread opener: "I spent [time] studying [topic]. Here's what 99% of people get wrong:"
3. Data shock: "[Surprising statistic]. Let me explain why this matters."
4. Contrarian: "Everyone is talking about [X]. Nobody is talking about [Y]."
5. Story hook: "In 2024, I [did X]. It changed everything. Here's how:"
```

**LinkedIn Hook Formulas:**
```
1. Career story: "I got fired. Best thing that ever happened to me. Here's why:"
2. Counter-narrative: "Stop telling people to [common advice]. Here's what actually works."
3. Vulnerability: "I failed at [X] 7 times before I finally understood [Y]."
4. Industry insight: "[Industry] is about to change forever. Here's what I'm seeing."
5. Framework share: "After [X years] in [field], I boiled everything down to [N] principles:"
```

**公众号 Hook Formulas:**
```
1. 反直觉开场: "我劝你，千万别再XXX了"
2. 故事悬念: "昨天，一个朋友跟我说了一件事，听完我沉默了很久"
3. 数据冲击: "一个残酷的数据：XX%的人正在经历XXX"
4. 身份唤醒: "如果你正在XXX，那这篇文章可能会改变你的想法"
5. 时代焦虑: "2026年了，还在XXX的人，该醒醒了"
```

### Step 3: Platform-Specific Content Generation

---

#### 📕 小红书 Output Format

```
[TITLE — max 20 chars, with emoji]

[Hook — first 2 lines are EVERYTHING, must stop scrolling]

[Body — 300-800 chars]
- Use line breaks every 1-2 sentences
- Emoji at the start of each section ✨💡🔥
- Personal tone ("我发现"/"亲测"/"真心推荐")
- Include specific numbers and details
- 种草感/实用性/共鸣感 三选一主打

[Call to Action]
💬 你们觉得呢？评论区聊聊~
📌 收藏起来慢慢看！
👉 关注我获取更多XX干货

[Hashtags — 5-10个]
#主话题 #细分话题 #流量词 #情绪词 #平台热词

[Image/Carousel Description]
封面图建议：[描述理想的封面图设计]
内页建议：[如需图文笔记，描述每页内容]
```

---

#### 🐦 Twitter/X Output Format

**Single Tweet:**
```
[280-char max tweet with hook + value + CTA]
```

**Thread (if topic needs depth):**
```
1/ [Hook tweet — must stand alone as viral-worthy]

2/ [Context or surprising fact]

3/ [Core insight #1]

4/ [Core insight #2]

5/ [Core insight #3 — the best one]

6/ [Practical takeaway or framework]

7/ [CTA: Follow for more / Repost if useful / Reply with your take]
```

**Optimization notes:**
- No hashtags in main tweet (hurts algo since 2024)
- Use line breaks for readability
- End threads with engagement question
- Time suggestion: Post at [optimal time for topic]

---

#### 💼 LinkedIn Output Format

```
[First line — hook that makes people click "see more"]

[Line break]

[Story or context — 2-3 short paragraphs]

[Key insight or framework — use numbered list if applicable]

[Personal reflection — what you learned]

[Call to action — question to drive comments]

[3-5 relevant hashtags]
```

**Optimization notes:**
- First 3 lines determine everything (before "see more" cut)
- Avoid external links in post (kills reach)
- Put links in first comment instead
- Personal stories outperform corporate content 3-5x
- Comment and reply to early engagers within first hour

---

#### 📱 公众号 Output Format

```
[标题 — max 30 chars, 公众号标题公式]
[副标题 (if applicable)]

[开头 — 300字以内建立共鸣或制造悬念]

[正文]
## 小标题1
[论点 + 故事/案例/数据]

## 小标题2
[论点 + 反转或深入]

## 小标题3
[论点 + 升华]

[结尾 — 金句收尾或行动号召]

---
[引导关注/转发的话术]
```

**Optimization notes:**
- 标题是一切，A/B测试至少3个标题
- 前3段决定留存率
- 每段不超过3行（手机阅读体验）
- 插入1-2个"金句"供截图转发
- 结尾设置互动问题提升完读率

---

### Step 4: Engagement Boosters

For each platform, append:

**Posting Strategy:**
- Best posting time for this topic/platform
- Engagement hack: What to do in the first 30 minutes
- Reply strategy: Prepare 2-3 potential reply templates for common comments

**A/B Test Suggestions:**
- 3 alternative titles/hooks to test
- Brief reasoning for each variant

## Quality Checklist

Before outputting any content:
- [ ] Hook is genuinely scroll-stopping (not generic clickbait)
- [ ] Content delivers on the hook's promise (no bait-and-switch)
- [ ] Platform-specific formatting applied correctly
- [ ] Tone matches platform culture
- [ ] Includes specific details/numbers (not vague platitudes)
- [ ] Call-to-action is natural, not forced
- [ ] No factual claims without basis
- [ ] Hashtags/tags are relevant and current
- [ ] Content length within platform sweet spot

## Anti-Patterns to Avoid

1. ❌ Generic motivational quotes with no substance
2. ❌ Clickbait that doesn't deliver
3. ❌ Copying viral post structures too obviously
4. ❌ Too many hashtags (looks desperate)
5. ❌ Long paragraphs on mobile-first platforms
6. ❌ Humble-bragging disguised as advice
7. ❌ Using "AI-generated" language patterns (overly formal, listy)
8. ❌ Ignoring platform-specific culture and norms

## Reference Files

- `references/platform-algorithms.md` — How each platform's algorithm works and how to optimize
- `references/hook-database.md` — 50+ proven hook templates per platform
