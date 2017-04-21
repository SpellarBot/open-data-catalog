# Family Investment Program Recipients and Grants by Month and County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/family-investment-program-recipients-and-grants-by-month-and-county) |
| Metadata | [Link](https://data.iowa.gov/api/views/79c3-mzyc) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/79c3-mzyc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/79c3-mzyc/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 79c3-mzyc |
| Name | Family Investment Program Recipients and Grants by Month and County |
| Attribution | Iowa Department of Human Services, Family Investment Program |
| Category | Economy |
| Tags | public assistance, fip, tanf, family investment program |
| Created | 2014-11-10T14:42:59Z |
| Publication Date | 2016-11-07T13:58:15Z |

## Description

The Family Investment Program (FIP) is Iowa's Temporary Assistance to Needy Families (TANF) program. FIP provides cash assistance to needy families, as they become self-supporting so children may be cared for in their own homes or in the homes of relatives.  Data are provided on the number of cases (families) served, the number of recipients served and the dollar value of the payments provided summed by month and county starting January 2011 and updated monthly. A case is defined as a family group who receives FIP assistance together. A recipient is an individual on a FIP case.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| No       |                | cy                  | CY                  | number        | number        |
| Yes      | time           | month               | Month               | calendar_date | calendar_date |
| Yes      | series tag     | county_name         | County Name         | text          | text          |
| Yes      | series tag     | county              | County #            | text          | text          |
| Yes      | series tag     | service_area        | Service Area        | text          | text          |
| Yes      | numeric metric | cases               | Cases               | number        | number        |
| Yes      | numeric metric | recipients          | Recipients          | number        | number        |
| Yes      | numeric metric | grants              | Grants              | money         | money         |
| No       |                | primary_county_lat  | Primary County Lat  | number        | number        |
| No       |                | primary_county_long | Primary County Long | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = cy,primary_county_lat,primary_county_long
```

## Data Commands

```ls
series e:79c3-mzyc d:2015-03-31T00:00:00.000Z t:county=1 t:service_area="Des Moines" t:county_name=Adair m:cases=16 m:recipients=38 m:grants=5258

series e:79c3-mzyc d:2015-03-31T00:00:00.000Z t:county=2 t:service_area="Des Moines" t:county_name=Adams m:cases=9 m:recipients=17 m:grants=2261

series e:79c3-mzyc d:2015-03-31T00:00:00.000Z t:county=3 t:service_area=Northern t:county_name=Allamakee m:cases=45 m:recipients=137 m:grants=16300
```

## Meta Commands

```ls
metric m:cases p:integer l:Cases d:"Number of family groups who receives FIP assistance together" t:dataTypeName=number

metric m:recipients p:integer l:Recipients d:"Number of individuals on a FIP cases" t:dataTypeName=number

metric m:grants p:double l:Grants d:"Amount of cash assistance payments made" t:dataTypeName=money

entity e:79c3-mzyc l:"Family Investment Program Recipients and Grants by Month and County" t:attribution="Iowa Department of Human Services, Family Investment Program" t:url=https://data.iowa.gov/api/views/79c3-mzyc

property e:79c3-mzyc t:meta.view v:id=79c3-mzyc v:category=Economy v:averageRating=0 v:name="Family Investment Program Recipients and Grants by Month and County" v:attribution="Iowa Department of Human Services, Family Investment Program"

property e:79c3-mzyc t:meta.view.license v:name="Public Domain"

property e:79c3-mzyc t:meta.view.owner v:id=grmb-3z9d v:profileImageUrlMedium=/api/users/grmb-3z9d/profile_images/THUMB v:profileImageUrlLarge=/api/users/grmb-3z9d/profile_images/LARGE v:screenName="Iowa Department of Human Services" v:profileImageUrlSmall=/api/users/grmb-3z9d/profile_images/TINY v:displayName="Iowa Department of Human Services"

property e:79c3-mzyc t:meta.view.tableauthor v:id=grmb-3z9d v:profileImageUrlMedium=/api/users/grmb-3z9d/profile_images/THUMB v:profileImageUrlLarge=/api/users/grmb-3z9d/profile_images/LARGE v:screenName="Iowa Department of Human Services" v:profileImageUrlSmall=/api/users/grmb-3z9d/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Human Services"
```

## Top Records

```ls
| cy   | month               | county_name | county | service_area | cases | recipients | grants    | primary_county_lat | primary_county_long | 
| ==== | =================== | =========== | ====== | ============ | ===== | ========== | ========= | ================== | =================== | 
| 2015 | 2015-03-31T00:00:00 | Adair       | 1      | Des Moines   | 16    | 38         | 5258.00   | 41.330746400000002 | -94.470941300000007 | 
| 2015 | 2015-03-31T00:00:00 | Adams       | 2      | Des Moines   | 9     | 17         | 2261.00   | 41.0289839         | -94.699184900000006 | 
| 2015 | 2015-03-31T00:00:00 | Allamakee   | 3      | Northern     | 45    | 137        | 16300.00  | 43.284283799999997 | -91.378092300000006 | 
| 2015 | 2015-03-31T00:00:00 | Appanoose   | 4      | Cedar Rapids | 49    | 114        | 15374.00  | 40.743163500000001 | -92.868610399999994 | 
| 2015 | 2015-03-31T00:00:00 | Audubon     | 5      | Western      | 17    | 37         | 5629.00   | 41.684589299999999 | -94.905822200000003 | 
| 2015 | 2015-03-31T00:00:00 | Benton      | 6      | Cedar Rapids | 53    | 132        | 18566.00  | 42.080186400000002 | -92.065691200000003 | 
| 2015 | 2015-03-31T00:00:00 | Black Hawk  | 7      | Northern     | 782   | 1871       | 246260.00 | 42.470095700000002 | -92.308819700000001 | 
| 2015 | 2015-03-31T00:00:00 | Boone       | 8      | Des Moines   | 66    | 159        | 21644.00  | 42.036549299999997 | -93.931670999999994 | 
| 2015 | 2015-03-31T00:00:00 | Bremer      | 9      | Northern     | 31    | 70         | 9871.00   | 42.7745873         | -92.318054799999999 | 
| 2015 | 2015-03-31T00:00:00 | Buchanan    | 10     | Northern     | 56    | 119        | 17391.00  | 42.470777699999999 | -91.837839200000005 | 
```