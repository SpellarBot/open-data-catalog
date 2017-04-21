# 2016 Adopted Budget FTEs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-adopted-budget-ftes) |
| Metadata | [Link](https://data.seattle.gov/api/views/xnpv-m68y) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/xnpv-m68y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/xnpv-m68y/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | xnpv-m68y |
| Name | 2016 Adopted Budget FTEs |
| Attribution | City of Seattle |
| Category | Finance |
| Tags | 2016 adopted budget ftes |
| Created | 2016-08-04T20:48:51Z |
| Publication Date | 2016-08-04T21:21:06Z |

## Description

2016 Adopted Budget FTEs

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | deptcode      | DeptCode      | text      | text        |
| Yes      | series tag     | bclname       | BCLName       | text      | text        |
| Yes      | series tag     | programname   | ProgramName   | text      | text        |
| Yes      | numeric metric | 2014_actual   | 2014 Actual   | number    | number      |
| Yes      | numeric metric | 2015_adopted  | 2015 Adopted  | number    | number      |
| Yes      | numeric metric | 2016_endorsed | 2016 Endorsed | number    | number      |
| Yes      | numeric metric | 2016_adopted  | 2016 Adopted  | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xnpv-m68y d:2016-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Administrative Services" t:bclname="Arts Account" m:2016_endorsed=5 m:2014_actual=4.75 m:2015_adopted=5 m:2016_adopted=5

series e:xnpv-m68y d:2016-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Community Development and Outreach" t:bclname="Arts Account" m:2016_endorsed=3 m:2014_actual=2.5 m:2015_adopted=3 m:2016_adopted=3

series e:xnpv-m68y d:2016-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Cultural Partnerships" t:bclname="Arts Account" m:2016_endorsed=5.75 m:2014_actual=5.75 m:2015_adopted=5.75 m:2016_adopted=6.75
```

## Meta Commands

```ls
metric m:2014_actual p:float l:"2014 Actual" t:dataTypeName=number

metric m:2015_adopted p:float l:"2015 Adopted" t:dataTypeName=number

metric m:2016_endorsed p:float l:"2016 Endorsed" t:dataTypeName=number

metric m:2016_adopted p:float l:"2016 Adopted" t:dataTypeName=number

entity e:xnpv-m68y l:"2016 Adopted Budget FTEs" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/xnpv-m68y

property e:xnpv-m68y t:meta.view v:id=xnpv-m68y v:category=Finance v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="2016 Adopted Budget FTEs" v:attribution="City of Seattle"

property e:xnpv-m68y t:meta.view.license v:name="Public Domain"

property e:xnpv-m68y t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:xnpv-m68y t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| deptcode | bclname                | programname                               | 2014_actual | 2015_adopted | 2016_endorsed | 2016_adopted | 
| ======== | ====================== | ========================================= | =========== | ============ | ============= | ============ | 
| ARTS     | Arts Account           | Administrative Services                   | 4.75        | 5.00         | 5.00          | 5.00         | 
| ARTS     | Arts Account           | Community Development and Outreach        | 2.50        | 3.00         | 3.00          | 3.00         | 
| ARTS     | Arts Account           | Cultural Partnerships                     | 5.75        | 5.75         | 5.75          | 6.75         | 
| ARTS     | Arts Account           | Langston Hughes Performing Arts Institute | 7.09        | 7.09         | 7.09          | 3.59         | 
| ARTS     | Municipal Arts Fund    | Artwork Conservation                      | 0.00        | 0.00         | 0.00          | 1.00         | 
| ARTS     | Municipal Arts Fund    | Public Art                                | 10.75       | 10.75        | 10.75         | 9.75         | 
| AUD      | Office of City Auditor | Office of City Auditor                    | 9.50        | 9.50         | 9.50          | 9.50         | 
| CBO      | City Budget Office     | City Budget Office                        | 29.50       | 33.00        | 33.00         | 35.00        | 
| CEN      | Access                 | Access                                    | 10.27       | 9.37         | 9.37          | 9.37         | 
| CEN      | Administration-SC      | Administration-SC                         | 20.11       | 22.11        | 22.11         | 22.11        | 
```