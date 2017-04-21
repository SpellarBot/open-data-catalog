# DSG Monthly rollup

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dsg-monthly-rollup) |
| Metadata | [Link](https://data.seattle.gov/api/views/s5r9-s7xv) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/s5r9-s7xv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/s5r9-s7xv/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | s5r9-s7xv |
| Name | DSG Monthly rollup |
| Category | City Business |
| Created | 2015-07-01T21:05:23Z |
| Publication Date | 2015-08-04T17:10:47Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | time           | creation_date | creation_date | calendar_date | calendar_date |
| No       |                | date_text     | DATE TEXT     | text          | text          |
| Yes      | numeric metric | monthly_total | MONTHLY TOTAL | number        | number        |
| Yes      | numeric metric | monthly       | Yearly        | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_text
```

## Data Commands

```ls
series e:s5r9-s7xv d:2009-12-10T00:00:00.000Z m:monthly_total=1 m:monthly=3

series e:s5r9-s7xv d:2009-11-23T00:00:00.000Z m:monthly_total=2 m:monthly=2

series e:s5r9-s7xv d:2013-01-10T00:00:00.000Z m:monthly_total=5 m:monthly=169
```

## Meta Commands

```ls
metric m:monthly_total p:integer l:"MONTHLY TOTAL" t:dataTypeName=number

metric m:monthly p:integer l:Yearly t:dataTypeName=number

entity e:s5r9-s7xv l:"DSG Monthly rollup" t:url=https://data.seattle.gov/api/views/s5r9-s7xv

property e:s5r9-s7xv t:meta.view v:id=s5r9-s7xv v:category="City Business" v:averageRating=0 v:name="DSG Monthly rollup"

property e:s5r9-s7xv t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:s5r9-s7xv t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| creation_date       | date_text | monthly_total | monthly | 
| =================== | ========= | ============= | ======= | 
| 2009-12-10T00:00:00 | 12/2009   | 1             | 3       | 
| 2009-11-23T00:00:00 | 11/2009   | 2             | 2       | 
| 2013-01-10T00:00:00 | 01/2013   | 5             | 169     | 
| 2013-06-05T00:00:00 | 06/2013   | 18            | 202     | 
| 2015-03-06T00:00:00 | 03/2015   | 42            | 475     | 
| 2011-07-28T00:00:00 | 07/2011   | 1             | 66      | 
| 2014-03-03T00:00:00 | 03/2014   | 13            | 271     | 
| 2013-11-16T00:00:00 | 11/2013   | 2             | 232     | 
| 2014-05-14T00:00:00 | 05/2014   | 6             | 287     | 
| 2014-12-03T00:00:00 | 12/2014   | 29            | 365     | 
```