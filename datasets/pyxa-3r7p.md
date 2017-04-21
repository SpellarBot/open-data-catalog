# Campaign Finance - FPPC Form 465 - Supplemental Independent Expenditure Report - Part 3 - Independent Expenditures Made

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-465-supplemental-independent-expenditure-report-part-3-independ-b1064) |
| Metadata | [Link](https://data.sfgov.org/api/views/pyxa-3r7p) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/pyxa-3r7p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/pyxa-3r7p/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | pyxa-3r7p |
| Name | Campaign Finance - FPPC Form 465 - Supplemental Independent Expenditure Report - Part 3 - Independent Expenditures Made |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, independent, expenditures, fppc, form, 465 |
| Created | 2012-04-30T15:46:18Z |
| Publication Date | 2014-08-21T09:09:18Z |

## Description

This dataset includes all itemized independent expenditures ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 465 Part 3 Independent Expenditures Made from 2009 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | filer_id            | Filer_ID            | text          | text          |
| Yes      | series tag     | filer_naml          | Filer_NamL          | text          | text          |
| Yes      | series tag     | report_num          | Report_Num          | text          | number        |
| Yes      | series tag     | committee_type      | Committee_Type      | text          | text          |
| Yes      | time           | rpt_date            | Rpt_Date            | calendar_date | calendar_date |
| No       |                | from_date           | From_Date           | calendar_date | calendar_date |
| No       |                | thru_date           | Thru_Date           | calendar_date | calendar_date |
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
| Yes      | numeric metric | expn_chkno          | Expn_ChkNo          | number        | text          |
| Yes      | series tag     | expn_code           | Expn_Code           | text          | text          |
| Yes      | series tag     | expn_dscr           | Expn_Dscr           | text          | text          |
| Yes      | series tag     | agent_naml          | Agent_NamL          | text          | text          |
| Yes      | series tag     | agent_namf          | Agent_NamF          | text          | text          |
| Yes      | series tag     | agent_namt          | Agent_NamT          | text          | text          |
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
Value = rpt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = from_date,thru_date,elect_date,expn_date
```

## Data Commands

```ls
series e:pyxa-3r7p d:2016-05-17T00:00:00.000Z t:payee_state=CA t:payee_zip4=94112 t:entity_cd=COM t:bal_num=C t:filer_naml="Chinese Progressive Association, nonprofit 501(c)3" t:payee_namf="Yue Chang" t:report_num=0 t:bal_juris=SF t:form_type=F465P3 t:bal_name="SF Affordable Housing Requirements" t:cmte_id=Pending t:rec_type=EXPN t:filer_id=1380710 t:committee_type=RCP t:payee_naml=Tan t:sup_opp_cd=S t:payee_city="San Francisco" t:expn_dscr="Phone Canvass" t:tran_id=qY5DNxEIH72r m:amount=92.43 m:cum_ytd=1565.19

series e:pyxa-3r7p d:2017-01-19T00:00:00.000Z t:payee_state=CA t:payee_zip4=94030 t:entity_cd=OTH t:bal_num=NA t:filer_naml="Friends of the Mayor, No Recall on Mayor Lee No on D, H, L, & M Committee" t:report_num=0 t:bal_juris="San Francisco" t:form_type=F465P3 t:bal_name="Recall Mayor Ed Lee" t:cmte_id=1234567 t:rec_type=EXPN t:filer_id=1389926 t:committee_type=RCP t:payee_naml="World Journal" t:sup_opp_cd=O t:payee_city=Millbrace t:expn_dscr="newspaper ad" t:tran_id=6TDb588hOK6D m:amount=1000 m:cum_ytd=6946

series e:pyxa-3r7p d:2016-05-17T00:00:00.000Z t:payee_state=CA t:payee_zip4=94133 t:entity_cd=COM t:bal_num=C t:filer_naml="Chinese Progressive Association, nonprofit 501(c)3" t:payee_namf=Flora t:report_num=0 t:bal_juris=SF t:form_type=F465P3 t:bal_name="SF Affordable Housing Requirements" t:cmte_id=Pending t:rec_type=EXPN t:filer_id=1380710 t:committee_type=RCP t:payee_naml=Luo t:sup_opp_cd=S t:payee_city="San Francisco" t:expn_dscr="Phone Canvass" t:tran_id=kuK9bGP8CRcw m:amount=143.69 m:cum_ytd=1565.19
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

metric m:cum_ytd p:double l:Cum_YTD t:dataTypeName=money

metric m:expn_chkno p:integer l:Expn_ChkNo t:dataTypeName=number

entity e:pyxa-3r7p l:"Campaign Finance - FPPC Form 465 - Supplemental Independent Expenditure Report - Part 3 - Independent Expenditures Made" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/pyxa-3r7p

property e:pyxa-3r7p t:meta.view v:id=pyxa-3r7p v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 465 - Supplemental Independent Expenditure Report - Part 3 - Independent Expenditures Made" v:attribution="San Francisco Ethics Commission"

property e:pyxa-3r7p t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:pyxa-3r7p t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:pyxa-3r7p t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                  | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | payee_naml            | payee_namf | payee_namt | payee_nams | payee_adr1 | payee_adr2 | payee_city          | payee_state | payee_zip4 | expn_date           | amount  | cum_ytd | expn_chkno | expn_code | expn_dscr                                                                              | agent_naml | agent_namf | agent_namt | agent_nams | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_st | tres_zip4 | cand_naml   | cand_namf | cand_namt | cand_nams | office_cd | offic_dscr | juris_cd | juris_dscr    | dist_no | off_s_h_cd | bal_name                                                                                                   | bal_num | bal_juris     | sup_opp_cd | memo_code | memo_refno | bakref_tid | g_from_e_f | xref_schnm | xref_match | 
| ======== | =========================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | ===================== | ========== | ========== | ========== | ========== | ========== | =================== | =========== | ========== | =================== | ======= | ======= | ========== | ========= | ====================================================================================== | ========== | ========== | ========== | ========== | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | =========== | ========= | ========= | ========= | ========= | ========== | ======== | ============= | ======= | ========== | ========================================================================================================== | ======= | ============= | ========== | ========= | ========== | ========== | ========== | ========== | ========== | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3                          | 0          | RCP            | 2016-05-17T00:00:00 | 2016-05-09T00:00:00 | 2016-05-16T00:00:00 |                     |                    |                     | EXPN     | F465P3    | qY5DNxEIH72r | COM       | Tan                   | Yue Chang  |            |            |            |            | San Francisco       | CA          | 94112      | 2016-05-16T00:00:00 | 92.43   | 1565.19 |            |           | Phone Canvass                                                                          |            |            |            |            | Pending |           |           |           |           |           |           |           |         |           |             |           |           |           |           |            |          |               |         |            | SF Affordable Housing Requirements                                                                         | C       | SF            | S          |           |            |            |            |            |            | 
| 1389926  | Friends of the Mayor, No Recall on Mayor Lee No on D, H, L, & M Committee   | 0          | RCP            | 2017-01-19T00:00:00 | 2016-01-01T00:00:00 | 2016-10-15T00:00:00 |                     |                    |                     | EXPN     | F465P3    | 6TDb588hOK6D | OTH       | World Journal         |            |            |            |            |            | Millbrace           | CA          | 94030      | 2016-10-07T00:00:00 | 1000    | 6946    |            |           | newspaper ad                                                                           |            |            |            |            | 1234567 |           |           |           |           |           |           |           |         |           |             |           |           |           |           |            |          |               |         |            | Recall Mayor Ed Lee                                                                                        | NA      | San Francisco | O          |           |            |            |            |            |            | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3                          | 0          | RCP            | 2016-05-17T00:00:00 | 2016-05-09T00:00:00 | 2016-05-16T00:00:00 |                     |                    |                     | EXPN     | F465P3    | kuK9bGP8CRcw | COM       | Luo                   | Flora      |            |            |            |            | San Francisco       | CA          | 94133      | 2016-05-16T00:00:00 | 143.69  | 1565.19 |            |           | Phone Canvass                                                                          |            |            |            |            | Pending |           |           |           |           |           |           |           |         |           |             |           |           |           |           |            |          |               |         |            | SF Affordable Housing Requirements                                                                         | C       | SF            | S          |           |            |            |            |            |            | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3                          | 0          | RCP            | 2016-05-17T00:00:00 | 2016-05-09T00:00:00 | 2016-05-16T00:00:00 |                     |                    |                     | EXPN     | F465P3    | VnFOnxkbXjhM | COM       | Li                    | Xiu Zhen   |            |            |            |            | San Francisco       | CA          | 94134      | 2016-05-16T00:00:00 | 99.33   | 1565.19 |            |           | Phone Canvass                                                                          |            |            |            |            | Pending |           |           |           |           |           |           |           |         |           |             |           |           |           |           |            |          |               |         |            | SF Affordable Housing Requirements                                                                         | C       | SF            | S          |           |            |            |            |            |            | 
| 970630   | SAN FRANCISCO LABOR & NEIGHBOR MEMBER EDUCATION./POLITICAL ISSUES COMMITTEE | 0          | RCP            | 2016-10-26T00:00:00 | 2016-01-01T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | F465P3    | S465-5244    | OTH       | Terris Barnes Walters |            |            |            |            |            | San Francisco       | CA          | 94104      | 2016-09-29T00:00:00 | 1092.58 | 1092.58 |            | IND       | Door hanger                                                                            |            |            |            |            |         |           |           |           |           |           |           |           |         |           |             |           |           |           |           |            | STW      |               |         |            | Yes on Proposition 55 - Tax Extension to Fund Education and Healthcare Initiative Constitutional Amendment | 55      | Statewide     | S          |           |            |            |            |            |            | 
| 1389926  | Friends of the Mayor, No Recall on Mayor Lee No on D, H, L, & M Committee   | 0          | RCP            | 2017-01-19T00:00:00 | 2016-01-01T00:00:00 | 2016-10-15T00:00:00 |                     |                    |                     | EXPN     | F465P3    | oJTb571ELhTu | OTH       | Sing Tao Daily        |            |            |            |            |            | South San Francisco | CA          | 94080      | 2016-10-10T00:00:00 | 1234    | 6946    |            |           | newspaper ad                                                                           |            |            |            |            | 1234567 |           |           |           |           |           |           |           |         |           |             |           |           |           |           |            |          |               |         |            | Recall Mayor Ed Lee                                                                                        | NA      | San Francisco | O          |           |            |            |            |            |            | 
| 1389926  | Friends of the Mayor, No Recall on Mayor Lee No on D, H, L, & M Committee   | 1          | RCP            | 2017-01-19T00:00:00 | 2016-10-16T00:00:00 | 2016-10-31T00:00:00 |                     |                    |                     | EXPN     | F465P3    | YnQd74quPQuJ | OTH       | World Journal         |            |            |            |            |            | Millbrace           | CA          | 94030      | 2016-10-27T00:00:00 | 1000    | 13655.5 |            |           | news paper ad                                                                          |            |            |            |            | 1234567 |           |           |           |           |           |           |           |         |           |             |           |           |           |           |            |          |               |         |            | Recall Mayor Ed Lee                                                                                        | NA      | San Francisco | O          |           |            |            |            |            |            | 
| 1384192  | San Franciscans for a City that Works                                       | 0          | RCP            | 2016-05-26T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | F465P3    | PDT7         | OTH       | WINNING DIRECTIONS    |            |            |            |            |            | GARDEN VALLEY       | CA          | 95633      | 2016-05-05T00:00:00 | 2203.69 | 2796.7  |            | IND       | IND. EXP. OF CAMPAIGN LITERATURE SUPPORTING JOSHUA ARCE FOR SUPERVISOR, SAN FRANCISCO. |            |            |            |            |         |           |           |           |           |           |           |           |         |           | JOSHUA ARCE |           |           |           | OTH       | SUPERVISOR | OTH      | SAN FRANCISCO | 9       |            |                                                                                                            |         |               | S          |           |            |            |            |            |            | 
| 1389926  | Friends of the Mayor, No Recall on Mayor Lee No on D, H, L, & M Committee   | 1          | RCP            | 2017-01-19T00:00:00 | 2016-10-16T00:00:00 | 2016-10-31T00:00:00 |                     |                    |                     | EXPN     | F465P3    | MVbuPS3IR79W | OTH       | KTSF                  |            |            |            |            |            | Brisbane            | CA          | 94005      | 2016-10-24T00:00:00 | 684     | 13655.5 |            |           | TV AD                                                                                  |            |            |            |            | 1234567 |           |           |           |           |           |           |           |         |           |             |           |           |           |           |            |          |               |         |            | Recall Mayor Ed Lee                                                                                        | NA      | San Francisco | O          |           |            |            |            |            |            | 
| 1384192  | San Franciscans for a City that Works                                       | 0          | RCP            | 2016-05-26T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | F465P3    | PDT2         | OTH       | WINNING DIRECTIONS    |            |            |            |            |            | GARDEN VALLEY       | CA          | 95633      | 2016-05-05T00:00:00 | 593.01  | 2796.7  |            | LIT       | IND. EXP. OF CAMPAIGN LITERATURE SUPPORTING JOSHUA ARCE FOR SUPERVISOR, SAN FRANCISCO. |            |            |            |            |         |           |           |           |           |           |           |           |         |           | JOSHUA ARCE |           |           |           | OTH       | SUPERVISOR | OTH      | SAN FRANCISCO | 9       |            |                                                                                                            |         |               | S          |           |            |            |            |            |            | 
```