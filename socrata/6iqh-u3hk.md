# Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-g-payments-made-by-an-agent-or-independent-contrac-ad4e0) |
| Metadata | [Link](https://data.sfgov.org/api/views/6iqh-u3hk) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/6iqh-u3hk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/6iqh-u3hk/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 6iqh-u3hk |
| Name | Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, payments, agent, independent, contractor, fppc, form, 460 |
| Created | 2012-04-30T16:17:42Z |
| Publication Date | 2014-08-21T09:13:40Z |

## Description

This dataset includes all itemized payments made by an agent or independent contractor ($500 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "G" Payments Made by an Agent or Independent Contractor from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | filer_id            | Filer_ID            | text          | text          |
| Yes      | series tag     | filer_naml          | Filer_NamL          | text          | text          |
| Yes      | series tag     | report_num          | Report_Num          | text          | number        |
| Yes      | series tag     | committee_type      | Committee_Type      | text          | text          |
| No       |                | rpt_date            | Rpt_Date            | calendar_date | calendar_date |
| Yes      | time           | from_date           | From_Date           | calendar_date | calendar_date |
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
Value = from_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = rpt_date,thru_date,elect_date,expn_date
```

## Data Commands

```ls
series e:6iqh-u3hk d:2016-07-01T00:00:00.000Z t:filer_naml="Vote Marjan Philhour for Supervisor 2016" t:entity_cd=OTH t:juris_dscr="San Francisco, CA" t:g_from_e_f=E t:expn_dscr="Sales Tax" t:office_cd=CSU t:tran_id=EDT48 t:payee_zip4=94612 t:form_type=G t:agent_naml="Spotlight Printing" t:filer_id=1374373 t:payee_naml="State Board of Equalization" t:cand_naml=Philhour t:juris_cd=OTH t:rec_type=EXPN t:payee_city=Oakland t:payee_state=CA t:report_num=1 t:dist_no=1 t:expn_code=CMP t:cand_namf=Marjan t:committee_type=CTL m:amount=48.13 m:cum_ytd=1391.38

series e:6iqh-u3hk d:2016-07-01T00:00:00.000Z t:sup_opp_cd=O t:filer_naml="NO ON V, ENOUGH IS ENOUGH: DON'T TAX OUR GROCERIES, WITH MAJOR FUNDING BY AMERICAN BEVERAGE ASSOCIATION CALIFORNIA PAC" t:entity_cd=OTH t:g_from_e_f=E t:tran_id=EDT28 t:payee_zip4=94080 t:form_type=G t:agent_naml="STOREFRONT POLITICAL MEDIA" t:bal_juris="CITY AND COUNTY OF SAN FRANCISCO" t:filer_id=1382995 t:payee_naml="SING TAO DAILY" t:bal_name="TAX ON DISTRIBUTING SUGAR-SWEETENED BEVERAGES - PROPOSITION V" t:rec_type=EXPN t:payee_city="San Francisco" t:payee_state=CA t:report_num=2 t:expn_code=PRT t:committee_type=BMC m:amount=36691.2 m:cum_ytd=36691.2

series e:6iqh-u3hk d:2016-05-22T00:00:00.000Z t:filer_naml="Sandra Lee Fewer for Supervisor 2016" t:entity_cd=OTH t:juris_dscr="San Francisco District 1" t:g_from_e_f=E t:office_cd=CSU t:tran_id=VSFW49QASM0 t:payee_zip4=84401 t:form_type=G t:agent_naml="River City Business Services" t:filer_id=1382203 t:payee_naml="Internal Revenue Service" t:cand_naml="Lee Fewer" t:juris_cd=CTY t:rec_type=EXPN t:payee_city=Ogden t:payee_state=UT t:report_num=1 t:dist_no=1 t:expn_code=SAL t:cand_namf=Sandra t:committee_type=CAO m:amount=736.97 m:cum_ytd=0
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

metric m:cum_ytd p:double l:Cum_YTD t:dataTypeName=money

entity e:6iqh-u3hk l:"Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/6iqh-u3hk

property e:6iqh-u3hk t:meta.view d:2017-09-25T07:23:45.607Z v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor" v:attribution="San Francisco Ethics Commission" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:id=6iqh-u3hk v:category="City Management and Ethics"

property e:6iqh-u3hk t:meta.view.license d:2017-09-25T07:23:45.607Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:6iqh-u3hk t:meta.view.owner d:2017-09-25T07:23:45.607Z v:displayName="San Francisco Ethics Commission" v:lastNotificationSeenAt=1500665894 v:id=kcqd-yeev v:screenName="San Francisco Ethics Commission"

property e:6iqh-u3hk t:meta.view.tableauthor d:2017-09-25T07:23:45.607Z v:displayName="San Francisco Ethics Commission" v:lastNotificationSeenAt=1500665894 v:roleName=publisher v:id=kcqd-yeev v:screenName="San Francisco Ethics Commission"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                                 | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | payee_naml                  | payee_namf | payee_namt | payee_nams | payee_adr1 | payee_adr2 | payee_city    | payee_state | payee_zip4 | expn_date           | amount  | cum_ytd | expn_chkno | expn_code | expn_dscr                | agent_naml                                  | agent_namf | agent_namt | agent_nams | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_st | tres_zip4 | cand_naml | cand_namf | cand_namt | cand_nams | office_cd | offic_dscr                          | juris_cd | juris_dscr               | dist_no | off_s_h_cd | bal_name                                                                 | bal_num | bal_juris                        | sup_opp_cd | memo_code | memo_refno | bakref_tid | g_from_e_f | xref_schnm | xref_match | 
| ======== | ========================================================================================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | =========================== | ========== | ========== | ========== | ========== | ========== | ============= | =========== | ========== | =================== | ======= | ======= | ========== | ========= | ======================== | =========================================== | ========== | ========== | ========== | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | =================================== | ======== | ======================== | ======= | ========== | ======================================================================== | ======= | ================================ | ========== | ========= | ========== | ========== | ========== | ========== | ========== | 
| 1374373  | Vote Marjan Philhour for Supervisor 2016                                                                                                   | 1          | CTL            | 2016-09-30T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | G         | EDT48        | OTH       | State Board of Equalization |            |            |            |            |            | Oakland       | CA          | 94612      | 2016-07-07T00:00:00 | 48.13   | 1391.38 |            | CMP       | Sales Tax                | Spotlight Printing                          |            |            |            |         |           |           |           |           |           |           |           |         |           | Philhour  | Marjan    |           |           | CSU       |                                     | OTH      | San Francisco, CA        | 1       |            |                                                                          |         |                                  |            |           |            |            | E          |            |            | 
| 1382995  | NO ON V, ENOUGH IS ENOUGH: DON'T TAX OUR GROCERIES, WITH MAJOR FUNDING BY AMERICAN BEVERAGE ASSOCIATION CALIFORNIA PAC                     | 2          | BMC            | 2016-12-19T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | G         | EDT28        | OTH       | SING TAO DAILY              |            |            |            |            |            | San Francisco | CA          | 94080      | 2016-08-26T00:00:00 | 36691.2 | 36691.2 |            | PRT       |                          | STOREFRONT POLITICAL MEDIA                  |            |            |            |         |           |           |           |           |           |           |           |         |           |           |           |           |           |           |                                     |          |                          |         |            | TAX ON DISTRIBUTING SUGAR-SWEETENED BEVERAGES - PROPOSITION V            |         | CITY AND COUNTY OF SAN FRANCISCO | O          |           |            |            | E          |            |            | 
| 1382203  | Sandra Lee Fewer for Supervisor 2016                                                                                                       | 1          | CAO            | 2016-09-06T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | G         | VSFW49QASM0  | OTH       | Internal Revenue Service    |            |            |            |            |            | Ogden         | UT          | 84401      | 2016-05-26T00:00:00 | 736.97  | 0       |            | SAL       |                          | River City Business Services                |            |            |            |         |           |           |           |           |           |           |           |         |           | Lee Fewer | Sandra    |           |           | CSU       |                                     | CTY      | San Francisco District 1 | 1       |            |                                                                          |         |                                  |            |           |            |            | E          |            |            | 
| 1386199  | JOBS, HOUSING AND PARKS NOW FOR CANDLESTICK POINT & HUNTERS POINT SHIPYARD, YES ON O, WITH MAJOR FUNDING BY FIVE POINT HOLDINGS, LLC       | 1          | BMC            | 2016-11-07T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | G         | PDT44        | OTH       | GOOGLE INC                  |            |            |            |            |            | Mountain View | CA          | 94043      | 2016-10-14T00:00:00 | 4250    | 9050    |            |           | DIGITAL MEDIA            | STOREFRONT POLITICAL MEDIA                  |            |            |            |         |           |           |           |           |           |           |           |         |           |           |           |           |           |           |                                     |          |                          |         |            | OFFICE DEVELOPMENT IN CANDLESTICK POINT AND HUNTERS POINT: PROPOSITION O |         | CITY AND COUNTY OF SAN FRANCISCO | S          |           | PDT44      |            | E          |            |            | 
| 1387859  | San Franciscans for Housing Not Tents - Yes on Q with major funding by Committee on Jobs Government Reform Fund and San Francisco Forward. | 1          | BMC            | 2016-10-20T00:00:00 | 2016-01-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | G         | PDT13        | OTH       | Zebra Graphics              |            |            |            |            |            | San Francisco | CA          | 94103      | 2016-09-13T00:00:00 | 1300    | 2700    |            | CMP       |                          | Whitehurst/Mosher Strategy & Media          |            |            |            |         |           |           |           |           |           |           |           |         |           |           |           |           |           |           |                                     |          |                          |         |            | Initiative Ordinance - Promotion of Safe and Open Sidewalks.             | Q       | San Francisco, CA                | S          |           |            |            | E          |            |            | 
| 1382203  | Sandra Lee Fewer for Supervisor 2016                                                                                                       | 2          | CAO            | 2016-05-24T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | G         | VSFW49N2385  | OTH       | Spotlight Printing          |            |            |            |            |            | San Francisco | CA          | 94107-1014 | 2016-04-20T00:00:00 | 150     | 0       |            | LIT       |                          | Stearns Consulting                          |            |            |            |         |           |           |           |           |           |           |           |         |           | Lee Fewer | Sandra    |           |           | CSU       |                                     | CTY      | San Francisco District 1 | 1       |            |                                                                          |         |                                  |            |           |            |            | E          |            |            | 
| 1377719  | Norman Yee for Supervisor 2016                                                                                                             | 1          | CTL            | 2016-08-01T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | G         | U5YdwSjXeaUX | OTH       | USPS - CAPS                 |            |            |            |            |            | San Mateo     | CA          | 94497      | 2016-06-11T00:00:00 | 470     | 1037    |            | POS       |                          | Terris, Barnes & Walters                    |            |            |            |         |           |           |           |           |           |           |           |         |           | Yee       | Norman    |           |           | CSU       |                                     | CTY      |                          | 7       |            |                                                                          |         |                                  | S          |           |            |            |            |            |            | 
| 1384000  | SUPERVISOR MARK FARRELL FOR DEMOCRATIC COUNTY CENTRAL COMMITTEE 2016                                                                       | 0          | CTL            | 2016-06-01T00:00:00 | 2016-04-24T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | EXPN     | G         | PDT31        | OTH       | BASIC 8 CREATIVE            |            |            |            |            |            | SAN FRANCISCO | CA          | 94114      | 2016-05-13T00:00:00 | 1200    | 11700   |            | LIT       |                          | WHITEHURST/MOSHER CAMPAIGN STRATEGY & MEDIA |            |            |            |         |           |           |           |           |           |           |           |         |           | FARRELL   | MARK      |           |           | OTH       | DEMOCRATIC COUNTY CENTRAL COMMITTEE | ASM      |                          | 19      |            |                                                                          |         |                                  |            |           |            |            | E          |            |            | 
| 1386199  | JOBS, HOUSING AND PARKS NOW FOR CANDLESTICK POINT & HUNTERS POINT SHIPYARD, YES ON O, WITH MAJOR FUNDING BY FIVE POINT HOLDINGS, LLC       | 1          | BMC            | 2016-11-07T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | EXPN     | G         | PDT93        | IND       | BRAVO                       | ADRIANO    |            |            |            |            | Oakland       | CA          | 94611      | 2016-10-20T00:00:00 | 900     | 1850    |            |           | DIGITAL MEDIA PRODUCTION | STOREFRONT POLITICAL MEDIA                  |            |            |            |         |           |           |           |           |           |           |           |         |           |           |           |           |           |           |                                     |          |                          |         |            | OFFICE DEVELOPMENT IN CANDLESTICK POINT AND HUNTERS POINT: PROPOSITION O |         | CITY AND COUNTY OF SAN FRANCISCO | S          |           |            |            | E          |            |            | 
| 1250905  | Newsom for Mayor                                                                                                                           | 2          | CTL            | 2004-09-16T00:00:00 | 2003-07-01T00:00:00 | 2003-09-20T00:00:00 | 2003-11-04T00:00:00 |                    |                     | EXPN     | G         | G1355        | IND       | Do                          | Lynn       |            |            |            |            | Fremont       | CA          | 94536      | 2003-09-15T00:00:00 | 1235.67 | 6178.35 | 0          | SAL       |                          | ADP                                         |            |            |            |         |           |           |           |           |           |           |           |         |           | Newsom    | Gavin     |           |           | MAY       |                                     | LOC      |                          |         |            |                                                                          |         |                                  | S          |           |            |            |            |            |            | 
```