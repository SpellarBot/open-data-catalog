# Cemeteries Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cemeteries-location) |
| Metadata | [Link](https://data.austintexas.gov/api/views/a2zj-3chk) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/a2zj-3chk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/a2zj-3chk/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | a2zj-3chk |
| Name | Cemeteries Location |
| Category | Government |
| Created | 2015-09-22T17:16:29Z |
| Publication Date | 2015-09-22T17:17:46Z |

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | city_cemeteries | CITY CEMETERIES | text      | text        |
| Yes      | series tag  | designation     | Designation     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a2zj-3chk d:2015-09-22T10:16:55.000Z t:designation="National Register of Historic Places, Historic Texas Cemetery, Austin Landmark" t:city_cemeteries="Oakwood Cemetery" m:row_number.a2zj-3chk=1

series e:a2zj-3chk d:2015-09-22T10:16:55.000Z t:designation="Historic Texas Cemetery" t:city_cemeteries="Austin Memorial Park Cemetery" m:row_number.a2zj-3chk=2

series e:a2zj-3chk d:2015-09-22T10:16:55.000Z t:city_cemeteries="Evergreen Cemetery" m:row_number.a2zj-3chk=3
```

## Meta Commands

```ls
metric m:row_number.a2zj-3chk p:long l:"Row Number"

entity e:a2zj-3chk l:"Cemeteries Location" t:url=https://data.austintexas.gov/api/views/a2zj-3chk

property e:a2zj-3chk t:meta.view v:id=a2zj-3chk v:category=Government v:attributionLink=http://www.austintexas.gov/department/cemeteries v:averageRating=0 v:name="Cemeteries Location"

property e:a2zj-3chk t:meta.view.license v:name="Public Domain"

property e:a2zj-3chk t:meta.view.owner v:id=wpqw-45f6 v:screenName=Betty v:displayName=Betty

property e:a2zj-3chk t:meta.view.tableauthor v:id=wpqw-45f6 v:screenName=Betty v:roleName=editor v:displayName=Betty
```

## Top Records

```ls
| :updated_at | city_cemeteries               | designation                                                                    | 
| =========== | ============================= | ============================================================================== | 
| 1442917015  | Oakwood Cemetery              | National Register of Historic Places, Historic Texas Cemetery, Austin Landmark | 
| 1442917015  | Austin Memorial Park Cemetery | Historic Texas Cemetery                                                        | 
| 1442917015  | Evergreen Cemetery            |                                                                                | 
| 1442917015  | Plummers Cemetery             |                                                                                | 
| 1442917015  | Oakwood Annex                 | National Register of Historic Places, Austin Landmark                          | 
```