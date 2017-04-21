# Housing and Community Development (2010-2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-and-community-development-2010-2012-0e4d0) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/m3z4-c8pp) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/m3z4-c8pp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/m3z4-c8pp/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | m3z4-c8pp |
| Name | Housing and Community Development (2010-2012) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | housing, development, community, bnia |
| Created | 2014-05-20T14:52:41Z |
| Publication Date | 2014-05-20T15:12:44Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and socioeconomic indicators for neighborhoods. The Census Bureau collects a wide variety of information through administration of both the decennial Census and the annual American Community Survey (ACS).

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010    | text      | text        |
| Yes      | numeric metric | shomes10   | shomes10   | number    | number      |
| Yes      | numeric metric | shomes11   | shomes11   | number    | number      |
| Yes      | numeric metric | shomes12   | shomes12   | number    | number      |
| Yes      | numeric metric | salepr10   | salepr10   | money     | money       |
| Yes      | numeric metric | salepr11   | salepr11   | money     | money       |
| Yes      | numeric metric | salepr12   | salepr12   | money     | money       |
| Yes      | numeric metric | dom10      | dom10      | number    | number      |
| Yes      | numeric metric | dom11      | dom11      | number    | number      |
| Yes      | numeric metric | dom12      | dom12      | number    | number      |
| Yes      | numeric metric | reosa11    | reosa11    | percent   | percent     |
| Yes      | numeric metric | reosa12    | reosa12    | percent   | percent     |
| Yes      | numeric metric | cashsa11   | cashsa11   | percent   | percent     |
| Yes      | numeric metric | cashsa12   | cashsa12   | percent   | percent     |
| Yes      | numeric metric | fore10     | fore10     | percent   | percent     |
| Yes      | numeric metric | fore11     | fore11     | percent   | percent     |
| Yes      | numeric metric | fore12     | fore12     | percent   | percent     |
| Yes      | numeric metric | ownroc10   | ownroc10   | percent   | percent     |
| Yes      | numeric metric | ownroc11   | ownroc11   | percent   | percent     |
| Yes      | numeric metric | ownroc12   | ownroc12   | percent   | percent     |
| Yes      | numeric metric | nomail10   | nomail10   | percent   | percent     |
| Yes      | numeric metric | nomail11   | nomail11   | percent   | percent     |
| Yes      | numeric metric | nomail12   | nomail12   | percent   | percent     |
| Yes      | numeric metric | totalres10 | totalres10 | number    | number      |
| Yes      | numeric metric | totalres11 | totalres11 | number    | number      |
| Yes      | numeric metric | totalres12 | totalres12 | number    | number      |
| Yes      | numeric metric | affordm12  | affordm12  | number    | number      |
| Yes      | numeric metric | affordr12  | affordr12  | number    | number      |
| Yes      | numeric metric | homtax11   | homtax11   | number    | number      |
| Yes      | numeric metric | homtax12   | homtax12   | number    | number      |
| Yes      | numeric metric | owntax11   | owntax11   | number    | number      |
| Yes      | numeric metric | owntax12   | owntax12   | number    | number      |
| Yes      | numeric metric | histax12   | histax12   | number    | number      |
| Yes      | numeric metric | resrehab10 | resrehab10 | percent   | percent     |
| Yes      | numeric metric | resrehab11 | resrehab11 | percent   | percent     |
| Yes      | numeric metric | resrehab12 | resrehab12 | percent   | percent     |
| Yes      | numeric metric | constper11 | constper11 | number    | number      |
| Yes      | numeric metric | constper12 | constper12 | number    | number      |
| Yes      | numeric metric | vacant10   | vacant10   | percent   | percent     |
| Yes      | numeric metric | vacant11   | vacant11   | percent   | percent     |
| Yes      | numeric metric | vacant12   | vacant12   | percent   | percent     |
| Yes      | numeric metric | baltvac11  | baltvac11  | percent   | percent     |
| Yes      | numeric metric | baltvac12  | baltvac12  | percent   | percent     |
| Yes      | numeric metric | vio10      | vio10      | percent   | percent     |
| Yes      | numeric metric | vio11      | vio11      | percent   | percent     |
| Yes      | numeric metric | vio12      | vio12      | percent   | percent     |
| Yes      | numeric metric | demper11   | demper11   | number    | number      |
| Yes      | numeric metric | demper12   | demper12   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m3z4-c8pp d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:dom11=55 m:resrehab10=1.3 m:vacant11=4.7 m:dom12=58 m:vacant10=4.3 m:resrehab12=1.4 m:dom10=85 m:resrehab11=1.6 m:histax12=0 m:fore11=1.3 m:fore12=2 m:constper12=0.9 m:ownroc10=66 m:constper11=0 m:fore10=2.6 m:salepr12=47500 m:salepr10=42500 m:salepr11=30000 m:cashsa11=78.2 m:owntax12=62.3 m:demper12=0.2 m:vacant12=5.1 m:demper11=0.4 m:cashsa12=76.1 m:owntax11=69 m:affordm12=49.8 m:baltvac11=3 m:baltvac12=2.8 m:reosa11=53.5 m:reosa12=29.3 m:vio12=3.3 m:vio11=5.3 m:vio10=5 m:affordr12=53.2 m:totalres10=5568 m:nomail10=9 m:shomes12=76 m:shomes10=118 m:shomes11=80 m:ownroc12=61.8 m:totalres12=5554 m:ownroc11=61.6 m:totalres11=5551 m:homtax11=599.9 m:nomail12=8.4 m:homtax12=550.8 m:nomail11=8.7

series e:m3z4-c8pp d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:dom11=74 m:resrehab10=1.9 m:vacant11=0.4 m:dom12=69 m:vacant10=0.3 m:resrehab12=1.8 m:dom10=102 m:resrehab11=3.1 m:histax12=0.6 m:fore11=1 m:fore12=1.4 m:constper12=0.8 m:ownroc10=82.7 m:constper11=4.8 m:fore10=2.1 m:salepr12=144501 m:salepr10=142250 m:salepr11=120000 m:cashsa11=32.1 m:owntax12=52.5 m:demper12=0 m:vacant12=0.8 m:demper11=0 m:cashsa12=25.4 m:owntax11=56.5 m:affordm12=43.3 m:baltvac11=6.7 m:baltvac12=3.7 m:reosa11=38.5 m:reosa12=9 m:vio12=1.3 m:vio11=3.1 m:vio10=2 m:affordr12=49.9 m:totalres10=3557 m:nomail10=2.3 m:shomes12=64 m:shomes10=72 m:shomes11=84 m:ownroc12=81 m:totalres12=3599 m:ownroc11=79.5 m:totalres11=3575 m:homtax11=740.4 m:nomail12=2.8 m:homtax12=641.6 m:nomail11=2.6

series e:m3z4-c8pp d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:dom11=66 m:resrehab10=1.4 m:vacant11=1.7 m:dom12=46 m:vacant10=1.5 m:resrehab12=1.8 m:dom10=94 m:resrehab11=1.9 m:histax12=0 m:fore11=1.7 m:fore12=2.3 m:constper12=0.3 m:ownroc10=67.2 m:constper11=0 m:fore10=3.2 m:salepr12=60000 m:salepr10=56000 m:salepr11=44000 m:cashsa11=66.7 m:owntax12=52.6 m:demper12=0.3 m:vacant12=2 m:demper11=0 m:cashsa12=67.4 m:owntax11=57.5 m:affordm12=44.5 m:baltvac11=0.9 m:baltvac12=0 m:reosa11=41.1 m:reosa12=23.2 m:vio12=2.6 m:vio11=3.2 m:vio10=2.2 m:affordr12=63.9 m:totalres10=6295 m:nomail10=6.2 m:shomes12=132 m:shomes10=153 m:shomes11=127 m:ownroc12=64.5 m:totalres12=6292 m:ownroc11=64.8 m:totalres11=6296 m:homtax11=613.7 m:nomail12=8.7 m:homtax12=582.8 m:nomail11=6.7
```

## Meta Commands

```ls
metric m:shomes10 p:integer l:shomes10 d:"Number of Homes Sold 2010" t:dataTypeName=number

metric m:shomes11 p:integer l:shomes11 d:"Number of Homes Sold 2011" t:dataTypeName=number

metric m:shomes12 p:integer l:shomes12 d:"Number of Homes Sold 2012" t:dataTypeName=number

metric m:salepr10 p:double l:salepr10 d:"Median Price of Homes Sold 2010" t:dataTypeName=money

metric m:salepr11 p:double l:salepr11 d:"Median Price of Homes Sold 2011" t:dataTypeName=money

metric m:salepr12 p:double l:salepr12 d:"Median Price of Homes Sold 2012" t:dataTypeName=money

metric m:dom10 p:float l:dom10 d:"Median Number of Days on the Market 2010" t:dataTypeName=number

metric m:dom11 p:double l:dom11 d:"Median Number of Days on the Market 2011" t:dataTypeName=number

metric m:dom12 p:integer l:dom12 d:"Median Number of Days on the Market 2012" t:dataTypeName=number

metric m:reosa11 p:float l:reosa11 d:"Percentage of Residential Sales in Foreclosure (REO) 2011" t:dataTypeName=percent

metric m:reosa12 p:float l:reosa12 d:"Percentage of Residential Sales in Foreclosure (REO) 2012" t:dataTypeName=percent

metric m:cashsa11 p:float l:cashsa11 d:"Percentage of Residential Sales for Cash 2011" t:dataTypeName=percent

metric m:cashsa12 p:float l:cashsa12 d:"Percentage of Residential Sales for Cash 2012" t:dataTypeName=percent

metric m:fore10 p:float l:fore10 d:"Percentage of Properties Under Mortgage Foreclosure" t:dataTypeName=percent

metric m:fore11 p:float l:fore11 d:"Percentage of Properties Under Mortgage Foreclosure 2011" t:dataTypeName=percent

metric m:fore12 p:float l:fore12 d:"Percentage of Properties Under Mortgage Foreclosure 2012" t:dataTypeName=percent

metric m:ownroc10 p:float l:ownroc10 d:"Percentage of Housing Units that are Owner-Occupied 2010" t:dataTypeName=percent

metric m:ownroc11 p:float l:ownroc11 d:"Percentage of Housing Units that are Owner-Occupied 2011" t:dataTypeName=percent

metric m:ownroc12 p:float l:ownroc12 d:"Percentage of Housing Units that are Owner-Occupied 2012" t:dataTypeName=percent

metric m:nomail10 p:float l:nomail10 d:"Percent Residential Properties that do Not Receive Mail 2010" t:dataTypeName=percent

metric m:nomail11 p:float l:nomail11 d:"Percent Residential Properties that do Not Receive Mail 2011" t:dataTypeName=percent

metric m:nomail12 p:float l:nomail12 d:"Percent Residential Properties that do Not Receive Mail 2012" t:dataTypeName=percent

metric m:totalres10 p:integer l:totalres10 d:"Total Number of Residential Properties 2010" t:dataTypeName=number

metric m:totalres11 p:integer l:totalres11 d:"Total Number of Residential Properties 2011" t:dataTypeName=number

metric m:totalres12 p:integer l:totalres12 d:"Total Number of Residential Properties 2012" t:dataTypeName=number

metric m:affordm12 p:float l:affordm12 d:"Affordability Index - Mortgage 2012" t:dataTypeName=number

metric m:affordr12 p:float l:affordr12 d:"Affordability Index - Rent 2012" t:dataTypeName=number

metric m:homtax11 p:float l:homtax11 d:"Number of Homestead Tax Credits per 1,000 Residential Units 2011" t:dataTypeName=number

metric m:homtax12 p:float l:homtax12 d:"Number of Homestead Tax Credits per 1,000 Residential Units 2012" t:dataTypeName=number

metric m:owntax11 p:float l:owntax11 d:"Number of Homeowner's Tax Credits per 1,000 Residential Units 2011" t:dataTypeName=number

metric m:owntax12 p:float l:owntax12 d:"Number of Homeowner's Tax Credits per 1,000 Residential Units 2012" t:dataTypeName=number

metric m:histax12 p:float l:histax12 d:"Number of Historic Tax Credits per 1,000 Residential Units 2012" t:dataTypeName=number

metric m:resrehab10 p:float l:resrehab10 d:"Percentage of Properties with Rehabilitation Permits Exceeding $5,000 2010" t:dataTypeName=percent

metric m:resrehab11 p:float l:resrehab11 d:"Percentage of Properties with Rehabilitation Permits Exceeding $5,000 2011" t:dataTypeName=percent

metric m:resrehab12 p:float l:resrehab12 d:"Percentage of Properties with Rehabilitation Permits Exceeding $5,000 2012" t:dataTypeName=percent

metric m:constper11 p:float l:constper11 d:"Number of New Construction Permits per 1,000 Residential Properties 2011" t:dataTypeName=number

metric m:constper12 p:float l:constper12 d:"Number of New Construction Permits per 1,000 Residential Properties 2012" t:dataTypeName=number

metric m:vacant10 p:float l:vacant10 d:"Percentage of Residential Properties that are Vacant and Abandoned 2010" t:dataTypeName=percent

metric m:vacant11 p:float l:vacant11 d:"Percentage of Residential Properties that are Vacant and Abandoned 2011" t:dataTypeName=percent

metric m:vacant12 p:float l:vacant12 d:"Percentage of Residential Properties that are Vacant and Abandoned 2012" t:dataTypeName=percent

metric m:baltvac11 p:float l:baltvac11 d:"Percentage of Vacant Properties Owned by Baltimore City 2011" t:dataTypeName=percent

metric m:baltvac12 p:float l:baltvac12 d:"Percentage of Vacant Properties Owned by Baltimore City 2012" t:dataTypeName=percent

metric m:vio10 p:float l:vio10 d:"Percentage of Residential Properties with Housing Violations (Excluding Vacants) 2010" t:dataTypeName=percent

metric m:vio11 p:float l:vio11 d:"Percentage of Residential Properties with Housing Violations (Excluding Vacants) 2011" t:dataTypeName=percent

metric m:vio12 p:float l:vio12 d:"Percentage of Residential Properties with Housing Violations (Excluding Vacants) 2012" t:dataTypeName=percent

metric m:demper11 p:float l:demper11 d:"Number of Demolition Permits per 1,000 Residential Properties 2011" t:dataTypeName=number

metric m:demper12 p:float l:demper12 d:"Number of Demolition Permits per 1,000 Residential Properties 2012" t:dataTypeName=number

entity e:m3z4-c8pp l:"Housing and Community Development (2010-2012)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/m3z4-c8pp

property e:m3z4-c8pp t:meta.view v:id=m3z4-c8pp v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Housing and Community Development (2010-2012)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:m3z4-c8pp t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:m3z4-c8pp t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:m3z4-c8pp t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | shomes10 | shomes11 | shomes12 | salepr10  | salepr11  | salepr12  | dom10 | dom11 | dom12 | reosa11 | reosa12 | cashsa11 | cashsa12 | fore10 | fore11 | fore12 | ownroc10 | ownroc11 | ownroc12 | nomail10 | nomail11 | nomail12 | totalres10 | totalres11 | totalres12 | affordm12 | affordr12 | homtax11 | homtax12 | owntax11 | owntax12 | histax12 | resrehab10 | resrehab11 | resrehab12 | constper11 | constper12 | vacant10 | vacant11 | vacant12 | baltvac11 | baltvac12 | vio10 | vio11 | vio12 | demper11 | demper12 | 
| ================================= | ======== | ======== | ======== | ========= | ========= | ========= | ===== | ===== | ===== | ======= | ======= | ======== | ======== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ========== | ========== | ========== | ========= | ========= | ======== | ======== | ======== | ======== | ======== | ========== | ========== | ========== | ========== | ========== | ======== | ======== | ======== | ========= | ========= | ===== | ===== | ===== | ======== | ======== | 
| Allendale/Irvington/S. Hilton     | 118      | 80       | 76       | 42500.00  | 30000.00  | 47500.00  | 85    | 55    | 58    | 53.5    | 29.3    | 78.2     | 76.1     | 2.6    | 1.3    | 2.0    | 66.0     | 61.6     | 61.8     | 9.0      | 8.7      | 8.4      | 5568       | 5551       | 5554       | 49.8      | 53.2      | 599.9    | 550.8    | 69.0     | 62.3     | 0.0      | 1.3        | 1.6        | 1.4        | 0.0        | 0.9        | 4.3      | 4.7      | 5.1      | 3.0       | 2.8       | 5.0   | 5.3   | 3.3   | 0.4      | 0.2      | 
| Beechfield/Ten Hills/West Hills   | 72       | 84       | 64       | 142250.00 | 120000.00 | 144501.00 | 102   | 74    | 69    | 38.5    | 9.0     | 32.1     | 25.4     | 2.1    | 1.0    | 1.4    | 82.7     | 79.5     | 81.0     | 2.3      | 2.6      | 2.8      | 3557       | 3575       | 3599       | 43.3      | 49.9      | 740.4    | 641.6    | 56.5     | 52.5     | 0.6      | 1.9        | 3.1        | 1.8        | 4.8        | 0.8        | 0.3      | 0.4      | 0.8      | 6.7       | 3.7       | 2.0   | 3.1   | 1.3   | 0.0      | 0.0      | 
| Belair-Edison                     | 153      | 127      | 132      | 56000.00  | 44000.00  | 60000.00  | 94    | 66    | 46    | 41.1    | 23.2    | 66.7     | 67.4     | 3.2    | 1.7    | 2.3    | 67.2     | 64.8     | 64.5     | 6.2      | 6.7      | 8.7      | 6295       | 6296       | 6292       | 44.5      | 63.9      | 613.7    | 582.8    | 57.5     | 52.6     | 0.0      | 1.4        | 1.9        | 1.8        | 0.0        | 0.3        | 1.5      | 1.7      | 2.0      | 0.9       | 0.0       | 2.2   | 3.2   | 2.6   | 0.0      | 0.3      | 
| Brooklyn/Curtis Bay/Hawkins Point | 104      | 86       | 84       | 58005.00  | 42950.00  | 47049.50  | 108   | 67.5  | 59    | 42.6    | 23.7    | 73.4     | 72.0     | 2.8    | 1.3    | 1.8    | 50.4     | 46.2     | 46.9     | 8.9      | 8.8      | 9.9      | 4283       | 4259       | 4256       | 38.8      | 51.4      | 382.0    | 364.4    | 51.0     | 47.2     | 0.0      | 1.3        | 1.0        | 1.2        | 0.5        | 0.5        | 3.7      | 4.2      | 5.0      | 2.7       | 3.8       | 3.7   | 4.3   | 3.1   | 0.9      | 3.8      | 
| Canton                            | 230      | 199      | 288      | 251000.00 | 231000.00 | 261200.00 | 82    | 58    | 27    | 14.0    | 3.9     | 26.6     | 20.1     | 1.8    | 0.5    | 0.6    | 69.9     | 67.9     | 68.7     | 7.7      | 7.4      | 6.4      | 4013       | 4017       | 4025       | 38.2      | 35.0      | 448.3    | 355.8    | 46.6     | 43.0     | 28.1     | 4.0        | 5.3        | 6.6        | 0.3        | 1.0        | 0.9      | 0.7      | 0.8      | 0.0       | 0.0       | 0.6   | 0.4   | 0.5   | 0.0      | 0.5      | 
| Cedonia/Frankford                 | 195      | 171      | 141      | 103225.00 | 88000.00  | 94500.00  | 98.5  | 71    | 48    | 42.6    | 16.9    | 45.4     | 42.2     | 2.9    | 1.3    | 2.4    | 79.2     | 76.5     | 76.1     | 4.8      | 5.2      | 6.2      | 6294       | 6290       | 6286       | 53.8      | 59.5      | 720.5    | 683.4    | 69.3     | 68.7     | 0.0      | 1.9        | 1.6        | 2.1        | 0.5        | 1.1        | 0.7      | 0.6      | 1.1      | 2.6       | 1.4       | 1.6   | 2.6   | 1.0   | 0.2      | 0.0      | 
| Cherry Hill                       | 9        | 8        | 6        | 69000.00  | 61050.00  | 16000.00  | 141   | 92    | 28    | 15.4    | 6.7     | 61.5     | 86.7     | 2.0    | 1.0    | 0.6    | 54.7     | 53.0     | 53.0     | 3.1      | 3.3      | 4.4      | 988        | 985        | 985        | 24.2      | 43.4      | 510.7    | 500.5    | 67.0     | 66.0     | 0.0      | 0.4        | 0.5        | 0.2        | 0.0        | 0.0        | 3.4      | 3.7      | 4.0      | 5.4       | 5.1       | 2.9   | 5.2   | 2.4   | 0.0      | 0.0      | 
| Chinquapin Park/Belvedere         | 74       | 59       | 63       | 117450.00 | 130000.00 | 124000.00 | 103   | 78    | 54    | 24.2    | 11.5    | 40.3     | 31.1     | 2.0    | 0.9    | 1.6    | 74.0     | 70.3     | 71.6     | 6.0      | 5.3      | 4.3      | 2694       | 2688       | 2689       | 36.7      | 59.4      | 674.9    | 636.7    | 61.0     | 58.0     | 0.0      | 2.3        | 1.8        | 1.3        | 0.0        | 0.0        | 0.3      | 0.6      | 0.7      | 0.0       | 5.6       | 2.3   | 3.8   | 2.9   | 0.4      | 0.0      | 
| Claremont/Armistead               | 16       | 18       | 6        | 139000.00 | 135000.00 | 79200.00  | 135   | 43    | 49    | 31.6    | 20.0    | 52.6     | 40.0     | 4.7    | 0.8    | 2.0    | 76.6     | 70.9     | 75.2     | 3.6      | 3.9      | 4.6      | 725        | 755        | 745        | 46.0      | 49.7      | 543.1    | 567.8    | 46.4     | 44.3     | 0.0      | 1.5        | 2.7        | 4.6        | 6.6        | 49.7       | 0.0      | 0.3      | 0.3      | 0.0       | 0.0       | 3.3   | 2.8   | 3.6   | 0.0      | 0.0      | 
| Clifton-Berea                     | 87       | 76       | 40       | 13250.00  | 16050.00  | 21250.00  | 71    | 44.5  | 36    | 53.1    | 14.6    | 90.6     | 85.4     | 1.7    | 0.5    | 0.9    | 35.8     | 34.4     | 34.0     | 9.5      | 8.8      | 9.6      | 4783       | 4756       | 4738       | 40.6      | 55.7      | 162.7    | 135.5    | 30.7     | 27.0     | 0.2      | 1.7        | 1.2        | 1.5        | 0.0        | 0.0        | 24.5     | 23.7     | 24.1     | 17.4      | 15.7      | 11.3  | 12.7  | 11.8  | 4.8      | 4.0      | 
```