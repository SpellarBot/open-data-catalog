# 2016 Adopted Budget Dollars

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-adopted-budget-dollars) |
| Metadata | [Link](https://data.seattle.gov/api/views/kn6u-e3ad) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/kn6u-e3ad/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/kn6u-e3ad/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | kn6u-e3ad |
| Name | 2016 Adopted Budget Dollars |
| Attribution | City of Seattle |
| Category | Finance |
| Tags | 2016 adopted budget dollars |
| Created | 2016-08-04T20:39:47Z |
| Publication Date | 2016-08-04T21:21:18Z |

## Description

2016 Adopted Budget Dollars

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | deptcode      | DeptCode      | text      | text        |
| Yes      | series tag     | bclname       | BCLName       | text      | text        |
| Yes      | series tag     | programname   | ProgramName   | text      | text        |
| Yes      | numeric metric | 2015_actual   | 2015 Actual   | money     | money       |
| Yes      | numeric metric | 2015_adopted  | 2015 Adopted  | money     | money       |
| Yes      | numeric metric | 2016_endorsed | 2016 Endorsed | money     | money       |
| Yes      | numeric metric | 2016_adopted  | 2016 Adopted  | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kn6u-e3ad d:2016-01-01T00:00:00.000Z t:deptcode=12LIBLEVY t:programname="Library Levy Operating Transfer" t:bclname="Library Levy Operating Transfer" m:2016_endorsed=13665837 m:2015_actual=12560843 m:2015_adopted=13139976 m:2016_adopted=13665837

series e:kn6u-e3ad d:2016-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Administrative Services" t:bclname="Arts Account" m:2016_endorsed=577473 m:2015_actual=535825 m:2015_adopted=652869 m:2016_adopted=598187

series e:kn6u-e3ad d:2016-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Community Development and Outreach" t:bclname="Arts Account" m:2016_endorsed=624749 m:2015_actual=537298 m:2015_adopted=616223 m:2016_adopted=611425
```

## Meta Commands

```ls
metric m:2015_actual p:double l:"2015 Actual" t:dataTypeName=money

metric m:2015_adopted p:double l:"2015 Adopted" t:dataTypeName=money

metric m:2016_endorsed p:double l:"2016 Endorsed" t:dataTypeName=money

metric m:2016_adopted p:double l:"2016 Adopted" t:dataTypeName=money

entity e:kn6u-e3ad l:"2016 Adopted Budget Dollars" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/kn6u-e3ad

property e:kn6u-e3ad t:meta.view v:id=kn6u-e3ad v:category=Finance v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="2016 Adopted Budget Dollars" v:attribution="City of Seattle"

property e:kn6u-e3ad t:meta.view.license v:name="Public Domain"

property e:kn6u-e3ad t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:kn6u-e3ad t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| deptcode  | bclname                                          | programname                               | 2015_actual | 2015_adopted | 2016_endorsed | 2016_adopted | 
| ========= | ================================================ | ========================================= | =========== | ============ | ============= | ============ | 
| 12LIBLEVY | Library Levy Operating Transfer                  | Library Levy Operating Transfer           | 12560843    | 13139976     | 13665837      | 13665837     | 
| ARTS      | Arts Account                                     | Administrative Services                   | 535825      | 652869       | 577473        | 598187       | 
| ARTS      | Arts Account                                     | Community Development and Outreach        | 537298      | 616223       | 624749        | 611425       | 
| ARTS      | Arts Account                                     | Cultural Partnerships                     | 3480285     | 3810876      | 3766536       | 4517092      | 
| ARTS      | Arts Account                                     | Langston Hughes Performing Arts Institute | 824622      | 875117       | 843873        | 428046       | 
| ARTS      | Capital Arts                                     | Capital Arts                              | 0.0         | 0.0          | 0.0           | 1856000      | 
| ARTS      | Municipal Arts Fund                              | Artwork Conservation                      | 0.0         | 0.0          | 0.0           | 187000       | 
| ARTS      | Municipal Arts Fund                              | Public Art                                | 2250314     | 3065271      | 3119332       | 3099449      | 
| AUD       | Office of City Auditor                           | Office of City Auditor                    | 1760573     | 1586256      | 1597521       | 1792064      | 
| CBLFEE    | Cable Fee Support to Information Technology Fund | Business Office                           |             | 0.0          | 0.0           | 238437       | 
```