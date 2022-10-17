# Data Visualization with PyViz

This repo utilizes data aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For cleaning and filtering the data.

* [hvplot](https://github.com/holoviz/hvplot) - For plotting our data using HoloViews. 

* [Path](https://github.com/jaraco/path) - For reading in our DataFrames. 

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  conda install -c pyviz hvplot geoviews
```

## Usage

To use the data visualization application, simply clone the repository and create a new_folder to save your **san_francisco_housing.ipynb** . Navigate to that folder within your terminal, and type the following :

```new_folder
   jupyter lab 
```

---

Upon launching the data visualization application, you will be able to view an interactive line + GeoViews plot, which allows users to visualize the gross rent of each neighborhood. 

<img width="1440" alt="Screen Shot 2022-10-16 at 11 35 02 AM" src="https://user-images.githubusercontent.com/105071493/196052129-0deeb2b3-eafe-4d5e-82fd-7ad1eeee16ad.png">

<img width="1440" alt="Screen Shot 2022-10-16 at 11 34 20 AM" src="https://user-images.githubusercontent.com/105071493/196052132-38d2001b-74b6-4599-ad67-4c2d3dda6f30.png">

---

## Contributors

Name: Sterling Davis 
Email: sterlingdayvis@gmail.com
LinkedIn: www.linkedin.com/in/sterlingdavis1

---

## License

MIT
