# 2013 Special April - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/april-2013-special-election-ecanvass-cd7cd) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/xqt5-mdmf) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/xqt5-mdmf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/xqt5-mdmf/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | xqt5-mdmf |
| Name | 2013 Special April - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2013, 2013 special, special, elections, results, precinct, ecanvass |
| Created | 2013-05-15T15:06:00Z |
| Publication Date | 2013-05-15T15:06:50Z |

## Description

April 2013 special election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | precinct     | Precinct     | text      | text        |
| Yes      | series tag     | race         | Race         | text      | text        |
| Yes      | numeric metric | leg          | LEG          | number    | number      |
| No       |                | cc           | CC           | number    | number      |
| No       |                | cg           | CG           | number    | number      |
| Yes      | series tag     | countergroup | CounterGroup | text      | text        |
| Yes      | series tag     | party        | Party        | text      | text        |
| Yes      | series tag     | countertype  | CounterType  | text      | text        |
| Yes      | numeric metric | sumofcount   | SumOfCount   | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:xqt5-mdmf d:2013-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=No t:countergroup=Total t:party=NP t:race="Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation" m:leg=45 m:sumofcount=16

series e:xqt5-mdmf d:2013-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation" m:leg=45 m:sumofcount=229

series e:xqt5-mdmf d:2013-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation" m:leg=45 m:sumofcount=0
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:xqt5-mdmf l:"2013 Special April - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/xqt5-mdmf

property e:xqt5-mdmf t:meta.view v:id=xqt5-mdmf v:category="Election results" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="2013 Special April - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:xqt5-mdmf t:meta.view.license v:name="Public Domain"

property e:xqt5-mdmf t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:xqt5-mdmf t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct      | race                                                                    | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ============= | ======================================================================= | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR         | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | No                | 16         | 
| ADAIR         | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | Registered Voters | 229        | 
| ADAIR         | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 0          | 
| ADAIR         | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | Times Counted     | 120        | 
| ADAIR         | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR         | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | Yes               | 104        | 
| ALDER SPRINGS | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | No                | 8          | 
| ALDER SPRINGS | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | Registered Voters | 426        | 
| ALDER SPRINGS | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 0          | 
| ALDER SPRINGS | Woodinville Fire & Rescue Proposition No. 1 Benefit Charge Continuation | 45  | 3  | 1  | Total        | NP    | Times Counted     | 92         | 
```