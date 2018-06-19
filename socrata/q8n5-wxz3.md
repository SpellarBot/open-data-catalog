# Rochester-Genesee Regional Transportation Authority (RGRTA) Percentage of Buses Running On Time: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rochester-genesee-regional-transportation-authority-rgrta-percentage-of-buses-running-on-t) |
| Metadata | [Link](https://data.ny.gov/api/views/q8n5-wxz3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q8n5-wxz3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q8n5-wxz3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q8n5-wxz3 |
| Name | Rochester-Genesee Regional Transportation Authority (RGRTA) Percentage of Buses Running On Time: Beginning 2009 |
| Attribution | Rochester Genesee Regional Transportation Authority |
| Category | Transportation |
| Tags | transportation, transit, rochester, rgrta, on-time performance, bus |
| Created | 2013-12-23T18:08:32Z |
| Publication Date | 2016-05-03T22:01:49Z |

## Description

This dataset identifies the percentage of Rochester-Genesee Regional Transportation Authority (RGRTA) buses that are on time. On-time performance includes the percentage of buses that leave their start point or arrive at a destination within 2:59 minutes early to 5:59 minutes late.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | subsidiary      | Subsidiary      | text      | text        |
| No       |                | month           | Month           | number    | number      |
| No       |                | year            | Year            | number    | number      |
| Yes      | numeric metric | percent_on_time | Percent On-Time | percent   | percent     |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:q8n5-wxz3 d:2009-04-01T00:00:00.000Z t:subsidiary="Regional Transit Service" m:percent_on_time=84

series e:q8n5-wxz3 d:2009-05-01T00:00:00.000Z t:subsidiary="Regional Transit Service" m:percent_on_time=83

series e:q8n5-wxz3 d:2009-06-01T00:00:00.000Z t:subsidiary="Regional Transit Service" m:percent_on_time=82
```

## Meta Commands

```ls
metric m:percent_on_time p:float l:"Percent On-Time" d:"The percentage of the time buses arrive and leave at their timepoints." t:dataTypeName=percent

entity e:q8n5-wxz3 l:"Rochester-Genesee Regional Transportation Authority (RGRTA) Percentage of Buses Running On Time:  Beginning 2009" t:attribution="Rochester Genesee Regional Transportation Authority" t:url=https://data.ny.gov/api/views/q8n5-wxz3

property e:q8n5-wxz3 t:meta.view v:id=q8n5-wxz3 v:category=Transportation v:averageRating=0 v:name="Rochester-Genesee Regional Transportation Authority (RGRTA) Percentage of Buses Running On Time:  Beginning 2009" v:attribution="Rochester Genesee Regional Transportation Authority"

property e:q8n5-wxz3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:q8n5-wxz3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:q8n5-wxz3 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| subsidiary               | month | year | percent_on_time | 
| ======================== | ===== | ==== | =============== | 
| Regional Transit Service | 4     | 2009 | 84.00           | 
| Regional Transit Service | 5     | 2009 | 83.00           | 
| Regional Transit Service | 6     | 2009 | 82.00           | 
| Regional Transit Service | 7     | 2009 | 83.60           | 
| Regional Transit Service | 8     | 2009 | 83.20           | 
| Regional Transit Service | 9     | 2009 | 81.30           | 
| Regional Transit Service | 10    | 2009 | 82.70           | 
| Regional Transit Service | 11    | 2009 | 83.70           | 
| Regional Transit Service | 12    | 2009 | 82.20           | 
| Regional Transit Service | 1     | 2009 | 82.90           | 
```