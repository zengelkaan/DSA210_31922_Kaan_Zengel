# Turkish Football Süper Lig Success Analysis - DSA210 Project 

## Project Overview

For the rest of the semester, I will analyze the key factors that contribute to team success in the Turkish Football Süper Lig. By examining factors like squad value, player age, running distance, match scheduling, attacking pressure, ball possession, shooting frequency,and passing efficiency, I aim to determine which indicators have the strongest effect on overall league standings. Using data visualization and statistical tools, I will examine match data and financial data, and evaluate whether these factors translate into better performance on the field. My goal is to provide insights into what influences team success in the Turkish Football Super League. 

## Objectives  

1. **Understand Performance Indicators on the Field**  
   - Examine how possession, shots, passing accuracy, penalty box touches, player running distance, and match scheduling influence match outcomes and overall league standings. Explore the relationship between these factors and team success.  

2. **Financial & Squad Age Impact**  
   - Identify whether squad value and team age distribution correlate with league performance.  
     
3. **Identify Key Factors**
   - Identify which indicators have greatest impact on team success.       

4. **Data-Driven Predictions**  
   - Build models with machine learning to have insight about league outcomes based on team statistics.  

5. **Apply Data Science Skills**  
   - Use what I have learned in this course in real life applications and develop my skills in data science.
  
## Motivation  

This project combines my passion for football and data science. Here’s why it matters:  

- **Understanding Variables on the Pitch**
  - Football is my life but it is unpredictable. However, data-driven insights can reveal predictions. 

- **Financial & Tactical Analysis** 
  - Clubs spend millions of money for transfers but is it directly effective on team success? 
  - Does a younger, more energetic team have an advantage over experienced squads?

- **Scheduling & Physical Impact** 
  - Do teams perform worse when playing midweek matches compared to weekends? Is there a relationship between number of fans and success? 
  - Does high running distance correlate with better results?  

I find it very exciting to analyze these and gain insights. I want to predict who might be more successful in the future based on past data.

## Dataset  
### **Match & Performance Data**
- **Ball Possession**
- **Shots per Match**
- **Penalty Box Touches per Match**
- **Player Running Distance per Match** 
- **Match Scheduling** 
- **Squad Value**:  
- **Team Age Distribution**

For data collection, I will use:
- FBref  
- Mackolik
- WhoScored
- Transfermarkt
- Google Trends
- Fixture Data

The dataset will be structured into a match-by-match record, containing key team statistics for each game.  

## Tools and Technologies  

For data analysis and visualization, I will use:  

- **Python** → Data processing & analysis  
- **Pandas** → Data manipulation  
- **Matplotlib & Seaborn** → Data visualization  
- **Scikit-learn** → Machine Learning models  
- **SciPy** → Hypothesis testing & correlation analysis  

## Analysis Plan  

### **Data Collection & Preprocessing**  
- Collect team statistics, squad value, and squad age from FBref, Transfermarkt, Mackolik and other resources, import them DataFrames.  
- Collect running distance and match scheduling data from match reports.  
- Clean the data and standardize numerical fields.  

### **Visualizations and Data Analysis**  
- Create visualizations with using scatter plots, heatmaps, and time series plots to explore relationships between variables.
  
### **Hypothesis Testing**  
-Test hypotheses like: 
 - **H₀:** Squad value, player age, and running distance have no significant effect on team performance.  
 - **Hₐ:** Teams with higher ball possession, higher shots and higher penalty box touches tend to perform better.

## Example Analysis  

To illustrate, I’ll create a scatter plot to visualize the relationship between squad market value and team success. The x-axis will represent squad market value (in millions of euros), and the y-axis will show points won by the team. If there’s a clear upward trend, it might suggest that financially stronger teams tend to win the game more.  

Another example involves comparing team performance on weekday vs. weekend matches. By grouping match outcomes into weekday (Monday–Friday) and weekend (Saturday–Sunday), I can analyze which schedule teams win matches more frequently. If teams consistently perform worse on weekdays, it could indicate that shorter recovery times, fixture congestion, or the number of fans negatively impact results.  

Similarly, I’ll examine the relationship between running distance per match and match success. For example, if teams with higher running distances tend to achieve better results, it might indicate that physical endurance and pressing intensity contribute to winning more games. On the other hand, if there’s no strong correlation, it could suggest that tactical efficiency (e.g., passing accuracy and attacking movements) is more important than pure physical effort.

## Conclusion

By the end of this project, I hope to answer:  

- Does financial strength (squad value) guarantee success?  
- Do teams that dominate possession and passing perform better?
- Are teams that are better at touching ball in the penalty box and taking shots more successful? 
- How does squad age and running distance impact team performance? 
- Do teams struggle more in weekday matches compared to weekends?  
- Can we accurately predict team performance using ML models?

This project will provide valuable football analytics insights while applying data science and machine learning to a real-world problem.I want to analyze past data and predict this year's champion based on the data.



 









