# Anticipated RFP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/anticipated-rfp) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/p8e4-uwuv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/p8e4-uwuv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/p8e4-uwuv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | p8e4-uwuv |
| Name | Anticipated RFP |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, rfp |
| Created | 2015-02-17T22:17:26Z |
| Publication Date | 2015-02-17T22:20:33Z |

## Description

List of upcoming Requests for Proposals

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | department                             | Department                             | text      | text        |
| Yes      | series tag     | services                               | Services                               | text      | text        |
| Yes      | numeric metric | estimated_cost_of_service_per_contract | Estimated Cost of Service per Contract | money     | text        |
| Yes      | numeric metric | anticipated_number_of_contracts        | Anticipated number of Contracts        | number    | text        |
| Yes      | time           | data_as_of_date                        | Data as of Date                        | text      | text        |
```

## Time Field

```ls
Value = data_as_of_date
Format & Zone = MM/dd/yyyy
```

## Data Commands

```ls
series e:p8e4-uwuv d:2014-12-01T00:00:00.000Z t:services="AutoCAD/Revit Consulting, Customization and Training Services" t:department="Architecture and Engineering" m:anticipated_number_of_contracts=1 m:estimated_cost_of_service_per_contract=1000000
```

## Meta Commands

```ls
metric m:estimated_cost_of_service_per_contract p:long l:"Estimated Cost of Service per Contract" t:dataTypeName=money

metric m:anticipated_number_of_contracts p:integer l:"Anticipated number of Contracts" t:dataTypeName=number

entity e:p8e4-uwuv l:"Anticipated RFP" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/p8e4-uwuv

property e:p8e4-uwuv t:meta.view v:id=p8e4-uwuv v:category=Education v:averageRating=0 v:name="Anticipated RFP" v:attribution="School Construction Authority (SCA)"

property e:p8e4-uwuv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:p8e4-uwuv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| department                   | services                                                      | estimated_cost_of_service_per_contract | anticipated_number_of_contracts | data_as_of_date | 
| ============================ | ============================================================= | ====================================== | =============================== | =============== | 
| Architecture and Engineering | AutoCAD/Revit Consulting, Customization and Training Services | $1,000,000                             | 1                               | 12/1/2014       | 
```