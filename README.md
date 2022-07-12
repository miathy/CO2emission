# CO2emission
In this assignment, you will perform some exploratory data analysis on a dataset of worldwide carbon dioxide and greenhouse gas emissions in the year 2016.

Download the dataset file carbon.csv. It is a plain text file that can be opened in any text editor, although for ease of understanding the data you can also open it in a spreadsheet application. The dataset contains the CO2 emission records of 151 countries. All records are stored as comma-separated values, one record per line. First line in the file holds column headers which are described below:

country

Country name.

co2

Annual emissions of carbon dioxide, measured in million tonnes.

coal_co2, cement_co2, flaring_co2, gas_co2, oil_co2, other_industry_co2

Annual emissions of CO2 in million tonnes from cement production, flaring, gas production, oil production and from other industries respectively. All these factors add up to co2 column value.

total_ghg

Total greenhouse gas emissions measured in CO2-equivalent million tonnes.
(Some countries have a negative value, which could be due to anomalous data, or the country being carbon negative.)

methane, nitrous_oxide

Methane and nitrous oxide emissions respectively, measured in CO2-equivalent million tonnes. Note that these factors do NOT add up to total_ghg value.

population

Population estimate of the country.

gdp

Gross domestic product of the country (dollars).

energy_consumption

Annual energy consumption, measured in TeraWatt-hours.

As your program starts, it should prompt the user for the dataset file name and load its data into memory in appropriate data structures (lists, tuples, dictionaries etc.). Next, your program should present the user with a main menu containing these options:

(1) CO2 emissions breakdown: For a user-selected country, calculate the per-capita CO2 emissions and its components (coal, cement, gas etc.). Display the results in kilograms per person (1 million tonne equates to 109 kilograms). Also show the CO2 component breakdown as a pie chart. Note that all components are not present for each country — some columns may be empty. You should only show the CO2 components that are present.

(2) Maximum emissions per GDP: Work out and display the country which had the highest total-GHG (greenhouse gas) emissions per dollar of GDP.

(3) Top 10 GHG countries: For the user-selected greenhouse gas (methane, nitrous oxide, total), work out the top ten countries according to per capita gas emissions. Show their emission values in the form of a bar chart.

(4) Energy consumption distribution: Calculate the per capita energy consumption of all countries in kWh units (1 TerraWatt-hour = 106 kiloWatt-hour). Show the energy consumption values in the form of a box chart.

(5) Exit the program

