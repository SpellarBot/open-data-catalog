# Lobbyist Disbursement of Public Monies Disclosures: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-disbursement-of-public-monies-disclosures-past-five-years) |
| Metadata | [Link](https://data.ny.gov/api/views/scx8-uayk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/scx8-uayk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/scx8-uayk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | scx8-uayk |
| Name | Lobbyist Disbursement of Public Monies Disclosures: Beginning 2008 |
| Attribution | NYS Joint Commission on Public Ethics |
| Category | Transparency |
| Tags | lobbyist disbursements, disclosures, integrity |
| Created | 2013-04-15T15:08:09Z |
| Publication Date | 2016-05-02T16:42:32Z |

## Description

Data provided by Lobbyist in their Bi-monthly filings submitted to NYS Joint Commission on Public Ethics

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | time           | reporting_year                   | Reporting Year                   | number    | number      |
| Yes      | series tag     | reporting_period                 | Reporting Period                 | text      | text        |
| Yes      | series tag     | lobbyist_name                    | Lobbyist Name                    | text      | text        |
| No       |                | lobbyist_address_1               | Lobbyist Address 1               | text      | text        |
| No       |                | lobbyist_address_2               | Lobbyist Address 2               | text      | text        |
| Yes      | series tag     | lobbyist_city                    | Lobbyist City                    | text      | text        |
| Yes      | series tag     | lobbyist_state                   | Lobbyist State                   | text      | text        |
| Yes      | series tag     | lobbyist_zip                     | Lobbyist Zip                     | text      | text        |
| Yes      | series tag     | lobbyist_phone                   | Lobbyist Phone                   | text      | text        |
| Yes      | series tag     | lobbyist_email                   | Lobbyist Email                   | email     | email       |
| Yes      | series tag     | additional_lobbyist              | Additional Lobbyist              | text      | text        |
| Yes      | series tag     | government_level                 | Government Level                 | text      | text        |
| Yes      | series tag     | client_name                      | Client Name                      | text      | text        |
| No       |                | client_address_1                 | Client Address 1                 | text      | text        |
| No       |                | client_address_2                 | Client Address 2                 | text      | text        |
| Yes      | series tag     | client_city                      | Client City                      | text      | text        |
| Yes      | series tag     | client_state                     | Client State                     | text      | text        |
| Yes      | series tag     | client_zip                       | Client Zip                       | text      | text        |
| Yes      | series tag     | client_phone                     | Client Phone                     | text      | text        |
| Yes      | numeric metric | total_expenses                   | Total Expenses                   | money     | money       |
| Yes      | numeric metric | total_compensation               | Total Compensation               | money     | money       |
| Yes      | numeric metric | total_reimbursed                 | Total Reimbursed                 | money     | money       |
| Yes      | series tag     | disbursement_details             | Disbursement Details             | text      | text        |
| Yes      | series tag     | person_details                   | Person Details                   | text      | text        |
| Yes      | series tag     | ldr_responsible_party_first_name | LDR Responsible Party First Name | text      | text        |
| Yes      | series tag     | ldr_responsible_party_last_name  | LDR Responsible Party Last Name  | text      | text        |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = lobbyist_address_1,lobbyist_address_2,client_address_1,client_address_2
```

## Data Commands

```ls
series e:scx8-uayk d:2008-01-01T00:00:00.000Z t:person_details="ASSEMBLY, SENATE, EXECUTIVE" t:ldr_responsible_party_first_name=JESSICA t:ldr_responsible_party_last_name=SHEARER t:client_phone="(212) 603-1741" t:lobbyist_state=NY t:reporting_period=ND t:lobbyist_phone="(212) 603-1741" t:client_zip=10036 t:lobbyist_zip=10036 t:disbursement_details="HEALTHCARE, STATE BUDGET" t:government_level=S t:lobbyist_name="1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT" t:lobbyist_city="NEW YORK" t:lobbyist_email=KFINNEGAN@LRBPC.COM t:client_name="HEALTHCARE EDUCATION PROJECT 1199/SEIU GREATER NY HOSPITAL ASSOCIATION" t:client_state=NY t:client_city="NEW YORK" m:total_reimbursed=0 m:total_compensation=0 m:total_expenses=85698

series e:scx8-uayk d:2010-01-01T00:00:00.000Z t:ldr_responsible_party_first_name=JACQUILINE t:ldr_responsible_party_last_name=WILLIAMS t:client_phone="(718) 907-5900" t:lobbyist_state=NY t:reporting_period=MJ t:lobbyist_phone=917-604-1304 t:additional_lobbyist="JACQUILINE  WILLIAMS" t:client_zip=11205 t:lobbyist_zip=11201 t:government_level=S t:lobbyist_name="99 SOLUTIONS LLC." t:lobbyist_city=BROOKLYN t:lobbyist_email=JACQUI@99-SOLUTIONS.COM t:client_name="BROOKLYN NAVY YARD DEVELOPMENT CORP." t:client_state=NY t:client_city=BROOKLYN m:total_reimbursed=0 m:total_compensation=12000 m:total_expenses=0

series e:scx8-uayk d:2010-01-01T00:00:00.000Z t:client_zip=11205 t:lobbyist_zip=11201 t:government_level=S t:lobbyist_name="99 SOLUTIONS LLC." t:ldr_responsible_party_first_name=JACQUILINE t:ldr_responsible_party_last_name=WILLIAMS t:lobbyist_state=NY t:client_phone="(718) 907-5900" t:lobbyist_city=BROOKLYN t:lobbyist_email=JACQUI@99-SOLUTIONS.COM t:reporting_period=JA t:lobbyist_phone=917-604-1304 t:client_name="BROOKLYN NAVY YARD DEVELOPMENT CORP." t:client_state=NY t:client_city=BROOKLYN m:total_reimbursed=0 m:total_compensation=12000 m:total_expenses=0
```

## Meta Commands

```ls
metric m:total_expenses p:integer l:"Total Expenses" d:"Summary of Expenses reported for period" t:dataTypeName=money

metric m:total_compensation p:integer l:"Total Compensation" d:"Summary of Compensation reported for the period" t:dataTypeName=money

metric m:total_reimbursed p:integer l:"Total Reimbursed" d:"Summary of Reimbursed Expenses reported for the period" t:dataTypeName=money

entity e:scx8-uayk l:"Lobbyist Disbursement of Public Monies Disclosures: Beginning 2008" t:attribution="NYS Joint Commission on Public Ethics" t:url=https://data.ny.gov/api/views/scx8-uayk

property e:scx8-uayk t:meta.view v:id=scx8-uayk v:category=Transparency v:attributionLink=http://www.jcope.ny.gov v:averageRating=0 v:name="Lobbyist Disbursement of Public Monies Disclosures: Beginning 2008" v:attribution="NYS Joint Commission on Public Ethics"

property e:scx8-uayk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:scx8-uayk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:scx8-uayk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| reporting_year | reporting_period | lobbyist_name                                  | lobbyist_address_1             | lobbyist_address_2 | lobbyist_city | lobbyist_state | lobbyist_zip | lobbyist_phone | lobbyist_email             | additional_lobbyist | government_level | client_name                                                            | client_address_1        | client_address_2     | client_city | client_state | client_zip | client_phone   | total_expenses | total_compensation | total_reimbursed | disbursement_details               | person_details              | ldr_responsible_party_first_name | ldr_responsible_party_last_name | 
| ============== | ================ | ============================================== | ============================== | ================== | ============= | ============== | ============ | ============== | ========================== | =================== | ================ | ====================================================================== | ======================= | ==================== | =========== | ============ | ========== | ============== | ============== | ================== | ================ | ================================== | =========================== | ================================ | =============================== | 
| 2008           | ND               | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 WEST 42ND STREET, ROOM 739 | NULL               | NEW YORK      | NY             | 10036        | (212) 603-1741 | KFINNEGAN@LRBPC.COM        |                     | S                | HEALTHCARE EDUCATION PROJECT 1199/SEIU GREATER NY HOSPITAL ASSOCIATION | 330 WEST 42ND STREET    |                      | NEW YORK    | NY           | 10036      | (212) 603-1741 | 85698          | 0                  | 0                | HEALTHCARE, STATE BUDGET           | ASSEMBLY, SENATE, EXECUTIVE | JESSICA                          | SHEARER                         | 
| 2010           | MJ               | 99 SOLUTIONS LLC.                              | 110 LIVINGSTON STREET          |                    | BROOKLYN      | NY             | 11201        | 917-604-1304   | JACQUI@99-SOLUTIONS.COM    | JACQUILINE WILLIAMS | S                | BROOKLYN NAVY YARD DEVELOPMENT CORP.                                   | 63 FLUSHING AVENUE      | UNIT 300 - BLDG. 292 | BROOKLYN    | NY           | 11205      | (718) 907-5900 | 0              | 12000              | 0                |                                    |                             | JACQUILINE                       | WILLIAMS                        | 
| 2010           | JA               | 99 SOLUTIONS LLC.                              | 110 LIVINGSTON STREET          |                    | BROOKLYN      | NY             | 11201        | 917-604-1304   | JACQUI@99-SOLUTIONS.COM    |                     | S                | BROOKLYN NAVY YARD DEVELOPMENT CORP.                                   | 63 FLUSHING AVENUE      | UNIT 300 - BLDG. 292 | BROOKLYN    | NY           | 11205      | (718) 907-5900 | 0              | 12000              | 0                |                                    |                             | JACQUILINE                       | WILLIAMS                        | 
| 2010           | ND               | 99 SOLUTIONS LLC.                              | 110 LIVINGSTON STREET          |                    | BROOKLYN      | NY             | 11201        | 917-604-1304   | JACQUI@99-SOLUTIONS.COM    |                     | S                | BROOKLYN NAVY YARD DEVELOPMENT CORP.                                   | 63 FLUSHING AVENUE      | UNIT 300 - BLDG. 292 | BROOKLYN    | NY           | 11205      | (718) 907-5900 | 0              | 12000              | 0                |                                    |                             | JACQUILINE                       | WILLIAMS                        | 
| 2011           | JF               | 99 SOLUTIONS LLC.                              | 20 JAY STREET                  | SUITE 1006         | BROOKLYN      | NY             | 11201        | 347-529-4535   | JACQUI@99-SOLUTIONS.COM    |                     | S                | BROOKLYN NAVY YARD DEVELOPMENT CORP.                                   | 63 FLUSHING AVENUE      | UNIT 300 - BLDG. 292 | BROOKLYN    | NY           | 11205      | (718) 907-5900 | 0              | 12000              | 0                |                                    |                             | JACQUILINE                       | WILLIAMS                        | 
| 2011           | MA               | 99 SOLUTIONS LLC.                              | 20 JAY STREET                  | SUITE 1006         | BROOKLYN      | NY             | 11201        | 347-529-4535   | JACQUI@99-SOLUTIONS.COM    |                     | B                | BROOKLYN NAVY YARD DEVELOPMENT CORP.                                   | 63 FLUSHING AVENUE      | UNIT 300 - BLDG. 292 | BROOKLYN    | NY           | 11205      | (718)907-5936  | 0              | 12000              | 0                |                                    |                             | JACQUILINE                       | WILLIAMS                        | 
| 2010           | SO               | 99 SOLUTIONS LLC.                              | 110 LIVINGSTON STREET          |                    | BROOKLYN      | NY             | 11201        | 917-604-1304   | JACQUI@99-SOLUTIONS.COM    |                     | S                | BROOKLYN NAVY YARD DEVELOPMENT CORPORATION                             | 63 FLUSHING AVENUE      | BLDG. 292, UNIT 300  | BROOKLYN    | NY           | 11205      | (718) 907-5936 | 0              | 12000              | 0                |                                    |                             | JACQUILINE                       | WILLIAMS                        | 
| 2012           | SO               | ADAMS, JOHN                                    | 400 CALGON CARBON DRIVE        |                    | PITTSBURGH    | PA             | 15205        | 412-787-6662   | JADAMS@CALGONCARBON-US.COM |                     | B                | CALGON CARBON CORPORATION                                              | 400 CALGON CARBON DRIVE |                      | PITTSBURGH  | PA           | 15205      | 412-787-6700   | 0              | 0                  | 0                |                                    |                             | JOHN                             | ADAMS                           | 
| 2008           | ND               | ADOLF, JAY                                     | 305 BROADWAY                   | SUITE 900          | NEW YORK      | NY             | 10007        | (212) 897-5848 | JADOLF@LAWSUITES.NET       |                     | S                | BIG APPLE CIRCUS                                                       | 505 EIGHTH AVENUE       | 19TH FLOOR           | NEW YORK    | NY           | 10018-6505 | (212) 268-2500 | 0              | 2700               | 0                |                                    |                             | JAY                              | ADOLF                           | 
| 2008           | JA               | ADOLF, JAY                                     | 305 BROADWAY                   | SUITE 900          | NEW YORK      | NY             | 10007        | (212) 897-5848 | JADOLF@LAWSUITES.NET       |                     | S                | BIG APPLE CIRCUS                                                       | 505 EIGHTH AVENUE       | 19TH FLOOR           | NEW YORK    | NY           | 10018-6505 | (212) 268-2500 | 0              | 2700               | 0                | CAPITAL GRANT-SLIFKA FAMILY CENTER | NY STATE SENATE             | JAY                              | ADOLF                           | 
```