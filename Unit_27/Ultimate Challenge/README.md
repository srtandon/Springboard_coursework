# Ultimate Data Science Challenge

## Part 1

An excercise in emploratory data analysis. The goal was to visualize and describe tim series data of login counts inorder to divulge any patters of demand.

The notebook can be found [here](https://github.com/srtandon/Springboard_coursework/blob/master/Unit_27/Ultimate%20Challenge/Ultimate%20Challenge%20--%20Part%201.ipynb).


## Part 2

This is an excercise in experimental design. The notebook can be found [here](https://github.com/srtandon/Springboard_coursework/blob/master/Unit_27/Ultimate%20Challenge/Ultimate%20Challenge%20--%20Part2.ipynb).

## Part 3

This is an excercise in all things data science. [notebook](https://github.com/srtandon/Springboard_coursework/blob/master/Unit_27/Ultimate%20Challenge/Ultimate%20Challenge%20--%20Part%203.ipynb)

Ultimate is interested in predicting rider retention. To help explore this question, we have provided a sample dataset of a cohort of users who signed up for an Ultimate account in January 2014. The data was pulled several months later; we consider a user retained if they were “active” (i.e. took a trip) in the preceding 30 days.
We would like you to use this data set to help understand what factors are the best predictors for retention, and offer suggestions to operationalize those insights to help Ultimate.

The data is in the attached file ultimate_data_challenge.json. See below for a detailed description of the dataset. Please include any code you wrote for the analysis and delete the dataset when you have finished with the challenge.

  1. Perform any cleaning, exploratory analysis, and/or visualizations to use the provided data for this analysis (a few sentences/plots describing your approach will suffice). What fraction of the observed users were retained?
  2. Build a predictive model to help Ultimate determine whether or not a user will be active in their 6th month on the system. Discuss why you chose your approach, what alternatives you considered, and any concerns you have. How valid is your model? Include any key indicators of model performance.
  3. Briefly discuss how Ultimate might leverage the insights gained from the model to improve its long-term rider retention (again, a few sentences will suffice).

#### Data description

- **city**: city this user signed up in
- **phone**: primary device for this user
- **signup_date**: date of account registration; in the form ‘YYYY MM DD’
- **last_trip_date**: the last time this user completed a trip; in the form ‘YYYY MM DD’
- **avg_dist**: the average distance in miles per trip taken in the first 30 days after signup
- **avg_rating_by_driver**: the rider’s average rating over all of their trips
- **avg_rating_of_driver**: the rider’s average rating of their drivers over all of their trips
- **surge_pct**: the percent of trips taken with surge multiplier > 1
- **avg_surge**: the average surge multiplier over all of this user’s trips
- **trips_in_first_30_days**: the number of trips this user took in the first 30 days after signing up
- **ultimate_black_user**: TRUE if the user took an Ultimate Black in their first 30 days; FALSE otherwise
- **weekday_pct**: the percent of the user’s trips occurring during a weekday
