# California Road Trip Planner

This project aims to help users plan a road trip through California by providing information on optimal routes, nearby attractions, places to eat, and more. It was a collaborative effort between two software engineers and two data scientists. (I was one of the data scientists; the first notebook is mostly my work, whereas the second notebook is mostly the other data scientist's work.)

***NOTE***: The reason why we did this project is because we were participants in a competition arranged by TripleTen titled "June 2024 Code Jam". 

More information about it can be found here: 
https://coding-bootcamps.notion.site/June-Code-Jam-June-2024-e8babfd291064a6fa455bfc491f08fdd 

Furthermore, the full live stream of all the presentations can be found here: https://www.youtube.com/live/BqdfDUsV7z8

## Link to Simulator
https://matthew-wright9630.github.io/RoadTrip2/

## Features

- **Interactive Map**: Select and view various destinations within California.
- **Route Optimization**: Calculate the shortest route through the cities selected by the user.
- **Points of Interest**: Discover popular attractions, including national parks and theme parks.

## Data Commentary

The team collected data on the latitude and longitude of most cities in California, as well as the prevalence of violent crime in each city and the address(es) of any Chipotle stores in each city. Lastly, the team also found the latitude and longitude coordinates of ten popular attractions in the state.

The most important data are the coordinates, as those are used by the simulator to minimize distance. The purpose of the violent crime data is to help the users of the simulator know which cities are the safest to stay overnight at, and the Chipotle data gives users a starting point regarding where they can get food.

## How the Simulator Works

In a nutshell, the simulator does the following:

- Approximates the shortest distance one would need to travel in order to reach every city on their road trip itinerary, and the approximate amount of time this would take.
- Compares the shortest route to a randomly selected alternative route, one that serves as the baseline to compare the optimal route to.
- Determines which city in a user's itinerary is closest to one of the ten popular attractions selected by the team, and the approximate distance between the locations.

## Ideas for Improving the Simulator

In no particular order, the following is a list of ideas on how to make the simulator an even more useful tool for anyone interested in going on a road trip in California:

- The simulator assumes that a user will go on a 10-minute break after every 2 hours of driving. It would be nice if the simulator allowed users to choose how often they will go on a break, and for how long.
- In addition to showing users the optimal route and nearby attractions, the team would like for the simulator to display data about each city on the itinerary such as places to eat, crime statistics, and the cost of overnight accommodation. These data can only help a user make informed decisions about where to go.
