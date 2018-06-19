# Master Expenditure Tracking Table 07-15-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/master-expenditure-tracking-table-03252016) |
| Metadata | [Link](https://data.wa.gov/api/views/k5p7-4crk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/k5p7-4crk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/k5p7-4crk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | k5p7-4crk |
| Name | Master Expenditure Tracking Table 07-15-2016 |
| Created | 2016-03-25T18:36:38Z |
| Publication Date | 2016-07-15T13:27:01Z |

## Description

Showing Chehalis River Basin Flood Authority's small projects funding program and individual local project expenditures.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | local_project            | Local Project:           | text          | text          |
| Yes      | numeric metric | planned_to_spend         | Planned To Spend:        | money         | money         |
| No       |                | paid_to_date             | Expenditures To Date:    | text          | money         |
| No       |                | percent_spent_to_date    | Percent Spent To Date:   | text          | number        |
| Yes      | time           | funding_agreement_start  | Funding Agreement Start: | calendar_date | calendar_date |
| Yes      | series tag     | funding_agreement_number | Project Name:            | text          | text          |
| Yes      | series tag     | funding_website          | Funding Website:         | url           | url           |
| Yes      | series tag     | project_website          | Project Website:         | url           | url           |
| Yes      | series tag     | project_sign_pic         | Project Sign:            | url           | url           |
```

## Time Field

```ls
Value = funding_agreement_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = paid_to_date,percent_spent_to_date
```

## Data Commands

```ls
series e:k5p7-4crk d:2016-05-11T00:00:00.000Z t:local_project="Aberdeen 16-2030" t:project_sign_pic="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1941&ItemID=665&mid=68366&wversion=Staging" t:project_website=https://www.ezview.wa.gov/site/alias__1941/overview/36772/overview.aspx t:funding_website="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=16-2030" t:funding_agreement_number="Fry Creek Restoration" m:planned_to_spend=150000

series e:k5p7-4crk d:2016-02-23T00:00:00.000Z t:local_project="Aberdeen 15-1527" t:project_sign_pic="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1775&ItemID=632&mid=65044&wversion=Staging" t:project_website=https://www.ezview.wa.gov/site/alias__1775/overview/34768/overview.aspx t:funding_website="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1527" t:funding_agreement_number="North Shore Levee Project" m:planned_to_spend=988000

series e:k5p7-4crk d:2015-11-12T00:00:00.000Z t:local_project="Aberdeen 15-1551" t:project_sign_pic="https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1743&ItemID=633&mid=64505&wversion=Staging" t:project_website=https://www.ezview.wa.gov/site/alias__1743/overview/34347/overview.aspx t:funding_website="https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1551" t:funding_agreement_number="Southside Dike/Levee Certification Project" m:planned_to_spend=15863
```

## Meta Commands

```ls
metric m:planned_to_spend p:integer l:"Planned To Spend:" t:dataTypeName=money

entity e:k5p7-4crk l:"Master Expenditure Tracking Table 07-15-2016" t:url=https://data.wa.gov/api/views/k5p7-4crk

property e:k5p7-4crk t:meta.view v:id=k5p7-4crk v:averageRating=0 v:name="Master Expenditure Tracking Table 07-15-2016"

property e:k5p7-4crk t:meta.view.owner v:id=ugen-sv2k v:screenName=Scott v:displayName=Scott

property e:k5p7-4crk t:meta.view.tableauthor v:id=ugen-sv2k v:screenName=Scott v:roleName=publisher v:displayName=Scott
```

## Top Records

```ls
| local_project               | planned_to_spend | paid_to_date | percent_spent_to_date | funding_agreement_start | funding_agreement_number                   | funding_website                                                                           | project_website                                                                 | project_sign_pic                                                                                                                    | 
| =========================== | ================ | ============ | ===================== | ======================= | ========================================== | ========================================================================================= | =============================================================================== | =================================================================================================================================== | 
| Aberdeen 16-2030            | 150000           | 0.0          | 0.00                  | 2016-05-11T00:00:00     | Fry Creek Restoration                      | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=16-2030, null] | [https://www.ezview.wa.gov/site/alias__1941/overview/36772/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1941&ItemID=665&mid=68366&wversion=Staging, null] | 
| Aberdeen 15-1527            | 988000           | 0.0          | 0.00                  | 2016-02-23T00:00:00     | North Shore Levee Project                  | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1527, null] | [https://www.ezview.wa.gov/site/alias__1775/overview/34768/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1775&ItemID=632&mid=65044&wversion=Staging, null] | 
| Aberdeen 15-1551            | 15863            | 0.0          | 0.00                  | 2015-11-12T00:00:00     | Southside Dike/Levee Certification Project | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1551, null] | [https://www.ezview.wa.gov/site/alias__1743/overview/34347/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1743&ItemID=633&mid=64505&wversion=Staging, null] | 
| Bucoda 15-1525              | 3100000          | 75625        | 2.44                  | 2015-09-25T00:00:00     | Main Street Regrade Project                | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1525, null] | [https://www.ezview.wa.gov/site/alias__1915/overview/36499/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1915&ItemID=658&mid=67939&wversion=Staging, null] | 
| Bucoda 15-1030 (CleanSpace) | 77835            | 23819        | 30.60                 | 2015-02-24T00:00:00     | Foundation Flood Openings Pilot Project    | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1030, null] | [https://www.ezview.wa.gov/site/alias__1946/overview/36847/overview.aspx, null] | [null, null]                                                                                                                        | 
| Bucoda 15-1031 (McCann)     | 1672             | 0.0          | 0.00                  | 2015-02-20T00:00:00     | Foundation Flood Openings Pilot Project    | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1031, null] | [https://www.ezview.wa.gov/site/alias__1946/overview/36847/overview.aspx, null] | [null, null]                                                                                                                        | 
| Centralia 15-1524           | 1100000          | 0.0          | 0.00                  | 2015-11-03T00:00:00     | China Creek Project                        | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1524, null] | [https://www.ezview.wa.gov/site/alias__1932/overview/36678/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1932&ItemID=622&mid=68215&wversion=Staging, null] | 
| Chehalis 15-1523            | 796000           | 163549       | 20.55                 | 2015-10-06T00:00:00     | Chehalis-Centralia Airport Pump Project    | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1523, null] | [https://www.ezview.wa.gov/site/alias__1931/overview/36668/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1931&ItemID=558&mid=68201&wversion=Staging, null] | 
| Chehalis 16-2031            | 110000           | 0.0          | 0.00                  | 2016-05-20T00:00:00     | Dillenbaugh Creek Culvert Assessment       | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=16-2031, null] | [https://www.ezview.wa.gov/site/alias__1943/overview/36792/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1943&ItemID=662&mid=68396&wversion=Staging, null] | 
| Cosmopolis 15-1510          | 3432000          | 152866       | 4.45                  | 2015-09-18T00:00:00     | Mill Creek Dam Improvement Project         | [https://secure.rco.wa.gov/prism/search/ProjectSnapshot.aspx?ProjectNumber=15-1510, null] | [https://www.ezview.wa.gov/site/alias__1763/overview/34596/overview.aspx, null] | [https://www.ezview.wa.gov/DesktopModules/Pictures/PictureView.aspx?tabID=0&alias=1763&ItemID=601&mid=64806&wversion=Staging, null] | 
```