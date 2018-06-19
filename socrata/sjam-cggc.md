# Cook County Budget - 2012 - Budget Long-term Forecast

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-budget-2012-budget-long-term-forecast-4c287) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/sjam-cggc) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/sjam-cggc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/sjam-cggc/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | sjam-cggc |
| Name | Cook County Budget - 2012 - Budget Long-term Forecast |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Created | 2011-10-24T21:07:00Z |
| Publication Date | 2014-10-09T20:52:35Z |

## Description

? Includes Sales Tax previously allocated to JTDC for FY08--9.  Reflects rate reduction for last 2 months of FY10, last 8 months of FY12 and FY13
 ? Provided for comparison purposes to revenues as shown in Revenue Estimate
 ? Sources: FY07-FY11 from Budget Citizen's Summary, Q-1 Total General Fund Expenditures.   FY13-16 based on FY12 with 3.2% annual growth (10 year CPI-U-2.44%/Health-8%).

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | revenues_and_fees | Revenues and Fees | text      | text        |
| Yes      | numeric metric | actual_fy07       | Actual FY07       | money     | money       |
| Yes      | numeric metric | actual_fy08       | Actual FY08       | money     | money       |
| Yes      | numeric metric | actual_fy09       | Actual FY09       | money     | money       |
| Yes      | numeric metric | actual_fy10       | Actual FY10       | money     | money       |
| Yes      | numeric metric | proj_actual_fy11  | Proj. Actual FY11 | money     | money       |
| Yes      | numeric metric | ept_est_fy12      | Ept. Est. FY12    | money     | money       |
| Yes      | numeric metric | proj_fy13         | Proj. FY13        | money     | money       |
| Yes      | numeric metric | proj_fy14         | Proj. FY14        | money     | money       |
| Yes      | numeric metric | proj_fy15         | Proj. FY15        | money     | money       |
| Yes      | numeric metric | proj_fy16         | Proj. FY16        | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sjam-cggc d:2012-01-01T00:00:00.000Z t:revenues_and_fees="Property Taxes" m:proj_fy15=247658000 m:ept_est_fy12=331520178 m:proj_fy14=233235000 m:actual_fy10=333613001 m:proj_actual_fy11=287243990 m:proj_fy16=224724000 m:actual_fy08=333321462 m:actual_fy09=354279383 m:actual_fy07=413814308 m:proj_fy13=345526000

series e:sjam-cggc d:2012-01-01T00:00:00.000Z t:revenues_and_fees="Bond Restructuring" m:proj_fy15=0 m:ept_est_fy12=0 m:proj_fy14=0 m:actual_fy10=0 m:proj_actual_fy11=85000000 m:proj_fy16=0 m:actual_fy08=0 m:actual_fy09=0 m:actual_fy07=0 m:proj_fy13=0

series e:sjam-cggc d:2012-01-01T00:00:00.000Z t:revenues_and_fees="County Treasurer" m:proj_fy15=51746000 m:ept_est_fy12=60007000 m:proj_fy14=54327000 m:actual_fy10=94284334 m:proj_actual_fy11=71760000 m:proj_fy16=49418000 m:actual_fy08=82744156 m:actual_fy09=79972437 m:actual_fy07=54478980 m:proj_fy13=57307000
```

## Meta Commands

```ls
metric m:actual_fy07 p:integer l:"Actual FY07" t:dataTypeName=money

metric m:actual_fy08 p:integer l:"Actual FY08" t:dataTypeName=money

metric m:actual_fy09 p:long l:"Actual FY09" t:dataTypeName=money

metric m:actual_fy10 p:long l:"Actual FY10" t:dataTypeName=money

metric m:proj_actual_fy11 p:long l:"Proj. Actual FY11" t:dataTypeName=money

metric m:ept_est_fy12 p:long l:"Ept. Est. FY12" t:dataTypeName=money

metric m:proj_fy13 p:long l:"Proj. FY13" t:dataTypeName=money

metric m:proj_fy14 p:long l:"Proj. FY14" t:dataTypeName=money

metric m:proj_fy15 p:long l:"Proj. FY15" t:dataTypeName=money

metric m:proj_fy16 p:long l:"Proj. FY16" t:dataTypeName=money

entity e:sjam-cggc l:"Cook County Budget - 2012 - Budget Long-term Forecast" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/sjam-cggc

property e:sjam-cggc t:meta.view v:id=sjam-cggc v:category="Finance & Administration" v:attributionLink=http://home.cookcountyil.gov/budget/ v:averageRating=0 v:name="Cook County Budget - 2012 - Budget Long-term Forecast" v:attribution="Cook County Department of Budget and Management Services"

property e:sjam-cggc t:meta.view.license v:name="Public Domain"

property e:sjam-cggc t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:sjam-cggc t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| revenues_and_fees     | actual_fy07 | actual_fy08 | actual_fy09 | actual_fy10 | proj_actual_fy11 | ept_est_fy12 | proj_fy13 | proj_fy14 | proj_fy15 | proj_fy16 | 
| ===================== | =========== | =========== | =========== | =========== | ================ | ============ | ========= | ========= | ========= | ========= | 
| Property Taxes        | 413814308   | 333321462   | 354279383   | 333613001   | 287243990        | 331520178    | 345526000 | 233235000 | 247658000 | 224724000 | 
| Bond Restructuring    | 0           | 0           | 0           | 0           | 85000000         | 0            | 0         | 0         | 0         | 0         | 
| Fees                  |             |             |             |             |                  |              |           |           |           |           | 
| County Treasurer      | 54478980    | 82744156    | 79972437    | 94284334    | 71760000         | 60007000     | 57307000  | 54327000  | 51746000  | 49418000  | 
| Treasurer Indemnity   | 0           | 0           | 0           | 0           | 0                | 0            | 0         | 0         | 0         | 0         | 
| County Clerk          | 8275008     | 8877439     | 10090209    | 9407629     | 9793079          | 10246000     | 10729000  | 11235000  | 11765000  | 12319000  | 
| Recorder of Deeds     | 64441453    | 46308166    | 34151181    | 33571773    | 30130063         | 32100000     | 33545000  | 35289000  | 36965000  | 38628000  | 
| Building & Zoning     | 1528464     | 1502838     | 1567539     | 1329972     | 1580000          | 2100000      | 2100000   | 2100000   | 2100000   | 2100000   | 
| Environmental Control | 3257906     | 4311489     | 3949671     | 4126084     | 3700000          | 4122000      | 4311000   | 4500000   | 4688000   | 4877000   | 
| Liquor Licenses       | 390000      | 370000      | 390000      | 370000      | 380000           | 380000       | 380000    | 380000    | 380000    | 380000    | 
```