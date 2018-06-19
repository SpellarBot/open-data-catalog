# Campaign Finance - FPPC Form 460 - Schedule C - Non-Monetary Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-c-non-monetary-contributions-f4184) |
| Metadata | [Link](https://data.sfgov.org/api/views/k76b-4yme) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/k76b-4yme/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/k76b-4yme/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | k76b-4yme |
| Name | Campaign Finance - FPPC Form 460 - Schedule C - Non-Monetary Contributions |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, in-kind, non-monetary, contributions, fppc, form, 460 |
| Created | 2012-04-30T03:29:11Z |
| Publication Date | 2014-08-21T09:32:50Z |

## Description

This dataset includes all itemized non-monetary contributions ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "C" Non-Monetary Contributions from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | filer_id               | Filer_ID               | text          | text          |
| Yes      | series tag     | filer_naml             | Filer_NamL             | text          | text          |
| Yes      | series tag     | report_num             | Report_Num             | text          | number        |
| Yes      | series tag     | committee_type         | Committee_Type         | text          | text          |
| No       |                | rpt_date               | Rpt_Date               | calendar_date | calendar_date |
| Yes      | time           | from_date              | From_Date              | calendar_date | calendar_date |
| No       |                | thru_date              | Thru_Date              | calendar_date | calendar_date |
| No       |                | elect_date             | Elect_Date             | calendar_date | calendar_date |
| Yes      | series tag     | tblcover_office_cd     | tblCover_Office_Cd     | text          | text          |
| Yes      | series tag     | tblcover_offic_dscr    | tblCover_Offic_Dscr    | text          | text          |
| Yes      | series tag     | rec_type               | Rec_Type               | text          | text          |
| Yes      | series tag     | form_type              | Form_Type              | text          | text          |
| Yes      | series tag     | tran_id                | Tran_ID                | text          | text          |
| Yes      | series tag     | entity_cd              | Entity_Cd              | text          | text          |
| Yes      | series tag     | tran_naml              | Tran_NamL              | text          | text          |
| Yes      | series tag     | tran_namf              | Tran_NamF              | text          | text          |
| Yes      | series tag     | tran_namt              | Tran_NamT              | text          | text          |
| Yes      | series tag     | tran_nams              | Tran_NamS              | text          | text          |
| Yes      | series tag     | tran_adr1              | Tran_Adr1              | text          | text          |
| Yes      | series tag     | tran_adr2              | Tran_Adr2              | text          | text          |
| Yes      | series tag     | tran_city              | Tran_City              | text          | text          |
| Yes      | series tag     | tran_state             | Tran_State             | text          | text          |
| Yes      | series tag     | tran_zip4              | Tran_Zip4              | text          | text          |
| Yes      | series tag     | tran_emp               | Tran_Emp               | text          | text          |
| Yes      | series tag     | tran_occ               | Tran_Occ               | text          | text          |
| Yes      | series tag     | tran_self              | Tran_Self              | text          | text          |
| Yes      | series tag     | tran_type              | Tran_Type              | text          | text          |
| No       |                | tran_date              | Tran_Date              | calendar_date | calendar_date |
| No       |                | tran_date1             | Tran_Date1             | calendar_date | calendar_date |
| Yes      | numeric metric | tran_amt1              | Tran_Amt1              | money         | money         |
| Yes      | numeric metric | tran_amt2              | Tran_Amt2              | money         | money         |
| Yes      | series tag     | tran_dscr              | Tran_Dscr              | text          | text          |
| Yes      | series tag     | cmte_id                | Cmte_ID                | text          | text          |
| Yes      | series tag     | tres_naml              | Tres_NamL              | text          | text          |
| Yes      | series tag     | tres_namf              | Tres_NamF              | text          | text          |
| Yes      | series tag     | tres_namt              | Tres_NamT              | text          | text          |
| Yes      | series tag     | tres_nams              | Tres_NamS              | text          | text          |
| Yes      | series tag     | tres_adr1              | Tres_Adr1              | text          | text          |
| Yes      | series tag     | tres_adr2              | Tres_Adr2              | text          | text          |
| Yes      | series tag     | tres_city              | Tres_City              | text          | text          |
| Yes      | series tag     | tres_state             | Tres_State             | text          | text          |
| Yes      | series tag     | tres_zip               | Tres_Zip               | text          | text          |
| Yes      | series tag     | intr_naml              | Intr_NamL              | text          | text          |
| Yes      | series tag     | intr_namf              | Intr_NamF              | text          | text          |
| Yes      | series tag     | intr_namt              | Intr_NamT              | text          | text          |
| Yes      | series tag     | intr_nams              | Intr_NamS              | text          | text          |
| Yes      | series tag     | intr_adr1              | Intr_Adr1              | text          | text          |
| Yes      | series tag     | intr_adr2              | Intr_Adr2              | text          | text          |
| Yes      | series tag     | intr_city              | Intr_City              | text          | text          |
| Yes      | series tag     | intr_state             | Intr_State             | text          | text          |
| Yes      | series tag     | intr_zip4              | Intr_Zip4              | text          | text          |
| Yes      | series tag     | intr_emp               | Intr_Emp               | text          | text          |
| Yes      | series tag     | intr_occ               | Intr_Occ               | text          | text          |
| Yes      | series tag     | intr_self              | Intr_Self              | text          | text          |
| Yes      | series tag     | cand_naml              | Cand_NamL              | text          | text          |
| Yes      | series tag     | cand_namf              | Cand_NamF              | text          | text          |
| Yes      | series tag     | cand_namt              | Cand_NamT              | text          | text          |
| Yes      | series tag     | cand_nams              | Cand_NamS              | text          | text          |
| Yes      | series tag     | tbldetltran_office_cd  | tblDetlTran_Office_Cd  | text          | text          |
| Yes      | series tag     | tbldetltran_offic_dscr | tblDetlTran_Offic_Dscr | text          | text          |
| Yes      | series tag     | juris_cd               | Juris_Cd               | text          | text          |
| Yes      | series tag     | juris_dscr             | Juris_Dscr             | text          | text          |
| Yes      | series tag     | dist_no                | Dist_No                | text          | text          |
| Yes      | series tag     | off_s_h_cd             | Off_S_H_Cd             | text          | text          |
| Yes      | series tag     | bal_name               | Bal_Name               | text          | text          |
| Yes      | series tag     | bal_num                | Bal_Num                | text          | text          |
| Yes      | series tag     | bal_juris              | Bal_Juris              | text          | text          |
| Yes      | series tag     | sup_opp_cd             | Sup_Opp_Cd             | text          | text          |
| Yes      | series tag     | memo_code              | Memo_Code              | text          | text          |
| Yes      | series tag     | memo_refno             | Memo_RefNo             | text          | text          |
| Yes      | series tag     | bakref_tid             | BakRef_TID             | text          | text          |
| Yes      | series tag     | xref_schnm             | XRef_SchNm             | text          | text          |
| Yes      | series tag     | xref_match             | XRef_Match             | text          | text          |
| Yes      | series tag     | loan_rate              | Loan_Rate              | text          | text          |
| Yes      | series tag     | int_cmteid             | Int_CmteId             | text          | text          |
```

## Time Field

```ls
Value = from_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = rpt_date,thru_date,elect_date,tran_date,tran_date1
```

## Data Commands

```ls
series e:k76b-4yme d:2016-05-22T00:00:00.000Z t:tran_state=CA t:tran_city="San Francisco" t:tran_self=n t:entity_cd=COM t:filer_naml="Aaron Peskin for Democratic County Central Committee 2016" t:intr_self=n t:tran_naml="San Francisco Tenants and Families for Affordable Housing, Sponsored by Community and Labor Organizations" t:report_num=1 t:tran_dscr=Postcard t:tran_zip4=94133 t:form_type=C t:cmte_id=1378915 t:rec_type=RCPT t:filer_id=1384150 t:committee_type=CTL t:tran_id=NON71 m:tran_amt2=2057.47 m:tran_amt1=56.32

series e:k76b-4yme d:2016-01-01T00:00:00.000Z t:tran_state=CA t:tran_city="San Francisco" t:tran_self=n t:entity_cd=COM t:filer_naml="Rachel Norton for Democratic County Central Committee 2016" t:intr_self=n t:tran_naml="San Francisco Democrats United for Progress" t:report_num=0 t:tran_dscr="phone banking" t:tran_zip4=94108 t:form_type=C t:cmte_id=1385333 t:rec_type=RCPT t:filer_id=1382950 t:committee_type=CTL t:tran_id=Suvp8GTcEQXt m:tran_amt2=5135.82 m:tran_amt1=1.5

series e:k76b-4yme d:2016-01-01T00:00:00.000Z t:tran_state=CA t:tran_city=Oakland t:tran_self=n t:entity_cd=COM t:filer_naml="Yes on Prop W, Fair Share for Free City College and Stronger SF Services, a coalition of educators, community and labor organizations. Major funding by American Federation of Teachers 2121 COPE Issues" t:intr_self=n t:tran_naml="Service Employees International Union Local 1021 Issues PAC" t:report_num=0 t:tran_dscr="Walk Piece" t:tran_zip4=94609 t:form_type=C t:cmte_id=1296947 t:rec_type=RCPT t:filer_id=1389010 t:committee_type=BMC t:tran_id=NON44 m:tran_amt2=277.96 m:tran_amt1=240.67
```

## Meta Commands

```ls
metric m:tran_amt1 p:double l:Tran_Amt1 t:dataTypeName=money

metric m:tran_amt2 p:double l:Tran_Amt2 t:dataTypeName=money

entity e:k76b-4yme l:"Campaign Finance - FPPC Form 460 - Schedule C - Non-Monetary Contributions" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/k76b-4yme

property e:k76b-4yme t:meta.view v:id=k76b-4yme v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule C - Non-Monetary Contributions" v:attribution="San Francisco Ethics Commission"

property e:k76b-4yme t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:k76b-4yme t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:k76b-4yme t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                                                                                               | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | tran_naml                                                                                                 | tran_namf | tran_namt | tran_nams | tran_adr1 | tran_adr2 | tran_city     | tran_state | tran_zip4 | tran_emp      | tran_occ               | tran_self | tran_type | tran_date           | tran_date1 | tran_amt1 | tran_amt2 | tran_dscr                                                               | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_state | tres_zip | intr_naml | intr_namf | intr_namt | intr_nams | intr_adr1 | intr_adr2 | intr_city | intr_state | intr_zip4 | intr_emp | intr_occ | intr_self | cand_naml | cand_namf | cand_namt | cand_nams | tbldetltran_office_cd | tbldetltran_offic_dscr | juris_cd | juris_dscr | dist_no | off_s_h_cd | bal_name | bal_num | bal_juris | sup_opp_cd | memo_code | memo_refno | bakref_tid | xref_schnm | xref_match | loan_rate | int_cmteid | 
| ======== | ======================================================================================================================================================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | ========================================================================================================= | ========= | ========= | ========= | ========= | ========= | ============= | ========== | ========= | ============= | ====================== | ========= | ========= | =================== | ========== | ========= | ========= | ======================================================================= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ======== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========= | ======== | ======== | ========= | ========= | ========= | ========= | ========= | ===================== | ====================== | ======== | ========== | ======= | ========== | ======== | ======= | ========= | ========== | ========= | ========== | ========== | ========== | ========== | ========= | ========== | 
| 1384150  | Aaron Peskin for Democratic County Central Committee 2016                                                                                                                                                | 1          | CTL            | 2016-09-16T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | RCPT     | C         | NON71        | COM       | San Francisco Tenants and Families for Affordable Housing, Sponsored by Community and Labor Organizations |           |           |           |           |           | San Francisco | CA         | 94133     |               |                        | n         |           | 2016-06-04T00:00:00 |            | 56.32     | 2057.47   | Postcard                                                                | 1378915 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1382950  | Rachel Norton for Democratic County Central Committee 2016                                                                                                                                               | 0          | CTL            | 2016-08-06T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | RCPT     | C         | Suvp8GTcEQXt | COM       | San Francisco Democrats United for Progress                                                               |           |           |           |           |           | San Francisco | CA         | 94108     |               |                        | n         |           | 2016-05-13T00:00:00 |            | 1.5       | 5135.82   | phone banking                                                           | 1385333 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1389010  | Yes on Prop W, Fair Share for Free City College and Stronger SF Services, a coalition of educators, community and labor organizations. Major funding by American Federation of Teachers 2121 COPE Issues | 0          | BMC            | 2016-09-29T00:00:00 | 2016-01-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | C         | NON44        | COM       | Service Employees International Union Local 1021 Issues PAC                                               |           |           |           |           |           | Oakland       | CA         | 94609     |               |                        | n         |           | 2016-09-17T00:00:00 |            | 240.67    | 277.96    | Walk Piece                                                              | 1296947 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1388075  | Save City College with major funding by the Foundation of City College of San Francisco - Yes on B                                                                                                       | 1          | BMC            | 2016-10-12T00:00:00 | 2016-01-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | C         | NON38        | COM       | Service Employees International Union Local 1021 Issues PAC                                               |           |           |           |           |           | Oakland       | CA         | 94609     |               |                        | n         |           | 2016-09-24T00:00:00 |            | 11.9      | 198.53    | Walk Expenses                                                           | 1296947 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1382499  | Bevan Dufty for Democratic County Central Committee 2016                                                                                                                                                 | 1          | CTL            | 2016-10-24T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | RCPT     | C         | wTgeRJqdkQbJ | IND       | Reilly                                                                                                    | Clinton   |           |           |           |           | San Francisco | CA         | 94104     | Self-employed | Businessman            | n         |           | 2016-06-10T00:00:00 |            | 2500      | 2500      | Appearance on Slate Mailer for Affordable Housing Alliance, ID # 594003 |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1384150  | Aaron Peskin for Democratic County Central Committee 2016                                                                                                                                                | 0          | CTL            | 2016-04-27T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2016-06-07T00:00:00 |                    |                     | RCPT     | C         | NON8         | IND       | O'Donoghue                                                                                                | Michael   |           |           |           |           | San Francisco | CA         | 94115     | Self-Employed | Real Estate Consultant | n         |           | 2016-04-19T00:00:00 |            | 4000      | 4000      | In-kind contribution of appearance on slate mailer                      |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383170  | Wade Woods for Democratic County Central Committee 2016                                                                                                                                                  | 0          | CTL            | 2016-05-31T00:00:00 | 2016-04-24T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | RCPT     | C         | XTVTkpRpZB1F | OTH       | San Francisco Tenants and Families for Affordable Housing Sponsored By Community and Labor Organizations  |           |           |           |           |           | San Francisco | CA         | 94133     |               |                        | n         |           | 2016-05-04T00:00:00 |            | 796.59    | 796.59    | Phonebank & Consulting                                                  |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1382480  | Rafael Mandelman for the Democratic County Central Committee 2016                                                                                                                                        | 2          | CTL            | 2016-10-26T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-10-26T00:00:00 |                    |                     | RCPT     | C         | mH1IUCLWzsh8 | COM       | SAN FRANCISCO TENANTS AND FAMILIES FOR AFFORDABLE HOUSING, SPONSORED BY COMMUNITY AND LABOR ORGANIZATIONS |           |           |           |           |           | San Francisco | CA         | 94133     |               |                        | n         |           | 2016-05-23T00:00:00 |            | 143.06    | 2546.58   | Payroll (Final)5/22/16                                                  | 1378915 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1384752  | Cindy Wu for Member, SF DCCC 2016                                                                                                                                                                        | 1          | CTL            | 2016-08-03T00:00:00 | 2016-04-24T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | RCPT     | C         | Yuz1XxlDKEsX | COM       | San Francisco Tenants and Families for Affordable Housing, Sponsored by Community and Labor Organizations |           |           |           |           |           | San Francisco | CA         | 94133     |               |                        | n         |           | 2016-04-30T00:00:00 |            | 331.21    | 1283.13   | Campaign Lit                                                            | 1378915 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1318200  | National Union of Healthcare Workers Candidate Committee for Quality Patient Care and Union Democracy                                                                                                    | 0          | RCP            | 2016-07-21T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | RCPT     | C         | PAY468       | OTH       | National Union of Healthcare Workers                                                                      |           |           |           |           |           | Emeryville    | CA         | 94608     |               |                        | n         | T         | 2016-06-09T00:00:00 |            | 2176.45   | 3337.25   | Bill Paid By Third Party                                                |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           | PAY468     |            |            |            |           |            | 
```