---
layout: default
title: Water Quality
nav_order: 4
---

# Water Quality on the Diné Reservation

There are many benchmark indicators of water, such as the amount of turbidity and pH that determine whether water is healthy. Heavy metal is one such indicator.
In naturally occurring ecosystems, untouched by human activity, the presence of heavy metals in water is usually low.

Often times heavy metals rise due to human activity such as mining and extraction of natural resources. Disturbance to rock can loosen heavy metals that eventually reach water sources. 
The level of heavy metals in water can have many environmental and health implications.

## Surface Water Quality

We wanted to find out if there were heavy metals in the water on the Diné Reservation and if those heavy metals were there because of the Gold King Mine Spill. 
We started by examining surface water. To examine the water quality before and after the Gold King Mine spill, we chose to look at the heavy metal contaminants, 
arsenic, lead, aluminum, iron, and manganese. Arsenic and lead are primary pollutants and the others are secondary. 
Primary pollutants take a lot less of the pollutant to be dangerous to health than secondary pollutants (*Table 4.1*).  
  

<table>
  <tr>
   <td><strong>Contaminant </strong>(primary pollutants in bold)
   </td>
   <td><strong>EPA limits for safe drinking water</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Arsenic</strong>
   </td>
   <td>10 ppb (parts per billion)
   </td>
  </tr>
  <tr>
   <td><strong>Lead</strong>
   </td>
   <td>15 ppb
   </td>
  </tr>
  <tr>
   <td>Aluminum
   </td>
   <td>200 ppb
   </td>
  </tr>
  <tr>
   <td>Iron
   </td>
   <td>300 ppb
   </td>
  </tr>
  <tr>
   <td>Manganese
   </td>
   <td>50 ppb
   </td>
  </tr>
</table>

> *Table 4.1: Contaminants and the Recommended EPA Limit for Safe Drinking*

Furthermore, we wanted to find out if the heavy metals made the water unsafe to drink.  
The EPA sets limits for the amount of contaminant present for drinking water to be safe.  
For each metal, we compared the presence of heavy metals to the EPA limit.

### Surface Water Testing Sites Map

There are many EPA water testing sites on the Diné Reservation.  We analyzed data collected at these sites, mapped here:

![Surface Water Sampling Sites](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/SurfaceWaterSamplingMap3.jpg?raw=true "surface water sampling sites")

> *Figure 4.1: Map showing where surface water was tested on the Diné Reservation.*

### How did we map that?
Below is a sample of code from this map.
Click on the image to view the complete code on GitHub.com. 
From there, you can fork the code to reproduce your own project.

[![Surface Water Sample Code](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/SurfaceWaterExampleCode.jpg?raw=true 
"Surface Water Sample Code")](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/ESIIL_stars_dine_water_analysis.ipynb)

### Heavy Metal Results Graphs

We chose to look at the monthly maximum readings of each heavy metal where the maximum exceeded the EPA limit.

<img src= "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/ArsenicGraph2.jpg?raw=true" alt = "Arsenic Graph" width="95%" height="95%">

> *Figure 4.2: Arsenic spikes before the Gold King Mine Spill in 2012 and immediately after the Gold King Mine Spill. 
Secondary spikes occurred after the spill, with the largest spikes in 2019.*



![Lead and Al](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/LeadAluminumGraph.jpg?raw=true "Lead and Aluminum Graphs")

> *Figure 4.3: Both lead and aluminum were not present before the Gold King Mine Spill, but were present afterward, with a secondary spike in 2019.*



![Iron and Manganese](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/IronManganeseGraph.jpg?raw=true "Iron and Manganese" )

> *Figure 4.4: The EPA began monitoring for iron and manganese a few days after the Gold King Mine Spill, so levels beforehand are unknown.
> There were secondary spikes, the largest in 2019.*



### How did we graph that?
Below is a sample of code from these graphs.
Click on the sample to view the complete code on GitHub.com. 
From there, you can fork the code to reproduce your own project.

[![Heavy Metals Sample Code](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/heavyMetalsCode3.jpg?raw=true
"Heavy Metals Sample Code")](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/91b255b7b3177e104ff4443e5581fc3f5e798ee5/Copy_of_Surface_Water_Data.ipynb)
![Heavy Metals Sample Code](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/heavyMetalsCode4.jpg?raw=true
"Heavy Metals Sample Code Graph")

### What happened in 2019?

With the consistent spikes in heavy metals in 2019, we suspected that the stream discharge was higher than normal.  Using Python coding and the (source) we decided to check. 
The stream flow in the graph below, shows that there was a high discharge of water in 2019.

<img src="https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/MonthlyMaxDischarge.jpg?raw=true" alt =
"Max Monthly Discharge for Dine Reservation 2005-2022"  width="70%" height="70%">

> *Figure 4.5: High peak in stream flow in 2019 on the San Juan River.*

In our second analysis, we found that there was a 75-year flooding event and a high peak in stream flow in 2019.  The event likely caused the heavy metals that had settled into the sediment to loosen and reappear in the water. 

<img src="https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/ReturnPeriodMonthlyFlow.jpg?raw=true" alt ="Return Period of Peak Flows" width="70%" height="70%">

> *Figure 4.6: This graph shows the return period for flow events on the y-axis.  The return period is how often a flow at that level occurs.
> In 2019 there was a 75-year flooding event.*


Not all samples were above acceptable limits.  Table 4.2 shows the percent of samples above EPA acceptable limits.  Sometimes levels didn’t have concerning levels of a particular heavy metal.  However, just the possibility, made it a health risk to drink water at that time. Looking at this table, one could surmise a 2 in 10 chance that their glass of water could have concerning levels of arsenic and lead between 2012-2022 (see previous graphs).  Likewise, a glass of water had a 9 in 10 chance of containing concerning levels of aluminum, iron, and manganese.


<table>
  <tr>
   <td><strong>Contaminant </strong>
   </td>
   <td><strong>Percentage of Samples Above EPA Acceptable Limits</strong>
   </td>
   <td><strong>EPA limits for safe drinking water</strong>
   </td>
  </tr>
  <tr>
   <td>Arsenic
   </td>
   <td><strong>15.5%</strong>
   </td>
   <td>10 ppb (parts per billion)
   </td>
  </tr>
  <tr>
   <td>Lead
   </td>
   <td><strong>24.3%</strong>
   </td>
   <td>15 ppb
   </td>
  </tr>
  <tr>
   <td>Aluminum
   </td>
   <td><strong>88.0%</strong>
   </td>
   <td>200 ppb
   </td>
  </tr>
  <tr>
   <td>Iron
   </td>
   <td><strong>87.5%</strong>
   </td>
   <td>300 ppb
   </td>
  </tr>
  <tr>
   <td>Manganese
   </td>
   <td><strong>88.4%</strong>
   </td>
   <td>50 ppb
   </td>
  </tr>
</table>

> *Table 4.2: Percent of surface water testing sites with contaminants above EPA acceptable limits for safe drinking water.*

### Surface Water Quality Results
In our findings, after the Gold King Mine Spill, there was a rise in the heavy metals arsenic, lead, aluminum, iron, and manganese.  Figures 4.2 - 4.4 show the levels rose beyond the EPA limits for safe drinking water. The heavy metals settled and then spiked again in 2019.  Further analysis revealed there was a high stream flow in 2019, likely causing the stream bed to re-invigorate the heavy metals.  This caused secondary spiking to levels much higher than initially in 2015 and 2016. In 2021, Arsenic spiked again to unacceptable limits for unknown reasons (*Figure 4.2*). 

## Well and Spring Water Quality

In addition to checking for surface water quality, we checked for well and spring water quality.  Well and spring water is an important source of drinking water on the Diné Reservation.  On the EPA website, we found water sampling data for a variety of wells on the reservation.  This site showed an EPA risk rating and exceedance values of heavy metals, including aluminum (Al), thorium (Th), antimony (Sb), and uranium (U), which we focused on in our analysis.

<img src="https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/EPAWaterSamples2.jpg?raw=true" alt="EPA Table of Water Samples">

> *Figure 4.7: EPA table, in csv format, of water sampling on the Diné Reservation.* 

First we made a map of the EPA’s testing sites. There are a total of 225 testing sites, the  map showing the location of heavy metals we analyzed.

<img src= "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/WellandSpringMap.jpg?raw=true" alt="Wells and Springs on the Reservation" width="60%" height="60%">

> *Figure 4.8: Locations of wells and springs tested by the EPA that contain Al, Th, Sb, and U.*


### How did we code that?

To code this, we used the csv in the EPA Sampling Table and combined it with the Diné Reservation map.

<img src ="https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/WellandSpringCode1.jpg?raw=true" alt= "Well and Spring Code 1" >
<img src ="https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/WellandSpringCode2.jpg?raw=true" alt= "Well and Spring Code 2" >
<img src ="https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/WellandSpringCode3.jpg?raw=true" alt= "Well and Spring Code 3" >
<img src ="https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/WellandSpringCodeFinal.jpg?raw=true" alt= "Well and Spring Code 4" >

### Well and Spring Testing Sites Maps

The following sites were tested for aluminum, thorium, antimony, and uranium.  We looked at the exceedance values of the EPA’s limits for safe drinking water. 

The data was collected between 1998-2000, before the Gold-King Mine spill. The presence of these metals could be natural or, more likely, could have entered the groundwater by uranium mining that occurred between 1944 and 1986.  

<img src= "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/AIExceedance2.jpg?raw=true" alt="Map of Wells with Exceedance of aluminum" width="60%" height="60%">

> *Figure 4.9: The red dots on the map show the location of 17 sites with aluminum values that exceed safe drinking water limits.*

### How did we code that?

To make this map, we called in the Exceedance of Aluminum column from the table.
![Exceedance of Al](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/ExceedanceofAlCode2.jpg?raw=true)

<img src= "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/ThExceedance2.jpg?raw=true" alt="Map of Wells with Exceedance of thorium" width="60%" height="60%">

> *Figure 4.10: The red dots on the map show the location of 22 sites with thorium values that exceed safe drinking water limits.*

<img src= "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/UExceedance.jpg?raw=true" alt="Map of Wells with Exceedance of uranium" width="60%" height="60%">

> *Figure 4.11: This map shows the location of 27 sites with uranium values that exceed safe drinking water limits.*

<img src= "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/SbExceedence.jpg?raw=true" alt="Map of Wells with Exceedance of antimony" width="60%" height="60%">

> *Figure 4.12: This map shows the location of 3 sites with antimony values that exceed safe drinking water limits.*


### Well and Spring Sites Results

We found that there is not only a concern of heavy metals in the water from the Gold King Mine spill, but there are likely still heavy metals present from historic uranium mining.
The last sampling of heavy metals was in 2000. More data needs to be collected to calculate if these heavy metals still exist today and whether they have increased or decreased.
An increase could indicate that pollution reached the groundwater from the Gold King Mine Spill.  

Next, we wondered how the heavy metals could have impacted the community and their health.  Our findings can be viewed in the section, [Water Accessibility](https://cu-esiil-edu.github.io/MSUDenver-DineWaterQuality2023/water-accessibility.html).



