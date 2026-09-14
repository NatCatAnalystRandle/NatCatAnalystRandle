# Hi, I’m Emmanuel Randle

I am a PhD researcher in Structural Engineering at Oregon State University. I develop computational models that connect earthquake and tsunami hazards with building damage, financial loss, insurance, reinsurance, and community consequences.

My research and technical interests include:

- earthquake and tsunami risk;
- catastrophe modeling;
- spatial correlation and statistical dependence;
- building fragility and damage modeling;
- insurance, reinsurance, and insurance-linked securities;
- portfolio risk and resilience finance;
- population displacement and disaster recovery.

## Featured catastrophe-risk project

### Seismic Correlation and Insurance Loss

I developed a reproducible, 13-notebook earthquake catastrophe-risk workflow that connects:

**USGS seismic sources → stochastic event catalogs → ground-motion fields → building damage → portfolio loss → insurance → reinsurance → parametric risk transfer**

The project uses the USGS 2018 National Seismic Hazard Model and a 2,000,000-year stochastic catalog containing 10,630 earthquake occurrences. It models structural and nonstructural damage across a 470-building portfolio in Seaside, Oregon.

### What the project evaluates

- Independent and spatially correlated ground-motion fields
- Aldea et al. and Goda–Atkinson spatial-correlation models
- Structural and nonstructural damage states
- Ground-up, gross insured, uninsured, ceded, and retained losses
- Average annual loss, AEP, OEP, and return-period PML
- Occurrence excess-of-loss and annual aggregate reinsurance
- TVaR-based tail capital and required reinsurance limits
- Parametric catastrophe-bond basis risk
- Paired bootstrap uncertainty using common event catalogs and random streams

### Selected result

For this demonstration portfolio, applying the same occurrence excess-of-loss program across all dependence cases increased the modeled 2,500-year retained AEP PML from **$19.36 million** in the independent case to **$33.27 million** and **$34.08 million** under the two spatial-correlation models.

The reinsurance limit required to restore the independent case’s retained 2,500-year PML increased from approximately **$61.84 million** to **$75.90 million** and **$76.67 million**. These are model-conditioned research results rather than insurance placement recommendations.

### Validation and reproducibility

- 13 completed notebooks
- 92 automated tests passed
- 65 upstream artifact checks passed
- 14 final synthesis checks passed
- Zero critical validation failures
- Deterministic random streams, restartable processing, SHA-256 artifact verification, and explicit accounting reconciliation

[Explore the validated v2.0.0 project](https://github.com/NatCatAnalystRandle/seismic-correlation-insurance-loss/tree/v2.0.0)

[Read the Phase 2 results report](https://github.com/NatCatAnalystRandle/seismic-correlation-insurance-loss/blob/v2.0.0/data/metadata/phase_2/notebook_13_phase_2_results/notebook_13_results_report.md)

[View the v2.0.0 release](https://github.com/NatCatAnalystRandle/seismic-correlation-insurance-loss/releases/tag/v2.0.0)

## Research and technical interests

- Earthquake and tsunami risk assessment
- Probabilistic catastrophe-risk modeling
- Spatial correlation and uncertainty propagation
- HAZUS-based building damage modeling
- Stochastic event catalogs and Monte Carlo simulation
- Insurance and reinsurance analytics
- Parametric insurance and catastrophe bonds
- Community resilience and population displacement

## Tools and methods

- Python and Jupyter
- Git and GitHub
- USGS National Seismic Hazard Models
- HAZUS-based fragility and damage models
- Monte Carlo simulation
- Statistical dependence modeling
- Geospatial analysis
- AAL, AEP, OEP, PML, VaR, and TVaR
- Insurance and reinsurance loss calculations
- Reproducible scientific computing

## Current affiliation

**PhD Researcher, Oregon State University**

## Connect with me

- [LinkedIn](https://www.linkedin.com/in/emmanuel-randle/)
- [Email](mailto:randlee@oregonstate.edu)
- [Personal website](https://natcatanalystrandle.github.io/)
