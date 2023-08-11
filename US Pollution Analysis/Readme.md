# US Pollution Analysis

![](https://github.com/Ingalesagar/PortfolioProjects/blob/main/US%20Pollution%20Analysis/US%20Pollution.png)

## Introduction
Air pollution is the contamination of air due to the presence of substances in the atmosphere that are harmful to the health of humans and other living beings, or cause damage to the climate or to materials.

This dataset provides you with the pollution in the U.S. It contains daily data for the four major pollutants NO2, O3, SO2, and CO each having 5 specific columns during 2006 and 2010.

Abbreviations: Carbon Monoxide (CO), Ozone (O3), Sulphur Dioxide (SO2), Nitrogen Dioxide (NO2)

## Problem Statement:
 **CO Pollutants**:
1.	Top 10 states with highest CO pollutants
2.	Find 1st max CO hour & value, display with card
3.	Show CO units calculation with card
4.	Table: CO in AQI by state, highlight high/low
5.	Chart: Max CO in each state
6.	Line chart: CO in AQI per year
7.	Top city: 1st CO pollutant
8.	Slicer: Interactive state selection
9.	Sync slicer: Date range for CO analysis
    
**O3 Pollutants**:
1.	Top 10 states with highest O3 pollutants
2.	Find 1st max Ozone hour & value, display with card
3.	Show Ozone units calculation with card
4.	Table: Ozone in AQI by state, highlight high/low
5.	Chart: Max O3 in each state
6.	Line chart: O3 in AQI per year
7.	Top city: 1st O3 pollutant
8.	Slicer: Interactive state selection
9.	Sync slicer: Date range for O3 analysis
    
**SO2 Pollutants**:
1.	Top 10 states/cities with highest SO2 pollutants
2.	Find 1st max SO2 hour & value, display with card
3.	Show SO2 units calculation with card
4.	Table: SO2 in AQI by state, highlight high/low
5.	Chart: Max SO2 in each state
6.	Line chart: SO2 in AQI per year
7.	Top city: 1st SO2 pollutant
8.	Sync slicer: Date range for SO2 analysis
9.	Slicer: Interactive state selection
    
**NO2 Pollutants**:
1.	Top 10 states with the highest NO2 pollutants
2.	Find 1st max NO2 hour & value, display with card
3.	Show NO2 units calculation with card
4.	Table: NO2 in AQI by state, highlight high/low
5.	Chart: Max NO2 in each state
6.	Line chart: NO2 in AQI per year
7.	Sync slicer: Date range for NO2 analysis
8.	Slicer: Interactive state selection

## Skills/Concepts demonstrated

The following Power BI features were incorporated:
- DAX,
- Quick measures,
- Page navigation,
- Modelling,
- Filters,
- Tooltips,
- Button,
- Data cleaning replacing all null values with 0,
- Cell elements,
- Slicer

##  Modelling   
![](https://github.com/Ingalesagar/PortfolioProjects/blob/main/US%20Pollution%20Analysis/US%20Pollution%20Modelling.PNG)

## Visualization
The report comprises of five pages:
1. Overview
2. Carbon Monoxide
3. Ozone
4. Sulphur Dioxide
5. Nitrogen Dioxide

Features:
1. Created text boxes to display all 4 category pollutants and give the action-page navigation.
2. Created Slicers to display states, cities,  counties and so on...
3. The years which has been affected by pollution using a slicer
4. Created a filled map to show only US States
5. Generated a table display county names along with codes
6. Created Quarter-wise bifurcation of all 4 pollutants.

## Analysis
**Carbon Monoxide**

Carbon monoxide is a colourless, highly poisonous, odourless, tasteless, flammable gas that is slightly less dense than air.

![](https://github.com/Ingalesagar/PortfolioProjects/blob/main/US%20Pollution%20Analysis/Carbon%20Monoxide.PNG)

1. Max of C02 AQI trended down, resulting in a 66.00% decrease between 2006 and 2010.
2. Max of C02 AQI started trending down on 2006, falling by 66.00% (99) in 4 years.
3. Mexicali is city with highest C02
4. At 588007, California had the highest C02 AQI and was 1,437.43% higher than Colorado, which had the lowest C02 AQI at 38246.
5. California accounted for 49.92% of C02 AQI.
6. Across all 10 State, C02 AQI ranged from 38246 to 588007.



**Ozone**

Ozone is a gas. High in the atmosphere, it protects us from UV radiation. But at ground level, ozone is a pollutant.

![](https://github.com/Ingalesagar/PortfolioProjects/blob/main/US%20Pollution%20Analysis/Ozone.PNG)


1. Max of O3 AQI trended down, resulting in a 2.91% decrease between 2006 and 2010.
2. Max of O3 AQI dropped from 206 to 200 during its steepest decline between 2006 and 2010.
3. Mexicali is city with highest O3.
4. At 6354584, California had the highest O3 AQI and was 2,520.90% higher than Country of Mexico, which had the lowest O3 AQI at 242458.
5. California accounted for 47.03% of O3 AQI.
6. Across all 10 State, O3 AQI ranged from 242458 to 6354584.



**Sulphur Dioxide**

Sulphur dioxide is a gas. Breathing it in can irritate your nose, throat and lungs. Sulphur dioxide is a common air pollutant.

![](https://github.com/Ingalesagar/PortfolioProjects/blob/main/US%20Pollution%20Analysis/Sulphur%20Dioxide.PNG)


1. Max of S02 AQI trended down, resulting in a 48.50% decrease between 2006 and 2010.
2. Max of S02 AQI dropped from 200 to 103 during its steepest decline between 2006 and 2010.
3. Park Hill city has the highest S02.
4. At 446412, Pennsylvania had the highest S02 AQI and was 1,761.91% higher than Country of Mexico, which had the lowest S02 AQI at 23976.
5. Pennsylvania accounted for 31.99% of S02 AQI.
6. Across all 10 State, S02 AQI ranged from 23976 to 446412.



**Nitrogen Oxide**

NO₂ is an intermediate in the industrial synthesis of nitric acid, millions of tons of which are produced each year for use primarily in the production of fertilizers.

![](https://github.com/Ingalesagar/PortfolioProjects/blob/main/US%20Pollution%20Analysis/Nitrogen%20Oxide.PNG)

1. Max of N02 AQI trended down, resulting in a 6.96% decrease between 2006 and 2010.
2. Max of N02 AQI started trending down on 2006, falling by 6.96% (8) in 4 years.
3. Phoenix city with highest N02
4. At 4253496, California had the highest N02 AQI and was 1,838.02% higher than District Of Columbia, which had the lowest N02 AQI at 219476.
5. Across all 10 State, N02 AQI ranged from 219476 to 4253496.


## Conclusion 
1.	Trends in AQI:
 •	There is a consistent trend of decreasing AQI values for CO2, O3, SO2, and NO2 between 2006 and 2010. This suggests potential improvements in air quality 
    during this period.
•	  The steepest decline in AQI values was observed for SO2, with a decrease of 48.50% between 2006 and 2010.

2.	Geographical Disparities:
 •	The city of Mexicali consistently had the highest AQI values for both CO2 and O3, while the city of Phoenix had the highest AQI value for NO2. This indicates 
    localized pollution hotspots.
 •	The states of California and Pennsylvania consistently had the highest AQI values across multiple pollutants. This might suggest higher levels of 
    industrialization or urbanization in these states.
4.	California's Dominance:
 •	California consistently accounted for a significant portion of the total AQI across multiple pollutants (CO2, O3, NO2), ranging from 47.03% to 49.92%. This 
    highlights the state's substantial contribution to air pollution levels in the dataset.
5.	Consistency in Decreases:
•	  Both CO2 and NO2 AQI values started trending down in 2006, and there was a decrease in their maximum AQI values by 66.00% and 6.96% respectively over a span 
    of 4 years. This might indicate the effectiveness of interventions aimed at reducing these pollutants













