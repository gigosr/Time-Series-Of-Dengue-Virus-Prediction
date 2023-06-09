# Dengue Virus Prediction 

<img width="947" alt="Screenshot 2023-04-16 at 9 58 43 PM" src="https://user-images.githubusercontent.com/121091458/232673657-23d08676-e681-4d82-96a4-11ccfbf13dc0.png">

##### Author Gligor Vasilev


### Overview

This project aims to predict dengue virus outbreaks using machine learning techniques. 

In this project, we leverage machine learning algorithms and historical dengue data to forecast dengue outbreaks. We use a combination of data preprocessing, feature engineering, and machine learning models to predict dengue cases in specific regions or areas. The models are trained on historical data and evaluated using appropriate performance metrics. The project also includes visualization and analysis of the predicted results to gain insights into the patterns and trends of dengue outbreaks.

The code provided in this repository allows users to easily run the dengue virus prediction models, analyze the results, and make informed decisions for disease control and prevention. The project has potential applications in resource allocation, disease control, public health messaging, economic impact assessment, risk assessment, and insurance planning.







### Business Understanding

Dengue is a mosquito-borne viral disease that poses a significant public health challenge in many tropical and subtropical regions worldwide. The rapid spread of the disease and its impact on healthcare resources, economic productivity, and public health make it a pressing concern for governments, healthcare providers, policymakers, and other stakeholders.

The main business problems related to dengue virus outbreaks that this project aims to address are:

Resource allocation: During dengue outbreaks, healthcare resources can be strained, including hospital beds, medical personnel, and supplies. Accurate prediction of dengue outbreaks can help allocate resources effectively to areas at higher risk, ensuring that adequate resources are available to manage the increased demand.
Disease control and prevention: Controlling mosquito populations, which transmit the dengue virus, is a critical strategy for preventing dengue virus transmission. Predicting dengue outbreaks can inform targeted mosquito control measures in high-risk areas, reducing the spread of the virus and preventing outbreaks.
Public health messaging and education: Timely and targeted public health messaging and education campaigns can help raise awareness among the public, healthcare professionals, and other stakeholders about the risks of dengue and the importance of preventive measures. Accurate prediction of dengue outbreaks can enable effective public health messaging and education efforts.
Economic impact: Dengue outbreaks can have significant economic consequences, including increased healthcare costs, lost productivity due to illness, and decreased tourism in affected areas. Predicting dengue outbreaks can help businesses and policymakers plan and implement appropriate measures to mitigate the economic impact.
Risk assessment and insurance planning: Accurate prediction of dengue outbreaks can assist insurance companies in assessing the risk of dengue-related claims and developing appropriate insurance products. It can also help individuals, businesses, and governments in planning for insurance coverage, risk management, and financial preparedness in areas prone to dengue outbreaks.
By addressing these business problems, this project aims to contribute to effective dengue virus control and prevention efforts, improve resource allocation, raise public awareness, and mitigate the impact of dengue outbreaks on public health and the economy.


### Project Overview

This project was created to help the people in San Juan and Iquitos to get prepared for dengue virus outbreaks and to help government agencies to allocate resources.
In this project, using the data from 1990 to 2010, I was able to create a predictive model with very minimal error, 6 cases per week for San Juan and 4 cases per week for Iquitos.


### The Data

The data i used was downloaded from
(https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/)
The data is for two cities :San Juan, Puerto Rico, and Iquitos in Peru.
The Data for San Juan is from 1990-2005
the data for Iquitos is from 2000-2010
In the chart below we see the average number of cases per city per year


<img width="800" alt="Screenshot 2023-04-19 at 3 23 29 PM" src="https://user-images.githubusercontent.com/121091458/233212743-55060e9c-6667-4c1a-8a64-6220e856895d.png">

Also the data has weather and temperature related predictors seen in the plot below




<img width="891" alt="Screenshot 2023-04-19 at 3 31 43 PM" src="https://user-images.githubusercontent.com/121091458/233213988-c713e3d5-4fd3-49ca-af91-884b91093f55.png">



### Models

For a base model i created decision tree with 
<img width="1005" alt="Screenshot 2023-04-19 at 3 37 23 PM" src="https://user-images.githubusercontent.com/121091458/233214704-e9184f7a-e259-4403-8eae-d07460665d41.png">


<img width="300" alt="Screenshot 2023-04-19 at 3 37 57 PM" src="https://user-images.githubusercontent.com/121091458/233214768-868f6ded-db17-4385-a15d-c26bd43030fc.png">

Aditionaly for my main model i created two ## ARIMA models for each city, the model below is for San Juan
<img width="683" alt="Screenshot 2023-04-19 at 3 40 41 PM" src="https://user-images.githubusercontent.com/121091458/233215115-99b70007-090e-47ac-92e6-75531635361e.png">

and the second ## Arima model is for Iquitos


<img width="622" alt="Screenshot 2023-04-19 at 3 42 16 PM" src="https://user-images.githubusercontent.com/121091458/233215312-40df8673-ff32-4622-a5b2-88413e8eaa71.png">


### Next steps


1. Early detection: A prediction model with great accuracy can help in early detection of dengue virus outbreaks. This can enable health officials to take timely measures to control the spread of the disease, such as spraying insecticides, educating people about preventive measures, and providing medical treatment.
2. Targeted interventions: With accurate prediction models, health officials can target their interventions to the areas where the risk of dengue virus transmission is highest. This can help in prioritizing the allocation of resources and implementing interventions such as vaccination campaigns or distribution of bed nets.
3. Improved resource allocation: A prediction model with great accuracy can help in optimizing the allocation of healthcare resources. This can include the provision of adequate medical supplies and staffing of healthcare facilities in areas where the risk of dengue virus transmission is highest.
4. Better disease monitoring: Accurate prediction models can also help in monitoring the spread of dengue virus over time, which can aid in the development of effective public health strategies and policies.


### Conclusion

The objective of the project is to predict the number of dengue fever cases in two cities, San Juan and Iquitos. The data used in this project is collected over a period of several years and includes various environmental and climatic factors that may influence the incidence of dengue fever. Based on the performance metrics, it can be concluded that the ARIMA model performed better than the baseline model in predicting the number of dengue fever cases in the given dataset. The ARIMA model had a lower mean absolute error (MAE) and root mean squared error (RMSE) compared to the baseline model.

The ARIMA model also showed better performance in terms of the R-squared value, which indicates the proportion of variance in the target variable that can be explained by the independent variables. The ARIMA model had a higher R-squared value than the baseline model, indicating that it was able to explain a greater proportion of the variance in the target variable.

Therefore, it can be concluded that the ARIMA model is a better predictor of dengue fever cases in the given dataset compared to the baseline model.

Overall, the project demonstrates the potential of using time series analysis and ARIMA models for predicting the incidence of dengue fever. However, further work could be done to improve the accuracy of the models, such as incorporating additional variables or using more advanced modeling techniques.


