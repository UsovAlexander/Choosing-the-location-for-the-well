# Choosing-the-location-for-the-well

We need to decide where to drill a new well. We were provided with oil samples in three regions: in each 10,000 fields, where the quality of oil and the volume of its reserves were measured. Let's build a machine learning model that will help determine the region where mining will bring the greatest profit. Let's analyze the possible profits and risks with the Bootstrap technique.

Steps to select a location:

We are looking for deposits in the selected region, we determine the values of the features for each;
We build a model and estimate the volume of stocks;
We choose the deposit with the highest estimates of values. The number of deposits depends on the company's budget and the cost of developing one well;
The profit is equal to the total profit of the selected fields.

id — the unique identifier of the well;  
f0, f1, f2 — three signs of points (no matter what they mean, but the signs themselves are significant);
product — the volume of reserves in the well (thousand barrels).