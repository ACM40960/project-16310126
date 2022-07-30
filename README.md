## An Investigation into Global Climate Variables and the Determinants of Global Warming


### 1. Intended Use 

The aim of this project is to conduct an investigation into the key determinants of global warming, with a focus on global climate variables.

###  2. Mathematica Installation

#### Introduction

Mathematica is a computing system which is favoured across many disciplines from geo-spatial mapping to general relativity for its excellence in data science, visualisation and image processing. It is a high-level programming language, making prototyping solutions to a variety of problems straight-forward.

#### General User

The general user can download Mathematica through the same website. However, licenses range in price, with an industry license ranging from €755 per year (excluding VAT).

#### Institution License

You can find out if your academic institution holds a site license to Mathematica by following the link the the [Mathematica homepage](https://www.wolfram.com/mathematica/).
1. Follow the banner to find out if you already have access to Wolfram tech through your institution.
2. Enter the email address that is associated with your organisation and tick the box to agree to the retention of personal data.
3. Assuming eligibility, you will be prompted to confirm status at the organisation and brought to a software download page.

![image](https://user-images.githubusercontent.com/60405870/181994454-1c5c3f40-ea87-4553-a6c1-9dc94f1ab1a3.png)
![image](https://user-images.githubusercontent.com/60405870/181994582-3907f6c3-e576-4469-9237-802dd11dc9f1.png)

You will be required to 
- Check your email and click the link to validate Wolfram ID.
- Fill out the Wolfram Home Use Request Form if prompted to do so. This will request an activation key for a single machine.
- You will then automatically receive an email from Wolfram with the Activation Key and a link to download the installer.
- Follow the link to sign into the Wolfram User Portal.
- Download and run the installer.
- Enter the Activation Key at the prompt.

[(Back to top)](#an-investigation-into-global-climate-variables-and-the-determinants-of-global-warming)

#### Buying a Lisence

If you cannot access Wolfram Methematica through your University or Institution, you can buy a lisence via their [website](https://www.wolfram.com/mathematica/pricing/). On this page choose your subscription plan, with a guide here on how to download in install Mathematica for Home and Office. 


### 3. Data 📊 📈 

#### Temperature Data 🌡️ ❄️ 🔥

The [temperature data ](https://www.metoffice.gov.uk/hadobs/hadcrut5/data/current/download.html )
obtained from Met Office Hadley Centre observations datasets, where we downloaded 3 files:

1. HadCRUT5 analysis time series: ensemble means and uncertainties: Summary Series Global Monthly NetCDF;
2. HadCRUT5 analysis time series: ensemble members: Ensemble Series Global Monthly NetCDF;
3. HadCRUT5 analysis gridded data: additional fields: Ensemble mean NetCDF.

![image](https://user-images.githubusercontent.com/60405870/181915878-c8c1037c-0570-4d1c-9007-99b6ca751970.png)

![image](https://user-images.githubusercontent.com/60405870/181915981-1f0f87f2-8767-49b3-8359-50ffc74eacb2.png)

[(Back to top)](#an-investigation-into-global-climate-variables-and-the-determinants-of-global-warming)

#### Precipitation Data ☔ 🌀 ⛈️

The [precipitation data](https://downloads.psl.noaa.gov/Datasets/ghcngridded/)
is available through the National Oceanic and Atmospheric Administration Physical Sciences
Laboratory, and is produced under the Global Historical Climatology Network. 
The associated dataset is the Precipitation Anomaly Dataset

![image](https://user-images.githubusercontent.com/60405870/181916247-9e4269f5-2747-4bd1-8157-8f12b6bc42c7.png)

[(Back to top)](#an-investigation-into-global-climate-variables-and-the-determinants-of-global-warming)

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

[(Back to top)](#an-investigation-into-global-climate-variables-and-the-determinants-of-global-warming)

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

The user can also choose to use the keyborad shortcut `cmd + '` or `ctrl + '` on a mac or windows system.

[(Back to top)](#an-investigation-into-global-climate-variables-and-the-determinants-of-global-warming)

### 5. Authors 🚺 👩‍🔬

 
Eilish Clune & Megan Farrell (21208251, 16310126).

[(Back to top)](#an-investigation-into-global-climate-variables-and-the-determinants-of-global-warming)
