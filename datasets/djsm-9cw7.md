# Registered Lobbyist Disclosures: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/registered-lobbyist-disclosures-past-six-years) |
| Metadata | [Link](https://data.ny.gov/api/views/djsm-9cw7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/djsm-9cw7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/djsm-9cw7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | djsm-9cw7 |
| Name | Registered Lobbyist Disclosures: Beginning 2007 |
| Attribution | NYS Joint Commission on Public Ethics |
| Category | Transparency |
| Tags | lobbyist disclosures, integrity |
| Created | 2013-04-16T16:49:37Z |
| Publication Date | 2016-05-02T16:46:02Z |

## Description

Data provided by Lobbyist in their Biennial Registration and Bi-monthly filings submitted to NYS Joint Commission on Public Ethics

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| Yes      | time           | reporting_year                  | Reporting Year                  | number    | number      |
| Yes      | series tag     | reporting_period                | Reporting Period                | text      | text        |
| Yes      | series tag     | lobbyist_name                   | Lobbyist Name                   | text      | text        |
| No       |                | lobbyist_address_1              | Lobbyist Address 1              | text      | text        |
| No       |                | lobbyist_address_2              | Lobbyist Address 2              | text      | text        |
| Yes      | series tag     | lobbyist_city                   | Lobbyist City                   | text      | text        |
| Yes      | series tag     | lobbyist_state                  | Lobbyist State                  | text      | text        |
| Yes      | series tag     | lobbyist_zip                    | Lobbyist Zip                    | text      | text        |
| Yes      | series tag     | lobbyist_phone                  | Lobbyist Phone                  | text      | text        |
| Yes      | series tag     | lobbyist_email                  | Lobbyist Email                  | email     | email       |
| Yes      | series tag     | lobbying_type                   | Lobbying Type                   | text      | text        |
| Yes      | series tag     | government_level                | Government Level                | text      | text        |
| Yes      | series tag     | lobbyist_type                   | Lobbyist Type                   | text      | text        |
| Yes      | series tag     | additional_lobbyists_lr         | Additional Lobbyists LR         | text      | text        |
| Yes      | series tag     | additional_lobbyists_lbr        | Additional Lobbyists LBR        | text      | text        |
| Yes      | series tag     | client_name                     | Client Name                     | text      | text        |
| No       |                | client_address_1                | Client Address 1                | text      | text        |
| No       |                | client_address_2                | Client Address 2                | text      | text        |
| Yes      | series tag     | client_city                     | Client City                     | text      | text        |
| Yes      | series tag     | client_state                    | Client State                    | text      | text        |
| Yes      | series tag     | client_zip                      | Client Zip                      | text      | text        |
| Yes      | series tag     | client_phone                    | Client Phone                    | text      | text        |
| Yes      | series tag     | client_business_nature          | Client Business Nature          | text      | text        |
| Yes      | series tag     | lr_responsible_party_first_name | LR Responsible Party First Name | text      | text        |
| Yes      | series tag     | lr_responsible_party_last_name  | LR Responsible Party Last Name  | text      | text        |
| Yes      | numeric metric | total_expenses                  | Total Expenses                  | money     | money       |
| Yes      | numeric metric | total_compensation              | Total Compensation              | money     | money       |
| Yes      | numeric metric | total_reimbursed                | Total Reimbursed                | money     | money       |
| Yes      | series tag     | bill_details_1                  | Bill Details 1                  | text      | text        |
| Yes      | series tag     | bill_details_2                  | Bill Details 2                  | text      | text        |
| Yes      | series tag     | procurement_details_1           | Procurement Details 1           | text      | text        |
| Yes      | series tag     | procurement_details_2           | Procurement Details 2           | text      | text        |
| Yes      | series tag     | lobbyist_subjects_1             | Lobbyist Subjects 1             | text      | text        |
| Yes      | series tag     | lobbyist_subjects_2             | Lobbyist Subjects 2             | text      | text        |
| Yes      | series tag     | person_1                        | Person 1                        | text      | text        |
| Yes      | series tag     | person_2                        | Person 2                        | text      | text        |
| Yes      | series tag     | procurement_number_1            | Procurement Number 1            | text      | text        |
| Yes      | series tag     | procurement_number_2            | Procurement Number 2            | text      | text        |
| Yes      | series tag     | procurement_subjects_1          | Procurement Subjects 1          | text      | text        |
| Yes      | series tag     | procurement_subjects_2          | Procurement Subjects 2          | text      | text        |
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
series e:djsm-9cw7 d:2015-01-01T00:00:00.000Z t:lobbyist_subjects_1="HEALTHCARE, HEALTHCARE FINANCE" t:lobbying_type=N t:lr_responsible_party_last_name=GRESHAM t:client_phone="(212) 582-1890" t:lobbyist_state=NY t:bill_details_1=NULL t:person_1="STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS" t:reporting_period=JF t:additional_lobbyists_lbr="HELEN SCHAUB" t:lobbyist_phone="(212) 603-1735" t:procurement_details_1=NULL t:additional_lobbyists_lr="LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB" t:client_business_nature=Labor t:client_zip=10036 t:lobbyist_zip=10036 t:government_level=B t:lobbyist_name="1199 SEIU UNITED HEALTHCARE WORKERS EAST" t:procurement_subjects_1=NULL t:lobbyist_city="NEW YORK" t:lobbyist_email=ARABB@LRBPC.COM t:lr_responsible_party_first_name=GEORGE t:lobbyist_type=E t:procurement_number_1=NULL t:client_name="1199 SEIU UNITED HEALTHCARE WORKERS EAST" t:client_state=NY t:client_city="NEW YORK" m:total_compensation=1000 m:total_reimbursed=0 m:total_expenses=0

series e:djsm-9cw7 d:2015-01-01T00:00:00.000Z t:lobbyist_subjects_1="HEALTHCARE, HEALTHCARE FINANCE, NYS BUDGET, MEDICAID POLICY, DSRIP" t:lobbying_type=N t:lr_responsible_party_last_name=GRESHAM t:client_phone="(212) 582-1890" t:lobbyist_state=NY t:bill_details_1="NYS BUDGET" t:person_1="STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS" t:reporting_period=MA t:additional_lobbyists_lbr="HELEN SCHAUB" t:lobbyist_phone="(212) 603-1735" t:procurement_details_1=NULL t:additional_lobbyists_lr="LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB" t:client_business_nature=Labor t:client_zip=10036 t:lobbyist_zip=10036 t:government_level=B t:lobbyist_name="1199 SEIU UNITED HEALTHCARE WORKERS EAST" t:procurement_subjects_1=NULL t:lobbyist_city="NEW YORK" t:lobbyist_email=ARABB@LRBPC.COM t:lr_responsible_party_first_name=GEORGE t:lobbyist_type=E t:procurement_number_1=NULL t:client_name="1199 SEIU UNITED HEALTHCARE WORKERS EAST" t:client_state=NY t:client_city="NEW YORK" m:total_compensation=2000 m:total_reimbursed=0 m:total_expenses=0

series e:djsm-9cw7 d:2015-01-01T00:00:00.000Z t:lobbyist_subjects_1="HEALTHCARE, HEALTHCARE FINANCE, DSRIP, LONG TERM CARE ISSUES, HOME CARE TRAINING, ADVANCED TRAINING INITIATIVE" t:lobbying_type=N t:lr_responsible_party_last_name=GRESHAM t:client_phone="(212) 582-1890" t:lobbyist_state=NY t:bill_details_1=NULL t:person_1="STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS" t:reporting_period=MJ t:additional_lobbyists_lbr="HELEN SCHAUB" t:lobbyist_phone="(212) 603-1735" t:procurement_details_1=NULL t:additional_lobbyists_lr="LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB" t:client_business_nature=Labor t:client_zip=10036 t:lobbyist_zip=10036 t:government_level=B t:lobbyist_name="1199 SEIU UNITED HEALTHCARE WORKERS EAST" t:procurement_subjects_1=NULL t:lobbyist_city="NEW YORK" t:lobbyist_email=ARABB@LRBPC.COM t:lr_responsible_party_first_name=GEORGE t:lobbyist_type=E t:procurement_number_1=NULL t:client_name="1199 SEIU UNITED HEALTHCARE WORKERS EAST" t:client_state=NY t:client_city="NEW YORK" m:total_compensation=2000 m:total_reimbursed=0 m:total_expenses=0
```

## Meta Commands

```ls
metric m:total_expenses p:integer l:"Total Expenses" d:"Summary of Expenses reported for the period" t:dataTypeName=money

metric m:total_compensation p:integer l:"Total Compensation" d:"Summary of Compensation reported for the period" t:dataTypeName=money

metric m:total_reimbursed p:integer l:"Total Reimbursed" d:"Summary of Reimbursed Expenses reported for the period" t:dataTypeName=money

entity e:djsm-9cw7 l:"Registered Lobbyist Disclosures: Beginning 2007" t:attribution="NYS Joint Commission on Public Ethics" t:url=https://data.ny.gov/api/views/djsm-9cw7

property e:djsm-9cw7 t:meta.view v:id=djsm-9cw7 v:category=Transparency v:attributionLink=http://www.jcope.ny.gov v:averageRating=0 v:name="Registered Lobbyist Disclosures: Beginning 2007" v:attribution="NYS Joint Commission on Public Ethics"

property e:djsm-9cw7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:djsm-9cw7 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:djsm-9cw7 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| reporting_year | reporting_period | lobbyist_name                                  | lobbyist_address_1               | lobbyist_address_2 | lobbyist_city | lobbyist_state | lobbyist_zip | lobbyist_phone | lobbyist_email       | lobbying_type | government_level | lobbyist_type | additional_lobbyists_lr                                     | additional_lobbyists_lbr                                    | client_name                                    | client_address_1   | client_address_2 | client_city | client_state | client_zip | client_phone   | client_business_nature  | lr_responsible_party_first_name | lr_responsible_party_last_name | total_expenses | total_compensation | total_reimbursed | bill_details_1           | bill_details_2 | procurement_details_1 | procurement_details_2 | lobbyist_subjects_1                                                                                            | lobbyist_subjects_2 | person_1                                            | person_2 | procurement_number_1 | procurement_number_2 | procurement_subjects_1 | procurement_subjects_2 | 
| ============== | ================ | ============================================== | ================================ | ================== | ============= | ============== | ============ | ============== | ==================== | ============= | ================ | ============= | =========================================================== | =========================================================== | ============================================== | ================== | ================ | =========== | ============ | ========== | ============== | ======================= | =============================== | ============================== | ============== | ================== | ================ | ======================== | ============== | ===================== | ===================== | ============================================================================================================== | =================== | =================================================== | ======== | ==================== | ==================== | ====================== | ====================== | 
| 2015           | JF               | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 330 WEST 42ND STREET             | 7TH FLOOR          | NEW YORK      | NY             | 10036        | (212) 603-1735 | ARABB@LRBPC.COM      | N             | B                | E             | LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB | HELEN SCHAUB                                                | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 310 W. 43RD STREET | 7TH FLOOR        | NEW YORK    | NY           | 10036      | (212) 582-1890 | Labor                   | GEORGE                          | GRESHAM                        | 0              | 1000               | 0                | NULL                     |                | NULL                  |                       | HEALTHCARE, HEALTHCARE FINANCE                                                                                 |                     | STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS |          | NULL                 |                      | NULL                   |                        | 
| 2015           | MA               | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 330 WEST 42ND STREET             | 7TH FLOOR          | NEW YORK      | NY             | 10036        | (212) 603-1735 | ARABB@LRBPC.COM      | N             | B                | E             | LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB | HELEN SCHAUB                                                | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 310 W. 43RD STREET | 7TH FLOOR        | NEW YORK    | NY           | 10036      | (212) 582-1890 | Labor                   | GEORGE                          | GRESHAM                        | 0              | 2000               | 0                | NYS BUDGET               |                | NULL                  |                       | HEALTHCARE, HEALTHCARE FINANCE, NYS BUDGET, MEDICAID POLICY, DSRIP                                             |                     | STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS |          | NULL                 |                      | NULL                   |                        | 
| 2015           | MJ               | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 330 WEST 42ND STREET             | 7TH FLOOR          | NEW YORK      | NY             | 10036        | (212) 603-1735 | ARABB@LRBPC.COM      | N             | B                | E             | LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB | HELEN SCHAUB                                                | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 310 W. 43RD STREET | 7TH FLOOR        | NEW YORK    | NY           | 10036      | (212) 582-1890 | Labor                   | GEORGE                          | GRESHAM                        | 0              | 2000               | 0                | NULL                     |                | NULL                  |                       | HEALTHCARE, HEALTHCARE FINANCE, DSRIP, LONG TERM CARE ISSUES, HOME CARE TRAINING, ADVANCED TRAINING INITIATIVE |                     | STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS |          | NULL                 |                      | NULL                   |                        | 
| 2015           | JA               | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 330 WEST 42ND STREET             | 7TH FLOOR          | NEW YORK      | NY             | 10036        | (212) 603-1735 | ARABB@LRBPC.COM      | N             | B                | E             | LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB | HELEN SCHAUB                                                | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 310 W. 43RD STREET | 7TH FLOOR        | NEW YORK    | NY           | 10036      | (212) 582-1890 | Labor                   | GEORGE                          | GRESHAM                        | 0              | 1000               | 0                | NULL                     |                | NULL                  |                       | HEALTHCARE, HEALTHCARE FINANCE, DSRIP, ADVANCED TRAINING INITIATIVE                                            |                     | STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS |          | NULL                 |                      | NULL                   |                        | 
| 2015           | SO               | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 330 WEST 42ND STREET             | 7TH FLOOR          | NEW YORK      | NY             | 10036        | (212) 603-1735 | ARABB@LRBPC.COM      | N             | B                | E             | LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB | HELEN SCHAUB,LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 310 W. 43RD STREET | 7TH FLOOR        | NEW YORK    | NY           | 10036      | (212) 582-1890 | Labor                   | GEORGE                          | GRESHAM                        | 0              | 1000               | 0                | NYS BUDGET, A1034, S5565 |                | NULL                  |                       | HEALTHCARE, HEALTHCARE FINANCE                                                                                 |                     | STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS |          | NULL                 |                      | NULL                   |                        | 
| 2015           | ND               | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 330 WEST 42ND STREET             | 7TH FLOOR          | NEW YORK      | NY             | 10036        | (212) 603-1735 | ARABB@LRBPC.COM      | N             | B                | E             | LILLIE CARINO,GEORGE GRESHAM,ANTONELLA PECHTEL,HELEN SCHAUB | HELEN SCHAUB                                                | 1199 SEIU UNITED HEALTHCARE WORKERS EAST       | 310 W. 43RD STREET | 7TH FLOOR        | NEW YORK    | NY           | 10036      | (212) 582-1890 | Labor                   | GEORGE                          | GRESHAM                        | 0              | 1000               | 0                | NYS BUDGET, A1034, S5565 |                | NULL                  |                       | HEALTHCARE, HEALTHCARE FINANCE, DSRIP, QIVAPP, VBPQIP                                                          |                     | STATE AND LOCAL EXECUTIVE AND LEGISLATIVE OFFICIALS |          | NULL                 |                      | NULL                   |                        | 
| 2015           | ND               | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 WEST 42ND STREET, 21ST FLOOR |                    | NEW YORK      | NY             | 10036        | (646) 473-8488 | ARABB@LEVYRATNER.COM | N             | S                | E             | DEBRA PUCCI                                                 | DEBRA PUCCI                                                 | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 W 42ND STREET  | 21ST FLOOR       | NEW YORK    | NY           | 10036      | 646-473-8488   | Health & Mental Hygiene | DEBRA                           | PUCCI                          | 0              | 600                | 0                | NULL                     |                | NULL                  |                       | NULL                                                                                                           |                     | NULL                                                |          | NULL                 |                      | NULL                   |                        | 
| 2015           | SO               | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 WEST 42ND STREET, 21ST FLOOR |                    | NEW YORK      | NY             | 10036        | (646) 473-8488 | ARABB@LEVYRATNER.COM | N             | S                | E             | DEBRA PUCCI                                                 | DEBRA PUCCI                                                 | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 W 42ND STREET  | 21ST FLOOR       | NEW YORK    | NY           | 10036      | 646-473-8488   | Health & Mental Hygiene | DEBRA                           | PUCCI                          | 0              | 300                | 0                | NULL                     |                | NULL                  |                       | NULL                                                                                                           |                     | NULL                                                |          | NULL                 |                      | NULL                   |                        | 
| 2015           | JA               | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 WEST 42ND STREET, 21ST FLOOR |                    | NEW YORK      | NY             | 10036        | (646) 473-8488 | ARABB@LEVYRATNER.COM | N             | S                | E             | DEBRA PUCCI                                                 | DEBRA PUCCI                                                 | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 W 42ND STREET  | 21ST FLOOR       | NEW YORK    | NY           | 10036      | 646-473-8488   | Health & Mental Hygiene | DEBRA                           | PUCCI                          | 0              | 600                | 0                | NULL                     |                | NULL                  |                       | NULL                                                                                                           |                     | NULL                                                |          | NULL                 |                      | NULL                   |                        | 
| 2015           | MJ               | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 WEST 42ND STREET, 21ST FLOOR |                    | NEW YORK      | NY             | 10036        | (646) 473-8488 | ARABB@LEVYRATNER.COM | N             | S                | E             | DEBRA PUCCI                                                 | DEBRA PUCCI                                                 | 1199/SEIU & GNYHA HEALTHCARE EDUCATION PROJECT | 330 W 42ND STREET  | 21ST FLOOR       | NEW YORK    | NY           | 10036      | 646-473-8488   | Health & Mental Hygiene | DEBRA                           | PUCCI                          | 0              | 600                | 0                | NULL                     |                | NULL                  |                       | NEW YORK STATE BUDGET                                                                                          |                     | EXECUTIVE BRANCH AND LEGISLATIVE BRANCH             |          | NULL                 |                      | NULL                   |                        | 
```