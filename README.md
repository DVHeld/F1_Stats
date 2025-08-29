# Formula 1 Stats

This is a little side-project I made in order to exercise and showcase what I can do using Power BI.

It uses this data from Kaggle: https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020

There's a simple menu from which to navigate into the main reports:
![Menu](https://github.com/DVHeld/F1_Stats/blob/main/img/Menu00.png?raw=true)

The Constructors - Drivers report provides information on a constructor's drivers. The information can be filtered by year. There's a table that contains each driver's result data for each race. There's also a graph that shows points earned by each driver over time.
![Constructors - Drivers report](https://github.com/DVHeld/F1_Stats/blob/main/img/ConstructorsDrivers00.png?raw=true)

![Constructors - Drivers report](https://github.com/DVHeld/F1_Stats/blob/main/img/ConstructorsDrivers01.png?raw=true)

The Constructors - Season Points report provides information on the points gained by a constructor in a given season. The upper graph compares the selected constructor's cumulative points to the ones of the rest of constructors. The lower graph shows cumulative and race points for the selected season and constructor.
![Constructors - Season Points report](https://github.com/DVHeld/F1_Stats/blob/main/img/ConstructorsSeasonPoints00.png?raw=true)

In the Races report, selecting a race in the left pane brings up that race's general information. The table shows the final lineup. The date and circuit name are shown at the right side. Hovering over the "Free Practice", "Sprint" and "Qualifications" labels brings up a tooltip showing more information on the corresponding race's detail.
![Races report](https://github.com/DVHeld/F1_Stats/blob/main/img/Races00.png?raw=true)

![Races report](https://github.com/DVHeld/F1_Stats/blob/main/img/Races01.png?raw=true)

![Races report](https://github.com/DVHeld/F1_Stats/blob/main/img/Races02.png?raw=true)

The Seasons positions report contains a snake graph showing the evolution of each driver's final place on each race of the selected season.
![Seasons positions report](https://github.com/DVHeld/F1_Stats/blob/main/img/SeasonPositions00.png?raw=true)

The Circuits report provides various information on the selected circuit. 
![Circuits report](https://github.com/DVHeld/F1_Stats/blob/main/img/Circuits00.png?raw=true)

The Drivers - Races report presents various information about a driver's races. Selecting a driver in the left panel brings up that driver's information. The main table lists all the driver's races, including the race's date, the driver's finishing position, status, constructor, race name and circuit name. The chart below the table shows the driver's finishing position over time for each race. The report can be filtered by circuit, constructor or race name. Selecting a race in the table or chart enables the "See race" button, ctrl+clicking it takes the user to the Drivers - Race Details report for the selected race.
![Drivers - Races report](https://github.com/DVHeld/F1_Stats/blob/main/img/DriversRaces00.png?raw=true)

The Drivers - Race Details report is accessible by selecting a race in the Drivers - Races report and ctrl+clicking the "See race" button. This report shows details of the driver's performance throughout the race. The left-side table shows a list of the times and position at the end of each lap. The upper section contains information on the race's results, the middle section contains general information about the driver for that race and the bottom section shows general information about the race.
![Drivers - Race Details report](https://github.com/DVHeld/F1_Stats/blob/main/img/DriversRaceDetails00.png?raw=true)