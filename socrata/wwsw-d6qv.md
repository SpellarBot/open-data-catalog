# Ability To Speak English By Total Income

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ability-to-speak-english-by-total-income-09d4c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/wwsw-d6qv) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/wwsw-d6qv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/wwsw-d6qv/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | wwsw-d6qv |
| Name | Ability To Speak English By Total Income |
| Attribution | Office of Language Access |
| Category | Culture and Recreation |
| Tags | english, income |
| Created | 2012-09-06T01:48:10Z |
| Publication Date | 2012-09-06T01:52:52Z |

## Description

(Excluding those less than 5 years old or speak only English) Hawaii?s Limited English Proficient (LEP) Population: A Demographic and Socio-Economic Profile

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | total_income | Total Income | text      | text        |
| Yes      | numeric metric | well         | Well         | number    | number      |
| Yes      | numeric metric | not_well     | Not Well     | number    | number      |
| Yes      | numeric metric | not_at_all   | Not at All   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wwsw-d6qv d:2012-09-05T18:48:12.000Z t:total_income="Less than $10,000" m:not_at_all=2577 m:well=21481 m:not_well=19071

series e:wwsw-d6qv d:2012-09-05T18:48:12.000Z t:total_income="$200,000 or more" m:not_at_all=0 m:well=151 m:not_well=311

series e:wwsw-d6qv d:2012-09-05T18:51:17.000Z t:total_income="$10,000 ? $14,999" m:not_at_all=473 m:well=8878 m:not_well=6185
```

## Meta Commands

```ls
metric m:well p:integer l:Well t:dataTypeName=number

metric m:not_well p:integer l:"Not Well" t:dataTypeName=number

metric m:not_at_all p:integer l:"Not at All" t:dataTypeName=number

entity e:wwsw-d6qv l:"Ability To Speak English By Total Income" t:attribution="Office of Language Access" t:url=https://data.hawaii.gov/api/views/wwsw-d6qv

property e:wwsw-d6qv t:meta.view v:id=wwsw-d6qv v:category="Culture and Recreation" v:attributionLink=http://hawaii.gov/dlir v:averageRating=0 v:name="Ability To Speak English By Total Income" v:attribution="Office of Language Access"

property e:wwsw-d6qv t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:wwsw-d6qv t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:wwsw-d6qv t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | total_income        | well  | not_well | not_at_all | 
| =========== | =================== | ===== | ======== | ========== | 
| 1346870892  | Less than $10,000   | 21481 | 19071    | 2577       | 
| 1346870892  | $200,000 or more    | 151   | 311      | 0          | 
| 1346871077  | $10,000 ? $14,999   | 8878  | 6185     | 473        | 
| 1346871086  | $15,000 ? $24,999   | 16414 | 9739     | 784        | 
| 1346871095  | $25,000 ? $34,999   | 10712 | 4375     | 251        | 
| 1346871105  | $35,000 ? $49,999   | 7864  | 3592     | 77         | 
| 1346871115  | $50,000 ? $74,000   | 4906  | 2019     | 72         | 
| 1346871123  | $75,000 ? $99,999   | 1050  | 993      | 0          | 
| 1346871132  | $100,000 ? $149,999 | 615   | 390      | 0          | 
| 1346871144  | $150,000 ? $199,999 | 257   | 164      | 127        | 
```