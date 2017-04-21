# Ethics Commission Enforcement Summaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ethics-commission-enforcement-summaries-fffa4) |
| Metadata | [Link](https://data.sfgov.org/api/views/yre9-mzkb) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/yre9-mzkb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/yre9-mzkb/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | yre9-mzkb |
| Name | Ethics Commission Enforcement Summaries |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics enforcement complaints sunshine |
| Created | 2013-03-29T17:01:59Z |
| Publication Date | 2017-01-27T19:41:10Z |

## Description

Summaries of closed complaints within the Ethics Commission's jurisdiction

## Columns

```ls
| Included | Schema Type | Field Name               | Name          | Data Type     | Render Type   |
| ======== | =========== | ======================== | ============= | ============= | ============= |
| Yes      | time        | date                     | Date          | calendar_date | calendar_date |
| Yes      | series tag  | respondents              | Respondents   | text          | text          |
| Yes      | series tag  | allegation_s             | Allegation(s) | text          | text          |
| Yes      | series tag  | disposition              | Disposition   | text          | text          |
| Yes      | series tag  | supporting_documents_url | URL           | url           | url           |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:yre9-mzkb d:2016-12-19T00:00:00.000Z t:respondents="Supervisor Eric Mar" t:allegation_s="Sunshine Ordinance sections 67.21(e), 67.25(a), 67.34" t:disposition="The Commission found that Respondent did not violate the Sunshine Ordinance." m:row_number.yre9-mzkb=1

series e:yre9-mzkb d:2016-12-19T00:00:00.000Z t:respondents="Stuart Shuffman for Mayor 2015" t:allegation_s="SF C&GCC (Campaign Finance Reform Ordinance) section1.22(b)(1)" t:supporting_documents_url=https://sfethics.org/wp-content/uploads/2016/12/2016-12-19-Stuart_Shuffman_Stipulation_sig_redacted_Redacted.pdf t:disposition="Settled, $2,552" m:row_number.yre9-mzkb=2

series e:yre9-mzkb d:2016-11-28T00:00:00.000Z t:respondents="Kimberly Alvarenga for Supervisor 2016" t:allegation_s="SF C&GCC (Campaign Finance Reform Ordinance) section 1.161" t:supporting_documents_url=https://sfethics.org/wp-content/uploads/2016/12/2016-11-28-Signed-Stip-Alvarenga-1617-42_Redacted-1.pdf t:disposition="Settled $500" m:row_number.yre9-mzkb=3
```

## Meta Commands

```ls
metric m:row_number.yre9-mzkb p:long l:"Row Number"

entity e:yre9-mzkb l:"Ethics Commission Enforcement Summaries" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/yre9-mzkb

property e:yre9-mzkb t:meta.view v:id=yre9-mzkb v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Ethics Commission Enforcement Summaries" v:attribution="San Francisco Ethics Commission"

property e:yre9-mzkb t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:yre9-mzkb t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:yre9-mzkb t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| date                | respondents                            | allegation_s                                                                                                                                               | disposition                                                                   | supporting_documents_url                                                                                                 | 
| =================== | ====================================== | ========================================================================================================================================================== | ============================================================================= | ======================================================================================================================== | 
| 2016-12-19T00:00:00 | Supervisor Eric Mar                    | Sunshine Ordinance sections 67.21(e), 67.25(a), 67.34                                                                                                      | The Commission found that Respondent did not violate the Sunshine Ordinance.  | [null, null]                                                                                                             | 
| 2016-12-19T00:00:00 | Stuart Shuffman for Mayor 2015         | SF C&GCC (Campaign Finance Reform Ordinance) section1.22(b)(1)                                                                                             | Settled, $2,552                                                               | [https://sfethics.org/wp-content/uploads/2016/12/2016-12-19-Stuart_Shuffman_Stipulation_sig_redacted_Redacted.pdf, null] | 
| 2016-11-28T00:00:00 | Kimberly Alvarenga for Supervisor 2016 | SF C&GCC (Campaign Finance Reform Ordinance) section 1.161                                                                                                 | Settled $500                                                                  | [https://sfethics.org/wp-content/uploads/2016/12/2016-11-28-Signed-Stip-Alvarenga-1617-42_Redacted-1.pdf, null]          | 
| 2016-11-28T00:00:00 | San Francisco for a City that Works    | SF C&GCC (Campaign Finance Reform Ordinance) sections 1.161 and 1.162                                                                                      | Settled $7,500                                                                | [https://sfethics.org/wp-content/uploads/2016/12/2016-11-28-Signed-Stip-CTW-Disclaimers-1617-36_Redacted-1.pdf, null]    | 
| 2016-11-28T00:00:00 | Board of Supervisors                   | Sunshine Ordinance sections 67.21 and 67.34                                                                                                                | The Commission found that Respondent did not violate the Sunshine Ordinance.  | [null, null]                                                                                                             | 
| 2016-11-28T00:00:00 | Barbara Sklar                          | SF C&GCC 3.1-102, EC Regulation 15.102-1, Sunshine Ordinance section 67.34                                                                                 | The Commission found that Respondent did not violate the Sunshine Ordinance.  | [null, null]                                                                                                             | 
| 2016-11-28T00:00:00 | John Rahaim, Sarah Jones               | Sunshine Ordinance sections 67.29                                                                                                                          | The Commission found that Respondent did not violate the Sunshine Ordinance.  | [null, null]                                                                                                             | 
| 2016-09-26T00:00:00 | Steve Kawa                             | Sunshine Ordinance sections 67.21, 67.29-7, 67.34                                                                                                          | The Commission found that Respondents did not violate the Sunshine Ordinance. | [null, null]                                                                                                             | 
| 2016-09-26T00:00:00 | Lynette Sweet                          | SF C&GCC sections 1.106, 1.109, 1.118 - failure to file campaign statements, failure to maintain required committee documents, failure to pay accrued debt | Administrative penalty of $74,409.18 and $4,650 forfeiture                    | [https://sfethics.org/wp-content/uploads/2016/12/2016-09-27-FINAL-ORDER-signed-19-131115-Sweet_Redacted.pdf, null]       | 
| 2016-06-27T00:00:00 |                                        | SF C&GCC section 3.1-101, FPPC Reg. 18730(b)(8.1)(A) - accepting a gift from a single source that exceed the annual gift limit                             | Dismissed                                                                     | [null, null]                                                                                                             | 
```