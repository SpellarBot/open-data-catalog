# Report Card 3c Resident Sentiment Island Economy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3c-resident-sentiment-island-economy-a4304) |
| Metadata | [Link](https://data.hawaii.gov/api/views/xrap-ydyp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/xrap-ydyp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/xrap-ydyp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | xrap-ydyp |
| Name | Report Card 3c Resident Sentiment Island Economy |
| Created | 2012-11-19T01:34:14Z |
| Publication Date | 2012-11-19T01:34:47Z |

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
series e:xrap-ydyp d:2005-01-01T00:00:00.000Z m:kauai=0.817016377353625 m:oahu=0.8064593436369296 m:maui_county=0.8017439267075528 m:hawaii_island=0.640711723068503

series e:xrap-ydyp d:2006-01-01T00:00:00.000Z m:kauai=0.8027080268560792 m:oahu=0.7985206332751774 m:maui_county=0.8453377252805074 m:hawaii_island=0.6855147437415409

series e:xrap-ydyp d:2012-01-01T00:00:00.000Z m:kauai=0.83 m:oahu=0.83 m:maui_county=0.84 m:hawaii_island=0.74
```

## Meta Commands

```ls
metric m:oahu p:float l:Oahu t:dataTypeName=number

metric m:maui_county p:decimal l:"Maui County" t:dataTypeName=number

metric m:kauai p:float l:Kauai t:dataTypeName=number

metric m:hawaii_island p:float l:"Hawaii Island" t:dataTypeName=number

entity e:xrap-ydyp l:"Report Card 3c Resident Sentiment Island Economy" t:url=https://data.hawaii.gov/api/views/xrap-ydyp

property e:xrap-ydyp t:meta.view v:id=xrap-ydyp v:averageRating=0 v:name="Report Card 3c Resident Sentiment Island Economy"

property e:xrap-ydyp t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:xrap-ydyp t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui_county         | kauai               | hawaii_island       | 
| ==== | =================== | =================== | =================== | =================== | 
| 2005 | 0.80645934363692962 | 0.80174392670755279 | 0.81701637735362498 | 0.64071172306850299 | 
| 2006 | 0.79852063327517742 | 0.84533772528050743 | 0.80270802685607923 | 0.68551474374154087 | 
| 2012 | 0.83                | 0.84                | 0.83                | 0.74                | 
```