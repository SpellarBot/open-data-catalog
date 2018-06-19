# Directory of Criminal Justice Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-criminal-justice-agencies) |
| Metadata | [Link](https://data.ny.gov/api/views/gugp-n5ip) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/gugp-n5ip/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/gugp-n5ip/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | gugp-n5ip |
| Name | Directory of Criminal Justice Agencies |
| Attribution | Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | public safety, law enforcement directory |
| Created | 2014-01-13T17:15:30Z |
| Publication Date | 2016-04-21T20:20:35Z |

## Description

A directory of the Criminal Justice Agencies located in New York State.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | case_id         | Case ID         | text      | number      |
| Yes      | series tag  | agency          | Agency          | text      | text        |
| No       |             | nominal_address | Nominal Address | text      | text        |
| Yes      | series tag  | street_address  | Street Address  | text      | text        |
| Yes      | series tag  | po_box          | PO Box          | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | state           | State           | text      | text        |
| Yes      | series tag  | zip             | Zip             | text      | text        |
| Yes      | series tag  | telephone       | Telephone       | text      | text        |
| Yes      | series tag  | county          | County          | text      | text        |
| Yes      | series tag  | agency_category | Agency Category | text      | text        |
| Yes      | series tag  | agency_type     | Agency Type     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = nominal_address
```

## Data Commands

```ls
series e:gugp-n5ip d:2016-04-19T09:58:24.000Z t:agency_type="Multi-Jurisdictional Agencies" t:zip=12228 t:county=Albany t:state=NY t:case_id=1515 t:agency="NYS DMV Division of Field Investigation" t:street_address="6 Empire State Plaza, Rm 431" t:telephone="(518) 474-8805" t:agency_category="NYS DMV Division of Field Investigation" t:city=Albany m:row_number.gugp-n5ip=1

series e:gugp-n5ip d:2016-04-19T09:58:24.000Z t:agency_type="Multi-Jurisdictional Agencies" t:zip=12228 t:county=Albany t:state=NY t:case_id=1516 t:agency="NYS DMV Division of Field Investigation" t:street_address="6 Empire State Plaza, Rm 430" t:telephone="(518) 473-6470" t:agency_category="NYS DMV Division of Field Investigation" t:city=Albany m:row_number.gugp-n5ip=2

series e:gugp-n5ip d:2016-04-19T09:58:24.000Z t:agency_type="Multi-Jurisdictional Agencies" t:zip=11492 t:county=Queens t:state=NY t:case_id=1524 t:agency="NYS DMV Division of Field Investigation" t:street_address="212-19 99th Street" t:telephone="(718) 468-0690" t:agency_category="NYS DMV Division of Field Investigation" t:city="Queens Village" m:row_number.gugp-n5ip=3
```

## Meta Commands

```ls
metric m:row_number.gugp-n5ip p:long l:"Row Number"

entity e:gugp-n5ip l:"Directory of Criminal Justice Agencies" t:attribution="Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/gugp-n5ip

property e:gugp-n5ip t:meta.view v:id=gugp-n5ip v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/crimnet/ojsa/agdir/index.html v:averageRating=0 v:name="Directory of Criminal Justice Agencies" v:attribution="Division of Criminal Justice Services"

property e:gugp-n5ip t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:gugp-n5ip t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:gugp-n5ip t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | case_id | agency                                  | nominal_address                        | street_address               | po_box       | city           | state | zip   | telephone      | county   | agency_category                         | agency_type                   | 
| =========== | ======= | ======================================= | ====================================== | ============================ | ============ | ============== | ===== | ===== | ============== | ======== | ======================================= | ============================= | 
| 1461059904  | 1515    | NYS DMV Division of Field Investigation | License & Registration Crimes Unit     | 6 Empire State Plaza, Rm 431 |              | Albany         | NY    | 12228 | (518) 474-8805 | Albany   | NYS DMV Division of Field Investigation | Multi-Jurisdictional Agencies | 
| 1461059904  | 1516    | NYS DMV Division of Field Investigation | Frauds & Facial Recognition Unit       | 6 Empire State Plaza, Rm 430 |              | Albany         | NY    | 12228 | (518) 473-6470 | Albany   | NYS DMV Division of Field Investigation | Multi-Jurisdictional Agencies | 
| 1461059904  | 1524    | NYS DMV Division of Field Investigation | NYC Metro Region 2 - Auto Theft Office | 212-19 99th Street           |              | Queens Village | NY    | 11492 | (718) 468-0690 | Queens   | NYS DMV Division of Field Investigation | Multi-Jurisdictional Agencies | 
| 1461059904  | 31      | Allegany County STOP DWI Program        |                                        | 5435C- County Road #48       |              | Belmont        | NY    | 14813 | (585) 268-5394 | Allegany | Stop DWI Programs                       | Law Enforcement Support       | 
| 1461059904  | 54      | Attica Correctional Facility            |                                        | 639 Exchange Street          |              | Attica         | NY    | 14011 | (585) 591-2000 | Wyoming  | NYS Correctional Facilities & Camps     | Corrections/Parole/Probation  | 
| 1461059904  | 73      | Beacon Correctional Facility            |                                        | 50 Camp Beacon Road          | P.O. Box 780 | Beacon         | NY    | 12508 | (845) 831-4200 | Dutchess | NYS Correctional Facilities & Camps     | Corrections/Parole/Probation  | 
| 1461059904  | 86      | Brant Town Police Department            | Brant Town Hall                        | 1294 STHY 249                | P.O. Box 251 | Brant          | NY    | 14027 | (716) 549-4040 | Erie     | Police                                  | Police and Sheriff            | 
| 1461059904  | 88      | Brewster Village Police Department      |                                        | 50 East Main Street          |              | Brewster       | NY    | 10509 | (845) 279-3618 | Putnam   | Police                                  | Police and Sheriff            | 
| 1461059904  | 101     | Brookwood Secure Center                 | Spookrock Road                         | 419 County Route 29          | P.O. Box 265 | Claverack      | NY    | 12513 | (518) 851-3211 | Columbia | Children and Family Services            | Youth Bureaus                 | 
| 1461059904  | 117     | Cairo Town Police Department            |                                        | 123 Angelo Canna Park        | P.O. Box 728 | Cairo          | NY    | 12413 | (518) 622-2324 | Greene   | Police                                  | Police and Sheriff            | 
```