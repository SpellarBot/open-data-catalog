# Austin Digital Assessment - Aggregated Responses by Geography

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-digital-assessment-aggregated-responses-by-geography) |
| Metadata | [Link](https://data.austintexas.gov/api/views/xf72-sbj4) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/xf72-sbj4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/xf72-sbj4/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | xf72-sbj4 |
| Name | Austin Digital Assessment - Aggregated Responses by Geography |
| Attribution | City of Austin Office of Telecommunications & Regulatory Affairs |
| Category | Workforce Development |
| Tags | technology, digitalinclusion, public access, training, literacy, online.community |
| Created | 2015-07-10T18:52:50Z |
| Publication Date | 2015-07-10T18:58:01Z |

## Description

The 2014 Austin Digital Assessment Project was supported by the Telecommunications & Regulatory Affairs Office of the City of Austin, the Telecommunications and Information Policy Institute at the University of Texas, and faculty and graduate students from the Department of Radio, Television, and Film and the University of Texas. This dataset includes the individual survey responses. To see aggregated dataset weighted to reflect Austin demographics, refer to the attached document

## Columns

```ls
| Included | Schema Type    | Field Name                                                                    | Name                                                                             | Data Type | Render Type |
| ======== | ============== | ============================================================================= | ================================================================================ | ========= | =========== |
| No       | time           | :updated_at                                                                   | updated_at                                                                       | meta_data | meta_data   |
| Yes      | series tag     | zipcode_council_district                                                      | ZIPCODE/COUNCIL DISTRICT                                                         | text      | text        |
| Yes      | numeric metric | internet_users                                                                | INTERNET USERS                                                                   | percent   | percent     |
| Yes      | numeric metric | internet_non_users                                                            | INTERNET NON-USERS                                                               | percent   | percent     |
| Yes      | numeric metric | home_internet_access                                                          | HOME INTERNET ACCESS                                                             | percent   | percent     |
| Yes      | numeric metric | smartphone_usage_rates                                                        | SMARTPHONE USAGE RATES                                                           | percent   | percent     |
| Yes      | numeric metric | pc_laptop_and_or_desktop_ownership                                            | PC (LAPTOP AND/OR DESKTOP) OWNERSHIP                                             | percent   | percent     |
| Yes      | numeric metric | non_users_reasons_for_not_using_the_internet_expense                          | NON-USERS - Reasons for not using the internet: EXPENSE                          | percent   | percent     |
| Yes      | numeric metric | non_users_reasons_for_not_using_the_internet_privacy_concerns                 | NON-USERS - Reasons for not using the internet: PRIVACY CONCERNS                 | percent   | percent     |
| Yes      | numeric metric | non_users_reasons_for_not_using_the_internet_not_interested                   | NON-USERS - Reasons for not using the internet: NOT INTERESTED                   | percent   | percent     |
| Yes      | numeric metric | non_users_reasons_for_not_using_the_internet_no_one_to_teach_me               | NON-USERS - Reasons for not using the internet: NO ONE TO TEACH ME               | percent   | percent     |
| No       |                | non_users_reasons_for_not_using_the_internet_not_enough_time                  | NON-USERS - Reasons for not using the internet: NOT ENOUGH TIME                  | percent   | percent     |
| Yes      | numeric metric | non_users_reasons_for_not_using_the_internet_too_difficult                    | NON-USERS - Reasons for not using the internet: TOO DIFFICULT                    | percent   | percent     |
| Yes      | numeric metric | non_users_reasons_for_not_using_the_internet_someone_uses_internet_for_me     | NON-USERS - Reasons for not using the internet: SOMEONE USES INTERNET FOR ME     | percent   | percent     |
| Yes      | numeric metric | non_users_reasons_for_not_using_the_internet_do_not_speak_english_well_enough | NON-USERS - Reasons for not using the internet: DO NOT SPEAK ENGLISH WELL ENOUGH | percent   | percent     |
| Yes      | numeric metric | non_users_help_with_technology_i_know_enough_to_go_online_on_my_own           | NON-USERS - Help with Technology: I know enough to go online on my own           | percent   | percent     |
| Yes      | numeric metric | non_users_help_with_technology_i_would_need_someone_to_help_me                | NON-USERS - Help with Technology: I would need someone to help me                | percent   | percent     |
| Yes      | numeric metric | non_users_help_with_technology_i_would_not_want_to_start_using_the_internet   | NON-USERS - Help with Technology: I would not want to start using the Internet   | percent   | percent     |
| Yes      | numeric metric | non_users_interested_in_free_training_yes                                     | NON-USERS - Interested in Free Training: YES                                     | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = non_users_reasons_for_not_using_the_internet_not_enough_time
```

## Data Commands

```ls
series e:xf72-sbj4 d:2015-07-10T11:53:21.000Z t:zipcode_council_district=78617 m:non_users_reasons_for_not_using_the_internet_someone_uses_internet_for_me=86 m:non_users_interested_in_free_training_yes=13 m:internet_users=88 m:non_users_reasons_for_not_using_the_internet_too_difficult=13 m:internet_non_users=13 m:non_users_reasons_for_not_using_the_internet_not_interested=88 m:non_users_reasons_for_not_using_the_internet_privacy_concerns=100 m:non_users_help_with_technology_i_would_need_someone_to_help_me=13 m:home_internet_access=65 m:pc_laptop_and_or_desktop_ownership=69 m:smartphone_usage_rates=73 m:non_users_reasons_for_not_using_the_internet_no_one_to_teach_me=13 m:non_users_reasons_for_not_using_the_internet_do_not_speak_english_well_enough=0 m:non_users_reasons_for_not_using_the_internet_expense=88 m:non_users_help_with_technology_i_know_enough_to_go_online_on_my_own=13 m:non_users_help_with_technology_i_would_not_want_to_start_using_the_internet=75

series e:xf72-sbj4 d:2015-07-10T11:53:21.000Z t:zipcode_council_district=78701 m:non_users_reasons_for_not_using_the_internet_someone_uses_internet_for_me=0 m:non_users_interested_in_free_training_yes=0 m:internet_users=100 m:non_users_reasons_for_not_using_the_internet_too_difficult=0 m:internet_non_users=0 m:non_users_reasons_for_not_using_the_internet_not_interested=0 m:non_users_reasons_for_not_using_the_internet_privacy_concerns=0 m:non_users_help_with_technology_i_would_need_someone_to_help_me=0 m:home_internet_access=100 m:pc_laptop_and_or_desktop_ownership=100 m:smartphone_usage_rates=82 m:non_users_reasons_for_not_using_the_internet_no_one_to_teach_me=0 m:non_users_reasons_for_not_using_the_internet_do_not_speak_english_well_enough=0 m:non_users_reasons_for_not_using_the_internet_expense=0 m:non_users_help_with_technology_i_know_enough_to_go_online_on_my_own=100 m:non_users_help_with_technology_i_would_not_want_to_start_using_the_internet=0

series e:xf72-sbj4 d:2015-07-10T11:53:21.000Z t:zipcode_council_district=78702 m:non_users_reasons_for_not_using_the_internet_someone_uses_internet_for_me=39 m:non_users_interested_in_free_training_yes=17 m:internet_users=80 m:non_users_reasons_for_not_using_the_internet_too_difficult=0 m:internet_non_users=20 m:non_users_reasons_for_not_using_the_internet_not_interested=50 m:non_users_reasons_for_not_using_the_internet_privacy_concerns=42 m:non_users_help_with_technology_i_would_need_someone_to_help_me=58 m:home_internet_access=81 m:pc_laptop_and_or_desktop_ownership=73 m:smartphone_usage_rates=83 m:non_users_reasons_for_not_using_the_internet_no_one_to_teach_me=0 m:non_users_reasons_for_not_using_the_internet_do_not_speak_english_well_enough=0 m:non_users_reasons_for_not_using_the_internet_expense=17 m:non_users_help_with_technology_i_know_enough_to_go_online_on_my_own=0 m:non_users_help_with_technology_i_would_not_want_to_start_using_the_internet=42
```

## Meta Commands

```ls
metric m:internet_users p:integer l:"INTERNET USERS" t:dataTypeName=percent

metric m:internet_non_users p:integer l:"INTERNET NON-USERS" t:dataTypeName=percent

metric m:home_internet_access p:integer l:"HOME INTERNET ACCESS" t:dataTypeName=percent

metric m:smartphone_usage_rates p:integer l:"SMARTPHONE USAGE RATES" t:dataTypeName=percent

metric m:pc_laptop_and_or_desktop_ownership p:integer l:"PC (LAPTOP AND/OR DESKTOP) OWNERSHIP" t:dataTypeName=percent

metric m:non_users_reasons_for_not_using_the_internet_expense p:integer l:"NON-USERS - Reasons for not using the internet: EXPENSE" t:dataTypeName=percent

metric m:non_users_reasons_for_not_using_the_internet_privacy_concerns p:integer l:"NON-USERS - Reasons for not using the internet: PRIVACY CONCERNS" t:dataTypeName=percent

metric m:non_users_reasons_for_not_using_the_internet_not_interested p:integer l:"NON-USERS - Reasons for not using the internet: NOT INTERESTED" t:dataTypeName=percent

metric m:non_users_reasons_for_not_using_the_internet_no_one_to_teach_me p:integer l:"NON-USERS - Reasons for not using the internet: NO ONE TO TEACH ME" t:dataTypeName=percent

metric m:non_users_reasons_for_not_using_the_internet_too_difficult p:integer l:"NON-USERS - Reasons for not using the internet: TOO DIFFICULT" t:dataTypeName=percent

metric m:non_users_reasons_for_not_using_the_internet_someone_uses_internet_for_me p:integer l:"NON-USERS - Reasons for not using the internet: SOMEONE USES INTERNET FOR ME" t:dataTypeName=percent

metric m:non_users_reasons_for_not_using_the_internet_do_not_speak_english_well_enough p:integer l:"NON-USERS - Reasons for not using the internet: DO NOT SPEAK ENGLISH WELL ENOUGH" t:dataTypeName=percent

metric m:non_users_help_with_technology_i_know_enough_to_go_online_on_my_own p:integer l:"NON-USERS - Help with Technology: I know enough to go online on my own" t:dataTypeName=percent

metric m:non_users_help_with_technology_i_would_need_someone_to_help_me p:integer l:"NON-USERS - Help with Technology: I would need someone to help me" t:dataTypeName=percent

metric m:non_users_help_with_technology_i_would_not_want_to_start_using_the_internet p:integer l:"NON-USERS - Help with Technology: I would not want to start using the Internet" t:dataTypeName=percent

metric m:non_users_interested_in_free_training_yes p:integer l:"NON-USERS - Interested in Free Training: YES" t:dataTypeName=percent

entity e:xf72-sbj4 l:"Austin Digital Assessment - Aggregated Responses by Geography" t:attribution="City of Austin Office of Telecommunications & Regulatory Affairs" t:url=https://data.austintexas.gov/api/views/xf72-sbj4

property e:xf72-sbj4 t:meta.view v:id=xf72-sbj4 v:category="Workforce Development" v:attributionLink=http://austintexas.gov/digitalinclusion v:averageRating=0 v:name="Austin Digital Assessment - Aggregated Responses by Geography" v:attribution="City of Austin Office of Telecommunications & Regulatory Affairs"

property e:xf72-sbj4 t:meta.view.license v:name="Public Domain"

property e:xf72-sbj4 t:meta.view.owner v:id=yczp-v4p4 v:screenName="Sharla Chamberlain" v:displayName="Sharla Chamberlain"

property e:xf72-sbj4 t:meta.view.tableauthor v:id=yczp-v4p4 v:screenName="Sharla Chamberlain" v:roleName=editor v:displayName="Sharla Chamberlain"
```

## Top Records

```ls
| :updated_at | zipcode_council_district | internet_users | internet_non_users | home_internet_access | smartphone_usage_rates | pc_laptop_and_or_desktop_ownership | non_users_reasons_for_not_using_the_internet_expense | non_users_reasons_for_not_using_the_internet_privacy_concerns | non_users_reasons_for_not_using_the_internet_not_interested | non_users_reasons_for_not_using_the_internet_no_one_to_teach_me | non_users_reasons_for_not_using_the_internet_not_enough_time | non_users_reasons_for_not_using_the_internet_too_difficult | non_users_reasons_for_not_using_the_internet_someone_uses_internet_for_me | non_users_reasons_for_not_using_the_internet_do_not_speak_english_well_enough | non_users_help_with_technology_i_know_enough_to_go_online_on_my_own | non_users_help_with_technology_i_would_need_someone_to_help_me | non_users_help_with_technology_i_would_not_want_to_start_using_the_internet | non_users_interested_in_free_training_yes | 
| =========== | ======================== | ============== | ================== | ==================== | ====================== | ================================== | ==================================================== | ============================================================= | =========================================================== | =============================================================== | ============================================================ | ========================================================== | ========================================================================= | ============================================================================= | =================================================================== | ============================================================== | =========================================================================== | ========================================= | 
| 1436529201  | 78617                    | 88             | 13                 | 65                   | 73                     | 69                                 | 88                                                   | 100                                                           | 88                                                          | 13                                                              | 100                                                          | 13                                                         | 86                                                                        | 0                                                                             | 13                                                                  | 13                                                             | 75                                                                          | 13                                        | 
| 1436529201  | 78701                    | 100            | 0                  | 100                  | 82                     | 100                                | 0                                                    | 0                                                             | 0                                                           | 0                                                               | 100                                                          | 0                                                          | 0                                                                         | 0                                                                             | 100                                                                 | 0                                                              | 0                                                                           | 0                                         | 
| 1436529201  | 78702                    | 80             | 20                 | 81                   | 83                     | 73                                 | 17                                                   | 42                                                            | 50                                                          | 0                                                               | 0                                                            | 0                                                          | 39                                                                        | 0                                                                             | 0                                                                   | 58                                                             | 42                                                                          | 17                                        | 
| 1436529201  | 78703                    | 94             | 6                  | 100                  | 91                     | 100                                |                                                      |                                                               |                                                             |                                                                 |                                                              |                                                            |                                                                           |                                                                               |                                                                     |                                                                |                                                                             |                                           | 
| 1436529201  | 78704                    | 99             | 1                  | 94                   | 95                     | 99                                 | 0                                                    | 86                                                            | 83                                                          | 83                                                              | 0                                                            | 86                                                         | 83                                                                        | 71                                                                            | 14                                                                  | 71                                                             | 14                                                                          | 83                                        | 
| 1436529201  | 78705                    | 100            | 0                  | 100                  | 100                    | 100                                |                                                      |                                                               |                                                             |                                                                 |                                                              |                                                            |                                                                           |                                                                               |                                                                     |                                                                |                                                                             |                                           | 
| 1436529201  | 78717                    | 100            | 0                  | 100                  | 90                     | 100                                | 0                                                    | 100                                                           | 0                                                           | 0                                                               | 0                                                            | 0                                                          | 0                                                                         | 0                                                                             | 100                                                                 | 0                                                              | 0                                                                           | 100                                       | 
| 1436529201  | 78721                    | 76             | 24                 | 88                   | 52                     | 88                                 | 100                                                  | 100                                                           | 0                                                           | 0                                                               | 0                                                            | 0                                                          | 0                                                                         | 0                                                                             | 0                                                                   | 100                                                            | 0                                                                           | 100                                       | 
| 1436529201  | 78722                    | 100            | 0                  | 100                  | 88                     | 100                                |                                                      |                                                               |                                                             |                                                                 |                                                              |                                                            |                                                                           |                                                                               | 100                                                                 | 0                                                              | 0                                                                           |                                           | 
| 1436529201  | 78723                    | 93             | 7                  | 92                   | 85                     | 94                                 | 63                                                   | 82                                                            | 55                                                          | 70                                                              | 30                                                           | 36                                                         | 73                                                                        | 27                                                                            | 18                                                                  | 9                                                              | 73                                                                          | 36                                        | 
```