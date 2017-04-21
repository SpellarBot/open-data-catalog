# Campaign Finance - FPPC Form 460 - Schedule E - Payments Made

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-e-payments-made-367ea) |
| Metadata | [Link](https://data.sfgov.org/api/views/hc26-j9if) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/hc26-j9if/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/hc26-j9if/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | hc26-j9if |
| Name | Campaign Finance - FPPC Form 460 - Schedule E - Payments Made |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, payments, expenditures, fppc, form, 460 |
| Created | 2012-04-30T05:30:20Z |
| Publication Date | 2014-08-21T09:05:35Z |

## Description

This dataset includes all itemized payments made ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "E" Payments Made from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | filer_id            | Filer_ID            | text          | text          |
| Yes      | series tag     | filer_naml          | Filer_NamL          | text          | text          |
| Yes      | series tag     | report_num          | Report_Num          | text          | number        |
| Yes      | series tag     | committee_type      | Committee_Type      | text          | text          |
| No       |                | rpt_date            | Rpt_Date            | calendar_date | calendar_date |
| No       |                | from_date           | From_Date           | calendar_date | calendar_date |
| Yes      | time           | thru_date           | Thru_Date           | calendar_date | calendar_date |
| No       |                | elect_date          | Elect_Date          | calendar_date | calendar_date |
| Yes      | series tag     | tblcover_office_cd  | tblCover_Office_Cd  | text          | text          |
| Yes      | series tag     | tblcover_offic_dscr | tblCover_Offic_Dscr | text          | text          |
| Yes      | series tag     | rec_type            | Rec_Type            | text          | text          |
| Yes      | series tag     | form_type           | Form_Type           | text          | text          |
| Yes      | series tag     | tran_id             | Tran_ID             | text          | text          |
| Yes      | series tag     | entity_cd           | Entity_Cd           | text          | text          |
| Yes      | series tag     | payee_naml          | Payee_NamL          | text          | text          |
| Yes      | series tag     | payee_namf          | Payee_NamF          | text          | text          |
| Yes      | series tag     | payee_namt          | Payee_NamT          | text          | text          |
| Yes      | series tag     | payee_nams          | Payee_NamS          | text          | text          |
| Yes      | series tag     | payee_adr1          | Payee_Adr1          | text          | text          |
| Yes      | series tag     | payee_adr2          | Payee_Adr2          | text          | text          |
| Yes      | series tag     | payee_city          | Payee_City          | text          | text          |
| Yes      | series tag     | payee_state         | Payee_State         | text          | text          |
| Yes      | series tag     | payee_zip4          | Payee_Zip4          | text          | text          |
| No       |                | expn_date           | Expn_Date           | calendar_date | calendar_date |
| Yes      | numeric metric | amount              | Amount              | money         | money         |
| Yes      | numeric metric | cum_ytd             | Cum_YTD             | money         | money         |
| Yes      | series tag     | expn_chkno          | Expn_ChkNo          | text          | text          |
| Yes      | series tag     | expn_code           | Expn_Code           | text          | text          |
| Yes      | series tag     | expn_dscr           | Expn_Dscr           | text          | text          |
| Yes      | series tag     | agent_naml          | Agent_NamL          | text          | text          |
| Yes      | series tag     | agent_namf          | Agent_NamF          | text          | text          |
| Yes      | numeric metric | agent_namt          | Agent_NamT          | number        | text          |
| Yes      | series tag     | agent_nams          | Agent_NamS          | text          | text          |
| Yes      | series tag     | cmte_id             | Cmte_ID             | text          | text          |
| Yes      | series tag     | tres_naml           | Tres_NamL           | text          | text          |
| Yes      | series tag     | tres_namf           | Tres_NamF           | text          | text          |
| Yes      | series tag     | tres_namt           | Tres_NamT           | text          | text          |
| Yes      | series tag     | tres_nams           | Tres_NamS           | text          | text          |
| Yes      | series tag     | tres_adr1           | Tres_Adr1           | text          | text          |
| Yes      | series tag     | tres_adr2           | Tres_Adr2           | text          | text          |
| Yes      | series tag     | tres_city           | Tres_City           | text          | text          |
| Yes      | series tag     | tres_st             | Tres_ST             | text          | text          |
| Yes      | series tag     | tres_zip4           | Tres_ZIP4           | text          | text          |
| Yes      | series tag     | cand_naml           | Cand_NamL           | text          | text          |
| Yes      | series tag     | cand_namf           | Cand_NamF           | text          | text          |
| Yes      | series tag     | cand_namt           | Cand_NamT           | text          | text          |
| Yes      | series tag     | cand_nams           | Cand_NamS           | text          | text          |
| Yes      | series tag     | office_cd           | Office_Cd           | text          | text          |
| Yes      | series tag     | offic_dscr          | Offic_Dscr          | text          | text          |
| Yes      | series tag     | juris_cd            | Juris_Cd            | text          | text          |
| Yes      | series tag     | juris_dscr          | Juris_Dscr          | text          | text          |
| Yes      | series tag     | dist_no             | Dist_No             | text          | text          |
| Yes      | series tag     | off_s_h_cd          | Off_S_H_Cd          | text          | text          |
| Yes      | series tag     | bal_name            | Bal_Name            | text          | text          |
| Yes      | series tag     | bal_num             | Bal_Num             | text          | text          |
| Yes      | series tag     | bal_juris           | Bal_Juris           | text          | text          |
| Yes      | series tag     | sup_opp_cd          | Sup_Opp_Cd          | text          | text          |
| Yes      | series tag     | memo_code           | Memo_Code           | text          | text          |
| Yes      | series tag     | memo_refno          | Memo_RefNo          | text          | text          |
| Yes      | series tag     | bakref_tid          | BakRef_TID          | text          | text          |
| Yes      | series tag     | g_from_e_f          | G_From_E_F          | text          | text          |
| Yes      | series tag     | xref_schnm          | XRef_SchNm          | text          | text          |
| Yes      | series tag     | xref_match          | XRef_Match          | text          | text          |
```

## Time Field

```ls
Value = thru_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = rpt_date,from_date,elect_date,expn_date
```

## Data Commands

```ls
series e:hc26-j9if d:2016-05-21T00:00:00.000Z t:payee_state=CA t:payee_zip4=94124 t:entity_cd=IND t:filer_naml="Chinese Progressive Association, nonprofit 501(c)3" t:payee_namf="Rui Yi" t:report_num=0 t:expn_code=IND t:form_type=E t:rec_type=EXPN t:filer_id=1380710 t:committee_type=RCP t:payee_naml=Chen t:sup_opp_cd=S t:payee_city="San Francisco" t:tran_id=FwO2sRJfoXH4 t:expn_dscr="Phone Canvass" m:amount=73.44 m:cum_ytd=226.2

series e:hc26-j9if d:2016-09-24T00:00:00.000Z t:cand_naml=Philhour t:payee_state=DC t:payee_zip4=20009 t:cand_namf=Marjan t:entity_cd=OTH t:dist_no=1 t:office_cd=CSU t:filer_naml="Vote Marjan Philhour for Supervisor 2016" t:juris_dscr="San Francisco, CA" t:report_num=1 t:expn_code=FND t:juris_cd=OTH t:form_type=E t:rec_type=EXPN t:filer_id=1374373 t:committee_type=CTL t:payee_naml="Democracy Engine" t:payee_city=Washington t:tran_id=EXP1980 m:amount=27.98 m:cum_ytd=750.17

series e:hc26-j9if d:2016-05-21T00:00:00.000Z t:payee_state=CA t:payee_zip4=94107 t:entity_cd=IND t:filer_naml="Chinese Progressive Association, nonprofit 501(c)3" t:payee_namf="Un Un" t:report_num=0 t:expn_code=IND t:form_type=E t:rec_type=EXPN t:filer_id=1380710 t:committee_type=RCP t:payee_naml=Che t:sup_opp_cd=S t:payee_city="San Francisco" t:tran_id=AcvJD2S5lhkt t:expn_dscr="Phone Canvass" m:amount=183.13 m:cum_ytd=390.97
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

metric m:cum_ytd p:double l:Cum_YTD t:dataTypeName=money

metric m:agent_namt p:integer l:Agent_NamT t:dataTypeName=number

entity e:hc26-j9if l:"Campaign Finance - FPPC Form 460 - Schedule E - Payments Made" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/hc26-j9if

property e:hc26-j9if t:meta.view v:id=hc26-j9if v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule E - Payments Made" v:attribution="San Francisco Ethics Commission"

property e:hc26-j9if t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:hc26-j9if t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:hc26-j9if t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                                                                                          | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | payee_naml                                | payee_namf | payee_namt | payee_nams | payee_adr1 | payee_adr2 | payee_city    | payee_state | payee_zip4 | expn_date           | amount  | cum_ytd | expn_chkno | expn_code | expn_dscr                                                                                        | agent_naml | agent_namf | agent_namt | agent_nams | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_st | tres_zip4 | cand_naml  | cand_namf | cand_namt | cand_nams | office_cd | offic_dscr                          | juris_cd | juris_dscr           | dist_no | off_s_h_cd | bal_name                                                                                          | bal_num | bal_juris     | sup_opp_cd | memo_code | memo_refno | bakref_tid | g_from_e_f | xref_schnm | xref_match | 
| ======== | =================================================================================================================================================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | ========================================= | ========== | ========== | ========== | ========== | ========== | ============= | =========== | ========== | =================== | ======= | ======= | ========== | ========= | ================================================================================================ | ========== | ========== | ========== | ========== | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | ========== | ========= | ========= | ========= | ========= | =================================== | ======== | ==================== | ======= | ========== | ================================================================================================= | ======= | ============= | ========== | ========= | ========== | ========== | ========== | ========== | ========== | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3                                                                                                                                                  | 0          | RCP            | 2016-05-24T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | E         | FwO2sRJfoXH4 | IND       | Chen                                      | Rui Yi     |            |            |            |            | San Francisco | CA          | 94124      | 2016-05-21T00:00:00 | 73.44   | 226.2   |            | IND       | Phone Canvass                                                                                    |            |            |            |            |         |           |           |           |           |           |           |           |         |           |            |           |           |           |           |                                     |          |                      |         |            |                                                                                                   |         |               | S          |           |            |            |            |            |            | 
| 1374373  | Vote Marjan Philhour for Supervisor 2016                                                                                                                                                            | 1          | CTL            | 2016-09-30T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | E         | EXP1980      | OTH       | Democracy Engine                          |            |            |            |            |            | Washington    | DC          | 20009      | 2016-09-21T00:00:00 | 27.98   | 750.17  |            | FND       |                                                                                                  |            |            |            |            |         |           |           |           |           |           |           |           |         |           | Philhour   | Marjan    |           |           | CSU       |                                     | OTH      | San Francisco, CA    | 1       |            |                                                                                                   |         |               |            |           |            |            |            |            |            | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3                                                                                                                                                  | 0          | RCP            | 2016-05-24T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | E         | AcvJD2S5lhkt | IND       | Che                                       | Un Un      |            |            |            |            | San Francisco | CA          | 94107      | 2016-05-21T00:00:00 | 183.13  | 390.97  |            | IND       | Phone Canvass                                                                                    |            |            |            |            |         |           |           |           |           |           |           |           |         |           |            |           |           |           |           |                                     |          |                      |         |            |                                                                                                   |         |               | S          |           |            |            |            |            |            | 
| 1386915  | Vote 16, Yes on Measure F, A Diverse Coalition to Expand Voting Rights with Major Funding from Ian Simmons and Blue Haven Initiative, LLC                                                           | 2          | BMC            | 2016-12-30T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | E         | EXP52        | IND       | Tamayo-Lee                                | Araceli    |            |            |            |            | San Francisco | CA          | 94131      | 2016-10-03T00:00:00 | 1920    | 5152.49 |            |           | Administrative Services                                                                          |            |            |            |            |         |           |           |           |           |           |           |           |         |           |            |           |           |           |           |                                     |          |                      |         |            | Lower the voting age for municpal and school district elections in San Francisco to 16, Measure F |         | San Francisco | S          |           |            |            |            |            |            | 
| 1383307  | Melissa San Miguel for Supervisor 2016                                                                                                                                                              | 0          | CTL            | 2016-04-27T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | E         | EXP39        | OTH       | River City Business Services              |            |            |            |            |            | Sacramento    | CA          | 95841      | 2016-04-18T00:00:00 | 25      | 1598.8  |            | OFC       |                                                                                                  |            |            |            |            |         |           |           |           |           |           |           |           |         |           | San Miguel | Melissa   |           |           | CSU       |                                     | OTH      | San Francisco County | 9       |            |                                                                                                   |         |               |            |           |            |            |            |            |            | 
| 1381294  | Hillary Ronen for Supervisor 2016                                                                                                                                                                   | 1          | CTL            | 2016-10-20T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | E         | EXP1516      | OTH       | Walgreens                                 |            |            |            |            |            | San Francisco | CA          | 94102      | 2016-07-15T00:00:00 | 13.03   | 478.05  |            | OFC       | Paid on PEX Prepaid Debit Card, payment to: PEX Card 1375 Broadway, Suite 1100 New York NY 10018 |            |            |            |            |         |           |           |           |           |           |           |           |         |           | Ronen      | Hillary   |           |           | CSU       | Supervisor                          | OTH      | San Francisco        | 9       |            |                                                                                                   |         |               |            |           |            |            |            |            |            | 
| 1384150  | Aaron Peskin for Democratic County Central Committee 2016                                                                                                                                           | 1          | CTL            | 2016-09-16T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | E         | EXP67        | OTH       | Ad Mail West                              |            |            |            |            |            | Sacramento    | CA          | 95811      | 2016-06-02T00:00:00 | 1949.87 | 10516.6 |            | LIT       |                                                                                                  |            |            |            |            |         |           |           |           |           |           |           |           |         |           | Peskin     | Aaron     |           |           | OTH       | Democratic County Central Committee | OTH      | San Francisco, CA    | 17      |            |                                                                                                   |         |               |            |           |            |            |            |            |            | 
| 1382620  | Mary Jung for Democratic County Central Committee 2016                                                                                                                                              | 2          | CAO            | 2016-04-28T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | E         | VSFZ89N2078  | OTH       | 50+1 Strategies                           |            |            |            |            |            | San Francisco | CA          | 94104-1909 | 2016-01-31T00:00:00 | 20000   | 0       |            | CNS       |                                                                                                  |            |            |            |            |         |           |           |           |           |           |           |           |         |           | Jung       | Mary      |           |           |           | Democratic County Central Committee | ASM      | 19                   |         |            |                                                                                                   |         |               |            |           |            |            |            |            |            | 
| 1385333  | SAN FRANCISCO DEMOCRATS UNITED FOR PROGRESS, SUPPORTING 23 CANDIDATES FOR THE 2016 SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE, INCLUDING TOM A. HSIEH JR. (COMPLETE COMMITTEE NAME ATTACHED) | 0          | RCP            | 2016-08-01T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | EXPN     | E         | EXP174       | IND       | HUANG                                     | KEXIN      |            |            |            |            | SAN FRANCISCO | CA          | 94112      | 2016-05-31T00:00:00 | 200     | 1040    |            |           | CANVASSING                                                                                       |            |            |            |            |         |           |           |           |           |           |           |           |         |           | HSIEH      | TOM A.    |           | JR.       | OTH       | DEMOCRATIC COUNTY CENTRAL COMMITTEE | ASM      |                      | 19      |            |                                                                                                   |         |               |            |           |            |            |            |            |            | 
| 1382851  | Kat Anderson for Democratic County Central Committee 2016                                                                                                                                           | 1          | CTL            | 2016-06-06T00:00:00 | 2016-04-24T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | E         | dwuVvEsE7Eds | OTH       | San Francisco Young Democrats Voter Guide |            |            |            |            |            | San Francisco | CA          | 94114      | 2016-05-04T00:00:00 | 250     | 250     |            | LIT       | San Francisco Young Democrats Slate Card Mailer                                                  |            |            |            |            |         |           |           |           |           |           |           |           |         |           | Anderson   | Kat       |           |           | OTH       | Democratic County Central Committee | CTY      | San Francisco        | 19      |            |                                                                                                   |         |               | S          |           |            |            |            |            |            | 
```