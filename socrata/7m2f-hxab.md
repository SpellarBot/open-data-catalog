# City of Colfax: Vendor Log March 7th, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-colfax-vendor-log-march-7th-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/7m2f-hxab) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/7m2f-hxab/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/7m2f-hxab/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 7m2f-hxab |
| Name | City of Colfax: Vendor Log March 7th, 2016 |
| Attribution | City of Colfax, Washington |
| Category | Economics |
| Tags | colfax, finance, vendor, accounts payable |
| Created | 2016-03-15T17:54:07Z |
| Publication Date | 2016-03-15T17:55:33Z |

## Description

This dataset has all vendors paid between February 17th and March 7th, 2016.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | numeric metric | number     | Number     | number        | number        |
| Yes      | series tag     | name       | Name       | text          | text          |
| Yes      | time           | print_date | Print Date | calendar_date | calendar_date |
| Yes      | numeric metric | amount     | Amount     | money         | money         |
```

## Time Field

```ls
Value = print_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7m2f-hxab d:2016-03-01T00:00:00.000Z t:name="U.S. Postal Service" m:amount=341.34 m:number=1309

series e:7m2f-hxab d:2016-03-03T00:00:00.000Z t:name="WSDA Pesticide Management Division" m:amount=174 m:number=1310

series e:7m2f-hxab d:2016-03-07T00:00:00.000Z t:name="Ace Hardware" m:amount=223.54 m:number=1311
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

metric m:amount p:double l:Amount t:dataTypeName=money

entity e:7m2f-hxab l:"City of Colfax: Vendor Log March 7th, 2016" t:attribution="City of Colfax, Washington" t:url=https://data.wa.gov/api/views/7m2f-hxab

property e:7m2f-hxab t:meta.view v:id=7m2f-hxab v:category=Economics v:attributionLink=http://www.colfaxwa.org v:averageRating=0 v:name="City of Colfax: Vendor Log March 7th, 2016" v:attribution="City of Colfax, Washington"

property e:7m2f-hxab t:meta.view.license v:name="Public Domain"

property e:7m2f-hxab t:meta.view.owner v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:displayName="Mike Rizzitiello"

property e:7m2f-hxab t:meta.view.tableauthor v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:roleName=editor v:displayName="Mike Rizzitiello"
```

## Top Records

```ls
| number | name                                | print_date          | amount   | 
| ====== | =================================== | =================== | ======== | 
|        | 9968756016                          |                     |          | 
|        |                                     |                     |          | 
| 1309   | U.S. Postal Service                 | 2016-03-01T00:00:00 | 341.34   | 
| 1310   | WSDA Pesticide Management Division  | 2016-03-03T00:00:00 | 174.00   | 
| 1311   | Ace Hardware                        | 2016-03-07T00:00:00 | 223.54   | 
| 1312   | Anatek Labs - Spokane               | 2016-03-07T00:00:00 | 80.00    | 
| 1313   | Avista Utilities                    | 2016-03-07T00:00:00 | 14016.38 | 
| 1314   | Blumenthal Uniform & Equipment      | 2016-03-07T00:00:00 | 27.20    | 
| 1315   | Canon Solutions America             | 2016-03-07T00:00:00 | 476.51   | 
| 1316   | Carpenter, McGuire and DeWulf, P.S. | 2016-03-07T00:00:00 | 187.50   | 
```