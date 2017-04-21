# Campaign Finance - Contributions Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-contributions-dataset) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3kfv-biw6) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3kfv-biw6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3kfv-biw6/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3kfv-biw6 |
| Name | Campaign Finance - Contributions Dataset |
| Category | Financial |
| Created | 2016-08-17T18:59:59Z |
| Publication Date | 2016-10-31T15:09:44Z |

## Description

This dataset lists all contributions and pledges received by candidates, officeholders and political committees on data files submitted per City Code Chapter 2-2-26.

For a complete listing of each column heading, please see the field listing here: http://www.austintexas.gov/edims/document.cfm?id=262464

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | donor                     | Donor                     | text          | text          |
| Yes      | series tag     | recipient                 | Recipient                 | text          | text          |
| Yes      | numeric metric | contribution_amount       | Contribution_Amount       | money         | money         |
| Yes      | time           | contribution_date         | Contribution_Date         | calendar_date | calendar_date |
| Yes      | series tag     | donor_type                | Donor_Type                | text          | text          |
| No       |                | donor_address             | Donor_Address             | text          | text          |
| Yes      | series tag     | city_state_zip            | City_State_Zip            | text          | text          |
| No       |                | contribution_year         | Contribution_Year         | number        | text          |
| Yes      | series tag     | donor_reported_occupation | Donor_Reported_Occupation | text          | text          |
| Yes      | series tag     | donor_reported_employer   | Donor_Reported_Employer   | text          | text          |
| Yes      | series tag     | contribution_type         | Contribution_Type         | text          | text          |
| No       |                | date_reported             | Date_Reported             | calendar_date | calendar_date |
| Yes      | series tag     | report_filed              | Report_Filed              | text          | text          |
| Yes      | series tag     | in_kind_description       | In_Kind_Description       | text          | text          |
| Yes      | series tag     | out_of_state_pac          | Out_of_State_PAC          | text          | text          |
| Yes      | series tag     | correction                | Correction                | text          | text          |
| Yes      | series tag     | view_report               | View_Report               | url           | url           |
| Yes      | series tag     | transaction_id            | TRANSACTION_ID            | text          | text          |
```

## Time Field

```ls
Value = contribution_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = donor_address,date_reported,contribution_year
```

## Data Commands

```ls
series e:3kfv-biw6 d:2015-07-16T00:00:00.000Z t:report_filed="C/OH: Candidate/Officeholder Campaign Finance Report" t:city_state_zip="Austin, TX, 78741" t:donor="Albert, David" t:contribution_type="Monetary Political Contribution" t:donor_type=Individual t:transaction_id=R20160125164251-A0001 t:recipient="Casar, Gregorio E. ""Greg""" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=246589" m:contribution_amount=250

series e:3kfv-biw6 d:2016-01-05T00:00:00.000Z t:report_filed="GPAC: General-Purpose Committee Campaign Finance Report" t:city_state_zip="Austin, TX, 78723" t:donor="Ko, Ramey" t:donor_reported_occupation=Attorney t:donor_reported_employer="Jung Ko PLLC" t:contribution_type="Monetary Political Contribution" t:donor_type=Individual t:transaction_id=R20160715174520-A0002 t:recipient="Stonewall Democrats of Austin" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=258187" m:contribution_amount=60

series e:3kfv-biw6 d:2016-05-13T00:00:00.000Z t:report_filed="C/OH: Candidate/Officeholder Campaign Finance Report" t:city_state_zip="Austin, TX, 78703" t:donor="Neavel, Nancy" t:contribution_type="Monetary Political Contribution" t:donor_type=Individual t:transaction_id=R20160715175240-A0014 t:recipient="Casar, Gregorio E. ""Greg""" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=258180" m:contribution_amount=50
```

## Meta Commands

```ls
metric m:contribution_amount p:integer l:Contribution_Amount t:dataTypeName=money

entity e:3kfv-biw6 l:"Campaign Finance - Contributions Dataset" t:url=https://data.austintexas.gov/api/views/3kfv-biw6

property e:3kfv-biw6 t:meta.view v:id=3kfv-biw6 v:category=Financial v:averageRating=0 v:name="Campaign Finance - Contributions Dataset"

property e:3kfv-biw6 t:meta.view.owner v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:displayName="Kathryn Darnall"

property e:3kfv-biw6 t:meta.view.tableauthor v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```

## Top Records

```ls
| donor           | recipient                     | contribution_amount | contribution_date   | donor_type | donor_address                 | city_state_zip     | contribution_year | donor_reported_occupation | donor_reported_employer | contribution_type               | date_reported       | report_filed                                            | in_kind_description | out_of_state_pac | correction | view_report                                                            | transaction_id        | 
| =============== | ============================= | =================== | =================== | ========== | ============================= | ================== | ================= | ========================= | ======================= | =============================== | =================== | ======================================================= | =================== | ================ | ========== | ====================================================================== | ===================== | 
| Albert, David   | Casar, Gregorio E. "Greg"     | 250                 | 2015-07-16T00:00:00 | Individual | 1101 Grove Blvd, #703         | Austin, TX, 78741  | 2015              |                           |                         | Monetary Political Contribution | 2016-01-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=246589, View Report] | R20160125164251-A0001 | 
| Ko, Ramey       | Stonewall Democrats of Austin | 60                  | 2016-01-05T00:00:00 | Individual | 4504 Ruiz St                  | Austin, TX, 78723  | 2016              | Attorney                  | Jung Ko PLLC            | Monetary Political Contribution | 2016-07-15T00:00:00 | GPAC: General-Purpose Committee Campaign Finance Report |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] | R20160715174520-A0002 | 
| Neavel, Nancy   | Casar, Gregorio E. "Greg"     | 50                  | 2016-05-13T00:00:00 | Individual | 47 Woodstone Sq               | Austin, TX, 78703  | 2016              |                           |                         | Monetary Political Contribution | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=258180, View Report] | R20160715175240-A0014 | 
| Himert, Norma   | Casar, Gregorio E. "Greg"     | 25                  | 2016-05-13T00:00:00 | Individual | 1704 Meander                  | Austin, TX, 78721  | 2016              |                           |                         | Monetary Political Contribution | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=258180, View Report] | R20160715175240-A0015 | 
| Bukstein, David | Flannigan, James T. "Jimmy"   | 40                  | 2016-06-12T00:00:00 | Individual | 1812 Airole Way               | Austin, TX, 78704  | 2016              |                           |                         | Monetary Political Contribution | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=258182, View Report] | R20160715180436-A0082 | 
| Tresca, Ina Ka  | Flannigan, James T. "Jimmy"   | 50                  | 2016-06-04T00:00:00 | Individual | 12510 Split Rail Pkwy.        | Austin, TX, 78750  | 2016              |                           |                         | Monetary Political Contribution | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=258182, View Report] | R20160715180436-A0111 | 
| Smith, Chuck    | Flannigan, James T. "Jimmy"   | 100                 | 2016-06-29T00:00:00 | Individual | 1713 Newfield Ln              | Austin, TX, 78703  | 2016              |                           |                         | Monetary Political Contribution | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=258182, View Report] | R20160715180436-A0169 | 
| Chapman, Paul   | Casar, Gregorio E. "Greg"     | 250                 | 2015-08-15T00:00:00 | Individual | 2121 Brentwood Dr.            | Houston, TX, 77019 | 2015              |                           |                         | Monetary Political Contribution | 2016-01-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=246589, View Report] | R20160125164251-A0002 | 
| Keshet, Dan     | Flannigan, James T. "Jimmy"   | 350                 | 2016-05-12T00:00:00 | Individual | 1007 S Congress Ave, Unit 315 | Austin, TX, 78704  | 2016              | Computer programmer       | Qcue, Inc               | Monetary Political Contribution | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=258182, View Report] | R20160715180436-A0298 | 
| Orbach, Ray     | Gallo, Sheri P.               | 150                 | 2016-06-14T00:00:00 | Individual | 4004 Petra Path               | Austin, TX, 78731  | 2016              |                           |                         | Monetary Political Contribution | 2016-07-14T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report    |                     |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=258109, View Report] | R20160715181229-A0078 | 
```