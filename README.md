# Weather Monitoring
![Screenshot 2024-10-19 122542](https://github.com/user-attachments/assets/97dede00-d613-4b5c-8f93-b1d45a50b010)
# Overview
The Real-Time Weather Monitoring System uses the OpenWeatherMap API to continuously track weather conditions, providing real-time data on temperature, humidity, and wind speed. Users can switch between Celsius, Fahrenheit, or Kelvin for temperature display. The system generates daily weather summaries, including average, minimum, and maximum temperatures, and visualizes a 5-day forecast through an intuitive 5-shade section. It also triggers alerts for extreme weather conditions based on user-defined thresholds.

![Screenshot 2024-10-19 134149](https://github.com/user-attachments/assets/8d0aec8c-0f7b-4db4-be22-1f96a293dfac)
Real-Time Weather Monitoring System uses the OpenWeatherMap API to continuously track weather conditions, providing real-time data on temperature, humidity, and wind speed.

![Screenshot 2024-10-19 125737](https://github.com/user-attachments/assets/c6fbc757-f541-445b-a634-f77ec4967641)
![Screenshot 2024-10-19 125945](https://github.com/user-attachments/assets/e5c4808e-305f-41e0-884a-aff77ee0d876)
# Weather Metrics:
* Humidity: Displayed as a percentage (%)
* Wind Speed: Shown in kilometers per hour (km/h)
* Temperature Units: Switchable between Celsius, Fahrenheit, and Kelvin.

# Weather Summaries:
* Average Daily Temperature
* Minimum and Maximum Temperatures of the Day
* Dominant Weather Condition (e.g., Clear, Rain, Snow)


![Screenshot 2024-10-19 125802](https://github.com/user-attachments/assets/ca6c7cda-d102-4da2-9887-3e742d1b0131)

# 5-Day Weather Forecast:
Comprehensive weather predictions visualized through a 5-shade section for easy understanding of trends over the coming days.

![Screenshot 2024-10-19 134210](https://github.com/user-attachments/assets/2bdf5a23-6fe5-45ca-9322-e6e257121953)

# Installation Steps

**Clone the Repository**:
   ```bash
   git clone https://github.com/SreerangamKushalKumar/weather-monitoring-system.git
-------

# Install Dependencies: Navigate to the project directory and install the necessary packages:

```bash
cd weather-monitoring-system
npm install

# Environment Variables: Create a .env file in the root directory and add the following details:
API_KEY=your_openweathermap_api_key
DATABASE_URL=your_database_url
INTERVAL=300000 # (5 minutes in milliseconds)

# Run the Application: Start the system using the following command:
npm

# Run in Python (Optional):

python

# Usages:
 - Search for any city using the search bar.
   -Select the desired temperature unit (Celsius/Fahrenheit/Kelvin) from the dropdown menu.
     - View the current weather conditions, along with a five-day forecast.

# Running Tests:
You can add and run tests to ensure everything is working correctly.

