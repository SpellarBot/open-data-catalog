# IDPH Leading Causes of Death, All Ages, 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-leading-causes-of-death-all-ages-2008-754dd) |
| Metadata | [Link](https://data.illinois.gov/api/views/ukeb-2mep) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ukeb-2mep/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ukeb-2mep/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ukeb-2mep |
| Name | IDPH Leading Causes of Death, All Ages, 2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | cause death |
| Created | 2012-01-18T21:20:30Z |
| Publication Date | 2012-01-23T21:26:55Z |

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
series e:ukeb-2mep d:2008-01-01T00:00:00.000Z t:cause_of_death="Diseases of heart" m:count=25979

series e:ukeb-2mep d:2008-01-01T00:00:00.000Z t:cause_of_death="Malignant neoplasms" m:count=24210

series e:ukeb-2mep d:2008-01-01T00:00:00.000Z t:cause_of_death="Cerebrovascular diseases" m:count=5765
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:ukeb-2mep l:"IDPH Leading Causes of Death, All Ages, 2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/ukeb-2mep

property e:ukeb-2mep t:meta.view v:id=ukeb-2mep v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Leading Causes of Death, All Ages, 2008" v:attribution="Illinois Center for Health Statistics"

property e:ukeb-2mep t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:ukeb-2mep t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| cause_of_death                     | count | 
| ================================== | ===== | 
| Diseases of heart                  | 25979 | 
| Malignant neoplasms                | 24210 | 
| Cerebrovascular diseases           | 5765  | 
| Chronic lower respiratory diseases | 5584  | 
| Accidents                          | 4173  | 
| Accidents - Motor vehicle          | 1138  | 
| Accidents - All other              | 3035  | 
| Alzheimer's disease                | 3188  | 
| Diabetes mellitus                  | 2839  | 
| Influenza and pneumonia            | 2663  | 
```