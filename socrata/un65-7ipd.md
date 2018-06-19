# MVA Vehicle Sales Counts by Month for CY 2002 - 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mva-vehicle-sales-counts-by-month-for-cy-2002-2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/un65-7ipd) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/un65-7ipd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/un65-7ipd/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | un65-7ipd |
| Name | MVA Vehicle Sales Counts by Month for CY 2002 - 2016 |
| Attribution | Motor Vehicle Administration |
| Category | Transportation |
| Tags | mva, vehicle, car, auto, trucks, sales, new, used, preowned, maryland mva |
| Created | 2015-11-20T13:39:16Z |
| Publication Date | 2016-12-23T18:35:37Z |

## Description

The number of new and used vehicles and the sales dollars respectively sold by month. Data as of October 2016

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       |                | year             | Year             | number    | text        |
| No       |                | month            | Month            | text      | text        |
| Yes      | numeric metric | new              | New              | number    | number      |
| Yes      | numeric metric | used             | Used             | number    | number      |
| Yes      | numeric metric | total_sales_new  | Total Sales New  | money     | money       |
| Yes      | numeric metric | total_sales_used | Total Sales Used | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:un65-7ipd d:2002-01-01T00:00:00.000Z m:new=31106 m:used=49927 m:total_sales_used=386481929 m:total_sales_new=755015820

series e:un65-7ipd d:2002-02-01T00:00:00.000Z m:new=27520 m:used=50982 m:total_sales_used=361353242 m:total_sales_new=664454223

series e:un65-7ipd d:2002-03-01T00:00:00.000Z m:new=34225 m:used=58794 m:total_sales_used=419385387 m:total_sales_new=805666244
```

## Meta Commands

```ls
metric m:new p:integer l:New t:dataTypeName=number

metric m:used p:integer l:Used t:dataTypeName=number

metric m:total_sales_new p:integer l:"Total Sales New" t:dataTypeName=money

metric m:total_sales_used p:integer l:"Total Sales Used" t:dataTypeName=money

entity e:un65-7ipd l:"MVA Vehicle Sales Counts by Month for CY 2002 - 2016" t:attribution="Motor Vehicle Administration" t:url=https://data.maryland.gov/api/views/un65-7ipd

property e:un65-7ipd t:meta.view v:id=un65-7ipd v:category=Transportation v:attributionLink=http://www.mva.maryland.gov/ v:averageRating=0 v:name="MVA Vehicle Sales Counts by Month for CY 2002 - 2016" v:attribution="Motor Vehicle Administration"

property e:un65-7ipd t:meta.view.owner v:id=pvrd-fajs v:screenName="Juanita Gray" v:displayName="Juanita Gray"

property e:un65-7ipd t:meta.view.tableauthor v:id=pvrd-fajs v:screenName="Juanita Gray" v:roleName=editor v:displayName="Juanita Gray"
```

## Top Records

```ls
| year | month | new   | used  | total_sales_new | total_sales_used | 
| ==== | ===== | ===== | ===== | =============== | ================ | 
| 2002 | JAN   | 31106 | 49927 | 755015820       | 386481929        | 
| 2002 | FEB   | 27520 | 50982 | 664454223       | 361353242        | 
| 2002 | MAR   | 34225 | 58794 | 805666244       | 419385387        | 
| 2002 | APR   | 36452 | 59817 | 846368297       | 433061150        | 
| 2002 | MAY   | 37359 | 60577 | 855005784       | 442569410        | 
| 2002 | JUN   | 36348 | 55415 | 830251613       | 414731166        | 
| 2002 | JUL   | 30367 | 55235 | 700530891       | 384673023        | 
| 2002 | AUG   | 38965 | 60310 | 934484212       | 455453720        | 
| 2002 | SEP   | 39740 | 55485 | 950502055       | 432112270        | 
| 2002 | OCT   | 35276 | 58020 | 865326154       | 456738532        | 
```