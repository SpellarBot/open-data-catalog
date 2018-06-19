# Choose Maryland: Compare Metros - Education

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-metros-education) |
| Metadata | [Link](https://data.maryland.gov/api/views/tybw-nzqj) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/tybw-nzqj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/tybw-nzqj/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | tybw-nzqj |
| Name | Choose Maryland: Compare Metros - Education |
| Attribution | Maryland Department of Commerce |
| Category | Education |
| Tags | maryland, baltimore, metro, compare, education, degree, bachelor, high school |
| Created | 2013-08-22T15:08:42Z |
| Publication Date | 2016-09-16T18:02:34Z |

## Description

Educational attainment rates - high school diploma and bachelor's degree.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                             | Data Type | Render Type |
| ======== | ============== | ====================== | ================================ | ========= | =========== |
| No       | time           | :updated_at            | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | metro                  | Metro                            | text      | text        |
| Yes      | numeric metric | bachelors_attainment   | Bachelor's Degree Attainment (%) | percent   | percent     |
| Yes      | numeric metric | high_school_attainment | High School Attainment (%)       | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tybw-nzqj d:2016-09-16T18:02:15.000Z t:metro="Atlanta metro" m:high_school_attainment=88.7 m:bachelors_attainment=37

series e:tybw-nzqj d:2016-09-16T18:02:15.000Z t:metro="Austin, TX metro" m:high_school_attainment=89.2 m:bachelors_attainment=42.6

series e:tybw-nzqj d:2016-09-16T18:02:15.000Z t:metro="Baltimore metro" m:high_school_attainment=90.4 m:bachelors_attainment=38.6
```

## Meta Commands

```ls
metric m:bachelors_attainment p:float l:"Bachelor's Degree Attainment (%)" t:dataTypeName=percent

metric m:high_school_attainment p:float l:"High School Attainment (%)" t:dataTypeName=percent

entity e:tybw-nzqj l:"Choose Maryland:  Compare Metros - Education" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/tybw-nzqj

property e:tybw-nzqj t:meta.view v:id=tybw-nzqj v:category=Education v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Metros - Education" v:attribution="Maryland Department of Commerce"

property e:tybw-nzqj t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:tybw-nzqj t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | metro               | bachelors_attainment | high_school_attainment | 
| =========== | =================== | ==================== | ====================== | 
| 1474048935  | Atlanta metro       | 37.0                 | 88.7                   | 
| 1474048935  | Austin, TX metro    | 42.6                 | 89.2                   | 
| 1474048935  | Baltimore metro     | 38.6                 | 90.4                   | 
| 1474048935  | Birmingham metro    | 28.6                 | 88.0                   | 
| 1474048935  | Boston metro        | 46.0                 | 91.4                   | 
| 1474048935  | Buffalo metro       | 30.3                 | 90.5                   | 
| 1474048935  | Charlotte metro     | 33.5                 | 87.9                   | 
| 1474048935  | Chicago metro       | 36.0                 | 87.9                   | 
| 1474048935  | Cincinnati metro    | 32.1                 | 90.5                   | 
| 1474048935  | Cleveland, OH metro | 29.4                 | 89.7                   | 
```