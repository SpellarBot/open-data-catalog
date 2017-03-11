# IDPH ASBESTOS LICENSED CONTRACTORS

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/5vh3-wnad/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/idph-asbestos-licensed-contractors-a3b2f)
* [Metadata URL](https://data.illinois.gov/api/views/5vh3-wnad)
* Id = 5vh3-wnad
* Name = IDPH ASBESTOS LICENSED CONTRACTORS
* Attribution = Illinois Department of Public Health, Division of Environmental Health
* [Attribution Link](http://www.dph.illinois.gov/topics-services/environmental-health-protection/abatement-structures-migrant-labor/asbestos)
* Category = Public Health
* Tags = [asbestos, contractors, idph, license]
* Created = 2013-09-10T16:31:18Z
* Publication Date = 2017-03-03T21:16:03Z
* Rows Updated = 2017-03-03T21:15:56Z

## Description

Asbestos Licensed Contractors are responsible for conducting asbestos abatement projects. All contractors who conduct asbestos abatement projects must have current insurance and are required to be licensed

Last Updated: February 2017

## Columns

```ls
| Name                      | Field Name                | Data Type     | Render Type   | Schema Type    | Included | 
| ========================= | ========================= | ============= | ============= | ============== | ======== | 
| CONTRACTOR NAME           | contractor_name           | text          | text          | series tag     | Yes      | 
| ADDRESS                   | address                   | text          | text          |                | No       | 
| CITY                      | city                      | text          | text          | series tag     | Yes      | 
| STATE                     | state                     | text          | text          | series tag     | Yes      | 
| ZIP CODE                  | zip_code                  | text          | text          | series tag     | Yes      | 
| COUNTY                    | county                    | text          | text          | series tag     | Yes      | 
| CONTACT PERSON            | contact_person            | text          | text          | series tag     | Yes      | 
| RESIDENTIAL REMOVAL       | residential_removal       | text          | text          | series tag     | Yes      | 
| INSURANCE EXPIRATION DATE | insurance_expiration_date | text          | text          | series tag     | Yes      | 
| PHONE                     | phone                     | number        | number        | numeric metric | Yes      | 
| FAX                       | fax                       | number        | number        | numeric metric | Yes      | 
| EMAIL                     | email                     | email         | email         | series tag     | Yes      | 
| License Expiration Date   | license_expiration_date   | calendar_date | calendar_date | time           | Yes      | 
```

## Time Field

```ls
Value = license_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = address
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
metric m:phone p:long l:PHONE t:dataTypeName=number

metric m:fax p:long l:FAX t:dataTypeName=number

entity e:5vh3-wnad l:"IDPH ASBESTOS LICENSED CONTRACTORS" t:attribution="Illinois Department of Public Health, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/5vh3-wnad

property e:5vh3-wnad t:meta.view d:2017-03-08T01:16:19.206Z v:id=5vh3-wnad v:category="Public Health" v:attributionLink=http://www.dph.illinois.gov/topics-services/environmental-health-protection/abatement-structures-migrant-labor/asbestos v:averageRating=0 v:name="IDPH ASBESTOS LICENSED CONTRACTORS" v:attribution="Illinois Department of Public Health, Division of Environmental Health"

property e:5vh3-wnad t:meta.view.license d:2017-03-08T01:16:19.206Z v:name="Public Domain"

property e:5vh3-wnad t:meta.view.owner d:2017-03-08T01:16:19.206Z v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"

property e:5vh3-wnad t:meta.view.tableauthor d:2017-03-08T01:16:19.206Z v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```