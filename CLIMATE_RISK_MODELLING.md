# Financial Risk Modelling from Climate Change for Banks

## Executive Summary

Climate change poses significant financial risks to the banking sector. This guide provides an introduction to understanding, assessing, and modelling climate-related financial risks in banking institutions.

## Table of Contents

1. [Introduction to Climate Financial Risk](#introduction-to-climate-financial-risk)
2. [Types of Climate Risks](#types-of-climate-risks)
3. [Regulatory Framework](#regulatory-framework)
4. [Risk Assessment Methodologies](#risk-assessment-methodologies)
5. [Climate Risk Modelling Techniques](#climate-risk-modelling-techniques)
6. [Data Sources and Scenario Analysis](#data-sources-and-scenario-analysis)
7. [Implementation Framework for Banks](#implementation-framework-for-banks)
8. [Best Practices and Recommendations](#best-practices-and-recommendations)

---

## Introduction to Climate Financial Risk

Climate change creates systemic risks that can affect the financial stability of banking institutions through multiple transmission channels:

- **Asset valuation changes**: Climate events can decrease the value of physical assets
- **Credit risk increases**: Borrowers may face difficulties repaying loans due to climate impacts
- **Operational disruptions**: Physical events can disrupt banking operations
- **Market volatility**: Transition to low-carbon economy can create market shifts
- **Reputational risk**: Stakeholder expectations regarding environmental responsibility

### Why Climate Risk Matters for Banks

1. **Financial Stability**: Climate events can trigger defaults and liquidity issues
2. **Regulatory Compliance**: Increasing regulatory requirements globally
3. **Investor Pressure**: ESG considerations driving investment decisions
4. **Strategic Planning**: Long-term business sustainability
5. **Competitive Advantage**: Early adopters can capture green finance opportunities

---

## Types of Climate Risks

### 1. Physical Risks

Physical risks arise from direct impacts of climate-related events and environmental changes.

#### Acute Physical Risks
- **Extreme weather events**: Hurricanes, floods, wildfires, droughts
- **Impact on assets**: Property damage, business interruption
- **Examples**: 
  - Flood damage to mortgaged properties
  - Hurricane impact on commercial real estate portfolios
  - Wildfire risks to agricultural loans

#### Chronic Physical Risks
- **Long-term climate patterns**: Rising sea levels, temperature changes, precipitation changes
- **Gradual degradation**: Reduced agricultural productivity, water scarcity
- **Examples**:
  - Coastal property depreciation due to sea level rise
  - Agricultural loan defaults due to changing growing conditions
  - Infrastructure degradation from temperature extremes

### 2. Transition Risks

Transition risks emerge from the shift toward a low-carbon economy.

#### Policy and Legal Risks
- **Carbon pricing mechanisms**: Carbon taxes, emissions trading schemes
- **Regulatory changes**: Stricter environmental regulations
- **Litigation**: Climate-related lawsuits
- **Examples**:
  - Stranded assets in fossil fuel sector
  - Compliance costs for high-emission industries
  - Legal liabilities for environmental damages

#### Technology Risks
- **Technological disruption**: Clean energy, electric vehicles, energy efficiency
- **Obsolescence**: Legacy technologies becoming uncompetitive
- **Examples**:
  - Internal combustion engine manufacturers facing obsolescence
  - Coal-fired power plants becoming uneconomical
  - Energy-intensive processes losing competitiveness

#### Market Risks
- **Demand shifts**: Consumer preferences for sustainable products
- **Supply chain disruptions**: Raw material availability changes
- **Examples**:
  - Declining demand for fossil fuel products
  - Repricing of carbon-intensive assets
  - Market volatility in transition-sensitive sectors

#### Reputational Risks
- **Stakeholder perception**: Negative publicity from climate-related activities
- **ESG ratings impact**: Lower scores affecting funding costs
- **Examples**:
  - Loss of customers due to fossil fuel financing
  - Difficulty attracting talent
  - Divestment campaigns

---

## Regulatory Framework

### Task Force on Climate-related Financial Disclosures (TCFD)

The TCFD framework provides recommendations across four pillars:

1. **Governance**: Board oversight and management's role
2. **Strategy**: Climate-related risks and opportunities
3. **Risk Management**: Identification, assessment, and management processes
4. **Metrics and Targets**: Performance indicators and emissions targets

### Basel Committee on Banking Supervision

- **Principles for Climate-related Financial Risks**: Integration into risk management
- **Capital adequacy considerations**: Climate risks in capital planning
- **Stress testing**: Climate scenario analysis

### Regional Regulatory Requirements

#### European Union
- **EU Taxonomy**: Classification of sustainable activities
- **SFDR**: Sustainability disclosure requirements
- **Green Asset Ratio**: Measuring green asset exposure

#### United States
- **SEC Climate Disclosure Rules**: Proposed climate risk disclosures
- **Federal Reserve**: Climate stress testing frameworks
- **OCC Guidelines**: Climate risk management expectations

#### Asia-Pacific
- **MAS Guidelines (Singapore)**: Environmental risk management
- **HKMA (Hong Kong)**: Climate risk management framework
- **PRA (UK)**: Climate Biennial Exploratory Scenario (CBES)

---

## Risk Assessment Methodologies

### 1. Climate Risk Identification

**Process Steps:**
1. **Portfolio screening**: Identify climate-sensitive exposures
2. **Geographic analysis**: Map physical risk exposure by location
3. **Sector analysis**: Assess transition risk by industry
4. **Counterparty assessment**: Evaluate borrower climate resilience

**Tools and Techniques:**
- Heat maps for geographic risk concentration
- Sector-based risk matrices
- Climate risk questionnaires for clients
- Third-party ESG data providers

### 2. Climate Risk Measurement

**Quantitative Approaches:**

#### Value at Risk (VaR) Extensions
- **Climate VaR**: Incorporating climate scenarios into VaR calculations
- **Probability distributions**: Adjusting for climate-related tail risks

#### Expected Loss Models
```
Expected Loss = PD × LGD × EAD

Where:
PD = Probability of Default (adjusted for climate factors)
LGD = Loss Given Default (adjusted for collateral value changes)
EAD = Exposure at Default
```

#### Climate-Adjusted Credit Rating Models
- Incorporate climate risk factors into credit scoring
- Sector-specific climate risk adjustments
- Geographic risk overlays

### 3. Climate Scenario Analysis

**Scenario Types:**

1. **Orderly Transition**: Smooth, early policy action
   - Carbon price increases gradually
   - Technology develops as expected
   - Economic disruption minimized

2. **Disorderly Transition**: Late, sudden policy action
   - Abrupt carbon price increases
   - Market disruption and stranded assets
   - Higher economic costs

3. **Hot House World**: Limited climate action
   - Severe physical climate impacts
   - High adaptation costs
   - Significant economic disruption

**Climate Scenario Frameworks:**
- **NGFS Scenarios**: Network for Greening the Financial System
- **IEA Pathways**: International Energy Agency scenarios
- **IPCC Scenarios**: Representative Concentration Pathways (RCPs)

---

## Climate Risk Modelling Techniques

### 1. Bottom-Up Approaches

#### Loan-Level Modelling
```
Climate Risk Score = f(Physical Risk, Transition Risk, Counterparty Resilience)

Components:
- Physical risk exposure (location, asset type)
- Transition risk exposure (sector, emissions intensity)
- Borrower adaptation capacity
- Collateral climate sensitivity
```

#### Portfolio Aggregation
- Sum individual exposures
- Apply correlation assumptions
- Consider diversification effects
- Stress concentration risks

### 2. Top-Down Approaches

#### Macroeconomic Models
- Link climate scenarios to macro variables
- GDP impact from climate events
- Sector-level output changes
- Employment and income effects

#### Climate-Macro Transmission Channels
```
Climate Event → Economic Impact → Financial Impact

Example Chain:
Drought → Agricultural output ↓ → Farm income ↓ → 
Loan defaults ↑ → Bank credit losses ↑
```

### 3. Hybrid Approaches

Combine bottom-up and top-down methods:
1. Use macro models for scenario generation
2. Apply sector-level adjustments
3. Model individual exposures
4. Aggregate to portfolio level
5. Compare with top-down results

### 4. Machine Learning and AI Techniques

**Applications:**
- **Predictive Analytics**: Default prediction incorporating climate variables
- **Natural Language Processing**: Analyzing climate-related news and disclosures
- **Satellite Imagery Analysis**: Monitoring physical asset conditions
- **Pattern Recognition**: Identifying climate risk indicators

**Example ML Model:**
```python
# Simplified climate risk classification
features = [
    'geographic_risk_score',
    'sector_emissions_intensity',
    'property_flood_zone',
    'counterparty_climate_score',
    'carbon_price_sensitivity'
]

model = RandomForestClassifier()
model.fit(X_train[features], y_train)  # y = high/medium/low risk
```

### 5. Stress Testing Frameworks

**Single-Factor Stress Tests:**
- Carbon price shock (e.g., $100/ton CO2)
- Extreme weather event (e.g., 100-year flood)
- Sector-specific shock (e.g., fossil fuel demand collapse)

**Multi-Factor Stress Tests:**
- Combined physical and transition scenarios
- Correlated shocks across geographies
- Compound climate events

**Reverse Stress Testing:**
- Identify climate scenarios that would cause bank failure
- Determine breaking points
- Inform risk appetite and limits

---

## Data Sources and Scenario Analysis

### Climate Data Sources

#### Physical Risk Data
1. **Climate Models**: CMIP6 (Coupled Model Intercomparison Project)
2. **Weather Data**: NOAA, local meteorological services
3. **Hazard Maps**: Flood zones, wildfire risk areas, hurricane tracks
4. **Geospatial Data**: Property locations, elevation, proximity to risks

**Key Providers:**
- Jupiter Intelligence
- Four Twenty Seven (Moody's)
- Climanomics
- riskthinking.AI

#### Transition Risk Data
1. **Emissions Data**: CDP (Carbon Disclosure Project), company reports
2. **Policy Databases**: Climate policy tracker, carbon pricing initiatives
3. **Technology Trends**: IEA technology reports, patents analysis
4. **Market Data**: Carbon prices, renewable energy costs

**Key Providers:**
- S&P Trucost
- MSCI ESG Research
- Sustainalytics
- ISS ESG

#### Financial and Economic Data
1. **Company Financials**: Annual reports, SEC filings
2. **Sector Benchmarks**: Industry associations, research firms
3. **Macroeconomic Indicators**: GDP, inflation, employment
4. **Asset Prices**: Real estate values, commodity prices

### Climate Scenario Development

#### Step 1: Define Scenario Parameters
- Time horizon (e.g., 2030, 2050, 2100)
- Temperature pathway (e.g., 1.5°C, 2°C, 4°C)
- Policy assumptions
- Technology assumptions

#### Step 2: Generate Climate Outcomes
- Physical changes (temperature, precipitation, sea level)
- Extreme event frequency and severity
- Regional variations

#### Step 3: Translate to Economic Impacts
```
Climate Outcome → Sector Impact → Financial Impact

Example:
2°C warming → 10% agricultural yield ↓ → 
20% default rate ↑ in agricultural loans
```

#### Step 4: Model Financial Metrics
- Credit losses by portfolio segment
- Asset value changes
- Operational cost impacts
- Revenue impacts

### Scenario Analysis Best Practices

1. **Use Multiple Scenarios**: Cover range of possibilities
2. **Long Time Horizons**: Climate risks unfold over decades
3. **Regular Updates**: Incorporate latest climate science
4. **Stakeholder Input**: Engage business units and risk functions
5. **Transparent Assumptions**: Document scenario design choices

---

## Implementation Framework for Banks

### Phase 1: Foundation Building (0-6 months)

#### Governance Structure
- **Board Oversight**: Establish climate risk committee or assign responsibility
- **Management Accountability**: Designate Chief Climate Risk Officer
- **Three Lines of Defense**: Define roles for business, risk, and audit

#### Data Infrastructure
- **Data Collection**: Inventory existing climate-related data
- **Data Gaps**: Identify missing data elements
- **Vendor Selection**: Evaluate climate data providers
- **System Integration**: Connect climate data to risk systems

#### Capacity Building
- **Training Programs**: Educate staff on climate risks
- **External Expertise**: Hire climate risk specialists
- **Partnerships**: Collaborate with research institutions

### Phase 2: Risk Assessment (6-12 months)

#### Portfolio Analysis
```
Steps:
1. Categorize exposures by climate sensitivity
2. Map physical risk exposure geographically
3. Identify transition risk by sector
4. Quantify exposures in risk categories
5. Report concentration risks
```

#### Scenario Development
- Select climate scenarios aligned with strategy
- Calibrate scenarios to bank's portfolio
- Develop scenario narratives
- Quantify scenario parameters

#### Pilot Studies
- Test methodologies on sample portfolios
- Refine approaches based on results
- Document lessons learned

### Phase 3: Integration (12-24 months)

#### Risk Management Integration
- **Credit Risk**: Incorporate into underwriting standards
- **Market Risk**: Add climate factors to market risk models
- **Operational Risk**: Assess physical risks to facilities
- **Liquidity Risk**: Consider climate-driven deposit volatility

#### Strategic Planning
- **Risk Appetite**: Set climate risk limits and tolerances
- **Capital Planning**: Include climate scenarios in ICAAP/CCAR
- **Business Strategy**: Identify green finance opportunities
- **Product Development**: Create climate-smart financial products

#### Disclosure and Reporting
- **TCFD Alignment**: Implement TCFD recommendations
- **Regulatory Reports**: Meet supervisory requirements
- **Investor Communications**: ESG reporting
- **Public Disclosure**: Climate risk reports

### Phase 4: Optimization (24+ months)

#### Advanced Analytics
- Develop sophisticated climate risk models
- Automate risk assessment processes
- Integrate AI/ML techniques
- Real-time monitoring capabilities

#### Portfolio Management
- **Active Management**: Reduce climate risk concentrations
- **Hedging**: Explore climate risk transfer instruments
- **Engagement**: Work with clients on transition plans
- **Divestment**: Exit high-risk, non-transitioning exposures

#### Performance Monitoring
```
Key Performance Indicators:
- Financed emissions (Scope 3)
- Green asset ratio
- Climate VaR
- Exposure to climate-sensitive sectors
- Client transition plan coverage
```

---

## Best Practices and Recommendations

### 1. Start with Materiality Assessment

**Prioritize efforts where climate risk is most material:**
- Focus on high-risk sectors first (energy, real estate, agriculture)
- Prioritize geographies with high physical risk
- Consider concentration risks

### 2. Adopt a Forward-Looking Approach

**Climate risks are inherently forward-looking:**
- Use scenarios, not just historical data
- Consider long time horizons (10-30 years)
- Update assumptions regularly
- Prepare for non-linear changes

### 3. Engage Across the Organization

**Climate risk is enterprise-wide:**
- Involve business units in risk assessment
- Collaborate across risk types
- Engage with clients and borrowers
- Coordinate with industry peers

### 4. Leverage External Resources

**Don't reinvent the wheel:**
- Use industry frameworks (TCFD, PCAF)
- Join industry initiatives (UNEP FI, NGFS)
- Partner with climate scientists
- Utilize vendor solutions

### 5. Balance Precision with Pragmatism

**Perfect is the enemy of good:**
- Start with simpler approaches
- Iterate and improve over time
- Document limitations transparently
- Focus on risk identification initially

### 6. Integrate Climate Risk into Culture

**Make climate risk part of DNA:**
- Include in compensation metrics
- Embed in credit culture
- Recognize good practices
- Communicate progress regularly

### 7. Monitor Regulatory Developments

**Stay ahead of requirements:**
- Track regulatory consultations
- Participate in industry feedback
- Prepare for stricter standards
- Align internal programs with expectations

### 8. Consider Opportunities, Not Just Risks

**Climate transition creates opportunities:**
- Green lending and bonds
- Sustainability-linked products
- Advisory services for transition
- ESG investment products

---

## Key Resources and References

### International Frameworks
- **TCFD**: Task Force on Climate-related Financial Disclosures
- **NGFS**: Network for Greening the Financial System
- **PCAF**: Partnership for Carbon Accounting Financials
- **UNEP FI**: United Nations Environment Programme Finance Initiative

### Climate Science Resources
- **IPCC Reports**: Intergovernmental Panel on Climate Change
- **CMIP**: Coupled Model Intercomparison Project
- **IEA**: International Energy Agency

### Industry Associations
- **IIF**: Institute of International Finance
- **GFMA**: Global Financial Markets Association
- **UNEP FI Banking**: Banking principles for responsible banking

### Regulatory Guidance
- **Basel Committee**: Principles for climate-related financial risks
- **FSB**: Financial Stability Board climate reports
- **ECB/SSM**: European Central Bank climate stress tests
- **Bank of England**: Climate Biennial Exploratory Scenario

### Academic and Research Institutions
- **Climate Econometrics**: Oxford University
- **LSE Grantham Institute**: London School of Economics
- **PIK**: Potsdam Institute for Climate Impact Research
- **RFF**: Resources for the Future

---

## Conclusion

Climate risk modelling for banks is an evolving discipline that requires:

1. **Strong Governance**: Leadership commitment and clear accountability
2. **Robust Data**: Quality climate and financial data
3. **Advanced Analytics**: Sophisticated modelling capabilities
4. **Cross-functional Collaboration**: Enterprise-wide integration
5. **Continuous Learning**: Adaptation to new science and methods

**Next Steps for Banks:**
- Assess current climate risk management maturity
- Develop a roadmap based on this framework
- Start with pilot projects in material risk areas
- Build capabilities systematically
- Engage with stakeholders throughout

Climate risk is not just a regulatory requirement—it's a strategic imperative for long-term resilience and competitiveness in the financial sector.

---

## Appendix: Sample Climate Risk Assessment Template

```markdown
# Climate Risk Assessment Template

## Portfolio Details
- Portfolio Type: [Mortgage/Corporate/Project Finance/etc.]
- Total Exposure: $XXX million
- Number of Facilities: XXX
- Geographic Distribution: [List]
- Sector Distribution: [List]

## Physical Risk Assessment

### Risk Identification
- Primary Physical Hazards: [Flood/Hurricane/Wildfire/etc.]
- Affected Locations: [List]
- Estimated Exposure: $XXX million (XX%)

### Risk Quantification
- Probability of Event: X%
- Expected Loss Given Event: $XXX million
- Climate-Adjusted Expected Loss: $XXX million
- Time Horizon: XXXX

## Transition Risk Assessment

### Risk Identification
- Primary Transition Drivers: [Policy/Technology/Market]
- Affected Sectors: [List]
- Estimated Exposure: $XXX million (XX%)

### Risk Quantification
- Scenario Applied: [Orderly/Disorderly/Hot House]
- Expected Credit Loss Impact: $XXX million
- Asset Value Change: -XX%
- Time Horizon: XXXX

## Overall Climate Risk Rating
- Physical Risk: [High/Medium/Low]
- Transition Risk: [High/Medium/Low]
- Combined Climate Risk: [High/Medium/Low]

## Mitigation Actions
1. [Action 1]
2. [Action 2]
3. [Action 3]

## Monitoring and Review
- Review Frequency: [Quarterly/Annual]
- Key Metrics to Track: [List]
- Responsible Party: [Name/Team]
```

---

**Document Version**: 1.0  
**Last Updated**: December 2024  
**Contact**: For questions or feedback on this guide, please open an issue in this repository.
