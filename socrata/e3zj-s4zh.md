# Seattle Crime Stats by 1990 Census Tract 1996-2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-crime-stats-by-1990-census-tract-1996-2007-74c37) |
| Metadata | [Link](https://data.seattle.gov/api/views/e3zj-s4zh) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/e3zj-s4zh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/e3zj-s4zh/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | e3zj-s4zh |
| Name | Seattle Crime Stats by 1990 Census Tract 1996-2007 |
| Attribution | city of seattle |
| Category | Public Safety |
| Tags | crime, violent, seattle |
| Created | 2009-11-23T20:07:19Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Violent Part 1 crime statistics by 1990 census tract.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | time           | report_year       | Report_Year       | number    | number      |
| Yes      | numeric metric | census_tract_1990 | Census_Tract_1990 | number    | number      |
| Yes      | series tag     | crime_type        | Crime_Type        | text      | text        |
| Yes      | numeric metric | report_year_total | Report_Year_Total | number    | number      |
```

## Time Field

```ls
Value = report_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:e3zj-s4zh d:1996-01-01T00:00:00.000Z t:crime_type="Aggravated Assault" m:census_tract_1990=1 m:report_year_total=11

series e:e3zj-s4zh d:1996-01-01T00:00:00.000Z t:crime_type=Homicide m:census_tract_1990=1 m:report_year_total=0

series e:e3zj-s4zh d:1996-01-01T00:00:00.000Z t:crime_type="NonResidential Burglary" m:census_tract_1990=1 m:report_year_total=41
```

## Meta Commands

```ls
metric m:census_tract_1990 p:double l:Census_Tract_1990 d:"The 1990 census tract the reported crimes occurred in" t:dataTypeName=number

metric m:report_year_total p:integer l:Report_Year_Total d:"Total number of crimes reported" t:dataTypeName=number

entity e:e3zj-s4zh l:"Seattle Crime Stats by 1990 Census Tract 1996-2007" t:attribution="city of seattle" t:url=https://data.seattle.gov/api/views/e3zj-s4zh

property e:e3zj-s4zh t:meta.view v:id=e3zj-s4zh v:category="Public Safety" v:averageRating=0 v:name="Seattle Crime Stats by 1990 Census Tract 1996-2007" v:attribution="city of seattle"

property e:e3zj-s4zh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:e3zj-s4zh t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:e3zj-s4zh t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| report_year | census_tract_1990 | crime_type              | report_year_total | 
| =========== | ================= | ======================= | ================= | 
| 1996        | 1                 | Aggravated Assault      | 11                | 
| 1996        | 1                 | Homicide                | 0                 | 
| 1996        | 1                 | NonResidential Burglary | 41                | 
| 1996        | 1                 | Property Crimes Total   | 430               | 
| 1996        | 1                 | Rape                    | 2                 | 
| 1996        | 1                 | Residential Burglary    | 42                | 
| 1996        | 1                 | Robbery                 | 2                 | 
| 1996        | 1                 | Theft                   | 293               | 
| 1996        | 1                 | Vehicle Theft           | 53                | 
| 1996        | 1                 | Violent Crimes Total    | 15                | 
```