# Sister Cities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sister-cities-74503) |
| Metadata | [Link](https://data.honolulu.gov/api/views/pvti-pwka) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/pvti-pwka/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/pvti-pwka/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | pvti-pwka |
| Name | Sister Cities |
| Created | 2012-06-23T01:58:59Z |
| Publication Date | 2012-06-23T02:04:35Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | sistercity              | SisterCity              | text          | text          |
| Yes      | time        | dateofcouncilresolution | DateOfCouncilResolution | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dateofcouncilresolution
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pvti-pwka d:1995-11-03T00:00:00.000Z t:sistercity="Baguio, Philippines" m:row_number.pvti-pwka=1

series e:pvti-pwka d:1998-08-05T00:00:00.000Z t:sistercity="Baku, Ajerbaijan" m:row_number.pvti-pwka=2

series e:pvti-pwka d:1970-01-20T00:00:00.000Z t:sistercity="Bombay, India" m:row_number.pvti-pwka=3
```

## Meta Commands

```ls
metric m:row_number.pvti-pwka p:long l:"Row Number"

entity e:pvti-pwka l:"Sister Cities" t:url=https://data.honolulu.gov/api/views/pvti-pwka

property e:pvti-pwka t:meta.view v:id=pvti-pwka v:averageRating=0 v:name="Sister Cities"

property e:pvti-pwka t:meta.view.owner v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"

property e:pvti-pwka t:meta.view.tableauthor v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"
```

## Top Records

```ls
| sistercity                 | dateofcouncilresolution | 
| ========================== | ======================= | 
| Baguio, Philippines        | 1995-11-03T00:00:00     | 
| Baku, Ajerbaijan           | 1998-08-05T00:00:00     | 
| Bombay, India              | 1970-01-20T00:00:00     | 
| Bruyeres, France           | 1960-11-01T00:00:00     | 
| Caracas, Venezuela         | 1999-01-27T00:00:00     | 
| Cebu, Philippines          | 1990-12-06T00:00:00     | 
| Funchal, Madeira, Portugal | 1979-09-19T00:00:00     | 
| Hainan Island, China       | 1985-02-27T00:00:00     | 
| Hiroshima, Japan           | 1959-05-19T00:00:00     | 
| Hue, Vietnam               | 1995-11-03T00:00:00     | 
```