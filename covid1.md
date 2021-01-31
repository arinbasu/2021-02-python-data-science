From:
[Five thirty's covid geography](https://github.com/fivethirtyeight/data/tree/master/covid-geography)

Contains data behind the story How One High-Risk Community In Rural South Carolina Is Bracing For COVID-19.

mmsa-icu-beds.csv combines data from the Centers for Disease Control and Prevention’s Behavioral Risk Factor Surveillance System (BRFSS), a collection of health-related surveys conducted each year of more than 400,000 Americans, and the Kaiser Family Foundation to show the number of people who are at high risk of becoming seriously ill from COVID-19 per ICU bed in each metropolitan area, micropolitan area or metropolitan division for which we have data.

Being high risk is defined by a number of health conditions and behaviors. Based on the CDC’s list of the relevant underlying conditions that put people at higher risk of serious illness from COVID-19, plus the advice of experts from the Cleveland Clinic, the American Lung Association and the American Heart Association, we counted people as at risk if they’re 65 or older; if they have ever been told they have hypertension, coronary heart disease, a myocardial infarction, angina, a stroke, chronic kidney disease, chronic obstructive pulmonary disease, emphysema, chronic bronchitis or diabetes; if they currently have asthma or a BMI over 40; if they smoke cigarettes every day or some days or use e-cigarettes or vaping products every day or some days; or if they’re currently pregnant. We included every individual who meets at least one of these conditions but counted them only once each, so anyone with multiple conditions doesn’t get counted multiple times. We were not able to include a number of conditions for which we did not have location-based data from the BRFSS, such as liver disease, having smoked, vaped or dabbed marijuana in the last 30 days, and getting cancer treatment or being on immunosuppression medications.

| Column |	Description |
|--------|--------------|
| MMSA   |	The name of the metropolitan area, micropolitan area or metropolitan division available in the CDC’s BRFSS |
| total_percent_at_risk |	The percent of individuals in that area that are at high risk of becoming seriously ill from COVID-19, per CDC’s BRFSS |
| high_risk_per_icu_bed |	The number of high risk individuals per ICU bed in that area |
| high_risk_per_hospital |	The number of high risk individuals per hospital in that area |
| icu_beds |	The number of ICU beds in the area, based on the Kaiser Family Foundation’s data |
| hospitals |	The number of hospitals in the area, based on the Kaiser Family Foundation’s data |
| total_at_risk |	The total number of high risk individuals in the area, per CDC’s BRFSS |
