# Player-Performance-Analysis
This project explores the factors influencing football players' performance by analyzing statistical and match-related data. It aims to build a comprehensive dataset and conduct detailed analyses to uncover insights into what drives players to excel in matches.

### Project Objectives
- **Data Integration:** Combine datasets related to player statistics, match information, and external factors to create a rich, unified dataset.
- **Performance Prediction:** Identify key variables and patterns to predict player performance, by prediticting the percetage of scoring.

### Overview
- **Data Sources:** Datasets on players, matches, and external conditions stored in the **data** folder.
- **Analysis:** An R Markdown file in the analysis/ folder for statistical modeling and visualization.
- **Reports:** Generated reports in HTML and PDF formats in the output/ folder.

The insights from this analysis can help coaches, analysts, and fans understand the dynamics of player performance in international football, providing a data-driven perspective on the sport.

### Contributers
- [Celine Al Harake](https://github.com/CelineHarakee)
- [Layal Canoe](https://github.com/layalcanoe)

---
##  Variables Codebook 
- **player_id:** An integer that uniquely identifies each player in the dataset.
- **player_name:** The full name of the player.
- **player_age:** The player’s age, recorded as an integer.
- **nationality:** The country or origin of the player.
- **date_of_birth:** The date on which the player was born.
- **height_in_cm:** The player’s height, measured in centimeters.
- **position:** The role or position the player holds on the field, e.g., forward, midfielder, defender, or goalkeeper.
- **club_id:** A unique identifier for the player’s club.
- **game_id:** A unique identifier for the match the player participated in.
- **competition_id:** A unique identifier for the competition or tournament in which the match occurred.
- **season:** The football season during which the match was played, represented in a YYYY format.
- **match_date:** The date the match took place.
- **home_club_id:** A unique identifier for the home team of the match.
- **away_club_id:** A unique identifier for the away team of the match.
- **home_club_goals:** The total number of goals scored by the home team in the match.
- **away_club_goals:** The total number of goals scored by the away team in the match.
- **match_outcome:** The outcome of the match for the player’s team, categorized as Win, Loss, or Draw.
- **home_club_name:** The full name of the home team.
- **away_club_name:** The full name of the away team.
- **yellow_card:** The number of yellow cards the player received during the match.
- **red_cards:** The number of red cards the player received during the match.
- **goals:** The total number of goals scored by the player during the match.
- **assists:** The total number of assists made by the player during the match.
- **minutes_played:** The total number of minutes the player was on the field during the match.
- **club_name:** The name of the club the player represents.
- **competition_name:** The name of the competition or league where the match took place.
