# City of Colfax: 2015 Building Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-colfax-2015-building-permits) |
| Metadata | [Link](https://data.wa.gov/api/views/f74k-9nzv) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/f74k-9nzv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/f74k-9nzv/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | f74k-9nzv |
| Name | City of Colfax: 2015 Building Permits |
| Attribution | City of Colfax, Washington |
| Category | Economics |
| Tags | building, permits, colfax, 2015 |
| Created | 2015-04-11T02:30:53Z |
| Publication Date | 2015-04-11T02:33:07Z |

## Description

This dataset consists of all building permits recorded thus far in the City of Colfax, Washington.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | permit_no        | Permit No.       | text          | text          |
| Yes      | time           | issue_date       | Issue Date       | calendar_date | calendar_date |
| Yes      | numeric metric | project_cost     | Project Cost     | money         | money         |
| Yes      | series tag     | owner            | Owner            | text          | text          |
| Yes      | series tag     | work_description | Work Description | text          | text          |
| Yes      | numeric metric | permit_fee       | Permit Fee       | money         | money         |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:f74k-9nzv d:2015-01-26T00:00:00.000Z t:owner="Cari Brenne" t:permit_no=15-04 t:work_description="Plumbing New Residence" m:permit_fee=154

series e:f74k-9nzv d:2015-03-04T00:00:00.000Z t:owner="Carl Brenne" t:permit_no=15-14 t:work_description="Mechanical Permit" m:permit_fee=77.9

series e:f74k-9nzv d:2015-03-19T00:00:00.000Z t:owner="Robert Hauser" t:permit_no=15-25 t:work_description="Mechanical Permit" m:permit_fee=95.9
```

## Meta Commands

```ls
metric m:project_cost p:double l:"Project Cost" t:dataTypeName=money

metric m:permit_fee p:double l:"Permit Fee" t:dataTypeName=money

entity e:f74k-9nzv l:"City of Colfax: 2015 Building Permits" t:attribution="City of Colfax, Washington" t:url=https://data.wa.gov/api/views/f74k-9nzv

property e:f74k-9nzv t:meta.view v:id=f74k-9nzv v:category=Economics v:attributionLink=http://www.Colfaxwa.org v:averageRating=0 v:name="City of Colfax: 2015 Building Permits" v:attribution="City of Colfax, Washington"

property e:f74k-9nzv t:meta.view.license v:name="Public Domain"

property e:f74k-9nzv t:meta.view.owner v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:displayName="Mike Rizzitiello"

property e:f74k-9nzv t:meta.view.tableauthor v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:roleName=editor v:displayName="Mike Rizzitiello"
```

## Top Records

```ls
| permit_no | issue_date          | project_cost | owner               | work_description          | permit_fee | 
| ========= | =================== | ============ | =================== | ========================= | ========== | 
| 15-01     |                     |              | Whitman County      |                           |            | 
| 15-04     | 2015-01-26T00:00:00 |              | Cari Brenne         | Plumbing New Residence    | 154.0      | 
| 15-14     | 2015-03-04T00:00:00 |              | Carl Brenne         | Mechanical Permit         | 77.9       | 
| 15-25     | 2015-03-19T00:00:00 |              | Robert Hauser       | Mechanical Permit         | 95.9       | 
| 15-08     | 2015-02-17T00:00:00 |              | Ruth Heisler        | Sewer Line                | 27.0       | 
| 15-09     | 2015-02-17T00:00:00 |              | Bernice Hilty       | Water Service Line        | 27.0       | 
| 15-19     | 2015-03-10T00:00:00 |              | Jonathan Krause     | Remodel Bathroom          | 55.0       | 
| 15-30     | 2015-04-08T00:00:00 |              | Scott Ackerman      | Grading Permit            | 124.5      | 
| 15-22     | 2015-03-17T00:00:00 | 22800.0      | Warwick Properties  | Gas/Electric Package Unit | 55.7       | 
| 15-20     | 2015-03-11T00:00:00 |              | Ackerman Apartments | Gas Furnace               | 38.3       | 
```