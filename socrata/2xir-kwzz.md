# DOHMH Beach Water Quality Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dohmh-beach-water-quality-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2xir-kwzz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2xir-kwzz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2xir-kwzz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2xir-kwzz |
| Name | DOHMH Beach Water Quality Data |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | health, beach, water quality, water |
| Created | 2016-06-01T18:54:05Z |
| Publication Date | 2016-06-21T16:02:38Z |

## Description

Water quality sample results collected by the Department of Health and Mental Hygiene at all New York City Beaches. These water quality results are used by the Department to determine the status (open, advisory, closed) of Beaches.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | sample_id           | Sample ID           | text          | text          |
| Yes      | time           | sample_date         | Sample Date         | calendar_date | calendar_date |
| Yes      | series tag     | beach_name          | Beach Name          | text          | text          |
| Yes      | series tag     | sample_location     | Sample Location     | text          | text          |
| Yes      | numeric metric | enterococci_results | Enterococci Results | number        | number        |
| Yes      | series tag     | units_or_notes      | Units or Notes      | text          | text          |
```

## Time Field

```ls
Value = sample_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2xir-kwzz d:2014-05-05T00:00:00.000Z t:units_or_notes="MPN/100 ml" t:sample_location=Center t:sample_id=050514CP13 t:beach_name="MIDLAND BEACH" m:enterococci_results=20

series e:2xir-kwzz d:2008-07-28T00:00:00.000Z t:units_or_notes="MPN/100 ml" t:sample_location=Right t:sample_id=072808BH09 t:beach_name="MIDLAND BEACH" m:enterococci_results=28

series e:2xir-kwzz d:2014-05-12T00:00:00.000Z t:units_or_notes="MPN/100 ml" t:sample_location=Right t:sample_id=051214CP36 t:beach_name="SOUTH BEACH" m:enterococci_results=4
```

## Meta Commands

```ls
metric m:enterococci_results p:float l:"Enterococci Results" t:dataTypeName=number

entity e:2xir-kwzz l:"DOHMH Beach Water Quality Data" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/2xir-kwzz

property e:2xir-kwzz t:meta.view v:id=2xir-kwzz v:category=Health v:averageRating=0 v:name="DOHMH Beach Water Quality Data" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:2xir-kwzz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2xir-kwzz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| sample_id  | sample_date         | beach_name      | sample_location | enterococci_results | units_or_notes               | 
| ========== | =================== | =============== | =============== | =================== | ============================ | 
| 050514CP13 | 2014-05-05T00:00:00 | MIDLAND BEACH   | Center          | 20.00               | MPN/100 ml                   | 
| 062011GR04 | 2011-06-20T00:00:00 | MANHATTAN BEACH | Left            |                     | Result below detection limit | 
| 072808BH09 | 2008-07-28T00:00:00 | MIDLAND BEACH   | Right           | 28.00               | MPN/100 ml                   | 
| 051214CP36 | 2014-05-12T00:00:00 | SOUTH BEACH     | Right           | 4.00                | MPN/100 ml                   | 
| 081511KB07 | 2011-08-15T00:00:00 | CEDAR GROVE     | Left            | 360.00              | MPN/100 ml                   | 
| 062909KB01 | 2009-06-29T00:00:00 | MANHATTAN BEACH | Left            | 8.00                | MPN/100 ml                   | 
| 082112KB07 | 2012-08-21T00:00:00 | CEDAR GROVE     | Left            | 20.00               | MPN/100 ml                   | 
| 072015GR06 | 2015-07-20T00:00:00 | MANHATTAN BEACH | Right           |                     | Result below detection limit | 
| 082613CP16 | 2013-08-26T00:00:00 | SOUTH BEACH     | Center          | 12.00               | MPN/100 ml                   | 
| 081709KB07 | 2009-08-17T00:00:00 | MIDLAND BEACH   | Left            | 4.00                | MPN/100 ml                   | 
```