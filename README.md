# 🧠 AI Agent Premium Skills

**EN** | [中文](#-中文说明)

> 5 production-grade Agent Skills for Claude, Codex, Cursor, Gemini CLI and more.
> Each skill is an independent repo — install only what you need.

---

## ⚡ Skills

| Skill | What It Does | Install |
|-------|-------------|---------|
| 🪙 [**Token Analyzer Pro**](https://github.com/ducquanghuy3-sys/token-analyzer-pro) | Crypto token analysis report with risk scores | `git clone .../token-analyzer-pro.git .skills/token-analyzer-pro` |
| 👛 [**Wallet Profiler**](https://github.com/ducquanghuy3-sys/wallet-profiler) | On-chain wallet intelligence, smart money scoring | `git clone .../wallet-profiler.git .skills/wallet-profiler` |
| 🔥 [**Viral Content Engine**](https://github.com/ducquanghuy3-sys/viral-content-engine) | 小红书/Twitter/LinkedIn/公众号 viral content | `git clone .../viral-content-engine.git .skills/viral-content-engine` |
| 📝 [**SEO Article Architect**](https://github.com/ducquanghuy3-sys/seo-article-architect) | SEO-optimized articles + full metadata | `git clone .../seo-article-architect.git .skills/seo-article-architect` |
| 🕵️ [**Competitor Intel Report**](https://github.com/ducquanghuy3-sys/competitor-intel-report) | SWOT + pricing + GTM strategy report | `git clone .../competitor-intel-report.git .skills/competitor-intel-report` |

Click any skill name above to see full docs, examples, and installation instructions.

---

## 🚀 Quick Install

### Install one skill
```bash
git clone https://github.com/ducquanghuy3-sys/token-analyzer-pro.git .skills/token-analyzer-pro
```

### Install all 5
```bash
for skill in token-analyzer-pro wallet-profiler viral-content-engine seo-article-architect competitor-intel-report; do
  git clone https://github.com/ducquanghuy3-sys/${skill}.git .skills/${skill}
done
```

### Claude.ai (manual)
1. Go to any skill repo above
2. Download the `SKILL.md` file
3. Settings → Skills → Upload → drag it in

---

## 🔌 API (Pay Per Call)

Don't want to use Claude? Call the API directly:

| Skill | Price | Endpoint |
|-------|-------|----------|
| Token Analyzer | $0.003 | `POST /api/skill/token-analyzer` |
| Wallet Profiler | $0.003 | `POST /api/skill/wallet-profiler` |
| Viral Content | $0.002 | `POST /api/skill/viral-content` |
| SEO Article | $0.003 | `POST /api/skill/seo-article` |
| Competitor Intel | $0.003 | `POST /api/skill/competitor-intel` |

👉 **[API Docs →](https://web-production-1873.up.railway.app/api/skills)** · **[Landing Page →](https://web-production-1873.up.railway.app)**

---

---

# 🧠 中文说明

[English](#-ai-agent-premium-skills) | **中文**

> 5 个高质量 AI Agent 技能，适用于 Claude、Codex、Cursor、Gemini CLI。
> 每个技能独立一个仓库，按需安装。

---

## ⚡ 技能列表

| 技能 | 功能 | 安装 |
|------|------|------|
| 🪙 [**代币分析专家**](https://github.com/ducquanghuy3-sys/token-analyzer-pro) | 机构级代币分析报告 | `git clone .../token-analyzer-pro.git .skills/token-analyzer-pro` |
| 👛 [**钱包画像分析**](https://github.com/ducquanghuy3-sys/wallet-profiler) | 链上钱包情报 + 聪明钱评分 | `git clone .../wallet-profiler.git .skills/wallet-profiler` |
| 🔥 [**爆款内容引擎**](https://github.com/ducquanghuy3-sys/viral-content-engine) | 小红书/Twitter/LinkedIn/公众号 多平台内容 | `git clone .../viral-content-engine.git .skills/viral-content-engine` |
| 📝 [**SEO文章架构师**](https://github.com/ducquanghuy3-sys/seo-article-architect) | SEO优化长文 + 完整元数据 | `git clone .../seo-article-architect.git .skills/seo-article-architect` |
| 🕵️ [**竞品情报分析**](https://github.com/ducquanghuy3-sys/competitor-intel-report) | SWOT + 定价拆解 + 行动建议 | `git clone .../competitor-intel-report.git .skills/competitor-intel-report` |

点击技能名称查看完整文档、使用示例和安装方法。

---

## 🚀 安装

### 只装一个
```bash
git clone https://github.com/ducquanghuy3-sys/token-analyzer-pro.git .skills/token-analyzer-pro
```

### 全部安装
```bash
for skill in token-analyzer-pro wallet-profiler viral-content-engine seo-article-architect competitor-intel-report; do
  git clone https://github.com/ducquanghuy3-sys/${skill}.git .skills/${skill}
done
```

### Claude.ai 网页版
1. 进入上面任意技能仓库
2. 下载 `SKILL.md` 文件
3. 设置 → 技能 → 上传 → 拖入

---

## 🔌 付费 API（按次计费）

不用 Claude 也能用，直接调 API：

| 技能 | 单价 | 接口 |
|------|------|------|
| 代币分析 | $0.003（¥0.02） | `POST /api/skill/token-analyzer` |
| 钱包画像 | $0.003 | `POST /api/skill/wallet-profiler` |
| 爆款内容 | $0.002 | `POST /api/skill/viral-content` |
| SEO文章 | $0.003 | `POST /api/skill/seo-article` |
| 竞品分析 | $0.003 | `POST /api/skill/competitor-intel` |

👉 **[API文档 →](https://web-production-1873.up.railway.app/api/skills)** · **[产品首页 →](https://web-production-1873.up.railway.app)**

---

## ⭐ Star = 支持

好用就给个 ⭐，帮助更多人发现。
