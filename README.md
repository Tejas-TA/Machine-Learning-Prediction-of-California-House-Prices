### Machine Learning Prediction of California House Prices <hr>

<b>Heroku</b> - https://california-house-price.herokuapp.com/ <br>
<b>Google Cloud Platform</b> - https://ai-california-house-prices.ue.r.appspot.com/ <br>
<b>Azure</b> - https://ml-california-house-price-predictions.azurewebsites.net/ [Free Tier Limit exceeded, Application might be shutdown] <br>


<img src="https://github.com/Tejas-TA/ML-California-House-Prices-Prediction/blob/main/California_Demo.gif" width = "100%" height="100%">

<h3>California House Price App Predicts the cost of affording a home based on factors such as longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, median_house_value, and ocean_proximity. The data is collected from 1990 California census data</h3><hr>

<h3>Dataset</h3> https://www.kaggle.com/camnugent/california-housing-prices <br><hr>

<h3>Libraries Used</h3>
1. Flask<br>
2. gunicorn<br>
3. itsdangerous<br>
4. Jinja2<br>
5. MarkupSafe<br>
6. Werkzeug<br>
7. Pillow<br>
8. Numpy<br>
9. Scikit-learn<br>
10. Pandas<br>
11. Seaborn<br>
12. Joblib<br>
13. Matplotlib<br>
14. HTML<br>
15. CSS<br>
16. Bootstrap<br>
17. JavaScript<br><hr>

<h3>Project Walkthrough</h3>
1. Exploratory Data Analysis(EDA)<br>
2. Data Visualization and Cleaning<br>
3. The total_bedrooms feature has 207 missing values. These missing values are filled by the mean of the entire feature<br>

![image](https://user-images.githubusercontent.com/13360641/111071406-0bd3ff80-84fc-11eb-9d88-cab70469b9e1.png)

There was an outlier in the median house value feature which was removed<br>
![image](https://user-images.githubusercontent.com/13360641/111071475-5190c800-84fc-11eb-8605-ac909da4e323.png)<br>
![image](https://user-images.githubusercontent.com/13360641/111071483-5f464d80-84fc-11eb-948a-bd59b3acf778.png)

4. Feature Engineering<br>
5. Feature Selection<br>
6. Trained many Machine Learning algorithms on the dataset<br>
7. Predicted all the trained models on the test dataset<br>
8. Model Evaluation(Calculated R2, Adjusted R2, MSE, RMSE, MAE and Accuracy)<br>
9. Accuracies graph of all the models' data was trained on is as below- <br>
![image](https://user-images.githubusercontent.com/13360641/111071512-8270fd00-84fc-11eb-8e93-ee66491df122.png)
10. Hyperparameter Tuning is done on the top-performing base ML algorithms(Catboost, RandomForest, LightGBM)<br>
11. Exported the model<br>
11. Developed Front End Web-based application and created a flask server<br>
12. App running successfully in Google Cloud Platform, Azure, and Heroku
<hr>
    
LinkedIn - https://www.linkedin.com/in/tejas-ta/ <br>
Email - tejasta@gmail.com <br>
Blogs - https://tejasta.medium.com/ <hr>
