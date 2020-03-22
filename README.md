# Python-API-Weather
This program uses API calls and the Pandas library to analyze global weather patterns by latitude.

In this program, latitude is the independent variable, a variety of weather phenomena are evaluated as potential dependent variables, and cities are the units of analysis. The program assembles a representative list of cities across the world by generating sets of random coordinate pairs and using the [Citipy](https://pypi.org/project/citipy/) library to find a city near each pair. The program matches each city to its weather statistics by making calls to the [Openweathermap](https://openweathermap.org/api) API. Finally, the program organizes and plots the data using Pandas and Matplotlib. The program is built using a Jupyter notebook.

Analysis of the program's output yields a few key findings. First, mean temperatures are highest in cities that are closer to the equator. Second, cities with low humidity are concentrated in the middle latitudes. And third, wind speed and cloudiness have a relatively uniform distribution at all latitudes. Included below are a few of the program's graphic outputs:

/

![Image of Temperature Graph Code](images/Lat_Temp_Graph.png)![Image of Humidity Graph Code](images/Lat_Hum_Graph.png)
