# Ability To Speak English By Marital Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ability-to-speak-english-by-marital-status-a49a2) |
| Metadata | [Link](https://data.hawaii.gov/api/views/6jpf-s9b3) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/6jpf-s9b3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/6jpf-s9b3/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 6jpf-s9b3 |
| Name | Ability To Speak English By Marital Status |
| Attribution | Office of Language Access |
| Category | Culture and Recreation |
| Tags | marital, english |
| Created | 2012-09-06T01:36:55Z |
| Publication Date | 2012-09-06T01:39:34Z |

## Description

(Excluding those less than 5 years old or speak only English) Hawaii?s Limited English Proficient (LEP) Population: A Demographic and Socio-Economic Profile

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | marital_status | Marital Status | text      | text        |
| Yes      | numeric metric | well           | Well           | number    | number      |
| Yes      | numeric metric | not_well       | Not Well       | number    | number      |
| Yes      | numeric metric | not_at_all     | Not at All     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6jpf-s9b3 d:2012-09-05T18:36:56.000Z t:marital_status=Married m:not_at_all=2651 m:well=44812 m:not_well=28565

series e:6jpf-s9b3 d:2012-09-05T18:36:56.000Z t:marital_status=Widowed m:not_at_all=943 m:well=7798 m:not_well=7256

series e:6jpf-s9b3 d:2012-09-05T18:36:56.000Z t:marital_status=Divorced m:not_at_all=212 m:well=4222 m:not_well=4355
```

## Meta Commands

```ls
metric m:well p:integer l:Well t:dataTypeName=number

metric m:not_well p:integer l:"Not Well" t:dataTypeName=number

metric m:not_at_all p:integer l:"Not at All" t:dataTypeName=number

entity e:6jpf-s9b3 l:"Ability To Speak English By Marital Status" t:attribution="Office of Language Access" t:url=https://data.hawaii.gov/api/views/6jpf-s9b3

property e:6jpf-s9b3 t:meta.view v:id=6jpf-s9b3 v:category="Culture and Recreation" v:attributionLink=http://hawaii.gov/dlir v:averageRating=0 v:name="Ability To Speak English By Marital Status" v:attribution="Office of Language Access"

property e:6jpf-s9b3 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:6jpf-s9b3 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:6jpf-s9b3 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | marital_status                      | well  | not_well | not_at_all | 
| =========== | =================================== | ===== | ======== | ========== | 
| 1346870216  | Married                             | 44812 | 28565    | 2651       | 
| 1346870216  | Widowed                             | 7798  | 7256     | 943        | 
| 1346870216  | Divorced                            | 4222  | 4355     | 212        | 
| 1346870216  | Separated                           | 1910  | 694      | 141        | 
| 1346870216  | Never married or under 15 years old | 19036 | 7728     | 438        | 
```