# Issued Title V Facility Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/issued-title-v-facility-permits) |
| Metadata | [Link](https://data.ny.gov/api/views/4n3a-en4b) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4n3a-en4b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4n3a-en4b/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4n3a-en4b |
| Name | Issued Title V Facility Permits |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | issued permit, emissions, air pollution, title v |
| Created | 2014-06-30T19:41:32Z |
| Publication Date | 2016-01-08T21:31:44Z |
| Rows Updated | 2016-01-08T21:30:08Z |

## Description

Owners or operators of emission sources that are subject to 6 NYCRR Subpart 201-6 must obtain a Title V facility permit.  

Draft permits are official versions of permits whose initial development is complete, and that are being noticed and made available for public review and comment. 

These permits are prepared by the Division of Air Resources regional staff.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | facility_name      | FACILITY NAME      | text          | text          |
| Yes      | series tag  | permit_id          | PERMIT ID          | text          | text          |
| Yes      | series tag  | url_to_permit_text | URL TO PERMIT TEXT | url           | url           |
| Yes      | series tag  | facility_location  | FACILITY LOCATION  | text          | text          |
| Yes      | series tag  | facility_city      | FACILITY CITY      | text          | text          |
| Yes      | series tag  | facility_state     | FACILITY STATE     | text          | text          |
| Yes      | series tag  | facility_zip       | FACILITY ZIP       | text          | number        |
| Yes      | time        | issue_date         | ISSUE DATE         | calendar_date | calendar_date |
| No       |             | expiration_date    | EXPIRATION DATE    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:4n3a-en4b l:"Issued Title V Facility Permits" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/4n3a-en4b

property e:4n3a-en4b t:meta.view v:id=4n3a-en4b v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/dardata/boss/afs/issued_atv.html v:averageRating=0 v:name="Issued Title V Facility Permits" v:attribution="New York State Department of Environmental Conservation"

property e:4n3a-en4b t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4n3a-en4b t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```