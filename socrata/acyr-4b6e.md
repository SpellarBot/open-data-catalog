# OEIG Primary Allegation of Complaints in FY 2010, FY 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-primary-allegation-of-complaints-in-fy-2010-fy-2011-99ec5) |
| Metadata | [Link](https://data.illinois.gov/api/views/acyr-4b6e) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/acyr-4b6e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/acyr-4b6e/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | acyr-4b6e |
| Name | OEIG Primary Allegation of Complaints in FY 2010, FY 2011 |
| Created | 2011-09-13T15:19:49Z |
| Publication Date | 2011-09-13T15:19:49Z |

## Description

Primary Allegation of Complaints in FY 2010, FY 2011 from the Office of Executive Inspector General Annual Report, Fiscal Year 2011, Appendix D.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | category_of_misconduct | Category of Misconduct | text      | text        |
| Yes      | numeric metric | fy_2010                | FY 2010                | number    | number      |
| Yes      | numeric metric | fy_2011                | FY 2011                | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:acyr-4b6e d:2010-01-01T00:00:00.000Z t:category_of_misconduct=Abuse m:fy_2010=2 m:fy_2011=29

series e:acyr-4b6e d:2010-01-01T00:00:00.000Z t:category_of_misconduct="Abuse of Time" m:fy_2010=74 m:fy_2011=94

series e:acyr-4b6e d:2010-01-01T00:00:00.000Z t:category_of_misconduct="Americans with Disabilities violation" m:fy_2010=0 m:fy_2011=1
```

## Meta Commands

```ls
metric m:fy_2010 p:integer l:"FY 2010" t:dataTypeName=number

metric m:fy_2011 p:integer l:"FY 2011" t:dataTypeName=number

entity e:acyr-4b6e l:"OEIG Primary Allegation of Complaints in FY 2010, FY 2011" t:url=https://data.illinois.gov/api/views/acyr-4b6e

property e:acyr-4b6e t:meta.view v:id=acyr-4b6e v:averageRating=0 v:name="OEIG Primary Allegation of Complaints in FY 2010, FY 2011"

property e:acyr-4b6e t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:acyr-4b6e t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```

## Top Records

```ls
| category_of_misconduct                | fy_2010 | fy_2011 | 
| ===================================== | ======= | ======= | 
| Abuse                                 | 2       | 29      | 
| Abuse of Time                         | 74      | 94      | 
| Americans with Disabilities violation | 0       | 1       | 
| Bid-rigging                           | 5       | 4       | 
| Breach of Confidentiality             | 20      | 19      | 
| Bribery                               | 2       | 4       | 
| Child Support                         | 0       | 9       | 
| Conflict of Interest                  | 33      | 28      | 
| Corruption                            | 0       | 5       | 
| Discrimination                        | 10      | 26      | 
```