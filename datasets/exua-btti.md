# Maryland Annual Vehicle Miles of Travel

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-annual-vehicle-miles-of-travel-29d08) |
| Metadata | [Link](https://data.maryland.gov/api/views/exua-btti) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/exua-btti/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/exua-btti/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | exua-btti |
| Name | Maryland Annual Vehicle Miles of Travel |
| Attribution | Maryland State Highway Administration |
| Category | Transportation |
| Tags | vehicle miles of travel, sha, state highway administration, vehicle, travel |
| Created | 2012-09-10T13:01:42Z |
| Publication Date | 2017-02-24T12:41:17Z |

## Description

Annual Vehicle Miles of Travel (AVMT) represents the estimated number of miles driven on Maryland's public highways for a given year. There are two components used to estimate AVMT - traffic count data and highway mileage.
Traffic count data is summarized and reported as Annual Average Daily Traffic (AADT).

AADTs are calculated from short-term (48-hour) traffic counts performed on all publicly maintained roads in Maryland (including county and municipal).  These counts are factored to account for seasonal variation in traffic patterns and represent an ?Average Day?. 

For planning purposes, AADT's are assigned to highway segments in order to provide a picture of traffic patterns is on the highway system on an average day.
Highway mileage statistics are complied annually based on mileage reports from the local jurisdictions and SHA and MDTA offices.  Any mileage changes  are field verified by SHA's data collections crews.   

AVMT is calculated by multiplying the AADT on a road segment by the segment length. Because AADT represents Daily traffic, the result is multiplied by 365 to represent Annual Vehicle Miles of Travel. (AVMT = AADT X SECTION LENGTH X365)

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                         | Data Type | Render Type |
| ======== | ============== | ========================================== | ============================================ | ========= | =========== |
| Yes      | time           | year                                       | YEAR                                         | number    | number      |
| Yes      | numeric metric | annual_vehicle_miles_of_travel_in_millions | Annual Vehicle Miles of Travel (in millions) | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:exua-btti d:2010-01-01T00:00:00.000Z m:annual_vehicle_miles_of_travel_in_millions=56206

series e:exua-btti d:2009-01-01T00:00:00.000Z m:annual_vehicle_miles_of_travel_in_millions=55631

series e:exua-btti d:2008-01-01T00:00:00.000Z m:annual_vehicle_miles_of_travel_in_millions=56148
```

## Meta Commands

```ls
metric m:annual_vehicle_miles_of_travel_in_millions p:integer l:"Annual Vehicle Miles of Travel (in millions)" d:"Annual Vehicle Miles of Travel (AVMT) represents the estimated number of miles driven on Maryland's public highways for a given year." t:dataTypeName=number

entity e:exua-btti l:"Maryland Annual Vehicle Miles of Travel" t:attribution="Maryland State Highway Administration" t:url=https://data.maryland.gov/api/views/exua-btti

property e:exua-btti t:meta.view v:id=exua-btti v:category=Transportation v:attributionLink="http://www.roads.maryland.gov/Index.aspx?PageId=302" v:averageRating=0 v:name="Maryland Annual Vehicle Miles of Travel" v:attribution="Maryland State Highway Administration"

property e:exua-btti t:meta.view.owner v:id=f7sy-qwp3 v:screenName="Jerry Einolf" v:displayName="Jerry Einolf"

property e:exua-btti t:meta.view.tableauthor v:id=f7sy-qwp3 v:screenName="Jerry Einolf" v:roleName=editor v:displayName="Jerry Einolf"
```

## Top Records

```ls
| year | annual_vehicle_miles_of_travel_in_millions | 
| ==== | ========================================== | 
| 2010 | 56206                                      | 
| 2009 | 55631                                      | 
| 2008 | 56148                                      | 
| 2007 | 56766                                      | 
| 2006 | 56616                                      | 
| 2005 | 56599                                      | 
| 2004 | 55118                                      | 
| 2003 | 54669                                      | 
| 2002 | 53761                                      | 
| 2001 | 52017                                      | 
```