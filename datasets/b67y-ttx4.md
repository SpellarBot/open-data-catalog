# IDFPR Count Of Licenses In Active Status By Profession And Zip Code as of January 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idfpr-count-of-licenses-in-active-status-by-profession-and-zip-code-as-of-january-2012-e1a61) |
| Metadata | [Link](https://data.illinois.gov/api/views/b67y-ttx4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/b67y-ttx4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/b67y-ttx4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | b67y-ttx4 |
| Name | IDFPR Count Of Licenses In Active Status By Profession And Zip Code as of January 2012 |
| Created | 2012-01-18T19:34:55Z |
| Publication Date | 2012-01-18T19:41:15Z |

## Description

This dataset provides a count of licensees regulated by the Illinois Department of Financial and Professional Regulation by Board, Profession, and Zip Code.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | board                      | Board                      | text      | text        |
| Yes      | series tag     | profession_number_and_name | Profession Number and Name | text      | text        |
| Yes      | series tag     | zip_code                   | Zip Code                   | text      | text        |
| Yes      | numeric metric | count                      | Count                      | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b67y-ttx4 d:2012-01-01T00:00:00.000Z t:zip_code=01060 t:profession_number_and_name="209 ADVANCED PRACTICE NURSE" t:board="Advanced Practice Nurse" m:count=1

series e:b67y-ttx4 d:2012-01-01T00:00:00.000Z t:zip_code=04074 t:profession_number_and_name="209 ADVANCED PRACTICE NURSE" t:board="Advanced Practice Nurse" m:count=1

series e:b67y-ttx4 d:2012-01-01T00:00:00.000Z t:zip_code=06105 t:profession_number_and_name="209 ADVANCED PRACTICE NURSE" t:board="Advanced Practice Nurse" m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:b67y-ttx4 l:"IDFPR Count Of Licenses In Active Status By Profession And Zip Code as of January 2012" t:url=https://data.illinois.gov/api/views/b67y-ttx4

property e:b67y-ttx4 t:meta.view v:id=b67y-ttx4 v:averageRating=0 v:name="IDFPR Count Of Licenses In Active Status By Profession And Zip Code as of January 2012"

property e:b67y-ttx4 t:meta.view.owner v:id=2jwj-ihvp v:screenName=Dfee v:displayName=Dfee

property e:b67y-ttx4 t:meta.view.tableauthor v:id=2jwj-ihvp v:screenName=Dfee v:displayName=Dfee
```

## Top Records

```ls
| board                   | profession_number_and_name  | zip_code | count | 
| ======================= | =========================== | ======== | ===== | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 01060    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 04074    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 06105    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 28304    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 30075    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 32563    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 35120    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 35214    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 35763    | 1     | 
| Advanced Practice Nurse | 209 ADVANCED PRACTICE NURSE | 36117    | 1     | 
```