# Horse Racing Licensing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/horse-racing-licensing) |
| Metadata | [Link](https://data.ny.gov/api/views/cz9u-yj7m) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cz9u-yj7m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cz9u-yj7m/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cz9u-yj7m |
| Name | Horse Racing Licensing |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | horse racing, licensing |
| Created | 2013-02-20T17:31:01Z |
| Publication Date | 2017-04-20T10:15:29Z |

## Description

The Horse Racing Licensing report lists all individuals licensed to compete within New York State.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | person_id   | Person ID   | text          | number        |
| Yes      | series tag  | name        | Name        | text          | text          |
| Yes      | series tag  | occupation  | Occupation  | text          | text          |
| Yes      | series tag  | eligibility | Eligibility | text          | text          |
| Yes      | series tag  | division    | Division    | text          | text          |
| Yes      | series tag  | license     | License     | text          | text          |
| Yes      | time        | expires     | Expires     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = expires
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cz9u-yj7m d:2019-09-19T00:00:00.000Z t:occupation="OWNER RENEWAL" t:division=THOROUGHBRED t:person_id=189894 t:name="JACK G. COLLINS JR" t:eligibility="ABLE TO PARTICIPATE" t:license="LICENSE # 1502041" m:row_number.cz9u-yj7m=1

series e:cz9u-yj7m d:2017-07-05T00:00:00.000Z t:occupation="STABLE EMPLOYEE" t:division=THOROUGHBRED t:person_id=178570 t:name="XAVIER D. GONZALEZ" t:eligibility="ABLE TO PARTICIPATE" t:license="LICENSE # 1495566" m:row_number.cz9u-yj7m=2

series e:cz9u-yj7m d:2018-08-13T00:00:00.000Z t:occupation="GS - TV CREW" t:division=HARNESS t:person_id=52455 t:name="MICHAEL C. SANTASKI" t:eligibility="ABLE TO PARTICIPATE" t:license="LICENSE # 1484279" m:row_number.cz9u-yj7m=3
```

## Meta Commands

```ls
metric m:row_number.cz9u-yj7m p:long l:"Row Number"

entity e:cz9u-yj7m l:"Horse Racing Licensing" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/cz9u-yj7m

property e:cz9u-yj7m t:meta.view v:id=cz9u-yj7m v:category="Government & Finance" v:attributionLink=http://license.gaming.ny.gov/ v:averageRating=0 v:name="Horse Racing Licensing" v:attribution="New York State Gaming Commission"

property e:cz9u-yj7m t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cz9u-yj7m t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cz9u-yj7m t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| person_id | name                | occupation      | eligibility         | division     | license           | expires             | 
| ========= | =================== | =============== | =================== | ============ | ================= | =================== | 
| 189894    | JACK G. COLLINS JR  | OWNER RENEWAL   | ABLE TO PARTICIPATE | THOROUGHBRED | LICENSE # 1502041 | 2019-09-19T00:00:00 | 
| 178570    | XAVIER D. GONZALEZ  | STABLE EMPLOYEE | ABLE TO PARTICIPATE | THOROUGHBRED | LICENSE # 1495566 | 2017-07-05T00:00:00 | 
| 52455     | MICHAEL C. SANTASKI | GS - TV CREW    | ABLE TO PARTICIPATE | HARNESS      | LICENSE # 1484279 | 2018-08-13T00:00:00 | 
| 108336    | ANDREW AARON        | OWNER RENEWAL   | ABLE TO PARTICIPATE | THOROUGHBRED | LICENSE # 1462697 | 2017-07-03T00:00:00 | 
| 126321    | JACALYN F. AARON    | OWNER RENEWAL   | ABLE TO PARTICIPATE | THOROUGHBRED | LICENSE # 1490151 | 2019-03-03T00:00:00 | 
| 146612    | ANABELLA M. ABARCA  | GROOM           | ABLE TO PARTICIPATE | HARNESS      | LICENSE # 1501324 | 2017-09-12T00:00:00 | 
| 189939    | TRINIDAD M. ABARCA  | STABLE EMPLOYEE | ABLE TO PARTICIPATE | THOROUGHBRED | RECEIPT # 1432628 | 2018-04-06T00:00:00 | 
| 195254    | STEPHANIE M. ABARE  | STABLE EMPLOYEE | ABLE TO PARTICIPATE | THOROUGHBRED | LICENSE # 1499995 | 2017-11-03T00:00:00 | 
| 53720     | JOHN ABATO          | OWNER RENEWAL   | ABLE TO PARTICIPATE | THOROUGHBRED | LICENSE # 1502892 | 2019-11-13T00:00:00 | 
| 140929    | ANTHONY ABBATE      | OWNER RENEWAL   | ABLE TO PARTICIPATE | THOROUGHBRED | LICENSE # 1486311 | 2019-03-21T00:00:00 | 
```