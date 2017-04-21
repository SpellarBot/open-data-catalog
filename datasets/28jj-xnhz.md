# OPIF & I OPIF Payments Report ? Composite ( FY 2016 - 2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/opif-i-opif-payments-report-composite-fy-2016-2013) |
| Metadata | [Link](https://data.oregon.gov/api/views/28jj-xnhz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/28jj-xnhz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/28jj-xnhz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 28jj-xnhz |
| Name | OPIF & I OPIF Payments Report ? Composite ( FY 2016 - 2013) |
| Category | Revenue & Expense |
| Tags | opif; iopif; i opif; opif and iopif; fy 2016-2013, composite report |
| Created | 2016-12-01T05:08:18Z |
| Publication Date | 2016-12-01T06:24:14Z |

## Description

This report provides reporting for the Filmmakers or companies receiving reimbursements, and the amount of each reimbursement from the OPIF and iOPIF programs under ORS 284.368. For more information, go to:
http://www.oregon.gov/transparency/Pages/TaxExpenditures.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                       | Data Type | Render Type |
| ======== | ============== | ======================================= | ========================================== | ========= | =========== |
| Yes      | series tag     | fiscal_year                             | Fiscal Year                                | text      | text        |
| Yes      | series tag     | opif_iopif_production_co_reimbursements | OPIF & iOPIF Production Co. Reimbursements | text      | text        |
| Yes      | numeric metric | amount                                  | Amount                                     | money     | money       |
| Yes      | series tag     | outcomes                                | Outcomes                                   | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:28jj-xnhz d:2016-01-01T00:00:00.000Z t:fiscal_year="FY 2015-2016" t:outcomes="Black Road completed production on their locally produced feature film by the same name in Ashland and the So Oregon Coast spending $95,000 in Oregon." t:opif_iopif_production_co_reimbursements="Black Road LLC" m:amount=15872

series e:28jj-xnhz d:2016-01-01T00:00:00.000Z t:fiscal_year="FY 2015-2016" t:outcomes="Clyde Park completed the post-production for the feature film CERTAIN WOMEN spending more than $75,500 in Oregon." t:opif_iopif_production_co_reimbursements="Clyde Park LLC" m:amount=15000

series e:28jj-xnhz d:2016-01-01T00:00:00.000Z t:fiscal_year="FY 2015-2016" t:outcomes="Collective Eye completed production on their locally produced feature documentary SEED: THE UNTOLD STORY spending $127,000 in Oregon." t:opif_iopif_production_co_reimbursements="Collective Eye Inc." m:amount=14741
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:28jj-xnhz l:"OPIF & I OPIF Payments Report ? Composite ( FY 2016 - 2013)" t:url=https://data.oregon.gov/api/views/28jj-xnhz

property e:28jj-xnhz t:meta.view v:id=28jj-xnhz v:category="Revenue & Expense" v:averageRating=0 v:name="OPIF & I OPIF Payments Report ? Composite ( FY 2016 - 2013)"

property e:28jj-xnhz t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:28jj-xnhz t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year  | opif_iopif_production_co_reimbursements | amount     | outcomes                                                                                                                                               | 
| ============ | ======================================= | ========== | ====================================================================================================================================================== | 
| FY 2015-2016 | Black Road LLC                          | 15872.00   | Black Road completed production on their locally produced feature film by the same name in Ashland and the So Oregon Coast spending $95,000 in Oregon. | 
| FY 2015-2016 | Clyde Park LLC                          | 15000.00   | Clyde Park completed the post-production for the feature film CERTAIN WOMEN spending more than $75,500 in Oregon.                                      | 
| FY 2015-2016 | Collective Eye Inc.                     | 14741.00   | Collective Eye completed production on their locally produced feature documentary SEED: THE UNTOLD STORY spending $127,000 in Oregon.                  | 
| FY 2015-2016 | Darkness Filmed Entertainment LLC       | 15417.00   | Darkness Filmed Ent locally produced the feature film OUT OF THE DARKNESS spending $140,000 in Oregon.                                                 | 
| FY 2015-2016 | Ex Libris Productions Inc               | 3281622.00 | Ex Libris spent more than $22M in Oregon labor and local services on season 2 of the TV Series THE LIBRARIANS.                                         | 
| FY 2015-2016 | Field Recordings                        | 9600.00    | Field Recordings completed the post-production for the TV series FLOPHOUSE spending $127,000 in Oregon.                                                | 
| FY 2015-2016 | Hinge Digital LLC                       | 9000.00    | Hinge Digital produced an animated TV Series called TOONAMI spending $80,000 in Oregon.                                                                | 
| FY 2015-2016 | Hive-FX                                 | 8500.00    | Hive-FX provided post-production and VFX services for the National Geographic series SURVIVING AMERICA spending $113,000 in Oregon.                    | 
| FY 2015-2016 | House Special                           | 17373.00   | House Special completed production on their nationally released project JAIL BREAK spending $138,000 in Oregon.                                        | 
| FY 2015-2016 | Iron Way Entertainment LLC              | 8500.00    | Iron Way Ent produced Season 3 of the locally produced, online and PBS series ORIGINAL FARE spending more than $108,000 in Oregon.                     | 
```