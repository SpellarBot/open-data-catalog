# Economic Development Compliance: Chapter 380 Agreement Basic Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/economic-development-compliance-chapter-380-agreement-basic-information) |
| Metadata | [Link](https://data.austintexas.gov/api/views/pxe3-na7s) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/pxe3-na7s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/pxe3-na7s/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | pxe3-na7s |
| Name | Economic Development Compliance: Chapter 380 Agreement Basic Information |
| Created | 2014-02-10T19:46:31Z |
| Publication Date | 2016-12-05T18:37:27Z |

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | firm                              | Firm                              | text          | text          |
| Yes      | series tag     | project_description               | Project Description               | text          | text          |
| Yes      | time           | date_approved                     | Date Approved                     | calendar_date | calendar_date |
| Yes      | series tag     | city_council_ordinance_resolution | City Council Ordinance/Resolution | url           | url           |
| Yes      | series tag     | agreement                         | Agreement                         | url           | url           |
| Yes      | series tag     | amendment_documents               | Amendment Documents               | url           | url           |
| Yes      | series tag     | status                            | Status                            | text          | text          |
| Yes      | numeric metric | total_investment                  | Total Investment                  | money         | money         |
| Yes      | numeric metric | existing_jobs_retained            | Existing Jobs Retained            | number        | number        |
| Yes      | numeric metric | new_jobs_created                  | New Jobs Created                  | number        | number        |
| Yes      | numeric metric | total_jobs_commited               | Total Jobs                        | number        | number        |
| Yes      | numeric metric | average_wage                      | Average Wage                      | money         | money         |
| Yes      | series tag     | incentive_basis                   | Incentive Basis                   | text          | text          |
| Yes      | numeric metric | total_estimated_incentive         | Total Estimated Incentive         | money         | money         |
| Yes      | numeric metric | total_payments_issued             | Total Payments Issued             | money         | text          |
```

## Time Field

```ls
Value = date_approved
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pxe3-na7s d:2011-12-15T00:00:00.000Z t:city_council_ordinance_resolution=http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/farathane_res_20111215-090.pdf t:status="Company Retained in Austin, Agreement Inactive" t:firm="US Farathane" t:agreement=http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/US_Farathane_Agreement.pdf t:incentive_basis="40% property tax rebate" t:project_description="Manufacturing Facility" m:new_jobs_created=228 m:total_estimated_incentive=212695 m:total_payments_issued=0 m:total_investment=26900000 m:existing_jobs_retained=0 m:total_jobs_commited=228

series e:pxe3-na7s d:2011-04-12T00:00:00.000Z t:city_council_ordinance_resolution=http://austintexas.gov/sites/default/files/files/Redevelopment/ord_ebay.pdf t:status="Company Retained in Austin, Agreement Inactive" t:firm=eBay t:agreement=http://austintexas.gov/sites/default/files/files/Redevelopment/380_ebay.pdf t:incentive_basis="$250 per job per year" t:project_description="Data Services Expansion" m:new_jobs_created=1000 m:total_estimated_incentive=1206250 m:total_payments_issued=0 m:total_investment=4944651 m:existing_jobs_retained=0 m:total_jobs_commited=1000

series e:pxe3-na7s d:2010-12-09T00:00:00.000Z t:city_council_ordinance_resolution="http://www.ci.austin.tx.us/edims/document.cfm?id=146317" t:status="Company Retained in Austin, Agreement Inactive" t:firm=SunPower t:agreement=http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/SunPowerCh380_Eda.pdf t:incentive_basis="$233 per job per year" t:project_description="Operations Center" m:average_wage=70000 m:new_jobs_created=450 m:total_estimated_incentive=901710 m:total_payments_issued=0 m:total_investment=10000000 m:existing_jobs_retained=0 m:total_jobs_commited=450
```

## Meta Commands

```ls
metric m:total_investment p:long l:"Total Investment" d:"Includes real property and business personal property" t:dataTypeName=money

metric m:existing_jobs_retained p:integer l:"Existing Jobs Retained" t:dataTypeName=number

metric m:new_jobs_created p:integer l:"New Jobs Created" t:dataTypeName=number

metric m:total_jobs_commited p:integer l:"Total Jobs" d:"Includes new jobs created and jobs retained" t:dataTypeName=number

metric m:average_wage p:integer l:"Average Wage" t:dataTypeName=money

metric m:total_estimated_incentive p:double l:"Total Estimated Incentive" t:dataTypeName=money

metric m:total_payments_issued p:double l:"Total Payments Issued" t:dataTypeName=money

entity e:pxe3-na7s l:"Economic Development Compliance: Chapter 380 Agreement Basic Information" t:url=https://data.austintexas.gov/api/views/pxe3-na7s

property e:pxe3-na7s t:meta.view v:id=pxe3-na7s v:averageRating=0 v:name="Economic Development Compliance: Chapter 380 Agreement Basic Information"

property e:pxe3-na7s t:meta.view.owner v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:displayName="Melissa Alvarado"

property e:pxe3-na7s t:meta.view.tableauthor v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:roleName=editor v:displayName="Melissa Alvarado"
```

## Top Records

```ls
| firm                                                                                                                       | project_description                                                                                               | date_approved       | city_council_ordinance_resolution                                                                                                         | agreement                                                                                                                                                        | amendment_documents | status                                         | total_investment | existing_jobs_retained | new_jobs_created | total_jobs_commited | average_wage | incentive_basis                                                                                 | total_estimated_incentive | total_payments_issued | 
| ========================================================================================================================== | ================================================================================================================= | =================== | ========================================================================================================================================= | ================================================================================================================================================================ | =================== | ============================================== | ================ | ====================== | ================ | =================== | ============ | =============================================================================================== | ========================= | ===================== | 
| *Samsung Total Estimated Incentive=Estimation Before Expansion                                                             |                                                                                                                   |                     | [null, null]                                                                                                                              | [null, null]                                                                                                                                                     | [null, null]        |                                                |                  |                        |                  |                     |              |                                                                                                 |                           |                       | 
| **Friday Night Lights Total Estimated Incentive is actual incentive amount paid to the company as the project is complete. |                                                                                                                   |                     | [null, null]                                                                                                                              | [null, null]                                                                                                                                                     | [null, null]        |                                                |                  |                        |                  |                     |              |                                                                                                 |                           |                       | 
| US Farathane                                                                                                               | Manufacturing Facility                                                                                            | 2011-12-15T00:00:00 | [http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/farathane_res_20111215-090.pdf, Ordinance 20111215-090] | [http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/US_Farathane_Agreement.pdf, US Farathane Agreement]                            | [null, null]        | Company Retained in Austin, Agreement Inactive | 26900000         | 0                      | 228              | 228                 |              | 40% property tax rebate                                                                         | 212695.00                 | $0.00                 | 
| eBay                                                                                                                       | Data Services Expansion                                                                                           | 2011-04-12T00:00:00 | [http://austintexas.gov/sites/default/files/files/Redevelopment/ord_ebay.pdf, Ordinance 20110412-001]                                     | [http://austintexas.gov/sites/default/files/files/Redevelopment/380_ebay.pdf, eBay Agreement]                                                                    | [null, null]        | Company Retained in Austin, Agreement Inactive | 4944651          | 0                      | 1000             | 1000                |              | $250 per job per year                                                                           | 1206250.00                | $0.00                 | 
| SunPower                                                                                                                   | Operations Center                                                                                                 | 2010-12-09T00:00:00 | [http://www.ci.austin.tx.us/edims/document.cfm?id=146317, Ordinance 20101209-074]                                                         | [http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/SunPowerCh380_Eda.pdf, SunPower Agreement]                                     | [null, null]        | Company Retained in Austin, Agreement Inactive | 10000000         | 0                      | 450              | 450                 | 70000        | $233 per job per year                                                                           | 901710.00                 | $0.00                 | 
| Websense                                                                                                                   | Headquarters                                                                                                      | 2014-02-20T00:00:00 | [http://www.ci.austin.tx.us/edims/document.cfm?id=205801, Ordinance 20140220-001]                                                         | [http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/Websense/WebsenseCh380_Eda.pdf, Websense Agreement]                            | [null, null]        | Company Retained in Austin, Agreement Inactive | 9935000          | 4                      | 470              | 474                 | 82000        | $100 per job per year                                                                           | 438000                    | $0.00                 | 
| Dropbox                                                                                                                    | Sales and Operations Office                                                                                       | 2014-02-20T00:00:00 | [http://www.ci.austin.tx.us/edims/document.cfm?id=205802, Ordinance 20140220-002]                                                         | [http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/Dropbox/DropboxCh380eda.pdf, Dropbox Agreement]                                | [null, null]        | Company Retained in Austin, Agreement Inactive | 5500000          | 30                     | 170              | 200                 | 59000        | $150 per job per year                                                                           | 244500.00                 | $0.00                 | 
| Facebook                                                                                                                   | Sales and Operations Office                                                                                       | 2010-03-11T00:00:00 | [http://austintexas.gov/sites/default/files/files/Redevelopment/ordinance-facebook-20100311063.pdf, Ordinance 20100311-063]               | [http://austintexas.gov/sites/default/files/files/Redevelopment/ch380eda_facebook.pdf, Facebook Agreement]                                                       | [null, null]        | Company Retained in Austin, Agreement Inactive | 3150000          | 0                      | 200              | 200                 | 54000        | $100 per job per year Years 1-3; $125 per job per year Years 4-10                               | 200000.00                 | $0.00                 | 
| National Instruments                                                                                                       | Research and Development Facility; plus commitment to support 1,000 students per year with STEM education efforts | 2013-03-07T00:00:00 | [http://www.austintexas.gov/edims/document.cfm?id=185873, Ordinance 20130307-066]                                                         | [http://austintexas.gov/sites/default/files/files/EGRSO/Economic_Development_Agreement_between_CoA_and_National_Instruments.pdf, National Instruments Agreement] | [null, null]        | Company Retained in Austin, Agreement Inactive | 80000000         | 2440                   | 1000             | 3440                |              | 50% property tax rebate                                                                         | 1667575.00                | $0.00                 | 
| Apple                                                                                                                      | Operating Center                                                                                                  | 2012-03-22T00:00:00 | [http://www.ci.austin.tx.us/edims/document.cfm?id=166416, Ordinance 20120322-089]                                                         | [http://austintexas.gov/sites/default/files/files/Redevelopment/CH_380_Agreements/Apple_Eco_Dev_Agreement.PDF, Apple Agreement]                                  | [null, null]        | Active                                         | 282500000        | 3100                   | 3635             | 6735                | 63950        | 100% Years 1-6; 80% Years 7-10 if only Phase I completed; 100% Years 7-10 if Phase II completed | 8600000.00                | $0.00                 | 
```