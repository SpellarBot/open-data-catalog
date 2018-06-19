# Master Expenditure Tracking Table (3-15-2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/concept-local-project-expenditures-1-11-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/ktwz-dygw) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ktwz-dygw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ktwz-dygw/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ktwz-dygw |
| Name | Master Expenditure Tracking Table (3-15-2016) |
| Created | 2016-01-11T18:58:35Z |
| Publication Date | 2016-03-25T17:52:54Z |

## Description

From RCO's publicly available, project-level expenditure website.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                     | Data Type | Render Type |
| ======== | ============== | ============================= | ======================== | ========= | =========== |
| Yes      | series tag     | local_project                 | Local Project:           | text      | text        |
| Yes      | numeric metric | planned_to_spend              | Planned To Spend:        | money     | money       |
| No       |                | paid_to_date                  | Paid To Date:            | text      | money       |
| No       |                | spent_to_date                 | Percent Spent To Date:   | text      | number      |
| Yes      | series tag     | funding_agreement_established | Funding Agreement Start: | text      | text        |
| Yes      | series tag     | funding_snapshot              | Funding Website:         | url       | url         |
| Yes      | series tag     | project_overview              | Project Website:         | url       | url         |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = paid_to_date,spent_to_date
```

## Data Commands

```ls
series e:ktwz-dygw d:2016-01-01T00:00:00.000Z t:local_project="Aberdeen 15-1527" t:funding_agreement_established="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1527" t:funding_snapshot=https://www.ezview.wa.gov/site/alias__1775/overview/34768/overview.aspx t:project_overview="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1775&ItemID=598&mid=65044&wversion=Staging" m:planned_to_spend=988000

series e:ktwz-dygw d:2016-01-01T00:00:00.000Z t:local_project="Aberdeen 15-1551" t:funding_agreement_established="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1551" t:funding_snapshot=https://www.ezview.wa.gov/site/alias__1743/overview/34347/overview.aspx t:project_overview="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1743&ItemID=599&mid=64505&wversion=Staging" m:planned_to_spend=15863

series e:ktwz-dygw d:2016-01-01T00:00:00.000Z t:local_project="Bucoda 15-1525" t:funding_agreement_established="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1525" t:funding_snapshot=https://www.ezview.wa.gov/site/alias__1915/overview/36499/overview.aspx t:project_overview="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1915&ItemID=545&mid=67939&wversion=Staging" m:planned_to_spend=3100000
```

## Meta Commands

```ls
metric m:planned_to_spend p:integer l:"Planned To Spend:" t:dataTypeName=money

entity e:ktwz-dygw l:"Master Expenditure Tracking Table (3-15-2016)" t:url=https://data.wa.gov/api/views/ktwz-dygw

property e:ktwz-dygw t:meta.view v:id=ktwz-dygw v:averageRating=0 v:name="Master Expenditure Tracking Table (3-15-2016)"

property e:ktwz-dygw t:meta.view.owner v:id=ugen-sv2k v:screenName=Scott v:displayName=Scott

property e:ktwz-dygw t:meta.view.tableauthor v:id=ugen-sv2k v:screenName=Scott v:roleName=publisher v:displayName=Scott
```

## Top Records

```ls
| local_project               | planned_to_spend | paid_to_date | spent_to_date | funding_agreement_established                                                     | funding_snapshot                                                                | project_overview                                                                                                                    | 
| =========================== | ================ | ============ | ============= | ================================================================================= | =============================================================================== | =================================================================================================================================== | 
| Aberdeen 15-1527            | 988000           | 0            | 0             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1527 | [https://www.ezview.wa.gov/site/alias__1775/overview/34768/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1775&ItemID=598&mid=65044&wversion=Staging, null] | 
| Aberdeen 15-1551            | 15863            | 0            | 0             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1551 | [https://www.ezview.wa.gov/site/alias__1743/overview/34347/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1743&ItemID=599&mid=64505&wversion=Staging, null] | 
| Bucoda 15-1525              | 3100000          | 31344        | 1             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1525 | [https://www.ezview.wa.gov/site/alias__1915/overview/36499/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1915&ItemID=545&mid=67939&wversion=Staging, null] | 
| Centralia 15-1524           | 900000           | 0            | 0             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1524 | [https://www.ezview.wa.gov/site/alias__1932/overview/36678/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1932&ItemID=608&mid=68215&wversion=Staging, null] | 
| Chehalis 15-1523            | 716000           | 15109        | 2             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1523 | [https://www.ezview.wa.gov/site/alias__1931/overview/36668/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1931&ItemID=556&mid=68201&wversion=Staging, null] | 
| Cosmopolis 15-1510          | 3082000          | 43506        | 1             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1510 | [https://www.ezview.wa.gov/site/alias__1763/overview/34596/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1931&ItemID=556&mid=68201&wversion=Staging, null] | 
| Elma 15-1516                | 367900           | 0            | 0             | https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=15-1516 | [https://www.ezview.wa.gov/site/alias__1917/overview/36519/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1917&ItemID=606&mid=67967&wversion=Staging, null] | 
| Grays Harbor County 15-1596 | 500000           | 0            | 0             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1596 | [https://www.ezview.wa.gov/site/alias__1937/overview/36729/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1937&ItemID=604&mid=68296&wversion=Staging, null] | 
| Grays Harbor County 16-1187 | 650000           | 0            | 0             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=16-1187 | [https://www.ezview.wa.gov/site/alias__1747/overview/34387/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1747&ItemID=605&mid=64561&wversion=Staging, null] | 
| Lewis County CD 15-1526     | 332350           | 0            | 0             | https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1526 | [https://www.ezview.wa.gov/site/alias__1939/overview/36752/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1939&ItemID=617&mid=68334&wversion=Staging, null] | 
```