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
| Rows Updated | 2017-03-09T16:13:14Z |

## Description

This dataset includes all itemized payments made by an agent or independent contractor ($500 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "G" Payments Made by an Agent or Independent Contractor from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | filer_id            | Filer_ID            | text          | text          |
| Yes      | series tag     | filer_naml          | Filer_NamL          | text          | text          |
| Yes      | numeric metric | report_num          | Report_Num          | number        | number        |
| Yes      | series tag     | committee_type      | Committee_Type      | text          | text          |
| No       |                | rpt_date            | Rpt_Date            | calendar_date | calendar_date |
| Yes      | series tag     | from_date           | From_Date           | calendar_date | calendar_date |
| Yes      | series tag     | thru_date           | Thru_Date           | calendar_date | calendar_date |
| Yes      | series tag     | elect_date          | Elect_Date          | calendar_date | calendar_date |
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
| Yes      | time           | expn_date           | Expn_Date           | calendar_date | calendar_date |
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
Value = expn_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = rpt_date
```

## Data Commands

```ls
series e:6iqh-u3hk d:2016-07-07T00:00:00.000Z t:thru_date=2016-09-24T00:00:00 t:cand_naml=Philhour t:payee_state=CA t:payee_zip4=94612 t:cand_namf=Marjan t:entity_cd=OTH t:from_date=2016-07-01T00:00:00 t:dist_no=1 t:office_cd=CSU t:filer_naml="Vote Marjan Philhour for Supervisor 2016" t:juris_dscr="San Francisco, CA" t:expn_code=CMP t:elect_date=2016-11-08T00:00:00 t:juris_cd=OTH t:agent_naml="Spotlight Printing" t:form_type=G t:rec_type=EXPN t:g_from_e_f=E t:filer_id=1374373 t:committee_type=CTL t:payee_naml="State Board of Equalization" t:payee_city=Oakland t:expn_dscr="Sales Tax" t:tran_id=EDT48 m:amount=48.13 m:report_num=1 m:cum_ytd=1391.38

series e:6iqh-u3hk d:2016-08-26T00:00:00.000Z t:thru_date=2016-09-24T00:00:00 t:payee_state=CA t:payee_zip4=94080 t:entity_cd=OTH t:from_date=2016-07-01T00:00:00 t:filer_naml="NO ON V, ENOUGH IS ENOUGH: DON'T TAX OUR GROCERIES, WITH MAJOR FUNDING BY AMERICAN BEVERAGE ASSOCIATION CALIFORNIA PAC" t:bal_juris="CITY AND COUNTY OF SAN FRANCISCO" t:expn_code=PRT t:elect_date=2016-11-08T00:00:00 t:agent_naml="STOREFRONT POLITICAL MEDIA" t:form_type=G t:bal_name="TAX ON DISTRIBUTING SUGAR-SWEETENED BEVERAGES - PROPOSITION V" t:rec_type=EXPN t:g_from_e_f=E t:filer_id=1382995 t:committee_type=BMC t:payee_naml="SING TAO DAILY" t:sup_opp_cd=O t:payee_city="San Francisco" t:tran_id=EDT28 m:amount=36691.2 m:report_num=2 m:cum_ytd=36691.2

series e:6iqh-u3hk d:2016-05-26T00:00:00.000Z t:thru_date=2016-06-30T00:00:00 t:cand_naml="Lee Fewer" t:payee_state=UT t:payee_zip4=84401 t:cand_namf=Sandra t:entity_cd=OTH t:from_date=2016-05-22T00:00:00 t:dist_no=1 t:office_cd=CSU t:filer_naml="Sandra Lee Fewer for Supervisor 2016" t:juris_dscr="San Francisco District 1" t:expn_code=SAL t:elect_date=2016-11-08T00:00:00 t:juris_cd=CTY t:agent_naml="River City Business Services" t:form_type=G t:rec_type=EXPN t:g_from_e_f=E t:filer_id=1382203 t:committee_type=CAO t:payee_naml="Internal Revenue Service" t:payee_city=Ogden t:tran_id=VSFW49QASM0 m:amount=736.97 m:report_num=1 m:cum_ytd=0
```

## Meta Commands

```ls
metric m:report_num p:integer l:Report_Num t:dataTypeName=number

metric m:amount p:double l:Amount t:dataTypeName=money

metric m:cum_ytd p:double l:Cum_YTD t:dataTypeName=money

entity e:6iqh-u3hk l:"Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/6iqh-u3hk

property e:6iqh-u3hk t:meta.view v:id=6iqh-u3hk v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor" v:attribution="San Francisco Ethics Commission"

property e:6iqh-u3hk t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:6iqh-u3hk t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:6iqh-u3hk t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```