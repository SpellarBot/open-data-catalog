# SB2381 Grant List - DCFS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sb2381-grant-list-dcfs-f6f71) |
| Metadata | [Link](https://data.illinois.gov/api/views/rmie-53h2) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rmie-53h2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rmie-53h2/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rmie-53h2 |
| Name | SB2381 Grant List - DCFS |
| Attribution | DCFS |
| Created | 2014-03-26T14:42:51Z |
| Publication Date | 2014-03-26T14:44:47Z |

## Description

Grants Awarded by DCFS FY14

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | oblgid       | Oblgid       | text      | text        |
| Yes      | series tag     | descd        | Descd        | text      | text        |
| Yes      | series tag     | comptnm      | ComptNm      | text      | text        |
| Yes      | series tag     | locstr       | LocStr       | text      | text        |
| Yes      | series tag     | loccsz       | LocCSZ       | text      | text        |
| Yes      | series tag     | prog         | Prog         | text      | text        |
| Yes      | numeric metric | totalob_fy14 | TotalOb_Fy14 | money     | money       |
| Yes      | series tag     | oblgbegdt    | OblgBegDt    | text      | text        |
| Yes      | series tag     | oblgenddt    | OblgEndDt    | text      | text        |
| Yes      | series tag     | code         | Code         | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rmie-53h2 d:2014-03-26T07:42:54.000Z t:oblgid=0005430024 t:comptnm="COUNTY OF MCHENRY ILLINOIS" t:prog="ADOPTION RESPITE" t:locstr="620 DAKOTA ST" t:code=2 t:oblgenddt=30-Jun-14 t:oblgbegdt=01-Jul-13 t:loccsz="CRYSTAL LAKE, IL  60012-" t:descd=ADP m:totalob_fy14=50000

series e:rmie-53h2 d:2014-03-26T07:42:54.000Z t:oblgid=0039710024 t:comptnm="THE CATHOLIC CHARITIES OF THE" t:prog="RESPITE CARE" t:locstr="721 N LA SALLE DR" t:code=2 t:oblgenddt=30-Jun-14 t:oblgbegdt=01-Jul-13 t:loccsz="CHICAGO, IL  60654-3503" t:descd=ADP m:totalob_fy14=83999.9

series e:rmie-53h2 d:2014-03-26T07:42:54.000Z t:oblgid=0042368014 t:comptnm="CHILDRENS HOME & AID SOC OF IL" t:prog="Adoption Respite" t:locstr="125 SOUTH WACKER DRIVE 14TH FL" t:code=2 t:oblgenddt=30-Jun-14 t:oblgbegdt=01-Jul-13 t:loccsz="CHICAGO, IL  60606-0000" t:descd=ADP m:totalob_fy14=50000
```

## Meta Commands

```ls
metric m:totalob_fy14 p:double l:TotalOb_Fy14 t:dataTypeName=money

entity e:rmie-53h2 l:"SB2381 Grant List - DCFS" t:attribution=DCFS t:url=https://data.illinois.gov/api/views/rmie-53h2

property e:rmie-53h2 t:meta.view v:id=rmie-53h2 v:averageRating=0 v:name="SB2381 Grant List - DCFS" v:attribution=DCFS

property e:rmie-53h2 t:meta.view.owner v:id=mcp3-3y86 v:screenName=cs v:displayName=cs

property e:rmie-53h2 t:meta.view.tableauthor v:id=mcp3-3y86 v:screenName=cs v:displayName=cs
```

## Top Records

```ls
| :updated_at | oblgid     | descd | comptnm                        | locstr                         | loccsz                   | prog                           | totalob_fy14 | oblgbegdt | oblgenddt | code | 
| =========== | ========== | ===== | ============================== | ============================== | ======================== | ============================== | ============ | ========= | ========= | ==== | 
| 1395819774  | 0005430024 | ADP   | COUNTY OF MCHENRY ILLINOIS     | 620 DAKOTA ST                  | CRYSTAL LAKE, IL 60012-  | ADOPTION RESPITE               | 50000.00     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0039710024 | ADP   | THE CATHOLIC CHARITIES OF THE  | 721 N LA SALLE DR              | CHICAGO, IL 60654-3503   | RESPITE CARE                   | 83999.90     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0042368014 | ADP   | CHILDRENS HOME & AID SOC OF IL | 125 SOUTH WACKER DRIVE 14TH FL | CHICAGO, IL 60606-0000   | Adoption Respite               | 50000.00     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0042369044 | ADP   | CHILDRENS HOME & AID SOC OF IL | 125 SOUTH WACKER DRIVE 14TH FL | CHICAGO, IL 60606-0000   | ADOPTION RESPITE               | 50000.00     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0042369154 | ADP   | CHILDRENS HOME & AID SOC OF IL | 125 SOUTH WACKER DRIVE 14TH FL | CHICAGO, IL 60606-0000   | ADOPTION RESPITE CARE          | 50000.00     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0049850024 | ADP   | COUNSELING AND FAMILY SERVICE  | 330 SW WASHINGTON ST           | PEORIA, IL 61602-1406    | RESPITE CARE                   | 80000.00     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0068389024 | ADP   | CORNERSTONE-FOUNDATIONS FOR    | 915 VERMONT ST                 | QUINCY, IL 62301-3049    | ADOPTION RESPITE PROGRAM       | 10126.00     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0100530054 | ADP   | ONE HOPE UNITED-HUDELSON REG   | 1400 EAST MCCORD               | CENTRALIA, IL 62801-0000 | RESPITE FOR ADOPTION AND GUARD | 75000.00     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0130059064 | ADP   | LUTHERAN SOCIAL SERVICES OF IL | 1001 E TOUHY AV #50            | DES PLAINES, IL 60018    | ADOPTION RESPITE PROGRAM       | 50000.00     | 01-Jul-13 | 30-Jun-14 | 2    | 
| 1395819774  | 0203299074 | ADP   | THE BABY FOLD                  | 108 EAST WILLOW STREET         | NORMAL, IL 61761         | ADOPTION RESPITE               | 100000.00    | 01-Jul-13 | 30-Jun-14 | 2    | 
```