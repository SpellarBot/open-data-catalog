# IDPH Leading Causes of Death, Youth - Ages 15-24, 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-leading-causes-of-death-youth-ages-15-24-2008-6362e) |
| Metadata | [Link](https://data.illinois.gov/api/views/7yct-c7in) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/7yct-c7in/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/7yct-c7in/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 7yct-c7in |
| Name | IDPH Leading Causes of Death, Youth - Ages 15-24, 2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | cause, death |
| Created | 2012-01-18T21:13:49Z |
| Publication Date | 2012-01-23T21:43:39Z |

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
series e:7yct-c7in d:2008-01-01T00:00:00.000Z t:cause_of_death=Accidents m:count=470

series e:7yct-c7in d:2008-01-01T00:00:00.000Z t:cause_of_death="Accidents - Motor vehicle" m:count=262

series e:7yct-c7in d:2008-01-01T00:00:00.000Z t:cause_of_death="Accidents - All other" m:count=208
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:7yct-c7in l:"IDPH Leading Causes of Death, Youth - Ages 15-24, 2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/7yct-c7in

property e:7yct-c7in t:meta.view v:id=7yct-c7in v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Leading Causes of Death, Youth - Ages 15-24, 2008" v:attribution="Illinois Center for Health Statistics"

property e:7yct-c7in t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:7yct-c7in t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| cause_of_death                  | count | 
| =============================== | ===== | 
| Accidents                       | 470   | 
| Accidents - Motor vehicle       | 262   | 
| Accidents - All other           | 208   | 
| Assault (homicide)              | 340   | 
| Intentional self-harm (suicide) | 133   | 
| Malignant neoplasms             | 65    | 
| Diseases of heart               | 41    | 
```