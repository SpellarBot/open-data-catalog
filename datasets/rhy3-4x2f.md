# Public Health Statistics - Preterm births in Chicago, by year, 1999 ? 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-preterm-births-in-chicago-by-year-1999-2009-55f9f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/rhy3-4x2f) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/rhy3-4x2f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/rhy3-4x2f/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | rhy3-4x2f |
| Name | Public Health Statistics - Preterm births in Chicago, by year, 1999 ? 2009 |
| Attribution | Illinois Department of Public Health (IDPH) |
| Category | Health & Human Services |
| Created | 2011-12-30T16:30:48Z |
| Publication Date | 2013-03-28T16:17:32Z |

## Description

This dataset contains the annual number of preterm births and the percent of total births these preterm births represent, with corresponding 95% confidence intervals, by Chicago community area, for the years 1999 ? 2009.  See the full dataset description for more information: http://bit.ly/M7AyBL

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | community_area_number | Community Area Number | text      | number      |
| Yes      | series tag     | community_area_name   | Community Area Name   | text      | text        |
| Yes      | numeric metric | births_1999           | Pre-term Births 1999  | number    | number      |
| Yes      | numeric metric | percent_1999          | Percent 1999          | number    | number      |
| Yes      | numeric metric | percent_1999_lower    | Percent 1999 Lower CI | number    | number      |
| Yes      | numeric metric | percent_1999_upper    | Percent 1999 Upper CI | number    | number      |
| Yes      | numeric metric | births_2000           | Pre-term Births 2000  | number    | number      |
| Yes      | numeric metric | percent_2000          | Percent 2000          | number    | number      |
| Yes      | numeric metric | percent_2000_lower_ci | Percent 2000 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2000_upper_ci | Percent 2000 Upper CI | number    | number      |
| Yes      | numeric metric | births_2001           | Pre-term Births 2001  | number    | number      |
| Yes      | numeric metric | percent_2001          | Percent 2001          | number    | number      |
| Yes      | numeric metric | percent_2001_lower_ci | Percent 2001 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2001_upper_ci | Percent 2001 Upper CI | number    | number      |
| Yes      | numeric metric | births_2002           | Pre-term Births 2002  | number    | number      |
| Yes      | numeric metric | percent_2002          | Percent 2002          | number    | number      |
| Yes      | numeric metric | percent_2002_lower_ci | Percent 2002 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2002_upper_ci | Percent 2002 Upper CI | number    | number      |
| Yes      | numeric metric | births_2003           | Pre-term Births 2003  | number    | number      |
| Yes      | numeric metric | percent_2003          | Percent 2003          | number    | number      |
| Yes      | numeric metric | percent_2003_lower_ci | Percent 2003 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2003_upper_ci | Percent 2003 Upper CI | number    | number      |
| Yes      | numeric metric | births_2004           | Pre-term Births 2004  | number    | number      |
| Yes      | numeric metric | percent_2004          | Percent 2004          | number    | number      |
| Yes      | numeric metric | percent_2004_lower_ci | Percent 2004 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2004_upper_ci | Percent 2004 Upper CI | number    | number      |
| Yes      | numeric metric | births_2005           | Pre-term Births 2005  | number    | number      |
| Yes      | numeric metric | percent_2005          | Percent 2005          | number    | number      |
| Yes      | numeric metric | percent_2005_lower_ci | Percent 2005 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2005_upper_ci | Percent 2005 Upper CI | number    | number      |
| Yes      | numeric metric | births_2006           | Pre-term Births 2006  | number    | number      |
| Yes      | numeric metric | percent_2006          | Percent 2006          | number    | number      |
| Yes      | numeric metric | percent_2006_lower_ci | Percent 2006 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2006_upper_ci | Percent 2006 Upper CI | number    | number      |
| Yes      | numeric metric | births_2007           | Pre-term Births 2007  | number    | number      |
| Yes      | numeric metric | percent_2007          | Percent 2007          | number    | number      |
| Yes      | numeric metric | percent_2007_lower_ci | Percent 2007 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2007_upper_ci | Percent 2007 Upper CI | number    | number      |
| Yes      | numeric metric | births_2008           | Pre-term Births 2008  | number    | number      |
| Yes      | numeric metric | percent_2008          | Percent 2008          | number    | number      |
| Yes      | numeric metric | percent_2008_lower_ci | Percent 2008 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2008_upper_ci | Percent 2008 Upper CI | number    | number      |
| Yes      | numeric metric | births_2009           | Pre-term Births 2009  | number    | number      |
| Yes      | numeric metric | percent_2009          | Percent 2009          | number    | number      |
| Yes      | numeric metric | percent_2009_lower_ci | Percent 2009 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2009_upper_ci | Percent 2009 Upper CI | number    | number      |
| Yes      | series tag     | warning               | Warning               | text      | text        |
```

## Time Field

```ls
Value = 1999
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rhy3-4x2f d:1999-01-01T00:00:00.000Z t:community_area_name="ROGERS PARK" t:community_area_number=1 m:births_2004=97 m:percent_2009=11.2 m:births_2003=109 m:percent_2008=11.8 m:births_2006=109 m:births_2005=93 m:births_2000=151 m:births_2002=110 m:percent_2007_lower_ci=8.1 m:births_2001=107 m:percent_2006_upper_ci=13.8 m:percent_2008_lower_ci=9.7 m:percent_2009_upper_ci=13.2 m:percent_1999_lower=8.6 m:percent_2008_upper_ci=13.9 m:percent_1999=10.3 m:percent_2001_upper_ci=10.6 m:births_2007=91 m:births_2008=105 m:births_1999=127 m:births_2009=103 m:percent_2003_lower_ci=8.7 m:percent_2001_lower_ci=7.4 m:percent_1999_upper=12 m:percent_2004_lower_ci=8.5 m:percent_2005_lower_ci=8.4 m:percent_2002_upper_ci=11.8 m:percent_2002_lower_ci=8.2 m:percent_2006_lower_ci=9.6 m:percent_2000_lower_ci=10.1 m:percent_2007=10 m:percent_2006=11.7 m:percent_2005=10.4 m:percent_2004=10.5 m:percent_2003=10.6 m:percent_2002=10 m:percent_2005_upper_ci=12.4 m:percent_2001=9 m:percent_2000=11.9 m:percent_2000_upper_ci=13.7 m:percent_2003_upper_ci=12.5 m:percent_2007_upper_ci=11.9 m:percent_2004_upper_ci=12.5 m:percent_2009_lower_ci=9.2

series e:rhy3-4x2f d:1999-01-01T00:00:00.000Z t:community_area_name="WEST RIDGE" t:community_area_number=2 m:births_2004=112 m:percent_2009=8.3 m:births_2003=136 m:percent_2008=8.4 m:births_2006=111 m:births_2005=106 m:births_2000=122 m:births_2002=102 m:percent_2007_lower_ci=8.7 m:births_2001=110 m:percent_2006_upper_ci=11.2 m:percent_2008_lower_ci=6.9 m:percent_2009_upper_ci=9.8 m:percent_1999_lower=5.4 m:percent_2008_upper_ci=9.9 m:percent_1999=6.8 m:percent_2001_upper_ci=10.6 m:births_2007=131 m:births_2008=103 m:births_1999=84 m:births_2009=104 m:percent_2003_lower_ci=9.2 m:percent_2001_lower_ci=7.4 m:percent_1999_upper=8.2 m:percent_2004_lower_ci=7.3 m:percent_2005_lower_ci=7.5 m:percent_2002_upper_ci=9.1 m:percent_2002_lower_ci=6.3 m:percent_2006_lower_ci=7.8 m:percent_2000_lower_ci=8 m:percent_2007=10.4 m:percent_2006=9.5 m:percent_2005=9.1 m:percent_2004=8.9 m:percent_2003=10.9 m:percent_2002=7.7 m:percent_2005_upper_ci=10.7 m:percent_2001=9 m:percent_2000=9.6 m:percent_2000_upper_ci=11.2 m:percent_2003_upper_ci=12.6 m:percent_2007_upper_ci=12.1 m:percent_2004_upper_ci=10.5 m:percent_2009_lower_ci=6.8

series e:rhy3-4x2f d:1999-01-01T00:00:00.000Z t:community_area_name=UPTOWN t:community_area_number=3 m:births_2004=71 m:percent_2009=10.3 m:births_2003=62 m:percent_2008=11.4 m:births_2006=91 m:births_2005=79 m:births_2000=116 m:births_2002=92 m:percent_2007_lower_ci=9 m:births_2001=92 m:percent_2006_upper_ci=13.4 m:percent_2008_lower_ci=9.1 m:percent_2009_upper_ci=12.5 m:percent_1999_lower=10.4 m:percent_2008_upper_ci=13.7 m:percent_1999=12.6 m:percent_2001_upper_ci=12.5 m:births_2007=86 m:births_2008=83 m:births_1999=107 m:births_2009=77 m:percent_2003_lower_ci=6.1 m:percent_2001_lower_ci=8.5 m:percent_1999_upper=14.8 m:percent_2004_lower_ci=7.4 m:percent_2005_lower_ci=7.8 m:percent_2002_upper_ci=13.8 m:percent_2002_lower_ci=9.4 m:percent_2006_lower_ci=9 m:percent_2000_lower_ci=11 m:percent_2007=11.2 m:percent_2006=11.2 m:percent_2005=9.9 m:percent_2004=9.5 m:percent_2003=8 m:percent_2002=11.6 m:percent_2005_upper_ci=12 m:percent_2001=10.5 m:percent_2000=13.2 m:percent_2000_upper_ci=15.4 m:percent_2003_upper_ci=9.9 m:percent_2007_upper_ci=13.4 m:percent_2004_upper_ci=11.6 m:percent_2009_lower_ci=8.1
```

## Meta Commands

```ls
metric m:births_1999 p:integer l:"Pre-term Births 1999" d:"Number of pre-term births (under 37 weeks) in 1999" t:dataTypeName=number

metric m:percent_1999 p:double l:"Percent 1999" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_1999_lower p:float l:"Percent 1999 Lower CI" t:dataTypeName=number

metric m:percent_1999_upper p:float l:"Percent 1999 Upper CI" t:dataTypeName=number

metric m:births_2000 p:integer l:"Pre-term Births 2000" d:"Number of pre-term births (under 37 weeks) in 2000" t:dataTypeName=number

metric m:percent_2000 p:float l:"Percent 2000" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2000_lower_ci p:float l:"Percent 2000 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2000_upper_ci p:float l:"Percent 2000 Upper CI" d:"Percent upper confidence interval" t:dataTypeName=number

metric m:births_2001 p:integer l:"Pre-term Births 2001" d:"Number of pre-term births (under 37 weeks) in 2001" t:dataTypeName=number

metric m:percent_2001 p:float l:"Percent 2001" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2001_lower_ci p:double l:"Percent 2001 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2001_upper_ci p:float l:"Percent 2001 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2002 p:integer l:"Pre-term Births 2002" d:"Number of pre-term births (under 37 weeks) in 2002" t:dataTypeName=number

metric m:percent_2002 p:float l:"Percent 2002" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2002_lower_ci p:float l:"Percent 2002 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2002_upper_ci p:double l:"Percent 2002 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2003 p:integer l:"Pre-term Births 2003" d:"Number of pre-term births (under 37 weeks) in 2003" t:dataTypeName=number

metric m:percent_2003 p:float l:"Percent 2003" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2003_lower_ci p:float l:"Percent 2003 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2003_upper_ci p:float l:"Percent 2003 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2004 p:integer l:"Pre-term Births 2004" d:"Number of pre-term births (under 37 weeks) in 2004" t:dataTypeName=number

metric m:percent_2004 p:double l:"Percent 2004" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2004_lower_ci p:float l:"Percent 2004 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2004_upper_ci p:float l:"Percent 2004 Upper CI" d:"Percent upper confidence interval" t:dataTypeName=number

metric m:births_2005 p:integer l:"Pre-term Births 2005" d:"Number of pre-term births (under 37 weeks) in 2005" t:dataTypeName=number

metric m:percent_2005 p:float l:"Percent 2005" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2005_lower_ci p:float l:"Percent 2005 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2005_upper_ci p:float l:"Percent 2005 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2006 p:integer l:"Pre-term Births 2006" d:"Number of pre-term births (under 37 weeks) in 2006" t:dataTypeName=number

metric m:percent_2006 p:float l:"Percent 2006" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2006_lower_ci p:float l:"Percent 2006 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2006_upper_ci p:float l:"Percent 2006 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2007 p:integer l:"Pre-term Births 2007" d:"Number of pre-term births (under 37 weeks) in 2007" t:dataTypeName=number

metric m:percent_2007 p:float l:"Percent 2007" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2007_lower_ci p:float l:"Percent 2007 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2007_upper_ci p:float l:"Percent 2007 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2008 p:integer l:"Pre-term Births 2008" d:"Number of pre-term births (under 37 weeks) in 2008" t:dataTypeName=number

metric m:percent_2008 p:float l:"Percent 2008" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2008_lower_ci p:float l:"Percent 2008 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2008_upper_ci p:float l:"Percent 2008 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

metric m:births_2009 p:integer l:"Pre-term Births 2009" d:"Number of pre-term births (under 37 weeks) in 2009" t:dataTypeName=number

metric m:percent_2009 p:float l:"Percent 2009" d:"Percent of all births that had a gestational age of under 37 weeks" t:dataTypeName=number

metric m:percent_2009_lower_ci p:float l:"Percent 2009 Lower CI" d:"Percent lower confidence interval (CI)" t:dataTypeName=number

metric m:percent_2009_upper_ci p:float l:"Percent 2009 Upper CI" d:"Percent upper confidence interval (CI)" t:dataTypeName=number

entity e:rhy3-4x2f l:"Public Health Statistics - Preterm births in Chicago, by year, 1999 ? 2009" t:attribution="Illinois Department of Public Health (IDPH)" t:url=https://data.cityofchicago.org/api/views/rhy3-4x2f

property e:rhy3-4x2f t:meta.view v:id=rhy3-4x2f v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics - Preterm births in Chicago, by year, 1999 ? 2009" v:attribution="Illinois Department of Public Health (IDPH)"

property e:rhy3-4x2f t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:rhy3-4x2f t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| community_area_number | community_area_name | births_1999 | percent_1999 | percent_1999_lower | percent_1999_upper | births_2000 | percent_2000 | percent_2000_lower_ci | percent_2000_upper_ci | births_2001 | percent_2001 | percent_2001_lower_ci | percent_2001_upper_ci | births_2002 | percent_2002 | percent_2002_lower_ci | percent_2002_upper_ci | births_2003 | percent_2003 | percent_2003_lower_ci | percent_2003_upper_ci | births_2004 | percent_2004 | percent_2004_lower_ci | percent_2004_upper_ci | births_2005 | percent_2005 | percent_2005_lower_ci | percent_2005_upper_ci | births_2006 | percent_2006 | percent_2006_lower_ci | percent_2006_upper_ci | births_2007 | percent_2007 | percent_2007_lower_ci | percent_2007_upper_ci | births_2008 | percent_2008 | percent_2008_lower_ci | percent_2008_upper_ci | births_2009 | percent_2009 | percent_2009_lower_ci | percent_2009_upper_ci | warning                                                                                                                   | 
| ===================== | =================== | =========== | ============ | ================== | ================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | ========================================================================================================================= | 
| 1                     | ROGERS PARK         | 127         | 10.3         | 8.6                | 12                 | 151         | 11.9         | 10.1                  | 13.7                  | 107         | 9            | 7.4                   | 10.6                  | 110         | 10           | 8.2                   | 11.8                  | 109         | 10.6         | 8.7                   | 12.5                  | 97          | 10.5         | 8.5                   | 12.5                  | 93          | 10.4         | 8.4                   | 12.4                  | 109         | 11.7         | 9.6                   | 13.8                  | 91          | 10           | 8.1                   | 11.9                  | 105         | 11.8         | 9.7                   | 13.9                  | 103         | 11.2         | 9.2                   | 13.2                  |                                                                                                                           | 
| 2                     | WEST RIDGE          | 84          | 6.8          | 5.4                | 8.2                | 122         | 9.6          | 8                     | 11.2                  | 110         | 9            | 7.4                   | 10.6                  | 102         | 7.7          | 6.3                   | 9.1                   | 136         | 10.9         | 9.2                   | 12.6                  | 112         | 8.9          | 7.3                   | 10.5                  | 106         | 9.1          | 7.5                   | 10.7                  | 111         | 9.5          | 7.8                   | 11.2                  | 131         | 10.4         | 8.7                   | 12.1                  | 103         | 8.4          | 6.9                   | 9.9                   | 104         | 8.3          | 6.8                   | 9.8                   |                                                                                                                           | 
| 3                     | UPTOWN              | 107         | 12.6         | 10.4               | 14.8               | 116         | 13.2         | 11                    | 15.4                  | 92          | 10.5         | 8.5                   | 12.5                  | 92          | 11.6         | 9.4                   | 13.8                  | 62          | 8            | 6.1                   | 9.9                   | 71          | 9.5          | 7.4                   | 11.6                  | 79          | 9.9          | 7.8                   | 12                    | 91          | 11.2         | 9                     | 13.4                  | 86          | 11.2         | 9                     | 13.4                  | 83          | 11.4         | 9.1                   | 13.7                  | 77          | 10.3         | 8.1                   | 12.5                  |                                                                                                                           | 
| 4                     | LINCOLN SQUARE      | 57          | 8.3          | 6.2                | 10.4               | 60          | 9            | 6.8                   | 11.2                  | 53          | 8.7          | 6.5                   | 10.9                  | 54          | 8.3          | 6.2                   | 10.4                  | 60          | 9            | 6.8                   | 11.2                  | 70          | 11.4         | 8.9                   | 13.9                  | 68          | 11.4         | 8.9                   | 13.9                  | 72          | 11.4         | 8.9                   | 13.9                  | 62          | 10.5         | 8                     | 13                    | 58          | 9            | 6.8                   | 11.2                  | 66          | 9.7          | 7.5                   | 11.9                  |                                                                                                                           | 
| 5                     | NORTH CENTER        | 48          | 9.7          | 7.1                | 12.3               | 65          | 11.1         | 8.5                   | 13.7                  | 53          | 9.9          | 7.4                   | 12.4                  | 45          | 8.3          | 6                     | 10.6                  | 67          | 11.5         | 8.9                   | 14.1                  | 63          | 10.5         | 8                     | 13                    | 64          | 10.4         | 8                     | 12.8                  | 79          | 11.9         | 9.4                   | 14.4                  | 66          | 10.3         | 7.9                   | 12.7                  | 56          | 8.2          | 6.2                   | 10.2                  | 70          | 9.8          | 7.6                   | 12                    |                                                                                                                           | 
| 6                     | LAKE VIEW           | 88          | 8.6          | 6.9                | 10.3               | 98          | 9.3          | 7.6                   | 11                    | 101         | 9.8          | 8                     | 11.6                  | 113         | 10.5         | 8.7                   | 12.3                  | 120         | 10.7         | 8.9                   | 12.5                  | 116         | 10.3         | 8.5                   | 12.1                  | 99          | 8.9          | 7.2                   | 10.6                  | 106         | 9.9          | 8.1                   | 11.7                  | 106         | 9            | 7.4                   | 10.6                  | 113         | 9.6          | 7.9                   | 11.3                  | 104         | 8.1          | 6.6                   | 9.6                   |                                                                                                                           | 
| 7                     | LINCOLN PARK        | 98          | 11.5         | 9.4                | 13.6               | 70          | 8.4          | 6.5                   | 10.3                  | 89          | 10.4         | 8.4                   | 12.4                  | 100         | 11.5         | 9.4                   | 13.6                  | 94          | 10.5         | 8.5                   | 12.5                  | 91          | 10.4         | 8.4                   | 12.4                  | 80          | 10.1         | 8                     | 12.2                  | 89          | 10.6         | 8.5                   | 12.7                  | 82          | 9.9          | 7.9                   | 11.9                  | 78          | 9.9          | 7.8                   | 12                    | 66          | 7.8          | 6                     | 9.6                   |                                                                                                                           | 
| 8                     | NEAR NORTH SIDE     | 98          | 13.3         | 10.8               | 15.8               | 89          | 11.5         | 9.2                   | 13.8                  | 88          | 10.8         | 8.7                   | 12.9                  | 102         | 13.3         | 10.9                  | 15.7                  | 97          | 12           | 9.8                   | 14.2                  | 95          | 11.6         | 9.4                   | 13.8                  | 80          | 10.3         | 8.2                   | 12.4                  | 80          | 10.1         | 8                     | 12.2                  | 83          | 10.9         | 8.7                   | 13.1                  | 97          | 11.8         | 9.6                   | 14                    | 82          | 9.6          | 7.6                   | 11.6                  |                                                                                                                           | 
| 9                     | EDISON PARK         | 4           | 3            |                    |                    | 8           | 5.5          | 1.8                   | 9.2                   | 17          | 13.8         | 7.7                   | 19.9                  | 16          | 11           | 5.9                   | 16.1                  | 20          | 15.5         | 9.3                   | 21.7                  | 10          | 6.8          | 2.7                   | 10.9                  | 14          | 10.7         | 5.4                   | 16                    | 12          | 9.2          | 4.3                   | 14.1                  | 12          | 9.5          | 4.4                   | 14.6                  | 14          | 9.7          | 4.9                   | 14.5                  | 16          | 12.6         | 6.8                   | 18.4                  | Percent and confidence interval estimates for years in which fewer than 20 births reported this attribute are unreliable. | 
| 10                    | NORWOOD PARK        | 32          | 7.5          | 5                  | 10                 | 41          | 9.8          | 7                     | 12.6                  | 43          | 10.1         | 7.2                   | 13                    | 40          | 9            | 6.3                   | 11.7                  | 50          | 11.2         | 8.3                   | 14.1                  | 56          | 12.8         | 9.7                   | 15.9                  | 42          | 10           | 7.1                   | 12.9                  | 51          | 11.9         | 8.8                   | 15                    | 45          | 10.6         | 7.7                   | 13.5                  | 41          | 10.6         | 7.5                   | 13.7                  | 32          | 8.3          | 5.5                   | 11.1                  |                                                                                                                           | 
```