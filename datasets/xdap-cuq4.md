# Campaign Finance - FPPC Form 497 - Late Contribution Report - Late Contributions Made

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-497-late-contribution-report-late-contributions-made-8b27b) |
| Metadata | [Link](https://data.sfgov.org/api/views/xdap-cuq4) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/xdap-cuq4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/xdap-cuq4/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | xdap-cuq4 |
| Name | Campaign Finance - FPPC Form 497 - Late Contribution Report - Late Contributions Made |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, fppc, form, 497, late, monetary, contribution, non-monetary |
| Created | 2012-04-29T03:05:10Z |
| Publication Date | 2017-01-25T19:03:24Z |

## Description

This dataset includes all itemized late contributions (cumulative $1,000 or more) e-filed on Fair Political Practices Commission (FPPC) Form 497 Late Contribution Report from 2008 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | filer_id       | Filer_ID       | text          | text          |
| Yes      | series tag     | filer_naml     | Filer_NamL     | text          | text          |
| Yes      | series tag     | report_num     | Report_Num     | text          | number        |
| Yes      | series tag     | committee_type | Committee_Type | text          | text          |
| Yes      | time           | rpt_date       | Rpt_Date       | calendar_date | calendar_date |
| No       |                | from_date      | From_Date      | calendar_date | calendar_date |
| No       |                | thru_date      | Thru_Date      | calendar_date | calendar_date |
| No       |                | elect_date     | Elect_Date     | calendar_date | calendar_date |
| Yes      | series tag     | rec_type       | Rec_Type       | text          | text          |
| Yes      | series tag     | form_type      | Form_Type      | text          | text          |
| Yes      | series tag     | tran_id        | Tran_ID        | text          | text          |
| Yes      | series tag     | entity_cd      | Entity_Cd      | text          | text          |
| Yes      | series tag     | enty_naml      | Enty_NamL      | text          | text          |
| Yes      | series tag     | enty_namf      | Enty_NamF      | text          | text          |
| Yes      | series tag     | enty_namt      | Enty_NamT      | text          | text          |
| Yes      | series tag     | enty_nams      | Enty_NamS      | text          | text          |
| Yes      | series tag     | enty_adr1      | Enty_Adr1      | text          | text          |
| Yes      | series tag     | enty_adr2      | Enty_Adr2      | text          | text          |
| Yes      | series tag     | enty_city      | Enty_City      | text          | text          |
| Yes      | series tag     | enty_st        | Enty_ST        | text          | text          |
| Yes      | series tag     | enty_zip4      | Enty_Zip4      | text          | text          |
| Yes      | series tag     | ctrib_emp      | Ctrib_Emp      | text          | text          |
| Yes      | series tag     | ctrib_occ      | Ctrib_Occ      | text          | text          |
| Yes      | numeric metric | ctrib_self     | Ctrib_Self     | number        | text          |
| No       |                | elec_date      | Elec_Date      | calendar_date | calendar_date |
| No       |                | ctrib_date     | Ctrib_Date     | calendar_date | calendar_date |
| No       |                | date_thru      | Date_Thru      | calendar_date | calendar_date |
| Yes      | numeric metric | amount         | Amount         | money         | money         |
| Yes      | series tag     | cmte_id        | Cmte_ID        | text          | text          |
| Yes      | series tag     | cand_naml      | Cand_NamL      | text          | text          |
| Yes      | series tag     | cand_namf      | Cand_NamF      | text          | text          |
| Yes      | series tag     | cand_namt      | Cand_NamT      | text          | text          |
| Yes      | series tag     | cand_nams      | Cand_NamS      | text          | text          |
| Yes      | series tag     | office_cd      | Office_Cd      | text          | text          |
| Yes      | series tag     | offic_dscr     | Offic_Dscr     | text          | text          |
| Yes      | series tag     | juris_cd       | Juris_Cd       | text          | text          |
| Yes      | series tag     | juris_dscr     | Juris_Dscr     | text          | text          |
| Yes      | series tag     | dist_no        | Dist_No        | text          | number        |
| Yes      | series tag     | off_s_h_cd     | Off_S_H_Cd     | text          | text          |
| Yes      | series tag     | bal_name       | Bal_Name       | text          | text          |
| Yes      | series tag     | bal_num        | Bal_Num        | text          | text          |
| Yes      | series tag     | bal_juris      | Bal_Juris      | text          | text          |
| Yes      | series tag     | memo_code      | Memo_Code      | text          | text          |
| Yes      | series tag     | memo_refno     | Memo_RefNo     | text          | text          |
| Yes      | series tag     | rpt_id_num     | Rpt_ID_Num     | text          | text          |
```

## Time Field

```ls
Value = rpt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = from_date,thru_date,elect_date,elec_date,ctrib_date,date_thru
```

## Data Commands

```ls
series e:xdap-cuq4 d:2016-05-17T00:00:00.000Z t:enty_zip4=94108 t:enty_city="San Francisco" t:enty_st=CA t:entity_cd=COM t:filer_naml="Kat Anderson for Democratic County Central Committee 2016" t:report_num=2 t:rpt_id_num=10 t:form_type=F497P1 t:enty_naml="San Francisco Democrats United for Progress, supporting 23 candidates for the 2016 San Francisco Democratic County Central Committee, including Tom A. Hsieh Jr." t:rec_type=S497 t:cmte_id=1385333 t:filer_id=1382851 t:tran_id=Z4aqmRfcnS6u m:amount=1005

series e:xdap-cuq4 d:2016-06-17T00:00:00.000Z t:enty_zip4=94114 t:cand_naml="GARY MCCOY" t:enty_city="SAN FRANCISCO" t:enty_st=CA t:entity_cd=COM t:office_cd=OTH t:dist_no=17 t:filer_naml="SAN FRANCISCO DEMOCRATS UNITED FOR PROGRESS, SUPPORTING 23 CANDIDATES FOR THE 2016 SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE, INCLUDING TOM A. HSIEH JR. (COMPLETE COMMITTEE NAME ATTACHED)" t:report_num=2 t:form_type=F497P2 t:juris_cd=ASM t:rpt_id_num=P16-DUP-15 t:enty_naml="GARY MCCOY FOR SFDCCC MEMBER 2016" t:cmte_id=1381741 t:rec_type=S497 t:filer_id=1385333 t:committee_type=RCP t:offic_dscr="DEMOCRATIC COUNTY CENTRAL COMMITTEE" t:tran_id=EDT621 m:amount=40

series e:xdap-cuq4 d:2016-09-28T00:00:00.000Z t:enty_zip4=94104 t:ctrib_occ="Advisory Director" t:enty_city="San Francisco" t:enty_st=CA t:entity_cd=IND t:enty_namf="John Spencer" t:filer_naml="San Franciscans Against Wasteful Spending, No on Propositions D, H, L & M" t:report_num=0 t:form_type=F497P1 t:rpt_id_num=644490-RE t:enty_naml="Wadsworth, Jr." t:rec_type=S497 t:ctrib_emp="Morgan Stanley" t:filer_id=1388893 t:committee_type=BMC t:tran_id=INC21 m:amount=15000
```

## Meta Commands

```ls
metric m:ctrib_self p:integer l:Ctrib_Self t:dataTypeName=number

metric m:amount p:double l:Amount t:dataTypeName=money

entity e:xdap-cuq4 l:"Campaign Finance - FPPC Form 497 - Late Contribution Report - Late Contributions Made" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/xdap-cuq4

property e:xdap-cuq4 t:meta.view v:id=xdap-cuq4 v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 497 - Late Contribution Report - Late Contributions Made" v:attribution="San Francisco Ethics Commission"

property e:xdap-cuq4 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:xdap-cuq4 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:xdap-cuq4 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                                                                                          | report_num | committee_type | rpt_date            | from_date | thru_date | elect_date          | rec_type | form_type | tran_id      | entity_cd | enty_naml                                                                                                                                                        | enty_namf    | enty_namt | enty_nams | enty_adr1 | enty_adr2 | enty_city     | enty_st | enty_zip4 | ctrib_emp      | ctrib_occ         | ctrib_self | elec_date           | ctrib_date          | date_thru | amount  | cmte_id | cand_naml     | cand_namf | cand_namt | cand_nams | office_cd | offic_dscr                          | juris_cd | juris_dscr | dist_no | off_s_h_cd | bal_name                                                                                            | bal_num | bal_juris | memo_code | memo_refno   | rpt_id_num | 
| ======== | =================================================================================================================================================================================================== | ========== | ============== | =================== | ========= | ========= | =================== | ======== | ========= | ============ | ========= | ================================================================================================================================================================ | ============ | ========= | ========= | ========= | ========= | ============= | ======= | ========= | ============== | ================= | ========== | =================== | =================== | ========= | ======= | ======= | ============= | ========= | ========= | ========= | ========= | =================================== | ======== | ========== | ======= | ========== | =================================================================================================== | ======= | ========= | ========= | ============ | ========== | 
| 1382851  | Kat Anderson for Democratic County Central Committee 2016                                                                                                                                           | 2          |                | 2016-05-17T00:00:00 |           |           | 2016-01-01T00:00:00 | S497     | F497P1    | Z4aqmRfcnS6u | COM       | San Francisco Democrats United for Progress, supporting 23 candidates for the 2016 San Francisco Democratic County Central Committee, including Tom A. Hsieh Jr. |              |           |           |           |           | San Francisco | CA      | 94108     |                |                   |            |                     | 2016-05-15T00:00:00 |           | 1005    | 1385333 |               |           |           |           |           |                                     |          |            |         |            |                                                                                                     |         |           |           |              | 10         | 
| 1385333  | SAN FRANCISCO DEMOCRATS UNITED FOR PROGRESS, SUPPORTING 23 CANDIDATES FOR THE 2016 SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE, INCLUDING TOM A. HSIEH JR. (COMPLETE COMMITTEE NAME ATTACHED) | 2          | RCP            | 2016-06-17T00:00:00 |           |           |                     | S497     | F497P2    | EDT621       | COM       | GARY MCCOY FOR SFDCCC MEMBER 2016                                                                                                                                |              |           |           |           |           | SAN FRANCISCO | CA      | 94114     |                |                   |            | 2016-06-07T00:00:00 | 2016-05-31T00:00:00 |           | 40      | 1381741 | GARY MCCOY    |           |           |           | OTH       | DEMOCRATIC COUNTY CENTRAL COMMITTEE | ASM      |            | 17      |            |                                                                                                     |         |           |           |              | P16-DUP-15 | 
| 1388893  | San Franciscans Against Wasteful Spending, No on Propositions D, H, L & M                                                                                                                           | 0          | BMC            | 2016-09-28T00:00:00 |           |           |                     | S497     | F497P1    | INC21        | IND       | Wadsworth, Jr.                                                                                                                                                   | John Spencer |           |           |           |           | San Francisco | CA      | 94104     | Morgan Stanley | Advisory Director |            |                     | 2016-09-27T00:00:00 |           | 15000   |         |               |           |           |           |           |                                     |          |            |         |            |                                                                                                     |         |           |           |              | 644490-RE  | 
| 1384146  | London Breed for Democratic County Central Committee 2016                                                                                                                                           | 0          | CTL            | 2016-05-13T00:00:00 |           |           |                     | S497     | F497P1    | INC101       | COM       | International Brotherhood of Electrical Workers Local Union 6                                                                                                    |              |           |           |           |           | San Francisco | CA      | 94117     |                |                   |            |                     | 2016-05-12T00:00:00 |           | 1000    | 921730  |               |           |           |           |           |                                     |          |            |         |            |                                                                                                     |         |           |           |              | 051216     | 
| 1378915  | San Francisco Tenants and Families for Affordable Housing, sponsored by community and labor organizations                                                                                           | 1          | RCP            | 2016-11-07T00:00:00 |           |           |                     | S497     | F497P2    | EDT822       | COM       | Yes on 55 - Californians for Budget Stability, Sponsored by Teachers, Health Care Providers, Doctors and Labor Organizations                                     |              |           |           |           |           | Sacramento    | CA      | 95814     |                |                   |            | 2016-11-08T00:00:00 | 2016-10-10T00:00:00 |           | 3673.02 | 1381382 |               |           |           |           |           |                                     |          |            |         |            | Tax Extension to Fund Education and Healthcare. Initiative Constitutional Amendment. Proposition 55 |         | Statewide |           |              | 19448      | 
| 1385333  | SAN FRANCISCO DEMOCRATS UNITED FOR PROGRESS, SUPPORTING 23 CANDIDATES FOR THE 2016 SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE, INCLUDING TOM A. HSIEH JR. (COMPLETE COMMITTEE NAME ATTACHED) | 2          | RCP            | 2016-06-17T00:00:00 |           |           |                     | S497     | F497P2    | EDT124       | COM       | SUPERVISOR MARK FARRELL FOR SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE 2016                                                                               |              |           |           |           |           | SAN FRANCISCO | CA      | 94108     |                |                   |            | 2016-06-07T00:00:00 | 2016-05-26T00:00:00 |           | 320     | 1384000 | MARK FARRELL  |           |           |           | OTH       | DEMOCRATIC COUNTY CENTRAL COMMITTEE | ASM      |            | 19      |            |                                                                                                     |         |           |           | EDT:S497:124 | P16-DUP-15 | 
| 1317554  | San Francisco Police Officers Association Issues PAC                                                                                                                                                | 0          | RCP            | 2016-06-30T00:00:00 |           |           |                     | S497     | F497P2    | EXP104185    | COM       | Californians for Death Penalty Reform and Savings                                                                                                                |              |           |           |           |           | Irvine        | CA      | 92614     |                |                   |            |                     | 2016-06-30T00:00:00 |           | 50000   | 1346266 |               |           |           |           |           |                                     |          |            |         |            | Death Penalty Reform and Savings Act of 2016 Measure (15-0096)                                      |         | Statewide |           |              | 17526      | 
| 1385955  | Tom Hsieh for San Francisco Democratic County Central Committee (17th Dist) 2016                                                                                                                    | 0          | CTL            | 2016-06-06T00:00:00 |           |           |                     | S497     | F497P1    | NON12        | COM       | San Francisco Democrats United for Progress                                                                                                                      |              |           |           |           |           | San Francisco | CA      | 94108     |                |                   |            |                     | 2016-05-13T00:00:00 |           | 1.5     | 1385333 |               |           |           |           |           |                                     |          |            |         |            |                                                                                                     |         |           |           |              | 20160606-1 | 
| 1384144  | Affordable San Francisco for All, Yes on Proposition C, an affordable housing coalition sponsored by Yerba Buena Consortium                                                                         | 0          | BMC            | 2016-05-13T00:00:00 |           |           |                     | S497     | F497P1    | NON86        | COM       | San Francisco Tenants and Families for Affordable Housing, Sponsored by Community and Labor Organizations                                                        |              |           |           |           |           | San Francisco | CA      | 94133     |                |                   |            |                     | 2016-05-11T00:00:00 |           | 2223.34 | 1378915 |               |           |           |           |           |                                     |          |            |         |            |                                                                                                     |         |           |           |              | 051116-1   | 
| 1385333  | SAN FRANCISCO DEMOCRATS UNITED FOR PROGRESS, SUPPORTING 23 CANDIDATES FOR THE 2016 SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE, INCLUDING TOM A. HSIEH JR. (COMPLETE COMMITTEE NAME ATTACHED) | 2          | RCP            | 2016-06-17T00:00:00 |           |           |                     | S497     | F497P2    | EDT95        | COM       | RACHEL NORTON FOR DEMOCRATIC COUNTY CENTRAL COMMITTEE 2016                                                                                                       |              |           |           |           |           | SAN FRANCISCO | CA      | 94118     |                |                   |            | 2016-06-07T00:00:00 | 2016-04-30T00:00:00 |           | 380     | 1382950 | RACHEL NORTON |           |           |           | OTH       | DEMOCRATIC COUNTY CENTRAL COMMITTEE | ASM      |            | 19      |            |                                                                                                     |         |           |           |              | P16-DUP-03 | 
```