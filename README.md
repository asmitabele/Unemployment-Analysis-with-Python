# Unemployment-Analysis-with-Python<br>

step1 : Import libraries<br>

pandas is used for data manipulation.
matplotlib and seaborn are used for visualization.<br>

step 2: Load and explore the dataset<br>
This line reads the CSV into a DataFrame df.<br>

step3 : Clean the data<br>
df.columns = ['State', 'Date', 'Frequency', 'Estimated Unemployment Rate (%)',
              'Estimated Employed', 'Estimated Labour Participation Rate (%)', 'Region']

step4 : Check missing values<br>
print(df.isnull().sum())<br>

Step 5: Data Preparation (Convert 'Date' to datetime)<br>
Converts the 'Date' column to proper datetime format for time-series analysis.<br>

Step 6: Unemployment Rate Over Time (Nationwide)<br>
Shows how the unemployment rate changed over months and years.<br>
Look for spikes during 2020-2021 (COVID period).

Step 7: Unemployment by Region<br>
Step 8: Average Unemployment Rate per State<br>
Step 9: Monthly Trends (Optional Aggregation)<br>

Visualize unemployment trends<br>
Draw insights<br>

✅ Final Output: Key Insights<br>

The unemployment rate spiked significantly during the COVID-19 lockdown.<br>
Some states and regions were more affected than others.<br>
After mid-2021, the rate started to decline, indicating recovery.<br>
