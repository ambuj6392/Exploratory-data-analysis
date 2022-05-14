# Exploratory-data-analysis

**Non-graphical Analysis: For understanding the distribution of data without plotting the graph. Below are the three commands that come under this:**
  * .df.info() - Print a concise summary of the data frame.
  * .df.describe() - It gives us some values in output like count, mean, standard deviation, minimum value, 25%, 50%, 75%, and maximum value etc.
  * .df.isnull() - It gives us Boolean output (either true or false). If there are any missing values then the output will be false otherwise true.
**Graphical Analysis: For understanding data using graphs and plots, we use graphical analysis. There are some common plots in EDA for graphical analysis:**
  # Univariate:
    Numerical: df[column].plot(kind=“hist”) - this is used to display histogram of the data
    Categorical: df[column].plot(kind=“bar”) - this is used to display bar plot of the data
  # Multivariate:
   ### Numerical vs Numerical:
      sns.pairplot() - this is used to plot a pairwise relationship between data. For each column, it plots the graph depending upon the parameters we pass in this pairplot() method.
      sns.heatmap() - this plot provides us the color matrix to visualize the value of the matrix.
   ### Categorical vs Categorical:
      sns.countplot(hue = ..) - as the name suggests, it shows the counts of observation using bars. This plot is very similar to bar plot or we can say that countplot is a group of many bar plots.
   ### Categorical vs Numerical:
      sns.boxplot() - this plot draws boxes to show the distribution of the data. There are many parameters that we can pass in the method depending on our needs.
      sns.pairplot(hue = ..) - this is the same as the above-defined pairplot.
      For reference and better understanding, image which has all the graphs which mentioned above is attached

