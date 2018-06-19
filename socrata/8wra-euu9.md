# Campaign Finance - Summary of Third Party Expenditures Regarding San Francisco Candidates - November 3, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-summary-of-third-party-expenditures-regarding-san-francisco-candidates-20) |
| Metadata | [Link](https://data.sfgov.org/api/views/8wra-euu9) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/8wra-euu9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/8wra-euu9/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 8wra-euu9 |
| Name | Campaign Finance - Summary of Third Party Expenditures Regarding San Francisco Candidates - November 3, 2015 |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Created | 2015-06-26T17:38:54Z |
| Publication Date | 2016-02-17T20:24:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag     | form_type                        | Form Type                        | text          | text          |
| Yes      | series tag     | report_number                    | Report Number                    | text          | text          |
| Yes      | time           | date_filed                       | Date filed                       | calendar_date | calendar_date |
| Yes      | series tag     | filer                            | Filer                            | text          | text          |
| Yes      | series tag     | filer_id                         | Filer Id                         | text          | text          |
| Yes      | numeric metric | amount                           | Amount                           | money         | money         |
| Yes      | series tag     | candidate_identified             | Candidate Identified             | text          | text          |
| Yes      | series tag     | district                         | District                         | text          | text          |
| Yes      | series tag     | support_oppose_or_neutral        | Support, Oppose or Neutral       | text          | text          |
| No       |                | start_date_of_distribution       | Start Date of Distribution       | calendar_date | calendar_date |
| No       |                | end_or_only_date_of_distribution | End or Only Date of Distribution | calendar_date | calendar_date |
| Yes      | series tag     | notes                            | Notes                            | text          | text          |
| Yes      | series tag     | attachment_1                     | Attachment 1                     | document      | document      |
| Yes      | series tag     | attachment_2                     | Attachment 2                     | document      | document      |
| Yes      | series tag     | attachment_3                     | Attachment 3                     | document      | document      |
| Yes      | series tag     | attachment_4                     | Attachment 4                     | document      | document      |
| Yes      | series tag     | attachment_5                     | Attachment 5                     | document      | document      |
| Yes      | series tag     | attachment_6                     | Attachment 6                     | document      | document      |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_date_of_distribution,end_or_only_date_of_distribution
```

## Data Commands

```ls
series e:8wra-euu9 d:2015-10-01T00:00:00.000Z t:filer="Building Owners and Managers Association of San Francisco Political Action Committee - Independent Expenditures AKA BOMA-SF-PAC-IE" t:report_number=G15-BSF-01 t:form_type=496 t:candidate_identified="Christensen, Julie" t:support_oppose_or_neutral=Support t:filer_id=870449 t:district=3 m:amount=2500

series e:8wra-euu9 d:2015-09-30T00:00:00.000Z t:filer="San Francisco Democratic County Central Committee" t:report_number=92915 t:form_type=163 t:candidate_identified="Gascon, George" t:support_oppose_or_neutral=Support t:filer_id=742051 t:district="District Attorney" m:amount=2273.19

series e:8wra-euu9 d:2015-09-29T00:00:00.000Z t:filer="San Franciscans for Affordable Housing, Jobs & Parks, Yes on Prop D" t:report_number=20150929-1 t:form_type=162 t:candidate_identified="Lee, Ed" t:support_oppose_or_neutral=Neutral t:filer_id=1377448 t:district=Mayor m:amount=2996.95
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:8wra-euu9 l:"Campaign Finance - Summary of Third Party Expenditures Regarding San Francisco Candidates - November 3, 2015" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/8wra-euu9

property e:8wra-euu9 t:meta.view v:id=8wra-euu9 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Summary of Third Party Expenditures Regarding San Francisco Candidates - November 3, 2015" v:attribution="San Francisco Ethics Commission"

property e:8wra-euu9 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:8wra-euu9 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:8wra-euu9 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| form_type | report_number | date_filed          | filer                                                                                                                              | filer_id | amount  | candidate_identified | district                   | support_oppose_or_neutral | start_date_of_distribution | end_or_only_date_of_distribution | notes       | attachment_1             | attachment_2             | attachment_3             | attachment_4             | attachment_5             | attachment_6             | 
| ========= | ============= | =================== | ================================================================================================================================== | ======== | ======= | ==================== | ========================== | ========================= | ========================== | ================================ | =========== | ======================== | ======================== | ======================== | ======================== | ======================== | ======================== | 
| 496       | G15-BSF-01    | 2015-10-01T00:00:00 | Building Owners and Managers Association of San Francisco Political Action Committee - Independent Expenditures AKA BOMA-SF-PAC-IE | 870449   | 2500    | Christensen, Julie   | 3                          | Support                   | 2015-09-30T00:00:00        | 2015-09-30T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 163       | 92915         | 2015-09-30T00:00:00 | San Francisco Democratic County Central Committee                                                                                  | 742051   | 2273.19 | Gascon, George       | District Attorney          | Support                   | 2015-09-29T00:00:00        | 2015-09-29T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 162       | 20150929-1    | 2015-09-29T00:00:00 | San Franciscans for Affordable Housing, Jobs & Parks, Yes on Prop D                                                                | 1377448  | 2996.95 | Lee, Ed              | Mayor                      | Neutral                   | 2015-09-28T00:00:00        | 2015-09-28T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 162       | 20151002-1    | 2015-10-02T00:00:00 | San Franciscans for Affordable Housing, Jobs & Parks, Yes on Prop D                                                                | 1377448  | 2900.81 | Lee, Ed              | Mayor                      | Support                   | 2015-10-01T00:00:00        | 2015-10-01T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 162       | 20150924-1    | 2015-09-24T00:00:00 | San Franciscans for Affordable Housing, Jobs & Parks, Yes on Prop D                                                                | 1377448  | 2479.41 | Lee, Ed              | Mayor                      | Neutral                   | 2015-08-26T00:00:00        | 2015-09-23T00:00:00              | media posts | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 163       | 100115        | 2015-10-06T00:00:00 | San Francisco Democratic County Central Committee                                                                                  | 742051   | 3211.62 | Christensen, Julie   | 3                          | Support                   | 2015-10-01T00:00:00        | 2015-10-01T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 162       | 20150916-2    | 2015-09-16T00:00:00 | San Franciscans for Affordable Housing, Jobs & Parks, Yes on Prop D                                                                | 1377448  | 519.2   | Lee, Ed              | Mayor                      | Neutral                   | 2015-09-08T00:00:00        | 2015-09-15T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 163       | 92915         | 2015-09-30T00:00:00 | San Francisco Democratic County Central Committee                                                                                  | 742051   | 142     | Christensen, Julie   | 3                          | Support                   | 2015-09-29T00:00:00        | 2015-09-29T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 162       | 20150930-1    | 2015-09-30T00:00:00 | San Franciscans for Affordable Housing, Jobs & Parks, Yes on Prop D                                                                | 1377448  | 5290.15 | Lee, Ed              | Mayor                      | Support                   | 2015-09-29T00:00:00        | 2015-09-30T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 163       | 92915         | 2015-09-30T00:00:00 | San Francisco Democratic County Central Committee                                                                                  | 742051   | 2273.19 | Randolph, Alex       | Board of Community College | Support                   | 2015-09-29T00:00:00        | 2015-09-29T00:00:00              |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
```