# Medical Examiner--2009 Manner of Death Autopsy Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-manner-of-death-autopsy-status-66301) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/as8j-bewu) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/as8j-bewu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/as8j-bewu/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | as8j-bewu |
| Name | Medical Examiner--2009 Manner of Death Autopsy Status |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T17:27:53Z |
| Publication Date | 2014-10-27T16:41:58Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | manner_of_death | MANNER OF DEATH | text      | text        |
| Yes      | series tag     | autopsy_status_ | AUTOPSY STATUS  | text      | text        |
| Yes      | numeric metric | count           | COUNT           | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:as8j-bewu d:2009-01-01T00:00:00.000Z t:autopsy_status_=YES t:manner_of_death=ACCIDENT m:count=836

series e:as8j-bewu d:2009-01-01T00:00:00.000Z t:autopsy_status_=NO t:manner_of_death=ACCIDENT m:count=598

series e:as8j-bewu d:2009-01-01T00:00:00.000Z t:autopsy_status_=YES t:manner_of_death=HOMICIDE m:count=629
```

## Meta Commands

```ls
metric m:count p:integer l:COUNT t:dataTypeName=number

entity e:as8j-bewu l:"Medical Examiner--2009 Manner of Death Autopsy Status" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/as8j-bewu

property e:as8j-bewu t:meta.view v:id=as8j-bewu v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Manner of Death Autopsy Status" v:attribution="Cook County Medical Examiner"

property e:as8j-bewu t:meta.view.license v:name="Public Domain"

property e:as8j-bewu t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:as8j-bewu t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| manner_of_death | autopsy_status_ | count | 
| =============== | =============== | ===== | 
| ACCIDENT        | YES             | 836   | 
| ACCIDENT        | NO              | 598   | 
| HOMICIDE        | YES             | 629   | 
| HOMICIDE        | NO              | 1     | 
| NATURAL         | YES             | 935   | 
| NATURAL         | NO              | 1685  | 
| REMAINS         | YES             | 1     | 
| REMAINS         | NO              | 40    | 
| STILL BIRTH     | YES             | 4     | 
| STILL BIRTH     | NO              | 3     | 
```