# Directory of Public Authorities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-public-authorities) |
| Metadata | [Link](https://data.ny.gov/api/views/4vym-q77x) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4vym-q77x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4vym-q77x/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4vym-q77x |
| Name | Directory of Public Authorities |
| Attribution | Authorities Budget Office |
| Category | Transparency |
| Tags | public authority, address, website, integrity |
| Created | 2013-04-16T19:45:46Z |
| Publication Date | 2015-08-28T22:17:56Z |
| Rows Updated | 2015-08-28T22:17:43Z |

## Description

The Authorities Budget Office is required by Section 6(b) of Public Authorities Law to maintain a comprehensive inventory of state and local authorities.  State authorities are defined as public authorities with one or more board member appointed by the governor, other than interstate or international authorities.  Local authorities are public authorities with no members appointed by the governor; not-for-profit corporations affiliated with, sponsored by, or created by a municipality; industrial development agencies or authorities; or any affiliate of any local authority.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | public_authority_type | Public Authority Type | text      | text        |
| Yes      | series tag  | public_authority_name | Public Authority Name | text      | text        |
| No       |             | address               | Address               | text      | text        |
| Yes      | series tag  | city                  | City                  | text      | text        |
| Yes      | series tag  | state                 | State                 | text      | text        |
| Yes      | series tag  | zip                   | Zip                   | text      | text        |
| Yes      | series tag  | website               | Website               | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:4vym-q77x l:"Directory of Public Authorities" t:attribution="Authorities Budget Office" t:url=https://data.ny.gov/api/views/4vym-q77x

property e:4vym-q77x t:meta.view v:id=4vym-q77x v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Directory of Public Authorities" v:attribution="Authorities Budget Office"

property e:4vym-q77x t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4vym-q77x t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4vym-q77x t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```