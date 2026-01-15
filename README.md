# weather-etl-pipeline
# 🌦️ Global Weather ETL Pipeline

An automated data engineering pipeline built in Python that extracts real-time weather data, transforms it for analysis, and loads it into structured storage.

## 🚀 Project Overview
This project demonstrates a production-ready **ETL (Extract, Transform, Load)** workflow. Instead of manual data collection, it uses a Python-based "Robot" (Class-based architecture) to communicate with the OpenWeatherMap API and generate clean datasets automatically.

## 🛠️ Features
- **API Integration:** Connects to OpenWeatherMap REST API using secure API keys.
- **Object-Oriented Design:** Built using a Python `class` for high reusability and clean code.
- **Data Transformation:** Uses `Pandas` to turn messy JSON data into clean, structured tables.
- **Automated Loading:** Saves processed data into a `.csv` format ready for Data Analysts to use in Excel, PowerBI, or Tableau.

## 📋 The ETL Process
1. **Extract:** Requests current weather (temp, humidity, conditions) for a list of global cities.
2. **Transform:** Adds timestamps, cleans nested JSON fields, and handles data formatting.
3. **Load:** Exports the finalized dataset to `final_report.csv`.

## 💻 Tech Stack
* **Language:** Python 3.x
* **Libraries:** * `Requests`: For API communication.
    * `Pandas`: For data manipulation and structuring.
    * `Datetime`: For time-stamping records.

## 📖 How to Run
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install pandas requests
