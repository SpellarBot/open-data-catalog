# Campaign Finance - FPPC Form 460 - Schedule D - Summary of Expenditures Supporting/Opposing Other Candidates, Measures and Committees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-d-summary-of-expenditures-supporting-opposing-othe-d044e) |
| Metadata | [Link](https://data.sfgov.org/api/views/i8us-xn7t) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/i8us-xn7t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/i8us-xn7t/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | i8us-xn7t |
| Name | Campaign Finance - FPPC Form 460 - Schedule D - Summary of Expenditures Supporting/Opposing Other Candidates, Measures and Committees |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, fppc, form, 460, expenditures, support, oppose, candidates, measures, committees |
| Created | 2012-04-30T04:16:11Z |
| Publication Date | 2014-08-21T09:15:52Z |

## Description

This dataset includes all itemized expenditures supporting/opposing other candidates, measures and committees ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "D" Expenditures Supporting/Opposing Other Candidates, Measures and Committees from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

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
series e:i8us-xn7t d:2016-10-22T00:00:00.000Z t:cand_naml="AHSHA SAFAI" t:payee_state=CA t:payee_zip4=94122 t:entity_cd=COM t:dist_no=11 t:office_cd=OTH t:filer_naml="PROTECT SF, A COMMITTEE SUPPORTING SAFAI FOR SUPERVISOR 2016 AND SPONSORED BY THE SAN FRANCISCO FIRE FIGHTERS...(see addt'l comments)" t:juris_dscr="SAN FRANCISCO" t:report_num=2 t:expn_code=IND t:juris_cd=OTH t:form_type=D t:rec_type=EXPN t:filer_id=1390689 t:committee_type=RCP t:payee_naml="AHSHA SAFAI FOR DISTRICT 11 SUPERVISOR - 2016" t:sup_opp_cd=S t:payee_city="SAN FRANCISCO" t:expn_dscr="INDEPENDENT EXPENDITURE OF LITERATURE SUPPORTING AHSHA SAFAI FOR SUPERVISOR, SF" t:tran_id=PDT23 t:offic_dscr=SUPERVISOR m:amount=4946.88 m:cum_ytd=406924.96

series e:i8us-xn7t d:2016-10-22T00:00:00.000Z t:entity_cd=COM t:bal_num=W t:filer_naml="Alice B. Toklas Lesbian and Gay Democratic Club PAC" t:report_num=1 t:bal_juris="City & County of San Francisco, CA" t:expn_code=IND t:form_type=D t:bal_name="Real Estate Transfer Tax on Properties Over $5 Million" t:rec_type=EXPN t:filer_id=842018 t:committee_type=RCP t:payee_naml="Yes on Prop W - 2016" t:sup_opp_cd=S t:expn_dscr=Slate t:tran_id=EDT2892 m:amount=3.39 m:cum_ytd=146.82

series e:i8us-xn7t d:2016-06-30T00:00:00.000Z t:cand_naml="JOSHUA ARCE" t:payee_state=CA t:payee_zip4=94105 t:entity_cd=COM t:dist_no=17 t:office_cd=OTH t:filer_naml="SAN FRANCISCO DEMOCRATS UNITED FOR PROGRESS, SUPPORTING 23 CANDIDATES FOR THE 2016 SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE, INCLUDING TOM A. HSIEH JR. (COMPLETE COMMITTEE NAME ATTACHED)" t:report_num=0 t:expn_code=IKD t:juris_cd=ASM t:form_type=D t:rec_type=EXPN t:filer_id=1385333 t:committee_type=RCP t:payee_naml="JOSHUA ARCE FOR SFDCCC MEMBER 2016" t:sup_opp_cd=S t:payee_city="SAN FRANCISCO" t:expn_dscr="IN-KIND CONTRIBUTION OF CANVASSING" t:tran_id=EDT913 t:offic_dscr="DEMOCRATIC COUNTY CENTRAL COMMITTEE" m:amount=53.33 m:cum_ytd=5578.58
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

metric m:cum_ytd p:double l:Cum_YTD t:dataTypeName=money

metric m:agent_namt p:integer l:Agent_NamT t:dataTypeName=number

entity e:i8us-xn7t l:"Campaign Finance - FPPC Form 460 - Schedule D - Summary of Expenditures Supporting/Opposing Other Candidates, Measures and Committees" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/i8us-xn7t

property e:i8us-xn7t t:meta.view v:id=i8us-xn7t v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule D - Summary of Expenditures Supporting/Opposing Other Candidates, Measures and Committees" v:attribution="San Francisco Ethics Commission"

property e:i8us-xn7t t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:i8us-xn7t t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:i8us-xn7t t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                                                                                          | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | payee_naml                                                | payee_namf | payee_namt | payee_nams | payee_adr1 | payee_adr2 | payee_city    | payee_state | payee_zip4 | expn_date           | amount  | cum_ytd   | expn_chkno | expn_code | expn_dscr                                                                               | agent_naml | agent_namf | agent_namt | agent_nams | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_st | tres_zip4 | cand_naml       | cand_namf | cand_namt | cand_nams | office_cd | offic_dscr                          | juris_cd | juris_dscr                     | dist_no | off_s_h_cd | bal_name                                                                                                                   | bal_num | bal_juris                          | sup_opp_cd | memo_code | memo_refno | bakref_tid | g_from_e_f | xref_schnm | xref_match | 
| ======== | =================================================================================================================================================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | ========================================================= | ========== | ========== | ========== | ========== | ========== | ============= | =========== | ========== | =================== | ======= | ========= | ========== | ========= | ======================================================================================= | ========== | ========== | ========== | ========== | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | =============== | ========= | ========= | ========= | ========= | =================================== | ======== | ============================== | ======= | ========== | ========================================================================================================================== | ======= | ================================== | ========== | ========= | ========== | ========== | ========== | ========== | ========== | 
| 1390689  | PROTECT SF, A COMMITTEE SUPPORTING SAFAI FOR SUPERVISOR 2016 AND SPONSORED BY THE SAN FRANCISCO FIRE FIGHTERS...(see addt'l comments)                                                               | 2          | RCP            | 2016-12-14T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | D         | PDT23        | COM       | AHSHA SAFAI FOR DISTRICT 11 SUPERVISOR - 2016             |            |            |            |            |            | SAN FRANCISCO | CA          | 94122      | 2016-10-11T00:00:00 | 4946.88 | 406924.96 |            | IND       | INDEPENDENT EXPENDITURE OF LITERATURE SUPPORTING AHSHA SAFAI FOR SUPERVISOR, SF         |            |            |            |            |         |           |           |           |           |           |           |           |         |           | AHSHA SAFAI     |           |           |           | OTH       | SUPERVISOR                          | OTH      | SAN FRANCISCO                  | 11      |            |                                                                                                                            |         |                                    | S          |           |            |            |            |            |            | 
| 842018   | Alice B. Toklas Lesbian and Gay Democratic Club PAC                                                                                                                                                 | 1          | RCP            | 2016-11-08T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | D         | EDT2892      | COM       | Yes on Prop W - 2016                                      |            |            |            |            |            |               |             |            | 2016-10-16T00:00:00 | 3.39    | 146.82    |            | IND       | Slate                                                                                   |            |            |            |            |         |           |           |           |           |           |           |           |         |           |                 |           |           |           |           |                                     |          |                                |         |            | Real Estate Transfer Tax on Properties Over $5 Million                                                                     | W       | City & County of San Francisco, CA | S          |           |            |            |            |            |            | 
| 1385333  | SAN FRANCISCO DEMOCRATS UNITED FOR PROGRESS, SUPPORTING 23 CANDIDATES FOR THE 2016 SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE, INCLUDING TOM A. HSIEH JR. (COMPLETE COMMITTEE NAME ATTACHED) | 0          | RCP            | 2016-08-01T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | EXPN     | D         | EDT913       | COM       | JOSHUA ARCE FOR SFDCCC MEMBER 2016                        |            |            |            |            |            | SAN FRANCISCO | CA          | 94105      | 2016-06-07T00:00:00 | 53.33   | 5578.58   |            | IKD       | IN-KIND CONTRIBUTION OF CANVASSING                                                      |            |            |            |            |         |           |           |           |           |           |           |           |         |           | JOSHUA ARCE     |           |           |           | OTH       | DEMOCRATIC COUNTY CENTRAL COMMITTEE | ASM      |                                | 17      |            |                                                                                                                            |         |                                    | S          |           |            |            |            |            |            | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3                                                                                                                                                  | 0          | RCP            | 2016-09-29T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | D         | WhApcpZ9DUqk | COM       | Chen                                                      | Pei Fang   |            |            |            |            | San Francisco | CA          | 94124      | 2016-09-22T00:00:00 | 18.36   | 2195.67   |            | IND       | Phone Canvass                                                                           |            |            |            |            |         |           |           |           |           |           |           |           |         |           |                 |           |           |           |           |                                     |          |                                |         |            | Real Estate Transfer Tax on Properties Over $5 Million                                                                     | W       | San Francisco                      | S          |           |            |            |            |            |            | 
| 1378915  | San Francisco Tenants and Families for Affordable Housing, sponsored by community and labor organizations                                                                                           | 0          | RCP            | 2016-05-26T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | D         | PDT229       | COM       | Bevan Dufty for Democratic County Central Committee 2016  |            |            |            |            |            | San Francisco | CA          | 94114      | 2016-05-04T00:00:00 | 535.71  | 1283.13   |            | IKD       | Phonebanking                                                                            |            |            |            |            |         |           |           |           |           |           |           |           |         |           | Bevan Dufty     |           |           |           | OTH       | Board Member                        | OTH      | San Francisco DCCC             | 17      |            |                                                                                                                            |         |                                    | S          |           |            |            |            |            |            | 
| 1385333  | SAN FRANCISCO DEMOCRATS UNITED FOR PROGRESS, SUPPORTING 23 CANDIDATES FOR THE 2016 SAN FRANCISCO DEMOCRATIC COUNTY CENTRAL COMMITTEE, INCLUDING TOM A. HSIEH JR. (COMPLETE COMMITTEE NAME ATTACHED) | 0          | RCP            | 2016-08-01T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | EXPN     | D         | EDT726       | COM       | EMILY MURASE FOR DEMOCRATIC COUNTY CENTRAL COMMITTEE 2016 |            |            |            |            |            | SAN FRANCISCO | CA          | 94132      | 2016-06-07T00:00:00 | 40      | 10216.74  |            | IKD       | IN-KIND CONTRIBUTION OF CANVASSING                                                      |            |            |            |            |         |           |           |           |           |           |           |           |         |           | EMILY MURASE    |           |           |           | OTH       | DEMOCRATIC COUNTY CENTRAL COMMITTEE | ASM      |                                | 19      |            |                                                                                                                            |         |                                    | S          |           |            |            |            |            |            | 
| 1384192  | San Franciscans for a City that Works (See Full Committee Name on Addt'l Page)                                                                                                                      | 1          | RCP            | 2016-10-27T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | D         | EDT137       | OTH       | AHSHA SAFAI, SUPERVISOR, 11/2016                          |            |            |            |            |            |               |             |            | 2016-10-10T00:00:00 | 4648    | 56599.17  |            | IND       | EST IND EXP OF CANVASSING SUPPORTING A SAFAI FOR SUPERVISOR, SF COVERING 10/10-10/16/16 |            |            |            |            |         |           |           |           |           |           |           |           |         |           | AHSHA SAFAI     |           |           |           | OTH       | SUPERVISOR                          | OTH      | SAN FRANCISCO                  | 11      |            |                                                                                                                            |         |                                    | S          |           |            |            |            |            |            | 
| 842018   | Alice B. Toklas Lesbian and Gay Democratic Club PAC                                                                                                                                                 | 1          | RCP            | 2016-11-08T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | D         | EDT2688      | COM       | Marjan Philhour for Supervisor 2016                       |            |            |            |            |            | San Francisco | CA          | 94114      | 2016-10-13T00:00:00 | 75.35   | 529.43    |            | IND       | Print Ad                                                                                |            |            |            |            |         |           |           |           |           |           |           |           |         |           | Marjan Philhour |           |           |           | OTH       | Supervisor                          | OTH      | City & County of San Francisco | 1       |            |                                                                                                                            |         |                                    | S          |           |            |            |            |            |            | 
| 842018   | Alice B. Toklas Lesbian and Gay Democratic Club PAC                                                                                                                                                 | 1          | RCP            | 2016-11-08T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | D         | EDT2738      | COM       | Yes on Prop 57 - 2016                                     |            |            |            |            |            |               |             |            | 2016-10-10T00:00:00 | 3.59    | 146.82    |            | IND       | Online Ads                                                                              |            |            |            |            |         |           |           |           |           |           |           |           |         |           |                 |           |           |           |           |                                     |          |                                |         |            | Criminal Sentences. Parole. Juvenile Criminal Proceedings and Sentencing. Initiative Constitutional Amendment and Statute. | 57      | State of California                | S          |           |            |            |            |            |            | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3                                                                                                                                                  | 1          | RCP            | 2016-09-21T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | EXPN     | D         | oMhnVmzjSrbH | COM       | Luo                                                       | Flora      |            |            |            |            | San Francisco | CA          | 94133      | 2016-05-26T00:00:00 | 50.28   | 4145.4    |            | IND       | Phone Canvass                                                                           |            |            |            |            |         |           |           |           |           |           |           |           |         |           |                 |           |           |           |           |                                     |          |                                |         |            | SF Affordable Housing Requirements                                                                                         | C       | SF                                 | S          |           |            |            |            |            |            | 
```