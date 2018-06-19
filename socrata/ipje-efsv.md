# Neighborhood Action & Sense of Community 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/neighborhood-action-sense-of-community-2010-0dfc6) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/ipje-efsv) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/ipje-efsv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/ipje-efsv/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | ipje-efsv |
| Name | Neighborhood Action & Sense of Community 2010 |
| Attribution | Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore |
| Category | Neighborhoods |
| Tags | community, neighborhoods, census |
| Created | 2013-02-26T14:05:20Z |
| Publication Date | 2014-04-04T00:02:00Z |

## Description

Baltimore City has a rich history of community organizing and civic engagement. On any given night, somewhere in the City a neighborhood group is meeting, discussing community concerns, planning for their collective future and advocating for action. BNIA-JFI currently tracks nine neighborhood and community indicators to measure the extent to which the City??_??s neighborhoods are active, organized, and empowered. These include: the number of neighborhood associations and block groups; the number of Community Development Corporations (CDCs); the number of umbrella organizations; the number of park stewardship groups; the number ofcommunity gardens; Healthy Neighborhood Initiative locations; the number of historic properties; the percentage of the population registered to vote; and the percentage of persons voting.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010    | text      | text        |
| Yes      | numeric metric | assoc10    | assoc10    | number    | number      |
| Yes      | numeric metric | cdcs10     | cdcs10     | number    | number      |
| Yes      | numeric metric | umbrella10 | umbrella10 | number    | number      |
| Yes      | numeric metric | parkgrps10 | parkgrps10 | number    | number      |
| Yes      | numeric metric | gardens10  | gardens10  | number    | number      |
| Yes      | numeric metric | chap10     | chap10     | number    | number      |
| Yes      | numeric metric | regvote10  | regvote10  | number    | number      |
| Yes      | numeric metric | voted10    | voted10    | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ipje-efsv d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:assoc10=15 m:chap10=0 m:cdcs10=0 m:parkgrps10=13 m:voted10=45.3 m:gardens10=6 m:umbrella10=1 m:regvote10=83.37

series e:ipje-efsv d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:assoc10=6 m:chap10=494 m:cdcs10=1 m:parkgrps10=7 m:voted10=52.6 m:gardens10=7 m:umbrella10=0 m:regvote10=79.73

series e:ipje-efsv d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:assoc10=4 m:chap10=0 m:cdcs10=0 m:parkgrps10=9 m:voted10=46.6 m:gardens10=6 m:umbrella10=0 m:regvote10=81.71
```

## Meta Commands

```ls
metric m:assoc10 p:integer l:assoc10 t:dataTypeName=number

metric m:cdcs10 p:integer l:cdcs10 t:dataTypeName=number

metric m:umbrella10 p:integer l:umbrella10 t:dataTypeName=number

metric m:parkgrps10 p:integer l:parkgrps10 t:dataTypeName=number

metric m:gardens10 p:integer l:gardens10 t:dataTypeName=number

metric m:chap10 p:integer l:chap10 t:dataTypeName=number

metric m:regvote10 p:float l:regvote10 t:dataTypeName=number

metric m:voted10 p:float l:voted10 t:dataTypeName=number

entity e:ipje-efsv l:"Neighborhood Action & Sense of Community 2010" t:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore" t:url=https://data.baltimorecity.gov/api/views/ipje-efsv

property e:ipje-efsv t:meta.view v:id=ipje-efsv v:category=Neighborhoods v:attributionLink=http://www.bniajfi.org v:averageRating=0 v:name="Neighborhood Action & Sense of Community 2010" v:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore"

property e:ipje-efsv t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ipje-efsv t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:ipje-efsv t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | assoc10 | cdcs10 | umbrella10 | parkgrps10 | gardens10 | chap10 | regvote10          | voted10            | 
| ================================= | ======= | ====== | ========== | ========== | ========= | ====== | ================== | ================== | 
| Allendale/Irvington/S. Hilton     | 15      | 0      | 1          | 13         | 6         | 0      | 83.37              | 45.3               | 
| Beechfield/Ten Hills/West Hills   | 6       | 1      | 0          | 7          | 7         | 494    | 79.73              | 52.6               | 
| Belair-Edison                     | 4       | 0      | 0          | 9          | 6         | 0      | 81.709999999999994 | 46.6               | 
| Brooklyn/Curtis Bay/Hawkins Point | 5       | 0      | 1          | 5          | 6         | 0      | 53.57              | 30.1               | 
| Canton                            | 9       | 0      | 0          | 13         | 2         | 0      | 79.5               | 43.2               | 
| Cedonia/Frankford                 | 4       | 0      | 0          | 7          | 4         | 0      | 73.89              | 46.6               | 
| Cherry Hill                       | 7       | 2      | 1          | 1          | 2         | 0      | 82.48              | 34.9               | 
| Chinquapin Park/Belvedere         | 11      | 1      | 0          | 6          | 3         | 0      | 83.24              | 51.2               | 
| Claremont/Armistead               | 3       | 0      | 0          | 1          | 2         | 0      | 60.72              | 37.799999999999997 | 
| Clifton-Berea                     | 20      | 1      | 0          | 12         | 7         | 77     | 91.46              | 40.299999999999997 | 
```