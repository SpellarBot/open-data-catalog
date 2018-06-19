# Age-Adjusted Incidence Rates for All Cancer Sites by Jurisdiction, Gender, and Race, Maryland 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/age-adjusted-incidence-rates-for-all-cancer-sites-by-jurisdiction-gender-and-race-maryland-81eb8) |
| Metadata | [Link](https://data.maryland.gov/api/views/yg8i-6p9m) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/yg8i-6p9m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/yg8i-6p9m/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | yg8i-6p9m |
| Name | Age-Adjusted Incidence Rates for All Cancer Sites by Jurisdiction, Gender, and Race, Maryland 2009 |
| Attribution | Maryland Cancer Registry |
| Category | Health and Human Services |
| Tags | cancer, maryland cancer registry |
| Created | 2013-01-03T22:12:49Z |
| Publication Date | 2013-01-04T20:51:21Z |

## Description

Definition of "All Cancer Sites": ICD-O-3 Topography (Site) Codes  C00.0 ? C80.9  with histology codes including all invasive cancers of all sites except basal and squamous cell skin cancers, and in situ cancer cases of the urinary bladder.  Rates are per 100,000 population and are age-adjusted to 2000 U.S. standard population. Rates based on case counts of 1-15 are suppressed per DHMH/MCR Data Use Policy and Procedures.

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
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yg8i-6p9m d:2009-01-01T00:00:00.000Z t:jurisdiction=Maryland m:total=443.7 m:whites=446.5 m:males=500.4 m:blacks=431.8 m:females=405 m:other_race=356.1

series e:yg8i-6p9m d:2009-01-01T00:00:00.000Z t:jurisdiction=Allegany m:total=532.3 m:whites=537 m:males=588.7 m:females=503.9

series e:yg8i-6p9m d:2009-01-01T00:00:00.000Z t:jurisdiction="Anne Arundel" m:total=472.8 m:whites=476.1 m:males=530.9 m:blacks=464.9 m:females=427.7 m:other_race=357.9
```

## Meta Commands

```ls
metric m:total p:float l:Total t:dataTypeName=number

metric m:males p:float l:Males t:dataTypeName=number

metric m:females p:float l:Females t:dataTypeName=number

metric m:whites p:float l:Whites t:dataTypeName=number

metric m:blacks p:float l:Blacks t:dataTypeName=number

metric m:other_race p:float l:"Other Race" t:dataTypeName=number

entity e:yg8i-6p9m l:"Age-Adjusted Incidence Rates for All Cancer Sites by Jurisdiction, Gender, and Race, Maryland 2009" t:attribution="Maryland Cancer Registry" t:url=https://data.maryland.gov/api/views/yg8i-6p9m

property e:yg8i-6p9m t:meta.view v:id=yg8i-6p9m v:category="Health and Human Services" v:attributionLink=http://fha.dhmh.maryland.gov/cancer/SitePages/mcr_home.aspx v:averageRating=0 v:name="Age-Adjusted Incidence Rates for All Cancer Sites by Jurisdiction, Gender, and Race, Maryland 2009" v:attribution="Maryland Cancer Registry"

property e:yg8i-6p9m t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:yg8i-6p9m t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| jurisdiction     | total | males | females | whites | blacks | other_race | 
| ================ | ===== | ===== | ======= | ====== | ====== | ========== | 
| Maryland         | 443.7 | 500.4 | 405.0   | 446.5  | 431.8  | 356.1      | 
| Allegany         | 532.3 | 588.7 | 503.9   | 537.0  |        |            | 
| Anne Arundel     | 472.8 | 530.9 | 427.7   | 476.1  | 464.9  | 357.9      | 
| Baltimore City   | 471.5 | 564.7 | 410.8   | 483.5  | 462.3  | 387.4      | 
| Baltimore County | 476.3 | 516.7 | 450.6   | 484.1  | 466.4  | 337.0      | 
| Calvert          | 412.9 | 424.8 | 396.3   | 423.4  | 356.8  |            | 
| Caroline         | 428.9 | 480.9 | 395.7   | 442.7  | 367.9  |            | 
| Carroll          | 440.7 | 478.2 | 417.1   | 440.7  | 386.7  |            | 
| Cecil            | 430.5 | 483.3 | 392.8   | 434.9  | 365.2  |            | 
| Charles          | 387.9 | 457.1 | 327.3   | 376.1  | 403.7  | 402.6      | 
```