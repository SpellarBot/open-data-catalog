# IDES - Mass Layoffs in Illinois, monthly and annual

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ides-mass-layoffs-in-illinois-monthly-and-annual-f9f5b) |
| Metadata | [Link](https://data.illinois.gov/api/views/6jt3-ntuh) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6jt3-ntuh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6jt3-ntuh/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6jt3-ntuh |
| Name | IDES - Mass Layoffs in Illinois, monthly and annual |
| Attribution | IDES - Economic Information and Analysis Division |
| Category | Economics |
| Tags | ides - mass layoffs in illinois, monthly and annual, layoff, ides |
| Created | 2012-05-02T19:36:24Z |
| Publication Date | 2012-05-03T16:20:36Z |

## Description

Includes all potential mass layoff events, regardless of the reason for the layoffs or their duration (i.e.temporary, extended; seasonal and economic related layoffs)
The number of weeks included in each month can vary each year, thereby limiting comparability across years.
Preliminary data.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                         | Data Type | Render Type |
| ======== | ============== | ========================================== | ============================================ | ========= | =========== |
| No       | time           | :updated_at                                | updated_at                                   | meta_data | meta_data   |
| Yes      | series tag     | month                                      | Month                                        | text      | text        |
| Yes      | numeric metric | layoff_events                              | Layoff Events                                | number    | text        |
| Yes      | numeric metric | initial_claims                             | Initial Claims                               | number    | text        |
| Yes      | series tag     | layoff_events_same_month_one_year_earlier  | Layoff Events: Same Month, One Year Earlier  | text      | text        |
| Yes      | series tag     | initial_claims_same_month_one_year_earlier | Initial Claims: Same Month, One Year Earlier | text      | text        |
| Yes      | series tag     | over_the_year_change_layoffs               | Over the Year Change: Layoffs                | text      | text        |
| Yes      | series tag     | over_the_year_change_initial_claims        | Over the Year Change: Initial Claims         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6jt3-ntuh d:2012-05-02T12:36:25.000Z t:initial_claims_same_month_one_year_earlier=14,519 t:over_the_year_change_layoffs=-27 t:month=Year-to-Date t:over_the_year_change_initial_claims=-1,795 t:layoff_events_same_month_one_year_earlier=158 m:layoff_events=131 m:initial_claims=12724

series e:6jt3-ntuh d:2012-05-02T12:36:25.000Z t:initial_claims_same_month_one_year_earlier=3,495 t:over_the_year_change_layoffs=-1 t:month=Mar-12 t:over_the_year_change_initial_claims=1,115 t:layoff_events_same_month_one_year_earlier=37 m:layoff_events=36 m:initial_claims=4610

series e:6jt3-ntuh d:2012-05-02T12:36:25.000Z t:initial_claims_same_month_one_year_earlier=3,508 t:over_the_year_change_layoffs=5 t:month=Feb-12 t:over_the_year_change_initial_claims=-217 t:layoff_events_same_month_one_year_earlier=35 m:layoff_events=40 m:initial_claims=3291
```

## Meta Commands

```ls
metric m:layoff_events p:long l:"Layoff Events" t:dataTypeName=number

metric m:initial_claims p:long l:"Initial Claims" t:dataTypeName=number

entity e:6jt3-ntuh l:"IDES - Mass Layoffs in Illinois, monthly and annual" t:attribution="IDES - Economic Information and Analysis Division" t:url=https://data.illinois.gov/api/views/6jt3-ntuh

property e:6jt3-ntuh t:meta.view v:id=6jt3-ntuh v:category=Economics v:averageRating=0 v:name="IDES - Mass Layoffs in Illinois, monthly and annual" v:attribution="IDES - Economic Information and Analysis Division"

property e:6jt3-ntuh t:meta.view.owner v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"

property e:6jt3-ntuh t:meta.view.tableauthor v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"
```

## Top Records

```ls
| :updated_at | month        | layoff_events | initial_claims | layoff_events_same_month_one_year_earlier | initial_claims_same_month_one_year_earlier | over_the_year_change_layoffs | over_the_year_change_initial_claims | 
| =========== | ============ | ============= | ============== | ========================================= | ========================================== | ============================ | =================================== | 
| 1335962185  | Year-to-Date | 131           | 12,724         | 158                                       | 14,519                                     | -27                          | -1,795                              | 
| 1335962185  | Mar-12       | 36            | 4,610          | 37                                        | 3,495                                      | -1                           | 1,115                               | 
| 1335962185  | Feb-12       | 40            | 3,291          | 35                                        | 3,508                                      | 5                            | -217                                | 
| 1335962185  | Jan-12       | 55            | 4,823          | 86                                        | 7,516                                      | -31                          | -2,693                              | 
| 1335962185  | 2011-totals  | 676           | 72,086         |                                           |                                            |                              |                                     | 
| 1335962185  | Dec-11       | 118           | 13,449         | 110                                       | 13,672                                     | 8                            | -223                                | 
| 1335962185  | Nov-11       | 57            | 5,056          | 59                                        | 5,386                                      | -2                           | -330                                | 
| 1335962185  | Oct-11       | 48            | 4,971          | 60                                        | 7,281                                      | -12                          | -2,310                              | 
| 1335962185  | Sep-11       | 48            | 5,092          | 35                                        | 5,053                                      | 13                           | 39                                  | 
| 1335962185  | Aug-11       | 35            | 5,514          | 32                                        | 3,707                                      | 3                            | 1,807                               | 
```