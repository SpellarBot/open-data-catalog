# SDOT Pothole Repairs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pothole-repairs-eaf38) |
| Metadata | [Link](https://data.seattle.gov/api/views/w3qe-e2jj) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/w3qe-e2jj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/w3qe-e2jj/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | w3qe-e2jj |
| Name | SDOT Pothole Repairs |
| Attribution | SDOT |
| Category | Transportation |
| Tags | pothole, sdot, city of seattle, seattle, work orders, streets, repair |
| Created | 2012-04-27T21:46:16Z |
| Publication Date | 2012-04-27T21:52:31Z |

## Description

Displays the pothole repair work orders that are currently being evaluated and repaired by SDOT?s Street Maintenance crews along with those that have been repaired over the previous year. The previous year is based on a rolling calendar.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | objectid      | OBJECTID      | text      | number      |
| Yes      | numeric metric | wokey         | WOKEY         | number    | number      |
| Yes      | series tag     | wo_status     | WO_STATUS     | text      | text        |
| Yes      | numeric metric | last90dayrprd | LAST90DAYRPRD | number    | number      |
| Yes      | numeric metric | current_qtr   | CURRENT_QTR   | number    | number      |
| Yes      | numeric metric | previous_1qtr | PREVIOUS_1QTR | number    | number      |
| Yes      | numeric metric | previous_2qtr | PREVIOUS_2QTR | number    | number      |
| Yes      | numeric metric | previous_3qtr | PREVIOUS_3QTR | number    | number      |
| Yes      | numeric metric | previous_4qtr | PREVIOUS_4QTR | number    | number      |
| Yes      | time           | initdt        | INITDT        | date      | date        |
| No       |                | fldstartdt    | FLDSTARTDT    | date      | date        |
| No       |                | fldenddt      | FLDENDDT      | date      | date        |
| Yes      | series tag     | location      | LOCATION      | text      | text        |
| Yes      | series tag     | addrdesc      | ADDRDESC      | text      | text        |
```

## Time Field

```ls
Value = initdt
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fldstartdt,fldenddt
```

## Data Commands

```ls
series e:w3qe-e2jj d:2017-04-18T00:00:00.000Z t:addrdesc="UTAH AVE S BETWEEN S LUCILE ST AND S FINDLAY ST" t:location="Utah street between South Lucile st and South Findlay st" t:objectid=1 t:wo_status="PENDING WORK REQUEST" m:previous_1qtr=0 m:current_qtr=0 m:previous_4qtr=0 m:previous_2qtr=0 m:previous_3qtr=0 m:wokey=514463 m:last90dayrprd=0

series e:w3qe-e2jj d:2017-04-17T00:00:00.000Z t:addrdesc="NW MARKET ST BETWEEN 28TH AVE NW AND NW 54TH ST" t:location="2801 NW MARKET ST, SEATTLE, WA 98107" t:objectid=2 t:wo_status=COMPLETED m:previous_1qtr=0 m:current_qtr=0 m:previous_4qtr=0 m:previous_2qtr=0 m:previous_3qtr=0 m:wokey=513957 m:last90dayrprd=0

series e:w3qe-e2jj d:2017-04-17T00:00:00.000Z t:addrdesc="32ND AVE W BETWEEN W MCGRAW ST AND W WHEELER ST" t:objectid=3 t:wo_status="PENDING WORK REQUEST" m:previous_1qtr=0 m:current_qtr=0 m:previous_4qtr=0 m:previous_2qtr=0 m:previous_3qtr=0 m:wokey=513914 m:last90dayrprd=0
```

## Meta Commands

```ls
metric m:wokey p:integer l:WOKEY d:"Work Order #" t:dataTypeName=number

metric m:last90dayrprd p:integer l:LAST90DAYRPRD d:"Potholes Repaired" t:dataTypeName=number

metric m:current_qtr p:integer l:CURRENT_QTR d:"Potholes Repaired" t:dataTypeName=number

metric m:previous_1qtr p:integer l:PREVIOUS_1QTR d:"Potholes Repaired" t:dataTypeName=number

metric m:previous_2qtr p:integer l:PREVIOUS_2QTR d:"Potholes Repaired" t:dataTypeName=number

metric m:previous_3qtr p:integer l:PREVIOUS_3QTR d:"Potholes Repaired" t:dataTypeName=number

metric m:previous_4qtr p:integer l:PREVIOUS_4QTR d:"Potholes Repaired" t:dataTypeName=number

entity e:w3qe-e2jj l:"SDOT Pothole Repairs" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/w3qe-e2jj

property e:w3qe-e2jj t:meta.view v:id=w3qe-e2jj v:category=Transportation v:averageRating=0 v:name="SDOT Pothole Repairs" v:attribution=SDOT

property e:w3qe-e2jj t:meta.view.license v:name="Public Domain"

property e:w3qe-e2jj t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:w3qe-e2jj t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | wokey  | wo_status            | last90dayrprd | current_qtr | previous_1qtr | previous_2qtr | previous_3qtr | previous_4qtr | initdt     | fldstartdt | fldenddt   | location                                                            | addrdesc                                                | 
| ======== | ====== | ==================== | ============= | =========== | ============= | ============= | ============= | ============= | ========== | ========== | ========== | =================================================================== | ======================================================= | 
| 1        | 514463 | PENDING WORK REQUEST | 0             | 0           | 0             | 0             | 0             | 0             | 1492473600 |            |            | Utah street between South Lucile st and South Findlay st            | UTAH AVE S BETWEEN S LUCILE ST AND S FINDLAY ST         | 
| 2        | 513957 | COMPLETED            | 0             | 0           | 0             | 0             | 0             | 0             | 1492387200 | 1492560000 | 1492560000 | 2801 NW MARKET ST, SEATTLE, WA 98107                                | NW MARKET ST BETWEEN 28TH AVE NW AND NW 54TH ST         | 
| 3        | 513914 | PENDING WORK REQUEST | 0             | 0           | 0             | 0             | 0             | 0             | 1492387200 |            |            |                                                                     | 32ND AVE W BETWEEN W MCGRAW ST AND W WHEELER ST         | 
| 4        | 514839 | PENDING WORK REQUEST | 0             | 0           | 0             | 0             | 0             | 0             | 1492473600 |            |            |                                                                     | SW WILLOW ST BETWEEN DELRIDGE WAY SW AND 23RD AVE SW    | 
| 5        | 513849 | COMPLETED            | 0             | 0           | 0             | 0             | 0             | 0             | 1492387200 | 1492560000 | 1492560000 | 3rd Ave S and Webster                                               | S WEBSTER ST BETWEEN 2ND AVE S AND 3RD AVE S            | 
| 6        | 514618 | PENDING WORK REQUEST | 0             | 0           | 0             | 0             | 0             | 0             | 1492473600 |            |            | Montlake Blvd B/T 45th and 23rd Ave E before ramp going to 509 ramp | MONTLAKE BLVD NE BETWEEN NE 45TH (RP) ST AND NE 45TH ST | 
| 7        | 514291 | PENDING WORK REQUEST | 0             | 0           | 0             | 0             | 0             | 0             | 1492473600 |            |            | 1600 COURTLAND PLACE S                                              | S CHARLESTOWN ST BETWEEN 36TH AVE S AND COURTLAND PL S  | 
| 8        | 514934 | PENDING WORK REQUEST | 0             | 0           | 0             | 0             | 0             | 0             | 1492560000 |            |            | 7108 46th ave s                                                     | 46TH AVE S BETWEEN S MYRTLE ST AND S ORCHARD ST         | 
| 9        | 514542 | PENDING WORK REQUEST | 0             | 0           | 0             | 0             | 0             | 0             | 1492473600 |            |            | 2400 BEACON AVE S,                                                  | BEACON AVE S BETWEEN 14TH AVE S AND S BAYVIEW ST        | 
| 10       | 513873 | COMPLETED            | 0             | 0           | 0             | 0             | 0             | 0             | 1492387200 | 1492560000 | 1492560000 | S GAZELLE ST BETWEEN DEAD END AND BEACON AVE S                      | S GAZELLE ST BETWEEN DEAD END AND BEACON AVE S          | 
```