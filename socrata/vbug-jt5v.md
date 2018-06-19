# Number of Deaths for Selected Causes among Maryland Residents, 1992-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-deaths-for-selected-causes-among-maryland-residents-1992-2011-034b2) |
| Metadata | [Link](https://data.maryland.gov/api/views/vbug-jt5v) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/vbug-jt5v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/vbug-jt5v/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | vbug-jt5v |
| Name | Number of Deaths for Selected Causes among Maryland Residents, 1992-2011 |
| Attribution | Vital Statistics Administration |
| Category | Health and Human Services |
| Tags | death, vital statistics |
| Created | 2012-11-19T21:49:23Z |
| Publication Date | 2012-11-19T21:50:45Z |

## Description

Number of deaths by underlying cause for selected causes of death among Maryland residents.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | selected_causes_of_death | Selected Causes of Death | text      | text        |
| No       |                | _1                       | 1992                     | number    | number      |
| No       |                | _2                       | 1993                     | number    | number      |
| No       |                | _3                       | 1994                     | number    | number      |
| No       |                | _4                       | 1995                     | number    | number      |
| No       |                | _5                       | 1996                     | number    | number      |
| No       |                | _6                       | 1997                     | number    | number      |
| No       |                | _7                       | 1998                     | number    | number      |
| No       |                | _8                       | 1999                     | number    | number      |
| No       |                | _9                       | 2000                     | number    | number      |
| Yes      | numeric metric | _10                      | 2001                     | number    | number      |
| Yes      | numeric metric | _11                      | 2002                     | number    | number      |
| Yes      | numeric metric | _12                      | 2003                     | number    | number      |
| Yes      | numeric metric | _13                      | 2004                     | number    | number      |
| Yes      | numeric metric | _14                      | 2005                     | number    | number      |
| Yes      | numeric metric | _15                      | 2006                     | number    | number      |
| Yes      | numeric metric | _16                      | 2007                     | number    | number      |
| Yes      | numeric metric | _17                      | 2008                     | number    | number      |
| Yes      | numeric metric | _18                      | 2009                     | number    | number      |
| Yes      | numeric metric | _19                      | 2010                     | number    | number      |
| Yes      | numeric metric | _20                      | 2011                     | number    | number      |
```

## Time Field

```ls
Value = 1992
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7,_8,_9
```

## Data Commands

```ls
series e:vbug-jt5v d:1992-01-01T00:00:00.000Z t:selected_causes_of_death="All Causes" m:_20=43650 m:_11=43917 m:_10=43673 m:_18=43763 m:_19=43255 m:_16=43597 m:_17=43849 m:_14=43778 m:_15=43491 m:_12=44364 m:_13=43157

series e:vbug-jt5v d:1992-01-01T00:00:00.000Z t:selected_causes_of_death="Diseases of the Heart" m:_20=10567 m:_11=11946 m:_10=12217 m:_18=11143 m:_19=10898 m:_16=11346 m:_17=11217 m:_14=11564 m:_15=11191 m:_12=12071 m:_13=11271

series e:vbug-jt5v d:1992-01-01T00:00:00.000Z t:selected_causes_of_death="Malignant Neoplasms" m:_20=10223 m:_11=10387 m:_10=10293 m:_18=10376 m:_19=10249 m:_16=10142 m:_17=10345 m:_14=10349 m:_15=10336 m:_12=10251 m:_13=10146
```

## Meta Commands

```ls
metric m:_10 p:integer l:2001 t:dataTypeName=number

metric m:_11 p:integer l:2002 t:dataTypeName=number

metric m:_12 p:integer l:2003 t:dataTypeName=number

metric m:_13 p:integer l:2004 t:dataTypeName=number

metric m:_14 p:integer l:2005 t:dataTypeName=number

metric m:_15 p:integer l:2006 t:dataTypeName=number

metric m:_16 p:integer l:2007 t:dataTypeName=number

metric m:_17 p:integer l:2008 t:dataTypeName=number

metric m:_18 p:integer l:2009 t:dataTypeName=number

metric m:_19 p:integer l:2010 t:dataTypeName=number

metric m:_20 p:integer l:2011 t:dataTypeName=number

entity e:vbug-jt5v l:"Number of Deaths for Selected Causes among Maryland Residents, 1992-2011" t:attribution="Vital Statistics Administration" t:url=https://data.maryland.gov/api/views/vbug-jt5v

property e:vbug-jt5v t:meta.view v:id=vbug-jt5v v:category="Health and Human Services" v:attributionLink=http://dhmh.maryland.gov/vsa/SitePages/reports.aspx v:averageRating=0 v:name="Number of Deaths for Selected Causes among Maryland Residents, 1992-2011" v:attribution="Vital Statistics Administration"

property e:vbug-jt5v t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:vbug-jt5v t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| selected_causes_of_death           | _1    | _2    | _3    | _4    | _5    | _6    | _7    | _8    | _9    | _10   | _11   | _12   | _13   | _14   | _15   | _16   | _17   | _18   | _19   | _20   | 
| ================================== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | 
| All Causes                         | 38833 | 40332 | 40939 | 41681 | 41903 | 41681 | 41970 | 42908 | 43602 | 43673 | 43917 | 44364 | 43157 | 43778 | 43491 | 43597 | 43849 | 43763 | 43255 | 43650 | 
| Diseases of the Heart              | 11844 | 12137 | 11990 | 11856 | 11913 | 11949 | 11869 | 12014 | 12285 | 12217 | 11946 | 12071 | 11271 | 11564 | 11191 | 11346 | 11217 | 11143 | 10898 | 10567 | 
| Malignant Neoplasms                | 9943  | 9897  | 10060 | 10158 | 10146 | 10107 | 10187 | 10096 | 10248 | 10293 | 10387 | 10251 | 10146 | 10349 | 10336 | 10142 | 10345 | 10376 | 10249 | 10223 | 
| Cerebrovascular Diseases           | 2100  | 2260  | 2515  | 2624  | 2650  | 2602  | 2631  | 2860  | 2933  | 2856  | 2803  | 2725  | 2712  | 2465  | 2358  | 2238  | 2250  | 2281  | 2262  | 2312  | 
| Chronic Lower Respiratory Diseases | 1451  | 1542  | 1663  | 1597  | 1760  | 1814  | 1711  | 1941  | 1922  | 1894  | 1939  | 1973  | 1902  | 1889  | 1827  | 1898  | 1955  | 2049  | 2035  | 2064  | 
| Diabetes Mellitus                  | 1102  | 1258  | 1322  | 1349  | 1413  | 1385  | 1433  | 1408  | 1512  | 1442  | 1509  | 1442  | 1410  | 1385  | 1230  | 1297  | 1237  | 1198  | 1186  | 1272  | 
| Accidents                          | 1262  | 1371  | 1340  | 1373  | 1411  | 1354  | 1343  | 1240  | 1114  | 1308  | 1320  | 1431  | 1400  | 1363  | 1424  | 1470  | 1460  | 1392  | 1440  | 1542  | 
| Motor Vehicle Accidents            | 629   | 667   | 651   | 676   | 649   | 639   | 629   | 547   | 574   | 657   | 696   | 701   | 667   | 635   | 719   | 677   | 643   | 586   | 506   | 512   | 
| Influenza and Pneumonia            | 1151  | 1233  | 1186  | 1354  | 1447  | 1457  | 1640  | 1150  | 1113  | 948   | 1138  | 1184  | 1123  | 1215  | 1091  | 1006  | 1017  | 978   | 922   | 1032  | 
| Septicemia                         | 588   | 588   | 600   | 628   | 628   | 668   | 741   | 966   | 956   | 981   | 1013  | 1091  | 1061  | 1080  | 964   | 921   | 998   | 1052  | 883   | 800   | 
```