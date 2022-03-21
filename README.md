# Exploring Landsat data in Google Earth Engine
Geoscience workshop for exploring Landsat data via GEE with python

## Workshop Resources
 - Google Earth Engine (GEE) - create an account for non-commercial purposes here: [GoogleEarthEngine](https://earthengine.google.com/)
 - Data - Supplied to you on the GEE site!

## Workshop Goals
By the end of this workshop, you will be able to:
- be familiar with data from the Landsat 8/9 satellites
- create a python environment for visualizinga and analyzing geospatial data
- leverage Google Earth Engine for working with geospatial data

## Outline
- [What is GEE?](#gee)
- [Landsat 8/9 overview](#landsat)
- [Exploring Landsat data](#streamlit)
- [Python library for GEE](#geemap)
- Anaconda conda miniconda
- Jupyter notebook for GEE and Landsat


## <a name="gee"></a>  What is Google Earth Engine?

It's a planetary-scale platform for doing data science. Google Earth Engine allows users to run algorithms on georeferenced imagery and vectors stored on Google's infrastructure. Instead of being just an observer, you have the ability to conduct spatial analysis on the global datasets found in Earth Engine's data catalog. You can also load your own data for your projects, or even submit a request a particular dataset you'd like Earth Engine to host.

What's on offer:

![data computation A P I applications graphic](imagesEngine/EngineOfferings.JPG)

The [Google Earth Engine Homepage](https://developers.google.com/earth-engine) is where you can launch into this adventure and find all kinds of resources, but this tutorial, based on the excellent work by Qiusheng Wu (Twitter: @giswqs), is a decent place to start if you are more interested in using python over javascript, the default for GEE.

You have to apply to have one (and only one) Google account approved for access. Do read the [Terms of Service](https://earthengine.google.com/terms/) carefully.

NOTE: *This tutorial is in the context of nonprofit, research, and education use. Commercial applications of Google Earth Engine require a paid commercial license.*

A good place for more orientation: https://earthengine.google.com/faq/

And once you sign up, you'll have access to the code editor shown above where you can follow along with the excellent [Javascript Starting Guide](https://developers.google.com/earth-engine/guides/getstarted). (Python installs are an option as well, but the guide examples are mainly Javascript.) 

## <a name="Landsat"></a> The Landsat 8 & 9 satellites

Exciting news is Landsat 9 came on line and started distribtuing data in February 2022!!!

Landsat 9 sensors are very similar to Landsat 8, but improved in data quality. 

Here are the bands on both satellites:
- Band 1 Coastal Aerosol (0.43 - 0.45 µm) 30 m
- Band 2 Blue (0.450 - 0.51 µm) 30 m
- Band 3 Green (0.53 - 0.59 µm) 30 m
- Band 4 Red (0.64 - 0.67 µm) 30 m
- Band 5 Near-Infrared (0.85 - 0.88 µm) 30 m
- Band 6 SWIR 1(1.57 - 1.65 µm) 30 m
- Band 7 SWIR 2 (2.11 - 2.29 µm) 30 m
- Band 8 Panchromatic (PAN) (0.50 - 0.68 µm) 15 m
- Band 9 Cirrus (1.36 - 1.38 µm) 30 m

The electromagnetic spectrum

<p cnter
   img src
that
</p>

Image source: [seos-project.eu](https://www.seos-project.eu/remotesensing/remotesensing-c00-p01.html) / Albertz 2007 with modifications

## <a name="streamlit"></a> Exploring Landsat data

## <a name="geemap"></a> The geemap python library

Qiusheng Wu built the python library *geemap* that creates a visual interface for GEE when using python - something that was lacking until *geemap* came along. There are many MANY resources at [geemap.org](https://geemap.org/) if you want to dig into more detailed tutorials on Qiusheng's YouTube channel after this brief foray into GEE and Landsat data.
