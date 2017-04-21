# Campaign Finance - FPPC Form 460 - Schedule F - Accrued Expenses (Unpaid Bills)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-f-accrued-expenses-unpaid-bills-e98b7) |
| Metadata | [Link](https://data.sfgov.org/api/views/tr8k-7cit) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tr8k-7cit/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tr8k-7cit/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tr8k-7cit |
| Name | Campaign Finance - FPPC Form 460 - Schedule F - Accrued Expenses (Unpaid Bills) |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, accrued, expenses, unpaid, bills, fppc, form, 460 |
| Created | 2012-04-30T16:00:03Z |
| Publication Date | 2014-08-21T09:10:50Z |

## Description

This dataset includes all itemized accrued expenses ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "F" Accrued Expenses (Unpaid Bills) from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

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
| Yes      | numeric metric | beg_bal             | Beg_Bal             | money         | money         |
| Yes      | numeric metric | amt_incur           | Amt_Incur           | money         | money         |
| Yes      | numeric metric | amt_paid            | Amt_Paid            | money         | money         |
| Yes      | numeric metric | end_bal             | End_Bal             | money         | money         |
| Yes      | series tag     | expn_code           | Expn_Code           | text          | text          |
| Yes      | series tag     | expn_dscr           | Expn_Dscr           | text          | text          |
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
| Yes      | series tag     | memo_code           | Memo_Code           | text          | text          |
| Yes      | series tag     | memo_refno          | Memo_RefNo          | text          | text          |
| Yes      | series tag     | bakref_tid          | BakRef_TID          | text          | text          |
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
Excluded Fields = rpt_date,thru_date,elect_date
```

## Data Commands

```ls
series e:tr8k-7cit d:2016-04-01T00:00:00.000Z t:payee_state=CA t:payee_zip4=94108 t:entity_cd=OTH t:filer_naml="SAN FRANCISCANS UNITED TO REDUCE DIABETES IN CHILDREN BY IMPOSING A 1 CENT PER OUNCE TAX ON THE DISTRIBUTION OF SUGARY DRINKS" t:report_num=0 t:expn_code=PRO t:form_type=F t:rec_type=DEBT t:filer_id=1377697 t:committee_type=BMC t:payee_naml="SUTTON LAW FIRM" t:tran_id=PAY189 t:payee_city="SAN FRANCISCO" t:expn_dscr="JAMES SUTTON, COMMITTEE TREASURER, IS OWNER OF PAYEE; NICHOLAS SANDERS, COMMITTEE ASSISTANT TREASURER, IS EMPLOYEE OF PAYEE." m:end_bal=3980.19 m:beg_bal=3980.19 m:amt_paid=0 m:amt_incur=0

series e:tr8k-7cit d:2016-01-01T00:00:00.000Z t:payee_state=CA t:payee_zip4=94110 t:entity_cd=COM t:filer_naml="Jane Kim for SF Democratic County Central Committee 2016" t:report_num=1 t:expn_code=LIT t:form_type=F t:rec_type=DEBT t:cmte_id=1384434 t:filer_id=1385346 t:committee_type=CTL t:payee_naml="Sophie Maxwell for SF DCCC 2016" t:tran_id=PAY12 t:payee_city="San Francisco" t:expn_dscr="Slate Mailer" m:end_bal=750 m:beg_bal=0 m:amt_paid=0 m:amt_incur=750

series e:tr8k-7cit d:2016-07-01T00:00:00.000Z t:payee_state=CA t:payee_zip4=95814 t:entity_cd=OTH t:filer_naml="Coalition for a Safer California" t:report_num=0 t:expn_code=PRO t:form_type=F t:rec_type=DEBT t:filer_id=1306339 t:committee_type=RCP t:payee_naml="Olson Hagel & Fishburn, LLP" t:tran_id=PAY598 t:payee_city=Sacramento m:end_bal=346.5 m:beg_bal=346.5 m:amt_paid=0 m:amt_incur=0
```

## Meta Commands

```ls
metric m:beg_bal p:double l:Beg_Bal t:dataTypeName=money

metric m:amt_incur p:double l:Amt_Incur t:dataTypeName=money

metric m:amt_paid p:double l:Amt_Paid t:dataTypeName=money

metric m:end_bal p:double l:End_Bal t:dataTypeName=money

entity e:tr8k-7cit l:"Campaign Finance - FPPC Form 460 - Schedule F - Accrued Expenses (Unpaid Bills)" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/tr8k-7cit

property e:tr8k-7cit t:meta.view v:id=tr8k-7cit v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule F - Accrued Expenses (Unpaid Bills)" v:attribution="San Francisco Ethics Commission"

property e:tr8k-7cit t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tr8k-7cit t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:tr8k-7cit t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                                                                      | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | payee_naml                                        | payee_namf | payee_namt | payee_nams | payee_adr1 | payee_adr2 | payee_city    | payee_state | payee_zip4 | beg_bal | amt_incur | amt_paid | end_bal | expn_code | expn_dscr                                                                                                                    | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_st | tres_zip4 | memo_code | memo_refno | bakref_tid | xref_schnm | xref_match | 
| ======== | =============================================================================================================================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | ================================================= | ========== | ========== | ========== | ========== | ========== | ============= | =========== | ========== | ======= | ========= | ======== | ======= | ========= | ============================================================================================================================ | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | ========= | ========== | ========== | ========== | ========== | 
| 1377697  | SAN FRANCISCANS UNITED TO REDUCE DIABETES IN CHILDREN BY IMPOSING A 1 CENT PER OUNCE TAX ON THE DISTRIBUTION OF SUGARY DRINKS                                                   | 0          | BMC            | 2016-04-20T00:00:00 | 2016-04-01T00:00:00 | 2016-04-15T00:00:00 |                     |                    |                     | DEBT     | F         | PAY189       | OTH       | SUTTON LAW FIRM                                   |            |            |            |            |            | SAN FRANCISCO | CA          | 94108      | 3980.19 | 0         | 0        | 3980.19 | PRO       | JAMES SUTTON, COMMITTEE TREASURER, IS OWNER OF PAYEE; NICHOLAS SANDERS, COMMITTEE ASSISTANT TREASURER, IS EMPLOYEE OF PAYEE. |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 1385346  | Jane Kim for SF Democratic County Central Committee 2016                                                                                                                        | 1          | CTL            | 2016-06-06T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | DEBT     | F         | PAY12        | COM       | Sophie Maxwell for SF DCCC 2016                   |            |            |            |            |            | San Francisco | CA          | 94110      | 0       | 750       | 0        | 750     | LIT       | Slate Mailer                                                                                                                 | 1384434 |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 1306339  | Coalition for a Safer California                                                                                                                                                | 0          | RCP            | 2016-12-05T00:00:00 | 2016-07-01T00:00:00 | 2016-11-28T00:00:00 |                     |                    |                     | DEBT     | F         | PAY598       | OTH       | Olson Hagel & Fishburn, LLP                       |            |            |            |            |            | Sacramento    | CA          | 95814      | 346.5   | 0         | 0        | 346.5   | PRO       |                                                                                                                              |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 1343052  | Committee to Elect Gladys Soto for San Francisco School Board - 2012                                                                                                            | 1          | CTL            | 2016-08-26T00:00:00 | 2016-07-01T00:00:00 | 2016-08-26T00:00:00 | 2012-11-06T00:00:00 |                    |                     | DEBT     | F         | dYt5S68hyHgg | OTH       | Durning, Santore & Davis, LLC                     |            |            |            |            |            | San Francisco | CA          | 94110-3779 | 494     | 0         | 0        | 494     | CNS       | Campaign organization,strategy,social media,website,campaign finance                                                         |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 1382995  | NO ON V, ENOUGH IS ENOUGH: DON'T TAX OUR GROCERIES, WITH MAJOR FUNDING BY AMERICAN BEVERAGE ASSOCIATION CALIFORNIA PAC                                                          | 2          | BMC            | 2016-10-27T00:00:00 | 2016-05-16T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | DEBT     | F         | PAY127       | OTH       | GODDARD GUNSTER                                   |            |            |            |            |            | Washington    | DC          | 20037      | 20000   | 0         | 20000    | 0       | CNS       |                                                                                                                              |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 982683   | Committee on Jobs Government Reform Fund                                                                                                                                        | 0          | RCP            | 2016-08-01T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | DEBT     | F         | hRDUCDwLB35E | OTH       | Pillsbury Winthrop Shaw Pittman LLP               |            |            |            |            |            | San Francisco | CA          | 94111-5998 | 284.37  | 0         | 0        | 284.37  | PRO       |                                                                                                                              |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 1386505  | YES ON P, COMPETITIVE BIDDING FOR CITY CONTRACTS, FUNDING BY NATIONAL ASSN. OF REALTORS, CALIFORNIA ASSN. OF REALTORS ISSUES MOBILIZATION PAC & SAN FRANCISCO ASSN. OF REALTORS | 1          | BMC            | 2016-11-07T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | DEBT     | F         | PAY84        | IND       | KU                                                | KAREN      |            |            |            |            | FREMONT       | CA          | 94555      | 0       | 780       | 0        | 780     | CNS       |                                                                                                                              |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 1382612  | Zoe Dunning for Democratic County Central Committee 2016                                                                                                                        | 0          | CAO            | 2016-07-28T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | DEBT     | F         | VSDYW9H7K19  | OTH       | 50+1 Strategies, LLC                              |            |            |            |            |            | San Francisco | CA          | 94104-1909 | 0       | 863.97    | 0        | 863.97  | CNS       | Consulting Fees                                                                                                              |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 1386505  | YES ON P, COMPETITIVE BIDDING FOR CITY CONTRACTS, FUNDING BY NATIONAL ASSN. OF REALTORS, CALIFORNIA ASSN. OF REALTORS ISSUES MOBILIZATION PAC & SAN FRANCISCO ASSN. OF REALTORS | 1          | BMC            | 2016-11-07T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | DEBT     | F         | PAY10        | OTH       | SUTTON LAW FIRM                                   |            |            |            |            |            | SAN FRANCISCO | CA          | 94108      | 3224.51 | 0         | 3224.51  | 0       | PRO       | JAMES SUTTON, TREASURER, IS OWNER OF PAYEE; MATTHEW ALVAREZ, ASSISTANT TREASURER, IS EMPLOYEE OF PAYEE.                      |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
| 1362060  | COMMITTEE FOR A BRIGHTER SAN FRANCISCO FUTURE                                                                                                                                   | 0          | RCP            | 2016-04-23T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 |                     |                    |                     | DEBT     | F         | PAY156       | OTH       | NIELSEN, MERKSAMER, PARRINELLO, GROSS & LEONI LLP |            |            |            |            |            | SACRAMENTO    | CA          | 95814      | 716.73  | 0         | 716.73   | 0       | PRO       |                                                                                                                              |         |           |           |           |           |           |           |           |         |           |           |            |            |            |            | 
```