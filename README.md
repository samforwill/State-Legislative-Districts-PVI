# State Legislative Districts PVI Analysis

This project explores the use of a machine learning model trained on 451 characteristics of Congressional Districts to predict the Partisan Voter Index (PVI) scores. Achieving an R^2 of 0.92 and RMSE of 4.3, the model accurately predicted PVI within 4.3 points of the actual scores. Utilizing this model, PVI scores were assigned to every state legislative district's upper chamber/state senate seats based on similar demographics.

## Project Steps

1. **Model Training and Prediction**:
    - Trained a model to predict PVI scores for Congressional districts.
    - Applied the model to predict PVI for state senate districts.

2. **Evaluation and Adjustment**:
    - Initially, the model predicted 31% of Senate seats held by Democrats versus the actual 42%.
    - Systematic undervaluation of Democrats led to an adjustment, adding 6.25 points to each district's PVI to align predictions with actual compositions.

3. **State-by-State Analysis**:
    - Post-adjustment, the model showed improved predictions for state legislative compositions across nearly all states except New Hampshire.

4. **Detailed Case Study - North Carolina**:
    - Conducted a detailed analysis of North Carolina's state senate seats using QGIS.
    - Mapped and colored districts based on predicted and actual party control, identifying mispredicted "toss-up" districts.

5. **Visualization of Predictive Power**:
    - Generated maps for all state legislative seats in the USA, categorizing districts from "Super Solid D" to "Super Solid R".

I am currently working on the write-up for this project. In the meantime, check out the visualizations:

## Visualizations

1. ![Predicted Composition Donut](https://github.com/samforwill/State-Legislative-Districts-PVI/blob/main/images/1-%20Predicted%20Composition%20Donut.png)
2. ![Predicted Composition State Senates](https://github.com/samforwill/State-Legislative-Districts-PVI/blob/main/images/2-%20Predicted%20Composition%20State%20Senates.png)
3. ![Shifted Predicted Composition Donut](https://github.com/samforwill/State-Legislative-Districts-PVI/blob/main/images/3-%20Shifted%20Predicted%20Composition%20Donut.png)
4. ![Shifted Predicted Composition State Senates](https://github.com/samforwill/State-Legislative-Districts-PVI/blob/main/images/4-%20Shifted%20Predicted%20Composition%20State%20Senates.png)
5. ![Composition Error](https://github.com/samforwill/State-Legislative-Districts-PVI/blob/main/images/5-%20Composition%20Error.png)
6. ![USA PVI](https://github.com/samforwill/State-Legislative-Districts-PVI/blob/main/images/6-%20USA%20PVI.png)
7. ![NC Senate Seats](https://github.com/samforwill/State-Legislative-Districts-PVI/blob/main/images/7-%20NC%20Senate%20Seats.png)
8. ![GOP Gerrymander](https://github.com/samforwill/State-Legislative-Districts-PVI/blob/main/images/8-%20GOP%20Gerrymander.png)

Stay tuned for more updates and interactive versions of these maps!
