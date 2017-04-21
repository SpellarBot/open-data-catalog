# Report Card 3h Resident Sentiment Treatment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3h-resident-sentiment-treatment-ba9f2) |
| Metadata | [Link](https://data.hawaii.gov/api/views/sudc-h239) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/sudc-h239/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/sudc-h239/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | sudc-h239 |
| Name | Report Card 3h Resident Sentiment Treatment |
| Created | 2012-11-19T02:03:59Z |
| Publication Date | 2012-11-19T02:04:29Z |

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
series e:sudc-h239 d:2005-01-01T00:00:00.000Z m:kauai=0.4742685795529252 m:oahu=0.3842605586389388 m:maui_county=0.42190058972222694 m:hawaii_island=0.44294569156955144

series e:sudc-h239 d:2006-01-01T00:00:00.000Z m:kauai=0.3763056087012812 m:oahu=0.4444086080685811 m:maui_county=0.45990094317385855 m:hawaii_island=0.5546885758359958

series e:sudc-h239 d:2009-01-01T00:00:00.000Z m:kauai=0.51 m:oahu=0.51 m:maui_county=0.44 m:hawaii_island=0.52
```

## Meta Commands

```ls
metric m:oahu p:decimal l:Oahu t:dataTypeName=number

metric m:maui_county p:decimal l:"Maui County" t:dataTypeName=number

metric m:kauai p:float l:Kauai t:dataTypeName=number

metric m:hawaii_island p:decimal l:"Hawaii Island" t:dataTypeName=number

entity e:sudc-h239 l:"Report Card 3h Resident Sentiment Treatment" t:url=https://data.hawaii.gov/api/views/sudc-h239

property e:sudc-h239 t:meta.view v:id=sudc-h239 v:averageRating=0 v:name="Report Card 3h Resident Sentiment Treatment"

property e:sudc-h239 t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:sudc-h239 t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui_county         | kauai               | hawaii_island       | 
| ==== | =================== | =================== | =================== | =================== | 
| 2005 | 0.38426055863893882 | 0.42190058972222694 | 0.47426857955292517 | 0.44294569156955144 | 
| 2006 | 0.44440860806858112 | 0.45990094317385855 | 0.37630560870128121 | 0.55468857583599585 | 
| 2009 | 0.51                | 0.44                | 0.51                | 0.52                | 
| 2010 | 0.48                | 0.48                | 0.45                | 0.53                | 
| 2012 | 0.59207689058163504 | 0.59843262978298195 | 0.46860978507084999 | 0.56661204891036399 | 
```