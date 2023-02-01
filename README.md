Overview/Purpose:

This script (city matching) reflects the preliminary step in our evaluation of rent control policy. It will use data sourced from the U.S. Census Bureau (Metropolitan and Micropolitan Statistical Area Population by Characteristics: 2020-2021: https://www.census.gov/data/tables/time-series/demo/popest/2020s-metro-and-micro-statistical-areas-detail.html)to match cities based on population and demographic composition.

The goal of this data cleaning will be to select a city located in a state with rent control measures and match it with a city located in a state without rent control measures. This construction of a counterfactual will allow us to more meaningfully analyze the relationship between rent control policy and select variables.

After cleaning the data, we took the absolute value of differences across total, male, and female population, and median age. We summed these differences and used them to identify each city’s closest counterpart. The issue with this approach is that cities included within the dataset had total populations ranging from 12,000 to over 19.7mm. 
![image](https://user-images.githubusercontent.com/119253324/215937175-416630b8-4705-412b-b7c6-6f6f63bfbd8e.png)


Smaller cities may yield smaller numerical differences due to their relative size and could therefore be falsely identified as closest matches. We also needed to ensure that we were only looking for matches between states with and without rent control measures.

We decided to narrow our parameters by selected the states we wished to compare, and later restricted our analysis to the top 10% of cities in terms of size within those states.

Our group decided to isolate Texas as the state we wished to analyze with regard to its lack of rent control measures. Texas preempts both mandatory inclusionary zonings and rent control.

California was selected as the state within which we wished to locate a counterfactual. This is because California is the only state that has statewide rent control caps in addition to city specific laws.

The cities that were paired were the Austin-Round Rock-Georgetown MSA in TX and the Sacramento-Roseville-Folsom MSA in California. Visualizations of their level of similarity are below: 

![image](https://user-images.githubusercontent.com/119253324/215937551-e1eb091b-3039-407f-8898-34b699f6e522.png)


![image](https://user-images.githubusercontent.com/119253324/215937706-af9bac2d-38be-4b17-a06f-1b4d0f83f402.png)

![image](https://user-images.githubusercontent.com/119253324/215937729-d4a5e15d-b95e-468c-8008-4ac37820dedd.png)



The cities that were paired were the Austin-Round Rock-Georgetown MSA in TX and the Sacramento-Roseville-Folsom MSA in California. Visualizations of their level of similarity are below: 
