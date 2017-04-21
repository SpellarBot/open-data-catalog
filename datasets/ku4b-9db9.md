# Children and Family Health & Well-Being (2010-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/children-and-family-health-well-being-2010-2013) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/ku4b-9db9) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/ku4b-9db9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/ku4b-9db9/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | ku4b-9db9 |
| Name | Children and Family Health & Well-Being (2010-2013) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | children, family, health, bnia |
| Created | 2015-05-14T20:05:07Z |
| Publication Date | 2015-05-14T20:09:30Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and socioeconomic indicators for neighborhoods. The Census Bureau collects a wide variety of information through administration of both the decennial Census and the annual American Community Survey (ACS).

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | neighborhood | Neighborhood | text      | text        |
| Yes      | numeric metric | teenbir10    | teenbir10    | number    | number      |
| Yes      | numeric metric | teenbir11    | teenbir11    | number    | number      |
| Yes      | numeric metric | teenbir12    | teenbir12    | number    | number      |
| Yes      | numeric metric | teenbir13    | teenbir13    | number    | number      |
| Yes      | numeric metric | termbir10    | termbir10    | percent   | percent     |
| Yes      | numeric metric | termbir11    | termbir11    | percent   | percent     |
| Yes      | numeric metric | termbir12    | termbir12    | percent   | percent     |
| Yes      | numeric metric | termbir13    | termbir13    | percent   | percent     |
| Yes      | numeric metric | birthwt10    | birthwt10    | percent   | percent     |
| Yes      | numeric metric | birthwt11    | birthwt11    | percent   | percent     |
| Yes      | numeric metric | birthwt12    | birthwt12    | percent   | percent     |
| Yes      | numeric metric | birthwt13    | birthwt13    | percent   | percent     |
| Yes      | numeric metric | prenatal10   | prenatal10   | percent   | percent     |
| Yes      | numeric metric | prenatal11   | prenatal11   | percent   | percent     |
| Yes      | numeric metric | prenatal12   | prenatal12   | percent   | percent     |
| Yes      | numeric metric | prenatal13   | prenatal13   | percent   | percent     |
| Yes      | numeric metric | leadtest10   | leadtest10   | number    | number      |
| Yes      | numeric metric | leadtest11   | leadtest11   | number    | number      |
| Yes      | numeric metric | leadtest12   | leadtest12   | number    | number      |
| Yes      | numeric metric | leadtest13   | leadtest13   | number    | number      |
| Yes      | numeric metric | ebl10        | ebl10        | percent   | percent     |
| Yes      | numeric metric | ebl11        | ebl11        | percent   | percent     |
| Yes      | numeric metric | ebl12        | ebl12        | percent   | percent     |
| Yes      | numeric metric | ebl13        | ebl13        | percent   | percent     |
| Yes      | numeric metric | tanf11       | tanf11       | percent   | percent     |
| Yes      | numeric metric | tanf12       | tanf12       | percent   | percent     |
| Yes      | numeric metric | tanf13       | tanf13       | percent   | percent     |
| Yes      | numeric metric | liquor11     | liquor11     | number    | number      |
| Yes      | numeric metric | liquor12     | liquor12     | number    | number      |
| Yes      | numeric metric | liquor13     | liquor13     | number    | number      |
| Yes      | numeric metric | fastfd11     | fastfd11     | number    | number      |
| Yes      | numeric metric | fastfd13     | fastfd13     | number    | number      |
| Yes      | numeric metric | hfai12       | hfai12       | number    | number      |
| Yes      | numeric metric | lifeexp11    | lifeexp11    | number    | number      |
| Yes      | numeric metric | lifeexp12    | lifeexp12    | number    | number      |
| Yes      | numeric metric | lifeexp13    | lifeexp13    | number    | number      |
| Yes      | numeric metric | mort1_11     | mort1_11     | number    | number      |
| Yes      | numeric metric | mort1_12     | mort1_12     | number    | number      |
| Yes      | numeric metric | mort1_13     | mort1_13     | number    | number      |
| Yes      | numeric metric | mort14_11    | mort14_11    | number    | number      |
| Yes      | numeric metric | mort_14_12   | mort_14_12   | number    | number      |
| Yes      | numeric metric | mort_14_13   | mort_14_13   | number    | number      |
| Yes      | numeric metric | mort24_11    | mort24_11    | number    | number      |
| Yes      | numeric metric | mort24_12    | mort24_12    | number    | number      |
| Yes      | numeric metric | mort24_13    | mort24_13    | number    | number      |
| Yes      | numeric metric | mort44_11    | mort44_11    | number    | number      |
| Yes      | numeric metric | mort44_12    | mort44_12    | number    | number      |
| Yes      | numeric metric | mort44_13    | mort44_13    | number    | number      |
| Yes      | numeric metric | mort64_11    | mort64_11    | number    | number      |
| Yes      | numeric metric | mort64_12    | mort64_12    | number    | number      |
| Yes      | numeric metric | mort64_13    | mort64_13    | number    | number      |
| Yes      | numeric metric | mort84_11    | mort84_11    | number    | number      |
| Yes      | numeric metric | mort84_12    | mort84_12    | number    | number      |
| Yes      | numeric metric | mort84_13    | mort84_13    | number    | number      |
| Yes      | numeric metric | mort85_11    | mort85_11    | number    | number      |
| Yes      | numeric metric | mort85_12    | mort85_12    | number    | number      |
| Yes      | numeric metric | mort85_13    | mort85_13    | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ku4b-9db9 d:2010-01-01T00:00:00.000Z t:neighborhood="Allendale/Irvington/S. Hilton" m:liquor12=0.9 m:liquor11=0.7 m:liquor13=0.6 m:mort84_11=453.8 m:lifeexp11=70 m:lifeexp13=71.3 m:lifeexp12=70.4 m:tanf11=10.2 m:tanf12=12.5 m:tanf13=11.1 m:mort85_11=1326.5 m:mort85_12=1381.4 m:mort_14_13=1.9 m:mort_14_12=1.9 m:mort14_11=3.2 m:birthwt10=87.4 m:birthwt12=83.8 m:mort24_11=18.2 m:birthwt11=83.8 m:mort24_12=19 m:mort24_13=14.9 m:birthwt13=85.3 m:mort64_11=134.3 m:termbir11=86 m:mort64_13=102.3 m:termbir10=85.3 m:mort64_12=129.4 m:fastfd13=0.8 m:mort44_11=41.9 m:mort44_12=39.8 m:prenatal12=57 m:prenatal13=47.3 m:mort44_13=29.6 m:fastfd11=0.6 m:prenatal10=51.9 m:prenatal11=55.3 m:mort1_13=14.1 m:mort1_11=14.8 m:mort1_12=16.9 m:mort84_13=336.1 m:mort84_12=430.3 m:teenbir12=45.9 m:leadtest13=336 m:teenbir13=38.2 m:teenbir10=55 m:ebl11=0 m:teenbir11=58.1 m:ebl10=0 m:leadtest10=386 m:ebl12=0 m:ebl13=0 m:leadtest12=187 m:leadtest11=166 m:termbir13=84.4 m:termbir12=84.3 m:hfai12=7.8 m:mort85_13=1065.3

series e:ku4b-9db9 d:2010-01-01T00:00:00.000Z t:neighborhood="Beechfield/Ten Hills/West Hills" m:liquor12=0.1 m:liquor11=0.2 m:liquor13=0.1 m:mort84_11=339.4 m:lifeexp11=74.1 m:lifeexp13=75.4 m:lifeexp12=74.7 m:tanf11=4.5 m:tanf12=5.8 m:tanf13=4.8 m:mort85_11=1539.7 m:mort85_12=1349.2 m:mort_14_13=0.9 m:mort_14_12=1.8 m:mort14_11=1.8 m:birthwt10=91.7 m:birthwt12=90.1 m:mort24_11=18.7 m:birthwt11=90.6 m:mort24_12=15.2 m:mort24_13=12.9 m:birthwt13=85.6 m:mort64_11=89.2 m:termbir11=90.6 m:mort64_13=71.5 m:termbir10=87.5 m:mort64_12=96.1 m:fastfd13=0.7 m:mort44_11=24 m:mort44_12=19.8 m:prenatal12=63 m:prenatal13=49 m:mort44_13=13.8 m:fastfd11=0.7 m:prenatal10=64.3 m:prenatal11=67.1 m:mort1_13=14.7 m:mort1_11=12.8 m:mort1_12=11.8 m:mort84_13=268.4 m:mort84_12=329 m:teenbir12=42.8 m:leadtest13=301 m:teenbir13=29.4 m:teenbir10=42.8 m:ebl11=0 m:teenbir11=21.4 m:ebl10=0 m:leadtest10=0 m:ebl12=0 m:ebl13=0 m:leadtest12=0 m:leadtest11=199 m:termbir13=83.7 m:termbir12=89.5 m:hfai12=15.6 m:mort85_13=904.8

series e:ku4b-9db9 d:2010-01-01T00:00:00.000Z t:neighborhood=Belair-Edison m:liquor12=0.7 m:liquor11=0.8 m:liquor13=0.5 m:mort84_11=345.3 m:lifeexp11=71.5 m:lifeexp13=72.1 m:lifeexp12=72.5 m:tanf11=10.1 m:tanf12=11.1 m:tanf13=10.1 m:mort85_11=1984.3 m:mort85_12=1842.5 m:mort_14_13=1.7 m:mort_14_12=2.2 m:mort14_11=2.2 m:birthwt10=87.7 m:birthwt12=83.8 m:mort24_11=26.4 m:birthwt11=84.5 m:mort24_12=23.6 m:mort24_13=15 m:birthwt13=87 m:mort64_11=100.6 m:termbir11=82.5 m:mort64_13=86.5 m:termbir10=84 m:mort64_12=105.6 m:fastfd13=0.9 m:mort44_11=30.1 m:mort44_12=26.2 m:prenatal12=63.2 m:prenatal13=44.9 m:mort44_13=22.3 m:fastfd11=1 m:prenatal10=63.9 m:prenatal11=63.3 m:mort1_13=14.3 m:mort1_11=21.3 m:mort1_12=15 m:mort84_13=278.4 m:mort84_12=335.7 m:teenbir12=58.1 m:leadtest13=0 m:teenbir13=33.8 m:teenbir10=67.6 m:ebl11=2 m:teenbir11=56.8 m:ebl10=7.5 m:leadtest10=200 m:ebl12=1.4 m:ebl13=0 m:leadtest12=356 m:leadtest11=256 m:termbir13=84.1 m:termbir12=82 m:hfai12=10.3 m:mort85_13=1574.8
```

## Meta Commands

```ls
metric m:teenbir10 p:float l:teenbir10 t:dataTypeName=number

metric m:teenbir11 p:float l:teenbir11 t:dataTypeName=number

metric m:teenbir12 p:float l:teenbir12 t:dataTypeName=number

metric m:teenbir13 p:float l:teenbir13 t:dataTypeName=number

metric m:termbir10 p:float l:termbir10 t:dataTypeName=percent

metric m:termbir11 p:float l:termbir11 t:dataTypeName=percent

metric m:termbir12 p:float l:termbir12 t:dataTypeName=percent

metric m:termbir13 p:float l:termbir13 t:dataTypeName=percent

metric m:birthwt10 p:float l:birthwt10 t:dataTypeName=percent

metric m:birthwt11 p:float l:birthwt11 t:dataTypeName=percent

metric m:birthwt12 p:float l:birthwt12 t:dataTypeName=percent

metric m:birthwt13 p:float l:birthwt13 t:dataTypeName=percent

metric m:prenatal10 p:float l:prenatal10 t:dataTypeName=percent

metric m:prenatal11 p:float l:prenatal11 t:dataTypeName=percent

metric m:prenatal12 p:float l:prenatal12 t:dataTypeName=percent

metric m:prenatal13 p:float l:prenatal13 t:dataTypeName=percent

metric m:leadtest10 p:float l:leadtest10 t:dataTypeName=number

metric m:leadtest11 p:float l:leadtest11 t:dataTypeName=number

metric m:leadtest12 p:float l:leadtest12 t:dataTypeName=number

metric m:leadtest13 p:float l:leadtest13 t:dataTypeName=number

metric m:ebl10 p:float l:ebl10 t:dataTypeName=percent

metric m:ebl11 p:float l:ebl11 t:dataTypeName=percent

metric m:ebl12 p:float l:ebl12 t:dataTypeName=percent

metric m:ebl13 p:float l:ebl13 t:dataTypeName=percent

metric m:tanf11 p:float l:tanf11 t:dataTypeName=percent

metric m:tanf12 p:float l:tanf12 t:dataTypeName=percent

metric m:tanf13 p:float l:tanf13 t:dataTypeName=percent

metric m:liquor11 p:float l:liquor11 t:dataTypeName=number

metric m:liquor12 p:float l:liquor12 t:dataTypeName=number

metric m:liquor13 p:float l:liquor13 t:dataTypeName=number

metric m:fastfd11 p:float l:fastfd11 t:dataTypeName=number

metric m:fastfd13 p:float l:fastfd13 t:dataTypeName=number

metric m:hfai12 p:float l:hfai12 t:dataTypeName=number

metric m:lifeexp11 p:float l:lifeexp11 t:dataTypeName=number

metric m:lifeexp12 p:float l:lifeexp12 t:dataTypeName=number

metric m:lifeexp13 p:float l:lifeexp13 t:dataTypeName=number

metric m:mort1_11 p:float l:mort1_11 t:dataTypeName=number

metric m:mort1_12 p:float l:mort1_12 t:dataTypeName=number

metric m:mort1_13 p:float l:mort1_13 t:dataTypeName=number

metric m:mort14_11 p:float l:mort14_11 t:dataTypeName=number

metric m:mort_14_12 p:float l:mort_14_12 t:dataTypeName=number

metric m:mort_14_13 p:float l:mort_14_13 t:dataTypeName=number

metric m:mort24_11 p:float l:mort24_11 t:dataTypeName=number

metric m:mort24_12 p:float l:mort24_12 t:dataTypeName=number

metric m:mort24_13 p:float l:mort24_13 t:dataTypeName=number

metric m:mort44_11 p:float l:mort44_11 t:dataTypeName=number

metric m:mort44_12 p:float l:mort44_12 t:dataTypeName=number

metric m:mort44_13 p:float l:mort44_13 t:dataTypeName=number

metric m:mort64_11 p:float l:mort64_11 t:dataTypeName=number

metric m:mort64_12 p:float l:mort64_12 t:dataTypeName=number

metric m:mort64_13 p:float l:mort64_13 t:dataTypeName=number

metric m:mort84_11 p:float l:mort84_11 t:dataTypeName=number

metric m:mort84_12 p:float l:mort84_12 t:dataTypeName=number

metric m:mort84_13 p:float l:mort84_13 t:dataTypeName=number

metric m:mort85_11 p:float l:mort85_11 t:dataTypeName=number

metric m:mort85_12 p:float l:mort85_12 t:dataTypeName=number

metric m:mort85_13 p:float l:mort85_13 t:dataTypeName=number

entity e:ku4b-9db9 l:"Children and Family Health & Well-Being (2010-2013)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/ku4b-9db9

property e:ku4b-9db9 t:meta.view v:id=ku4b-9db9 v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Children and Family Health & Well-Being (2010-2013)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:ku4b-9db9 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ku4b-9db9 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:ku4b-9db9 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| neighborhood                      | teenbir10 | teenbir11 | teenbir12 | teenbir13 | termbir10 | termbir11 | termbir12 | termbir13 | birthwt10 | birthwt11 | birthwt12 | birthwt13 | prenatal10 | prenatal11 | prenatal12 | prenatal13 | leadtest10 | leadtest11 | leadtest12 | leadtest13 | ebl10 | ebl11 | ebl12 | ebl13 | tanf11 | tanf12 | tanf13 | liquor11 | liquor12 | liquor13 | fastfd11 | fastfd13 | hfai12 | lifeexp11 | lifeexp12 | lifeexp13 | mort1_11 | mort1_12 | mort1_13 | mort14_11 | mort_14_12 | mort_14_13 | mort24_11 | mort24_12 | mort24_13 | mort44_11 | mort44_12 | mort44_13 | mort64_11 | mort64_12 | mort64_13 | mort84_11 | mort84_12 | mort84_13 | mort85_11 | mort85_12 | mort85_13 | 
| ================================= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ===== | ===== | ===== | ===== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ====== | ========= | ========= | ========= | ======== | ======== | ======== | ========= | ========== | ========== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| Allendale/Irvington/S. Hilton     | 55.0      | 58.1      | 45.9      | 38.2      | 85.3      | 86.0      | 84.3      | 84.4      | 87.4      | 83.8      | 83.8      | 85.3      | 51.9       | 55.3       | 57.0       | 47.3       | 386.0      | 166.0      | 187.0      | 336.0      | 0.0   | 0.0   | 0.0   | 0.0   | 10.2   | 12.5   | 11.1   | 0.7      | 0.9      | 0.6      | 0.6      | 0.8      | 7.8    | 70.0      | 70.4      | 71.3      | 14.8     | 16.9     | 14.1     | 3.2       | 1.9        | 1.9        | 18.2      | 19.0      | 14.9      | 41.9      | 39.8      | 29.6      | 134.3     | 129.4     | 102.3     | 453.8     | 430.3     | 336.1     | 1326.5    | 1381.4    | 1065.3    | 
| Beechfield/Ten Hills/West Hills   | 42.8      | 21.4      | 42.8      | 29.4      | 87.5      | 90.6      | 89.5      | 83.7      | 91.7      | 90.6      | 90.1      | 85.6      | 64.3       | 67.1       | 63.0       | 49.0       | 0.0        | 199.0      | 0.0        | 301.0      | 0.0   | 0.0   | 0.0   | 0.0   | 4.5    | 5.8    | 4.8    | 0.2      | 0.1      | 0.1      | 0.7      | 0.7      | 15.6   | 74.1      | 74.7      | 75.4      | 12.8     | 11.8     | 14.7     | 1.8       | 1.8        | 0.9        | 18.7      | 15.2      | 12.9      | 24.0      | 19.8      | 13.8      | 89.2      | 96.1      | 71.5      | 339.4     | 329.0     | 268.4     | 1539.7    | 1349.2    | 904.8     | 
| Belair-Edison                     | 67.6      | 56.8      | 58.1      | 33.8      | 84.0      | 82.5      | 82.0      | 84.1      | 87.7      | 84.5      | 83.8      | 87.0      | 63.9       | 63.3       | 63.2       | 44.9       | 200.0      | 256.0      | 356.0      | 0.0        | 7.5   | 2.0   | 1.4   | 0.0   | 10.1   | 11.1   | 10.1   | 0.8      | 0.7      | 0.5      | 1.0      | 0.9      | 10.3   | 71.5      | 72.5      | 72.1      | 21.3     | 15.0     | 14.3     | 2.2       | 2.2        | 1.7        | 26.4      | 23.6      | 15.0      | 30.1      | 26.2      | 22.3      | 100.6     | 105.6     | 86.5      | 345.3     | 335.7     | 278.4     | 1984.3    | 1842.5    | 1574.8    | 
| Brooklyn/Curtis Bay/Hawkins Point | 111.1     | 94.6      | 63.8      | 52.0      | 83.1      | 82.3      | 85.0      | 87.1      | 89.9      | 86.7      | 91.4      | 86.3      | 50.9       | 47.2       | 49.6       | 43.9       | 0.0        | 360.0      | 374.0      | 115.0      | 0.0   | 0.0   | 0.0   | 0.0   | 13.8   | 14.8   | 14.8   | 1.5      | 1.4      | 1.3      | 0.8      | 0.9      | 8.6    | 69.7      | 69.5      | 69.5      | 7.7      | 7.9      | 10.2     | 3.1       | 4.4        | 3.1        | 17.2      | 13.4      | 11.5      | 36.5      | 34.7      | 27.2      | 145.8     | 155.4     | 114.8     | 466.6     | 468.9     | 378.3     | 1776.0    | 1568.0    | 1376.0    | 
| Canton                            | 46.5      | 23.3      | 0.0       | 46.5      | 94.6      | 93.7      | 90.6      | 92.7      | 94.6      | 97.6      | 92.9      | 95.5      | 73.9       | 79.4       | 79.5       | 66.4       | 96.0       | 124.0      | 130.0      | 129.0      | 0.0   | 0.0   | 0.0   | 0.0   | 1.4    | 0.9    | 0.6    | 4.6      | 4.9      | 4.3      | 1.1      | 1.2      | 16.9   | 77.0      | 77.4      | 77.3      | 5.7      | 1.8      | 1.8      | 0.0       | 0.0        | 0.0        | 6.6       | 8.8       | 8.8       | 2.8       | 3.3       | 2.8       | 78.8      | 74.8      | 57.4      | 373.3     | 384.2     | 310.6     | 1539.5    | 1407.9    | 1065.8    | 
| Cedonia/Frankford                 | 48.9      | 42.1      | 38.7      | 45.5      | 83.8      | 86.3      | 84.8      | 87.8      | 84.4      | 85.7      | 86.5      | 91.4      | 56.6       | 61.6       | 63.8       | 48.7       | 240.0      | 199.0      | 320.0      | 287.0      | 0.0   | 0.0   | 0.0   | 0.0   | 8.5    | 10.5   | 7.9    | 0.6      | 0.8      | 0.6      | 0.8      | 0.9      | 12.3   | 72.8      | 72.8      | 72.2      | 13.7     | 15.2     | 14.4     | 2.3       | 2.3        | 2.3        | 12.3      | 12.8      | 9.1       | 27.8      | 28.7      | 22.8      | 95.7      | 95.4      | 79.8      | 434.6     | 434.6     | 374.3     | 1560.0    | 1480.0    | 1184.0    | 
| Cherry Hill                       | 57.6      | 60.5      | 63.4      | 74.9      | 80.9      | 79.6      | 83.1      | 84.6      | 88.8      | 79.0      | 89.8      | 84.0      | 57.2       | 52.5       | 57.2       | 47.4       | 198.0      | 322.0      | 382.0      | 149.0      | 0.0   | 0.0   | 0.0   | 0.0   | 21.9   | 23.5   | 21.3   | 0.1      | 0.1      | 0.1      | 0.7      | 1.0      | 8.8    | 68.7      | 68.8      | 69.3      | 15.2     | 14.8     | 17.4     | 3.4       | 3.4        | 2.5        | 21.9      | 21.9      | 16.1      | 47.2      | 47.2      | 33.8      | 140.2     | 142.7     | 113.4     | 473.4     | 442.5     | 363.6     | 1423.1    | 1461.5    | 1269.2    | 
| Chinquapin Park/Belvedere         | 50.6      | 84.4      | 63.3      | 16.9      | 87.0      | 89.3      | 89.4      | 89.3      | 92.6      | 87.7      | 90.2      | 91.3      | 63.9       | 58.2       | 49.2       | 54.4       | 146.0      | 233.0      | 138.0      | 105.0      | 0.0   | 0.0   | 0.0   | 0.0   | 5.6    | 7.3    | 5.6    | 1.3      | 0.8      | 1.3      | 0.4      | 0.8      | 15.3   | 75.4      | 74.9      | 75.0      | 11.1     | 11.3     | 11.8     | 1.6       | 1.6        | 0.0        | 9.0       | 12.5      | 12.5      | 18.3      | 18.3      | 13.7      | 97.9      | 107.1     | 85.9      | 316.3     | 311.3     | 256.5     | 1576.5    | 1694.1    | 1458.8    | 
| Claremont/Armistead               | 48.9      | 48.9      | 45.1      | 48.9      | 83.0      | 89.2      | 89.5      | 83.3      | 83.0      | 90.0      | 91.1      | 84.2      | 47.2       | 50.8       | 63.7       | 47.4       | 240.0      | 222.0      | 244.0      | 155.0      | 0.0   | 0.0   | 0.0   | 0.0   | 7.9    | 7.7    | 7.0    | 1.1      | 0.9      | 1.1      | 0.9      | 1.1      | 7.4    | 73.1      | 72.7      | 72.5      | 0.0      | 3.1      | 4.9      | 1.1       | 0.0        | 0.0        | 11.7      | 10.1      | 6.7       | 19.4      | 19.4      | 16.9      | 127.1     | 132.1     | 110.2     | 500.0     | 522.9     | 380.0     | 1195.1    | 1268.3    | 1170.7    | 
| Clifton-Berea                     | 72.0      | 61.7      | 77.1      | 51.4      | 82.8      | 85.6      | 85.7      | 82.2      | 83.6      | 88.1      | 90.3      | 81.5      | 52.2       | 56.9       | 64.0       | 42.2       | 0.0        | 0.0        | 0.0        | 0.0        | 0.0   | 0.0   | 0.0   | 0.0   | 21.0   | 25.3   | 24.1   | 1.9      | 1.7      | 1.9      | 0.9      | 1.4      | 8.8    | 65.1      | 66.4      | 66.8      | 21.5     | 17.6     | 17.8     | 3.1       | 3.1        | 3.1        | 41.3      | 31.9      | 24.0      | 66.8      | 59.5      | 48.7      | 195.0     | 185.6     | 146.0     | 415.4     | 416.9     | 335.3     | 1449.3    | 1468.6    | 1227.1    | 
```