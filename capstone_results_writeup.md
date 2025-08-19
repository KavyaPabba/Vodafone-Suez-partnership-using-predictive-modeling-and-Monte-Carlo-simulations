# Executive Results & Methodology (Press‑facts only)

## Data Collection (Open Sources)
- SUEZ × Vodafone PR: 2M NB‑IoT smart meters by 2030; up to 15% consumption reduction.
- Orange–Veolia/Birdz PR: 3M water meters connected (LoRaWAN) in France.
  See appendix CSVs for source titles/URLs.

## Wrangling & League
- Consolidated league: `eu_telco_energy_league_press_facts.csv` (EU/UK focus). Pace KPI → `league_ranked_speed.csv`.

## Predictive Modelling (MODEL)
- Logistic S‑curve for Vodafone–SUEZ: K=2,000,000, start=2024, target=2030, r=0.55; milestones 50%=2027, 80%=2030.
- Projection CSV: `vodafone_suez_projection_from_public_target.csv`; Plot: `vodafone_suez_adoption.png`.

## Value & ROI (MODEL)
- Parameters: annual spend €300, savings 15%, capex/meter €100.
- Payback year: 2027; ROI (horizon): 0.88; NPV: €98,208,706; IRR (annual): 73.48%.
- Outputs: `vodafone_suez_value_curve_MODEL.png`, `vodafone_suez_roi_summary.csv`.

## Sensitivity & Monte Carlo (MODEL)
- One‑way sensitivity table: `vodafone_suez_sensitivity_one_way.csv`; tornado: `vodafone_suez_sensitivity_units_tornado.png`.
- Monte Carlo summary: `vodafone_suez_monte_carlo_summary.csv` (units by 2030; time to 1M meters).

## Comparative KPIs & Countries
- ROI bar (available metrics) → `roi_comparison.png`; KPI radar → `kpi_radar.png`.
- Sector scale chart: `plot_scale_smart_water.png`.
- Top countries (allocation MODEL): `top_countries_allocated_MODEL.csv`, `top_countries_bar_MODEL.png`.

**Note:** MODEL outputs derive from public endpoints and benchmark parameters; replace with company figures to refine ROI.
