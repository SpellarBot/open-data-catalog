# Public Health Statistics - Prenatal care in Chicago, by year, 1999 ? 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-prenatal-care-in-chicago-by-year-1999-2009-ed1c9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2q9j-hh6g) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2q9j-hh6g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2q9j-hh6g/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2q9j-hh6g |
| Name | Public Health Statistics - Prenatal care in Chicago, by year, 1999 ? 2009 |
| Attribution | Illinois Department of Public Health (IDPH) |
| Category | Health & Human Services |
| Tags | birth, maternal health, care |
| Created | 2011-12-30T15:19:11Z |
| Publication Date | 2012-05-22T18:37:46Z |

## Description

This dataset contains the annual number and percent of live births by the trimester in which the mother began prenatal care, with corresponding 95% confidence intervals, by Chicago community area, for the years 1999 ? 2009.  See full description at http://bit.ly/KcmIg2

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | community_area_number         | Community Area Number         | text      | number      |
| Yes      | series tag     | community_area_name           | Community Area Name           | text      | text        |
| Yes      | series tag     | trimester_prenatal_care_began | Trimester Prenatal Care Began | text      | text        |
| Yes      | numeric metric | births_1999                   | Births 1999                   | number    | number      |
| Yes      | numeric metric | percent_1999                  | Percent 1999                  | number    | number      |
| Yes      | numeric metric | percent_1999_lower_ci         | Percent 1999 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_1999_upper_ci         | Percent 1999 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2000                   | Births 2000                   | number    | number      |
| Yes      | numeric metric | percent_2000                  | Percent 2000                  | number    | number      |
| Yes      | numeric metric | percent_2000_lower_ci         | Percent 2000 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2000_upper_ci         | Percent 2000 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2001                   | Births 2001                   | number    | number      |
| Yes      | numeric metric | percent_2001                  | Percent 2001                  | number    | number      |
| Yes      | numeric metric | percent_2001_lower_ci         | Percent 2001 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2001_upper_ci         | Percent 2001 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2002                   | Births 2002                   | number    | number      |
| Yes      | numeric metric | percent_2002                  | Percent 2002                  | number    | number      |
| Yes      | numeric metric | percent_2002_lower_ci         | Percent 2002 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2002_upper_ci         | Percent 2002 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2003                   | Births 2003                   | number    | number      |
| Yes      | numeric metric | percent_2003                  | Percent 2003                  | number    | number      |
| Yes      | numeric metric | percent_2003_lower_ci         | Percent 2003 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2003_upper_ci         | Percent 2003 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2004                   | Births 2004                   | number    | number      |
| Yes      | numeric metric | percent_2004                  | Percent 2004                  | number    | number      |
| Yes      | numeric metric | percent_2004_lower_ci         | Percent 2004 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2004_upper_ci         | Percent 2004 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2005                   | Births 2005                   | number    | number      |
| Yes      | numeric metric | percent_2005                  | Percent 2005                  | number    | number      |
| Yes      | numeric metric | percent_2005_lower_ci         | Percent 2005 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2005_upper_ci         | Percent 2005 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2006                   | Births 2006                   | number    | number      |
| Yes      | numeric metric | percent_2006                  | Percent 2006                  | number    | number      |
| Yes      | numeric metric | percent_2006_lower_ci         | Percent 2006 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2006_upper_ci         | Percent 2006 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2007                   | Births 2007                   | number    | number      |
| Yes      | numeric metric | percent_2007                  | Percent 2007                  | number    | number      |
| Yes      | numeric metric | percent_2007_lower_ci         | Percent 2007 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2007_upper_ci         | Percent 2007 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2008                   | Births 2008                   | number    | number      |
| Yes      | numeric metric | percent_2008                  | Percent 2008                  | number    | number      |
| Yes      | numeric metric | percent_2008_lower_ci         | Percent 2008 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2008_upper_ci         | Percent 2008 Upper CI         | number    | number      |
| Yes      | numeric metric | births_2009                   | Births 2009                   | number    | number      |
| Yes      | numeric metric | percent_2009                  | Percent 2009                  | number    | number      |
| Yes      | numeric metric | percent_2009_lower_ci         | Percent 2009 Lower CI         | number    | number      |
| Yes      | numeric metric | percent_2009_upper_ci         | Percent 2009 Upper CI         | number    | number      |
| Yes      | series tag     | warning                       | Warning                       | text      | text        |
```

## Time Field

```ls
Value = 1999
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2q9j-hh6g d:1999-01-01T00:00:00.000Z t:trimester_prenatal_care_began="1ST TRIMESTER" t:community_area_name="ROGERS PARK" t:community_area_number=1 m:births_2004=517 m:percent_2009=73 m:births_2003=613 m:percent_2008=71.6 m:births_2006=622 m:births_2005=541 m:births_2000=692 m:births_2002=674 m:percent_2007_lower_ci=65.2 m:births_2001=731 m:percent_2006_upper_ci=69.6 m:percent_2008_lower_ci=68.6 m:percent_2009_upper_ci=75.9 m:percent_2008_upper_ci=74.6 m:percent_1999=58.9 m:percent_2001_upper_ci=64.4 m:births_2007=622 m:births_2008=639 m:births_1999=726 m:births_2009=670 m:percent_2003_lower_ci=56.9 m:percent_2001_lower_ci=58.8 m:percent_1999_upper_ci=61.6 m:percent_2004_lower_ci=52.6 m:percent_2005_lower_ci=57.5 m:percent_2002_upper_ci=64.1 m:percent_2002_lower_ci=58.3 m:percent_2006_lower_ci=63.6 m:percent_1999_lower_ci=56.2 m:percent_2000_lower_ci=51.9 m:percent_2007=68.2 m:percent_2006=66.6 m:percent_2005=60.7 m:percent_2004=55.8 m:percent_2003=59.9 m:percent_2002=61.2 m:percent_2005_upper_ci=63.9 m:percent_2001=61.6 m:percent_2000=54.6 m:percent_2000_upper_ci=57.3 m:percent_2003_upper_ci=62.9 m:percent_2007_upper_ci=71.2 m:percent_2004_upper_ci=59 m:percent_2009_lower_ci=70.1

series e:2q9j-hh6g d:1999-01-01T00:00:00.000Z t:trimester_prenatal_care_began="2ND TRIMESTER" t:community_area_name="ROGERS PARK" t:community_area_number=1 m:births_2004=153 m:percent_2009=9.9 m:births_2003=165 m:percent_2008=9.8 m:births_2006=117 m:births_2005=115 m:births_2000=326 m:births_2002=226 m:percent_2007_lower_ci=8.5 m:births_2001=245 m:percent_2006_upper_ci=14.6 m:percent_2008_lower_ci=7.9 m:percent_2009_upper_ci=11.8 m:percent_2008_upper_ci=11.7 m:percent_1999=21 m:percent_2001_upper_ci=22.9 m:births_2007=96 m:births_2008=87 m:births_1999=259 m:births_2009=91 m:percent_2003_lower_ci=13.8 m:percent_2001_lower_ci=18.3 m:percent_1999_upper_ci=23.3 m:percent_2004_lower_ci=14.1 m:percent_2005_lower_ci=10.7 m:percent_2002_upper_ci=22.9 m:percent_2002_lower_ci=18.1 m:percent_2006_lower_ci=10.4 m:percent_1999_lower_ci=18.7 m:percent_2000_lower_ci=23.3 m:percent_2007=10.5 m:percent_2006=12.5 m:percent_2005=12.9 m:percent_2004=16.5 m:percent_2003=16.1 m:percent_2002=20.5 m:percent_2005_upper_ci=15.1 m:percent_2001=20.6 m:percent_2000=25.7 m:percent_2000_upper_ci=28.1 m:percent_2003_upper_ci=18.4 m:percent_2007_upper_ci=12.5 m:percent_2004_upper_ci=18.9 m:percent_2009_lower_ci=8

series e:2q9j-hh6g d:1999-01-01T00:00:00.000Z t:trimester_prenatal_care_began="3RD TRIMESTER" t:community_area_name="ROGERS PARK" t:community_area_number=1 t:warning="Percent and confidence interval estimates for years in which fewer than 20 births reported this attribute are unreliable." m:births_2004=47 m:percent_2009=2.8 m:births_2003=59 m:percent_2008=1.6 m:births_2006=26 m:births_2005=40 m:births_2000=96 m:births_2002=62 m:percent_2007_lower_ci=1.3 m:births_2001=60 m:percent_2006_upper_ci=3.9 m:percent_2008_lower_ci=0.8 m:percent_2009_upper_ci=3.9 m:percent_2008_upper_ci=2.4 m:percent_1999=7.3 m:percent_2001_upper_ci=6.3 m:births_2007=21 m:births_2008=14 m:births_1999=90 m:births_2009=26 m:percent_2003_lower_ci=4.4 m:percent_2001_lower_ci=3.9 m:percent_1999_upper_ci=8.8 m:percent_2004_lower_ci=3.7 m:percent_2005_lower_ci=3.1 m:percent_2002_upper_ci=7 m:percent_2002_lower_ci=4.2 m:percent_2006_lower_ci=1.7 m:percent_1999_lower_ci=5.8 m:percent_2000_lower_ci=6.1 m:percent_2007=2.3 m:percent_2006=2.8 m:percent_2005=4.5 m:percent_2004=5.1 m:percent_2003=5.8 m:percent_2002=5.6 m:percent_2005_upper_ci=5.9 m:percent_2001=5.1 m:percent_2000=7.6 m:percent_2000_upper_ci=9.1 m:percent_2003_upper_ci=7.2 m:percent_2007_upper_ci=3.3 m:percent_2004_upper_ci=6.5 m:percent_2009_lower_ci=1.7
```

## Meta Commands

```ls
metric m:births_1999 p:integer l:"Births 1999" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_1999 p:float l:"Percent 1999" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_1999_lower_ci p:float l:"Percent 1999 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_1999_upper_ci p:float l:"Percent 1999 Upper CI" d:"Percent upper confidence interval" t:dataTypeName=number

metric m:births_2000 p:integer l:"Births 2000" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2000 p:float l:"Percent 2000" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2000_lower_ci p:double l:"Percent 2000 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2000_upper_ci p:double l:"Percent 2000 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2001 p:integer l:"Births 2001" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2001 p:float l:"Percent 2001" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2001_lower_ci p:float l:"Percent 2001 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2001_upper_ci p:float l:"Percent 2001 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2002 p:integer l:"Births 2002" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2002 p:float l:"Percent 2002" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2002_lower_ci p:float l:"Percent 2002 Lower CI" d:"percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2002_upper_ci p:float l:"Percent 2002 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2003 p:integer l:"Births 2003" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2003 p:float l:"Percent 2003" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2003_lower_ci p:float l:"Percent 2003 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2003_upper_ci p:float l:"Percent 2003 Upper CI" d:"Percent upper confidence interval" t:dataTypeName=number

metric m:births_2004 p:integer l:"Births 2004" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2004 p:float l:"Percent 2004" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2004_lower_ci p:float l:"Percent 2004 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2004_upper_ci p:float l:"Percent 2004 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2005 p:integer l:"Births 2005" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2005 p:float l:"Percent 2005" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2005_lower_ci p:double l:"Percent 2005 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2005_upper_ci p:double l:"Percent 2005 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2006 p:integer l:"Births 2006" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2006 p:float l:"Percent 2006" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2006_lower_ci p:float l:"Percent 2006 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2006_upper_ci p:float l:"Percent 2006 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2007 p:integer l:"Births 2007" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2007 p:float l:"Percent 2007" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2007_lower_ci p:float l:"Percent 2007 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2007_upper_ci p:float l:"Percent 2007 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2008 p:integer l:"Births 2008" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2008 p:float l:"Percent 2008" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2008_lower_ci p:float l:"Percent 2008 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2008_upper_ci p:float l:"Percent 2008 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2009 p:integer l:"Births 2009" d:"Number of births by the trimester prenatal care began" t:dataTypeName=number

metric m:percent_2009 p:float l:"Percent 2009" d:"Percent of all births with prenatal care beginning in this trimester." t:dataTypeName=number

metric m:percent_2009_lower_ci p:float l:"Percent 2009 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2009_upper_ci p:float l:"Percent 2009 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

entity e:2q9j-hh6g l:"Public Health Statistics - Prenatal care in Chicago, by year, 1999 ? 2009" t:attribution="Illinois Department of Public Health (IDPH)" t:url=https://data.cityofchicago.org/api/views/2q9j-hh6g

property e:2q9j-hh6g t:meta.view v:id=2q9j-hh6g v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics - Prenatal care in Chicago, by year, 1999 ? 2009" v:attribution="Illinois Department of Public Health (IDPH)"

property e:2q9j-hh6g t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:2q9j-hh6g t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| community_area_number | community_area_name | trimester_prenatal_care_began | births_1999 | percent_1999 | percent_1999_lower_ci | percent_1999_upper_ci | births_2000 | percent_2000 | percent_2000_lower_ci | percent_2000_upper_ci | births_2001 | percent_2001 | percent_2001_lower_ci | percent_2001_upper_ci | births_2002 | percent_2002 | percent_2002_lower_ci | percent_2002_upper_ci | births_2003 | percent_2003 | percent_2003_lower_ci | percent_2003_upper_ci | births_2004 | percent_2004 | percent_2004_lower_ci | percent_2004_upper_ci | births_2005 | percent_2005 | percent_2005_lower_ci | percent_2005_upper_ci | births_2006 | percent_2006 | percent_2006_lower_ci | percent_2006_upper_ci | births_2007 | percent_2007 | percent_2007_lower_ci | percent_2007_upper_ci | births_2008 | percent_2008 | percent_2008_lower_ci | percent_2008_upper_ci | births_2009 | percent_2009 | percent_2009_lower_ci | percent_2009_upper_ci | warning                                                                                                                   | 
| ===================== | =================== | ============================= | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | ========================================================================================================================= | 
| 1                     | ROGERS PARK         | 1ST TRIMESTER                 | 726         | 58.9         | 56.2                  | 61.6                  | 692         | 54.6         | 51.9                  | 57.3                  | 731         | 61.6         | 58.8                  | 64.4                  | 674         | 61.2         | 58.3                  | 64.1                  | 613         | 59.9         | 56.9                  | 62.9                  | 517         | 55.8         | 52.6                  | 59                    | 541         | 60.7         | 57.5                  | 63.9                  | 622         | 66.6         | 63.6                  | 69.6                  | 622         | 68.2         | 65.2                  | 71.2                  | 639         | 71.6         | 68.6                  | 74.6                  | 670         | 73           | 70.1                  | 75.9                  |                                                                                                                           | 
| 1                     | ROGERS PARK         | 2ND TRIMESTER                 | 259         | 21           | 18.7                  | 23.3                  | 326         | 25.7         | 23.3                  | 28.1                  | 245         | 20.6         | 18.3                  | 22.9                  | 226         | 20.5         | 18.1                  | 22.9                  | 165         | 16.1         | 13.8                  | 18.4                  | 153         | 16.5         | 14.1                  | 18.9                  | 115         | 12.9         | 10.7                  | 15.1                  | 117         | 12.5         | 10.4                  | 14.6                  | 96          | 10.5         | 8.5                   | 12.5                  | 87          | 9.8          | 7.9                   | 11.7                  | 91          | 9.9          | 8                     | 11.8                  |                                                                                                                           | 
| 1                     | ROGERS PARK         | 3RD TRIMESTER                 | 90          | 7.3          | 5.8                   | 8.8                   | 96          | 7.6          | 6.1                   | 9.1                   | 60          | 5.1          | 3.9                   | 6.3                   | 62          | 5.6          | 4.2                   | 7                     | 59          | 5.8          | 4.4                   | 7.2                   | 47          | 5.1          | 3.7                   | 6.5                   | 40          | 4.5          | 3.1                   | 5.9                   | 26          | 2.8          | 1.7                   | 3.9                   | 21          | 2.3          | 1.3                   | 3.3                   | 14          | 1.6          | 0.8                   | 2.4                   | 26          | 2.8          | 1.7                   | 3.9                   | Percent and confidence interval estimates for years in which fewer than 20 births reported this attribute are unreliable. | 
| 1                     | ROGERS PARK         | NO PRENATAL CARE              | 79          | 6.4          | 5                     | 7.8                   | 60          | 4.7          | 3.5                   | 5.9                   | 38          | 3.2          | 2.2                   | 4.2                   | 41          | 3.7          | 2.6                   | 4.8                   | 39          | 3.8          | 2.6                   | 5                     | 23          | 2.5          | 1.5                   | 3.5                   | 27          | 3            | 1.9                   | 4.1                   | 22          | 2.4          | 1.4                   | 3.4                   | 13          | 1.4          | 0.6                   | 2.2                   | 12          | 1.3          | 0.5                   | 2.1                   | 6           | 0.7          | 0.2                   | 1.2                   | Percent and confidence interval estimates for years in which fewer than 20 births reported this attribute are unreliable. | 
| 1                     | ROGERS PARK         | NOT GIVEN                     | 79          | 6.4          | 5                     | 7.8                   | 93          | 7.3          | 5.9                   | 8.7                   | 113         | 9.5          | 7.8                   | 11.2                  | 98          | 8.9          | 7.2                   | 10.6                  | 148         | 14.5         | 12.3                  | 16.7                  | 186         | 20.1         | 17.5                  | 22.7                  | 169         | 18.9         | 16.3                  | 21.5                  | 147         | 15.7         | 13.4                  | 18                    | 160         | 17.5         | 15                    | 20                    | 140         | 15.7         | 13.3                  | 18.1                  | 125         | 13.6         | 11.4                  | 15.8                  |                                                                                                                           | 
| 2                     | WEST RIDGE          | 1ST TRIMESTER                 | 882         | 71.9         | 69.4                  | 74.4                  | 826         | 65.1         | 62.5                  | 67.7                  | 806         | 66.1         | 63.4                  | 68.8                  | 894         | 67.8         | 65.3                  | 70.3                  | 807         | 64.6         | 61.9                  | 67.3                  | 722         | 57.6         | 54.9                  | 60.3                  | 753         | 64.4         | 61.7                  | 67.1                  | 803         | 68.5         | 65.8                  | 71.2                  | 880         | 69.7         | 67.2                  | 72.2                  | 902         | 73.3         | 70.8                  | 75.8                  | 886         | 71.1         | 68.6                  | 73.6                  |                                                                                                                           | 
| 2                     | WEST RIDGE          | 2ND TRIMESTER                 | 180         | 14.7         | 12.7                  | 16.7                  | 262         | 20.7         | 18.5                  | 22.9                  | 213         | 17.5         | 15.4                  | 19.6                  | 196         | 14.9         | 13                    | 16.8                  | 160         | 12.8         | 10.9                  | 14.7                  | 156         | 12.4         | 10.6                  | 14.2                  | 110         | 9.4          | 7.7                   | 11.1                  | 139         | 11.8         | 10                    | 13.6                  | 136         | 10.8         | 9.1                   | 12.5                  | 131         | 10.6         | 8.9                   | 12.3                  | 150         | 12           | 10.2                  | 13.8                  |                                                                                                                           | 
| 2                     | WEST RIDGE          | 3RD TRIMESTER                 | 52          | 4.2          | 3.1                   | 5.3                   | 80          | 6.3          | 5                     | 7.6                   | 62          | 5.1          | 3.9                   | 6.3                   | 62          | 4.7          | 3.6                   | 5.8                   | 35          | 2.8          | 1.9                   | 3.7                   | 38          | 3            | 2.1                   | 3.9                   | 29          | 2.5          | 1.6                   | 3.4                   | 23          | 2            | 1.2                   | 2.8                   | 22          | 1.7          | 1                     | 2.4                   | 31          | 2.5          | 1.6                   | 3.4                   | 55          | 4.4          | 3.3                   | 5.5                   |                                                                                                                           | 
| 2                     | WEST RIDGE          | NO PRENATAL CARE              | 33          | 2.7          | 1.8                   | 3.6                   | 27          | 2.1          | 1.3                   | 2.9                   | 12          | 1            | 0.4                   | 1.6                   | 14          | 1.1          | 0.5                   | 1.7                   | 9           | 0.7          | 0.2                   | 1.2                   | 6           | 0.5          | 0.1                   | 0.9                   | 11          | 0.9          | 0.3                   | 1.5                   | 13          | 1.1          | 0.5                   | 1.7                   | 12          | 1            | 0.5                   | 1.5                   | 10          | 0.8          | 0.3                   | 1.3                   | 5           | 0.4          |                       |                       | Percent and confidence interval estimates for years in which fewer than 20 births reported this attribute are unreliable. | 
| 2                     | WEST RIDGE          | NOT GIVEN                     | 80          | 6.5          | 5.1                   | 7.9                   | 73          | 5.8          | 4.5                   | 7.1                   | 126         | 10.3         | 8.6                   | 12                    | 153         | 11.6         | 9.9                   | 13.3                  | 238         | 19.1         | 16.9                  | 21.3                  | 332         | 26.5         | 24.1                  | 28.9                  | 266         | 22.8         | 20.4                  | 25.2                  | 195         | 16.6         | 14.5                  | 18.7                  | 212         | 16.8         | 14.7                  | 18.9                  | 157         | 12.8         | 10.9                  | 14.7                  | 151         | 12.1         | 10.3                  | 13.9                  |                                                                                                                           | 
```