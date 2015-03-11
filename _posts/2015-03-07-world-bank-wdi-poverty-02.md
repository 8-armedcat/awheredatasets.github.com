---
layout: post
title: World Development Indicators - Poverty, 1976-2014
tag: [gini index, income share, poverty gap]
category: [afghanistan, albania, algeria, angola, argentina, armenia, australia, austria, azerbaijan, bangladesh, belarus, belgium, belize, benin, bhutan, bolivia, bosnia & herzegovina, botswana, brazil, bulgaria, burkina faso, burundi, cape verde, cambodia, cameroon, canada, central african republic, chad, chile, china, colombia, comoros, democratic republic of the congo, congo, costa rica, cote d'ivoire, croatia, czech republic, denmark, djibouti, dominican republic, ecuador, egypt, el salvador, equatorial guinea, eritrea, estonia, ethiopia, fiji, finland, france, gabon, the gambia, georgia, germany, ghana, greece, guatemala, guinea, guinea-bissau, guyana, haiti, honduras, hungary, iceland, india, indonesia, iran, iraq, ireland, israel, italy, jamaica, japan, jordan, kazakhstan, kenya, kosovo, kyrgyzstan, laos, latvia, lebanon, lesotho, liberia, lithuania, macedonia, madagascar, malawi, malaysia, maldives, mali, marshall is., mauritania, mauritius, mexico, micronesia, moldova, mongolia, montenegro, morocco, mozambique, namibia, nepal, netherlands, nicaragua, niger, nigeria, norway, pakistan, panama, papua new guinea, paraguay, peru, philippines, poland, romania, russia, rwanda, sao tome & principe, senegal, serbia, seychelles, sierra leone, slovenia, solomon is., south africa, south sudan, spain, sri lanka, st. lucia, sudan, suriname, swaziland, sweden, switzerland, syria, tajikistan, tanzania, thailand, timor leste, togo, trinidad & tobago, tunisia, turkey, turkmenistan, uganda, ukraine, united kingdom, united states, uruguay, uzbekistan, venezuela, vietnam, yemen, zambia, zimbabwe]
---

{% include _toc.html %}
{% include JB/setup %}


## Description
---
The primary World Bank collection of development indicators, compiled from officially-recognized international sources. It presents the most current and accurate global development data available, and includes national, regional and global estimates.  

For countries with an active poverty monitoring program, the World Bank—in collaboration with national institutions, other development agencies, and civil society—regularly conducts analytical work to assess the extent and causes of poverty and inequality, examine the impact of growth and public policy, and review household survey data and measurement methods. Data here includes poverty and inequality measures generated from analytical reports, from national poverty monitoring programs, and from the World Bank’s Development Research Group which has been producing internationally comparable and global poverty estimates and lines since 1990.

For more information please visit the World Bank Poverty [website](http://data.worldbank.org/topic/poverty)

### Location / Time Coverage
Country: World  
Time Frame: 1976-2014 (Various by country)  

### Citation / Source
Producer: The World Bank Data Group  

Citation: World Development Indicators, the World Bank, Public Access Dataset, Accessed on Feb 25, 2015. http://data.worldbank.org/topic/poverty

## Methodology
----
The World Bank compiles and standardizes data from a variety of sources to create its indicator database. They have detailed explanations of their methodologies, covering topics like:

- Data Consistency
- Change in Terminology
- Aggregation Rules
- Growth Rates
- World Bank Atlas Method
- Alternative Conversion Factors

For a complete explanation of their procedures please visit World Bank Data [Methodologies](http://data.worldbank.org/about/data-overview/methodologies)

The World Bank also provides information around [Data Quality and Effectiveness](http://data.worldbank.org/about/data-overview/data-quality-and-effectiveness) and [Frequently Asked Questions](http://data.worldbank.org/about/faq). 

For a definition of each individual variable please review the "description" details on the Dev aWhere platform. 

## Data Policy
----
*Access Authority* 
World Bank's Development Data Group 
Email: data@worldbank.org
Phone: (202) 473-7824 or 1 (800) 590-1906

*Contacts*
World Bank's Development Data Group  
Email: data@worldbank.org
Phone: (202) 473-7824 or 1 (800) 590-1906

*Confidentiality*  
This is a publicly accessible data set.

*Access Conditions*  
NA 

*Citation Requirement*  
All references to WDI data will have to be mentioned with the proper URL and the access date.

*Right & Disclaimer*  

- You are free to copy, distribute, adapt, display or include the data in other products for commercial and noncommercial purposes at no cost subject to certain limitations summarized below.
- You must include attribution for the data you use in the manner indicated in the metadata included with the data.
- You must not claim or imply that The World Bank endorses your use of the data by or use The World Bank’s logo(s) or trademark(s) in conjunction with such use.
- Other parties may have ownership interests in some of the materials contained on The World Bank Web site. For example, we maintain a list of some specific data within the Datasets that you may not redistribute or reuse without first contacting the original content provider, as well as information regarding how to contact the original content provider. Before incorporating any data in other products, please check the list: [Terms of use: Restricted Data](http://www.worldbank.org/terms-datasets-restricted)
- The World Bank makes no warranties with respect to the data and you agree The World Bank shall not be liable to you in connection with your use of the data.
- This is only a summary of the Terms of Use for Datasets Listed in The World Bank Data Catalogue. Please read the actual agreement that controls your use of the Datasets, which is available here: [Terms of use for datasets](http://www.worldbank.org/terms-datasets). Also see [World Bank Terms and Conditions](http://www.worldbank.org/terms).

## Other Information
----
aWhere has taken some data cleaning steps to make this data available in the platform. 

### Data Cleaning
The original World Development Poverty Indicators dataset contains 22 variables. 18 of these variables are available through the [WDI](http://cran.r-project.org/web/packages/WDI/index.html) package in R. 4 variables are not available, they are: 

- Annualized growth in survey mean consumption or income per capita, bottom 40% (%, based on 2005 PPP)
- Annualized growth in survey mean consumption or income per capita, total population (%, based on 2005 PPP)
- Survey mean consumption or income per capita, bottom 40% (2005 PPP $ per day)
- Survey mean consumption or income per capita, total population (2005 PPP $ per day)

The original dataset includes regions and areas that cannot be mapping on aWhere platform [Dev aWhere](http://apps.awhere.com/). Those regions and areas were removed, but all individual country data was retained. These regions are: Africa, Arab World, Caribbean small states, Central Europe and the Baltics, Channel Islands, East Asia & Pacific (all income levels), East Asia & Pacific (developing only), Euro area, Europe & Central Asia (all income levels), Europe & Central Asia (developing only), European Union, Fragile and conflict affected situations, Heavily indebted poor countries (HIPC), High income, High income: nonOECD, High income: OECD, Latin America & Caribbean (all income levels), Latin America & Caribbean (developing only), Least developed countries: UN classification, Low & middle income, Low income, Lower middle income, Middle East & North Africa (all income levels), Middle East & North Africa (developing only), Middle income, North Africa, North America, Not classified, OECD members, Other small states, Pacific island small states, Sint Maarten (Dutch part), Small states, South Asia, St. Vincent and the Grenadines, Sub-Saharan Africa (all income levels), Sub-Saharan Africa (developing only), Sub-Saharan Africa excluding South Africa, Sub-Saharan Africa excluding South Africa and Nigeria, Upper middle income, West Bank and Gaza, World.

The data cleaning also removed empty records (countries that do not have any data for any variable). 

### Relevant Papers
NA

### Papers That Cite this Data Set
NA

## Data Quality Profile
----
Data Quality Profile will provide data map for data navigation within the aWhere platform, descriptive statistics, and data point distribution plot. 

### Data Map
You can use the data map to assist navigation within the aWhere platform. 
<script src="https://gist.github.com/yizhexu/5e266d17eeed5f2c4af7.js"></script>

### Descriptive Statistics
Here is a data distribution chart. 
<script src="https://gist.github.com/yizhexu/a556cd8f6deb118371ab.js"></script>

### Data Distribution
<a href="http://imgur.com/vG8SHBj"><img src="http://i.imgur.com/vG8SHBj.jpg" title="source: imgur.com" /></a>

[1]: http://cran.r-project.org/web/packages/WDI/index.html "WDI Package"
[2]: http://apps.awhere.com/ "Dev aWhere"
[3]: http://data.worldbank.org/topic/poverty "World Development Indicators - Poverty"
[4]: http://www.worldbank.org/terms-datasets-restricted "Terms of use: Restricted Data"
[5]: http://www.worldbank.org/terms-datasets "Terms of use for datasets"
[6]: http://www.worldbank.org/terms "World Bank Terms and Conditions"
[7]: http://data.worldbank.org/about/data-overview/methodologies "Methodologies"
[8]: http://data.worldbank.org/about/faq "Frequently Asked Questions"