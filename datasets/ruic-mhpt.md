# IDPH Infant Mortality, State Totals, 1907-2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-infant-mortality-state-totals-1907-2008-78e60) |
| Metadata | [Link](https://data.illinois.gov/api/views/ruic-mhpt) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ruic-mhpt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ruic-mhpt/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ruic-mhpt |
| Name | IDPH Infant Mortality, State Totals, 1907-2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | infant, mortality |
| Created | 2012-01-17T22:04:48Z |
| Publication Date | 2012-01-23T21:45:34Z |

## Description

* 1950 - 2007: Resident data from tabulations in Illinois Department of Public Health.
(1953 - 1954 Maternal deaths from Vital Statistics of the United States)
** 1940 - 1949: Resident data from Vital Statistics of the United States for each year.
*** 1918 - 1939: Occurrence data from United States Bureau of the Census publications.
NA (not available)

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | year        | Year       | text      | text        |
| Yes      | numeric metric | number      | Number     | number    | number      |
| Yes      | numeric metric | rate        | Rate       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ruic-mhpt d:2012-01-17T14:04:57.000Z t:year=2008* m:rate=7.2 m:number=1263

series e:ruic-mhpt d:2012-01-17T14:04:57.000Z t:year=2007* m:rate=6.6 m:number=1196

series e:ruic-mhpt d:2012-01-17T14:04:57.000Z t:year=2006* m:rate=7.4 m:number=1343
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

metric m:rate p:float l:Rate t:dataTypeName=number

entity e:ruic-mhpt l:"IDPH Infant Mortality, State Totals, 1907-2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/ruic-mhpt

property e:ruic-mhpt t:meta.view v:id=ruic-mhpt v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Infant Mortality, State Totals, 1907-2008" v:attribution="Illinois Center for Health Statistics"

property e:ruic-mhpt t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:ruic-mhpt t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| :updated_at | year  | number | rate | 
| =========== | ===== | ====== | ==== | 
| 1326809097  | 2008* | 1263   | 7.2  | 
| 1326809097  | 2007* | 1196   | 6.6  | 
| 1326809097  | 2006* | 1343   | 7.4  | 
| 1326809097  | 2005* | 1294   | 7.2  | 
| 1326809097  | 2004* | 1317   | 7.3  | 
| 1326809097  | 2003* | 1380   | 7.6  | 
| 1326809097  | 2002* | 1304   | 7.2  | 
| 1326809097  | 2001* | 1379   | 7.5  | 
| 1326809097  | 2000* | 1528   | 8.3  | 
| 1326809097  | 1999* | 1504   | 8.3  | 
```