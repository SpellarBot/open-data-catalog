# City of Colfax: Building Permits January 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-colfax-building-permits-january-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/iqrw-294q) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/iqrw-294q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/iqrw-294q/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | iqrw-294q |
| Name | City of Colfax: Building Permits January 2016 |
| Attribution | City of Colfax, Washington |
| Category | Economics |
| Tags | colfax, building permits, permits, building, january, 2016 |
| Created | 2016-03-15T17:59:37Z |
| Publication Date | 2016-03-15T18:01:18Z |

## Description

This dataset has building permits issued during the month of January 2016.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | time           | permit_no        | Permit No.       | calendar_date | calendar_date |
| No       |                | issue_date       | Issue Date       | calendar_date | calendar_date |
| Yes      | numeric metric | project_cost     | Project Cost     | money         | money         |
| Yes      | series tag     | owner            | Owner            | text          | text          |
| No       |                | project_address  | Project Address  | text          | text          |
| Yes      | series tag     | work_description | Work Description | text          | text          |
| Yes      | series tag     | type             | Type             | text          | text          |
| Yes      | numeric metric | permit_fee       | Permit Fee       | money         | money         |
```

## Time Field

```ls
Value = permit_no
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issue_date,project_address
```

## Data Commands

```ls
series e:iqrw-294q d:0016-01-01T00:00:00.000Z t:owner="Rolling Hills Eyecare" t:type=Mechanical t:work_description="Change out gas furnace" m:project_cost=3824.7 m:permit_fee=38.3

series e:iqrw-294q d:0016-02-01T00:00:00.000Z t:owner="Patricia Pfaff" t:type=Building t:work_description=remodel m:project_cost=33000 m:permit_fee=476.55

series e:iqrw-294q d:0016-04-01T00:00:00.000Z t:owner="Linda and Tony Line" t:type=Building t:work_description="roof repair" m:project_cost=6000 m:permit_fee=229.75
```

## Meta Commands

```ls
metric m:project_cost p:double l:"Project Cost" t:dataTypeName=money

metric m:permit_fee p:double l:"Permit Fee" t:dataTypeName=money

entity e:iqrw-294q l:"City of Colfax: Building Permits January 2016" t:attribution="City of Colfax, Washington" t:url=https://data.wa.gov/api/views/iqrw-294q

property e:iqrw-294q t:meta.view v:id=iqrw-294q v:category=Economics v:attributionLink=http://www.colfaxwa.org v:averageRating=0 v:name="City of Colfax: Building Permits January 2016" v:attribution="City of Colfax, Washington"

property e:iqrw-294q t:meta.view.license v:name="Public Domain"

property e:iqrw-294q t:meta.view.owner v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:displayName="Mike Rizzitiello"

property e:iqrw-294q t:meta.view.tableauthor v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:roleName=editor v:displayName="Mike Rizzitiello"
```

## Top Records

```ls
| permit_no           | issue_date          | project_cost | owner                             | project_address   | work_description       | type       | permit_fee | 
| =================== | =================== | ============ | ================================= | ================= | ====================== | ========== | ========== | 
| 0016-01-01T00:00:00 | 2016-01-04T00:00:00 | 3824.7       | Rolling Hills Eyecare             | 120 N Main Street | Change out gas furnace | Mechanical | 38.30      | 
| 0016-02-01T00:00:00 | 2016-01-12T00:00:00 | 33000.0      | Patricia Pfaff                    | 102 Mill Street   | remodel                | Building   | 476.55     | 
| 0016-04-01T00:00:00 | 2016-01-21T00:00:00 | 6000.0       | Linda and Tony Line               | 627 N Perkins     | roof repair            | Building   | 229.75     | 
| 0016-05-01T00:00:00 | 2016-01-27T00:00:00 | 4718.0       | Whitman County Historical Society | 623 N Perkins     | Change out gas furnace | Mechanical | 39.80      | 
```