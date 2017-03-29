# Historical Budget Summary by Category FY14-FY05

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-budget-summary-by-category-fy14-fy05) |
| Metadata | [Link](https://data.somervillema.gov/api/views/nbhj-n6p6) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/nbhj-n6p6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/nbhj-n6p6/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | nbhj-n6p6 |
| Name | Historical Budget Summary by Category FY14-FY05 |
| Attribution | City of Somerville |
| Category | Finance |
| Tags | budget, finance |
| Created | 2015-08-18T14:19:57Z |
| Publication Date | 2015-08-18T15:00:26Z |

## Description

This table contains historical revenue and expenditures for the fiscal years 2005 through 2014, as well as budgeted spending for FY15.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | category      | Category      | text      | text        |
| Yes      | series tag     | type          | Type          | text      | text        |
| Yes      | series tag     | fy15_budgeted | FY15 Budgeted | text      | text        |
| Yes      | series tag     | fy14_actual   | FY14 Actual   | text      | text        |
| Yes      | series tag     | fy13_actual   | FY13 Actual   | text      | text        |
| Yes      | series tag     | fy12_actual   | FY12 Actual   | text      | text        |
| Yes      | series tag     | fy11_actual   | FY11 Actual   | text      | text        |
| Yes      | series tag     | fy10_actual   | FY10 Actual   | text      | text        |
| Yes      | series tag     | fy09_actual   | FY09 Actual   | text      | text        |
| Yes      | series tag     | fy08_actual   | FY08 Actual   | text      | text        |
| Yes      | series tag     | fy07_actual   | FY07 Actual   | text      | text        |
| Yes      | series tag     | fy06_actual   | FY06 Actual   | text      | text        |
| Yes      | series tag     | fy05_actual   | FY05 Actual   | text      | text        |
| Yes      | numeric metric | fy04_actual   | FY04 Actual   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nbhj-n6p6 d:2015-08-18T07:20:02.000Z t:fy08_actual="* 85,376,533" t:fy10_actual="* 94,988,009" t:fy14_actual="* 113,841,399" t:fy11_actual="* 98,703,496" t:type=Revenue t:fy13_actual="* 108,407,664" t:fy15_budgeted="* 120,467,965" t:category="Real Estate and Personal Property taxes" t:fy12_actual="* 102,975,330" t:fy09_actual="* 90,085,919" t:fy07_actual="* 81,005,608" t:fy05_actual="* 72,674,214" t:fy06_actual="* 76,777,383" m:fy04_actual=69129693

series e:nbhj-n6p6 d:2015-08-18T07:20:02.000Z t:fy08_actual="* 870,517" t:fy10_actual="* 1,078,578" t:fy14_actual="* 847,582" t:fy11_actual="* 1,161,723" t:type=Revenue t:fy13_actual="* 1,118,479" t:fy15_budgeted=0.0 t:category="Tax Liens" t:fy12_actual="* 1,297,050" t:fy09_actual="* 1,165,496" t:fy07_actual="* 660,729" t:fy05_actual="* 1,144,242" t:fy06_actual="* 986,111" m:fy04_actual=881336

series e:nbhj-n6p6 d:2015-08-18T07:20:02.000Z t:fy08_actual="* 5,007,547" t:fy10_actual="* 4,563,267" t:fy14_actual="* 7,759,040" t:fy11_actual="* 4,894,601" t:type=Revenue t:fy13_actual="* 7,206,904" t:fy15_budgeted="* 8,092,927" t:category="Motor Vehicle Exces and other excise taxes" t:fy12_actual="* 6,762,048" t:fy09_actual="* 4,531,602" t:fy07_actual="* 5,009,381" t:fy05_actual="* 5,379,484" t:fy06_actual="* 5,272,658" m:fy04_actual=5353299
```

## Meta Commands

```ls
metric m:fy04_actual p:integer l:"FY04 Actual" t:dataTypeName=number

entity e:nbhj-n6p6 l:"Historical Budget Summary by Category FY14-FY05" t:attribution="City of Somerville" t:url=https://data.somervillema.gov/api/views/nbhj-n6p6

property e:nbhj-n6p6 t:meta.view v:id=nbhj-n6p6 v:category=Finance v:attributionLink=http://www.somervillema.gov v:averageRating=100 v:name="Historical Budget Summary by Category FY14-FY05" v:attribution="City of Somerville"

property e:nbhj-n6p6 t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:nbhj-n6p6 t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:nbhj-n6p6 t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| :updated_at | category                                   | type        | fy15_budgeted | fy14_actual   | fy13_actual   | fy12_actual   | fy11_actual  | fy10_actual  | fy09_actual  | fy08_actual  | fy07_actual  | fy06_actual  | fy05_actual  | fy04_actual | 
| =========== | ========================================== | =========== | ============= | ============= | ============= | ============= | ============ | ============ | ============ | ============ | ============ | ============ | ============ | =========== | 
| 1439882402  | Real Estate and Personal Property taxes    | Revenue     | * 120,467,965 | * 113,841,399 | * 108,407,664 | * 102,975,330 | * 98,703,496 | * 94,988,009 | * 90,085,919 | * 85,376,533 | * 81,005,608 | * 76,777,383 | * 72,674,214 | 69129693    | 
| 1439882402  | Tax Liens                                  | Revenue     | 0.0           | * 847,582     | * 1,118,479   | * 1,297,050   | * 1,161,723  | * 1,078,578  | * 1,165,496  | * 870,517    | * 660,729    | * 986,111    | * 1,144,242  | 881336      | 
| 1439882402  | Motor Vehicle Exces and other excise taxes | Revenue     | * 8,092,927   | * 7,759,040   | * 7,206,904   | * 6,762,048   | * 4,894,601  | * 4,563,267  | * 4,531,602  | * 5,007,547  | * 5,009,381  | * 5,272,658  | * 5,379,484  | 5353299     | 
| 1439882402  | Payment in Lieu of Taxes                   | Revenue     | * 280,000     | * 285,596     | * 182,347     | * 192,334     | * 398,281    | * 163,644    | * 158,827    | * 314,262    | * 131,329    | * 354,342    | * 341,819    | 0           | 
| 1439882402  | Intergovernmental                          | Revenue     | * 48,718,962  | * 48,636,241  | * 46,990,120  | * 47,039,837  | * 49,550,557 | * 48,419,400 | * 52,874,902 | * 57,090,098 | * 55,910,532 | * 52,834,555 | * 52,783,382 | 51121156    | 
| 1439882402  | Departmental and Other                     | Revenue     | * 23,044,756  | * 15,889,255  | * 16,140,477  | * 16,666,181  | * 16,949,907 | * 16,472,773 | * 16,451,131 | * 16,220,081 | * 15,070,380 | * 14,418,864 | * 12,689,433 | 10350164    | 
| 1439882402  | Investment Income                          | Revenue     | * 200,000     | * 195,726     | * 219,363     | * 302,077     | * 384,630    | * 537,733    | * 958,237    | * 1,415,843  | * 1,653,740  | * 1,057,635  | * 613,010    | 407104      | 
| 1439882402  | Miscellaneous                              | Revenue     | * 234,977     | * 268,687     | * 102,500     | * 71,679      | * 229,144    | 0.0          | 0.0          | -            | 0.0          | 0.0          | 0.0          | 0           | 
| 1439882402  | General Government                         | Expenditure | * 17,632,372  | * 15,352,145  | * 14,128,083  | * 10,602,889  | * 10,234,910 | * 10,326,740 | * 10,637,759 | * 10,606,052 | * 9,607,282  | * 9,126,650  | * 7,512,721  | 7007665     | 
| 1439882402  | Public Safety                              | Expenditure | * 37,766,487  | * 35,808,041  | * 35,239,869  | * 35,736,569  | * 30,678,877 | * 30,000,336 | * 30,630,468 | * 31,785,380 | * 25,827,555 | * 25,563,283 | * 24,624,428 | 23895192    | 
```