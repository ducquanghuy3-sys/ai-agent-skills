---
name: wallet-profiler
description: "On-chain wallet intelligence and smart money profiling. Input a wallet address, get a comprehensive profile: wallet type classification, trading performance, DeFi activity, risk exposure, behavioral patterns, and smart money score. Trigger whenever user provides a wallet address (0x... or Solana address) and wants to know: who is this wallet, is this smart money, what is this wallet doing, wallet analysis, whale tracking, copy-trade candidates, wallet risk check, or any on-chain behavioral analysis. Also triggers for: '分析这个钱包', '这个地址是谁', 'smart money分析', '鲸鱼追踪'. Supports EVM chains and Solana."
---

# Wallet Profiler

Transform any blockchain address into a comprehensive behavioral intelligence profile.

## Language Detection

- Chinese input → Full output in 中文
- English input → Full output in English
- Mixed → Match the dominant language

## Input Processing

Accept:
- EVM address: `0x` + 40 hex chars
- Solana address: Base58 string (32-44 chars)
- ENS name: `vitalik.eth`
- Solana domain: `name.sol`
- Casual: "analyze 0xABC...", "这个钱包怎么样 0xDEF..."

Auto-detect chain from address format. If EVM, default to Ethereum mainnet but note the wallet may be active on multiple chains.

## Profile Report Structure

### Section 1: Wallet Identity / 钱包画像

```
┌─────────────────────────────────────────┐
│  WALLET PROFILE                         │
│  Address: [0x... or shortened]          │
│  Type: [See classification below]       │
│  Smart Money Score: [X/100] [████░░░░]  │
│  First Activity: [Date]                 │
│  Age: [X days/months/years]             │
│  Chains Active: [ETH, ARB, BASE...]     │
└─────────────────────────────────────────┘
```

**Classification system (pick one primary):**

| Type | Criteria |
|------|----------|
| 🐋 Whale | >$1M in assets, large single trades |
| 🧠 Smart Money | Consistent profitable trades, early entries |
| 🏦 Institution/Fund | Multi-sig, large systematic operations |
| 🤖 Bot/MEV | High frequency, sandwich patterns, arb |
| 🏛️ DAO Treasury | Governance contract, proposal execution |
| 💎 Diamond Hands | Long hold periods, accumulation pattern |
| 🔄 Active Trader | Frequent swaps, position rotation |
| 🌱 Retail | Small positions, follows trends |
| 🌾 Yield Farmer | Moves between yield opportunities |
| 🎨 NFT Trader | Primary activity in NFT markets |

### Section 2: Portfolio Snapshot / 持仓快照

**Current Holdings (Top 10 by value):**

| Asset | Amount | Value (USD) | % of Portfolio | Chain |
|-------|--------|-------------|----------------|-------|
| ETH   | X.XX   | $X,XXX      | XX%            | Multi |
| ...   | ...    | ...         | ...            | ...   |

**Portfolio Metrics:**
- Total estimated value: $[X]
- Concentration (top 3 assets): [X]%
- Stablecoin allocation: [X]%
- DeFi locked value: $[X]
- NFT estimated value: $[X]

### Section 3: Trading Performance / 交易表现

Analyze the last 90 days of trading activity:

**Win/Loss Analysis:**
- Total trades: [X]
- Win rate: [X]% (trades with positive P&L)
- Average win: +[X]% | Average loss: -[X]%
- Largest win: [Token] +[X]% ($[X])
- Largest loss: [Token] -[X]% ($[X])
- Estimated 90d P&L: [+/-]$[X]

**Trading Style:**
- Average hold time: [X hours/days/weeks]
- Preferred entry: [Early/Mid/Late trend]
- Position sizing: [Concentrated/Diversified]
- Trading frequency: [X trades/week]

### Section 4: DeFi Activity / DeFi活跃度

| Protocol | Activity Type | Volume (90d) | Status |
|----------|--------------|-------------|--------|
| Uniswap  | Swaps        | $[X]        | Active |
| Aave     | Lending      | $[X]        | Active |
| ...      | ...          | ...         | ...    |

**DeFi Metrics:**
- Protocols used (90d): [X]
- Most-used protocol: [Name]
- Lending health factor (if applicable): [X]
- LP positions active: [X]
- Farming strategies: [Brief description]

### Section 5: Behavioral Patterns / 行为模式

**Activity Heatmap (conceptual):**
- Most active hours: [UTC timezone range]
- Most active days: [Weekday pattern]
- Gas spending pattern: [Efficient/Aggressive/Wasteful]

**Notable Behaviors:**
- [ ] Early adopter of new protocols (how many times in 6 months?)
- [ ] Follows specific influencer wallets (cluster analysis)
- [ ] Contrarian (buys during fear, sells during greed)
- [ ] Momentum trader (follows price trends)
- [ ] Airdrop farmer (many protocol first-interactions)
- [ ] Bridge activity (cross-chain movements)

### Section 6: Risk Exposure / 风险暴露

| Risk Type | Level | Detail |
|-----------|-------|--------|
| Concentration Risk | 🟢🟡🔴 | Top asset is X% of portfolio |
| Protocol Risk | 🟢🟡🔴 | Exposure to unaudited contracts |
| Leverage Risk | 🟢🟡🔴 | Borrowing positions, health factors |
| Liquidity Risk | 🟢🟡🔴 | Illiquid tokens, locked positions |
| Counterparty Risk | 🟢🟡🔴 | CEX exposure, bridge risk |

### Section 7: Smart Money Score / 聪明钱评分

Calculate composite score (0-100):

| Factor | Weight | Score | Reasoning |
|--------|--------|-------|-----------|
| Trading P&L | 25% | /100 | Historical profitability |
| Early Entry | 20% | /100 | How often first 10% of buyers |
| Risk Management | 20% | /100 | Stop-loss usage, diversification |
| Protocol Selection | 15% | /100 | Quality of protocols interacted |
| Consistency | 10% | /100 | Stable performance vs lucky hits |
| On-chain Hygiene | 10% | /100 | Gas efficiency, contract interaction safety |

```
SMART MONEY SCORE: [XX/100]
Rating: [Legendary / Expert / Skilled / Average / Novice]

Copy-Trade Suitability: [HIGH / MEDIUM / LOW / NOT RECOMMENDED]
Reason: [One line explanation]
```

### Section 8: Actionable Insights / 关键洞察

Top 3 takeaways:
1. [Most important finding about this wallet]
2. [Second most important]
3. [Third most important]

**If this is your wallet (self-analysis):**
- Optimization suggestions
- Risk reduction recommendations
- Strategy improvement tips

**If analyzing others (research):**
- What to learn from this wallet
- Patterns worth replicating
- Red flags to watch

## Privacy & Ethics

1. Only analyze publicly available on-chain data
2. NEVER attempt to identify the real-world person behind a wallet
3. NEVER speculate on identity unless the address is publicly known (e.g., labeled on Etherscan)
4. If the address appears to be a personal wallet (not a known entity), avoid language that could be used for stalking or harassment
5. Frame analysis as behavioral pattern research, not personal surveillance

## Data Accuracy Disclaimer

> ⚠️ On-chain data analysis has limitations. P&L calculations are estimates based on visible transactions and may not account for: CEX activity, OTC trades, multi-wallet strategies, or internal transfers. Smart Money Scores are heuristic-based and should not be the sole basis for any financial decision.
>
> ⚠️ 链上数据分析存在局限性。盈亏计算为基于可见交易的估算，可能未包含：中心化交易所活动、OTC交易、多钱包策略或内部转账。聪明钱评分基于启发式算法，不应作为任何财务决策的唯一依据。
