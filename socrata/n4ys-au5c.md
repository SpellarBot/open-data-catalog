# Motor Vehicle Crashes by Facility, Port Authority of NY NJ: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-crashes-by-facility-port-authority-of-ny-nj-beginning-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/n4ys-au5c) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/n4ys-au5c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/n4ys-au5c/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | n4ys-au5c |
| Name | Motor Vehicle Crashes by Facility, Port Authority of NY NJ: Beginning 2000 |
| Attribution | Port Authority of NY & NJ |
| Category | Transportation |
| Tags | motor vehicle, crashes, accidents, port authority |
| Created | 2013-05-09T13:40:16Z |
| Publication Date | 2016-06-15T15:40:25Z |

## Description

The Port Authority of NY & NJ annually reports on motor vehicle crashes throughout its facilities.  The data reported in this dataset represents motor vehicle crashes of vehicles in transport on public trafficways within Port Authority jurisdiction.  A crash is a harmful event which involves a motor vehicle in transport that strikes another motor vehicle, other property, debris, animal, pedestrian, or bicyclist, or in which a motor vehicle overturns (rolls over), jackknifes, catches fire or explodes while within the trafficway.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                  | Data Type | Render Type |
| ======== | ============== | ================================= | ===================================== | ========= | =========== |
| Yes      | series tag     | facility                          | Facility                              | text      | text        |
| Yes      | time           | year                              | Year                                  | number    | number      |
| Yes      | numeric metric | total_no_of_motor_vehicle_crashes | Total Number of Motor Vehicle Crashes | number    | number      |
| Yes      | numeric metric | no_of_fatal_crashes               | Number of Fatal Crashes               | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:n4ys-au5c d:2000-01-01T00:00:00.000Z t:facility="Bayonne Bridge" m:total_no_of_motor_vehicle_crashes=24 m:no_of_fatal_crashes=0

series e:n4ys-au5c d:2001-01-01T00:00:00.000Z t:facility="Bayonne Bridge" m:total_no_of_motor_vehicle_crashes=19 m:no_of_fatal_crashes=1

series e:n4ys-au5c d:2002-01-01T00:00:00.000Z t:facility="Bayonne Bridge" m:total_no_of_motor_vehicle_crashes=13 m:no_of_fatal_crashes=0
```

## Meta Commands

```ls
metric m:total_no_of_motor_vehicle_crashes p:integer l:"Total Number of Motor Vehicle Crashes" t:dataTypeName=number

metric m:no_of_fatal_crashes p:integer l:"Number of Fatal Crashes" d:"Total number of crashes that involved at least one fatal injury" t:dataTypeName=number

entity e:n4ys-au5c l:"Motor Vehicle Crashes by Facility, Port Authority of NY NJ: Beginning 2000" t:attribution="Port Authority of NY & NJ" t:url=https://data.ny.gov/api/views/n4ys-au5c

property e:n4ys-au5c t:meta.view v:id=n4ys-au5c v:category=Transportation v:averageRating=0 v:name="Motor Vehicle Crashes by Facility, Port Authority of NY NJ: Beginning 2000" v:attribution="Port Authority of NY & NJ"

property e:n4ys-au5c t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:n4ys-au5c t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:n4ys-au5c t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| facility       | year | total_no_of_motor_vehicle_crashes | no_of_fatal_crashes | 
| ============== | ==== | ================================= | =================== | 
| Bayonne Bridge | 2000 | 24                                | 0                   | 
| Bayonne Bridge | 2001 | 19                                | 1                   | 
| Bayonne Bridge | 2002 | 13                                | 0                   | 
| Bayonne Bridge | 2003 | 13                                | 0                   | 
| Bayonne Bridge | 2004 | 11                                | 0                   | 
| Bayonne Bridge | 2005 | 13                                | 0                   | 
| Bayonne Bridge | 2006 | 12                                | 0                   | 
| Bayonne Bridge | 2007 | 14                                | 0                   | 
| Bayonne Bridge | 2008 | 17                                | 0                   | 
| Bayonne Bridge | 2009 | 20                                | 0                   | 
```