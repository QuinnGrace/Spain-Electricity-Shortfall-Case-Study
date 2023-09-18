# Spain Electricity Shortfall Case Study: Predicting Daily Shortfall With Machine Learning (AI)

NOTE: Due to the nature of this project, code cannot be shared publicly.

## Context 
The Spanish Government is considering further investments in renewable energy. To do so, they need information about Spain's current renewable and non-renewable energy generation trends and patterns. Specifically, they want to be able to predict the load shortfall on any given day given certain conditions (wind speed, pressure, humidity etc.). Load shortfall is the difference between renewable and non-renewable energy generation. 

## Expected Outcomes
- Identify energy generation trends and patterns
- Create a regression model that predicts load shortfall
- Present findings

## Tools Used
- Python
  - SKLearn
  - Pandas
  - NumPy
- Flask
- AWS EC2

## Output
An ensemble model that had an RMSE of 3582 - We placed 6th out of 38 teams. This means we could accurately predict the load shortfall.

![image](https://github.com/QuinnGrace/Spain-Electricity-Shortfall-Case-Study/assets/73368635/94ef0a21-1d4e-41f0-ab67-e8372eb6a68e)

The histogram shows a mostly positive load shortfall, meaning renewable energy generation is often greater than non-renewable energy generation.

![image](https://github.com/QuinnGrace/Spain-Electricity-Shortfall-Case-Study/assets/73368635/34c34bf9-c0c8-4c3c-982f-e3ddec8db988)

This line graph shows that weekends had a lower load shortfall, possibly due to lower power consumption.

![image](https://github.com/QuinnGrace/Spain-Electricity-Shortfall-Case-Study/assets/73368635/464b656d-4b1b-4d95-bba5-90199a9fb108)

This line graph shows that summer months have a higher load shortfall, possibly due to higher solar generation.

## Recommendations
- Further investigations should be done into why weekends have a lower load shortfall.
  - If it is due to lower power consumption, then the Spanish government should prioritise power generation on weekdays (when demand is higher).
  - Otherwise, weekend power generation should be prioritsed to increase the amount of renewable energy
- Due to the high amount of renewable electricity produced in summer, other seasons should be prioritised. This could mean using types of power that produce more in other seasons, such as wind energy.

## Acknowledgements
I would like to thank my team members for their contributions:
- Timmy Egbe
- Gideon Odekina
- Esther Akinniyi
- Tolulope Adeleke
- Andi Jafta
- Musa Aliu
