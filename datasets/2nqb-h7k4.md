# FPPC 803 - Behested Payment Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fppc-803-behested-payment-report) |
| Metadata | [Link](https://data.sfgov.org/api/views/2nqb-h7k4) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/2nqb-h7k4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/2nqb-h7k4/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 2nqb-h7k4 |
| Name | FPPC 803 - Behested Payment Report |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | fppc, 803, behested, payments, charitable |
| Created | 2015-04-20T16:56:12Z |
| Publication Date | 2016-02-20T22:02:31Z |

## Description

In accordance with the California Government Code section 82015, payments made at the behest of elected officials are presumed not to be contributions if they meet the following guidelines:(a) the payments are made principally for legislative, governmental, or charitable purposes, and(b) the payments are made principally for purposes unrelated to the official's candidacy for elected office.Although such payments are not contributions, they MUST BE REPORTED on the Report of Payments Made at the Behest of an Elected Officer form to the elected officer's agency within 30 days after the total payments made by a single source equal to or exceed $5,000 in a calendar year. The agency must forward a copy of the report to the Ethics Commission within 30 days of its receipt.After the $5,000 threshold is met for a particular calendar year, all subsequent payments made by the same source during the calendar year must be reported by the elected officer within 30 days after the date the payment is made.These reports are public records.  The table includes all FPPC 803 forms filed with the Ethics Commission from April 20, 2015 to the present.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type      | Render Type    |
| ======== | ============== | ========================== | ========================== | ============== | ============== |
| Yes      | series tag     | elected_officer_last_name  | Elected Officer Last Name  | text           | text           |
| Yes      | series tag     | elected_officer_first_name | Elected Officer First Name | text           | text           |
| Yes      | series tag     | agency_name                | Agency Name                | text           | text           |
| Yes      | time           | date_filed                 | Date Filed                 | calendar_date  | calendar_date  |
| No       |                | period_start_date          | Period Start Date          | calendar_date  | calendar_date  |
| No       |                | period_end_date            | Period End Date            | calendar_date  | calendar_date  |
| Yes      | series tag     | payor_name                 | Payor Name                 | text           | text           |
| Yes      | series tag     | payee_name                 | Payee Name                 | text           | text           |
| Yes      | numeric metric | amount                     | Amount                     | money          | money          |
| Yes      | series tag     | purpose                    | Purpose                    | drop_down_list | drop_down_list |
| Yes      | series tag     | amendment                  | Amendment                  | checkbox       | checkbox       |
| No       |                | date_of_original_filing    | Date of Original Filing    | calendar_date  | calendar_date  |
| Yes      | series tag     | filing                     | Filing                     | document       | document       |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_start_date,period_end_date,date_of_original_filing
```

## Data Commands

```ls
series e:2nqb-h7k4 d:2015-04-24T00:00:00.000Z t:payee_name="San Francisco Travel Foundation (City Hall Centennial Celebration)" t:filing.file_id=K7Ilmdl1XMaEOBmze6rvzd8HXgGtIoT27VsVZUqwBSY t:filing.content_type=application/pdf t:elected_officer_last_name=Lee t:elected_officer_first_name=Edwin t:filing.size=124817 t:filing.filename=20150330_20150424_803_Lee_Edwin_Evelyn_and_Walter_Haas_Jr._Fund_Redacted.pdf t:purpose=thi2-6wsq t:agency_name=Mayor t:payor_name="Evelyn and Walter Haas Jr. Fund" m:amount=25000

series e:2nqb-h7k4 d:2015-04-24T00:00:00.000Z t:payee_name="San Francisco Travel Foundation (City Hall Centennial Celebration)" t:filing.file_id=LpOrmu0NWDL8UegTecabLpm--sjfMAplKue-dNH9GfY t:filing.content_type=application/pdf t:elected_officer_last_name=Lee t:elected_officer_first_name=Edwin t:filing.size=124026 t:filing.filename=20150402_20150424_803_Lee_Edwin_Lisa_&_Douglas_Goldman_Fund_Redacted.pdf t:purpose=thi2-6wsq t:agency_name=Mayor t:payor_name="Lisa & Douglas Goldman Fund" m:amount=25000

series e:2nqb-h7k4 d:2015-04-27T00:00:00.000Z t:payee_name="Equality California" t:filing.file_id=xEDy5fI5JMp20AUHVXHyi5MTJavdKLfPTdccEimK5-U t:filing.content_type=application/pdf t:elected_officer_last_name=Wiener t:elected_officer_first_name=Scott t:filing.size=127354 t:filing.filename=20150331_20150427_803_Wiener_Scott_Levi_Strauss_Redacted.pdf t:purpose=thi2-6wsq t:agency_name="Board of Supervisors" t:payor_name="Levi Strauss" m:amount=5000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:2nqb-h7k4 l:"FPPC 803 - Behested Payment Report" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/2nqb-h7k4

property e:2nqb-h7k4 t:meta.view v:id=2nqb-h7k4 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2012/05/payments-made-at-the-behest-of-an-elected-officer.html v:averageRating=0 v:name="FPPC 803 - Behested Payment Report" v:attribution="San Francisco Ethics Commission"

property e:2nqb-h7k4 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:2nqb-h7k4 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:2nqb-h7k4 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| elected_officer_last_name | elected_officer_first_name | agency_name          | date_filed          | period_start_date   | period_end_date     | payor_name                                           | payee_name                                                         | amount    | purpose   | amendment | date_of_original_filing | filing                                                                                                                                                                    | 
| ========================= | ========================== | ==================== | =================== | =================== | =================== | ==================================================== | ================================================================== | ========= | ========= | ========= | ======================= | ========================================================================================================================================================================= | 
| Lee                       | Edwin                      | Mayor                | 2015-04-24T00:00:00 | 2015-03-30T00:00:00 | 2015-03-30T00:00:00 | Evelyn and Walter Haas Jr. Fund                      | San Francisco Travel Foundation (City Hall Centennial Celebration) | 25000.00  | thi2-6wsq |           | 2015-04-24T00:00:00     | [application/pdf, K7Ilmdl1XMaEOBmze6rvzd8HXgGtIoT27VsVZUqwBSY, 20150330_20150424_803_Lee_Edwin_Evelyn_and_Walter_Haas_Jr._Fund_Redacted.pdf, 124817]                      | 
| Lee                       | Edwin                      | Mayor                | 2015-04-24T00:00:00 | 2015-04-02T00:00:00 | 2015-04-02T00:00:00 | Lisa & Douglas Goldman Fund                          | San Francisco Travel Foundation (City Hall Centennial Celebration) | 25000.00  | thi2-6wsq |           | 2015-04-24T00:00:00     | [application/pdf, LpOrmu0NWDL8UegTecabLpm--sjfMAplKue-dNH9GfY, 20150402_20150424_803_Lee_Edwin_Lisa_&_Douglas_Goldman_Fund_Redacted.pdf, 124026]                          | 
| Wiener                    | Scott                      | Board of Supervisors | 2015-04-27T00:00:00 | 2015-03-31T00:00:00 | 2015-03-31T00:00:00 | Levi Strauss                                         | Equality California                                                | 5000.00   | thi2-6wsq |           | 2015-04-27T00:00:00     | [application/pdf, xEDy5fI5JMp20AUHVXHyi5MTJavdKLfPTdccEimK5-U, 20150331_20150427_803_Wiener_Scott_Levi_Strauss_Redacted.pdf, 127354]                                      | 
| Lee                       | Edwin                      | Mayor                | 2015-05-01T00:00:00 | 2015-04-21T00:00:00 | 2015-04-21T00:00:00 | Wells Fargo Bank                                     | Friends and Foundation of the San Francisco Public Library         | 50000.00  | thi2-6wsq |           | 2015-05-01T00:00:00     | [application/pdf, 7OCUOJtKwuagVlShOPESAqdxbPxxbGZh8g60mlunIfc, 20150421_20150501_803_Lee_Edwin_Wells_Fargo_Bank_Redacted.pdf, 116714]                                     | 
| Lee                       | Edwin                      | Mayor                | 2015-05-01T00:00:00 | 2015-04-29T00:00:00 | 2015-04-29T00:00:00 | Tishman Speyer Properties, LP                        | San Francisco Travel Foundation (City Hall Centenial Celebration)  | 25000.00  | thi2-6wsq |           | 2015-05-01T00:00:00     | [application/pdf, _MNbmS0MercVZv4Szho0ytMTEEQqaobZegx9tAF1dcg, 20150429_20150501_803_Lee_Edwin_Tishman_Speyer_Properties_LP_Redacted.pdf, 120234]                         | 
| Lee                       | Edwin                      | Mayor                | 2015-05-13T00:00:00 | 2015-05-07T00:00:00 | 2015-05-07T00:00:00 | Al & Mei Wong                                        | San Francisco Travel Foundation (City Hall Centennial Celebration) | 10000.00  | thi2-6wsq |           | 2015-05-13T00:00:00     | [application/pdf, 6jI_NbttnLQR6s9oWS64moxih3kgXRIddm5kg88usvU, 20150507_20150513_803_Lee_Edwin_Al_&_Mei_Wong_Redacted.pdf, 122177]                                        | 
| Lee                       | Edwin                      | Mayor                | 2015-05-13T00:00:00 | 2015-05-07T00:00:00 | 2015-05-07T00:00:00 | Fisher Family C/O Pisces Inc.                        | San Francisco Travel Foundation (City Hall Centennial Celebration) | 25000.00  | thi2-6wsq |           | 2015-05-13T00:00:00     | [application/pdf, Sp2FGmD4vaAROpVP8k9wXwxcBAUvXlOPikc6fC6GkJ0, 20150507_20150513_803_Lee_Edwin_Fisher_Family_C.O_Pisces_Inc._Redacted.pdf, 121223]                        | 
| Lee                       | Edwin                      | Mayor                | 2015-05-13T00:00:00 | 2015-05-07T00:00:00 | 2015-05-07T00:00:00 | John Keker                                           | San Francisco Travel Foundation (City Hall Centennial Celebration) | 15000.00  | thi2-6wsq |           | 2015-05-13T00:00:00     | [application/pdf, IK2eg62Ve2OEtkl27e6O7-9Ha7RG4Syc8qd3vG6Hf6c, 20150507_20150513_803_Lee_Edwin_John_Keker_Redacted.pdf, 121650]                                           | 
| Lee                       | Edwin                      | Mayor                | 2015-05-13T00:00:00 | 2015-05-07T00:00:00 | 2015-05-07T00:00:00 | Jose S. Medeiros                                     | San Francisco Travel Foundation (City Hall Centennial Celebration) | 15000.00  | thi2-6wsq |           | 2015-05-13T00:00:00     | [application/pdf, qUnz86rc4-eQGBJbWgPo5svS0XYP3FN-wJ2tmv8F2Bs, 20150507_20150513_803_Lee_Edwin_Jose_S._Medeiros_Redacted.pdf, 121427]                                     | 
| Lee                       | Edwin                      | Mayor                | 2015-05-13T00:00:00 | 2015-05-07T00:00:00 | 2015-05-07T00:00:00 | Mr. and Mrs. Coulter (Coulter 2006 Management Trust) | San Francisco Travel Foundation (City Hall Centennial Celebration) | 100000.00 | thi2-6wsq |           | 2015-05-13T00:00:00     | [application/pdf, 65FlaIzfUmQMm9QLF5qewxCWQx4-e7paZ7SiDctnoVI, 20150507_20150513_803_Lee_Edwin_Mr._and_Mrs._Coulter_(Coulter_2006_Management_Trust)_Redacted.pdf, 121464] | 
```