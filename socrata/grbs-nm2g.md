# Village Alliance Merchants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/village-alliance-merchants-49b8d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/grbs-nm2g) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/grbs-nm2g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/grbs-nm2g/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | grbs-nm2g |
| Name | Village Alliance Merchants |
| Attribution | Village Alliance |
| Category | Business |
| Tags | merchants, business, businesses, directory, directories |
| Created | 2011-09-30T19:32:35Z |
| Publication Date | 2013-06-21T19:29:20Z |

## Description

A business directory of Village Alliance Merchants. Update Frequency: As needed

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | name        | NAME       | text      | text        |
| Yes      | numeric metric | st_         | ST. #      | number    | number      |
| No       |                | st          | ST         | text      | text        |
| Yes      | series tag     | phone       | PHONE      | text      | text        |
| Yes      | series tag     | none_       | (none)     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = st
```

## Data Commands

```ls
series e:grbs-nm2g d:2011-09-30T12:32:41.000Z t:name="2 Bros Pizza" m:st_=32

series e:grbs-nm2g d:2011-09-30T12:32:41.000Z t:name="2 Bros Pizza" m:st_=36

series e:grbs-nm2g d:2011-09-30T12:32:41.000Z t:name="20/20 Optical" m:st_=57
```

## Meta Commands

```ls
metric m:st_ p:integer l:"ST. #" t:dataTypeName=number

entity e:grbs-nm2g l:"Village Alliance Merchants" t:attribution="Village Alliance" t:url=https://data.cityofnewyork.us/api/views/grbs-nm2g

property e:grbs-nm2g t:meta.view v:id=grbs-nm2g v:category=Business v:averageRating=0 v:name="Village Alliance Merchants" v:attribution="Village Alliance"

property e:grbs-nm2g t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:grbs-nm2g t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | name                                 | st_ | st | phone          | none_ | 
| =========== | ==================================== | === | == | ============== | ===== | 
| 1317385961  | 2 Bros Pizza                         | 32  | NY |                |       | 
| 1317385961  | 2 Bros Pizza                         | 36  | NY |                |       | 
| 1317385961  | 20/20 Optical                        | 57  | NY |                |       | 
| 1317385961  | 6th Avenue News & Tobacco            | 488 | NY |                |       | 
| 1317385961  | 8 Crown Trade Co.                    | 28  | NY |                |       | 
| 1317385961  | 8th Street Parking Corp.             | 11  | NY |                |       | 
| 1317385961  | 8th Street Parking Corp.             | 9   | NY |                |       | 
| 1317385961  | 8th Street Wine Cellar (Lower level) | 28  | NY | (212) 260-9463 |       | 
| 1317385961  | 99 Cents Fresh Pizza                 | 388 | NY |                |       | 
| 1317385961  | AC Gears                             | 69  | NY | (212) 260-2269 |       | 
```