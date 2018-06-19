# TAX 12-2012 Tobacco Tax Collections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-12-2012-tobacco-tax-collections-e1a50) |
| Metadata | [Link](https://data.hawaii.gov/api/views/42id-b4fw) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/42id-b4fw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/42id-b4fw/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 42id-b4fw |
| Name | TAX 12-2012 Tobacco Tax Collections |
| Attribution | Department of Taxation |
| Category | Government-Wide Support |
| Tags | tax, tobacco |
| Created | 2013-02-05T23:19:10Z |
| Publication Date | 2013-02-05T23:22:11Z |

## Description

Tobacco Tax Collections

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | amount_of_tax   | AMOUNT OF TAX   | text      | text        |
| Yes      | series tag     | first_district  | FIRST District  | text      | number      |
| Yes      | series tag     | second_district | SECOND District | text      | number      |
| Yes      | series tag     | third_district  | THIRD District  | text      | number      |
| Yes      | series tag     | fourth_district | FOURTH District | text      | number      |
| Yes      | numeric metric | dec_2012        | Dec 2012        | number    | number      |
| Yes      | numeric metric | dec_2011        | Dec 2011        | number    | number      |
| Yes      | numeric metric | 2012_2013       | 2012-2013       | number    | number      |
| Yes      | numeric metric | 2011_2012       | 2011-2012       | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:42id-b4fw d:2012-01-01T00:00:00.000Z t:fourth_district=243120.00 t:third_district=972480.00 t:amount_of_tax=Cigarettes t:first_district=8393011.80 t:second_district=923856.00 m:dec_2012=10532467.8 m:2012_2013=62563792.8 m:dec_2011=12595487 m:2011_2012=67224154.76

series e:42id-b4fw d:2012-01-01T00:00:00.000Z t:fourth_district=0.00 t:third_district=655.20 t:amount_of_tax="Tobacco Products" t:first_district=560341.23 t:second_district=957.92 m:dec_2012=561954.35 m:2012_2013=2978403.71 m:dec_2011=432379.41 m:2011_2012=3095626.79

series e:42id-b4fw d:2012-01-01T00:00:00.000Z t:fourth_district=7005.19 t:third_district=1139.83 t:amount_of_tax=Cigars t:first_district=81273.32 t:second_district=4201.89 m:dec_2012=93620.23 m:2012_2013=685292.62 m:dec_2011=101049.71 m:2011_2012=775153.56
```

## Meta Commands

```ls
metric m:dec_2012 p:double l:"Dec 2012" t:dataTypeName=number

metric m:dec_2011 p:float l:"Dec 2011" t:dataTypeName=number

metric m:2012_2013 p:double l:2012-2013 t:dataTypeName=number

metric m:2011_2012 p:double l:2011-2012 t:dataTypeName=number

entity e:42id-b4fw l:"TAX 12-2012 Tobacco Tax Collections" t:attribution="Department of Taxation" t:url=https://data.hawaii.gov/api/views/42id-b4fw

property e:42id-b4fw t:meta.view v:id=42id-b4fw v:category="Government-Wide Support" v:attributionLink=http://www6.hawaii.gov/tax/a5_3txcolrpt.htm v:averageRating=0 v:name="TAX 12-2012 Tobacco Tax Collections" v:attribution="Department of Taxation"

property e:42id-b4fw t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:42id-b4fw t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:42id-b4fw t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| amount_of_tax                       | first_district | second_district | third_district | fourth_district | dec_2012    | dec_2011    | 2012_2013   | 2011_2012   | 
| =================================== | ============== | =============== | ============== | =============== | =========== | =========== | =========== | =========== | 
| Cigarettes                          | 8393011.80     | 923856.00       | 972480.00      | 243120.00       | 10532467.80 | 12595487.00 | 62563792.80 | 67224154.76 | 
| Tobacco Products                    | 560341.23      | 957.92          | 655.20         | 0.00            | 561954.35   | 432379.41   | 2978403.71  | 3095626.79  | 
| Cigars                              | 81273.32       | 4201.89         | 1139.83        | 7005.19         | 93620.23    | 101049.71   | 685292.62   | 775153.56   | 
| Little Cigars                       | 23301.63       | 0.00            | 0.00           | 719.04          | 24020.67    | 19320.32    | 147934.44   | 152182.36   | 
| Penalties and Interest              | 0.00           | 0.00            | 0.00           | 0.00            | 0.00        | 0.00        | 0.00        | 0.00        | 
| License Fees                        | 40.00          | 0.00            | 0.00           | 0.00            | 40.00       | 22.50       | 225.00      | 312.50      | 
| Retail Permits                      | 2880.00        | 220.00          | 180.00         | 40.00           | 3320.00     | 2420.00     | 27905.00    | 27310.00    | 
| Cigarette Stamp Administrative Fund | 18115.86       | 1858.03         | 1948.55        | 501.69          | 22424.13    | 26296.47    | 132750.83   | 136254.47   | 
| Cigarette Stamp Enforcement Fund    | 134057.33      | 13749.44        | 14419.27       | 3712.50         | 165938.54   | 194593.90   | 982356.27   | 1019284.90  | 
| Hawaii Cancer Research Fund         | 1117748.31     | 114640.55       | 120225.54      | 30954.17        | 1383568.57  | 1622492.38  | 8190727.27  | 8495672.38  | 
```