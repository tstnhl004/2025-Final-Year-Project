# 2025-Final-Year-Project
Simulation of user migration in a multi-tier HetNet (2G-5G), quantifying how operator incentives (device, bundle, loyalty) shift adoption. Models QoS (rate, latency, coverage) and user heterogeneity, compares baseline vs incentives, and outputs migration rates, adoption changes, and flow heatmaps.

# Network Migration System: Utility-Based Decision Model

A sophisticated simulation framework for modeling user migration behavior across heterogeneous mobile network technologies (2G through 6G). This system employs utility-based decision theory to understand and predict how users transition between different Radio Access Technologies (RATs) under various incentive structures.

## Overview

This project models the complex dynamics of network technology adoption in telecommunications, focusing on how users make decisions to migrate from legacy networks (2G/3G) to modern technologies (4G/5G/6G). The simulation accounts for heterogeneous user populations, economic incentives, and quality-of-service considerations.

## System Architecture

The system comprises four interconnected components:

### 1. **Network Environment**
- Multiple Radio Access Technologies (2G, 3G, 4G, 5G, 6G)
- Technology-specific characteristics (bandwidth, latency, coverage)
- Dynamic network state evolution

### 2. **Heterogeneous User Population**
- **Price Sensitivity**: Varying willingness to pay for service improvements
- **Technology Affinity**: Preference for newer vs. proven technologies
- **Income Level**: Economic constraints on technology adoption
- **Switching Sensitivity**: Resistance to changing networks

### 3. **Utility-Based Decision Model**
The core decision engine that evaluates migration choices through:
- **QoS Benefits**: Performance improvements from network upgrades
- **Economic Incentives**: Financial rewards, subsidies, and discounts
- **Switching Costs**: Barriers to migration (device, learning curve, etc.)

### 4. **Incentive Management System**
Strategic levers to influence user behavior:
- Device subsidies and promotions
- Bundle discounts
- Loyalty rewards and retention programs

### Feedback Loop
Migration outcomes continuously update the network environment and population state, creating a dynamic, evolving system.

## Key Features

- **Agent-Based Modeling**: Individual user agents with heterogeneous characteristics
- **Probabilistic Decision Making**: Logit-based choice models for realistic behavior
- **Dynamic Incentive Optimization**: Adaptive strategies to maximize migration rates
- **Multi-Technology Support**: Simultaneous modeling of multiple network generations
- **Temporal Analysis**: Track migration patterns over time
- **Economic Modeling**: Cost-benefit analysis for operators and users


## Usage

The main implementation is contained in `FinalSimulation.ipynb`, which includes:

1. **Model Setup**: Initialize network environment and user population
2. **Utility Functions**: Define decision-making criteria
3. **Simulation Engine**: Run migration scenarios
4. **Incentive Strategies**: Test different policy interventions
5. **Analysis & Visualization**: Evaluate outcomes and generate insights

## Research Applications

This framework is designed for:

- **Telecommunications Strategy**: Network investment and shutdown planning
- **Policy Analysis**: Understanding regulatory impacts on technology adoption
- **Market Research**: Consumer behavior in technology transitions
- **Economic Modeling**: Cost-benefit analysis of network infrastructure
- **Academic Research**: Publications in technology diffusion and network economics

## Contributing

Contributions are welcome! Areas for enhancement:

- Machine learning integration for parameter estimation
- Real world data calibration
- Spatial network modeling
- Multi operator competition dynamics
- 6G technology specifications

## Authors

- Nhlalonhle Tsotetsi


**Note**: This is a research simulation tool. Real-world deployment requires careful calibration with actual market data and validation with domain experts.
