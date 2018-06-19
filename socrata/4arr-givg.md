# Public Health Statistics - Births and birth rates in Chicago, by year, 1999 ? 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-births-and-birth-rates-in-chicago-by-year-1999-2009-1b495) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/4arr-givg) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/4arr-givg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/4arr-givg/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 4arr-givg |
| Name | Public Health Statistics - Births and birth rates in Chicago, by year, 1999 ? 2009 |
| Attribution | Illinois Department of Public Health (IDPH) |
| Category | Health & Human Services |
| Tags | birth, health |
| Created | 2011-12-30T19:03:52Z |
| Publication Date | 2012-10-22T19:33:57Z |

## Description

This dataset contains the annual number of births and crude birth rate (births per 1,000 residents) with corresponding 95% confidence intervals, by Chicago community area, for the years 1999 ? 2009.  See the full dataset description for more information: https://data.cityofchicago.org/api/assets/8C4E8E51-6162-4DF3-9C29-D3F205FA2FB4

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | community_area           | Community Area           | text      | number      |
| Yes      | series tag     | community_area_name      | Community Area Name      | text      | text        |
| Yes      | numeric metric | births_1999              | Births 1999              | number    | number      |
| Yes      | numeric metric | birth_rate_1999          | Birth Rate 1999          | number    | number      |
| Yes      | numeric metric | birth_rate_1999_lower_ci | Birth Rate 1999 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_1999_upper_ci | Birth Rate 1999 Upper CI | number    | number      |
| Yes      | numeric metric | births_2000              | Births 2000              | number    | number      |
| Yes      | numeric metric | birth_rate_2000          | Birth Rate 2000          | number    | number      |
| Yes      | numeric metric | birth_rate_2000_lower_ci | Birth Rate 2000 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2000_upper_ci | Birth Rate 2000 Upper CI | number    | number      |
| Yes      | numeric metric | births_2001              | Births 2001              | number    | number      |
| Yes      | numeric metric | birth_rate_2001          | Birth Rate 2001          | number    | number      |
| Yes      | numeric metric | birth_rate_2001_lower_ci | Birth Rate 2001 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2001_upper_ci | Birth Rate 2001 Upper CI | number    | number      |
| Yes      | numeric metric | births_2002              | Births 2002              | number    | number      |
| Yes      | numeric metric | birth_rate_2002          | Birth Rate 2002          | number    | number      |
| Yes      | numeric metric | birth_rate_2002_lower_ci | Birth Rate 2002 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2002_upper_ci | Birth Rate 2002 Upper CI | number    | number      |
| Yes      | numeric metric | births_2003              | Births 2003              | number    | number      |
| Yes      | numeric metric | birth_rate_2003          | Birth Rate 2003          | number    | number      |
| Yes      | numeric metric | birth_rate_2003_lower_ci | Birth Rate 2003 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2003_upper_ci | Birth Rate 2003 Upper CI | number    | number      |
| Yes      | numeric metric | births_2004              | Births 2004              | number    | number      |
| Yes      | numeric metric | birth_rate_2004          | Birth Rate 2004          | number    | number      |
| Yes      | numeric metric | birth_rate_2004_lower_ci | Birth Rate 2004 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2004_upper_ci | Birth Rate 2004 Upper CI | number    | number      |
| Yes      | numeric metric | births_2005              | Births 2005              | number    | number      |
| Yes      | numeric metric | birth_rate_2005          | Birth Rate 2005          | number    | number      |
| Yes      | numeric metric | birth_rate_2005_lower_ci | Birth Rate 2005 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2005_upper_ci | Birth Rate 2005 Upper CI | number    | number      |
| Yes      | numeric metric | births_2006              | Births 2006              | number    | number      |
| Yes      | numeric metric | birth_rate_2006          | Birth Rate 2006          | number    | number      |
| Yes      | numeric metric | birth_rate_2006_lower_ci | Birth Rate 2006 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2006_upper_ci | Birth Rate 2006 Upper CI | number    | number      |
| Yes      | numeric metric | births_2007              | Births 2007              | number    | number      |
| Yes      | numeric metric | birth_rate_2007          | Birth Rate 2007          | number    | number      |
| Yes      | numeric metric | birth_rate_2007_lower_ci | Birth Rate 2007 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2007_upper_ci | Birth Rate 2007 Upper CI | number    | number      |
| Yes      | numeric metric | births_2008              | Births 2008              | number    | number      |
| Yes      | numeric metric | birth_rate_2008          | Birth Rate 2008          | number    | number      |
| Yes      | numeric metric | birth_rate_2008_lower_ci | Birth Rate 2008 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2008_upper_ci | Birth Rate 2008 Upper CI | number    | number      |
| Yes      | numeric metric | births_2009              | Births 2009              | number    | number      |
| Yes      | numeric metric | birth_rate_2009          | Birth Rate 2009          | number    | number      |
| Yes      | numeric metric | birth_rate_2009_lower_ci | Birth Rate 2009 Lower CI | number    | number      |
| Yes      | numeric metric | birth_rate_2009_upper_ci | Birth Rate 2009 Upper CI | number    | number      |
```

## Time Field

```ls
Value = 1999
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4arr-givg d:1999-01-01T00:00:00.000Z t:community_area_name="Rogers Park" t:community_area=1 m:births_2004=926 m:birth_rate_2003_upper_ci=17.8 m:births_2003=1024 m:birth_rate_1999_lower_ci=18.3 m:birth_rate_1999_upper_ci=20.5 m:births_2006=934 m:birth_rate_2002_upper_ci=18.9 m:births_2005=892 m:births_2000=1267 m:birth_rate_2007_upper_ci=16.9 m:births_2002=1101 m:births_2001=1187 m:birth_rate_2001_upper_ci=20.1 m:birth_rate_2009_lower_ci=15.3 m:birth_rate_2002=17.8 m:birth_rate_2001=19 m:birth_rate_2000=20 m:birth_rate_2002_lower_ci=16.7 m:birth_rate_2001_lower_ci=17.9 m:birth_rate_2004_lower_ci=14.4 m:birth_rate_2005_lower_ci=14.1 m:birth_rate_2006_upper_ci=17 m:births_2007=912 m:births_2008=892 m:births_1999=1233 m:births_2009=918 m:birth_rate_2000_lower_ci=18.9 m:birth_rate_2003_lower_ci=15.8 m:birth_rate_2000_upper_ci=21.1 m:birth_rate_2008_lower_ci=14.7 m:birth_rate_2003=16.8 m:birth_rate_2004=15.4 m:birth_rate_2005=15.1 m:birth_rate_2006=16 m:birth_rate_2007=15.9 m:birth_rate_2008=15.7 m:birth_rate_2008_upper_ci=16.7 m:birth_rate_2009=16.4 m:birth_rate_2006_lower_ci=15 m:birth_rate_2007_lower_ci=14.9 m:birth_rate_2004_upper_ci=16.4 m:birth_rate_2005_upper_ci=16.1 m:birth_rate_2009_upper_ci=17.5 m:birth_rate_1999=19.4

series e:4arr-givg d:1999-01-01T00:00:00.000Z t:community_area_name="West Ridge" t:community_area=2 m:births_2004=1254 m:birth_rate_2003_upper_ci=18.2 m:births_2003=1249 m:birth_rate_1999_lower_ci=15.9 m:birth_rate_1999_upper_ci=17.7 m:births_2006=1173 m:birth_rate_2002_upper_ci=19.1 m:births_2005=1169 m:births_2000=1268 m:birth_rate_2007_upper_ci=18.5 m:births_2002=1319 m:births_2001=1219 m:birth_rate_2001_upper_ci=17.6 m:birth_rate_2009_lower_ci=16.3 m:birth_rate_2002=18.1 m:birth_rate_2001=16.7 m:birth_rate_2000=17.3 m:birth_rate_2002_lower_ci=17.1 m:birth_rate_2001_lower_ci=15.8 m:birth_rate_2004_lower_ci=16.2 m:birth_rate_2005_lower_ci=15.2 m:birth_rate_2006_upper_ci=17.1 m:births_2007=1262 m:births_2008=1231 m:births_1999=1227 m:births_2009=1247 m:birth_rate_2000_lower_ci=16.3 m:birth_rate_2003_lower_ci=16.2 m:birth_rate_2000_upper_ci=18.3 m:birth_rate_2008_lower_ci=16.1 m:birth_rate_2003=17.2 m:birth_rate_2004=17.2 m:birth_rate_2005=16.1 m:birth_rate_2006=16.2 m:birth_rate_2007=17.5 m:birth_rate_2008=17.1 m:birth_rate_2008_upper_ci=18.1 m:birth_rate_2009=17.3 m:birth_rate_2006_lower_ci=15.3 m:birth_rate_2007_lower_ci=16.5 m:birth_rate_2004_upper_ci=18.2 m:birth_rate_2005_upper_ci=17 m:birth_rate_2009_upper_ci=18.3 m:birth_rate_1999=16.8

series e:4arr-givg d:1999-01-01T00:00:00.000Z t:community_area_name=Uptown t:community_area=3 m:births_2004=748 m:birth_rate_2003_upper_ci=13.5 m:births_2003=774 m:birth_rate_1999_lower_ci=12.4 m:birth_rate_1999_upper_ci=14.2 m:births_2006=810 m:birth_rate_2002_upper_ci=13.7 m:births_2005=795 m:births_2000=881 m:birth_rate_2007_upper_ci=14 m:births_2002=796 m:births_2001=873 m:birth_rate_2001_upper_ci=14.8 m:birth_rate_2009_lower_ci=12.2 m:birth_rate_2002=12.8 m:birth_rate_2001=13.9 m:birth_rate_2000=13.9 m:birth_rate_2002_lower_ci=11.9 m:birth_rate_2001_lower_ci=13 m:birth_rate_2004_lower_ci=11.4 m:birth_rate_2005_lower_ci=12.4 m:birth_rate_2006_upper_ci=14.6 m:births_2007=768 m:births_2008=731 m:births_1999=846 m:births_2009=745 m:birth_rate_2000_lower_ci=13 m:birth_rate_2003_lower_ci=11.7 m:birth_rate_2000_upper_ci=14.8 m:birth_rate_2008_lower_ci=11.7 m:birth_rate_2003=12.6 m:birth_rate_2004=12.3 m:birth_rate_2005=13.3 m:birth_rate_2006=13.7 m:birth_rate_2007=13.1 m:birth_rate_2008=12.6 m:birth_rate_2008_upper_ci=13.5 m:birth_rate_2009=13.1 m:birth_rate_2006_lower_ci=12.8 m:birth_rate_2007_lower_ci=12.2 m:birth_rate_2004_upper_ci=13.2 m:birth_rate_2005_upper_ci=14.2 m:birth_rate_2009_upper_ci=14 m:birth_rate_1999=13.3
```

## Meta Commands

```ls
metric m:births_1999 p:integer l:"Births 1999" d:"Number of births in 1999" t:dataTypeName=number

metric m:birth_rate_1999 p:float l:"Birth Rate 1999" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_1999_lower_ci p:float l:"Birth Rate 1999 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_1999_upper_ci p:float l:"Birth Rate 1999 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2000 p:integer l:"Births 2000" d:"Number of births in 2000" t:dataTypeName=number

metric m:birth_rate_2000 p:float l:"Birth Rate 2000" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2000_lower_ci p:float l:"Birth Rate 2000 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2000_upper_ci p:float l:"Birth Rate 2000 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2001 p:integer l:"Births 2001" d:"Number of births in 2001" t:dataTypeName=number

metric m:birth_rate_2001 p:float l:"Birth Rate 2001" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2001_lower_ci p:float l:"Birth Rate 2001 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2001_upper_ci p:float l:"Birth Rate 2001 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2002 p:integer l:"Births 2002" d:"Number of births in 2002" t:dataTypeName=number

metric m:birth_rate_2002 p:float l:"Birth Rate 2002" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2002_lower_ci p:float l:"Birth Rate 2002 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2002_upper_ci p:float l:"Birth Rate 2002 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2003 p:integer l:"Births 2003" d:"Number of births in 2003" t:dataTypeName=number

metric m:birth_rate_2003 p:float l:"Birth Rate 2003" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2003_lower_ci p:float l:"Birth Rate 2003 Lower CI" d:"Birth rate lower confidence interval (C)" t:dataTypeName=number

metric m:birth_rate_2003_upper_ci p:float l:"Birth Rate 2003 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2004 p:integer l:"Births 2004" d:"Number of births in 2004" t:dataTypeName=number

metric m:birth_rate_2004 p:float l:"Birth Rate 2004" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2004_lower_ci p:double l:"Birth Rate 2004 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2004_upper_ci p:float l:"Birth Rate 2004 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2005 p:integer l:"Births 2005" d:"Number of births in 2005" t:dataTypeName=number

metric m:birth_rate_2005 p:float l:"Birth Rate 2005" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2005_lower_ci p:double l:"Birth Rate 2005 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2005_upper_ci p:float l:"Birth Rate 2005 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2006 p:integer l:"Births 2006" d:"Number of births in 2006" t:dataTypeName=number

metric m:birth_rate_2006 p:float l:"Birth Rate 2006" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2006_lower_ci p:float l:"Birth Rate 2006 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2006_upper_ci p:float l:"Birth Rate 2006 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2007 p:integer l:"Births 2007" d:"Number of births in 2007" t:dataTypeName=number

metric m:birth_rate_2007 p:float l:"Birth Rate 2007" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2007_lower_ci p:float l:"Birth Rate 2007 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2007_upper_ci p:float l:"Birth Rate 2007 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2008 p:integer l:"Births 2008" d:"Number of births in 2008" t:dataTypeName=number

metric m:birth_rate_2008 p:float l:"Birth Rate 2008" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2008_lower_ci p:double l:"Birth Rate 2008 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2008_upper_ci p:double l:"Birth Rate 2008 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2009 p:integer l:"Births 2009" d:"Number of births in 2009" t:dataTypeName=number

metric m:birth_rate_2009 p:float l:"Birth Rate 2009" d:"Number of childbirths per 1000 people" t:dataTypeName=number

metric m:birth_rate_2009_lower_ci p:float l:"Birth Rate 2009 Lower CI" d:"Birth rate lower confidence interval (CI)" t:dataTypeName=number

metric m:birth_rate_2009_upper_ci p:double l:"Birth Rate 2009 Upper CI" d:"Birth rate upper confidence interval (CI)" t:dataTypeName=number

entity e:4arr-givg l:"Public Health Statistics - Births and birth rates in Chicago, by year, 1999 ? 2009" t:attribution="Illinois Department of Public Health (IDPH)" t:url=https://data.cityofchicago.org/api/views/4arr-givg

property e:4arr-givg t:meta.view v:id=4arr-givg v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics - Births and birth rates in Chicago, by year, 1999 ? 2009" v:attribution="Illinois Department of Public Health (IDPH)"

property e:4arr-givg t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:4arr-givg t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| community_area | community_area_name | births_1999 | birth_rate_1999 | birth_rate_1999_lower_ci | birth_rate_1999_upper_ci | births_2000 | birth_rate_2000 | birth_rate_2000_lower_ci | birth_rate_2000_upper_ci | births_2001 | birth_rate_2001 | birth_rate_2001_lower_ci | birth_rate_2001_upper_ci | births_2002 | birth_rate_2002 | birth_rate_2002_lower_ci | birth_rate_2002_upper_ci | births_2003 | birth_rate_2003 | birth_rate_2003_lower_ci | birth_rate_2003_upper_ci | births_2004 | birth_rate_2004 | birth_rate_2004_lower_ci | birth_rate_2004_upper_ci | births_2005 | birth_rate_2005 | birth_rate_2005_lower_ci | birth_rate_2005_upper_ci | births_2006 | birth_rate_2006 | birth_rate_2006_lower_ci | birth_rate_2006_upper_ci | births_2007 | birth_rate_2007 | birth_rate_2007_lower_ci | birth_rate_2007_upper_ci | births_2008 | birth_rate_2008 | birth_rate_2008_lower_ci | birth_rate_2008_upper_ci | births_2009 | birth_rate_2009 | birth_rate_2009_lower_ci | birth_rate_2009_upper_ci | 
| ============== | =================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | =========== | =============== | ======================== | ======================== | 
| 1              | Rogers Park         | 1233        | 19.4            | 18.3                     | 20.5                     | 1267        | 20              | 18.9                     | 21.1                     | 1187        | 19              | 17.9                     | 20.1                     | 1101        | 17.8            | 16.7                     | 18.9                     | 1024        | 16.8            | 15.8                     | 17.8                     | 926         | 15.4            | 14.4                     | 16.4                     | 892         | 15.1            | 14.1                     | 16.1                     | 934         | 16              | 15                       | 17                       | 912         | 15.9            | 14.9                     | 16.9                     | 892         | 15.7            | 14.7                     | 16.7                     | 918         | 16.4            | 15.3                     | 17.5                     | 
| 2              | West Ridge          | 1227        | 16.8            | 15.9                     | 17.7                     | 1268        | 17.3            | 16.3                     | 18.3                     | 1219        | 16.7            | 15.8                     | 17.6                     | 1319        | 18.1            | 17.1                     | 19.1                     | 1249        | 17.2            | 16.2                     | 18.2                     | 1254        | 17.2            | 16.2                     | 18.2                     | 1169        | 16.1            | 15.2                     | 17                       | 1173        | 16.2            | 15.3                     | 17.1                     | 1262        | 17.5            | 16.5                     | 18.5                     | 1231        | 17.1            | 16.1                     | 18.1                     | 1247        | 17.3            | 16.3                     | 18.3                     | 
| 3              | Uptown              | 846         | 13.3            | 12.4                     | 14.2                     | 881         | 13.9            | 13                       | 14.8                     | 873         | 13.9            | 13                       | 14.8                     | 796         | 12.8            | 11.9                     | 13.7                     | 774         | 12.6            | 11.7                     | 13.5                     | 748         | 12.3            | 11.4                     | 13.2                     | 795         | 13.3            | 12.4                     | 14.2                     | 810         | 13.7            | 12.8                     | 14.6                     | 768         | 13.1            | 12.2                     | 14                       | 731         | 12.6            | 11.7                     | 13.5                     | 745         | 13.1            | 12.2                     | 14                       | 
| 4              | Lincoln Square      | 685         | 15.4            | 14.2                     | 16.6                     | 663         | 14.9            | 13.8                     | 16                       | 612         | 13.9            | 12.8                     | 15                       | 648         | 14.9            | 13.8                     | 16                       | 670         | 15.6            | 14.4                     | 16.8                     | 615         | 14.5            | 13.4                     | 15.6                     | 599         | 14.3            | 13.2                     | 15.4                     | 634         | 15.3            | 14.1                     | 16.5                     | 590         | 14.4            | 13.2                     | 15.6                     | 647         | 16              | 14.8                     | 17.2                     | 683         | 17.1            | 15.8                     | 18.4                     | 
| 5              | North Center        | 493         | 15.5            | 14.1                     | 16.9                     | 583         | 18.3            | 16.8                     | 19.8                     | 535         | 16.8            | 15.4                     | 18.2                     | 545         | 17.1            | 15.7                     | 18.5                     | 585         | 18.3            | 16.8                     | 19.8                     | 598         | 18.8            | 17.3                     | 20.3                     | 616         | 19.3            | 17.8                     | 20.8                     | 665         | 20.9            | 19.3                     | 22.5                     | 640         | 20.1            | 18.5                     | 21.7                     | 686         | 21.5            | 19.9                     | 23.1                     | 714         | 22.4            | 20.8                     | 24                       | 
| 6              | Lake View           | 1021        | 10.8            | 10.1                     | 11.5                     | 1058        | 11.2            | 10.5                     | 11.9                     | 1035        | 10.9            | 10.2                     | 11.6                     | 1079        | 11.4            | 10.7                     | 12.1                     | 1123        | 11.9            | 11.2                     | 12.6                     | 1127        | 11.9            | 11.2                     | 12.6                     | 1115        | 11.8            | 11.1                     | 12.5                     | 1071        | 11.3            | 10.6                     | 12                       | 1174        | 12.4            | 11.7                     | 13.1                     | 1177        | 12.5            | 11.8                     | 13.2                     | 1278        | 13.5            | 12.8                     | 14.2                     | 
| 7              | Lincoln Park        | 850         | 13.2            | 12.3                     | 14.1                     | 836         | 13              | 12.1                     | 13.9                     | 854         | 13.3            | 12.4                     | 14.2                     | 872         | 13.6            | 12.7                     | 14.5                     | 897         | 14              | 13.1                     | 14.9                     | 875         | 13.6            | 12.7                     | 14.5                     | 790         | 12.3            | 11.4                     | 13.2                     | 843         | 13.1            | 12.2                     | 14                       | 826         | 12.9            | 12                       | 13.8                     | 788         | 12.3            | 11.4                     | 13.2                     | 849         | 13.2            | 12.3                     | 14.1                     | 
| 8              | Near North Side     | 736         | 10.1            | 9.4                      | 10.8                     | 771         | 10.6            | 9.9                      | 11.3                     | 812         | 11              | 10.2                     | 11.8                     | 769         | 10.3            | 9.6                      | 11                       | 807         | 10.7            | 10                       | 11.4                     | 822         | 10.8            | 10.1                     | 11.5                     | 773         | 10.1            | 9.4                      | 10.8                     | 790         | 10.2            | 9.5                      | 10.9                     | 760         | 9.7             | 9                        | 10.4                     | 825         | 10.4            | 9.7                      | 11.1                     | 856         | 10.7            | 10                       | 11.4                     | 
| 9              | Edison Park         | 134         | 11.9            | 9.9                      | 13.9                     | 145         | 12.9            | 10.8                     | 15                       | 123         | 10.9            | 9                        | 12.8                     | 145         | 12.9            | 10.8                     | 15                       | 129         | 11.5            | 9.5                      | 13.5                     | 147         | 13.1            | 11                       | 15.2                     | 131         | 11.7            | 9.7                      | 13.7                     | 131         | 11.7            | 9.7                      | 13.7                     | 126         | 11.2            | 9.2                      | 13.2                     | 144         | 12.9            | 10.8                     | 15                       | 127         | 11.3            | 9.3                      | 13.3                     | 
| 10             | Norwood Park        | 425         | 11.3            | 10.2                     | 12.4                     | 420         | 11.1            | 10                       | 12.2                     | 427         | 11.4            | 10.3                     | 12.5                     | 443         | 11.8            | 10.7                     | 12.9                     | 447         | 11.9            | 10.8                     | 13                       | 436         | 11.7            | 10.6                     | 12.8                     | 421         | 11.3            | 10.2                     | 12.4                     | 429         | 11.5            | 10.4                     | 12.6                     | 423         | 11.4            | 10.3                     | 12.5                     | 388         | 10.4            | 9.4                      | 11.4                     | 385         | 10.4            | 9.4                      | 11.4                     | 
```