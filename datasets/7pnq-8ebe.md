# Census Demographics (2010-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-demographics-2010-2013) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/7pnq-8ebe) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/7pnq-8ebe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/7pnq-8ebe/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 7pnq-8ebe |
| Name | Census Demographics (2010-2013) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | census, demographics, bnia |
| Created | 2015-05-14T20:35:18Z |
| Publication Date | 2015-05-14T20:38:37Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and socioeconomic indicators for neighborhoods. The Census Bureau collects a wide variety of information through administration of both the decennial Census and the annual American Community Survey (ACS).

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | neighborhood | Neighborhood | text      | text        |
| Yes      | numeric metric | tpop10       | tpop10       | number    | number      |
| Yes      | numeric metric | male10       | male10       | number    | number      |
| Yes      | numeric metric | female10     | female10     | number    | number      |
| Yes      | numeric metric | paa10        | paa10        | percent   | percent     |
| Yes      | numeric metric | pwhite10     | pwhite10     | percent   | percent     |
| Yes      | numeric metric | pasi10       | pasi10       | percent   | percent     |
| Yes      | numeric metric | p2more10     | p2more10     | percent   | percent     |
| Yes      | numeric metric | ppac10       | ppac10       | percent   | percent     |
| Yes      | numeric metric | phisp10      | phisp10      | percent   | percent     |
| Yes      | numeric metric | racdiv10     | racdiv10     | percent   | percent     |
| Yes      | numeric metric | age5_10      | age5_10      | percent   | percent     |
| Yes      | numeric metric | age18_10     | age18_10     | percent   | percent     |
| Yes      | numeric metric | age24_10     | age24_10     | percent   | percent     |
| Yes      | numeric metric | age64_10     | age64_10     | percent   | percent     |
| Yes      | numeric metric | age65_10     | age65_10     | percent   | percent     |
| Yes      | series tag     | hhs10        | hhs10        | text      | text        |
| Yes      | numeric metric | femhhs10     | femhhs10     | percent   | percent     |
| Yes      | numeric metric | fam10        | fam10        | percent   | percent     |
| Yes      | numeric metric | hhsize10     | hhsize10     | number    | number      |
| Yes      | numeric metric | mhhi13       | mhhi13       | money     | money       |
| Yes      | numeric metric | hh25inc13    | hh25inc13    | percent   | percent     |
| Yes      | numeric metric | hh40inc13    | hh40inc13    | percent   | percent     |
| Yes      | numeric metric | hh60inc13    | hh60inc13    | percent   | percent     |
| Yes      | numeric metric | hh75inc13    | hh75inc13    | percent   | percent     |
| Yes      | numeric metric | hhm7513      | hhm7513      | percent   | percent     |
| Yes      | numeric metric | hhpov13      | hhpov13      | percent   | percent     |
| Yes      | numeric metric | hhchpov13    | hhchpov13    | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7pnq-8ebe d:2010-01-01T00:00:00.000Z t:neighborhood="Allendale/Irvington/S. Hilton" t:hhs10="* 6,098" m:racdiv10=22.9 m:age64_10=51.9 m:paa10=88.2 m:male10=7246 m:hhsize10=2.6 m:p2more10=1.3 m:female10=8971 m:fam10=35.9 m:hhm7513=18.3 m:hh75inc13=10.5 m:hh25inc13=37.8 m:hhchpov13=35.9 m:age24_10=10.3 m:hh40inc13=19 m:hh60inc13=14.5 m:age18_10=18.4 m:pasi10=0.5 m:age5_10=6.6 m:ppac10=0.5 m:femhhs10=63.6 m:hhpov13=19.8 m:phisp10=1.3 m:tpop10=16217 m:pwhite10=8.3 m:age65_10=12.8

series e:7pnq-8ebe d:2010-01-01T00:00:00.000Z t:neighborhood="Beechfield/Ten Hills/West Hills" t:hhs10="* 5,076" m:racdiv10=36.2 m:age64_10=56.2 m:paa10=78.9 m:male10=5566 m:hhsize10=2.4 m:p2more10=1.5 m:female10=6698 m:fam10=33.6 m:hhm7513=27.5 m:hh75inc13=10.6 m:hh25inc13=18.7 m:hhchpov13=15.1 m:age24_10=10.2 m:hh40inc13=19.2 m:hh60inc13=24 m:age18_10=16.7 m:pasi10=0.8 m:age5_10=6.5 m:ppac10=0.4 m:femhhs10=51.4 m:hhpov13=8.3 m:phisp10=1.6 m:tpop10=12264 m:pwhite10=16.8 m:age65_10=10.5

series e:7pnq-8ebe d:2010-01-01T00:00:00.000Z t:neighborhood=Belair-Edison t:hhs10="* 6,174" m:racdiv10=24.6 m:age64_10=54 m:paa10=86.9 m:male10=7891 m:hhsize10=2.9 m:p2more10=1.1 m:female10=9525 m:fam10=40.6 m:hhm7513=21.6 m:hh75inc13=14.7 m:hh25inc13=26.3 m:hhchpov13=25.5 m:age24_10=10.9 m:hh40inc13=17.8 m:hh60inc13=19.5 m:age18_10=20.2 m:pasi10=0.5 m:age5_10=6.9 m:ppac10=0.3 m:femhhs10=63.7 m:hhpov13=12.5 m:phisp10=1.2 m:tpop10=17416 m:pwhite10=9.9 m:age65_10=8
```

## Meta Commands

```ls
metric m:tpop10 p:integer l:tpop10 t:dataTypeName=number

metric m:male10 p:integer l:male10 t:dataTypeName=number

metric m:female10 p:integer l:female10 t:dataTypeName=number

metric m:paa10 p:float l:paa10 t:dataTypeName=percent

metric m:pwhite10 p:float l:pwhite10 t:dataTypeName=percent

metric m:pasi10 p:float l:pasi10 t:dataTypeName=percent

metric m:p2more10 p:float l:p2more10 t:dataTypeName=percent

metric m:ppac10 p:float l:ppac10 t:dataTypeName=percent

metric m:phisp10 p:float l:phisp10 t:dataTypeName=percent

metric m:racdiv10 p:float l:racdiv10 t:dataTypeName=percent

metric m:age5_10 p:float l:age5_10 t:dataTypeName=percent

metric m:age18_10 p:float l:age18_10 t:dataTypeName=percent

metric m:age24_10 p:float l:age24_10 t:dataTypeName=percent

metric m:age64_10 p:float l:age64_10 t:dataTypeName=percent

metric m:age65_10 p:float l:age65_10 t:dataTypeName=percent

metric m:femhhs10 p:float l:femhhs10 t:dataTypeName=percent

metric m:fam10 p:float l:fam10 t:dataTypeName=percent

metric m:hhsize10 p:float l:hhsize10 t:dataTypeName=number

metric m:mhhi13 p:double l:mhhi13 t:dataTypeName=money

metric m:hh25inc13 p:float l:hh25inc13 t:dataTypeName=percent

metric m:hh40inc13 p:float l:hh40inc13 t:dataTypeName=percent

metric m:hh60inc13 p:float l:hh60inc13 t:dataTypeName=percent

metric m:hh75inc13 p:float l:hh75inc13 t:dataTypeName=percent

metric m:hhm7513 p:float l:hhm7513 t:dataTypeName=percent

metric m:hhpov13 p:float l:hhpov13 t:dataTypeName=percent

metric m:hhchpov13 p:float l:hhchpov13 t:dataTypeName=percent

entity e:7pnq-8ebe l:"Census Demographics (2010-2013)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/7pnq-8ebe

property e:7pnq-8ebe t:meta.view v:id=7pnq-8ebe v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Census Demographics (2010-2013)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:7pnq-8ebe t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:7pnq-8ebe t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:7pnq-8ebe t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| neighborhood                      | tpop10 | male10 | female10 | paa10 | pwhite10 | pasi10 | p2more10 | ppac10 | phisp10 | racdiv10 | age5_10 | age18_10 | age24_10 | age64_10 | age65_10 | hhs10   | femhhs10 | fam10 | hhsize10 | mhhi13 | hh25inc13 | hh40inc13 | hh60inc13 | hh75inc13 | hhm7513 | hhpov13 | hhchpov13 | 
| ================================= | ====== | ====== | ======== | ===== | ======== | ====== | ======== | ====== | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======= | ======== | ===== | ======== | ====== | ========= | ========= | ========= | ========= | ======= | ======= | ========= | 
| Allendale/Irvington/S. Hilton     | 16217  | 7246   | 8971     | 88.2  | 8.3      | 0.5    | 1.3      | 0.5    | 1.3     | 22.9     | 6.6     | 18.4     | 10.3     | 51.9     | 12.8     | * 6,098 | 63.6     | 35.9  | 2.6      |        | 37.8      | 19.0      | 14.5      | 10.5      | 18.3    | 19.8    | 35.9      | 
| Beechfield/Ten Hills/West Hills   | 12264  | 5566   | 6698     | 78.9  | 16.8     | 0.8    | 1.5      | 0.4    | 1.6     | 36.2     | 6.5     | 16.7     | 10.2     | 56.2     | 10.5     | * 5,076 | 51.4     | 33.6  | 2.4      |        | 18.7      | 19.2      | 24.0      | 10.6      | 27.5    | 8.3     | 15.1      | 
| Belair-Edison                     | 17416  | 7891   | 9525     | 86.9  | 9.9      | 0.5    | 1.1      | 0.3    | 1.2     | 24.6     | 6.9     | 20.2     | 10.9     | 54.0     | 8.0      | * 6,174 | 63.7     | 40.6  | 2.9      |        | 26.3      | 17.8      | 19.5      | 14.7      | 21.6    | 12.5    | 25.5      | 
| Brooklyn/Curtis Bay/Hawkins Point | 14243  | 6981   | 7262     | 35.9  | 47.8     | 1.7    | 4.1      | 0.7    | 9.8     | 66.7     | 10.2    | 18.2     | 11.1     | 53.5     | 7.1      | * 5,204 | 51.0     | 39.5  | 2.6      |        | 35.0      | 23.3      | 18.1      | 11.6      | 12.0    | 23.8    | 37.6      | 
| Canton                            | 8100   | 4011   | 4089     | 4.0   | 86.0     | 3.4    | 1.3      | 0.4    | 5.0     | 28.3     | 4.1     | 3.0      | 10.5     | 71.5     | 10.9     | * 4,310 | 19.8     | 8.8   | 1.9      |        | 9.8       | 8.4       | 15.0      | 11.6      | 55.1    | 1.8     | 13.2      | 
| Cedonia/Frankford                 | 23557  | 10788  | 12769    | 78.5  | 15.1     | 2.3    | 1.8      | 0.4    | 2.0     | 37.5     | 7.3     | 17.2     | 11.6     | 55.3     | 8.7      | * 9,348 | 55.3     | 34.5  | 2.5      |        | 29.9      | 20.2      | 18.0      | 12.6      | 19.3    | 17.3    | 25.5      | 
| Cherry Hill                       | 8202   | 3343   | 4859     | 95.1  | 1.6      | 0.2    | 1.1      | 0.3    | 1.6     | 11.2     | 11.4    | 24.3     | 12.1     | 43.8     | 8.4      | * 3,145 | 80.7     | 45.4  | 2.6      |        | 48.3      | 20.5      | 11.9      | 10.1      | 9.3     | 40.8    | 55.3      | 
| Chinquapin Park/Belvedere         | 7756   | 3527   | 4229     | 69.0  | 23.2     | 1.7    | 1.8      | 0.6    | 3.7     | 49.5     | 7.2     | 14.2     | 11.1     | 56.2     | 11.5     | * 3,359 | 51.5     | 29.3  | 2.3      |        | 27.8      | 19.1      | 17.0      | 10.9      | 25.2    | 9.4     | 13.0      | 
| Claremont/Armistead               | 8231   | 3717   | 4514     | 53.1  | 32.2     | 0.5    | 2.0      | 0.9    | 11.4    | 66.7     | 8.3     | 18.5     | 10.4     | 53.2     | 9.5      | * 3,419 | 57.1     | 35.3  | 2.4      |        | 42.2      | 18.2      | 16.9      | 5.3       | 17.4    | 15.8    | 31.4      | 
| Clifton-Berea                     | 9874   | 4473   | 5401     | 96.3  | 1.1      | 0.3    | 1.1      | 0.3    | 1.0     | 7.9      | 7.5     | 18.0     | 10.5     | 48.5     | 15.5     | * 3,529 | 70.0     | 34.7  | 2.8      |        | 50.0      | 18.5      | 13.4      | 10.4      | 7.7     | 25.6    | 43.7      | 
```