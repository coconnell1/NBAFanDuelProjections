# NBAFanDuelProjections
Using machine learning to predict NBA player fantasy scores for FanDuel.

Included in this repository is the entire notebook that I have worked on, and a PDF version of that notebook. 

The majority of the needed information can be found in the notebook or PDF, but I will highlight some quick points.

Data comes from NBA API - https://github.com/swar/nba_api

This website is used to keep track of FanDuel player prices. Files are downloaded from there daily. - https://www.lineups.com/nba/nba-fantasy-basketball-projections

A sheet containing projections for the current day will be exported (path needs to be changed to fit your machine). The current day's optimal FanDuel lineup will be generated from the predictions made from the model. 

This project initially started using linear regression with multiple variables, which is what the report mostly covers. Since then, I have made further adjustments to the model to improve accuracy with random forest, which is updated within the notebok. I am still working to improve the model, so changes will continue to come. 

Feel free to email any questions to cobijoconnell@gmail.com. Thanks!
