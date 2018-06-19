# Licensed Automobile Dealers And Repairers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-automobile-dealers-and-repairers) |
| Metadata | [Link](https://data.ct.gov/api/views/apne-w8c6) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/apne-w8c6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/apne-w8c6/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | apne-w8c6 |
| Name | Licensed Automobile Dealers And Repairers |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv, dealer, repair, automobile |
| Created | 2014-03-29T20:51:12Z |
| Publication Date | 2014-03-30T14:50:32Z |

## Description

Listing of licensed automobile dealers and repairers

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | business_name    | Business Name    | text      | text        |
| No       |             | business_address | Business Address | text      | text        |
| Yes      | series tag  | note             | Note             | text      | text        |
| Yes      | series tag  | zip_code         | Zip Code         | text      | text        |
| Yes      | series tag  | license_type     | License Type     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = business_address
```

## Data Commands

```ls
series e:apne-w8c6 d:2014-03-29T14:47:12.000Z t:business_name="FRANKS LLC" t:license_type="USED DEALER" t:zip_code=06401 m:row_number.apne-w8c6=1

series e:apne-w8c6 d:2014-03-29T14:47:12.000Z t:business_name="ANDOVER AUTO PARTS INC" t:license_type="USED DEALER" t:zip_code=06232 m:row_number.apne-w8c6=2

series e:apne-w8c6 d:2014-03-29T14:47:19.000Z t:business_name="JOSEPH M BROWN" t:license_type="USED DEALER" t:zip_code=06401 m:row_number.apne-w8c6=3
```

## Meta Commands

```ls
metric m:row_number.apne-w8c6 p:long l:"Row Number"

entity e:apne-w8c6 l:"Licensed Automobile Dealers And Repairers" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/apne-w8c6

property e:apne-w8c6 t:meta.view v:id=apne-w8c6 v:category=Transportation v:attributionLink=http://www.ct.gov/dmv v:averageRating=0 v:name="Licensed Automobile Dealers And Repairers" v:attribution="Department of Motor Vehicles"

property e:apne-w8c6 t:meta.view.license v:name="Public Domain"

property e:apne-w8c6 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:apne-w8c6 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | business_name                                   | business_address | note | zip_code | license_type | 
| =========== | =============================================== | ================ | ==== | ======== | ============ | 
| 1396104432  | FRANKS LLC                                      | 142 WAKELEE AVE  |      | 06401    | USED DEALER  | 
| 1396104432  | ANDOVER AUTO PARTS INC                          | 497 ROUTE 6      |      | 06232    | USED DEALER  | 
| 1396104439  | JOSEPH M BROWN                                  | 66 PERSHING DR   |      | 06401    | USED DEALER  | 
| 1396104443  | GENERAL MUFFLER & AUTO SUPPLY INC               | 670 MAIN ST      |      | 06401    | USED DEALER  | 
| 1396104444  | AUTO REPAIRS UNLIMITED LLC                      | 535 MAIN ST      |      | 06401    | USED DEALER  | 
| 1396104446  | CT DISCOUNT MUFFLER AND BRAKE USED CAR SALE LLC | 421 EAST MAIN ST |      | 06401    | USED DEALER  | 
| 1396104476  | ANDOVER AUTO PARTS INC                          | 497 ROUTE 6      |      | 06232    | RECYCLER     | 
| 1396104482  | RE NU AUTO SALES AND SERVICE INC                | 33 RIGGS ST      |      | 06401    | USED DEALER  | 
| 1396104482  | RIVERVIEW SUPER SERVICE INC                     | 680 MAIN ST      |      | 06401    | USED DEALER  | 
| 1396104491  | JES MOTORS LLC                                  | 133 WAKELEE AVE  |      | 06401    | USED DEALER  | 
```