# Sanitation 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sanitation-2010-4e255) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/wh9c-xr5p) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/wh9c-xr5p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/wh9c-xr5p/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | wh9c-xr5p |
| Name | Sanitation 2010 |
| Attribution | Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore |
| Category | Neighborhoods |
| Tags | sanitation, census |
| Created | 2013-02-26T13:40:53Z |
| Publication Date | 2014-04-04T00:05:35Z |

## Description

All sanitation data for Vital Signs indicators are provided by the Baltimore CitiStat. BNIA-JFI normalizes this data by population to establish rates. Normalizing data allows for the rates to reflect the concentration of the issue relative to the population in the area and allows for comparison between areas of differentpopulations.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | community_statistical_area | Community Statistical Area | text      | text        |
| Yes      | numeric metric | dirtyst10                  | dirtyst10                  | number    | number      |
| Yes      | numeric metric | drains10                   | drains10                   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wh9c-xr5p d:2010-01-01T00:00:00.000Z t:community_statistical_area="Allendale/Irvington/South Hilton" m:drains10=4.19 m:dirtyst10=41.68

series e:wh9c-xr5p d:2010-01-01T00:00:00.000Z t:community_statistical_area="Beechfield/Ten Hills/West Hills" m:drains10=3.42 m:dirtyst10=10.52

series e:wh9c-xr5p d:2010-01-01T00:00:00.000Z t:community_statistical_area=Belair-Edison m:drains10=4.08 m:dirtyst10=90.2
```

## Meta Commands

```ls
metric m:dirtyst10 p:float l:dirtyst10 t:dataTypeName=number

metric m:drains10 p:float l:drains10 t:dataTypeName=number

entity e:wh9c-xr5p l:"Sanitation 2010" t:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore" t:url=https://data.baltimorecity.gov/api/views/wh9c-xr5p

property e:wh9c-xr5p t:meta.view v:id=wh9c-xr5p v:category=Neighborhoods v:attributionLink=http://www.bniajfi.org/ v:averageRating=0 v:name="Sanitation 2010" v:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore"

property e:wh9c-xr5p t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:wh9c-xr5p t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:wh9c-xr5p t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| community_statistical_area        | dirtyst10          | drains10           | 
| ================================= | ================== | ================== | 
| Allendale/Irvington/South Hilton  | 41.68              | 4.1900000000000004 | 
| Beechfield/Ten Hills/West Hills   | 10.52              | 3.42               | 
| Belair-Edison                     | 90.2               | 4.08               | 
| Brooklyn/Curtis Bay/Hawkins Point | 91.48              | 4.21               | 
| Canton                            | 32.840000000000003 | 6.3                | 
| Cedonia/Frankford                 | 22.5               | 2.5                | 
| Cherry Hill                       | 11.7               | 1.22               | 
| Chinquapin Park/Belvedere         | 26.3               | 5.03               | 
| Claremont/Armistead               | 8.14               | 1.58               | 
| Clifton-Berea                     | 167.21             | 10.94              | 
```