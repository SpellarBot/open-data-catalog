# Greenhouse Gas Reporting Update

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/greenhouse-gas-reporting-update) |
| Metadata | [Link](https://data.oregon.gov/api/views/bw2w-bwtx) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/bw2w-bwtx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/bw2w-bwtx/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | bw2w-bwtx |
| Name | Greenhouse Gas Reporting Update |
| Created | 2015-08-11T16:18:03Z |
| Publication Date | 2015-09-28T19:55:12Z |

## Description

Comment period open Friday, Aug. 14 through Thursday, Sept. 29, 2015

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email_address       | Email Address       | email     | email       |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional Document | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bw2w-bwtx d:2015-09-28T13:29:53.000Z t:first_name=Elysia t:organization="Portland General Electric Company" t:additional_document.filename="PGE DEQ GHG Rule Update Comment Letter_09282015.pdf" t:additional_document.size=697512 t:additional_document.content_type=application/pdf t:state=Oregon t:last_name=Treanor t:additional_document.file_id=EhG6O5wtoBq1gcOYJ2SL-pJa_kPfvTwgWFY4-8MHK8M t:comment="Portland General Electric Company's comments on the proposed Greenhouse Gas Reporting Rule Update are attached." t:email_address=elysia.treanor@pgn.com m:row_number.bw2w-bwtx=1

series e:bw2w-bwtx d:2015-09-29T10:22:17.000Z t:first_name=Etta t:organization=PacifiCorp t:additional_document.filename="DEQ GHG Final Comments 9 29 15.pdf" t:additional_document.size=49545 t:additional_document.content_type=application/pdf t:state=Oregon t:last_name=Lockey t:additional_document.file_id=mP82WQsUGRhATPxw6hbSfXyFD162Rf70Lo4fUIZUIkU t:email_address=etta.lockey@pacificorp.com m:row_number.bw2w-bwtx=2

series e:bw2w-bwtx d:2015-09-29T11:52:45.000Z t:first_name=Wendy t:organization="Oregon Department of Energy" t:additional_document.filename="ODOE DEQ GHG Rule Final Comments 09292015.docx" t:additional_document.size=16325 t:additional_document.content_type=application/vnd.openxmlformats-officedocument.wordprocessingml.document t:state=Oregon t:last_name=Simons t:additional_document.file_id=wkB0yMIxk8khxldCinqdMCYBjzaN96FGd60MYmSBV2c t:email_address=wendy.simons@state.or.us m:row_number.bw2w-bwtx=3
```

## Meta Commands

```ls
metric m:row_number.bw2w-bwtx p:long l:"Row Number"

entity e:bw2w-bwtx l:"Greenhouse Gas Reporting Update" t:url=https://data.oregon.gov/api/views/bw2w-bwtx

property e:bw2w-bwtx t:meta.view v:id=bw2w-bwtx v:averageRating=0 v:name="Greenhouse Gas Reporting Update"

property e:bw2w-bwtx t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:bw2w-bwtx t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| :updated_at | first_name | last_name   | email_address                       | organization                      | state  | comment                                                                                                         | additional_document                                                                                                                                                           | 
| =========== | ========== | =========== | =================================== | ================================= | ====== | =============================================================================================================== | ============================================================================================================================================================================= | 
| 1443446993  | Elysia     | Treanor     | elysia.treanor@pgn.com              | Portland General Electric Company | Oregon | Portland General Electric Company's comments on the proposed Greenhouse Gas Reporting Rule Update are attached. | [application/pdf, EhG6O5wtoBq1gcOYJ2SL-pJa_kPfvTwgWFY4-8MHK8M, PGE DEQ GHG Rule Update Comment Letter_09282015.pdf, 697512]                                                   | 
| 1443522137  | Etta       | Lockey      | etta.lockey@pacificorp.com          | PacifiCorp                        | Oregon |                                                                                                                 | [application/pdf, mP82WQsUGRhATPxw6hbSfXyFD162Rf70Lo4fUIZUIkU, DEQ GHG Final Comments 9 29 15.pdf, 49545]                                                                     | 
| 1443527565  | Wendy      | Simons      | wendy.simons@state.or.us            | Oregon Department of Energy       | Oregon |                                                                                                                 | [application/vnd.openxmlformats-officedocument.wordprocessingml.document, wkB0yMIxk8khxldCinqdMCYBjzaN96FGd60MYmSBV2c, ODOE DEQ GHG Rule Final Comments 09292015.docx, 16325] | 
| 1443534683  | Bob        | Baumgartner | BaumgartnerB@CleanWaterServices.org | Clean Water Services              | Oregon | Comments attached.                                                                                              | [application/pdf, DMhuW2Dw85SvDDHfEhXlAoWXNHa8KE9V1UIaFiqe6mA, CWS comments on proposed revisions to greenhouse gas reporting rules.pdf, 1040633]                             | 
| 1443534693  | Bob        | Baumgartner | BaumgartnerB@CleanWaterServices.org | Clean Water Services              | Oregon | Comments attached.                                                                                              | [application/pdf, DMhuW2Dw85SvDDHfEhXlAoWXNHa8KE9V1UIaFiqe6mA, CWS comments on proposed revisions to greenhouse gas reporting rules.pdf, 1040633]                             | 
```