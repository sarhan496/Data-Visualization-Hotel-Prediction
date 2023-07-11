# Data-Visualization-Hotel-Prediction
ICT550 MINI PROJECT


1.0 INTRODUCTION
By now, all of us are aware that the Covid-19 pandemic has sent shock waves of disruptions to worldwide travel plans as travel restrictions have been imposed and flights have been cancelled. This has contributed to visitors scrambling to cancel their bookings for hotels and tours. In fact,the global travel industry has been overwhelmed by the large number of corona-virus induced cancellations. But hotel cancellations are nothing new.
1.1 THE DATASET
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests?

The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019. The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020.
1.2 OBJECTIVES
•	To evaluate feature importance i.e. which features are most important to predict hotel booking cancellations.
•	To predict the guests who are most likely to cancel their reservation and this will help to generate better forecasts and reduce business decision uncertainty.
•	 Build a model that could predict bookings with a high cancellation probability.
•	This notebook aims to predict the future Number of Guests for each hotel type.
 
 
2.0 ROOT CAUSE IDENTIFICATION

5W1H METHOD

•	WHO
o	Who is involved - On this project: This data set is ideal for anyone looking to practice their exploratory data analysis (EDA) or get started in building predictive models!
•	WHAT
o	What project you do: This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. 
•	WHEN
o	Year do dataset: The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019. 
o	The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020.
•	WHERE
o	Location dataset was done: This project has been downloaded testing from kaggle web based. 
•	WHY
o	Why this project does: Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests?
o	This hotel booking dataset can help you explore those questions!
•	HOW
o	How this project can support: To accomplish our aim, we will perform simple dataset visualization and analysis. we will use :
	Seaborn
	Plotly libraries for the visualization.
o	For the first step, I will clear the data and then use an Auto Arima model for the predicted future Number of Guests.
