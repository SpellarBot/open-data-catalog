# Performance Metrics - Chicago Park District - Comptroller Accounts Payable Aging

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-chicago-park-district-comptroller-accounts-payable-aging-d00b2) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/q93p-dagd) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/q93p-dagd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/q93p-dagd/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | q93p-dagd |
| Name | Performance Metrics - Chicago Park District - Comptroller Accounts Payable Aging |
| Attribution | Chicago Park District |
| Category | Administration & Finance |
| Tags | performance metrics, parks |
| Created | 2011-11-25T20:04:49Z |
| Publication Date | 2012-07-03T20:50:20Z |

## Description

The Office of the Comptroller consists of four divisions that provide financial services to the Parks: General Accounting, Accounts Payable, Accounts Receivable, Payroll and Quality Control. The data displayed below is in relation to the Accounts Payable division and represents the percentage of invoices that are paid  to vendors within 60 days of invoice data.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                             | Data Type | Render Type |
| ======== | ============== | =========== | ================================ | ========= | =========== |
| No       | time           | :updated_at | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | month       | Month                            | text      | text        |
| Yes      | numeric metric | a_p_aging   | % of Invoices Paid within Target | percent   | percent     |
| Yes      | numeric metric | target      | Target                           | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q93p-dagd d:2012-07-02T12:44:33.000Z t:month="May 2011" m:a_p_aging=88 m:target=90

series e:q93p-dagd d:2012-07-02T12:44:38.000Z t:month="Jun 2011" m:a_p_aging=79 m:target=90

series e:q93p-dagd d:2012-07-02T12:44:44.000Z t:month="July 2011" m:a_p_aging=88 m:target=90
```

## Meta Commands

```ls
metric m:a_p_aging p:integer l:"% of Invoices Paid within Target" t:dataTypeName=percent

metric m:target p:integer l:Target t:dataTypeName=percent

entity e:q93p-dagd l:"Performance Metrics - Chicago Park District - Comptroller Accounts Payable Aging" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/q93p-dagd

property e:q93p-dagd t:meta.view v:id=q93p-dagd v:category="Administration & Finance" v:attributionLink=http://www.chicagoparkdistrict.com/ v:averageRating=0 v:name="Performance Metrics - Chicago Park District - Comptroller Accounts Payable Aging" v:attribution="Chicago Park District"

property e:q93p-dagd t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:q93p-dagd t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| :updated_at | month     | a_p_aging | target | 
| =========== | ========= | ========= | ====== | 
| 1341233073  | May 2011  | 88        | 90     | 
| 1341233078  | Jun 2011  | 79        | 90     | 
| 1341233084  | July 2011 | 88        | 90     | 
| 1341233086  | Aug 2011  | 89        | 90     | 
| 1341233089  | Sep 2011  | 85        | 90     | 
| 1341233091  | Oct 2011  | 87        | 90     | 
| 1341233094  | Nov 2011  | 86        | 90     | 
| 1341233096  | Dec 2011  | 62        | 90     | 
| 1341233099  | Jan 2012  | 73        | 90     | 
| 1341233101  | Feb 2012  | 54        | 90     | 
```