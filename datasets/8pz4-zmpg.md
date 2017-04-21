# Reportable Communicable Disease Cases, 2000 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/reportable-communicable-disease-cases-2000-2009-66716) |
| Metadata | [Link](https://data.illinois.gov/api/views/8pz4-zmpg) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8pz4-zmpg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8pz4-zmpg/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8pz4-zmpg |
| Name | Reportable Communicable Disease Cases, 2000 - 2009 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section |
| Category | Health |
| Tags | health, reportable, communicable disease, disease |
| Created | 2014-08-11T21:51:19Z |
| Publication Date | 2014-08-11T21:59:10Z |

## Description

Data provided by the Communicable Disease Section of the Office of Health Protection's Division of Infectious Diseases.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | disease    | Disease | text      | text        |
| Yes      | numeric metric | 2000       | 2000    | number    | number      |
| Yes      | numeric metric | 2001       | 2001    | number    | number      |
| Yes      | numeric metric | 2002       | 2002    | number    | number      |
| Yes      | numeric metric | 2003       | 2003    | number    | number      |
| Yes      | numeric metric | 2004       | 2004    | number    | number      |
| Yes      | numeric metric | 2005       | 2005    | number    | number      |
| Yes      | numeric metric | 2006       | 2006    | number    | number      |
| Yes      | numeric metric | 2007       | 2007    | number    | number      |
| Yes      | numeric metric | 2008       | 2008    | number    | number      |
| Yes      | numeric metric | 2009       | 2009    | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8pz4-zmpg d:2000-01-01T00:00:00.000Z t:disease=Anthrax m:2008=0 m:2009=0 m:2006=0 m:2007=0 m:2004=0 m:2005=0 m:2002=0 m:2003=0 m:2001=0 m:2000=0

series e:8pz4-zmpg d:2000-01-01T00:00:00.000Z t:disease=Blastomycosis m:2006=119 m:2007=137 m:2004=92 m:2005=102 m:2002=87 m:2003=89 m:2001=47 m:2000=65

series e:8pz4-zmpg d:2000-01-01T00:00:00.000Z t:disease="Botulism, foodborne" m:2008=0 m:2009=0 m:2006=1 m:2007=0 m:2004=0 m:2005=1 m:2002=0 m:2003=0 m:2001=0 m:2000=0
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

entity e:8pz4-zmpg l:"Reportable Communicable Disease Cases, 2000 - 2009" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section" t:url=https://data.illinois.gov/api/views/8pz4-zmpg

property e:8pz4-zmpg t:meta.view v:id=8pz4-zmpg v:category=Health v:averageRating=0 v:name="Reportable Communicable Disease Cases, 2000 - 2009" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section"

property e:8pz4-zmpg t:meta.view.license v:name="Public Domain"

property e:8pz4-zmpg t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:8pz4-zmpg t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| disease                             | 2000  | 2001  | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009 | 
| =================================== | ===== | ===== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| Anthrax                             | 0     | 0     | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Blastomycosis                       | 65    | 47    | 87   | 89   | 92   | 102  | 119  | 137  |      |      | 
| Botulism, foodborne                 | 0     | 0     | 0    | 0    | 0    | 1    | 1    | 0    | 0    | 0    | 
| Botulism, infant                    | 2     | 0     | 1    | 0    | 0    | 1    | 1    | 1    | 1    | 0    | 
| Brucellosis                         | 8     | 4     | 7    | 0    | 9    | 13   | 8    | 6    | 1    | 4    | 
| California encephalitis             | 3     | 5     | 8    | 11   | 8    | 1    | 0    | 0    | 0    | 1    | 
| Campylobacter                       | 951   | 1256  | 1207 | 1235 | 1401 | 1376 | 1294 | 1277 |      |      | 
| Chickenpox, total (including adult) | 12848 | 10653 | 9879 | 3823 | 6279 | 1816 | 1915 | 1091 | 1489 | 1582 | 
| Chickenpox, adult                   |       |       |      |      | 7    | 107  | 150  | 202  | 151  | 126  | 
| Cholera                             | 0     | 0     | 0    | 0    | 1    | 0    | 1    | 0    | 1    | 0    | 
```