# Campaign Finance - FPPC Form 460 - Schedule B2 - Loan Guarantors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-schedule-b2-loan-guarantors-21869) |
| Metadata | [Link](https://data.sfgov.org/api/views/ec3y-6ty9) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ec3y-6ty9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ec3y-6ty9/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ec3y-6ty9 |
| Name | Campaign Finance - FPPC Form 460 - Schedule B2 - Loan Guarantors |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, loan, guarantors, fppc, form, 460 |
| Created | 2012-04-30T03:20:04Z |
| Publication Date | 2014-08-21T08:31:15Z |

## Description

This dataset includes all itemized guarantors of loans ($100 or more) e-filed on Fair Political Practices Commission (FPPC) Form 460 Schedule "B2" Loan Guarantors from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

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
series e:ec3y-6ty9 d:2004-05-14T00:00:00.000Z t:loan_self=n t:lndr_namt=Mr. t:entity_cd=IND t:loan_rate=f t:filer_naml="Committee to Elect John Farrell Assessor" t:lndr_naml=Farrell t:report_num=3 t:form_type=B2 t:loan_st=CA t:rec_type=LOAN t:lndr_namf=John t:loan_occ=Manager t:filer_id=1240076 t:committee_type=CTL t:tran_id=48 t:loan_city="San Francisco" m:loan_amt2=0 m:loan_amt1=0 m:loan_amt4=0 m:loan_amt3=0 m:loan_amt6=0 m:loan_amt5=0 m:loan_amt8=0 m:loan_amt7=0

series e:ec3y-6ty9 d:2004-05-14T00:00:00.000Z t:loan_self=n t:lndr_namt=Mr. t:entity_cd=IND t:loan_rate=f t:filer_naml="Committee to Elect John Farrell Assessor" t:lndr_naml=Farrell t:report_num=3 t:form_type=B2 t:loan_st=CA t:rec_type=LOAN t:lndr_namf=John t:loan_occ=Manager t:filer_id=1240076 t:committee_type=CTL t:tran_id=49 t:loan_city="San Francisco" m:loan_amt2=50000 m:loan_amt1=0 m:loan_amt4=0 m:loan_amt3=0 m:loan_amt6=0 m:loan_amt5=0 m:loan_amt8=0 m:loan_amt7=0

series e:ec3y-6ty9 d:2003-09-23T00:00:00.000Z t:loan_self=n t:lndr_namt=Mr. t:entity_cd=IND t:loan_rate=f t:filer_naml="Committee to Elect John Farrell Assessor" t:lndr_naml=Farrell t:report_num=2 t:form_type=B2 t:loan_st=CA t:rec_type=LOAN t:lndr_namf=John t:loan_occ=Manager t:filer_id=1240076 t:committee_type=CTL t:tran_id=48 t:loan_city="San Francisco" m:loan_amt2=0 m:loan_amt1=0 m:loan_amt4=0 m:loan_amt3=0 m:loan_amt6=0 m:loan_amt5=0 m:loan_amt8=0 m:loan_amt7=0
```

## Meta Commands

```ls
metric m:loan_amt1 p:double l:Loan_Amt1 t:dataTypeName=money

metric m:loan_amt2 p:integer l:Loan_Amt2 t:dataTypeName=money

metric m:loan_amt3 p:integer l:Loan_Amt3 t:dataTypeName=money

metric m:loan_amt4 p:integer l:Loan_Amt4 t:dataTypeName=money

metric m:loan_amt5 p:integer l:Loan_Amt5 t:dataTypeName=money

metric m:loan_amt6 p:integer l:Loan_Amt6 t:dataTypeName=money

metric m:loan_amt7 p:integer l:Loan_Amt7 t:dataTypeName=money

metric m:loan_amt8 p:integer l:Loan_Amt8 t:dataTypeName=money

entity e:ec3y-6ty9 l:"Campaign Finance - FPPC Form 460 - Schedule B2 - Loan Guarantors" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/ec3y-6ty9

property e:ec3y-6ty9 t:meta.view v:id=ec3y-6ty9 v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Schedule B2 - Loan Guarantors" v:attribution="San Francisco Ethics Commission"

property e:ec3y-6ty9 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ec3y-6ty9 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:ec3y-6ty9 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                               | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | tran_id | entity_cd | lndr_naml | lndr_namf | lndr_namt | lndr_nams | loan_adr1 | loan_adr2 | loan_city     | loan_st | loan_zip4 | loan_date1          | loan_date2          | loan_amt1 | loan_amt2 | loan_amt3 | loan_amt4 | loan_rate | loan_emp | loan_occ | loan_self | cmte_id | tres_naml | tres_namf | tres_namt | tres_nams | tres_adr1 | tres_adr2 | tres_city | tres_st | tres_zip4 | b2lender_name_inter_name | intr_namf | intr_namt | intr_nams | intr_adr1 | intr_adr2 | intr_city | intr_st | intr_zip4 | memo_code | memo_refno | bakref_tid | xref_schnm | xref_match | loan_amt5 | loan_amt6 | loan_amt7 | loan_amt8 | 
| ======== | ======================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ============= | ======= | ========= | =================== | =================== | ========= | ========= | ========= | ========= | ========= | ======== | ======== | ========= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | ======================== | ========= | ========= | ========= | ========= | ========= | ========= | ======= | ========= | ========= | ========== | ========== | ========== | ========== | ========= | ========= | ========= | ========= | 
| 1240076  | Committee to Elect John Farrell Assessor | 3          | CTL            | 2004-05-14T00:00:00 | 2002-01-20T00:00:00 | 2002-02-21T00:00:00 |                     |                    |                     | LOAN     | B2        | 48      | IND       | Farrell   | John      | Mr.       |           |           |           | San Francisco | CA      |           | 2002-12-01T00:00:00 |                     | 0         | 0         | 0         | 0         | f         |          | Manager  | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1240076  | Committee to Elect John Farrell Assessor | 3          | CTL            | 2004-05-14T00:00:00 | 2002-01-20T00:00:00 | 2002-02-21T00:00:00 |                     |                    |                     | LOAN     | B2        | 49      | IND       | Farrell   | John      | Mr.       |           |           |           | San Francisco | CA      |           | 2002-12-01T00:00:00 |                     | 0         | 50000     | 0         | 0         | f         |          | Manager  | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1240076  | Committee to Elect John Farrell Assessor | 2          | CTL            | 2003-09-23T00:00:00 | 2002-01-20T00:00:00 | 2002-02-21T00:00:00 |                     |                    |                     | LOAN     | B2        | 48      | IND       | Farrell   | John      | Mr.       |           |           |           | San Francisco | CA      |           | 2002-12-01T00:00:00 |                     | 0         | 0         | 0         | 0         | f         |          | Manager  | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1240076  | Committee to Elect John Farrell Assessor | 2          | CTL            | 2003-09-23T00:00:00 | 2002-01-20T00:00:00 | 2002-02-21T00:00:00 |                     |                    |                     | LOAN     | B2        | 49      | IND       | Farrell   | John      | Mr.       |           |           |           | San Francisco | CA      |           | 2002-12-01T00:00:00 |                     | 0         | 50000     | 0         | 0         | f         |          | Manager  | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1240076  | Committee to Elect John Farrell Assessor | 1          | CTL            | 2002-10-31T00:00:00 | 2002-01-20T00:00:00 | 2002-02-21T00:00:00 |                     |                    |                     | LOAN     | B2        | 48      | IND       | Farrell   | John      | Mr.       |           |           |           | San Francisco | CA      |           | 2002-12-01T00:00:00 |                     | 0         | 0         | 0         | 0         | f         |          | Manager  | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1240076  | Committee to Elect John Farrell Assessor | 1          | CTL            | 2002-10-31T00:00:00 | 2002-01-20T00:00:00 | 2002-02-21T00:00:00 |                     |                    |                     | LOAN     | B2        | 49      | IND       | Farrell   | John      | Mr.       |           |           |           | San Francisco | CA      |           | 2002-12-01T00:00:00 |                     | 0         | 50000     | 0         | 0         | f         |          | Manager  | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1249109  | San Franciscans for Yes on Proposition J | 0          | BMC            | 2002-10-23T00:00:00 | 2002-10-01T00:00:00 | 2002-10-19T00:00:00 | 2002-11-05T00:00:00 |                    |                     | LOAN     | B2        | 17      | IND       | *         |           |           |           |           |           | San Francisco | CA      |           | 2002-10-23T00:00:00 |                     | 0         | 0         | 0         | 0         | f         |          |          | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1240076  | Committee to Elect John Farrell Assessor | 0          | CAO            | 2002-08-18T00:00:00 | 2002-02-22T00:00:00 | 2002-06-30T00:00:00 | 2002-03-05T00:00:00 |                    |                     | LOAN     | B2        | 13      | IND       | Farrell   | John      | Mr        |           |           |           | San Francisco | CA      |           | 2002-01-08T00:00:00 |                     | 0         | 50000     | 0         | 0         | f         |          | manager  | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1227780  | Ramos for Trustee                        | 0          | CAO            | 2002-07-31T00:00:00 | 2002-01-01T00:00:00 | 2002-06-30T00:00:00 |                     |                    |                     | LOAN     | B2        | 11      | IND       | *         |           |           |           |           |           | San Francisco | CA      |           | 2000-10-25T00:00:00 |                     | 0         | 0         | 0         | 0         | f         |          |          | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
| 1225983  | DISTRICT 6 DEMOCRATS                     | 0          | RCP            | 2002-10-20T00:00:00 | 2002-07-01T00:00:00 | 2002-10-19T00:00:00 | 2002-03-05T00:00:00 |                    |                     | LOAN     | B2        | B2-83   | IND       | HOBSON    | FREDERICK | Mr.       |           |           |           | SAN FRANCISCO | CA      | 94102     | 2002-02-01T00:00:00 | 2002-10-08T00:00:00 | 3000      | 0         | 0         | 0         | f         |          |          | n         |         |           |           |           |           |           |           |           |         |           |                          |           |           |           |           |           |           |         |           |           |            |            |            |            | 0         | 0         | 0         | 0         | 
```