
![Aviation Accident Data Analysis](./images/plane readme.jpeg)

# Aviation Accident Data Analysis

**Author**: [Lucinda Wanjiru](mailto:lucinda.wanjiru@student.moringaschool.com)

## Overview

### Overview

The company is planning to enter into the aviation industry in order to diversify its assets. Specifically, interested in purchasing and operating airplanes for commercial and private enterprises. A risk assessment is essential to minimize liability and maximize safety. 
This project analyzes data from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

A descriptive analysis of the data, including accident frequency, severity by aircraft make and model, impact of weather conditions, relationship between flight purpose (e.g., private vs. commercial), and risks.

This analysis can be used by the company to determine which aircraft has the lowest operational, financial, and safety risks.

## Business Problem

The company will be able to reduce the risks of safety and financial obligations related to aircraft operation by picking the safest and most reliable models. I aim to:

- Identify low-risk aircraft models.
- Assess the severity and frequency of accidents.

- Assess the elements that contribute to accidents.
- Make recommendations for the best airplanes based on the data analysis results.
This will allow the company to choose which airplanes to purchase.

## Data Understanding

The aviation accident [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) sourced from Kaggle originally obtained from the National Transportation Safety Board contains a detailed record of airplane accidents. Every accident has a unique ID, that is, 'Accident Number' and includes important details such as the date, location, airplane make and model, the severity of injuries, etc. The dataset also captures factors like weather conditions and the phase of flight. This dataset allows for comprehensive analysis of accident patterns, risk factors, etc and to understand the relationship between airplane models, accident severity, and environmental factors.

## Methods

This project uses descriptive analysis, including which summarizes key metrics like total incidents, fatalities, and injury rates. Time Series Analysis identifies trends in accidents over the years. Categorical Analysis compares incidents by aircraft make, model, or purpose of flight. The correlation heatmap visually represents the relationships between the number of engines and the different categories of injuries/uninjured in aviation accidents.


## Results

Most animals have short stays at AAC (under 15 days) but some have long stays (over 180 days), and most of these are dogs.

![stay_lengths_by_type](./images/stay_lengths_by_type.png)

The total number of sheltered animals typically peaks in May of each year and then hits its lowest point around January. There is often a secondary peak sometime after May before the number of sheltered animals drops rapidly. The number of sheltered animals has dropped precipitously in 2020, likely as a result of COVID-19.

![sheltered_by_month.png](./images/sheltered_by_month.png)

## Conclusions

This analysis leads to three recommendations for improving operations of the Austin Animal Center:

- **Engage in targeted outreach campaigns for dogs that have been sheltered at AAC for more than 30 days.** While most dogs will have been placed after 30 days, this may help reduce the number of dogs that end up having extended stays, potentially requiring many more months of care.
- **Reduce current spending until the numbers of intakes and sheltered animals return to normal.** Given the reduced activity during this period, AAC should consider ways to temporarily reduce costs by changing space utilization or staffing.
- **Hire seasonal staff and rent temporary space for May through December.** To accommodate the high volume of intakes and number of sheltered animals in the spring and fall, AAC should leverage seasonal resources, rather than full-year ones. This will allow AAC to cut back on expenditures during the months when there is lower

### Next Steps

Further analyses could yield additional insights to further improve operations at AAC:

- **Better prediction of animals that are likely to have long stays.** This modeling could use already available data, such as breed and intake condition.
- **Model need for medical support.** This modeling could predict the need for specialized personnel to address animals' medical needs, including neutering, using intake condition and sex data.
- **Predicting undesirable outcomes.** This modeling could identify animals that are more likely to have undesirable outcomes (e.g. Euthanasia) for targeted medical support or outreach.

## For More Information

See the full analysis in the [Jupyter Notebook](./animal-shelter-needs-analysis.ipynb) or review this [presentation](./Animal_Shelter_Needs_Presentation.pdf).

For additional info, contact Alison Peebles Madigan at [alison.peeblesmadigan@flatironschool.com](mailto:alison.peeblesmadigan@flatironschool.com)

![logo](./images/aac_logo_tall.jpg)

## Repository Structure

```
├── data
├── images
├── README.md
├── Animal_Shelter_Needs_Presentation.pdf
└── animal_shelter_needs_analysis.ipynb
```
