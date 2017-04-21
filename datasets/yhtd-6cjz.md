# Crime & Safety 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/crime-safety-2010-4552d) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/yhtd-6cjz) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/yhtd-6cjz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/yhtd-6cjz/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | yhtd-6cjz |
| Name | Crime & Safety 2010 |
| Attribution | Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore |
| Category | Neighborhoods |
| Tags | crime, census |
| Created | 2013-02-26T13:25:21Z |
| Publication Date | 2014-04-04T00:06:03Z |

## Description

All crime data for Vital Signs indicators are provided by the Baltimore City Police Department. BNIA-JFI normalizes this data by population to establish crime rates. Normalizing data allows for the rates to reflect the concentration of the crime relative to the population in the area and allows for comparison between areas of different populations.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010  | text      | text        |
| Yes      | numeric metric | domvio10   | domvio10 | number    | number      |
| Yes      | numeric metric | crime10    | crime10  | number    | number      |
| Yes      | numeric metric | viol10     | viol10   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yhtd-6cjz d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:crime10=40.57 m:domvio10=59.38 m:viol10=12.64

series e:yhtd-6cjz d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:crime10=33.59 m:domvio10=47.86 m:viol10=8.4

series e:yhtd-6cjz d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:crime10=50.3 m:domvio10=51.1 m:viol10=13.26
```

## Meta Commands

```ls
metric m:domvio10 p:float l:domvio10 t:dataTypeName=number

metric m:crime10 p:float l:crime10 t:dataTypeName=number

metric m:viol10 p:float l:viol10 t:dataTypeName=number

entity e:yhtd-6cjz l:"Crime & Safety 2010" t:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore" t:url=https://data.baltimorecity.gov/api/views/yhtd-6cjz

property e:yhtd-6cjz t:meta.view v:id=yhtd-6cjz v:category=Neighborhoods v:attributionLink=http://www.bniajfi.org/ v:averageRating=0 v:name="Crime & Safety 2010" v:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore"

property e:yhtd-6cjz t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:yhtd-6cjz t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:yhtd-6cjz t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | domvio10 | crime10            | viol10 | 
| ================================= | ======== | ================== | ====== | 
| Allendale/Irvington/S. Hilton     | 59.38    | 40.57              | 12.64  | 
| Beechfield/Ten Hills/West Hills   | 47.86    | 33.590000000000003 | 8.4    | 
| Belair-Edison                     | 51.1     | 50.3               | 13.26  | 
| Brooklyn/Curtis Bay/Hawkins Point | 68.03    | 81.650000000000006 | 25.35  | 
| Canton                            | 34.32    | 60.99              | 8.27   | 
| Cedonia/Frankford                 | 60.24    | 43.72              | 11.97  | 
| Cherry Hill                       | 62.91    | 59.99              | 22.56  | 
| Chinquapin Park/Belvedere         | 39.71    | 43.58              | 12.64  | 
| Claremont/Armistead               | 60.38    | 52.61              | 13.24  | 
| Clifton-Berea                     | 49.73    | 57.93              | 23.29  | 
```