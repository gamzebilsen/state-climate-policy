# State Climate/Renewable Energy Policy Analysis
The project compares renewable energy policy impacts by comparing 3 states' changes in renewable energy generation across time using difference in differences. The chosen states compared are Nebraska (no policy) vs Kansas (Renewable Energy Standard that directs utilities in a voluntary fashion) and Nebraska (no policy) vs Missouri (Renewable Energy Standard that directs utilities in a mandatory fashion) because of their similar climate, political standing based on the 2020 US general elections and populations.

## Data 
1. Monthly energy generation data is from EIA 
2. Monthly temperature data is from NOAA

## Installation
You can download the data in csv form. Pynotebook was used to scrape NOAA to get average monthly temperature data for all three states. 

## Usage
This data can be used to understand the impact of renewable energy related policy on energy generation in a given state. The data is from 5 states, so it can be used on states beyond the ones previously mentioned. 

The code can also be used for any state by extracting same data for different states from EIA. 

Overall, we see that Renewable Energy Plans do lead to a positive difference for states with plans (mandatory or voluntary) compared to those who do not, albeit a small impact. It was however interesting to see Nebraska who has no plans having a higher accelaration in renewable energy generation compared to Missouri who has the mandatory goal. Missouri in the end is the state who throughout the time produced the least energy from renewables, and overall had the slowest increase in the integration, highlighting the possible impact of other factors that aren't included in this project such as economic or natural resources available to agents in each state. 

## Roadmap
This project can be replicated for different states. Different time frames for the difference-in-differences can be used compared to the one chosen for this project. Additional variables can be controlled for such as data that represents economic wellbeing or statewide natural resources beyond temperature. 
