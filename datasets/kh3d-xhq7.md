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
| Publication Date | 2013-06-21T20:10:11Z |

## Description

Queens Public Library Hours and Locations

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | name         | name         | text      | text        |
| Yes      | series tag  | phone        | phone        | text      | text        |
| No       |             | mn           | Mn           | text      | text        |
| No       |             | tu           | Tu           | text      | text        |
| No       |             | we           | We           | text      | text        |
| No       |             | th           | Th           | text      | text        |
| No       |             | fr           | Fr           | text      | text        |
| No       |             | sa           | Sa           | text      | text        |
| No       |             | su           | Su           | text      | text        |
| Yes      | series tag  | notification | notification | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mn,tu,we,th,fr,sa,su
```

## Data Commands

```ls
series e:kh3d-xhq7 d:2011-10-08T13:59:54.000Z t:phone="(718) 352-2027" t:name=Auburndale m:row_number.kh3d-xhq7=1

series e:kh3d-xhq7 d:2011-10-08T13:59:56.000Z t:phone="(718) 639-5228" t:name=Maspeth t:notification="<b>Return all Queens Library books, videos, music at Queens Library at Maspeth. Use the self-service book return, available every day and every night. Receipts given for your security.</b>" m:row_number.kh3d-xhq7=2

series e:kh3d-xhq7 d:2011-10-08T13:59:54.000Z t:phone="(718) 423-7004" t:name="Bay Terrace" m:row_number.kh3d-xhq7=3
```

## Meta Commands

```ls
metric m:row_number.kh3d-xhq7 p:long l:"Row Number"

entity e:kh3d-xhq7 l:"Queens Library Branches" t:attribution="Queens Library (QBPL)" t:url=https://data.cityofnewyork.us/api/views/kh3d-xhq7

property e:kh3d-xhq7 t:meta.view d:2017-06-09T13:59:37.787Z v:id=kh3d-xhq7 v:category=Recreation v:averageRating=0 v:name="Queens Library Branches" v:attribution="Queens Library (QBPL)"

property e:kh3d-xhq7 t:meta.view.owner d:2017-06-09T13:59:37.787Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:kh3d-xhq7 t:meta.view.tableauthor d:2017-06-09T13:59:37.787Z v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | name          | phone          | mn               | tu               | we               | th               | fr               | sa               | su               | notification                                                                                                                                                                          | 
| =========== | ============= | ============== | ================ | ================ | ================ | ================ | ================ | ================ | ================ | ===================================================================================================================================================================================== | 
| 1318082394  | Auburndale    | (718) 352-2027 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed           |                                                                                                                                                                                       | 
| 1318082396  | Maspeth       | (718) 639-5228 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed           | Return all Queens Library books, videos, music at Queens Library at Maspeth. Use the self-service book return, available every day and every night. Receipts given for your security. | 
| 1318082394  | Bay Terrace   | (718) 423-7004 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 1:00AM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed           |                                                                                                                                                                                       | 
| 1318082394  | Arverne       | (718) 634-4784 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed           |                                                                                                                                                                                       | 
| 1318082394  | Astoria       | (718) 278-2220 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed           |                                                                                                                                                                                       | 
| 1318082396  | Seaside       | (718) 634-1876 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed           |                                                                                                                                                                                       | 
| 1318082396  | McGoldrick    | (718) 461-1616 | 10:00PM - 8:00PM | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed           |                                                                                                                                                                                       | 
| 1318082396  | Broad Channel | (718) 318-4943 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 10:00AM - 6:00PM | 1:00PM - 6:00PM  | 10:00AM - 5:30PM | closed           |                                                                                                                                                                                       | 
| 1318082396  | Forest Hills  | (718) 268-7934 | 1:00PM - 8:00PM  | 1:00PM - 6:00PM  | 10:00AM - 6:00PM | 1:00PM - 8:00PM  | 10:00AM - 6:00PM | 10:00AM - 5:30PM | closed           |                                                                                                                                                                                       | 
| 1318082396  | Cyber Center  | (718) 990-0700 | 10:00AM - 8:45PM | 10:00AM - 8:45PM | 10:00AM - 8:45PM | 10:00AM - 8:45PM | 10:00AM - 8:45PM | 10:00AM - 5:15PM | 12:00PM - 4:45PM |                                                                                                                                                                                       | 
```