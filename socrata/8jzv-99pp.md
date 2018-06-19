# Ability To Speak English By Language

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ability-to-speak-english-by-language-791d1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8jzv-99pp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8jzv-99pp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8jzv-99pp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8jzv-99pp |
| Name | Ability To Speak English By Language |
| Attribution | Office of Language Access |
| Category | Culture and Recreation |
| Tags | language, english |
| Created | 2012-09-06T01:33:29Z |
| Publication Date | 2012-09-06T01:36:10Z |

## Description

(Excluding those less than 5 years old or speak only English) Hawaii?s Limited English Proficient (LEP) Population: A Demographic and Socio-Economic Profile

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | language_spoken_at_home | Language spoken at home | text      | text        |
| Yes      | numeric metric | well                    | Well                    | number    | number      |
| Yes      | numeric metric | not_well                | Not Well                | number    | number      |
| Yes      | numeric metric | not_at_all              | Not at All              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8jzv-99pp d:2012-09-05T18:33:30.000Z t:language_spoken_at_home="1. Tagalog" m:not_at_all=215 m:well=20272 m:not_well=7549

series e:8jzv-99pp d:2012-09-05T18:33:30.000Z t:language_spoken_at_home="2. Ilokano" m:not_at_all=400 m:well=13701 m:not_well=10911

series e:8jzv-99pp d:2012-09-05T18:33:30.000Z t:language_spoken_at_home="3. Japanese" m:not_at_all=703 m:well=12849 m:not_well=9064
```

## Meta Commands

```ls
metric m:well p:integer l:Well t:dataTypeName=number

metric m:not_well p:integer l:"Not Well" t:dataTypeName=number

metric m:not_at_all p:integer l:"Not at All" t:dataTypeName=number

entity e:8jzv-99pp l:"Ability To Speak English By Language" t:attribution="Office of Language Access" t:url=https://data.hawaii.gov/api/views/8jzv-99pp

property e:8jzv-99pp t:meta.view v:id=8jzv-99pp v:category="Culture and Recreation" v:attributionLink=http://hawaii.gov/dlir v:averageRating=0 v:name="Ability To Speak English By Language" v:attribution="Office of Language Access"

property e:8jzv-99pp t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:8jzv-99pp t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:8jzv-99pp t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | language_spoken_at_home    | well  | not_well | not_at_all | 
| =========== | ========================== | ===== | ======== | ========== | 
| 1346870010  | 1. Tagalog                 | 20272 | 7549     | 215        | 
| 1346870010  | 2. Ilokano                 | 13701 | 10911    | 400        | 
| 1346870010  | 3. Japanese                | 12849 | 9064     | 703        | 
| 1346870010  | 4. Chinese, inc.           | 8027  | 6518     | 1130       | 
| 1346870010  | Mandarin & Cantonese       |       |          |            | 
| 1346870010  | 5. Korean                  | 6018  | 4544     | 413        | 
| 1346870010  | 6. Vietnamese              | 1952  | 2796     | 791        | 
| 1346870010  | 7. Bisayan                 | 1824  | 2256     | 255        | 
| 1346870010  | 8. Other Pacific languages | 4090  | 1666     | 62         | 
| 1346870010  | 9. Samoan                  | 3261  | 280      | 221        | 
```