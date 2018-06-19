# CT Transit Hartford Area Route Bus Stops

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ct-transit-hartford-area-route-bus-stops) |
| Metadata | [Link](https://data.ct.gov/api/views/n4zd-qppb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/n4zd-qppb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/n4zd-qppb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | n4zd-qppb |
| Name | CT Transit Hartford Area Route Bus Stops |
| Attribution | CT Transit |
| Category | Transportation |
| Tags | bus, stop, transit |
| Created | 2015-06-08T20:12:49Z |
| Publication Date | 2015-06-08T20:18:55Z |

## Description

Bus stop locations for CT Transit hartford area routes

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | stop_id        | stop_id        | text      | number      |
| Yes      | series tag     | stop_code      | stop_code      | text      | text        |
| Yes      | series tag     | stop_name      | stop_name      | text      | text        |
| No       |                | stop_lat       | stop_lat       | number    | number      |
| Yes      | numeric metric | stop_lon       | stop_lon       | number    | number      |
| Yes      | series tag     | zone_id        | zone_id        | text      | text        |
| Yes      | series tag     | stop_url       | stop_url       | text      | text        |
| Yes      | series tag     | location_type  | location_type  | text      | text        |
| Yes      | series tag     | parent_station | parent_station | text      | text        |
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
series e:n4zd-qppb d:2015-06-08T13:12:55.000Z t:stop_id=1 t:stop_name="Main St and Travelers" m:stop_lon=-72.673497

series e:n4zd-qppb d:2015-06-08T13:12:55.000Z t:stop_id=2 t:stop_name="Capitol Ave and Broad St" m:stop_lon=-72.686764

series e:n4zd-qppb d:2015-06-08T13:12:55.000Z t:stop_id=3 t:stop_name="Hillside Ave and New Britain Ave" m:stop_lon=-72.697386
```

## Meta Commands

```ls
metric m:stop_lon p:decimal l:stop_lon t:dataTypeName=number

entity e:n4zd-qppb l:"CT Transit Hartford Area Route Bus Stops" t:attribution="CT Transit" t:url=https://data.ct.gov/api/views/n4zd-qppb

property e:n4zd-qppb t:meta.view v:id=n4zd-qppb v:category=Transportation v:attributionLink=https://www.cttransit.com/about/developers v:averageRating=0 v:name="CT Transit Hartford Area Route Bus Stops" v:attribution="CT Transit"

property e:n4zd-qppb t:meta.view.license v:name="Public Domain"

property e:n4zd-qppb t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:n4zd-qppb t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | stop_id | stop_code | stop_name                        | stop_lat           | stop_lon            | zone_id | stop_url | location_type | parent_station | 
| =========== | ======= | ========= | ================================ | ================== | =================== | ======= | ======== | ============= | ============== | 
| 1433769175  | 1       |           | Main St and Travelers            | 41.764927999999998 | -72.673496999999998 |         |          |               |                | 
| 1433769175  | 2       |           | Capitol Ave and Broad St         | 41.763773          | -72.686763999999997 |         |          |               |                | 
| 1433769175  | 3       |           | Hillside Ave and New Britain Ave | 41.739189000000003 | -72.697385999999995 |         |          |               |                | 
| 1433769175  | 4       |           | Market St and Constitution Plaza | 41.766356000000002 | -72.671263999999994 |         |          |               |                | 
| 1433769175  | 5       |           | Mountain St and Haddam St        | 41.728219000000003 | -72.701752999999997 |         |          |               |                | 
| 1433769175  | 7       |           | Pitkin St and Main St            | 41.763697000000001 | -72.647246999999993 |         |          |               |                | 
| 1433769175  | 8       |           | Mountain St and Haddam St        | 41.728245000000001 | -72.701510999999996 |         |          |               |                | 
| 1433769175  | 9       |           | Hillside Ave and New Britain Ave | 41.73977           | -72.697226999999998 |         |          |               |                | 
| 1433769175  | 10      |           | Capitol Ave and Broad St         | 41.763593999999998 | -72.686813000000001 |         |          |               |                | 
| 1433769175  | 19      |           | Pitkin St and Main St            | 41.763876000000003 | -72.647441000000001 |         |          |               |                | 
```