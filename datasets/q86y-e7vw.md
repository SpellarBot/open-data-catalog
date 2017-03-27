# Proposed One- Day- Per- Week Watering Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proposed-one-day-per-week-watering-schedule) |
| Metadata | [Link](https://data.austintexas.gov/api/views/q86y-e7vw) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/q86y-e7vw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/q86y-e7vw/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | q86y-e7vw |
| Name | Proposed One- Day- Per- Week Watering Schedule |
| Category | Utility |
| Created | 2016-02-11T18:08:35Z |
| Publication Date | 2016-02-11T19:03:27Z |

## Description

These are the results of a survey hosted on SpeakUpAustin.org and commissioned by the Austin Water Utility regarding proposed changes to watering restrictions, including permanent once-a-week watering limits.  In total, some 1,854 users took the survey over a two month period.

## Columns

```ls
| Included | Schema Type | Field Name                                                                                        | Name                                                                                               | Data Type | Render Type |
| ======== | =========== | ================================================================================================= | ================================================================================================== | ========= | =========== |
| No       | time        | :updated_at                                                                                       | updated_at                                                                                         | meta_data | meta_data   |
| Yes      | series tag  | what_is_your_current_residential_zip_code                                                         | What is your current residential zip code?                                                         | text      | text        |
| Yes      | series tag  | what_council_district_do_you_reside_in                                                            | What Council District do you reside in?                                                            | text      | number      |
| Yes      | series tag  | what_is_your_ethnic_background                                                                    | What is your ethnic background?                                                                    | text      | text        |
| Yes      | series tag  | one_day_per_week_watering_is_enough_for_my_needs                                                  | One day per week watering is enough for my needs.                                                  | text      | text        |
| Yes      | series tag  | i_support_a_permanent_one_day_per_week_watering_schedule_to_conserve_the_regions_water_supply     | I support a permanent one day per week watering schedule to conserve the regions water supply.     | text      | text        |
| Yes      | series tag  | one_day_per_week_watering_has_negatively_affected_me_my_family                                    | One day per week watering has negatively affected me/my family.                                    | text      | text        |
| Yes      | series tag  | i_have_made_landscaping_changes_because_of_watering_restrictions_drought                          | I have made landscaping changes because of watering restrictions/drought.                          | text      | text        |
| Yes      | series tag  | i_have_made_irrigation_system_repairs_or_upgrades_because_of_watering_restrictions                | I have made irrigation system repairs or upgrades because of watering restrictions.                | text      | text        |
| Yes      | series tag  | one_day_per_week_watering_has_negatively_affected_my_business                                     | One day per week watering has negatively affected my business.                                     | text      | text        |
| Yes      | series tag  | i_would_support_permanent_year_round_one_day_per_week_watering_restrictions                       | I would support permanent year round one day per week watering restrictions.                       | text      | text        |
| Yes      | series tag  | i_would_support_seasonal_one_day_per_week_watering_restrictions                                   | I would support seasonal one day per week watering restrictions.                                   | text      | text        |
| Yes      | series tag  | i_would_support_permanent_one_day_per_week_watering_if_other_restrictions_were_loosened_or_lifted | I would support permanent one day per week watering if other restrictions were loosened or lifted. | text      | text        |
| Yes      | series tag  | i_would_support_looser_restrictions_on_at_home_car_washing                                        | I would support looser restrictions on at home car washing.                                        | text      | text        |
| Yes      | series tag  | i_would_support_looser_restrictions_on_ornamental_fountains                                       | I would support looser restrictions on ornamental fountains.                                       | text      | text        |
| Yes      | series tag  | i_would_support_looser_restrictions_on_patio_misters                                              | I would support looser restrictions on patio misters.                                              | text      | text        |
| Yes      | series tag  | i_would_support_looser_restrictions_on_hose_end_sprinklers                                        | I would support looser restrictions on hose end sprinklers.                                        | text      | text        |
| Yes      | series tag  | i_would_support_looser_restrictions_on_pressure_washing                                           | I would support looser restrictions on pressure washing.                                           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q86y-e7vw d:2016-02-11T10:08:43.000Z t:what_council_district_do_you_reside_in=10 t:what_is_your_current_residential_zip_code=78731 m:row_number.q86y-e7vw=1

series e:q86y-e7vw d:2016-02-11T10:08:45.000Z t:what_council_district_do_you_reside_in=6 t:what_is_your_ethnic_background=white-caucasian t:what_is_your_current_residential_zip_code=78729 m:row_number.q86y-e7vw=2

series e:q86y-e7vw d:2016-02-11T10:08:45.000Z t:what_council_district_do_you_reside_in=6 t:what_is_your_ethnic_background=white-caucasian t:what_is_your_current_residential_zip_code=78732 m:row_number.q86y-e7vw=3
```

## Meta Commands

```ls
metric m:row_number.q86y-e7vw p:long l:"Row Number"

entity e:q86y-e7vw l:"Proposed One- Day- Per- Week Watering Schedule" t:url=https://data.austintexas.gov/api/views/q86y-e7vw

property e:q86y-e7vw t:meta.view v:id=q86y-e7vw v:category=Utility v:averageRating=0 v:name="Proposed One- Day- Per- Week Watering Schedule"

property e:q86y-e7vw t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:displayName=AustinGo

property e:q86y-e7vw t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```