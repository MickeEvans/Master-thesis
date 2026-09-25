# Companies

- Vermiculus
    - internship@vermiculus.se
    - Vi har hört gott om er genom Yelena och Felicia, vi har kontakt med samma handledare och vi har tönkt ha han som handledare igen. 
- Ericsson

- Vattenfall
Pitch 1: Deep hedging of renewable production and price-area risk
A wind or solar portfolio faces volume risk and price risk at once, and they are correlated: prices tend to fall exactly when it's windy (cannibalization). On top of that, liquid hedges are mostly on the Nordic system price, while revenue is earned in a bidding area (SE1–SE4), which leaves basis risk. Classical delta hedging handles none of this well. We would build a deep hedging agent that jointly models weather-driven production, area prices and futures and EPADs. It would learn hedge ratios that minimize a risk measure of portfolio revenue, benchmarked against Vattenfall's current static hedging approach. Value: a data-driven hedging strategy for renewable assets and PPAs, and a tool for pricing the risk in new PPA contracts.

Pitch 2: Machine learning for hydropower scheduling as stochastic control
Hydro reservoir management is a classic stochastic optimal control problem. It is traditionally solved with stochastic dynamic programming ("water values"), which scales poorly with multiple reservoirs and uncertainty sources. We would apply deep RL or deep BSDE methods to compute water values and dispatch policies. We would validate them against SDP on a small system where it is tractable, then scale to settings where it isn't. Value: potentially faster and more flexible production planning, directly tied to how hydro is bid into the market.