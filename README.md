# Player-Performance-Analysis
This project explores the factors influencing football players' performance by analyzing statistical and match-related data. It aims to build a comprehensive dataset and conduct detailed analyses to uncover insights into what drives players to excel in matches.

### Project Objectives
- **Data Integration:** Combine datasets related to player statistics, match information, and external factors to create a rich, unified dataset.
- **Performance Prediction:** Identify key variables and patterns to predict player performance, by prediticting the percetage of scoring.

### Overview
- **Data Sources:** The dataset used in this project includes detailed player statistics, match information, and external factors. Key features are combined with match-related variables. All data is stored in the **`data`** folder, organized for easy access and analysis.
- **Code:** The analysis and prediction process is executed in a Jupyter Notebook file **`code.ipynb`**. The code covers data preprocessing, feature selection, and model building. The machine learning model is built using Random Forest Regressor, a robust algorithm that is ideal for regression tasks like goal prediction. The notebook also includes data visualizations to provide insights into the relationships between different features and player performance.
  #### The key steps in the notebook include:
1. **Data Preprocessing:** Cleaning and transforming raw data into a format suitable for model training.
2. **Visualization:** Visualizing trends and distributions to gain a better understanding of player performance and key metrics.
3. **Model Training:** Using the Random Forest algorithm to predict the number of goals scored by players.
4. **Evaluation:** Assessing model performance using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared score.

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
