# Directory of Public Authorities

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/4vym-q77x/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/directory-of-public-authorities)
* Id = 4vym-q77x
* Name = Directory of Public Authorities
* Attribution = Authorities Budget Office
* Attribution Link = http://www.abo.ny.gov/
* Category = Transparency
* Tags = [public authority, address, website, integrity]
* Created = 2013-04-16T19:45:46Z
* Publication Date = 2015-08-28T22:17:56Z
* Rows Updated = 2015-08-28T22:17:43Z

## Description

The Authorities Budget Office is required by Section 6(b) of Public Authorities Law to maintain a comprehensive inventory of state and local authorities.  State authorities are defined as public authorities with one or more board member appointed by the governor, other than interstate or international authorities.  Local authorities are public authorities with no members appointed by the governor; not-for-profit corporations affiliated with, sponsored by, or created by a municipality; industrial development agencies or authorities; or any affiliate of any local authority.

## Columns

```ls
| Name                  | Field Name            | Data Type | Render Type | Schema Type    | Included | 
| ===================== | ===================== | ========= | =========== | ============== | ======== | 
| updated_at            | :updated_at           | meta_data | meta_data   | time           | Yes      | 
| Public Authority Type | public_authority_type | text      | text        | series tag     | Yes      | 
| Public Authority Name | public_authority_name | text      | text        | series tag     | Yes      | 
| Address               | address               | text      | text        |                | No       | 
| City                  | city                  | text      | text        | series tag     | Yes      | 
| State                 | state                 | text      | text        | series tag     | Yes      | 
| Zip                   | zip                   | number    | text        | numeric metric | Yes      | 
| Website               | website               | url       | url         | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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
series e:4vym-q77x d:2015-08-28T15:17:39.000Z t:state=NY t:public_authority_type=State t:public_authority_name="Agriculture and New York State Horse Breeding Development Fund" t:city=SCHENECTADY m:zip=12305

series e:4vym-q77x d:2015-08-28T15:17:39.000Z t:state=NY t:public_authority_type="Local - IDA" t:public_authority_name="Albany City Industrial Development Agency" t:city=ALBANY m:zip=12207

series e:4vym-q77x d:2015-08-28T15:17:39.000Z t:state=NY t:public_authority_type=Local t:public_authority_name="Albany Community Development Agency" t:city=ALBANY m:zip=12210
```

## Meta Commands

```ls
metric m:zip p:integer l:Zip d:"Zip Code of the location of the public authority?s primary office" t:dataTypeName=number

entity e:4vym-q77x l:"Directory of Public Authorities" t:attribution="Authorities Budget Office" t:url=https://data.ny.gov/api/views/4vym-q77x

property e:4vym-q77x t:meta.view d:2017-03-03T14:36:43.751Z v:id=4vym-q77x v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Directory of Public Authorities" v:attribution="Authorities Budget Office"

property e:4vym-q77x t:meta.view.owner d:2017-03-03T14:36:43.751Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4vym-q77x t:meta.view.tableauthor d:2017-03-03T14:36:43.751Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4vym-q77x t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:36:43.751Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```