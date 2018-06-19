# Park Scores 2005-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/park-scores-2005-2014) |
| Metadata | [Link](https://data.sfgov.org/api/views/fjq8-r8ws) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/fjq8-r8ws/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/fjq8-r8ws/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | fjq8-r8ws |
| Name | Park Scores 2005-2014 |
| Attribution | San Francisco Recreation & Parks Department |
| Category | Culture and Recreation |
| Tags | park scores, prop c, park, park maintenance |
| Created | 2016-03-29T21:22:47Z |
| Publication Date | 2016-04-04T16:22:16Z |

## Description

Average quarterly park evaluation scores from Q3 FY2005 to Q4 FY2014. These scores are collected and reported pursuant to 2003's Prop C, which requires city agencies to establish and publish standards for street, sidewalk, and park maintenance. Beginning FY2015 a new methodology was developed to evaluate parks, therefore these scores should not form the basis of direct comparisons with scores reported in FY2015 and onward. FY2015 data onward is published and maintained by the SF Controller's Office.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | parkid     | ParkID | text      | number      |
| Yes      | series tag     | psa        | PSA    | text      | text        |
| Yes      | series tag     | park       | Park   | text      | text        |
| No       |                | fq         | FQ     | text      | text        |
| Yes      | numeric metric | score      | Score  | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = fq
```

## Data Commands

```ls
series e:fjq8-r8ws d:2005-01-01T00:00:00.000Z t:park="Carl Larsen Park" t:parkid=86 t:psa=PSA4 m:score=0.795

series e:fjq8-r8ws d:2005-01-01T00:00:00.000Z t:park="Junipero Serra Playground" t:parkid=13 t:psa=PSA4 m:score=0.957

series e:fjq8-r8ws d:2005-01-01T00:00:00.000Z t:park="Rolph Nicol Playground" t:parkid=9 t:psa=PSA4 m:score=0.864
```

## Meta Commands

```ls
metric m:score p:double l:Score t:dataTypeName=number

entity e:fjq8-r8ws l:"Park Scores 2005-2014" t:attribution="San Francisco Recreation & Parks Department" t:url=https://data.sfgov.org/api/views/fjq8-r8ws

property e:fjq8-r8ws t:meta.view v:id=fjq8-r8ws v:category="Culture and Recreation" v:averageRating=0 v:name="Park Scores 2005-2014" v:attribution="San Francisco Recreation & Parks Department"

property e:fjq8-r8ws t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:fjq8-r8ws t:meta.view.owner v:id=qivp-g7uh v:screenName="Eric Pawlowsky" v:displayName="Eric Pawlowsky"

property e:fjq8-r8ws t:meta.view.tableauthor v:id=qivp-g7uh v:screenName="Eric Pawlowsky" v:roleName=editor v:displayName="Eric Pawlowsky"
```

## Top Records

```ls
| parkid | psa  | park                      | fq     | score               | 
| ====== | ==== | ========================= | ====== | =================== | 
| 86     | PSA4 | Carl Larsen Park          | FY05Q3 | 0.79500000000000004 | 
| 13     | PSA4 | Junipero Serra Playground | FY05Q3 | 0.95699999999999996 | 
| 9      | PSA4 | Rolph Nicol Playground    | FY05Q3 | 0.86399999999999999 | 
| 117    | PSA2 | Alamo Square              | FY05Q4 | 0.85699999999999998 | 
| 60     | PSA6 | Jose Coronado Playground  | FY05Q4 | 0.85899999999999999 | 
| 42     | PSA3 | Little Hollywood Park     | FY05Q4 | 0.84599999999999997 | 
| 10     | PSA4 | Lake Merced Park          | FY05Q4 | 0.73                | 
| 94     | GGP  | Golden Gate Park          | FY05Q4 | 0.58799999999999997 | 
| 104    | PSA2 | Grattan Playground        | FY05Q4 | 0.873               | 
| 153    | PSA1 | Francisco Park            | FY05Q4 | 1                   | 
```