# Five Year Plan Summary by Borough and Capital Categories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/five-year-plan-summary-by-borough-and-capital-categories) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/24nr-gahi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/24nr-gahi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/24nr-gahi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 24nr-gahi |
| Name | Five Year Plan Summary by Borough and Capital Categories |
| Attribution | NYC School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, education |
| Created | 2016-06-02T14:46:59Z |
| Publication Date | 2016-06-02T14:55:05Z |

## Description

Five year plan summary cost by borough and capital category.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | category    | Category    | text      | text        |
| Yes      | series tag     | subcategory | Subcategory | text      | text        |
| Yes      | series tag     | work_type   | Work Type   | text      | text        |
| Yes      | numeric metric | fy15        | FY15        | number    | number      |
| Yes      | numeric metric | fy16        | FY16        | number    | number      |
| Yes      | numeric metric | fy17        | FY17        | number    | number      |
| Yes      | numeric metric | fy18        | FY18        | number    | number      |
| Yes      | numeric metric | fy19        | FY19        | number    | number      |
| Yes      | numeric metric | total       | Total       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:24nr-gahi d:2016-06-02T07:47:20.000Z t:category="State of Good Repair" t:subcategory="New Construction" t:work_type="1. Building Replacement" m:total=0 m:fy15=0 m:fy16=0 m:fy17=0 m:fy18=0 m:fy19=0

series e:24nr-gahi d:2016-06-02T07:47:20.000Z t:category="State of Good Repair" t:subcategory="Major Modernizations and Rehabilitations" t:work_type="1.Full Modernizations" m:total=0 m:fy15=0 m:fy16=0 m:fy17=0 m:fy18=0 m:fy19=0

series e:24nr-gahi d:2016-06-02T07:47:20.000Z t:category="State of Good Repair" t:subcategory="Major Modernizations and Rehabilitations" t:work_type="2.Interior Modernizations" m:total=0.02 m:fy15=0.02 m:fy16=0.01 m:fy17=0 m:fy18=0 m:fy19=0
```

## Meta Commands

```ls
metric m:fy15 p:float l:FY15 t:dataTypeName=number

metric m:fy16 p:float l:FY16 t:dataTypeName=number

metric m:fy17 p:float l:FY17 t:dataTypeName=number

metric m:fy18 p:float l:FY18 t:dataTypeName=number

metric m:fy19 p:float l:FY19 t:dataTypeName=number

metric m:total p:float l:Total t:dataTypeName=number

entity e:24nr-gahi l:"Five Year Plan Summary by Borough and Capital Categories" t:attribution="NYC School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/24nr-gahi

property e:24nr-gahi t:meta.view v:id=24nr-gahi v:category=Education v:averageRating=0 v:name="Five Year Plan Summary by Borough and Capital Categories" v:attribution="NYC School Construction Authority (SCA)"

property e:24nr-gahi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:24nr-gahi t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | category             | subcategory                              | work_type                        | fy15  | fy16   | fy17   | fy18   | fy19   | total  | 
| =========== | ==================== | ======================================== | ================================ | ===== | ====== | ====== | ====== | ====== | ====== | 
| 1464853640  | State of Good Repair | New Construction                         | 1. Building Replacement          | 0     | 0      | 0      | 0      | 0      | 0      | 
| 1464853640  | State of Good Repair | Major Modernizations and Rehabilitations | 1.Full Modernizations            | 0     | 0      | 0      | 0      | 0      | 0      | 
| 1464853640  | State of Good Repair | Major Modernizations and Rehabilitations | 2.Interior Modernizations        | 0.02  | 0.01   | 0      | 0      | 0      | 0.02   | 
| 1464853640  | State of Good Repair | Major Modernizations and Rehabilitations | 3.Exterior Modernizations        | 0.07  | 0.05   | 0      | 0      | 0      | 0.12   | 
| 1464853640  | State of Good Repair | Building Upgrade                         | 1.Asbestos                       | 39.77 | 35     | 35     | 35     | 35     | 179.77 | 
| 1464853640  | State of Good Repair | Building Upgrade                         | 2.Boiler Conversion              | 32.14 | 111.74 | 181.31 | 175.48 | 111.68 | 612.35 | 
| 1464853640  | State of Good Repair | Building Upgrade                         | 3.Climate Control                | 41.86 | 51.35  | 59.16  | 47.17  | 45.1   | 244.64 | 
| 1464853640  | State of Good Repair | Building Upgrade                         | 4.Indoor Air Pollution Abatement | 0     | 0      | 0      | 0      | 0      | 0      | 
| 1464853640  | State of Good Repair | Building Upgrade                         | 5.Kitchen Conversions            | 0     | 0      | 0      | 0      | 0      | 0      | 
| 1464853640  | State of Good Repair | Building Upgrade                         | 6.Low-Voltage Electrical Systems | 61.1  | 31.34  | 21.11  | 10.72  | 23.6   | 147.87 | 
```