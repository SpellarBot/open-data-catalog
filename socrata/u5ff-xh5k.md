# Ability To Speak English By Nativity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ability-to-speak-english-by-nativity-d3157) |
| Metadata | [Link](https://data.hawaii.gov/api/views/u5ff-xh5k) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/u5ff-xh5k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/u5ff-xh5k/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | u5ff-xh5k |
| Name | Ability To Speak English By Nativity |
| Attribution | Office of Language Access |
| Category | Culture and Recreation |
| Tags | native, english |
| Created | 2012-09-06T01:40:31Z |
| Publication Date | 2012-09-06T01:43:28Z |

## Description

(Excluding those less than 5 years old or speak only English) Hawaii?s Limited English Proficient (LEP) Population: A Demographic and Socio-Economic Profile

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | nativity    | Nativity   | text      | text        |
| Yes      | numeric metric | well        | Well       | number    | number      |
| Yes      | numeric metric | not_well    | Not Well   | number    | number      |
| Yes      | numeric metric | not_at_all  | Not at All | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u5ff-xh5k d:2012-09-05T18:40:32.000Z t:nativity=Native m:not_at_all=268 m:well=14944 m:not_well=7346

series e:u5ff-xh5k d:2012-09-05T18:40:32.000Z t:nativity="Foreign born" m:not_at_all=4117 m:well=62834 m:not_well=41252
```

## Meta Commands

```ls
metric m:well p:integer l:Well t:dataTypeName=number

metric m:not_well p:integer l:"Not Well" t:dataTypeName=number

metric m:not_at_all p:integer l:"Not at All" t:dataTypeName=number

entity e:u5ff-xh5k l:"Ability To Speak English By Nativity" t:attribution="Office of Language Access" t:url=https://data.hawaii.gov/api/views/u5ff-xh5k

property e:u5ff-xh5k t:meta.view v:id=u5ff-xh5k v:category="Culture and Recreation" v:attributionLink=http://hawaii.gov/dlir v:averageRating=0 v:name="Ability To Speak English By Nativity" v:attribution="Office of Language Access"

property e:u5ff-xh5k t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:u5ff-xh5k t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:u5ff-xh5k t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | nativity     | well  | not_well | not_at_all | 
| =========== | ============ | ===== | ======== | ========== | 
| 1346870432  | Native       | 14944 | 7346     | 268        | 
| 1346870432  | Foreign born | 62834 | 41252    | 4117       | 
```