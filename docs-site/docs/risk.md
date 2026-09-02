# Impact/Risk

Impact and risk models combine hazard, exposure, and vulnerability.

## Framework

Risk = Hazard × Exposure × Vulnerability

Within the NVM, these components are interpreted as:

- **Hazard**: the probability, intensity, and spatial footprint of volcanic hazards such as ashfall
- **Exposure**: the buildings, infrastructure, land uses, or other assets located in places that may be affected
- **Vulnerability**: the expected response of those assets when exposed to a given hazard intensity

The current ashfall building implementation combines probabilistic ashfall hazard, national building exposure, and New Zealand-specific building vulnerability models to estimate damage and financial loss.

## Ashfall building damage and loss

The 2026 NVM report presents the first national probabilistic assessment of volcanic ash risk to New Zealand buildings. The model estimates risk by running ashfall hazard information through building vulnerability relationships and loss calculations.

Key risk metrics include:

- Damage probabilities for representative building types
- Repair cost estimates
- Average annual loss
- Loss exceedance probabilities
- Regional and volcanic-source contributions to national risk

These outputs are intended to support consistent comparison across regions and volcanic sources. They are most useful for strategic planning, resilience investment, emergency management preparedness, and financial risk assessment.

## Uncertainty

Uncertainty is a central part of the NVM framework. It arises from hazard modelling, eruption occurrence and magnitude assumptions, building exposure information, vulnerability relationships, and loss modelling assumptions.

The current implementation explicitly incorporates uncertainty in building response through expert elicitation and calibrated aggregation. Results should therefore be interpreted as probabilistic estimates rather than precise predictions for a future eruption.
