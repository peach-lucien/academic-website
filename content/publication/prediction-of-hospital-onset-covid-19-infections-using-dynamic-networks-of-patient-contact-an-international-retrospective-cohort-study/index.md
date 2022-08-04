---
title: "Prediction of hospital-onset COVID-19 infections using dynamic networks
  of patient contact: an international retrospective cohort study"
publication_types:
  - "2"
authors:
  - Ashleigh Myall
  - James R Price
  - Robert L Peach
  - Mohamed Abbas
  - Sid Mookerjee
  - Nina Zhu
  - Isa Ahmad
  - Damien Ming
  - Farzan Ramzan
  - Daniel Teixeira
  - Christophe Graf
  - Andrea Y Weiße
  - Stephan Harbarth
  - Alison Holmes
  - Mauricio Barahona
doi: https://doi.org/10.1016/S2589-7500(22)00093-0
publication: "The Lancet Digital Health 4.8 (2022): e573-e583."
abstract: >+
  Background


  Real-time prediction is key to prevention and control of infections associated with health-care settings. Contacts enable spread of many infections, yet most risk prediction frameworks fail to account for their dynamics. We developed, tested, and internationally validated a real-time machine-learning framework, incorporating dynamic patient-contact networks to predict hospital-onset COVID-19 infections (HOCIs) at the individual level.

  Methods


  We report an international retrospective cohort study of our framework, which extracted patient-contact networks from routine hospital data and combined network-derived variables with clinical and contextual information to predict individual infection risk. We trained and tested the framework on HOCIs using the data from 51 157 hospital inpatients admitted to a UK National Health Service hospital group (Imperial College Healthcare NHS Trust) between April 1, 2020, and April 1, 2021, intersecting the first two COVID-19 surges. We validated the framework using data from a Swiss hospital group (Department of Rehabilitation, Geneva University Hospitals) during a COVID-19 surge (from March 1 to May 31, 2020; 40 057 inpatients) and from the same UK group after COVID-19 surges (from April 2 to Aug 13, 2021; 43 375 inpatients). All inpatients with a bed allocation during the study periods were included in the computation of network-derived and contextual variables. In predicting patient-level HOCI risk, only inpatients spending 3 or more days in hospital during the study period were examined for HOCI acquisition risk.


  Findings


  The framework was highly predictive across test data with all variable types (area under the curve [AUC]-receiver operating characteristic curve [ROC] 0·89 [95% CI 0·88–0·90]) and similarly predictive using only contact-network variables (0·88 [0·86–0·90]). Prediction was reduced when using only hospital contextual (AUC-ROC 0·82 [95% CI 0·80–0·84]) or patient clinical (0·64 [0·62–0·66]) variables. A model with only three variables (ie, network closeness, direct contacts with infectious patients [network derived], and hospital COVID-19 prevalence [hospital contextual]) achieved AUC-ROC 0·85 (95% CI 0·82–0·88). Incorporating contact-network variables improved performance across both validation datasets (AUC-ROC in the Geneva dataset increased from 0·84 [95% CI 0·82–0·86] to 0·88 [0·86–0·90]; AUC-ROC in the UK post-surge dataset increased from 0·49 [0·46–0·52] to 0·68 [0·64–0·70]).

draft: false
featured: true
tags:
  - networks
  - healthcare
categories:
  - networks
  - healthcare
projects:
  - networks
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
summary: Dynamic contact networks are robust predictors of individual patient
  risk of HOCIs. Their integration in clinical care could enhance individualised
  infection prevention and early diagnosis of COVID-19 and other nosocomial
  infections.
date: 2022-08-04T10:01:51.144Z
---
