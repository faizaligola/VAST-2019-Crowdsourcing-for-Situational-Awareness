# VAST-2019-Crowdsourcing-for-Situational-Awareness
This project entails a thorough analysis of seismic events in the fictional city of St. Himark during April, utilizing a government-released application to assess earthquake intensities across various areas, with data cleaning and visualization executed through Tableau and Python, culminating in crucial insights and conclusions.

VAST 2019's Mini Challenge 1 focuses on a disaster in St. Himark post-earthquake. Authorities investigate damage and required resources, aided by a pre-earthquake reporting app facilitating government engagement and emergency response prioritization.

Our analysis aims to determine:
1. How would you prioritize neighborhoods for response? Which parts of the city are hardest hit? 
2. Compare the reliability of neighborhood reports. Which neighborhoods are providing reliable reports? 

We'll utilize the mc1-reports-data.csv file, encompassing individual reports of shaking/damage categorized by neighborhood and time. Citizens can submit reports in 5-minute increments due to server design, possibly delayed during blackouts.

The dataset includes:
Timestamps (formatted as YYYY-MM-DD hh:mm:ss)
Neighborhood locations experiencing trembling or damage
Categorical values {shake_intensity, sewer_and_water, power, roads_and_bridges, medical, buildings} representing shaking intensity and damage severity (from 0 to 10; missing data accepted).

With St. Himark's map and provided shake maps, we'll visualize data using Tableau, exploring trends and answering key questions.
## Map of St. Himark
![1](https://github.com/faizaligola/VAST-2019-Crowdsourcing-for-Situational-Awareness/assets/80847944/2bb6c15c-a199-4f86-a0c4-d263431fd267)
## Pre Quake Shake Map
![2](https://github.com/faizaligola/VAST-2019-Crowdsourcing-for-Situational-Awareness/assets/80847944/1ec58016-8289-4983-9d0f-efeeee706945)
## Major Quake Shake Map
![3](https://github.com/faizaligola/VAST-2019-Crowdsourcing-for-Situational-Awareness/assets/80847944/65c73a62-5e18-4e18-ae87-6c7839e232c7)
## Visualization Dashboard
![4](https://github.com/faizaligola/VAST-2019-Crowdsourcing-for-Situational-Awareness/assets/80847944/a3ba9247-88c6-469b-a8c9-e39889ea3165)

## Result
In summary, using Tableau, we visualized data for VAST 2019 - Mini Challenge 1 questions on situational awareness. We identified Location 3 (Old Town) as the most affected area, differing from public perceptions. While Location 8 (Scenic Vista) had numerous reports, the earthquake intensity was lower, highlighting perception-based data anomalies. Comparing reliability, Locations 8 and 9 had misaligned reports, while Location 3 displayed consistency between public perception and actual shake intensity.
