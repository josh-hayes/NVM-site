# Hazard

The hazard component describes the volcanic processes that may affect exposed assets. In the current NVM implementation, the primary hazard is **volcanic ashfall** from New Zealand volcanoes.

There are three critical components to hazard:

- Probability  
- Hazard Intensity  
- Spatial extent  

For volcanic ashfall, the hazard intensity measure is commonly represented using ash thickness or loading. These measures are important because they can be related to building damage mechanisms such as roof loading, ash ingress, abrasion, corrosion, and cleanup requirements.

## Probabilistic

The NVM uses a probabilistic approach rather than a single deterministic eruption scenario. This means the model represents many possible volcanic futures, including uncertainty in eruption occurrence, eruption magnitude, wind conditions, ash dispersal, and resulting ashfall footprints.

In the ashfall building damage report, probabilistic eruption occurrence and magnitude information is combined with ashfall hazard modelling to estimate the likelihood of ashfall intensities at locations across New Zealand. This supports outputs such as:

- Spatial variation in ashfall risk
- Contributions from different volcanic sources
- Loss exceedance probabilities
- Average annual loss estimates

The probabilistic framing allows results to be compared consistently across regions and volcanic sources, while keeping uncertainty explicit.

## Multi-hazard eruption scenarios

The current national implementation focuses on ashfall building damage. However, volcanic eruptions can produce multiple hazards, including ashfall, pyroclastic density currents, lahars, lava flows, debris flows, ballistic projectiles, and gas emissions.

The NVM is designed to evolve toward multi-hazard volcanic risk assessment. The 2026 report notes that fragility functions were also developed for building damage from volcanic mass-flow hazards, although these were not applied in the ashfall-focused national loss analysis. These functions provide a starting point for future model components that represent hazards beyond ashfall.
