# IDPH ASBESTOS LICENSED CONTRACTORS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-asbestos-licensed-contractors-a3b2f) |
| Metadata | [Link](https://data.illinois.gov/api/views/5vh3-wnad) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5vh3-wnad/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5vh3-wnad/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5vh3-wnad |
| Name | IDPH ASBESTOS LICENSED CONTRACTORS |
| Attribution | Illinois Department of Public Health, Division of Environmental Health |
| Category | Public Health |
| Tags | asbestos, contractors, idph, license |
| Created | 2013-09-10T16:31:18Z |
| Publication Date | 2017-03-22T19:22:01Z |
| Rows Updated | 2017-03-22T19:21:54Z |

## Description

Asbestos Licensed Contractors are responsible for conducting asbestos abatement projects. All contractors who conduct asbestos abatement projects must have current insurance and are required to be licensed

Last Updated: February 2017

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag  | contractor_name           | CONTRACTOR NAME           | text          | text          |
| No       |             | address                   | ADDRESS                   | text          | text          |
| Yes      | series tag  | city                      | CITY                      | text          | text          |
| Yes      | series tag  | state                     | STATE                     | text          | text          |
| Yes      | series tag  | zip_code                  | ZIP CODE                  | text          | text          |
| Yes      | series tag  | county                    | COUNTY                    | text          | text          |
| Yes      | series tag  | contact_person            | CONTACT PERSON            | text          | text          |
| Yes      | series tag  | residential_removal       | RESIDENTIAL REMOVAL       | text          | text          |
| No       |             | insurance_expiration_date | INSURANCE EXPIRATION DATE | text          | text          |
| Yes      | series tag  | phone                     | PHONE                     | text          | number        |
| Yes      | series tag  | fax                       | FAX                       | text          | number        |
| Yes      | series tag  | email                     | EMAIL                     | email         | email         |
| Yes      | time        | license_expiration_date   | License Expiration Date   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = license_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,insurance_expiration_date
```

## Data Commands

```ls
series e:5vh3-wnad d:2017-05-15T00:00:00.000Z t:zip_code=63130 t:contractor_name="06 ENVIRONMENTAL SERVICES, INC." t:state=MO t:contact_person="DAN GIESLER" t:city="ST. LOUIS" m:row_number.5vh3-wnad=1

series e:5vh3-wnad d:2017-05-15T00:00:00.000Z t:zip_code=60514 t:contractor_name="1ST ALL AROUND COMPANY" t:email=1STALLAROUND@GMAIL.COM t:state=IL t:contact_person="MARCIN SWIERZOWSKI" t:residential_removal=YES t:city="CLARENDON HILLS" m:row_number.5vh3-wnad=2

series e:5vh3-wnad d:2017-05-15T00:00:00.000Z t:zip_code=62832 t:contractor_name="A & A ABATEMENT LLC" t:county=Perry t:email=roger.harsy@yahoo.com t:state=IL t:residential_removal=YES t:city="DU QUOIN" m:row_number.5vh3-wnad=3
```

## Meta Commands

```ls
metric m:row_number.5vh3-wnad p:long l:"Row Number"

entity e:5vh3-wnad l:"IDPH ASBESTOS LICENSED CONTRACTORS" t:attribution="Illinois Department of Public Health, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/5vh3-wnad

property e:5vh3-wnad t:meta.view v:id=5vh3-wnad v:category="Public Health" v:attributionLink=http://www.dph.illinois.gov/topics-services/environmental-health-protection/abatement-structures-migrant-labor/asbestos v:averageRating=0 v:name="IDPH ASBESTOS LICENSED CONTRACTORS" v:attribution="Illinois Department of Public Health, Division of Environmental Health"

property e:5vh3-wnad t:meta.view.license v:name="Public Domain"

property e:5vh3-wnad t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:5vh3-wnad t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```