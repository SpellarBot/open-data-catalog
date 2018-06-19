# Bus Stop Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bus-stop-locations) |
| Metadata | [Link](https://data.honolulu.gov/api/views/yczt-gks6) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/yczt-gks6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/yczt-gks6/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | yczt-gks6 |
| Name | Bus Stop Locations |
| Category | Transportation |
| Created | 2015-05-23T01:13:40Z |
| Publication Date | 2015-05-23T01:14:28Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| No       |                | stop_lat       | stop_lat       | number    | number      |
| Yes      | series tag     | stop_code      | stop_code      | text      | number      |
| Yes      | numeric metric | stop_lon       | stop_lon       | number    | number      |
| Yes      | series tag     | stop_id        | stop_id        | text      | number      |
| Yes      | series tag     | stop_url       | stop_url       | text      | text        |
| Yes      | series tag     | parent_station | parent_station | text      | text        |
| Yes      | series tag     | stop_desc      | stop_desc      | text      | text        |
| Yes      | series tag     | stop_name      | stop_name      | text      | text        |
| Yes      | series tag     | location_type  | location_type  | text      | number      |
| Yes      | series tag     | zone_id        | zone_id        | text      | text        |
| Yes      | series tag     | lat_long       | lat_long       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = stop_lat
```

## Data Commands

```ls
series e:yczt-gks6 d:2015-05-22T18:13:45.000Z t:stop_id=2031 t:lat_long="21.4001, -157.9626" t:stop_code=2031 t:location_type=0 t:stop_url="http://hea.thebus.org/nextbus.asp?s=2031" t:stop_name="HOOLAULEA ST + OPP HOOHAKU ST" m:stop_lon=-157.9626

series e:yczt-gks6 d:2015-05-22T18:13:45.000Z t:stop_id=1200 t:lat_long="21.2796, -157.7023" t:stop_code=1200 t:location_type=0 t:stop_url="http://hea.thebus.org/nextbus.asp?s=1200" t:stop_name="LUNALILO HOME RD + OPP ANAPALAU ST" m:stop_lon=-157.7023

series e:yczt-gks6 d:2015-05-22T18:13:45.000Z t:stop_id=4026 t:lat_long="21.2594, -157.7957" t:stop_code=4026 t:location_type=0 t:stop_url="http://hea.thebus.org/nextbus.asp?s=4026" t:stop_name="KAHALA AVE + OPP PAIKAU ST" m:stop_lon=-157.7957
```

## Meta Commands

```ls
metric m:stop_lon p:float l:stop_lon t:dataTypeName=number

entity e:yczt-gks6 l:"Bus Stop Locations" t:url=https://data.honolulu.gov/api/views/yczt-gks6

property e:yczt-gks6 t:meta.view v:id=yczt-gks6 v:category=Transportation v:averageRating=0 v:name="Bus Stop Locations"

property e:yczt-gks6 t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:yczt-gks6 t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```

## Top Records

```ls
| :updated_at | stop_lat           | stop_code | stop_lon            | stop_id | stop_url                                 | parent_station | stop_desc | stop_name                            | location_type | zone_id | lat_long           | 
| =========== | ================== | ========= | =================== | ======= | ======================================== | ============== | ========= | ==================================== | ============= | ======= | ================== | 
| 1432318425  | 21.400099999999998 | 2031      | -157.96260000000001 | 2031    | http://hea.thebus.org/nextbus.asp?s=2031 |                |           | HOOLAULEA ST + OPP HOOHAKU ST        | 0             |         | 21.4001, -157.9626 | 
| 1432318425  | 21.279599999999999 | 1200      | -157.70230000000001 | 1200    | http://hea.thebus.org/nextbus.asp?s=1200 |                |           | LUNALILO HOME RD + OPP ANAPALAU ST   | 0             |         | 21.2796, -157.7023 | 
| 1432318425  | 21.259399999999999 | 4026      | -157.79570000000001 | 4026    | http://hea.thebus.org/nextbus.asp?s=4026 |                |           | KAHALA AVE + OPP PAIKAU ST           | 0             |         | 21.2594, -157.7957 | 
| 1432318425  | 21.376799999999999 | 1869      | -157.91679999999999 | 1869    | http://hea.thebus.org/nextbus.asp?s=1869 |                |           | HALAWA HEIGHTS RD + IWAIWA ST        | 0             |         | 21.3768, -157.9168 | 
| 1432318425  | 21.2576            | 4024      | -157.80119999999999 | 4024    | http://hea.thebus.org/nextbus.asp?s=4024 |                |           | DIAMOND HEAD RD + 3701               | 0             |         | 21.2576, -157.8012 | 
| 1432318425  | 21.259             | 4025      | -157.79750000000001 | 4025    | http://hea.thebus.org/nextbus.asp?s=4025 |                |           | KAHALA AVE + KULAMANU ST             | 0             |         | 21.259, -157.7975  | 
| 1432318425  | 21.2559            | 4022      | -157.8092           | 4022    | http://hea.thebus.org/nextbus.asp?s=4022 |                |           | DIAMOND HEAD RD + DIAMOND HEAD LIGHT | 0             |         | 21.2559, -157.8092 | 
| 1432318425  | 21.257100000000001 | 4023      | -157.80250000000001 | 4023    | http://hea.thebus.org/nextbus.asp?s=4023 |                |           | DIAMOND HEAD RD + 3647               | 0             |         | 21.2571, -157.8025 | 
| 1432318425  | 21.257300000000001 | 4020      | -157.81569999999999 | 4020    | http://hea.thebus.org/nextbus.asp?s=4020 |                |           | DIAMOND HEAD RD + 3165               | 0             |         | 21.2573, -157.8157 | 
| 1432318425  | 21.2563            | 4021      | -157.8125           | 4021    | http://hea.thebus.org/nextbus.asp?s=4021 |                |           | DIAMOND HEAD RD + BEACH RD           | 0             |         | 21.2563, -157.8125 | 
```