# SSMMA Village Of Midlothian Building Permits Issued 2011- August 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-village-of-midlothian-building-permits-issued-2011-august-2012-2fc42) |
| Metadata | [Link](https://data.illinois.gov/api/views/cii2-ipkp) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cii2-ipkp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cii2-ipkp/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cii2-ipkp |
| Name | SSMMA Village Of Midlothian Building Permits Issued 2011- August 2012 |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | building, administration, permitting |
| Created | 2012-11-27T17:59:33Z |
| Publication Date | 2012-11-27T18:01:28Z |

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | permit_no_or_type  | Permit No or Type  | text          | text          |
| Yes      | time        | date_permit_issued | Date Permit Issued | calendar_date | calendar_date |
| Yes      | series tag  | location_1         | Location 1         | text          | text          |
```

## Time Field

```ls
Value = date_permit_issued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cii2-ipkp d:2012-05-08T00:00:00.000Z t:location_1="14049 Walter Hagen Ln." t:permit_no_or_type=Electrical m:row_number.cii2-ipkp=1

series e:cii2-ipkp d:2011-12-12T00:00:00.000Z t:location_1="14301 Keystone" t:permit_no_or_type=3725B m:row_number.cii2-ipkp=2

series e:cii2-ipkp d:2011-09-23T00:00:00.000Z t:location_1="14301 Keystone" t:permit_no_or_type=3721A m:row_number.cii2-ipkp=3
```

## Meta Commands

```ls
metric m:row_number.cii2-ipkp p:long l:"Row Number"

entity e:cii2-ipkp l:"SSMMA Village Of Midlothian  Building Permits Issued 2011- August 2012" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/cii2-ipkp

property e:cii2-ipkp t:meta.view v:id=cii2-ipkp v:category=Municipality v:averageRating=0 v:name="SSMMA Village Of Midlothian  Building Permits Issued 2011- August 2012" v:attribution="South Suburban Mayors and Managers Association"

property e:cii2-ipkp t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:cii2-ipkp t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:cii2-ipkp t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| permit_no_or_type | date_permit_issued  | location_1             | 
| ================= | =================== | ====================== | 
| Electrical        | 2012-05-08T00:00:00 | 14049 Walter Hagen Ln. | 
| 3725B             | 2011-12-12T00:00:00 | 14301 Keystone         | 
| 3721A             | 2011-09-23T00:00:00 | 14301 Keystone         | 
| Misc.             | 2012-05-21T00:00:00 | 14307 Keeler           | 
| Misc.             | 2011-09-14T00:00:00 | 14311 Keystone         | 
| Misc.             | 2011-09-15T00:00:00 | 14315 Keystone         | 
| Electrical        | 2012-06-14T00:00:00 | 14316 Kilpatrick       | 
| Electrical        | 2012-06-08T00:00:00 | 14318 Kolmar           | 
| Misc.             | 2012-02-08T00:00:00 | 14324 Kilpatrick       | 
| Fence             | 2012-06-06T00:00:00 | 14328 Lawndale         | 
```