# Creating Customer Segments using Machine Learning

This project aims to identify customer segments hidden in the data utilizing unsupervised machine learning techniques on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal. Also, explored the data by selecting a small subset to sample to determine if any product categories highly correlate with one another. 

Afterwards, preprocessed the data by scaling each product category and then identifying (and removing) unwanted outliers. With the good, clean customer spending data, applied PCA transformations to the data and implemented clustering algorithms to segment the transformed customer data. Finally, compared the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes. Its's part of a series of projects under Udacity ML Engineer Degree.

# Things you will learn by completing this project:

 - How to apply preprocessing techniques such as feature scaling and outlier detection.
 - How to interpret data points that have been scaled, transformed, or reduced from PCA.
 - How to analyze PCA dimensions and construct a new feature space.
 - How to optimally cluster a set of data to find hidden patterns in a dataset.
 - How to assess information given by cluster data and use it in a meaningful way.
 
 # Key Takeaways
 
I believe it is important for any industry or business to know their customers in order to function in the most efficent manner possible in order to derive the hoghest profits. Good business comes from knowing your customers well in today's customer oriented world. It's equally important for businesses to understand the market segmentations and how their customers are divided to best entertain their needs and build an important relationship.

# Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the UCI Machine Learning Repository. Note (m.u.) is shorthand for monetary units.

Features
 - Fresh: annual spending (m.u.) on fresh products (Continuous);
 - Milk: annual spending (m.u.) on milk products (Continuous);
 - Grocery: annual spending (m.u.) on grocery products (Continuous);
 - Frozen: annual spending (m.u.) on frozen products (Continuous);
 - Detergents_Paper: annual spending (m.u.) on detergents and paper products (Continuous);
 - Delicatessen: annual spending (m.u.) on and delicatessen products (Continuous);
 - Channel: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
 - Region: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal)
