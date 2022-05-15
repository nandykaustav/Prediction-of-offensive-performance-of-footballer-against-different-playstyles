# Prediction-of-offensive-performance-of-footballer-against-different-playstyles
This project aims to build a prediction model for a particular footballer to assess his attacking performance against different playstyles of different teams. All the data was taken from Understat using the API https://understat.readthedocs.io/en/latest/classes/understat.html created by Amos Bastian.

The player I have used is Mohamed Salah. For this, following broad steps were involved:

  1. Accessing the player's past matches against different teams in the last few seasons in the current team (the number of seasons to be considered can be varied).
  2. Compiling a the overall data of those teams in the league in those particular seasons against all opponents and also the concerned player's performance against these teams in      these matches. This served as the training data.
  3. Compiling the overall data data of all teams in the current season till this point. This served as the prediction data.
  4. Making the predictions on the prediction data based on the training data.

This project is still being improved by re-adjusting/adding new features of data and constantly tuning the model.
