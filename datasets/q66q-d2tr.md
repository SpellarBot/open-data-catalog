# Campaign Finance - FPPC Form 460 - Schedule A - Monetary Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-a-monetary-contributions-1ea7c) |
| Metadata | [Link](https://data.sfgov.org/api/views/q66q-d2tr) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/q66q-d2tr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/q66q-d2tr/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | q66q-d2tr |
| Name | Campaign Finance - FPPC Form 460 - Schedule A - Monetary Contributions |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, monetary, contributions, fppc, form, 460 |
| Created | 2012-04-30T02:57:03Z |
| Publication Date | 2014-08-21T09:52:33Z |

## Description

This dataset includes all itemized monetary contributions ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "A" Monetary Contributions from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | filer_id               | Filer_ID               | text          | text          |
| Yes      | series tag     | filer_naml             | Filer_NamL             | text          | text          |
| Yes      | series tag     | report_num             | Report_Num             | text          | number        |
| Yes      | series tag     | committee_type         | Committee_Type         | text          | text          |
| No       |                | rpt_date               | Rpt_Date               | calendar_date | calendar_date |
| No       |                | from_date              | From_Date              | calendar_date | calendar_date |
| Yes      | time           | thru_date              | Thru_Date              | calendar_date | calendar_date |
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
| Yes      | numeric metric | xref_schnm             | XRef_SchNm             | number        | text          |
| Yes      | series tag     | xref_match             | XRef_Match             | text          | text          |
| Yes      | series tag     | loan_rate              | Loan_Rate              | text          | text          |
| Yes      | series tag     | int_cmteid             | Int_CmteId             | text          | text          |
```

## Time Field

```ls
Value = thru_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = rpt_date,from_date,elect_date,tran_date,tran_date1
```

## Data Commands

```ls
series e:q66q-d2tr d:2016-06-30T00:00:00.000Z t:tran_state=CA t:tran_city="Pleasant Hill" t:tran_namf="Anthony J" t:tran_emp=N/A t:tran_self=n t:entity_cd=IND t:filer_naml="Protect our Benefits" t:intr_self=n t:tran_naml=Serpa t:report_num=0 t:tran_zip4=94523 t:form_type=A t:rec_type=RCPT t:filer_id=990028 t:committee_type=RCP t:tran_occ=Retired t:tran_id=INC3998 m:tran_amt2=200 m:tran_amt1=200

series e:q66q-d2tr d:2016-09-24T00:00:00.000Z t:report_num=0 t:tran_zip4=20001-2198 t:tran_state=DC t:form_type=A t:tran_city=Washington t:rec_type=RCPT t:filer_id=1378224 t:committee_type=CTL t:tran_self=n t:entity_cd=OTH t:filer_naml="Scott Wiener for State Senate 2016" t:tran_id=INC5405 t:intr_self=n t:tran_naml="DRIVE Committee (FEC ID #C00032979)" m:tran_amt2=8400 m:tran_amt1=4200

series e:q66q-d2tr d:2016-04-23T00:00:00.000Z t:tran_state=CA t:tran_city="San Francisco" t:tran_namf=Meagan t:tran_emp="Hill & Company" t:tran_self=n t:entity_cd=IND t:filer_naml="Rachel Norton for Democratic County Central Committee 2016" t:intr_self=n t:tran_naml=Levitan t:report_num=0 t:tran_zip4=94118 t:form_type=A t:rec_type=RCPT t:filer_id=1382950 t:committee_type=CTL t:tran_occ=Realtor t:tran_id=lciEyf87y9aX m:tran_amt2=100 m:tran_amt1=100
```

## Meta Commands

```ls
metric m:tran_amt1 p:double l:Tran_Amt1 t:dataTypeName=money

metric m:tran_amt2 p:double l:Tran_Amt2 t:dataTypeName=money

metric m:xref_schnm p:integer l:XRef_SchNm t:dataTypeName=number

entity e:q66q-d2tr l:"Campaign Finance - FPPC Form 460 - Schedule A - Monetary Contributions" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/q66q-d2tr

property e:q66q-d2tr t:meta.view v:id=q66q-d2tr v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule A - Monetary Contributions" v:attribution="San Francisco Ethics Commission"

property e:q66q-d2tr t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:q66q-d2tr t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:q66q-d2tr t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                 | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | tran_naml                           | tran_namf | tran_namt | tran_nams | tran_adr1 | tran_adr2 | tran_city     | tran_state | tran_zip4  | tran_emp                       | tran_occ                        | tran_self | tran_type | tran_date           | tran_date1 | tran_amt1 | tran_amt2 | tran_dscr | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_state | tres_zip | intr_naml | intr_namf | intr_namt | intr_nams | intr_adr1 | intr_adr2 | intr_city | intr_state | intr_zip4 | intr_emp | intr_occ | intr_self | cand_naml | cand_namf | cand_namt | cand_nams | tbldetltran_office_cd | tbldetltran_offic_dscr | juris_cd | juris_dscr | dist_no | off_s_h_cd | bal_name | bal_num | bal_juris | sup_opp_cd | memo_code | memo_refno | bakref_tid | xref_schnm | xref_match | loan_rate | int_cmteid | 
| ======== | ========================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | =================================== | ========= | ========= | ========= | ========= | ========= | ============= | ========== | ========== | ============================== | =============================== | ========= | ========= | =================== | ========== | ========= | ========= | ========= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ======== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ========= | ======== | ======== | ========= | ========= | ========= | ========= | ========= | ===================== | ====================== | ======== | ========== | ======= | ========== | ======== | ======= | ========= | ========== | ========= | ========== | ========== | ========== | ========== | ========= | ========== | 
| 990028   | Protect our Benefits                                       | 0          | RCP            | 2016-07-25T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | RCPT     | A         | INC3998      | IND       | Serpa                               | Anthony J |           |           |           |           | Pleasant Hill | CA         | 94523      | N/A                            | Retired                         | n         |           | 2016-02-09T00:00:00 |            | 200       | 200       |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1378224  | Scott Wiener for State Senate 2016                         | 0          | CTL            | 2016-09-29T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | A         | INC5405      | OTH       | DRIVE Committee (FEC ID #C00032979) |           |           |           |           |           | Washington    | DC         | 20001-2198 |                                |                                 | n         |           | 2016-09-13T00:00:00 |            | 4200      | 8400      |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1382950  | Rachel Norton for Democratic County Central Committee 2016 | 0          | CTL            | 2016-04-26T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2016-06-07T00:00:00 |                    |                     | RCPT     | A         | lciEyf87y9aX | IND       | Levitan                             | Meagan    |           |           |           |           | San Francisco | CA         | 94118      | Hill & Company                 | Realtor                         | n         |           | 2016-04-23T00:00:00 |            | 100       | 100       |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1382203  | Sandra Lee Fewer for Supervisor 2016                       | 2          | CAO            | 2016-05-24T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | A         | VSGVCBMRP98  | IND       | Lee                                 | Ivy       |           |           |           |           | San Francisco | CA         | 94122-4709 | City & County of San Francisco | Attorney                        | n         |           | 2016-04-17T00:00:00 |            | 10        | 210       |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1378224  | Scott Wiener for State Senate 2016                         | 0          | CTL            | 2016-09-29T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | A         | INC4884      | IND       | Cushman                             | Lawrence  |           |           |           |           | San Diego     | CA         | 92108      | Cushman Associates             | Personal Investments Consultant | n         |           | 2016-07-18T00:00:00 |            | 1000      | 3500      |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1378224  | Scott Wiener for State Senate 2016                         | 0          | CTL            | 2016-09-29T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | A         | INC5291      | IND       | Milloy                              | Leslie    |           |           |           |           | San Franciso  | CA         | 94122      | Milloy Consulting              | Marketing Consultant            | n         |           | 2016-09-01T00:00:00 |            | 25        | 275       |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1381505  | Dean Preston for Supervisor 2016                           | 1          | CTL            | 2016-09-28T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | A         | INC675       | IND       | Belzer                              | Irvin     |           |           |           |           | Kansas City   | MO         | 64110      | Bryan Cave LLP                 | Partner                         | n         |           | 2016-03-03T00:00:00 |            | 100       | 100       |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1380968  | Ian Kalin for School Board 2016                            | 0          | CTL            | 2016-09-28T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | A         | INC240       | IND       | Sullivan                            | Dan       |           |           |           |           | San Francisco | CA         | 94114      | Better Boyfriend, Inc.         | Founder                         | n         |           | 2016-08-31T00:00:00 |            | 80        | 130       |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 1377719  | Norman Yee for Supervisor 2016                             | 0          | CTL            | 2016-04-28T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2016-11-08T00:00:00 |                    |                     | RCPT     | A         | lPgCTgsTVy78 | IND       | Mulligan                            | Patrick   |           |           |           |           | San Francisco | CA         | 94127      | CCSF                           | Carpenter                       | n         |           | 2016-01-25T00:00:00 |            | 200       | 200       |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
| 990028   | Protect our Benefits                                       | 0          | RCP            | 2016-07-25T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | RCPT     | A         | INC4160      | IND       | Kurpinsky                           | Thomas J  |           |           |           |           | Cloverdale    | CA         | 95425      | N/A                            | Retired                         | n         |           | 2016-03-18T00:00:00 |            | 500       | 500       |           |         |           |           |           |           |           |           |           |            |          |           |           |           |           |           |           |           |            |           |          |          | n         |           |           |           |           |                       |                        |          |            |         |            |          |         |           |            |           |            |            |            |            |           |            | 
```