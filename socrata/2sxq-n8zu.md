# Nowcast Predictions for Chikungunya Virus-Infected Travelers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nowcast-predictions-for-chikungunya-virus-infected-travelers-187b8) |
| Metadata | [Link](https://data.cdc.gov/api/views/2sxq-n8zu) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/2sxq-n8zu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/2sxq-n8zu/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 2sxq-n8zu |
| Name | Nowcast Predictions for Chikungunya Virus-Infected Travelers |
| Tags | chikungunya, americas, travelers, predictions |
| Created | 2014-09-05T17:47:35Z |
| Publication Date | 2015-08-10T15:54:41Z |

## Description

Interactive visualization: http://www.cdc.gov/chikungunya/modeling/index.html.This dataset contains monthly predictions for the spread of chikungunya virus transmission. A full description of the methods is available at: http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0104915.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | location             | location             | text          | text          |
| Yes      | time           | month                | month                | calendar_date | calendar_date |
| Yes      | numeric metric | pinfectedtravelerave | pInfectedTravelerAve | number        | number        |
| Yes      | numeric metric | infectedtravelermin  | pInfectedTravelerMin | number        | number        |
| Yes      | numeric metric | infectedtravelermax  | pInfectedTravelerMax | number        | number        |
| Yes      | numeric metric | localcases           | localcases           | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2sxq-n8zu d:2013-12-01T00:00:00.000Z t:location=Nassau m:pinfectedtravelerave=0.01 m:infectedtravelermin=0.01 m:localcases=0 m:infectedtravelermax=0.03

series e:2sxq-n8zu d:2013-12-01T00:00:00.000Z t:location=Annaba m:pinfectedtravelerave=0 m:infectedtravelermin=0 m:localcases=0 m:infectedtravelermax=0

series e:2sxq-n8zu d:2013-12-01T00:00:00.000Z t:location=Anapa m:pinfectedtravelerave=0 m:infectedtravelermin=0 m:localcases=0 m:infectedtravelermax=0
```

## Meta Commands

```ls
metric m:pinfectedtravelerave p:double l:pInfectedTravelerAve t:dataTypeName=number

metric m:infectedtravelermin p:double l:pInfectedTravelerMin d:"The 2.5th percentile (lower bound of the middle 95th percentile) of the distribution of pInfectedTraveler estimates." t:dataTypeName=number

metric m:infectedtravelermax p:double l:pInfectedTravelerMax d:"The 97.5th percentile (upper bound of the middle 95th percentile) of the distribution of pInfectedTraveler estimates." t:dataTypeName=number

metric m:localcases p:integer l:localcases d:"If cases were reported in that month in that location: 1, otherwise: 0" t:dataTypeName=number

entity e:2sxq-n8zu l:"Nowcast Predictions for Chikungunya Virus-Infected Travelers" t:url=https://data.cdc.gov/api/views/2sxq-n8zu

property e:2sxq-n8zu t:meta.view v:id=2sxq-n8zu v:averageRating=0 v:name="Nowcast Predictions for Chikungunya Virus-Infected Travelers"

property e:2sxq-n8zu t:meta.view.owner v:id=8dgr-8c6s v:screenName=Michael v:displayName=Michael

property e:2sxq-n8zu t:meta.view.tableauthor v:id=8dgr-8c6s v:screenName=Michael v:roleName=publisher v:displayName=Michael

property e:2sxq-n8zu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| location      | month               | pinfectedtravelerave | infectedtravelermin | infectedtravelermax | localcases | 
| ============= | =================== | ==================== | =================== | =================== | ========== | 
| Nassau        | 2013-12-01T00:00:00 | 0.01                 | 0.01                | 0.03                | 0          | 
| Annaba        | 2013-12-01T00:00:00 | 0                    | 0                   | 0                   | 0          | 
| Anapa         | 2013-12-01T00:00:00 | 0                    | 0                   | 0                   | 0          | 
| Allentown     | 2013-12-01T00:00:00 | 0                    | 0                   | 0                   | 0          | 
| Albuquerque   | 2013-12-01T00:00:00 | 0                    | 0                   | 0.01                | 0          | 
| Aberdeen      | 2013-12-01T00:00:00 | 0                    | 0                   | 0                   | 0          | 
| Atlantic City | 2013-12-01T00:00:00 | 0                    | 0                   | 0.01                | 0          | 
| Izmir         | 2013-12-01T00:00:00 | 0                    | 0                   | 0                   | 0          | 
| Buenos Aires  | 2013-12-01T00:00:00 | 0.01                 | 0                   | 0.02                | 0          | 
| Sochi         | 2013-12-01T00:00:00 | 0                    | 0                   | 0                   | 0          | 
```