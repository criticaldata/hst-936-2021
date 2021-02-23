## Project A: Modeling mobility networks across US counties and states

### Keywords: 
mobility networks, data visualization, biostatistics

### Context: 
The movement of people within the US has relevance to many fields including economics, epidemiology, policy-making, and infrastructure development. However, analysis of mobility has never been more important that in the era of COVID where major outbreaks of the disease have been caused by inter-state and inter-county travel of infected peoples.

### Project Focus: 
In this project, you will leverage PlaceIQ county-to-county mobility data to quantify the temporal evolution of the mobility network for each state in the US. Thanks to a data collection effort led by Dr. Yuan Lai in DUSP, the team has gathered information about the flow of persons (edges or links) between US counties (nodes) since the beginning of 2020. Using visualization tools, you will represent the evolution of each state’s interaction network over time. Additionally, you will use network science metrics to estimate the evolution of each state’s network characteristics (e.g., density, diameter). We would encourage you to combine additional mobility data sources (e.g., Apple, Google, Unacast, Facebook, SafeGraph) to enrich the mobility knowledge graph. If time permits, the team could explore how the network characteristics relate with COVID-19 morbidity and mortality, characterizations of social structures through the Facebook Social Connectedness Index, as well as excess mortality in each state.

### Are you interested? 
We are looking for students interested in interdisciplinary research, with a background in data visualization in Python (matplotlib, seaborn, etc.). Knowledge of Python is required; experience in procession mobility data will be nice.


## Project B: Extension of Excess Mortality Study at the County Level Across the US

### Context: 
Coronavirus has taken a major toll on the US, but the full extent of its damage is not yet known. Understanding the extent of undercounting, and how it varies in different parts of the country is key to developing evidence-based solutions for fighting the pandemic and reopening the country. Measuring “excess deaths,” or the number of deaths above the average recorded for the same period in previous years, can provide a window onto the true toll of coronavirus. In order to estimate excess deaths. We have conducted this analysis for Colorado thus far and have work that has laid the foundation for further analysis, but now would like to extend this analysis to other states and incorporate additional data elements.

### Project focus: 
With death certificates from 15+ states across the United States (with more in progress) we have access to a rich dataset that enables for a more granular understanding of mortality from 2015 - 2020. We hope to build on the foundation of the investigation into Colorado by extending this investigation to other states, further investigating what might be underlying drivers of patterns observed in excess mortality. Additionally, we hope to refine techniques to estimate stratified excess mortality at the state-level or county-level excess mortality. That could include Poisson or negative binomial regression models for weekly all-cause deaths, the incorporation of trends in cause-specific deaths, Bayesian methods and/or hierarchical models (where each county/CBSA would be tied to a base state-level distribution).

### Are you interested? 
We are looking for students interested in interdisciplinary research, with a background in classical statistical learning techniques, large-scale data processing, interest in policy and collaboration with state DOH and exposure to forecasting methods. Knowledge of Python or R is strongly recommended.


## Project C: Causal Mediation Evaluation of Excess Mortality at the County Level in the United States

### Context: 
COVID-19 has led to increased morbidity and mortality among older populations and those with underlying health conditions, but also among those who are unable to access outpatient and emergency services because of the lockdown and surge in acute care demand. Explaining the underlying causes of death, and assessing the geographical heterogeneity of the excess death toll within each state, require careful retrospective analysis of death certificates, including job occupation, industry, and education level information. To that end, we have contacted departments of health across all 50 states and the District of Columbia. We have collected county-level all-cause mortality data for 15 states, and are about to conclude additional partnerships with local departments. Additionally, we compiled news articles from the Media Cloud state-level media aggregator that had specific county mentions since March 1, 2020. Deriving additional insights from infoveillance tools may help provide the narrative behind excess death calculation from COVID-19 at the county level in the US.

### Project focus: 
The challenge is to develop a causal-mediation analysis framework to explain: (a) the direct effect of underlying demographics, population health, and county infrastructure onto COVID-19-induced excess mortality; (b) the indirect contribution of mobility on COVID-19 mortality and non-COVID-19 excess deaths, by integrating inter-county mobility data from PlaceIQ, Unacast, SafeGraph, and Facebook.

### Are you interested? 
We are looking for students interested in interdisciplinary research, with a background in statistics, natural language processing, and/or network science. Knowledge of Python or R is required; experience in epidemiology is a plus.


## Project D: Association of COVID-19 Excess Mortality with Job Occupation and Outbreak Centers

### Context: 
The risk for developing COVID-19 is different not only across race, ethnicity, income, education levels, etc. but also across different job occupations with varying levels of exposure. For example, preliminary research has shown that cooks, packaging workers, construction workers, and others have had a higher risk of dying from COVID-19.

### Project Focus: 
1) Job occupation is listed as part of the death certificates that we have received from certain states. We have been in touch with the CDC NIOCCS for their expertise on how to match free text describing both job occupation and industry fields to an established category. Their team has invited us to beta test NIOCCS v4, which uses NLP techniques instead of a rule-based process to map job occupation names to a broader job category and industry sector, and have shared some code to help get started. 
2) In our work in Colorado thus far, we have looked at outbreaks in food processing and meatpacking areas, along with jails and nursing homes. How might we examine nontraditional data sources, such as news articles from MIT media cloud to gain insight into particular outbreaks that impacted certain occupations?

### Are you interested? 
We are looking for students interested in interdisciplinary research, with a background in classic machine learning techniques and large-scale data processing. Knowledge of Python or R is required.

## Project E: Vulnerability Indices - Excess Mortality and its link to Social Vulnerability Index (SVI) and CCVI

### Context: 
Coronavirus has taken a major toll on the US, but the full extent of its damage is not yet known. Understanding the extent of undercounting, and how it varies in different parts of the country is key to developing evidence-based solutions for fighting the pandemic and reopening the country. Measuring “excess deaths,” or the number of deaths above the average recorded for the same period in previous years, can provide a window onto the true toll of coronavirus. In order to estimate excess deaths, MIT and Surgo have identified the need for timely reporting of deaths at the local level. 

### Project Focus: 
Our teams plan to link excess deaths data to relevant datasets such as Surgo’s COVID Community Vulnerability Index (CCVI) to better understand the factors driving patterns in excess mortality. Doing analysis at the local county level will provide policymakers with the tools and precision needed to make important public health decisions in the coming months. Students would explore both the Social Vulnerability Index (SVI) from the CDC along with the CCVI to examine disparities in the impact of the virus among the most vulnerable in addition to county-level epidemiologic factors related to the COVID-19 pandemic. If time permits, students will attempt to create a vulnerability index based on excess mortality data.
This project will answer key questions around vulnerability and excess mortality:
* How do vulnerability and excess mortality relate?
* Are more vulnerable communities experiencing even higher death tolls than we think? 
* Are there certain kinds of vulnerability that make communities more susceptible to the impacts of COVID-19?
* Can excess mortality give us a more precise understanding of community vulnerability to COVID?

### Are you interested? 
We are looking for students interested in interdisciplinary research, with a background in classic machine learning techniques, large-scale data processing, and experience with census variables (race, ethnicity, income, education, occupation, etc.). Knowledge of Python or R is required.


## Project F: Evaluating Black Market Sales of Purported Treatments for COVID-19

### Context: 
Since the advent of Andrew Wakefield’s erroneous 1998 study linking the measles-mumps-rubella vaccine to the emergence of autism, vaccine hesitancy has taken root in the United States – the effects of which have been further exacerbated by misinformation about recently developed vaccine candidates to combat the COVID-19 pandemic. However, vaccine hesitancy (and acceptance!) isn’t uniform across American communities (neither in terms of hesitancy itself nor the motivations for it), which makes targeting interventions to address underlying concerns particularly challenging.

### Project Focus: 
Using page view and search data from Wikipedia (top) and Google (bottom), analyze the geographic heterogeneity of vaccine hesitancy and its motivations in the United States, with a focus on COVID-19-specific vaccination; then, conduct biostatistical analyses to determine risk factors to determine whether some populations are at greater risk for vaccine hesitancy – and different motivations for vaccine hesitancy – than others to help inform targeting of interventions.

### Are you interested? 
This project is ongoing with my research group. We are looking for students interested in interdisciplinary research, with a background in biostatistic, large-scale data processing, and/or research regarding misinformation. Knowledge of Python is recommended but not required for all team members.

Reach out on Twitter to learn more; find me at @maiamajumder


## Project G: Evaluating Black Market Sales of Purported Treatments for COVID-19

### Context: 
Fraudulent products and purported cures for COVID-19 have been commonplace in the news media since the beginning of the pandemic. Though not all of products that have been touted as potential cures require a prescription (i.e., Vitamin D), many of them (i.e., hydroxychloroquine, ivermectin, etc.) do – thus necessitating black market purchasing by everyday consumers who wish to acquire them.

### Project Focus: 
Using data from Google (top) and Reddit (bottom), determine interest in purchasing various purported treatments from the FDA’s fraudulent COVID-19 products database time and space; then, compare against interest in the news media using the MediaCloud platform to ascertain the influence of news coverage on purchasing interest. An optional additional analysis could include developing biostatistical models to determine which populations across the United States have thus far been at greatest risk of purchasing fraudulent COVID-19 products on the black market.

### Are you interested? 
This project is ongoing with my research group. We are looking for students interested in interdisciplinary research, with a background in large-scale data processing, natural language and text-based analyses, and/or research regarding misinformation. Knowledge of Python is recommended but not required for all team members; experience with biostatistical modeling is also a plus.

Reach out on Twitter to learn more; find me at @maiamajumder


## Project H: Early Warning Modeling Systems for COVID-19 Using Wastewater Data

### Context: 
Evidence suggests that wastewater may provide important RNA-based signals regarding local disease prevalence of COVID-19 prior to surges in identified cases and hospitalizations, though the mechanism of action is not presently well-understood. Other novel data streams for disease surveillance – such as search query data – have faced similar challenges in the early years of their utilization for the development of early warning modeling systems to enable improved resource allocation. These challenges have typically been overcome through the implementation of non-mechanistic – or phenomenological – modeling techniques across multiple data streams.

### Project Focus: 
Using phenomenological methods, develop an early warning modeling system that can offer short-term predictions for hospitalizations in select geographic regions where wastewater data are being collected by our partner organization, Biobot (right). This system should include wastewater as one input data stream, but should be paired with others (e.g., hospitalizations, search query, etc.) as well.

### Are you interested? 
This project is ongoing with my research group. We are looking for students interested in interdisciplinary research, with a background in large-scale data processing, natural language and text-based analyses, and/or pharmaceutical interventions. Knowledge of Python is recommended but not required for all team members.

Reach out on Twitter to learn more; find me at @maiamajumder


## Project J: Analyzing Clinical Trials for COVID-19 Using NLP

### Context: 
To date, nearly 5,000 studies regarding COVID-19 have been registered by the U.S. government. A wealth of text-based data is available for each trial, both as free text and as standardized fields. Detailed descriptions of interventions, outcomes, and eligibility criteria are also provided. Many of these trials aim to test the efficacy of various pharmaceutical interventions against COVID-19; however, eligibility restrictions often exclude certain special groups from such studies.

### Project Focus: 
Using data from clinicaltrials.gov (top), describe trends in COVID-19-related studies over the course of the pandemic. Special attention should be paid to eligibility criteria to determine the frequency at which special groups are excluded and how such exclusions may influence intervention practices in the months and years ahead. An optional additional analysis that evaluates the role of news media in scientific exploration could involve assessing whether interventions that have been commonly covered in news media as per MediaCloud (bottom) are also more commonly covered in trials.

### Are you interested? 
This project is ongoing with my research group. We are looking for students interested in interdisciplinary research, with a background in large-scale data processing, natural language and text-based analyses, and/or pharmaceutical interventions. Knowledge of Python is recommended but not required for all team members.

Reach out on Twitter to learn more; find me at @maiamajumder


## Project #K: NCD Digital Health for Refugees in Kenya

### Context: 
Digital health for NCD management in refugee populations. MIT Sana, JHU, and Dimagi deploying at International Rescue Committee (IRC) for refugee populations.  Scale up of previous implementation in Lebanon for Syrian refugees.

### Project Focus: 
Design, development, implementation, evaluation.

### Are you interested? 
kepaik@mit.edu
