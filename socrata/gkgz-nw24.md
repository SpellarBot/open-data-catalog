# Occupational Employment Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/occupational-employment-statistics) |
| Metadata | [Link](https://data.ny.gov/api/views/gkgz-nw24) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/gkgz-nw24/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/gkgz-nw24/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | gkgz-nw24 |
| Name | Occupational Employment Statistics |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | occupations, wages, employment |
| Created | 2013-02-15T17:05:02Z |
| Publication Date | 2015-10-15T16:00:31Z |

## Description

The Occupational Employment Statistics (OES) survey is a semiannual mail survey of employers that measures occupational employment and occupational wage rates for wage and salary workers in nonfarm establishments, by industry. OES estimates are constructed from a sample of about 52,000 establishments. Each year, forms are mailed to two semiannual panels of approximately 8,500 sampled establishments, one panel in May and the other in November. Estimates are a snapshot in time and cannot be used as a time series.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | area_type                  | Area Type                  | text      | number      |
| Yes      | numeric metric | area                       | Area                       | number    | number      |
| Yes      | series tag     | area_name                  | Area Name                  | text      | text        |
| Yes      | series tag     | standard_occupational_code | Standard Occupational Code | text      | text        |
| Yes      | series tag     | occupational_title         | Occupational Title         | text      | text        |
| Yes      | series tag     | employment                 | Employment                 | text      | text        |
| Yes      | numeric metric | mean                       | Mean Wage                  | money     | money       |
| Yes      | numeric metric | median                     | Median Wage                | money     | money       |
| Yes      | numeric metric | entry_wage                 | Entry Wage                 | money     | money       |
| Yes      | numeric metric | experienced_wage           | Experienced Wage           | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gkgz-nw24 d:2015-08-03T15:16:49.000Z t:area_type=1 t:employment=8810950 t:area_name="New York State" t:occupational_title="Total, All Occupations" t:standard_occupational_code=00-0000 m:median=41650 m:area=36 m:entry_wage=22330 m:mean=56690 m:experienced_wage=73870

series e:gkgz-nw24 d:2015-08-03T15:16:49.000Z t:area_type=1 t:employment=445250 t:area_name="New York State" t:occupational_title="Management Occupations" t:standard_occupational_code=11-0000 m:median=121450 m:area=36 m:entry_wage=70440 m:mean=141300 m:experienced_wage=176720

series e:gkgz-nw24 d:2015-08-03T15:16:49.000Z t:area_type=1 t:employment=18570 t:area_name="New York State" t:occupational_title="Chief Executives" t:standard_occupational_code=11-1011 m:area=36 m:entry_wage=113900 m:mean=208430
```

## Meta Commands

```ls
metric m:area p:integer l:Area d:"Geographic Area Code: 1 - Capital Region 2 - Central New York Region 3 - Finger Lakes Region 4 - Hudson Valley Region 5 - Long Island Region 6 - Mohawk Valley Region 7 - New York City Region 8 - North Country Region 9 - Southern Tier Region 10 - Western New York Region 36 - New York Statewide" t:dataTypeName=number

metric m:mean p:integer l:"Mean Wage" d:"Mean of all wages in an occupation" t:dataTypeName=money

metric m:median p:integer l:"Median Wage" d:"Median of all wages in an occupation." t:dataTypeName=money

metric m:entry_wage p:integer l:"Entry Wage" d:"Average of bottom third of wages in an occupation." t:dataTypeName=money

metric m:experienced_wage p:integer l:"Experienced Wage" d:"Experienced wage - Average of the top two thirds of wages in an occupation." t:dataTypeName=money

entity e:gkgz-nw24 l:"Occupational Employment Statistics" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/gkgz-nw24

property e:gkgz-nw24 t:meta.view v:id=gkgz-nw24 v:category="Economic Development" v:attributionLink=http://www.labor.ny.gov/stats/lswage2.asp v:averageRating=0 v:name="Occupational Employment Statistics" v:attribution="New York State Department of Labor"

property e:gkgz-nw24 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:gkgz-nw24 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:gkgz-nw24 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | area_type | area | area_name      | standard_occupational_code | occupational_title                        | employment | mean   | median | entry_wage | experienced_wage | 
| =========== | ========= | ==== | ============== | ========================== | ========================================= | ========== | ====== | ====== | ========== | ================ | 
| 1438615009  | 1         | 36   | New York State | 00-0000                    | Total, All Occupations                    | 8810950    | 56690  | 41650  | 22330      | 73870            | 
| 1438615009  | 1         | 36   | New York State | 11-0000                    | Management Occupations                    | 445250     | 141300 | 121450 | 70440      | 176720           | 
| 1438615009  | 1         | 36   | New York State | 11-1011                    | Chief Executives                          | 18570      | 208430 |        | 113900     |                  | 
| 1438615009  | 1         | 36   | New York State | 11-1021                    | General and Operations Managers           | 146050     | 143480 | 120780 | 64950      | 182740           | 
| 1438615009  | 1         | 36   | New York State | 11-1031                    | Legislators                               | 6470       | 83810  | 84380  | 69200      | 91110            | 
| 1438615009  | 1         | 36   | New York State | 11-2011                    | Advertising and Promotions Managers       | 4320       | 175130 | 171100 | 93600      |                  | 
| 1438615009  | 1         | 36   | New York State | 11-2021                    | Marketing Managers                        | 12390      | 179560 | 168980 | 104970     |                  | 
| 1438615009  | 1         | 36   | New York State | 11-2022                    | Sales Managers                            | 18060      | 177040 | 169580 | 87630      |                  | 
| 1438615009  | 1         | 36   | New York State | 11-2031                    | Public Relations and Fundraising Managers | 5790       | 152480 | 139240 | 86410      | 185520           | 
| 1438615009  | 1         | 36   | New York State | 11-3011                    | Administrative Services Managers          | 19220      | 119490 | 109470 | 68290      | 145090           | 
```