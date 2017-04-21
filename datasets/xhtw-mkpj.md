# Campaign Finance - Credits Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-credits-dataset) |
| Metadata | [Link](https://data.austintexas.gov/api/views/xhtw-mkpj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/xhtw-mkpj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/xhtw-mkpj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | xhtw-mkpj |
| Name | Campaign Finance - Credits Dataset |
| Created | 2016-10-25T16:56:57Z |
| Publication Date | 2016-10-27T16:21:50Z |

## Description

This table lists any credit, interest, rebate, refund, reimbursement, or return of a deposit fee resulting from the use of a political contribution or an asset purchased with a political contribution reported on the Texas Ethics Commission C/OH Form, Schedule K. For more information about credits, please visit the Texas Ethic Commission's instruction guide here:
https://www.ethics.state.tx.us/forms/COH_ins.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | payer                         | Payer                         | text          | text          |
| Yes      | series tag     | recipient                     | Recipient                     | text          | text          |
| Yes      | time           | credit_date                   | Credit_Date                   | calendar_date | calendar_date |
| Yes      | numeric metric | credit_amount                 | Credit_Amount                 | number        | text          |
| Yes      | series tag     | payer_type                    | Payer_Type                    | text          | text          |
| No       |                | payer_address                 | Payer_Address                 | text          | text          |
| Yes      | series tag     | payer_city_state_zip          | Payer_City_State_Zip          | text          | text          |
| No       |                | credit_year                   | Credit_Year                   | number        | text          |
| Yes      | series tag     | political_contribution_return | Political_Contribution_Return | text          | text          |
| Yes      | series tag     | transaction_type              | Transaction_Type              | text          | text          |
| No       |                | date_reported                 | Date_Reported                 | calendar_date | calendar_date |
| Yes      | series tag     | report_filed                  | Report_Filed                  | text          | text          |
| Yes      | series tag     | in_kind_description           | In_Kind_Description           | text          | text          |
| Yes      | series tag     | out_of_state_pac              | Out_of_State_PAC              | text          | text          |
| Yes      | series tag     | correction                    | Correction                    | text          | text          |
| Yes      | series tag     | view_report                   | View_Report                   | url           | url           |
| Yes      | series tag     | transaction_id                | TRANSACTION_ID                | text          | text          |
```

## Time Field

```ls
Value = credit_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = payer_address,date_reported,credit_year
```

## Data Commands

```ls
series e:xhtw-mkpj d:2016-07-07T00:00:00.000Z t:report_filed="C/OH: Candidate/Officeholder Campaign Finance Report" t:payer_type=Entity t:payer="The Camarillo Group" t:political_contribution_return=X t:transaction_type="Interest, Credits, Gains, Refunds, and Contributions Returned to Filer" t:payer_city_state_zip="Austin, TX, 78766" t:in_kind_description="contribution from prior report returned (inadvertantly written on closed account" t:transaction_id=R20161012171011-K0001 t:recipient="Garza, Delia" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=264498" m:credit_amount=150

series e:xhtw-mkpj d:2016-11-08T00:00:00.000Z t:report_filed="SPAC: Specific-Purpose Committee Campaign Finance Report" t:payer_type=Entity t:payer="Macho Marketing" t:transaction_type="Interest, Credits, Gains, Refunds, and Contributions Returned to Filer" t:payer_city_state_zip="Austin, TX, 78752" t:in_kind_description="in-kind refund" t:transaction_id=R20170117131413-K0001 t:recipient="Sensible Transportation Solutions for Austin" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=269900" m:credit_amount=6235

series e:xhtw-mkpj d:2016-11-01T00:00:00.000Z t:report_filed="SPAC: Specific-Purpose Committee Campaign Finance Report" t:payer_type=Entity t:payer="Bike Share of Austin" t:transaction_type="Interest, Credits, Gains, Refunds, and Contributions Returned to Filer" t:payer_city_state_zip="Austin, TX, 78701" t:transaction_id=R20170123091851-K0001 t:recipient="Austin Forward" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=269922" m:credit_amount=6002.62
```

## Meta Commands

```ls
metric m:credit_amount p:float l:Credit_Amount d:"The exact dollar amount of the credit/gain/refund/returned contribution, or interest." t:dataTypeName=number

entity e:xhtw-mkpj l:"Campaign Finance - Credits Dataset" t:url=https://data.austintexas.gov/api/views/xhtw-mkpj

property e:xhtw-mkpj t:meta.view v:id=xhtw-mkpj v:averageRating=0 v:name="Campaign Finance - Credits Dataset"

property e:xhtw-mkpj t:meta.view.owner v:id=swky-es5z v:profileImageUrlMedium=/api/users/swky-es5z/profile_images/THUMB v:profileImageUrlLarge=/api/users/swky-es5z/profile_images/LARGE v:screenName="Grace Kretschmer" v:profileImageUrlSmall=/api/users/swky-es5z/profile_images/TINY v:displayName="Grace Kretschmer"

property e:xhtw-mkpj t:meta.view.tableauthor v:id=swky-es5z v:profileImageUrlMedium=/api/users/swky-es5z/profile_images/THUMB v:profileImageUrlLarge=/api/users/swky-es5z/profile_images/LARGE v:screenName="Grace Kretschmer" v:profileImageUrlSmall=/api/users/swky-es5z/profile_images/TINY v:roleName=editor v:displayName="Grace Kretschmer"
```

## Top Records

```ls
| payer                | recipient                                    | credit_date         | credit_amount | payer_type | payer_address          | payer_city_state_zip | credit_year | political_contribution_return | transaction_type                                                       | date_reported       | report_filed                                             | in_kind_description                                                              | out_of_state_pac | correction | view_report                                                            | transaction_id        | 
| ==================== | ============================================ | =================== | ============= | ========== | ====================== | ==================== | =========== | ============================= | ====================================================================== | =================== | ======================================================== | ================================================================================ | ================ | ========== | ====================================================================== | ===================== | 
| The Camarillo Group  | Garza, Delia                                 | 2016-07-07T00:00:00 | 150.00        | Entity     | PO Box 9632            | Austin, TX, 78766    | 2016        | X                             | Interest, Credits, Gains, Refunds, and Contributions Returned to Filer | 2016-10-11T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | contribution from prior report returned (inadvertantly written on closed account |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=264498, View Report] | R20161012171011-K0001 | 
| Macho Marketing      | Sensible Transportation Solutions for Austin | 2016-11-08T00:00:00 | 6235.00       | Entity     | 6757 Airport Blvd.     | Austin, TX, 78752    | 2016        |                               | Interest, Credits, Gains, Refunds, and Contributions Returned to Filer | 2017-01-17T00:00:00 | SPAC: Specific-Purpose Committee Campaign Finance Report | in-kind refund                                                                   |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=269900, View Report] | R20170117131413-K0001 | 
| Bike Share of Austin | Austin Forward                               | 2016-11-01T00:00:00 | 6002.62       | Entity     | 1000 Brazos St Ste 100 | Austin, TX, 78701    | 2016        |                               | Interest, Credits, Gains, Refunds, and Contributions Returned to Filer | 2017-01-17T00:00:00 | SPAC: Specific-Purpose Committee Campaign Finance Report |                                                                                  |                  |            | [http://www.austintexas.gov/edims/document.cfm?id=269922, View Report] | R20170123091851-K0001 | 
```