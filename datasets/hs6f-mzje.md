# Workforce and Economic Development (2010-2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/workforce-and-economic-development-2010-2012-8f44e) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/hs6f-mzje) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/hs6f-mzje/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/hs6f-mzje/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | hs6f-mzje |
| Name | Workforce and Economic Development (2010-2012) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | work, workforce, economic, bnia |
| Created | 2014-05-20T16:01:49Z |
| Publication Date | 2014-05-20T16:12:42Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and socioeconomic indicators for neighborhoods. The Census Bureau collects a wide variety of information through administration of both the decennial Census and the annual American Community Survey (ACS).

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010   | text      | text        |
| Yes      | numeric metric | empl12     | empl12    | percent   | percent     |
| Yes      | numeric metric | unempl12   | unempl12  | percent   | percent     |
| Yes      | numeric metric | nilf12     | nilf12    | percent   | percent     |
| Yes      | numeric metric | unempr12   | unempr12  | number    | number      |
| Yes      | numeric metric | lesshs12   | lesshs12  | percent   | percent     |
| Yes      | numeric metric | hsdipl12   | hsdipl12  | percent   | percent     |
| Yes      | numeric metric | somecol12  | somecol12 | percent   | percent     |
| Yes      | numeric metric | wrkout10   | wrkout10  | percent   | percent     |
| Yes      | numeric metric | wrkout11   | wrkout11  | percent   | percent     |
| Yes      | numeric metric | comprop10  | comprop10 | number    | number      |
| Yes      | numeric metric | comprop11  | comprop11 | number    | number      |
| Yes      | numeric metric | comprop12  | comprop12 | number    | number      |
| Yes      | numeric metric | crehab10   | crehab10  | percent   | percent     |
| Yes      | numeric metric | crehab11   | crehab11  | percent   | percent     |
| Yes      | numeric metric | crehab12   | crehab12  | percent   | percent     |
| Yes      | numeric metric | banks11    | banks11   | number    | number      |
| Yes      | numeric metric | banks12    | banks12   | number    | number      |
| Yes      | numeric metric | numbus10   | numbus10  | number    | number      |
| Yes      | numeric metric | numbus11   | numbus11  | number    | number      |
| Yes      | numeric metric | numbus12   | numbus12  | number    | number      |
| Yes      | numeric metric | totemp10   | totemp10  | number    | number      |
| Yes      | numeric metric | totemp11   | totemp11  | number    | number      |
| Yes      | numeric metric | totemp12   | totemp12  | number    | number      |
| Yes      | numeric metric | smlbus10   | smlbus10  | number    | number      |
| Yes      | numeric metric | smlbus11   | smlbus11  | number    | number      |
| Yes      | numeric metric | smlbus12   | smlbus12  | number    | number      |
| Yes      | numeric metric | biz1_10    | biz1_10   | percent   | percent     |
| Yes      | numeric metric | biz1_11    | biz1_11   | percent   | percent     |
| Yes      | numeric metric | biz1_12    | biz1_12   | percent   | percent     |
| Yes      | numeric metric | biz2_10    | biz2_10   | percent   | percent     |
| Yes      | numeric metric | biz2_11    | biz2_11   | percent   | percent     |
| Yes      | numeric metric | biz2_12    | biz2_12   | percent   | percent     |
| Yes      | numeric metric | biz4_10    | biz4_10   | percent   | percent     |
| Yes      | numeric metric | biz4_11    | biz4_11   | percent   | percent     |
| Yes      | numeric metric | biz4_12    | biz4_12   | percent   | percent     |
| Yes      | numeric metric | neiind10   | neiind10  | number    | number      |
| Yes      | numeric metric | neiind11   | neiind11  | number    | number      |
| Yes      | numeric metric | neiind12   | neiind12  | number    | number      |
| Yes      | numeric metric | neibus10   | neibus10  | number    | number      |
| Yes      | numeric metric | neibus11   | neibus11  | number    | number      |
| Yes      | numeric metric | neibus12   | neibus12  | number    | number      |
| Yes      | numeric metric | neiemp10   | neiemp10  | number    | number      |
| Yes      | numeric metric | neiemp11   | neiemp11  | number    | number      |
| Yes      | numeric metric | neiemp12   | neiemp12  | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hs6f-mzje d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:neiind10=183 m:neiind11=161 m:neiind12=162 m:lesshs12=24.5 m:wrkout11=59 m:nilf12=29.1 m:wrkout10=60.3 m:numbus10=269 m:numbus11=237 m:numbus12=253 m:banks11=0 m:biz2_11=15.6 m:biz2_12=24.5 m:banks12=0 m:neibus11=9.9 m:neiemp12=1370 m:neibus12=10 m:neiemp11=1378 m:somecol12=11 m:neiemp10=1503 m:neibus10=11.3 m:biz2_10=19.3 m:unempl12=13.6 m:hsdipl12=64.5 m:unempr12=19.2 m:comprop10=279 m:comprop11=278 m:smlbus11=226 m:biz1_12=9.5 m:comprop12=284 m:empl12=57.7 m:smlbus12=242 m:totemp11=2502 m:biz1_10=8.9 m:totemp10=2778 m:smlbus10=255 m:biz1_11=11 m:totemp12=2629 m:biz4_11=29.1 m:biz4_12=34.8 m:crehab11=8.6 m:crehab10=13.3 m:biz4_10=33.8 m:crehab12=13.7

series e:hs6f-mzje d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:neiind10=98 m:neiind11=87 m:neiind12=88 m:lesshs12=14.2 m:wrkout11=66.9 m:nilf12=23.2 m:wrkout10=62.5 m:numbus10=154 m:numbus11=136 m:numbus12=141 m:banks11=0.1 m:biz2_11=12.5 m:biz2_12=12.1 m:banks12=0.1 m:neibus11=7.1 m:neiemp12=684 m:neibus12=7.2 m:neiemp11=663 m:somecol12=22.3 m:neiemp10=753 m:neibus10=8 m:biz2_10=22.1 m:unempl12=10.1 m:hsdipl12=63.5 m:unempr12=13.3 m:comprop10=47 m:comprop11=47 m:smlbus11=130 m:biz1_12=4.3 m:comprop12=46 m:empl12=66.9 m:smlbus12=134 m:totemp11=1329 m:biz1_10=3.9 m:totemp10=1462 m:smlbus10=148 m:biz1_11=8.1 m:totemp12=1383 m:biz4_11=30.1 m:biz4_12=29.8 m:crehab11=27.7 m:crehab10=25.5 m:biz4_10=32.5 m:crehab12=4.3

series e:hs6f-mzje d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:neiind10=172 m:neiind11=172 m:neiind12=189 m:lesshs12=18.8 m:wrkout11=49.4 m:nilf12=25.8 m:wrkout10=48.5 m:numbus10=225 m:numbus11=224 m:numbus12=251 m:banks11=0.2 m:biz2_11=18.8 m:biz2_12=23.5 m:banks12=0.1 m:neibus11=9.9 m:neiemp12=1008 m:neibus12=10.9 m:neiemp11=915 m:somecol12=14 m:neiemp10=1044 m:neibus10=9.9 m:biz2_10=22.7 m:unempl12=12 m:hsdipl12=67.2 m:unempr12=16.3 m:comprop10=165 m:comprop11=165 m:smlbus11=217 m:biz1_12=7.6 m:comprop12=165 m:empl12=62.3 m:smlbus12=244 m:totemp11=1540 m:biz1_10=8.9 m:totemp10=1590 m:smlbus10=217 m:biz1_11=12.1 m:totemp12=1605 m:biz4_11=31.3 m:biz4_12=38.6 m:crehab11=10.9 m:crehab10=8.5 m:biz4_10=31.6 m:crehab12=8.5
```

## Meta Commands

```ls
metric m:empl12 p:float l:empl12 d:"Percent Population 16-64 Employed (2008-2012)" t:dataTypeName=percent

metric m:unempl12 p:float l:unempl12 d:"Percent Population 16-64 Unemployed and Looking for Work (2008-2012)" t:dataTypeName=percent

metric m:nilf12 p:float l:nilf12 d:"Percent Population 16-64 Not in Labor Force (2008-2012)" t:dataTypeName=percent

metric m:unempr12 p:float l:unempr12 d:"Unemployment Rate (2008-2012)" t:dataTypeName=number

metric m:lesshs12 p:float l:lesshs12 d:"Percent Population (25 years and over) With Less Than a High School Diploma or GED (2008-2012)" t:dataTypeName=percent

metric m:hsdipl12 p:float l:hsdipl12 d:"Percent Population (25 years and over) With High School Diploma (2008-2012)" t:dataTypeName=percent

metric m:somecol12 p:float l:somecol12 d:"Percent Population (25 years and over) with Some College or Bachelor's Degree or Higher (2008-2012)" t:dataTypeName=percent

metric m:wrkout10 p:float l:wrkout10 d:"Percent of the Population that Work Outside of the City (2010)" t:dataTypeName=percent

metric m:wrkout11 p:float l:wrkout11 d:"Percent of the Population that Work Outside of the City (2011)" t:dataTypeName=percent

metric m:comprop10 p:integer l:comprop10 d:"Total Number of Commercial Properties (2010)" t:dataTypeName=number

metric m:comprop11 p:integer l:comprop11 d:"Total Number of Commercial Properties (2011)" t:dataTypeName=number

metric m:comprop12 p:integer l:comprop12 d:"Total Number of Commercial Properties (2012)" t:dataTypeName=number

metric m:crehab10 p:float l:crehab10 d:"Percent of Commercial Properties with Rehab Permits Above $5,000 (2010)" t:dataTypeName=percent

metric m:crehab11 p:float l:crehab11 d:"Percent of Commercial Properties with Rehab Permits Above $5,000 (2011)" t:dataTypeName=percent

metric m:crehab12 p:float l:crehab12 d:"Percent of Commercial Properties with Rehab Permits Above $5,000 (2012)" t:dataTypeName=percent

metric m:banks11 p:float l:banks11 d:"Number of Banks and Bank Branches per 1,000 Residents (2011)" t:dataTypeName=number

metric m:banks12 p:float l:banks12 d:"Number of Banks and Bank Branches per 1,000 Residents (2012)" t:dataTypeName=number

metric m:numbus10 p:integer l:numbus10 d:"Total Number of Businesses (2010)" t:dataTypeName=number

metric m:numbus11 p:integer l:numbus11 d:"Total Number of Businesses (2011)" t:dataTypeName=number

metric m:numbus12 p:integer l:numbus12 d:"Total Number of Businesses (2012)" t:dataTypeName=number

metric m:totemp10 p:integer l:totemp10 d:"Total Number of Employees (2010)" t:dataTypeName=number

metric m:totemp11 p:integer l:totemp11 d:"Total Number of Employees (2011)" t:dataTypeName=number

metric m:totemp12 p:integer l:totemp12 d:"Total Number of Employees (2012)" t:dataTypeName=number

metric m:smlbus10 p:integer l:smlbus10 d:"Number of Businesses with Under 50 Employees (2010)" t:dataTypeName=number

metric m:smlbus11 p:integer l:smlbus11 d:"Number of Businesses with Under 50 Employees (2011)" t:dataTypeName=number

metric m:smlbus12 p:integer l:smlbus12 d:"Number of Businesses with Under 50 Employees (2012)" t:dataTypeName=number

metric m:biz1_10 p:float l:biz1_10 d:"Percent of Businesses that are 1 year old or less (2010)" t:dataTypeName=percent

metric m:biz1_11 p:float l:biz1_11 d:"Percent of Businesses that are 1 year old or less (2011)" t:dataTypeName=percent

metric m:biz1_12 p:float l:biz1_12 d:"Percent of Businesses that are 1 year old or less (2012)" t:dataTypeName=percent

metric m:biz2_10 p:float l:biz2_10 d:"Percent of Businesses that are 2 years old or less (2010)" t:dataTypeName=percent

metric m:biz2_11 p:float l:biz2_11 d:"Percent of Businesses that are 2 years old or less (2011)" t:dataTypeName=percent

metric m:biz2_12 p:float l:biz2_12 d:"Percent of Businesses that are 2 years old or less (2012)" t:dataTypeName=percent

metric m:biz4_10 p:float l:biz4_10 d:"Percent of Businesses that are 4 years old or less (2010)" t:dataTypeName=percent

metric m:biz4_11 p:float l:biz4_11 d:"Percent of Businesses that are 4 years old or less (2011)" t:dataTypeName=percent

metric m:biz4_12 p:float l:biz4_12 d:"Percent of Businesses that are 4 years old or less (2012)" t:dataTypeName=percent

metric m:neiind10 p:integer l:neiind10 d:"Number of Businesses by Selected Neighborhood Industry (NAICS Sectors) (2010)" t:dataTypeName=number

metric m:neiind11 p:integer l:neiind11 d:"Number of Businesses by Selected Neighborhood Industry (NAICS Sectors) (2011)" t:dataTypeName=number

metric m:neiind12 p:integer l:neiind12 d:"Number of Businesses by Selected Neighborhood Industry (NAICS Sectors) (2012)" t:dataTypeName=number

metric m:neibus10 p:float l:neibus10 d:"Neighborhood Businesses per 1,000 residents (NAICS Sectors) (2010)" t:dataTypeName=number

metric m:neibus11 p:float l:neibus11 d:"Neighborhood Businesses per 1,000 residents (NAICS Sectors) (2011)" t:dataTypeName=number

metric m:neibus12 p:float l:neibus12 d:"Neighborhood Businesses per 1,000 residents (NAICS Sectors) (2012)" t:dataTypeName=number

metric m:neiemp10 p:integer l:neiemp10 d:"Total number of Employees by Selected Neighborhood Industry (NAICS Sectors) (2010)" t:dataTypeName=number

metric m:neiemp11 p:integer l:neiemp11 d:"Total number of Employees by Selected Neighborhood Industry (NAICS Sectors) (2011)" t:dataTypeName=number

metric m:neiemp12 p:integer l:neiemp12 d:"Total number of Employees by Selected Neighborhood Industry (NAICS Sectors) (2012)" t:dataTypeName=number

entity e:hs6f-mzje l:"Workforce and Economic Development (2010-2012)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/hs6f-mzje

property e:hs6f-mzje t:meta.view v:id=hs6f-mzje v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Workforce and Economic Development (2010-2012)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:hs6f-mzje t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:hs6f-mzje t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:hs6f-mzje t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | empl12 | unempl12 | nilf12 | unempr12 | lesshs12 | hsdipl12 | somecol12 | wrkout10           | wrkout11           | comprop10 | comprop11 | comprop12 | crehab10 | crehab11 | crehab12 | banks11 | banks12 | numbus10 | numbus11 | numbus12 | totemp10 | totemp11 | totemp12 | smlbus10 | smlbus11 | smlbus12 | biz1_10 | biz1_11 | biz1_12 | biz2_10 | biz2_11 | biz2_12 | biz4_10 | biz4_11 | biz4_12 | neiind10 | neiind11 | neiind12 | neibus10 | neibus11 | neibus12 | neiemp10 | neiemp11 | neiemp12 | 
| ================================= | ====== | ======== | ====== | ======== | ======== | ======== | ========= | ================== | ================== | ========= | ========= | ========= | ======== | ======== | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| Allendale/Irvington/S. Hilton     | 57.7   | 13.6     | 29.1   | 19.2     | 24.5     | 64.5     | 11.0      | 60.3               | 59                 | 279       | 278       | 284       | 13.3     | 8.6      | 13.7     | 0.0     | 0       | 269      | 237      | 253      | 2778     | 2502     | 2629     | 255      | 226      | 242      | 8.9     | 11.0    | 9.5     | 19.3    | 15.6    | 24.5    | 33.8    | 29.1    | 34.8    | 183      | 161      | 162      | 11.3     | 9.9      | 10.0     | 1503     | 1378     | 1370     | 
| Beechfield/Ten Hills/West Hills   | 66.9   | 10.1     | 23.2   | 13.3     | 14.2     | 63.5     | 22.3      | 62.5               | 66.900000000000006 | 47        | 47        | 46        | 25.5     | 27.7     | 4.3      | 0.1     | 0.1     | 154      | 136      | 141      | 1462     | 1329     | 1383     | 148      | 130      | 134      | 3.9     | 8.1     | 4.3     | 22.1    | 12.5    | 12.1    | 32.5    | 30.1    | 29.8    | 98       | 87       | 88       | 8.0      | 7.1      | 7.2      | 753      | 663      | 684      | 
| Belair-Edison                     | 62.3   | 12.0     | 25.8   | 16.3     | 18.8     | 67.2     | 14.0      | 48.5               | 49.4               | 165       | 165       | 165       | 8.5      | 10.9     | 8.5      | 0.2     | 0.1     | 225      | 224      | 251      | 1590     | 1540     | 1605     | 217      | 217      | 244      | 8.9     | 12.1    | 7.6     | 22.7    | 18.8    | 23.5    | 31.6    | 31.3    | 38.6    | 172      | 172      | 189      | 9.9      | 9.9      | 10.9     | 1044     | 915      | 1008     | 
| Brooklyn/Curtis Bay/Hawkins Point | 56.6   | 14.5     | 29.3   | 20.5     | 34.2     | 59.5     | 6.4       | 72.7               | 75.8               | 880       | 838       | 856       | 5.2      | 7.4      | 13.7     | 0.1     | 0.1     | 329      | 414      | 317      | 6127     | 6696     | 4945     | 297      | 386      | 291      | 2.7     | 7.5     | 6.9     | 10.9    | 15.0    | 14.8    | 21.9    | 30.7    | 23.0    | 161      | 208      | 153      | 11.3     | 14.6     | 10.7     | 1227     | 1463     | 1114     | 
| Canton                            | 84.6   | 3.6      | 12.0   | 4.0      | 8.6      | 30.2     | 61.2      | 53.699999999999996 | 50.5               | 205       | 210       | 208       | 14.1     | 13.3     | 13.5     | 0.5     | 0.2     | 314      | 322      | 364      | 2653     | 2516     | 2921     | 307      | 316      | 352      | 7.6     | 10.9    | 11.5    | 17.8    | 17.7    | 26.1    | 33.4    | 34.2    | 39.0    | 214      | 230      | 248      | 26.4     | 28.4     | 30.6     | 2029     | 1887     | 2211     | 
| Cedonia/Frankford                 | 65.3   | 9.6      | 25.0   | 12.9     | 20.0     | 68.1     | 11.9      | 53.1               | 50                 | 231       | 231       | 231       | 7.8      | 9.5      | 6.9      | 0.3     | 0.1     | 426      | 379      | 407      | 3281     | 2935     | 2963     | 414      | 368      | 397      | 9.4     | 10.6    | 9.8     | 22.3    | 17.7    | 21.1    | 36.2    | 33.5    | 35.6    | 316      | 280      | 297      | 13.4     | 11.9     | 12.6     | 2255     | 1998     | 2073     | 
| Cherry Hill                       | 51.3   | 14.7     | 34.3   | 22.3     | 23.3     | 69.6     | 7.1       | 57.1               | 53.2               | 91        | 93        | 93        | 29.7     | 38.7     | 23.7     | 0.0     | 0.0     | 88       | 138      | 100      | 872      | 1198     | 1190     | 84       | 132      | 95       | 3.4     | 9.4     | 5.0     | 5.7     | 18.8    | 16.0    | 14.8    | 26.8    | 21.0    | 47       | 85       | 56       | 5.7      | 10.4     | 6.8      | 353      | 625      | 641      | 
| Chinquapin Park/Belvedere         | 69.5   | 9.3      | 21.4   | 11.9     | 13.2     | 52.9     | 33.9      | 55.1               | 48.4               | 57        | 57        | 56        | 10.5     | 17.5     | 21.4     | 0.3     | 0.4     | 140      | 128      | 145      | 1170     | 1153     | 1211     | 136      | 124      | 140      | 5.7     | 7.0     | 9.7     | 21.4    | 10.9    | 20.0    | 32.1    | 28.9    | 35.2    | 106      | 99       | 107      | 13.7     | 12.8     | 13.8     | 880      | 868      | 891      | 
| Claremont/Armistead               | 61.5   | 9.2      | 29.7   | 13.1     | 25.9     | 65.4     | 8.7       | 56.7               | 61.6               | 183       | 182       | 186       | 10.4     | 7.7      | 9.1      | 0.0     | 0       | 177      | 185      | 190      | 2681     | 3024     | 2749     | 162      | 168      | 176      | 7.3     | 7.0     | 7.9     | 14.7    | 14.1    | 16.8    | 27.7    | 26.5    | 28.4    | 76       | 77       | 86       | 9.2      | 9.4      | 10.4     | 1124     | 1243     | 1137     | 
| Clifton-Berea                     | 46.5   | 12.1     | 42.1   | 21.0     | 27.6     | 64.0     | 8.4       | 49.1               | 45.8               | 149       | 149       | 150       | 6.7      | 4.7      | 19.3     | 0.0     | 0       | 182      | 169      | 164      | 2009     | 1487     | 1448     | 173      | 161      | 156      | 4.9     | 7.7     | 5.5     | 15.9    | 11.2    | 13.4    | 34.1    | 29.0    | 26.2    | 132      | 126      | 120      | 13.4     | 12.8     | 12.2     | 709      | 732      | 721      | 
```