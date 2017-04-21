# Illinois Population, 2000-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-population-2000-2009-b6d2b) |
| Metadata | [Link](https://data.illinois.gov/api/views/qcyd-8efc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qcyd-8efc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qcyd-8efc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qcyd-8efc |
| Name | Illinois Population, 2000-2009 |
| Attribution | Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics |
| Category | Health |
| Tags | population, illinois |
| Created | 2014-08-11T20:56:22Z |
| Publication Date | 2014-08-11T20:58:24Z |

## Description

Data provided by the IL Center for Health Statistics.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | text      | text        |
| Yes      | numeric metric | 2000       | 2000   | number    | number      |
| Yes      | numeric metric | 2001       | 2001   | number    | number      |
| Yes      | numeric metric | 2002       | 2002   | number    | number      |
| Yes      | numeric metric | 2003       | 2003   | number    | number      |
| Yes      | numeric metric | 2004       | 2004   | number    | number      |
| Yes      | numeric metric | 2005       | 2005   | number    | number      |
| Yes      | numeric metric | 2006       | 2006   | number    | number      |
| Yes      | numeric metric | 2007       | 2007   | number    | number      |
| Yes      | numeric metric | 2008       | 2008   | number    | number      |
| Yes      | numeric metric | 2009       | 2009   | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qcyd-8efc d:2000-01-01T00:00:00.000Z t:county=Illinois m:2008=12901550 m:2009=12910410 m:2006=12831950 m:2007=12852530 m:2004=12713700 m:2005=12763500 m:2002=12601000 m:2003=12653800 m:2001=12482000 m:2000=12436000

series e:qcyd-8efc d:2000-01-01T00:00:00.000Z t:county=Adams m:2008=66250 m:2009=66300 m:2006=66960 m:2007=66360 m:2004=66800 m:2005=66790 m:2002=67700 m:2003=67100 m:2001=67800 m:2000=68200

series e:qcyd-8efc d:2000-01-01T00:00:00.000Z t:county=Alexander m:2008=8920 m:2009=8500 m:2006=9120 m:2007=8880 m:2004=9200 m:2005=9330 m:2002=9500 m:2003=9300 m:2001=9500 m:2000=9600
```

## Meta Commands

```ls
metric m:2000 p:integer l:2000 t:dataTypeName=number

metric m:2001 p:integer l:2001 t:dataTypeName=number

metric m:2002 p:integer l:2002 t:dataTypeName=number

metric m:2003 p:integer l:2003 t:dataTypeName=number

metric m:2004 p:integer l:2004 t:dataTypeName=number

metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

entity e:qcyd-8efc l:"Illinois Population, 2000-2009" t:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/qcyd-8efc

property e:qcyd-8efc t:meta.view v:id=qcyd-8efc v:category=Health v:averageRating=0 v:name="Illinois Population, 2000-2009" v:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics"

property e:qcyd-8efc t:meta.view.license v:name="Public Domain"

property e:qcyd-8efc t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:qcyd-8efc t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 2000     | 2001     | 2002     | 2003     | 2004     | 2005     | 2006     | 2007     | 2008     | 2009     | 
| ========= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| Illinois  | 12436000 | 12482000 | 12601000 | 12653800 | 12713700 | 12763500 | 12831950 | 12852530 | 12901550 | 12910410 | 
| Adams     | 68200    | 67800    | 67700    | 67100    | 66800    | 66790    | 66960    | 66360    | 66250    | 66300    | 
| Alexander | 9600     | 9500     | 9500     | 9300     | 9200     | 9330     | 9120     | 8880     | 8920     | 8500     | 
| Bond      | 17600    | 17600    | 17900    | 17900    | 18000    | 17860    | 17800    | 17920    | 17780    | 17580    | 
| Boone     | 42100    | 43600    | 45300    | 47100    | 48900    | 49320    | 51440    | 53050    | 53630    | 53480    | 
| Brown     | 6900     | 6900     | 6800     | 6800     | 6800     | 6730     | 6740     | 6620     | 6630     | 6690     | 
| Bureau    | 35500    | 35300    | 35400    | 35400    | 35200    | 35440    | 35540    | 35260    | 35130    | 34870    | 
| Calhoun   | 5100     | 5100     | 5100     | 5200     | 5200     | 5270     | 5270     | 5220     | 5140     | 5100     | 
| Carroll   | 16600    | 16400    | 16400    | 16300    | 16200    | 16030    | 15970    | 15760    | 15640    | 15560    | 
| Cass      | 13700    | 13600    | 13600    | 13800    | 13800    | 13770    | 13770    | 13800    | 13780    | 13510    | 
```