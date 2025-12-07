# ETL and Time-Series Analysis on Electricity Daily Load Dataset

## 📘 Project Overview
This project focuses on performing **Extraction, Transformation, Loading (ETL)** and **Time-Series Analysis** on Delhi’s electricity load data.  
The dataset consists of thousands of daily CSV files (each containing 15-minute records), a historical load archive, and hourly weather data.  

The objectives of this project are to:  
- Merge fragmented daily load files into a single clean dataset  
- Fix timestamps, missing values, and structural inconsistencies  
- Join electricity load data with weather data  
- Generate insights into demand patterns, peak hours, weekday–weekend behavior, and weather–load relationships  

---

## 🎯 Project Objective
The primary goal of this project is to build a **reliable, analysis-ready time-series dataset** from raw electricity load files and derive meaningful insights into Delhi’s power consumption patterns.  

Key steps include:  
- Extracting daily load CSVs from the repository  
- Transforming unstructured or inconsistent data into a uniform format  
- Creating continuous timestamps  
- Merging weather data for richer analysis  
- Performing exploratory time-series analysis to understand trends, peaks, and external influences  

---

## 🧰 Tech Stack & Libraries
- **Python 3**  
- **NumPy**  
- **Pandas**  
- **Matplotlib** & **Seaborn**  
- **zipfile**, **requests**, **BytesIO**, **os**, **tqdm**  
- **Jupyter Notebook**
