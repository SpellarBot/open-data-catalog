# Payment in Lieu of Taxes (PILOT) on State Property

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/payment-in-lieu-of-taxes-pilot-on-state-property) |
| Metadata | [Link](https://data.ct.gov/api/views/vr9v-n6m6) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/vr9v-n6m6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/vr9v-n6m6/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | vr9v-n6m6 |
| Name | Payment in Lieu of Taxes (PILOT) on State Property |
| Category | Government |
| Created | 2014-08-01T16:29:48Z |
| Publication Date | 2014-08-01T16:35:42Z |

## Description

The Office of Policy and Management administers the Payment in Lieu of Taxes (PILOT) on State Property program pursuant to CGS ?12-19a, ?12-19b, ?12-19c, ?4b-39, ?32-666, and PA 13-277 ? 58-61. This program provides payments for real property tax losses due to exemptions applicable to state-owned real property, certain real property that is the subject of a state lease or long-term financing contract, municipally-owned airports and certain land held in trust by the federal government.

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
series e:vr9v-n6m6 d:2014-08-01T09:29:52.000Z t:vendor_name_1="TOWN OF ANDOVER" m:amount_fy2011=24956.52 m:amount_fy2012=22292.75 m:amount_fy2013=21124.18 m:amount_fy2014=18766.88 m:amount_fy2006=32889.35 m:amount_fy2007=35614.93 m:amount_fy2004=34256.37 m:vendor=1 m:amount_fy2005=33608.22 m:amount_fy2009=30710.5 m:amount_fy2008=42394.82 m:amount_fy2010=26498.55

series e:vr9v-n6m6 d:2014-08-01T09:29:52.000Z t:vendor_name_1="CITY OF ANSONIA" m:amount_fy2011=100811.99 m:amount_fy2012=98287.73 m:amount_fy2013=96030.41 m:amount_fy2014=94496.74 m:amount_fy2006=88938.94 m:amount_fy2007=90864.96 m:amount_fy2004=90773.01 m:vendor=2 m:amount_fy2005=86609.54 m:amount_fy2009=78342.33 m:amount_fy2008=90718.24 m:amount_fy2010=108217.62

series e:vr9v-n6m6 d:2014-08-01T09:29:52.000Z t:vendor_name_1="TOWN OF ASHFORD" m:amount_fy2011=6085.64 m:amount_fy2012=6002.15 m:amount_fy2013=5791.07 m:amount_fy2014=5628.54 m:amount_fy2006=6747.45 m:amount_fy2007=6892.71 m:amount_fy2004=6886.09 m:vendor=3 m:amount_fy2005=6329.18 m:amount_fy2009=7000.75 m:amount_fy2008=6866.27 m:amount_fy2010=6117.38
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

entity e:vr9v-n6m6 l:"Payment in Lieu of Taxes (PILOT) on State Property" t:url=https://data.ct.gov/api/views/vr9v-n6m6

property e:vr9v-n6m6 t:meta.view v:id=vr9v-n6m6 v:category=Government v:averageRating=0 v:name="Payment in Lieu of Taxes (PILOT) on State Property"

property e:vr9v-n6m6 t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:vr9v-n6m6 t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| :updated_at | vendor | vendor_name_1        | amount_fy2004 | amount_fy2005 | amount_fy2006 | amount_fy2007 | amount_fy2008 | amount_fy2009 | amount_fy2010 | amount_fy2011 | amount_fy2012 | amount_fy2013 | amount_fy2014 | 
| =========== | ====== | ==================== | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | 
| 1406885392  | 1      | TOWN OF ANDOVER      | 34256.37      | 33608.22      | 32889.35      | 35614.93      | 42394.82      | 30710.50      | 26498.55      | 24956.52      | 22292.75      | 21124.18      | 18766.88      | 
| 1406885392  | 2      | CITY OF ANSONIA      | 90773.01      | 86609.54      | 88938.94      | 90864.96      | 90718.24      | 78342.33      | 108217.62     | 100811.99     | 98287.73      | 96030.41      | 94496.74      | 
| 1406885392  | 3      | TOWN OF ASHFORD      | 6886.09       | 6329.18       | 6747.45       | 6892.71       | 6866.27       | 7000.75       | 6117.38       | 6085.64       | 6002.15       | 5791.07       | 5628.54       | 
| 1406885392  | 4      | TOWN OF AVON         | 74578.99      | 79484.82      | 67798.12      | 69969.34      | 68647.86      | 70467.79      | 63803.24      | 92641.28      | 92464.75      | 90796.11      | 86888.52      | 
| 1406885392  | 5      | TOWN OF BARKHAMSTED  | 17753.50      | 18744.98      | 16433.01      | 16990.12      | 16578.99      | 16564.98      | 13769.49      | 18663.35      | 18346.36      | 17540.19      | 16897.42      | 
| 1406885392  | 6      | TOWN OF BEACON FALLS | 60278.16      | 59179.19      | 68584.57      | 69249.82      | 67665.59      | 58453.67      | 52981.05      | 45046.14      | 45500.04      | 44460.18      | 45746.75      | 
| 1406885392  | 7      | TOWN OF BERLIN       | 19376.35      | 6779.98       | 17028.10      | 21806.90      | 21050.18      | 21016.36      | 26999.02      | 25151.40      | 25505.15      | 25341.85      | 24302.41      | 
| 1406885392  | 8      | TOWN OF BETHANY      | 47801.53      | 47525.39      | 40200.78      | 42577.80      | 41621.49      | 43160.40      | 36770.28      | 37861.91      | 36934.02      | 36053.81      | 34257.90      | 
| 1406885392  | 9      | TOWN OF BETHEL       | 35639.37      | 27389.79      | 28353.45      | 29528.27      | 29517.39      | 29894.61      | 27140.34      | 26355.19      | 26249.30      | 26054.55      | 25209.82      | 
| 1406885392  | 10     | TOWN OF BETHLEHEM    | 1731.15       | 1807.89       | 1274.97       | 1375.89       | 1392.74       | 1467.71       | 1191.63       | 1359.58       | 1290.45       | 1203.09       | 1114.59       | 
```