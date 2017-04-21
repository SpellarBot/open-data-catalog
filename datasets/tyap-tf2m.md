# Rochester-Genesee Regional Transportation Authority (RGRTA) Rider Volumes: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rochester-genesee-regional-transportation-authority-rgrta-rider-volumes-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/tyap-tf2m) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tyap-tf2m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tyap-tf2m/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tyap-tf2m |
| Name | Rochester-Genesee Regional Transportation Authority (RGRTA) Rider Volumes: Beginning 2006 |
| Attribution | Rochester Genesee Regional Transportation Authority |
| Category | Transportation |
| Tags | transportation, ridership, transit, bus, rochester, rgrta |
| Created | 2013-12-23T18:24:12Z |
| Publication Date | 2016-05-03T22:00:41Z |

## Description

This dataset includes ridership for the eight transportation subsidiaries managed by the Rochester Genesee Regional Transportation Authority. Ridership includes the total number of riders, passengers or boardings.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | subsidiary | Subsidiary | text      | text        |
| No       |                | month      | Month      | number    | number      |
| No       |                | year       | Year       | number    | number      |
| Yes      | numeric metric | ridership  | Ridership  | number    | number      |
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
series e:tyap-tf2m d:2006-04-01T00:00:00.000Z t:subsidiary="Regional Transit Service" m:ridership=1066870

series e:tyap-tf2m d:2006-05-01T00:00:00.000Z t:subsidiary="Regional Transit Service" m:ridership=1217939

series e:tyap-tf2m d:2006-06-01T00:00:00.000Z t:subsidiary="Regional Transit Service" m:ridership=1183756
```

## Meta Commands

```ls
metric m:ridership p:integer l:Ridership d:"The total number of riders, passengers, or boardings." t:dataTypeName=number

entity e:tyap-tf2m l:"Rochester-Genesee Regional Transportation Authority (RGRTA) Rider Volumes:  Beginning 2006" t:attribution="Rochester Genesee Regional Transportation Authority" t:url=https://data.ny.gov/api/views/tyap-tf2m

property e:tyap-tf2m t:meta.view v:id=tyap-tf2m v:category=Transportation v:averageRating=0 v:name="Rochester-Genesee Regional Transportation Authority (RGRTA) Rider Volumes:  Beginning 2006" v:attribution="Rochester Genesee Regional Transportation Authority"

property e:tyap-tf2m t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tyap-tf2m t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tyap-tf2m t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| subsidiary               | month | year | ridership | 
| ======================== | ===== | ==== | ========= | 
| Regional Transit Service | 4     | 2006 | 1066870   | 
| Regional Transit Service | 5     | 2006 | 1217939   | 
| Regional Transit Service | 6     | 2006 | 1183756   | 
| Regional Transit Service | 7     | 2006 | 933542    | 
| Regional Transit Service | 8     | 2006 | 1018668   | 
| Regional Transit Service | 9     | 2006 | 1227358   | 
| Regional Transit Service | 10    | 2006 | 1307201   | 
| Regional Transit Service | 11    | 2006 | 1252595   | 
| Regional Transit Service | 12    | 2006 | 1178240   | 
| Regional Transit Service | 1     | 2007 | 1312857   | 
```