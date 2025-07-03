# E-Commerce-Product-Delivery-Prediction
E-Commerce Product Delivery Prediction
Project Overview:
This project focuses on predicting whether products from an international e-commerce company will be delivered on time. It also analyzes key factors influencing delivery outcomes and explores customer behavior. The company primarily deals in electronic products.

Dataset Summary:
The dataset consists of 10,999 records with 12 variables, including:

ID: Unique customer identifier

Warehouse_block: Warehouse section (A, B, C, D, E)

Mode_of_Shipment: Shipment type (Ship, Flight, Road)

Customer_care_calls: Number of inquiry calls made by the customer

Customer_rating: Rating given by the customer (1 to 5)

Cost_of_the_Product: Product price in USD

Prior_purchases: Number of past purchases made by the customer

Product_importance: Importance level (Low, Medium, High)

Gender: Gender of the customer (Male, Female)

Discount_offered: Discount applied to the product

Weight_in_gms: Product weight in grams

Reached.on.Time_Y.N: Target variable (1 = Not on time, 0 = On time)

Key Insights:

Products weighing between 2500–3500 grams and priced below $250 were more likely to be delivered on time.

The majority of shipments from Warehouse F used shipping mode, likely due to its proximity to a seaport.

High customer care call volume was associated with delayed deliveries.

Loyal customers (with more prior purchases) experienced higher on-time delivery rates.

Products with discounts above 10% were more likely to arrive on time compared to those with smaller discounts.

Model Performance:
Multiple classification algorithms were tested.

Decision Tree achieved the highest accuracy at 69%.

Random Forest and Logistic Regression followed with 68% and 67% accuracy.

K-Nearest Neighbors (KNN) had the lowest performance at 65%.

