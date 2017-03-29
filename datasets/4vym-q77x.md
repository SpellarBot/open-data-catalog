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
| Publication Date | 2017-03-21T22:01:11Z |

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
series e:4vym-q77x d:2017-03-21T22:01:04.000Z t:zip=12305 t:website=http://www.nysirestakes.com t:state=NY t:public_authority_type=State t:public_authority_name="Agriculture and New York State Horse Breeding Development Fund" t:city=SCHENECTADY m:row_number.4vym-q77x=1

series e:4vym-q77x d:2017-03-21T22:01:04.000Z t:zip=12205 t:website=http://cdrpc.org/programs/water-quality/combined-sewer-overflow-cso/ t:state=NY t:public_authority_type="Local - LDC" t:public_authority_name="Albany CSO Pool Communities Corporation" t:city=ALBANY m:row_number.4vym-q77x=2

series e:4vym-q77x d:2017-03-21T22:01:04.000Z t:zip=12207 t:website=http://www.albanyida.com t:state=NY t:public_authority_type="Local - IDA" t:public_authority_name="Albany City Industrial Development Agency" t:city=ALBANY m:row_number.4vym-q77x=3
```

## Meta Commands

```ls
metric m:row_number.4vym-q77x p:long l:"Row Number"

entity e:4vym-q77x l:"Directory of Public Authorities" t:attribution="Authorities Budget Office" t:url=https://data.ny.gov/api/views/4vym-q77x

property e:4vym-q77x t:meta.view v:id=4vym-q77x v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Directory of Public Authorities" v:attribution="Authorities Budget Office"

property e:4vym-q77x t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4vym-q77x t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4vym-q77x t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | public_authority_type | public_authority_name                                          | address                                           | city        | state | zip   | website                                                                                 | 
| =========== | ===================== | ============================================================== | ================================================= | =========== | ===== | ===== | ======================================================================================= | 
| 1490133664  | State                 | Agriculture and New York State Horse Breeding Development Fund | 1 Broadway Center                                 | SCHENECTADY | NY    | 12305 | [http://www.nysirestakes.com, null]                                                     | 
| 1490133664  | Local - LDC           | Albany CSO Pool Communities Corporation                        | CDRPC, One Park Place, Suite 102                  | ALBANY      | NY    | 12205 | [http://cdrpc.org/programs/water-quality/combined-sewer-overflow-cso/, null]            | 
| 1490133664  | Local - IDA           | Albany City Industrial Development Agency                      | 21 Lodge Street                                   | ALBANY      | NY    | 12207 | [http://www.albanyida.com, null]                                                        | 
| 1490133664  | Local                 | Albany Community Development Agency                            | 200 Henry Johnson Boulevard, Second Floor         | ALBANY      | NY    | 12210 | [http://www.albanyny.org/Government/Departments/DevelopmentandPlanning/ACDA.aspx, null] | 
| 1490133664  | State                 | Albany Convention Center Authority                             | 126 State St.                                     | ALBANY      | NY    | 12207 | [http://www.accany.com, null]                                                           | 
| 1490133664  | Local                 | Albany County Airport Authority                                | Albany International Airport, Admin Bldg Room 204 | ALBANY      | NY    | 12211 | [http://www.albanyairport.com/, null]                                                   | 
| 1490133664  | Local - LDC           | Albany County Business Development Corporation                 | Five Computer Drive South                         | ALBANY      | NY    | 12205 | [null, null]                                                                            | 
| 1490133664  | Local - LDC           | Albany County Capital Resource Corporation                     | 112 State Street , Room 740                       | ALBANY      | NY    | 12207 | [null, null]                                                                            | 
| 1490133664  | Local - IDA           | Albany County Industrial Development Agency                    | 21 Everett Road Extension                         | ALBANY      | NY    | 12205 | [http://www.albanycounty.com/ida/, null]                                                | 
| 1490133664  | Local - LDC           | Albany County Land Bank Corporation                            | 69 State Street, 8th Floor                        | ALBANY      | NY    | 12207 | [http://www.albanycountylandbank.org, null]                                             | 
```