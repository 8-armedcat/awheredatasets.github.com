---
layout: post
title: World Development Indicators - External Debt, 1960-2014
tag: [debt, arrears, bonds, private debt, public debt, grant, loan]
category: [afghanistan, albania, algeria, american samoa, andorra, angola, antigua & barbuda, argentina, armenia, aruba, australia, austria, azerbaijan, the bahamas, bahrain, bangladesh, barbados, belarus, belgium, belize, benin, bermuda, bhutan, bolivia, bosnia & herzegovina, botswana, brazil, brunei, bulgaria, burkina faso, burundi, cape verde, cambodia, cameroon, canada, cayman is., central african republic, chad, chile, china, colombia, comoros, democratic republic of the congo, congo, costa rica, cote d'ivoire, croatia, cuba, curaçao, cyprus, czech republic, denmark, djibouti, dominica, dominican republic, ecuador, egypt, el salvador, equatorial guinea, eritrea, estonia, ethiopia, faroe is., fiji, finland, france, french polynesia, gabon, the gambia, georgia, germany, ghana, greece, greenland, grenada, guatemala, guinea, guinea-bissau, guyana, haiti, honduras, hong kong, hungary, iceland, india, indonesia, iran, iraq, ireland, isle of man, israel, italy, jamaica, japan, jordan, kazakhstan, kenya, kiribati, north korea, south korea, kosovo, kuwait, kyrgyzstan, laos, latvia, lebanon, lesotho, liberia, libya, liechtenstein, lithuania, luxembourg, macao, macedonia, madagascar, malawi, malaysia, maldives, mali, malta, marshall is., mauritania, mauritius, mexico, micronesia, moldova, monaco, mongolia, montenegro, morocco, mozambique, myanmar, namibia, nepal, netherlands, new caledonia, new zealand, nicaragua, niger, nigeria, northern mariana is., norway, oman, pakistan, palau, panama, papua new guinea, paraguay, peru, philippines, poland, portugal, puerto rico, qatar, romania, russia, rwanda, samoa, san marino, sao tome & principe, saudi arabia, senegal, serbia, seychelles, sierra leone, singapore, slovenia, solomon is., somalia, south africa, south sudan, spain, sri lanka, st. kitts & nevis, st. lucia, sudan, suriname, swaziland, sweden, switzerland, syria, tajikistan, tanzania, thailand, timor leste, togo, tonga, trinidad & tobago, tunisia, turkey, turkmenistan, turks & caicos is., tuvalu, uganda, ukraine, united arab emirates, united kingdom, united states, uruguay, uzbekistan, vanuatu, venezuela, vietnam, virgin is., yemen, zambia, zimbabwe]
---

{% include _toc.html %}
{% include JB/setup %}


## Description
---
The primary World Bank collection of development indicators, compiled from officially-recognized international sources. It presents the most current and accurate global development data available, and includes national, regional and global estimates.  

Debt statistics provide a detailed picture of debt stocks and flows of developing countries. Data presented as part of the Quarterly External Debt Statistics takes a closer look at the external debt of high-income countries and emerging markets to enable a more complete understanding of global financial flows. The Quarterly Public Sector Debt database provides further data on public sector valuation methods, debt instruments, and clearly defined tiers of debt for central, state and local government, as well as extra-budgetary agencies and funds. Data are gathered from national statistical organizations and central banks as well as by various major multilateral institutions and World Bank staff.

For more information please visit the World Bank [website](http://data.worldbank.org/topic/external-debt)

### Location / Time Coverage
Country: World  
Time Frame: 1970-2013 (Various by country)  

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
The original World Development External Debt Indicators contains 233 variables. 229 of these variables are available through the [WDI](http://cran.r-project.org/web/packages/WDI/index.html) package in R. 3 indicators are unavailable for download through World Development Indicators API. They are:

- External debt stocks (% of exports of goods, services and primary income)
- Interest payments on external debt (% of exports of goods, services and primary income)
- Primary income on FDI, payments (current US$)

1 indicator failed to load through the api: BM.GSR.TOTL.CD, "Imports of goods, services and primary income (BoP, current US$)".

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
<script src="https://gist.github.com/yizhexu/8b89f84741cdca2d350e.js"></script>

### Descriptive Statistics
<script src="https://gist.github.com/yizhexu/ee60b1a4f8dee48faf95.js"></script>

### Data Distribution
Here is a data distribution chart. 
<a href="http://imgur.com/7be4O02"><img src="http://i.imgur.com/7be4O02.jpg" title="source: imgur.com" /></a>

[1]: http://cran.r-project.org/web/packages/WDI/index.html "WDI Package"
[2]: http://apps.awhere.com/ "Dev aWhere"
[3]: http://data.worldbank.org/topic/poverty "World Development Indicators - Poverty"
[4]: http://www.worldbank.org/terms-datasets-restricted "Terms of use: Restricted Data"
[5]: http://www.worldbank.org/terms-datasets "Terms of use for datasets"
[6]: http://www.worldbank.org/terms "World Bank Terms and Conditions"
[7]: http://data.worldbank.org/about/data-overview/methodologies "Methodologies"
[8]: http://data.worldbank.org/about/faq "Frequently Asked Questions"