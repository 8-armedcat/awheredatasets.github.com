---
layout: post
title: "Famine Early Warning System NET Price Volatility - Tanzania, 2002-2012"
tag: [price, crop, maize, bean, rice, wheat]
categories: [tanzania]
---

{% include _toc.html %}
{% include JB/setup %}

## Description
----
This dataset from the Famine Early Warning System Network (FEWS NET) documents ten years, from 2002 to 2012, of cereal price fluctuations across twenty-five African countries. These numbers provide a month-by-month record of the degree and scope of price crises as well as undisturbed cereal markets in Africa ([USAID](1)). 

This dataset includes daily price data for beans, maize, rice and wheat of 14 markets including Arusha, Dar es Salaam, Mwanza, Mbeya, Tanga, Bukoba, Songea, Sumbawanga, Iringa, Dodoma, Morogoro, Moshi, Musoma, and Kigoma ([USAID](1)).   

### Location / Time Coverage
Country: Tanzania
Markets: Arusha, Bukoba, Dar es salaam, Dodoma, Iringa, Kigoma, Mbeya, Morogoro, Moshi, Musoma, Mwanza, Songea, Sumbawanga, and Tanga 
  
Time Frame: 2002-2012
Time increments: Day 

### Citation / Source
Producer(s)   
United State Agency of International Development, http://www.usaid.gov/data	

Citation  
Famine Early Warning System NET Price Volatility - Tanzania, 2002-2012, public use dataset (Nov 2014), provided by United State Agency of International Development (USAID), www.usaid.gov	

## Methodology
----
Not Available.   

### Attribute Information
The original dataset provides wholesale and retail price for maize, maize white, rice, sorghum, and wheat. 

## Data Policy
----
*Access Authority*  
NA

*Contacts*  
NA  

*Confidentiality*  
Public use files.

*Access Conditions*  
NA 

*Citation Requirement*  
All references to this data will have to be mentioned with the proper URL and the access date.

*Right & Disclaimer*  
NA  

## Other Information
----
aWhere has taken some data cleaning steps to make this data available in the platform. 

### Data Cleaning

Data cleaning includes: 

- Convert the data to a format with location (market name) and time in columns instead of rows
- Take the market name to look up latitude and longitude information
- Create an "attribute name" and  "unit" row to record the appropriate attribute name
- Create an "id" column to generate market wise record ids
- Combine the two "Wholesale price, maize white" variables
 

### Relevant Papers
NA


### Papers That Cite this Data Set
NA


## Data Quality Profile
----
Data Quality Profile will provide data map for data navigation within the aWhere platform, descriptive statistics, and data point distribution plot. 

### Data Map
<script src="https://gist.github.com/yizhexu/262854f876f9e26f247d.js"></script>


### Descriptive Statistics
<script src="https://gist.github.com/yizhexu/978d9d373e0ed5e8685c.js"></script>

### Data Distribution
<a href="http://imgur.com/UGiNguj"><img src="http://i.imgur.com/UGiNguj.jpg" title="source: imgur.com" /></a>


[1]: http://catalog.data.gov/dataset/fews-net-price-volatility-data-2002-2012 "USAID FEWS NET Price Volatility Data 2002-2012"
[2]: http://www.competeafrica.org/Files/20121105_RATIN_Final.pdf "East Africa Trade Hub, 2012, Regional Agriculture Trade Intelligence Network"
[3]: http://www.eagc.org/acpaf_esa/ATPAF%20-ESA%20_Janet.pdf "Janet Kalulu Ngombalu, Regional Agricultural Trade Intelligence Network – RATIN"