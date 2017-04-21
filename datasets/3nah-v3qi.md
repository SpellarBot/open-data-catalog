# Report Card 3g Resident Sentiment Jobs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3g-resident-sentiment-jobs-5610d) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3nah-v3qi) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3nah-v3qi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3nah-v3qi/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3nah-v3qi |
| Name | Report Card 3g Resident Sentiment Jobs |
| Created | 2012-11-19T01:59:37Z |
| Publication Date | 2012-11-19T02:00:12Z |

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
series e:3nah-v3qi d:2005-01-01T00:00:00.000Z m:kauai=0.7175066632539088 m:oahu=0.7183750124263869 m:maui_county=0.7240299685703832 m:hawaii_island=0.6004248999459071

series e:3nah-v3qi d:2006-01-01T00:00:00.000Z m:kauai=0.7285164014138272 m:oahu=0.6710925069232837 m:maui_county=0.7290411369781887 m:hawaii_island=0.6383316364811477

series e:3nah-v3qi d:2009-01-01T00:00:00.000Z m:kauai=0.825376248526154 m:oahu=0.736146853979284 m:maui_county=0.845519482200392 m:hawaii_island=0.773603017331282
```

## Meta Commands

```ls
metric m:oahu p:decimal l:Oahu t:dataTypeName=number

metric m:maui_county p:decimal l:"Maui County" t:dataTypeName=number

metric m:kauai p:decimal l:Kauai t:dataTypeName=number

metric m:hawaii_island p:decimal l:"Hawaii Island" t:dataTypeName=number

entity e:3nah-v3qi l:"Report Card 3g Resident Sentiment Jobs" t:url=https://data.hawaii.gov/api/views/3nah-v3qi

property e:3nah-v3qi t:meta.view v:id=3nah-v3qi v:averageRating=0 v:name="Report Card 3g Resident Sentiment Jobs"

property e:3nah-v3qi t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:3nah-v3qi t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui_county         | kauai               | hawaii_island       | 
| ==== | =================== | =================== | =================== | =================== | 
| 2005 | 0.71837501242638691 | 0.72402996857038315 | 0.71750666325390877 | 0.60042489994590709 | 
| 2006 | 0.6710925069232837  | 0.72904113697818873 | 0.72851640141382723 | 0.63833163648114766 | 
| 2009 | 0.73614685397928403 | 0.84551948220039197 | 0.82537624852615399 | 0.77360301733128201 | 
| 2010 | 0.66182799438327999 | 0.81355591006313199 | 0.71282805686065598 | 0.73562145535279999 | 
| 2012 | 0.73                | 0.79                | 0.66                | 0.65                | 
```