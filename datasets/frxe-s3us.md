# Expenditures-dollars

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-dollars-e3bf9) |
| Metadata | [Link](https://data.seattle.gov/api/views/frxe-s3us) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/frxe-s3us/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/frxe-s3us/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | frxe-s3us |
| Name | Expenditures-dollars |
| Category | Finance |
| Created | 2013-09-17T16:31:13Z |
| Publication Date | 2013-10-07T18:52:19Z |

## Description

Expenditures - dollars

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | department    | Department    | text      | text        |
| Yes      | series tag     | bcl           | BCL           | text      | text        |
| Yes      | series tag     | program       | Program       | text      | text        |
| Yes      | numeric metric | 2012_actual   | 2012 Actual   | number    | number      |
| Yes      | numeric metric | 2013_adopted  | 2013 Adopted  | number    | number      |
| Yes      | numeric metric | 2014_endorsed | 2014 Endorsed | number    | number      |
| Yes      | numeric metric | 2014_proposed | 2014 Proposed | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:frxe-s3us d:2013-10-07T11:51:54.000Z t:bcl="Library Levy Operating Transfer" t:program="Library Levy Operating Transfer" t:department=12LIBLEVY m:2013_adopted=13049781 m:2014_proposed=12658704 m:2014_endorsed=12658704

series e:frxe-s3us d:2013-10-07T11:51:54.000Z t:bcl="Arts Account" t:program="Administrative Services" t:department=ARTS m:2013_adopted=400683 m:2014_proposed=587579 m:2012_actual=409133 m:2014_endorsed=411913

series e:frxe-s3us d:2013-10-07T11:51:54.000Z t:bcl="Arts Account" t:program="Community Development and Outreach" t:department=ARTS m:2013_adopted=518398 m:2014_proposed=524770 m:2012_actual=1721308 m:2014_endorsed=534369
```

## Meta Commands

```ls
metric m:2012_actual p:integer l:"2012 Actual" t:dataTypeName=number

metric m:2013_adopted p:integer l:"2013 Adopted" t:dataTypeName=number

metric m:2014_endorsed p:integer l:"2014 Endorsed" t:dataTypeName=number

metric m:2014_proposed p:integer l:"2014 Proposed" t:dataTypeName=number

entity e:frxe-s3us l:Expenditures-dollars t:url=https://data.seattle.gov/api/views/frxe-s3us

property e:frxe-s3us t:meta.view v:id=frxe-s3us v:category=Finance v:averageRating=0 v:name=Expenditures-dollars

property e:frxe-s3us t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:frxe-s3us t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | department | bcl                                              | program                                   | 2012_actual | 2013_adopted | 2014_endorsed | 2014_proposed | 
| =========== | ========== | ================================================ | ========================================= | =========== | ============ | ============= | ============= | 
| 1381146714  | 12LIBLEVY  | Library Levy Operating Transfer                  | Library Levy Operating Transfer           |             | 13049781     | 12658704      | 12658704      | 
| 1381146714  | ARTS       | Arts Account                                     | Administrative Services                   | 409133      | 400683       | 411913        | 587579        | 
| 1381146714  | ARTS       | Arts Account                                     | Community Development and Outreach        | 1721308     | 518398       | 534369        | 524770        | 
| 1381146714  | ARTS       | Arts Account                                     | Cultural Partnerships                     | 2502448     | 3030729      | 3005137       | 3440764       | 
| 1381146714  | ARTS       | Arts Account                                     | Langston Hughes Performing Arts Institute |             | 745698       | 778669        | 809180        | 
| 1381146714  | ARTS       | Municipal Arts Fund                              | Municipal Arts Fund                       | 2798353     | 2449820      | 2513673       | 2991764       | 
| 1381146714  | AUD        | Office of City Auditor                           | Office of City Auditor                    | 1148312     | 1913014      | 1461132       | 1402670       | 
| 1381146714  | CBLFEE     | Cable Fee Support to Information Technology Fund | Cable Communications                      | 723252      | 745244       | 766477        | 776904        | 
| 1381146714  | CBLFEE     | Cable Fee Support to Information Technology Fund | Community Technology                      | 1317216     | 1333350      | 1367133       | 1431718       | 
| 1381146714  | CBLFEE     | Cable Fee Support to Information Technology Fund | Finance and Administration                | 299688      | 373754       | 386050        | 0             | 
```