# Bus Safety Information Network (BUSNET) Operator Report: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bus-safety-information-network-busnet-operator-report-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/h9zr-j4pg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/h9zr-j4pg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/h9zr-j4pg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | h9zr-j4pg |
| Name | Bus Safety Information Network (BUSNET) Operator Report: Beginning 2009 |
| Attribution | New York State Department of Transportation (NYSDOT) |
| Category | Transportation |
| Tags | transportaion, bus inspections |
| Created | 2015-02-24T18:41:16Z |
| Publication Date | 2016-05-13T16:57:13Z |

## Description

The Bus Safety Information Network (BUSNET) Profile Operator Report dataset provides a summary of annual bus passenger vehicle operators safety inspections conducted by New York State Department of Transportation (NYSDOT).   The dataset is a summary listing of all operators that have one or more vehicles inspected under NYSDOT semi-annual vehicle safety inspection program by state fiscal year.  The semi-annual bus inspection program is helps to reduce accidents, injuries, and fatalities resulting from unsafe vehicles operating on highways in New York State.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | state_fiscal_year_end_date | State Fiscal Year End Date | calendar_date | calendar_date |
| Yes      | series tag     | operator_name              | Operator Name              | text          | text          |
| Yes      | numeric metric | inspections                | Total Inspections          | number        | number        |
| Yes      | numeric metric | failed_inspections         | Failed Inspections         | number        | number        |
| Yes      | series tag     | operator_id                | Operator ID                | text          | number        |
| Yes      | series tag     | city                       | City                       | text          | text          |
| Yes      | series tag     | region                     | Region                     | text          | number        |
```

## Time Field

```ls
Value = state_fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:h9zr-j4pg d:2014-03-31T00:00:00.000Z t:region=11 t:operator_name="1ST CLASS TRANSPORTATION SERVICE" t:operator_id=48486 t:city="QUEENS VILLAGE" m:failed_inspections=1 m:inspections=4

series e:h9zr-j4pg d:2014-03-31T00:00:00.000Z t:region=11 t:operator_name="21ST AVE. TRANSPORTATION" t:operator_id=3531 t:city=BROOKLYN m:failed_inspections=19 m:inspections=250

series e:h9zr-j4pg d:2014-03-31T00:00:00.000Z t:region=10 t:operator_name="3J'S LIMOUSINE INC." t:operator_id=50284 t:city=MELVILLE m:failed_inspections=0 m:inspections=2
```

## Meta Commands

```ls
metric m:inspections p:integer l:"Total Inspections" d:"The number of inspections, including re-inspections and failed inspections, performed for an Operator during the state fiscal year" t:dataTypeName=number

metric m:failed_inspections p:integer l:"Failed Inspections" d:"The number of inspections that failed, requiring re-inspection" t:dataTypeName=number

entity e:h9zr-j4pg l:"Bus Safety Information Network (BUSNET) Operator Report:  Beginning 2009" t:attribution="New York State Department of Transportation (NYSDOT)" t:url=https://data.ny.gov/api/views/h9zr-j4pg

property e:h9zr-j4pg t:meta.view d:2017-06-09T13:53:30.827Z v:id=h9zr-j4pg v:category=Transportation v:attributionLink=https://www.dot.ny.gov/divisions/operating/osss/bus/inspection v:averageRating=0 v:name="Bus Safety Information Network (BUSNET) Operator Report:  Beginning 2009" v:attribution="New York State Department of Transportation (NYSDOT)"

property e:h9zr-j4pg t:meta.view.owner d:2017-06-09T13:53:30.827Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:h9zr-j4pg t:meta.view.tableauthor d:2017-06-09T13:53:30.827Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:h9zr-j4pg t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:53:30.827Z v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| state_fiscal_year_end_date | operator_name                    | inspections | failed_inspections | operator_id | city           | region | 
| ========================== | ================================ | =========== | ================== | =========== | ============== | ====== | 
| 2014-03-31T00:00:00        | 1ST CLASS TRANSPORTATION SERVICE | 4           | 1                  | 48486       | QUEENS VILLAGE | 11     | 
| 2014-03-31T00:00:00        | 21ST AVE. TRANSPORTATION         | 250         | 19                 | 3531        | BROOKLYN       | 11     | 
| 2014-03-31T00:00:00        | 3J'S LIMOUSINE INC.              | 2           | 0                  | 50284       | MELVILLE       | 10     | 
| 2014-03-31T00:00:00        | 3RD AVENUE TRANSIT               | 114         | 1                  | 6043        | BROOKLYN       | 11     | 
| 2014-03-31T00:00:00        | 422 DND CORP                     | 5           | 0                  | 49379       | ISLIP TERRACE  | 10     | 
| 2014-03-31T00:00:00        | 5 STAR LIMO OF ELMIRA            | 2           | 1                  | 49862       | ELMIRA         | 4      | 
| 2014-03-31T00:00:00        | A & A SERVICE                    | 5           | 1                  | 5758        | MT VERNON      | 11     | 
| 2014-03-31T00:00:00        | A & B VAN SERVICE                | 37          | 0                  | 3479        | STATEN ISLAND  | 11     | 
| 2014-03-31T00:00:00        | A & E MEDICAL TRANSPORT INC      | 42          | 5                  | 6165        | CANANDAIGUA    | 4      | 
| 2014-03-31T00:00:00        | A & E TRANSPORT SERVICES         | 28          | 4                  | 6692        | OSWEGO         | 3      | 
```