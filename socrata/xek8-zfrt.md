# Health Insurance Premiums on Policies Written in New York Annually

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-insurance-premiums-on-policies-written-in-new-york-annually-2011) |
| Metadata | [Link](https://data.ny.gov/api/views/xek8-zfrt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xek8-zfrt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xek8-zfrt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xek8-zfrt |
| Name | Health Insurance Premiums on Policies Written in New York Annually |
| Attribution | New York State Department of Financial Services |
| Category | Economic Development |
| Tags | health insurance, premiums written |
| Created | 2013-02-28T19:44:34Z |
| Publication Date | 2016-11-29T20:19:51Z |

## Description

Health Insurance Premiums on Policies Written in New York Annually

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | type_of_insurer | Type of Insurer | text      | text        |
| Yes      | series tag     | company_name    | Company Name    | text      | text        |
| Yes      | time           | year            | Year            | number    | text        |
| Yes      | numeric metric | assets          | Assets          | number    | number      |
| Yes      | numeric metric | liabilities     | Liabilities     | number    | number      |
| Yes      | series tag     | premium_written | Premium Written | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xek8-zfrt d:2015-01-01T00:00:00.000Z t:type_of_insurer=HMO t:company_name="Aetna Health Inc." t:premium_written=293,883,999 m:assets=275955315 m:liabilities=77570118

series e:xek8-zfrt d:2015-01-01T00:00:00.000Z t:type_of_insurer=AH t:company_name="Aetna Health Insurance Company of New York" t:premium_written=485,752 m:assets=10493738 m:liabilities=328989

series e:xek8-zfrt d:2015-01-01T00:00:00.000Z t:type_of_insurer=HMO t:company_name="Alphacare of New York, Inc." t:premium_written=102,422,039 m:assets=48214356 m:liabilities=33222618
```

## Meta Commands

```ls
metric m:assets p:long l:Assets t:dataTypeName=number

metric m:liabilities p:long l:Liabilities t:dataTypeName=number

entity e:xek8-zfrt l:"Health Insurance Premiums on Policies Written in New York Annually" t:attribution="New York State Department of Financial Services" t:url=https://data.ny.gov/api/views/xek8-zfrt

property e:xek8-zfrt t:meta.view v:id=xek8-zfrt v:category="Economic Development" v:averageRating=0 v:name="Health Insurance Premiums on Policies Written in New York Annually" v:attribution="New York State Department of Financial Services"

property e:xek8-zfrt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xek8-zfrt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:xek8-zfrt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| type_of_insurer | company_name                                               | year | assets    | liabilities | premium_written | 
| =============== | ========================================================== | ==== | ========= | =========== | =============== | 
| HMO             | Aetna Health Inc.                                          | 2015 | 275955315 | 77570118    | 293,883,999     | 
| AH              | Aetna Health Insurance Company of New York                 | 2015 | 10493738  | 328989      | 485,752         | 
| HMO             | Alphacare of New York, Inc.                                | 2015 | 48214356  | 33222618    | 102,422,039     | 
| AH              | American Independent Network Insurance Company of New York | 2015 | 25380706  | 33660515    | 2,468,022       | 
| HMO             | Atlantis Health Plan, Inc.                                 | 2015 | 2194154   | 3268496     | 3,843,973       | 
| HMO             | Capital District Physicians Health Plan                    | 2015 | 478711918 | 185857197   | 1,513,146,241   | 
| AH              | Care Improvement Plus of South Central Insurance Company   | 2015 | 900901751 | 585750014   | -               | 
| AH              | Care Improvement Plus of TX Ins Co                         | 2015 | 377003795 | 236497007   | -17,464         | 
| HMO             | Catholic Special Needs Plan, LLC                           | 2015 | 14859537  | 9086708     | 46,182,621      | 
| A43             | CDPHP Universal Benefits, Inc.                             | 2015 | 176197487 | 94173086    | 786,344,128     | 
```