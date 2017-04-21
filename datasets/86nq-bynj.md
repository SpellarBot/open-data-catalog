# Campaign Finance - FPPC Form 461 - Major Donor and Independent Expenditure Committee Statement - Part 5 - Contributions (Including Loans, Forgiveness of Loans, and Loan Guarantees) and Expenditures...

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-461-major-donor-and-independent-expenditure-committee-statement-7f846) |
| Metadata | [Link](https://data.sfgov.org/api/views/86nq-bynj) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/86nq-bynj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/86nq-bynj/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 86nq-bynj |
| Name | Campaign Finance - FPPC Form 461 - Major Donor and Independent Expenditure Committee Statement - Part 5 - Contributions (Including Loans, Forgiveness of Loans, and Loan Guarantees) and Expenditures... |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, contributions, expenditures, major, donor, independent, expenditure, committee, fppc, form, 461 |
| Created | 2012-04-30T15:38:14Z |
| Publication Date | 2014-08-21T09:07:10Z |

## Description

This dataset includes all itemized Contributions (Including Loans, Forgiveness of Loans, and Loan Guarantees) and Expenditures Made ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 461 "Part 5" Contributions (Including Loans, Forgiveness of Loans, and Loan Guarantees) and Expenditures Made from 2009 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

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
| Yes      | series tag     | emplbus_cb          | EmplBus_CB          | text          | text          |
| Yes      | series tag     | bus_name            | Bus_Name            | text          | text          |
| Yes      | series tag     | bus_adr1            | Bus_Adr1            | text          | text          |
| Yes      | series tag     | bus_adr2            | Bus_Adr2            | text          | text          |
| Yes      | series tag     | bus_city            | Bus_City            | text          | text          |
| Yes      | series tag     | bus_st              | Bus_ST              | text          | text          |
| Yes      | series tag     | bus_zip4            | Bus_ZIP4            | text          | text          |
| Yes      | series tag     | bus_inter           | Bus_Inter           | text          | text          |
| Yes      | series tag     | busact_cb           | BusAct_CB           | text          | text          |
| Yes      | series tag     | busactvity          | BusActvity          | text          | text          |
| Yes      | series tag     | assoc_cb            | Assoc_CB            | text          | text          |
| Yes      | series tag     | assoc_int           | Assoc_Int           | text          | text          |
| Yes      | series tag     | other_cb            | Other_CB            | text          | text          |
| Yes      | series tag     | other_int           | Other_Int           | text          | text          |
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
series e:86nq-bynj d:2017-01-19T00:00:00.000Z t:memo_refno=EDT168 t:payee_state=CA t:payee_zip4=94702 t:entity_cd=OTH t:filer_naml="Tenderloin Neighborhood Development Corporation" t:report_num=1 t:assoc_cb="Non-Profit Housing Association" t:bal_juris="City & County of San Francisco" t:expn_code=IKD t:form_type=F461P5 t:bal_name="Competitive Bidding for Affordable Housing Projects on City-Owned Property; Measure P" t:cmte_id=1306869 t:rec_type=EXPN t:filer_id=SFO154091 t:committee_type=MDI t:payee_naml="Sierra Club, San Francisco Bay Chapter Campaigns SMO" t:sup_opp_cd=O t:payee_city=Berkeley t:expn_dscr="Slate Mailer" t:tran_id=EDT168 m:amount=2000 m:cum_ytd=19000

series e:86nq-bynj d:2016-11-07T00:00:00.000Z t:payee_state=CA t:payee_zip4=94104 t:entity_cd=COM t:bal_num=S t:filer_naml="San Francisco Opera Association" t:report_num=1 t:bal_juris="City & County of San Francisco" t:expn_code=IKD t:form_type=F461P5 t:bal_name="Allocation of Hotel Tax Funds" t:cmte_id=1386300 t:rec_type=EXPN t:filer_id=Pending t:busact_cb=X t:committee_type=MDI t:busactvity="Opera Company" t:payee_naml="Yes on S, San Franciscans for the Arts & Ending Family Homelessness" t:sup_opp_cd=S t:payee_city="San Francisco" t:expn_dscr="Staff time" t:tran_id=NON41 m:amount=28.6 m:cum_ytd=39602.33

series e:86nq-bynj d:2016-11-01T00:00:00.000Z t:tres_naml=Fazio t:payee_state=CA t:payee_zip4=94118 t:entity_cd=COM t:bal_num=I t:filer_naml="MEALS ON WHEELS OF SAN FRANCISCO, INC." t:report_num=0 t:assoc_cb="NON-PROFIT - SENIOR HEALTH" t:bal_juris="San Francisco" t:expn_code=MON t:tres_st=CA t:form_type=F461P5 t:tres_city="San Francisco" t:bal_name="Funding for Seniors and Adults with Disabilities, Measure" t:cmte_id=1381446 t:rec_type=EXPN t:filer_id=PENDING t:committee_type=MDI t:tres_zip4=94118 t:payee_naml="Dignity Fund Coalition, Yes on I" t:sup_opp_cd=S t:payee_city="San Francisco" t:tran_id=INC46 t:tres_namf=Tony m:amount=2500 m:cum_ytd=15000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

metric m:cum_ytd p:double l:Cum_YTD t:dataTypeName=money

metric m:agent_namt p:integer l:Agent_NamT t:dataTypeName=number

entity e:86nq-bynj l:"Campaign Finance - FPPC Form 461 - Major Donor and Independent Expenditure Committee Statement - Part 5 - Contributions (Including Loans, Forgiveness of Loans, and Loan Guarantees) and Expenditures Made" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/86nq-bynj

property e:86nq-bynj t:meta.view v:id=86nq-bynj v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 461 - Major Donor and Independent Expenditure Committee Statement - Part 5 - Contributions (Including Loans, Forgiveness of Loans, and Loan Guarantees) and Expenditures Made" v:attribution="San Francisco Ethics Commission"

property e:86nq-bynj t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:86nq-bynj t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:86nq-bynj t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id  | filer_naml                                      | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | payee_naml                                                          | payee_namf | payee_namt | payee_nams | payee_adr1 | payee_adr2 | payee_city    | payee_state | payee_zip4 | expn_date           | amount | cum_ytd  | expn_chkno | expn_code | expn_dscr    | agent_naml | agent_namf | agent_namt | agent_nams | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city     | tres_st | tres_zip4 | cand_naml | cand_namf | cand_namt | cand_nams | office_cd | offic_dscr | juris_cd | juris_dscr    | dist_no | off_s_h_cd | bal_name                                                                              | bal_num | bal_juris                      | sup_opp_cd | memo_code | memo_refno | bakref_tid | g_from_e_f | xref_schnm | xref_match | emplbus_cb | bus_name         | bus_adr1 | bus_adr2 | bus_city | bus_st | bus_zip4 | bus_inter | busact_cb | busactvity                                                                     | assoc_cb                       | assoc_int | other_cb | other_int | 
| ========= | =============================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | =================================================================== | ========== | ========== | ========== | ========== | ========== | ============= | =========== | ========== | =================== | ====== | ======== | ========== | ========= | ============ | ========== | ========== | ========== | ========== | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ============= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========== | ======== | ============= | ======= | ========== | ===================================================================================== | ======= | ============================== | ========== | ========= | ========== | ========== | ========== | ========== | ========== | ========== | ================ | ======== | ======== | ======== | ====== | ======== | ========= | ========= | ============================================================================== | ============================== | ========= | ======== | ========= | 
| SFO154091 | Tenderloin Neighborhood Development Corporation | 1          | MDI            | 2017-01-19T00:00:00 | 2016-01-01T00:00:00 | 2016-10-22T00:00:00 |                     |                    |                     | EXPN     | F461P5    | EDT168       | OTH       | Sierra Club, San Francisco Bay Chapter Campaigns SMO                |            |            |            |            |            | Berkeley      | CA          | 94702      | 2016-10-13T00:00:00 | 2000   | 19000    |            | IKD       | Slate Mailer |            |            |            |            | 1306869 |           |           |           |           |           |           |               |         |           |           |           |           |           |           |            |          |               |         |            | Competitive Bidding for Affordable Housing Projects on City-Owned Property; Measure P |         | City & County of San Francisco | O          |           | EDT168     |            |            |            |            |            |                  |          |          |          |        |          |           |           |                                                                                | Non-Profit Housing Association |           |          |           | 
| Pending   | San Francisco Opera Association                 | 1          | MDI            | 2016-11-07T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | F461P5    | NON41        | COM       | Yes on S, San Franciscans for the Arts & Ending Family Homelessness |            |            |            |            |            | San Francisco | CA          | 94104      | 2016-06-23T00:00:00 | 28.6   | 39602.33 |            | IKD       | Staff time   |            |            |            |            | 1386300 |           |           |           |           |           |           |               |         |           |           |           |           |           |           |            |          |               |         |            | Allocation of Hotel Tax Funds                                                         | S       | City & County of San Francisco | S          |           |            |            |            |            |            |            |                  |          |          |          |        |          |           | X         | Opera Company                                                                  |                                |           |          |           | 
| PENDING   | MEALS ON WHEELS OF SAN FRANCISCO, INC.          | 0          | MDI            | 2016-11-01T00:00:00 | 2016-01-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | F461P5    | INC46        | COM       | Dignity Fund Coalition, Yes on I                                    |            |            |            |            |            | San Francisco | CA          | 94118      | 2016-03-30T00:00:00 | 2500   | 15000    |            | MON       |              |            |            |            |            | 1381446 | Fazio     | Tony      |           |           |           |           | San Francisco | CA      | 94118     |           |           |           |           |           |            |          |               |         |            | Funding for Seniors and Adults with Disabilities, Measure                             | I       | San Francisco                  | S          |           |            |            |            |            |            |            |                  |          |          |          |        |          |           |           |                                                                                | NON-PROFIT - SENIOR HEALTH     |           |          |           | 
| pending   | Yat-Pang Au and affilated entities              | 0          | MDI            | 2016-12-01T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | F461P5    | y6ckVzBjrN1R | COM       | Jane Kim for DCCC                                                   |            |            |            |            |            | San Francisco | CA          | 94104      | 2016-06-07T00:00:00 | 1000   | 1000     |            | MON       |              |            |            |            |            | 1385346 |           |           |           |           |           |           |               |         |           | Kim       | Jane      |           |           | OTH       | DCCC       | LOC      | San Francisco |         |            |                                                                                       |         |                                | S          |           |            |            |            |            |            | X          |                  |          |          |          |        |          |           |           |                                                                                |                                |           |          |           | 
| Pending   | Yerba Buena Neighborhood Consortium             | 0          | MDI            | 2016-07-11T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | F461P5    | uJVPJa2eyWeR | COM       | Affordable San Francisco For All, Yes On Proposition C              |            |            |            |            |            | San Francisco | CA          | 94114      | 2016-04-25T00:00:00 | 90000  | 125000   |            | MON       |              |            |            |            |            | 1384144 |           |           |           |           |           |           |               |         |           |           |           |           |           |           |            |          |               |         |            | Inclusionary Housing Requirements                                                     | C       | San Francisco                  | S          |           |            |            |            |            |            |            |                  |          |          |          |        |          |           | X         | Nonprofit Community Advocates for San Francisco's South of Market Neighborhood |                                |           |          |           | 
| Pending   | San Francisco Opera Association                 | 1          | MDI            | 2016-11-07T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | F461P5    | NON43        | COM       | Yes on S, San Franciscans for the Arts & Ending Family Homelessness |            |            |            |            |            | San Francisco | CA          | 94104      | 2016-06-28T00:00:00 | 28.6   | 39602.33 |            | IKD       | Staff time   |            |            |            |            | 1386300 |           |           |           |           |           |           |               |         |           |           |           |           |           |           |            |          |               |         |            | Allocation of Hotel Tax Funds                                                         | S       | City & County of San Francisco | S          |           |            |            |            |            |            |            |                  |          |          |          |        |          |           | X         | Opera Company                                                                  |                                |           |          |           | 
| SFO154331 | OSL BISON, LLC                                  | 0          | MDI            | 2016-05-26T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | F461P5    | EXP1         | COM       | YES ON B, SAN FRANCISCANS FOR BETTER, SUSTAINABLE PARKS             |            |            |            |            |            | SAN FRANCISCO | CA          | 94108      | 2016-05-09T00:00:00 | 25000  | 25000    |            | MON       |              |            |            |            |            |         |           |           |           |           |           |           |               |         |           |           |           |           |           |           |            |          |               |         |            | MEASURE B                                                                             |         | SAN FRANCISCO                  | S          |           |            |            |            |            |            |            |                  |          |          |          |        |          |           | X         | ENTERTAINMENT                                                                  |                                |           |          |           | 
| pending   | Yat-Pang Au and affilated entities              | 0          | MDI            | 2016-12-01T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | F461P5    | laAj5r9SlXdm | COM       | Mayor Libby Schaaf for Oakland                                      |            |            |            |            |            | Oaklabd       | CA          | 94607      | 2016-04-20T00:00:00 | 1000   | 1000     |            | MON       |              |            |            |            |            | 1379188 |           |           |           |           |           |           |               |         |           | Schaaf    | Libby     |           |           | MAY       |            | CIT      |               |         |            |                                                                                       |         |                                | S          |           |            |            |            |            |            | X          |                  |          |          |          |        |          |           |           |                                                                                |                                |           |          |           | 
| pending   | San Francisco Travel Association                | 0          | MDI            | 2016-10-19T00:00:00 | 2016-01-01T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | F461P5    | WsyO7uzayys6 | COM       | San Franciscans for Housing Not Tents                               |            |            |            |            |            | San Francisco | CA          | 94104      | 2016-10-06T00:00:00 | 5000   | 10000    |            | MON       |              |            |            |            |            | 1387859 |           |           |           |           |           |           |               |         |           |           |           |           |           |           |            |          |               |         |            | Prohibiting Tents on Public Sidewalks                                                 | Q       | San Francisco                  | S          |           |            |            |            |            |            |            |                  |          |          |          |        |          |           |           |                                                                                |                                |           |          |           | 
| SFO154351 | MICK HELLMAN                                    | 0          | MDI            | 2016-05-27T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | F461P5    | EXP1         | COM       | YES ON B, SAN FRANCISCANS FOR BETTER, SUSTAINABLE PARKS             |            |            |            |            |            | SAN FRANCISCO | CA          | 94108      | 2016-05-20T00:00:00 | 20000  | 20000    |            | MON       |              |            |            |            |            | 1379182 |           |           |           |           |           |           |               |         |           |           |           |           |           |           |            |          |               |         |            | MEASURE B                                                                             |         | SAN FRANCISCO                  | S          |           |            |            |            |            |            | X          | HMI CAPITAL, LLC |          |          |          |        |          |           |           |                                                                                | PRIVATE INVESTMENTS            |           |          |           | 
```