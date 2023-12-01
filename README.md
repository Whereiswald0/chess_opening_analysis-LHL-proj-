# Midterm_LHL_project - Online Chess Games analysis

## Project/Goals
##### Chess has been greatly influenced by the increase both in the power of computing and its widespread availabilty. The impact of machine learning in the 21st century on the way chess is played at the highest levels cannot be understated. 

##### At the same time, for most players learning long and complicated move-orders developed by dedicated chess engines is less important for their improvement than examining which openings are most popular at their skill level and learning how to tackle those. 

##### Rather than offering opening suggestions that perform well against a machine, our project will examine the most commonly played openings at various skill levels and using statistical modeling suggest which openings have a higher chance of winning against players of a particular skill level.

##### Analysis of the distribution of rated players across the world will also be included in order to provide a picture of what skill level might be faced when playing over the board.

## Process
##### 1. Locate and clean appropriate datasets (see note.txt in the datasets and analysis folders)
##### 2. Examine and develope statiscial models to provide insights.
##### 3. Produce clean and elegant Tableau dashboards to enable easy access to the relevant data to end users.

## Results - [Tableau Dashboard](https://public.tableau.com/app/profile/adrian1635/viz/Chess_17013176907810/Sheet11?publish=yes)
##### Due to the complexity of chess as a game, neither Logical Regression nor Generalized Linear Models were able to be used to find correlations between move order and win conditions at this level. 
##### Instead, Tableau's visualisations and filtering were used to describe the datasets and produce recommendations.
##### A lack of correlation in this data is a result in and of itself (we were never going to 'solve' chess)

## Challenges 
##### The amount of data available on chess games is vast (60-70GB of data are produced by lichess just from game results, without analysis)
##### Knowing how to limit this while obtaining enough data the something can be meaningfully said is key.

## Future Goals
##### Add additional datasets, produce slices of datasets by rating to be processed using statistical models (an attempt to keep the dataset smaller but focused, so that models can be built more easily and accurately)
##### Structure API calls that will pull live data for those particular slices
##### Apply machine learning models to produce better results.
