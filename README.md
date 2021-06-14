# Python-API-Weather
This program uses API calls and the Pandas library to analyze global weather patterns.

Technologies Used: Python, Pandas, MatPlotLib, Jupyter Notebook, Citipy Library, Openweathermap API

In this program, latitude is analyzed as an independent variable, several weather variables are evaluated as potential dependent variables, and cities are used as units of analysis. First, the program assembles a list of cities around the world by generating random coordinate pairs and using the [Citipy](https://pypi.org/project/citipy/) library to find a city near each pair. Next, it loads weather statistics for each of the cities by making calls to the [OpenWeatherMap](https://openweathermap.org/api) API. Finally, it organizes and plots the data using the [Pandas](https://pandas.pydata.org/) and [Matplotlib](https://matplotlib.org/index.html) libraries. The program is built using a [Jupyter](https://jupyter.org/) notebook.

Analysis of the program's output yields a few key findings. First, average temperatures tend to be higher in cities that are closer to the equator. Second, cities located in the middle latitudes tend to exhibit lower levels of humidity. And third, both wind speed and cloudiness have a relatively uniform distribution across all latitudes. Included below are a few of the program's graphic outputs:

/

![Image of Temperature Graph Code](images/Lat_Temp_Graph.png)![Image of Humidity Graph Code](images/Lat_Hum_Graph.png)
