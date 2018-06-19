# 2016 Adopted Budget Resources with Fundname

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-adopted-budget-resources-with-fundname) |
| Metadata | [Link](https://data.seattle.gov/api/views/wtgt-ejqk) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/wtgt-ejqk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/wtgt-ejqk/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | wtgt-ejqk |
| Name | 2016 Adopted Budget Resources with Fundname |
| Attribution | City of Seattle |
| Category | Finance |
| Tags | 2016 budget |
| Created | 2016-09-15T15:52:34Z |
| Publication Date | 2016-09-15T15:59:12Z |

## Description

2016 Adopted Budget Resources

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | dept                 | Dept                 | text      | text        |
| Yes      | series tag     | fundname             | FundName             | text      | text        |
| Yes      | series tag     | revenuetablecategory | RevenueTableCategory | text      | text        |
| Yes      | series tag     | revenuesourcename    | RevenueSourceName    | text      | text        |
| Yes      | numeric metric | 2014_actual          | 2014 Actual          | number    | number      |
| Yes      | numeric metric | 2015_adopted         | 2015 Adopted         | number    | number      |
| Yes      | numeric metric | 2016_endorsed        | 2016 Endorsed        | number    | number      |
| Yes      | numeric metric | 2016_adopted         | 2016 Adopted         | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wtgt-ejqk d:2016-01-01T00:00:00.000Z t:revenuetablecategory=Levy t:dept=12LIBLEVY t:revenuesourcename="Interest Earnings" t:fundname="2012 Library Levy Fund (18100)" m:2016_endorsed=0 m:2014_actual=65534 m:2015_adopted=0 m:2016_adopted=50000

series e:wtgt-ejqk d:2016-01-01T00:00:00.000Z t:revenuetablecategory=Levy t:dept=12LIBLEVY t:revenuesourcename="Levy Revenue" t:fundname="2012 Library Levy Fund (18100)" m:2016_endorsed=17340000 m:2014_actual=17081846 m:2015_adopted=17168000 m:2016_adopted=17340000

series e:wtgt-ejqk d:2016-01-01T00:00:00.000Z t:revenuetablecategory=Levy t:dept=12LIBLEVY t:revenuesourcename="Use of (Contribution to) Fund Balance" t:fundname="2012 Library Levy Fund (18100)" m:2016_endorsed=-432163 m:2014_actual=-3070456 m:2015_adopted=-880024 m:2016_adopted=-1482163
```

## Meta Commands

```ls
metric m:2014_actual p:double l:"2014 Actual" t:dataTypeName=number

metric m:2015_adopted p:decimal l:"2015 Adopted" t:dataTypeName=number

metric m:2016_endorsed p:double l:"2016 Endorsed" t:dataTypeName=number

metric m:2016_adopted p:decimal l:"2016 Adopted" t:dataTypeName=number

entity e:wtgt-ejqk l:"2016 Adopted Budget Resources with Fundname" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/wtgt-ejqk

property e:wtgt-ejqk t:meta.view v:id=wtgt-ejqk v:category=Finance v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="2016 Adopted Budget Resources with Fundname" v:attribution="City of Seattle"

property e:wtgt-ejqk t:meta.view.license v:name="Public Domain"

property e:wtgt-ejqk t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:wtgt-ejqk t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| dept      | fundname                       | revenuetablecategory                  | revenuesourcename                     | 2014_actual | 2015_adopted | 2016_endorsed | 2016_adopted | 
| ========= | ============================== | ===================================== | ===================================== | =========== | ============ | ============= | ============ | 
| 12LIBLEVY | 2012 Library Levy Fund (18100) | Levy                                  | Interest Earnings                     | 65534       | 0            | 0             | 50000        | 
| 12LIBLEVY | 2012 Library Levy Fund (18100) | Levy                                  | Levy Revenue                          | 17081846    | 17168000     | 17340000      | 17340000     | 
| 12LIBLEVY | 2012 Library Levy Fund (18100) | Levy                                  | Use of (Contribution to) Fund Balance | -3070456    | -880024      | -432163       | -1482163     | 
| ARTS      | Arts Account (00140)           | Admission Tax Allocation              | Interfund Transfers                   | 5300702     | 5953328      | 6124320       | 6492924      | 
| ARTS      | Arts Account (00140)           | General Fund                          | Interfund Transfers                   | 550500      | 0            | 0             | 1500000      | 
| ARTS      | Arts Account (00140)           | Misc Revenues                         | Interest Earnings                     | 15985       | 20000        | 20000         | 20000        | 
| ARTS      | Arts Account (00140)           | Misc Revenues                         | Interest Increase/Decrease            | 5385        | 0            | 0             | 0            | 
| ARTS      | Arts Account (00140)           | Misc Revenues                         | Interfund Transfers                   | 70880       | 30880        | 31961         | 31961        | 
| ARTS      | Arts Account (00140)           | Misc Revenues                         | Misc Income                           | 6193        | 0            | 0             | 0            | 
| ARTS      | Arts Account (00140)           | Use of/(Contribution to) Fund Balance | Use of/(Contribution to) Fund Balance | -571614     | -49123       | -363650       | -34135       | 
```