# TIF District Programming

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tif-district-programming-2014-2018-83053) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ycd5-punx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ycd5-punx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ycd5-punx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ycd5-punx |
| Name | TIF District Programming |
| Attribution | City of Chicago - Office of Budget and Management |
| Category | Community & Economic Development |
| Tags | tif |
| Created | 2014-09-09T14:34:34Z |
| Publication Date | 2016-01-23T00:05:19Z |

## Description

The dataset for Tax Increment Financing (TIF) District Programming contains amounts shown in the TIF District Programming 2015-2019 reports as well as 2020 through the planned expiration of each TIF district. The report and corresponding dataset show estimated fund and project balances through the end of FY 2014. Amounts shown in columns 2015 and later reflect known obligations and proposed projects as well as estimates of revenue based on the current equalized assessed value data for each TIF district produced by the Cook County Clerk.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | tif_number       | TIF Number       | text          | text          |
| Yes      | series tag     | tif_name         | TIF Name         | text          | text          |
| No       |                | time_period      | Time Period      | text          | text          |
| Yes      | series tag     | type             | Type             | text          | text          |
| Yes      | series tag     | description      | Description      | text          | text          |
| Yes      | numeric metric | amount           | Amount           | money         | money         |
| Yes      | time           | designation_date | Designation Date | calendar_date | calendar_date |
| No       |                | expiration_date  | Expiration Date  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = designation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = time_period,expiration_date
```

## Data Commands

```ls
series e:ycd5-punx d:2009-05-13T00:00:00.000Z t:description="Program administration" t:type="Current Obligations" t:tif_name="Irving Park/Elston" t:tif_number=T-165 m:amount=-4800

series e:ycd5-punx d:2009-06-30T00:00:00.000Z t:description="RA - Chicago Neighborhoods Initiative" t:type="Current Obligations" t:tif_name="North Pullman" t:tif_number=T-166 m:amount=-4000000

series e:ycd5-punx d:2009-04-22T00:00:00.000Z t:description="Program administration" t:type="Current Obligations" t:tif_name="Little Village East" t:tif_number=T-164 m:amount=-20500
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:ycd5-punx l:"TIF District Programming" t:attribution="City of Chicago - Office of Budget and Management" t:url=https://data.cityofchicago.org/api/views/ycd5-punx

property e:ycd5-punx t:meta.view v:id=ycd5-punx v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="TIF District Programming" v:attribution="City of Chicago - Office of Budget and Management"

property e:ycd5-punx t:meta.view.owner v:id=7ek2-d4pb v:screenName="David Miller" v:displayName="David Miller"

property e:ycd5-punx t:meta.view.tableauthor v:id=7ek2-d4pb v:screenName="David Miller" v:roleName=editor v:displayName="David Miller"
```

## Top Records

```ls
| tif_number | tif_name            | time_period | type                | description                           | amount      | designation_date    | expiration_date     | 
| ========== | =================== | =========== | =================== | ===================================== | =========== | =================== | =================== | 
| T-165      | Irving Park/Elston  | 2028        | Current Obligations | Program administration                | -4800.00    | 2009-05-13T00:00:00 | 2033-12-31T00:00:00 | 
| T-166      | North Pullman       | 2015        | Current Obligations | RA - Chicago Neighborhoods Initiative | -4000000.00 | 2009-06-30T00:00:00 | 2033-12-31T00:00:00 | 
| T-164      | Little Village East | 2026        | Current Obligations | Program administration                | -20500.00   | 2009-04-22T00:00:00 | 2033-12-31T00:00:00 | 
| T-164      | Little Village East | 2027        | Current Obligations | Program administration                | -27900.00   | 2009-04-22T00:00:00 | 2033-12-31T00:00:00 | 
| T-164      | Little Village East | 2028        | Current Obligations | Program administration                | -35600.00   | 2009-04-22T00:00:00 | 2033-12-31T00:00:00 | 
| T-164      | Little Village East | 2029        | Current Obligations | Program administration                | -39100.00   | 2009-04-22T00:00:00 | 2033-12-31T00:00:00 | 
| T-164      | Little Village East | 2030        | Current Obligations | Program administration                | -41200.00   | 2009-04-22T00:00:00 | 2033-12-31T00:00:00 | 
| T-164      | Little Village East | 2031        | Current Obligations | Program administration                | -109200.00  | 2009-04-22T00:00:00 | 2033-12-31T00:00:00 | 
| T-164      | Little Village East | 2032        | Current Obligations | Program administration                | -142500.00  | 2009-04-22T00:00:00 | 2033-12-31T00:00:00 | 
| T-164      | Little Village East | 2033        | Current Obligations | Program administration                | -157300.00  | 2009-04-22T00:00:00 | 2033-12-31T00:00:00 | 
```