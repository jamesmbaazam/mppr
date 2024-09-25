# Hands-on compartmental modelling of COVID-19 and Mpox

## Goals

- Two groups to develop compartmental models of COVID-19 and Mpox, based on experience:
    - COVID-19 work:
        - Reproduce the model in this COVID-19 model for various West African countries
- Model Mpox transmission pathways

## COVID-19 modelling

This is majorly a reproducibility exercise.

The goal here is to re-implement the model in the paper, [“Modeling COVID-19 dynamics in the sixteen West African countries”](https://www.sciencedirect.com/science/article/pii/S2468227622003143). 

### Tasks

- Do you agree with the model structure used? How would you modify it?
- Convince yourself that you understand the dynamics
- Use the model fitting approach used in the paper or suggest/attempt an alternative approach.
- You are provided with data. Brainstorm what additional data would be needed to fit the model aside the data provided.
- Explore scenarios:
    - Expected mortality given resource constraints
    - Mitigation strategies:
        - Detection rate (case ascertainment), which can be used as proxy for testing capacity.
        - NPI (transmission rate reduction)

## Mpox modelling

### Brief

There is an [ongoing mpox outbreak](https://www.who.int/news/item/14-08-2024-who-director-general-declares-mpox-outbreak-a-public-health-emergency-of-international-concern) that is disproportionately affecting the Democratic Republic of Congo (DRC). Many initiatives have been put in place to brainstorm how to respond to the analytics needs of this outbreak in a timely fashion. See for example, the [WHO Mpox analytics Collaboratory](https://www.who.int/initiatives/collaboratory/community).

### Goal

The goal here will be to attempt to model the long term dynamics of mpox, investigating the impact of different transmission pathways and contact patterns on the spread of the disease.

### Tasks

- Develop two compartmental models:
    - Model 1: Model with homogenous mixing + three transmission routes (direct contact, airborne, and sexual contact).
    - Model 2: Modify the simple model to include heterogeneous mixing with contact patterns.
- Data: You will be given 3 datasets [Incidence data](https://global.health/), age pyramids, [social contact matrices](https://hugogruson.fr/contactdata/articles/countries.html).
- Model fitting: Explore different combinations of the parameters of close contacts (assumed to be sexual contacts; a simplification) and airborne transmission that best fit the DRC data.
    
### Resources

- WHO 2022-24 Mpox (Monkeypox) [Outbreak Global Trends](https://worldhealthorg.shinyapps.io/mpx_global/)
- UK Government mpox [technical briefings](https://www.gov.uk/government/publications/monkeypox-outbreak-technical-briefings)

## Basics of Economic Modelling

- Develop an economic analyses  of the COVID-19 and Mpox models:
    - Prior reading:  [Budget Impact Analysis—Principles of Good Practice: Report of the ISPOR 2012 Budget Impact Analysis Good Practice II Task Force](https://www.valueinhealthjournal.com/article/S1098-3015(13)04235-6/fulltext)

# Other resources

- Model fitting and parameter estimation:
    - [Slides](https://docs.google.com/document/d/1drY4n-X0TIdpXIn9avpvTKEPtRgtG51XTC4eTJtC5as/edit) from online course by Dr. Andrzej Jarynowski and Prof. Vitaly Belik. 

