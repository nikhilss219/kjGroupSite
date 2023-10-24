---
title: "Solid state hydrogen storage : Decoding the path through machine learning"
date: 2023-10-24T14:37:12.819Z
draft: false
featured: false
categories:
  - MachineLearning
image:
  filename: graphabstractfinal-papersize-.png
  focal_point: Smart
  preview_only: false
---
We present a machine learning (ML) framework HEART (HydrogEn storAge propeRty predicTor) for identifying suitable families of metal alloys for hydrogen storage under ambient conditions. Our framework includes two ML models that predict the hydrogen storage capacity (HYST) and the enthalpy of hydride formation (THOR) of multi-component metal alloys. We demonstrate that a chemically diverse set of features effectively describes the hydrogen storage properties of the alloys. In HYST, we use absorption temperature as a feature which improved H2wt% prediction significantly. For out-of-the-bag samples, HYST predicted H2wt% with R2 score of 0.81 and mean absolute error (MAE) of 0.45 wt% whereas R2 score is 0.89 and MAE is 4.53 kJ/molH2 for THOR. These models are further employed to predict H2wt% and ∆H for ∼ 6.4 million multi-component metal alloys. We have identified 6480 compositions with superior storage properties (H2wt% > 2.5 at room temperature and ∆H < 60 kJ/molH2). We have also discussed in detail the interesting trends picked up by these models like temperature de- pendent variation in the rate of hydrogenation and alloying effect on H2wt% and ∆H in different families of alloys. Importantly certain elements like Al, Si, Sc, Cr, and Mn when mixed in small fractions with hydriding elements like Mg, Ti, V etc. systematically reduce ∆H without significantly compro- mising the storage capacity. Further upon increasing the number of elements in the alloy i.e from binary to ternary to quaternary, the number of composi- tions with lower enthalpies also increases. From the 6.4 million compositions, we have reported new alloy families having potential for hydrogen storage at room temperature. Finally, we demonstrate that HEART has the potential to scan vast chemical spaces by narrowing down potential materials for hydrogen storage.