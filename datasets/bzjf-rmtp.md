# Current RFP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-rfp) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bzjf-rmtp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bzjf-rmtp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bzjf-rmtp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bzjf-rmtp |
| Name | Current RFP |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, rfp |
| Created | 2015-01-28T21:05:11Z |
| Publication Date | 2015-01-28T21:10:21Z |

## Description

List of active Requests For Proposals

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | series tag     | solicitation_number                     | Solicitation Number                     | text      | text        |
| Yes      | time           | due_date                                | Due Date                                | text      | text        |
| Yes      | series tag     | department                              | Department                              | text      | text        |
| Yes      | series tag     | services                                | Services                                | text      | text        |
| Yes      | numeric metric | not_to_exceed_award_amount_per_contract | Not-To-Exceed Award Amount per Contract | money     | text        |
| Yes      | numeric metric | number_of_contract_s                    | Number of Contract (s)                  | number    | text        |
| Yes      | series tag     | assigned_contract_negotiator            | Assigned Contract Negotiator            | text      | text        |
| Yes      | series tag     | assigned_contract_negotiator_email      | Assigned Contract Negotiator Email      | text      | text        |
| No       |                | data_as_of_date                         | Data as of Date                         | text      | text        |
```

## Time Field

```ls
Value = due_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = data_as_of_date
```

## Data Commands

```ls
series e:bzjf-rmtp d:2014-12-30T00:00:00.000Z t:services="Services in Connection with Building Maintenance" t:assigned_contract_negotiator="Sal DeVita" t:assigned_contract_negotiator_email=sdevita@nycsca.org t:department="Administrative Services (ADMIN)" t:solicitation_number=15-00031R m:not_to_exceed_award_amount_per_contract=4800000 m:number_of_contract_s=1
```

## Meta Commands

```ls
metric m:not_to_exceed_award_amount_per_contract p:long l:"Not-To-Exceed Award Amount per Contract" t:dataTypeName=money

metric m:number_of_contract_s p:integer l:"Number of Contract (s)" t:dataTypeName=number

entity e:bzjf-rmtp l:"Current RFP" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/bzjf-rmtp

property e:bzjf-rmtp t:meta.view v:id=bzjf-rmtp v:category=Education v:averageRating=0 v:name="Current RFP" v:attribution="School Construction Authority (SCA)"

property e:bzjf-rmtp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bzjf-rmtp t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| solicitation_number | due_date   | department                      | services                                         | not_to_exceed_award_amount_per_contract | number_of_contract_s | assigned_contract_negotiator | assigned_contract_negotiator_email | data_as_of_date | 
| =================== | ========== | =============================== | ================================================ | ======================================= | ==================== | ============================ | ================================== | =============== | 
| 15-00031R           | 12/30/2014 | Administrative Services (ADMIN) | Services in Connection with Building Maintenance | $4,800,000                              | 1                    | Sal DeVita                   | sdevita@nycsca.org                 | 12/1/2014       | 
```