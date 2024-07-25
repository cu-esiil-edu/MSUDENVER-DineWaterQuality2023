---
layout: default
title: Water Accessibility
nav_order: 5
---

# Water Accessibility on the Diné Reservation

<img src = "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/childrenInSand.png?raw=true" alt = "children playing in sand" width = "60%" height = "60%">

> *Figure 5.1: Children playing in the sand on a construction site during the period of time that uranium mining was ocurring on the Diné Reservation. 
Credit: rawpixel.com / U.S. National Archives (Source)*

## Location of Most Vulnerable Populations

We wanted to find out where the most sensitive people are located on the Diné Reservation and whether they live near well contamination.  To do this, we used US Census Bureau data to look at 3 vulnerable populations, ages 65 and up, women 15-50, and youth under 18. 

### Ages 65 and Up

We chose to look at ages 65 and up because of age-related health factors.  According to the CDC, 

> As people get older, their immune systems do not work as well. Older adults are also more likely to have underlying health conditions. Most deaths from respiratory viruses occur in people older than 65, with risk increasing sharply with advancing age (Centers for Disease Control and Prevention, 2024).

This aging population is especially vulnerable to the effects of heavy metals in water because they have likely been drinking the water for decades.  One metal of concern is arsenic. As discovered in our study of water quality, the EPA defines arsenic that is above 10 parts per billion (ppb) as unsafe. Arsenic was found in the amounts of 40 ppb in the surface water after the Gold King Mine Spill in 2015 and again in 2019 when water levels were high.  

Arsenic is harmful to most of the body systems. The first symptoms of long-term exposure to high levels of arsenic are usually observed in the skin and include pigmentation changes, skin lesions and hard patches on the palms and soles of the feet (hyperkeratosis). The International Agency for Research on Cancer has stated that arsenic in drinking-water is a carcinogenic to humans.  This is partly due to an increased risk of skin cancer in humans with 3 to 4 decades of exposure to contaminated water (Agency for Toxic Substances and Disease Registry, 2023a).


People ages 65 and older are a part of the generation that worked in the mines during the uranium mine boom. Many experienced or are currently experiencing repercussions such as lung cancer and liver failure. 

While not all people on the reservation worked in the mines, exposure didn’t just affect miners, it also impacted their families and communities.  A Diné woman described hand washing the yellow powder off of her husband’s clothing after he returned from the mines (Associated Press, 2011).
Others describe swimming in uranium-contaminated ponds and playing with contaminated dirt during childhood. They didn’t know it was dangerous (Calvert, 2021).

There are several products of uranium that can enter into groundwater.  One heavy metal is thorium.  Ingesting thorium can lead to bone and liver cancer.  This is concerning on the reservation as our study found 22 well or spring sites with thorium levels that exceed EPA limits (Figure 4.10).

Radon is another product of uranium.  Houses built on an area with uranium or built with rocks from the uranium mines, can contain high levels of radon as surrounding materials release radon into the air.  Many homes were built with rocks from the mines on the reservation.  Additionally, when uranium is in water, it can release radon into the air.  Dr. Frank Dalichow, the Diné oncologist, remarked ““People don't smoke out here, so where is all this cancer really coming from” (Calvert, 2021)? To some the answer is obvious, breathing in radon is linked to lung cancer in both smokers and non-smokers (Agency for Toxic Substances and Disease Registry, 2023b).  It is coming from the uranium mines.
 .  
### Map of Adults 65 and Older
<img src = "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/Map%2565up.jpg?raw=true" alt = "Map of Percent of Population 65 and Up" width ="60%" height ="60%">

> *Figure 5.2 Percent and location of the total population who are 65 and older on the Diné Reservation.*

### How did we map that?
To make this map, we divided the population above 65 years old by the total population and rounded it to the ones place, using the formula below. The P0 numbers are representative of US Census Populations and were pulled from a table. 

![65Up](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/65upcode5-%25.jpg?raw=true "65 and up sample code")

### Women Ages 15-50

Another vulnerable group we included in our study was fertility in women, which the US Census defines as women between the ages 15-50 years old (Figure 5.3).  In other words, this is the age span when women could become pregnant.  Especially at risk is the developing zygote, embryo or fetus, depending on stage of development, as contaminants pass from the placenta of the mother and through the umbilical cord to the child.  While developing, the embryo or fetus does not have the liver function to process contaminants as well as children and adults. This makes the unborn child very vulnerable.

In our surface water study, we looked at levels of lead and arsenic.  We found that the EPA limit of safety for lead is 15 ppb and in 2019, it spiked to over 500 ppb!  According to the American Academy of Pediatrics, there is no safe level of lead in children (American Academy of Pediatrics, 2024).  “Lead exposure is especially harmful to infants, fetuses, and children due to the developing nature of their brains” (Spicer, 2018).

In 2019, arsenic in surface water spiked to 40 ppb, which is 30 ppb above EPA safe limits. Arsenic is a reproductive toxicant and a teratogen, which means it can cause malformations. This is especially concerning as arsenic is readily transferred across the placenta, and concentrations in cord blood are similar to those in maternal blood.  Additionally, arsenic exposure in pregnant women can lead to miscarriage and infant mortality post birth (Agency for Toxic Substances and Disease Registry, 2023).

Additionally, manganese and uranium are concerns as contaminants to women 15-50.  Nervous system and reproductive effects have been observed in animals after high oral doses of manganese.  After the Gold King Mine Spill, manganese rose to 11,000 ppb in 2015 and 20,000 ppb in 2019 (Figure 4.4).  The EPA safe limit is 50 ppb and manganese has returned to that level.  Uranium continues to be present in women and their infants.  A New Mexico University study found:

> 26 percent of Navajo women currently have concentrations of uranium in their system that exceed levels found in the highest 5 percent of the U.S. population, and that newborns with equally high concentrations continue to be exposed to uranium during their first year (Calvert, 2021).

The level of uranium was found to exceed EPA safe drinking water limits in 27 wells and springs on the reservation (Figure 4.11).  Many of those are located in and near to Canyon de Chelly where 28% of the population are women ages 15-50 (Figure 5.3).

### Map of Women Ages 15-50

<img src = "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/Map%2515to50.jpg?raw=true" alt = "Map of percent of women ages 15-50" width = "60%" height = "60%" >

> *Figure 5.3: Location and the percent of the total population of women who are between the ages of 15 and 50 on the Diné Reservation.*  


### How did we map that?

After finding the women ages 15-50 out of the total population, we used the following code to create a choropleth map showing population percentages. 

![code for 15-50](https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/Sample%2515to50.jpg?raw=true "sample code for map") 

### People Under 18

Children and adolescents, under the age of 18, are legally not adults.  Physiologically this is also true as their brains and bodies are not fully developed.  For some, development may continue into the early 20s, but our data was confined by the US Census Bureau’s definition for adult, which is 18 years old.

Many of the contaminants we studied are of concern in the under 18 group.  Lead is a well known poison.

> The effects of lead exposure in children include, but are not limited to:
>    * Lower IQ
>    * Delayed or impaired neurological development
>    * Decreased hearing, speech and language disabilities
>    * Poor attention span, learning disabilities, and anti-social behaviors (Spicer, 2018)

Additionally, lead “can often cause problems with bones, replacing calcium,” which is a huge concern for a body experiencing bone growth.  It can cause delayed growth and also remains in the bones, so that the lead continuously causes neurological issues after exposure.  Neurological issues may show up as inattentiveness and disorganization (Agency for Toxic Substances and Disease Registry, 2023).

Antimony was found in the well water on the Diné Reservation. It has been shown to cause development effects in animals that swallow antimony. It can also cause liver damage and low blood sugar (Agency for Toxic Substances and Disease Registry, 2019).  It is safe to assume that it would impact humans similarly.

### Map of Percent of Population Under 18

<img src = "https://github.com/cu-esiil-edu/MSUDenver-DineWaterQuality2023/blob/main/img/Map%25under18.jpg?raw=true" alt="Map of Percent of Population Under 18" width = "60%" height = "60%">

> *Figure 5.4: In python with folium maps there is an option to create popups.  In the code, the mouse can roll over each attribute, in this case the block groups, and get a bubble that shows information.  In our code (bottom right) we specify that we want "% under 18" to show in the popup.*  


