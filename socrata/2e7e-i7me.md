# Bicycle Parking (Public)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bicycle-parking-public) |
| Metadata | [Link](https://data.sfgov.org/api/views/2e7e-i7me) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/2e7e-i7me/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/2e7e-i7me/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 2e7e-i7me |
| Name | Bicycle Parking (Public) |
| Attribution | SFMTA |
| Category | Transportation |
| Tags | bikes, sfmta |
| Created | 2016-04-28T16:56:22Z |
| Publication Date | 2016-06-04T06:27:28Z |

## Description

This dataset was created to publish information on bicycle parking facilities installed and managed by the SFMTA.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | numeric metric | year_installed   | Year Installed   | number    | number      |
| Yes      | numeric metric | month_installed  | Month Installed  | number    | number      |
| Yes      | series tag     | object_id        | Object ID        | text      | number      |
| No       |                | address          | Address          | text      | text        |
| Yes      | series tag     | location         | Location         | text      | text        |
| Yes      | series tag     | street           | Street           | text      | text        |
| Yes      | series tag     | placement        | Placement        | text      | text        |
| Yes      | numeric metric | number_of_racks  | Number of Racks  | number    | number      |
| Yes      | numeric metric | number_of_spaces | Number of Spaces | number    | number      |
| Yes      | time           | last_edited_date | Last Edited Date | date      | date        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:2e7e-i7me d:2016-04-26T00:00:00.000Z t:placement=ROADWAY t:location="Universal Cafe" t:street="19TH ST" t:object_id=1 m:number_of_racks=6 m:month_installed=12 m:year_installed=2013 m:number_of_spaces=12

series e:2e7e-i7me d:2016-04-26T00:00:00.000Z t:placement=SIDEWALK t:location="Live Fit Gym" t:street="24TH ST" t:object_id=2 m:number_of_racks=1 m:month_installed=0 m:year_installed=2003 m:number_of_spaces=2

series e:2e7e-i7me d:2016-04-26T00:00:00.000Z t:placement=SIDEWALK t:location="Office Depot" t:street="03RD ST" t:object_id=3 m:number_of_racks=1 m:month_installed=1 m:year_installed=2013 m:number_of_spaces=2
```

## Meta Commands

```ls
metric m:year_installed p:integer l:"Year Installed" t:dataTypeName=number

metric m:month_installed p:integer l:"Month Installed" t:dataTypeName=number

metric m:number_of_racks p:integer l:"Number of Racks" t:dataTypeName=number

metric m:number_of_spaces p:integer l:"Number of Spaces" t:dataTypeName=number

entity e:2e7e-i7me l:"Bicycle Parking (Public)" t:attribution=SFMTA t:url=https://data.sfgov.org/api/views/2e7e-i7me

property e:2e7e-i7me t:meta.view v:id=2e7e-i7me v:category=Transportation v:averageRating=0 v:name="Bicycle Parking (Public)" v:attribution=SFMTA

property e:2e7e-i7me t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:2e7e-i7me t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:2e7e-i7me t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| year_installed | month_installed | object_id | address          | location            | street      | placement | number_of_racks | number_of_spaces | last_edited_date | 
| ============== | =============== | ========= | ================ | =================== | =========== | ========= | =============== | ================ | ================ | 
| 2013           | 12              | 1         | 2814 19TH ST     | Universal Cafe      | 19TH ST     | ROADWAY   | 6               | 12               | 1461628800       | 
| 2003           | 0               | 2         | 2929 24TH ST     | Live Fit Gym        | 24TH ST     | SIDEWALK  | 1               | 2                | 1461628800       | 
| 2013           | 1               | 3         | 33 03RD ST       | Office Depot        | 03RD ST     | SIDEWALK  | 1               | 2                | 1461628800       | 
| 2013           | 1               | 4         | 460 GOUGH ST     | Welcome Stranger    | GOUGH       | SIDEWALK  | 1               | 2                | 1461628800       | 
| 2015           | 11              | 5         | 807 LINCOLN WAY  | Little Shamrock     | LINCOLN WAY | SIDEWALK  | 1               | 2                | 1461628800       | 
| 2006           | 0               | 6         | None             | Duboce Park         | DUBOCE      | SIDEWALK  | 1               | 2                | 1461628800       | 
| 0              | 0               | 7         | 2961 16TH ST     | Victoria Theater    | 16TH ST     | SIDEWALK  | 1               | 2                | 1461628800       | 
| 2003           | 0               | 8         | 2348 CLEMENT ST  | Royal Ground Coffee | CLEMENT     | SIDEWALK  | 1               | 2                | 1461628800       | 
| 2015           | 9               | 9         | 543 Hugo St      | residential         | HUGO ST     | SIDEWALK  | 1               | 2                | 1461628800       | 
| 2004           | 0               | 10        | 2029 FILLMORE ST | Lilith              | FILLMORE    | SIDEWALK  | 1               | 2                | 1461628800       | 
```