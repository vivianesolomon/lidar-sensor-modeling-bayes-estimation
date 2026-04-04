# lidar-sensor-modeling-bayes-estimation
This project models LiDAR sensor noise and applies Bayesian inference for state estimation using real-world data collected from a Velodyne Puck sensor.

- Modeled LiDAR range measurements as Gaussian distribution
- Constructed conditional probability model P(Z|X)
- Applied Bayes rule to estimate position probabilities
- Transformed GPS coordinates into a local Cartesian frame


LiDAR Histogram + Gaussian Fit
<img width="563" height="455" alt="image" src="https://github.com/user-attachments/assets/94ee1d82-435e-449f-9d9e-95a525a6587b" />

Bayesian State Estimation
- Highest probability state: x2 (=0.669)
- Demonstrate probabilistic localization from noisy measurements

GPS Transformation
- Converted lat/lon -> (x,y)
- Observed higher variance in x-direction
