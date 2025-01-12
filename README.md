# Hotel_booking_cancelations
**About Dataset**
**Context**
 
The dataset used in this project is from real-world hotel booking data that contains information about hotel bookings made for two types of hotels: a City Hotel and a Resort Hotel. This dataset spans a period of two years, from July 1, 2015, to August 31, 2017, and includes information about both bookings that arrived and those that were canceled. The dataset has a total of 119,390 observations, each representing an individual hotel booking.

The dataset provides useful insights for understanding hotel booking trends, cancellations, and demand. By analyzing this data, hotel managers and businesses can identify patterns that may assist them in making data-driven decisions to improve their operations, manage booking capacity, and reduce cancellations.
<br>




**Content**
Since this is hotel real data, all data elements pertaining hotel or costumer identification were deleted. Four Columns, 'name', 'email', 'phone number' and 'credit_card' have been artificially created and added to the dataset.
<br>
<b>used data set:<b>
<br>
<a href ="https://github.com/Ashwani000/Hotel_booking_cancelations/blob/main/Hotel%20Bookings.xlsx">Dataset</a>
<br>
For pivot Tables:
<br>
<a href ="https://github.com/Ashwani000/Hotel_booking_cancelations/blob/main/Pivot%20Tables.xlsx">pivot table</a>
<br>
**Some of the key features in the dataset are as follows:**<br>

*1.Hotel Type:* Indicates whether the booking was made at a City Hotel or a Resort Hotel.<br>
*2.Arrival Date:* The date the guest was supposed to arrive.<br>
*3.Stay Duration:* The number of nights the guest planned to stay.<br>
*4.Booking Date:* The date when the booking was made.<br>
*5.Cancellation:* A binary column indicating whether the booking was canceled (1 for canceled, 0 for not canceled).<br>
*6.Lead Time:* The time between the booking date and the arrival date.<br>
*7.Number of Adults:* Number of adults in the booking.<br>
*8.Number of Children:* Number of children in the booking.<br>
*9.Booking Source:* The platform or channel through which the booking was made (e.g., website, phone).<br>
*10.Special Requests:* Indicates whether the guest made any special requests during the booking.<br>
*11.Customer Location:* The country or region where the customer originated from.
<br>
**Objective of the Project:**<br>
The goal of the project is to predict hotel booking cancellations based on various features in the dataset. This will help hotels identify and mitigate the risk of cancellations, which is a major challenge in the hospitality industry.
<br>
<br>

*Key objectives include:*<br>

*1.Exploratory Data Analysis (EDA):* Analyze the dataset to uncover trends, correlations, and patterns in hotel bookings, cancellations, and customer behavior.<br>
*2.Cancellation Prediction:* Build a predictive model to estimate the likelihood of a booking being canceled. This could involve classification algorithms such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.<br>
*3.Feature Engineering:* Create new features from existing data that might improve the prediction model, such as lead time categories, booking time patterns, or customer segments.<br>
*4.Model Evaluation:* Evaluate the performance of different models using various metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
<br>
**Potential Benefits of the Project:**<br>
*1.Revenue Optimization:* By predicting cancellations in advance, hotels can overbook strategically or adjust their prices dynamically to compensate for potential losses.<br>
*2.Operational Efficiency:* Accurate predictions help hotels to better manage their booking capacity and ensure optimal room availability.
<br>
*3.Customer Insights:* Understanding which factors are correlated with cancellations allows hotels to identify high-risk bookings and target them with personalized offers or interventions (e.g., offering discounts to prevent cancellations).<br>
*4.Business Strategy:* This analysis can help businesses fine-tune their marketing and booking strategies to reduce the overall cancellation rate.
<br>
**Acknowledgments:**<br>
This dataset is sourced from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes. It was published in Data in Brief, Volume 22, February 2019. The dataset is publicly available for educational and research purposes.

The dataset’s structure and details make it highly suitable for modeling and analysis of the factors influencing hotel booking cancellations, making it a valuable tool for data science projects aimed at the hospitality sector.











