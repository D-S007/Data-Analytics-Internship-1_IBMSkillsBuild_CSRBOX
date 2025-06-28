# Seaborn

1. import seaborn as sns # Import seaborn library
2. sns.set(style='darkgrid') # Set the style of seaborn plots
3. sns.histplot(data=df, x='column') # Create a histogram
4. sns.scatterplot(data=df, x='x_col', y='y_col') # Create a scatter plot
5. sns.lineplot(data=df, x='x_col', y='y_col') # Create a line plot
6. sns.barplot(data=df, x='x_col', y='y_col') # Create a bar plot
7. sns.boxplot(data=df, x='x_col', y='y_col') # Create a box plot
8. sns.violinplot(data=df, x='x_col', y='y_col') # Create a violin plot
9. sns.heatmap(data=df.corr(), annot=True) # Create a heatmap of correlation matrix
10. sns.pairplot(data=df) # Create a pair plot
11. sns.jointplot(data=df, x='x_col', y='y_col', kind='scatter') # Create a joint plot