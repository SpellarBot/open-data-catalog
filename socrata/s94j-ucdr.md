# SB2381- FY13 DCFS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sb2381-fy13-dcfs-0b7d1) |
| Metadata | [Link](https://data.illinois.gov/api/views/s94j-ucdr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/s94j-ucdr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/s94j-ucdr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | s94j-ucdr |
| Name | SB2381- FY13 DCFS |
| Attribution | DCFS |
| Created | 2014-04-02T14:36:01Z |
| Publication Date | 2014-04-02T14:39:19Z |

## Description

Grants Awarded by DCFS FY13

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | oblgid        | Oblgid        | text      | text        |
| Yes      | series tag     | descd         | Descd         | text      | text        |
| Yes      | series tag     | comptnm       | ComptNm       | text      | text        |
| Yes      | series tag     | locstr        | LocStr        | text      | text        |
| Yes      | series tag     | loccsz        | LocCSZ        | text      | text        |
| Yes      | series tag     | prog          | Prog          | text      | text        |
| Yes      | numeric metric | totalob_fy13  | TotalOb_FY13  | money     | money       |
| Yes      | series tag     | oblgbegdt     | OblgBegDt     | text      | text        |
| Yes      | series tag     | oblgenddt     | OblgEndDt     | text      | text        |
| Yes      | numeric metric | fin_rpt_lvl   | FIN_RPT_LVL   | number    | number      |
| Yes      | series tag     | contract_type | Contract_Type | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:s94j-ucdr d:2014-04-02T07:36:04.000Z t:oblgid=3844959023 t:comptnm="ADOPTIONS UNLIMITED INC" t:prog="800 INQUIRY LINE" t:contract_type="Non-Substitute Care" t:locstr="120 W MADISON ST STE 800" t:oblgenddt=30-Jun-13 t:oblgbegdt=01-Jul-12 t:loccsz="CHICAGO, IL  60602-4158" t:descd=ADP m:totalob_fy13=789442 m:fin_rpt_lvl=2

series e:s94j-ucdr d:2014-04-02T07:36:04.000Z t:oblgid=3844959033 t:comptnm="ADOPTIONS UNLIMITED INC" t:prog="RECRUITMENT & KIN CONNECT PROJ" t:contract_type=Grant t:locstr="120 W MADISON ST STE 800" t:oblgenddt=30-Sep-15 t:oblgbegdt=01-Dec-10 t:loccsz="CHICAGO, IL  60602-4158" t:descd=ADP m:totalob_fy13=369537.41 m:fin_rpt_lvl=2

series e:s94j-ucdr d:2014-04-02T07:36:04.000Z t:oblgid=4577169013 t:comptnm="CENTER FOR LAW AND SOCIAL WORK" t:prog="FAMILY MATTERS" t:contract_type="Non-Substitute Care" t:locstr="4753 N. BROADWAY #632" t:oblgenddt=30-Jun-13 t:oblgbegdt=01-Jul-12 t:loccsz="CHICAGO, IL  60640" t:descd=ADP m:totalob_fy13=750670.34 m:fin_rpt_lvl=2
```

## Meta Commands

```ls
metric m:totalob_fy13 p:double l:TotalOb_FY13 t:dataTypeName=money

metric m:fin_rpt_lvl p:integer l:FIN_RPT_LVL t:dataTypeName=number

entity e:s94j-ucdr l:"SB2381- FY13 DCFS" t:attribution=DCFS t:url=https://data.illinois.gov/api/views/s94j-ucdr

property e:s94j-ucdr t:meta.view v:id=s94j-ucdr v:averageRating=0 v:name="SB2381- FY13 DCFS" v:attribution=DCFS

property e:s94j-ucdr t:meta.view.owner v:id=mcp3-3y86 v:screenName=cs v:displayName=cs

property e:s94j-ucdr t:meta.view.tableauthor v:id=mcp3-3y86 v:screenName=cs v:displayName=cs
```

## Top Records

```ls
| :updated_at | oblgid     | descd | comptnm                        | locstr                         | loccsz                  | prog                           | totalob_fy13 | oblgbegdt | oblgenddt | fin_rpt_lvl | contract_type       | 
| =========== | ========== | ===== | ============================== | ============================== | ======================= | ============================== | ============ | ========= | ========= | =========== | =================== | 
| 1396424164  | 3844959023 | ADP   | ADOPTIONS UNLIMITED INC        | 120 W MADISON ST STE 800       | CHICAGO, IL 60602-4158  | 800 INQUIRY LINE               | 789442.00    | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
| 1396424164  | 3844959033 | ADP   | ADOPTIONS UNLIMITED INC        | 120 W MADISON ST STE 800       | CHICAGO, IL 60602-4158  | RECRUITMENT & KIN CONNECT PROJ | 369537.41    | 01-Dec-10 | 30-Sep-15 | 2           | Grant               | 
| 1396424164  | 4577169013 | ADP   | CENTER FOR LAW AND SOCIAL WORK | 4753 N. BROADWAY #632          | CHICAGO, IL 60640       | FAMILY MATTERS                 | 750670.34    | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
| 1396424164  | 0042369043 | ADP   | CHILDRENS HOME & AID SOC OF IL | 125 SOUTH WACKER DRIVE 14TH FL | CHICAGO, IL 60606-0000  | ADOPTION RESPITE               | 50000.00     | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
| 1396424164  | 0042369153 | ADP   | CHILDRENS HOME & AID SOC OF IL | 125 SOUTH WACKER DRIVE 14TH FL | CHICAGO, IL 60606-0000  | ADOPTION RESPITE CARE          | 50000.00     | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
| 1396424164  | 0068389023 | ADP   | CORNERSTONE-FOUNDATIONS FOR    | 915 VERMONT ST                 | QUINCY, IL 62301-3049   | ADOPTION RESPITE PROGRAM       | 10126.00     | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
| 1396424164  | 0049850023 | ADP   | COUNSELING AND FAMILY SERVICE  | 330 SW WASHINGTON ST           | PEORIA, IL 61602-1406   | RESPITE CARE                   | 80000.00     | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
| 1396424164  | 0005430023 | ADP   | COUNTY OF MCHENRY ILLINOIS     | 620 DAKOTA ST                  | CRYSTAL LAKE, IL 60012- | ADOPTION RESPITE               | 50000.00     | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
| 1396424164  | 3365624013 | ADP   | HEALTHY FAMILIES CHICAGO       | 2100 S MARSHALL BLVD FL 2      | CHICAGO, IL 60623-3515  | MAINTAINING ADOPT. CONNECTIONS | 461000.00    | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
| 1396424164  | 3365624023 | ADP   | HEALTHY FAMILIES CHICAGO       | 2100 S MARSHALL BLVD FL 2      | CHICAGO, IL 60623-3515  | RESPITE SERVICES               | 75000.00     | 01-Jul-12 | 30-Jun-13 | 2           | Non-Substitute Care | 
```