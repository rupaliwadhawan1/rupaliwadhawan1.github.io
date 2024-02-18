---
date: 2021-01-06 05:20:35 +0300
title: Toronto Police Patrol Program
subtitle: Machine Learning, Geographic Regression with Frontend
image: /uploads/screenshot-2024-02-17-at-5-18-54-pm.png
---
The project proposes the implementation of AI predictive modeling to enhance the effectiveness of TPS (Toronto Police Service) operations by identifying high-risk areas through a heatmap. This tool will also recommend optimized patrol schedules to guarantee minimal response times. Furthermore, the project aims to analyze historical data to create new divisional response time guidelines, ensuring a more efficient and responsive police service.

![Palm trees](/uploads/1.png)

**Approach**<br>This project applies gradient boosting and Folium to optimize police patrol locations, aiming to improve response times and public safety. Gradient boosting identifies optimal patrol car stations, while Folium creates an interactive heatmap categorizing neighborhoods by risk level. Response times are calculated using driving distances between police divisions and stations, assuming a constant speed of 70 km/h. This approach combines advanced data analytics, machine learning, and geospatial visualization to deploy patrol resources strategically. The project presents a scalable solution to enhance efficiency and responsiveness in police operations.



**Tools**

* Gradient Boosting Regressor: For predicting optimal patrol positions per division.
* Google Map APIs: For calculating optimal response times.
* Folium: For creating heatmap and plotting patrol points.