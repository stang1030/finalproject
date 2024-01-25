---
title: Analyzing the Incidence of Lung Cancer in the US Over Time
author: Sophia Tang
---

+++ {"part": "abstract"}
Here is a summary of my work.
+++

## Introduction
This project was put together for the NCSSM J-Term on open source science. I used data from the World Health Organization's [Global Cancer Observatory](https://gco.iarc.fr/). In their database, they have a dataset of time trends of cancer incidence and mortality for over half a century from 60 countries. I chose to look specifically at the **lung cancer incidence** in the US, and the differences between male and female cancer patients. 

## Tables
*All other analyses (crude rate, cumulative risk, etc) were calculated using these totals.*
### *Total Incidences of Lung Cancer in Women, Yearly*
![](#femalescruderate)
### *Total Incidences of Lung Cancer in Men, Yearly*
![](#malescr)

## Graphs
**Comparing the crude rate of lung cancer incidence in males vs. females over time.**
![](#crchart)
:::{dropdown} What is **crude rate**?
:open:
The crude rate is the ratio of the number of new cases in a specified population and time period to the size of the population at risk during the same time period. Incidence rate is usually presented as an annual rate per 100,000 persons at risk. [ECIS](https://ecis.jrc.ec.europa.eu/info/glossary.html) 

$CR = (E/P) * K$
Where E=incidence, P=mid-year total population, K=constant
:::

**Comparing the cumulative risk of lung cancer incidence in males vs. females over time.**
![](#cumulativerisk)
:::{dropdown} What is **cumulative risk**?
:open:
Cumulative incidence is the probability of individuals getting the disease over a specified age-span. Cumulative risk is expressed as the number of cases/deaths per 1000 person-years that are expected to occur in a given population between the specified age limits if the cancer rates were as those observed in the specified time period in the absence of competing causes. [ECIS](https://ecis.jrc.ec.europa.eu/info/glossary.html)

$CI=New cases/Population at risk$
:::

**Comparing the age-standardized rate of lung cancer incidence in males vs. females over time.**
![](#asr)
:::{dropdown} What is **age-standardized rate**?
:open:
The ASR is a weighted mean of the age-specific rates where the weights are taken from the population distribution of a standard population; the ASR is expressed per 100,000. Comparison of rates referring to different time periods or different geographical areas is only possible after considering the differences in the age structure of the underlying populations. The age-standardisation allows the comparison of the rates that are arithmetically adjusted to have the same age structure of the standard population. [ECIS](https://ecis.jrc.ec.europa.eu/info/glossary.html)
:::

## What does this data mean?
While the three graphs shown are all different measurements of the incidence of lung cancer, they all show the same trend. 

For all three graphs, the male and female lines start farthest apart at 1975. Overall, there is a higher incidence of lung cancer in males. Over time, they begin to converge. By 2016, they are extremely close together. The female incidence of lung cancer stayed fairly constant over time, but the three measures of incidence are actually slightly higher in 2016 than 1975. Interestingly, the male incidence decreased drastically beginning at some point between 1980 and 1990. 

### Why is this trend happening? 
According to a recent editorial commentary on the impact of cancer control in the US, while lung cancer continues to be the leading cause of cancer mortality globally, 2021 statistics from the American Cancer Society reported declines in lung cancer incidence and mortality rates in both males and females. This reflects the successful efforts over the years to institute tobacco control measures, increased early diagnosis, and subsequent treatment. Adult cigarette smoking prevalence decreased by 29.8% in males and 38.7% in females from 1990 to 19.9% and 15.3% in females in 2019. This shows the increased public awareness of the hazards of smoking, public smoking restrictions, and less accessibility to cigarette products [](doi:10.21037/ace-21-5). This helps explain why male and female lung cancer incidence are converging. 



