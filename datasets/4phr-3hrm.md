# Campaign Finance - FPPC Form 460 - Schedule B1 - Loans Received

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-b1-loans-received-acc2c) |
| Metadata | [Link](https://data.sfgov.org/api/views/4phr-3hrm) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4phr-3hrm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4phr-3hrm/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4phr-3hrm |
| Name | Campaign Finance - FPPC Form 460 - Schedule B1 - Loans Received |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, loans, received, fppc, form, 460 |
| Created | 2012-04-29T23:26:15Z |
| Publication Date | 2014-08-21T08:34:23Z |

## Description

This dataset includes all itemized loans received ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "B1" Loans Received from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | filer_id                 | Filer_ID                 | text          | text          |
| Yes      | series tag     | filer_naml               | Filer_NamL               | text          | text          |
| Yes      | series tag     | report_num               | Report_Num               | text          | number        |
| Yes      | series tag     | committee_type           | Committee_Type           | text          | text          |
| Yes      | time           | rpt_date                 | Rpt_Date                 | calendar_date | calendar_date |
| No       |                | from_date                | From_Date                | calendar_date | calendar_date |
| No       |                | thru_date                | Thru_Date                | calendar_date | calendar_date |
| No       |                | elect_date               | Elect_Date               | calendar_date | calendar_date |
| Yes      | series tag     | tblcover_office_cd       | tblCover_Office_Cd       | text          | text          |
| Yes      | series tag     | tblcover_offic_dscr      | tblCover_Offic_Dscr      | text          | text          |
| Yes      | series tag     | rec_type                 | Rec_Type                 | text          | text          |
| Yes      | series tag     | form_type                | Form_Type                | text          | text          |
| Yes      | series tag     | tran_id                  | Tran_ID                  | text          | text          |
| Yes      | series tag     | entity_cd                | Entity_Cd                | text          | text          |
| Yes      | series tag     | lndr_naml                | Lndr_NamL                | text          | text          |
| Yes      | series tag     | lndr_namf                | Lndr_NamF                | text          | text          |
| Yes      | series tag     | lndr_namt                | Lndr_NamT                | text          | text          |
| Yes      | series tag     | lndr_nams                | Lndr_NamS                | text          | text          |
| Yes      | series tag     | loan_adr1                | Loan_Adr1                | text          | text          |
| Yes      | series tag     | loan_adr2                | Loan_Adr2                | text          | text          |
| Yes      | series tag     | loan_city                | Loan_City                | text          | text          |
| Yes      | series tag     | loan_st                  | Loan_ST                  | text          | text          |
| Yes      | series tag     | loan_zip4                | Loan_Zip4                | text          | text          |
| No       |                | loan_date1               | Loan_Date1               | calendar_date | calendar_date |
| No       |                | loan_date2               | Loan_Date2               | calendar_date | calendar_date |
| Yes      | numeric metric | loan_amt1                | Loan_Amt1                | money         | money         |
| Yes      | numeric metric | loan_amt2                | Loan_Amt2                | money         | money         |
| Yes      | numeric metric | loan_amt3                | Loan_Amt3                | money         | money         |
| Yes      | numeric metric | loan_amt4                | Loan_Amt4                | money         | money         |
| Yes      | series tag     | loan_rate                | Loan_Rate                | text          | text          |
| Yes      | series tag     | loan_emp                 | Loan_EMP                 | text          | text          |
| Yes      | series tag     | loan_occ                 | Loan_OCC                 | text          | text          |
| Yes      | series tag     | loan_self                | Loan_Self                | text          | text          |
| Yes      | series tag     | cmte_id                  | Cmte_ID                  | text          | text          |
| Yes      | series tag     | tres_naml                | Tres_NamL                | text          | text          |
| Yes      | series tag     | tres_namf                | Tres_NamF                | text          | text          |
| Yes      | series tag     | tres_namt                | Tres_NamT                | text          | text          |
| Yes      | series tag     | tres_nams                | Tres_NamS                | text          | text          |
| Yes      | series tag     | tres_adr1                | Tres_Adr1                | text          | text          |
| Yes      | series tag     | tres_adr2                | Tres_Adr2                | text          | text          |
| Yes      | series tag     | tres_city                | Tres_City                | text          | text          |
| Yes      | series tag     | tres_st                  | Tres_ST                  | text          | text          |
| Yes      | series tag     | tres_zip4                | Tres_ZIP4                | text          | text          |
| Yes      | series tag     | b2lender_name_inter_name | B2Lender_Name_Inter_name | text          | text          |
| Yes      | series tag     | intr_namf                | Intr_NamF                | text          | text          |
| Yes      | series tag     | intr_namt                | Intr_NamT                | text          | text          |
| Yes      | series tag     | intr_nams                | Intr_NamS                | text          | text          |
| Yes      | series tag     | intr_adr1                | Intr_Adr1                | text          | text          |
| Yes      | series tag     | intr_adr2                | Intr_Adr2                | text          | text          |
| Yes      | series tag     | intr_city                | Intr_City                | text          | text          |
| Yes      | series tag     | intr_st                  | Intr_ST                  | text          | text          |
| Yes      | series tag     | intr_zip4                | Intr_ZIP4                | text          | text          |
| Yes      | series tag     | memo_code                | Memo_Code                | text          | text          |
| Yes      | series tag     | memo_refno               | Memo_RefNo               | text          | text          |
| Yes      | series tag     | bakref_tid               | BakRef_TID               | text          | text          |
| Yes      | series tag     | xref_schnm               | XRef_SchNm               | text          | text          |
| Yes      | series tag     | xref_match               | XRef_Match               | text          | text          |
| Yes      | numeric metric | loan_amt5                | Loan_Amt5                | money         | money         |
| Yes      | numeric metric | loan_amt6                | Loan_Amt6                | money         | money         |
| Yes      | numeric metric | loan_amt7                | Loan_Amt7                | money         | money         |
| Yes      | numeric metric | loan_amt8                | Loan_Amt8                | money         | money         |
```

## Time Field

```ls
Value = rpt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = from_date,thru_date,elect_date,loan_date1,loan_date2
```

## Data Commands

```ls
series e:4phr-3hrm d:2003-07-08T00:00:00.000Z t:loan_self=n t:entity_cd=OTH t:loan_rate=f t:filer_naml="LGBT Community for Newsom" t:lndr_naml="Barnes, Mosher, Whitehurst, Lauter & Partners, Inc." t:report_num=0 t:form_type=B1 t:loan_st=CA t:rec_type=LOAN t:filer_id=1254056 t:committee_type=RCP t:loan_zip4=94102 t:tran_id=PAY5 t:loan_city="San Francisco" m:loan_amt2=50 m:loan_amt1=50 m:loan_amt4=0 m:loan_amt3=150 m:loan_amt6=0 m:loan_amt5=0 m:loan_amt8=50 m:loan_amt7=0

series e:4phr-3hrm d:2010-10-05T00:00:00.000Z t:loan_self=n t:lndr_namt=Ms. t:entity_cd=IND t:loan_rate="0.00 %" t:loan_emp="SF Board of Education" t:filer_naml="Coalition to Elect Kim-Shree Maufas 4 School Board" t:lndr_naml=Maufas t:report_num=0 t:form_type=B1 t:loan_st=CA t:rec_type=LOAN t:lndr_namf=Kim-Shree t:loan_occ=Commissioner t:filer_id=1284567 t:committee_type=CTL t:loan_zip4=94110 t:tran_id=6513666 t:loan_city="San Francisco" m:loan_amt2=20 m:loan_amt1=0 m:loan_amt4=20 m:loan_amt3=747 m:loan_amt6=0 m:loan_amt5=0 m:loan_amt8=20

series e:4phr-3hrm d:2009-05-22T00:00:00.000Z t:loan_self=n t:entity_cd=OTH t:loan_rate=0.00% t:filer_naml="COMMITTEE TO REBUILD GENERAL HOSPITAL, YES ON PROP. A, A COALITION OF DOCTORS, NURSES, HEALTHCARE PROFESSIONALS, SEIU LOCAL 1021 AND THE SAN FRANCISCO GENERAL HOSPITAL FOUNDATION" t:lndr_naml="BARNES, MOSHER, WHITEHURST, LAUTER, & PARTNERS, INC. & ITS AFFILIATED ENTITIES" t:report_num=3 t:form_type=B1 t:loan_st=CA t:memo_code=PAY926 t:rec_type=LOAN t:filer_id=1306196 t:committee_type=BMC t:loan_zip4=94105 t:tran_id=PAY926 t:loan_city="SAN FRANCISCO" m:loan_amt2=2500 m:loan_amt1=2500 m:loan_amt4=0 m:loan_amt3=2500 m:loan_amt6=0 m:loan_amt5=0 m:loan_amt8=2500 m:loan_amt7=0
```

## Meta Commands

```ls
metric m:loan_amt1 p:integer l:Loan_Amt1 t:dataTypeName=money

metric m:loan_amt2 p:integer l:Loan_Amt2 t:dataTypeName=money

metric m:loan_amt3 p:double l:Loan_Amt3 t:dataTypeName=money

metric m:loan_amt4 p:integer l:Loan_Amt4 t:dataTypeName=money

metric m:loan_amt5 p:double l:Loan_Amt5 t:dataTypeName=money

metric m:loan_amt6 p:integer l:Loan_Amt6 t:dataTypeName=money

metric m:loan_amt7 p:double l:Loan_Amt7 t:dataTypeName=money

metric m:loan_amt8 p:integer l:Loan_Amt8 t:dataTypeName=money

entity e:4phr-3hrm l:"Campaign Finance - FPPC Form 460 - Schedule B1 - Loans Received" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/4phr-3hrm

property e:4phr-3hrm t:meta.view v:id=4phr-3hrm v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule B1 - Loans Received" v:attribution="San Francisco Ethics Commission"

property e:4phr-3hrm t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4phr-3hrm t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:4phr-3hrm t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                                                                                                                         | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | lndr_naml                                                                      | lndr_namf | lndr_namt | lndr_nams | loan_adr1 | loan_adr2 | loan_city     | loan_st | loan_zip4 | loan_date1          | loan_date2          | loan_amt1 | loan_amt2 | loan_amt3 | loan_amt4 | loan_rate | loan_emp                     | loan_occ                | loan_self | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city     | tres_st | tres_zip4 | b2lender_name_inter_name | intr_namf | intr_namt | intr_nams | intr_adr1 | intr_adr2 | intr_city     | intr_st | intr_zip4 | memo_code | memo_refno | bakref_tid | xref_schnm | xref_match | loan_amt5 | loan_amt6 | loan_amt7 | loan_amt8 | 
| ======== | ================================================================================================================================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | ============================================================================== | ========= | ========= | ========= | ========= | ========= | ============= | ======= | ========= | =================== | =================== | ========= | ========= | ========= | ========= | ========= | ============================ | ======================= | ========= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ============= | ======= | ========= | ======================== | ========= | ========= | ========= | ========= | ========= | ============= | ======= | ========= | ========= | ========== | ========== | ========== | ========== | ========= | ========= | ========= | ========= | 
| 1254056  | LGBT Community for Newsom                                                                                                                                                          | 0          | RCP            | 2003-07-08T00:00:00 | 2003-01-01T00:00:00 | 2003-06-30T00:00:00 |                     |                    |                     | LOAN     | B1        | PAY5         | OTH       | Barnes, Mosher, Whitehurst, Lauter & Partners, Inc.                            |           |           |           |           |           | San Francisco | CA      | 94102     | 2003-04-07T00:00:00 |                     | 50        | 50        | 150       | 0         | f         |                              |                         | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           |           |            |            |            |            | 0         | 0         | 0         | 50        | 
| 1284567  | Coalition to Elect Kim-Shree Maufas 4 School Board                                                                                                                                 | 0          | CTL            | 2010-10-05T00:00:00 | 2010-07-01T00:00:00 | 2010-09-30T00:00:00 | 2006-11-07T00:00:00 |                    |                     | LOAN     | B1        | 6513666      | IND       | Maufas                                                                         | Kim-Shree | Ms.       |           |           |           | San Francisco | CA      | 94110     | 2008-12-16T00:00:00 |                     | 0         | 20        | 747       | 20        | 0.00 %    | SF Board of Education        | Commissioner            | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           |           |            |            |            |            | 0         | 0         |           | 20        | 
| 1306196  | COMMITTEE TO REBUILD GENERAL HOSPITAL, YES ON PROP. A, A COALITION OF DOCTORS, NURSES, HEALTHCARE PROFESSIONALS, SEIU LOCAL 1021 AND THE SAN FRANCISCO GENERAL HOSPITAL FOUNDATION | 3          | BMC            | 2009-05-22T00:00:00 | 2008-10-19T00:00:00 | 2008-12-31T00:00:00 |                     |                    |                     | LOAN     | B1        | PAY926       | OTH       | BARNES, MOSHER, WHITEHURST, LAUTER, & PARTNERS, INC. & ITS AFFILIATED ENTITIES |           |           |           |           |           | SAN FRANCISCO | CA      | 94105     | 2008-12-23T00:00:00 | 2009-12-31T00:00:00 | 2500      | 2500      | 2500      | 0         | 0.00%     |                              |                         | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           | PAY926    |            |            |            |            | 0         | 0         | 0         | 2500      | 
| 1326084  | Students First                                                                                                                                                                     | 0          | BMC            | 2010-10-20T00:00:00 | 2010-10-01T00:00:00 | 2010-10-15T00:00:00 | 2011-11-08T00:00:00 |                    |                     | LOAN     | B1        | PAY30        | IND       | Atkins                                                                         | Howard    |           |           |           |           | San Francisco | CA      | 94104     | 2010-06-30T00:00:00 |                     | 0         | 5000      | 5000      | 5000      |           | Wells Fargo Bank             | Chief Financial Officer | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           |           |            |            |            |            | 0         | 0         | 0         | 5000      | 
| 1278393  | Phil Ting for Assessor                                                                                                                                                             | 0          | CTL            | 2008-07-30T00:00:00 | 2008-01-01T00:00:00 | 2008-06-30T00:00:00 | 2005-11-08T00:00:00 |                    |                     | LOAN     | B1        | B1-1         | IND       | Ting                                                                           | Philip Y. |           |           |           |           | San Francisco | CA      | 94133     | 2006-01-13T00:00:00 | 2007-07-27T00:00:00 | 0         | 600       | 0         | 600       | 0.000     | City & Cty. of San Francisco | Assessor                | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           |           |            |            |            |            | 0         | 0         | 0         | 600       | 
| 1284567  | Coalition to Elect Kim-Shree Maufas 4 School Board                                                                                                                                 | 0          | CTL            | 2013-08-02T00:00:00 | 2013-01-01T00:00:00 | 2013-06-30T00:00:00 | 2006-11-07T00:00:00 |                    |                     | LOAN     | B1        | 5YpuJUUbKs6s | IND       | Maufas                                                                         | Kim-Shree | Ms.       |           |           |           | San Francisco | CA      | 94110     | 2008-01-02T00:00:00 |                     | 0         | 500       | -46.5     | 500       | 0         | SF Board of Education        | Commissioner            | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           |           |            |            |            |            | 0         | 0         | 0         | 500       | 
| 991703   | Irish American Democratic Club/San Francisco                                                                                                                                       | 0          | RCP            | 2006-10-05T00:00:00 | 2006-07-01T00:00:00 | 2006-10-05T00:00:00 | 2006-11-07T00:00:00 |                    |                     | LOAN     | B1        | 5            | IND       | *                                                                              |           |           |           |           |           | San Francisco | CA      |           |                     |                     | 0         | 0         | 0         | 0         | f         |                              |                         | n         |         |           |           |           |           |           |           | San Francisco | CA      |           |                          |           |           |           |           |           | San Francisco | CA      |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1303565  | Rachel Norton for Board of Education                                                                                                                                               | 1          | CTL            | 2009-06-12T00:00:00 | 2008-10-19T00:00:00 | 2008-12-31T00:00:00 | 2008-11-04T00:00:00 |                    |                     | LOAN     | B1        | 5468290      | IND       | Norton                                                                         | Rachel    |           |           |           |           |               |         |           | 2008-10-15T00:00:00 |                     | 0         | 5000      | 5505      | 5000      |           |                              |                         | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           |           |            |            |            |            | 0         | 0         |           | 5000      | 
| 1284567  | Coalition to Elect Kim-Shree Maufas 4 School Board                                                                                                                                 | 1          | CTL            | 2014-02-11T00:00:00 | 2013-07-01T00:00:00 | 2013-12-31T00:00:00 | 2006-11-07T00:00:00 |                    |                     | LOAN     | B1        | CBeelQh6iaGN | IND       | Maufas                                                                         | Kim-Shree | Ms.       |           |           |           | San Francisco | CA      | 94110     | 2011-07-01T00:00:00 | 2014-12-31T00:00:00 | 0         | 130       | -54.5     | 130       | 0         | SF Board of Education        | Commissioner            | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           |           |            |            |            |            | 0         | 0         | 0         | 130       | 
| 1341381  | Engardio For District 7 Supervisor 2012                                                                                                                                            | 1          | CTL            | 2012-11-05T00:00:00 | 2012-07-01T00:00:00 | 2012-09-30T00:00:00 | 2012-11-06T00:00:00 |                    |                     | LOAN     | B1        | 12764602     | IND       | Engardio                                                                       | Joel      |           |           |           |           | San Francisco | CA      | 94122     | 2011-09-06T00:00:00 |                     | 0         | 1000      | 0         | 1000      | 0.00 %    | self                         | candidate               | n         |         |           |           |           |           |           |           |               |         |           |                          |           |           |           |           |           |               |         |           |           |            |            |            |            | 0         | 0         |           | 1000      | 
```