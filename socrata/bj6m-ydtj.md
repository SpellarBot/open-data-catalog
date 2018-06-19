# MWBE Waivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mwbe-waivers-4b766) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bj6m-ydtj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bj6m-ydtj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bj6m-ydtj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bj6m-ydtj |
| Name | MWBE Waivers |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | mwbe waivers |
| Created | 2014-10-26T01:34:09Z |
| Publication Date | 2014-10-26T01:34:55Z |

## Description

Summary of waivers of MWBE goals required by LL1

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | vendor                     | Vendor                     | text          | text          |
| Yes      | series tag     | waiver_partial_full        | Waiver (Partial/Full)      | text          | text          |
| Yes      | numeric metric | percentage_original        | Percentage Original        | number        | number        |
| Yes      | series tag     | percentage_after_waiver    | Percentage after waiver    | text          | text          |
| Yes      | time           | contract_registration_date | Contract Registration Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = contract_registration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bj6m-ydtj d:2013-07-05T00:00:00.000Z t:percentage_after_waiver=17 t:vendor="VERNON HILLS CONTRACTING CORP." t:waiver_partial_full=Partial m:percentage_original=31

series e:bj6m-ydtj d:2013-10-09T00:00:00.000Z t:percentage_after_waiver=11 t:vendor="A RUSSO WRECKING INC" t:waiver_partial_full=Partial m:percentage_original=16

series e:bj6m-ydtj d:2013-12-10T00:00:00.000Z t:percentage_after_waiver=3 t:vendor="A RUSSO WRECKING INC" t:waiver_partial_full=Partial m:percentage_original=10
```

## Meta Commands

```ls
metric m:percentage_original p:integer l:"Percentage Original" t:dataTypeName=number

entity e:bj6m-ydtj l:"MWBE Waivers" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/bj6m-ydtj

property e:bj6m-ydtj t:meta.view v:id=bj6m-ydtj v:category="City Government" v:averageRating=0 v:name="MWBE Waivers" v:attribution="Office of the Mayor (OTM)"

property e:bj6m-ydtj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bj6m-ydtj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| vendor                         | waiver_partial_full | percentage_original | percentage_after_waiver | contract_registration_date | 
| ============================== | =================== | =================== | ======================= | ========================== | 
| VERNON HILLS CONTRACTING CORP. | Partial             | 31                  | 17                      | 2013-07-05T00:00:00        | 
| A RUSSO WRECKING INC           | Partial             | 16                  | 11                      | 2013-10-09T00:00:00        | 
| A RUSSO WRECKING INC           | Partial             | 10                  | 3                       | 2013-12-10T00:00:00        | 
| HALCYON CONSTRUCTION CORP      | Partial             | 30                  | 12                      | 2013-07-11T00:00:00        | 
| EN-TECH CORP                   | Full                | 3                   | Full                    | 2013-07-11T00:00:00        | 
| NEDERMAN, LLC                  | Partial             | 10                  | 5                       | 2013-11-21T00:00:00        | 
```