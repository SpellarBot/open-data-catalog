# Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/resources-f9146) |
| Metadata | [Link](https://data.seattle.gov/api/views/vyby-j9tn) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vyby-j9tn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vyby-j9tn/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vyby-j9tn |
| Name | Resources |
| Attribution | City Budget Office |
| Category | Finance |
| Created | 2013-09-17T16:36:33Z |
| Publication Date | 2014-11-03T15:31:18Z |

## Description

Resources

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | dept                 | Dept                 | text      | text        |
| Yes      | series tag     | fundname             | FundName             | text      | text        |
| Yes      | series tag     | revenuetablecategory | RevenueTableCategory | text      | text        |
| Yes      | series tag     | revenuesourcename    | RevenueSourceName    | text      | text        |
| Yes      | numeric metric | 2012_actual          | 2012 Actual          | number    | number      |
| Yes      | numeric metric | 2013_adopted         | 2013 Adopted         | number    | number      |
| Yes      | numeric metric | 2014_endorsed        | 2014 Endorsed        | number    | number      |
| Yes      | numeric metric | 2014_proposed        | 2014 Proposed        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vyby-j9tn d:2014-11-03T07:30:36.000Z t:revenuetablecategory=Levy t:dept=12LIBLEVY t:revenuesourcename="2012 Library Levy" t:fundname="2012 Library Levy Fund (18100)" m:2013_adopted=16998000 m:2014_proposed=17340000 m:2012_actual=16868000 m:2014_endorsed=17168000

series e:vyby-j9tn d:2014-11-03T07:30:36.000Z t:revenuetablecategory="Levy Fund Balance" t:dept=12LIBLEVY t:revenuesourcename="Use of (Contribution to) Fund Balance" t:fundname="2012 Library Levy Fund (18100)" m:2013_adopted=-1520743 m:2014_proposed=-432163 m:2012_actual=-4963146 m:2014_endorsed=-880024

series e:vyby-j9tn d:2014-11-03T07:30:36.000Z t:revenuetablecategory="Admission Tax Allocation" t:dept=ARTS t:revenuesourcename="Interfund Transfers" t:fundname="Arts Account (00140)" m:2013_adopted=5300702 m:2014_proposed=6124320 m:2012_actual=4398229 m:2014_endorsed=5953328
```

## Meta Commands

```ls
metric m:2012_actual p:integer l:"2012 Actual" t:dataTypeName=number

metric m:2013_adopted p:integer l:"2013 Adopted" t:dataTypeName=number

metric m:2014_endorsed p:integer l:"2014 Endorsed" t:dataTypeName=number

metric m:2014_proposed p:integer l:"2014 Proposed" t:dataTypeName=number

entity e:vyby-j9tn l:Resources t:attribution="City Budget Office" t:url=https://data.seattle.gov/api/views/vyby-j9tn

property e:vyby-j9tn t:meta.view v:id=vyby-j9tn v:category=Finance v:attributionLink=http://www.seattle.gov/financedepartment/ v:averageRating=0 v:name=Resources v:attribution="City Budget Office"

property e:vyby-j9tn t:meta.view.license v:name="Public Domain"

property e:vyby-j9tn t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:vyby-j9tn t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | dept      | fundname                       | revenuetablecategory                  | revenuesourcename                     | 2012_actual | 2013_adopted | 2014_endorsed | 2014_proposed | 
| =========== | ========= | ============================== | ===================================== | ===================================== | =========== | ============ | ============= | ============= | 
| 1414999836  | 12LIBLEVY | 2012 Library Levy Fund (18100) | Levy                                  | 2012 Library Levy                     | 16868000    | 16998000     | 17168000      | 17340000      | 
| 1414999836  | 12LIBLEVY | 2012 Library Levy Fund (18100) | Levy Fund Balance                     | Use of (Contribution to) Fund Balance | -4963146    | -1520743     | -880024       | -432163       | 
| 1414999836  | ARTS      | Arts Account (00140)           | Admission Tax Allocation              | Interfund Transfers                   | 4398229     | 5300702      | 5953328       | 6124320       | 
| 1414999836  | ARTS      | Arts Account (00140)           | General Fund                          | Interfund Transfers                   | 405000      | 550500       | 0             | 0             | 
| 1414999836  | ARTS      | Arts Account (00140)           | Langston Hughes Operating             | Interfund Transfers                   | 70880       | 70880        | 30880         | 31961         | 
| 1414999836  | ARTS      | Arts Account (00140)           | Misc Revenues                         | Interest Earnings                     | 9070        | 20000        | 20000         | 20000         | 
| 1414999836  | ARTS      | Arts Account (00140)           | Misc Revenues                         | Interest Increase/Decrease            | -8960       | 0            | 0             | 0             | 
| 1414999836  | ARTS      | Arts Account (00140)           | Misc Revenues                         | Misc Income                           | 2475        | 0            | 0             | 0             | 
| 1414999836  | ARTS      | Arts Account (00140)           | Use of/(Contribution to) Fund Balance | Use of/(Contribution to) Fund Balance | 309668      | -429871      | -99123        | -363650       | 
| 1414999836  | ARTS      | Municipal Arts Fund (62600)    | 1% for Art Revenues                   | Interfund Transfers (1% for Art)      | 1775002     | 3085893      | 3563755       | 3328968       | 
```