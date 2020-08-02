 ![](BHP_website.png)

This data science project is all about creating a model for real estate price prediction. So first i have collected all the data from KAGGLE.COM into my local space. First  i removed all NA values in the "data cleaning" process and then i started with "feature engineering" where i added new column as bhk(integer) and price per sqft for analysis. Then i moved with "dimensionality reduction" where i replaced all the locations which contains less than 10 datapoints with 'other'. Then i started "outlier detection" with standard deviation and mean method. Because my location is in text form so first i converted text data into numbers with the help of "one hot encoding" method. After all the analysis i started model building with the help of "Sklearn". So first i trained my data and then my model is ready for prediction and accuracy of my model is around 80%. Then i saved my model as pickle file in my computer and then i used flask server , HTML, CSS, JS for creating website. The tools used in this project is listed below,

1. Python programming language.
2. Numpy and Pandas for Data Cleaning.
3. Matplotlib for data visualization.
4. Sklearn for Model Building.
5. Jupyter notebook, visual studio code and pycharm as IDE.
6. Python flask for http server.
7. HTML/CSS/Javascript for UI.
