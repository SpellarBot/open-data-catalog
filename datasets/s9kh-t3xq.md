# Arts and Culture (2010-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arts-and-culture-2010-2013) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/s9kh-t3xq) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/s9kh-t3xq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/s9kh-t3xq/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | s9kh-t3xq |
| Name | Arts and Culture (2010-2013) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | arts, culture, bnia |
| Created | 2015-05-14T19:42:22Z |
| Publication Date | 2015-05-14T19:43:59Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and socioeconomic indicators for neighborhoods. The Census Bureau collects a wide variety of information through administration of both the decennial Census and the annual American Community Survey (ACS).

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | neighborhood | Neighborhood | text      | text        |
| Yes      | numeric metric | artbus11     | artbus11     | number    | number      |
| Yes      | numeric metric | artbus12     | artbus12     | number    | number      |
| Yes      | numeric metric | artbus13     | artbus13     | number    | number      |
| Yes      | numeric metric | artemp11     | artemp11     | number    | number      |
| Yes      | numeric metric | artemp12     | artemp12     | number    | number      |
| Yes      | numeric metric | artemp13     | artemp13     | number    | number      |
| Yes      | numeric metric | libcard11    | libcard11    | number    | number      |
| Yes      | numeric metric | libcard12    | libcard12    | number    | number      |
| Yes      | numeric metric | libcard13    | libcard13    | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:s9kh-t3xq d:2010-01-01T00:00:00.000Z t:neighborhood="Allendale/Irvington/S. Hilton" m:libcard11=194.7 m:libcard12=206 m:libcard13=185.5 m:artbus12=0 m:artemp12=0 m:artbus13=0 m:artemp13=0 m:artbus11=0 m:artemp11=0

series e:s9kh-t3xq d:2010-01-01T00:00:00.000Z t:neighborhood="Beechfield/Ten Hills/West Hills" m:libcard11=153.2 m:libcard12=152.5 m:libcard13=140.4 m:artbus12=0.2 m:artemp12=7 m:artbus13=0.1 m:artemp13=4 m:artbus11=0.1 m:artemp11=4

series e:s9kh-t3xq d:2010-01-01T00:00:00.000Z t:neighborhood=Belair-Edison m:libcard11=319.4 m:libcard12=310.2 m:libcard13=261.3 m:artbus12=0.2 m:artemp12=26 m:artbus13=0.2 m:artemp13=26 m:artbus11=0.1 m:artemp11=24
```

## Meta Commands

```ls
metric m:artbus11 p:float l:artbus11 t:dataTypeName=number

metric m:artbus12 p:float l:artbus12 t:dataTypeName=number

metric m:artbus13 p:float l:artbus13 t:dataTypeName=number

metric m:artemp11 p:integer l:artemp11 t:dataTypeName=number

metric m:artemp12 p:integer l:artemp12 t:dataTypeName=number

metric m:artemp13 p:integer l:artemp13 t:dataTypeName=number

metric m:libcard11 p:float l:libcard11 t:dataTypeName=number

metric m:libcard12 p:float l:libcard12 t:dataTypeName=number

metric m:libcard13 p:float l:libcard13 t:dataTypeName=number

entity e:s9kh-t3xq l:"Arts and Culture (2010-2013)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/s9kh-t3xq

property e:s9kh-t3xq t:meta.view v:id=s9kh-t3xq v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Arts and Culture (2010-2013)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:s9kh-t3xq t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:s9kh-t3xq t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:s9kh-t3xq t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| neighborhood                      | artbus11 | artbus12 | artbus13 | artemp11 | artemp12 | artemp13 | libcard11 | libcard12 | libcard13 | 
| ================================= | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ========= | ========= | 
| Allendale/Irvington/S. Hilton     | 0.0      | 0.0      | 0.0      | 0        | 0        | 0        | 194.7     | 206.0     | 185.5     | 
| Beechfield/Ten Hills/West Hills   | 0.1      | 0.2      | 0.1      | 4        | 7        | 4        | 153.2     | 152.5     | 140.4     | 
| Belair-Edison                     | 0.1      | 0.2      | 0.2      | 24       | 26       | 26       | 319.4     | 310.2     | 261.3     | 
| Brooklyn/Curtis Bay/Hawkins Point | 0.1      | 0.2      | 0.2      | 9        | 12       | 6        | 229.7     | 194.2     | 187.1     | 
| Canton                            | 0.0      | 0.0      | 0.1      | 0        | 0        | 1        | 267.8     | 235.3     | 169.4     | 
| Cedonia/Frankford                 | 0.2      | 0.3      | 0.2      | 12       | 15       | 11       | 216.3     | 212.3     | 186.2     | 
| Cherry Hill                       | 0.1      | 0.1      | 0.2      | 50       | 4        | 12       | 323.6     | 299.3     | 279.7     | 
| Chinquapin Park/Belvedere         | 0.1      | 0.1      | 0.1      | 10       | 10       | 2        | 236.7     | 247.9     | 218.3     | 
| Claremont/Armistead               | 0.4      | 0.4      | 0.2      | 22       | 22       | 14       | 182.7     | 161.9     | 145.3     | 
| Clifton-Berea                     | 0.0      | 0.0      | 0.1      | 0        | 0        | 1        | 279.5     | 263.3     | 220.8     | 
```