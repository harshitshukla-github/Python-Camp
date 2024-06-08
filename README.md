Pokémon Stats Analysis
Overview
This project involves a comprehensive analysis of Pokémon stats using a dataset containing various attributes of Pokémon. The primary objective is to visualize and interpret the data to derive meaningful insights.

Dataset
The dataset used in this analysis is Pokemon.csv, which includes the following columns:

#: ID of the Pokémon
Name: Name of the Pokémon
Type 1: Primary type of the Pokémon
Type 2: Secondary type of the Pokémon (if any)
Total: Sum of all base stats (HP, Attack, Defense, Sp. Atk, Sp. Def, Speed)
HP: Hit Points
Attack: Attack strength
Defense: Defense strength
Sp. Atk: Special Attack strength
Sp. Def: Special Defense strength
Speed: Speed of the Pokémon
Generation: The generation in which the Pokémon was introduced
Legendary: Boolean indicating whether the Pokémon is legendary
Analysis and Visualizations
The analysis is performed using Python, with libraries such as Pandas, Seaborn, and Matplotlib. Below are the visualizations and their interpretations:

1. Distribution of Pokémon by Primary Type
Description: Bar chart showing the count of Pokémon for each primary type.
Insight: Water, Normal, and Grass types are the most common, while Flying, Ghost, and Ice types are the least common.
2. Distribution of Pokémon by Total Stats
Description: Histogram illustrating the frequency distribution of Pokémon based on their total stats.
Insight: Most Pokémon have total stats between 300 and 500, indicating a clustering around mid-range stats.
3. Boxplot of Total Stats by Primary Type
Description: Boxplot comparing the distribution of total stats across different primary types.
Insight: Dragon and Psychic types generally have higher total stats compared to other types. Dragons show significant variability in stats.
4. Scatterplot of Attack vs Defense
Description: Scatterplot showing the relationship between Attack and Defense stats, distinguishing between Legendary and non-Legendary Pokémon.
Insight: Legendary Pokémon tend to have higher Attack and Defense stats. There is no strong correlation between Attack and Defense overall, indicating diverse roles and strategies.
5. Heatmap of Correlation Matrix
Description: Heatmap showing the correlation between different Pokémon stats.
Insight: Strong positive correlations exist between Total and other individual stats. Sp. Atk and Sp. Def have a moderate positive correlation.
6. Generation-wise Distribution of Pokémon
Description: Plot showing the number of Pokémon introduced in each generation.
Insight: The number of Pokémon introduced varies across generations, reflecting changes in game design and strategy.
7. Legendary Pokémon by Type
Description: Bar chart showing the distribution of Legendary Pokémon by their primary type.
Insight: Dragon and Psychic types have a higher number of Legendary Pokémon, indicating their perceived power or special abilities.
How to Run the Notebook
Ensure you have the required libraries installed:

bash
Copy code
pip install pandas seaborn matplotlib
Clone the repository and navigate to the project directory:

bash
Copy code
git clone <repository_url>
cd pokemon-stats-analysis
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook pokemon-visualization.ipynb
Run all cells to generate the plots and analyses.

Conclusion
This project provides a detailed analysis of Pokémon stats, offering insights into their distribution, correlations, and characteristics based on type and generation. The visualizations help in understanding the diversity and strengths of different Pokémon.

Author
HARSHIT SHUKLA

License
This project is licensed under the MIT License.
