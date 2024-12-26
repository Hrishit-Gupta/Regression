### Project Overview  

This project involves:  
1. **Data Cleaning and Preprocessing**: The provided dataset was cleaned and preprocessed to ensure high-quality inputs for the model.  
2. **Exploratory Data Analysis (EDA)**: Key patterns and insights from the dataset were explored to guide the modeling process.  
3. **Model Training**: A Linear Regression model was trained and evaluated using the following regularization techniques:  
   - **Lasso Regression**  
   - **Ridge Regression**  
   - **ElasticNet Regression**  

   Metrics used for evaluation:  
   - **Mean Squared Error (MSE)**  
   - **Mean Absolute Error (MAE)**  
   - **R² Score**  

4. **Model Serialization**: The trained model was serialized using `pickle` for seamless deployment.  
5. **Flask Application**: A Flask-based web app was created to allow users to predict outcomes by providing input feature values.  

This project demonstrates end-to-end machine learning workflow, from data preparation to flask app for prediction

<br>
<br>

### Information about the Algerian Forest Fires Dataset : 
<br>
<br>
The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria.
<br>
<br>
122 instances for each region.
<br>
<br>
The period from June 2012 to September 2012. The dataset includes 11 attribues and 1 output attribue (class) The 244 instances have been classified into fire(138 classes) and not fire (106 classes) classes.
<br>
<br>
Attribute Information:
<br>
<br>
Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012) Weather data observations
<br>
<br>
Temp : temperature noon (temperature max) in Celsius degrees: 22 to 42
<br>
<br>
RH : Relative Humidity in %: 21 to 90
<br>
<br>
Ws :Wind speed in km/h: 6 to 29
<br>
<br>
Rain: total day in mm: 0 to 16.8 FWI Components
<br>
<br>
Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5
<br>
<br>
Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9
<br>
<br>
Drought Code (DC) index from the FWI system: 7 to 220.4
<br>
<br>
Initial Spread Index (ISI) index from the FWI system: 0 to 18.5
<br>
<br>
Buildup Index (BUI) index from the FWI system: 1.1 to 68
<br>
<br>
Fire Weather Index (FWI) Index: 0 to 31.1
<br>
<br>
Classes: two classes, namely Fire and not Fire
<br>
<br>







