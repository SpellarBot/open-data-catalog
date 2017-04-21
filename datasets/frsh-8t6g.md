# Medical Examiner - Autopsy Status - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-autopsy-status-2009-a0985) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/frsh-8t6g) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/frsh-8t6g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/frsh-8t6g/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | frsh-8t6g |
| Name | Medical Examiner - Autopsy Status - 2009 |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-21T21:13:29Z |
| Publication Date | 2014-10-09T21:30:34Z |

## Description

From the 2009 Annual Report, Autopsy Status

## Columns

```ls
| Included | Schema Type    | Field Name      | Name           | Data Type | Render Type |
| ======== | ============== | =============== | ============== | ========= | =========== |
| Yes      | series tag     | autopsy_status_ | AUTOPSY STATUS | text      | text        |
| Yes      | numeric metric | count_          | COUNT          | number    | number      |
| Yes      | numeric metric | percent_        | PERCENT        | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:frsh-8t6g d:2009-01-01T00:00:00.000Z t:autopsy_status_=YES m:count_=2649 m:percent_=50.61

series e:frsh-8t6g d:2009-01-01T00:00:00.000Z t:autopsy_status_=NO m:count_=2585 m:percent_=49.39
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent_ p:float l:PERCENT t:dataTypeName=percent

entity e:frsh-8t6g l:"Medical Examiner - Autopsy Status - 2009" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/frsh-8t6g

property e:frsh-8t6g t:meta.view v:id=frsh-8t6g v:category=Healthcare v:attributionLink=http://cookcountyil.gov/medicalexaminer v:averageRating=0 v:name="Medical Examiner - Autopsy Status - 2009" v:attribution="Cook County Medical Examiner"

property e:frsh-8t6g t:meta.view.license v:name="Public Domain"

property e:frsh-8t6g t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:frsh-8t6g t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| autopsy_status_ | count_ | percent_ | 
| =============== | ====== | ======== | 
| YES             | 2649   | 50.61    | 
| NO              | 2585   | 49.39    | 
```