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
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:m2gw-xt7z d:2015-01-01T00:00:00.000Z t:description="1032 Fort Street Garage (bet. S. Hotel St-S. King St)" t:latitude_longitude="21.310518, -157.861866" t:operator=ProPark m:daily_max=18

series e:m2gw-xt7z d:2015-01-01T00:00:00.000Z t:after_hours_flat_rate="Fri-Sat - $10 in after 5pm; Sun-Thu-$7 in after 5pm" t:note="Disabled Spaces" t:monthly_rate="$215 Sun-Thu, in after 5pm" t:hours_of_operation="Mon-Sun, 24 hrs." t:indoors_outdoors=Outdoors t:phone=592-7275 t:description="1131 Maunakea Street" t:height_restriction=None t:hourly="20 mins-$1; 1 hr-$3; 2 hrs-$5; 4 hrs-$7" t:latitude_longitude="21.312651, -157.862120" t:operator="United Parking Svc." m:earlybird=10

series e:m2gw-xt7z d:2015-01-01T00:00:00.000Z t:weekendrate=$3.25 t:after_hours_flat_rate="$3.25 after 4:30 pm" t:monthly_rate="$210 unrsvd; $375 rsvd" t:phone=522-1293 t:description="1132 Bishop Street" t:hourly="$3.25/half hr" t:latitude_longitude="21.310231, -157.860206" t:operator=Ampco m:daily_max=33 m:earlybird=15
```

## Meta Commands

```ls
metric m:daily_max p:integer l:"Daily Max" t:dataTypeName=money

metric m:earlybird p:long l:EarlyBird t:dataTypeName=money

entity e:m2gw-xt7z l:"Parking 2015" t:url=https://data.honolulu.gov/api/views/m2gw-xt7z

property e:m2gw-xt7z t:meta.view d:2017-09-25T07:26:38.788Z v:averageRating=0 v:name="Parking 2015" v:id=m2gw-xt7z v:category=Transportation

property e:m2gw-xt7z t:meta.view.owner d:2017-09-25T07:26:38.788Z v:displayName="Karl Sueyoshi" v:id=b4zr-4dtj v:screenName="Karl Sueyoshi"

property e:m2gw-xt7z t:meta.view.tableauthor d:2017-09-25T07:26:38.788Z v:displayName="Karl Sueyoshi" v:roleName=publisher v:id=b4zr-4dtj v:screenName="Karl Sueyoshi"
```

## Top Records

```ls
| description                                           | address              | latitude_longitude     | entrance | phone    | operator               | hourly                                  | daily_max | earlybird                    | after_hours_flat_rate                               | weekendrate                   | monthly_rate               | hours_of_operation | indoors_outdoors | service_type                     | motorcyles_allowed | vehicle_types | height_restriction | note                     | 
| ===================================================== | ==================== | ====================== | ======== | ======== | ====================== | ======================================= | ========= | ============================ | =================================================== | ============================= | ========================== | ================== | ================ | ================================ | ================== | ============= | ================== | ======================== | 
| 000 Aloha Tower Drive                                 |                      |                        |          |          |                        |                                         |           |                              |                                                     |                               |                            |                    |                  |                                  |                    |               |                    |                          | 
| 1021 Smith Street                                     | 1021 Smith Street    | 21.311542, -157.862936 |          | 592-7275 | Diamond                |                                         |           |                              | $5 after 5 pm                                       | $5 before 5 pm $10 after 5 pm |                            |                    |                  |                                  |                    |               |                    | Tenants only before 5 pm | 
| 1025 Waimanu Street                                   | 1025 Waimanu Street  | 21.296648, -157.851510 |          | 597-1789 | District Parking Svc   |                                         |           |                              |                                                     |                               |                            | Mon-Sun            | Outdoors         |                                  |                    |               | None               |                          | 
| 1032 Fort Street Garage (bet. S. Hotel St-S. King St) | 1043 Bethel Street   | 21.310518, -157.861866 |          |          | ProPark                |                                         | 18        |                              |                                                     |                               |                            |                    |                  |                                  |                    |               |                    |                          | 
| 1131 Maunakea Street                                  | 1131 Maunakea Street | 21.312651, -157.862120 |          | 592-7275 | United Parking Svc.    | 20 mins-$1; 1 hr-$3; 2 hrs-$5; 4 hrs-$7 |           | $10 in after 7am out by 5 pm | Fri-Sat - $10 in after 5pm; Sun-Thu-$7 in after 5pm |                               | $215 Sun-Thu, in after 5pm | Mon-Sun, 24 hrs.   | Outdoors         |                                  |                    |               | None               | Disabled Spaces          | 
| 1132 Bishop Street                                    | 1132 Bishop Street   | 21.310231, -157.860206 |          | 522-1293 | Ampco                  | $3.25/half hr                           | 33        | $15 before 8 am              | $3.25 after 4:30 pm                                 | $3.25                         | $210 unrsvd; $375 rsvd     |                    |                  |                                  |                    |               |                    |                          | 
| 1135 Smith St (bet. N. Pauahi St-N. Hotel St)         | 1135 Smith Street    | 21.312396, -157.861906 |          |          | Diamond                |                                         | 12        |                              |                                                     |                               |                            |                    |                  |                                  |                    |               |                    |                          | 
| 1171 Maunakea St (bet. N. Beretania St-N. Pauhahi St) | 1171 Maunakea Street | 21.313275, -157.861368 |          |          | Diamond                |                                         | 10        |                              |                                                     |                               |                            |                    |                  |                                  |                    |               |                    |                          | 
| 1188 Maunakea                                         | 1188 Maunakea        | 21.313504, -157.861538 |          | 592-7275 | Diamond                | 20 mins-$1; 1 hr-$2; 2 hrs-$4; 4 hrs-$6 |           | $10, in after 7am out by 5pm | $10 Sat-Sun in after 5pm; $5 Mon-Fri in after 5pm   |                               | $100 Sun-Thu in after 5 pm | Mon-Sun, 24 hrs    | Outdoors         | Pay and Display; Disabled Spaces |                    |               |                    |                          | 
| 1192 Alakea St. (bet. S. Beretania St-S. Hotel St)    | 1192 Alakea Street   | 21.310214, -157.858552 |          |          | United Parking Service |                                         | 21        |                              |                                                     |                               |                            |                    |                  |                                  |                    |               |                    |                          | 
```