# Unemployment-Analysis-with-Python<br>
Step 1: Bring in the library<br> 

 Pandas is used to manipulate data.<br> 
 Seaborn and matplotlib are used for visualization.<br> 

 Step 2: Open the dataset and investigate it<br> 
 The CSV is read into a DataFrame df by this line.<br> 

 df.columns = ['State', 'Date', 'Frequency', 'Estimated Unemployment Rate (%)', 'Estimated Employed', 'Estimated Labour Participation Rate (%)', 'Region'] <br> 
 
 step 3: Clean the data<br> 

 Step 4: Use print(df.isnull()) to check for missing values. sum()<br> 

 Data Preparation (Convert 'Date' to datetime) is step five.<br> 
 The 'Date' column is converted to the appropriate datetime format for time-series analysis.<br> 

 Step 6: The Nationwide Unemployment Rate Over Time<br> 
 demonstrates the variations in the unemployment rate over time, both in months and years.<br> 
 Keep an eye out for rises during the COVID-19 timeframe, 2020–2021.<br> 
 
 Step 7: Regional Unemployment<br> 
 
 Step 8: State-by-State Average Unemployment Rate<br> 
 
 Step 9: Monthly Patterns (Aggregation Option)<br> 

 See the patterns in unemployment<br> 
 Make observations<br> 

✅ Final Output: Key Insights<br>

The unemployment rate spiked significantly during the COVID-19 lockdown.<br>
Some states and regions were more affected than others.<br>
After mid-2021, the rate started to decline, indicating recovery.<br>
