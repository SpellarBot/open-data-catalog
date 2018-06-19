# Report Card 3e Resident Sentiment Quality of Life

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3e-resident-sentiment-quality-of-life-6b311) |
| Metadata | [Link](https://data.hawaii.gov/api/views/asy7-es7y) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/asy7-es7y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/asy7-es7y/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | asy7-es7y |
| Name | Report Card 3e Resident Sentiment Quality of Life |
| Created | 2012-11-19T01:43:34Z |
| Publication Date | 2012-11-19T01:44:19Z |

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
series e:asy7-es7y d:2005-01-01T00:00:00.000Z m:kauai=0.4970077333894108 m:oahu=0.5255251793721967 m:maui_county=0.442994100814845 m:hawaii_island=0.42121161841152444

series e:asy7-es7y d:2006-01-01T00:00:00.000Z m:kauai=0.3998850380599975 m:oahu=0.47299202016269115 m:maui_county=0.33356046995154937 m:hawaii_island=0.4722787586519994

series e:asy7-es7y d:2007-01-01T00:00:00.000Z m:kauai=0.3334570903771371 m:oahu=0.4600462274511121 m:maui_county=0.4049017930078276 m:hawaii_island=0.3708777179550467
```

## Meta Commands

```ls
metric m:oahu p:decimal l:Oahu t:dataTypeName=number

metric m:maui_county p:decimal l:"Maui County" t:dataTypeName=number

metric m:kauai p:decimal l:Kauai t:dataTypeName=number

metric m:hawaii_island p:decimal l:"Hawaii Island" t:dataTypeName=number

entity e:asy7-es7y l:"Report Card 3e Resident Sentiment Quality of Life" t:url=https://data.hawaii.gov/api/views/asy7-es7y

property e:asy7-es7y t:meta.view v:id=asy7-es7y v:averageRating=0 v:name="Report Card 3e Resident Sentiment Quality of Life"

property e:asy7-es7y t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:asy7-es7y t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui_county         | kauai               | hawaii_island       | 
| ==== | =================== | =================== | =================== | =================== | 
| 2005 | 0.52552517937219667 | 0.44299410081484503 | 0.49700773338941079 | 0.42121161841152444 | 
| 2006 | 0.47299202016269115 | 0.33356046995154937 | 0.39988503805999748 | 0.47227875865199942 | 
| 2007 | 0.46004622745111212 | 0.40490179300782758 | 0.33345709037713711 | 0.3708777179550467  | 
| 2012 | 0.69098329170751305 | 0.76758702829104297 | 0.61154157540546195 | 0.62491025594531202 | 
```