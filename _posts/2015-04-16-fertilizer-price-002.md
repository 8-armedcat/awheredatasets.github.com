---
layout: post
title: "National Fertilizers Price - Market Level, 2010-2014"
tag: [price, fertilizer, market]
category: [benin, burkina faso, burundi, cote d'ivoire, ghana, kenya, malawi, mali, mozambique, niger, nigeria, rwanda, senegal, swaziland, togo, uganda, tanzania, zambia]
---

{% include _toc.html %}
{% include JB/setup %}


## Description
---
AfricaFertilizer.org is a global initiative facilitating the exchange of information on soil fertility, fertilizers, and good agricultural practices in Africa. AfricaFertilizer.org is led by IFDC, in partnership with the International Fertilizer Industry Association (IFA), the African Fertilizer and Agribusiness Partnership (AFAP), the Food and Agriculture Organization of the United Nations (FAO) through its CountrySTAT program, and the African Union Commission (AUC) and its NEPAD Planning and Coordination Agency. 

AFO’s initiative supports all African countries, with a focus on the 39 Sub-Saharan African countries. AFO provides priority support and technical assistance to national statistical counterparts as CountrySTAT Fertilizer Technical Working Groups in seven countries: Ghana, Ethiopia, Kenya, Mozambique, Nigeria, Senegal, and Tanzania. Support to these priority countries includes onside technical trainings and validation workshops to ensure the proper documentation and dissemination of robust fertilizer statistics at national and sub-national levels (including on production, trade, consumption, use by crop, directories and products). 

AFO, in collaboration with the East Africa Community and the Economic and Monetary Union of West African States, provides customized support to 10 countries. AFO provides remote and physical support to 12 other Sub-Saharan Africa countries. 

For more information, please review [Africa Fertlizer](1).

### Location / Time Coverage
Country: Market level data for Benin, Burkina Faso, Burundi, Cote d'Ivoire, Ghana, Kenya, Malawi, Mali, Mozambique, Niger, Nigeria, Rwanda, Senegal, Swaziland, Togo, Uganda, Tanzania, Zambia  
Time Frame: 2010 - 2014

### Citation / Source
Producer: AfricaFertilizer.org

Africa Fertilizer, 2015, "National Price". First accessed at: http://africafertilizer.org/prices_national.html

## Methodology
----
Not Available

## Data Policy
----
*Access Authority*:   
Address: IFDC P.O. Box 2040 Muscle Shoals, Alabama 35662 (U.S.A.) 
Phone: +1 256 381 6600 
Fax: +1 256 381 7408 
E-Mail: info@africafertilizer.org

*Contacts*:  
Address: IFDC P.O. Box 2040 Muscle Shoals, Alabama 35662 (U.S.A.) 
Phone: +1 256 381 6600 
Fax: +1 256 381 7408 
E-Mail: info@africafertilizer.org

*Confidentiality*:   
This is a publicly accessible data set 

*Access Conditions*:  
This is a publicly accessible dataset

*Citation Requirement*:  
NA

*Right & Disclaimer*:   
NA

## Other Information
----
aWhere has taken some data cleaning steps to make this data available in the  Dev aWhere [platform](2). 

### Data Cleaning
The original dataset included 1 down loadable file in xls format. The data cleaning process involved changing the data structure to a "wide" data structure where each indicator is mapped to a unique location and time combination. The data cleaning also include reconstructing metadata information by scraping information from Africafertilizer.org website

The data cleaning process also:

- Extract data table from separate html files exported from AfricaFertilizer.org
- Dropped duplicated records
- Calculated average price for 12 duplicated records. These are 
	- NPK 15 15 15 price for Dimbokro, Cote d'Ivoire in March, 2013
	- NPK 15 15 15 price for Kedougou, Senegal in March, 2013
	- PK 0 23 19 + 6.5S + 5MgO + 10CaO price for Arrah, Cote d'Ivoire in March, 2013
	- Urea price for Kaffrine, Senegal in March 2013; Kedougou, Senegal in March 2013, and Kolda, Senegal in April 2013. 
- Cleaned up market location latitude and longitude using resources provided by AfricaFertilizer.org
- Assigned city centroids as locations for:
	- Sassandra, Côte D'Ivoire
	- Tema, Ghana
	- Kangari, Kenya
	- Lumakanda, Kenya
	- Bvumbwe, Malawi
	- Karaye, Nigeria
	- Lagos, Nigeria
	- Mutum Biyu, Nigeria
	- Luanshya, Zambia
	- Mkushi, Zambia

### Relevant Papers
NA

### Papers That Cite this Data Set
NA

## Data Quality Profile
----
Data Quality Profile will provide data map for data navigation within the aWhere platform, descriptive statistics, and data point distribution plot. 

### Data Map
You can use the data map to assist navigation within the aWhere platform. 
<script src="https://gist.github.com/yizhexu/599eb23040313c50cc21.js"></script>

### Descriptive Statistics
Here is a data distribution chart. 
<script src="https://gist.github.com/yizhexu/493187dcbf59c87695bf.js"></script>

### Data Distribution
<a href="http://imgur.com/G9hTvRG"><img src="http://i.imgur.com/G9hTvRG.jpg" title="source: imgur.com" /></a>



[1]: http://africafertilizer.org/ "Africa Fertilizer"
[2]: http://apps.awhere.com/ "Dev aWhere"
