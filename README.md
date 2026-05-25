Hydrogen Production via Steam Methane Reforming (SMR)

Aspen HYSYS simulation project for hydrogen production using Steam Methane Reforming (SMR) with sensitivity analysis and methane recycle optimization.

Project Overview

This project models industrial hydrogen production using Steam Methane Reforming (SMR) in Aspen HYSYS v12.

The simulation includes:
- Primary steam reformer
- High-temperature water gas shift reactor
- Low-temperature water gas shift reactor
- CO₂ absorption section
- PSA purification unit
- Methane recycle loop
- Heat integration network

Key Results

- Hydrogen Purity: 98.0 mol%
- CH₄ Conversion: 85.4%
- Overall CO Conversion: 92.1%
- H₂ Production Rate: 126.8 kgmol/hr
- Steam-to-Carbon Ratio: 4.0

Sensitivity Analysis

The project analyzes effects of:
- Steam-to-carbon ratio
- Reformer temperature
- Reformer pressure
- WGS reactor temperature

Software Used

- Aspen HYSYS v12
- Peng-Robinson EOS

Repository Structure

```text
report/              -> Final project report
images/              -> Simulation screenshots and plots
simulation-files/    -> Aspen HYSYS files
references/          -> Literature references
```

Key Engineering Concepts

- Steam Methane Reforming (SMR)
- Water Gas Shift Reaction (WGS)
- Heat Integration
- Process Optimization
- Chemical Process Simulation
- Equilibrium Thermodynamics

Important Findings

- Increasing reformer temperature improves methane conversion
- Higher pressure reduces SMR conversion
- Methane recycle significantly improves carbon utilization
- Heat integration recovers ~96% furnace duty

Authors

- Menavath Pavan Kumar
- Team Members

References

- Xu & Froment (1989)
- IEA Future of Hydrogen (2019)
- LeValley et al. (2014)
