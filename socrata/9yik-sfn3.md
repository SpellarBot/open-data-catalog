# Reportable Communicable Disease Cases, 1990 - 1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/reportable-communicable-disease-cases-1990-1999-9407f) |
| Metadata | [Link](https://data.illinois.gov/api/views/9yik-sfn3) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9yik-sfn3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9yik-sfn3/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9yik-sfn3 |
| Name | Reportable Communicable Disease Cases, 1990 - 1999 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section |
| Category | Health |
| Tags | health, reportable, communicable disease, disease |
| Created | 2014-08-11T21:46:41Z |
| Publication Date | 2014-08-11T21:50:38Z |

## Description

Data provided by the Communicable Disease Section of the Office of Health Protection's Division of Infectious Diseases

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | diseases   | Diseases | text      | text        |
| Yes      | numeric metric | 1990       | 1990     | number    | number      |
| Yes      | numeric metric | 1991       | 1991     | number    | number      |
| Yes      | numeric metric | 1992       | 1992     | number    | number      |
| Yes      | numeric metric | 1993       | 1993     | number    | number      |
| Yes      | numeric metric | 1994       | 1994     | number    | number      |
| Yes      | numeric metric | 1995       | 1995     | number    | number      |
| Yes      | numeric metric | 1996       | 1996     | number    | number      |
| Yes      | numeric metric | 1997       | 1997     | number    | number      |
| Yes      | numeric metric | 1998       | 1998     | number    | number      |
| Yes      | numeric metric | 1999       | 1999     | number    | number      |
```

## Time Field

```ls
Value = 1990
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9yik-sfn3 d:1990-01-01T00:00:00.000Z t:diseases=Amebiasis m:1995=82 m:1996=69 m:1997=47 m:1998=54 m:1991=36 m:1992=56 m:1993=50 m:1994=45 m:1990=59 m:1999=65

series e:9yik-sfn3 d:1990-01-01T00:00:00.000Z t:diseases="Animal Bites" m:1995=8433 m:1996=12269 m:1997=9067 m:1998=12192 m:1991=6726 m:1992=9696 m:1993=9270 m:1994=9813 m:1990=6761 m:1999=9446

series e:9yik-sfn3 d:1990-01-01T00:00:00.000Z t:diseases=Anthrax m:1995=0 m:1996=0 m:1997=0 m:1998=0 m:1991=0 m:1992=0 m:1993=0 m:1994=0 m:1990=0 m:1999=0
```

## Meta Commands

```ls
metric m:1990 p:integer l:1990 t:dataTypeName=number

metric m:1991 p:integer l:1991 t:dataTypeName=number

metric m:1992 p:integer l:1992 t:dataTypeName=number

metric m:1993 p:integer l:1993 t:dataTypeName=number

metric m:1994 p:integer l:1994 t:dataTypeName=number

metric m:1995 p:integer l:1995 t:dataTypeName=number

metric m:1996 p:integer l:1996 t:dataTypeName=number

metric m:1997 p:integer l:1997 t:dataTypeName=number

metric m:1998 p:integer l:1998 t:dataTypeName=number

metric m:1999 p:integer l:1999 t:dataTypeName=number

entity e:9yik-sfn3 l:"Reportable Communicable Disease Cases, 1990 - 1999" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section" t:url=https://data.illinois.gov/api/views/9yik-sfn3

property e:9yik-sfn3 t:meta.view v:id=9yik-sfn3 v:category=Health v:averageRating=0 v:name="Reportable Communicable Disease Cases, 1990 - 1999" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Diseases, Communicable Disease Section"

property e:9yik-sfn3 t:meta.view.license v:name="Public Domain"

property e:9yik-sfn3 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:9yik-sfn3 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| diseases            | 1990  | 1991  | 1992  | 1993  | 1994  | 1995  | 1996  | 1997  | 1998  | 1999  | 
| =================== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | 
| Amebiasis           | 59    | 36    | 56    | 50    | 45    | 82    | 69    | 47    | 54    | 65    | 
| Animal Bites        | 6761  | 6726  | 9696  | 9270  | 9813  | 8433  | 12269 | 9067  | 12192 | 9446  | 
| Anthrax             | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| Blastomycosis       | 44    | 29    | 32    | 24    | 25    | 43    | 41    | 29    | 47    | 50    | 
| Botulism, Foodborne | 0     | 1     | 0     | 0     | 1     | 0     | 0     | 1     | 0     | 0     | 
| Botulism, Infant    | 0     | 0     | 0     | 0     | 2     | 0     | 0     | 1     | 3     | 0     | 
| Brucellosis         | 5     | 8     | 4     | 6     | 5     | 8     | 8     | 7     | 5     | 10    | 
| Campylobacter       | 687   | 702   | 694   | 882   | 950   | 1064  | 1037  | 874   | 678   | 721   | 
| Cat Scratch Fever   | 0     | 0     | 1     | 0     | 3     | 0     | 1     | 7     | 37    | 31    | 
| Chickenpox          | 31189 | 24044 | 33603 | 26447 | 33889 | 24798 | 19898 | 19501 | 16477 | 13881 | 
```