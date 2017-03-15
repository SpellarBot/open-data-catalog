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
| Rows Updated | 2013-06-21T20:10:06Z |

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

series e:kh3d-xhq7 d:2011-10-08T13:59:56.000Z t:phone="(718) 639-5228" t:name=Maspeth t:notification="Return all Queens Library books, videos, music at Queens Library at Maspeth. Use the self-service book return, available every day and every night. Receipts given for your security." m:row_number.kh3d-xhq7=2

series e:kh3d-xhq7 d:2011-10-08T13:59:54.000Z t:phone="(718) 423-7004" t:name="Bay Terrace" m:row_number.kh3d-xhq7=3
```

## Meta Commands

```ls
metric m:row_number.kh3d-xhq7 p:long l:"Row Number"

entity e:kh3d-xhq7 l:"Queens Library Branches" t:attribution="Queens Library (QBPL)" t:url=https://data.cityofnewyork.us/api/views/kh3d-xhq7

property e:kh3d-xhq7 t:meta.view v:id=kh3d-xhq7 v:category=Recreation v:averageRating=0 v:name="Queens Library Branches" v:attribution="Queens Library (QBPL)"

property e:kh3d-xhq7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:kh3d-xhq7 t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```