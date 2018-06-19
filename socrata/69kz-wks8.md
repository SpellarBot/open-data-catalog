# Report Card 3i Resident Sentiment Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3i-resident-sentiment-resources-8c1d5) |
| Metadata | [Link](https://data.hawaii.gov/api/views/69kz-wks8) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/69kz-wks8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/69kz-wks8/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 69kz-wks8 |
| Name | Report Card 3i Resident Sentiment Resources |
| Created | 2012-11-19T02:09:31Z |
| Publication Date | 2012-11-19T02:10:02Z |

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
series e:69kz-wks8 d:2005-01-01T00:00:00.000Z m:kauai=0.3513872741572606 m:oahu=0.3430250239986566 m:maui_county=0.25294141674548787 m:hawaii_island=0.30496474045536204

series e:69kz-wks8 d:2006-01-01T00:00:00.000Z m:kauai=0.2641552280879654 m:oahu=0.34857296113508385 m:maui_county=0.31372205529984715 m:hawaii_island=0.3915939122599473

series e:69kz-wks8 d:2009-01-01T00:00:00.000Z m:kauai=0.55 m:oahu=0.51 m:maui_county=0.45 m:hawaii_island=0.46
```

## Meta Commands

```ls
metric m:oahu p:decimal l:Oahu t:dataTypeName=number

metric m:maui_county p:decimal l:"Maui County" t:dataTypeName=number

metric m:kauai p:decimal l:Kauai t:dataTypeName=number

metric m:hawaii_island p:double l:"Hawaii Island" t:dataTypeName=number

entity e:69kz-wks8 l:"Report Card 3i Resident Sentiment Resources" t:url=https://data.hawaii.gov/api/views/69kz-wks8

property e:69kz-wks8 t:meta.view v:id=69kz-wks8 v:averageRating=0 v:name="Report Card 3i Resident Sentiment Resources"

property e:69kz-wks8 t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:69kz-wks8 t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui_county         | kauai               | hawaii_island       | 
| ==== | =================== | =================== | =================== | =================== | 
| 2005 | 0.34302502399865659 | 0.25294141674548787 | 0.35138727415726062 | 0.30496474045536204 | 
| 2006 | 0.34857296113508385 | 0.31372205529984715 | 0.26415522808796538 | 0.39159391225994727 | 
| 2009 | 0.51                | 0.45                | 0.55000000000000004 | 0.46                | 
| 2010 | 0.53                | 0.42                | 0.56999999999999995 | 0.52                | 
| 2012 | 0.67237341160375197 | 0.67621428060256406 | 0.57184759760766102 | 0.563164854499831   | 
```