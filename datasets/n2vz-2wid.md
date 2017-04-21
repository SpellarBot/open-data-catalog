# L&I Counties Listed On Affidavit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-counties-listed-on-affidavit) |
| Metadata | [Link](https://data.wa.gov/api/views/n2vz-2wid) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/n2vz-2wid/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/n2vz-2wid/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | n2vz-2wid |
| Name | L&I Counties Listed On Affidavit |
| Attribution | L&I |
| Category | Labor |
| Tags | affidavit, county, work |
| Created | 2015-11-05T20:21:54Z |
| Publication Date | 2015-12-07T20:06:23Z |

## Description

Counties Listed On Affidavit

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type | Render Type |
| ======== | =========== | ========================== | ========================== | ========= | =========== |
| No       | time        | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | affidavit_id_number        | Affidavit ID Number        | text      | number      |
| Yes      | series tag  | county_listed_on_affidavit | County Listed On Affidavit | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:n2vz-2wid d:2015-11-05T12:21:56.000Z t:county_listed_on_affidavit=Cowlitz t:affidavit_id_number=25 m:row_number.n2vz-2wid=1

series e:n2vz-2wid d:2015-11-05T12:21:56.000Z t:county_listed_on_affidavit=Cowlitz t:affidavit_id_number=30 m:row_number.n2vz-2wid=2

series e:n2vz-2wid d:2015-11-05T12:21:56.000Z t:county_listed_on_affidavit=Cowlitz t:affidavit_id_number=33 m:row_number.n2vz-2wid=3
```

## Meta Commands

```ls
metric m:row_number.n2vz-2wid p:long l:"Row Number"

entity e:n2vz-2wid l:"L&I Counties Listed On Affidavit" t:attribution=L&I t:url=https://data.wa.gov/api/views/n2vz-2wid

property e:n2vz-2wid t:meta.view v:id=n2vz-2wid v:category=Labor v:averageRating=0 v:name="L&I Counties Listed On Affidavit" v:attribution=L&I

property e:n2vz-2wid t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:n2vz-2wid t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```

## Top Records

```ls
| :updated_at | affidavit_id_number | county_listed_on_affidavit | 
| =========== | =================== | ========================== | 
| 1446726116  | 25                  | Cowlitz                    | 
| 1446726116  | 30                  | Cowlitz                    | 
| 1446726116  | 33                  | Cowlitz                    | 
| 1446726116  | 34                  | Cowlitz                    | 
| 1446726116  | 36                  | Cowlitz                    | 
| 1446726116  | 59                  | Spokane                    | 
| 1446726117  | 92                  | Spokane                    | 
| 1446726117  | 93                  | Spokane                    | 
| 1446726117  | 94                  | Spokane                    | 
| 1446726117  | 102                 | Walla Walla                | 
```