# Weather-app-CLI-Project


## Description
This Python script allows you to retrieve weather and temperature information for a specified city using the OpenWeatherMap API. You can choose to display the temperature in either metric or imperial units. The script also provides colorful weather symbols based on the current weather conditions.

## Prerequisites
Before using this script, you need to have the following prerequisites in place:

1. **Python 3.x:** Ensure that you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. **API Key:** You will need an API key from OpenWeatherMap to access their weather data. You can obtain one by signing up on the [OpenWeatherMap website](https://openweathermap.org/api) and following their instructions.

## Installation
1. Clone this GitHub repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/your-weather-project.git
   ```

2. Create a `secrets.ini` file in the project directory and add your OpenWeatherMap API key as follows:
   ```ini
   [openweather]
   api_key = YOUR_API_KEY_HERE
   ```

3. Install the required dependencies using pip:
   ```bash
   pip install configparser requests argparse
   ```

## Usage
To use the script, follow these steps:

1. Open your terminal/command prompt.

2. Navigate to the project directory:
   ```bash
   cd your-weather-project
   ```

3. Run the script with the following command:
   ```bash
   python weather.py CITY_NAME [OPTIONS]
   ```

   Replace `CITY_NAME` with the name of the city for which you want to retrieve weather information.

   Available options:
   - `-i, --imperial`: Display temperature in imperial units (Fahrenheit). This option is optional.

4. The script will fetch and display weather information for the specified city, including weather symbols and temperature.

## Example
Here is an example of how to use the script to get weather information for New York City in imperial units:
```bash
python weather.py New York -i
```

## Author
- Aswin R
- GitHub: https://github.com/AshCoder07


## Acknowledgments
- OpenWeatherMap for providing the weather data API.
- Python community for their excellent libraries and resources.
