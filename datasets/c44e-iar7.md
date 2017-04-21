# TAX 12-2012 Liquor Collections And Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-12-2012-liquor-collections-and-permits-9ee3a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/c44e-iar7) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/c44e-iar7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/c44e-iar7/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | c44e-iar7 |
| Name | TAX 12-2012 Liquor Collections And Permits |
| Attribution | Department of Taxation |
| Category | Government-Wide Support |
| Tags | liquor, tax |
| Created | 2013-02-05T23:09:02Z |
| Publication Date | 2013-02-05T23:16:58Z |

## Description

Liquor Collections And Permits

## Columns

```ls
| Included | Schema Type    | Field Name    | Name            | Data Type | Render Type |
| ======== | ============== | ============= | =============== | ========= | =========== |
| Yes      | series tag     | amount_of_tax | Amount of Tax   | text      | text        |
| Yes      | numeric metric | first         | FIRST DISTRICT  | number    | text        |
| Yes      | numeric metric | second        | SECOND DISTRICT | number    | text        |
| Yes      | numeric metric | third         | THIRD DISTRICT  | number    | text        |
| Yes      | numeric metric | fourth        | FOURTH DISTRICT | number    | text        |
| Yes      | series tag     | all_districts | Dec 2012        | text      | text        |
| Yes      | numeric metric | dec_2011      | Dec 2011        | number    | text        |
| Yes      | numeric metric | 2012_2013     | 2012-2013       | number    | text        |
| Yes      | numeric metric | 2011_2012     | 2011-2012       | number    | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:c44e-iar7 d:2012-01-01T00:00:00.000Z t:amount_of_tax=Wholesale t:all_districts=4416207.38 m:fourth=263163.45 m:2012_2013=23295222.38 m:second=617388.4 m:dec_2011=4620423.76 m:2011_2012=23536339.82 m:first=2975315.64 m:third=560339.89

series e:c44e-iar7 d:2012-01-01T00:00:00.000Z t:amount_of_tax="Penalties and Interest" t:all_districts=0 m:fourth=0 m:2012_2013=0 m:second=0 m:dec_2011=0 m:2011_2012=47.5 m:first=0 m:third=0

series e:c44e-iar7 d:2012-01-01T00:00:00.000Z t:amount_of_tax="Permit Fees" t:all_districts=7.5 m:fourth=0 m:2012_2013=290 m:second=0 m:dec_2011=97.5 m:2011_2012=965 m:first=7.5 m:third=0
```

## Meta Commands

```ls
metric m:first p:double l:"FIRST DISTRICT" t:dataTypeName=number

metric m:second p:float l:"SECOND DISTRICT" t:dataTypeName=number

metric m:third p:double l:"THIRD DISTRICT" t:dataTypeName=number

metric m:fourth p:double l:"FOURTH DISTRICT" t:dataTypeName=number

metric m:dec_2011 p:double l:"Dec 2011" t:dataTypeName=number

metric m:2012_2013 p:decimal l:2012-2013 t:dataTypeName=number

metric m:2011_2012 p:double l:2011-2012 t:dataTypeName=number

entity e:c44e-iar7 l:"TAX 12-2012 Liquor Collections And Permits" t:attribution="Department of Taxation" t:url=https://data.hawaii.gov/api/views/c44e-iar7

property e:c44e-iar7 t:meta.view v:id=c44e-iar7 v:category="Government-Wide Support" v:attributionLink=http://www6.hawaii.gov/tax/a5_3txcolrpt.htm v:averageRating=0 v:name="TAX 12-2012 Liquor Collections And Permits" v:attribution="Department of Taxation"

property e:c44e-iar7 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c44e-iar7 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:c44e-iar7 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| amount_of_tax          | first      | second   | third     | fourth    | all_districts | dec_2011   | 2012_2013          | 2011_2012   | 
| ====================== | ========== | ======== | ========= | ========= | ============= | ========== | ================== | =========== | 
| Wholesale              | 2975315.64 | 617388.4 | 560339.89 | 263163.45 | 4416207.38    | 4620423.76 | 23295222.379999999 | 23536339.82 | 
| Penalties and Interest | 0          | 0        | 0         | 0         | 0             | 0          | 0                  | 47.5        | 
| Permit Fees            | 7.5        | 0        | 0         | 0         | 7.5           | 97.5       | 290                | 965         | 
| TOTAL COLLECTIONS      | 2975323.14 | 617388.4 | 560339.89 | 263163.45 | 4416214.88    | 4620521.26 | 23295512.379999999 | 23537352.32 | 
```