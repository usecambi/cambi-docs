---
icon: person-skating
---

# Risk Factors and Mitigation

**Synthetic Stability Risks:**

* **Depeg risk**: Mitigated through over-collateralization (150% minimum) and automated liquidations via Uniswap V4
* **Oracle manipulation**: Multi-source price feeds (Pyth, Chainlink/API3 & proprietary) with circuit breakers
* **RWA defaults**: Diversified portfolio across 50+ receivables, insurance buffer fund (2% of TVL)
* **Yield distribution risk**: Isolated smart contracts ensure base yields even if optimization layer fails

**Regulatory Risks:**

* **Securities classification**: Synthetics are collateral receipts, not investment contracts
* **Cross-border restrictions**: Compliant KYC for institutional vaults while maintaining permissionless retail access
* **RWA custody**: Licensed partners (Liqi) handle securities custody; we only interact with tokens

**Technical Risks:**

* **Smart contract bugs**: Multi-audit strategy + bug bounties
* **Composability breaks**: Capped wrapped versions (wcmBTC) ensure sustainable DeFi compatibility
* **Liquidation cascades**: Isolated vault architecture prevents contagion

**Currency Risk Elimination (cmUSD):**

* USD-denominated receivables eliminate FX exposure
* Counterparties are Brazilian companies with USD revenues
* Natural hedge through business model alignment
* No need for expensive derivative hedging services

**Institutional Risk Parameters (cmBTC):**

* Higher collateralization ratios for institutions (200% vs 150%)
* Dedicated liquidation pools to prevent cascades
* Automated rebalancing for large positions

**Unified Pool Risk Isolation:**

* Each asset vault maintains independent solvency
* Optimization layer can be paused without affecting base yields
* Emergency withdrawal preserves principal + base yield
* Circuit breakers prevent excessive redistribution
