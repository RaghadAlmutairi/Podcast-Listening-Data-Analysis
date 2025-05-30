# Podcast Listening Data Analysis Project

## Overview
This project analyzes podcast listening data to uncover user behavior patterns and provide personalized episode recommendations. The analysis is implemented in a Jupyter Notebook (`Podcast_Analysis_Structure.ipynb`) using Python with libraries such as Pandas, Matplotlib, and Seaborn.

## Project Structure
The notebook is divided into the following key sections:

1. **Data Loading and Preprocessing**:
   - Loads data from `users.csv` (user demographics), `episodes.csv` (episode details), and `listens.json` (listening records).
   - Performs basic data cleaning to ensure data integrity (e.g., removing missing values).

2. **Exploratory Data Analysis**:
   - Analyzes listening duration by age group using categorized bins (<18, 18-25, 26-35, 36-50, 51-65, 65+).
   - Visualizes results with a bar plot to identify trends in user engagement.

3. **Recommendation System**:
   - Implements a function (`recommend_episodes`) to suggest up to three new episodes based on a user's most frequently listened category.
   - Handles cases where no new episodes are available by falling back to the second most popular category.

4. **Final Report**:
   - Summarizes findings, including age group listening patterns and recommendation system performance.
   - Provides actionable recommendations to enhance user experience, such as tailoring content for specific age groups and improving the recommendation algorithm.

## Key Findings
- Middle-aged users (26-50) exhibit longer listening durations, indicating higher engagement.
- The recommendation system successfully suggests relevant episodes based on user preferences, with Sports being a popular category (e.g., recommendations for user ID 1).
- Opportunities exist to enhance content variety and refine recommendations using advanced techniques.

## How to Use
1. Ensure the required data files (`users.csv`, `episodes.csv`, `listens.json`) are in the `assignment/` directory.
2. Install dependencies: `pandas`, `matplotlib`, `seaborn`.
3. Run the Jupyter Notebook (`Podcast_Analysis_Structure.ipynb`) to execute the analysis and view results.

## Future Improvements
- Incorporate advanced machine learning for more precise recommendations.
- Expand analysis to include additional factors like country or gender.
- Collect user feedback to refine content and recommendations.

## Requirements
- Python 3.10
- Libraries: `pandas`, `matplotlib`, `seaborn`

## License
This project is for educational purposes and does not include a specific license.