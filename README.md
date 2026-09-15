# EYPE Greenhouse — Economic & Financial Analysis

Project developed for the **Economics of Technology and Management course** within the **MSc in Cybersecurity at Sapienza University of Rome**.

The study evaluates the economic viability of **EYPE (Enjoy Your Plant Everywhere)**, a hydroponic greenhouse that I helped develop with other students during high school. It revisits that engineering project through **financial modeling, investment appraisal, risk analysis, and sustainability considerations**, examining whether the benefits of local food production can justify the initial investment and operating costs.

## Project Materials

| File | Contents |
| --- | --- |
| [Analysis presentation](Sustainable%20Farming%20with%20EYPE%20Greenhouse%20-%20ETM.pdf) | Research objective, assumptions, methodology, results, and sustainability discussion. |
| [Excel financial model](Economic%20analysis%20-%20ETM.xlsx) | Input data, cash-flow calculations, economic indicators, sensitivity and scenario tables, break-even analysis, and Monte Carlo simulations. |
| [EYPE technical manual](EYPEManualeTecnico.pdf) | Original greenhouse documentation, covering its mechanical, electronic, software, and hydroponic components. Written in Italian. |

**Start with the presentation for an overview**, then explore the Excel workbook for the calculations and the technical manual for the engineering context.

## From Engineering Prototype to Economic Case Study

EYPE is a modular system for **controlled-environment agriculture**, using a nutrient solution in place of soil. Sensors and actuators support the monitoring and control of growing conditions, while local and web interfaces provide access to plant parameters and cultivation settings.

The original design combines mechanical structures, electronic control, a mini PC, and software built around **ASP.NET/C#, Angular/TypeScript, and local and web databases**. Its architecture supports local operation even without an Internet connection.

This coursework uses that technical foundation to assess the costs and benefits of adopting the system. The financial analysis is by Andrea Altomare; the original EYPE prototype was a collaborative school project developed under the **GrowTech / Classe Virtuale** initiative.

## Analysis Approach

The model applies **Discounted Cash Flow (DCF)** analysis over a **five-year horizon**, using a **5% baseline discount rate**.

- **CAPEX estimation:** structural components, sensors, controllers, actuators, assembly, and software setup.
- **OPEX estimation:** electricity, chemical products, maintenance, and cloud hosting.
- **Benefit estimation:** avoided produce purchases, water savings, and avoided soil and fertilizer costs.
- **Investment appraisal:** Net Present Value (**NPV**), Payback Time (**PBT**), Discounted Payback Time (**DPBT**), Internal Rate of Return (**IRR**), and Profitability Index (**PI**).
- **Sensitivity analysis:** changes in structural costs, electricity costs, produce procurement savings, and the discount rate.
- **Scenario analysis:** combined optimistic and pessimistic changes in construction costs, energy costs, and produce prices.
- **Break-even analysis:** production quantity, produce value, and structural investment thresholds.
- **Monte Carlo simulation:** two sets of 1,000 scenarios examining uncertainty in investment, operating costs, production, and benefits, including a stress case with higher structural costs.

## Baseline Results

The baseline assumes **€950 in initial investment**, **€420 in annual operating costs**, and **€1,250 in annual benefits**, resulting in a modeled **€830 annual net benefit**. Produce procurement savings account for €1,200 of those benefits, based on an assumed annual output of **100 kg valued at €12/kg**.

| Indicator | Baseline model result |
| --- | --- |
| Net Present Value | €2,643.47 |
| Payback Time | 1.14 years |
| Discounted Payback Time | 1.21 years |
| Internal Rate of Return | 83.1% |
| Profitability Index | 3.78 |

These are **model-based estimates under the stated assumptions**, rather than measured investment returns. The benefits represent avoided expenditure. Their realization depends on factors such as actual crop output, the value of displaced purchases, energy consumption, and maintenance needs.

The Monte Carlo sections use random sampling, so their results can change when the workbook recalculates. The presentation records the simulation outcomes used at the time of preparation.

## Sustainability & Technology Management

The presentation considers water efficiency, local food production, and the energy demands of hydroponic cultivation in relation to **SDG 12: Responsible Consumption and Production** and **SDG 13: Climate Action**. It discusses renewable energy integration and the importance of considering environmental impacts beyond water savings alone.

The project demonstrates **quantitative decision-making, Excel financial modeling, cost-benefit analysis, uncertainty assessment, and technical communication**, linking the design of an automated physical system to its economic feasibility and resource requirements.
