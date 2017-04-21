# SDOT Storm Response Vehicle Travel Directions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-storm-response-vehicle-travel-directions) |
| Metadata | [Link](https://data.seattle.gov/api/views/ixan-y3x4) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ixan-y3x4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ixan-y3x4/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ixan-y3x4 |
| Name | SDOT Storm Response Vehicle Travel Directions |
| Tags | storm response |
| Created | 2016-12-14T15:27:05Z |
| Publication Date | 2016-12-14T17:54:21Z |

## Description

Displays the direction of storm response trucks traveling in the city based on the most recent 10 minutes of data collection from the vehicles.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | numeric metric | fleet       | FLEET      | number    | text        |
| No       |                | id          | ID         | text      | text        |
| Yes      | series tag     | assettype   | ASSETTYPE  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:ixan-y3x4 d:2016-12-14T15:27:05.000Z t:objectid=1703598 t:assettype=Standard m:fleet=85707

series e:ixan-y3x4 d:2016-12-14T15:27:05.000Z t:objectid=1703599 t:assettype=Standard m:fleet=85707

series e:ixan-y3x4 d:2016-12-14T15:27:05.000Z t:objectid=1703600 t:assettype=Standard m:fleet=85707
```

## Meta Commands

```ls
metric m:fleet p:integer l:FLEET d:FLEET t:dataTypeName=number

entity e:ixan-y3x4 l:"SDOT Storm Response Vehicle Travel Directions" t:url=https://data.seattle.gov/api/views/ixan-y3x4

property e:ixan-y3x4 t:meta.view v:id=ixan-y3x4 v:averageRating=0 v:name="SDOT Storm Response Vehicle Travel Directions"

property e:ixan-y3x4 t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:ixan-y3x4 t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| :updated_at | objectid | fleet | id | assettype | 
| =========== | ======== | ===== | == | ========= | 
| 0           | 1703598  | 85707 | 14 | Standard  | 
| 0           | 1703599  | 85707 | 14 | Standard  | 
| 0           | 1703600  | 85707 | 14 | Standard  | 
| 0           | 1703601  | 85707 | 14 | Standard  | 
| 0           | 1703602  | 85707 | 14 | Standard  | 
| 0           | 1703603  | 85707 | 14 | Standard  | 
| 0           | 1703604  | 85707 | 14 | Standard  | 
| 0           | 1703605  | 85707 | 14 | Standard  | 
| 0           | 1703606  | 85707 | 14 | Standard  | 
| 0           | 1703607  | 85707 | 14 | Standard  | 
```