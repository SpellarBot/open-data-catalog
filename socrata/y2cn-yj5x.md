# IFA Investments by Fiscal Year, Program and County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ifa-investments-by-fiscal-year-program-and-county) |
| Metadata | [Link](https://data.iowa.gov/api/views/y2cn-yj5x) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/y2cn-yj5x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/y2cn-yj5x/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | y2cn-yj5x |
| Name | IFA Investments by Fiscal Year, Program and County |
| Attribution | Iowa Finance Authority |
| Category | Government |
| Tags | investments, grants, loan agreements, couseling sessions, rental units, title certificates |
| Created | 2015-01-09T17:11:55Z |
| Publication Date | 2015-04-24T19:51:02Z |

## Description

This dataset includes Investments made by Iowa Finance Authority in the State of Iowa. The data includes investment amounts and quantity by program by Fiscal year and is broken out by County, Congressional District, and Council of Government. The Investments vary by program and include Grant Recipients, Loan Agreements, Counseling Sessions, Rental Units, and Title Certificates.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                   | Data Type     | Render Type   |
| ======== | ============== | ===================== | ====================== | ============= | ============= |
| No       |                | fiscalyear            | Fiscal Year            | number        | number        |
| Yes      | time           | fiscal_year_ending    | Fiscal Year Ending     | calendar_date | calendar_date |
| Yes      | numeric metric | countytypeid          | County Type ID         | number        | number        |
| Yes      | series tag     | countyname            | County Name            | text          | text          |
| Yes      | series tag     | congressionaldistrict | Congressional District | text          | number        |
| Yes      | series tag     | cog                   | COG                    | text          | text          |
| Yes      | series tag     | programname           | Program Name           | text          | text          |
| Yes      | series tag     | programtype           | Investment Type        | text          | text          |
| Yes      | numeric metric | quantity              | Quantity               | number        | number        |
| Yes      | numeric metric | investmentamount      | Investment             | money         | money         |
| No       |                | primary_county_lat    | Primary County Lat     | number        | number        |
| No       |                | primary_county_long   | Primary County Long    | number        | number        |
```

## Time Field

```ls
Value = fiscal_year_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = primary_county_lat,primary_county_long,fiscalyear
```

## Data Commands

```ls
series e:y2cn-yj5x d:2008-06-30T00:00:00.000Z t:programtype="Loan Agreements" t:countyname=ADAIR t:cog="Southern Iowa Council of Governments" t:programname="HO - FirstHome Loan Program" t:congressionaldistrict=3 m:investmentamount=327410 m:countytypeid=1 m:quantity=4

series e:y2cn-yj5x d:2008-06-30T00:00:00.000Z t:programtype="Grant Recipients" t:countyname=ADAIR t:cog="Southern Iowa Council of Governments" t:programname="HO - FirstHome Plus Down Payment Assistance" t:congressionaldistrict=3 m:investmentamount=5000 m:countytypeid=1 m:quantity=2

series e:y2cn-yj5x d:2008-06-30T00:00:00.000Z t:programtype="Rental Units" t:countyname=ADAIR t:cog="Southern Iowa Council of Governments" t:programname="S8 - Section 8 Housing Assistance Payments (14.195)" t:congressionaldistrict=3 m:investmentamount=0 m:countytypeid=1 m:quantity=52
```

## Meta Commands

```ls
metric m:countytypeid p:integer l:"County Type ID" d:"Iowa county code. Multiple counties are given a ""0""" t:dataTypeName=number

metric m:quantity p:integer l:Quantity d:"Number of grant recipients, loan agreements, rental units, title certificates, or counseling sessions associated with the investment." t:dataTypeName=number

metric m:investmentamount p:long l:Investment d:"The amount of investment made in the fiscal year for the program and county." t:dataTypeName=money

entity e:y2cn-yj5x l:"IFA Investments by Fiscal Year, Program and County" t:attribution="Iowa Finance Authority" t:url=https://data.iowa.gov/api/views/y2cn-yj5x

property e:y2cn-yj5x t:meta.view v:id=y2cn-yj5x v:category=Government v:averageRating=0 v:name="IFA Investments by Fiscal Year, Program and County" v:attribution="Iowa Finance Authority"

property e:y2cn-yj5x t:meta.view.license v:name="Public Domain"

property e:y2cn-yj5x t:meta.view.owner v:id=xjjb-b658 v:profileImageUrlMedium=/api/users/xjjb-b658/profile_images/THUMB v:profileImageUrlLarge=/api/users/xjjb-b658/profile_images/LARGE v:screenName="Iowa Finance Authority" v:profileImageUrlSmall=/api/users/xjjb-b658/profile_images/TINY v:displayName="Iowa Finance Authority"

property e:y2cn-yj5x t:meta.view.tableauthor v:id=2ckc-m6iv v:profileImageUrlMedium=/api/users/2ckc-m6iv/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ckc-m6iv/profile_images/LARGE v:screenName="Iowa Finance Authority" v:profileImageUrlSmall=/api/users/2ckc-m6iv/profile_images/TINY v:roleName=editor v:displayName="Iowa Finance Authority"
```

## Top Records

```ls
| fiscalyear | fiscal_year_ending  | countytypeid | countyname | congressionaldistrict | cog                                  | programname                                         | programtype        | quantity | investmentamount | primary_county_lat | primary_county_long | 
| ========== | =================== | ============ | ========== | ===================== | ==================================== | =================================================== | ================== | ======== | ================ | ================== | =================== | 
| 2008       | 2008-06-30T00:00:00 | 1            | ADAIR      | 3                     | Southern Iowa Council of Governments | HO - FirstHome Loan Program                         | Loan Agreements    | 4        | 327410           | 41.3307464         | -94.4709413         | 
| 2008       | 2008-06-30T00:00:00 | 1            | ADAIR      | 3                     | Southern Iowa Council of Governments | HO - FirstHome Plus Down Payment Assistance         | Grant Recipients   | 2        | 5000             | 41.3307464         | -94.4709413         | 
| 2008       | 2008-06-30T00:00:00 | 1            | ADAIR      | 3                     | Southern Iowa Council of Governments | S8 - Section 8 Housing Assistance Payments (14.195) | Rental Units       | 52       | 0                | 41.3307464         | -94.4709413         | 
| 2008       | 2008-06-30T00:00:00 | 1            | ADAIR      | 3                     | Southern Iowa Council of Governments | SRF - Local Wastewater Protection (LD)              | Loan Agreements    | 5        | 95883            | 41.3307464         | -94.4709413         | 
| 2008       | 2008-06-30T00:00:00 | 1            | ADAIR      | 3                     | Southern Iowa Council of Governments | SRF - Onsite Wastewater Assistance (LD)             | Loan Agreements    | 3        | 16631            | 41.3307464         | -94.4709413         | 
| 2008       | 2008-06-30T00:00:00 | 1            | ADAIR      | 3                     | Southern Iowa Council of Governments | TG - Title Guaranty Residential                     | Title Certificates | 61       | 6250889          | 41.3307464         | -94.4709413         | 
| 2008       | 2008-06-30T00:00:00 | 2            | ADAMS      | 3                     | Southern Iowa Council of Governments | HO - FirstHome Loan Program                         | Loan Agreements    | 1        | 50400            | 41.0289839         | -94.6991849         | 
| 2008       | 2008-06-30T00:00:00 | 2            | ADAMS      | 3                     | Southern Iowa Council of Governments | SRF - Local Wastewater Protection (LD)              | Loan Agreements    | 12       | 161477           | 41.0289839         | -94.6991849         | 
| 2008       | 2008-06-30T00:00:00 | 2            | ADAMS      | 3                     | Southern Iowa Council of Governments | SRF - Onsite Wastewater Assistance (LD)             | Loan Agreements    | 9        | 64070            | 41.0289839         | -94.6991849         | 
| 2008       | 2008-06-30T00:00:00 | 2            | ADAMS      | 3                     | Southern Iowa Council of Governments | TG - Title Guaranty Residential                     | Title Certificates | 17       | 1095150          | 41.0289839         | -94.6991849         | 
```