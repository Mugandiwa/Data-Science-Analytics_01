**Data-Science-Analytics_01**

**PART 1 - VISUALISATION**

**Question 1**

A survey was conducted to gauge audience interest in different data science topics, namely: Big Data (Spark / Hadoop) Data Analysis / Statistics Data Journalism Data Visualization Deep Learning Machine Learning The participants had three options for each topic: Very Interested, Somewhat interested, and Not interested. 2,233 respondents completed the survey. If you examine the csv file, you will find that the first column represents the data science topics, and the first row represents the choices for each topic.

**Question 2**

Use the artist layer of Matplotlib to plot the bar chart to visualise the percentage of the respondent’s interest in the different data science topics surveyed. To create this bar chart, you can follow the following steps:

Sort the dataframe in descending order of Very interested. Convert the numbers into percentages of the total number of respondents. Recall that 2,233 respondents completed the survey. Round percentages to 2 decimal places. As for the chart: Use a figure size of (20, 8), Bar width of 0.8, Use colour #5cb85c for the Very interested bars, colour #5bc0de for the Somewhat interested bars, and colour #d9534f for the Not interested bars. Use font size 14 for the bar labels, percentages, and legend. Use font size 16 for the title, and Display the percentages above the bars and remove the left, top, and right borders.

**Part 2 - Supervised Learning Using Tree-Based Model**

Using the “ClaimsData.csv” vehicle insurance data file provided, you can explore the data and fit a tree-based model to the vehicle insurance data. The risk departments in insurance companies decide the client’s premium by looking at their risk profile. Clients who are likely to claim large amounts are given higher quotes for premiums than low-risk clients.

You may do an exploratory data analysis, Several graphs and calculations can be extracted from the data provided: two scatterplots (continuous variables), two bar graphs (mean claim amount for categorical variables), and two calculations without graphs (mean claim amount of vehicles in each category and mean claim amount of vehicles for each model year). What insight can you draw from these? In your answer, give a short interpretation of two graphs or calculations. For example, are there cars with a particular mileage that have larger claims? Are the mean claim amounts in any of the categories different? Ensure that you provide possible reasons for any differences you observe.

**Insight Questions from a Fitted Tree-Based Model**

You were asked to fit a tree-based model to this data set. Why do you think a tree-based model is more appropriate than a neural network in this scenario?

Use the decision tree image you generated to gain insight into the factors that affect the claim amount. Start by looking at the first split of the decision tree, and recommending a course of action with regard to the age of the driver. Choose two more nodes to interpret, and comment on the impact the output could have on premiums.

_NOTE: Remember to set the random_state=0 for reproducibility._

**A PDF OF THE NOTEBOOK INCLUDING A LINK TO THE EXECUTABLE VERSION ON BINDER**
