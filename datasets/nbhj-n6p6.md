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
| Rows Updated | 2015-08-18T14:20:11Z |

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

property e:nbhj-n6p6 t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"

property e:nbhj-n6p6 t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```