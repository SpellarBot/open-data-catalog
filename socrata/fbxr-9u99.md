# Public Health Statistics - Low birth weight in Chicago, by year, 1999 ? 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-low-birth-weight-in-chicago-by-year-1999-2009-6526f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/fbxr-9u99) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/fbxr-9u99/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/fbxr-9u99/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | fbxr-9u99 |
| Name | Public Health Statistics - Low birth weight in Chicago, by year, 1999 ? 2009 |
| Attribution | Illinois Department of Public Health (IDPH) |
| Category | Health & Human Services |
| Created | 2012-05-22T20:56:45Z |
| Publication Date | 2012-10-23T20:41:48Z |

## Description

This dataset contains the annual number of low birth weight births and the percent of total births these low birth weight births represent, with corresponding 95% confidence intervals, by Chicago community area, for the years 1999 ? 2009. See full description at http://bit.ly/KcNNzH

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | community_area        | Community Area        | text      | number      |
| Yes      | series tag     | community_area_name   | Community Area Name   | text      | text        |
| Yes      | numeric metric | births_1999           | Births 1999           | number    | number      |
| Yes      | numeric metric | percent_1999          | Percent 1999          | number    | number      |
| Yes      | numeric metric | percent_1999_lower_ci | Percent 1999 Lower CI | number    | number      |
| Yes      | numeric metric | percent_1999_upper_ci | Percent 1999 Upper CI | number    | number      |
| Yes      | numeric metric | births_2000           | Births 2000           | number    | number      |
| Yes      | numeric metric | percent_2000          | Percent 2000          | number    | number      |
| Yes      | numeric metric | percent_2000_lower_ci | Percent 2000 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2000_upper_ci | Percent 2000 Upper CI | number    | number      |
| Yes      | numeric metric | births_2001           | Births 2001           | number    | number      |
| Yes      | numeric metric | percent_2001          | Percent 2001          | number    | number      |
| Yes      | numeric metric | percent_2001_lower_ci | Percent 2001 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2001_upper_ci | Percent 2001 Upper CI | number    | number      |
| Yes      | numeric metric | births_2002           | Births 2002           | number    | number      |
| Yes      | numeric metric | percent_2002          | Percent 2002          | number    | number      |
| Yes      | numeric metric | percent_2002_lower_ci | Percent 2002 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2002_upper_ci | Percent 2002 Upper CI | number    | number      |
| Yes      | numeric metric | births_2003           | Births 2003           | number    | number      |
| Yes      | numeric metric | percent_2003          | Percent 2003          | number    | number      |
| Yes      | numeric metric | percent_2003_lower_ci | Percent 2003 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2003_upper_ci | Percent 2003 Upper CI | number    | number      |
| Yes      | numeric metric | births_2004           | Births 2004           | number    | number      |
| Yes      | numeric metric | percent_2004          | Percent 2004          | number    | number      |
| Yes      | numeric metric | percent_2004_lower_ci | Percent 2004 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2004_upper_ci | Percent 2004 Upper CI | number    | number      |
| Yes      | numeric metric | births_2005           | Births 2005           | number    | number      |
| Yes      | numeric metric | percent_2005          | Percent 2005          | number    | number      |
| Yes      | numeric metric | percent_2005_lower_ci | Percent 2005 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2005_upper_ci | Percent 2005 Upper CI | number    | number      |
| Yes      | numeric metric | births_2006           | Births 2006           | number    | number      |
| Yes      | numeric metric | percent_2006          | Percent 2006          | number    | number      |
| Yes      | numeric metric | percent_2006_lower_ci | Percent 2006 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2006_upper_ci | Percent 2006 Upper CI | number    | number      |
| Yes      | numeric metric | births_2007           | Births 2007           | number    | number      |
| Yes      | numeric metric | percent_2007          | Percent 2007          | number    | number      |
| Yes      | numeric metric | percent_2007_lower_ci | Percent 2007 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2007_upper_ci | Percent 2007 Upper CI | number    | number      |
| Yes      | numeric metric | births_2008           | Births 2008           | number    | number      |
| Yes      | numeric metric | percent_2008          | Percent 2008          | number    | number      |
| Yes      | numeric metric | percent_2008_lower_ci | Percent 2008 Lower CI | number    | number      |
| Yes      | numeric metric | percent_2008_upper_ci | Percent 2008 Upper CI | number    | number      |
| Yes      | numeric metric | births_2009           | Births 2009           | number    | number      |
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
series e:fbxr-9u99 d:1999-01-01T00:00:00.000Z t:community_area_name="ROGERS PARK" t:community_area=1 m:births_2004=71 m:percent_2009=11 m:births_2003=86 m:percent_2008=8.5 m:births_2006=77 m:births_2005=79 m:births_2000=114 m:births_2002=96 m:percent_2007_lower_ci=6.6 m:births_2001=97 m:percent_2006_upper_ci=10 m:percent_2008_lower_ci=6.7 m:percent_2009_upper_ci=13 m:percent_2008_upper_ci=10.3 m:percent_1999=8.4 m:percent_2001_upper_ci=9.8 m:births_2007=77 m:births_2008=76 m:births_1999=103 m:births_2009=101 m:percent_2003_lower_ci=6.7 m:percent_2001_lower_ci=6.6 m:percent_1999_upper_ci=9.9 m:percent_2004_lower_ci=6 m:percent_2005_lower_ci=7 m:percent_2002_upper_ci=10.4 m:percent_2002_lower_ci=7 m:percent_2006_lower_ci=6.4 m:percent_1999_lower_ci=6.9 m:percent_2000_lower_ci=7.4 m:percent_2007=8.4 m:percent_2006=8.2 m:percent_2005=8.9 m:percent_2004=7.7 m:percent_2003=8.4 m:percent_2002=8.7 m:percent_2005_upper_ci=10.8 m:percent_2001=8.2 m:percent_2000=9 m:percent_2000_upper_ci=10.6 m:percent_2003_upper_ci=10.1 m:percent_2007_upper_ci=10.2 m:percent_2004_upper_ci=9.4 m:percent_2009_lower_ci=9

series e:fbxr-9u99 d:1999-01-01T00:00:00.000Z t:community_area_name="WEST RIDGE" t:community_area=2 m:births_2004=114 m:percent_2009=8.1 m:births_2003=120 m:percent_2008=6.6 m:births_2006=80 m:births_2005=96 m:births_2000=104 m:births_2002=92 m:percent_2007_lower_ci=8.4 m:births_2001=107 m:percent_2006_upper_ci=8.2 m:percent_2008_lower_ci=5.2 m:percent_2009_upper_ci=9.6 m:percent_2008_upper_ci=8 m:percent_1999=6.6 m:percent_2001_upper_ci=10.4 m:births_2007=128 m:births_2008=81 m:births_1999=81 m:births_2009=101 m:percent_2003_lower_ci=8 m:percent_2001_lower_ci=7.2 m:percent_1999_upper_ci=8 m:percent_2004_lower_ci=7.5 m:percent_2005_lower_ci=6.6 m:percent_2002_upper_ci=8.4 m:percent_2002_lower_ci=5.6 m:percent_2006_lower_ci=5.4 m:percent_1999_lower_ci=5.2 m:percent_2000_lower_ci=6.7 m:percent_2007=10.1 m:percent_2006=6.8 m:percent_2005=8.2 m:percent_2004=9.1 m:percent_2003=9.6 m:percent_2002=7 m:percent_2005_upper_ci=9.8 m:percent_2001=8.8 m:percent_2000=8.2 m:percent_2000_upper_ci=9.7 m:percent_2003_upper_ci=11.2 m:percent_2007_upper_ci=11.8 m:percent_2004_upper_ci=10.7 m:percent_2009_lower_ci=6.6

series e:fbxr-9u99 d:1999-01-01T00:00:00.000Z t:community_area_name=UPTOWN t:community_area=3 m:births_2004=64 m:percent_2009=8.3 m:births_2003=62 m:percent_2008=8.2 m:births_2006=83 m:births_2005=67 m:births_2000=99 m:births_2002=58 m:percent_2007_lower_ci=5.7 m:births_2001=77 m:percent_2006_upper_ci=12.3 m:percent_2008_lower_ci=6.2 m:percent_2009_upper_ci=10.3 m:percent_2008_upper_ci=10.2 m:percent_1999=9.3 m:percent_2001_upper_ci=10.7 m:births_2007=58 m:births_2008=60 m:births_1999=79 m:births_2009=62 m:percent_2003_lower_ci=6.1 m:percent_2001_lower_ci=6.9 m:percent_1999_upper_ci=11.3 m:percent_2004_lower_ci=6.6 m:percent_2005_lower_ci=6.5 m:percent_2002_upper_ci=9.1 m:percent_2002_lower_ci=5.5 m:percent_2006_lower_ci=8.1 m:percent_1999_lower_ci=7.3 m:percent_2000_lower_ci=9.1 m:percent_2007=7.6 m:percent_2006=10.2 m:percent_2005=8.4 m:percent_2004=8.6 m:percent_2003=8 m:percent_2002=7.3 m:percent_2005_upper_ci=10.3 m:percent_2001=8.8 m:percent_2000=11.2 m:percent_2000_upper_ci=13.3 m:percent_2003_upper_ci=9.9 m:percent_2007_upper_ci=9.5 m:percent_2004_upper_ci=10.6 m:percent_2009_lower_ci=6.3
```

## Meta Commands

```ls
metric m:births_1999 p:integer l:"Births 1999" t:dataTypeName=number

metric m:percent_1999 p:float l:"Percent 1999" t:dataTypeName=number

metric m:percent_1999_lower_ci p:double l:"Percent 1999 Lower CI" t:dataTypeName=number

metric m:percent_1999_upper_ci p:float l:"Percent 1999 Upper CI" t:dataTypeName=number

metric m:births_2000 p:integer l:"Births 2000" t:dataTypeName=number

metric m:percent_2000 p:float l:"Percent 2000" t:dataTypeName=number

metric m:percent_2000_lower_ci p:float l:"Percent 2000 Lower CI" t:dataTypeName=number

metric m:percent_2000_upper_ci p:float l:"Percent 2000 Upper CI" t:dataTypeName=number

metric m:births_2001 p:integer l:"Births 2001" t:dataTypeName=number

metric m:percent_2001 p:double l:"Percent 2001" t:dataTypeName=number

metric m:percent_2001_lower_ci p:float l:"Percent 2001 Lower CI" t:dataTypeName=number

metric m:percent_2001_upper_ci p:float l:"Percent 2001 Upper CI" t:dataTypeName=number

metric m:births_2002 p:integer l:"Births 2002" t:dataTypeName=number

metric m:percent_2002 p:double l:"Percent 2002" t:dataTypeName=number

metric m:percent_2002_lower_ci p:float l:"Percent 2002 Lower CI" t:dataTypeName=number

metric m:percent_2002_upper_ci p:float l:"Percent 2002 Upper CI" t:dataTypeName=number

metric m:births_2003 p:integer l:"Births 2003" t:dataTypeName=number

metric m:percent_2003 p:float l:"Percent 2003" t:dataTypeName=number

metric m:percent_2003_lower_ci p:float l:"Percent 2003 Lower CI" t:dataTypeName=number

metric m:percent_2003_upper_ci p:float l:"Percent 2003 Upper CI" t:dataTypeName=number

metric m:births_2004 p:integer l:"Births 2004" t:dataTypeName=number

metric m:percent_2004 p:float l:"Percent 2004" t:dataTypeName=number

metric m:percent_2004_lower_ci p:float l:"Percent 2004 Lower CI" t:dataTypeName=number

metric m:percent_2004_upper_ci p:float l:"Percent 2004 Upper CI" t:dataTypeName=number

metric m:births_2005 p:integer l:"Births 2005" t:dataTypeName=number

metric m:percent_2005 p:float l:"Percent 2005" t:dataTypeName=number

metric m:percent_2005_lower_ci p:float l:"Percent 2005 Lower CI" t:dataTypeName=number

metric m:percent_2005_upper_ci p:float l:"Percent 2005 Upper CI" t:dataTypeName=number

metric m:births_2006 p:integer l:"Births 2006" t:dataTypeName=number

metric m:percent_2006 p:float l:"Percent 2006" t:dataTypeName=number

metric m:percent_2006_lower_ci p:float l:"Percent 2006 Lower CI" t:dataTypeName=number

metric m:percent_2006_upper_ci p:double l:"Percent 2006 Upper CI" t:dataTypeName=number

metric m:births_2007 p:integer l:"Births 2007" t:dataTypeName=number

metric m:percent_2007 p:float l:"Percent 2007" t:dataTypeName=number

metric m:percent_2007_lower_ci p:float l:"Percent 2007 Lower CI" t:dataTypeName=number

metric m:percent_2007_upper_ci p:float l:"Percent 2007 Upper CI" t:dataTypeName=number

metric m:births_2008 p:integer l:"Births 2008" t:dataTypeName=number

metric m:percent_2008 p:float l:"Percent 2008" t:dataTypeName=number

metric m:percent_2008_lower_ci p:float l:"Percent 2008 Lower CI" t:dataTypeName=number

metric m:percent_2008_upper_ci p:float l:"Percent 2008 Upper CI" t:dataTypeName=number

metric m:births_2009 p:integer l:"Births 2009" t:dataTypeName=number

metric m:percent_2009 p:float l:"Percent 2009" t:dataTypeName=number

metric m:percent_2009_lower_ci p:float l:"Percent 2009 Lower CI" t:dataTypeName=number

metric m:percent_2009_upper_ci p:float l:"Percent 2009 Upper CI" t:dataTypeName=number

entity e:fbxr-9u99 l:"Public Health Statistics - Low birth weight in Chicago, by year, 1999 ? 2009" t:attribution="Illinois Department of Public Health (IDPH)" t:url=https://data.cityofchicago.org/api/views/fbxr-9u99

property e:fbxr-9u99 t:meta.view v:id=fbxr-9u99 v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics - Low birth weight in Chicago, by year, 1999 ? 2009" v:attribution="Illinois Department of Public Health (IDPH)"

property e:fbxr-9u99 t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:fbxr-9u99 t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| community_area | community_area_name | births_1999 | percent_1999 | percent_1999_lower_ci | percent_1999_upper_ci | births_2000 | percent_2000 | percent_2000_lower_ci | percent_2000_upper_ci | births_2001 | percent_2001 | percent_2001_lower_ci | percent_2001_upper_ci | births_2002 | percent_2002 | percent_2002_lower_ci | percent_2002_upper_ci | births_2003 | percent_2003 | percent_2003_lower_ci | percent_2003_upper_ci | births_2004 | percent_2004 | percent_2004_lower_ci | percent_2004_upper_ci | births_2005 | percent_2005 | percent_2005_lower_ci | percent_2005_upper_ci | births_2006 | percent_2006 | percent_2006_lower_ci | percent_2006_upper_ci | births_2007 | percent_2007 | percent_2007_lower_ci | percent_2007_upper_ci | births_2008 | percent_2008 | percent_2008_lower_ci | percent_2008_upper_ci | births_2009 | percent_2009 | percent_2009_lower_ci | percent_2009_upper_ci | warning                                                                                                                   | 
| ============== | =================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | =========== | ============ | ===================== | ===================== | ========================================================================================================================= | 
| 1              | ROGERS PARK         | 103         | 8.4          | 6.9                   | 9.9                   | 114         | 9            | 7.4                   | 10.6                  | 97          | 8.2          | 6.6                   | 9.8                   | 96          | 8.7          | 7                     | 10.4                  | 86          | 8.4          | 6.7                   | 10.1                  | 71          | 7.7          | 6                     | 9.4                   | 79          | 8.9          | 7                     | 10.8                  | 77          | 8.2          | 6.4                   | 10                    | 77          | 8.4          | 6.6                   | 10.2                  | 76          | 8.5          | 6.7                   | 10.3                  | 101         | 11           | 9                     | 13                    |                                                                                                                           | 
| 2              | WEST RIDGE          | 81          | 6.6          | 5.2                   | 8                     | 104         | 8.2          | 6.7                   | 9.7                   | 107         | 8.8          | 7.2                   | 10.4                  | 92          | 7            | 5.6                   | 8.4                   | 120         | 9.6          | 8                     | 11.2                  | 114         | 9.1          | 7.5                   | 10.7                  | 96          | 8.2          | 6.6                   | 9.8                   | 80          | 6.8          | 5.4                   | 8.2                   | 128         | 10.1         | 8.4                   | 11.8                  | 81          | 6.6          | 5.2                   | 8                     | 101         | 8.1          | 6.6                   | 9.6                   |                                                                                                                           | 
| 3              | UPTOWN              | 79          | 9.3          | 7.3                   | 11.3                  | 99          | 11.2         | 9.1                   | 13.3                  | 77          | 8.8          | 6.9                   | 10.7                  | 58          | 7.3          | 5.5                   | 9.1                   | 62          | 8            | 6.1                   | 9.9                   | 64          | 8.6          | 6.6                   | 10.6                  | 67          | 8.4          | 6.5                   | 10.3                  | 83          | 10.2         | 8.1                   | 12.3                  | 58          | 7.6          | 5.7                   | 9.5                   | 60          | 8.2          | 6.2                   | 10.2                  | 62          | 8.3          | 6.3                   | 10.3                  |                                                                                                                           | 
| 4              | LINCOLN SQUARE      | 52          | 7.6          | 5.6                   | 9.6                   | 49          | 7.4          | 5.4                   | 9.4                   | 45          | 7.4          | 5.3                   | 9.5                   | 42          | 6.5          | 4.6                   | 8.4                   | 47          | 7            | 5.1                   | 8.9                   | 45          | 7.3          | 5.2                   | 9.4                   | 50          | 8.3          | 6.1                   | 10.5                  | 59          | 9.3          | 7                     | 11.6                  | 52          | 8.8          | 6.5                   | 11.1                  | 50          | 7.7          | 5.6                   | 9.8                   | 55          | 8.1          | 6.1                   | 10.1                  |                                                                                                                           | 
| 5              | NORTH CENTER        | 42          | 8.5          | 6                     | 11                    | 41          | 7            | 4.9                   | 9.1                   | 38          | 7.1          | 4.9                   | 9.3                   | 39          | 7.2          | 5                     | 9.4                   | 35          | 6            | 4.1                   | 7.9                   | 55          | 9.2          | 6.9                   | 11.5                  | 49          | 8            | 5.9                   | 10.1                  | 60          | 9            | 6.8                   | 11.2                  | 51          | 8            | 5.9                   | 10.1                  | 44          | 6.4          | 4.6                   | 8.2                   | 65          | 9.1          | 7                     | 11.2                  |                                                                                                                           | 
| 6              | LAKE VIEW           | 77          | 7.5          | 5.9                   | 9.1                   | 82          | 7.8          | 6.2                   | 9.4                   | 91          | 8.8          | 7.1                   | 10.5                  | 90          | 8.3          | 6.7                   | 9.9                   | 89          | 7.9          | 6.3                   | 9.5                   | 85          | 7.5          | 6                     | 9                     | 68          | 6.1          | 4.7                   | 7.5                   | 75          | 7            | 5.5                   | 8.5                   | 85          | 7.2          | 5.7                   | 8.7                   | 92          | 7.8          | 6.3                   | 9.3                   | 81          | 6.3          | 5                     | 7.6                   |                                                                                                                           | 
| 7              | LINCOLN PARK        | 66          | 7.8          | 6                     | 9.6                   | 48          | 5.7          | 4.1                   | 7.3                   | 76          | 8.9          | 7                     | 10.8                  | 82          | 9.4          | 7.5                   | 11.3                  | 76          | 8.5          | 6.7                   | 10.3                  | 74          | 8.5          | 6.7                   | 10.3                  | 66          | 8.4          | 6.5                   | 10.3                  | 70          | 8.3          | 6.4                   | 10.2                  | 48          | 5.8          | 4.2                   | 7.4                   | 58          | 7.4          | 5.6                   | 9.2                   | 56          | 6.6          | 4.9                   | 8.3                   |                                                                                                                           | 
| 8              | NEAR NORTH SIDE     | 83          | 11.3         | 9                     | 13.6                  | 65          | 8.4          | 6.4                   | 10.4                  | 88          | 10.8         | 8.7                   | 12.9                  | 88          | 11.4         | 9.2                   | 13.6                  | 77          | 9.5          | 7.5                   | 11.5                  | 77          | 9.4          | 7.4                   | 11.4                  | 74          | 9.6          | 7.5                   | 11.7                  | 71          | 9            | 7                     | 11                    | 74          | 9.7          | 7.6                   | 11.8                  | 84          | 10.2         | 8.1                   | 12.3                  | 74          | 8.6          | 6.7                   | 10.5                  |                                                                                                                           | 
| 9              | EDISON PARK         | 6           | 4.5          | 1                     | 8                     | 7           | 4.8          | 1.3                   | 8.3                   | 8           | 6.5          | 2.1                   | 10.9                  | 13          | 9            | 4.3                   | 13.7                  | 17          | 13.2         | 7.4                   | 19                    | 11          | 7.5          | 3.2                   | 11.8                  | 9           | 6.9          | 2.6                   | 11.2                  | 6           | 4.6          | 1                     | 8.2                   | 6           | 4.8          | 1.1                   | 8.5                   | 12          | 8.3          | 3.8                   | 12.8                  | 10          | 7.9          | 3.2                   | 12.6                  | Percent and confidence interval estimates for years in which fewer than 20 births reported this attribute are unreliable. | 
| 10             | NORWOOD PARK        | 26          | 6.1          | 3.8                   | 8.4                   | 31          | 7.4          | 4.9                   | 9.9                   | 34          | 8            | 5.4                   | 10.6                  | 29          | 6.5          | 4.2                   | 8.8                   | 38          | 8.5          | 5.9                   | 11.1                  | 42          | 9.6          | 6.8                   | 12.4                  | 30          | 7.1          | 4.6                   | 9.6                   | 40          | 9.3          | 6.5                   | 12.1                  | 29          | 6.9          | 4.5                   | 9.3                   | 24          | 6.2          | 3.8                   | 8.6                   | 19          | 4.9          | 2.7                   | 7.1                   | Percent and confidence interval estimates for years in which fewer than 20 births reported this attribute are unreliable. | 
```