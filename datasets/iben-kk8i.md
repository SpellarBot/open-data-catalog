# RAMS - Traffic ATR Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rams-traffic-atr-location) |
| Metadata | [Link](https://data.iowa.gov/api/views/iben-kk8i) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/iben-kk8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/iben-kk8i/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | iben-kk8i |
| Name | RAMS - Traffic ATR Location |
| Attribution | Iowa Department of Transportation - Office of Research & Analytics |
| Category | Transportation & Utilities |
| Tags | iowa dot, iowa department of transportation, rams, traffic atr location, asset, inventory |
| Created | 2016-12-06T20:47:40Z |
| Publication Date | 2016-12-06T20:49:42Z |

## Description

Traffic ATR Location data maintained inside the Roadway Asset Management System (RAMS).

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | event_id             | EVENT_ID             | text      | text        |
| Yes      | series tag     | route_id             | ROUTE_ID             | text      | text        |
| Yes      | numeric metric | measure              | MEASURE              | number    | number      |
| Yes      | time           | business_date        | BUSINESS_DATE        | date      | date        |
| No       |                | effective_start_date | EFFECTIVE_START_DATE | date      | date        |
| No       |                | effective_end_date   | EFFECTIVE_END_DATE   | date      | date        |
| Yes      | series tag     | user_create          | USER_CREATE          | text      | text        |
| Yes      | series tag     | user_mod             | USER_MOD             | text      | text        |
| No       |                | system_create_date   | SYSTEM_CREATE_DATE   | date      | date        |
| No       |                | system_mod_date      | SYSTEM_MOD_DATE      | date      | date        |
| Yes      | series tag     | atr_number           | ATR_NUMBER           | text      | number      |
| Yes      | series tag     | locerror             | LOCERROR             | text      | text        |
| Yes      | series tag     | objectid             | OBJECTID             | text      | number      |
```

## Time Field

```ls
Value = business_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = effective_start_date,effective_end_date,system_create_date,system_mod_date
```

## Data Commands

```ls
series e:iben-kk8i d:2016-01-01T06:00:00.000Z t:route_id=S001910080E t:event_id=0000000005 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=1 t:atr_number=115 m:measure=62.320173

series e:iben-kk8i d:2016-01-01T06:00:00.000Z t:route_id=S001910080E t:event_id=0000000003 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=2 t:atr_number=704 m:measure=2.2972479999999997

series e:iben-kk8i d:2016-01-01T06:00:00.000Z t:route_id=S001910080E t:event_id=0000000004 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=3 t:atr_number=110 m:measure=33.261879
```

## Meta Commands

```ls
metric m:measure p:decimal l:MEASURE d:MEASURE t:dataTypeName=number

entity e:iben-kk8i l:"RAMS - Traffic ATR Location" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/iben-kk8i

property e:iben-kk8i t:meta.view v:id=iben-kk8i v:category="Transportation & Utilities" v:averageRating=0 v:name="RAMS - Traffic ATR Location" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:iben-kk8i t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:iben-kk8i t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| event_id   | route_id    | measure                                             | business_date | effective_start_date | effective_end_date | user_create | user_mod | system_create_date | system_mod_date | atr_number | locerror | objectid | 
| ========== | =========== | =================================================== | ============= | ==================== | ================== | =========== | ======== | ================== | =============== | ========== | ======== | ======== | 
| 0000000005 | S001910080E | 62.3201729999999969322743709199130535125732421875   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 115        | NO ERROR | 1        | 
| 0000000003 | S001910080E | 2.297247999999999734654920757748186588287353515625  | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 704        | NO ERROR | 2        | 
| 0000000004 | S001910080E | 33.26187900000000041700332076288759708404541015625  | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 110        | NO ERROR | 3        | 
| 0000000129 | S001910080W | 303.72751799999997501799953170120716094970703125    | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 704        | NO ERROR | 4        | 
| 0000000128 | S001910080W | 272.746840000000020154402591288089752197265625      | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 110        | NO ERROR | 5        | 
| 0000000127 | S001910080W | 243.6885320000000092477421276271343231201171875     | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 115        | NO ERROR | 6        | 
| 0000000126 | S001910080W | 167.150160999999997102349880151450634002685546875   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 117        | NO ERROR | 7        | 
| 0000000125 | S001910080W | 119.602652000000006182744982652366161346435546875   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 103        | NO ERROR | 8        | 
| 0000000124 | S001910080W | 84.367627999999996291080606169998645782470703125    | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 111        | NO ERROR | 9        | 
| 0000000123 | S001910080W | 3.9982009999999998939301804057322442531585693359375 | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769055         | 1464789873      | 119        | NO ERROR | 10       | 
```