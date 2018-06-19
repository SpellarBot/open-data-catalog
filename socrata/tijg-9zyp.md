# Expenditures by Candidates and Political Committees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-by-candidates-and-political-committees) |
| Metadata | [Link](https://data.wa.gov/api/views/tijg-9zyp) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/tijg-9zyp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/tijg-9zyp/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | tijg-9zyp |
| Name | Expenditures by Candidates and Political Committees |
| Attribution | Public Disclosure Commission |
| Tags | political finance, elections, expenditures, campaign, political committee |
| Created | 2017-01-05T21:22:44Z |
| Publication Date | 2017-04-18T03:24:54Z |

## Description

This dataset contains expenditures made by Washington State Candidates and Political Committees for the last 10 years as reported to the PDC on forms C3, C4, Schedule C and their electronic filing equivalents.

In-kind contributions are not included in this dataset but they are considered as both a contribution and expenditure. In-kind contributions are included in the dataset "Contributions to Candidates and Political Committees"

For candidates, the number of years is determined by the year of the election, not necessarily the year the expenditure was reported. For political committees, the number of years is determined by the calendar year of the reporting period.

Candidates and political committees choosing to file under "mini reporting" are not included in this dataset. See WAC 390-16-105 for information regarding eligibility.

This dataset is a best-effort by the PDC to provide a complete set of records as described herewith and may contain incomplete or incorrect information. The PDC provides access to the original reports for the purpose of record verification.

Descriptions attached to this dataset do not constitute legal definitions; please consult RCW 42.17A and WAC Title 390 for legal definitions and additional information regarding political finance disclosure requirements.

CONDITION OF RELEASE: This publication constitutes a list of individuals prepared by the Washington State Public Disclosure Commission and may not be used for commercial purposes. This list is provided on the condition and with the understanding that the persons receiving it agree to this statutorily imposed limitation on its use. See
RCW 42.56.070(9) and AGO 1975 No. 15.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| No       |                | id                       | id                       | text          | text          |
| Yes      | series tag     | report_number            | report_number            | text          | text          |
| Yes      | series tag     | origin                   | origin                   | text          | text          |
| Yes      | series tag     | filer_id                 | filer_id                 | text          | text          |
| Yes      | series tag     | type                     | type                     | text          | text          |
| Yes      | series tag     | filer_name               | filer_name               | text          | text          |
| Yes      | series tag     | first_name               | first_name               | text          | text          |
| Yes      | series tag     | middle_initial           | middle_initial           | text          | text          |
| Yes      | series tag     | last_name                | last_name                | text          | text          |
| Yes      | series tag     | office                   | office                   | text          | text          |
| Yes      | series tag     | legislative_district     | legislative_district     | text          | text          |
| Yes      | series tag     | position                 | position                 | text          | text          |
| Yes      | series tag     | party                    | party                    | text          | text          |
| Yes      | series tag     | ballot_number            | ballot_number            | text          | text          |
| Yes      | series tag     | for_or_against           | for_or_against           | text          | text          |
| Yes      | series tag     | jurisdiction             | jurisdiction             | text          | text          |
| Yes      | series tag     | jurisdiction_county      | jurisdiction_county      | text          | text          |
| Yes      | series tag     | jurisdiction_type        | jurisdiction_type        | text          | text          |
| No       |                | election_year            | election_year            | number        | number        |
| Yes      | numeric metric | amount                   | amount                   | money         | money         |
| Yes      | series tag     | itemized_or_non_itemized | itemized_or_non_itemized | text          | text          |
| Yes      | time           | expenditure_date         | expenditure_date         | calendar_date | calendar_date |
| Yes      | series tag     | description              | description              | text          | text          |
| Yes      | series tag     | code                     | code                     | text          | text          |
| Yes      | series tag     | recipient_name           | recipient_name           | text          | text          |
| No       |                | recipient_address        | recipient_address        | text          | text          |
| Yes      | series tag     | recipient_city           | recipient_city           | text          | text          |
| Yes      | series tag     | recipient_state          | recipient_state          | text          | text          |
| Yes      | series tag     | recipient_zip            | recipient_zip            | text          | text          |
| Yes      | series tag     | url                      | url                      | url           | url           |
```

## Time Field

```ls
Value = expenditure_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,recipient_address,election_year
```

## Data Commands

```ls
series e:tijg-9zyp d:2012-08-05T00:00:00.000Z t:office="PUBLIC UTILITY COMMISSIONER" t:position=01 t:report_number=100490476 t:filer_name="MALINOWSKI JAMES H" t:jurisdiction_county=CLARK t:middle_initial=H t:recipient_state=WA t:origin=A/GT50 t:jurisdiction="CLARK PUBLIC UTILITIES" t:party="NON PARTISAN" t:type=Candidate t:recipient_name="SENIOR MESSENGER" t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100490476" t:itemized_or_non_itemized=Itemized t:jurisdiction_type=Local t:first_name=JAMES t:recipient_city=VANCOUVER t:recipient_zip=98668 t:description=AD t:filer_id="MALIJ  601" t:last_name=MALINOWSKI m:amount=220

series e:tijg-9zyp d:2012-08-29T00:00:00.000Z t:office="PUBLIC UTILITY COMMISSIONER" t:position=01 t:report_number=100490476 t:filer_name="MALINOWSKI JAMES H" t:jurisdiction_county=CLARK t:middle_initial=H t:recipient_state=WA t:origin=A/GT50 t:jurisdiction="CLARK PUBLIC UTILITIES" t:party="NON PARTISAN" t:type=Candidate t:recipient_name="SENIOR MESSENGER" t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100490476" t:itemized_or_non_itemized=Itemized t:jurisdiction_type=Local t:first_name=JAMES t:recipient_city=VANCOUVER t:recipient_zip=98668 t:description=AD t:filer_id="MALIJ  601" t:last_name=MALINOWSKI m:amount=200

series e:tijg-9zyp d:2012-08-23T00:00:00.000Z t:report_number=100491167 t:filer_name="NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC" t:origin=A/GT50 t:recipient_state=WA t:type="Political Committee" t:recipient_name="COMMITTEE TO ELECT CARY CONDOTTA" t:itemized_or_non_itemized=Itemized t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491167" t:recipient_city=WENATCHEE t:recipient_zip=98807 t:description="CONTRIBUTION TO CANDIDATE" t:filer_id="NATIIO 020" t:last_name="NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC" m:amount=500
```

## Meta Commands

```ls
metric m:amount p:double l:amount d:"The amount of the expenditure or in-kind contribution. In-kind contributions are both a contribution and an expenditure and represented in both the contributions and expenditures data." t:dataTypeName=money

entity e:tijg-9zyp l:"Expenditures by Candidates and Political Committees" t:attribution="Public Disclosure Commission" t:url=https://data.wa.gov/api/views/tijg-9zyp

property e:tijg-9zyp t:meta.view v:id=tijg-9zyp v:attributionLink=http://www.pdc.wa.gov v:averageRating=0 v:name="Expenditures by Candidates and Political Committees" v:attribution="Public Disclosure Commission"

property e:tijg-9zyp t:meta.view.license v:name="Public Domain"

property e:tijg-9zyp t:meta.view.owner v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:displayName="Washington Public Disclosure Commission"

property e:tijg-9zyp t:meta.view.tableauthor v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:roleName=publisher v:displayName="Washington Public Disclosure Commission"
```

## Top Records

```ls
| id          | report_number | origin | filer_id   | type                | filer_name                                                 | first_name | middle_initial | last_name                                                  | office                      | legislative_district | position | party        | ballot_number | for_or_against | jurisdiction           | jurisdiction_county | jurisdiction_type | election_year | amount | itemized_or_non_itemized | expenditure_date    | description               | code | recipient_name                   | recipient_address  | recipient_city | recipient_state | recipient_zip | url                                                                            | 
| =========== | ============= | ====== | ========== | =================== | ========================================================== | ========== | ============== | ========================================================== | =========================== | ==================== | ======== | ============ | ============= | ============== | ====================== | =================== | ================= | ============= | ====== | ======================== | =================== | ========================= | ==== | ================================ | ================== | ============== | =============== | ============= | ============================================================================== | 
| 761539.expn | 100490476     | A/GT50 | MALIJ 601  | Candidate           | MALINOWSKI JAMES H                                         | JAMES      | H              | MALINOWSKI                                                 | PUBLIC UTILITY COMMISSIONER |                      | 01       | NON PARTISAN |               |                | CLARK PUBLIC UTILITIES | CLARK               | Local             | 2012          | 220.00 | Itemized                 | 2012-08-05T00:00:00 | AD                        |      | SENIOR MESSENGER                 | PO BOX 1995        | VANCOUVER      | WA              | 98668         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100490476, View report] | 
| 761541.expn | 100490476     | A/GT50 | MALIJ 601  | Candidate           | MALINOWSKI JAMES H                                         | JAMES      | H              | MALINOWSKI                                                 | PUBLIC UTILITY COMMISSIONER |                      | 01       | NON PARTISAN |               |                | CLARK PUBLIC UTILITIES | CLARK               | Local             | 2012          | 200.00 | Itemized                 | 2012-08-29T00:00:00 | AD                        |      | SENIOR MESSENGER                 | PO BOX 1995        | VANCOUVER      | WA              | 98668         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100490476, View report] | 
| 761716.expn | 100491167     | A/GT50 | NATIIO 020 | Political Committee | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |            |                | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |                             |                      |          |              |               |                |                        |                     |                   | 2012          | 500.00 | Itemized                 | 2012-08-23T00:00:00 | CONTRIBUTION TO CANDIDATE |      | COMMITTEE TO ELECT CARY CONDOTTA | P.O. BOX 3001      | WENATCHEE      | WA              | 98807         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491167, View report] | 
| 761723.expn | 100491167     | A/GT50 | NATIIO 020 | Political Committee | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |            |                | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |                             |                      |          |              |               |                |                        |                     |                   | 2012          | 900.00 | Itemized                 | 2012-08-23T00:00:00 | CONTRIBUTION TO CANDIDATE |      | FRIENDS OF SHELLY SCHLUMPF       | P.O. BOX 73074     | PUYALLUP       | WA              | 98373         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491167, View report] | 
| 761724.expn | 100491167     | A/GT50 | NATIIO 020 | Political Committee | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |            |                | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |                             |                      |          |              |               |                |                        |                     |                   | 2012          | 500.00 | Itemized                 | 2012-08-23T00:00:00 | CONTRIBUTION TO CANDIDATE |      | FRIENDS FOR ANN RIVERS           | P.O. BOX 957       | LA CENTER      | WA              | 98629         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491167, View report] | 
| 761727.expn | 100491167     | A/GT50 | NATIIO 020 | Political Committee | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |            |                | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |                             |                      |          |              |               |                |                        |                     |                   | 2012          | 900.00 | Itemized                 | 2012-08-23T00:00:00 | CONTRIBUTION TO CANDIDATE |      | FRIENDS OF LARRY SPRINGER        | 700 20TH AVENUE W. | KIRKLAND       | WA              | 98033         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491167, View report] | 
| 761733.expn | 100491167     | A/GT50 | NATIIO 020 | Political Committee | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |            |                | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |                             |                      |          |              |               |                |                        |                     |                   | 2012          | 500.00 | Itemized                 | 2012-08-23T00:00:00 | CONTRIBUTION TO CANDIDATE |      | FRIENDS OF ROSS HUNTER           | P.O. BOX 4204      | BELLEVUE       | WA              | 98009         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491167, View report] | 
| 761736.expn | 100491167     | A/GT50 | NATIIO 020 | Political Committee | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |            |                | NATL ASSN OF INDUSTRIAL & OFFICE PROPERTIES WA CHAPTER PAC |                             |                      |          |              |               |                |                        |                     |                   | 2012          | 300.00 | Itemized                 | 2012-08-23T00:00:00 | CONTRIBUTION TO CANDIDATE |      | FRIENDS OF ANDY BILLIG           | P.O. BOX 145       | SPOKANE        | WA              | 99210         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491167, View report] | 
| 761774.expn | 100491285     | A/GT50 | SNOHRC 206 | Political Committee | SNOHOMISH CO REPUB CENT COMM NON EXEMPT                    |            |                | SNOHOMISH CO REPUB CENT COMM NON EXEMPT                    |                             |                      |          |              |               |                |                        |                     |                   | 2012          | 798.20 | Itemized                 | 2012-03-29T00:00:00 | COUNTY CONVENTION SET UP  |      | TOTAL RENTAL CENTER, INC.        | 9217 EVERGREEN WAY | EVERETT        | WA              | 98204         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491285, View report] | 
| 761781.expn | 100491285     | A/GT50 | SNOHRC 206 | Political Committee | SNOHOMISH CO REPUB CENT COMM NON EXEMPT                    |            |                | SNOHOMISH CO REPUB CENT COMM NON EXEMPT                    |                             |                      |          |              |               |                |                        |                     |                   | 2012          | 795.75 | Itemized                 | 2012-03-31T00:00:00 | BALLOT PRINTING           |      | MARZOLF ROSS                     |                    |                | WA              |               | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100491285, View report] | 
```