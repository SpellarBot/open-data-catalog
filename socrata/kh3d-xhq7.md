# Queens Library Branches

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/queens-library-branches-86453) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kh3d-xhq7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kh3d-xhq7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kh3d-xhq7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kh3d-xhq7 |
| Name | Queens Library Branches |
| Attribution | Queens Library (QBPL) |
| Category | Recreation |
| Tags | library, services, queens, qpl, hours, schedule |
| Created | 2011-10-08T20:59:51Z |
| Publication Date | 2017-09-16T17:38:37Z |

## Description

Queens Public Library Hours and Locations

## Columns

```ls
| Included | Schema Type    | Field Name        | Name             | Data Type | Render Type |
| ======== | ============== | ================= | ================ | ========= | =========== |
| No       | time           | :updated_at       | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | name              | name             | text      | text        |
| No       |                | address           | Address          | text      | text        |
| Yes      | series tag     | city              | City             | text      | text        |
| Yes      | series tag     | postcode          | Postcode         | text      | number      |
| Yes      | series tag     | phone             | phone            | text      | text        |
| No       |                | mn                | Mn               | text      | text        |
| No       |                | tu                | Tu               | text      | text        |
| No       |                | we                | We               | text      | text        |
| No       |                | th                | Th               | text      | text        |
| No       |                | fr                | Fr               | text      | text        |
| No       |                | sa                | Sa               | text      | text        |
| No       |                | su                | Su               | text      | text        |
| Yes      | series tag     | notification      | notification     | text      | text        |
| Yes      | series tag     | borough           | Borough          | text      | text        |
| No       |                | latitude          | Latitude         | number    | number      |
| No       |                | longitude         | Longitude        | number    | number      |
| Yes      | numeric metric | community_board   | Community Board  | number    | number      |
| Yes      | numeric metric | community_council | Council District | number    | number      |
| Yes      | numeric metric | census_tract      | Census Tract     | number    | number      |
| Yes      | numeric metric | bin               | BIN              | number    | number      |
| Yes      | numeric metric | bbl               | BBL              | number    | number      |
| Yes      | series tag     | nta               | NTA              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,mn,tu,we,th,fr,sa,su,latitude,longitude
```

## Data Commands

```ls
series e:kh3d-xhq7 d:2017-09-16T17:38:07.000Z t:city=Arverne t:phone="(718) 634-4784" t:postcode=11692 t:name=Arverne t:nta=Hammels-Arverne-Edgemere t:borough=QUEENS m:bin=4158900018 m:community_board=14 m:bbl=4158900018 m:community_council=31 m:census_tract=97204

series e:kh3d-xhq7 d:2017-09-16T17:38:07.000Z t:city="Long Island City" t:phone="(718) 278-2220" t:postcode=11102 t:name=Astoria t:nta="Old Astoria" t:borough=QUEENS m:bin=4005400030 m:community_board=1 m:bbl=4005400030 m:community_council=22 m:census_tract=83

series e:kh3d-xhq7 d:2017-09-16T17:38:07.000Z t:city=Flushing t:phone="(718) 352-2027" t:postcode=11358 t:name=Auburndale t:nta="Ft. Totten-Bay Terrace-Clearview" t:borough=QUEENS m:bin=4057690010 m:community_board=7 m:bbl=4057690010 m:community_council=19 m:census_tract=1017
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:community_council p:integer l:"Council District" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:long l:BIN t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:kh3d-xhq7 l:"Queens Library Branches" t:attribution="Queens Library (QBPL)" t:url=https://data.cityofnewyork.us/api/views/kh3d-xhq7

property e:kh3d-xhq7 t:meta.view d:2017-09-25T07:30:55.776Z v:averageRating=0 v:name="Queens Library Branches" v:attribution="Queens Library (QBPL)" v:id=kh3d-xhq7 v:category=Recreation

property e:kh3d-xhq7 t:meta.view.owner d:2017-09-25T07:30:55.776Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:kh3d-xhq7 t:meta.view.tableauthor d:2017-09-25T07:30:55.776Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | name          | address                       | city             | postcode | phone          | mn               | tu              | we               | th               | fr               | sa               | su     | notification                                                                        | borough | latitude  | longitude  | community_board | community_council | census_tract | bin        | bbl        | nta                                                   | 
| =========== | ============= | ============================= | ================ | ======== | ============== | ================ | =============== | ================ | ================ | ================ | ================ | ====== | =================================================================================== | ======= | ========= | ========== | =============== | ================= | ============ | ========== | ========== | ===================================================== | 
| 1505583487  | Arverne       | 312 Beach 54 Street           | Arverne          | 11692    | (718) 634-4784 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM | 10:00AM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.593066 | -73.784341 | 14              | 31                | 97204        | 4158900018 | 4158900018 | Hammels-Arverne-Edgemere                              | 
| 1505583487  | Astoria       | 14-01 Astoria Boulevard       | Long Island City | 11102    | (718) 278-2220 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM | 10:00AM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.772173 | -73.928757 | 1               | 22                | 83           | 4005400030 | 4005400030 | Old Astoria                                           | 
| 1505583487  | Auburndale    | 25-55 Francis Lewis Boulevard | Flushing         | 11358    | (718) 352-2027 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.773525 | -73.796552 | 7               | 19                | 1017         | 4057690010 | 4057690010 | Ft. Totten-Bay Terrace-Clearview                      | 
| 1505583487  | Baisley Park  | 117-11 Sutphin Boulevard      | Jamaica          | 11436    | (718) 529-1590 | closed           | closed          | closed           | closed           | closed           | closed           | closed | This library is currently CLOSED for renovations and will reopen in September 2009. | QUEENS  | 40.680318 | -73.79203  | 12              | 28                | 288          | 4122040099 | 4122040099 | Baisley Park                                          | 
| 1505583487  | Bay Terrace   | 18-36 Bell Boulevard          | Bayside          | 11360    | (718) 423-7004 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM | 10:00AM - 6:00PM | 1:00AM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.783103 | -73.777013 | 7               | 19                | 99704        | 4058650082 | 4058650082 | Ft. Totten-Bay Terrace-Clearview                      | 
| 1505583487  | Bayside       | 214-20 Northern Boulevard     | Bayside          | 11361    | (718) 229-1834 | 10:00AM - 8:00PM | 1:00PM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.760363 | -73.768588 | 11              | 19                | 1471         | 4073330215 | 4073330215 | Bayside-Bayside Hills                                 | 
| 1505583487  | Bellerose     | 250-06 Hillside Avenue        | Bellerose        | 11426    | (718) 831-8644 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.735403 | -73.717266 | 13              | 23                | 157101       | 4086040085 | 4086040085 | Bellerose                                             | 
| 1505583487  | Briarwood     | 85-12 Main Street             | Briarwood        | 11435    | (718) 658-1680 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.71014  | -73.819621 | 8               | 24                | 22001        | 4096510025 | 4096510025 | Briarwood-Jamaica Hills                               | 
| 1505583487  | Broad Channel | 16-26 Cross Bay Boulevard     | Broad Channel    | 11693    | (718) 318-4943 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM | 10:00AM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.600838 | -73.820374 | 14              | 32                | 107201       | 4154810530 | 4154810530 | Breezy Point-Belle Harbor-Rockaway Park-Broad Channel | 
| 1505583487  | Broadway      | 40-20 Broadway                | Long Island City | 11103    | (718) 721-2462 | 10:00AM - 8:00PM | 1:00AM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed |                                                                                     | QUEENS  | 40.758859 | -73.918772 | 1               | 26                | 157          | 4006760050 | 4006760050 | Astoria                                               | 
```