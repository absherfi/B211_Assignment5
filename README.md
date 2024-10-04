# B211_Assignment5

This project analyzes NBA player stats to identify trends in three-point shooting accuracy and field goals. It focuses on the player with the most regular seasons played, calculates their three-point accuracy, and uses linear regression to predict accuracy trends. Missing seasons are estimated using interpolation. Additionally, statistical analysis is performed on Field Goals Made (FGM) and Field Goals Attempted (FGA), including mean, variance, skew, and kurtosis. T-tests are conducted to compare FGM and FGA, as well as individual t-tests for each column.

Two classes are used:

NBAPlayerStats: Handles player-specific data, accuracy calculations, and regression.
FieldGoalStats: Manages FGM and FGA statistics and t-tests.

Limitations include assumptions of clean data, linear trends in accuracy, and normal distribution for the t-tests.
