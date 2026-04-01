# Climate Risk Modelling Quick Reference Guide

A quick reference for key concepts in climate financial risk modelling for banks.

## Climate Risk Types

### Physical Risks
- **Acute**: Extreme weather events (hurricanes, floods, wildfires)
- **Chronic**: Long-term changes (sea level rise, temperature shifts, precipitation patterns)

### Transition Risks
- **Policy/Legal**: Carbon pricing, regulations, litigation
- **Technology**: Clean tech disruption, obsolescence
- **Market**: Demand shifts, supply chain changes
- **Reputational**: Stakeholder pressure, ESG ratings

## Key Frameworks

### TCFD Four Pillars
1. **Governance**: Oversight and accountability
2. **Strategy**: Risks, opportunities, resilience
3. **Risk Management**: Integration into enterprise risk
4. **Metrics & Targets**: Performance measurement

### Risk Assessment Process
1. **Identify**: Screen portfolio for climate exposures
2. **Measure**: Quantify potential financial impacts
3. **Manage**: Set limits, implement controls
4. **Monitor**: Track metrics, adjust strategies
5. **Report**: Disclose to stakeholders

## Climate Scenarios (NGFS)

### Orderly Transition
- Early policy action
- Smooth adjustment
- Limited physical risks
- Lower economic costs

### Disorderly Transition
- Delayed action
- Abrupt changes
- Stranded assets
- Higher economic costs

### Hot House World
- Limited climate action
- Severe physical impacts
- Economic disruption
- High adaptation costs

## Risk Metrics

### Credit Risk Metrics
```
Climate VaR: Value at Risk adjusted for climate scenarios
Climate PD: Probability of Default with climate factors
Climate LGD: Loss Given Default adjusted for asset values
Financed Emissions: Scope 3 emissions from lending
```

### Portfolio Metrics
```
Green Asset Ratio = Green Assets / Total Assets
Climate Risk Concentration = High-Risk Exposure / Total Portfolio
Transition Risk Score = Weighted average sector risk
Physical Risk Exposure = Geographic risk-weighted exposure
```

### Performance Metrics
```
Carbon Intensity = Emissions / Revenue or Assets
Emissions Trajectory = YoY change in financed emissions
Transition Plan Coverage = % clients with credible plans
Green Finance Volume = New green lending/investment
```

## High-Risk Sectors (Transition)

### Very High Risk
- Coal mining and power generation
- Oil & gas extraction
- Oil refining
- Carbon-intensive chemicals

### High Risk
- Cement and concrete
- Steel manufacturing
- Aviation
- Shipping
- Agriculture (high-emission methods)

### Moderate Risk
- Automotive (ICE vehicles)
- Real estate (low efficiency)
- Conventional utilities
- Plastics manufacturing

## High-Risk Geographies (Physical)

### Flood Risk
- Coastal areas (sea level rise)
- Riverine flood zones
- Low-lying regions

### Hurricane/Cyclone Risk
- Tropical coastal regions
- Southeast US, Caribbean, Southeast Asia

### Wildfire Risk
- Mediterranean climates
- Drought-prone regions
- Forest-adjacent areas

### Water Stress
- Arid and semi-arid regions
- Over-extracted aquifer areas
- Glacier-dependent watersheds

## Data Sources

### Climate Data
- **Physical**: CMIP6, NOAA, local meteorological
- **Hazard Maps**: FEMA, EU Floods Directive, local authorities
- **Projections**: IPCC, national climate assessments

### Transition Data
- **Emissions**: CDP, company disclosures, PCAF
- **Policy**: Climate policy databases, carbon pricing initiatives
- **Technology**: IEA reports, sector associations

### Financial Data
- **ESG**: MSCI, Sustainalytics, S&P Trucost, ISS ESG
- **Credit**: Rating agencies, financial statements
- **Market**: Asset prices, sector benchmarks

## Regulatory Landscape

### Global
- **FSB TCFD**: Climate disclosure framework
- **Basel Committee**: Climate risk principles
- **NGFS**: Central bank climate scenarios

### Regional
- **EU**: Taxonomy, SFDR, EBA guidelines
- **UK**: PRA climate stress tests
- **US**: SEC climate disclosure (proposed)
- **Asia**: MAS, HKMA frameworks

## Quick Calculation Formulas

### Expected Loss (Climate-Adjusted)
```
EL = PD_climate × LGD_climate × EAD

Where:
PD_climate = Base PD × Climate Risk Multiplier
LGD_climate = Base LGD × Asset Value Adjustment
EAD = Exposure at Default
```

### Carbon Footprint (Financed Emissions)
```
Financed Emissions = Σ (Outstanding / Total Equity+Debt) × Company Emissions

For each loan/investment:
Attribution Factor = Our Exposure / (Company Equity + Debt)
Our Emissions = Attribution Factor × Company Total Emissions
```

### Climate Value at Risk (CVaR)
```
CVaR = Portfolio Value × Scenario Impact % × Probability

Example:
$100M portfolio × 15% loss in scenario × 40% probability = $6M CVaR
```

### Transition Risk Score (Simple)
```
Score = Σ (Exposure_i × Sector Risk Weight_i) / Total Exposure

Sector Risk Weights:
- Coal: 10
- Oil & Gas: 8
- Heavy Industry: 6
- Conventional Utilities: 5
- Other: 1-3
```

## Implementation Checklist

### Governance
- [ ] Assign board oversight
- [ ] Designate executive accountability
- [ ] Establish climate risk committee
- [ ] Define roles and responsibilities

### Data & Systems
- [ ] Inventory current data
- [ ] Identify data gaps
- [ ] Evaluate vendor solutions
- [ ] Integrate into risk systems

### Assessment
- [ ] Screen portfolio for climate risks
- [ ] Conduct materiality assessment
- [ ] Perform scenario analysis
- [ ] Quantify exposures

### Management
- [ ] Set risk appetite and limits
- [ ] Update policies and procedures
- [ ] Integrate into underwriting
- [ ] Develop mitigation strategies

### Monitoring & Reporting
- [ ] Define KPIs and metrics
- [ ] Establish reporting processes
- [ ] TCFD disclosure preparation
- [ ] Regulatory reporting compliance

## Common Challenges

### Data Quality
- **Challenge**: Incomplete, inconsistent climate data
- **Solution**: Start with available data, improve over time

### Uncertainty
- **Challenge**: Long time horizons, scenario uncertainty
- **Solution**: Use multiple scenarios, stress test assumptions

### Methodology
- **Challenge**: Evolving best practices, no single approach
- **Solution**: Follow industry frameworks, document choices

### Resource Constraints
- **Challenge**: Limited expertise and budget
- **Solution**: Prioritize material risks, leverage external resources

### Business Integration
- **Challenge**: Resistance to change, competing priorities
- **Solution**: Executive sponsorship, align with strategy

## Best Practices

### Start Simple
- Focus on material risks first
- Use qualitative before quantitative
- Leverage industry tools and templates
- Build capabilities over time

### Engage Stakeholders
- Involve business units in assessment
- Collaborate with clients on transition
- Partner with industry peers
- Communicate with investors

### Be Transparent
- Document assumptions and limitations
- Explain methodology choices
- Report uncertainties clearly
- Update regularly as methods improve

### Link to Strategy
- Align with business objectives
- Identify opportunities, not just risks
- Integrate into capital allocation
- Use to inform product development

## Green Finance Opportunities

### Products
- Green mortgages (energy-efficient homes)
- Sustainability-linked loans (ESG targets)
- Green bonds (certified projects)
- Transition finance (decarbonization plans)
- Renewable energy project finance

### Sectors
- Renewable energy (solar, wind, hydro)
- Energy efficiency (buildings, industry)
- Sustainable transport (EVs, public transit)
- Circular economy (recycling, reuse)
- Climate adaptation (resilient infrastructure)

### Benefits
- Revenue growth from expanding market
- Risk reduction through portfolio transition
- Regulatory advantage and recognition
- Brand enhancement and talent attraction
- Client relationship deepening

## Key Acronyms

- **TCFD**: Task Force on Climate-related Financial Disclosures
- **NGFS**: Network for Greening the Financial System
- **PCAF**: Partnership for Carbon Accounting Financials
- **CDP**: Carbon Disclosure Project
- **IPCC**: Intergovernmental Panel on Climate Change
- **CMIP**: Coupled Model Intercomparison Project
- **ESG**: Environmental, Social, Governance
- **CVaR**: Climate Value at Risk
- **PD**: Probability of Default
- **LGD**: Loss Given Default
- **EAD**: Exposure at Default
- **SFDR**: Sustainable Finance Disclosure Regulation (EU)
- **MAS**: Monetary Authority of Singapore
- **HKMA**: Hong Kong Monetary Authority
- **PRA**: Prudential Regulation Authority (UK)

## Useful Resources

### Frameworks & Standards
- TCFD Recommendations: www.fsb-tcfd.org
- NGFS Scenarios: www.ngfs.net
- PCAF Standard: www.carbonaccountingfinancials.com

### Climate Science
- IPCC Reports: www.ipcc.ch
- Climate Data: www.worldclim.org
- Hazard Maps: National authorities, FEMA, etc.

### Industry Guidance
- UNEP FI: www.unepfi.org
- IIF Sustainable Finance: www.iif.com
- Banking associations: Regional/national

### Training & Certification
- CFA ESG Certificate
- GARP Sustainability & Climate Risk Certificate
- Climate risk courses: Universities, online platforms

---

## Getting Started: 30-Day Action Plan

### Week 1: Foundation
- [ ] Review TCFD framework
- [ ] Assess current state (governance, data, processes)
- [ ] Identify key stakeholders
- [ ] Secure executive sponsorship

### Week 2: Assessment
- [ ] Screen portfolio for climate exposures
- [ ] Identify material risk concentrations
- [ ] Map data availability
- [ ] Engage with industry peers

### Week 3: Planning
- [ ] Define initial scope and objectives
- [ ] Select priority sectors/geographies
- [ ] Identify quick wins
- [ ] Develop implementation roadmap

### Week 4: Execution
- [ ] Launch pilot assessment
- [ ] Engage with clients
- [ ] Begin capability building
- [ ] Communicate progress

---

**For comprehensive coverage, see:**
- [CLIMATE_RISK_MODELLING.md](CLIMATE_RISK_MODELLING.md) - Full framework and methodology
- [CLIMATE_RISK_EXAMPLES.md](CLIMATE_RISK_EXAMPLES.md) - Practical examples and case studies

**Document Version**: 1.0  
**Last Updated**: December 2024
