# cli-weather 

**cli-weather** is a command line app to get instant weather data based on city name or postalcode right on the command line.  
Written in python and powered by **WeatherBIT API**, cli-weather also provides detailed weather data on historic and 16 day forecasts basis and not just the temparature.  

With *cli-weather app* you can retrieve current weather observations from over **45,000** live weather stations using WeatherBIT API, and highly localized weather forecasts for any point on the globe using the world's most trusted weather models!

You can look up weather data by many methods including:   
- By entering city_name    
- By entering postal_code  

## Installation

```
pip install cli-weather
```

## Usage

```
cli-weather command [-h] [-c COUNTRY] [-u UNITS] [-d] city_name/postal_code
```

|Command         | Description                   |
|----------------|-------------------------------|
|city            | Get weather by city name      |
|postalcode      | Get weather by postal code    |

|Option          | Description                   |
|----------------|-------------------------------|
|-c, --country   | Country of entered area       |
|-u, --units     | Metric, Scientific, Farenheit |
|-d, --detailed  | Display detailed weather data |
|-h, --help      | Show this message and exit    |

## Data sources

* [weatherbit.io](https://weatherbit.io/)

## Dependencies

* [requests](http://docs.python-requests.org/en/latest/) >= 2.4

## Try without using pip

```
Fork this repository
$ git clone "https://github.com/username/cli-weather"
$ cd cli_weather
$ pip install requests
$ python main.py [command] [options]

```

## License

GNU General Public License v3.0

**ver 0.1.2**

3 - Alpha Test Release
- Python2 and Python3 compatible
- Introduction of wheel distribution in binary
- Minor bug fixes in setup.py
 

**ver 0.1.1**  

3 - Alpha Test Release
- Minor bug fixes in setup.py
- Doc update in PyPIDocumentation.md

**ver 0.1.0**  

3 - Alpha Test Release
- Get weather by city
- Get weather by postalcode
- Change units according as you wish [Metric/Scientific/Farenheit]
- Only temparature by default, detailed information from snowfall to solar radiation using -d
