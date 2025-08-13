---
icon: gear-code
---

# Technical Implementation

Standing on the shoulders of giants like MakerDAO, Cambi inherits battle-tested CDP mechanics while adding novel features for RWA integration and yield distribution. The smart contract architecture consists of several key components working in harmony to deliver a secure, efficient system.

The Vault Manager contract handles user deposits and strategy allocation. When users deposit Bitcoin, the contract assigns it to their chosen vault strategy and mints the appropriate synthetic tokens. The beauty of this system is its simplicity – users interact with a single contract regardless of their chosen strategy, while backend logic handles the complexity of yield generation.

The RWA Oracle system represents one of our key innovations. Traditional DeFi oracles like Pyth provide crypto price feeds, but RWA yields require different infrastructure. We're building custom oracles that track receivables performance, maturity schedules, and yield realizations. This data feeds into our rebalancing algorithms, ensuring optimal portfolio allocation across different receivables categories.

The daily rebasing mechanism, inspired by protocols like Ampleforth but applied to yield distribution rather than price stability, requires careful implementation to avoid common pitfalls. Each synthetic token tracks a "rebase multiplier" that increases daily based on realized yields. This creates the user experience of watching balances grow while maintaining composability with DeFi protocols through wrapped versions.

Security remains paramount given we're handling both volatile crypto assets and real-world financial instruments. Beyond standard smart contract audits from firms, we're implementing additional safeguards specific to RWA integration. These include multi-signature controls on RWA purchases, time delays on large rebalancing operations, and circuit breakers that pause operations if unusual yield patterns are detected.

### Add a new block

{% stepper %}
{% step %}
### Open the insert block menu

Press `/` on your keyboard to open the insert block menu.
{% endstep %}

{% step %}
### Search for the block you need&#x20;

Try searching for “Stepper”, for exampe, to insert the stepper block.
{% endstep %}

{% step %}
### Insert and edit your block

Click or press Enter to insert your block. From here, you’ll be able to edit it as needed.
{% endstep %}
{% endstepper %}

