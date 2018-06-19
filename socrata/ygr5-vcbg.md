# Towed Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/towed-vehicles-18129) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ygr5-vcbg) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ygr5-vcbg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ygr5-vcbg/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ygr5-vcbg |
| Name | Towed Vehicles |
| Attribution | Chicago Police Department |
| Category | Transportation |
| Tags | vehicles, streets |
| Created | 2011-09-30T08:00:05Z |
| Publication Date | 2014-12-01T15:17:41Z |

## Description

This dataset displays location for vehicles that have been towed and impounded by the City of Chicago within the last 90 days. Illegally parked vehicles, abandoned vehicles and vehicles used for illegal activities may be towed by the Chicago Police Department, the Department of Streets and Sanitation, the Department of Revenue, Aviation and the office of the City Clerk. After a tow request is issued, an inventory number is assigned by the Department of Streets and Sanitation and a truck is dispatched to tow the requested vehicle to a City auto pound. Disclaimer: This dataset includes vehicles towed or relocated by the City of Chicago; it does not include vehicles towed by a private towing company. 
Background Info: 
Auto Pound Locations (http://j.mp/kG5sgF).
Tow Process Overview (http://j.mp/lfBOEP).
Common Towing Questions (http://j.mp/imFYlp).
Parking and Standing Violations (http://j.mp/ifW8Uj).
Data Owner: Chicago Police Department.
Time Period: Last 90 days.
Frequency: Data is updated daily.
Related Applications: Find Your Vehicle (http://j.mp/lWn0S7).

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | time        | tow_date           | Tow Date           | calendar_date | calendar_date |
| Yes      | series tag  | make               | Make               | text          | text          |
| Yes      | series tag  | style              | Style              | text          | text          |
| Yes      | series tag  | model              | Model              | text          | text          |
| Yes      | series tag  | color              | Color              | text          | text          |
| Yes      | series tag  | plate              | Plate              | text          | text          |
| Yes      | series tag  | state              | State              | text          | text          |
| No       |             | towed_to_address   | Towed to Address   | text          | text          |
| Yes      | series tag  | tow_facility_phone | Tow Facility Phone | text          | text          |
| Yes      | series tag  | inventory_number   | Inventory Number   | text          | text          |
```

## Time Field

```ls
Value = tow_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = towed_to_address
```

## Data Commands

```ls
series e:ygr5-vcbg d:2017-04-14T00:00:00.000Z t:inventory_number=2820063 t:style=LL t:color=GRY t:state=IL t:plate=L340568 t:tow_facility_phone="(773) 568-8495" t:make=FORD m:row_number.ygr5-vcbg=1

series e:ygr5-vcbg d:2017-01-31T00:00:00.000Z t:inventory_number=6874519 t:style=4D t:color=BLK t:state=IL t:plate=N895558 t:tow_facility_phone="(773) 265-7605" t:make=VOLK m:row_number.ygr5-vcbg=2

series e:ygr5-vcbg d:2017-01-31T00:00:00.000Z t:inventory_number=6874516 t:style=LL t:color=BLK t:state=IL t:plate=E406181 t:tow_facility_phone="(773) 265-7605" t:make=NISS m:row_number.ygr5-vcbg=3
```

## Meta Commands

```ls
metric m:row_number.ygr5-vcbg p:long l:"Row Number"

entity e:ygr5-vcbg l:"Towed Vehicles" t:attribution="Chicago Police Department" t:url=https://data.cityofchicago.org/api/views/ygr5-vcbg

property e:ygr5-vcbg t:meta.view v:id=ygr5-vcbg v:category=Transportation v:attributionLink=http://www.chicagopolice.org/ v:averageRating=0 v:name="Towed Vehicles" v:attribution="Chicago Police Department"

property e:ygr5-vcbg t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ygr5-vcbg t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| tow_date            | make | style | model | color | plate   | state | towed_to_address  | tow_facility_phone | inventory_number | 
| =================== | ==== | ===== | ===== | ===== | ======= | ===== | ================= | ================== | ================ | 
| 2017-04-14T00:00:00 | FORD | LL    |       | GRY   | L340568 | IL    | 10300 S. Doty     | (773) 568-8495     | 2820063          | 
| 2017-01-31T00:00:00 | VOLK | 4D    |       | BLK   | N895558 | IL    | 701 N. Sacramento | (773) 265-7605     | 6874519          | 
| 2017-01-31T00:00:00 | NISS | LL    |       | BLK   | E406181 | IL    | 701 N. Sacramento | (773) 265-7605     | 6874516          | 
| 2017-04-14T00:00:00 | NISS | 4D    |       | BLU   | Z712177 | IL    | 10300 S. Doty     | (773) 568-8495     | 2820061          | 
| 2017-01-31T00:00:00 | BUIC | 4D    |       | RED   | S396615 | IL    | 701 N. Sacramento | (773) 265-7605     | 6874517          | 
| 2017-01-31T00:00:00 | JEEP | LL    |       | BLK   | V241099 | IL    | 701 N. Sacramento | (773) 265-7605     | 6874518          | 
| 2017-04-13T00:00:00 | LINC | LL    |       | SIL   | Z669681 | IL    | 10300 S. Doty     | (773) 785-9752     | 1717000          | 
| 2017-02-23T00:00:00 | CHEV | 4D    | MAL   | GRY   | E521741 | IL    | 701 N. Sacramento | (773) 265-7605     | 6877679          | 
| 2017-03-19T00:00:00 | MERC | LL    |       | BLK   | Y120614 | IL    | 701 N. Sacramento | (773) 265-7605     | 6880855          | 
| 2017-01-30T00:00:00 | TOYT | 4D    |       | BLU   | Q464587 | IL    | 10300 S. Doty     | (773) 568-8495     | 2812800          | 
```