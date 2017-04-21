# Campaign Finance - FPPC Form 460 - Schedule I - Miscellaneous Increases to Cash

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-i-miscellaneous-increases-to-cash-1453d) |
| Metadata | [Link](https://data.sfgov.org/api/views/6ssu-ewuc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/6ssu-ewuc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/6ssu-ewuc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 6ssu-ewuc |
| Name | Campaign Finance - FPPC Form 460 - Schedule I - Miscellaneous Increases to Cash |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, miscellaneous, increases, cash, fppc, form, 460, campaign, finance |
| Created | 2012-04-30T16:46:59Z |
| Publication Date | 2014-08-21T09:38:02Z |

## Description

This dataset includes all itemized Miscellaneous Increases to Cash ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "I" Miscellaneous Increases to Cash from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

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
| Yes      | series tag     | tran_date1             | Tran_Date1             | text          | text          |
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
Excluded Fields = rpt_date,thru_date,elect_date,tran_date
```

## Data Commands

```ls
series e:6ssu-ewuc d:2016-07-01T00:00:00.000Z t:tran_state=TX t:tran_city=Austin t:tran_namf="Solveij R." t:tran_self=n t:entity_cd=IND t:filer_naml="San Francisco Tenants and Families for Affordable Housing, sponsored by community and labor organizations" t:intr_self=n t:tran_naml=Praxis t:report_num=1 t:tran_dscr="Void Check" t:tran_zip4=78746 t:form_type=I t:rec_type=RCPT t:filer_id=1378915 t:committee_type=RCP t:tran_id=INC1010 m:tran_amt2=0 m:tran_amt1=192.75

series e:6ssu-ewuc d:2016-07-01T00:00:00.000Z t:tran_state=CA t:tran_city="San Francisco" t:entity_cd=OTH t:tran_self=n t:filer_naml="Kimberly Alvarenga for Supervisor 2016" t:intr_self=n t:tran_naml="San Francisco Ethics Commission" t:report_num=0 t:tran_dscr="public financing" t:tran_zip4=94102 t:form_type=I t:rec_type=RCPT t:filer_id=1381277 t:committee_type=CTL t:tran_id=B9rKwdhTo64H m:tran_amt2=37528 m:tran_amt1=16348

series e:6ssu-ewuc d:2016-01-01T00:00:00.000Z t:tran_state=CA t:tran_city=Alameda t:tran_namf=Victoria t:tran_self=n t:entity_cd=IND t:filer_naml="Aaron Peskin for Supervisor 2015" t:intr_self=n t:tran_naml=Sharp t:report_num=0 t:tran_dscr="Check reversal" t:tran_zip4=94501 t:form_type=I t:rec_type=RCPT t:filer_id=1376394 t:committee_type=CTL t:tran_id=INC4859 m:tran_amt2=0 m:tran_amt1=80
```

## Meta Commands

```ls
metric m:tran_amt1 p:double l:Tran_Amt1 t:dataTypeName=money

metric m:tran_amt2 p:double l:Tran_Amt2 t:dataTypeName=money

entity e:6ssu-ewuc l:"Campaign Finance - FPPC Form 460 - Schedule I - Miscellaneous Increases to Cash" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/6ssu-ewuc

property e:6ssu-ewuc t:meta.view v:id=6ssu-ewuc v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule I - Miscellaneous Increases to Cash" v:attribution="San Francisco Ethics Commission"

property e:6ssu-ewuc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:6ssu-ewuc t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:6ssu-ewuc t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                                                                                              | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | tran_naml                             | tran_namf  | tran_namt | tran_nams | tran_adr1 | tran_adr2 | tran_city     | tran_state | tran_zip4  | tran_emp                              | tran_occ        | tran_self | tran_type | tran_date           | tran_date1 | tran_amt1 | tran_amt2 | tran_dscr                                     | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_state | tres_zip | intr_naml | intr_namf | intr_namt | intr_nams | intr_adr1 | intr_adr2 | intr_city | intr_state | intr_zip4 | intr_emp | intr_occ | intr_self | cand_naml | cand_namf | cand_namt | cand_nams | tbldetltran_office_cd | tbldetltran_offic_dscr | juris_cd | juris_dscr | dist_no | off_s_h_cd | bal_name | bal_num | bal_juris | sup_opp_cd | memo_code | memo_refno | bakref_tid | xref_schnm | xref_match | loan_rate | int_cmteid | 
| ======== | ======================================================================================================================================================================================================= | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | ===================================== | ========== | ========= | ========= | ========= | ========= | ============= | ========== | ========== | ===================================== | =============== | ========= | ========= | =================== | ========== | ========= | ========= | ============================================= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ======== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========= | ======== | ======== | ========= | ========= | ========= | ========= | ========= | ===================== | ====================== | ======== | ========== | ======= | ========== | ======== | ======= | ========= | ========== | ========= | ========== | ========== | ========== | ========== | ========= | ========== | 
| 1378915  | San Francisco Tenants and Families for Affordable Housing, sponsored by community and labor organizations                                                                                               | 1          | RCP            | 2016-10-27T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | I         | INC1010      | IND       | Praxis                                | Solveij R. |           |           |           |           | Austin        | TX         | 78746      |                                       |                 | n         |           | 2016-08-03T00:00:00 |            | 192.75    | 0         | Void Check                                    |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1381277  | Kimberly Alvarenga for Supervisor 2016                                                                                                                                                                  | 0          | CTL            | 2016-09-29T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | I         | B9rKwdhTo64H | OTH       | San Francisco Ethics Commission       |            |           |           |           |           | San Francisco | CA         | 94102      |                                       |                 | n         |           | 2016-08-29T00:00:00 |            | 16348     | 37528     | public financing                              |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1376394  | Aaron Peskin for Supervisor 2015                                                                                                                                                                        | 0          | CTL            | 2016-04-27T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2015-11-03T00:00:00 |                    |                     | RCPT     | I         | INC4859      | IND       | Sharp                                 | Victoria   |           |           |           |           | Alameda       | CA         | 94501      |                                       |                 | n         |           | 2016-03-31T00:00:00 |            | 80        | 0         | Check reversal                                |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1368216  | RE-ELECT DISTRICT ATTORNEY GEORGE GASCON 2015                                                                                                                                                           | 0          | CTL            | 2016-08-01T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | RCPT     | I         | INC832       | OTH       | SAN FRANCISCO FIREFIGHTERS SLATE CARD |            |           |           |           |           | NOVATO        | CA         | 94949      |                                       |                 | n         |           | 2016-02-01T00:00:00 |            | 500       | 0         | REFUND                                        | 1342688 |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1386302  | San Franciscans for Sports and Recreation                                                                                                                                                               | 0          | BMC            | 2016-07-01T00:00:00 | 2016-06-16T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | I         | QzP9aq3DaFPh | IND       | MACK                                  | KAREN      |           |           |           |           | SAN FRANCISCO | CA         | 94115      | ALTMAN AND CRONIN BENEFIT CONSULTANTS | PENSION ACTUARY | n         |           | 2016-06-19T00:00:00 |            | 650       | 650       | AUCTION: PRIVATE PLANE FLIGHT                 |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1378138  | Committee to Save the Mission, Yes on Prop. I, Sponsored by a Coalition of Mission Neighborhood Organizations                                                                                           | 0          | BMC            | 2016-07-18T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | RCPT     | I         | INC741       | OTH       | NationBuilder                         |            |           |           |           |           | Los Angeles   | CA         | 90071      |                                       |                 | n         |           | 2016-03-11T00:00:00 |            | 506       | 0         | Refund                                        |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1379663  | Jonathan Lyens for Supervisor 2016                                                                                                                                                                      | 0          | CTL            | 2016-09-28T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | I         | INC387       | OTH       | City and County of San Francisco      |            |           |           |           |           | San Francisco | CA         | 94102      |                                       |                 | n         |           | 2016-09-23T00:00:00 |            | 19309.7   | 0         | Public Funds/ Matching Funds                  |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1382203  | Sandra Lee Fewer for Supervisor 2016                                                                                                                                                                    | 1          | CAO            | 2016-09-06T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | I         | VSGVCCJY380  | OTH       | City & County of San Francisco        |            |           |           |           |           | San Francisco | CA         | 94102-4603 |                                       |                 | n         |           | 2016-06-22T00:00:00 |            | 20000     | 0         | Public Financing - Initial Qualifying Request |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1378915  | San Francisco Tenants and Families for Affordable Housing, sponsored by community and labor organizations                                                                                               | 0          | RCP            | 2016-05-26T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | RCPT     | I         | INC909       | OTH       | State Compensation Insurance Fund     |            |           |           |           |           | Fremont       | CA         | 94538      |                                       |                 | n         |           | 2016-05-12T00:00:00 |            | 108.43    | 0         | Refund of Payment                             |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1367243  | ShareBetter SF, Yes on F - Supported by a broad coalition of tenants and landlords, neighborhood associations, affordable housing proponents, senior... [See 410 statement for complete committee name] | 0          | BMC            | 2016-07-28T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2015-11-03T00:00:00 |                    |                     | RCPT     | I         | piHFSkjFR6ac | OTH       | San Francisco Department of Elections |            |           |           |           |           | San Francisco | CA         | 94102      |                                       |                 | n         |           | 2016-01-26T00:00:00 |            | 200       | 200       | Refund of filing fee                          |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
```