# Ability To Speak English By Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ability-to-speak-english-by-race-db919) |
| Metadata | [Link](https://data.hawaii.gov/api/views/avad-trha) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/avad-trha/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/avad-trha/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | avad-trha |
| Name | Ability To Speak English By Race |
| Attribution | Office of Language Access |
| Category | Culture and Recreation |
| Tags | race, english |
| Created | 2012-09-06T01:44:30Z |
| Publication Date | 2012-09-06T01:47:19Z |

## Description

(Excluding those less than 5 years old or speak only English) Hawaii?s Limited English Proficient (LEP) Population: A Demographic and Socio-Economic Profile

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | race        | Race       | text      | text        |
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
series e:avad-trha d:2012-09-05T18:44:32.000Z t:race="While alone" m:not_at_all=82 m:well=2196 m:not_well=1106

series e:avad-trha d:2012-09-05T18:44:32.000Z t:race="Asian alone" m:not_at_all=4065 m:well=65043 m:not_well=43183

series e:avad-trha d:2012-09-05T18:44:32.000Z t:race="Native Hawaiian & other Pacific Islander alone" m:not_at_all=203 m:well=7325 m:not_well=2560
```

## Meta Commands

```ls
metric m:well p:integer l:Well t:dataTypeName=number

metric m:not_well p:integer l:"Not Well" t:dataTypeName=number

metric m:not_at_all p:integer l:"Not at All" t:dataTypeName=number

entity e:avad-trha l:"Ability To Speak English By Race" t:attribution="Office of Language Access" t:url=https://data.hawaii.gov/api/views/avad-trha

property e:avad-trha t:meta.view v:id=avad-trha v:category="Culture and Recreation" v:attributionLink=http://hawaii.gov/dlir v:averageRating=0 v:name="Ability To Speak English By Race" v:attribution="Office of Language Access"

property e:avad-trha t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:avad-trha t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:avad-trha t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | race                                           | well  | not_well | not_at_all | 
| =========== | ============================================== | ===== | ======== | ========== | 
| 1346870672  | While alone                                    | 2196  | 1106     | 82         | 
| 1346870672  | Asian alone                                    | 65043 | 43183    | 4065       | 
| 1346870672  | Native Hawaiian & other Pacific Islander alone | 7325  | 2560     | 203        | 
| 1346870672  | Other races alone                              | 826   | 1028     | 35         | 
| 1346870672  | Two or more major race groups                  | 2388  | 721      | 0          | 
```