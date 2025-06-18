# Uber-Data-Analysis
🚕 Uber Data Analysis
Duration: June 2024 – July 2024
Tools: Jupyter Notebook, VS Code, Git
Languages & Libraries: Python (Pandas, NumPy, Matplotlib, Seaborn)

📌 Project Overview
This project explores a dataset of Uber rides. The aim is to clean the data, visualize trip trends, and answer key business questions such as peak booking times, ride distances, and usage patterns by day/month.

🧹 1. Data Preprocessing
Loaded the dataset using pandas

Checked for missing values and filled or removed them

Converted START_DATE and END_DATE columns to datetime format

Created new columns like hour, day-night, and month for further analysis

📊 2. Data Visualization
Used Seaborn and Matplotlib for visualizing:

Ride categories (Business, Personal, etc.)

Purpose of trips

Time of day rides were booked (Morning, Afternoon, Evening, Night)

Monthly ride volume

Weekly ride distribution

Miles traveled per ride

❓ 3. Questions Answered
Q1: What time do people book cabs the most from Uber?
Evening was the most frequent time slot for bookings, as seen in the day-night column plot.

Q2: In which months do people book Uber rides less frequently?
Ride frequency dropped significantly in January and December, likely due to holidays or weather.

Q3: On which days of the week are Uber rides booked the most?
The analysis shows peak bookings on Thursdays and Fridays, suggesting business travel patterns.

Q4: How many miles do people usually book a cab for through Uber?
Most rides were around 4 to 10 miles, with a few long-distance outliers.