# Report Card 3b Resident Sentiment Tourism for Family

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3b-resident-sentiment-tourism-for-family-05412) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3nqr-pbqh) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3nqr-pbqh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3nqr-pbqh/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3nqr-pbqh |
| Name | Report Card 3b Resident Sentiment Tourism for Family |
| Created | 2012-11-19T01:28:41Z |
| Publication Date | 2012-11-19T01:29:19Z |

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
series e:3nqr-pbqh d:2005-01-01T00:00:00.000Z m:kauai=0.44 m:oahu=0.46 m:maui_county=0.5 m:hawaii_island=0.38

series e:3nqr-pbqh d:2006-01-01T00:00:00.000Z m:kauai=0.35155732903594833 m:oahu=0.4501563226972335 m:maui_county=0.38591815749620706 m:hawaii_island=0.4318170817932991

series e:3nqr-pbqh d:2007-01-01T00:00:00.000Z m:kauai=0.345996709386396 m:oahu=0.44243841894897445 m:maui_county=0.3963783808980098 m:hawaii_island=0.35638960707558737
```

## Meta Commands

```ls
metric m:oahu p:float l:Oahu t:dataTypeName=number

metric m:maui_county p:decimal l:"Maui County" t:dataTypeName=number

metric m:kauai p:double l:Kauai t:dataTypeName=number

metric m:hawaii_island p:decimal l:"Hawaii Island" t:dataTypeName=number

entity e:3nqr-pbqh l:"Report Card 3b Resident Sentiment Tourism for Family" t:url=https://data.hawaii.gov/api/views/3nqr-pbqh

property e:3nqr-pbqh t:meta.view v:id=3nqr-pbqh v:averageRating=0 v:name="Report Card 3b Resident Sentiment Tourism for Family"

property e:3nqr-pbqh t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:3nqr-pbqh t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui_county         | kauai               | hawaii_island       | 
| ==== | =================== | =================== | =================== | =================== | 
| 2005 | 0.46                | 0.5                 | 0.44                | 0.38                | 
| 2006 | 0.45015632269723349 | 0.38591815749620706 | 0.35155732903594833 | 0.43181708179329908 | 
| 2007 | 0.44243841894897445 | 0.39637838089800981 | 0.34599670938639598 | 0.35638960707558737 | 
| 2009 | 0.38040763814066264 | 0.55190188807612639 | 0.45002647500152648 | 0.42280186218714272 | 
| 2010 | 0.39059919380491792 | 0.50803035687941911 | 0.43307374970213341 | 0.41337993878362955 | 
| 2012 | 0.41555277957300302 | 0.57223004571068981 | 0.49179824162562435 | 0.41916063572228934 | 
```