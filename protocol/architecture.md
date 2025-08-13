---
icon: sitemap
---

# Architecture and Mechanics

The Cambi Protocol operates on a collateralized debt position (CDP) model, evolved from the battle-tested MakerDAO architecture but optimized for emerging market dynamics and Bitcoin collateralization. Users deposit collateral assets (primarily BTC and stablecoins, but yield-bearing ETH is also accepted) and mint synthetic assets against them. However, unlike traditional CDPs that simply create synthetic representations, Cambi's synthetics are actively yield-bearing through (gradually) on-chain RWA investment strategies.

The protocol flow works as follows:

* A user in São Paulo wants to protect their savings from inflation while maintaining spending power in Brazilian Reais.
* They transfer R$10,000 via Pix, Brazil's instant payment system, which gets automatically converted to Bitcoin through our on-ramp partners.
* This Bitcoin is then deposited into the protocol as collateral. The user chooses their risk profile – let's say "Balanced" with 40% RWA exposure – and mints cmBRL against their collateral.
* Immediately, their cmBRL begins earning yield from a combination of Bitcoin lending (1-4% from platforms like Aave or Morpho through our yield-optimizing partner Fungi) and Brazilian receivables (20%+ yield from tokenized assets via partners like Liqi). This cmBRL can be used to buy groceries, pay for rent, or even attached to a crypto-native credit card.
* Alternatively, the user can mint cmUSD and automatically protect their holdings against local inflation while still remaining liquid and earning yield. This is an objectively superior alternative to other dollarization options offered by players like Nomad or Wise.
* On top of that, users also have the option to mint cmBTC and stay exposed only to the new digital gold standard, wrapping it to leverage it's composability across DeFi or just follow El Salvador's reserve value mentality - but with yield on top!

The genius of the system lies in the yield generation mechanism. Unlike Volcano Bonds that promise yields from future Bitcoin mining or appreciation, Cambi generates real, immediate yield from proven fixed-income assets. Through partnerships with tokenization platforms like Liqi and Etherfuse, the protocol accesses a diverse portfolio of Brazilian receivables, LatAm government bonds, and private credit instruments. These aren't experimental DeFi yields – they're the same instruments that Brazilian banks and funds have used for decades to generate returns.

The protocol manages risk through multiple layers:

* First, over-collateralization ensures that even if Bitcoin drops significantly, positions remain solvent.
* Second, the RWA portfolio is actively managed using a combination of human expertise, DAO governance, and AI-powered risk assessment & tooling.
* Third, yields are laddered across different maturities – as 30-day receivables mature and pay out, the funds are automatically rolled into new instruments, creating a continuous yield stream regardless of individual user lock periods. This accrues back into the synthetics with are rebased automatically.
