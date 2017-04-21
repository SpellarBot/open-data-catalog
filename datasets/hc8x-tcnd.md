# FDNY Firehouse Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-firehouse-listing-890bc) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hc8x-tcnd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hc8x-tcnd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hc8x-tcnd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hc8x-tcnd |
| Name | FDNY Firehouse Listing |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fire department, fdny, fd, fires, community board, station, fire station, fire house, emergency, 911 |
| Created | 2011-07-30T00:10:56Z |
| Publication Date | 2011-07-30T00:10:56Z |

## Description

Listing of all NYC fire houses with addresses

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | facilityname    | FacilityName    | text      | text        |
| No       |             | facilityaddress | FacilityAddress | text      | text        |
| Yes      | series tag  | borough         | Borough         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = facilityaddress
```

## Data Commands

```ls
series e:hc8x-tcnd d:2011-07-29T17:11:00.000Z t:facilityname=FacilityName t:borough=Borough m:row_number.hc8x-tcnd=1

series e:hc8x-tcnd d:2011-07-29T17:11:00.000Z t:facilityname="Engine 4/Ladder 15" t:borough=Manhattan m:row_number.hc8x-tcnd=2

series e:hc8x-tcnd d:2011-07-29T17:11:00.000Z t:facilityname="Engine 10/Ladder 10" t:borough=Manhattan m:row_number.hc8x-tcnd=3
```

## Meta Commands

```ls
metric m:row_number.hc8x-tcnd p:long l:"Row Number"

entity e:hc8x-tcnd l:"FDNY Firehouse Listing" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/hc8x-tcnd

property e:hc8x-tcnd t:meta.view v:id=hc8x-tcnd v:category="Public Safety" v:averageRating=0 v:name="FDNY Firehouse Listing" v:attribution="Fire Department of New York City (FDNY)"

property e:hc8x-tcnd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hc8x-tcnd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | facilityname                                            | facilityaddress       | borough   | 
| =========== | ======================================================= | ===================== | ========= | 
| 1311959460  | FacilityName                                            | FacilityAddress       | Borough   | 
| 1311959460  | Engine 4/Ladder 15                                      | 42 South Street       | Manhattan | 
| 1311959460  | Engine 10/Ladder 10                                     | 124 Liberty Street    | Manhattan | 
| 1311959460  | Engine 6                                                | 49 Beekman Street     | Manhattan | 
| 1311959460  | Engine 7/Ladder 1/Battalion 1/Manhattan Borough Command | 100-104 Duane Street  | Manhattan | 
| 1311959460  | Ladder 8                                                | 14 North Moore Street | Manhattan | 
| 1311959460  | Engine 9/Ladder 6                                       | 75 Canal Street       | Manhattan | 
| 1311959460  | Engine 15/Ladder 18/Battalion 4                         | 25 Pitt Street        | Manhattan | 
| 1311959460  | Engine 28/Ladder 11                                     | 222 East 2nd Street   | Manhattan | 
| 1311959460  | Engine 5                                                | 340 East 14th Street  | Manhattan | 
```