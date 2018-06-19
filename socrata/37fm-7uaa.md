# NYCHA Customer Contact Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycha-customer-contact-centers-c9ece) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/37fm-7uaa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/37fm-7uaa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/37fm-7uaa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 37fm-7uaa |
| Name | NYCHA Customer Contact Centers |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | City Government |
| Tags | nycha, nyc housing, government service, call center, walk-in center |
| Created | 2013-03-28T19:11:18Z |
| Publication Date | 2016-09-15T22:22:22Z |

## Description

The customer contact center locations, phone numbers and schedules

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| No       |             | address_1   | Address 1  | text      | text        |
| No       |             | address_2   | Address 2  | text      | text        |
| Yes      | series tag  | city        | City       | text      | text        |
| Yes      | series tag  | state       | State      | text      | text        |
| Yes      | series tag  | zip_code    | Zip Code   | text      | text        |
| Yes      | series tag  | phone__     | Phone #    | text      | text        |
| Yes      | series tag  | days        | Days       | text      | text        |
| Yes      | series tag  | hours       | Hours      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:37fm-7uaa d:2016-09-15T22:22:11.000Z t:days="Mon.- Fri." t:zip_code=10458 t:hours="8am - 5pm" t:name="Bronx/Manhattan Customer Contact Center" t:state=NY t:phone_="(718) 707-7771" t:city=Bronx m:row_number.37fm-7uaa=1

series e:37fm-7uaa d:2016-09-15T22:22:11.000Z t:days="Mon.- Fri." t:zip_code=11238 t:hours="8am - 5pm" t:name="Brooklyn/Staten Island Customer Contact Center" t:state=NY t:phone_="(718) 707-7771" t:city=Brooklyn m:row_number.37fm-7uaa=2
```

## Meta Commands

```ls
metric m:row_number.37fm-7uaa p:long l:"Row Number"

entity e:37fm-7uaa l:"NYCHA Customer Contact Centers" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/37fm-7uaa

property e:37fm-7uaa t:meta.view v:id=37fm-7uaa v:category="City Government" v:attributionLink=http://www.nyc.gov/html/nycha/html/residents/maint_requests.shtml v:averageRating=0 v:name="NYCHA Customer Contact Centers" v:attribution="New York City Housing Authority (NYCHA)"

property e:37fm-7uaa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:37fm-7uaa t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | name                                           | address_1                               | address_2 | city     | state | zip_code | phone__        | days       | hours     | 
| =========== | ============================================== | ======================================= | ========= | ======== | ===== | ======== | ============== | ========== | ========= | 
| 1473978131  | Bronx/Manhattan Customer Contact Center        | 478 East Fordham Road (1 Fordham Plaza) | 2nd Floor | Bronx    | NY    | 10458    | (718) 707-7771 | Mon.- Fri. | 8am - 5pm | 
| 1473978131  | Brooklyn/Staten Island Customer Contact Center | 787 Atlantic Avenue                     | 2nd Floor | Brooklyn | NY    | 11238    | (718) 707-7771 | Mon.- Fri. | 8am - 5pm | 
```