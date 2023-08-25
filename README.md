# CBB-Prediction-Model

Project Description: College Basketball Outcome Prediction System**

**Introduction:**
The College Basketball Outcome Prediction System is a powerful tool developed to predict the results of college basketball games using a combination of historical team performance data and sophisticated simulation techniques. By incorporating offensive and defensive statistics of college basketball teams, conducting simulations, and enabling customizable team selections, this system provides accurate predictions and insights for a range of users including enthusiasts, bettors, coaches, and teams.

**Objective:**
The primary objective of this project is to create a dynamic prediction system that accurately forecasts college basketball game outcomes while accommodating individual team preferences through a user-friendly dropdown menu interface.

**Methodology:**
1. **Data Collection and Preparation:**
   - Data is gathered from Excel spreadsheets specific to each college basketball team, containing offensive points per game and defensive points allowed information.
   - Recent game statistics are utilized to calculate the standard deviation for each team's offensive and defensive performances.

2. **Team Selection and Customization:**
   - The system features a user-friendly dropdown menu with the names of all college basketball teams.
   - Users can easily select the teams they wish to analyze and predict outcomes for.

3. **Ranking and Projection:**
   - The selected team names are used to access their corresponding Excel spreadsheets, extracting offensive and defensive data.
   - Average team rankings are calculated by combining offensive and defensive metrics, providing a balanced assessment of team performance.
   - A projection formula utilizes the average rankings to estimate each team's performance in the upcoming game.

4. **Simulations and Outcome Predictions:**
   - Simulations are executed to generate probable game scores for both home and away teams, employing a normal distribution approach.
   - The simulated scores are compared to determine the game winner and type of outcome (home win, away win, or overtime).
   - Point spreads are calculated by adding the team-specific spread value to the simulated score for each team.
   - Over/under totals are determined by summing up the simulated scores and comparing them to predetermined thresholds.

5. **Data Analysis and Insights:**
   - The system compiles a comprehensive table of simulated game outcomes, encompassing winner designations, point spreads, and over/under results.
   - Metrics such as the number of wins, win percentages, and average scores are computed to offer deeper insights into team performance.

**Benefits:**
1. **Personalized Analysis:** The dropdown menu allows users to easily customize team selections, tailoring predictions to specific interests.

2. **Accurate Predictions:** Utilizing recent team statistics and simulation techniques, the system delivers highly accurate predictions for college basketball game outcomes.

3. **Effortless Data Retrieval:** The system automatically retrieves team data from dedicated Excel spreadsheets, streamlining the prediction process.

4. **Informed Decision-Making:** Enthusiasts, bettors, coaches, and teams can make well-informed decisions by utilizing the system's data-driven predictions and detailed analyses.

**Conclusion:**
The College Basketball Outcome Prediction System is a dynamic and accessible tool that combines historical team performance data, simulations, and user-friendly features to accurately forecast college basketball game outcomes. By catering to individual team preferences and providing valuable insights, the system empowers a wide range of users to make informed decisions and gain a comprehensive understanding of the competitive landscape in college basketball.
