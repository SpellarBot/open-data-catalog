# Housing and Community Development Vital Signs 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-and-community-development-vital-signs-2010-1cb56) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/utne-q9c6) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/utne-q9c6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/utne-q9c6/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | utne-q9c6 |
| Name | Housing and Community Development Vital Signs 2010 |
| Attribution | Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore |
| Category | Neighborhoods |
| Tags | community, housing, market, development |
| Created | 2013-01-22T19:37:18Z |
| Publication Date | 2014-04-04T00:04:05Z |

## Description

BNIA-JFI uses Community Statistical Areas (CSAs) boundaries for tracking Vital Signs data so that progress can be measured over time. CSAs are based on Census tracts which remain consistent from year to year. BNIA-JFI relates CSAs to neighborhoods as defined by the Baltimore City Department of Planning.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010    | text      | text        |
| Yes      | numeric metric | resrehab10 | resrehab10 | number    | number      |
| Yes      | numeric metric | vacant10   | vacant10   | number    | number      |
| Yes      | numeric metric | vio10      | vio10      | number    | number      |
| Yes      | numeric metric | salepr10   | salepr10   | number    | number      |
| Yes      | numeric metric | salesnum10 | salesnum10 | number    | number      |
| Yes      | numeric metric | salesdom10 | salesdom10 | number    | number      |
| Yes      | numeric metric | ownerocc10 | ownerocc10 | number    | number      |
| Yes      | numeric metric | fore10     | fore10     | number    | number      |
| Yes      | numeric metric | totalres10 | totalres10 | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:utne-q9c6 d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:resrehab10=1.29 m:ownerocc10=66 m:totalres10=5568 m:vacant10=4.31 m:salepr10=42500 m:salesdom10=85 m:vio10=4.97 m:salesnum10=118 m:fore10=2.59

series e:utne-q9c6 d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:resrehab10=1.94 m:ownerocc10=82.7 m:totalres10=3557 m:vacant10=0.28 m:salepr10=142250 m:salesdom10=102 m:vio10=2 m:salesnum10=72 m:fore10=2.11

series e:utne-q9c6 d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:resrehab10=1.35 m:ownerocc10=67.2 m:totalres10=6295 m:vacant10=1.45 m:salepr10=56000 m:salesdom10=94 m:vio10=2.22 m:salesnum10=153 m:fore10=3.15
```

## Meta Commands

```ls
metric m:resrehab10 p:float l:resrehab10 t:dataTypeName=number

metric m:vacant10 p:float l:vacant10 t:dataTypeName=number

metric m:vio10 p:float l:vio10 t:dataTypeName=number

metric m:salepr10 p:integer l:salepr10 t:dataTypeName=number

metric m:salesnum10 p:integer l:salesnum10 t:dataTypeName=number

metric m:salesdom10 p:float l:salesdom10 t:dataTypeName=number

metric m:ownerocc10 p:float l:ownerocc10 t:dataTypeName=number

metric m:fore10 p:float l:fore10 t:dataTypeName=number

metric m:totalres10 p:integer l:totalres10 t:dataTypeName=number

entity e:utne-q9c6 l:"Housing and Community Development Vital Signs 2010" t:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore" t:url=https://data.baltimorecity.gov/api/views/utne-q9c6

property e:utne-q9c6 t:meta.view v:id=utne-q9c6 v:category=Neighborhoods v:attributionLink=http://www.bniajfi.org/ v:averageRating=0 v:name="Housing and Community Development Vital Signs 2010" v:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore"

property e:utne-q9c6 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:utne-q9c6 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:utne-q9c6 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | resrehab10         | vacant10            | vio10              | salepr10 | salesnum10 | salesdom10 | ownerocc10         | fore10             | totalres10 | 
| ================================= | ================== | =================== | ================== | ======== | ========== | ========== | ================== | ================== | ========== | 
| Allendale/Irvington/S. Hilton     | 1.29               | 4.3099999999999996  | 4.97               | 42500    | 118        | 85         | 66                 | 2.59               | 5568       | 
| Beechfield/Ten Hills/West Hills   | 1.94               | 0.28000000000000003 | 2                  | 142250   | 72         | 102        | 82.7               | 2.11               | 3557       | 
| Belair-Edison                     | 1.35               | 1.45                | 2.2200000000000002 | 56000    | 153        | 94         | 67.2               | 3.15               | 6295       | 
| Brooklyn/Curtis Bay/Hawkins Point | 1.26               | 3.74                | 3.74               | 58005    | 104        | 108        | 50.4               | 2.8                | 4283       | 
| Canton                            | 3.99               | 0.92                | 0.6                | 251000   | 230        | 82         | 69.900000000000006 | 1.79               | 4013       | 
| Cedonia/Frankford                 | 1.91               | 0.67                | 1.6                | 103225   | 195        | 98.5       | 79.2               | 2.88               | 6294       | 
| Cherry Hill                       | 0.4                | 3.44                | 2.94               | 69000    | 9          | 141        | 54.7               | 2.02               | 988        | 
| Chinquapin Park/Belvedere         | 2.2599999999999998 | 0.33                | 2.34               | 117450   | 74         | 103        | 74                 | 2.04               | 2694       | 
| Claremont/Armistead               | 1.52               | 0                   | 3.31               | 139000   | 16         | 135        | 76.599999999999994 | 4.6900000000000004 | 725        | 
| Clifton-Berea                     | 1.71               | 24.5                | 11.33              | 13250    | 87         | 71         | 35.799999999999997 | 1.65               | 4783       | 
```