# Proposed - Updating Air Quality Rules to Address Federal Regulations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proposed-updating-air-quality-rules-to-address-federal-regulations) |
| Metadata | [Link](https://data.oregon.gov/api/views/eitf-mgpx) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/eitf-mgpx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/eitf-mgpx/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | eitf-mgpx |
| Name | Proposed - Updating Air Quality Rules to Address Federal Regulations |
| Attribution | Department of Environmental Quality |
| Created | 2015-12-14T19:49:02Z |
| Publication Date | 2016-11-15T17:41:08Z |

## Description

Comment on proposed rulemaking. Comment period runs from 11/15/16-12/23/16. Comments submitted outside this comment period will not be considered.

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
series e:eitf-mgpx d:2016-01-26T14:44:23.000Z t:first_name=Kathryn t:organization="Northwest Pulp and Paper Assn." t:additional_document.filename="NWPPA Comments DEQ AQ Fed Regs Adoption Jan 26 2016 .pdf" t:additional_document.size=282304 t:additional_document.content_type=application/pdf t:state=Oregon t:last_name=VanNatta t:additional_document.file_id=04868dd1-8a62-4b9f-93ce-3b2561b180f9 t:comment="See attached comments.  Thank you for the opportunity to comment." t:email_address=kathryn@nwpulpandpaper.org m:row_number.eitf-mgpx=1
```

## Meta Commands

```ls
metric m:row_number.eitf-mgpx p:long l:"Row Number"

entity e:eitf-mgpx l:"Proposed - Updating Air Quality Rules to Address Federal Regulations" t:attribution="Department of Environmental Quality" t:url=https://data.oregon.gov/api/views/eitf-mgpx

property e:eitf-mgpx t:meta.view v:id=eitf-mgpx v:attributionLink=http://oregon.gov/deq v:averageRating=0 v:name="Proposed - Updating Air Quality Rules to Address Federal Regulations" v:attribution="Department of Environmental Quality"

property e:eitf-mgpx t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:eitf-mgpx t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| :updated_at | first_name | last_name | email_address              | organization                   | state  | comment                                                          | additional_document                                                                                                       | 
| =========== | ========== | ========= | ========================== | ============================== | ====== | ================================================================ | ========================================================================================================================= | 
| 1453819463  | Kathryn    | VanNatta  | kathryn@nwpulpandpaper.org | Northwest Pulp and Paper Assn. | Oregon | See attached comments. Thank you for the opportunity to comment. | [application/pdf, 04868dd1-8a62-4b9f-93ce-3b2561b180f9, NWPPA Comments DEQ AQ Fed Regs Adoption Jan 26 2016 .pdf, 282304] | 
```