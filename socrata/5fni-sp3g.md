# WQ Permit Fee Rulemaking 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wq-permit-fee-rulemaking-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/5fni-sp3g) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/5fni-sp3g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/5fni-sp3g/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 5fni-sp3g |
| Name | WQ Permit Fee Rulemaking 2015 |
| Created | 2015-09-10T21:55:56Z |
| Publication Date | 2015-09-14T22:55:34Z |

## Description

Public comment open September 15, 2015 through October 15, 2015.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
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
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5fni-sp3g d:2015-01-01T00:00:00.000Z t:first_name=Forrest t:organization="Rogue Riverkeeper" t:additional_document.filename="RRK fee increase comments 10-14-2015.pdf" t:additional_document.size=190038 t:additional_document.content_type=application/pdf t:state=OR t:last_name=English t:additional_document.file_id=grSyy5tBSOl8PFJAgGbFzf91t3CtA6XSZGlIidLrtLI t:comment="Attached comments in support of fee increases to provide staff and infrastructure resources for DEQ." t:email_address=forrest@rogueriverkeeper.org m:row_number.5fni-sp3g=1

series e:5fni-sp3g d:2015-01-01T00:00:00.000Z t:first_name=Janet t:organization="Oregon Association of Clean Water Agencies" t:additional_document.filename="DEQ WQ fee increase LOC SDAO ACWA 10 15.pdf" t:additional_document.size=318180 t:additional_document.content_type=application/pdf t:state=Oregon t:last_name=Gillaspie t:additional_document.file_id=AdVSg5Ipjp0l7qXXTuAWF5e-wSvalKQn-aTz6uJtPbw t:comment="Attached are the comments of the League of Oregon Cities, Special Districts Association of Oregon, and Oregon Association of Clean Water Agencies regarding the pending water quality fee increases" t:email_address=gillaspie@oracwa.org m:row_number.5fni-sp3g=2

series e:5fni-sp3g d:2015-01-01T00:00:00.000Z t:first_name=goha2004 t:organization=goha2004 t:last_name=goha2004 t:comment="http://runotes.cloudns.org/my-funny-valentine-chris-botti-skachat-noty-dlya.html <a target=""_blank"" href=""http://runotes.cloudns.org/hora-tiganeasca-skachat-noty-akkordeon.html"">http://runotes.cloudns.org/imprint-s-rozhdestvom-tebya-skachat-noty.html</a> [url=http://runotes.cloudns.org/a-n-jell-ty-prekrasen-skachat-noty-dlya-fono.html]http://runotes.cloudns.org/happy-new-year-skachat-melodiyu-dlya-fortepiano.html[/url]" t:email_address=gohaBoatH@gmail.com m:row_number.5fni-sp3g=3
```

## Meta Commands

```ls
metric m:row_number.5fni-sp3g p:long l:"Row Number"

entity e:5fni-sp3g l:"WQ Permit Fee Rulemaking 2015" t:url=https://data.oregon.gov/api/views/5fni-sp3g

property e:5fni-sp3g t:meta.view v:id=5fni-sp3g v:averageRating=0 v:name="WQ Permit Fee Rulemaking 2015"

property e:5fni-sp3g t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:5fni-sp3g t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| first_name | last_name | email_address                | organization                               | state  | comment                                                                                                                                                                                                                                                                                                                           | additional_document                                                                                                 | 
| ========== | ========= | ============================ | ========================================== | ====== | ================================================================================================================================================================================================================================================================================================================================= | =================================================================================================================== | 
| Forrest    | English   | forrest@rogueriverkeeper.org | Rogue Riverkeeper                          | OR     | Attached comments in support of fee increases to provide staff and infrastructure resources for DEQ.                                                                                                                                                                                                                              | [application/pdf, grSyy5tBSOl8PFJAgGbFzf91t3CtA6XSZGlIidLrtLI, RRK fee increase comments 10-14-2015.pdf, 190038]    | 
| Janet      | Gillaspie | gillaspie@oracwa.org         | Oregon Association of Clean Water Agencies | Oregon | Attached are the comments of the League of Oregon Cities, Special Districts Association of Oregon, and Oregon Association of Clean Water Agencies regarding the pending water quality fee increases                                                                                                                               | [application/pdf, AdVSg5Ipjp0l7qXXTuAWF5e-wSvalKQn-aTz6uJtPbw, DEQ WQ fee increase LOC SDAO ACWA 10 15.pdf, 318180] | 
| goha2004   | goha2004  | gohaBoatH@gmail.com          | goha2004                                   |        | http://runotes.cloudns.org/my-funny-valentine-chris-botti-skachat-noty-dlya.html http://runotes.cloudns.org/imprint-s-rozhdestvom-tebya-skachat-noty.html [url=http://runotes.cloudns.org/a-n-jell-ty-prekrasen-skachat-noty-dlya-fono.html]http://runotes.cloudns.org/happy-new-year-skachat-melodiyu-dlya-fortepiano.html[/url] | [null, null, null, null]                                                                                            | 
```