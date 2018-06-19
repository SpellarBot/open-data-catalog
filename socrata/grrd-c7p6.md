# Education and Youth 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/education-and-youth-2010-d09a2) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/grrd-c7p6) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/grrd-c7p6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/grrd-c7p6/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | grrd-c7p6 |
| Name | Education and Youth 2010 |
| Attribution | Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore |
| Category | Neighborhoods |
| Tags | education, youth, census |
| Created | 2013-02-26T13:51:39Z |
| Publication Date | 2014-04-04T00:03:12Z |

## Description

BNIA-JFI tracks twenty seven indicators for elementary, middle, and high school students in an effort to measure the educational performance and youth engagement in Baltimore City. These indicators are grouped into the following seven categories: student enrollment and demographics; dropout rate and high school completion; student attendance, suspensions and expulsions; elementary and middle school student achievement; high school performance; youth labor force participation; and youth civic engagement. The source of data for the Education and Youth section is provided by the Baltimore City Public School System, the American Community Survey and the Baltimore City Board of Elections. The data provided by the Baltimore City Public Schools includes student address, which allows BNIA-JFI to present data on educational performance by the neighborhood in which the student lives, not by the school attended. This allows BNIA-JFI to examine the relationship between community conditions and educational performance. Education and Youth indicators may not be directly comparable to data provided by either the Baltimore City Public School System or the Maryland Department ofEducation due to several reasons including differences in methodology used to create indicators, excluding students who cannot be matched between data filesprovided by BCPSS, and excluding students whose home address cannot be geocoded. In the 2009-2010 school year, 3.4% of the student addresses could not be matched or geocoded. This means that these students were not included in our analysis and not included in calculations for the City as a whole and therefore directcomparisons to data and results available through the Baltimore City Public Schools and the Maryland Report Card cannot be made.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010    | text      | text        |
| Yes      | numeric metric | eenr0910   | eenr0910   | number    | number      |
| Yes      | numeric metric | menr0910   | menr0910   | number    | number      |
| Yes      | numeric metric | henr0910   | henr0910   | number    | number      |
| Yes      | numeric metric | caelem0910 | caelem0910 | number    | number      |
| Yes      | numeric metric | camid0910  | camid0910  | number    | number      |
| Yes      | numeric metric | cahigh0910 | cahigh0910 | number    | number      |
| Yes      | numeric metric | susp0910   | susp0910   | number    | number      |
| Yes      | numeric metric | drop0910   | drop0910   | number    | number      |
| Yes      | numeric metric | compl0910  | compl0910  | number    | number      |
| Yes      | numeric metric | farms0910  | farms0910  | number    | number      |
| Yes      | numeric metric | aastud0910 | aastud0910 | number    | number      |
| Yes      | numeric metric | wstud0910  | wstud0910  | number    | number      |
| Yes      | numeric metric | hstud0910  | hstud0910  | number    | number      |
| Yes      | numeric metric | yempl10    | yempl10    | number    | number      |
| Yes      | numeric metric | yvotereg10 | yvotereg10 | number    | number      |
| Yes      | numeric metric | yvoted10   | yvoted10   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:grrd-c7p6 d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:aastud0910=94.92 m:cahigh0910=41.17 m:menr0910=747 m:wstud0910=2.9 m:caelem0910=14.67 m:yvoted10=20.02 m:susp0910=9.47 m:yvotereg10=78.89 m:drop0910=3.76 m:yempl10=82.11 m:camid0910=28.78 m:hstud0910=0.76 m:farms0910=86.05 m:henr0910=1064 m:compl0910=80.35 m:eenr0910=1118

series e:grrd-c7p6 d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:aastud0910=95.4 m:cahigh0910=29.94 m:menr0910=349 m:wstud0910=2.14 m:caelem0910=6.45 m:yvoted10=24.72 m:susp0910=8.11 m:yvotereg10=83.55 m:drop0910=1.96 m:yempl10=76.67 m:camid0910=11.75 m:hstud0910=0.65 m:farms0910=76.26 m:henr0910=511 m:compl0910=85.87 m:eenr0910=574

series e:grrd-c7p6 d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:aastud0910=96.92 m:cahigh0910=41.1 m:menr0910=831 m:wstud0910=1.25 m:caelem0910=14.03 m:yvoted10=19.83 m:susp0910=9.89 m:yvotereg10=80.85 m:drop0910=4.02 m:yempl10=79.62 m:camid0910=12.39 m:hstud0910=0.29 m:farms0910=85.54 m:henr0910=1219 m:compl0910=82.86 m:eenr0910=1162
```

## Meta Commands

```ls
metric m:eenr0910 p:integer l:eenr0910 t:dataTypeName=number

metric m:menr0910 p:integer l:menr0910 t:dataTypeName=number

metric m:henr0910 p:integer l:henr0910 t:dataTypeName=number

metric m:caelem0910 p:float l:caelem0910 t:dataTypeName=number

metric m:camid0910 p:float l:camid0910 t:dataTypeName=number

metric m:cahigh0910 p:float l:cahigh0910 t:dataTypeName=number

metric m:susp0910 p:float l:susp0910 t:dataTypeName=number

metric m:drop0910 p:float l:drop0910 t:dataTypeName=number

metric m:compl0910 p:double l:compl0910 t:dataTypeName=number

metric m:farms0910 p:float l:farms0910 t:dataTypeName=number

metric m:aastud0910 p:float l:aastud0910 t:dataTypeName=number

metric m:wstud0910 p:float l:wstud0910 t:dataTypeName=number

metric m:hstud0910 p:float l:hstud0910 t:dataTypeName=number

metric m:yempl10 p:double l:yempl10 t:dataTypeName=number

metric m:yvotereg10 p:float l:yvotereg10 t:dataTypeName=number

metric m:yvoted10 p:float l:yvoted10 t:dataTypeName=number

entity e:grrd-c7p6 l:"Education and Youth 2010" t:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore" t:url=https://data.baltimorecity.gov/api/views/grrd-c7p6

property e:grrd-c7p6 t:meta.view v:id=grrd-c7p6 v:category=Neighborhoods v:attributionLink=http://www.bniajfi.org/ v:averageRating=0 v:name="Education and Youth 2010" v:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore"

property e:grrd-c7p6 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:grrd-c7p6 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:grrd-c7p6 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | eenr0910 | menr0910 | henr0910 | caelem0910         | camid0910          | cahigh0910         | susp0910           | drop0910           | compl0910          | farms0910          | aastud0910         | wstud0910 | hstud0910           | yempl10 | yvotereg10         | yvoted10           | 
| ================================= | ======== | ======== | ======== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ========= | =================== | ======= | ================== | ================== | 
| Allendale/Irvington/S. Hilton     | 1118     | 747      | 1064     | 14.67              | 28.78              | 41.17              | 9.4700000000000006 | 3.76               | 80.349999999999994 | 86.05              | 94.92              | 2.9       | 0.76                | 82.11   | 78.89              | 20.02              | 
| Beechfield/Ten Hills/West Hills   | 574      | 349      | 511      | 6.45               | 11.75              | 29.94              | 8.11               | 1.96               | 85.87              | 76.260000000000005 | 95.4               | 2.14      | 0.65                | 76.67   | 83.55              | 24.72              | 
| Belair-Edison                     | 1162     | 831      | 1219     | 14.03              | 12.39              | 41.1               | 9.89               | 4.0199999999999996 | 82.86              | 85.54              | 96.92              | 1.25      | 0.28999999999999998 | 79.62   | 80.849999999999994 | 19.829999999999998 | 
| Brooklyn/Curtis Bay/Hawkins Point | 1011     | 525      | 615      | 19.579999999999998 | 21.33              | 36.26              | 7.97               | 5.2                | 78.459999999999994 | 85.78              | 58.92              | 31.12     | 6.55                | 87.33   | 44.7               | 7.05               | 
| Canton                            | 90       | 32       | 49       | 7.78               | 21.88              | 22.45              | 8.4700000000000006 | 4.08               | 75                 | 73.540000000000006 | 19.579999999999998 | 59.79     | 17.46               | 92.03   | 52.82              | 15.18              | 
| Cedonia/Frankford                 | 1284     | 729      | 1477     | 10.51              | 9.0500000000000007 | 35.479999999999997 | 9.11               | 2.57               | 82.12              | 80.510000000000005 | 91.33              | 3.47      | 0.95                | 91.26   | 68.97              | 15.83              | 
| Cherry Hill                       | 833      | 412      | 584      | 14.29              | 16.989999999999998 | 44.18              | 10.46              | 3.94               | 76.400000000000006 | 91.25              | 97.61              | 0.49      | 0.05                | 85.51   | 72.09              | 14.06              | 
| Chinquapin Park/Belvedere         | 381      | 228      | 351      | 10.5               | 9.2100000000000009 | 34.47              | 6.52               | 4.2699999999999996 | 76.39              | 79.55              | 93.28              | 3.6       | 0.39                | 81.55   | 66.78              | 17.25              | 
| Claremont/Armistead               | 538      | 267      | 343      | 14.13              | 15.36              | 41.4               | 4.79               | 3.21               | 80.33              | 81.849999999999994 | 58.68              | 23.8      | 14.38               | 87.04   | 57.81              | 11.42              | 
| Clifton-Berea                     | 879      | 523      | 784      | 15.36              | 17.97              | 42.22              | 10.36              | 4.59               | 77.7               | 89.9               | 98.24              | 0.26      | 0.39                | 84.53   | 81.61              | 16.649999999999999 | 
```