# Campaign Finance - FPPC Form 460 - Schedule H - Loans Made to Others

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-h-loans-made-to-others-db6b5) |
| Metadata | [Link](https://data.sfgov.org/api/views/62ex-d3qk) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/62ex-d3qk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/62ex-d3qk/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 62ex-d3qk |
| Name | Campaign Finance - FPPC Form 460 - Schedule H - Loans Made to Others |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, loans, others, fppc, form, 460 |
| Created | 2012-04-30T16:26:51Z |
| Publication Date | 2014-08-21T08:32:30Z |

## Description

This dataset includes all itemized loans made to others ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "H" Loans Made to Others from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

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
series e:62ex-d3qk d:2016-05-26T00:00:00.000Z t:loan_self=n t:entity_cd=COM t:loan_rate=5% t:filer_naml="UNITE HERE LOCAL 2 PAC" t:lndr_naml="ShareBetter SF, Yes on F" t:report_num=0 t:form_type=H t:loan_st=CA t:cmte_id=1367243 t:rec_type=LOAN t:filer_id=1243324 t:committee_type=RCP t:loan_zip4=94118 t:tran_id=x29XtNP74GvO t:loan_city="San Francisco" m:loan_amt2=0 m:loan_amt1=0 m:loan_amt4=90000 m:loan_amt3=0 m:loan_amt6=0 m:loan_amt5=90000 m:loan_amt8=90000 m:loan_amt7=1351.24

series e:62ex-d3qk d:2016-05-24T00:00:00.000Z t:report_num=0 t:loan_self=n t:form_type=H t:loan_st=CA t:rec_type=LOAN t:cmte_id=1260178 t:memo_code=RCV3456 t:filer_id=1245538 t:committee_type=RCP t:entity_cd=OTH t:loan_zip4=94126 t:filer_naml="SF Moderates" t:tran_id=RCV3456 t:lndr_naml="SF Moderates Voter Guide" t:loan_city="San Francisco" m:loan_amt2=5000 m:loan_amt1=0 m:loan_amt4=5000 m:loan_amt3=0 m:loan_amt6=0 m:loan_amt5=0 m:loan_amt8=5000 m:loan_amt7=0

series e:62ex-d3qk d:2016-07-26T00:00:00.000Z t:report_num=0 t:loan_self=n t:form_type=H t:loan_st=CA t:rec_type=LOAN t:cmte_id=1260178 t:memo_code=RCV3456 t:filer_id=1245538 t:committee_type=RCP t:entity_cd=OTH t:loan_zip4=94126 t:filer_naml="SF Moderates" t:tran_id=RCV3456 t:lndr_naml="SF Moderates Voter Guide" t:loan_city="San Francisco" m:loan_amt2=5000 m:loan_amt1=0 m:loan_amt4=5000 m:loan_amt3=0 m:loan_amt6=0 m:loan_amt5=0 m:loan_amt8=5000 m:loan_amt7=0
```

## Meta Commands

```ls
metric m:loan_amt1 p:double l:Loan_Amt1 t:dataTypeName=money

metric m:loan_amt2 p:double l:Loan_Amt2 t:dataTypeName=money

metric m:loan_amt3 p:double l:Loan_Amt3 t:dataTypeName=money

metric m:loan_amt4 p:double l:Loan_Amt4 t:dataTypeName=money

metric m:loan_amt5 p:double l:Loan_Amt5 t:dataTypeName=money

metric m:loan_amt6 p:double l:Loan_Amt6 t:dataTypeName=money

metric m:loan_amt7 p:double l:Loan_Amt7 t:dataTypeName=money

metric m:loan_amt8 p:double l:Loan_Amt8 t:dataTypeName=money

entity e:62ex-d3qk l:"Campaign Finance - FPPC Form 460 - Schedule H - Loans Made to Others" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/62ex-d3qk

property e:62ex-d3qk t:meta.view v:id=62ex-d3qk v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule H - Loans Made to Others" v:attribution="San Francisco Ethics Commission"

property e:62ex-d3qk t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:62ex-d3qk t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:62ex-d3qk t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                  | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id      | entity_cd | lndr_naml                                                                | lndr_namf | lndr_namt | lndr_nams | loan_adr1 | loan_adr2 | loan_city     | loan_st | loan_zip4 | loan_date1          | loan_date2          | loan_amt1 | loan_amt2 | loan_amt3 | loan_amt4 | loan_rate | loan_emp | loan_occ | loan_self | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_st | tres_zip4 | b2lender_name_inter_name | intr_namf | intr_namt | intr_nams | intr_adr1 | intr_adr2 | intr_city | intr_st | intr_zip4 | memo_code | memo_refno | bakref_tid | xref_schnm | xref_match | loan_amt5 | loan_amt6 | loan_amt7 | loan_amt8 | 
| ======== | =========================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ============ | ========= | ======================================================================== | ========= | ========= | ========= | ========= | ========= | ============= | ======= | ========= | =================== | =================== | ========= | ========= | ========= | ========= | ========= | ======== | ======== | ========= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | ======================== | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | ========= | ========== | ========== | ========== | ========== | ========= | ========= | ========= | ========= | 
| 1243324  | UNITE HERE LOCAL 2 PAC                                                      | 0          | RCP            | 2016-05-26T00:00:00 | 2016-04-24T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | LOAN     | H         | x29XtNP74GvO | COM       | ShareBetter SF, Yes on F                                                 |           |           |           |           |           | San Francisco | CA      | 94118     | 2015-10-22T00:00:00 | 2016-02-14T00:00:00 | 0         | 0         | 0         | 90000     | 5%        |          |          | n         | 1367243 |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 90000     | 0         | 1351.24   | 90000     | 
| 1245538  | SF Moderates                                                                | 0          | RCP            | 2016-05-24T00:00:00 | 2016-01-01T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | LOAN     | H         | RCV3456      | OTH       | SF Moderates Voter Guide                                                 |           |           |           |           |           | San Francisco | CA      | 94126     | 2015-10-15T00:00:00 |                     | 0         | 5000      | 0         | 5000      |           |          |          | n         | 1260178 |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           | RCV3456   |            |            |            |            | 0         | 0         | 0         | 5000      | 
| 1245538  | SF Moderates                                                                | 0          | RCP            | 2016-07-26T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | LOAN     | H         | RCV3456      | OTH       | SF Moderates Voter Guide                                                 |           |           |           |           |           | San Francisco | CA      | 94126     | 2015-10-15T00:00:00 |                     | 0         | 5000      | 0         | 5000      |           |          |          | n         | 1260178 |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           | RCV3456   |            |            |            |            | 0         | 0         | 0         | 5000      | 
| 1245538  | SF Moderates                                                                | 0          | RCP            | 2016-09-23T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 | 2016-11-08T00:00:00 |                    |                     | LOAN     | H         | RCV3456      | OTH       | SF Moderates Voter Guide                                                 |           |           |           |           |           | San Francisco | CA      | 94126     | 2015-10-15T00:00:00 |                     | 0         | 5000      | 0         | 5000      |           |          |          | n         | 1260178 |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           | RCV3456   |            |            |            |            | 0         | 0         | 0         | 5000      | 
| 1243324  | UNITE HERE LOCAL 2 PAC                                                      | 0          | RCP            | 2016-04-28T00:00:00 | 2016-01-01T00:00:00 | 2016-04-23T00:00:00 | 2016-06-07T00:00:00 |                    |                     | LOAN     | H         | x29XtNP74GvO | COM       | ShareBetter SF, Yes on F                                                 |           |           |           |           |           | San Francisco | CA      | 94118     | 2015-10-22T00:00:00 | 2016-02-14T00:00:00 | 0         | 90000     | 0         | 90000     | 5%        |          |          | n         | 1367243 |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 90000     | 
| 891575   | San Francisco Chamber of Commerce 21st Century PAC                          | 1          | RCP            | 2006-01-16T00:00:00 | 2005-09-25T00:00:00 | 2005-10-22T00:00:00 | 2005-11-08T00:00:00 |                    |                     | LOAN     | H         | RCV220       | COM       | Save Hetch Hetchy - Yes on A                                             |           |           |           |           |           | San Francisco | CA      | 94104-    | 2003-04-24T00:00:00 | 2004-04-23T00:00:00 | 0         | 14000     | 100       | 14000     | f         |          |          | n         | 1246283 |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           | RCV220    |            |            |            |            | 0         | 0         | 0         | 14000     | 
| 891575   | San Francisco Chamber of Commerce 21st Century PAC                          | 1          | RCP            | 2006-01-16T00:00:00 | 2005-09-25T00:00:00 | 2005-10-22T00:00:00 | 2005-11-08T00:00:00 |                    |                     | LOAN     | H         | RCV210       | COM       | Save Hetch Hetchy - Yes on A                                             |           |           |           |           |           | San Francisco | CA      | 94104-    | 2002-08-26T00:00:00 | 2003-09-11T00:00:00 | 0         | 8500      | 100       | 8500      | f         |          |          | n         | 1246283 |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           | RCV210    |            |            |            |            | 0         | 0         | 0         | 10500     | 
| 891575   | SF FORWARD SPONSORED BY SAN FRANCISCO CHAMBER OF COMMERCE                   | 2          | RCP            | 2009-11-19T00:00:00 | 2005-07-01T00:00:00 | 2005-09-24T00:00:00 | 2005-11-08T00:00:00 |                    |                     | LOAN     | H         | RCV246       | COM       | Save Hetch Hetchy - Yes on A                                             |           |           |           |           |           | San Francisco | CA      | 94104-    | 2004-03-16T00:00:00 | 2005-03-16T00:00:00 | 0         | 100       | 100       | 100       | 0.00%     |          |          | n         | 1246283 |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           | RCV246    |            |            |            |            | 0         | 0         | 0         | 100       | 
| 970630   | SAN FRANCISCO LABOR & NEIGHBOR MEMBER EDUCATION./POLITICAL ISSUES COMMITTEE | 0          | RCP            | 2012-03-22T00:00:00 | 2012-01-01T00:00:00 | 2012-03-17T00:00:00 |                     |                    |                     | LOAN     | H         | H-3380       | COM       | San Francisco Labor Council Labor & Neighbor Independent Expenditure PAC |           |           |           |           |           | San Francisco | CA      | 94109     | 2009-12-31T00:00:00 |                     | 0         | 4000      | 0         | 4000      | 0.000     |          |          | n         | 991525  |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 4000      | 
| 992298   | Residential Builders Assn. of S.F. Independent Expenditure Fund             | 0          | RCP            | 2004-02-19T00:00:00 | 2004-01-18T00:00:00 | 2004-02-14T00:00:00 |                     |                    |                     | LOAN     | H         | H1           | OTH       | Residential Builders Association of San Francisco                        |           |           |           |           |           | San Francisco | CA      | 94117     | 2001-01-10T00:00:00 | 2004-01-10T00:00:00 | 0         | 50000     | 0         | 50000     | f         |          |          | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 50000     | 
```