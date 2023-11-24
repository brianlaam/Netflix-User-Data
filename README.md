# Netflix User Data Analysis

This project performs exploratory data analysis on the Netflix user dataset to understand usage patterns.

## Data

The dataset contains information on 5000 Netflix subscribers including:

- User ID
- Subscription type 
- Monthly fee
- Join date
- Country
- Age
- Gender
- Device used
- Plan duration

## Analysis

The Jupyter notebook `netflix_analysis.ipynb` contains the following visualizations and insights:

### Distribution of Subscription Types

- Bar chart showing the number of users per subscription type. Basic has the most subscribers.

### Device Usage

- Pivot table and heatmap of mean user age by device type and country.

### Correlations

- Heatmap of correlation matrix between different attributes like age, revenue etc. Indicates relationships between variables.

## Requirements

The analysis uses Python 3 along with the following libraries:

- Pandas
- Matplotlib
- Seaborn

The notebook can be run online in Google Colab.

## Usage

To replicate the analysis:

1. Clone this repository 
2. Upload the data CSV file
3. Open the Jupyter notebook
4. Run all cells to generate the visualizations

Feel free to use and adapt the code for your own datasets!
