---
layout: post
title: "FAOSTAT Indicators - Inputs Indicators 1961-2013"
tag: [ fertilizer, pesticide, land]
category: [afghanistan, albania, algeria, american samoa, andorra, angola, anguilla, antigua & barbuda, argentina, armenia, aruba, australia, austria, azerbaijan, the bahamas, bahrain, bangladesh, barbados, belarus, belgium, belize, benin, bermuda, bhutan, bolivia, bosnia & herzegovina, botswana, brazil, british virgin is., brunei, bulgaria, burkina faso, burundi, cape verde, cambodia, cameroon, canada, cayman is., central african republic, chad, chile, china, colombia, comoros, congo, cook is., costa rica, croatia, cuba, cyprus, czech republic, denmark, djibouti, dominica, dominican republic, democratic republic of the congo, ecuador, egypt, el salvador, equatorial guinea, eritrea, estonia, ethiopia, falkland is., faroe is., fiji, finland, france, french guiana, french polynesia, gabon, the gambia, georgia, germany, ghana, gibraltar, greece, greenland, grenada, guadeloupe, guam, guatemala, guinea, guinea-bissau, guyana, haiti, honduras, hong kong, hungary, iceland, india, indonesia, iran, iraq, ireland, isle of man, israel, italy, jamaica, japan, jordan, kazakhstan, kenya, kiribati, kuwait, kyrgyzstan, laos, latvia, lebanon, lesotho, liberia, libya, liechtenstein, lithuania, luxembourg, macao, macedonia, madagascar, malawi, malaysia, maldives, mali, malta, marshall is., martinique, mauritania, mauritius, mayotte, mexico, micronesia, monaco, mongolia, montenegro, montserrat, morocco, mozambique, myanmar, namibia, nauru, nepal, netherlands, netherlands antilles, new caledonia, new zealand, nicaragua, niger, nigeria, niue, norfolk i., north korea, northern mariana is., norway, oman, pakistan, palau, panama, papua new guinea, paraguay, peru, philippines, pitcairn is., poland, portugal, puerto rico, qatar, south korea, moldova, romania, russia, rwanda, samoa, san marino, sao tome & principe, saudi arabia, senegal, serbia, seychelles, sierra leone, singapore, slovakia, slovenia, solomon is., somalia, south africa, south sudan, spain, sri lanka, sudan, suriname, swaziland, sweden, switzerland, syria, taiwan, tajikistan, tanzania, thailand, timor leste, togo, tokelau, tonga, trinidad & tobago, tunisia, turkey, turkmenistan, turks & caicos is., tuvalu, uganda, ukraine, united arab emirates, united kingdom, united states, virgin is., uruguay, uzbekistan, vanuatu, venezuela, vietnam, wallis & futuna, western sahara, yemen, zambia, zimbabwe]
---

{% include _toc.html %}
{% include JB/setup %}

##Description

FAOSTAT provides time-series and cross sectional  data relating to food and agriculture for some 200 countries. It is available in English, French and Spanish. This database includes indicators in areas like Food Security, Production, Trade, Food Balance, Prices, Inputs, Population, Investment, Agri-Environmental Indicators, Agriculture Emission, Land Use Emission, Forestry, ASTI R&D Indicators, and Emergency Responses.   

Some of the most interesting data for economists is found in input domain. The national distribution of land, among arable land, pastures and other lands, as well as the importance of irrigation are just some of the interesting datasets. [FAO][6] 

The Agricultural Inputs domain covers:

- Investment
- Land and irrigation
- Labour
- Machinery
- Fertilizers
- Pesticides
- Population

The inputs domain considers factors of production for the agricultural sector. Broadly speaking, this section details how countries differ in endowments of the three classic inputs: labour, land and capital. Qualitative differences are important for each but are particularly difficult to summarise in a single indicator for land, the productivity of which depends heavily on water and soil conditions. : 

###Location / Time Coverage

Country: World  
Time Frame: 1961-2013 (Various by country)  

###Citation / Source

Producer(s)   
Food and Agriculture Organization of the United Nations (FAO of the UN) 

Citation  
FAO of the UN, FAOSTAT, Public Access Dataset, Accessed on Feb 10, 2015. http://faostat3.fao.org/home/E

##Methodology

###Classifications    
The classifications includes Agriculture Total, Air and climate change, Annual population, ASTI-Expenditures, ASTI-Researchers by Agency Type, ASTI-Researchers by Gender and Degree Level, Burning - Biomass, Burning - Crop Residues, Burning - Savanna, Commodity Balances - Crops Primary Equivalent, Commodity Balances - Livestock and Fish Primary Equivalent, Consumer Price Indices, Crop Residues, Cropland, Crops, Crops and livestock products, Crops processed, Cultivation of Organic Soils, Detailed trade matrix, Energy, Energy Use, Enteric Fermentation, Fertilizers, Fertilizers - Trade Value, Fertilizers archive, Food Balance Sheets, Food Supply - Crops Primary Equivalent, Food Supply - Livestock and Fish Primary Equivalent, Forest Land, Forestry Production and Trade, Forestry Trade Flows, Grassland, Land, Land Use Total, Live Animals, Live animals, Livestock, Livestock Primary, Livestock Processed, Manure applied to Soils, Manure left on Pasture, Manure Management, Pesticides, Pesticides (trade), Pesticides (use), Producer Price Indices - Annual, Producer Prices - Annual, Producer Prices - Archive, Producer Prices - Monthly, Production Indices, Rice Cultivation, Soil, Synthetic Fertilizers, Trade Indices, Value of Agricultural Production, Water. The specific indicators of each classification can be found on [FAOSTAT][1].

###Methodology
FAOSTAT provides the following resources:

- [Methodology][2] 
- [Units and Symbols][3]   
- [Glossary list][4]
- [Abbreviation list][5]  

##Data Policy

*Access Authority*  
Economic and Social Development Department, Viale delle Terme di Caracalla, FAO-statistics@fao.org

*Contacts*  
Economic and Social Development Department, Viale delle Terme di Caracalla, FAO-statistics@fao.org

*Confidentiality*  
This is a publicly accessible data set.

*Access Conditions*  
NA 

*Citation Requirement*  
All references to FAOSTAT data will have to be mentioned with the proper URL and the access date.

*Right & Disclaimer*  
The designations employed and the presentation of materials in FAOSTAT do not imply the expression of any opinion whatsoever on the part of the Food and Agriculture Organization of the United Nations concerning the legal status of any country, territory, city or area or its authorities, or concerning the delimination of its frontiers or boundaries.  
Where the designation "country" or "area" appears on this internet site, it covers countries, territories or areas.  
The data of the FAOSTAT database shown on this internet site are copyrighted by the Food and Agriculture Organization of the United Nations and are provided for your internal use only. They may not be re-disseminated in any form without written permission of the FAO Statistics Division.  

##Other Information

The original inputs dataset included 631 attributes. 423 of these attributes were not provided through the FAOSTAT [R package ][7]. These attributes are fertilizer and pesticide-specific data in the following categories: 
 
- Fertilizers archive
- Fertilizers
- Pesticides (trade)
- Fertilizers Trade Value

The original dataset also included regions and areas that cannot be mapped on the [Dev aWhere platform][8], which were removed. These regions are: 
  
- Belgium-Luxembourg
- Saint Helena, Ascension and Tristan da Cunha
- Saint Kitts and Nevis
- Saint Lucia
- Saint Pierre and Miquelon
- Saint Vincent and the Grenadines
- Union of Soviet Socialist Republic
- Channel Islands

###Relevant Papers

> Food and Agriculture Organization. FAO Statistical Yearbook 2013. Rome: Food and Agriculture Organization, 2013. http://www.fao.org/docrep/018/i3107e/i3107e00.htm.  

> Haluk Kasnakoglu, and Robert Mayo. “FAO Statistical Data Quality Framework: A Multi-Layered Approach to Monitoring and Assessment.” Rome, Italy, 2004.

###Papers That Cite this Data Set
NA

## Data Quality Profile
----
Data Quality Profile will provide data map for data navigation within the aWhere platform, descriptive statistics, and data point distribution plot. 

### Data Map
You can use the data map to assist navigation within the aWhere platform. 
<script src="https://gist.github.com/yizhexu/97acce32fe1c2035009c.js"></script>

### Descriptive Statistics
<script src="https://gist.github.com/yizhexu/8be396b7fce249a8fe1d.js"></script>

### Data Distribution
Here is a data distribution chart. 
<a href="http://imgur.com/hBJdR9t"><img src="http://i.imgur.com/hBJdR9t.jpg" title="source: imgur.com" /></a>


[1]: http://faostat3.fao.org/mes/classifications/E "Classifications" 
[2]: http://faostat3.fao.org/mes/methodology_list/E "Methods & Standards"
[3]: http://faostat3.fao.org/mes/units/E "Standard Units and Symbols used in FAOSTAT"
[4]: http://faostat3.fao.org/mes/glossary/E "Glossary List"
[5]: http://faostat3.fao.org/mes/abbreviations/E "Abbreviations List"
[6]: http://faostat3.fao.org/download/Q/*/E "Production"
[7]: http://cran.r-project.org/web/packages/FAOSTAT/index.html "FAOSTAT: A complementary package to the FAOSTAT database and the Statistical Yearbook of the Food and Agricultural Organization of the United Nations"
[8]: http://apps.awhere.com/ "aWhere Platform"