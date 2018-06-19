# Sustainability (2010-2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sustainability-2010-2012-ef16d) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/3khh-rk6j) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/3khh-rk6j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/3khh-rk6j/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 3khh-rk6j |
| Name | Sustainability (2010-2012) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | sustainability, bnia |
| Created | 2014-05-20T17:29:23Z |
| Publication Date | 2014-05-20T17:36:24Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and socioeconomic indicators for neighborhoods. The Census Bureau collects a wide variety of information through administration of both the decennial Census and the annual American Community Survey (ACS).

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010    | text      | text        |
| Yes      | numeric metric | regvote10  | regvote10  | percent   | percent     |
| Yes      | numeric metric | regvote12  | regvote12  | percent   | percent     |
| Yes      | numeric metric | voted10    | voted10    | percent   | percent     |
| Yes      | numeric metric | voted12    | voted12    | percent   | percent     |
| Yes      | numeric metric | dirtyst10  | dirtyst10  | number    | number      |
| Yes      | numeric metric | dirtyst11  | dirtyst11  | number    | number      |
| Yes      | numeric metric | dirtyst12  | dirtyst12  | number    | number      |
| Yes      | numeric metric | clogged10  | clogged10  | number    | number      |
| Yes      | numeric metric | clogged11  | clogged11  | number    | number      |
| Yes      | numeric metric | clogged12  | clogged12  | number    | number      |
| Yes      | numeric metric | drvalone12 | drvalone12 | percent   | percent     |
| Yes      | numeric metric | carpool12  | carpool12  | percent   | percent     |
| Yes      | numeric metric | pubtran12  | pubtran12  | percent   | percent     |
| Yes      | numeric metric | walked12   | walked12   | percent   | percent     |
| Yes      | numeric metric | trav14_12  | trav14_12  | percent   | percent     |
| Yes      | numeric metric | trav29_12  | trav29_12  | percent   | percent     |
| Yes      | numeric metric | trav44_12  | trav44_12  | percent   | percent     |
| Yes      | numeric metric | trav45_12  | trav45_12  | percent   | percent     |
| Yes      | numeric metric | trees07    | trees07    | percent   | percent     |
| Yes      | numeric metric | cmos11     | cmos11     | number    | number      |
| Yes      | numeric metric | waterc11   | waterc11   | number    | number      |
| Yes      | numeric metric | heatgas12  | heatgas12  | percent   | percent     |
| Yes      | numeric metric | elheat12   | elheat12   | percent   | percent     |
| Yes      | numeric metric | novhcl12   | novhcl12   | percent   | percent     |
| Yes      | numeric metric | weather10  | weather10  | percent   | percent     |
| Yes      | numeric metric | weather11  | weather11  | percent   | percent     |
| Yes      | numeric metric | weather12  | weather12  | percent   | percent     |
| Yes      | numeric metric | wlksc11    | wlksc11    | number    | number      |
| Yes      | numeric metric | bkln12     | bkln12     | number    | number      |
| Yes      | numeric metric | othrcom12  | othrcom12  | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3khh-rk6j d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:carpool12=12.1 m:voted12=57 m:voted10=45.3 m:trav45_12=21.6 m:heatgas12=68.1 m:trav44_12=25.7 m:clogged12=6.2 m:othrcom12=1.7 m:drvalone12=61.7 m:clogged10=4.2 m:clogged11=4.6 m:trees07=32.7 m:wlksc11=44 m:waterc11=16 m:cmos11=6 m:regvote12=82.8 m:regvote10=83.4 m:trav29_12=40 m:weather10=0.5 m:weather12=0.4 m:weather11=0.4 m:walked12=4.5 m:pubtran12=19.9 m:bkln12=2.4 m:trav14_12=12.7 m:elheat12=18.9 m:dirtyst11=41 m:dirtyst10=41.7 m:novhcl12=31 m:dirtyst12=48.1

series e:3khh-rk6j d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:carpool12=8.6 m:voted12=61.9 m:voted10=52.6 m:trav45_12=14.5 m:heatgas12=76.9 m:trav44_12=25 m:clogged12=4.8 m:othrcom12=0.7 m:drvalone12=75.9 m:clogged10=3.4 m:clogged11=3.3 m:trees07=48.1 m:wlksc11=32.5 m:waterc11=17 m:cmos11=7 m:regvote12=81.6 m:regvote10=79.7 m:trav29_12=45.3 m:weather10=0.5 m:weather12=0.4 m:weather11=0.3 m:walked12=1.7 m:pubtran12=13.2 m:bkln12=4.2 m:trav14_12=15.2 m:elheat12=14.4 m:dirtyst11=12.2 m:dirtyst10=10.5 m:novhcl12=16 m:dirtyst12=13.9

series e:3khh-rk6j d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:carpool12=12.2 m:voted12=59.8 m:voted10=46.6 m:trav45_12=19.6 m:heatgas12=71.8 m:trav44_12=32 m:clogged12=3.8 m:othrcom12=1.8 m:drvalone12=66.9 m:clogged10=4.1 m:clogged11=6.1 m:trees07=20.1 m:wlksc11=62.3 m:waterc11=17 m:cmos11=6 m:regvote12=83.2 m:regvote10=81.7 m:trav29_12=38.3 m:weather10=0.6 m:weather12=0.6 m:weather11=0.3 m:walked12=2.7 m:pubtran12=16.3 m:bkln12=0.2 m:trav14_12=10.1 m:elheat12=11.2 m:dirtyst11=66.3 m:dirtyst10=90.2 m:novhcl12=27.2 m:dirtyst12=79.1
```

## Meta Commands

```ls
metric m:regvote10 p:float l:regvote10 d:"Percent of Population (Over the age of 18) Who are Registered to Vote (2010)" t:dataTypeName=percent

metric m:regvote12 p:float l:regvote12 d:"Percent of Population (Over the age of 18) Who are Registered to Vote (2012)" t:dataTypeName=percent

metric m:voted10 p:float l:voted10 d:"Percent Population (Over the age of 18) Who Voted in the General Election (2010)" t:dataTypeName=percent

metric m:voted12 p:float l:voted12 d:"Percent Population (Over the age of 18) Who Voted in the General Election (2012)" t:dataTypeName=percent

metric m:dirtyst10 p:float l:dirtyst10 d:"Rate of Dirty Streets and Alleys Reports per 1,000 Residents (2010)" t:dataTypeName=number

metric m:dirtyst11 p:float l:dirtyst11 d:"Rate of Dirty Streets and Alleys Reports per 1,000 Residents (2011)" t:dataTypeName=number

metric m:dirtyst12 p:float l:dirtyst12 d:"Rate of Dirty Streets and Alleys Reports per 1,000 Residents (2012)" t:dataTypeName=number

metric m:clogged10 p:float l:clogged10 d:"Rate of Clogged Storm Drain Reports per 1,000 Residents (2010)" t:dataTypeName=number

metric m:clogged11 p:float l:clogged11 d:"Rate of Clogged Storm Drain Reports per 1,000 Residents (2011)" t:dataTypeName=number

metric m:clogged12 p:float l:clogged12 d:"Rate of Clogged Storm Drain Reports per 1,000 Residents (2012)" t:dataTypeName=number

metric m:drvalone12 p:float l:drvalone12 d:"Percent of Population that Drove Alone to Work (2008-2012)" t:dataTypeName=percent

metric m:carpool12 p:float l:carpool12 d:"Percent of Population that Carpool to Work (2008-2012)" t:dataTypeName=percent

metric m:pubtran12 p:float l:pubtran12 d:"Percent of Population that Uses Public Transportation to Get to Work (2008-2012)" t:dataTypeName=percent

metric m:walked12 p:float l:walked12 d:"Percent of Population that Walks to Work (2008-2012)" t:dataTypeName=percent

metric m:trav14_12 p:float l:trav14_12 d:"Percent of Employed Population with Travel Time to Work of 0-14 Minutes (2008-2012)" t:dataTypeName=percent

metric m:trav29_12 p:float l:trav29_12 d:"Percent of Employed Population with Travel Time to Work of 15-29 Minutes (2008-2012)" t:dataTypeName=percent

metric m:trav44_12 p:float l:trav44_12 d:"Percent of Employed Population with Travel Time to Work of 30-44 Minutes (2008-2012)" t:dataTypeName=percent

metric m:trav45_12 p:float l:trav45_12 d:"Percent of Employed Population with Travel Time to Work of 45 Minutes and Over (2008-2012)" t:dataTypeName=percent

metric m:trees07 p:float l:trees07 d:"Percent of Area Covered by Trees (2007)" t:dataTypeName=percent

metric m:cmos11 p:integer l:cmos11 d:"Number of Community Managed Open Spaces (2011)" t:dataTypeName=number

metric m:waterc11 p:double l:waterc11 d:"Median Daily Water Consumption (2011)" t:dataTypeName=number

metric m:heatgas12 p:float l:heatgas12 d:"Percent of Residences Heated by Utility Gas (2008-2012)" t:dataTypeName=percent

metric m:elheat12 p:float l:elheat12 d:"Percent of Residences Heated by Electricity (2008-2012)" t:dataTypeName=percent

metric m:novhcl12 p:float l:novhcl12 d:"Percent of Households with No Vehicles Available (2008-2012)" t:dataTypeName=percent

metric m:weather10 p:float l:weather10 d:"Percent of Residential Properties Weatherized (2010)" t:dataTypeName=percent

metric m:weather11 p:float l:weather11 d:"Percent of Residential Properties Weatherized (2011)" t:dataTypeName=percent

metric m:weather12 p:float l:weather12 d:"Percent of Residential Properties Weatherized (2012)" t:dataTypeName=percent

metric m:wlksc11 p:float l:wlksc11 d:"Walk Score (2012)" t:dataTypeName=number

metric m:bkln12 p:float l:bkln12 d:"Number of Miles of Bike Lanes (2012)" t:dataTypeName=number

metric m:othrcom12 p:float l:othrcom12 d:"Percent of Population Using Other Means to Commute to Work (Taxi, Motorcycle, Bicycle, Other) (2008-2012)" t:dataTypeName=percent

entity e:3khh-rk6j l:"Sustainability (2010-2012)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/3khh-rk6j

property e:3khh-rk6j t:meta.view v:id=3khh-rk6j v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Sustainability (2010-2012)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:3khh-rk6j t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:3khh-rk6j t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:3khh-rk6j t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | regvote10 | regvote12 | voted10 | voted12 | dirtyst10 | dirtyst11 | dirtyst12 | clogged10 | clogged11 | clogged12 | drvalone12 | carpool12 | pubtran12 | walked12 | trav14_12 | trav29_12 | trav44_12 | trav45_12 | trees07 | cmos11 | waterc11           | heatgas12 | elheat12 | novhcl12 | weather10 | weather11 | weather12 | wlksc11 | bkln12 | othrcom12 | 
| ================================= | ========= | ========= | ======= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========= | ========= | ======== | ========= | ========= | ========= | ========= | ======= | ====== | ================== | ========= | ======== | ======== | ========= | ========= | ========= | ======= | ====== | ========= | 
| Allendale/Irvington/S. Hilton     | 83.4      | 82.8      | 45.3    | 57.0    | 41.7      | 41.0      | 48.1      | 4.2       | 4.6       | 6.2       | 61.7       | 12.1      | 19.9      | 4.5      | 12.7      | 40.0      | 25.7      | 21.6      | 32.7    | 6      | 16                 | 68.1      | 18.9     | 31.0     | 0.5       | 0.4       | 0.4       | 44.0    | 2.4    | 1.7       | 
| Beechfield/Ten Hills/West Hills   | 79.7      | 81.6      | 52.6    | 61.9    | 10.5      | 12.2      | 13.9      | 3.4       | 3.3       | 4.8       | 75.9       | 8.6       | 13.2      | 1.7      | 15.2      | 45.3      | 25.0      | 14.5      | 48.1    | 7      | 17                 | 76.9      | 14.4     | 16.0     | 0.5       | 0.3       | 0.4       | 32.5    | 4.2    | 0.7       | 
| Belair-Edison                     | 81.7      | 83.2      | 46.6    | 59.8    | 90.2      | 66.3      | 79.1      | 4.1       | 6.1       | 3.8       | 66.9       | 12.2      | 16.3      | 2.7      | 10.1      | 38.3      | 32.0      | 19.6      | 20.1    | 6      | 17                 | 71.8      | 11.2     | 27.2     | 0.6       | 0.3       | 0.6       | 62.3    | 0.2    | 1.8       | 
| Brooklyn/Curtis Bay/Hawkins Point | 53.6      | 53.3      | 30.1    | 28.3    | 91.5      | 112.1     | 82.8      | 4.2       | 5.8       | 5.5       | 51.9       | 20.0      | 20.7      | 3.5      | 22.6      | 28.8      | 28.0      | 20.5      | 15.1    | 7      | 17                 | 70.1      | 23.0     | 33.8     | 1.4       | 9.1       | 0.9       | 17.7    | 3.2    | 3.9       | 
| Canton                            | 79.5      | 71.5      | 43.2    | 52.0    | 32.8      | 38.5      | 38.3      | 6.3       | 8.9       | 5.9       | 80.6       | 3.8       | 6.2       | 5.8      | 18.5      | 44.8      | 23.5      | 13.2      | 9.6     | 3      | 12                 | 65.8      | 29.7     | 11.0     | 0.0       | 0.0       | 0.1       | 89.2    | 2.8    | 3.6       | 
| Cedonia/Frankford                 | 73.9      | 78.5      | 46.6    | 56.2    | 22.5      | 24.2      | 24.3      | 2.5       | 5.6       | 3.1       | 68.5       | 12.1      | 17.2      | 1.7      | 10.1      | 40.0      | 27.4      | 22.6      | 28.8    | 6      | 18                 | 73.4      | 18.1     | 25.2     | 0.4       | 0.3       | 0.6       | 57.4    | 2.2    | 0.5       | 
| Cherry Hill                       | 82.5      | 82.3      | 34.9    | 53.1    | 11.7      | 12.7      | 7.2       | 1.2       | 3.7       | 2.9       | 42.8       | 17.9      | 37.3      | 2.0      | 17.1      | 37.0      | 20.2      | 25.7      | 19.0    | 0      | 17                 | 63.8      | 30.1     | 51.0     | 15.7      | 74.4      | 8.1       | 38.1    | 2.8    | 0.0       | 
| Chinquapin Park/Belvedere         | 83.2      | 85.9      | 51.2    | 61.9    | 26.3      | 32.1      | 47.3      | 5.0       | 4.3       | 6.1       | 71.6       | 8.5       | 10.6      | 6.6      | 21.7      | 36.2      | 23.7      | 18.4      | 39.4    | 3      | 15                 | 70.2      | 21.7     | 21.8     | 0.4       | 0.3       | 0.6       | 74.6    | 0.8    | 2.8       | 
| Claremont/Armistead               | 60.7      | 60.9      | 37.8    | 39.0    | 8.1       | 12.6      | 17.1      | 1.6       | 2.9       | 3.0       | 64.5       | 14.1      | 18.4      | 2.4      | 13.5      | 25.6      | 35.8      | 25.1      | 28.0    | 1      | 25                 | 82.1      | 16.1     | 26.1     | 1.0       | 0.5       | 0.7       | 31.0    | 1.3    | 0.6       | 
| Clifton-Berea                     | 91.5      | 89.5      | 40.3    | 57.5    | 167.2     | 171.9     | 167.7     | 10.9      | 9.9       | 9.9       | 46.1       | 12.7      | 38.5      | 1.8      | 11.8      | 32.7      | 28.9      | 26.6      | 8.3     | 25     | 14.000000000000002 | 65.6      | 16.8     | 49.3     | 0.4       | 0.4       | 0.3       | 58.3    | 0.5    | 1.0       | 
```