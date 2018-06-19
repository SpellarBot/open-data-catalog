# Ability To Speak English By Age

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ability-to-speak-english-by-age-7669a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ri9m-brxc) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ri9m-brxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ri9m-brxc/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ri9m-brxc |
| Name | Ability To Speak English By Age |
| Attribution | Office of Language Access |
| Category | Culture and Recreation |
| Tags | age, language |
| Created | 2012-09-06T01:10:49Z |
| Publication Date | 2012-09-06T01:18:11Z |

## Description

(Excluding those less than 5 years old or speak only English) HAWAII?S LIMITED ENGLISH PROFICIENT (LEP) POPULATION: A DEMOGRAPHIC AND SOCIO-ECONOMIC PROFILE (2007)

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | age         | Age        | text      | text        |
| Yes      | numeric metric | well        | Well       | number    | number      |
| Yes      | numeric metric | not_well    | Not Well   | number    | number      |
| Yes      | numeric metric | not_at_all  | Not At All | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ri9m-brxc d:2012-09-05T18:10:51.000Z t:age="19 years or under" m:not_at_all=24 m:well=8214 m:not_well=2862

series e:ri9m-brxc d:2012-09-05T18:10:51.000Z t:age="20-39 years old" m:not_at_all=557 m:well=19036 m:not_well=10089

series e:ri9m-brxc d:2012-09-05T18:10:51.000Z t:age="40-59 years old" m:not_at_all=1918 m:well=28925 m:not_well=14003
```

## Meta Commands

```ls
metric m:well p:integer l:Well t:dataTypeName=number

metric m:not_well p:integer l:"Not Well" t:dataTypeName=number

metric m:not_at_all p:integer l:"Not At All" t:dataTypeName=number

entity e:ri9m-brxc l:"Ability To Speak English By Age" t:attribution="Office of Language Access" t:url=https://data.hawaii.gov/api/views/ri9m-brxc

property e:ri9m-brxc t:meta.view v:id=ri9m-brxc v:category="Culture and Recreation" v:attributionLink=http://hawaii.gov/dlir v:averageRating=0 v:name="Ability To Speak English By Age" v:attribution="Office of Language Access"

property e:ri9m-brxc t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ri9m-brxc t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:ri9m-brxc t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | age                | well  | not_well | not_at_all | 
| =========== | ================== | ===== | ======== | ========== | 
| 1346868651  | 19 years or under  | 8214  | 2862     | 24         | 
| 1346868651  | 20-39 years old    | 19036 | 10089    | 557        | 
| 1346868651  | 40-59 years old    | 28925 | 14003    | 1918       | 
| 1346868651  | 60-79 years old    | 15634 | 15417    | 895        | 
| 1346868651  | 80 years and above | 5969  | 6227     | 991        | 
```