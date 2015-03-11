---
layout: post
title: "National Agriculture Sample Survey - Nigeria, 2010-2011"
tag: [price, crop, livestock, poultry, fishery, small holder farmer, large holder farmer, area, land, production, input, fertilizer, pesticide]
category: [nigeria]
---

{% include _toc.html %}
{% include JB/setup %}

## Description
---
The dataset was extracted from National Agricultural Sample Survey Report. National Agricultural Sample Survey (NASS) is an annual survey conducted to fill in the gap of National Agricultural Sample Census (NASC), which is supposed to be conducted every ten years as recommended by Food and Agriculture Organization (FAO).  

The National Agricultural Sample Survey (NASS) was conducted at the household level and establishment level (corporate farm), composing all agricultural activities; crop, livestock, poultry and fisheries. The result is intended to monitor some of the government policies in agriculture (Special Programme for Food Security), assist researchers and academia.  

The key objectives of the survey include [NBS, p8](1):

1. Collection of relevant statistics to facilitate the production of GDP.
2. Production of data to aid economic analysis on agriculture.
3. Collection of current socio-economic statistics in Nigeria to assist in policy formulation and aid the monitoring and evaluation of various government programmes on food security.
4. To make data available to researchers and academia .   

The scope covered all the sub-sectors of agriculture [NBS, p9](1):

1. Private crop farmers and corporate crop farming: area and production, gender, age group, funds, inputs, employment
2. Private livestock farming and corporate livestock farming: livestock production, inputs, funds, employment
3. Private poultry farming and corporate poultry farming: poultry count, inputs, funds, employment
4. Private fisheries and corporate fisheries: fish farming and fish hunting production, inputs, funds, employment 


### Location / Time Coverage
Country: Nigeria
Administrative Boundaries 1: Abia, Adamawa, Akwa Ibom, Anambra, Bauchi, Bayelsa, Benue, Borno, Cross River, Delta, Ebonyi, Edo, Ekiti, Enugu, Federal Capital Territory, Gombe, Imo, Jigawa, Kaduna, Kano, Katsina, Kebbi, Kogi, Kwara, Lagos, Nassarawa, Niger, Ogun, Ondo, Osun, Oyo, Plateau, Rivers, Sokoto, Taraba, Yobe, and Zamfara
  
Time Frame: 2010-2011 

### Citation / Source
Producer(s)   
National Bureau of Statistics (NBS)  
Federal Ministry of Agriculture and Rural Development (FMA&RD)

Funder(s)
National Bureau of Statistics (NBS)  
Federal Ministry of Agriculture and Rural Development (FMA&RD)

Citation  
NBS, National Agriculture Sample Survey, Nigeria - 2010, Public Access Dataset, Accessed on Feb 18, 2015. www.nigerianstat.gov.ng/pages/download/66

## Methodology
----
The dataset was extracted from National Agricultural Sample Survey Report. The sampling information for NASS survey is: 

### Sampling Procedure  
The sample NASS is designed to be representative at the state level and it was derived from the NBS 2007/12 NISH sample design. It is a two stage cluster sampling process ([NBS, p10][1]).

### Sample Size
For small holder farmers  
Households (National): 35,520 farming households  
Households (State): 960 households  

For corporate farms  
Corporate farms (National): 400  
For more information of the EA and household selection please review [NBS, 2010, p11](1)  

### Weighting
Weighting information was not provided in the documentation of this dataset.    

### Other Information
For other information including: Training, Field Work, Quality Control, Data Analysis and Process, and Report Writing, please review [NBS, 2010, p13](1)  

## Data Policy
----
*Access Authority*  
NA

*Contacts*  
NA  

*Confidentiality*  
This is a publicly accessible data set.

*Access Conditions*  
NA 

*Citation Requirement*  
All references to this data will have to be mentioned with the proper URL and the access date.

*Right & Disclaimer*  
NA  

## Other Information
----
### Data Cleaning
The original dataset provides aggregated information for crop, livestock, fishery, and poultry farming of both large scale and small scale farmers. The data was provided as 101 aggregated tables in a pdf document [NBS, 2010, p53-195](1). Data cleaning includes: extracted the information from the report; changed the data format to meeting aWhere platform loading requirement; replaced unknown symbols ("-" or ".") with empty data points; grouped crops according to aWhere crop classification rules; assign units. 

Based on the type of farmer, the dataset was grouped into 4 farmer groups:

- Crop Farmers
- Livestock Farmers
- Poultry Farmers
- Fishery Farmers

Under each type of farmers, the dataset was further grouped into 2 types of farmer groups: Large Holder Farmers and Small Holder Farmers. 

Further grouping was done based on the farm activities. Please use the "Data Map" in the Data Quality Profile section of this summary.  

Some of the tables from the report has ambiguous attribute definitions. Attributes from these tables are assigned categories as follow:

- Table 33 has been assigned in folder Livestock farmers
- Table 80 has been assigned in corporate farmer, crop farmer

The units of some attributes in the origial dataset has not been assigned. These attributes and their assigned units are: 
 
- Table 11 Sales from Own Production at Farm for 10 crops, assigned units: 1000 naira
- Tables include "distribution", assigned units: holder
- Table 67 Type of holding, assigned units: holder
- Average unit price of livestock, assigned unit: naira/animal
- Poultry farming expense, assigned naira
- Table 83 Cost of input, assigned unit: naira
- Table 86 Persons Engaged in Corporate Livestock Farming, assigned units: 1000 person and naira
- Table 96 Sources of Funding and Amount in Corporate Poultry Farming, assigned unit: naira
- Table 99 Operating Expenses in Corporate Poultry Farming, assigned unit: naira

Some tables from the report are not included in this dataset because the interpretation of the attribute is unclear. These tables are:

- Table 24 Distribution of ways that government can assist farmers

Some tables from the report are not included in this dataset because the values are repeating:

- Table 3 Distribution of Holding by Size (Hectare) of Tenure and by States (same as table 1)
- Table 77 and table 78 are repeating. Kept Table 78 for clearer title

### Relevant Papers
NA

### Papers That Cite this Data Set
NA

## Data Quality Profile
----
Data Quality Profile will provide data map for data navigation within the aWhere platform, descriptive statistics, and data point distribution plot. 

### Data Map
You can use the data map to assist navigation within the aWhere platform. 
<script src="https://gist.github.com/yizhexu/9be76eb8b22b0c20b8e4.js"></script>

### Descriptive Statistics
Here is a data distribution chart. 
<script src="https://gist.github.com/yizhexu/fb5068cbe5900c705e0f.js"></script>

### Data Distribution
<a href="http://imgur.com/1LiOOnt"><img src="http://i.imgur.com/1LiOOnt.jpg" title="source: imgur.com" /></a>



[1]: www.nigerianstat.gov.ng/pages/download/66 "National Agricultural Sample Survey, NASS 2010/2011"
