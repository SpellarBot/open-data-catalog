# Campaign Finance - FPPC Form 496 - Late Independent Expenditure Report - Part 3 - Contributions of $100 or More Received

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-496-late-independent-expenditure-report-part-3-contributions-of-1ef0e) |
| Metadata | [Link](https://data.sfgov.org/api/views/p4sp-es3b) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/p4sp-es3b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/p4sp-es3b/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | p4sp-es3b |
| Name | Campaign Finance - FPPC Form 496 - Late Independent Expenditure Report - Part 3 - Contributions of $100 or More Received |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, monetary, contributions, fppc, form, 496 |
| Created | 2012-06-27T20:30:29Z |
| Publication Date | 2017-01-26T15:51:04Z |

## Description

This dataset includes all itemized contributions of $100 or more e-filed on Fair Political Practices Commission (FPPC) Form 496 "Part 3" Contributions of $100 or More Received from 2009 to the present. The data is current as of the last modified date on this dataset. 

See the data key for column definitions: https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | filer_id               | Filer_ID               | text          | text          |
| Yes      | series tag     | filer_naml             | Filer_NamL             | text          | text          |
| Yes      | series tag     | report_num             | Report_Num             | text          | number        |
| Yes      | series tag     | committee_type         | Committee_Type         | text          | text          |
| Yes      | time           | rpt_date               | Rpt_Date               | calendar_date | calendar_date |
| No       |                | from_date              | From_Date              | calendar_date | calendar_date |
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
| Yes      | numeric metric | loan_rate              | Loan_Rate              | number        | text          |
| Yes      | series tag     | int_cmteid             | Int_CmteId             | text          | text          |
```

## Time Field

```ls
Value = rpt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = from_date,thru_date,elect_date,tran_date,tran_date1
```

## Data Commands

```ls
series e:p4sp-es3b d:2016-10-11T00:00:00.000Z t:tran_state=CA t:tran_city="San Francisco" t:tran_self=n t:entity_cd=COM t:filer_naml="Robert F. Kennedy Democratic Club" t:intr_self=n t:tran_naml="San Francisco Laborer's Local 261" t:report_num=1 t:tran_zip4=94110-1920 t:form_type=F496P3 t:cmte_id=981076 t:rec_type=RCPT t:filer_id=1383372 t:committee_type=RCP t:tran_id=VSGYQD72EA8 m:tran_amt1=2500

series e:p4sp-es3b d:2016-10-11T00:00:00.000Z t:tran_state=CA t:tran_city="San Francisco" t:tran_self=n t:entity_cd=COM t:filer_naml="Robert F. Kennedy Democratic Club" t:intr_self=n t:tran_naml="San Francisco Laborer's Local 261" t:report_num=1 t:tran_zip4=94110-1920 t:form_type=F496P3 t:cmte_id=981076 t:rec_type=RCPT t:filer_id=1383372 t:committee_type=RCP t:tran_id=VSGYQD72EA8 m:tran_amt1=2500

series e:p4sp-es3b d:2016-11-08T00:00:00.000Z t:tran_state=CA t:tran_city="San Rafael" t:tran_self=n t:entity_cd=COM t:filer_naml="Robert F. Kennedy Democratic Club" t:intr_self=n t:tran_naml="Govern for California Action Committee" t:report_num=0 t:tran_zip4=94901-5596 t:form_type=F496P3 t:cmte_id=1346242 t:rec_type=RCPT t:filer_id=1383372 t:committee_type=RCP t:tran_id=VSGYQDFYHS9 m:tran_amt1=15000
```

## Meta Commands

```ls
metric m:tran_amt1 p:double l:Tran_Amt1 t:dataTypeName=money

metric m:tran_amt2 p:double l:Tran_Amt2 t:dataTypeName=money

metric m:loan_rate p:integer l:Loan_Rate t:dataTypeName=number

entity e:p4sp-es3b l:"Campaign Finance - FPPC Form 496 - Late Independent Expenditure Report - Part 3 - Contributions of $100 or More Received" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/p4sp-es3b

property e:p4sp-es3b t:meta.view v:id=p4sp-es3b v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 496 - Late Independent Expenditure Report - Part 3 - Contributions of $100 or More Received" v:attribution="San Francisco Ethics Commission"

property e:p4sp-es3b t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:p4sp-es3b t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:p4sp-es3b t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                         | report_num | committee_type | rpt_date            | from_date | thru_date | elect_date | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | tran_naml                                                          | tran_namf | tran_namt | tran_nams | tran_adr1 | tran_adr2 | tran_city     | tran_state | tran_zip4  | tran_emp               | tran_occ            | tran_self | tran_type | tran_date           | tran_date1 | tran_amt1 | tran_amt2 | tran_dscr | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_state | tres_zip | intr_naml | intr_namf | intr_namt | intr_nams | intr_adr1 | intr_adr2 | intr_city | intr_state | intr_zip4 | intr_emp | intr_occ | intr_self | cand_naml | cand_namf | cand_namt | cand_nams | tbldetltran_office_cd | tbldetltran_offic_dscr | juris_cd | juris_dscr | dist_no | off_s_h_cd | bal_name | bal_num | bal_juris | sup_opp_cd | memo_code | memo_refno | bakref_tid | xref_schnm | xref_match | loan_rate | int_cmteid | 
| ======== | ================================================== | ========== | ============== | =================== | ========= | ========= | ========== | ================== | =================== | ======== | ========= | ============ | ========= | ================================================================== | ========= | ========= | ========= | ========= | ========= | ============= | ========== | ========== | ====================== | =================== | ========= | ========= | =================== | ========== | ========= | ========= | ========= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ======== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========= | ======== | ======== | ========= | ========= | ========= | ========= | ========= | ===================== | ====================== | ======== | ========== | ======= | ========== | ======== | ======= | ========= | ========== | ========= | ========== | ========== | ========== | ========== | ========= | ========== | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 1          | RCP            | 2016-10-11T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQD72EA8  | COM       | San Francisco Laborer's Local 261                                  |           |           |           |           |           | San Francisco | CA         | 94110-1920 |                        |                     | n         |           | 2016-10-05T00:00:00 |            | 2500      |           |           | 981076  |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 1          | RCP            | 2016-10-11T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQD72EA8  | COM       | San Francisco Laborer's Local 261                                  |           |           |           |           |           | San Francisco | CA         | 94110-1920 |                        |                     | n         |           | 2016-10-05T00:00:00 |            | 2500      |           |           | 981076  |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 0          | RCP            | 2016-11-08T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQDFYHS9  | COM       | Govern for California Action Committee                             |           |           |           |           |           | San Rafael    | CA         | 94901-5596 |                        |                     | n         |           | 2016-11-07T00:00:00 |            | 15000     |           |           | 1346242 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 0          | RCP            | 2016-11-08T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQDFYHS9  | COM       | Govern for California Action Committee                             |           |           |           |           |           | San Rafael    | CA         | 94901-5596 |                        |                     | n         |           | 2016-11-07T00:00:00 |            | 15000     |           |           | 1346242 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 3          | RCP            | 2016-09-27T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQD6JYM4  | SCC       | Union of American Physicians and Dentists Medical Action Committee |           |           |           |           |           | Oakland       | CA         | 94612-3750 |                        |                     | n         |           | 2016-09-26T00:00:00 |            | 1500      |           |           | 1356185 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3 | 0          |                | 2016-10-09T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | BwnTeecnImca | OTH       | Chinese Progressive Association                                    |           |           |           |           |           | San Francisco | CA         | 94133      |                        |                     | n         |           | 2016-09-23T00:00:00 |            | 9500      | 9500      |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 0          | RCP            | 2016-11-08T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQDFQ4F7  | IND       | Josefowitz                                                         | Nicholas  |           |           |           |           | San Francisco | CA         | 94115-1126 | Bay Area Rapid Transit | BART Board Director | n         |           | 2016-11-05T00:00:00 |            | 15000     |           |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 0          | RCP            | 2016-11-08T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQDFQ4F7  | IND       | Josefowitz                                                         | Nicholas  |           |           |           |           | San Francisco | CA         | 94115-1126 | Bay Area Rapid Transit | BART Board Director | n         |           | 2016-11-05T00:00:00 |            | 15000     |           |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 3          | RCP            | 2016-09-27T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQD5ECE5  | COM       | Progress San Francisco                                             |           |           |           |           |           | Sacramento    | CA         | 95815-4404 |                        |                     | n         |           | 2016-09-26T00:00:00 |            | 100000    |           |           | 1381519 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1383372  | Robert F. Kennedy Democratic Club                  | 0          | RCP            | 2016-11-01T00:00:00 |           |           |            |                    |                     | RCPT     | F496P3    | VSGYQDD4JA3  | COM       | Progress San Francisco                                             |           |           |           |           |           | Sacramento    | CA         | 95815-4404 |                        |                     | n         |           | 2016-10-27T00:00:00 |            | 200000    |           |           | 1381519 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
```