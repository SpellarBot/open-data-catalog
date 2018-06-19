# MDAg - Structural BMPs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mdag-structural-bmps) |
| Metadata | [Link](https://data.maryland.gov/api/views/6xeb-v5qh) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/6xeb-v5qh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/6xeb-v5qh/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 6xeb-v5qh |
| Name | MDAg - Structural BMPs |
| Attribution | MDA |
| Category | Agriculture |
| Tags | tmdl, chesapeake bay, agriculture, wip |
| Created | 2015-07-08T20:30:08Z |
| Publication Date | 2016-06-22T14:37:52Z |

## Description

Structural BMP implementation from fiscal year 1984-2015 credited toward Maryland's Watershed Implementation Plan (WIP) goals for the Chesapeake Bay.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | practice_number  | Practice Number  | text          | text          |
| Yes      | series tag     | practice_name    | Practice Name    | text          | text          |
| Yes      | series tag     | wip_category     | WIP Category     | text          | text          |
| Yes      | numeric metric | extent_installed | Extent Installed | number        | number        |
| Yes      | series tag     | unit             | Unit             | text          | text          |
| Yes      | time           | date_installed   | Date Installed   | calendar_date | calendar_date |
| Yes      | series tag     | county           | County           | text          | text          |
| Yes      | series tag     | watershed_number | Watershed Number | text          | text          |
| Yes      | series tag     | watershed_name   | Watershed Name   | text          | text          |
| Yes      | series tag     | basin_name       | Basin Name       | text          | text          |
```

## Time Field

```ls
Value = date_installed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6xeb-v5qh d:2011-03-01T00:00:00.000Z t:watershed_name="Upper Chester River" t:unit=Acres t:watershed_number=02-13-05-10 t:county=Kent t:wip_category="Alternative Crop" t:practice_number=RI-03 t:basin_name="UPPER EASTERN SHORE" t:practice_name="Alternative Crop/Switchgrass" m:extent_installed=33

series e:6xeb-v5qh d:2010-05-10T00:00:00.000Z t:watershed_name="Upper Chester River" t:unit=Acres t:watershed_number=02-13-05-10 t:county=Kent t:wip_category="Alternative Crop" t:practice_number=RI-03 t:basin_name="UPPER EASTERN SHORE" t:practice_name="Alternative Crop/Switchgrass" m:extent_installed=29.1

series e:6xeb-v5qh d:2012-06-22T00:00:00.000Z t:watershed_name="Upper Chester River" t:unit=Acres t:watershed_number=02-13-05-10 t:county="Queen Anne's" t:wip_category="Alternative Crop" t:practice_number=RI-03 t:basin_name="UPPER EASTERN SHORE" t:practice_name="Alternative Crop/Switchgrass" m:extent_installed=23
```

## Meta Commands

```ls
metric m:extent_installed p:float l:"Extent Installed" t:dataTypeName=number

entity e:6xeb-v5qh l:"MDAg - Structural BMPs" t:attribution=MDA t:url=https://data.maryland.gov/api/views/6xeb-v5qh

property e:6xeb-v5qh t:meta.view v:id=6xeb-v5qh v:category=Agriculture v:averageRating=0 v:name="MDAg - Structural BMPs" v:attribution=MDA

property e:6xeb-v5qh t:meta.view.license v:name="Public Domain"

property e:6xeb-v5qh t:meta.view.owner v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:displayName="Alisha Mulkey"

property e:6xeb-v5qh t:meta.view.tableauthor v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:roleName=editor v:displayName="Alisha Mulkey"
```

## Top Records

```ls
| practice_number | practice_name                | wip_category     | extent_installed | unit  | date_installed      | county       | watershed_number | watershed_name       | basin_name          | 
| =============== | ============================ | ================ | ================ | ===== | =================== | ============ | ================ | ==================== | =================== | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 33.00            | Acres | 2011-03-01T00:00:00 | Kent         | 02-13-05-10      | Upper Chester River  | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 29.10            | Acres | 2010-05-10T00:00:00 | Kent         | 02-13-05-10      | Upper Chester River  | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 23.00            | Acres | 2012-06-22T00:00:00 | Queen Anne's | 02-13-05-10      | Upper Chester River  | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 21.00            | Acres | 2012-06-22T00:00:00 | Queen Anne's | 02-13-05-10      | Upper Chester River  | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 20.00            | Acres | 2012-06-22T00:00:00 | Queen Anne's | 02-13-05-09      | Middle Chester River | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 20.00            | Acres | 2010-03-01T00:00:00 | Kent         | 02-13-05-09      | Middle Chester River | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 20.00            | Acres | 2009-05-10T00:00:00 | Kent         | 02-13-05-09      | Middle Chester River | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 19.00            | Acres | 2009-05-10T00:00:00 | Kent         | 02-13-05-09      | Middle Chester River | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 19.00            | Acres | 2012-03-01T00:00:00 | Kent         | 02-13-05-05      | Lower Chester River  | UPPER EASTERN SHORE | 
| RI-03           | Alternative Crop/Switchgrass | Alternative Crop | 16.00            | Acres | 2011-03-01T00:00:00 | Kent         | 02-13-05-10      | Upper Chester River  | UPPER EASTERN SHORE | 
```