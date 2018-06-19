# Community Development Block Grant (CDBG) Contracts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-development-block-grant-cdbg-contracts) |
| Metadata | [Link](https://data.ny.gov/api/views/n9bu-8eic) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/n9bu-8eic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/n9bu-8eic/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | n9bu-8eic |
| Name | Community Development Block Grant (CDBG) Contracts |
| Attribution | NYS Homes & Community Renewal |
| Category | Economic Development |
| Tags | grants, housing, construction, infrastructure, economic development, jobs, municipality, cdbg, small cities |
| Created | 2016-05-17T21:03:15Z |
| Publication Date | 2016-05-31T17:01:39Z |

## Description

Listing of open and closed CDBG contracts between NYS Homes & Community Renewal?s Office of Community Renewal and grant recipients. Details include contract number, project name, project type, activity, contract amount, grant recipient, county, municipality and contract status, for the Community Development Block Grant (CDBG) Program.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | project_number  | Project Number  | text      | text        |
| Yes      | time           | project_year    | Project Year    | text      | number      |
| Yes      | series tag     | project_name    | Project Name    | text      | text        |
| Yes      | series tag     | project_type    | Project Type    | text      | text        |
| Yes      | numeric metric | contract_amount | Contract Amount | money     | money       |
| Yes      | series tag     | county          | County          | text      | text        |
| Yes      | series tag     | grant_recipient | Grant Recipient | text      | text        |
| Yes      | series tag     | recipient_type  | Recipient Type  | text      | text        |
| Yes      | series tag     | current_status  | Current Status  | text      | text        |
```

## Time Field

```ls
Value = project_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:n9bu-8eic d:2006-01-01T00:00:00.000Z t:project_name="NYS Rural Housing Coalition" t:county=Albany t:project_number=9994TA196-06 t:recipient_type=N/A t:current_status=Closed t:grant_recipient="NYS Rural Housing Coalition" t:project_type="Technical Assistance" m:contract_amount=30000

series e:n9bu-8eic d:2006-01-01T00:00:00.000Z t:project_name="Town of Schuyler" t:county=Herkimer t:project_number=1045TA208-06 t:recipient_type=Town t:current_status=Closed t:grant_recipient=Schuyler t:project_type="Technical Assistance" m:contract_amount=12000

series e:n9bu-8eic d:2006-01-01T00:00:00.000Z t:project_name="Village of Schoharie" t:county=Schoharie t:project_number=1041ME63-06 t:recipient_type=Village t:current_status=Closed t:grant_recipient=Schoharie t:project_type="Economic Development" m:contract_amount=200000
```

## Meta Commands

```ls
metric m:contract_amount p:integer l:"Contract Amount" d:"Indicates dollar amount of the contract awarded to the recipient organization." t:dataTypeName=money

entity e:n9bu-8eic l:"Community Development Block Grant (CDBG) Contracts" t:attribution="NYS Homes & Community Renewal" t:url=https://data.ny.gov/api/views/n9bu-8eic

property e:n9bu-8eic t:meta.view v:id=n9bu-8eic v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/Programs/NYS-CDBG/ v:averageRating=0 v:name="Community Development Block Grant (CDBG) Contracts" v:attribution="NYS Homes & Community Renewal"

property e:n9bu-8eic t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:n9bu-8eic t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| project_number | project_year | project_name                | project_type         | contract_amount | county      | grant_recipient             | recipient_type | current_status | 
| ============== | ============ | =========================== | ==================== | =============== | =========== | =========================== | ============== | ============== | 
| 9994TA196-06   | 2006         | NYS Rural Housing Coalition | Technical Assistance | 30000           | Albany      | NYS Rural Housing Coalition | N/A            | Closed         | 
| 1045TA208-06   | 2006         | Town of Schuyler            | Technical Assistance | 12000           | Herkimer    | Schuyler                    | Town           | Closed         | 
| 1041ME63-06    | 2006         | Village of Schoharie        | Economic Development | 200000          | Schoharie   | Schoharie                   | Village        | Closed         | 
| 975HO74-06     | 2006         | Rensselaer County           | Home Ownership       | 300000          | Rensselaer  | Rensselaer                  | County         | Closed         | 
| 988PW129-06    | 2006         | Town of Ripley              | Public Water         | 400000          | Chautauqua  | Ripley                      | Town           | Closed         | 
| 1036HR76-06    | 2006         | Town of Schaghticoke        | Housing Rehab        | 400000          | Rensselaer  | Schaghticoke                | Town           | Closed         | 
| 975HR71-06     | 2006         | Rensselaer County           | Housing Rehab        | 300000          | Rensselaer  | Rensselaer                  | County         | Closed         | 
| 987PW121-06    | 2006         | Town of Ridgeway            | Public Water         | 400000          | Orleans     | Ridgeway                    | Town           | Closed         | 
| 974PF106-06    | 2006         | City of Rensselaer          | Public Facilities    | 400000          | Rensselaer  | Rensselaer                  | City           | Closed         | 
| 656PR67-15     | 2015         | Village of Little Valley    | Public Sewer         | 600000          | Cattaraugus | Little Valley               | Village        | Open           | 
```