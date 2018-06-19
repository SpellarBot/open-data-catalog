# Canal System Guard Gates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/canal-system-guard-gates) |
| Metadata | [Link](https://data.ny.gov/api/views/daiv-97a8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/daiv-97a8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/daiv-97a8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | daiv-97a8 |
| Name | Canal System Guard Gates |
| Attribution | New York State Canal Corporation |
| Category | Recreation |
| Tags | canal, waterway, guard gate, erie canal, champlain canal, oswego canal, cayuga-seneca canal |
| Created | 2013-02-26T23:54:47Z |
| Publication Date | 2013-03-01T16:25:49Z |

## Description

The New York State Canal System is a 524 mile inland waterway that includes 20 guard gates, which are used to close off a section of canal seasonally or in rare instances in an emergency so that a section can be dewatered. Information provided in this data set includes the name of each guard gate, its phone number (where applicable), and specific location by mileage along the canal and geographic coordinates.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | canal_name    | Canal Name    | text      | text        |
| Yes      | numeric metric | mile          | Mile          | number    | number      |
| Yes      | series tag     | name_location | Name/Location | text      | text        |
| Yes      | series tag     | phone         | Phone         | text      | text        |
| No       |                | latitude      | Latitude      | number    | number      |
| No       |                | longitude     | Longitude     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:daiv-97a8 d:2013-02-26T15:54:48.000Z t:name_location="Crocker's Reef, Fort Miller" t:phone=NA t:canal_name="Champlain Canal" m:mile=31.84

series e:daiv-97a8 d:2013-02-26T15:54:48.000Z t:name_location="Guard Gate 1, Waterford" t:phone=NA t:canal_name="Erie Canal" m:mile=2.52

series e:daiv-97a8 d:2013-02-26T15:54:48.000Z t:name_location="Guard Gate 2, Waterford" t:phone="(518) 237-0833" t:canal_name="Erie Canal" m:mile=2.77
```

## Meta Commands

```ls
metric m:mile p:float l:Mile d:"Mileage along the waterway (in 1/100ths of a mile)" t:dataTypeName=number

entity e:daiv-97a8 l:"Canal System Guard Gates" t:attribution="New York State Canal Corporation" t:url=https://data.ny.gov/api/views/daiv-97a8

property e:daiv-97a8 t:meta.view v:id=daiv-97a8 v:category=Recreation v:attributionLink=http://www.canals.ny.gov/boating/guardgates.cgi v:averageRating=0 v:name="Canal System Guard Gates" v:attribution="New York State Canal Corporation"

property e:daiv-97a8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:daiv-97a8 t:meta.view.tableauthor v:id=6kas-u9kj v:profileImageUrlMedium=/api/users/6kas-u9kj/profile_images/THUMB v:profileImageUrlLarge=/api/users/6kas-u9kj/profile_images/LARGE v:screenName="Jenson Jacob" v:profileImageUrlSmall=/api/users/6kas-u9kj/profile_images/TINY v:roleName=administrator v:displayName="Jenson Jacob"

property e:daiv-97a8 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | canal_name      | mile   | name_location               | phone          | latitude | longitude | 
| =========== | =============== | ====== | =========================== | ============== | ======== | ========= | 
| 1361894088  | Champlain Canal | 31.84  | Crocker's Reef, Fort Miller | NA             | 43.18955 | -73.58102 | 
| 1361894088  | Erie Canal      | 2.52   | Guard Gate 1, Waterford     | NA             | 42.80340 | -73.70890 | 
| 1361894088  | Erie Canal      | 2.77   | Guard Gate 2, Waterford     | (518) 237-0833 | 42.80489 | -73.71336 | 
| 1361894088  | Erie Canal      | 74.54  | Guard Gate 3, Indian Castle | NA             | 43.00942 | -74.77205 | 
| 1361894088  | Erie Canal      | 79.84  | Guard Gate 4, Little Falls  | NA             | 43.03755 | -74.86223 | 
| 1361894088  | Erie Canal      | 87.20  | Guard Gate 5, Herkimer      | NA             | 43.01536 | -74.99444 | 
| 1361894088  | Erie Canal      | 111.80 | Guard Gate 6, Rome          | NA             | 43.19945 | -75.38903 | 
| 1361894088  | Erie Canal      | 115.05 | Guard Gate 7, Rome          | NA             | 43.20126 | -75.45348 | 
| 1361894088  | Erie Canal      | 249.96 | Bushnell's Basin            | NA             | 43.06838 | -77.46847 | 
| 1361894088  | Erie Canal      | 252.35 | Cartersville                | NA             | 43.07917 | -77.50114 | 
```