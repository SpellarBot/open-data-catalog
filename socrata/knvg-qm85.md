# Master Expenditure Tracking Table 4-19-2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/master-expenditure-tracking-table-07-20-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/knvg-qm85) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/knvg-qm85/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/knvg-qm85/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | knvg-qm85 |
| Name | Master Expenditure Tracking Table 4-19-2017 |
| Attribution | WA State Recreation and Conservation Office |
| Created | 2016-07-17T16:43:22Z |
| Publication Date | 2017-04-19T16:16:48Z |

## Description

Showing Chehalis River Basin Flood Authority's local projects funding program and individual 2015-17 expenditures.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type     | Render Type   |
| ======== | ============== | =============== | ================ | ============= | ============= |
| Yes      | series tag     | jurisdiction    | Jurisdiction:    | text          | text          |
| Yes      | series tag     | project         | Project:         | text          | text          |
| Yes      | numeric metric | budget          | Budget: $        | number        | number        |
| Yes      | numeric metric | spent_1         | Spent: $         | number        | number        |
| Yes      | numeric metric | spent_2         | Spent: %         | number        | number        |
| Yes      | time           | start           | Start:           | calendar_date | calendar_date |
| Yes      | series tag     | funding_website | Funding Website: | url           | url           |
| Yes      | series tag     | project_website | Project Website: | url           | url           |
| Yes      | series tag     | map             | Map:             | url           | url           |
| Yes      | series tag     | sign            | Sign:            | url           | url           |
```

## Time Field

```ls
Value = start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:knvg-qm85 d:2016-05-11T00:00:00.000Z t:sign="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1941&ItemID=687&mid=68366&wversion=Staging" t:project="Aberdeen -- Fry Creek Restoration" t:project_website=https://www.ezview.wa.gov/site/alias__1941/overview/36772/overview.aspx t:map=http://arcg.is/1V7FZ8l t:funding_website="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=16-2030" t:jurisdiction=Aberdeen m:budget=500000 m:spent_2=0 m:spent_1=0

series e:knvg-qm85 d:2016-02-23T00:00:00.000Z t:sign="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1775&ItemID=632&mid=65044&wversion=Staging" t:project="Aberdeen -- North Shore Levee" t:project_website=https://www.ezview.wa.gov/site/alias__1775/overview/34768/overview.aspx t:map=http://arcg.is/1V7FZ8l t:funding_website="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1527" t:jurisdiction=Aberdeen m:budget=988000 m:spent_2=38 m:spent_1=377598

series e:knvg-qm85 d:2015-11-12T00:00:00.000Z t:sign="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1743&ItemID=633&mid=64505&wversion=Staging" t:project="Aberdeen -- Southside Levee" t:project_website=https://www.ezview.wa.gov/site/alias__1743/overview/34347/overview.aspx t:map=http://arcg.is/1V7FZ8l t:funding_website="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1551" t:jurisdiction=Aberdeen m:budget=37463 m:spent_2=38 m:spent_1=14277
```

## Meta Commands

```ls
metric m:budget p:integer l:"Budget: $" t:dataTypeName=number

metric m:spent_1 p:integer l:"Spent: $" t:dataTypeName=number

metric m:spent_2 p:integer l:"Spent: %" t:dataTypeName=number

entity e:knvg-qm85 l:"Master Expenditure Tracking Table 4-19-2017" t:attribution="WA State Recreation and Conservation Office" t:url=https://data.wa.gov/api/views/knvg-qm85

property e:knvg-qm85 t:meta.view v:id=knvg-qm85 v:averageRating=0 v:name="Master Expenditure Tracking Table 4-19-2017" v:attribution="WA State Recreation and Conservation Office"

property e:knvg-qm85 t:meta.view.owner v:id=ugen-sv2k v:screenName=Scott v:displayName=Scott

property e:knvg-qm85 t:meta.view.tableauthor v:id=ugen-sv2k v:screenName=Scott v:roleName=publisher v:displayName=Scott
```

## Top Records

```ls
| jurisdiction | project                               | budget  | spent_1 | spent_2 | start               | funding_website                                                                           | project_website                                                                 | map                            | sign                                                                                                                                | 
| ============ | ===================================== | ======= | ======= | ======= | =================== | ========================================================================================= | =============================================================================== | ============================== | =================================================================================================================================== | 
| Aberdeen     | Aberdeen -- Fry Creek Restoration     | 500000  | 0       | 0       | 2016-05-11T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=16-2030, null] | [https://www.ezview.wa.gov/site/alias__1941/overview/36772/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1941&ItemID=687&mid=68366&wversion=Staging, null] | 
| Aberdeen     | Aberdeen -- North Shore Levee         | 988000  | 377598  | 38      | 2016-02-23T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1527, null] | [https://www.ezview.wa.gov/site/alias__1775/overview/34768/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1775&ItemID=632&mid=65044&wversion=Staging, null] | 
| Aberdeen     | Aberdeen -- Southside Levee           | 37463   | 14277   | 38      | 2015-11-12T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1551, null] | [https://www.ezview.wa.gov/site/alias__1743/overview/34347/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1743&ItemID=633&mid=64505&wversion=Staging, null] | 
| Bucoda       | Bucoda -- Flood Openings (CleanSpace) | 96557   | 96557   | 100     | 2015-02-24T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1030, null] | [https://www.ezview.wa.gov/site/alias__1946/overview/36847/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [null, null]                                                                                                                        | 
| Bucoda       | Bucoda -- Flood Openings (McCann)     | 255     | 255     | 100     | 2015-02-20T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1031, null] | [https://www.ezview.wa.gov/site/alias__1946/overview/36847/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [null, null]                                                                                                                        | 
| Bucoda       | Bucoda -- Main Street Regrade         | 122818  | 108895  | 89      | 2015-09-25T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1525, null] | [https://www.ezview.wa.gov/site/alias__1915/overview/36499/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1915&ItemID=658&mid=67939&wversion=Staging, null] | 
| Centralia    | Centralia -- China Creek              | 1100000 | 68911   | 6       | 2015-11-03T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1524, null] | [https://www.ezview.wa.gov/site/alias__1932/overview/36678/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1932&ItemID=622&mid=68215&wversion=Staging, null] | 
| Chehalis     | Chehalis -- Dillenbaugh Creek Study   | 110000  | 0       | 0       | 2016-05-20T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=16-2031, null] | [https://www.ezview.wa.gov/site/alias__1943/overview/36792/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1943&ItemID=692&mid=68396&wversion=Staging, null] | 
| Chehalis     | Chehalis-Centralia Airport Pump       | 1146000 | 233306  | 20      | 2015-10-06T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1523, null] | [https://www.ezview.wa.gov/site/alias__1931/overview/36668/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1931&ItemID=558&mid=68201&wversion=Staging, null] | 
| Chehalis     | Chehalis -- WWTP Demo                 | 12500   | 0       | 0       | 2016-11-03T00:00:00 | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=16-2727, null] | [https://www.ezview.wa.gov/site/alias__1955/overview/36956/overview.aspx, null] | [http://arcg.is/1V7FZ8l, null] | [null, null]                                                                                                                        | 
```