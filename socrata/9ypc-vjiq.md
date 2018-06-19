# Lottery Aid to Education

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-aid-to-education) |
| Metadata | [Link](https://data.ny.gov/api/views/9ypc-vjiq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9ypc-vjiq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9ypc-vjiq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9ypc-vjiq |
| Name | Lottery Aid to Education |
| Attribution | New York Gaming Commission |
| Category | Government & Finance |
| Tags | new york lottery, education, aid, school districts |
| Created | 2016-08-29T18:59:41Z |
| Publication Date | 2016-08-31T21:08:44Z |

## Description

Aid to education provided by the New York Lottery by fiscal year, by county, by school district

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | time           | beginning_fiscal_year | Beginning Fiscal Year | number    | number      |
| No       |                | ending_fiscal_year    | Ending Fiscal Year    | number    | number      |
| Yes      | series tag     | county                | County                | text      | text        |
| Yes      | series tag     | school_district       | School District       | text      | text        |
| Yes      | numeric metric | amount_of_aid         | Amount of Aid         | money     | money       |
```

## Time Field

```ls
Value = beginning_fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = ending_fiscal_year
```

## Data Commands

```ls
series e:9ypc-vjiq d:2002-01-01T00:00:00.000Z t:county=Albany t:school_district=Albany m:amount_of_aid=7242297.04

series e:9ypc-vjiq d:2002-01-01T00:00:00.000Z t:county=Albany t:school_district=Berne-Knox-Westerlo m:amount_of_aid=874046.94

series e:9ypc-vjiq d:2002-01-01T00:00:00.000Z t:county=Albany t:school_district=Bethlehem m:amount_of_aid=2786954.71
```

## Meta Commands

```ls
metric m:amount_of_aid p:double l:"Amount of Aid" d:"Aid to Education for the Fiscal Year" t:dataTypeName=money

entity e:9ypc-vjiq l:"Lottery Aid to Education" t:attribution="New York Gaming Commission" t:url=https://data.ny.gov/api/views/9ypc-vjiq

property e:9ypc-vjiq t:meta.view v:id=9ypc-vjiq v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/About+Us/Mission+for+Education/Mission+for+Education v:averageRating=0 v:name="Lottery Aid to Education" v:attribution="New York Gaming Commission"

property e:9ypc-vjiq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9ypc-vjiq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| beginning_fiscal_year | ending_fiscal_year | county | school_district     | amount_of_aid | 
| ===================== | ================== | ====== | =================== | ============= | 
| 2002                  | 2003               | Albany | Albany              | 7242297.04    | 
| 2002                  | 2003               | Albany | Berne-Knox-Westerlo | 874046.94     | 
| 2002                  | 2003               | Albany | Bethlehem           | 2786954.71    | 
| 2002                  | 2003               | Albany | Cohoes              | 1820297.94    | 
| 2002                  | 2003               | Albany | Green Island        | 241859.93     | 
| 2002                  | 2003               | Albany | Guilderland         | 3182536.10    | 
| 2002                  | 2003               | Albany | Maplewood           | 32160.30      | 
| 2002                  | 2003               | Albany | Menands Csd         | 6870.00       | 
| 2002                  | 2003               | Albany | North Colonie       | 1808923.74    | 
| 2002                  | 2003               | Albany | Ravena-Coeymans     | 1442362.27    | 
```