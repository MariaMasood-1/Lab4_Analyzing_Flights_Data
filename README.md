# Lab5: Analyzing Flights Data

This lab focusses on extracting, exploring, manipulating and analyzing flights data available on [OpenFlights project](https://openflights.org/). Most the flights data regarding the Airport ID, name, city, country, latitude, longitude, etc are stored in multiple files. We have used two datasets namely airports.dat and routes.dat. For extracting the latitude and longitude information, airports.dat is used and for extracting the source and setination unique airport ids, routes.dat is used. A list is created that stores the routes distance values of all the possible routes available in the data using Haversine formula to calculate the orthodromic distance is the shortest distance between two points on a sphere (or the surface of Earth). Using the list of routes distances, a histogram is created that shows the distribution of different flight distances. <br>

![Distribution of flight distances](https://user-images.githubusercontent.com/76536418/118193078-28fe4f00-b415-11eb-9be0-147069f21866.png)

<br>

## Libraries used:
<br>

### **Numpy:** <br>
NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. <br>

### **Matplotlib:** <br>
Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It is a comprehensive library for creating static, animated, and interactive visualizations in Python<br>

### **CSV:** <br>
The csv library provides functionality to both read from and write to CSV files. Designed to work out of the box with Excel-generated CSV files, it is easily adapted to work with a variety of CSV formats. The csv library contains objects and other code to read, write, and process data from and to CSV files.<br>
