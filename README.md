# B211-Assignment_4

Purpose of Program:
Analyzing longevity and shooting evolution of the NBA player with the most regular season appearances
- Calculating 3-point average for each season they played
- Perform linear regression
- Calculating 3-point average accuracy
- Using interpolation to estimate missing values

Class Design & Implementation:
- NBADataAnalyzer: Handle data loading and filtering
- PlayerStats Class: Performs player-specific calculations
- StatisticalModeling Class: Calculates variance, skew, etc.

Limitations:
- This player didn't participate in the 2002-2003 and 2015-2016 season
- By using interpolation to estimate the missing values for the two seasons the player didn't participate in, it may not even reflect their actual performance
