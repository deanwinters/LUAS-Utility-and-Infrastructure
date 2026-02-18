# LUAS-Utility-and-Infrastructure
**2025 Dean Winters**

## What is this?
This small project explores the ability of Dublin's two LUAS tram lines to meet passenger demand. Data taken for this investigation is sourced from the CSO (tag: TOA10). 

## Why?
Transport demands are not static. It is thus important to identify aspects of transport infrastructure that excel, and those that require, or may in future require, additional infrastructure. This can be examined with the dataset specifically by LUAS line, per year.

What is the peak load of the LUAS service? This problem may arise due to special occasions such as match days. For instance, at the time of writing there will be three large events taking place in Dublin on the 22nd/Nov/2025 - two large music concerts, and a large sporting event.
While that is specific to a singularity (one day), there are instances where a high load demand may be spread across weeks or months (for example: hosting Euro2028, hosting a Rugby World Cup, national commemorative events such as 1916-2016, etc.). Knowing the total load the LUAS may offer as service for events or indeed multi-events is important for city-wide planning (e.g.: road closures, Garda presence).
If Ireland is to apply/organise to host any major events in Dublin, generating these figures as part of the tender process is imperative.


## What is quantified?

The CSO provides detailed statistics for each LUAS line for 2018-2024. Annual ridership, average journey length, tram infrastructure (track length, car capacity), punctuality, among others. A theoretical passenger bandwidth for each line is inferred from the data and used in forecasting analysis. 

This bandwidth is simply the highest number of services ran in a calendar year multiplied by the car capacity of that line of that year. To note, the maximum value of the total vehicle run annual reports is taken to be near the physical limit for the amount of services LUAS could run on either line without heavily propagated delays. This is supported by some analysis of the relationship between annual vehicle runs and timeliness provided in the notebook.

## Some key findings

LUAS passenger traffic is observed to be severely stunted for the years 2020 and 2021 due to the Covid19 pandemic. Overall, the LUAS has seen increased use from pre-pandemic levels – both LUAS lines have seen an increase on annual ridership. Besides this, LUAS use has continued to rise, and in 2024 both lines saw their peak annual use since at least 2018. The introduction of higher-capacity rolling stock to the Green Line forecasts an even further growth.

The LUAS has maintained a high level of punctuality over the seven-year window, with both lines never falling short of 90% on-time servicing annually. In particular the Green Line consistently reports greater than 97% timeliness. The largest dip in punctuality was observed on the Red Line in 2022, where 90.73% of services arrived on-time. Service punctuality on both lines remains exceptionally high despite the year-on-year peak annual ridership figures.

The Red Line saw ridership that reached 85.9% of its bandwidth in the last year reported. The Green Line serviced 72.2% of its bandwidth in the same time period. This leaves less than 10% and 30% for the Red and Green lines respectively to service excess demand due to multievents, and if the increasing ridership trend continues this excess capability will further diminish. In total, the LUAS offers an estimated 13 million passengers excess capability for multievents, with the Green Line offering the majority with 10 million passengers. 
As LUAS continues to facilitate an increasing amount of vehicle service runs per year post-pandemic, there is an increased risk of this load factor further approaching maximum. 

