# Baltimore City Contracts - Bureau of Purchases, Department of Finance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-contracts-bureau-of-purchases-department-of-finance-525ae) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/e7gh-hui5) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/e7gh-hui5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/e7gh-hui5/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | e7gh-hui5 |
| Name | Baltimore City Contracts - Bureau of Purchases, Department of Finance |
| Attribution | Baltimore City Department of Finance |
| Category | Financial |
| Tags | contract, contracts, citibuy |
| Created | 2012-02-29T16:34:51Z |
| Publication Date | 2014-03-27T23:51:26Z |

## Description

This data contains contracts which (1) cover City or agency-specific needs over a period of time and (2) were coordinated through the Bureau of Purchases in the Department of Finance.  All materials, supplies, equipment, and services used by City Agencies ??_??_??_ with the exception of professional services and public works (i.e., construction) ??_??_??_ must be obtained through the Bureau of Purchases. Professional services may be procured through the Board of Estimates with the assistance of the Law Department; public works (i.e., construction) may be procured through the Department of Public Works (DPW).Multiple listings in this Bureau of Purchases data reflect estimated breakdown among citywide and individual agency needs. Funds are encumbered against these contracts as goods or services are ordered. The contracts in this list have a starting date of July 1, 2010 or later. This dataset will be updated on a monthly basis.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | contractno       | contractNo       | text      | text        |
| Yes      | series tag     | desc             | desc             | text      | text        |
| Yes      | series tag     | vendorid         | vendorID         | text      | text        |
| Yes      | series tag     | vendorname       | vendorName       | text      | text        |
| Yes      | series tag     | agency           | agency           | text      | text        |
| Yes      | time           | begindate        | beginDate        | date      | date        |
| No       |                | enddate          | endDate          | date      | date        |
| Yes      | numeric metric | totalcontractamt | totalContractAmt | money     | money       |
| Yes      | numeric metric | amtspent         | amtSpent         | money     | money       |
| Yes      | numeric metric | amtremaining     | amtRemaining     | money     | money       |
```

## Time Field

```ls
Value = begindate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = enddate
```

## Data Commands

```ls
series e:e7gh-hui5 d:2011-08-20T07:00:00.000Z t:contractno=P503784:0 t:vendorname="Triangle Sign & Service" t:desc="Way Finding Signage - Heritage" t:vendorid=00000363 t:agency="MAYOR'S OFFICE OF CIVIC PROMOTION" m:amtremaining=197028 m:amtspent=344620 m:totalcontractamt=541648

series e:e7gh-hui5 d:2011-08-20T07:00:00.000Z t:contractno=P503784:0 t:vendorname="Triangle Sign & Service" t:desc="Way Finding Signage - Heritage" t:vendorid=00000363 t:agency=City-Wide m:amtremaining=23980 m:amtspent=76020 m:totalcontractamt=100000

series e:e7gh-hui5 d:2010-10-08T07:00:00.000Z t:contractno=P504527:0 t:vendorname="ROBNET, INC" t:desc="Railroad Spikes" t:vendorid=00000936 t:agency="PUBLIC WORKS" m:amtremaining=0 m:amtspent=11700 m:totalcontractamt=11700
```

## Meta Commands

```ls
metric m:totalcontractamt p:double l:totalContractAmt t:dataTypeName=money

metric m:amtspent p:double l:amtSpent t:dataTypeName=money

metric m:amtremaining p:double l:amtRemaining t:dataTypeName=money

entity e:e7gh-hui5 l:"Baltimore City Contracts -  Bureau of Purchases, Department of Finance" t:attribution="Baltimore City Department of Finance" t:url=https://data.baltimorecity.gov/api/views/e7gh-hui5

property e:e7gh-hui5 t:meta.view v:id=e7gh-hui5 v:category=Financial v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Finance.aspx v:averageRating=0 v:name="Baltimore City Contracts -  Bureau of Purchases, Department of Finance" v:attribution="Baltimore City Department of Finance"

property e:e7gh-hui5 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:e7gh-hui5 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:e7gh-hui5 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| contractno | desc                                         | vendorid | vendorname                                      | agency                            | begindate  | enddate    | totalcontractamt | amtspent  | amtremaining | 
| ========== | ============================================ | ======== | =============================================== | ================================= | ========== | ========== | ================ | ========= | ============ | 
| P503784:0  | Way Finding Signage - Heritage               | 00000363 | Triangle Sign & Service                         | MAYOR'S OFFICE OF CIVIC PROMOTION | 1313823600 | 1345359600 | 541648.00        | 344620.00 | 197028.00    | 
| P503784:0  | Way Finding Signage - Heritage               | 00000363 | Triangle Sign & Service                         | City-Wide                         | 1313823600 | 1345359600 | 100000.00        | 76020.00  | 23980.00     | 
| P504527:0  | Railroad Spikes                              | 00000936 | ROBNET, INC                                     | PUBLIC WORKS                      | 1286521200 | 1315897200 | 11700.00         | 11700.00  | 0.00         | 
| P506086:0  | EXTERIOR WINDOW WASHING                      | 00004283 | With Anointed Hands, LLC                        | ENOCH PRATT FREE LIBRARY          | 1293955200 | 1327046400 | 69480.00         | 62790.00  | 6690.00      | 
| P508318:0  | Lead Abatement Low Income Residences Part II | 00005961 | Coalition to End Childhood Lead Poisoning, Inc. | City-Wide                         | 1279436400 | 1327996800 | 261600.00        | 25765.00  | 235835.00    | 
| P508318:0  | Lead Abatement Low Income Residences Part II | 00005961 | Coalition to End Childhood Lead Poisoning, Inc. | HEALTH                            | 1279436400 | 1327996800 | 214000.00        | 213034.00 | 966.00       | 
| P509255:0  | Decorative Street Light Fixtures & Poles     | 00003638 | Hadco, A Philips Group Brand                    | City-Wide                         | 1309503600 | 1372575600 | 1558175.00       | 910383.50 | 647791.50    | 
| P510696:0  | Revolution Traffic Cone                      | 00000679 | National Capital Industries                     | PUBLIC WORKS                      | 1285743600 | 1348815600 | 63220.00         | 48745.00  | 14475.00     | 
| P510696:0  | Revolution Traffic Cone                      | 00000679 | National Capital Industries                     | TRANSPORTATION                    | 1285743600 | 1348815600 | 63220.00         | 34830.00  | 28390.00     | 
| P510696:0  | Revolution Traffic Cone                      | 00000679 | National Capital Industries                     | City-Wide                         | 1285743600 | 1348815600 | 30000.00         | 1265.00   | 28735.00     | 
```