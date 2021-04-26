# Garcia_Choi_Pang_ENV872_ProjectRepository
Repository for final class project for Environmental Data Analytics (ENV 872). Group: Grace (Eun Hye) Choi, Qiaotong Pang, &amp; Jessica Garcia

Sea Turtle Protection Policies & Light Pollution
<Group Project for Environmental_Data_Analytics_2021 (Spring 2021)>
<Created by Grace Choi, Qiaotong Pang, & Jess Garcia>

<Data Source>
The artificial light data were obtained from the Defense Meteorological Satellite Program (DMSP) Operational Linescan System (OLS). 
DMSP OLS: Nighttime Lights Time Series Version 4, Defense Meteorological Program Operational Linescan System. (n.d.). Google Developers. 
https://developers.google.com/earth-engine/datasets/catalog/NOAA_DMSP-OLS_NIGHTTIME_LIGHTS

Sea Turtles Lighting Ordinances for Florida Counties and Municipalities were obtained from Sea Turtle Protection Ordinances. (n.d.). 
Florida Fish And Wildlife Conservation Commission. https://myfwc.com/conservation/you-conserve/lighting/ordinances/

<Data Structure>
The annual radiance data covers from 1992-2013.
The data were documented from a total of 55 locations. For the purpose of this project, we chose to only include counties/municipalities 
that adopted sea turtle protection ordiannces between 1994-2011.

<Units of measure>
-avg_lights_x_pct: "The average visible band digital number (DN) of cloud-free light detections multiplied by the percent frequency of light detection. 
The inclusion of the percent frequency of detection term normalizes the resulting digital values for variations in the persistence of lighting. 
For instance, the value for a light only detected half the time is discounted by 50%. Note that this product contains detections from fires and a 
variable amount of background noise"

<Repository Compliers>
https://github.com/jmg144/Garcia_Choi_Pang_ENV872_ProjectRepository
