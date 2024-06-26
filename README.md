With over 118 million users, 5 million drivers, and 6.3 billion trips with 17.4 million trips completed per day - Uber is the company behind the data for moving people and making deliveries hassle-free. How are drivers assigned to riders cost-efficiently, and how is dynamic pricing leveraged to balance supply and demand? Thanks to the large volumes of data Uber collects and the fantastic team that handles Uber Data Analysis using Machine Learning tools and frameworks.

The Uber Datasets:
We will perform data analysis on two types of rider data from Uber. The first dataset contains information about the rides taken by one particular user, and the second contains similar details about the rides taken by Uber users in two cities.
1sr: https://www.kaggle.com/datasets/zusmani/uberdrives
2nd: https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma

Uber Data Analysis - Challenges Working with Uber data:
Working with different kinds of data poses a unique challenge each time. Issues might crop up in the data values stemming from the data collection stage or the data storing/retrieval stage. One such challenge for the Uber dataset is that many location columns have NULL values or say “Unknown Location.” When fewer in number, you can delete these rows. But in our case, “Unknown Location” has a high occurrence in the location columns but does not give us any knowledge or insight about the user’s travel patterns. But due to their significance, those rows cannot be ignored unless the rest of the features of those rows are proven to be equally useless.

Learning Takeaways from Uber Data Analysis Project using Machine Learning: 
We looked at two different types of Uber ride datasets – a personal ride history for a single person and a two-month record of all the Uber rides in Boston, MA. We compared similar graphs in the EDA process of both these datasets to generate real-world insights into the behavior of the Uber riders and trips in the city of Boston. Furthermore, we used different ML models to perform a price prediction of the Uber ride based on a fixed number of features from the second dataset. We also perform feature selection to reduce the number of features and find the optimal amount to improve model performance to a certain degree. We find that Gradient Boosting Machine (GBM) works best in this dataset, yielding 0.95.

Finally, we noted some crucial issues faced by scientists during EDA and data analysis and listed the challenges of working with the Uber datasets.
