# City of Colfax: Building Permits February 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-colfax-building-permits-february-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/sefr-g784) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/sefr-g784/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/sefr-g784/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | sefr-g784 |
| Name | City of Colfax: Building Permits February 2016 |
| Attribution | City of Colfax, Washington |
| Category | Economics |
| Tags | colfax, building, permit, building permit, 2016 |
| Created | 2016-03-15T18:03:43Z |
| Publication Date | 2016-03-15T18:07:06Z |

## Description

This dataset has building permits issued by the City during February 2016

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | permit_no        | Permit No.       | text          | text          |
| Yes      | time           | issue_date       | Issue Date       | calendar_date | calendar_date |
| Yes      | numeric metric | project_cost     | Project Cost     | money         | money         |
| Yes      | series tag     | owner            | Owner            | text          | text          |
| No       |                | project_address  | Project Address  | text          | text          |
| Yes      | series tag     | work_description | Work Description | text          | text          |
| Yes      | series tag     | type             | Type             | text          | text          |
| Yes      | numeric metric | permit_fee       | Permit Fee       | money         | money         |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address
```

## Data Commands

```ls
series e:sefr-g784 d:2016-02-04T00:00:00.000Z t:owner="Marshall Gibbs" t:permit_no=16-06 t:type=Building t:work_description="Framing work/Alteration" m:project_cost=20000 m:permit_fee=357.88

series e:sefr-g784 d:2016-02-05T00:00:00.000Z t:owner="Gary & Janis Behymer" t:permit_no=16-07 t:type=Mechanical t:work_description="Change out gas furnace" m:project_cost=4322.78 m:permit_fee=39.8

series e:sefr-g784 d:2016-02-05T00:00:00.000Z t:owner="Jerry & Marsha Binder" t:permit_no=16-08 t:type=Mechanical t:work_description="Gas Furnace" m:project_cost=3222.14 m:permit_fee=39.8
```

## Meta Commands

```ls
metric m:project_cost p:double l:"Project Cost" t:dataTypeName=money

metric m:permit_fee p:double l:"Permit Fee" t:dataTypeName=money

entity e:sefr-g784 l:"City of Colfax: Building Permits February 2016" t:attribution="City of Colfax, Washington" t:url=https://data.wa.gov/api/views/sefr-g784

property e:sefr-g784 t:meta.view v:id=sefr-g784 v:category=Economics v:attributionLink=http://www.colfaxwa.org v:averageRating=0 v:name="City of Colfax: Building Permits February 2016" v:attribution="City of Colfax, Washington"

property e:sefr-g784 t:meta.view.license v:name="Public Domain"

property e:sefr-g784 t:meta.view.owner v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:displayName="Mike Rizzitiello"

property e:sefr-g784 t:meta.view.tableauthor v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:roleName=editor v:displayName="Mike Rizzitiello"
```

## Top Records

```ls
| permit_no | issue_date          | project_cost | owner                 | project_address           | work_description          | type       | permit_fee | 
| ========= | =================== | ============ | ===================== | ========================= | ========================= | ========== | ========== | 
| 16-06     | 2016-02-04T00:00:00 | 20000.00     | Marshall Gibbs        | S 204 Main Street         | Framing work/Alteration   | Building   | 357.88     | 
| 16-07     | 2016-02-05T00:00:00 | 4322.78      | Gary & Janis Behymer  | 612 E Valleyview          | Change out gas furnace    | Mechanical | 39.80      | 
| 16-08     | 2016-02-05T00:00:00 | 3222.14      | Jerry & Marsha Binder | 802 E Southview           | Gas Furnace               | Mechanical | 39.80      | 
| 16-09     | 2016-02-11T00:00:00 | 6780.0       | John & Brook Rohner   | 1813 1/2 North Oak Street | tub to shower conversion  | Plumbing   | 31.50      | 
| 16-10     | 2016-02-12T00:00:00 | 3950.0       | Tom Welch             | 208 E Cooper              | Install Gas Furnace       | Mechanical | 39.80      | 
| 16-11     | 2016-02-18T00:00:00 | 7460.0       | Estate of Bonnie Knox | 819 E Valleyview          | Change gas furnace & AC   | Mechanical | 53.50      | 
| 16-12     | 2016-02-19T00:00:00 | 50000.0      | B&S Ventures          | 310 E James               | Repair Roof, porch, walls | Building   | 648.25     | 
| 16-13     | 2016-02-22T00:00:00 | 3806.0       | Jon Webber            | 703 W Orchard             | Install Gas Furnace       | Mechanical | 39.80      | 
| 16-14     | 2016-02-22T00:00:00 | 30000.0      | CJ Young              | 1812 N Oak                | New Shop/Garage           | Building   | 446.25     | 
| 16-15     | 2016-02-22T00:00:00 | 3000.0       | Felipe Guitron        | 205 N Main                | Replace Sign              | Building   | 49.50      | 
```