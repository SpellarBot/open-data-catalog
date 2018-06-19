# TAX 12-2012 LIQUID FUEL RATE SCHEDULE

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-12-2012-liquid-fuel-rate-schedule-87423) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ap2e-c6eb) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ap2e-c6eb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ap2e-c6eb/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ap2e-c6eb |
| Name | TAX 12-2012 LIQUID FUEL RATE SCHEDULE |
| Attribution | Department of Taxation |
| Category | Government-Wide Support |
| Tags | rate, tax, fuel |
| Created | 2013-02-05T20:27:06Z |
| Publication Date | 2013-02-05T21:28:16Z |

## Description

SCHEDULE OF TAX RATES PER GALLON (Effective July 1, 2010) (Fuel Tax rates in cents per gallon)

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | rate_and_fuel_type | Rate and Fuel Type | text      | text        |
| Yes      | numeric metric | county_fuel_tax    | COUNTY FUEL TAX    | number    | number      |
| Yes      | numeric metric | state_tax          | STATE TAX          | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ap2e-c6eb d:2012-01-01T00:00:00.000Z t:rate_and_fuel_type="City & County of Honolulu" m:county_fuel_tax=16.5 m:state_tax=17

series e:ap2e-c6eb d:2012-01-01T00:00:00.000Z t:rate_and_fuel_type="County of Maui" m:county_fuel_tax=16 m:state_tax=17

series e:ap2e-c6eb d:2012-01-01T00:00:00.000Z t:rate_and_fuel_type="County of Hawaii" m:county_fuel_tax=8.8 m:state_tax=17
```

## Meta Commands

```ls
metric m:county_fuel_tax p:float l:"COUNTY FUEL TAX" t:dataTypeName=number

metric m:state_tax p:float l:"STATE TAX" t:dataTypeName=number

entity e:ap2e-c6eb l:"TAX 12-2012 LIQUID FUEL RATE SCHEDULE" t:attribution="Department of Taxation" t:url=https://data.hawaii.gov/api/views/ap2e-c6eb

property e:ap2e-c6eb t:meta.view v:id=ap2e-c6eb v:category="Government-Wide Support" v:attributionLink=http://www6.hawaii.gov/tax/a5_3txcolrpt.htm v:averageRating=0 v:name="TAX 12-2012 LIQUID FUEL RATE SCHEDULE" v:attribution="Department of Taxation"

property e:ap2e-c6eb t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ap2e-c6eb t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:ap2e-c6eb t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| rate_and_fuel_type                 | county_fuel_tax | state_tax | 
| ================================== | =============== | ========= | 
| GASOLINE AND DIESEL OIL (HIGHWAY): |                 |           | 
| City & County of Honolulu          | 16.5            | 17.0      | 
| County of Maui                     | 16.0            | 17.0      | 
| County of Hawaii                   | 8.8             | 17.0      | 
| County of Kauai                    | 13.0            | 17.0      | 
| DIESEL OIL (OFF-HIGHWAY):          |                 |           | 
| All Counties                       | 0.0             | 2.0       | 
| LIQ. PET. GAS (HWY USE):           |                 |           | 
| City & County of Honolulu          | 5.4             | 5.2       | 
| County of Maui                     | 4.3             | 5.2       | 
```