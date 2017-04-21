# IDPH Leading Causes of Death, Adults - Ages 45-64, 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-leading-causes-of-death-adults-ages-45-64-2008-2f6eb) |
| Metadata | [Link](https://data.illinois.gov/api/views/kait-c3i5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kait-c3i5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kait-c3i5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kait-c3i5 |
| Name | IDPH Leading Causes of Death, Adults - Ages 45-64, 2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | cause, death |
| Created | 2012-01-18T21:17:14Z |
| Publication Date | 2012-01-23T21:26:40Z |

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
series e:kait-c3i5 d:2008-01-01T00:00:00.000Z t:cause_of_death="Malignant neoplasms" m:count=6601

series e:kait-c3i5 d:2008-01-01T00:00:00.000Z t:cause_of_death="Diseases of heart" m:count=4566

series e:kait-c3i5 d:2008-01-01T00:00:00.000Z t:cause_of_death=Accidents m:count=1029
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:kait-c3i5 l:"IDPH Leading Causes of Death, Adults - Ages 45-64, 2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/kait-c3i5

property e:kait-c3i5 t:meta.view v:id=kait-c3i5 v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Leading Causes of Death, Adults - Ages 45-64, 2008" v:attribution="Illinois Center for Health Statistics"

property e:kait-c3i5 t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:kait-c3i5 t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| cause_of_death                      | count | 
| =================================== | ===== | 
| Malignant neoplasms                 | 6601  | 
| Diseases of heart                   | 4566  | 
| Accidents                           | 1029  | 
| Accidents - Motor vehicle           | 272   | 
| Accidents - All other               | 757   | 
| Cerebrovascular diseases            | 692   | 
| Chronic lower respiratory diseases  | 654   | 
| Diabetes mellitus                   | 630   | 
| Chronic liver disease and cirrhosis | 614   | 
| Intentional self-harm (suicide)     | 449   | 
```