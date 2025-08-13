---
icon: engine
---

# Yield Engine (CCYOE)

### Cross-Collateral Yield Optimization Engine

Cambi's most innovative feature isn't just accessing high yields – it's intelligently distributing them across the protocol to create sustainable, market-beating returns for all users. Think of it as both an embedded protocol hedge, as well a constant pseudo-equalizer that allocates yields (instead of token inflation or “free money” for mercenary capital) as a form of incentive to build a powerful, Bitcoin-first treasury for the protocol.

#### The Problem with Isolated Yields

Traditional protocols treat each asset in isolation:

* USDC earns T-bill yields (5%) - that Circle keeps entirely
* BTC earns DeFi lending yields (3%) - really high risk for low returns
* Local currencies earn local rates - which are usually locked up and heavily controlled

This creates inefficiencies and limits growth potential.

#### Cambi's Approach

We treat all protocol yields as a unified pool, dynamically optimizing distribution while maintaining risk isolation:

**Base Layer**: Each asset generates native yields

* cmBRL: 14-25% from Brazilian markets
* cmUSD: 12-18% from USD-denominated receivables
* cmBTC: 3-8% from institutional lending

**Optimization Layer**: Excess yields flow into unified pool

* If cmBRL yield exceeds targets, excess yield boosts cmUSD/cmBTC
* And since we're competing against single-digit-yields from other yield-bearing stables
* If cmUSD yield exceeds targets, excess yield boosts cmBTC
* During high-demand periods, yields auto-balance
* Protocol treasury captures value for security and growth

**Simplified Distribution Logic**:

```
Base Yield Distribution:
- cmBRL holders: Native yield (currently 14-25%)
- cmUSD holders: Native yield (currently 12-18%)
- cmBTC holders: Native yield (currently 3-8%)

Optimization Distribution:
- Calculate excess yields above target rates
- Redistribute based on:
  - 40% to under-supplied assets
  - 30% to strategic growth incentives
  - 20% to all holders proportionally
  - 10% to protocol treasury
```

#### Dynamic Supply Caps

To maintain attractive yields, we also implement dynamic supply caps:

* **cmBRL**: Unlimited (main yield generator for protocol)
* **cmUSD**: $50M initial cap (expands by $25M when yield >14%)
* **cmBTC**: $20M initial cap (expands by $10M when utilization >80%)

#### Real-World Example

Imagine the protocol state:

* cmBRL: $80M TVL generating 25% = $20M annual yield
* cmUSD: $40M TVL expecting 15% = $6M expected yield
* cmBTC: $15M TVL expecting 5% = $750k expected yield

Total protocol yield: $20M Total expected distribution: $6.75M Excess yield: $13.25M

This excess is redistributed:

* cmUSD boost: +3% (to 18%)
* cmBTC boost: +2% (to 7%)
* Strategic reserves: $2M
* Future incentives: $3M

#### Benefits of Unification

1. **Network Effects**: Success in one asset benefits all users
2. **Sustainable Yields**: Excess Brazilian yields subsidize other assets
3. **Strategic Flexibility**: Adjust yields to drive growth where needed
4. **Risk Mitigation**: Diversified yield sources protect against single-asset issues
