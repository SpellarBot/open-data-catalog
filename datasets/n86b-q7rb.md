# Currently Accredited Law Enforcement Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/currently-accredited-law-enforcement-agencies) |
| Metadata | [Link](https://data.ny.gov/api/views/n86b-q7rb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/n86b-q7rb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/n86b-q7rb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | n86b-q7rb |
| Name | Currently Accredited Law Enforcement Agencies |
| Attribution | New York State Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | public safety, accreditation, law enforcement |
| Created | 2014-04-09T15:03:56Z |
| Publication Date | 2017-01-30T23:00:32Z |

## Description

This is a directory of the New York State Law Enforcement  Agencies currently accredited under the New York State Law Enforcement Accreditation Program which was established in 1989 through Article 36, ?846-h of the New York State Executive Law. The program was designed to provide law enforcement agencies with a mechanism to evaluate and improve the overall effectiveness of their agency and the performance of their staff.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | agency_name              | Agency Name              | text      | text        |
| Yes      | series tag     | county                   | County                   | text      | text        |
| Yes      | numeric metric | day_accredited           | Day Accredited           | number    | number      |
| Yes      | numeric metric | month_accredited_numeric | Month Accredited Numeric | number    | number      |
| Yes      | series tag     | month_accredited_name    | Month Accredited Name    | text      | text        |
| Yes      | time           | year_accredited          | Year Accredited          | number    | number      |
```

## Time Field

```ls
Value = year_accredited
Format & Zone = yyyy
```

## Data Commands

```ls
series e:n86b-q7rb d:1999-01-01T00:00:00.000Z t:month_accredited_name=December t:county=ALBANY t:agency_name="ALBANY CITY PD" m:month_accredited_numeric=12 m:day_accredited=9

series e:n86b-q7rb d:2003-01-01T00:00:00.000Z t:month_accredited_name=March t:county=ALBANY t:agency_name="ALBANY CO SO" m:month_accredited_numeric=3 m:day_accredited=4

series e:n86b-q7rb d:1990-01-01T00:00:00.000Z t:month_accredited_name=September t:county=ALBANY t:agency_name="BETHLEHEM TOWN PD" m:month_accredited_numeric=9 m:day_accredited=20
```

## Meta Commands

```ls
metric m:day_accredited p:integer l:"Day Accredited" d:"Day of the month on which the agency was originally accredited." t:dataTypeName=number

metric m:month_accredited_numeric p:integer l:"Month Accredited Numeric" d:"Numeric value of the month in which the agency was originally accredited." t:dataTypeName=number

entity e:n86b-q7rb l:"Currently Accredited Law Enforcement Agencies" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/n86b-q7rb

property e:n86b-q7rb t:meta.view v:id=n86b-q7rb v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/ops/accred/accredited-agencies.htm v:averageRating=0 v:name="Currently Accredited Law Enforcement Agencies" v:attribution="New York State Division of Criminal Justice Services"

property e:n86b-q7rb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:n86b-q7rb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:n86b-q7rb t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name        | county   | day_accredited | month_accredited_numeric | month_accredited_name | year_accredited | 
| ================== | ======== | ============== | ======================== | ===================== | =============== | 
| ALBANY CITY PD     | ALBANY   | 9              | 12                       | December              | 1999            | 
| ALBANY CO SO       | ALBANY   | 4              | 3                        | March                 | 2003            | 
| BETHLEHEM TOWN PD  | ALBANY   | 20             | 9                        | September             | 1990            | 
| COLONIE TOWN PD    | ALBANY   | 8              | 12                       | December              | 1994            | 
| GUILDERLAND TN PD  | ALBANY   | 3              | 9                        | September             | 2009            | 
| SUNY POLICE ALBANY | ALBANY   | 7              | 6                        | June                  | 2011            | 
| SUNY POLICE ALFRED | ALLEGANY | 14             | 6                        | June                  | 2012            | 
| BINGHAMTON CITY PD | BROOME   | 3              | 6                        | June                  | 1993            | 
| BROOME CO SO       | BROOME   | 23             | 10                       | October               | 2001            | 
| ENDICOTT VG PD     | BROOME   | 6              | 12                       | December              | 1990            | 
```