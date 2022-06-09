We worked on a model that can predict the score of an IPL Team from a point in time. The constraints though being that a minimum of 5 overs need to be taken as the input for prediction of score.

We’ve tried out 2 Models/Methods for the Prediction Model : Random Forest Classifier Lasso Regression

For a smooth experience for User, a Web Application is provided where the user enters the Input Parameters.

The Input Parameters include : Batting Team Bowling Team Venue Overs Bowled (Eg : 6.4) Runs Scored (Eg : 72) Wickets Fallen (Eg : 2) Runs scored in previous 5 Overs (Eg : 52) Wickets taken in previous 5 Overs (Eg : 1)

Here, the Venue at which a match is being played is also important since the Score varies. For Example, in a smaller venue such as M Chinnaswamy (Bengaluru), the score will be quite higher compared to larger venues such as Eden Garderns (Kolkata).

As a result, we get the predicted score after providing the required inputs. The predicted score is generated using Lasso Regression since it was more effective than Random Forest Classifier.