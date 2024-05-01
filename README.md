# Netflix-Subscriptions-Forecasting-using-Python

In this project, we aim to estimate the expected number of new Netflix subscribers within a specified time frame by analyzing historical subscriber data and employing various statistical models. 

By examining trends in subscriber growth, we can gain insights into the potential expansion of their business. This estimation process enables Netflix to make well-informed decisions regarding investments in content, marketing strategies, and infrastructure, all of which are crucial for supporting their growing subscriber base.

The process to follow in a Time Series Project :
  1. **Data collection:** Gather time series data from reliable sources.
  2. **Data Cleaning:** Clean and pre-process data to handle outliers or missing values.
  3. **Visualize data:** Plot data to identify any trends or seasonality.
  4. **Stationarity test:** Use statistical tests to check if the data is stationary.
  5. **Decompose data:** Separate data into a trend, seasonality, and residual components.
  6. **Choose a model:** Select an appropriate time series model based on data properties.
  7. **Train the model:** Fit the model to the data and tune parameters to improve accuracy.
  8. **Evaluate the model:** Use performance metrics to assess model accuracy.
  9. **Predict future values:** Use the trained model to make predictions about future time series values.

Please note that the Jupyter notebook may not display the entire plots, maybe because they are generated using **the Plotly package** of Python. Therefore, I recommend running the notebook locally for a better visualization experience. 

Below is the forecast plot for Netflix subscribers for the next 5 days.

<img width="872" alt="forecasting_results" src="https://github.com/FatineDev/Netflix-Subscriptions-Forecasting-using-Python/assets/120562023/6fe6da53-7ce8-4306-9327-845d37b5ae27">

**UPDATE** I've added a new Jupyter file with updates (Netflix_TS_updated.ipynb). I noticed that the output images generated with the Plotly package weren't displayed at all (likely due to an issue with Github's Notebook renderer). To address this, I downloaded and displayed these images using the Pillow package and the display method, ensuring you can now see all the graphs clearly.