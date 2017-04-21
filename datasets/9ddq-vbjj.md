# Cost Summary By Citywide Category

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cost-summary-by-citywide-category) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9ddq-vbjj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9ddq-vbjj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9ddq-vbjj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9ddq-vbjj |
| Name | Cost Summary By Citywide Category |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, school, construction, plan, summary, cost |
| Created | 2017-01-31T14:54:32Z |
| Publication Date | 2017-01-31T15:02:24Z |

## Description

Five year plan summary cost by citywide category.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | program_category | Program Category | text      | text        |
| Yes      | series tag     | code             | Code             | text      | text        |
| Yes      | numeric metric | fy15             | FY15             | number    | number      |
| Yes      | numeric metric | fy16             | FY16             | number    | number      |
| Yes      | numeric metric | fy17             | FY17             | number    | number      |
| Yes      | numeric metric | fy18             | FY18             | number    | number      |
| Yes      | numeric metric | fy19             | FY19             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9ddq-vbjj d:2017-01-31T14:54:35.000Z t:program_category=ASBESTOS t:code=1C1 m:fy15=39.77 m:fy16=36.7 m:fy17=35 m:fy18=35 m:fy19=35

series e:9ddq-vbjj d:2017-01-31T14:54:35.000Z t:program_category="KITCHEN CONVERSIONS" t:code=1C5 m:fy15=0 m:fy16=0 m:fy17=0 m:fy18=0 m:fy19=0

series e:9ddq-vbjj d:2017-01-31T14:54:35.000Z t:program_category="LEAD PAINT ABATEMENT" t:code=1C12 m:fy15=1.1 m:fy16=1.19 m:fy17=3 m:fy18=3 m:fy19=3
```

## Meta Commands

```ls
metric m:fy15 p:float l:FY15 d:"Dollars allocated (in millions) to this Program Category for Fiscal Year 2015." t:dataTypeName=number

metric m:fy16 p:float l:FY16 d:"Dollars allocated (in millions) to this Program Category for Fiscal Year 2016." t:dataTypeName=number

metric m:fy17 p:float l:FY17 d:"Dollars allocated (in millions) to this Program Category for Fiscal Year 2017." t:dataTypeName=number

metric m:fy18 p:float l:FY18 d:"Dollars allocated (in millions) to this Program Category for Fiscal Year 2018." t:dataTypeName=number

metric m:fy19 p:float l:FY19 d:"Dollars allocated (in millions) to this Program Category for Fiscal Year 2019." t:dataTypeName=number

entity e:9ddq-vbjj l:"Cost Summary By Citywide Category" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/9ddq-vbjj

property e:9ddq-vbjj t:meta.view v:id=9ddq-vbjj v:category=Education v:averageRating=0 v:name="Cost Summary By Citywide Category" v:attribution="School Construction Authority (SCA)"

property e:9ddq-vbjj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9ddq-vbjj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | program_category              | code | fy15   | fy16   | fy17   | fy18   | fy19   | 
| =========== | ============================= | ==== | ====== | ====== | ====== | ====== | ====== | 
| 1485874475  | ASBESTOS                      | 1C1  | 39.77  | 36.7   | 35     | 35     | 35     | 
| 1485874475  | KITCHEN CONVERSIONS           | 1C5  | 0      | 0      | 0      | 0      | 0      | 
| 1485874475  | LEAD PAINT ABATEMENT          | 1C12 | 1.1    | 1.19   | 3      | 3      | 3      | 
| 1485874475  | KITCHEN AREAS                 | 1E15 | 3.07   | 4.7    | 3.33   | 1.78   | 2      | 
| 1485874475  | CIP RESPONSE                  | 1E20 | 0      | 0      | 0      | 0      | 0      | 
| 1485874475  | TRANSPORTABLES                | 2A4  | 0.01   | 0      | 0.09   | 0      | 0      | 
| 1485874475  | PRE-KINDERGARTEN INITIATIVE   | 2A8  | 261.81 | 275.39 | 213.93 | 38.07  | 10.79  | 
| 1485874475  | TECHNOLOGY                    | 3A1  | 62.2   | 11.7   | 191.96 | 192.06 | 192.08 | 
| 1485874475  | ROOM CONVERSIONS/PARTITIONING | 3A2  | 25.26  | 71.06  | 87.77  | 50.71  | 41     | 
| 1485874475  | ACCESSIBILITY                 | 3A3  | 3.14   | 24.19  | 37.62  | 27.25  | 35.36  | 
```