# Airline Data Analysis
___

![aeroplane_photo](airline_photo.jpg)

## Description/Background
The airline data holds immense importance, as it offers insights into the functioning and efficiency of the aviation industry. It provides valuable information about flight routes, schedules, passenger demographics, and preferences, which airlines can leverage to optimize their operations and enhance customer experiences. 

By analyzing data on delays, cancellations, and on-time performance, airlines can identify trends and implement strategies to improve punctuality and mitigate disruptions. Moreover, regulatory bodies and policymakers rely on this data to ensure safety standards, enforce regulations, and make informed decisions regarding aviation policies. 

Researchers and analysts use airline data to study market trends, assess environmental impacts, and develop strategies for sustainable growth within the industry.

## Table of Contents
___
- [Description/Background](#description/background)
- [About the dataset](#about-the-dataset)
- [Dataset Glossary](#dataset-glossary)
- [Technologies](#technologies)
- [Data Sources](#data-sources)
- [Usage Instructions](#usage-instructions)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Data Analysis](#data-analysis)
- [Results and Discussions](#results-and-discussions)
- [Recommendations](#recommendations)
- [References](#references)
- [License](#license)

## About the dataset
___
This dataset comprises diverse parameters relating to airline operations on a global scale. The dataset prominently incorporates fields such as Passenger ID, First Name, Last Name, Gender, Age, Nationality, Airport Name, Airport Country Code, Country Name, Airport Continent, Continents, Departure Date, Arrival Airport, Pilot Name, and Flight Status. 

These columns collectively provide comprehensive insights into passenger demographics, travel details, flight routes, crew information, and flight statuses. Researchers and industry experts can leverage this dataset to analyze trends in passenger behavior, optimize travel experiences, evaluate pilot performance, and enhance overall flight operations.

## Dataset Glossary
___
| Column | Description |
|--------|-------------|
| Passenger ID | Unique identifier for each passenger |  
First Name | First name of the passenger  
Last Name | Last name of the passenger  
Gender | Gender of the passenger  
Age | Age of the passenger  
Nationality | Nationality of the passenger  
Airport Name | Name of the airport where the passenger boarded  
Airport Country Code | Country code of the airport's location  
Country Name | Name of the country the airport is located in  
Airport Continent | Continent where the airport is situated  
Continents | Continents involved in the flight route  
Departure Date | Date when the flight departed  
Arrival Airport | Destination airport of the flight  
Pilot Name | Name of the pilot operating the flight  
Flight Status | Current status of the flight (e.g., on-time, delayed, canceled)  

## Technologies
___
* PostgreSQL (for data cleaning, analysis, and visualisation)
* MS Excel (for data visualisation)  

## Data Sources
___
Dataset was collected from a reputable airline database, showing details of flights from January to December 2022.  

## Usage Instructions
___
- Data analysis can be performed on any preferred Database Management System. However, the queries in this project was written in PostgreSQL. Take note of syntax.
- Download dataset file from this project repository into local machine. 
- On windows machine, enter ``` Windows + E ``` and paste the file path ```C:/ProgramData/MySQL/MySQL Server 8.0/Uploads``` on the file address to go into 'Uploads' folder.
- While in the 'Uploads' folder, create a folder named 'input_files' and copy the downloaded dataset files into this folder 
> [!CAUTION]
> You must perform all the steps above before running the SQL script.
- Open the "airline_data_analysis_queries.sql" file on your Database Management System and run the script. This should automatically create a database and table, and import the dataset into the table.
> [!WARNING]
> Run each block of code individually for better experience.

## Data Cleaning and Preprocessing
___
* Over 800 records with invalid 'arrival_airport' code were deleted

## Data Analysis
___

### **1. Airports with the most travels**


### **Discussion and Recommendation**  
* Böblingen Flugfeld airport, Germany was the most frequently travelled airport (36 passenger flights).
This airport may require additional flights or larger aircraft to cater to the rising demand and
increase revenue. They may also require more staff and improved processes to manage potential traffic

### **1. Airports with the most travels**  



### **Discussion and Recommendation**

__  
### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  

### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  
### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  

### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  
### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  

### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  

### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  

### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  

### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  

### **1. Airports with the most travels**



### **Discussion and Recommendation**

__  
