# Netflix Analysis

## Overview

This project involves analyzing a Netflix dataset to gain insights into the content available on the platform. The analysis includes data cleaning, processing, and visualization using various charts to understand the distribution and characteristics of movies and TV shows.

## Libraries Used

- `pandas` - For data manipulation and analysis.
- `numpy` - For numerical operations.
- `sklearn.preprocessing.LabelEncoder` - For encoding categorical data.
- `matplotlib.pyplot` - For creating static, animated, and interactive visualizations.
- `seaborn` - For statistical data visualization.

## Project Structure

1. **Importing Necessary Libraries**  
   Libraries such as `pandas`, `numpy`, `LabelEncoder`, `matplotlib`, and `seaborn` are imported to handle data manipulation and visualization.

2. **Read the CSV File as DataFrame**  
   The dataset is loaded into a DataFrame for analysis.

3. **Sampling Data from a DataFrame**  
   A subset of the data is sampled for initial exploration and testing.

## Data Cleaning and Processing

1. **Dealing with Missing Data**  
   Missing values are handled through imputation or removal based on the extent and nature of the missing data.

2. **Date Conversion and Feature Extraction**  
   Dates are converted to a consistent format, and relevant features are extracted for analysis.

3. **Feature Engineering and Data Cleaning**  
   Key attributes are extracted, and data is normalized to prepare for visualization.

4. **Save the Cleaned DataFrame as CSV File**  
   The cleaned DataFrame is saved as a new CSV file for future use.

## Data Visualization

Visualizations are created using Netflix brand colors:

- **Pie Chart**  
  Displays the ratio of Movies to TV Shows.

- **Histogram**  
  Shows the distribution of movie durations with a vertical line indicating the mean duration.

- **Box Plot**  
  Visualizes the spread of durations for Movies and TV Shows.

- **Count Plot**  
  Illustrates the number of titles by genre.

## Dashboard

A Power BI dashboard was created to visualize the insights from this analysis. You can view it [here](https://app.powerbi.com/links/ohLC6mZp4s?ctid=eaf624c8-a0c4-4195-87d2-443e5d7516cd&pbi_source=linkShare&bookmarkGuid=4586f22d-6f05-4be4-b266-45744cf24f91).

Additionally, two dashboard themes have been created:

- **Dark Mode Dashboard**  
  ![Dark Mode](C:\Users\Abdo\Desktop\Projects\Netflix_Analysis_Project\Dark_mood.png)

- **Light Mode Dashboard**  
  ![Light Mode](C:\Users\Abdo\Desktop\Projects\Netflix_Analysis_Project\Light_Mood.png)

## Conclusion

This analysis of the Netflix dataset provided insights into various aspects of the content available on the platform:

- **Ratio of Movies to TV Shows**  
  Visualized using a pie chart to show the proportion of movies versus TV shows.

- **Distribution of Movie Duration**  
  A histogram depicted the range of movie lengths, with a vertical line indicating the mean duration.

- **Additional Insights**  
  - Comparison of movie and TV show durations using a box plot.
  - Number of titles by genre.

These visualizations reveal key trends and distributions in Netflix's content library. Future analyses could explore content popularity trends, viewer ratings, and personalized recommendations for even deeper insights.


