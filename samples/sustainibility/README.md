# DEA Sustainability Analysis: Complete Dataset

We've successfully compiled comprehensive sustainability data for Data Envelopment Analysis across 28 countries with 4 input and 4 output metrics from authoritative sources.

## Data Sources and Methodology

### Input Metrics (Undesirable Outputs/Resource Consumption)

**1. CO2 Emissions Per Capita (tonnes CO2, 2023)**
- **Source:** EDGAR Database (European Commission JRC/IEA)
- **Rationale:** Direct measure of greenhouse gas environmental pressure from fossil fuel consumption
- **Range:** 1.71 (Colombia) to 14.66 (Australia)

**2. Energy Use Per Capita (kg oil equivalent, 2022)**
- **Source:** World Bank World Development Indicators (EG.USE.PCAP.KG.OE)
- **Rationale:** Total primary energy supply representing resource consumption intensity
- **Range:** 603.0 (Morocco) to 7,632.3 (Canada)

**3. Material Footprint Per Capita (tonnes, 2019-2020)**
- **Source:** UNEP IRP Global Material Flows Database / Eurostat (SDG Indicators 12.2.1/8.4.1)
- **Rationale:** Comprehensive measure of raw material extraction to meet consumption (biomass, fossil fuels, metals, minerals)
- **Range:** 9.0 (Morocco) to 42.9 (Finland)

**4. Ecological Footprint Per Capita (global hectares, 2012)**
- **Source:** Global Footprint Network National Footprint Accounts
- **Rationale:** Aggregate measure of environmental pressure across carbon, cropland, grazing, forests, fishing, and built-up land
- **Range:** 1.53 (Morocco) to 9.31 (Australia)

### Output Metrics (Desirable Outcomes)

**1. Environmental Performance Index Score (0-100, 2024)**
- **Source:** Yale Center for Environmental Law & Policy
- **Rationale:** Comprehensive environmental performance across 58 indicators including climate, air quality, biodiversity, ecosystem health
- **Range:** 47.9 (South Africa) to 75.7 (Estonia)

**2. Human Development Index (0-1, 2023)**
- **Source:** UNDP Human Development Report 2025
- **Rationale:** Composite social sustainability measure capturing health (life expectancy), education, and living standards
- **Range:** 0.710 (Morocco) to 0.962 (Denmark)

**3. Renewable Energy Consumption (%, 2021-2022)**
- **Source:** World Bank WDI (EG.FEC.RNEW.ZS) / IEA
- **Rationale:** Share of sustainable energy in total final energy consumption, indicating transition from fossil fuels
- **Range:** 0.6% (Singapore) to 50.3% (Sweden)

**4. Life Expectancy at Birth (years, 2023)**
- **Source:** UNDP HDR 2025 / UN Population Division
- **Rationale:** Ultimate measure of population health and social well-being reflecting healthcare, nutrition, environment quality
- **Range:** 66.1 (South Africa) to 84.7 (Japan)

---

## DEA Analysis Suitability

**✓ DMU Requirement:** 28 countries ≥ 24 (minimum 3 × 8 variables)  
**✓ Input Orientation:** All inputs represent resources consumed or environmental pressures (lower is better for efficiency)  
**✓ Output Orientation:** All outputs represent positive sustainability outcomes (higher is better)  
**✓ Isotonicity:** Outputs expected to increase with inputs under efficient operation  
**✓ Data Quality:** All from internationally recognized, peer-reviewed sources  
**✓ Recent Data:** Primarily 2019-2024 (most recent available)  
**✓ Geographic Diversity:** Covers 6 continents, varied development levels  
**✓ Discrimination Power:** Wide value ranges ensure model can distinguish efficiency differences

### Key Analytical Insights

**Efficiency Leaders (Likely):**
- **Environmental:** Estonia (highest EPI), Sweden, Finland
- **Social:** Denmark (highest HDI), Nordic countries
- **Resource Efficiency:** Morocco, Colombia (low inputs, reasonable outputs)
- **Renewable Energy:** Sweden (50.3%), Brazil (47.5%), Finland (43.1%)

**Efficiency Challenges (Likely):**
- **High Resource Intensity:** USA, Canada, Australia (high on all input metrics)
- **Environmental Performance:** China, South Africa (lower EPI scores)
- **Development Gaps:** Morocco, Thailand (lower HDI despite some efficiencies)

### DEA Model Recommendations

1. **Model Type:** Use both CCR (constant returns to scale) and BCC (variable returns to scale) models to assess scale efficiency
2. **Orientation:** Output-oriented preferred (maximize sustainability outcomes given resource constraints)
3. **Slack Analysis:** Examine input/output slacks to identify specific improvement areas for inefficient DMUs
4. **Sensitivity Analysis:** Test stability with different metric combinations given data year variations
5. **Peer Analysis:** Identify reference sets for inefficient countries to learn best practices

---

## Data Quality Notes

- **Temporal Consistency:** Minor year differences (2012-2024) unavoidable due to data availability; represents best available recent data
- **Material Footprint:** Some values estimated from authoritative sources (UNEP IRP) where exact 2019-2020 country data unavailable; Finland (42.9) is exact EEA-reported value
- **Ecological Footprint:** 2012 data older but most comprehensive available; provides stable baseline for cross-country comparison
- **All Values:** Verified against multiple sources where possible; priority given to primary international organizations (UN, World Bank, OECD, Yale)

This dataset enables robust DEA analysis to identify sustainability efficiency leaders, benchmark performance, and provide policy insights for countries seeking to improve their sustainability outcomes relative to resource consumption.



