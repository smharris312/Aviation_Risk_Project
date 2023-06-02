# Aviation_Risk_Project

**Authors**: Sangyun (Yun) Thom, Sean Harris, Steven Hui

## Overview

This project aims to analyze the risk involved in aviation business by completing descriptive analyses on the data. The ultimate goal of this project is to provide 3 actionable recommendations to the business stakeholders evaluating the risk involved in the aviation business as potential future directions and strategies.

## Business Situation

Businesses that are interested in expanding to the aviation operations and purchases must evaluate the risk involved prior to making an executive decision. Knowledge on different risk factors in aviation business can help them provide more effective preventative measures or purchase safer airplanes.

## Data Information

The data is retrieved from the National Transportation Safety Board. It contains aircraft accident and incident reports. First, we want to import important packages for our project, and read in the raw data in .csv file. The raw dataset contains 90348 entries and 30 columns, dating from 1948 to 2022. Although not all categories are visible, majority of columns appear to contain some null values. Also, majority of them have objects as their data type.

## Methods

For the purpose of this project, we want to focus on a subset of the dataset provided. Since the stakeholders are new to the aviation business, we want to start with **domestic** operations. We also decide to focus on the **airplanes** as a type of aircraft, as the airplanes are typical type of aircraft used in the aviation business. **No amateur built airplanes** are included, because we reason that the amateur builts airplanes are not suitable for stakeholders to consider for their business model. Lastly, we only consider the **accident reports** from the data, as the accidents typically lead to more aircraft damages and injuries.

To propose recommendations to the stakeholders for their airplane operation business model, we complete 3 main exploratory data analyses (EDA) focusing on accident reports during last 10 years (from 2013 to 2022):

1. Month of the year with most accidents
2. Number of accidents and the severity of the airplane damage
3. Number of injuries of top 5 makes of airplanes with most accident reports

## Results

![image](https://github.com/smharris312/Aviation_Risk_Project/assets/128647470/d4e600b9-1ad8-414a-a303-84f90e548902)

Across 3 different severities of injuries (Fatal, Serious and Minor), **Cessna** appears to be the make that had the highest number of people with injuries. This finding suggests that among the 5 makes that had the most accident reports, **Cessna** has the most fatal, serious, and minor injuries. However, it is important to note that there can be several caveats. For example, these 5 makes most likely have many accident reports because they are the most widely used airplane makes. Therefore, while this analysis can provide a great insight into what make has reported the most injuries during last 10 years, further investigation is warranted.

## Conclusions

This project aims to provide three recommendations for the stakeholders to consider when purchasing and operating airplanes in the United States based on data from 2013 to 2022:

-**Additional safety training for staff members before July.** The most accident prone time of the year is July. Implementing additional safety training for members before this time hits can provide preventative measures.

-**Stricter safety policies for the airplanes operating.** Our analysis on the airplane damage during last 10 years indicates that many post-accident airplanes have substantial damages. Therefore, we recommend that stricter safety policies to be implemented to prevent airplanes that are in risk for substantial damanges from operating, and to repair them before they are in need of substantial repair. Further analyses on various related topics such as cost of applying stricter safety policies, age of airplanes, and hours of operation can provide more in-depth information.

-**Be cautious when purchasing from airplane makes with the most accident reports, such as Cessna.** Among 5 makes that had most accidents reported, Cessna had the biggest number of injuries. It may be beneficial to keep this information in mind when purchasing new airplanes. However, these top 5 makes most likely have many accidents because they are the most widely used airplane makes. Also, each make has several different models of airplanes that may have different safety measures. Therefore, further research is warranted on the actual safety of these airplanes.

### Future Insights

Further analyses can be beneficial to the stakeholders assessing risks in aviation business model. Here are some potential future insights:

- **Consider engine configurations.** Evaluating the relationship between engine configurations and accidents can provide valuable insights on what type of airplane is the safest.
- **Consider insurance options.** Based on the risk assessment provided in this project, the stakeholders can consider different insurance options that would be more suitable.
- **Develop safety policies for weather conditions** Having severe weather conditions can increase the risk of airplane operation and safety. Therefore, development or re-evaluation of safety policies can be beneficial to the stakeholders for reducing potential risks associated with flying airplanes in severe weather conditions.

## For More Information
See the full analysis in the [Jupyter Notebook](./Aviation_Risk_Analysis.ipynb) or review this [presentation](./Aviation_Risk_Presentation.pdf).

For additional info, contact Sean Harris at [smharris@myyahoo.com](mailto:smharris@myyahoo.com)

## Repository Structure

'''
├── .gitignore
├── Aviation_Data.csv
├── Aviation_Risk_Analysis.ipynb
├── Aviation_Risk_Presentation.pdf
├── README.md
'''
