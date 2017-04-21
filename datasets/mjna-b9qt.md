# Report Card 3f Resident Sentiment Govt Promote

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3f-resident-sentiment-govt-promote-da41e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/mjna-b9qt) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/mjna-b9qt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/mjna-b9qt/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | mjna-b9qt |
| Name | Report Card 3f Resident Sentiment Govt Promote |
| Created | 2012-11-19T01:49:09Z |
| Publication Date | 2012-11-19T01:49:42Z |

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
series e:mjna-b9qt d:2005-01-01T00:00:00.000Z m:kauai=0.5829729980184845 m:oahu=0.6416405228539861 m:maui_county=0.5544221985037294 m:hawaii_island=0.5567314342389112

series e:mjna-b9qt d:2006-01-01T00:00:00.000Z m:kauai=0.555978012089302 m:oahu=0.6339005910675337 m:maui_county=0.6040272991743069 m:hawaii_island=0.6182277783413431

series e:mjna-b9qt d:2009-01-01T00:00:00.000Z m:kauai=0.411675735334243 m:oahu=0.595933757841949 m:maui_county=0.46 m:hawaii_island=0.39840165120863
```

## Meta Commands

```ls
metric m:oahu p:decimal l:Oahu t:dataTypeName=number

metric m:maui_county p:decimal l:"Maui County" t:dataTypeName=number

metric m:kauai p:decimal l:Kauai t:dataTypeName=number

metric m:hawaii_island p:decimal l:"Hawaii Island" t:dataTypeName=number

entity e:mjna-b9qt l:"Report Card 3f Resident Sentiment Govt Promote" t:url=https://data.hawaii.gov/api/views/mjna-b9qt

property e:mjna-b9qt t:meta.view v:id=mjna-b9qt v:averageRating=0 v:name="Report Card 3f Resident Sentiment Govt Promote"

property e:mjna-b9qt t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:mjna-b9qt t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui_county         | kauai               | hawaii_island       | 
| ==== | =================== | =================== | =================== | =================== | 
| 2005 | 0.64164052285398609 | 0.55442219850372942 | 0.58297299801848446 | 0.55673143423891125 | 
| 2006 | 0.63390059106753371 | 0.60402729917430686 | 0.55597801208930198 | 0.61822777834134313 | 
| 2009 | 0.59593375784194902 | 0.46                | 0.41167573533424301 | 0.39840165120863003 | 
| 2010 | 0.64662955010738199 | 0.56149819066432805 | 0.65328380158955002 | 0.57341422796924402 | 
| 2012 | 0.74018551443010105 | 0.73480139442729198 | 0.59504941174965997 | 0.60656246910333    | 
```