# Twitter Entity Sentiment Analysis

This project analyzes and visualizes sentiment patterns in social media data to understand public opinion and attributes towards specific topics using the `twitter-entity-sentiment-analysis` dataset.

### dataset :  
This dataset is useful for analyzing public sentiment toward specific entities, identifying trends, and understanding how public opinion shifts over time or in response to events. It's suitable for tasks like training sentiment analysis models, conducting exploratory data analysis (EDA), and creating visualizations to understand sentiment patterns.

source: [kaggel.com](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

## Analysis process

This project involved the following steps:


1. **Installation and Setup**:
   - Installed the Kaggle API client and configured the necessary credentials.

2. **Dataset Download**:
   - Downloaded the `twitter-entity-sentiment-analysis` dataset from Kaggle using the Kaggle API.

3. **Data Extraction**:
   - Extracted the contents of the downloaded ZIP file into the working directory.

4. **Data Loading**:
   - Loaded the training and validation datasets into Pandas DataFrames.

5. **Column Renaming and Data Merging**:
   - Renamed columns for clarity and merged the training and validation datasets into a single DataFrame.

6. **Data Cleaning**:
   - Removed rows with missing values and dropped duplicate entries to ensure data quality.

7. **Sentiment Distribution Visualization**:
   - Visualized the distribution of sentiment labels in both the training and validation datasets using count plots.

8. **Tweet Length Analysis**:
   - Calculated the length of each tweet and added it as a new feature in the dataset.

9. **Tweet Length Distribution Visualization**:
   - Visualized the distribution of tweet lengths using histograms and KDE curves to understand their spread.

10. **Correlation Analysis and Visualization**:
    - Analyzed the correlation between tweet length and sentiment, and visualized the relationship using box plots.
