# WeatherPy and VacationPy API Challenge

**Title:** Exploring Weather Patterns and Vacation Destinations with Python and APIs

This repository contains three Python projects: WeatherPy, VacationPy, and Vacation_starter_solved.

## WeatherPy

WeatherPy is a Python project that analyzes weather data for various cities around the world. It collects weather information using the OpenWeatherMap API (https://openweathermap.org/api), performs data analysis, and visualizes the results.

## VacationPy

VacationPy is a Python project that utilizes weather data collected in WeatherPy to identify ideal vacation spots. It incorporates data from OpenWeatherMap and Geoapify API to find hotels near cities with optimal weather conditions.

## [VacationPy_starter_solved](#vacationpy_starter_solved)

VacationPy_starter_solved is a Python project that utilizes a provided cities.csv data renamed as cities_starter.csv to identify ideal vacation spots. It incorporates data from OpenWeatherMap and Geoapify API to find hotels near cities with optimal weather conditions.

## Table of Contents
- [Prerequisites](#prerequisites)
- [WeatherPy](#weatherpy)
- [VacationPy](#vacationpy)
- [VacationPy_starter_solved](#vacationpy_starter_solved)
- [License](#license)
- [Code Source](#code-source)
- [References](#references)
- [Author](#author)
- [Findings](#findings)

## Prerequisites

Before running the Python scripts, make sure you have the following installed on your system:
- **Python:** The scripts are written in Python, and you need the Python interpreter to execute them.
- **Jupyter Notebook:** The scripts are presented in Jupyter Notebooks. You can install Jupyter Notebook using the recommended method for your operating system.
- **Git:** If you plan to clone the repository and manage versions using Git, make sure Git is installed on your machine.
- **API Keys:** Obtain API keys for the required services (OpenWeatherMap and Geoapify) and store them in a file named `api_keys.py` in the same directory as the scripts.
- **Citipy:** Citipy is used for working with city data based on latitude and longitude. Install Citipy using the following command: `!pip install citipy`

**API Keys:**
You will need API keys for the following services:
- **OpenWeatherMap API:** Get your API key by creating an account on the OpenWeatherMap website.
- **Geoapify API:** Sign up for a Geoapify account to obtain the API key.

**Note:** Ensure that the required CSV files ("cities.csv," "cities_starter.csv") are available in the same directory as the Jupyter Notebooks.

Install the required dependencies:
Obtain an API key from Geoapify and replace 'YOUR_API_KEY' in the VacationPy/config.py file with your key.

Please follow the provided links to install the necessary software and obtain API keys.

**How to Use the Jupyter Notebook**
1. Clone this repository to your local machine or download the Jupyter Notebook file and CSV files.
2. Ensure you have the required CSV files (cities.csv and cities_starter.csv) in the same directory as the Jupyter Notebook file, or update the file paths in the notebook to specify the correct locations.
3. Open a terminal or command prompt and navigate to the directory containing the Jupyter Notebook file.
4. Run the Jupyter Notebook to execute it interactively.

---

## WeatherPy

### Features
- Retrieves weather data for a list of cities using OpenWeatherMap API.
- Performs data analysis on temperature, humidity, cloudiness, and wind speed.
- Generates scatter plots and linear regression plots to visualize relationships between weather variables.
- Creates a CSV file containing the weather data as "cities.csv".

**Usage**
Follow the instructions in the WeatherPy Jupyter notebook to execute the code cells and generate weather analysis and visualizations.

## VacationPy

### Features
- Uses weather data from WeatherPy to identify cities with ideal vacation weather.
- Retrieves hotel information using Geoapify API.
- Creates a map plot with hotel locations using holoviews and hvplot.

**Usage**
Run the Jupyter notebook.

**Code Source**
The code source can be found here: [GitHub Repository](https://github.com/AnyasorG/python-api-challenge)

## [VacationPy_starter_solved](#vacationpy_starter_solved)
### Features
- Uses provide weather data from WeatherPy as cities_starter.csv to identify cities with ideal vacation weather.
- Retrieves hotel information using Geoapify API.
- Creates a map plot with hotel locations using holoviews and hvplot.

**Usage**
Run the Jupyter notebook.

**Code Source**
The code source can be found here: [GitHub Repository](https://github.com/AnyasorG/python-api-challenge)

## License
This project is open-source and is made available under the terms of the MIT License. The MIT License is a permissive open-source license that allows you to use, modify, and distribute this software for your own purposes. For the full details of the MIT License, please refer to [MIT License](https://choosealicense.com/licenses/mit/).

## Author
Godswill Anyasor

## Findings
The findings are documented with the Jupyter notes WeatherPy.ipynb, VacationPy.ipynb, and Vacation_starter_code.ipynb.

- Fig1. City Max Latitude vs. Max Temperature (2022-10-18)
- Fig 2. City Latitude vs. Humidity (2022-10-18)
- Fig 3. City Latitude vs. Cloudiness (2022-10-18)
- Fig 4. City Latitude vs. Wind Speed (2022-10-18)

Data is located at [GitHub Repository](https://github.com/AnyasorG/python-api-challenge.git).

## References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
- [Python](https://www.python.org/): Official Python website.
- [CSV Module Documentation](https://docs.python.org/3/library/csv.html): Python documentation on working with CSV files.
