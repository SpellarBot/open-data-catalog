# Choose Maryland: Compare States - Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-states-workforce) |
| Metadata | [Link](https://data.maryland.gov/api/views/5esm-neyf) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/5esm-neyf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/5esm-neyf/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 5esm-neyf |
| Name | Choose Maryland: Compare States - Workforce |
| Attribution | Maryland Department of Commerce |
| Category | Business and Economy |
| Tags | maryland, state, compare, employment, unemployment, labor force |
| Created | 2013-07-29T01:08:29Z |
| Publication Date | 2017-04-12T14:07:27Z |

## Description

Workforce summary - employed, unemployed, participation rates, STEM employment.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                                                  | Data Type | Render Type |
| ======== | ============== | ============================ | ===================================================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                                            | meta_data | meta_data   |
| Yes      | series tag     | state                        | State                                                 | text      | text        |
| Yes      | numeric metric | civilian_laborforce          | Civilian Labor Force                                  | number    | number      |
| Yes      | numeric metric | employment                   | Employment                                            | number    | number      |
| Yes      | numeric metric | unemployment                 | Unemployment                                          | number    | number      |
| Yes      | numeric metric | unemployment_rate            | Unemployment Rate (%)                                 | percent   | percent     |
| Yes      | numeric metric | laborforce_rate_total        | Labor Force Participation Rate, Total (%)             | percent   | percent     |
| Yes      | numeric metric | laborforce_rate_male         | Labor Force Participation Rate, Male (%)              | percent   | percent     |
| Yes      | numeric metric | laborforce_rate_female       | Labor Force Participation Rate, Female (%)            | percent   | percent     |
| Yes      | numeric metric | stem_workers                 | Employment in STEM Occupations (%)                    | percent   | percent     |
| Yes      | numeric metric | scientists_engineers_per100k | Doctoral Scientists and Engineers per 100,000 Workers | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5esm-neyf d:2017-04-12T14:06:55.000Z t:state=Alabama m:unemployment_rate=6 m:employment=2039000 m:unemployment=130000 m:scientists_engineers_per100k=358 m:laborforce_rate_male=62.3 m:laborforce_rate_female=51.9 m:civilian_laborforce=2169000 m:laborforce_rate_total=56.9 m:stem_workers=5.1

series e:5esm-neyf d:2017-04-12T14:06:55.000Z t:state=Alaska m:unemployment_rate=6.6 m:employment=337000 m:unemployment=24000 m:scientists_engineers_per100k=426 m:laborforce_rate_male=75.5 m:laborforce_rate_female=65 m:civilian_laborforce=360000 m:laborforce_rate_total=70.5 m:stem_workers=6.2

series e:5esm-neyf d:2017-04-12T14:06:55.000Z t:state=Arizona m:unemployment_rate=5.3 m:employment=3066000 m:unemployment=172000 m:scientists_engineers_per100k=398 m:laborforce_rate_male=63.7 m:laborforce_rate_female=54 m:civilian_laborforce=3238000 m:laborforce_rate_total=58.8 m:stem_workers=6.7
```

## Meta Commands

```ls
metric m:civilian_laborforce p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employment p:integer l:Employment t:dataTypeName=number

metric m:unemployment p:integer l:Unemployment t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate (%)" t:dataTypeName=percent

metric m:laborforce_rate_total p:float l:"Labor Force Participation Rate, Total (%)" t:dataTypeName=percent

metric m:laborforce_rate_male p:float l:"Labor Force Participation Rate, Male (%)" t:dataTypeName=percent

metric m:laborforce_rate_female p:float l:"Labor Force Participation Rate, Female (%)" t:dataTypeName=percent

metric m:stem_workers p:float l:"Employment in STEM Occupations (%)" t:dataTypeName=percent

metric m:scientists_engineers_per100k p:integer l:"Doctoral Scientists and Engineers per 100,000 Workers" t:dataTypeName=number

entity e:5esm-neyf l:"Choose Maryland:  Compare States - Workforce" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/5esm-neyf

property e:5esm-neyf t:meta.view v:id=5esm-neyf v:category="Business and Economy" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare States - Workforce" v:attribution="Maryland Department of Commerce"

property e:5esm-neyf t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:5esm-neyf t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | state       | civilian_laborforce | employment | unemployment | unemployment_rate | laborforce_rate_total | laborforce_rate_male | laborforce_rate_female | stem_workers | scientists_engineers_per100k | 
| =========== | =========== | =================== | ========== | ============ | ================= | ===================== | ==================== | ====================== | ============ | ============================ | 
| 1492006015  | Alabama     | 2169000             | 2039000    | 130000       | 6.0               | 56.9                  | 62.3                 | 51.9                   | 5.1          | 358                          | 
| 1492006015  | Alaska      | 360000              | 337000     | 24000        | 6.6               | 70.5                  | 75.5                 | 65.0                   | 6.2          | 426                          | 
| 1492006015  | Arizona     | 3238000             | 3066000    | 172000       | 5.3               | 58.8                  | 63.7                 | 54.0                   | 6.7          | 398                          | 
| 1492006015  | Arkansas    | 1343000             | 1289000    | 54000        | 4.0               | 57.6                  | 62.7                 | 52.8                   | 4.0          | 244                          | 
| 1492006015  | California  | 19103000            | 18065000   | 1038000      | 5.4               | 63.0                  | 69.4                 | 56.9                   | 7.6          | 693                          | 
| 1492006015  | Colorado    | 2891000             | 2795000    | 96000        | 3.3               | 68.0                  | 73.6                 | 62.5                   | 8.6          | 651                          | 
| 1492006015  | Connecticut | 1892000             | 1796000    | 96000        | 5.1               | 66.7                  | 71.2                 | 62.5                   | 6.7          | 658                          | 
| 1492006015  | Delaware    | 473000              | 452000     | 21000        | 4.4               | 62.5                  | 66.5                 | 58.8                   | 6.9          | 823                          | 
| 1492006015  | Florida     | 9839000             | 9359000    | 480000       | 4.9               | 58.4                  | 63.0                 | 54.1                   | 4.6          | 295                          | 
| 1492006015  | Georgia     | 4920000             | 4656000    | 264000       | 5.4               | 62.6                  | 67.6                 | 58.0                   | 6.0          | 403                          | 
```