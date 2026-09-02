# National Volcano Model

The National Volcano Model (NVM) is a framework for understanding volcanic hazard, impact, and risk across Aotearoa New Zealand. It is designed to provide consistent, decision-relevant information that supports planning, preparedness, and resilience across multiple sectors and scales.

---

## Purpose

Volcanic eruptions can affect communities, infrastructure, and economies across wide areas, often in complex and interconnected ways. However, information about volcanic hazards and their consequences is typically fragmented, difficult to compare, or not directly aligned with decision-making needs.

The NVM addresses this gap by providing a **nationally consistent approach** to modelling volcanic hazard and translating it into potential impacts and risks. Its purpose is to support:

- Emergency management and response planning  
- Infrastructure and lifeline resilience planning  
- Government decision-making and policy development  
- Strategic risk assessment at regional and national scales  

---

## What the model does

The NVM integrates multiple components of risk modelling into a single framework:

- **Hazard** — representation of volcanic processes (e.g., ashfall) and their spatial extent and intensity  
- **Exposure** — the assets, systems, and populations that may be affected
- **Vulnerability** — relationships between hazard intensity and expected consequences  
- **Risk** — the combination of hazard, exposure, and vulnerability to estimate potential impacts  

By linking these components, the model moves beyond describing hazards to estimating **what those hazards mean in practice**.

---

## Key principles

The development of the NVM is guided by several core principles:

### Consistency
A common modelling framework is used across New Zealand, allowing results to be compared between regions, hazards, and scenarios.

### Decision relevance
Outputs are designed to support real-world decisions, rather than purely academic analysis.

### Scalability
The framework can operate at multiple spatial scales, from local case studies to national assessments.

### Extensibility
The model is designed to evolve over time, incorporating additional hazards, assets, and modelling approaches.

---

## Current scope

The current implementation of the NVM focuses primarily on **volcanic ashfall impacts on buildings**, using probabilistic hazard modelling, national building exposure information, and vulnerability relationships to estimate damage and loss.

The first technical implementation is documented in:

> Hayes, J.L.; Williams, J.H.; Magill, C.R.; O'Leary, T.M.; Bebbington, M.; Wilson, T.M.; Leonard, G.S.; Fitzgerald, R.H.; Craig, H.; Lindsay, J. 2026. *National Volcano Model: Probabilistic volcanic ash building damage*. GNS Science report 2026/21. DOI: [10.21420/NSEH-1881](https://doi.org/10.21420/NSEH-1881).

This ashfall-focused component brings together:

- Probabilistic eruption occurrence and magnitude information
- Ashfall hazard modelling using Tephra2
- A national building exposure dataset
- New Zealand-specific building vulnerability models developed through structured expert elicitation
- Probabilistic estimates of building damage, repair cost, average annual loss, and loss exceedance probability

This provides a foundational capability that can be expanded to include:

- Additional hazards, including volcanic mass-flow hazards such as pyroclastic density currents, lahars, and lava flows
- Infrastructure systems (e.g., transport, power, water)  
- Broader societal impacts and disruption  

---

## Why this matters

New Zealand has multiple active volcanic systems capable of producing widespread impacts. Understanding these impacts in a consistent and comparable way is essential for:

- Identifying areas of higher risk  
- Prioritising resilience investments  
- Supporting coordinated planning across sectors  
- Improving preparedness for large-scale events  

The NVM provides a step toward a more integrated, national-scale understanding of volcanic risk.

---

## How to use this documentation

This documentation provides an overview of the structure, components, and outputs of the model.
 
- The **Model Components** section details hazard, vulnerability, and risk  
- The **Outputs** section explains what the model produces  
- The **Guidance** section outlines how results should be interpreted  

---
