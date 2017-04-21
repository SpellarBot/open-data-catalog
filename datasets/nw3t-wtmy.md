# IDPH Infant Mortality, State Total, by Race, 1980-2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-infant-mortality-state-total-by-race-1980-2008-c7c20) |
| Metadata | [Link](https://data.illinois.gov/api/views/nw3t-wtmy) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/nw3t-wtmy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/nw3t-wtmy/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | nw3t-wtmy |
| Name | IDPH Infant Mortality, State Total, by Race, 1980-2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | infant, mortality |
| Created | 2012-01-18T19:04:05Z |
| Publication Date | 2012-01-23T21:44:48Z |

## Description

Rates shown are per 1,000 live births * Corrected Rate

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | year             | Year             | text      | text        |
| Yes      | numeric metric | white            | White            | number    | number      |
| Yes      | numeric metric | african_american | African-American | number    | number      |
| Yes      | numeric metric | overall          | Overall          | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nw3t-wtmy d:2008-01-01T00:00:00.000Z m:white=5.8 m:overall=7.2 m:african_american=13.9

series e:nw3t-wtmy d:2007-01-01T00:00:00.000Z m:white=5.3 m:overall=6.6 m:african_american=13.5

series e:nw3t-wtmy d:2006-01-01T00:00:00.000Z m:white=6.1 m:overall=7.4 m:african_american=14.4
```

## Meta Commands

```ls
metric m:white p:float l:White t:dataTypeName=number

metric m:african_american p:float l:African-American t:dataTypeName=number

metric m:overall p:float l:Overall t:dataTypeName=number

entity e:nw3t-wtmy l:"IDPH Infant Mortality, State Total, by Race, 1980-2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/nw3t-wtmy

property e:nw3t-wtmy t:meta.view v:id=nw3t-wtmy v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Infant Mortality, State Total, by Race, 1980-2008" v:attribution="Illinois Center for Health Statistics"

property e:nw3t-wtmy t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:nw3t-wtmy t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| year  | white | african_american | overall | 
| ===== | ===== | ================ | ======= | 
| 2008  | 5.8   | 13.9             | 7.2     | 
| 2007  | 5.3   | 13.5             | 6.6     | 
| 2006  | 6.1   | 14.4             | 7.4     | 
| 2005  | 5.7   | 15.4             | 7.2     | 
| 2004  | 5.9   | 14.8             | 7.3     | 
| 2003  | 6.1   | 15.6             | 7.6     | 
| 2002* | 5.5   | 15.7             | 7.2     | 
| 2001  | 5.9   | 14.9             | 7.5     | 
| 2000  | 6.5   | 16.3             | 8.3     | 
| 1999  | 6.2   | 17.4             | 8.3     | 
```