## An Investigation into Global Climate Variables and the Determinants of Global Warming

### Table of Contents

### 1. Intended use

The aim of this project is to conduct an investigation into the key determinants of global warming, with a focus on global climate variables.

### 2. Mathematica Installation

#### Introduction

Mathematica is a computing system which is favoured across many disciplines from geo-spatial mapping to general relativity for its excellence in data science, visualisation and image processing. It is a high-level programming language, making prototyping solutions to a variety of problems straight-forward.

#### General User

The general user can download Mathematica through... However, the license cost approximately €3,550.

#### Student License

UCD students (and staff) are able to access Mathematica for free through the Software Download page of [UCD Connect](https://www.ucd.ie/connect/).


### 3. Data 📊 📈

#### Temperature Data 🌡️ ❄️ 🔥

The [temperature data ](https://www.metoffice.gov.uk/hadobs/hadcrut5/data/current/download.html )
obtained from Met Office Hadley Centre observations datasets, where we downloaded 3 files:

1. HadCRUT5 analysis time series: ensemble means and uncertainties: Summary Series Global Monthly NetCDF;
2. HadCRUT5 analysis time series: ensemble members: Ensemble Series Global Monthly NetCDF;
3. HadCRUT5 analysis gridded data: additional fields: Ensemble mean NetCDF.

![image](https://user-images.githubusercontent.com/60405870/181915878-c8c1037c-0570-4d1c-9007-99b6ca751970.png)

![image](https://user-images.githubusercontent.com/60405870/181915981-1f0f87f2-8767-49b3-8359-50ffc74eacb2.png)


#### Precipitation Data ☔ 🌀 ⛈️

The [precipitation data](https://downloads.psl.noaa.gov/Datasets/ghcngridded/)
is available through the National Oceanic and Atmospheric Administration Physical Sciences
Laboratory, and is produced under the Global Historical Climatology Network. 
The associated dataset is the Precipitation Anomaly Dataset

![image](https://user-images.githubusercontent.com/60405870/181916247-9e4269f5-2747-4bd1-8157-8f12b6bc42c7.png)


#### Carbon Dioxide (CO$_2$) ✈️ 🚛 🏭  

Carbon dioxide data is freely available through the Global Monitoring Laboratory (GML) of the National Oceanic and Atmospheric Association (NOAA). The initial lines within each dataset contain meta-data on usage. The [CO2](https://gml.noaa.gov/aftp/products/trends/co2/) directory contains 

From here, we have made use of the three files:

1. Estimated CO2 Daily Global Seasonal Cycle and Trend (ppm)

* file name co2_trend_gl.csv

* file size 112K

* last modified upon download 

2. CO$_2$ Global Annual Mean Estimates at Mauna Loa, Hawaii.

* file name co2_annmean_mlo.csv

* file size 3.7K

* last modified upon download 11th July 2022

3. CO$_2$ Global Monthly Estimates at Mauna Loa, Hawaii.

* file name co2_mm_mlo.csv

* file size 36K

* last modified upon download 11th July 2022

### 4. Running the notebook 🏃‍♀️ 🖥️ 

To run the notebook, download the notebook ACM40960.nb along with all prescribed data-sets into the same folder as the Mathematica noteboo. The Mathematica homepage

![image](https://user-images.githubusercontent.com/60405870/181854711-00dee655-c37b-4269-975c-086cbe729d64.png)

Open the Mathematica document. We recommend the user evaluate notebook before expanding sections, which takes approximately 2 minutes 24 seconds. The Evaluate Notebook option is included under the the evaluation tab.

![image](https://user-images.githubusercontent.com/60405870/181855350-fdfb1e80-435b-4ee1-be20-a5cf0ba6ca86.png)

The notebook is organised into six sections across 
1. Importing Data;
2. Data Cleaning;
3. Overview Plots;
4. Norway and Libya Case Studies;
5. Linear Modelling;
6. Carbon Dioxide.

Sections can be expanded in a few different ways. By clicking the section expansion the section is opened.

![image](https://user-images.githubusercontent.com/60405870/181856130-0f6416f1-38af-4561-b0b7-a55e557fe29c.png)

The user can also choose to use the keyborad shortcut cmd + ' or ctrl + ' on a mac or windows system.

### Authors 🚺 👩‍🔬

 
Eilish Clune & Megan Farrell (21208251, 16310126).

