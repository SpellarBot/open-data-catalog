# Turnstile Usage Data: 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/turnstile-usage-data-2017) |
| Metadata | [Link](https://data.ny.gov/api/views/v5y5-mwpb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/v5y5-mwpb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/v5y5-mwpb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | v5y5-mwpb |
| Name | Turnstile Usage Data: 2017 |
| Attribution | MTA Headquarters, New York City Transit |
| Category | Transportation |
| Tags | turnstile, subway |
| Created | 2016-12-27T16:59:25Z |
| Publication Date | 2017-04-17T10:39:06Z |

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
series e:v5y5-mwpb d:2016-12-31T00:00:00.000Z t:scp=02-00-00 t:line_name=NQR456W t:unit=R051 t:time=03:00:00 t:division=BMT t:c_a=A002 t:station="59 ST" t:description=REGULAR m:exits=2028378 m:entries=5991546

series e:v5y5-mwpb d:2016-12-31T00:00:00.000Z t:scp=02-00-00 t:line_name=NQR456W t:unit=R051 t:time=07:00:00 t:division=BMT t:c_a=A002 t:station="59 ST" t:description=REGULAR m:exits=2028389 m:entries=5991565

series e:v5y5-mwpb d:2016-12-31T00:00:00.000Z t:scp=02-00-00 t:line_name=NQR456W t:unit=R051 t:time=11:00:00 t:division=BMT t:c_a=A002 t:station="59 ST" t:description=REGULAR m:exits=2028441 m:entries=5991644
```

## Meta Commands

```ls
metric m:entries p:integer l:Entries d:"The cumulative ENTRY register value for a device. This register was initialized during system setup. It is a 10 digit number representing the number of entries on the specific device since its inception. Other forms of initialization may occur upon roll-over of the counter, erasing the memory device containing the register data, and replacing the processing device of the turnstile." t:dataTypeName=number

metric m:exits p:integer l:Exits d:"The cumulative EXITS register value for a device. This register was initialized during system setup. It is a 10 digit number representing the number of entries on the specific device since its inception. Other forms of initialization may occur upon roll-over of the counter, erasing the memory device containing the register data, and replacing the processing device of the turnstile." t:dataTypeName=number

entity e:v5y5-mwpb l:"Turnstile Usage Data: 2017" t:attribution="MTA Headquarters, New York City Transit" t:url=https://data.ny.gov/api/views/v5y5-mwpb

property e:v5y5-mwpb t:meta.view v:id=v5y5-mwpb v:category=Transportation v:attributionLink=http://www.mta.info/developers/download.html v:averageRating=0 v:name="Turnstile Usage Data: 2017" v:attribution="MTA Headquarters, New York City Transit"

property e:v5y5-mwpb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:v5y5-mwpb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:v5y5-mwpb t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| c_a  | unit | scp      | station | line_name | division | date                | time     | description | entries | exits   | 
| ==== | ==== | ======== | ======= | ========= | ======== | =================== | ======== | =========== | ======= | ======= | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2016-12-31T00:00:00 | 03:00:00 | REGULAR     | 5991546 | 2028378 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2016-12-31T00:00:00 | 07:00:00 | REGULAR     | 5991565 | 2028389 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2016-12-31T00:00:00 | 11:00:00 | REGULAR     | 5991644 | 2028441 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2016-12-31T00:00:00 | 15:00:00 | REGULAR     | 5991971 | 2028502 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2016-12-31T00:00:00 | 19:00:00 | REGULAR     | 5992418 | 2028543 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2016-12-31T00:00:00 | 23:00:00 | REGULAR     | 5992638 | 2028572 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2017-01-01T00:00:00 | 03:00:00 | REGULAR     | 5992718 | 2028585 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2017-01-01T00:00:00 | 07:00:00 | REGULAR     | 5992730 | 2028594 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2017-01-01T00:00:00 | 11:00:00 | REGULAR     | 5992776 | 2028636 | 
| A002 | R051 | 02-00-00 | 59 ST   | NQR456W   | BMT      | 2017-01-01T00:00:00 | 15:00:00 | REGULAR     | 5992980 | 2028680 | 
```