# 👛 Wallet Profiler / 钱包画像分析

> On-chain wallet intelligence & smart money scoring. Input an address, get a full profile.
>
> 链上钱包情报与聪明钱评分。输入地址，输出完整画像。

## Install / 安装

**Claude.ai:** Settings → Skills → Upload → drag `SKILL.md`

**Claude Code / Codex / Cursor:**
```bash
cp -r wallet-profiler/ .claude/skills/
```

## What You Get / 输出内容

- Wallet classification (Whale/Smart Money/Bot/Retail/etc.) / 钱包类型分类
- Portfolio snapshot / 持仓快照
- 90-day trading P&L & win rate / 90天盈亏与胜率
- DeFi activity across protocols / DeFi活跃度
- Smart Money Score (0-100) / 聪明钱评分
- Copy-trade suitability / 跟单建议

## Example Prompts / 示例

```
Profile this wallet: 0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045
```
```
分析这个钱包地址，帮我判断是不是聪明钱: 0xABC...
```

## Files / 文件

```
wallet-profiler/
├── SKILL.md
└── references/
    └── scoring-methodology.md   # Smart Money Score calculation
```

## API

```bash
curl -X POST https://web-production-1873.up.railway.app/api/skill/wallet-profiler \
  -H "Content-Type: application/json" \
  -d '{"user_id": "your_id", "address": "0xd8dA..."}'
```

⭐ [More skills / 更多技能 →](https://github.com/ducquanghuy3-sys/ai-agent-skills)
