# IDPH Leading Causes of Death, Children - Ages 5-14, 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-leading-causes-of-death-children-ages-5-14-2008-ff909) |
| Metadata | [Link](https://data.illinois.gov/api/views/maiz-s72e) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/maiz-s72e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/maiz-s72e/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | maiz-s72e |
| Name | IDPH Leading Causes of Death, Children - Ages 5-14, 2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Created | 2012-01-18T19:13:16Z |
| Publication Date | 2012-01-23T21:44:01Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | cause_of_death | Cause of Death | text      | text        |
| Yes      | numeric metric | count          | Count          | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:maiz-s72e d:2008-01-01T00:00:00.000Z t:cause_of_death=Accidents m:count=64

series e:maiz-s72e d:2008-01-01T00:00:00.000Z t:cause_of_death="Accidents - Motor vehicle" m:count=36

series e:maiz-s72e d:2008-01-01T00:00:00.000Z t:cause_of_death="Accidents - All other" m:count=28
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:maiz-s72e l:"IDPH Leading Causes of Death, Children - Ages 5-14, 2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/maiz-s72e

property e:maiz-s72e t:meta.view v:id=maiz-s72e v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Leading Causes of Death, Children - Ages 5-14, 2008" v:attribution="Illinois Center for Health Statistics"

property e:maiz-s72e t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:maiz-s72e t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| cause_of_death                                                       | count | 
| ==================================================================== | ===== | 
| Accidents                                                            | 64    | 
| Accidents - Motor vehicle                                            | 36    | 
| Accidents - All other                                                | 28    | 
| Malignant neoplasms                                                  | 30    | 
| Assault (homicide)                                                   | 19    | 
| Diseases of heart                                                    | 14    | 
| Congenital malformations, deformations and chromosomal abnormalities | 11    | 
| Intentional self-harm (suicide)                                      | 10    | 
```