# Number of Cancer Cases for All Cancer Sites by Jurisdiction, Gender, and Race, Maryland 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-cancer-cases-for-all-cancer-sites-by-jurisdiction-gender-and-race-maryland-2009-eaa80) |
| Metadata | [Link](https://data.maryland.gov/api/views/sx7q-snbm) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/sx7q-snbm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/sx7q-snbm/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | sx7q-snbm |
| Name | Number of Cancer Cases for All Cancer Sites by Jurisdiction, Gender, and Race, Maryland 2009 |
| Attribution | Maryland Cancer Registry |
| Category | Health and Human Services |
| Tags | cancer, maryland cancer registry |
| Created | 2013-01-03T20:49:35Z |
| Publication Date | 2013-01-04T20:51:46Z |

## Description

Definition of "All Cancer Sites": ICD-O-3 Topography (Site) Codes  C00.0 ? C80.9  with histology codes including all invasive cancers of all sites except basal and squamous cell skin cancers, and in situ cancer cases of the urinary bladder.  Total includes cases reported as transexual, hermaphrodite, and unknown gender.  Some cells are missing data due to suppression of low cell counts.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | jurisdiction | Jurisdiction | text      | text        |
| Yes      | numeric metric | total        | Total        | number    | number      |
| Yes      | numeric metric | males        | Males        | number    | number      |
| Yes      | numeric metric | females      | Females      | number    | number      |
| Yes      | numeric metric | whites       | Whites       | number    | number      |
| Yes      | numeric metric | blacks       | Blacks       | number    | number      |
| Yes      | numeric metric | other_race   | Other Race   | number    | number      |
| Yes      | numeric metric | unknown_race | Unknown Race | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sx7q-snbm d:2009-01-01T00:00:00.000Z t:jurisdiction=Maryland m:total=26800 m:whites=18912 m:unknown_race=250 m:males=13346 m:blacks=6557 m:females=13413 m:other_race=1081

series e:sx7q-snbm d:2009-01-01T00:00:00.000Z t:jurisdiction=Allegany m:total=518 m:whites=503 m:unknown_race=0 m:males=254 m:females=263

series e:sx7q-snbm d:2009-01-01T00:00:00.000Z t:jurisdiction="Anne Arundel" m:total=2589 m:whites=2204 m:unknown_race=15 m:males=1342 m:blacks=311 m:females=1241 m:other_race=59
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

metric m:males p:integer l:Males t:dataTypeName=number

metric m:females p:integer l:Females t:dataTypeName=number

metric m:whites p:integer l:Whites t:dataTypeName=number

metric m:blacks p:integer l:Blacks t:dataTypeName=number

metric m:other_race p:integer l:"Other Race" t:dataTypeName=number

metric m:unknown_race p:integer l:"Unknown Race" t:dataTypeName=number

entity e:sx7q-snbm l:"Number of Cancer Cases for All Cancer Sites by Jurisdiction, Gender, and Race, Maryland 2009" t:attribution="Maryland Cancer Registry" t:url=https://data.maryland.gov/api/views/sx7q-snbm

property e:sx7q-snbm t:meta.view v:id=sx7q-snbm v:category="Health and Human Services" v:attributionLink=http://fha.dhmh.maryland.gov/cancer/SitePages/mcr_home.aspx v:averageRating=0 v:name="Number of Cancer Cases for All Cancer Sites by Jurisdiction, Gender, and Race, Maryland 2009" v:attribution="Maryland Cancer Registry"

property e:sx7q-snbm t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:sx7q-snbm t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| jurisdiction     | total | males | females | whites | blacks | other_race | unknown_race | 
| ================ | ===== | ===== | ======= | ====== | ====== | ========== | ============ | 
| Maryland         | 26800 | 13346 | 13413   | 18912  | 6557   | 1081       | 250          | 
| Allegany         | 518   | 254   | 263     | 503    |        |            | 0            | 
| Anne Arundel     | 2589  | 1342  | 1241    | 2204   | 311    | 59         | 15           | 
| Baltimore City   | 3048  | 1512  | 1533    | 1094   | 1898   | 41         | 15           | 
| Baltimore County | 4369  | 2081  | 2285    | 3502   | 741    | 109        | 17           | 
| Calvert          | 360   | 168   | 185     | 308    | 46     |            |              | 
| Caroline         | 156   | 79    | 77      | 136    |        |            | 0            | 
| Carroll          | 839   | 412   | 427     | 800    | 24     |            |              | 
| Cecil            | 455   | 234   | 221     | 431    |        |            | 0            | 
| Charles          | 500   | 267   | 230     | 313    | 163    | 16         | 8            | 
```