# 2015 Federal Grants Data As of June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-federal-grants-data-as-of-june-30-2015) |
| Metadata | [Link](https://data.mo.gov/api/views/55pd-epiy) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/55pd-epiy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/55pd-epiy/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 55pd-epiy |
| Name | 2015 Federal Grants Data As of June 30, 2015 |
| Category | Government Administration |
| Created | 2015-07-02T15:09:33Z |
| Publication Date | 2015-07-02T15:11:04Z |

## Description

The data provided here details the State of Missouri's Federal Grants Data as of June 30, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | time           | fiscal_year                       | Fiscal Year                       | number    | text        |
| Yes      | series tag     | agency_name                       | Agency Name                       | text      | text        |
| Yes      | series tag     | federal_agency_name               | Federal Agency Name               | text      | text        |
| Yes      | series tag     | grant_name                        | Grant Name                        | text      | text        |
| Yes      | series tag     | grant_purpose                     | Grant Purpose                     | text      | text        |
| Yes      | numeric metric | received_amount                   | Received Amount                   | number    | number      |
| Yes      | series tag     | name_of_agency_receiving_transfer | Name of Agency Receiving Transfer | text      | text        |
| Yes      | series tag     | transfer_purpose                  | Transfer Purpose                  | text      | text        |
| Yes      | series tag     | statistics                        | Statistics                        | text      | text        |
| Yes      | numeric metric | transfer_amount                   | Transfer Amount                   | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:55pd-epiy d:2015-01-01T00:00:00.000Z t:federal_agency_name="NATIONAL FOUNDATION OF ARTS AND HUMANITIES" t:grant_name="GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES" t:grant_purpose="THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION." t:agency_name="OFFICE OF SECRETARY OF STATE" m:received_amount=1138697.94

series e:55pd-epiy d:2015-01-01T00:00:00.000Z t:federal_agency_name="NATIONAL FOUNDATION OF ARTS AND HUMANITIES" t:grant_name="GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES" t:name_of_agency_receiving_transfer="MENTAL HEALTH" t:transfer_purpose="TO MAINTAIN LIBRARIAN411.ORG AND PROVIDE AWARENESS KITS FOR USE BY PUBLIC LIBRARIES." t:grant_purpose="THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION." t:agency_name="OFFICE OF SECRETARY OF STATE" m:transfer_amount=8770.5

series e:55pd-epiy d:2015-01-01T00:00:00.000Z t:federal_agency_name="NATIONAL FOUNDATION OF ARTS AND HUMANITIES" t:grant_name="GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES" t:grant_purpose="THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION." t:agency_name="OFFICE OF SECRETARY OF STATE" m:received_amount=1330690.67
```

## Meta Commands

```ls
metric m:received_amount p:double l:"Received Amount" t:dataTypeName=number

metric m:transfer_amount p:double l:"Transfer Amount" t:dataTypeName=number

entity e:55pd-epiy l:"2015 Federal Grants Data As of June 30, 2015" t:url=https://data.mo.gov/api/views/55pd-epiy

property e:55pd-epiy t:meta.view v:id=55pd-epiy v:category="Government Administration" v:averageRating=0 v:name="2015 Federal Grants Data As of June 30, 2015"

property e:55pd-epiy t:meta.view.license v:name="Public Domain"

property e:55pd-epiy t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:55pd-epiy t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| fiscal_year | agency_name                  | federal_agency_name                        | grant_name                                              | grant_purpose                                                                                                                                          | received_amount | name_of_agency_receiving_transfer | transfer_purpose                                                                     | statistics | transfer_amount | 
| =========== | ============================ | ========================================== | ======================================================= | ====================================================================================================================================================== | =============== | ================================= | ==================================================================================== | ========== | =============== | 
| 2015        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES         | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         | 1138697.94      |                                   |                                                                                      |            |                 | 
| 2015        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES         | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         |                 | MENTAL HEALTH                     | TO MAINTAIN LIBRARIAN411.ORG AND PROVIDE AWARENESS KITS FOR USE BY PUBLIC LIBRARIES. |            | 8770.50         | 
| 2015        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES         | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         | 1330690.67      |                                   |                                                                                      |            |                 | 
| 2015        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES         | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         |                 | MENTAL HEALTH                     | TO MAINTAIN LIBRARIAN411.ORG AND PROVIDE AWARENESS KITS FOR USE BY PUBLIC LIBRARIES. |            | 19404.00        | 
| 2015        | OFFICE OF ATTORNEY GENERAL   | US DEPARTMENT OF HEALTH AND HUMAN SERVICES | STATE MEDICAID FRAUD CONTROL UNIT GRANT PROGRAM         | TO INVESTIGATE AND PROSECUTE MEDICAID FRAUD                                                                                                            | 1612770.00      |                                   |                                                                                      |            |                 | 
| 2015        | OFFICE OF ADMINISTRATION     | US DEPARTMENT OF COMMERCE                  | STATE BROADBAND DATA AND DEVELOPMENT GRANT              | PUBLISH BROADBAND MAPS, PROVIDE TECHNICAL ASSISTANCE, ESTABLISH REGIONAL PLANNING TEAMS AND DEVELOP STRATEGIC BROADBAND OUTCOMES AND OTHER ACTIVITIES. | 835520.67       |                                   |                                                                                      |            |                 | 
| 2015        | CONSERVATION                 | US DEPARTMENT OF AGRICULTURE               | REIMBURSEMENT OF TSP SUPPORT FOR FARM BILL PROGRAMS     | PROVIDE TECHNICAL ASSISTANCE TO LANDOWNERS FOR PLANNED CONSERVATION PRACTICES                                                                          | 312705.00       |                                   |                                                                                      |            |                 | 
| 2015        | CONSERVATION                 | US DEPARTMENT OF THE INTERIOR              | LONG TERM RESOURCE MONITORING                           | RESOURCE MONITORING FOR THE UPPER MISSISSIPPI RIVER SYSTEM                                                                                             | 369568.20       |                                   |                                                                                      |            |                 | 
| 2015        | CONSERVATION                 | US DEPARTMENT OF THE INTERIOR              | LOWER OSAGE RIVER HABITAT AND FISH COMMUNITY EVALUATION | LOWER OSAGE RIVER HABITAT AND FISH COMMUNITY EVALUATION                                                                                                | 79029.62        |                                   |                                                                                      |            |                 | 
| 2015        | CONSERVATION                 | US DEPARTMENT OF THE INTERIOR              | FY15 AQUATIC RESOURCE EDUCATION                         | AQUATIC RESOURCE EDUCATION PROGRAM                                                                                                                     | 630167.24       |                                   |                                                                                      |            |                 | 
```