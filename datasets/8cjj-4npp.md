# 2014 Federal Grants Data As of June 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-federal-grants-data-as-of-june-30-2014-2111a) |
| Metadata | [Link](https://data.mo.gov/api/views/8cjj-4npp) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/8cjj-4npp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/8cjj-4npp/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 8cjj-4npp |
| Name | 2014 Federal Grants Data As of June 30, 2014 |
| Category | Government Administration |
| Created | 2014-07-02T18:46:16Z |
| Publication Date | 2014-07-02T18:47:33Z |

## Description

The data provided here details the State of Missouri's Federal Grants Data as of June 30, 2014.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | time           | fiscal_year                       | Fiscal Year                       | number    | text        |
| Yes      | series tag     | agency_name                       | Agency Name                       | text      | text        |
| Yes      | series tag     | federal_agency_name               | Federal Agency Name               | text      | text        |
| Yes      | series tag     | grant_name                        | Grant Name                        | text      | text        |
| Yes      | series tag     | grant_purpose                     | Grant Purpose                     | text      | text        |
| Yes      | numeric metric | received_amount                   | Received Amount                   | money     | money       |
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
series e:8cjj-4npp d:2014-01-01T00:00:00.000Z t:federal_agency_name="NATIONAL FOUNDATION OF ARTS AND HUMANITIES" t:grant_name="GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES" t:grant_purpose="THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION." t:agency_name="OFFICE OF SECRETARY OF STATE" m:received_amount=2994821

series e:8cjj-4npp d:2014-01-01T00:00:00.000Z t:federal_agency_name="NATIONAL FOUNDATION OF ARTS AND HUMANITIES" t:grant_name="GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES" t:name_of_agency_receiving_transfer="MENTAL HEALTH" t:transfer_purpose="THE LIBRARY CREATED 38 HOPE KITS, TO BE ROTATED IN THE CONSUMER LIVING AREAS OF THE FULTON STATE HOSPITAL, A PUBLIC MENTAL HEALTH FACILITY. ALSO, FOUR HOPE-INSPIRING, EDUCATIONAL PRESENTATIONS WERE HELD." t:grant_purpose="THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION." t:agency_name="OFFICE OF SECRETARY OF STATE" t:statistics="A TOTAL OF 276 PEOPLE WERE SERVED THROUGH THE PROJECT." m:transfer_amount=7240

series e:8cjj-4npp d:2014-01-01T00:00:00.000Z t:federal_agency_name="NATIONAL FOUNDATION OF ARTS AND HUMANITIES" t:grant_name="GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES" t:name_of_agency_receiving_transfer="MENTAL HEALTH" t:transfer_purpose="THE LIBRARY CREATED 38 HOPE KITS, TO BE ROTATED IN THE CONSUMER LIVING AREAS OF THE FULTON STATE HOSPITAL, A PUBLIC MENTAL HEALTH FACILITY. ALSO, FOUR HOPE-INSPIRING, EDUCATIONAL PRESENTATIONS WERE HELD." t:grant_purpose="THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION." t:agency_name="OFFICE OF SECRETARY OF STATE" t:statistics="A TOTAL OF 276 PEOPLE WERE SERVED THROUGH THE PROJECT." m:transfer_amount=3560.69
```

## Meta Commands

```ls
metric m:received_amount p:double l:"Received Amount" t:dataTypeName=money

metric m:transfer_amount p:double l:"Transfer Amount" t:dataTypeName=number

entity e:8cjj-4npp l:"2014 Federal Grants Data As of June 30, 2014" t:url=https://data.mo.gov/api/views/8cjj-4npp

property e:8cjj-4npp t:meta.view v:id=8cjj-4npp v:category="Government Administration" v:averageRating=0 v:name="2014 Federal Grants Data As of June 30, 2014"

property e:8cjj-4npp t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:8cjj-4npp t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| fiscal_year | agency_name                  | federal_agency_name                        | grant_name                                      | grant_purpose                                                                                                                                          | received_amount | name_of_agency_receiving_transfer | transfer_purpose                                                                                                                                                                                                                                       | statistics                                                                                                                                          | transfer_amount | 
| =========== | ============================ | ========================================== | =============================================== | ====================================================================================================================================================== | =============== | ================================= | ====================================================================================================================================================================================================================================================== | =================================================================================================================================================== | =============== | 
| 2014        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         | 2994821.00      |                                   |                                                                                                                                                                                                                                                        |                                                                                                                                                     |                 | 
| 2014        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         |                 | MENTAL HEALTH                     | THE LIBRARY CREATED 38 HOPE KITS, TO BE ROTATED IN THE CONSUMER LIVING AREAS OF THE FULTON STATE HOSPITAL, A PUBLIC MENTAL HEALTH FACILITY. ALSO, FOUR HOPE-INSPIRING, EDUCATIONAL PRESENTATIONS WERE HELD.                                            | A TOTAL OF 276 PEOPLE WERE SERVED THROUGH THE PROJECT.                                                                                              | 7240.00         | 
| 2014        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         |                 | MENTAL HEALTH                     | THE LIBRARY CREATED 38 HOPE KITS, TO BE ROTATED IN THE CONSUMER LIVING AREAS OF THE FULTON STATE HOSPITAL, A PUBLIC MENTAL HEALTH FACILITY. ALSO, FOUR HOPE-INSPIRING, EDUCATIONAL PRESENTATIONS WERE HELD.                                            | A TOTAL OF 276 PEOPLE WERE SERVED THROUGH THE PROJECT.                                                                                              | 3560.69         | 
| 2014        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         |                 | MENTAL HEALTH                     | PROVIDED 5 REGIONAL TRAININGS OF MENTAL HEALTH FIRST AID TO PUBLIC LIBRARY STAFF; REDESIGNED LIBRARIAN411.ORG; SURVEYED PUBLIC LIBRARY STAFF REGARDING MENTAL HEALTH RESOURCE NEEDS; CREATED AWARENESS KITS FOR USE BY PUBLIC LIBRARIES.               | REGIONAL TRAININGS HAD 88 ATTENDEES; LIBRARIAN411.ORG HAD 86,574 HITS FROM 23,754 VISITORS ACROSS THE U.S. & BEYOND; 60 AWARENESS KITS DISTRIBUTED. | 8730.00         | 
| 2014        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         |                 | MENTAL HEALTH                     | PROVIDED 5 REGIONAL TRAININGS OF MENTAL HEALTH FIRST AID TO PUBLIC LIBRARY STAFF; REDESIGNED LIBRARIAN411.ORG; SURVEYED PUBLIC LIBRARY STAFF REGARDING MENTAL HEALTH RESOURCE NEEDS; CREATED AWARENESS KITS FOR USE BY PUBLIC LIBRARIES.               | REGIONAL TRAININGS HAD 88 ATTENDEES; LIBRARIAN411.ORG HAD 86,574 HITS FROM 23,754 VISITORS ACROSS THE U.S. & BEYOND; 60 AWARENESS KITS DISTRIBUTED. | 5628.51         | 
| 2014        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         | 1715226.00      |                                   |                                                                                                                                                                                                                                                        |                                                                                                                                                     |                 | 
| 2014        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         |                 | MENTAL HEALTH                     | TO UPDATE TWO VIDEOS ON THE LIBRARIAN411 WEBSITE THAT ADDRESS LIBRARY CUSTOMER SERVICE TO MISSOURIANS WITH MENTAL ILLNESSES. ALSO, KITS WILL BE CREATED AND DISTRIBUTED TO PUBLIC LIBRARIES TO RAISE AWARENESS OF MENTAL HEALTH AND DISABILITY ISSUES. |                                                                                                                                                     | 10500.00        | 
| 2014        | OFFICE OF SECRETARY OF STATE | NATIONAL FOUNDATION OF ARTS AND HUMANITIES | GRANTS TO STATE LIBRARY ADMINISTRATIVE AGENCIES | THIS GRANT IS TO PROVIDE ASSISTANCE TO IMPROVE LIBRARY SERVICES FOR THE PURPOSES SPECIFIED IN THE APPLICATION.                                         | 69931.00        |                                   |                                                                                                                                                                                                                                                        |                                                                                                                                                     |                 | 
| 2014        | OFFICE OF ATTORNEY GENERAL   | US DEPARTMENT OF HEALTH AND HUMAN SERVICES | STATE MEDICAID FRAUD CONTROL UNIT GRANT PROGRAM | TO INVESTIGATE AND PROSECUTE MEDICAID FRAUD                                                                                                            | 1524416.00      |                                   |                                                                                                                                                                                                                                                        |                                                                                                                                                     |                 | 
| 2014        | OFFICE OF ADMINISTRATION     | US DEPARTMENT OF COMMERCE                  | STATE BROADBAND DATA AND DEVELOPMENT GRANT      | PUBLISH BROADBAND MAPS, PROVIDE TECHNICAL ASSISTANCE, ESTABLISH REGIONAL PLANNING TEAMS AND DEVELOP STRATEGIC BROADBAND OUTCOMES AND OTHER ACTIVITIES. | 2364128.11      |                                   |                                                                                                                                                                                                                                                        |                                                                                                                                                     |                 | 
```