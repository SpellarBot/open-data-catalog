# Census Demographics 2010-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-demographics-2010-2012-c96cc) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/yp84-wh4q) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/yp84-wh4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/yp84-wh4q/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | yp84-wh4q |
| Name | Census Demographics 2010-2012 |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | census, bnia, demographics |
| Created | 2014-05-20T14:09:03Z |
| Publication Date | 2016-04-15T16:00:41Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and  socioeconomic indicators for neighborhoods. The Census Bureau collects a widevariety of information through administration of both the decennial Census and theannual American Community Survey (ACS).

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
| Yes      | numeric metric | mhhi12     | mhhi12    | money     | money       |
| Yes      | numeric metric | hh25inc12  | hh25inc12 | percent   | percent     |
| Yes      | numeric metric | hh40inc12  | hh40inc12 | percent   | percent     |
| Yes      | numeric metric | hh60inc12  | hh60inc12 | percent   | percent     |
| Yes      | numeric metric | hh75inc12  | hh75inc12 | percent   | percent     |
| Yes      | numeric metric | hhm7512    | hhm7512   | percent   | percent     |
| Yes      | numeric metric | hhpov12    | hhpov12   | percent   | percent     |
| Yes      | numeric metric | hhchpov12  | hhchpov12 | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yp84-wh4q d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:racdiv10=22.9 m:mhhi12=33177.66 m:hhsize10=2.6 m:p2more10=1.3 m:hhm7512=18.3 m:hhchpov12=35.9 m:fam10=35.9 m:hh25inc12=37.8 m:hh40inc12=19 m:age24_10=10.3 m:hh60inc12=14.5 m:tpop10=16217 m:phisp10=1.3 m:pwhite10=8.3 m:age65_10=12.8 m:age64_10=51.9 m:paa10=88.2 m:male10=7246 m:hh75inc12=10.5 m:female10=8971 m:hhs10=6098 m:age18_10=18.4 m:pasi10=0.5 m:age5_10=6.6 m:ppac10=0.5 m:femhhs10=63.6 m:hhpov12=19.8

series e:yp84-wh4q d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:racdiv10=36.2 m:mhhi12=50135.12 m:hhsize10=2.4 m:p2more10=1.5 m:hhm7512=27.5 m:hhchpov12=15.1 m:fam10=33.6 m:hh25inc12=18.7 m:hh40inc12=19.2 m:age24_10=10.2 m:hh60inc12=24 m:tpop10=12264 m:phisp10=1.6 m:pwhite10=16.8 m:age65_10=10.5 m:age64_10=56.2 m:paa10=78.9 m:male10=5566 m:hh75inc12=10.6 m:female10=6698 m:hhs10=5076 m:age18_10=16.7 m:pasi10=0.8 m:age5_10=6.5 m:ppac10=0.4 m:femhhs10=51.4 m:hhpov12=8.3

series e:yp84-wh4q d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:racdiv10=24.6 m:mhhi12=46743.28 m:hhsize10=2.9 m:p2more10=1.1 m:hhm7512=21.6 m:hhchpov12=25.5 m:fam10=40.6 m:hh25inc12=26.3 m:hh40inc12=17.8 m:age24_10=10.9 m:hh60inc12=19.5 m:tpop10=17416 m:phisp10=1.2 m:pwhite10=9.9 m:age65_10=8 m:age64_10=54 m:paa10=86.9 m:male10=7891 m:hh75inc12=14.7 m:female10=9525 m:hhs10=6174 m:age18_10=20.2 m:pasi10=0.5 m:age5_10=6.9 m:ppac10=0.3 m:femhhs10=63.7 m:hhpov12=12.5
```

## Meta Commands

```ls
metric m:tpop10 p:integer l:tpop10 d:"Total Population" t:dataTypeName=number

metric m:male10 p:integer l:male10 d:"Total Male Population" t:dataTypeName=number

metric m:female10 p:integer l:female10 d:"Total Female Population" t:dataTypeName=number

metric m:paa10 p:float l:paa10 d:"Percent of Residents - Black/African-American (Non-Hispanic)" t:dataTypeName=percent

metric m:pwhite10 p:float l:pwhite10 d:"Percent of Residents - White/Caucasian (Noon-Hispanic)" t:dataTypeName=percent

metric m:pasi10 p:float l:pasi10 d:"Percent of Residents - Asian (Non-Hispanic)" t:dataTypeName=percent

metric m:p2more10 p:float l:p2more10 d:"Percent of Residents - Two or More Races (Non-Hispanic)" t:dataTypeName=percent

metric m:ppac10 p:float l:ppac10 d:"Percent of Residents - All Other Races (Hawaiian/ Pacific Islander, Alaskan/ Native American Other Race) (Non-Hispanic)" t:dataTypeName=percent

metric m:phisp10 p:float l:phisp10 d:"Percent of Residents - Hispanic" t:dataTypeName=percent

metric m:racdiv10 p:float l:racdiv10 d:"Racial Diversity Index" t:dataTypeName=number

metric m:age5_10 p:float l:age5_10 d:"Percent of Population 0-5 years old" t:dataTypeName=percent

metric m:age18_10 p:float l:age18_10 d:"Percent of Population 6-18 years old" t:dataTypeName=percent

metric m:age24_10 p:float l:age24_10 d:"Percent of Population 19-24 years old" t:dataTypeName=percent

metric m:age64_10 p:float l:age64_10 d:"Percent of Population 25-64 years old" t:dataTypeName=percent

metric m:age65_10 p:float l:age65_10 d:"Percent of Population 65 years and over" t:dataTypeName=percent

metric m:hhs10 p:integer l:hhs10 d:"Total Number of Households" t:dataTypeName=number

metric m:femhhs10 p:float l:femhhs10 d:"Percent of Female-Headed Households with Children Under 18" t:dataTypeName=percent

metric m:fam10 p:float l:fam10 d:"Percent of Households with Children Under 18" t:dataTypeName=percent

metric m:hhsize10 p:float l:hhsize10 d:"Average Household Size" t:dataTypeName=number

metric m:mhhi12 p:double l:mhhi12 d:"Median Household Income" t:dataTypeName=money

metric m:hh25inc12 p:float l:hh25inc12 d:"Percent of Households Earning Less than $25,000" t:dataTypeName=percent

metric m:hh40inc12 p:float l:hh40inc12 d:"Percent of Households Earning $25,000 to $40,000" t:dataTypeName=percent

metric m:hh60inc12 p:float l:hh60inc12 d:"Percent of Households Earning $40,000 to $60,000" t:dataTypeName=percent

metric m:hh75inc12 p:float l:hh75inc12 d:"Percent of Households Earning $60,000 to $75,000" t:dataTypeName=percent

metric m:hhm7512 p:float l:hhm7512 d:"Percent of Households Earning More than $75,000" t:dataTypeName=percent

metric m:hhpov12 p:float l:hhpov12 d:"Percent of Households Living Below the Poverty Line" t:dataTypeName=percent

metric m:hhchpov12 p:float l:hhchpov12 d:"Percent of Children Living Below the Poverty Line" t:dataTypeName=percent

entity e:yp84-wh4q l:"Census Demographics 2010-2012" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/yp84-wh4q

property e:yp84-wh4q t:meta.view v:id=yp84-wh4q v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Census Demographics 2010-2012" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:yp84-wh4q t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:yp84-wh4q t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:yp84-wh4q t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | tpop10 | male10 | female10 | paa10 | pwhite10 | pasi10 | p2more10 | ppac10 | phisp10 | racdiv10 | age5_10 | age18_10 | age24_10 | age64_10 | age65_10 | hhs10 | femhhs10 | fam10 | hhsize10 | mhhi12   | hh25inc12 | hh40inc12 | hh60inc12 | hh75inc12 | hhm7512 | hhpov12 | hhchpov12 | 
| ================================= | ====== | ====== | ======== | ===== | ======== | ====== | ======== | ====== | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ===== | ======== | ===== | ======== | ======== | ========= | ========= | ========= | ========= | ======= | ======= | ========= | 
| Allendale/Irvington/S. Hilton     | 16217  | 7246   | 8971     | 88.2  | 8.3      | 0.5    | 1.3      | 0.5    | 1.3     | 22.9     | 6.6     | 18.4     | 10.3     | 51.9     | 12.8     | 6098  | 63.6     | 35.9  | 2.6      | 33177.66 | 37.8      | 19.0      | 14.5      | 10.5      | 18.3    | 19.8    | 35.9      | 
| Beechfield/Ten Hills/West Hills   | 12264  | 5566   | 6698     | 78.9  | 16.8     | 0.8    | 1.5      | 0.4    | 1.6     | 36.2     | 6.5     | 16.7     | 10.2     | 56.2     | 10.5     | 5076  | 51.4     | 33.6  | 2.4      | 50135.12 | 18.7      | 19.2      | 24.0      | 10.6      | 27.5    | 8.3     | 15.1      | 
| Belair-Edison                     | 17416  | 7891   | 9525     | 86.9  | 9.9      | 0.5    | 1.1      | 0.3    | 1.2     | 24.6     | 6.9     | 20.2     | 10.9     | 54.0     | 8.0      | 6174  | 63.7     | 40.6  | 2.9      | 46743.28 | 26.3      | 17.8      | 19.5      | 14.7      | 21.6    | 12.5    | 25.5      | 
| Brooklyn/Curtis Bay/Hawkins Point | 14243  | 6981   | 7262     | 35.9  | 47.8     | 1.7    | 4.1      | 0.7    | 9.8     | 66.7     | 10.2    | 18.2     | 11.1     | 53.5     | 7.1      | 5204  | 51.0     | 39.5  | 2.6      | 33526.36 | 35.0      | 23.3      | 18.1      | 11.6      | 12.0    | 23.8    | 37.6      | 
| Canton                            | 8100   | 4011   | 4089     | 4.0   | 86.0     | 3.4    | 1.3      | 0.4    | 5.0     | 28.3     | 4.1     | 3.0      | 10.5     | 71.5     | 10.9     | 4310  | 19.8     | 8.8   | 1.9      | 84978.14 | 9.8       | 8.4       | 15.0      | 11.6      | 55.1    | 1.8     | 13.2      | 
| Cedonia/Frankford                 | 23557  | 10788  | 12769    | 78.5  | 15.1     | 2.3    | 1.8      | 0.4    | 2.0     | 37.5     | 7.3     | 17.2     | 11.6     | 55.3     | 8.7      | 9348  | 55.3     | 34.5  | 2.5      | 39556.12 | 29.9      | 20.2      | 18.0      | 12.6      | 19.3    | 17.3    | 25.5      | 
| Cherry Hill                       | 8202   | 3343   | 4859     | 95.1  | 1.6      | 0.2    | 1.1      | 0.3    | 1.6     | 11.2     | 11.4    | 24.3     | 12.1     | 43.8     | 8.4      | 3145  | 80.7     | 45.4  | 2.6      | 22980.54 | 48.3      | 20.5      | 11.9      | 10.1      | 9.3     | 40.8    | 55.3      | 
| Chinquapin Park/Belvedere         | 7756   | 3527   | 4229     | 69.0  | 23.2     | 1.7    | 1.8      | 0.6    | 3.7     | 49.5     | 7.2     | 14.2     | 11.1     | 56.2     | 11.5     | 3359  | 51.5     | 29.3  | 2.3      | 42852.96 | 27.8      | 19.1      | 17.0      | 10.9      | 25.2    | 9.4     | 13.0      | 
| Claremont/Armistead               | 8231   | 3717   | 4514     | 53.1  | 32.2     | 0.5    | 2.0      | 0.9    | 11.4    | 66.7     | 8.3     | 18.5     | 10.4     | 53.2     | 9.5      | 3419  | 57.1     | 35.3  | 2.4      | 31970.51 | 42.2      | 18.2      | 16.9      | 5.3       | 17.4    | 15.8    | 31.4      | 
| Clifton-Berea                     | 9874   | 4473   | 5401     | 96.3  | 1.1      | 0.3    | 1.1      | 0.3    | 1.0     | 7.9      | 7.5     | 18.0     | 10.5     | 48.5     | 15.5     | 3529  | 70.0     | 34.7  | 2.8      | 24883.93 | 50.0      | 18.5      | 13.4      | 10.4      | 7.7     | 25.6    | 43.7      | 
```