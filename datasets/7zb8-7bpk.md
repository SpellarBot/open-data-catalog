# Property Tax Rates by Tax Class

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/property-tax-rates-by-tax-class) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7zb8-7bpk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7zb8-7bpk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7zb8-7bpk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7zb8-7bpk |
| Name | Property Tax Rates by Tax Class |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Created | 2015-12-29T19:36:31Z |
| Publication Date | 2015-12-29T20:00:13Z |

## Description

Table of tax rates by year

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | year        | YEAR       | text      | text        |
| Yes      | numeric metric | class_1     | CLASS 1    | percent   | percent     |
| Yes      | numeric metric | class_2     | CLASS 2    | percent   | percent     |
| Yes      | numeric metric | class_3     | CLASS 3    | percent   | percent     |
| Yes      | numeric metric | class_4     | CLASS 4    | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7zb8-7bpk d:2015-12-29T11:39:54.000Z t:year=15/16 m:class_1=19.554 m:class_2=12.883 m:class_3=10.813 m:class_4=10.656

series e:7zb8-7bpk d:2015-12-29T11:39:54.000Z t:year=14/15 m:class_1=19.157 m:class_2=12.855 m:class_3=11.125 m:class_4=10.684

series e:7zb8-7bpk d:2015-12-29T11:39:54.000Z t:year=13/14 m:class_1=19.191 m:class_2=13.145 m:class_3=11.902 m:class_4=10.323
```

## Meta Commands

```ls
metric m:class_1 p:float l:"CLASS 1" d:"Most residential property of up to three units (family homes and small stores or offices with one or two apartments attached), and most condominiums that are not more than three stories." t:dataTypeName=percent

metric m:class_2 p:float l:"CLASS 2" d:"All other property that is not in Class 1 and is primarily residential (rentals, cooperatives and condominiums). Class 2 includes: Sub-Class 2a (4 - 6 unit rental building); Sub-Class 2b (7 - 10 unit rental building); Sub-Class 2c (2 - 10 unit cooperative or condominium); and Class 2 (11 units or more)." t:dataTypeName=percent

metric m:class_3 p:float l:"CLASS 3" d:"Most utility property." t:dataTypeName=percent

metric m:class_4 p:float l:"CLASS 4" d:"All commercial and industrial properties, such as office, retail, factory buildings and all other properties not included in tax classes 1, 2 or 3." t:dataTypeName=percent

entity e:7zb8-7bpk l:"Property Tax Rates by Tax Class" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/7zb8-7bpk

property e:7zb8-7bpk t:meta.view v:id=7zb8-7bpk v:category="City Government" v:averageRating=0 v:name="Property Tax Rates by Tax Class" v:attribution="Department of Finance (DOF)"

property e:7zb8-7bpk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7zb8-7bpk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | year                          | class_1 | class_2 | class_3 | class_4 | 
| =========== | ============================= | ======= | ======= | ======= | ======= | 
| 1451389194  | 15/16                         | 19.554  | 12.883  | 10.813  | 10.656  | 
| 1451389194  | 14/15                         | 19.157  | 12.855  | 11.125  | 10.684  | 
| 1451389194  | 13/14                         | 19.191  | 13.145  | 11.902  | 10.323  | 
| 1451389194  | 12/13                         | 18.569  | 13.181  | 12.477  | 10.288  | 
| 1451389194  | 11/12                         | 18.205  | 13.433  | 12.473  | 10.152  | 
| 1451389194  | 10/11                         | 17.364  | 13.353  | 12.631  | 10.312  | 
| 1451389194  | 9/10                          | 17.088  | 13.241  | 12.743  | 10.426  | 
| 1451389194  | Average Annual Tax Rate 08/09 | 16.196  | 12.596  | 12.137  | 10.241  | 
| 1451389194  | 08/09 3rd & 4th Qtr.          | 16.787  | 13.053  | 12.577  | 10.612  | 
| 1451389194  | 08/09 1st & 2nd Qtr.          | 15.605  | 12.139  | 11.698  | 9.870   | 
```