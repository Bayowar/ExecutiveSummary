# The Critical Influence of Air Pollution and Socioeconomic Status on Cardiovascular Disease Mortality Rates in the U.S. with Public Health and Social Justice Implications.

## Introduction

Cardiovascular disease (CVD) continues to be one of the leading cause of death in the United States. While its biomedical causes have been well-documented, this study expands the discourse by examining the intersection between air pollution—particularly fine particulate matter (PM2.5)—and socioeconomic status (SES). It reframes CVD as not merely a medical condition, but as a public health outcome shaped by socio-structural inequality and environmental injustice.

Communities with lower income, poorer healthcare access, and diminished political capital are disproportionately located in over-populated areas prone to increased pollution. These populations face dual vulnerabilities: they are more exposed to pollutants and less equipped to mitigate their health impacts.

<div class="image-grid">
    <img src="https://github.com/Bayowar/Bayowar.github.io/raw/c5634d96bb715680ac124ea24860391ac4420351/researchpaperdata2_0_0/output_103_0.png" alt="Average PM2.5 Levels in 2010">
    <img src="https://github.com/Bayowar/Bayowar.github.io/raw/c5634d96bb715680ac124ea24860391ac4420351/researchpaperdata2_0_0/output_103_1.png" alt="Average Cardiovascular Mortality Rates in 2010">
    <img src="https://github.com/Bayowar/Bayowar.github.io/raw/c5634d96bb715680ac124ea24860391ac4420351/researchpaperdata2_0_0/output_103_2.png" alt="Average Poverty Rate in 2010">
</div>

### Why Cardiovascular Disease is Significant.

Cardiovascular disease (CVD) is a class of diseases that affect the heart or blood vessels in simple terms. These conditions include and are not limited to coronary artery disease , stroke, heart failure and hypertension (more likely a risk factor). CVD is a critical public health concern due to its high prevalence and substantial impact on morbidity and mortality, contributing significantly to healthcare costs and reduced quality of life. An understanding of its determinants is essential for developing effective prevention, intervention strategies and for healthier communities.

### Air Pollution and Particulate Matter 2.5 (PM2.5).

Air pollution, particularly fine particulate matter (PM2.5), has emerged as a significant environmental risk factor for CVD. PM2.5 refers to minute airborne particles that are 2.5 micrometers in diameter or less. These particles can be inhaled through the bronchi, bronchioles and alveoli of the lungs, entering the bloodstream and triggering a cascade of adverse physiological responses.

Its vascular impacts are also documented as PM2.5 exposure is associated with increased inflammation, oxidative stress, endothelial dysfunction, and altered blood coagulation (Krittanawong et al.,). These processes contribute to the development and progression of atherosclerosis, hypertension, and CVD.

### Socioeconomic Status: Factors and Importance

Socioeconomic status (SES) is a multifaceted social construct encompassing various socio-economic factors significantly influencing individuals and communities. Key indicators of SES include income, which affects access to essential resources such as healthcare, healthy food, and housing; education, which shapes health literacy, employment prospects, and health-promoting behaviors; and healthcare access, which determines the availability and quality of medical services for disease prevention, diagnosis, and treatment. Notably, lower socioeconomic status is frequently associated with increased exposure to risk factors for cardiovascular disease.

### Public Health and Social Justice Implications

The confluence of elevated particulate matter 2.5 levels and low socioeconomic status (SES) carries significant implications for both public health and social justice. Communities characterized by lower SES frequently experience a disproportionate burden of cardiovascular disease (CVD). This disparity can be related to increased exposure to environmental pollutants coupled with diminished access to resources that could otherwise mitigate adverse health effects. The inequitable distribution represents a critical environmental injustice wherein marginalized populations are unjustly subjected to elevated health risks. Consequently, effectively addressing the multipronged challenge of CVD necessitates a holistic approach that integrates both biomedical and socio-environmental determinants. Interventions should be strategically designed to achieve a dual objective by reducing overall pollution levels and actively mitigating existing socioeconomic disparities to foster health equity.

This study analyzes data from 2,132 U.S. counties, using a cross-sectional approach to identify how geography, poverty, and pollution converge to produce avoidable, unequal mortality outcomes.This paper contributes to the growing body of research emphasizing the need for social justice policies that protect vulnerable populations and address health disparities driven by structural inequality.

## Research Purpose

This study addresses these questions:

* What is the association between air pollution(PM2.5), socioeconomic factors (poverty, education, and health insurance) and cardiovascular mortality rates in the U.S?
* How does hypertension mortality rate influence cardiovascular mortality rates in the U.S?

The study adopts a multifactorial framework, emphasizing how environmental and social stressors interact in a way that intensifies harm beyond their individual effects.

## Methodology

The analysis draws from nationally verified data sources:

* Environmental Protection Agency (EPA): PM2.5 estimates (1990–2010) and county-level SES indices.
* National Center for Health Statistics (NCHS): Age-adjusted cardiovascular and hypertension mortality rates.
* American Community Survey (2009–2010): Income, education, insurance status, and poverty data.

Data were cleaned, merged using FIPS codes, and analyzed using Python-based tools. Key engineered features include uninsured rates, education levels, and poverty rates. The timeline was constrained to 2009–2010 to maintain alignment and statistical relevance across datasets.

Exploratory anslysis, descriptive statistics, correlation analysis,regression models and visualizations were done to reveal trends in our cross-sectional analysis of data from year 2009 and 2010.

### Limitations.

Lack of causality due to the snap-shot nature of cross-sectional data.

## Analysis

Our findings reveal that impact of socioeconomic disparities are as significant as pm2.5 exposure on CMR. A few southern states ranked high on pollution and cardiovascular mortality, and low on income and education, suggesting geographic clustering of socio-environmental injustice associated with increased cardiovascular disease mortality rate.

### Pollution and CMR

PM2.5 exposure was a statistically significant predictor of cardiovascular mortality.Higher PM2.5 exposure is associated with increased cardiovascular mortality, reinforcing concerns about air pollution's influence on heart disease and its mortality rate.

### Role of Socioeconomic Status

SES emerged as a risk multiplier showing lower-income locations with higher uninsured populations and lower educational attainment had elevated CVD mortality rates. This supports the concept of multifactorial cumulative disadvantage—where multiple vulnerabilities intersect to worsen adverse health outcomes.

<img src="https://github.com/Bayowar/Bayowar.github.io/raw/c5634d96bb715680ac124ea24860391ac4420351/researchpaperdata2_0_0/output_128_0.png" alt="Scatterplot showing SES factors,PM2.5 and CMR">

### Hypertension and Cardiovascular Mortality

While our visualizations suggest a potentially weak direct influence of overall hypertension mortality rates on cardiovascular mortality rates—an expected finding given the multifactorial nature of CMR, which can be linked to various factors sometimes interrelated with hypertension—our regression model revealed a statistically significant positive relationship between hypertension-related death rates and cardiovascular mortality rates. However, there were implications that other significant conditions or factors, such as PM2.5 levels and broader socioeconomic determinants, likely exert substantial influence and warrant further investigation.

<img src="https://github.com/Bayowar/Bayowar.github.io/raw/c5634d96bb715680ac124ea24860391ac4420351/researchpaperdata2_0_0/output_152_0.png" alt="Barchart showing Hypertension rates and Cardiovascular Mortality Rates">

It is important to note that these are ecological correlations. While they can suggest potential relationships at the population level, they do not establish individual-level causation. Further individual-level studies would be needed to confirm these associations and understand the underlying mechanisms.

## Recommendations

* Achieving socio-environmental justice demands immediate, transformative action through a decisive four-year phased strategy.
* By prioritizing high-burden areas initially for stricter, vulnerability-based air quality regulations and robust enforcement across individuals, entrepreneurs, businesses, and industries.
* Concurrently, a phased expansion of healthcare access via mobile clinics and Medicaid is important.
* Long-term resilience requires phased investments in education and green job creation.
* System-wide building permitting reform mandating Green or Social Health Equity Impact Assessments is essential.
* The initial phase necessitates a 100 million dollar grant allocation with joint EPA-HHS task force oversight, emphasizing parallel state legislation, meaningful community engagement, transparency, and strict, ongoing impact evaluation to inform action and improve lives in the most vulnerable communities.

## Conclusion

This paper concludes that the study of socioeconomic status (SES) and PM2.5 exposure on cardiovascular disease (CVD) mortality rates in the U.S. reveals a significant interplay where lower SES exacerbates the negative health effects of air pollution, leading to higher cardiovascular death rates in communities. Addressing this requires a fundamental four-year policy shift involving stricter air quality regulations prioritizing burdened, low-SES areas, expanded healthcare access, investments in community education and green jobs, and permit reforms mandating equity impact assessments. The proposed implementation emphasizes community involvement and rigorous evaluation, advocating for proactive prevention and the dismantling of systemic inequalities to achieve socio-environmental and health justice.
