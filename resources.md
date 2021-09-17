Date@140921
=========================
References:
https://www.w3resource.com/graphics/matplotlib/basic/index.php
https://pynative.com/python-basic-exercise-for-beginners/
https://www.kaggle.com/leonlxy/matplotlib-tutorial-with-exercises-1

Notes:
=====================================
Matplotlib is a Python 2D plotting library that produces high-quality charts and figures, which helps us visualize extensive data to understand better. Pandas is a handy and useful data-structure tool for analyzing large and complex data.

Date@160921
==================
References:
https://www.kaggle.com/shubh0799/churn-modelling
https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/#10.-Diverging-Bars

Notes:
1: Matplotlib consists of 3 layers which are the Backend, Artist, and Scripting layers. The scripting layer is the matplotlib.pyplot interface.
2: The scripting layer makes it relatively easy to create plots because it automates the process of putting everything together. Thus, it is the most widely-used layer by data scientists.

3: The rcParams package of matplotlib is used to store and change the default settings.
4:Histogram is used to visualize the distribution of a variable.

4: Scatter plots are commonly used to map the relationship between numerical variables. We can visualize the correlation between variables using a scatter plot

5: We can put multiple scatter plots on the same Figure object. Although the syntax is longer than some other libraries (e.g. Seaborn), Matplotlib is highly flexible in terms of subplots. We will do several examples that consist of subplots.

6: Scatteplot is a classic and fundamental plot used to study the relationship between two variables. If you have multiple groups in your data you may want to visualise each group in a different color 

Date@170921@AM
References:
https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/#1.-Scatter-plot
https://raw.githubusercontent.com/selva86/datasets/master/mpg_ggplot2.csv

Notes:
1: If you want to understand how two variables change with respect to each other, the line of best fit is the way to go.To disable the groupings and to just draw one line-of-best-fit for the entire dataset, remove the hue='cyl' parameter from the 
sns.lmplot() from the dataset (mpg_ggplot2.csv)

2:Marginal histograms have a histogram along the X and Y axis variables. This is used to visualize the relationship between the X and Y along with the univariate distribution of the X and the Y individually. This plot if often used in exploratory data analysis (EDA).

3:Marginal boxplot serves a similar purpose as marginal histogram. However, the boxplot helps to pinpoint the median, 25th and 75th percentiles of the X and the Y.

4: Correlogram is used to visually see the correlation metric between all possible pairs of numeric variables in a given dataframe (or 2D array).

5: Pairwise plot is a favorite in exploratory analysis to understand the relationship between all possible pairs of numeric variables. It is a must have tool for bivariate analysis.

6: If you want to see how the items are varying based on a single metric and visualize the order and amount of this variance, the diverging bars is a great tool. It helps to quickly differentiate the performance of groups in your data and is quite intuitive and instantly conveys the point.

7: Divering dot plot is also similar to the diverging bars. However compared to diverging bars, the absence of bars reduces the amount of contrast and disparity between the groups.

8: Lollipop with markers provides a flexible way of visualizing the divergence by laying emphasis on any significant datapoints you want to bring attention to and give reasoning within the chart appropriately.

9: By coloring the area between the axis and the lines, the area chart throws more emphasis not just on the peaks and troughs but also the duration of the highs and lows. The longer the duration of the highs, the larger is the area under the line.

10: Ordered bar chart conveys the rank order of the items effectively. But adding the value of the metric above the chart, the user gets the precise information from the chart itself.

11: Lollipop chart serves a similar purpose as a ordered bar chart in a visually pleasing way