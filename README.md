# HEC-RAS-Water-Surface-Profiles
Hydraulic analysis of trapezoidal and rectangular channels using HEC-RAS and the standard-step method for water surface profile computation.
# Water Surface Profile Analysis using HEC-RAS and Standard-Step Method

This project involves hydraulic analysis of a trapezoidal channel transitioning into a rectangular channel. The objective is to compute normal and critical depths, sketch water surface profiles, and compare results obtained using HEC-RAS with those from the standard-step method.

## Problem Statement
- **Trapezoidal Channel**  
  - Bottom width: 5 m  
  - Side slopes: 1.5H:1V  
  - Length: 200 m  
  - Slope: 0.0008  
  - Manning's n: 0.013  

- **Rectangular Channel**  
  - Width: 4 m  
  - Two reaches:  
    - Upper reach: slope = 0.0012, length = 150 m  
    - Lower reach: slope = 0.0024, length = 250 m  
  - Manning's n: 0.013  

- Flow discharge: **10 m³/s**  
- Rectangular channel ends in a free overfall (flow depth at the end ≈ critical depth).  
- Local losses at the junction are ignored.

## Tasks
1. Determine normal and critical depths, sketch depth lines, and propose a possible water surface profile.  
2. Model and compute the water surface profile using **HEC-RAS**.  
3. Implement the **standard-step method** in Python to compute profiles and compare with HEC-RAS results.

## Methods Used
- **HEC-RAS 1D Steady Flow Simulation**
- **Standard-Step Method** for gradually varied flow
- Manning's equation for uniform flow
- Critical depth computation from specific energy principles

## Results
- Normal and critical depth values for each channel segment
- Water surface profile plots for:
  - Trapezoidal reach
  - Upper rectangular reach
  - Lower rectangular reach
- Comparison between HEC-RAS and computed results

## How to Run
1. Open the HEC-RAS project file in the `HECRAS/` folder and run the steady flow analysis.  
2. Run the Python script in `StandardStepMethod/` to compute profiles.
3. Compare output plots in `Results/`.


