# Parking 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-2015) |
| Metadata | [Link](https://data.honolulu.gov/api/views/m2gw-xt7z) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/m2gw-xt7z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/m2gw-xt7z/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | m2gw-xt7z |
| Name | Parking 2015 |
| Category | Transportation |
| Created | 2015-05-13T01:24:50Z |
| Publication Date | 2015-05-13T01:34:27Z |
| Rows Updated | 2015-05-13T01:25:33Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                   | Data Type | Render Type |
| ======== | ============== | ===================== | ====================== | ========= | =========== |
| Yes      | series tag     | description           | Description            | text      | text        |
| No       |                | address               | Address                | text      | text        |
| Yes      | series tag     | latitude_longitude    | Latitude, Longitude    | text      | text        |
| Yes      | series tag     | entrance              | Entrance               | text      | text        |
| Yes      | series tag     | phone                 | Phone                  | text      | text        |
| Yes      | series tag     | operator              | Operator               | text      | text        |
| Yes      | series tag     | hourly                | Hourly                 | text      | text        |
| Yes      | numeric metric | daily_max             | Daily Max              | money     | money       |
| Yes      | numeric metric | earlybird             | EarlyBird              | money     | text        |
| Yes      | series tag     | after_hours_flat_rate | After Hours(flat rate) | text      | text        |
| Yes      | series tag     | weekendrate           | WeekendRate            | text      | text        |
| Yes      | series tag     | monthly_rate          | Monthly Rate           | text      | text        |
| Yes      | series tag     | hours_of_operation    | Hours of Operation     | text      | text        |
| Yes      | series tag     | indoors_outdoors      | Indoors/Outdoors       | text      | text        |
| Yes      | series tag     | service_type          | Service Type           | text      | text        |
| Yes      | series tag     | motorcyles_allowed    | Motorcyles Allowed     | text      | text        |
| Yes      | series tag     | vehicle_types         | Vehicle Types          | text      | text        |
| Yes      | series tag     | height_restriction    | Height Restriction     | text      | text        |
| Yes      | series tag     | note                  | Note                   | text      | text        |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:m2gw-xt7z d:2015-01-01T00:00:00.000Z t:description="1032 Fort Street Garage (bet. S. Hotel St-S. King St)" t:latitude_longitude="21.310518, -157.861866" t:operator=ProPark m:daily_max=18

series e:m2gw-xt7z d:2015-01-01T00:00:00.000Z t:after_hours_flat_rate="Fri-Sat - $10 in after 5pm; Sun-Thu-$7 in after 5pm" t:phone=592-7275 t:description="1131 Maunakea Street" t:hours_of_operation="Mon-Sun, 24 hrs." t:indoors_outdoors=Outdoors t:hourly="20 mins-$1; 1 hr-$3; 2 hrs-$5; 4 hrs-$7" t:monthly_rate="$215 Sun-Thu, in after 5pm" t:latitude_longitude="21.312651, -157.862120" t:note="Disabled Spaces" t:operator="United Parking Svc." t:height_restriction=None m:earlybird=10

series e:m2gw-xt7z d:2015-01-01T00:00:00.000Z t:after_hours_flat_rate="$3.25 after 4:30 pm" t:phone=522-1293 t:description="1132 Bishop Street" t:hourly="$3.25/half hr" t:monthly_rate="$210 unrsvd; $375 rsvd" t:latitude_longitude="21.310231, -157.860206" t:operator=Ampco t:weekendrate=$3.25 m:daily_max=33 m:earlybird=15
```

## Meta Commands

```ls
metric m:daily_max p:integer l:"Daily Max" t:dataTypeName=money

metric m:earlybird p:long l:EarlyBird t:dataTypeName=money

entity e:m2gw-xt7z l:"Parking 2015" t:url=https://data.honolulu.gov/api/views/m2gw-xt7z

property e:m2gw-xt7z t:meta.view v:id=m2gw-xt7z v:category=Transportation v:averageRating=0 v:name="Parking 2015"

property e:m2gw-xt7z t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"

property e:m2gw-xt7z t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```