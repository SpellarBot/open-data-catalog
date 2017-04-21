# Turnstile Usage Data: 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/turnstile-usage-data-2016) |
| Metadata | [Link](https://data.ny.gov/api/views/ekwu-khcy) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ekwu-khcy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ekwu-khcy/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ekwu-khcy |
| Name | Turnstile Usage Data: 2016 |
| Attribution | MTA Headquarters, New York City Transit |
| Category | Transportation |
| Tags | turnstile, subway |
| Created | 2015-12-29T19:47:06Z |
| Publication Date | 2017-01-02T13:16:36Z |

## Description

Data file contains information on entry/exit register values for individual control areas.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | series tag     | c_a         | C/A         | text          | text          |
| Yes      | series tag     | unit        | Unit        | text          | text          |
| Yes      | series tag     | scp         | SCP         | text          | text          |
| Yes      | series tag     | station     | Station     | text          | text          |
| Yes      | series tag     | line_name   | Line Name   | text          | text          |
| Yes      | series tag     | division    | Division    | text          | text          |
| Yes      | time           | date        | Date        | calendar_date | calendar_date |
| Yes      | series tag     | time        | Time        | text          | text          |
| Yes      | series tag     | description | Description | text          | text          |
| Yes      | numeric metric | entries     | Entries     | number        | number        |
| Yes      | numeric metric | exits       | Exits       | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ekwu-khcy d:2016-03-04T00:00:00.000Z t:scp=02-00-00 t:line_name=NQR456 t:unit=R051 t:time=23:00:00 t:division=BMT t:c_a=A002 t:station="59 ST" t:description=REGULAR m:exits=1881239 m:entries=5572864

series e:ekwu-khcy d:2016-03-04T00:00:00.000Z t:scp=02-00-00 t:line_name=NQR456 t:unit=R051 t:time=19:00:00 t:division=BMT t:c_a=A002 t:station="59 ST" t:description=REGULAR m:exits=1881206 m:entries=5572521

series e:ekwu-khcy d:2016-03-04T00:00:00.000Z t:scp=02-00-00 t:line_name=NQR456 t:unit=R051 t:time=15:00:00 t:division=BMT t:c_a=A002 t:station="59 ST" t:description=REGULAR m:exits=1881113 m:entries=5571587
```

## Meta Commands

```ls
metric m:entries p:integer l:Entries d:"The cumulative ENTRY register value for a device. This register was initialized during system setup. It is a 10 digit number representing the number of entries on the specific device since its inception. Other forms of initialization may occur upon roll-over of the counter, erasing the memory device containing the register data, and replacing the processing device of the turnstile." t:dataTypeName=number

metric m:exits p:integer l:Exits d:"The cumulative EXITS register value for a device. This register was initialized during system setup. It is a 10 digit number representing the number of entries on the specific device since its inception. Other forms of initialization may occur upon roll-over of the counter, erasing the memory device containing the register data, and replacing the processing device of the turnstile." t:dataTypeName=number

entity e:ekwu-khcy l:"Turnstile Usage Data: 2016" t:attribution="MTA Headquarters, New York City Transit" t:url=https://data.ny.gov/api/views/ekwu-khcy

property e:ekwu-khcy t:meta.view v:id=ekwu-khcy v:category=Transportation v:attributionLink=http://www.mta.info/developers/download.html v:averageRating=0 v:name="Turnstile Usage Data: 2016" v:attribution="MTA Headquarters, New York City Transit"

property e:ekwu-khcy t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ekwu-khcy t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| c_a  | unit | scp      | station | line_name | division | date                | time     | description | entries | exits   | 
| ==== | ==== | ======== | ======= | ========= | ======== | =================== | ======== | =========== | ======= | ======= | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-04T00:00:00 | 23:00:00 | REGULAR     | 5572864 | 1881239 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-04T00:00:00 | 19:00:00 | REGULAR     | 5572521 | 1881206 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-04T00:00:00 | 15:00:00 | REGULAR     | 5571587 | 1881113 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-04T00:00:00 | 11:00:00 | REGULAR     | 5571313 | 1881031 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-04T00:00:00 | 08:10:05 | REGULAR     | 5571173 | 1880736 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-04T00:00:00 | 07:00:00 | REGULAR     | 5571136 | 1880657 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-04T00:00:00 | 03:00:00 | REGULAR     | 5571113 | 1880626 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-03T00:00:00 | 23:00:00 | REGULAR     | 5571055 | 1880614 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-03T00:00:00 | 19:00:00 | REGULAR     | 5570646 | 1880568 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456    | BMT      | 2016-03-03T00:00:00 | 15:00:00 | REGULAR     | 5569734 | 1880473 | 
```