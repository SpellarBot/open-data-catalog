# DLLR Performance Improvement Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dllr-performance-improvement-measures) |
| Metadata | [Link](https://data.maryland.gov/api/views/7m66-dvnt) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/7m66-dvnt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/7m66-dvnt/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 7m66-dvnt |
| Name | DLLR Performance Improvement Measures |
| Attribution | DLLR |
| Tags | ged, nepd, diplomas, dllr, unemployment, trainees, complaints, licensees, education, employment, labor, licensing |
| Created | 2016-07-18T17:29:34Z |
| Publication Date | 2017-03-20T16:44:52Z |

## Description

# of GED? and NEPD diplomas awarded, WIA - The percentage of Youth program participants who are enrolled in education at the date of participation or at any point during the program and obtain a High School diploma, GED, or a recognized certificate by the end of the 3rd quarter following program exit, Unemployment Rate, Rate that adult employment trainees enter employment, and percentage of consumer complaints against licensees closed within 180 days of receipt

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ============================================ | ============= | ============= |
| Yes      | time           | date                                     | Date for Fiscal Year                         | calendar_date | calendar_date |
| No       |                | year                                     | Year                                         | number        | text          |
| Yes      | numeric metric | ged_s                                    | GEDs                                         | number        | number        |
| Yes      | numeric metric | nedp_diplomas                            | NEDP Diplomas                                | number        | number        |
| Yes      | numeric metric | trainees_entering_employment             | Percent of Trainees Entering Employment      | percent       | percent       |
| Yes      | numeric metric | complaints_closed                        | Percent of Complaints Closed Within 180 Days | percent       | percent       |
| Yes      | numeric metric | wia_diploma_degree_or_certificate        | WIA - Diploma, Degree, or Certificate        | percent       | percent       |
| No       |                | date_for_calendar_year                   | Date for Calendar Year                       | calendar_date | calendar_date |
| Yes      | numeric metric | unemployment_rate                        | MD Unemployment Rate (Calendar Year)         | percent       | percent       |
| Yes      | numeric metric | national_unemployment_rate_calendar_year | National Unemployment Rate (Calendar Year)   | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_for_calendar_year,year
```

## Data Commands

```ls
series e:7m66-dvnt d:2012-06-30T00:00:00.000Z m:unemployment_rate=7 m:national_unemployment_rate_calendar_year=8.1 m:trainees_entering_employment=82 m:ged_s=5023 m:nedp_diplomas=579 m:wia_diploma_degree_or_certificate=79.6 m:complaints_closed=60

series e:7m66-dvnt d:2013-06-30T00:00:00.000Z m:unemployment_rate=6.6 m:national_unemployment_rate_calendar_year=7.4 m:trainees_entering_employment=80 m:ged_s=5056 m:nedp_diplomas=570 m:wia_diploma_degree_or_certificate=83.5 m:complaints_closed=65

series e:7m66-dvnt d:2014-06-30T00:00:00.000Z m:unemployment_rate=5.8 m:national_unemployment_rate_calendar_year=6.2 m:trainees_entering_employment=80 m:ged_s=4033 m:nedp_diplomas=499 m:wia_diploma_degree_or_certificate=80.1 m:complaints_closed=47
```

## Meta Commands

```ls
metric m:ged_s p:integer l:GEDs d:"GED's awarded annually from fiscal years 2012-2016" t:dataTypeName=number

metric m:nedp_diplomas p:integer l:"NEDP Diplomas" d:"NEDP diplomas awarded annually from fiscal year 2012-2016" t:dataTypeName=number

metric m:trainees_entering_employment p:integer l:"Percent of Trainees Entering Employment" d:"Percent of WIA adult program participants who enter employment annually from fiscal years 2012-2016" t:dataTypeName=percent

metric m:complaints_closed p:integer l:"Percent of Complaints Closed Within 180 Days" d:"Percentage of consumer complaints against licensees closed within 180 days of receipt" t:dataTypeName=percent

metric m:wia_diploma_degree_or_certificate p:float l:"WIA - Diploma, Degree, or Certificate" d:"percentage of Youth program participants who are enrolled in education at the date of participation or at any point during the program and obtain a High School diploma, GED, or a recognized certificate by the end of the 3rd quarter following program exit reported annually from fiscal years 2012-2106" t:dataTypeName=percent

metric m:unemployment_rate p:double l:"MD Unemployment Rate (Calendar Year)" d:"Maryland's annual unemployment rate from calendar years 2012-2016" t:dataTypeName=percent

metric m:national_unemployment_rate_calendar_year p:float l:"National Unemployment Rate (Calendar Year)" t:dataTypeName=percent

entity e:7m66-dvnt l:"DLLR Performance Improvement Measures" t:attribution=DLLR t:url=https://data.maryland.gov/api/views/7m66-dvnt

property e:7m66-dvnt t:meta.view v:id=7m66-dvnt v:attributionLink=http://dllr.maryland.gov/ v:averageRating=0 v:name="DLLR Performance Improvement Measures" v:attribution=DLLR

property e:7m66-dvnt t:meta.view.license v:name="Public Domain"

property e:7m66-dvnt t:meta.view.owner v:id=ejht-gz2j v:screenName="Angela Castleberry" v:displayName="Angela Castleberry"

property e:7m66-dvnt t:meta.view.tableauthor v:id=ejht-gz2j v:screenName="Angela Castleberry" v:roleName=editor v:displayName="Angela Castleberry"
```

## Top Records

```ls
| date                | year | ged_s | nedp_diplomas | trainees_entering_employment | complaints_closed | wia_diploma_degree_or_certificate | date_for_calendar_year | unemployment_rate | national_unemployment_rate_calendar_year | 
| =================== | ==== | ===== | ============= | ============================ | ================= | ================================= | ====================== | ================= | ======================================== | 
| 2012-06-30T00:00:00 | 2012 | 5023  | 579           | 82                           | 60                | 79.6                              | 2012-12-31T00:00:00    | 7                 | 8.1                                      | 
| 2013-06-30T00:00:00 | 2013 | 5056  | 570           | 80                           | 65                | 83.5                              | 2013-12-31T00:00:00    | 6.6               | 7.4                                      | 
| 2014-06-30T00:00:00 | 2014 | 4033  | 499           | 80                           | 47                | 80.1                              | 2014-12-31T00:00:00    | 5.8               | 6.2                                      | 
| 2015-06-30T00:00:00 | 2015 | 1986  | 203           | 79                           | 65                | 77.6                              | 2015-12-31T00:00:00    | 5.2               | 5.3                                      | 
| 2016-06-30T00:00:00 | 2016 | 3685  | 221           | 75                           | 78                | 77.8                              | 2016-12-31T00:00:00    | 4.3               | 4.9                                      | 
```