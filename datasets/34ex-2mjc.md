# Children and Family Health & Well-Being - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/children-and-family-health-well-being-2010-6fb2d) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/34ex-2mjc) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/34ex-2mjc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/34ex-2mjc/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 34ex-2mjc |
| Name | Children and Family Health & Well-Being - 2010 |
| Attribution | Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore |
| Category | Neighborhoods |
| Tags | health, census, childern, family |
| Created | 2013-02-26T13:12:29Z |
| Publication Date | 2014-04-03T23:59:46Z |

## Description

Baltimore City continues to make improving the health and lives of its residents a priority. In 2011, the City released the update of Community Health Profilesfor all CSAs as well as Healthy Baltimore 2015 Safe Homes and Families, acomprehensive health policy agenda and measures for tracking progress. In order to describe the health and well being of City residents, BNIA-JFI currently tracks thirteen adult, juvenile, and infant health indicators for Baltimore City and its neighborhoods. The data is provided by the Maryland Department of Health andMental Hygiene, Maryland Department of the Environment, Baltimore Substance Abuse Systems (BSAS), the Baltimore City Health Department, and the United States Bureau of the Census. Where possible, data is presented at the CSA and City level. For several indicators, data is only available at the zip code level.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010    | text      | text        |
| Yes      | numeric metric | termbir10  | termbir10  | number    | number      |
| Yes      | numeric metric | birthwt10  | birthwt10  | number    | number      |
| Yes      | numeric metric | prenatal10 | prenatal10 | number    | number      |
| Yes      | numeric metric | teenbir10  | teenbir10  | number    | number      |
| Yes      | numeric metric | leadtest10 | leadtest10 | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:34ex-2mjc d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:birthwt10=87.45 m:leadtest10=386 m:prenatal10=51.95 m:teenbir10=55.05 m:termbir10=85.28

series e:34ex-2mjc d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:birthwt10=91.67 m:leadtest10=0 m:prenatal10=64.29 m:teenbir10=42.78 m:termbir10=87.5

series e:34ex-2mjc d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:birthwt10=87.7 m:leadtest10=200 m:prenatal10=63.93 m:teenbir10=67.57 m:termbir10=84.02
```

## Meta Commands

```ls
metric m:termbir10 p:float l:termbir10 t:dataTypeName=number

metric m:birthwt10 p:float l:birthwt10 t:dataTypeName=number

metric m:prenatal10 p:float l:prenatal10 t:dataTypeName=number

metric m:teenbir10 p:float l:teenbir10 t:dataTypeName=number

metric m:leadtest10 p:integer l:leadtest10 t:dataTypeName=number

entity e:34ex-2mjc l:"Children and Family Health & Well-Being - 2010" t:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore" t:url=https://data.baltimorecity.gov/api/views/34ex-2mjc

property e:34ex-2mjc t:meta.view v:id=34ex-2mjc v:category=Neighborhoods v:attributionLink=http://www.bniajfi.org/ v:averageRating=0 v:name="Children and Family Health & Well-Being - 2010" v:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore"

property e:34ex-2mjc t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:34ex-2mjc t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:34ex-2mjc t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | termbir10 | birthwt10 | prenatal10         | teenbir10          | leadtest10 | 
| ================================= | ========= | ========= | ================== | ================== | ========== | 
| Allendale/Irvington/S. Hilton     | 85.28     | 87.45     | 51.95              | 55.05              | 386        | 
| Beechfield/Ten Hills/West Hills   | 87.5      | 91.67     | 64.290000000000006 | 42.78              | 0          | 
| Belair-Edison                     | 84.02     | 87.7      | 63.93              | 67.569999999999993 | 200        | 
| Brooklyn/Curtis Bay/Hawkins Point | 83.15     | 89.89     | 50.94              | 111.11             | 0          | 
| Canton                            | 94.59     | 94.59     | 73.87              | 46.51              | 96         | 
| Cedonia/Frankford                 | 83.83     | 84.37     | 56.6               | 48.92              | 240        | 
| Cherry Hill                       | 80.92     | 88.82     | 57.24              | 57.64              | 198        | 
| Chinquapin Park/Belvedere         | 87.04     | 92.59     | 63.89              | 50.63              | 146        | 
| Claremont/Armistead               | 83.02     | 83.02     | 47.17              | 48.87              | 240        | 
| Clifton-Berea                     | 82.84     | 83.58     | 52.24              | 71.98              | 0          | 
```