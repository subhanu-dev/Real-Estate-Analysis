# EDA and Insight Analysis for Apartments in Colombo 🏢

## Introduction
This study aims to analyze the rental landscape in Colombo by leveraging a comprehensive dataset of apartment listings from various neighborhoods. 
The data set comprises various apartments from different neighborhoods across Colombo. This report will explore how rental prices vary across neighborhoods, identify the most influential property attributes, and provide data-driven recommendations for stakeholders in the real estate industry

Read the full report at 🔗: [EDA and Insight Analysis Report](https://github.com/subhanu-dev/Real-Estate-Analysis/blob/main/EDA_Report.pdf)
## Dataset Overview

Apartment_ID: Unique identifier for each apartment listing 
 * Neighborhood: Name of the neighborhoods 
 * Rental_Price: Monthly rental price 
 * Size_in_Sqft: Size of the apartment in square feet 
 * Distance_to_City_Center_KM: Distance to the Colombo Fort Station 
 * Bedrooms: Number of bedrooms 
 * Bathrooms: Number of bathrooms 
 * Furnished: Whether the apartment is furnished 
 * Building_Type: Type of the building

## Feature types for data columns include,
1. Categorical columns: Bedrooms, Neighborhood, Furnished, Building_Type 
2. Numerical Columns: Distance_to_city_Cente, Rental_Price, Bathrooms, ID, Size_in_sqft

## Methodology
1. Checking for Duplicates and Handling them
2. Dropping the unwanted ID column
3. Summary Statistics
   * Summary statistics for numerical columns
   * Ordinal Transformation of the bathroom feature.
   * Summary Statistics for Categorical Features
4. Numerical feature analysis
   * Plotting numerical column distributions
   * Plotting Boxplots to further understand the distribution and outlier detection
   * Removing Outliers
   * Bivariate analysis for Numerical Columns
5. Categorical Feature Analysis
   * Data Cleaning in Categorical features
   * Countplots for each of the categorical features to see value counts for each feature
   * Getting the boxplot distributions in rental values against each of the categorical columns and additional groupings
6. Correlation analysis of the numerical features Pair plots for plotting distribution
7. Discussion
   * Size (in Square Feet) and Rental Price
   * Distance to City Center and Rental Price
   * Neighborhood and Rental Prices
   * Building Type and Rental Prices
   * Bedrooms, Bathrooms, and Rental Price
   * Unexpected Findings with Furniture and Rental Price

## Conclusion
The analysis highlights some clear patterns in the rental market of Sri Lanka, particularly the positive correlation between size, bedrooms, and bathrooms with rental price, as well as the expected price differences between neighborhoods and building types.
We have also found expected trends of a decrease in rental price with distance from the fort though as not as significant.
However, the unexpected result regarding furnished versus non-furnished properties emphasizes the importance of data accuracy and validation.
