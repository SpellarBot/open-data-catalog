# Payment in Lieu of Taxes (PILOT) on Private Tax-Exempt Property

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/payment-in-lieu-of-taxes-pilot-on-private-tax-exempt-property) |
| Metadata | [Link](https://data.ct.gov/api/views/ax65-fnv9) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ax65-fnv9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ax65-fnv9/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ax65-fnv9 |
| Name | Payment in Lieu of Taxes (PILOT) on Private Tax-Exempt Property |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | opm, pilot |
| Created | 2014-08-04T17:28:12Z |
| Publication Date | 2014-08-04T17:34:00Z |

## Description

Office of Policy and Management administers the Payment in Lieu of Taxes (PILOT) on Private Tax-Exempt Property pursuant to CGS ?12-19b(b), ?12-20a and ?12-20b. This program provides payments for real property tax losses due to exemptions applicable to eligible private colleges and general and free standing chronic disease hospitals.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | numeric metric | vendor        | Vendor        | number    | number      |
| Yes      | series tag     | vendor_name_1 | Vendor Name 1 | text      | text        |
| Yes      | numeric metric | amount_fy2004 | Amount FY2004 | money     | money       |
| Yes      | numeric metric | amount_fy2005 | Amount FY2005 | money     | money       |
| Yes      | numeric metric | amount_fy2006 | Amount FY2006 | money     | money       |
| Yes      | numeric metric | amount_fy2007 | Amount FY2007 | money     | money       |
| Yes      | numeric metric | amount_fy2008 | Amount FY2008 | money     | money       |
| Yes      | numeric metric | amount_fy2009 | Amount FY2009 | money     | money       |
| Yes      | numeric metric | amount_fy2010 | Amount FY2010 | money     | money       |
| Yes      | numeric metric | amount_fy2011 | Amount FY2011 | money     | money       |
| Yes      | numeric metric | amount_fy2012 | Amount FY2012 | money     | money       |
| Yes      | numeric metric | amount_fy2013 | Amount FY2013 | money     | money       |
| Yes      | numeric metric | amount_fy2014 | Amount FY2014 | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ax65-fnv9 d:2014-08-04T10:28:16.000Z t:vendor_name_1="TOWN OF AVON" m:amount_fy2011=7283.85 m:amount_fy2012=3232.19 m:amount_fy2013=0 m:amount_fy2014=0 m:amount_fy2006=10884.4 m:amount_fy2007=11257.8 m:amount_fy2004=11324.74 m:vendor=4 m:amount_fy2005=11133.84 m:amount_fy2009=10983.9 m:amount_fy2008=11056.57 m:amount_fy2010=9201.87

series e:ax65-fnv9 d:2014-08-04T10:28:16.000Z t:vendor_name_1="TOWN OF BETHANY" m:amount_fy2011=19074.47 m:amount_fy2012=17182.21 m:amount_fy2013=16483.79 m:amount_fy2014=15055.77 m:amount_fy2006=23765.78 m:amount_fy2007=25226.99 m:amount_fy2004=29372.13 m:vendor=8 m:amount_fy2005=27992.64 m:amount_fy2009=25145.03 m:amount_fy2008=25056.24 m:amount_fy2010=20792.81

series e:ax65-fnv9 d:2014-08-04T10:28:16.000Z t:vendor_name_1="TOWN OF BETHEL" m:amount_fy2011=19002.28 m:amount_fy2012=17395.62 m:amount_fy2013=16969.35 m:amount_fy2014=15782.82 m:amount_fy2006=23561.89 m:amount_fy2007=24592.87 m:amount_fy2004=62728.03 m:vendor=9 m:amount_fy2005=22671.21 m:amount_fy2009=24120.06 m:amount_fy2008=24608.85 m:amount_fy2010=20200.54
```

## Meta Commands

```ls
metric m:vendor p:integer l:Vendor t:dataTypeName=number

metric m:amount_fy2004 p:double l:"Amount FY2004" t:dataTypeName=money

metric m:amount_fy2005 p:double l:"Amount FY2005" t:dataTypeName=money

metric m:amount_fy2006 p:double l:"Amount FY2006" t:dataTypeName=money

metric m:amount_fy2007 p:double l:"Amount FY2007" t:dataTypeName=money

metric m:amount_fy2008 p:double l:"Amount FY2008" t:dataTypeName=money

metric m:amount_fy2009 p:double l:"Amount FY2009" t:dataTypeName=money

metric m:amount_fy2010 p:double l:"Amount FY2010" t:dataTypeName=money

metric m:amount_fy2011 p:double l:"Amount FY2011" t:dataTypeName=money

metric m:amount_fy2012 p:double l:"Amount FY2012" t:dataTypeName=money

metric m:amount_fy2013 p:double l:"Amount FY2013" t:dataTypeName=money

metric m:amount_fy2014 p:double l:"Amount FY2014" t:dataTypeName=money

entity e:ax65-fnv9 l:"Payment in Lieu of Taxes (PILOT) on Private Tax-Exempt Property" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/ax65-fnv9

property e:ax65-fnv9 t:meta.view v:id=ax65-fnv9 v:category=Government v:averageRating=0 v:name="Payment in Lieu of Taxes (PILOT) on Private Tax-Exempt Property" v:attribution="Office of Policy and Management"

property e:ax65-fnv9 t:meta.view.license v:name="Public Domain"

property e:ax65-fnv9 t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:ax65-fnv9 t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| :updated_at | vendor | vendor_name_1      | amount_fy2004 | amount_fy2005 | amount_fy2006 | amount_fy2007 | amount_fy2008 | amount_fy2009 | amount_fy2010 | amount_fy2011 | amount_fy2012 | amount_fy2013 | amount_fy2014 | 
| =========== | ====== | ================== | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | 
| 1407148096  | 4      | TOWN OF AVON       | 11324.74      | 11133.84      | 10884.40      | 11257.80      | 11056.57      | 10983.90      | 9201.87       | 7283.85       | 3232.19       | 0.00          | 0.00          | 
| 1407148096  | 8      | TOWN OF BETHANY    | 29372.13      | 27992.64      | 23765.78      | 25226.99      | 25056.24      | 25145.03      | 20792.81      | 19074.47      | 17182.21      | 16483.79      | 15055.77      | 
| 1407148096  | 9      | TOWN OF BETHEL     | 62728.03      | 22671.21      | 23561.89      | 24592.87      | 24608.85      | 24120.06      | 20200.54      | 19002.28      | 17395.62      | 16969.35      | 15782.82      | 
| 1407148096  | 11     | TOWN OF BLOOMFIELD | 253276.38     | 248631.02     | 264793.91     | 190963.01     | 190980.01     | 194917.17     | 161659.50     | 150557.31     | 218857.51     | 212319.59     | 195473.41     | 
| 1407148096  | 14     | TOWN OF BRANFORD   | 121148.18     | 120476.28     | 121538.64     | 121633.12     | 121434.67     | 121252.91     | 117822.89     | 116749.57     | 114614.98     | 114174.92     | 113085.82     | 
| 1407148096  | 15     | CITY OF BRIDGEPORT | 7998647.43    | 7513037.86    | 9988123.43    | 11023396.18   | 11748632.85   | 11200500.00   | 9917386.81    | 8700528.95    | 8537526.34    | 8045925.70    | 7563747.43    | 
| 1407148096  | 17     | CITY OF BRISTOL    | 695837.52     | 781634.22     | 872113.64     | 893799.41     | 908664.42     | 896803.87     | 675228.79     | 624626.95     | 573473.53     | 552637.04     | 521930.05     | 
| 1407148096  | 21     | TOWN OF CANAAN     | 0.00          | 0.00          | 0.00          | 0.00          | 2476.09       | 2392.42       | 2770.93       | 2515.54       | 2279.19       | 2256.90       | 2026.71       | 
| 1407148096  | 25     | TOWN OF CHESHIRE   | 0.00          | 0.00          | 0.00          | 194210.19     | 188921.64     | 185563.56     | 152156.24     | 158658.43     | 142485.27     | 135981.68     | 123840.65     | 
| 1407148096  | 33     | TOWN OF CROMWELL   | 139388.61     | 116184.89     | 128286.04     | 128730.31     | 135670.47     | 130457.81     | 59877.57      | 55283.05      | 49673.01      | 58349.93      | 51354.84      | 
```