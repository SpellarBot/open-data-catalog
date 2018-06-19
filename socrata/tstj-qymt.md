# Hotel/Motel Tax Collected by Jurisdiction and Quarter

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hotel-motel-tax-collected-by-jurisdiction-and-quarter) |
| Metadata | [Link](https://data.iowa.gov/api/views/tstj-qymt) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tstj-qymt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tstj-qymt/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tstj-qymt |
| Name | Hotel/Motel Tax Collected by Jurisdiction and Quarter |
| Attribution | Iowa Department of Revenue |
| Category | Economy |
| Tags | taxes, hotel, motel, inn, public lodging house, rooming house, tourist court, bed-and-breakfast |
| Created | 2015-04-09T16:29:53Z |
| Publication Date | 2017-01-09T18:47:23Z |

## Description

This dataset provides information on hotel/motel taxes collected by jurisdiction, tax year and quarter starting with tax year 2000.  The hotel/motel tax is imposed on the gross receipts from the renting of sleeping rooms, apartments, or sleeping quarters in any: hotel, motel, inn, public lodging house, rooming house, tourist court, bed-and-breakfast, or in any place where sleeping accommodations are furnished to transient guests
...when contracted for periods of 31 consecutive days or less.  Contracts for periods of more than 31 consecutive days are exempt. To qualify, the renter must contract to rent for a single period of more than 31 days and cannot accumulate these days.  The tax base must include the entire cost related to the rental of the room. If a person is charged for other items when renting a room, the charges must be stated separately or the entire amount will be subject to the hotel/motel tax.  Hotel/motel tax is reported and remitted with the quarterly sales tax to the Iowa Department of Revenue.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | series tag     | jurisdiction | Jurisdiction | text          | text          |
| Yes      | time           | effective    | Effective    | calendar_date | calendar_date |
| No       |                | tax_year     | Tax Year     | number        | number        |
| Yes      | numeric metric | annual_total | Annual Total | money         | money         |
| No       |                | 4th_quarter  | 4th Quarter  | money         | money         |
| No       |                | 3rd_quarter  | 3rd Quarter  | money         | money         |
| No       |                | 2nd_quarter  | 2nd Quarter  | money         | money         |
| No       |                | 1st_quarter  | 1st Quarter  | money         | money         |
```

## Time Field

```ls
Value = effective
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = 4th_quarter,3rd_quarter,2nd_quarter,1st_quarter,tax_year
```

## Data Commands

```ls
series e:tstj-qymt d:1998-07-01T00:00:00.000Z t:jurisdiction=Adair m:annual_total=28865.45

series e:tstj-qymt d:2015-01-01T00:00:00.000Z t:jurisdiction=Albia m:annual_total=30104.62

series e:tstj-qymt d:2003-01-01T00:00:00.000Z t:jurisdiction=Algona m:annual_total=140209.16
```

## Meta Commands

```ls
metric m:annual_total p:double l:"Annual Total" d:"Total hotel/motel taxes collected for tax year." t:dataTypeName=money

entity e:tstj-qymt l:"Hotel/Motel Tax Collected by Jurisdiction and Quarter" t:attribution="Iowa Department of Revenue" t:url=https://data.iowa.gov/api/views/tstj-qymt

property e:tstj-qymt t:meta.view v:id=tstj-qymt v:category=Economy v:attributionLink=https://tax.iowa.gov/report/Hotel-Motel v:averageRating=0 v:name="Hotel/Motel Tax Collected by Jurisdiction and Quarter" v:attribution="Iowa Department of Revenue"

property e:tstj-qymt t:meta.view.license v:name="Public Domain"

property e:tstj-qymt t:meta.view.owner v:id=y22p-i8y2 v:profileImageUrlMedium=/api/users/y22p-i8y2/profile_images/THUMB v:profileImageUrlLarge=/api/users/y22p-i8y2/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/y22p-i8y2/profile_images/TINY v:displayName="Revenue, Research and Analysis"

property e:tstj-qymt t:meta.view.tableauthor v:id=y22p-i8y2 v:profileImageUrlMedium=/api/users/y22p-i8y2/profile_images/THUMB v:profileImageUrlLarge=/api/users/y22p-i8y2/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/y22p-i8y2/profile_images/TINY v:roleName=editor v:displayName="Revenue, Research and Analysis"
```

## Top Records

```ls
| jurisdiction     | effective           | tax_year | annual_total | 4th_quarter | 3rd_quarter | 2nd_quarter | 1st_quarter | 
| ================ | =================== | ======== | ============ | =========== | =========== | =========== | =========== | 
| Adair            | 1998-07-01T00:00:00 | 2016     | 28865.45     | 8220.45     | 3923.55     | 5428.55     | 11292.90    | 
| Albia            | 2015-01-01T00:00:00 | 2016     | 30104.62     | 12146.89    | 721.49      | 6216.84     | 11019.40    | 
| Algona           | 2003-01-01T00:00:00 | 2016     | 140209.16    | 36390.97    | 21838.04    | 30344.09    | 51636.06    | 
| Altoona          | 1980-04-01T00:00:00 | 2016     | 1052306.29   | 293771.59   | 212007.46   | 169796.13   | 376731.11   | 
| Ames             | 1988-04-01T00:00:00 | 2016     | 2297230.95   | 646658.39   | 478204.79   | 483966.07   | 688401.70   | 
| Anamosa          | 2001-01-01T00:00:00 | 2016     | 77303.59     | 23682.05    | 13099.24    | 17337.25    | 23185.05    | 
| Ankeny           | 1979-04-01T00:00:00 | 2016     | 1396167.36   | 420868.63   | 298588.36   | 258398.70   | 418311.67   | 
| Appanoose County | 2004-10-01T00:00:00 | 2016     | 256869.68    | 68287.28    | 36523.27    | 46884.18    | 105174.95   | 
| Arnolds Park     | 1995-01-01T00:00:00 | 2016     | 347063.00    | 83677.35    | 21677.60    | 20370.30    | 221337.75   | 
| Atlantic         | 2011-01-01T00:00:00 | 2016     | 59449.44     | 16241.80    | 9192.08     | 11463.56    | 22552.00    | 
```