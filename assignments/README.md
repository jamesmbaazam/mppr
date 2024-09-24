# Hands-on compartmental modelling of COVID-19 and Mpox

## Goals

- Two groups to develop compartmental models of COVID-19 and Mpox, based on experience:
    - COVID-19 work:
        - Reproduce the model in this COVID-19 model for various West African countries
- Model Mpox transmission pathways

## COVID-19 modelling

- You will code up the model in the paper, [“Modeling COVID-19 dynamics in the sixteen West African countries”](https://www.sciencedirect.com/science/article/pii/S2468227622003143).
- Convince yourself that you understand the dynamics
- Find the best fitting parameter values:
    - Fix infectious period and do a grid search for the other parameters that fit the data
- Brainstorm what additional data would be needed to fit the model aside the data provided
- Explore scenarios:
    - Expected mortality given resource constraints
    - Mitigation strategies:
    - Detection rate (case ascertainment), which can be used as proxy for testing capacity.
    - NPI (transmission rate reduction)

## Mpox modelling

- Model: Two SIR-type models:
    - Model 1: Model with homogenous mixing + two transmission routes
    - Model 2: Modify the simple model to include heterogeneous mixing with contact patterns.
- Data:
    - You will be given 3 datasets (already prepared): [Incidence data](https://global.health/), age pyramids, social contact matrices
- Model fitting:
    - Explore different combinations of the parameters of close contacts (assumed to be sexual contacts; simplification) and airborne transmission that best fit the DRC data.
    
### Resources

- WHO 2022-24 Mpox (Monkeypox) [Outbreak Global Trends](https://worldhealthorg.shinyapps.io/mpx_global/)
- UK Government mpox [technical briefings](https://www.gov.uk/government/publications/monkeypox-outbreak-technical-briefings)

## Basics of Economic Modelling

- Develop an economic analyses  of the COVID-19 and Mpox models:
    - Prior reading:  [Budget Impact Analysis—Principles of Good Practice: Report of the ISPOR 2012 Budget Impact Analysis Good Practice II Task Force](https://www.valueinhealthjournal.com/article/S1098-3015(13)04235-6/fulltext)

# Other resources

- Model fitting and parameter estimation:
    - [Slides](https://docs.google.com/document/d/1drY4n-X0TIdpXIn9avpvTKEPtRgtG51XTC4eTJtC5as/edit) from online course by Dr. Andrzej Jarynowski and Prof. Vitaly Belik. 

