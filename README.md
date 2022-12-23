# Google-Play-Store-Case-Study
**Overview**

This repo contains a case study of the applications on the Google Play Store, where we handle data, compare, the attributes like size, price, ratings of the app and visualize to gain valuable insights.

The tasks performed on the data set are as follows: 

- Data Cleaning
- Data Manipulation
- Data Analysis 
- Data Communication with Information Visualization

The analysis focuses on the breadth and present the data with aesthetics, instead of focusing on a single attribute in depth. This will give us an overall understanding of the applications listend on Play Store.

**Workflow**

1.	The project starts with importing the necessary libraries and the required dataset
![import and view](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/import%20and%20view.png?raw=true)

2.	The following tasks related to data handling were performed 
  - data handling 
  - cleaning junk records
  - adding missing values 
  - changing data types 
  - removing outliers
![data clean](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/data%20clean.png?raw=true)

3.	Analyzed the ratings using the histogram, and saw that data was skewed towards the higher ratings.
![distribution of rating](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/distribution%20of%20rating.png?raw=true)
![distribution of rating 2](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/distribution%20of%20rating%202.png?raw=true)

4.	Then we observed a weak trend between the ratings and the size of the app using a scatter plot.
![scatter plot](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/size%20vs%20rating.png?raw=true)

5.	To understand the nuances, we used reg plot.

![reg-plot](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/regplot.png?raw=true)

6.	Using pair-plot we were able to see multiple scatter plots and draw several inferences, e.g. price and rating have a very weak trend, reviews and price being inversely related.
![pair plot](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/pair%20plot.png?raw=true)

7.	Later we utilized estimator functions along with bar plots as well as box plots to observe the spread of ratings across the different Content Rating Categories. The observation we made was, the ‘Everyone’ category has a lot of apps having very low ratings.
![estimator](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/estimator.png?raw=true)
![estimator 2](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/estimator%202.png?raw=true)
![boxplot](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/boxplot.png?raw=true)

8.	Finally, we created a heat map comparing the ratings across different Reviews and Content Rating buckets. 
![heatmap-green](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/heat-green.png?raw=true)
![heatmap-mako](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/heat-mako.png?raw=true)
![heatmap-viridis](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/heat-viridis.png?raw=true)
![heatmap-flare](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/heat-flare.png?raw=true)
![heatmap-rocket-r](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/heat-rocket-r.png?raw=true)
![heatmap-magma](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/heat-magma.png?raw=true)

9. Overview of monthly average ratings
![monthly updated](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/line-update-month.png?raw=true)
![monthly updated](https://github.com/therealyash/Google-Play-Store-Case-Study/blob/main/Assets/Images/monthly-average%20rating.png?raw=true)





