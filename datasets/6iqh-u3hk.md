# Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/6iqh-u3hk/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-g-payments-made-by-an-agent-or-independent-contrac-ad4e0)
* [Metadata URL](https://data.sfgov.org/api/views/6iqh-u3hk)
* Id = 6iqh-u3hk
* Name = Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor
* Attribution = San Francisco Ethics Commission
* [Attribution Link](http://nf4.netfile.com/pub2?aid=sfo)
* Category = City Management and Ethics
* Tags = [ethics, campaign, finance, payments, agent, independent, contractor, fppc, form, 460]
* Created = 2012-04-30T16:17:42Z
* Publication Date = 2014-08-21T09:13:40Z
* Rows Updated = 2017-02-13T17:04:15Z

## Description

This dataset includes all itemized payments made by an agent or independent contractor ($500 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "G" Payments Made by an Agent or Independent Contractor from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Name                | Field Name          | Data Type     | Render Type   | Schema Type    | Included | 
| =================== | =================== | ============= | ============= | ============== | ======== | 
| Filer_ID            | filer_id            | text          | text          | series tag     | Yes      | 
| Filer_NamL          | filer_naml          | text          | text          | series tag     | Yes      | 
| Report_Num          | report_num          | number        | number        | numeric metric | Yes      | 
| Committee_Type      | committee_type      | text          | text          | series tag     | Yes      | 
| Rpt_Date            | rpt_date            | calendar_date | calendar_date | time           | Yes      | 
| From_Date           | from_date           | calendar_date | calendar_date |                | No       | 
| Thru_Date           | thru_date           | calendar_date | calendar_date |                | No       | 
| Elect_Date          | elect_date          | calendar_date | calendar_date |                | No       | 
| tblCover_Office_Cd  | tblcover_office_cd  | text          | text          | series tag     | Yes      | 
| tblCover_Offic_Dscr | tblcover_offic_dscr | text          | text          | series tag     | Yes      | 
| Rec_Type            | rec_type            | text          | text          | series tag     | Yes      | 
| Form_Type           | form_type           | number        | text          | numeric metric | Yes      | 
| Tran_ID             | tran_id             | text          | text          | series tag     | Yes      | 
| Entity_Cd           | entity_cd           | text          | text          | series tag     | Yes      | 
| Payee_NamL          | payee_naml          | text          | text          | series tag     | Yes      | 
| Payee_NamF          | payee_namf          | text          | text          | series tag     | Yes      | 
| Payee_NamT          | payee_namt          | text          | text          | series tag     | Yes      | 
| Payee_NamS          | payee_nams          | text          | text          | series tag     | Yes      | 
| Payee_Adr1          | payee_adr1          | text          | text          | series tag     | Yes      | 
| Payee_Adr2          | payee_adr2          | text          | text          | series tag     | Yes      | 
| Payee_City          | payee_city          | text          | text          | series tag     | Yes      | 
| Payee_State         | payee_state         | text          | text          | series tag     | Yes      | 
| Payee_Zip4          | payee_zip4          | text          | text          | series tag     | Yes      | 
| Expn_Date           | expn_date           | calendar_date | calendar_date |                | No       | 
| Amount              | amount              | money         | money         | numeric metric | Yes      | 
| Cum_YTD             | cum_ytd             | money         | money         | numeric metric | Yes      | 
| Expn_ChkNo          | expn_chkno          | text          | text          | series tag     | Yes      | 
| Expn_Code           | expn_code           | text          | text          | series tag     | Yes      | 
| Expn_Dscr           | expn_dscr           | text          | text          | series tag     | Yes      | 
| Agent_NamL          | agent_naml          | text          | text          | series tag     | Yes      | 
| Agent_NamF          | agent_namf          | text          | text          | series tag     | Yes      | 
| Agent_NamT          | agent_namt          | text          | text          | series tag     | Yes      | 
| Agent_NamS          | agent_nams          | text          | text          | series tag     | Yes      | 
| Cmte_ID             | cmte_id             | text          | text          | series tag     | Yes      | 
| Tres_NamL           | tres_naml           | text          | text          | series tag     | Yes      | 
| Tres_NamF           | tres_namf           | text          | text          | series tag     | Yes      | 
| Tres_NamT           | tres_namt           | text          | text          | series tag     | Yes      | 
| Tres_NamS           | tres_nams           | text          | text          | series tag     | Yes      | 
| Tres_Adr1           | tres_adr1           | text          | text          | series tag     | Yes      | 
| Tres_Adr2           | tres_adr2           | text          | text          | series tag     | Yes      | 
| Tres_City           | tres_city           | text          | text          | series tag     | Yes      | 
| Tres_ST             | tres_st             | text          | text          | series tag     | Yes      | 
| Tres_ZIP4           | tres_zip4           | text          | text          | series tag     | Yes      | 
| Cand_NamL           | cand_naml           | text          | text          | series tag     | Yes      | 
| Cand_NamF           | cand_namf           | text          | text          | series tag     | Yes      | 
| Cand_NamT           | cand_namt           | text          | text          | series tag     | Yes      | 
| Cand_NamS           | cand_nams           | text          | text          | series tag     | Yes      | 
| Office_Cd           | office_cd           | text          | text          | series tag     | Yes      | 
| Offic_Dscr          | offic_dscr          | text          | text          | series tag     | Yes      | 
| Juris_Cd            | juris_cd            | text          | text          | series tag     | Yes      | 
| Juris_Dscr          | juris_dscr          | text          | text          | series tag     | Yes      | 
| Dist_No             | dist_no             | text          | text          | series tag     | Yes      | 
| Off_S_H_Cd          | off_s_h_cd          | text          | text          | series tag     | Yes      | 
| Bal_Name            | bal_name            | text          | text          | series tag     | Yes      | 
| Bal_Num             | bal_num             | text          | text          | series tag     | Yes      | 
| Bal_Juris           | bal_juris           | text          | text          | series tag     | Yes      | 
| Sup_Opp_Cd          | sup_opp_cd          | number        | text          | numeric metric | Yes      | 
| Memo_Code           | memo_code           | text          | text          | series tag     | Yes      | 
| Memo_RefNo          | memo_refno          | text          | text          | series tag     | Yes      | 
| BakRef_TID          | bakref_tid          | text          | text          | series tag     | Yes      | 
| G_From_E_F          | g_from_e_f          | number        | text          | numeric metric | Yes      | 
| XRef_SchNm          | xref_schnm          | text          | text          | series tag     | Yes      | 
| XRef_Match          | xref_match          | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = rpt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = elect_date,thru_date,expn_date,from_date
Annotation Fields = 
```

## Data Commands

```ls
series e:6iqh-u3hk d:2016-09-30T00:00:00.000Z t:cand_naml=Philhour t:payee_state=CA t:payee_zip4=94612 t:cand_namf=Marjan t:entity_cd=OTH t:dist_no=1 t:office_cd=CSU t:filer_naml="Vote Marjan Philhour for Supervisor 2016" t:juris_dscr="San Francisco, CA" t:expn_code=CMP t:juris_cd=OTH t:agent_naml="Spotlight Printing" t:form_type=G t:rec_type=EXPN t:g_from_e_f=E t:filer_id=1374373 t:committee_type=CTL t:payee_naml="State Board of Equalization" t:payee_city=Oakland t:expn_dscr="Sales Tax" t:tran_id=EDT48 m:amount=48.13 m:report_num=1 m:cum_ytd=1391.38

series e:6iqh-u3hk d:2016-12-19T00:00:00.000Z t:payee_state=CA t:payee_zip4=94080 t:entity_cd=OTH t:filer_naml="NO ON V, ENOUGH IS ENOUGH: DON'T TAX OUR GROCERIES, WITH MAJOR FUNDING BY AMERICAN BEVERAGE ASSOCIATION CALIFORNIA PAC" t:bal_juris="CITY AND COUNTY OF SAN FRANCISCO" t:expn_code=PRT t:agent_naml="STOREFRONT POLITICAL MEDIA" t:form_type=G t:bal_name="TAX ON DISTRIBUTING SUGAR-SWEETENED BEVERAGES - PROPOSITION V" t:rec_type=EXPN t:g_from_e_f=E t:filer_id=1382995 t:committee_type=BMC t:payee_naml="SING TAO DAILY" t:sup_opp_cd=O t:payee_city="San Francisco" t:tran_id=EDT28 m:amount=36691.2 m:report_num=2 m:cum_ytd=36691.2

series e:6iqh-u3hk d:2016-09-06T00:00:00.000Z t:cand_naml="Lee Fewer" t:payee_state=UT t:payee_zip4=84401 t:cand_namf=Sandra t:entity_cd=OTH t:dist_no=1 t:office_cd=CSU t:filer_naml="Sandra Lee Fewer for Supervisor 2016" t:juris_dscr="San Francisco District 1" t:expn_code=SAL t:juris_cd=CTY t:agent_naml="River City Business Services" t:form_type=G t:rec_type=EXPN t:g_from_e_f=E t:filer_id=1382203 t:committee_type=CAO t:payee_naml="Internal Revenue Service" t:payee_city=Ogden t:tran_id=VSFW49QASM0 m:amount=736.97 m:report_num=1 m:cum_ytd=0
```

## Meta Commands

```ls
metric m:report_num p:integer l:Report_Num t:dataTypeName=number

entity e:6iqh-u3hk l:"Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/6iqh-u3hk

property e:6iqh-u3hk t:meta.view d:2017-03-07T23:58:35.829Z v:id=6iqh-u3hk v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule G - Payments Made by an Agent or Independent Contractor" v:attribution="San Francisco Ethics Commission"

property e:6iqh-u3hk t:meta.view.license d:2017-03-07T23:58:35.829Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:6iqh-u3hk t:meta.view.owner d:2017-03-07T23:58:35.829Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:6iqh-u3hk t:meta.view.tableauthor d:2017-03-07T23:58:35.829Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```