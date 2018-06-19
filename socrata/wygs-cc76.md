# Campaign Finance - Data Key

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-data-key-bed01) |
| Metadata | [Link](https://data.sfgov.org/api/views/wygs-cc76) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wygs-cc76/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wygs-cc76/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wygs-cc76 |
| Name | Campaign Finance - Data Key |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | data, key, campaign, finance |
| Created | 2012-03-28T23:12:16Z |
| Publication Date | 2012-03-28T23:22:05Z |

## Description

The dataset contains descriptions for each column of historical campaign finance data available on data.sfgov.org or the Excel exports on the Ethics Commission's Campaign Finance Database at http://nf4.netfile.com/pub2?aid=sfoPlease note -- the column header names on different schedules of Form 460 often match, but sometimes have different meanings.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | numeric metric | form        | Form        | number    | text        |
| Yes      | series tag     | schedule    | Schedule    | text      | text        |
| Yes      | series tag     | column      | Column      | text      | text        |
| Yes      | series tag     | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wygs-cc76 d:2012-03-28T16:12:18.000Z t:schedule=A t:description="Filer ID (FPPC or Local)" t:column=Filer_ID m:form=460

series e:wygs-cc76 d:2012-03-28T16:12:18.000Z t:schedule=A t:description="Filer Name (Committee Name)" t:column=Filer_NamL m:form=460

series e:wygs-cc76 d:2012-03-28T16:12:18.000Z t:schedule=A t:description="Report Number (Amendment Sequence Order, 000 Original Report, 001-999 Amendment Report #)" t:column=Report_Num m:form=460
```

## Meta Commands

```ls
metric m:form p:integer l:Form t:dataTypeName=number

entity e:wygs-cc76 l:"Campaign Finance - Data Key" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/wygs-cc76

property e:wygs-cc76 t:meta.view v:id=wygs-cc76 v:category="City Management and Ethics" v:averageRating=0 v:name="Campaign Finance - Data Key" v:attribution="San Francisco Ethics Commission"

property e:wygs-cc76 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wygs-cc76 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:wygs-cc76 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| :updated_at | form | schedule | column              | description                                                                                                                                                                                                                  | 
| =========== | ==== | ======== | =================== | ============================================================================================================================================================================================================================ | 
| 1332951138  | 460  | A        | Filer_ID            | Filer ID (FPPC or Local)                                                                                                                                                                                                     | 
| 1332951138  | 460  | A        | Filer_NamL          | Filer Name (Committee Name)                                                                                                                                                                                                  | 
| 1332951138  | 460  | A        | Report_Num          | Report Number (Amendment Sequence Order, 000 Original Report, 001-999 Amendment Report #)                                                                                                                                    | 
| 1332951138  | 460  | A        | Committee_Type      | Type of Committee including (CAO - Candidate/Officeholder, CTL - Controlled Committee, RCP - Recipient Committee, SMO - Slate Mailer Organization, BMC - Ballot Measure Committee, MDI - Major Donor/Independent Expenditure | 
| 1332951138  | 460  | A        | Rpt_Date            | Date Document is Generated (As Written in CAL Submission)                                                                                                                                                                    | 
| 1332951138  | 460  | A        | From_Date           | Period Start Date                                                                                                                                                                                                            | 
| 1332951138  | 460  | A        | Thru_Date           | Period End Date                                                                                                                                                                                                              | 
| 1332951138  | 460  | A        | Elect_Date          | Election Date                                                                                                                                                                                                                | 
| 1332951138  | 460  | A        | tblCover.Office_Cd  | Office Sought (Codes in CAL Spec)                                                                                                                                                                                            | 
| 1332951138  | 460  | A        | tblCover.Offic_Dscr | Office Sought Description (Required if Office_CD is "OTH" Code for Other)                                                                                                                                                    | 
```