Steam Game Reviews: Player Engagement & Sentiment Analysis
A data analytics capstone exploring how players engage with games, how sentiment forms, and what drives recommendations on Steam.

Overview
This project analyzes a large dataset of Steam game reviews to understand player engagement, review behavior, and sentiment patterns. Using Python, pandas, and visualization libraries, the analysis uncovers how players interact with games, what influences recommendations, and how engagement varies across titles and player segments.
The project follows a structured data lifecycle: Ask → Prepare → Process → Analyze → Share

Project Flow
1. Data Preprocessing
00_data_preprocessing.ipynb
- Loads raw Steam review data
- Cleans and standardizes fields (dates, playtime, recommendation flags)
- Removes duplicates and invalid entries
- Creates engineered features (e.g., playtime categories)
- Outputs steam_games_cleaned.csv for downstream analysis
2. Describe & Engage
01_describe_engage.ipynb
- Explores playtime distributions
- Analyzes recommendation patterns
- Examines session frequency (reviews per user per game)
- Visualizes engagement using boxplots and histograms
3. Comparative Analysis
02_compare.ipynb
- Compares engagement across games
- Evaluates playtime categories (casual, moderate, heavy)
- Identifies high‑engagement vs low‑engagement titles
- Uses bar charts and summary tables
4. Correlation Analysis
03_correlation.ipynb
- Computes correlation matrix for numeric variables
- Visualizes relationships using a heatmap
- Validates earlier findings (e.g., weak correlation between playtime and sentiment)

Key Visualizations
- Playtime vs Recommendation Boxplot
- Session Frequency Histogram
- Top Games Engagement Table
- Recommendation Rate by Playtime Category
- Trend Analysis Line Charts
- Correlation Matrix Heatmap
These visuals support a clear narrative about how players behave and how sentiment forms.

Key Findings
Engagement Patterns
- Most players are casual, but heavy players contribute disproportionately to total playtime.
- Higher playtime slightly increases the likelihood of recommending a game — but the correlation is weak.
Review Behavior
- Nearly all users leave one review per game, confirming that reviews are typically one‑time expressions of sentiment.
- Review volume fluctuates over time, often aligning with seasonal activity or major game events.
Game‑Level Insights
- Some games attract large audiences but show shallow engagement.
- Others have smaller but highly committed communities with strong satisfaction scores.
Sentiment Dynamics
- Recommendation rates remain relatively stable over time, with minor fluctuations that may reflect updates or community sentiment shifts.

Tools & Technologies
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook
- CSV Data Processing
- GitHub for version control
