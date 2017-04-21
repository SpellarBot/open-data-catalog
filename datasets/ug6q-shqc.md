# Turnstile Usage Data: 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/turnstile-usage-data-2015) |
| Metadata | [Link](https://data.ny.gov/api/views/ug6q-shqc) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ug6q-shqc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ug6q-shqc/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ug6q-shqc |
| Name | Turnstile Usage Data: 2015 |
| Attribution | MTA Headquarters, New York City Transit |
| Category | Transportation |
| Tags | turnstile, subway |
| Created | 2015-02-25T21:28:55Z |
| Publication Date | 2016-01-05T15:35:29Z |

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
series e:ug6q-shqc d:2015-01-04T00:00:00.000Z t:scp=00-00-00 t:line_name=J t:unit=R003 t:time=19:00:00 t:division=BMT t:c_a=J025 t:station="CYPRESS HILLS" t:description=REGULAR m:exits=164769 m:entries=141500

series e:ug6q-shqc d:2015-01-04T00:00:00.000Z t:scp=00-00-00 t:line_name=J t:unit=R003 t:time=19:00:00 t:division=BMT t:c_a=J025 t:station="CYPRESS HILLS" t:description=REGULAR m:exits=164769 m:entries=141500

series e:ug6q-shqc d:2015-01-04T00:00:00.000Z t:scp=02-06-00 t:line_name=25 t:unit=R110 t:time=12:00:00 t:division=IRT t:c_a=R647 t:station="FLATBUSH AVE" t:description=REGULAR m:exits=5163389 m:entries=4060905
```

## Meta Commands

```ls
metric m:entries p:integer l:Entries d:"The cumulative ENTRY register value for a device. This register was initialized during system setup. It is a 10 digit number representing the number of entries on the specific device since its inception. Other forms of initialization may occur upon roll-over of the counter, erasing the memory device containing the register data, and replacing the processing device of the turnstile." t:dataTypeName=number

metric m:exits p:integer l:Exits d:"The cumulative EXITS register value for a device. This register was initialized during system setup. It is a 10 digit number representing the number of entries on the specific device since its inception. Other forms of initialization may occur upon roll-over of the counter, erasing the memory device containing the register data, and replacing the processing device of the turnstile." t:dataTypeName=number

entity e:ug6q-shqc l:"Turnstile Usage Data: 2015" t:attribution="MTA Headquarters, New York City Transit" t:url=https://data.ny.gov/api/views/ug6q-shqc

property e:ug6q-shqc t:meta.view v:id=ug6q-shqc v:category=Transportation v:attributionLink=http://www.mta.info/developers/download.html v:averageRating=0 v:name="Turnstile Usage Data: 2015" v:attribution="MTA Headquarters, New York City Transit"

property e:ug6q-shqc t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ug6q-shqc t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ug6q-shqc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| c_a  | unit | scp      | station       | line_name | division | date                | time     | description | entries  | exits   | 
| ==== | ==== | ======== | ============= | ========= | ======== | =================== | ======== | =========== | ======== | ======= | 
| J025 | R003 | 00-00-00 | CYPRESS HILLS | J         | BMT      | 2015-01-04T00:00:00 | 19:00:00 | REGULAR     | 141500   | 164769  | 
| J025 | R003 | 00-00-00 | CYPRESS HILLS | J         | BMT      | 2015-01-04T00:00:00 | 19:00:00 | REGULAR     | 141500   | 164769  | 
| R647 | R110 | 02-06-00 | FLATBUSH AVE  | 25        | IRT      | 2015-01-04T00:00:00 | 12:00:00 | REGULAR     | 4060905  | 5163389 | 
| R647 | R110 | 02-06-00 | FLATBUSH AVE  | 25        | IRT      | 2015-01-04T00:00:00 | 12:00:00 | REGULAR     | 4060905  | 5163389 | 
| E005 | R247 | 00-00-00 | 55 ST         | D         | BMT      | 2015-01-08T00:00:00 | 15:00:00 | REGULAR     | 5732632  | 3581166 | 
| E005 | R247 | 00-00-00 | 55 ST         | D         | BMT      | 2015-01-08T00:00:00 | 15:00:00 | REGULAR     | 5732632  | 3581166 | 
| N025 | R102 | 01-00-04 | 125 ST        | ACBD      | IND      | 2015-01-30T00:00:00 | 19:00:00 | REGULAR     | 6620983  | 2967213 | 
| J025 | R003 | 00-00-02 | CYPRESS HILLS | J         | BMT      | 2015-01-21T00:00:00 | 19:00:00 | REGULAR     | 3749371  | 2408124 | 
| N090 | R139 | 01-00-00 | CANAL ST      | ACE       | IND      | 2015-01-29T00:00:00 | 03:00:00 | REGULAR     | 843099   | 8970807 | 
| R111 | R027 | 00-03-01 | WALL ST       | 23        | IRT      | 2015-01-04T00:00:00 | 19:00:00 | REGULAR     | 10440698 | 3765920 | 
```