# US-medical-insurance-cost
In this project, I will investigate a csv file with medical insurance costs using Python fundamentals. It is my hope that with this project I will analyze various attributes within insurance.csv to learn more about the patient information in the file and gain insight into potential use cases for the dataset.

Next, I decide to look through insurance.csv and acquaint myself with the data. Things I look for are the following:

The names of columns and rows
Any noticeable missing data
Types of values (numerical vs. categorical)

I decided to analyze the following attributes:
- Find out the average age of the patients in the dataset.
- Number of men vs. women counted in the dataset
- Analyze where majority of the individuals are from.
- Look at the different costs between smokers vs. non-smokers.
- Creating a dictionary that contains all patient information

To perform these inspections, I have built out a class called PatientsInfo which contains fives methods:

- analyze_ages()
- analyze_sexes()
- maximum_regions()
- smokers_charges()
- create_dictionary()
