# Depts typeahead data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/depts-typeahead-data-8bfd7) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/mxn5-gsdz) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/mxn5-gsdz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/mxn5-gsdz/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | mxn5-gsdz |
| Name | Depts typeahead data |
| Attribution | King County |
| Category | Website content |
| Tags | typeahead |
| Created | 2013-09-08T01:45:14Z |
| Publication Date | 2013-09-11T00:46:21Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | department  | Department | text      | text        |
| Yes      | series tag  | url         | url        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mxn5-gsdz d:2013-09-07T19:00:26.000Z t:department="Superior Court Local Rules" t:url=/courts/Clerk/Rules.aspx m:row_number.mxn5-gsdz=1

series e:mxn5-gsdz d:2013-09-07T19:03:31.000Z t:department="Prosecuting Attorney" t:url=/Prosecutor.aspx m:row_number.mxn5-gsdz=2

series e:mxn5-gsdz d:2013-09-07T19:03:34.000Z t:department="Property tax assessments" t:url=/operations/Finance/Treasury/PropertyTax/FAQ/Assessment.aspx m:row_number.mxn5-gsdz=3
```

## Meta Commands

```ls
metric m:row_number.mxn5-gsdz p:long l:"Row Number"

entity e:mxn5-gsdz l:"Depts typeahead data" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/mxn5-gsdz

property e:mxn5-gsdz t:meta.view v:id=mxn5-gsdz v:category="Website content" v:averageRating=0 v:name="Depts typeahead data" v:attribution="King County"

property e:mxn5-gsdz t:meta.view.license v:name="Public Domain"

property e:mxn5-gsdz t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:mxn5-gsdz t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | department                                                            | url                                                          | 
| =========== | ===================================================================== | ============================================================ | 
| 1378580426  | Superior Court Local Rules                                            | /courts/Clerk/Rules.aspx                                     | 
| 1378580611  | Prosecuting Attorney                                                  | /Prosecutor.aspx                                             | 
| 1378580614  | Property tax assessments                                              | /operations/Finance/Treasury/PropertyTax/FAQ/Assessment.aspx | 
| 1378580618  | Procurement and Contract Services Section                             | /operations/procurement.aspx                                 | 
| 1378580625  | Permitting and Environmental Review                                   | /healthservices/SubstanceAbuse/Services/Prevention.aspx      | 
| 1378580685  | Noxious Weed Control Program                                          | /environment/animalsAndPlants/noxious-weeds.aspx             | 
| 1378580782  | KingStat                                                              | http://your.kingcounty.gov/dnrp/measures/default.aspx        | 
| 1378580520  | Puget Sound Fresh Program                                             | http://www.pugetsoundfresh.org/                              | 
| 1378580582  | Regional Justice Center - Adult and Juvenile Detention, Kent Division | /courts/detention/adult_detention/RJC.aspx                   | 
| 1378580594  | Records and Licensing Services Division                               | /operations/RALS.aspx                                        | 
```