---
layout: default
title: Water Quantity
nav_order: 3
---

# Water Quantity on the Diné Reservation

We wanted to look at water quantity to see if there could be a correlation between well depth and well contaminants.  Precipitation and runoff that are recharging wells could carry pollutants into groundwater. Contaminated wells that are being used could harm people, livestock and even become present in agricultural crops.  

“Generally, private wells do not receive the same services that wells supplying the public do. Well owner's are responsible for protecting their drinking water. To do so, a well owner must be aware of their well's potential for contamination and the possible health effects those potential contaminants can have” (EPA, 2024).


## Map of 5 Wells
We chose to analyze 5 USGS wells that are continuously monitored shown in Figure 3.1 

<img src = "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/mapWellDepth.png?raw=true" alt= "Map of Well Depth" width="50%" height="50%">

> *Figure 3.1 Location of wells monitored by the USGS.*

### How did we map that?

[![Depth Data Code](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/DepthDataCode3.jpg?raw=true)](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/37589d1e18ce6453b6cbf0a742ee1bc02605208a/Copy_of_ESIIL_Depth_Data.ipynb)

## Graphing Well Depth

Next, we analyzed the water depth at the USGS locations using graphs created through Python coding.  Water depth is the land surface to the surface of the water.  

Two well sites had fairly consistent depths annually between 2006-2022 (Figures 1 and 2).

![Map of Well 1](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/DepthWell1.png?raw=true)
![Map of Well 4](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/DepthWell4.png?raw=true)

> *Figures 1 and 2: Water levels stayed about the same.*

Three sites showed year-to-year changes in the depth of the wells.  Figure 3 shows that the aquifer is being recharged with the well depth decreasing and the water level rising.
This well might not be in use. Figures 4 and 5 are likely being used as the well depth is increasing and the water level is decreasing.

![Map of Well 3](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/DepthWell3.jpg?raw=true)

> *Figure 3: Aquifer was recharged with the well depth decreasing and the water level rising.*

![Map of Well 2](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/DepthWell2.jpg?raw=true)
![Map of Well 5](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/DepthWell5.jpg?raw=true)

> *Figures 4 and 5: These wells were likely in use as the well depth was increasing and the water level was decreasing.*

 
### How did we graph that?

[![Depth Data Code](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/DepthDataCode4.jpg?raw=true)](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/37589d1e18ce6453b6cbf0a742ee1bc02605208a/Copy_of_ESIIL_Depth_Data.ipynb)

## Depth not Statistically Significant

In python, we did an ANOVA test that found these changes were not statistically significant.  We started with the import: from scypi.stats import f_oneway.  Then, entered our values to calculate variance.  To see more, or to reference this code for your own project, click on the code image.

### How did we test that?

[![ANOVA Test](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/DepthDataCode7.jpg?raw=true)](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/37589d1e18ce6453b6cbf0a742ee1bc02605208a/Copy_of_ESIIL_Depth_Data.ipynb)


## Results

While the water levels did not change significantly, we don’t know whether wells contain contaminants from the Gold King Mine Spill.  More needs to be learned about the 
[water quality](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/2a252f78a491ddc01372c4dd522833f838bd241b/water-quality.md) 
of the wells and springs on the Diné Reservation before, during, and after the spill.
