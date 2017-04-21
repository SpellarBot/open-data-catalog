# Census Demographics (2010-2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-demographics-2010-2014) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/t7sb-aegk) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/t7sb-aegk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/t7sb-aegk/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | t7sb-aegk |
| Name | Census Demographics (2010-2014) |
| Attribution | BNIA-JFI |
| Category | Neighborhoods |
| Tags | census, bnia |
| Created | 2016-04-15T15:44:10Z |
| Publication Date | 2016-04-15T16:00:36Z |

## Description

Census data are frequently used throughout Vital Signs as denominators for normalizing many other indicators and rates. The socioeconomic and demographic indicators are grouped into the following categories: population, race/ethnicity, age, households, and income and poverty.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010   | text      | text        |
| Yes      | numeric metric | tpop10     | tpop10    | number    | number      |
| Yes      | numeric metric | male10     | male10    | number    | number      |
| Yes      | numeric metric | female10   | female10  | number    | number      |
| Yes      | numeric metric | paa10      | paa10     | percent   | percent     |
| Yes      | numeric metric | pwhite10   | pwhite10  | percent   | percent     |
| Yes      | numeric metric | pasi10     | pasi10    | percent   | percent     |
| Yes      | numeric metric | p2more10   | p2more10  | percent   | percent     |
| Yes      | numeric metric | ppac10     | ppac10    | percent   | percent     |
| Yes      | numeric metric | phisp10    | phisp10   | percent   | percent     |
| Yes      | numeric metric | racdiv10   | racdiv10  | number    | number      |
| Yes      | numeric metric | age5_10    | age5_10   | percent   | percent     |
| Yes      | numeric metric | age18_10   | age18_10  | percent   | percent     |
| Yes      | numeric metric | age24_10   | age24_10  | percent   | percent     |
| Yes      | numeric metric | age64_10   | age64_10  | percent   | percent     |
| Yes      | numeric metric | age65_10   | age65_10  | percent   | percent     |
| Yes      | numeric metric | hhs10      | hhs10     | number    | number      |
| Yes      | numeric metric | femhhs10   | femhhs10  | percent   | percent     |
| Yes      | numeric metric | fam10      | fam10     | percent   | percent     |
| Yes      | numeric metric | hhsize10   | hhsize10  | number    | number      |
| Yes      | numeric metric | mhhi14     | mhhi14    | money     | money       |
| Yes      | numeric metric | hh25inc14  | hh25inc14 | percent   | percent     |
| Yes      | numeric metric | hh40inc14  | hh40inc14 | percent   | percent     |
| Yes      | numeric metric | hh60inc14  | hh60inc14 | percent   | percent     |
| Yes      | numeric metric | hh75inc14  | hh75inc14 | percent   | percent     |
| Yes      | numeric metric | hhm7514    | hhm7514   | percent   | percent     |
| Yes      | numeric metric | hhpov14    | hhpov14   | percent   | percent     |
| Yes      | numeric metric | hhchpov14  | hhchpov14 | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t7sb-aegk d:2010-01-01T00:00:00.000Z t:csa2010="Greater Rosemont" m:racdiv10=7.6 m:age64_10=50 m:paa10=96.6 m:male10=8783 m:hhsize10=2.8 m:p2more10=1.3 m:female10=10476 m:fam10=35.4 m:hh75inc14=9.2 m:hhm7514=12.5 m:hh25inc14=40.1 m:hhchpov14=43.1 m:age24_10=11 m:hh40inc14=22.1 m:hh60inc14=16.1 m:age18_10=18.8 m:pasi10=0.2 m:age5_10=7.3 m:hhpov14=21.7 m:ppac10=0.3 m:femhhs10=68 m:phisp10=1 m:tpop10=19259 m:pwhite10=0.7 m:age65_10=12.9

series e:t7sb-aegk d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:racdiv10=22.9 m:age64_10=51.9 m:paa10=88.2 m:male10=7246 m:hhsize10=2.6 m:p2more10=1.3 m:female10=8971 m:fam10=35.9 m:hh75inc14=12.5 m:hhm7514=15.9 m:hh25inc14=35.6 m:hhchpov14=41.5 m:age24_10=10.3 m:hh40inc14=19.4 m:hh60inc14=16.6 m:age18_10=18.4 m:pasi10=0.5 m:age5_10=6.6 m:hhpov14=23.1 m:ppac10=0.5 m:femhhs10=63.6 m:phisp10=1.3 m:tpop10=16217 m:pwhite10=8.3 m:age65_10=12.8

series e:t7sb-aegk d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:racdiv10=36.2 m:age64_10=56.2 m:paa10=78.9 m:male10=5566 m:hhsize10=2.4 m:p2more10=1.5 m:female10=6698 m:fam10=33.6 m:hh75inc14=12.9 m:hhm7514=29.2 m:hh25inc14=20.1 m:hhchpov14=22.3 m:age24_10=10.2 m:hh40inc14=17.5 m:hh60inc14=20.3 m:age18_10=16.7 m:pasi10=0.8 m:age5_10=6.5 m:hhpov14=11.8 m:ppac10=0.4 m:femhhs10=51.4 m:phisp10=1.6 m:tpop10=12264 m:pwhite10=16.8 m:age65_10=10.5
```

## Meta Commands

```ls
metric m:tpop10 p:integer l:tpop10 d:"Total Population (2010)" t:dataTypeName=number

metric m:male10 p:integer l:male10 d:"Total Male Population (2010)" t:dataTypeName=number

metric m:female10 p:integer l:female10 d:"Total Female Population (2010)" t:dataTypeName=number

metric m:paa10 p:float l:paa10 d:"Percent of Residents - Black/African-American (2010)" t:dataTypeName=percent

metric m:pwhite10 p:float l:pwhite10 d:"Percent of Residents - White/Caucasian (2010)" t:dataTypeName=percent

metric m:pasi10 p:float l:pasi10 d:"Percent of Residents - Asian (2010)" t:dataTypeName=percent

metric m:p2more10 p:float l:p2more10 d:"Percent of Residents - Two or More Races (2010)" t:dataTypeName=percent

metric m:ppac10 p:float l:ppac10 d:"Percent of Residents - All Other Races (Hawaiian/ Pacific Islander, Alaskan/ Native American Other Race) (2010)" t:dataTypeName=percent

metric m:phisp10 p:float l:phisp10 d:"Percent of Residents - Hispanic (2010)" t:dataTypeName=percent

metric m:racdiv10 p:float l:racdiv10 d:"Racial Diversity Index (2010)" t:dataTypeName=number

metric m:age5_10 p:float l:age5_10 d:"Percent of Population 0-5 years old (2010)" t:dataTypeName=percent

metric m:age18_10 p:float l:age18_10 d:"Percent of Population 6-18 years old (2010)" t:dataTypeName=percent

metric m:age24_10 p:float l:age24_10 d:"Percent of Population 19-24 years old (2010)" t:dataTypeName=percent

metric m:age64_10 p:float l:age64_10 d:"Percent of Population 25-64 years old (2010)" t:dataTypeName=percent

metric m:age65_10 p:float l:age65_10 d:"Percent of Population 65 years and over (2010)" t:dataTypeName=percent

metric m:hhs10 p:long l:hhs10 d:"Total Number of Households (2010)" t:dataTypeName=number

metric m:femhhs10 p:float l:femhhs10 d:"Percent of Female-Headed Households with Children under 18 (2010)" t:dataTypeName=percent

metric m:fam10 p:float l:fam10 d:"Percent of Households with Children Under 18 (2010)" t:dataTypeName=percent

metric m:hhsize10 p:float l:hhsize10 d:"Average Household Size (2010)" t:dataTypeName=number

metric m:mhhi14 p:double l:mhhi14 d:"Median Household Income (2010-2014)" t:dataTypeName=money

metric m:hh25inc14 p:float l:hh25inc14 d:"Percent of Households Earning Less than $25,000 (2010-2014)" t:dataTypeName=percent

metric m:hh40inc14 p:float l:hh40inc14 d:"Percent of Households Earning $25,000 to $40,000 (2010-2014)" t:dataTypeName=percent

metric m:hh60inc14 p:float l:hh60inc14 d:"Percent of Households Earning $40,000 to $60,000 (2010-2014)" t:dataTypeName=percent

metric m:hh75inc14 p:float l:hh75inc14 d:"Percent of Households Earning $60,000 to $75,000 (2010-2014)" t:dataTypeName=percent

metric m:hhm7514 p:float l:hhm7514 d:"Percent of Households Earning More than $75,000 (2010-2014)" t:dataTypeName=percent

metric m:hhpov14 p:float l:hhpov14 d:"Percent of Family Households Living Below the Poverty Line (2010-2014)" t:dataTypeName=percent

metric m:hhchpov14 p:float l:hhchpov14 d:"Percent of Children Living Below the Poverty Line (2010-2014)" t:dataTypeName=percent

entity e:t7sb-aegk l:"Census Demographics (2010-2014)" t:attribution=BNIA-JFI t:url=https://data.baltimorecity.gov/api/views/t7sb-aegk

property e:t7sb-aegk t:meta.view v:id=t7sb-aegk v:category=Neighborhoods v:attributionLink=http://bniajfi.org/ v:averageRating=0 v:name="Census Demographics (2010-2014)" v:attribution=BNIA-JFI

property e:t7sb-aegk t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:t7sb-aegk t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:t7sb-aegk t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | tpop10 | male10 | female10 | paa10 | pwhite10 | pasi10 | p2more10 | ppac10 | phisp10 | racdiv10 | age5_10 | age18_10 | age24_10 | age64_10 | age65_10 | hhs10 | femhhs10 | fam10 | hhsize10 | mhhi14 | hh25inc14 | hh40inc14 | hh60inc14 | hh75inc14 | hhm7514 | hhpov14 | hhchpov14 | 
| ================================= | ====== | ====== | ======== | ===== | ======== | ====== | ======== | ====== | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ===== | ======== | ===== | ======== | ====== | ========= | ========= | ========= | ========= | ======= | ======= | ========= | 
| Greater Rosemont                  | 19259  | 8783   | 10476    | 96.6  | 0.7      | 0.2    | 1.3      | 0.3    | 1.0     | 7.6      | 7.3     | 18.8     | 11.0     | 50.0     | 12.9     |       | 68.0     | 35.4  | 2.8      |        | 40.1      | 22.1      | 16.1      | 9.2       | 12.5    | 21.7    | 43.1      | 
| Allendale/Irvington/S. Hilton     | 16217  | 7246   | 8971     | 88.2  | 8.3      | 0.5    | 1.3      | 0.5    | 1.3     | 22.9     | 6.6     | 18.4     | 10.3     | 51.9     | 12.8     |       | 63.6     | 35.9  | 2.6      |        | 35.6      | 19.4      | 16.6      | 12.5      | 15.9    | 23.1    | 41.5      | 
| Beechfield/Ten Hills/West Hills   | 12264  | 5566   | 6698     | 78.9  | 16.8     | 0.8    | 1.5      | 0.4    | 1.6     | 36.2     | 6.5     | 16.7     | 10.2     | 56.2     | 10.5     |       | 51.4     | 33.6  | 2.4      |        | 20.1      | 17.5      | 20.3      | 12.9      | 29.2    | 11.8    | 22.3      | 
| Belair-Edison                     | 17416  | 7891   | 9525     | 86.9  | 9.9      | 0.5    | 1.1      | 0.3    | 1.2     | 24.6     | 6.9     | 20.2     | 10.9     | 54.0     | 8.0      |       | 63.7     | 40.6  | 2.9      |        | 32.7      | 18.5      | 17.5      | 9.4       | 21.8    | 18.1    | 36.9      | 
| Brooklyn/Curtis Bay/Hawkins Point | 14243  | 6981   | 7262     | 35.9  | 47.8     | 1.7    | 4.1      | 0.7    | 9.8     | 66.7     | 10.2    | 18.2     | 11.1     | 53.5     | 7.1      |       | 51.0     | 39.5  | 2.6      |        | 33.6      | 19.8      | 19.7      | 9.9       | 17.0    | 28.4    | 46.9      | 
| Canton                            | 8100   | 4011   | 4089     | 4.0   | 86.0     | 3.4    | 1.3      | 0.4    | 5.0     | 28.3     | 4.1     | 3.0      | 10.5     | 71.5     | 10.9     |       | 19.8     | 8.8   | 1.9      |        | 9.4       | 8.3       | 13.1      | 7.5       | 61.7    | 2.8     | 6.5       | 
| Cedonia/Frankford                 | 23557  | 10788  | 12769    | 78.5  | 15.1     | 2.3    | 1.8      | 0.4    | 2.0     | 37.5     | 7.3     | 17.2     | 11.6     | 55.3     | 8.7      |       | 55.3     | 34.5  | 2.5      |        | 30.1      | 20.9      | 19.4      | 9.0       | 20.7    | 17.4    | 26.0      | 
| Cherry Hill                       | 8202   | 3343   | 4859     | 95.1  | 1.6      | 0.2    | 1.1      | 0.3    | 1.6     | 11.2     | 11.4    | 24.3     | 12.1     | 43.8     | 8.4      |       | 80.7     | 45.4  | 2.6      |        | 53.2      | 21.4      | 13.3      | 4.4       | 7.7     | 41.8    | 53.7      | 
| Chinquapin Park/Belvedere         | 7756   | 3527   | 4229     | 69.0  | 23.2     | 1.7    | 1.8      | 0.6    | 3.7     | 49.5     | 7.2     | 14.2     | 11.1     | 56.2     | 11.5     |       | 51.5     | 29.3  | 2.3      |        | 29.5      | 16.9      | 16.1      | 10.1      | 27.5    | 12.5    | 24.3      | 
| Claremont/Armistead               | 8231   | 3717   | 4514     | 53.1  | 32.2     | 0.5    | 2.0      | 0.9    | 11.4    | 66.7     | 8.3     | 18.5     | 10.4     | 53.2     | 9.5      |       | 57.1     | 35.3  | 2.4      |        | 35.5      | 22.2      | 19.4      | 5.9       | 16.9    | 16.5    | 27.6      | 
```