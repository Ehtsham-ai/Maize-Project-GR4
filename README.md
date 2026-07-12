# Maize-Project-GR4
README
============================================================
Syferkuil DSSAT Maize Nitrogen Split Analysis Project
============================================================

Project Title:
Modeling Maize Response to Dynamics of Nitrogen Splits Across
Growth Stages in South Africa Using DSSAT


1. PROJECT OVERVIEW
------------------------------------------------------------

This project uses DSSAT (Decision Support System for
Agrotechnology Transfer) to evaluate how different nitrogen
application timings influence maize production under South
African climatic conditions.

The main research question is:

How does splitting nitrogen fertilizer application across
different maize growth stages affect grain yield, biomass
production, nitrogen use efficiency, crop development and
yield stability?


2. DSSAT SIMULATION DESIGN
------------------------------------------------------------

Location:
Syferkuil, South Africa

Simulation period:
1984 - 2019

Number of seasons:
36 years

Number of simulations:
144

Treatments:

N100:
- 100% nitrogen applied at planting
- Total nitrogen = 40 kg N ha-1


N50_50:
- 50% nitrogen at planting
- 50% nitrogen as a later split


N33_33_33:
- Three equal nitrogen applications


N25_25_25_25:
- Four equal nitrogen applications


All treatments received the same total nitrogen amount.
Only nitrogen timing was changed.


3. INPUT DATA FILES
------------------------------------------------------------

summary.csv

Purpose:
Final DSSAT seasonal output.

Important variables:

HWAM:
Grain yield (kg ha-1)

CWAM:
Crop biomass (kg ha-1)

HIAM:
Harvest index

NIAM:
Nitrogen uptake

GNAM:
Grain nitrogen


evaluate.csv

Purpose:
Crop evaluation and phenology output.

Important variables:

ADAPS:
Anthesis timing

MDAPS:
Maturity timing

HWAMS:
Yield

CWAMS:
Biomass

HIAMS:
Harvest index


plantgro.csv

Purpose:
Daily crop growth dynamics.

Important variables:

CWAD:
Biomass accumulation

LAID:
Leaf area index

GWAD:
Grain weight development

NSTD:
Nitrogen status


weather.csv

Purpose:
Climate analysis.

Important variables:

Rainfall

Temperature

Solar radiation

VPD


4. ANALYSIS WORKFLOW
------------------------------------------------------------

Step 1:
Climate characterization

Includes:
- rainfall variability
- temperature trends
- radiation analysis


Step 2:
Yield response analysis

Includes:
- mean yield comparison
- yield stability
- seasonal yield variation


Step 3:
Climate-yield relationship

Includes:

Rainfall versus maize yield relationship

Purpose:
To understand whether nitrogen strategies respond
differently under wet and dry seasons.


Step 4:
Crop growth analysis

Includes:

- biomass accumulation
- LAI development
- grain filling
- nitrogen dynamics


Step 5:
Nitrogen analysis

Includes:

Nitrogen uptake comparison

Nitrogen Use Efficiency (NUE):

NUE = Grain Yield / Applied Nitrogen

Total nitrogen applied:
40 kg N ha-1


Step 6:
Phenology analysis

Includes:

- anthesis timing
- maturity duration
- harvest index


5. GRAPH INTERPRETATION GUIDE
------------------------------------------------------------

Yield graphs:

Answer:
Which nitrogen split produces higher maize yield?


Yield stability graphs:

Answer:
Which treatment performs consistently across different
weather seasons?


Rainfall-yield graphs:

Answer:
How does climate variability influence nitrogen response?


Biomass graphs:

Answer:
How does nitrogen timing influence total crop growth?


LAI graphs:

Answer:
How does nitrogen availability affect canopy development?


Nitrogen uptake graphs:

Answer:
Which strategy allows maize to capture more nitrogen?


NUE graphs:

Answer:
Which treatment produces more grain per unit nitrogen?


Phenology graphs:

Answer:
Does nitrogen timing change crop development duration?


6. COMPARISON WITH REFERENCE STUDY
------------------------------------------------------------

Reference:

Lam et al. (2023)

Their study:
- DSSAT-based maize modelling
- South African conditions
- evaluated water and fertilizer management


Difference between studies:

Lam et al.:
Focus:
Water and fertilizer quantity management


This project:
Focus:
Nitrogen split timing while keeping total nitrogen constant


Similarity:

Both studies:
- use DSSAT
- analyse maize production
- evaluate climate effects
- use long-term simulations


7. EXPECTED SCIENTIFIC INTERPRETATION
------------------------------------------------------------

The final interpretation should not only identify the
highest yielding treatment.

The preferred nitrogen strategy should consider:

- grain yield
- yield stability
- biomass production
- nitrogen efficiency
- climate adaptability


8. PRESENTATION GUIDANCE
------------------------------------------------------------

Recommended key figures:

1. Nitrogen treatment vs grain yield

2. Yield stability across seasons

3. Rainfall versus yield relationship

4. Biomass accumulation curves

5. LAI development

6. Nitrogen use efficiency

7. Nitrogen uptake comparison

8. Maturity and harvest index


9. IMPORTANT NOTES
------------------------------------------------------------

- All treatments contain equal total nitrogen.
- Differences are caused by nitrogen application timing.
- Weather variability is included through historical seasons.
- Results represent DSSAT simulation outputs, not direct field
  measurements.


End of README
