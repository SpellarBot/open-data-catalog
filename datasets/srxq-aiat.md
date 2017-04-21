# PED_NewCommercialPermitsIssued

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ped-newcommercialpermitsissued) |
| Metadata | [Link](https://data.srcity.org/api/views/srxq-aiat) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/srxq-aiat/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/srxq-aiat/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | srxq-aiat |
| Name | PED_NewCommercialPermitsIssued |
| Created | 2017-01-23T14:07:47Z |
| Publication Date | 2017-01-23T16:05:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                        | Data Type     | Render Type   |
| ======== | ============== | ===================== | =========================== | ============= | ============= |
| Yes      | series tag     | goaltype              | GoalType                    | text          | text          |
| Yes      | series tag     | measure               | Measure                     | text          | text          |
| No       |                | year                  | Year                        | number        | number        |
| Yes      | series tag     | type                  | Type                        | text          | text          |
| Yes      | time           | date                  | Date                        | calendar_date | calendar_date |
| Yes      | numeric metric | totalnewsquarefootage | TotalNewSquareFootageIssued | number        | number        |
| Yes      | numeric metric | noofpermits           | NoOfPermits                 | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:srxq-aiat d:2015-07-08T00:00:00.000Z t:measure=NewCommercialSqrFtIssued t:type=daily t:goaltype=Prevailing m:totalnewsquarefootage=1463 m:noofpermits=3

series e:srxq-aiat d:2016-08-01T00:00:00.000Z t:measure=NewCommercialSqrFtIssued t:type=monthly t:goaltype=Prevailing m:totalnewsquarefootage=67829 m:noofpermits=38

series e:srxq-aiat d:2015-11-09T00:00:00.000Z t:measure=NewCommercialSqrFtIssued t:type=daily t:goaltype=Prevailing m:totalnewsquarefootage=13542 m:noofpermits=3
```

## Meta Commands

```ls
metric m:totalnewsquarefootage p:integer l:TotalNewSquareFootageIssued t:dataTypeName=number

metric m:noofpermits p:integer l:NoOfPermits t:dataTypeName=number

entity e:srxq-aiat l:PED_NewCommercialPermitsIssued t:url=https://data.srcity.org/api/views/srxq-aiat

property e:srxq-aiat t:meta.view v:id=srxq-aiat v:averageRating=0 v:name=PED_NewCommercialPermitsIssued

property e:srxq-aiat t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:srxq-aiat t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```

## Top Records

```ls
| goaltype   | measure                  | year | type    | date                | totalnewsquarefootage | noofpermits | 
| ========== | ======================== | ==== | ======= | =================== | ===================== | =========== | 
| Prevailing | NewCommercialSqrFtIssued | 2015 | daily   | 2015-07-08T00:00:00 | 1463                  | 3           | 
| Prevailing | NewCommercialSqrFtIssued | 2016 | monthly | 2016-08-01T00:00:00 | 67829                 | 38          | 
| Prevailing | NewCommercialSqrFtIssued | 2015 | daily   | 2015-11-09T00:00:00 | 13542                 | 3           | 
| Prevailing | NewCommercialSqrFtIssued | 2017 | daily   | 2017-01-17T00:00:00 | 1150                  | 3           | 
| Prevailing | NewCommercialSqrFtIssued | 2016 | daily   | 2016-02-18T00:00:00 | 0                     | 2           | 
| Prevailing | NewCommercialSqrFtIssued | 2016 | daily   | 2016-07-27T00:00:00 | 4900                  | 1           | 
| Prevailing | NewCommercialSqrFtIssued | 2016 | daily   | 2016-07-14T00:00:00 | 1457                  | 2           | 
| Prevailing | NewCommercialSqrFtIssued | 2016 | daily   | 2016-10-19T00:00:00 | 1716                  | 3           | 
| Prevailing | NewCommercialSqrFtIssued | 2016 | daily   | 2016-05-24T00:00:00 | 0                     | 1           | 
| Prevailing | NewCommercialSqrFtIssued | 2016 | daily   | 2016-08-10T00:00:00 | 63                    | 1           | 
```