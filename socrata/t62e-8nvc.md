# Beach Swim Advisories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/beach-swim-advisories) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/t62e-8nvc) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/t62e-8nvc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/t62e-8nvc/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | t62e-8nvc |
| Name | Beach Swim Advisories |
| Category | Parks & Recreation |
| Tags | beaches, parks, chicago park district, open spaces, parks & recreation, recreation, water |
| Created | 2016-05-27T20:34:04Z |
| Publication Date | 2016-06-10T15:22:19Z |

## Description

The Chicago Park District issues swim advisories at beaches along Chicago's Lake Michigan lakefront based on predicted E. coli levels.  This dataset shows the predictions and whether a swim advisory was issued due to the predicted E. coli level being at least 235 Colony Forming Units (CFU) per 100 ml of water.

The data used to make the predictions can be found in https://data.cityofchicago.org/d/qmqz-2xku and https://data.cityofchicago.org/d/k7hf-8y75. The measured E. coli levels determined later can be found in https://data.cityofchicago.org/d/2ivx-z93u.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | beach_name      | Beach Name      | text          | text          |
| Yes      | time           | date            | Date            | calendar_date | calendar_date |
| Yes      | numeric metric | predicted_level | Predicted Level | number        | number        |
| Yes      | numeric metric | probability     | Probability     | number        | number        |
| Yes      | series tag     | swim_advisory   | Swim Advisory   | text          | text          |
| Yes      | series tag     | recordid        | RecordID        | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:t62e-8nvc d:2016-06-04T00:00:00.000Z t:recordid=Calumet20160604 t:swim_advisory=N t:beach_name=Calumet m:probability=0.107 m:predicted_level=33.8

series e:t62e-8nvc d:2016-06-04T00:00:00.000Z t:recordid=63rdStreet20160604 t:swim_advisory=N t:beach_name=63rdStreet m:probability=0.106 m:predicted_level=33.6

series e:t62e-8nvc d:2016-06-04T00:00:00.000Z t:recordid=OakStreet20160604 t:swim_advisory=N t:beach_name=OakStreet m:probability=0.018 m:predicted_level=18.9
```

## Meta Commands

```ls
metric m:predicted_level p:float l:"Predicted Level" d:"Predicted E. coli level in Colony Forming Units (CFU) per 100 ml of water" t:dataTypeName=number

metric m:probability p:float l:Probability d:"Probability of the E. coli level being at least 235 Colony Forming Units (CFU) per 100 ml of water" t:dataTypeName=number

entity e:t62e-8nvc l:"Beach Swim Advisories" t:url=https://data.cityofchicago.org/api/views/t62e-8nvc

property e:t62e-8nvc t:meta.view v:id=t62e-8nvc v:category="Parks & Recreation" v:averageRating=0 v:name="Beach Swim Advisories"

property e:t62e-8nvc t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:t62e-8nvc t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| beach_name | date                | predicted_level | probability | swim_advisory | recordid           | 
| ========== | =================== | =============== | =========== | ============= | ================== | 
| Calumet    | 2016-06-04T00:00:00 | 33.8            | 0.107       | N             | Calumet20160604    | 
| 63rdStreet | 2016-06-04T00:00:00 | 33.6            | 0.106       | N             | 63rdStreet20160604 | 
| OakStreet  | 2016-06-04T00:00:00 | 18.9            | 0.018       | N             | OakStreet20160604  | 
| Foster     | 2016-06-04T00:00:00 | 14.9            | 0.021       | N             | Foster20160604     | 
| Montrose   | 2016-06-04T00:00:00 | 101.5           | 0.277       | N             | Montrose20160604   | 
| Osterman   | 2016-06-04T00:00:00 | 7.6             | 0.004       | N             | Osterman20160604   | 
| Rainbow    | 2016-06-04T00:00:00 | 32.5            | 0.078       | N             | Rainbow20160604    | 
| Leone      | 2016-06-04T00:00:00 | 9.6             | 0.006       | N             | Leone20160604      | 
| Ohio       | 2016-06-04T00:00:00 | 37.0            | 0.082       | N             | Ohio20160604       | 
| Calumet    | 2016-06-06T00:00:00 | 51.3            | 0.164       | N             | Calumet20160606    | 
```