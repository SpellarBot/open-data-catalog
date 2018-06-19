# Campaign Finance - FPPC Form 496 - Late Independent Expenditure Report - Independent Expenditures Made

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-496-late-independent-expenditure-report-independent-expenditure-a1f90) |
| Metadata | [Link](https://data.sfgov.org/api/views/4fd4-wqps) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4fd4-wqps/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4fd4-wqps/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4fd4-wqps |
| Name | Campaign Finance - FPPC Form 496 - Late Independent Expenditure Report - Independent Expenditures Made |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, fppc, form, 496, late, independent, expenditure |
| Created | 2012-04-29T02:57:48Z |
| Publication Date | 2014-08-21T08:10:05Z |

## Description

This dataset includes all itemized late independent expenditures ($1000 or more) e-filed on Fair Political Practices Commission (FPPC) Form 496 Late Independent Expenditures Report from 2008 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

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
| Yes      | numeric metric | amount         | Amount         | money         | money         |
| No       |                | exp_date       | Exp_Date       | calendar_date | calendar_date |
| No       |                | date_thru      | Date_Thru      | calendar_date | calendar_date |
| Yes      | series tag     | expn_dscr      | Expn_Dscr      | text          | text          |
| Yes      | series tag     | memo_code      | Memo_Code      | text          | text          |
| Yes      | series tag     | memo_refno     | Memo_RefNo     | text          | text          |
| Yes      | series tag     | bal_name       | Bal_Name       | text          | text          |
| Yes      | series tag     | bal_num        | Bal_Num        | text          | text          |
| Yes      | series tag     | bal_juris      | Bal_Juris      | text          | text          |
| Yes      | series tag     | sup_opp_cd     | Sup_Opp_Cd     | text          | text          |
| Yes      | series tag     | cand_naml      | Cand_NamL      | text          | text          |
| Yes      | series tag     | cand_namf      | Cand_NamF      | text          | text          |
| Yes      | series tag     | cand_namt      | Cand_NamT      | text          | text          |
| Yes      | series tag     | cand_nams      | Cand_NamS      | text          | text          |
| Yes      | series tag     | office_cd      | Office_Cd      | text          | text          |
| Yes      | series tag     | offic_dscr     | Offic_Dscr     | text          | text          |
| Yes      | series tag     | juris_cd       | Juris_Cd       | text          | text          |
| Yes      | series tag     | juris_dscr     | Juris_Dscr     | text          | text          |
| Yes      | series tag     | dist_no        | Dist_No        | text          | number        |
| Yes      | series tag     | rpt_id_num     | Rpt_ID_Num     | text          | text          |
```

## Time Field

```ls
Value = rpt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = from_date,thru_date,elect_date,exp_date,date_thru
```

## Data Commands

```ls
series e:4fd4-wqps d:2010-10-20T00:00:00.000Z t:cand_naml="Debra Walker" t:office_cd=CSU t:dist_no=6 t:filer_naml="Friends Supporting Debra Walker for Supervisor 2010 sponsored by labor organizations" t:juris_dscr="County of San Francisco" t:report_num=0 t:form_type=F496 t:juris_cd=OTH t:rpt_id_num=4153 t:rec_type=S496 t:filer_id=1331560 t:committee_type=RCP t:sup_opp_cd=S t:tran_id=PDT16 t:expn_dscr="Predictive Dialer for Phonebanking (Estimated Expenses)" m:amount=33.5

series e:4fd4-wqps d:2012-11-02T00:00:00.000Z t:cand_naml="CHRISTINA OLAGUE" t:office_cd=OTH t:filer_naml="SAN FRANCISCO WOMEN FOR ACCOUNTABILITY AND A RESPONSIBLE SUPERVISOR OPPOSING CHRISTINA OLAGUE 2012" t:juris_dscr="SAN FRANCISCO" t:report_num=0 t:juris_cd=OTH t:rpt_id_num=HB-G12-42 t:form_type=F496 t:rec_type=S496 t:filer_id=1353184 t:committee_type=RCP t:sup_opp_cd=O t:offic_dscr=SUPERVISOR t:tran_id=EDT7 t:expn_dscr="INDEPENDENT EXPENDITURE OF LITERATURE OPPOSING CHRISTINA OLAGUE, SUPERVISOR, SAN FRANCISCO" m:amount=8569.55

series e:4fd4-wqps d:2010-11-18T00:00:00.000Z t:cand_naml="Rafael Mandelman" t:office_cd=CSU t:dist_no=8 t:filer_naml="Teachers, Nurses, Muni riders, neighbors and working families supporting Mandelman for Supervisor 2010 sponsored by labor organizations" t:juris_dscr="County of San Francisco" t:report_num=1 t:form_type=F496 t:juris_cd=OTH t:rpt_id_num=4945 t:rec_type=S496 t:filer_id=1331561 t:committee_type=RCP t:sup_opp_cd=S t:tran_id=PDT52 t:expn_dscr="Paid Callers for Phonebanking (Estimated Expenses)" m:amount=900.48
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:4fd4-wqps l:"Campaign Finance - FPPC Form 496 - Late Independent Expenditure Report - Independent Expenditures Made" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/4fd4-wqps

property e:4fd4-wqps t:meta.view v:id=4fd4-wqps v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 496 - Late Independent Expenditure Report - Independent Expenditures Made" v:attribution="San Francisco Ethics Commission"

property e:4fd4-wqps t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4fd4-wqps t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:4fd4-wqps t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                              | report_num | committee_type | rpt_date            | from_date | thru_date | elect_date | rec_type | form_type | tran_id      | amount   | exp_date            | date_thru | expn_dscr                                                                                  | memo_code | memo_refno    | bal_name                                                                       | bal_num | bal_juris            | sup_opp_cd | cand_naml        | cand_namf | cand_namt | cand_nams | office_cd | offic_dscr | juris_cd | juris_dscr                         | dist_no | rpt_id_num | 
| ======== | ======================================================================================================================================= | ========== | ============== | =================== | ========= | ========= | ========== | ======== | ========= | ============ | ======== | =================== | ========= | ========================================================================================== | ========= | ============= | ============================================================================== | ======= | ==================== | ========== | ================ | ========= | ========= | ========= | ========= | ========== | ======== | ================================== | ======= | ========== | 
| 1331560  | Friends Supporting Debra Walker for Supervisor 2010 sponsored by labor organizations                                                    | 0          | RCP            | 2010-10-20T00:00:00 |           |           |            | S496     | F496      | PDT16        | 33.5     | 2010-10-20T00:00:00 |           | Predictive Dialer for Phonebanking (Estimated Expenses)                                    |           |               |                                                                                |         |                      | S          | Debra Walker     |           |           |           | CSU       |            | OTH      | County of San Francisco            | 6       | 4153       | 
| 1353184  | SAN FRANCISCO WOMEN FOR ACCOUNTABILITY AND A RESPONSIBLE SUPERVISOR OPPOSING CHRISTINA OLAGUE 2012                                      | 0          | RCP            | 2012-11-02T00:00:00 |           |           |            | S496     | F496      | EDT7         | 8569.55  | 2012-11-01T00:00:00 |           | INDEPENDENT EXPENDITURE OF LITERATURE OPPOSING CHRISTINA OLAGUE, SUPERVISOR, SAN FRANCISCO |           |               |                                                                                |         |                      | O          | CHRISTINA OLAGUE |           |           |           | OTH       | SUPERVISOR | OTH      | SAN FRANCISCO                      |         | HB-G12-42  | 
| 1331561  | Teachers, Nurses, Muni riders, neighbors and working families supporting Mandelman for Supervisor 2010 sponsored by labor organizations | 1          | RCP            | 2010-11-18T00:00:00 |           |           |            | S496     | F496      | PDT52        | 900.48   | 2010-11-01T00:00:00 |           | Paid Callers for Phonebanking (Estimated Expenses)                                         |           |               |                                                                                |         |                      | S          | Rafael Mandelman |           |           |           | CSU       |            | OTH      | County of San Francisco            | 8       | 4945       | 
| 742051   | San Francisco Democratic County Central Committee                                                                                       | 0          | RCP            | 2015-10-24T00:00:00 |           |           |            | S496     | F496      | PDT3535      | 789      | 2015-10-23T00:00:00 |           | Member communication mailer                                                                |           | PDT:S496:3535 |                                                                                |         |                      | S          | Ed Lee           |           |           |           | MAY       |            | OTH      | City & County of San Francisco, CA | 0       | 102315EL   | 
| 742051   | San Francisco Democratic County Central Committee                                                                                       | 0          | RCP            | 2012-11-01T00:00:00 |           |           |            | S496     | F496      | PDT1087      | 861.96   | 2012-10-31T00:00:00 |           | Mailer including all design, production & postage (member communication)                   |           |               | Policy Opposing Corporate Personhood                                           | G       | San Francisco County | S          |                  |           |           |           |           |            |          |                                    |         | 103112#G   | 
| 1229831  | LENNAR HOMES OF CALIFORNIA INC.                                                                                                         | 1          | MDI            | 2008-06-12T00:00:00 |           |           |            | S496     | F496      | EDT538       | 20036.48 | 2008-06-02T00:00:00 |           | PHONE CALLS                                                                                |           |               | MIXED-USE DEVELOPMENT PROJECT FOR CANDLESTICK POINT AND HUNTERS POINT SHIPYARD | G       | CITY & COUNTY OF SF  | S          |                  |           |           |           |           |            |          |                                    |         | LIER08-231 | 
| 891575   | SF FORWARD SPONSORED BY SAN FRANCISCO CHAMBER OF COMMERCE                                                                               | 0          | RCP            | 2012-10-25T00:00:00 |           |           |            | S496     | F496      | EDT95        | 5000     | 2012-10-23T00:00:00 |           | INDEPENDENT EXPENDITURE OF SLATE MAILER SUPPORTING MEASURE B, SAN FRANCISCO.               |           |               | MEASURE B                                                                      |         | SAN FRANCISCO        | S          |                  |           |           |           |           |            |          |                                    |         | G12-SRS-03 | 
| 1380710  | Chinese Progressive Association, nonprofit 501(c)3                                                                                      | 0          |                | 2015-10-23T00:00:00 |           |           |            | S496     | F496      | b221pgvsCDLX | 84.65    | 2015-10-22T00:00:00 |           | Phone Canvass                                                                              |           |               | Short-Term Residential Rentals                                                 | F       | San Francisco        | S          |                  |           |           |           |           |            |          |                                    |         | 2015102301 | 
| 1380893  | Retain Our Independent Sheriff Mirkarimi 2015                                                                                           | 1          | RCP            | 2016-01-22T00:00:00 |           |           |            | S496     | F496      | EDT4         | 15950    | 2015-10-29T00:00:00 |           | Consulting & television production                                                         |           | EDT:S496:4    |                                                                                |         |                      | S          | Ross Mirkarimi   |           |           |           | OTH       | Sheriff    | OTH      | San Francisco                      |         | 20151029-1 | 
| 742051   | San Francisco Democratic County Central Committee                                                                                       | 0          | RCP            | 2015-10-15T00:00:00 |           |           |            | S496     | F496      | PDT3023      | 53.05    | 2015-10-13T00:00:00 |           | Member communication mailer                                                                |           | PDT:S496:3023 |                                                                                |         |                      | S          | Vicki Hennessy   |           |           |           | SHC       |            | OTH      | San Francisco, CA                  |         | 101415VH   | 
```