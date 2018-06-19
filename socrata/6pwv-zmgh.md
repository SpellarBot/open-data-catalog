# SHL Vehicles ? LPEP Provider

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/shl-vehicles-lpep-provider) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6pwv-zmgh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6pwv-zmgh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6pwv-zmgh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6pwv-zmgh |
| Name | SHL Vehicles ? LPEP Provider |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, shl, lpep, transportation, cab |
| Created | 2015-10-07T15:21:12Z |
| Publication Date | 2015-12-02T15:06:54Z |

## Description

This list contains information on LPEP providers that are authorized for NYC TLC licensed SHL vehicles.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | license_number | License Number | text          | text          |
| Yes      | series tag  | name           | Name           | text          | text          |
| No       |             | address        | Address        | text          | text          |
| Yes      | series tag  | city           | City           | text          | text          |
| Yes      | series tag  | state          | State          | text          | text          |
| Yes      | series tag  | zip            | Zip            | text          | text          |
| Yes      | series tag  | phone          | Phone          | text          | text          |
| Yes      | series tag  | hour_phone_24  | 24 Hour Phone  | text          | text          |
| Yes      | series tag  | type           | Type           | text          | text          |
| Yes      | series tag  | status         | Status         | text          | text          |
| Yes      | time        | date           | Date           | calendar_date | calendar_date |
| Yes      | series tag  | time           | Time           | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:6pwv-zmgh d:2017-04-17T00:00:00.000Z t:zip=95110 t:time=06:00 t:phone=(718)752-1656 t:hour_phone_24=(917)359-1984 t:status=CURRENT t:license_number=LP0002 t:name="VERIFONE INC." t:state=CA t:type="LPEP PROVIDER" t:city="SAN JOSE" m:row_number.6pwv-zmgh=1

series e:6pwv-zmgh d:2017-04-17T00:00:00.000Z t:zip=11101 t:time=06:00 t:phone=(718)349-7700 t:hour_phone_24=(877)268-2947 t:status=CURRENT t:license_number=LP0001 t:name="CREATIVE MOBILE TECHNOLOGIES, LLC" t:state=NY t:type="LPEP PROVIDER" t:city=LIC m:row_number.6pwv-zmgh=2
```

## Meta Commands

```ls
metric m:row_number.6pwv-zmgh p:long l:"Row Number"

entity e:6pwv-zmgh l:"SHL Vehicles ? LPEP Provider" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/6pwv-zmgh

property e:6pwv-zmgh t:meta.view v:id=6pwv-zmgh v:category=Transportation v:averageRating=0 v:name="SHL Vehicles ? LPEP Provider" v:attribution="Taxi and Limousine Commission (TLC)"

property e:6pwv-zmgh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6pwv-zmgh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name                              | address                      | city     | state | zip   | phone         | hour_phone_24 | type          | status  | date                | time  | 
| ============== | ================================= | ============================ | ======== | ===== | ===== | ============= | ============= | ============= | ======= | =================== | ===== | 
| LP0002         | VERIFONE INC.                     | 2099 GATEWAY PLACE SUITE 600 | SAN JOSE | CA    | 95110 | (718)752-1656 | (917)359-1984 | LPEP PROVIDER | CURRENT | 2017-04-17T00:00:00 | 06:00 | 
| LP0001         | CREATIVE MOBILE TECHNOLOGIES, LLC | 42-50 24 STREET              | LIC      | NY    | 11101 | (718)349-7700 | (877)268-2947 | LPEP PROVIDER | CURRENT | 2017-04-17T00:00:00 | 06:00 | 
```