# Sales-Analysis
Sales analysis of the online electronics store.

This project is based on [tutorial](https://youtu.be/eMOA1pPVUc4).

I try to answer the following questions:
1. What was the best month for sales?
2. What city sold the most product?
3. What time should we display advertisements to maximize the likelihood of purchases?
4. What products are most often sold together?
5. What product sold the most?

Main stages of this analysis are:
1. Getting main info about data (top values, unique values, NaN amount, how orders are presented, etc)
2. Cleaning data from NaN
3. Adding necessary info to perform analysis
4. Answering questions.

# Pokemon-Analysis

Basic data analysis of the pokemon-data

This project is based on [tutorial](https://youtu.be/vmEHCJofslg)

Following interesing manipulations are done:
1. Reordering of columns
2. Filtering data with several conditions
3. Resetting index(with/without delete)
4. Conditional changes.
    - Change value of one column, while there is a condition on on other column.
    
# Graphs
This notebook is created for practice of creating data-graphs.

The following tutorials were used:
1. [Intro to Data Visualization in Python with Matplotlib! (line graph, bar chart, title, labels, size)](https://youtu.be/DAQNHzOcO5A)
2. [Python Plotting Tutorial w/ Matplotlib & Pandas (Line Graph, Histogram, Pie Chart, Box & Whiskers)](https://youtu.be/0P7QnIQDBJY)

The following graphs were created:
1. Simple line graphs
  - how to put legend, xticks, yticks,titles, change colors of graphs, etc.
2. Two or more graphs in one figure
3. Bar chart
4. Histogram
5. Pie chart
  - how to set percent values.
  
 # Amazon review Sentiment Analysis (ML)
 
In this project i followed [tutorial](https://youtu.be/M9Itm95JzL0) and tried to build a ml-model, that can predict if review is possitive or negative.

Main steps are:
1. Loading data & cleaning it. Creating auxiliary classes to keep code clean and understandable
2. After checking that there are much more positive reviews than negative, cut off rest of extra positive reviews. This action keep our model in blanace (equal amount of test data (positive and negative reviews))
3. Vectorization of reviews( *bag of words + tfidf*)
4. Classification using **sklearn-library**
5. Tuning out clf-s with grid search to find best hyperparams
6. Save/Load models with **pickle-library**

 
 
