Crop Yield Prediction 

About the Project

I worked on this project to explore how agricultural and weather-related factors can help us understand crop yield across different countries and years. I used Python in Jupyter Notebook to explore the data and investigate how rainfall, temperature, and pesticide usage relate to crop production.

Dataset

I used a merged dataset named df_yield_merged.csv, which contains information about:

* Country or region
* Year
* Crop type
* Average annual rainfall
* Pesticide usage
* Average temperature
* Crop yield

Dataset source: Dataset for Crop Yield Prediction – Zenodo

What I Worked On

* Loaded and explored the dataset using Python and Pandas.
* Reviewed the data and prepared it for analysis.
* Explored crop yield alongside rainfall, temperature, and pesticide usage.
* Used data analysis and visualisation to look for trends and relationships.
  
Machine Learning Models

I trained and compared two regression models to predict crop yield:

* Linear Regression
* Random Forest Regressor

I evaluated both models using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score to understand how well their predictions matched the actual values.

Model Results

    Model	                       MAE	                  RMSE	                R² Score
Linear Regression	             33135.73	              52947.53	               0.6231

Random Forest	                 4078.33	              10955.04	               0.9839

Conclusion

In my experiments, Random Forest performed better than Linear Regression across all three evaluation metrics. It had lower prediction errors and a higher R² score on the test data.

This project helped me gain hands-on experience with regression models, model evaluation, and comparing machine learning approaches on an agricultural dataset.

Tools and Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

Project File

Crop_Yield_Weather_Analysis.ipynb — contains the code and analysis for this project.

How to Run

1. Download or clone this repository.
2. Install Python and Jupyter Notebook.
3. Install the libraries required by the notebook.
4. Download the dataset from the Zenodo source above.
5. Update the dataset file path in the notebook to match your computer.
6. Open the notebook and run the cells in order.

What I Learned

This project gave me practical experience working with datasets, exploring data using Python, and investigating how weather and agricultural factors relate to crop yield. It also helped me improve my understanding of data analysis and visualization.
