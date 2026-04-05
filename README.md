# lidar-sensor-modeling-bayes-estimation
Author: Viviane Solomon, Engineer @ Harvey Mudd College

# Overview
This lab covers probabilistic sensor modeling and Bayesian state estimation using real LiDAR and GPS data collected from a stationary sensor in the Parsons building courtyard.

# Lab Sections
1. Histograms: Range histograms for azimuth = -90º, 0º, and 90º.
2. Gaussian Model: Fit a Gaussian PDF p(z | μ, σ²) to the -90º range data
3. GPS Coordinate Transform: Convert lat/lon to local X/Y (meters) using the flat-earth approximation from E80 Lab 7
4. Bayes Rule: Estimate robot's position across 4 discrete states given a range measurement z = 9.272m
5. Police Data Model: Conditional age distributions by race from police_killings.csv, modeled with Gaussian PDFs and empirical histograms

# Setup
## Running in Google Colab
1. Upload the following files to Google Drive under MyDrive/:
- lab1_azimuth_90.csv
- lab1_azimuth_00.csv
- lab1_aximuth_90.csv
- police_killings.csv

2. Open E205_Lab1_VKS.ipynb in Google Colab
3. Mount Drive when prompted and run cells top to bottom

## Data
The LiDAR data and police_killings.csv were provided as part of the lab prompt and are included in this repository.

