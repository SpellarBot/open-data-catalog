# IDPH Births to Teen Mothers, State Total, by Age, 1959-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-births-to-teen-mothers-state-total-by-age-1959-2009-eb7de) |
| Metadata | [Link](https://data.illinois.gov/api/views/kci4-pwje) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kci4-pwje/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kci4-pwje/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kci4-pwje |
| Name | IDPH Births to Teen Mothers, State Total, by Age, 1959-2009 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | teen, mother, birth |
| Created | 2012-01-18T21:58:58Z |
| Publication Date | 2012-01-23T21:24:59Z |

## Description

* Prior to 1980, age 15 - 17 and age 18 - 19 were not reported separately.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | time           | year                         | Year                         | number    | number      |
| Yes      | numeric metric | births_to_all_ages           | Births to All Ages           | number    | number      |
| Yes      | numeric metric | maternal_ages_10_14          | Maternal Ages 10 - 14        | number    | number      |
| Yes      | numeric metric | maternal_ages_15_17_         | Maternal Ages 15 - 17*       | number    | number      |
| Yes      | numeric metric | maternal_ages_18_19_         | Maternal Ages 18 - 19*       | number    | number      |
| Yes      | numeric metric | maternal_ages_15_19          | Maternal Ages 15 - 19        | number    | number      |
| Yes      | numeric metric | teen_births                  | Teen Births                  | number    | number      |
| Yes      | numeric metric | births_to_teens_mothers_rate | Births to Teens Mothers Rate | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kci4-pwje d:2009-01-01T00:00:00.000Z m:maternal_ages_10_14=186 m:maternal_ages_15_17_=5057 m:maternal_ages_15_19=16190 m:births_to_all_ages=171077 m:teen_births=16376 m:maternal_ages_18_19_=11133 m:births_to_teens_mothers_rate=9.6

series e:kci4-pwje d:2008-01-01T00:00:00.000Z m:maternal_ages_10_14=256 m:maternal_ages_15_17_=5653 m:maternal_ages_15_19=17397 m:births_to_all_ages=176634 m:teen_births=17653 m:maternal_ages_18_19_=11744 m:births_to_teens_mothers_rate=10

series e:kci4-pwje d:2007-01-01T00:00:00.000Z m:maternal_ages_10_14=260 m:maternal_ages_15_17_=5988 m:maternal_ages_15_19=18054 m:births_to_all_ages=180530 m:teen_births=18314 m:maternal_ages_18_19_=12066 m:births_to_teens_mothers_rate=10.1
```

## Meta Commands

```ls
metric m:births_to_all_ages p:integer l:"Births to All Ages" t:dataTypeName=number

metric m:maternal_ages_10_14 p:integer l:"Maternal Ages 10 - 14" t:dataTypeName=number

metric m:maternal_ages_15_17_ p:integer l:"Maternal Ages 15 - 17*" t:dataTypeName=number

metric m:maternal_ages_18_19_ p:integer l:"Maternal Ages 18 - 19*" t:dataTypeName=number

metric m:maternal_ages_15_19 p:integer l:"Maternal Ages 15 - 19" t:dataTypeName=number

metric m:teen_births p:integer l:"Teen Births" t:dataTypeName=number

metric m:births_to_teens_mothers_rate p:float l:"Births to Teens Mothers Rate" t:dataTypeName=number

entity e:kci4-pwje l:"IDPH Births to Teen Mothers, State Total, by Age, 1959-2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/kci4-pwje

property e:kci4-pwje t:meta.view v:id=kci4-pwje v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Births to Teen Mothers, State Total, by Age, 1959-2009" v:attribution="Illinois Center for Health Statistics"

property e:kci4-pwje t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:kci4-pwje t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| year | births_to_all_ages | maternal_ages_10_14 | maternal_ages_15_17_ | maternal_ages_18_19_ | maternal_ages_15_19 | teen_births | births_to_teens_mothers_rate | 
| ==== | ================== | =================== | ==================== | ==================== | =================== | =========== | ============================ | 
| 2009 | 171077             | 186                 | 5057                 | 11133                | 16190               | 16376       | 9.6                          | 
| 2008 | 176634             | 256                 | 5653                 | 11744                | 17397               | 17653       | 10.0                         | 
| 2007 | 180530             | 260                 | 5988                 | 12066                | 18054               | 18314       | 10.1                         | 
| 2006 | 180503             | 275                 | 6120                 | 11632                | 17752               | 18027       | 10.0                         | 
| 2005 | 178872             | 319                 | 5794                 | 11241                | 17035               | 17354       | 9.7                          | 
| 2004 | 180665             | 295                 | 5983                 | 11541                | 17524               | 17819       | 9.9                          | 
| 2003 | 182393             | 276                 | 5922                 | 11472                | 17394               | 17670       | 9.7                          | 
| 2002 | 180555             | 318                 | 6090                 | 12138                | 18228               | 18546       | 10.3                         | 
| 2001 | 184022             | 344                 | 6635                 | 13113                | 19748               | 20092       | 10.9                         | 
| 2000 | 185003             | 392                 | 7156                 | 13560                | 20716               | 21108       | 11.4                         | 
```