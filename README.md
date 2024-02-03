# mlb-project
### Project for both Machine Learning and Web Mining class Spring 2024

For this project I would like to take a players statline for said game and determine if his play alone affected if the game ended with his team winning or losing. Another interesting thing to look for would be for undervalued and overvalued players in terms of who is the best team player.

Some features that might be of importance is a player's batting average, runs batted in, on base percentage, extra base hits and home runs hit.

Grouping some of these features may be usefule like grouping runs batted with extra base hits because if a batter hits a double and there is a runner on any base they will probably score and obviously if a batter hits a home run then they are guarenteed to score. Another grouping of features that may be interesting is on base base percentage and slugging percentage

I am hoping to find that when looking at all of these factors, knowing their position and team we can predict if the team will win or lose that game. Since we will not be looking at the entire team I can also pull in their fielding stats such as errors and put outs to get a little insight on the other teams chances as well. I would also like to find out what stats affect the outcomes of games the most.

I will scrape espn for batting and fielding stats such as the KC royals at https://www.espn.com/mlb/team/stats/_/name/kc/kansas-city-royals as well as batting splits at https://www.espn.com/mlb/team/splits/_/name/kc
Another place I might find data is an api such as the MLB api