# Cook County State's Attorney--Staff Using Crimes As Role Types

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-states-attorney-staff-using-crimes-as-role-types-c73bd) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/xe52-c6ij) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xe52-c6ij/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xe52-c6ij/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | xe52-c6ij |
| Name | Cook County State's Attorney--Staff Using Crimes As Role Types |
| Attribution | Cook County State's Attorney |
| Category | Courts |
| Created | 2011-09-20T23:01:10Z |
| Publication Date | 2014-10-27T16:44:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | role_type                        | ROLE TYPE                        | text      | text        |
| Yes      | numeric metric | staff_using_crimes_as_role_types | Staff Using Crimes as Role Types | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xe52-c6ij d:2011-09-20T16:01:12.000Z t:role_type=ADMINISTRATIVE m:staff_using_crimes_as_role_types=224

series e:xe52-c6ij d:2011-09-20T16:01:12.000Z t:role_type=ASA m:staff_using_crimes_as_role_types=500

series e:xe52-c6ij d:2011-09-20T16:01:12.000Z t:role_type=INVESTIGATIONS m:staff_using_crimes_as_role_types=100
```

## Meta Commands

```ls
metric m:staff_using_crimes_as_role_types p:integer l:"Staff Using Crimes as Role Types" t:dataTypeName=number

entity e:xe52-c6ij l:"Cook County State's Attorney--Staff Using Crimes As Role Types" t:attribution="Cook County State's Attorney" t:url=https://datacatalog.cookcountyil.gov/api/views/xe52-c6ij

property e:xe52-c6ij t:meta.view v:id=xe52-c6ij v:category=Courts v:averageRating=0 v:name="Cook County State's Attorney--Staff Using Crimes As Role Types" v:attribution="Cook County State's Attorney"

property e:xe52-c6ij t:meta.view.license v:name="Public Domain"

property e:xe52-c6ij t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:xe52-c6ij t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | role_type           | staff_using_crimes_as_role_types | 
| =========== | =================== | ================================ | 
| 1316534472  | ADMINISTRATIVE      | 224                              | 
| 1316534472  | ASA                 | 500                              | 
| 1316534472  | INVESTIGATIONS      | 100                              | 
| 1316534472  | VICTIM WITNESS SVCS | 36                               | 
| 1316534472  | TOTAL AGGREGATE     | 860                              | 
```