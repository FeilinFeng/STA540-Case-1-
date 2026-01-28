# STA540 Case 1

This is the homework for STA 540 Case Study, Duke University. This homework aims to reproduce the result for paper "Relative Effectiveness of Social Media, Dating Apps, and Information Search Sites in Promoting HIV Self-testing: Observational Cohort Study" (Stafylis et al., 2022). 

## Study Overview
### Background & Motivation 
The incidence of HIV is still high among minority men who have sex with men (MSM). While HIV self-testing is a crucial tool for early detection, its adoption remains inadequate. Digital platforms (social media sites, dating apps, and information search sites) offer a useful way to reach these high-risk populations, but their effectiveness maybe different. Therefore, this study aims to evaluate which specific types of platforms are most effective in promoting HIV self-testing usage among MSM.


### Primary Objectives
The primary objective of this study is to compare the relative promotional effectiveness among MSM recruited through three types of web-based platforms, using the HIV self-test order rate as the primary outcome. 

### Secondary Objectives
The secondary objective of this study is to assess the characteristics differences between participants who ordered the test kit and those who did not. Characteristics of interest include their substance use, stage of health behavior change, attitudes toward HIV testing and treatment, HIV-related stigma, and medical mistrust. 


## Replicated Table 1

The replicated Table 1 is shonw below. The relevant code is stored in the `code.rmd`.
|Characteristic                                                          |Value      |
|:-----------------------------------------------------------------------|:----------|
|Age in years, median (IQR)                                              |25 (21-27) |
|Ethnicity, n (%)                                                        |66 (26)    |
|Hispanic/Latinx                                                         |66 (26)    |
|Not Hispanic/Latinx                                                     |66 (26)    |
|Race, n (%)                                                             |           |
|American Indian or Alaskan Native                                       |1 (0.4)    |
|Black or African American                                               |196 (78.4) |
|White                                                                   |28 (11.2)  |
|Other                                                                   |14 (5.6)   |
|Multiracial                                                             |11 (4.4)   |
|History of PrEP uptake, n (%)                                           |           |
|Never taken PrEP                                                        |232 (91.3) |
|In the past 6 months                                                    |22 (8.7)   |
|Number of male sex partners in the past 90 days, median (IQR)           |4 (3-6)    |
|Condom use, n (%)                                                       |           |
|Never                                                                   |36 (14.2)  |
|Sometimes                                                               |108 (42.5) |
|About half the time                                                     |37 (14.6)  |
|Most of the time                                                        |68 (26.8)  |
|Always                                                                  |5 (2.0)    |
|Condomless receptive anal sex in the past 90 days, n (%)                |210 (82.7) |
|Ever tested for HIV during lifetime, n (%)                              |191 (75.2) |
|Months since last HIV test                                              |11 (6-21)  |
|If not tested for HIV, n (%)                                            |63 (24.8)  |
|Main reasons cited by the 63 participants for not getting tested, n (%) |           |
|Unlikely to be exposed to HIV                                           |8 (12.7)   |
|Afraid of testing HIV-positive                                          |26 (41.3)  |
|Did not want to think about HIV/HIV-positive                            |8 (12.7)   |
|Worried about names being reported if positive                          |3 (4.8)    |
|Dislike for needles                                                     |5 (7.9)    |
|Unable to trust that the results will be confidential                   |3 (4.8)    |
|Unaware of where to get tested                                          |7 (11.1)   |
|Other reasons                                                           |3 (4.8)    |

## Replicated Results

### Primary Analysis Results

The cell-specific order rates are shown below.

|WAVE |SITE      | ORDER | WAVE TIME|SITE TYPE    | ORDER RATE|
|:----|:---------|---:|---------:|:------------|--------:|
|1    |Facebook  |  13|        70|Social Media |    0.186|
|1    |Google    |  17|        70|Info Sites   |    0.243|
|1    |Grindr    |   9|        70|Dating Apps  |    0.129|
|2    |Instagram |  13|        38|Social Media |    0.342|
|2    |Jack'd    | 125|        38|Dating Apps  |    3.289|
|2    |Bing      |   0|        38|Info Sites   |    0.000|

The pairwise contrast results are shown below. The p-value is adjusted using Benjamini-Hochberg correction.

|contrast                   |WAVE |        ratio|           SE|  df| null| z.ratio| p.value|
|:--------------------------|:----|------------:|------------:|---:|----:|-------:|-------:|
|Dating Apps / Info Sites   |1    | 5.290000e-01| 2.180000e-01| Inf|    1|  -1.543|   0.369|
|Dating Apps / Social Media |1    | 6.920000e-01| 3.000000e-01| Inf|    1|  -0.848|   0.467|
|Info Sites / Social Media  |1    | 1.308000e+00| 4.820000e-01| Inf|    1|   0.728|   0.467|
|Dating Apps / Info Sites   |2    | 6.064565e+11| 2.562107e+16| Inf|    1|   0.001|   1.000|
|Dating Apps / Social Media |2    | 9.615000e+00| 2.802000e+00| Inf|    1|   7.767|   0.000|
|Info Sites / Social Media  |2    | 0.000000e+00| 0.000000e+00| Inf|    1|  -0.001|   1.000|

## Study Replication Reflection


## References
