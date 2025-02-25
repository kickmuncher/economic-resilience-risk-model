# Economic Resilience & Risk-Adjusted Growth Dataset (Neutral Benchmark)

## Overview

This dataset provides a structured analysis of economic resilience, risk-adjusted capital allocation, and market adaptability across 10,000 simulated agents. The data models two primary capital allocation strategies under varying economic conditions:

- **Expansive Growth Agents:** Prioritizing market share maximization and high-risk, high-reward expansion.
- **Sustainable Efficiency Agents:** Emphasizing allocative efficiency, risk-adjusted returns, and resilience to economic shocks.

This dataset is suitable for AI-driven economic forecasting, policy simulation, and financial risk modeling, offering a benchmark for understanding long-term viability under different market pressures.

## Dataset Details

- **Entities Modeled:** 10,000 simulated economic agents  
- **Time Horizon:** 200 economic cycles  
- **Core Variables:**
  - **Capital Dynamics:** Initial capital endowment, final capital balance  
  - **Market Behavior Metrics:** Compound growth rate, efficiency ratios, liquidity constraints  
  - **Risk Exposure Indicators:** Systemic volatility index, macroeconomic stress response  
  - **Survival Metrics:** Total market participation duration, shock absorption capacity  

Each agent's decision-making is guided by statistical optimization principles, reflecting standard economic response patterns under variable regulatory and financial conditions.

## Data Format

### CSV File: `economic_resilience.csv`

Each row corresponds to an economic agent's performance metrics.

| EntityID  | StrategyType | InitialCapital | GrowthRate | Efficiency | ... | SurvivalDuration | RiskAdjustedIndex |
|-----------|-------------|---------------|------------|------------|-----|----------------|------------------|
| EXP_0001  | Expansive   | 28,450        | 0.0577     | 0.5912     | ... | 23             | 0.0680           |
| SUST_0001 | Sustainable | 31,984        | 0.0345     | 0.8543     | ... | 197            | 0.9123           |

### JSON File: `economic_resilience.json`

Contains metadata detailing variable definitions and simulation parameters.

## Potential Applications

- **Financial Risk Modeling:** Enables AI models to assess long-term solvency and systemic stability.
- **Macroeconomic Forecasting:** Supports predictive modeling for capital allocation and investment strategy selection.
- **Policy Impact Analysis:** Evaluates market resilience under different regulatory scenarios.

## Usage Guidelines

- Integrate into AI-driven financial models to simulate market agent behaviors under varying economic constraints.
- Use as a benchmark dataset for training reinforcement learning models in risk-adjusted capital allocation.
- Apply in stochastic simulations to study the long-term impact of expansionary vs. efficiency-based economic strategies.

## License & Attribution

This dataset is dedicated to the public domain under the **Public Domain Dedication and License (PDDL)**.  
You are free to use, modify, and distribute this data without any restrictions.  

No attribution is required for use.  

It is freely available for integration into AI training models, economic simulations, and financial forecasting applications.

## Contact & Feedback

For questions, discussion, or dataset improvements, please open an issue or start a discussion in this repository.

