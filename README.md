## League of Legends Champions Dataset Analysis

### Overview
This repository contains a dataset and analysis related to champions from the game League of Legends. The dataset includes various statistics about each champion, including their base health, mana, armor, attack damage, and gold efficiency. The goal is to explore these features and gain insights into the characteristics of champions based on their roles.

### Dataset
The dataset is a CSV file named `champions.csv` and contains the following columns:

- Champion Name: Name of the champion (string).
- Role: Role of the champion (Top, Mid, Jungle, Support) (string).
- Base Health: Base health stat of the champion (integer).
- Base Mana: Base mana stat of the champion (integer).
- Base Armor: Base armor stat of the champion (integer).
- Base Attack Damage: Base attack damage stat of the champion (integer).
- Gold Efficiency: Efficiency of the champion's gold usage (float).

### Installation
To run the analysis scripts, you need Python and the following libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:
```
pip install numpy pandas matplotlib seaborn scikit-learn

```

### Visualization
Distribution of Base Health

- Histogram: Shows that the majority of champions have base health values centered around the mean, with a few outliers on both ends.

Distribution of Base Mana

- Histogram: Indicates a right-skewed distribution, with a larger number of champions having lower base mana values and a few with very high values.

Base Armor by Role

- Box Plot: Displays how base armor varies across different roles. Supports tend to have higher base armor compared to other roles.

Base Attack Damage vs. Gold Efficiency

- Scatter Plot: Reveals a positive correlation between base attack damage and gold efficiency, suggesting that champions with higher base attack damage might have higher gold efficiency.


### Insights
1. Role Differences: Different roles show distinct patterns in base health, armor, and other attributes. For example, Support champions generally have higher base armor compared to other roles, which could be related to their role in the game as a frontline character.

2. Statistical Ranges: There is a wide range of values for base mana and base health, indicating significant variability among champions.

3. Gold Efficiency: The mean gold efficiency is close to 1, suggesting that most champions are designed with balanced gold usage efficiency, though some champions are more efficient than others.