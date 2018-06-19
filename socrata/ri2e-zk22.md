# FY2015 Annual Report Expense Table

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-expense-table) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ri2e-zk22) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ri2e-zk22/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ri2e-zk22/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ri2e-zk22 |
| Name | FY2015 Annual Report Expense Table |
| Tags | atcems, fy2015, annual report, expenses |
| Created | 2016-08-29T15:55:47Z |
| Publication Date | 2016-08-29T15:58:30Z |

## Description

** Static Data Set ** This table shows ATCEMS expenses for the past five fiscal years, broken out by expense category. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | expenses   | Expenses | text      | text        |
| Yes      | numeric metric | fy2009     | FY2009   | money     | money       |
| Yes      | numeric metric | fy2010     | FY2010   | money     | money       |
| Yes      | numeric metric | fy2011     | FY2011   | money     | money       |
| Yes      | numeric metric | fy2012     | FY2012   | money     | money       |
| Yes      | numeric metric | fy2013     | FY2013   | money     | money       |
| Yes      | numeric metric | fy2014     | FY2014   | money     | money       |
| Yes      | numeric metric | fy2015     | FY2015   | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ri2e-zk22 d:2015-01-01T00:00:00.000Z t:expenses=Personnel m:fy2014=50154536.06 m:fy2015=54043802 m:fy2010=37995807 m:fy2011=40516709 m:fy2012=42954071 m:fy2013=46843265 m:fy2009=37234360

series e:ri2e-zk22 d:2015-01-01T00:00:00.000Z t:expenses=Contractuals m:fy2014=6206476 m:fy2015=9733365 m:fy2010=3419780 m:fy2011=3999856 m:fy2012=4276891 m:fy2013=4747735 m:fy2009=3482174

series e:ri2e-zk22 d:2015-01-01T00:00:00.000Z t:expenses=Commodities m:fy2014=3649470 m:fy2015=3058963 m:fy2010=2365789 m:fy2011=2937652 m:fy2012=2859109 m:fy2013=2767544 m:fy2009=1983025
```

## Meta Commands

```ls
metric m:fy2009 p:double l:FY2009 t:dataTypeName=money

metric m:fy2010 p:double l:FY2010 t:dataTypeName=money

metric m:fy2011 p:double l:FY2011 t:dataTypeName=money

metric m:fy2012 p:double l:FY2012 t:dataTypeName=money

metric m:fy2013 p:double l:FY2013 t:dataTypeName=money

metric m:fy2014 p:double l:FY2014 t:dataTypeName=money

metric m:fy2015 p:double l:FY2015 t:dataTypeName=money

entity e:ri2e-zk22 l:"FY2015 Annual Report Expense Table" t:url=https://data.austintexas.gov/api/views/ri2e-zk22

property e:ri2e-zk22 t:meta.view v:id=ri2e-zk22 v:averageRating=0 v:name="FY2015 Annual Report Expense Table"

property e:ri2e-zk22 t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:ri2e-zk22 t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| expenses                | fy2009      | fy2010      | fy2011      | fy2012      | fy2013      | fy2014      | fy2015      | 
| ======================= | =========== | =========== | =========== | =========== | =========== | =========== | =========== | 
| Personnel               | 37234360.00 | 37995807.00 | 40516709.00 | 42954071.00 | 46843265.00 | 50154536.06 | 54043802.00 | 
| Contractuals            | 3482174.00  | 3419780.00  | 3999856.00  | 4276891.00  | 4747735.00  | 6206476.00  | 9733365.00  | 
| Commodities             | 1983025.00  | 2365789.00  | 2937652.00  | 2859109.00  | 2767544.00  | 3649470.00  | 3058963.00  | 
| Other - Expense Refunds | -210330.00  | -333700.00  | -400421.00  | -389353.00  | -651412.00  | -346499.00  | 4345032.00  | 
| Total                   | 42489229.00 | 43447676.00 | 47053796.00 | 49700718.00 | 53707132.00 | 59663983.06 | 71181162.00 | 
```