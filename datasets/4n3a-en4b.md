# Issued Title V Facility Permits

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/4n3a-en4b/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/issued-title-v-facility-permits)
* [Metadata URL](https://data.ny.gov/api/views/4n3a-en4b)
* Id = 4n3a-en4b
* Name = Issued Title V Facility Permits
* Attribution = New York State Department of Environmental Conservation
* [Attribution Link](http://www.dec.ny.gov/dardata/boss/afs/issued_atv.html)
* Category = Energy & Environment
* Tags = [issued permit, emissions, air pollution, title v]
* Created = 2014-06-30T19:41:32Z
* Publication Date = 2016-01-08T21:31:44Z
* Rows Updated = 2016-01-08T21:30:08Z

## Description

Owners or operators of emission sources that are subject to 6 NYCRR Subpart 201-6 must obtain a Title V facility permit.  

Draft permits are official versions of permits whose initial development is complete, and that are being noticed and made available for public review and comment. 

These permits are prepared by the Division of Air Resources regional staff.

## Columns

```ls
| Name               | Field Name         | Data Type     | Render Type   | Schema Type | Included | 
| ================== | ================== | ============= | ============= | =========== | ======== | 
| FACILITY NAME      | facility_name      | text          | text          | series tag  | Yes      | 
| PERMIT ID          | permit_id          | text          | text          | series tag  | Yes      | 
| URL TO PERMIT TEXT | url_to_permit_text | url           | url           | series tag  | Yes      | 
| FACILITY LOCATION  | facility_location  | text          | text          | series tag  | Yes      | 
| FACILITY CITY      | facility_city      | text          | text          | series tag  | Yes      | 
| FACILITY STATE     | facility_state     | text          | text          | series tag  | Yes      | 
| FACILITY ZIP       | facility_zip       | text          | number        | series tag  | Yes      | 
| ISSUE DATE         | issue_date         | calendar_date | calendar_date | time        | Yes      | 
| EXPIRATION DATE    | expiration_date    | calendar_date | calendar_date |             | No       | 
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = expiration_date
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:4n3a-en4b l:"Issued Title V Facility Permits" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/4n3a-en4b

property e:4n3a-en4b t:meta.view d:2017-03-08T01:07:27.824Z v:id=4n3a-en4b v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/dardata/boss/afs/issued_atv.html v:averageRating=0 v:name="Issued Title V Facility Permits" v:attribution="New York State Department of Environmental Conservation"

property e:4n3a-en4b t:meta.view.owner d:2017-03-08T01:07:27.824Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4n3a-en4b t:meta.view.tableauthor d:2017-03-08T01:07:27.824Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```