# Children and Family Health & Well-Being (2010-2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/children-and-family-health-well-being-2010-2012-9be9b) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/bse9-tznm) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/bse9-tznm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/bse9-tznm/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | bse9-tznm |
| Name | Children and Family Health & Well-Being (2010-2012) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | children, health, bnia |
| Created | 2014-05-20T15:29:29Z |
| Publication Date | 2014-05-20T15:41:23Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and socioeconomic indicators for neighborhoods. The Census Bureau collects a wide variety of information through administration of both the decennial Census and the annual American Community Survey (ACS).

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010    | text      | text        |
| Yes      | numeric metric | teenbir10  | teenbir10  | number    | number      |
| Yes      | numeric metric | teenbir11  | teenbir11  | number    | number      |
| Yes      | numeric metric | teenbir12  | teenbir12  | number    | number      |
| Yes      | numeric metric | termbir10  | termbir10  | percent   | percent     |
| Yes      | numeric metric | termbir11  | termbir11  | percent   | percent     |
| Yes      | numeric metric | termbir12  | termbir12  | percent   | percent     |
| Yes      | numeric metric | birthwt10  | birthwt10  | percent   | percent     |
| Yes      | numeric metric | birthwt11  | birthwt11  | percent   | percent     |
| Yes      | numeric metric | birthwt12  | birthwt12  | percent   | percent     |
| Yes      | numeric metric | prenatal10 | prenatal10 | percent   | percent     |
| Yes      | numeric metric | prenatal11 | prenatal11 | percent   | percent     |
| Yes      | numeric metric | prenatal12 | prenatal12 | percent   | percent     |
| Yes      | numeric metric | leadtest10 | leadtest10 | number    | number      |
| Yes      | numeric metric | leadtest11 | leadtest11 | number    | number      |
| Yes      | numeric metric | leadtest12 | leadtest12 | number    | number      |
| Yes      | numeric metric | ebl10      | ebl10      | percent   | percent     |
| Yes      | numeric metric | ebl11      | ebl11      | percent   | percent     |
| Yes      | numeric metric | ebl12      | ebl12      | percent   | percent     |
| Yes      | numeric metric | tanf11     | tanf11     | percent   | percent     |
| Yes      | numeric metric | tanf12     | tanf12     | percent   | percent     |
| Yes      | numeric metric | liquor11   | liquor11   | number    | number      |
| Yes      | numeric metric | liquor12   | liquor12   | number    | number      |
| Yes      | numeric metric | fastfd11   | fastfd11   | number    | number      |
| Yes      | numeric metric | hfai12     | hfai12     | number    | number      |
| Yes      | numeric metric | lifeexp11  | lifeexp11  | number    | number      |
| Yes      | numeric metric | lifeexp12  | lifeexp12  | number    | number      |
| Yes      | numeric metric | mort1_11   | mort1_11   | number    | number      |
| Yes      | numeric metric | mort1_12   | mort1_12   | number    | number      |
| Yes      | numeric metric | mort14_11  | mort14_11  | number    | number      |
| Yes      | numeric metric | mort_14_12 | mort_14_12 | number    | number      |
| Yes      | numeric metric | mort24_11  | mort24_11  | number    | number      |
| Yes      | numeric metric | mort24_12  | mort24_12  | number    | number      |
| Yes      | numeric metric | mort44_11  | mort44_11  | number    | number      |
| Yes      | numeric metric | mort44_12  | mort44_12  | number    | number      |
| Yes      | numeric metric | mort64_11  | mort64_11  | number    | number      |
| Yes      | numeric metric | mort64_12  | mort64_12  | number    | number      |
| Yes      | numeric metric | mort84_11  | mort84_11  | number    | number      |
| Yes      | numeric metric | mort84_12  | mort84_12  | number    | number      |
| Yes      | numeric metric | mort85_11  | mort85_11  | number    | number      |
| Yes      | numeric metric | mort85_12  | mort85_12  | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bse9-tznm d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:liquor12=0.9 m:liquor11=0.7 m:mort84_11=453.8 m:lifeexp11=70 m:lifeexp12=70.4 m:teenbir12=45.9 m:ebl11=0 m:teenbir10=55 m:ebl10=0 m:teenbir11=58.1 m:tanf11=10.2 m:tanf12=12.5 m:ebl12=0 m:leadtest10=386 m:leadtest12=187 m:leadtest11=166 m:mort85_11=1326.5 m:mort85_12=1381.4 m:termbir12=84.3 m:hfai12=7.8 m:mort_14_12=1.9 m:birthwt10=87.4 m:mort14_11=3.2 m:birthwt12=83.8 m:birthwt11=83.8 m:mort24_11=18.2 m:mort24_12=19 m:mort64_11=134.3 m:termbir11=86 m:termbir10=85.3 m:mort64_12=129.4 m:mort44_11=41.9 m:prenatal12=57 m:mort44_12=39.8 m:fastfd11=0.6 m:prenatal10=51.9 m:prenatal11=55.3 m:mort1_11=14.8 m:mort1_12=16.9 m:mort84_12=430.3

series e:bse9-tznm d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:liquor12=0.1 m:liquor11=0.2 m:mort84_11=339.4 m:lifeexp11=74.1 m:lifeexp12=74.7 m:teenbir12=42.8 m:ebl11=0 m:teenbir10=42.8 m:ebl10=0 m:teenbir11=21.4 m:tanf11=4.5 m:tanf12=5.8 m:ebl12=0 m:leadtest10=0 m:leadtest12=0 m:leadtest11=199 m:mort85_11=1539.7 m:mort85_12=1349.2 m:termbir12=89.5 m:hfai12=15.6 m:mort_14_12=1.8 m:birthwt10=91.7 m:mort14_11=1.8 m:birthwt12=90.1 m:birthwt11=90.6 m:mort24_11=18.7 m:mort24_12=15.2 m:mort64_11=89.2 m:termbir11=90.6 m:termbir10=87.5 m:mort64_12=96.1 m:mort44_11=24 m:prenatal12=63 m:mort44_12=19.8 m:fastfd11=0.7 m:prenatal10=64.3 m:prenatal11=67.1 m:mort1_11=12.8 m:mort1_12=11.8 m:mort84_12=329

series e:bse9-tznm d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:liquor12=0.7 m:liquor11=0.8 m:mort84_11=345.3 m:lifeexp11=71.5 m:lifeexp12=72.5 m:teenbir12=58.1 m:ebl11=2 m:teenbir10=67.6 m:ebl10=7.5 m:teenbir11=56.8 m:tanf11=10.1 m:tanf12=11.1 m:ebl12=1.4 m:leadtest10=200 m:leadtest12=356 m:leadtest11=256 m:mort85_11=1984.3 m:mort85_12=1842.5 m:termbir12=82 m:hfai12=10.3 m:mort_14_12=2.2 m:birthwt10=87.7 m:mort14_11=2.2 m:birthwt12=83.8 m:birthwt11=84.5 m:mort24_11=26.4 m:mort24_12=23.6 m:mort64_11=100.6 m:termbir11=82.5 m:termbir10=84 m:mort64_12=105.6 m:mort44_11=30.1 m:prenatal12=63.2 m:mort44_12=26.2 m:fastfd11=1 m:prenatal10=63.9 m:prenatal11=63.3 m:mort1_11=21.3 m:mort1_12=15 m:mort84_12=335.7
```

## Meta Commands

```ls
metric m:teenbir10 p:float l:teenbir10 d:"Teen Birth Rate per 1,000 Females (aged 15-19) (2010)" t:dataTypeName=number

metric m:teenbir11 p:float l:teenbir11 d:"Teen Birth Rate per 1,000 Females (aged 15-19) (2011)" t:dataTypeName=number

metric m:teenbir12 p:float l:teenbir12 d:"Teen Birth Rate per 1,000 Females (aged 15-19) (2012)" t:dataTypeName=number

metric m:termbir10 p:float l:termbir10 d:"Percent of Births Delivered at Term (37-42 Weeks) (2010)" t:dataTypeName=percent

metric m:termbir11 p:float l:termbir11 d:"Percent of Births Delivered at Term (37-42 Weeks) (2011)" t:dataTypeName=percent

metric m:termbir12 p:float l:termbir12 d:"Percent of Births Delivered at Term (37-42 Weeks) (2012)" t:dataTypeName=percent

metric m:birthwt10 p:float l:birthwt10 d:"Percent of Babies Born with a Satisfactory Birth Weight (2010)" t:dataTypeName=percent

metric m:birthwt11 p:float l:birthwt11 d:"Percent of Babies Born with a Satisfactory Birth Weight (2011)" t:dataTypeName=percent

metric m:birthwt12 p:float l:birthwt12 d:"Percent of Babies Born with a Satisfactory Birth Weight (2012)" t:dataTypeName=percent

metric m:prenatal10 p:float l:prenatal10 d:"Percent of Births Where the Mother Received Early Prenatal Care (First Trimester) (2010)" t:dataTypeName=percent

metric m:prenatal11 p:float l:prenatal11 d:"Percent of Births Where the Mother Received Early Prenatal Care (First Trimester) (2011)" t:dataTypeName=percent

metric m:prenatal12 p:float l:prenatal12 d:"Percent of Births Where the Mother Received Early Prenatal Care (First Trimester) (2012)" t:dataTypeName=percent

metric m:leadtest10 p:float l:leadtest10 d:"Number of Children (aged 0-6) Tested for Elevated Blood Lead Levels (2010)" t:dataTypeName=number

metric m:leadtest11 p:float l:leadtest11 d:"Number of Children (aged 0-6) Tested for Elevated Blood Lead Levels (2011)" t:dataTypeName=number

metric m:leadtest12 p:float l:leadtest12 d:"Number of Children (aged 0-6) Tested for Elevated Blood Lead Levels (2012)" t:dataTypeName=number

metric m:ebl10 p:float l:ebl10 d:"Percent of Children (aged 0-6) with Elevated Blood Lead Levels (2010)" t:dataTypeName=percent

metric m:ebl11 p:float l:ebl11 d:"Percent of Children (aged 0-6) with Elevated Blood Lead Levels (2011)" t:dataTypeName=percent

metric m:ebl12 p:float l:ebl12 d:"Percent of Children (aged 0-6) with Elevated Blood Lead Levels (2012)" t:dataTypeName=percent

metric m:tanf11 p:float l:tanf11 d:"Percent of Families Receiving TANF (2011)" t:dataTypeName=percent

metric m:tanf12 p:float l:tanf12 d:"Percent of Families Receiving TANF (2012)" t:dataTypeName=percent

metric m:liquor11 p:float l:liquor11 d:"Liquor Outlet density (per 1,000 Residents) (2011)" t:dataTypeName=number

metric m:liquor12 p:float l:liquor12 d:"Liquor Outlet density (per 1,000 Residents) (2012)" t:dataTypeName=number

metric m:fastfd11 p:float l:fastfd11 d:"Fast Food Outlet Density (per 1,000 Residents) (2011)" t:dataTypeName=number

metric m:hfai12 p:float l:hfai12 d:"Average Healthy Food Availability Index (2012)" t:dataTypeName=number

metric m:lifeexp11 p:float l:lifeexp11 d:"Life Expectancy (2011)" t:dataTypeName=number

metric m:lifeexp12 p:float l:lifeexp12 d:"Life Expectancy (2012)" t:dataTypeName=number

metric m:mort1_11 p:float l:mort1_11 d:"Mortality by Age (Less than 1 year old) (2011)" t:dataTypeName=number

metric m:mort1_12 p:float l:mort1_12 d:"Mortality by Age (Less than 1 year old) (2012)" t:dataTypeName=number

metric m:mort14_11 p:float l:mort14_11 d:"Mortality by Age (1-14 years old) (2011)" t:dataTypeName=number

metric m:mort_14_12 p:float l:mort_14_12 d:"Mortality by Age (1-14 years old) (2012)" t:dataTypeName=number

metric m:mort24_11 p:float l:mort24_11 d:"Mortality by Age (15-24 years old) (2011)" t:dataTypeName=number

metric m:mort24_12 p:float l:mort24_12 d:"Mortality by Age (15-24 years old) (2012)" t:dataTypeName=number

metric m:mort44_11 p:float l:mort44_11 d:"Mortality by Age (25-44 years old) (2011)" t:dataTypeName=number

metric m:mort44_12 p:float l:mort44_12 d:"Mortality by Age (25-44 years old) (2012)" t:dataTypeName=number

metric m:mort64_11 p:float l:mort64_11 d:"Mortality by Age (45-64 years old) (2011)" t:dataTypeName=number

metric m:mort64_12 p:float l:mort64_12 d:"Mortality by Age (45-64 years old) (2012)" t:dataTypeName=number

metric m:mort84_11 p:float l:mort84_11 d:"Mortality by Age (65-84 years old) (2011)" t:dataTypeName=number

metric m:mort84_12 p:float l:mort84_12 d:"Mortality by Age (65-84 years old) (2012)" t:dataTypeName=number

metric m:mort85_11 p:float l:mort85_11 d:"Mortality by Age (85 and over) (2011)" t:dataTypeName=number

metric m:mort85_12 p:float l:mort85_12 d:"Mortality by Age (85 and over) (2012)" t:dataTypeName=number

entity e:bse9-tznm l:"Children and Family Health & Well-Being (2010-2012)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/bse9-tznm

property e:bse9-tznm t:meta.view v:id=bse9-tznm v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Children and Family Health & Well-Being (2010-2012)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:bse9-tznm t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:bse9-tznm t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:bse9-tznm t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | teenbir10 | teenbir11 | teenbir12 | termbir10 | termbir11 | termbir12 | birthwt10 | birthwt11 | birthwt12 | prenatal10 | prenatal11 | prenatal12 | leadtest10 | leadtest11 | leadtest12 | ebl10 | ebl11 | ebl12 | tanf11 | tanf12 | liquor11 | liquor12 | fastfd11 | hfai12 | lifeexp11 | lifeexp12 | mort1_11 | mort1_12 | mort14_11 | mort_14_12 | mort24_11 | mort24_12 | mort44_11 | mort44_12 | mort64_11 | mort64_12 | mort84_11 | mort84_12 | mort85_11 | mort85_12 | 
| ================================= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========== | ========== | ========== | ========== | ========== | ===== | ===== | ===== | ====== | ====== | ======== | ======== | ======== | ====== | ========= | ========= | ======== | ======== | ========= | ========== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| Allendale/Irvington/S. Hilton     | 55.0      | 58.1      | 45.9      | 85.3      | 86.0      | 84.3      | 87.4      | 83.8      | 83.8      | 51.9       | 55.3       | 57.0       | 386.0      | 166.0      | 187.0      | 0.0   | 0.0   | 0.0   | 10.2   | 12.5   | 0.7      | 0.9      | 0.6      | 7.8    | 70.0      | 70.4      | 14.8     | 16.9     | 3.2       | 1.9        | 18.2      | 19.0      | 41.9      | 39.8      | 134.3     | 129.4     | 453.8     | 430.3     | 1326.5    | 1381.4    | 
| Beechfield/Ten Hills/West Hills   | 42.8      | 21.4      | 42.8      | 87.5      | 90.6      | 89.5      | 91.7      | 90.6      | 90.1      | 64.3       | 67.1       | 63.0       | 0.0        | 199.0      | 0.0        | 0.0   | 0.0   | 0.0   | 4.5    | 5.8    | 0.2      | 0.1      | 0.7      | 15.6   | 74.1      | 74.7      | 12.8     | 11.8     | 1.8       | 1.8        | 18.7      | 15.2      | 24.0      | 19.8      | 89.2      | 96.1      | 339.4     | 329.0     | 1539.7    | 1349.2    | 
| Belair-Edison                     | 67.6      | 56.8      | 58.1      | 84.0      | 82.5      | 82.0      | 87.7      | 84.5      | 83.8      | 63.9       | 63.3       | 63.2       | 200.0      | 256.0      | 356.0      | 7.5   | 2.0   | 1.4   | 10.1   | 11.1   | 0.8      | 0.7      | 1.0      | 10.3   | 71.5      | 72.5      | 21.3     | 15.0     | 2.2       | 2.2        | 26.4      | 23.6      | 30.1      | 26.2      | 100.6     | 105.6     | 345.3     | 335.7     | 1984.3    | 1842.5    | 
| Brooklyn/Curtis Bay/Hawkins Point | 111.1     | 94.6      | 63.8      | 83.1      | 82.3      | 85.0      | 89.9      | 86.7      | 91.4      | 50.9       | 47.2       | 49.6       | 0.0        | 360.0      | 374.0      | 0.0   | 0.0   | 0.0   | 13.8   | 14.8   | 1.5      | 1.4      | 0.8      | 8.6    | 69.7      | 69.5      | 7.7      | 7.9      | 3.1       | 4.4        | 17.2      | 13.4      | 36.5      | 34.7      | 145.8     | 155.4     | 466.6     | 468.9     | 1776.0    | 1568.0    | 
| Canton                            | 46.5      | 23.3      | 0.0       | 94.6      | 93.7      | 90.6      | 94.6      | 97.6      | 92.9      | 73.9       | 79.4       | 79.5       | 96.0       | 124.0      | 130.0      | 0.0   | 0.0   | 0.0   | 1.4    | 0.9    | 4.6      | 4.9      | 1.1      | 16.9   | 77.0      | 77.4      | 5.7      | 1.8      | 0.0       | 0.0        | 6.6       | 8.8       | 2.8       | 3.3       | 78.8      | 74.8      | 373.3     | 384.2     | 1539.5    | 1407.9    | 
| Cedonia/Frankford                 | 48.9      | 42.1      | 38.7      | 83.8      | 86.3      | 84.8      | 84.4      | 85.7      | 86.5      | 56.6       | 61.6       | 63.8       | 240.0      | 199.0      | 320.0      | 0.0   | 0.0   | 0.0   | 8.5    | 10.5   | 0.6      | 0.8      | 0.8      | 12.3   | 72.8      | 72.8      | 13.7     | 15.2     | 2.3       | 2.3        | 12.3      | 12.8      | 27.8      | 28.7      | 95.7      | 95.4      | 434.6     | 434.6     | 1560.0    | 1480.0    | 
| Cherry Hill                       | 57.6      | 60.5      | 63.4      | 80.9      | 79.6      | 83.1      | 88.8      | 79.0      | 89.8      | 57.2       | 52.5       | 57.2       | 198.0      | 322.0      | 382.0      | 0.0   | 0.0   | 0.0   | 21.9   | 23.5   | 0.1      | 0.1      | 0.7      | 8.8    | 68.7      | 68.8      | 15.2     | 14.8     | 3.4       | 3.4        | 21.9      | 21.9      | 47.2      | 47.2      | 140.2     | 142.7     | 473.4     | 442.5     | 1423.1    | 1461.5    | 
| Chinquapin Park/Belvedere         | 50.6      | 84.4      | 63.3      | 87.0      | 89.3      | 89.4      | 92.6      | 87.7      | 90.2      | 63.9       | 58.2       | 49.2       | 146.0      | 233.0      | 138.0      | 0.0   | 0.0   | 0.0   | 5.6    | 7.3    | 1.3      | 0.8      | 0.4      | 15.3   | 75.4      | 74.9      | 11.1     | 11.3     | 1.6       | 1.6        | 9.0       | 12.5      | 18.3      | 18.3      | 97.9      | 107.1     | 316.3     | 311.3     | 1576.5    | 1694.1    | 
| Claremont/Armistead               | 48.9      | 48.9      | 45.1      | 83.0      | 89.2      | 89.5      | 83.0      | 90.0      | 91.1      | 47.2       | 50.8       | 63.7       | 240.0      | 222.0      | 244.0      | 0.0   | 0.0   | 0.0   | 7.9    | 7.7    | 1.1      | 0.9      | 0.9      | 7.4    | 73.1      | 72.7      | 0.0      | 3.1      | 1.1       | 0.0        | 11.7      | 10.1      | 19.4      | 19.4      | 127.1     | 132.1     | 500.0     | 522.9     | 1195.1    | 1268.3    | 
| Clifton-Berea                     | 72.0      | 61.7      | 77.1      | 82.8      | 85.6      | 85.7      | 83.6      | 88.1      | 90.3      | 52.2       | 56.9       | 64.0       | 0.0        | 0.0        | 0.0        | 0.0   | 0.0   | 0.0   | 21.0   | 25.3   | 1.9      | 1.7      | 0.9      | 8.8    | 65.1      | 66.4      | 21.5     | 17.6     | 3.1       | 3.1        | 41.3      | 31.9      | 66.8      | 59.5      | 195.0     | 185.6     | 415.4     | 416.9     | 1449.3    | 1468.6    | 
```