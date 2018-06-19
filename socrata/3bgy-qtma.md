# Reportable Communicable Disease Cases, 2010 - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/reportable-communicable-disease-cases-2010-2012-331b7) |
| Metadata | [Link](https://data.illinois.gov/api/views/3bgy-qtma) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/3bgy-qtma/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/3bgy-qtma/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 3bgy-qtma |
| Name | Reportable Communicable Disease Cases, 2010 - 2012 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section |
| Category | Health |
| Tags | health, reportable, communicable disease, disease |
| Created | 2014-08-11T21:53:12Z |
| Publication Date | 2014-08-11T21:54:19Z |

## Description

Data provided by the Communicable Disease Section of the Office of Health Protection's Division of Infectious Diseases

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | disease    | Disease | text      | text        |
| Yes      | numeric metric | 2010       | 2010    | number    | number      |
| Yes      | numeric metric | 2011       | 2011    | number    | number      |
| Yes      | numeric metric | 2012       | 2012    | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3bgy-qtma d:2010-01-01T00:00:00.000Z t:disease=Anthrax m:2012=0 m:2011=0 m:2010=0

series e:3bgy-qtma d:2010-01-01T00:00:00.000Z t:disease="Botulism, foodborne" m:2012=0 m:2011=0 m:2010=0

series e:3bgy-qtma d:2010-01-01T00:00:00.000Z t:disease="Botulism, infant" m:2012=1 m:2011=0 m:2010=0
```

## Meta Commands

```ls
metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

entity e:3bgy-qtma l:"Reportable Communicable Disease Cases, 2010 - 2012" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section" t:url=https://data.illinois.gov/api/views/3bgy-qtma

property e:3bgy-qtma t:meta.view v:id=3bgy-qtma v:category=Health v:averageRating=0 v:name="Reportable Communicable Disease Cases, 2010 - 2012" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section"

property e:3bgy-qtma t:meta.view.license v:name="Public Domain"

property e:3bgy-qtma t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:3bgy-qtma t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| disease                             | 2010 | 2011 | 2012 | 
| =================================== | ==== | ==== | ==== | 
| Anthrax                             | 0    | 0    | 0    | 
| Blastomycosis                       |      |      |      | 
| Botulism, foodborne                 | 0    | 0    | 0    | 
| Botulism, infant                    | 0    | 0    | 1    | 
| Brucellosis                         | 1    | 8    | 5    | 
| California encephalitis             | 0    | 1    | 0    | 
| Campylobacter                       |      |      |      | 
| Chickenpox, total (including adult) | 1195 | 881  | 898  | 
| Chickenpox, adult                   | 120  | 133  | 133  | 
| Cholera                             | 0    | 1    | 0    | 
```