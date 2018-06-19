# Report Card 3d Resident Sentiment Island Expense Locals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3d-resident-sentiment-island-expense-locals-38f44) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jxj3-wzqf) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jxj3-wzqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jxj3-wzqf/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jxj3-wzqf |
| Name | Report Card 3d Resident Sentiment Island Expense Locals |
| Created | 2012-11-19T01:38:40Z |
| Publication Date | 2012-11-19T01:39:15Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | year          | Year          | number    | text        |
| Yes      | numeric metric | oahu          | Oahu          | number    | number      |
| Yes      | numeric metric | maui_county   | Maui County   | number    | number      |
| Yes      | numeric metric | kauai         | Kauai         | number    | number      |
| Yes      | numeric metric | hawaii_island | Hawaii Island | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jxj3-wzqf d:2005-01-01T00:00:00.000Z m:kauai=0.5692756427764489 m:oahu=0.5385142324615881 m:maui_county=0.7352338759759092 m:hawaii_island=0.5155984139910501

series e:jxj3-wzqf d:2006-01-01T00:00:00.000Z m:kauai=0.6930050974344144 m:oahu=0.600600362696733 m:maui_county=0.7707853965194649 m:hawaii_island=0.580803458454027

series e:jxj3-wzqf d:2007-01-01T00:00:00.000Z m:kauai=0.6628682836718379 m:oahu=0.5235850419448088 m:maui_county=0.647055044098386 m:hawaii_island=0.5764631465532308
```

## Meta Commands

```ls
metric m:oahu p:decimal l:Oahu t:dataTypeName=number

metric m:maui_county p:decimal l:"Maui County" t:dataTypeName=number

metric m:kauai p:decimal l:Kauai t:dataTypeName=number

metric m:hawaii_island p:decimal l:"Hawaii Island" t:dataTypeName=number

entity e:jxj3-wzqf l:"Report Card 3d Resident Sentiment Island Expense Locals" t:url=https://data.hawaii.gov/api/views/jxj3-wzqf

property e:jxj3-wzqf t:meta.view v:id=jxj3-wzqf v:averageRating=0 v:name="Report Card 3d Resident Sentiment Island Expense Locals"

property e:jxj3-wzqf t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:jxj3-wzqf t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui_county         | kauai               | hawaii_island       | 
| ==== | =================== | =================== | =================== | =================== | 
| 2005 | 0.53851423246158814 | 0.73523387597590917 | 0.56927564277644893 | 0.51559841399105011 | 
| 2006 | 0.600600362696733   | 0.77078539651946487 | 0.69300509743441441 | 0.58080345845402703 | 
| 2007 | 0.52358504194480882 | 0.64705504409838599 | 0.66286828367183792 | 0.57646314655323083 | 
| 2009 | 0.46951428490046598 | 0.58219824120661601 | 0.62413455471810597 | 0.47198256569138902 | 
| 2010 | 0.49151412027976382 | 0.64967670732212879 | 0.51708372872347397 | 0.41792343331544957 | 
| 2012 | 0.62905722493258698 | 0.71071599857325096 | 0.58239449658686904 | 0.56803634927793201 | 
```