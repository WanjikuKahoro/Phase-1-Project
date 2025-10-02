# Aviation Accidents Analysis

## Overview
This project analyzes aviation accident data to identify patterns, assess aircraft safety and understand factors contributing to injuries and fatalities. The aim is to provide actionable insights for stakeholders, such as aviation regulators, operators and safety analysts.

---

## Business Understanding
**Stakeholders:** Aviation authorities, aircraft manufacturers, airline operators, insurance companies.

**Key Business Questions:**
1. Which aircraft makes or manufacturers are the safest or riskiest?  
2. How do aircraft characteristics (category, engine type, number of engines, builders) influence accident severity?  
3. How do environmental factors (weather conditions, seasonality) affect the likelihood of fatal accidents?  
4. Are there trends in injuries or fatalities over time (monthly or seasonal)?  

---

## Data Understanding and Analysis

**Source of Data:**  
The dataset was obtained from publicly available aviation accident records in kaggle, containing detailed information on aircraft, accidents, injuries, and environmental conditions.

(https://github.com/learn-co-curriculum/dsc-phase-1-project-v3/blob/master/data/Aviation_Data.csv)

**Description of Data:**  
The dataset includes the following key columns:  
- `Event.Id`: Unique identifier for each accident event  
- `Make`: Aircraft manufacturer 
- `Aircraft.Category`: Type of aircraft (Airplane, Helicopter, etc.)  
- `Engine.Type` and `Number.of.Engines`: Engine specifications  
- `Amateur.Built`: Indicates if the aircraft was built by a professional or an amateur 
- `Total.Fatal.Injuries`, `Total.Serious.Injuries`, `Total.Minor.Injuries`, `Total.Uninjured`: Injury counts  
- `Weather.Condition`, `Season`, `Month`: Environmental factors  

---

## Three Visualizations

1. **Fatality Rate by Engine Type and Number of Engines**  
   - Bar charts highlighting how engine type and the number of engines correlate with fatalities.  

2. **Fatal and Uninjured Injuries Over Months**  
   - Line chart showing trends in fatal and non-fatal injuries across months.  

3. **Fatality Rate by Season and Weather Conditions**
   - Bar Charts highlighting the correlation between fatalities and season and weather condition.

> These visualizations are included in the slides and notebook for detailed interpretation.

---

## Conclusion

**Summary of Conclusions:**
1. Certain aircraft manufacturers consistently show lower fatality rates, highlighting safer designs. 
  Adams is the Riskiest
  Cub Crafters Inc is the safest

2. Engine type and number of engines are strongly associated with accident severity; single-engine aircraft and certain engine types have higher fatality risk.  
   1 Engine aircrafts have a higher fatality rate while 6 Engine aircrafts have lower risk
   Reciprocating are more prone to fatality than LR engines.

3. Environmental factors, such as weather conditions and seasonality, significantly affect the likelihood and severity of accidents.  
  During summer, there is more air activity and VMCs are widely used therefore there are more events, but the fatality rate is lower.
These insights can inform **aviation safety policies, maintenance priorities, and risk management strategies**.

---
