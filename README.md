# Media Company Case Study

## Overview

This repository contains a case study analyzing the declining viewership of a digital media company's show. The project includes the following components:
 1. Media_Company_Case_Study.ipynb: Jupyter Notebook containing the entire analysis, including data preprocessing, modeling, and insights.
 2. data/: Folder containing the dataset used for analysis.
 3. plots/: Folder with visualizations generated during the analysis.

## Problem Statement

The company wants to understand why the viewership of their show has decreased. The potential reasons could include:

 1. Decline in the number of visitors coming to the platform.
 2. Fewer people watching the videos.
 3. Decrease in marketing spend.
 4. Competitive shows (e.g., cricket matches).
 5. Special holidays affecting viewership.
 6. Story twists impacting viewer interest.

## Data Description

The dataset covers the period from March 1, 2017, to May 19, 2017 and includes the following columns:

 1. Views_show: Number of times the show was viewed.
 2. Visitors: Number of visitors who browsed the platform (not necessarily watched a video).
 3. Views_platform: Number of times a video was viewed on the platform.
 4. Ad_impression: Proxy for marketing budget; represents the number of ad impressions.
 5. Cricket_match_india: Binary indicator (1 = cricket match was played on a given day, 0 = no match).
 6. Character_A: Binary indicator (1 = Character A was present in the episode, 0 = Character A was absent).

## Run

Execute the Jupyter Notebook to perform the analysis:

```bash
jupyter notebook Media_Company_Case_Study.ipynb
```

## Visualizations

Generated plots and visualizations are saved in the plots/ folder.

## Tools and Libraries Used

Python Libraries:

 1. pandas for data manipulation
 2. numpy for numerical operations
 3. matplotlib and seaborn for data visualization
 4. scikit-learn for building and evaluating the regression model

## Results

The regression analysis highlights the key factors influencing viewership, such as:

 1. The number of platform visitors.
 2. Marketing spend (ad impressions).
 3. The impact of competitive shows like cricket matches.
 4. The presence of Character A.

## Conclusion

By identifying these key drivers, the media company can:

 1. Optimize marketing strategies.
 2. Schedule episodes to avoid conflicts with major events.
 3. Plan storyline developments that maintain viewer interest.

## Developer Information

- **Name**: Snehal Yadav
- **Contact**: [snehalyadav3099@gmail.com](mailto:snehalyadav3099@gmail.com)