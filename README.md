# MLB-Pitching-Database-Development
This project is done by Alayna C. Myrick, Calvin Wu, and Yuanyuan Ge. We created a MySQL database that encompasses all of the MLB pitches from the 2015-2018 season. Data for this database was sourced from two main sources; Kaggle and web scraped data from the Baseball Reference website.

This database was built with the goal of it being used for predictive modeling for pitch types by MLB organizations and sports analytics firms. It can also be used for a variety of other descriptive purposes as well.

The database contains five relational tables: ‘Pitches’, ‘Pitcher_Stats’, ‘Pitcher_Info’, ‘Batter_Info’, and ‘Teams’. Our team decided to include both pitching statistics per season (found in ‘Pitcher_Stats’ table) and personal pitcher information such as birthday and height (found in ‘Pitcher_Info’ table). We also included basic batter information such as the team a player played for during a specific season. The ‘Pitches’ table includes over 2.8 million individually recorded pitches during major league games and includes the game context for each pitch.
