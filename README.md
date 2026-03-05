# Hospitality Data Analysis 

## Project Overview

This project analyzes hotel booking data to understand occupancy trends, revenue performance, and booking behavior across different properties.
The analysis focuses on cleaning raw datasets, generating business metrics, and extracting insights that help evaluate hotel performance.


## Objective

The goal of this project is to perform data cleaning, exploratory data analysis (EDA), and feature engineering on hospitality booking datasets to identify key patterns in occupancy, revenue generation, and demand trends.

## Data Cleaning & Preparation

**1.Removed invalid records such as negative guest values.**

**2.Detected and removed outliers using the 3-standard-deviation method.**

**3.Handled missing values using median/mean imputation.**

**4.Standardized date formats for time-based analysis.**

**5.Integrated datasets using property_id joins.**

## Feature Engineering

**1.Occupancy Rate (%) – Calculated using Successful Bookings / Capacity to measure how effectively each property utilizes its available rooms.**

**2.Overbooking Identification – Detected records where successful bookings exceeded property capacity to identify operational inconsistencies.**

**3.Property Performance Metrics – Generated booking and revenue metrics at the property level to evaluate and compare hotel performance.**


## Key Analysis Performed

**1.The project answers several business questions.**

**2.Total bookings per property.**

**3.Overbooking detection where bookings exceed capacity.**

**4.Average occupancy rate by room category.**

**5.City-wise revenue analysis.**


## Conclusion.
**This project demonstrates the use of Python and Pandas to clean, analyze, and extract insights from hospitality booking data. Through data preprocessing, feature engineering, and exploratory analysis, key metrics such as occupancy rate, revenue performance, and booking patterns were evaluated across different properties and cities.**

**6.Month-by-month revenue trends.**

**7.Weekday vs weekend occupancy comparison.**

