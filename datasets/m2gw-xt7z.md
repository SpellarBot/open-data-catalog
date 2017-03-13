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
| No       | time           | :updated_at           | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | description           | Description            | text      | text        |
| No       |                | address               | Address                | text      | text        |
| Yes      | series tag     | latitude_longitude    | Latitude, Longitude    | text      | text        |
| Yes      | series tag     | entrance              | Entrance               | text      | text        |
| Yes      | series tag     | phone                 | Phone                  | text      | text        |
| Yes      | series tag     | operator              | Operator               | text      | text        |
| Yes      | series tag     | hourly                | Hourly                 | text      | text        |
| Yes      | numeric metric | daily_max             | Daily Max              | money     | money       |
| Yes      | series tag     | earlybird             | EarlyBird              | text      | text        |
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
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:m2gw-xt7z d:2015-05-12T18:25:05.000Z t:description="1032 Fort Street Garage (bet. S. Hotel St-S. King St)" t:latitude_longitude="21.310518, -157.861866" t:operator=ProPark m:daily_max=18

series e:m2gw-xt7z d:2015-05-12T18:25:05.000Z t:after_hours_flat_rate="$3.25 after 4:30 pm" t:phone=522-1293 t:description="1132 Bishop Street" t:earlybird="$15 before 8 am" t:monthly_rate="$210 unrsvd; $375 rsvd" t:hourly="$3.25/half hr" t:latitude_longitude="21.310231, -157.860206" t:operator=Ampco t:weekendrate=$3.25 m:daily_max=33

series e:m2gw-xt7z d:2015-05-12T18:25:05.000Z t:description="1135 Smith St (bet. N. Pauahi St-N. Hotel St)" t:latitude_longitude="21.312396, -157.861906" t:operator=Diamond m:daily_max=12
```

## Meta Commands

```ls
entity e:m2gw-xt7z l:"Parking 2015" t:url=https://data.honolulu.gov/api/views/m2gw-xt7z

property e:m2gw-xt7z t:meta.view v:id=m2gw-xt7z v:category=Transportation v:averageRating=0 v:name="Parking 2015"

property e:m2gw-xt7z t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"

property e:m2gw-xt7z t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```