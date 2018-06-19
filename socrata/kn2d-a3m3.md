# Registered Public Corporations Disclosures: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/registered-public-corporations-disclosures-past-six-years) |
| Metadata | [Link](https://data.ny.gov/api/views/kn2d-a3m3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kn2d-a3m3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kn2d-a3m3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kn2d-a3m3 |
| Name | Registered Public Corporations Disclosures: Beginning 2007 |
| Attribution | NYS Joint Commission on Public Ethics |
| Category | Transparency |
| Tags | public corporations, disclosures, integrity |
| Created | 2013-04-15T21:07:26Z |
| Publication Date | 2016-05-02T16:48:05Z |

## Description

Data provided by Public Corporation in their Biennial Registration and Bi-monthly filings submitted to NYS Joint Commission on Public Ethics.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | time           | reporting_year                   | Reporting Year                   | number    | number      |
| Yes      | series tag     | reporting_period                 | Reporting Period                 | text      | text        |
| Yes      | series tag     | name                             | Name                             | text      | text        |
| Yes      | series tag     | pc_business_nature               | PC Business Nature               | text      | text        |
| Yes      | series tag     | lobbying_type                    | Lobbying Type                    | text      | text        |
| Yes      | series tag     | government_level                 | Government Level                 | text      | text        |
| No       |                | address_1                        | Address 1                        | text      | text        |
| No       |                | address_2                        | Address 2                        | text      | text        |
| Yes      | series tag     | city                             | City                             | text      | text        |
| Yes      | series tag     | state                            | State                            | text      | text        |
| Yes      | series tag     | zip                              | Zip                              | text      | text        |
| Yes      | series tag     | phone                            | Phone                            | text      | text        |
| Yes      | series tag     | email                            | Email                            | email     | email       |
| Yes      | series tag     | pr_responsible_person_first_name | PR Responsible Person First Name | text      | text        |
| Yes      | series tag     | pr_responsible_person_last_name  | PR Responsible Person Last Name  | text      | text        |
| Yes      | numeric metric | total_expenses                   | Total Expenses                   | money     | money       |
| Yes      | numeric metric | total_compensation               | Total Compensation               | money     | money       |
| Yes      | series tag     | lobbyist_subjects                | Lobbyist Subjects                | text      | text        |
| Yes      | series tag     | person                           | Person                           | text      | text        |
| Yes      | series tag     | bill_details                     | Bill Details                     | text      | text        |
| Yes      | series tag     | procurement_numbers              | Procurement Numbers              | text      | text        |
| Yes      | series tag     | procurement_subjects             | Procurement Subjects             | text      | text        |
| Yes      | series tag     | procurement_details              | Procurement Details              | text      | text        |
| Yes      | series tag     | in_house_lobbyist                | In House Lobbyist                | text      | text        |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:kn2d-a3m3 d:2008-01-01T00:00:00.000Z t:zip=12206 t:person="EXECUTIVE CHAMBER, DIVISION OF BUDGET, ASSEMBLY, SENATE" t:lobbyist_subjects="ANY ITEMS RELATING TO TRANSPORTATION, CDTA AND OR IT'S SUBSIDIARIES" t:lobbying_type=N t:phone="(518) 437-8300" t:government_level=S t:pr_responsible_person_first_name=RAYMOND t:email=RAYM@CDTA.ORG t:name="CAPITAL DISTRICT TRANSPORTATION AUTHORITY" t:state=NY t:pr_responsible_person_last_name=MELLEADY t:reporting_period=JA t:in_house_lobbyist="RAYMOND MELLEADY" t:pc_business_nature=Transportation t:city=ALBANY m:total_compensation=0 m:total_expenses=0

series e:kn2d-a3m3 d:2008-01-01T00:00:00.000Z t:bill_details="S.6802  A.9802  S.6801  A.9801" t:zip=12206 t:person="ASSEMBLY  ASSEMBLYMAN CANESTRARI  ASSEMBLYMAN TEDISCO  ASSEMBLYMAN MACDONALD  ASSEMBLYMAN BARCLAY  ASSEMBLYWOMAN SCHIMEL  ASSEMBLYMAN AMEDORE  ASSEMBLYMAN GORDON  ASSEMBLYMAN MACENENY  ASSSENBLYMAN REILLY  SENATE  SENATOR BRUNO  SENATOR FARLEY  SENATOR BRESLIN" t:lobbyist_subjects="THE EXECUTIVE BUDGET BILL" t:lobbying_type=N t:phone="(518) 437-8300" t:government_level=S t:pr_responsible_person_first_name=RAYMOND t:email=RAYM@CDTA.ORG t:name="CAPITAL DISTRICT TRANSPORTATION AUTHORITY" t:state=NY t:pr_responsible_person_last_name=MELLEADY t:reporting_period=JF t:in_house_lobbyist="RAYMOND MELLEADY" t:pc_business_nature=Transportation t:city=ALBANY m:total_compensation=1500 m:total_expenses=2000

series e:kn2d-a3m3 d:2008-01-01T00:00:00.000Z t:zip=12206 t:person="EXECUTIVE CHAMBER, DIVISION OF BUDGET, ASSEMBLY, SENATE" t:lobbyist_subjects="ANY ITEMS RELATING TO TRANSPORTATION, CDTA AND OR IT'S SUBSIDIARIES" t:lobbying_type=N t:phone="(518) 437-8300" t:government_level=S t:pr_responsible_person_first_name=RAYMOND t:email=RAYM@CDTA.ORG t:name="CAPITAL DISTRICT TRANSPORTATION AUTHORITY" t:state=NY t:pr_responsible_person_last_name=MELLEADY t:reporting_period=MA t:in_house_lobbyist="RAYMOND MELLEADY" t:pc_business_nature=Transportation t:city=ALBANY m:total_compensation=0 m:total_expenses=0
```

## Meta Commands

```ls
metric m:total_expenses p:integer l:"Total Expenses" d:"Summary of Expenses Reported for the period" t:dataTypeName=money

metric m:total_compensation p:integer l:"Total Compensation" d:"Summary of Compensation Reported for the period" t:dataTypeName=money

entity e:kn2d-a3m3 l:"Registered Public Corporations Disclosures: Beginning 2007" t:attribution="NYS Joint Commission on Public Ethics" t:url=https://data.ny.gov/api/views/kn2d-a3m3

property e:kn2d-a3m3 t:meta.view v:id=kn2d-a3m3 v:category=Transparency v:attributionLink=http://www.jcope.ny.gov v:averageRating=0 v:name="Registered Public Corporations Disclosures: Beginning 2007" v:attribution="NYS Joint Commission on Public Ethics"

property e:kn2d-a3m3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kn2d-a3m3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kn2d-a3m3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| reporting_year | reporting_period | name                                      | pc_business_nature       | lobbying_type | government_level | address_1                  | address_2 | city   | state | zip   | phone          | email                   | pr_responsible_person_first_name | pr_responsible_person_last_name | total_expenses | total_compensation | lobbyist_subjects                                                   | person                                                                                                                                                                                                                                                  | bill_details                                       | procurement_numbers | procurement_subjects | procurement_details | in_house_lobbyist  | 
| ============== | ================ | ========================================= | ======================== | ============= | ================ | ========================== | ========= | ====== | ===== | ===== | ============== | ======================= | ================================ | =============================== | ============== | ================== | =================================================================== | ======================================================================================================================================================================================================================================================= | ================================================== | =================== | ==================== | =================== | ================== | 
| 2008           | JA               | CAPITAL DISTRICT TRANSPORTATION AUTHORITY | Transportation           | N             | S                | 110 WATERVLIET AVENUE      | NULL      | ALBANY | NY    | 12206 | (518) 437-8300 | RAYM@CDTA.ORG           | RAYMOND                          | MELLEADY                        | 0              | 0                  | ANY ITEMS RELATING TO TRANSPORTATION, CDTA AND OR IT'S SUBSIDIARIES | EXECUTIVE CHAMBER, DIVISION OF BUDGET, ASSEMBLY, SENATE                                                                                                                                                                                                 |                                                    |                     |                      |                     | RAYMOND MELLEADY   | 
| 2008           | JF               | CAPITAL DISTRICT TRANSPORTATION AUTHORITY | Transportation           | N             | S                | 110 WATERVLIET AVENUE      | NULL      | ALBANY | NY    | 12206 | (518) 437-8300 | RAYM@CDTA.ORG           | RAYMOND                          | MELLEADY                        | 2000           | 1500               | THE EXECUTIVE BUDGET BILL                                           | ASSEMBLY ASSEMBLYMAN CANESTRARI ASSEMBLYMAN TEDISCO ASSEMBLYMAN MACDONALD ASSEMBLYMAN BARCLAY ASSEMBLYWOMAN SCHIMEL ASSEMBLYMAN AMEDORE ASSEMBLYMAN GORDON ASSEMBLYMAN MACENENY ASSSENBLYMAN REILLY SENATE SENATOR BRUNO SENATOR FARLEY SENATOR BRESLIN | S.6802 A.9802 S.6801 A.9801                        |                     |                      |                     | RAYMOND MELLEADY   | 
| 2008           | MA               | CAPITAL DISTRICT TRANSPORTATION AUTHORITY | Transportation           | N             | S                | 110 WATERVLIET AVENUE      | NULL      | ALBANY | NY    | 12206 | (518) 437-8300 | RAYM@CDTA.ORG           | RAYMOND                          | MELLEADY                        | 0              | 0                  | ANY ITEMS RELATING TO TRANSPORTATION, CDTA AND OR IT'S SUBSIDIARIES | EXECUTIVE CHAMBER, DIVISION OF BUDGET, ASSEMBLY, SENATE                                                                                                                                                                                                 |                                                    |                     |                      |                     | RAYMOND MELLEADY   | 
| 2008           | MJ               | CAPITAL DISTRICT TRANSPORTATION AUTHORITY | Transportation           | N             | S                | 110 WATERVLIET AVENUE      | NULL      | ALBANY | NY    | 12206 | (518) 437-8300 | RAYM@CDTA.ORG           | RAYMOND                          | MELLEADY                        | 0              | 0                  | ANY ITEMS RELATING TO TRANSPORTATION, CDTA AND OR IT'S SUBSIDIARIES | EXECUTIVE CHAMBER, DIVISION OF BUDGET, ASSEMBLY, SENATE                                                                                                                                                                                                 |                                                    |                     |                      |                     | RAYMOND MELLEADY   | 
| 2007           | ND               | CAPITAL DISTRICT TRANSPORTATION AUTHORITY | Transportation           | N             | S                | 110 WATERVLIET AVENUE      | NULL      | ALBANY | NY    | 12206 | (518) 437-8300 | RAYM@CDTA.ORG           | RAYMOND                          | MELLEADY                        | 0              | 0                  | ANY ITEMS RELATING TO TRANSPORTATION, CDTA AND OR IT'S SUBSIDIARIES | EXECUTIVE CHAMBER, DIVISION OF BUDGET, ASSEMBLY, SENATE                                                                                                                                                                                                 |                                                    |                     |                      |                     | RAYMOND MELLEADY   | 
| 2008           | ND               | CAPITAL DISTRICT TRANSPORTATION AUTHORITY | Transportation           | N             | S                | 110 WATERVLIET AVENUE      | NULL      | ALBANY | NY    | 12206 | (518) 437-8300 | RAYM@CDTA.ORG           | RAYMOND                          | MELLEADY                        | 0              | 0                  | ANY ITEMS RELATING TO TRANSPORTATION, CDTA AND OR IT'S SUBSIDIARIES | EXECUTIVE CHAMBER, DIVISION OF BUDGET, ASSEMBLY, SENATE                                                                                                                                                                                                 |                                                    |                     |                      |                     | RAYMOND MELLEADY   | 
| 2008           | SO               | CAPITAL DISTRICT TRANSPORTATION AUTHORITY | Transportation           | N             | S                | 110 WATERVLIET AVENUE      | NULL      | ALBANY | NY    | 12206 | (518) 437-8300 | RAYM@CDTA.ORG           | RAYMOND                          | MELLEADY                        | 0              | 0                  | ANY ITEMS RELATING TO TRANSPORTATION, CDTA AND OR IT'S SUBSIDIARIES | EXECUTIVE CHAMBER, DIVISION OF BUDGET, ASSEMBLY, SENATE                                                                                                                                                                                                 |                                                    |                     |                      |                     | RAYMOND MELLEADY   | 
| 2007           | JA               | CITY OF ALBANY                            | State & Local Government | N             | S                | CITY HALL -24 EAGLE STREET | NULL      | ALBANY | NY    | 12207 | (518) 434-5050 | REILLYJ@CI.ALBANY.NY.US | GERALD D.                        | JENNINGS                        | 0              | 2170               | PUBLIC LANDS LAW                                                    | ELIOT SPITZER, JOHN MCENENY, JOSEPH BRUNO, NEIL BRESLIN, NYS LEGISLATURE, RONALD CANESTRARI, SHELDON SILVER                                                                                                                                             | A.5697; S.3067 (RESIDENTIAL PARKING PERMIT SYSTEM) |                     |                      |                     | GERALD D. JENNINGS | 
| 2008           | JA               | CITY OF ALBANY                            | State & Local Government | N             | S                | CITY HALL -24 EAGLE STREET | NULL      | ALBANY | NY    | 12207 | (518) 434-5050 | REILLYJ@CI.ALBANY.NY.US | GERALD D.                        | JENNINGS                        | 0              | 2170               | PUBLIC LANDS LAW                                                    | DAVID PATERSON, JOHN MCENENY, DEAN SKELOS, NEIL BRESLIN, NYS LEGISLATURE, RONALD CANESTRARI, SHELDON SILVER                                                                                                                                             | A.5697; S.3067 (RESIDENTIAL PARKING PERMIT SYSTEM) |                     |                      |                     | GERALD D. JENNINGS | 
| 2007           | JF               | CITY OF ALBANY                            | State & Local Government | N             | S                | CITY HALL -24 EAGLE STREET | NULL      | ALBANY | NY    | 12207 | (518) 434-5050 | REILLYJ@CI.ALBANY.NY.US | GERALD D.                        | JENNINGS                        | 0              | 2170               | PUBLIC LANDS LAW                                                    | ELIOT SPITZER, JOHN MCENENY, JOSEPH BRUNO, NEIL BRESLIN, NYS LEGISLATURE, RONALD CANESTRARI, SHELDON SILVER                                                                                                                                             | S.1239; A.2732; S.5593-C; A.9025-C                 |                     |                      |                     | GERALD D. JENNINGS | 
```