# IDPH Leading Causes of Death, Young Children - Ages 1-4, 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-leading-causes-of-death-young-children-ages-1-4-2008-e19c4) |
| Metadata | [Link](https://data.illinois.gov/api/views/6i2z-c3xh) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6i2z-c3xh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6i2z-c3xh/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6i2z-c3xh |
| Name | IDPH Leading Causes of Death, Young Children - Ages 1-4, 2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | cause, death, leading |
| Created | 2012-01-18T19:09:35Z |
| Publication Date | 2012-01-23T21:44:24Z |

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
series e:6i2z-c3xh d:2008-01-01T00:00:00.000Z t:cause_of_death=Accidents m:count=44

series e:6i2z-c3xh d:2008-01-01T00:00:00.000Z t:cause_of_death="Congenital malformations, deformations and chromosomal abnormalities" m:count=23

series e:6i2z-c3xh d:2008-01-01T00:00:00.000Z t:cause_of_death="Diseases of heart" m:count=15
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:6i2z-c3xh l:"IDPH Leading Causes of Death, Young Children - Ages 1-4, 2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/6i2z-c3xh

property e:6i2z-c3xh t:meta.view v:id=6i2z-c3xh v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Leading Causes of Death, Young Children - Ages 1-4, 2008" v:attribution="Illinois Center for Health Statistics"

property e:6i2z-c3xh t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:6i2z-c3xh t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| cause_of_death                                                       | count | 
| ==================================================================== | ===== | 
| Accidents                                                            | 44    | 
| Congenital malformations, deformations and chromosomal abnormalities | 23    | 
| Diseases of heart                                                    | 15    | 
| Malignant neoplasms                                                  | 12    | 
| Assault (homicide)                                                   | 12    | 
| Accidents - Motor vehicle                                            | 9     | 
| Accidents - All other                                                | 35    | 
```