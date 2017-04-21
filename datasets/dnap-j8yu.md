# Competitiveness Metrics for Washington's Economy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/competitiveness-metrics-for-washingtons-economy-2bbe9) |
| Metadata | [Link](https://data.wa.gov/api/views/dnap-j8yu) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dnap-j8yu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dnap-j8yu/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dnap-j8yu |
| Name | Competitiveness Metrics for Washington's Economy |
| Category | Economics |
| Tags | commerce, competitiveness |
| Created | 2013-11-15T22:00:04Z |
| Publication Date | 2013-12-02T18:06:27Z |

## Description

A summary of how Washington's economic competiticeness has been assessed by third party studies since 2007

## Columns

```ls
| Included | Schema Type    | Field Name                                                          | Name                                                                | Data Type | Render Type |
| ======== | ============== | =================================================================== | =================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                         | updated_at                                                          | meta_data | meta_data   |
| Yes      | series tag     | study                                                               | Study                                                               | text      | text        |
| Yes      | series tag     | metric                                                              | Metric                                                              | text      | text        |
| Yes      | series tag     | metric_area_our_categorization                                      | Metric Area (our categorization)                                    | text      | text        |
| Yes      | numeric metric | 2007_score                                                          | 2007 Score                                                          | number    | number      |
| Yes      | numeric metric | 2008_score                                                          | 2008 Score                                                          | number    | number      |
| Yes      | numeric metric | 2009_score                                                          | 2009 Score                                                          | number    | number      |
| Yes      | numeric metric | 2010_score                                                          | 2010 Score                                                          | number    | number      |
| Yes      | numeric metric | 2011_score                                                          | 2011 Score                                                          | number    | number      |
| Yes      | numeric metric | 2012_score                                                          | 2012 Score                                                          | number    | number      |
| Yes      | numeric metric | 2013_score                                                          | 2013 Score                                                          | number    | number      |
| Yes      | numeric metric | 2007_rank                                                           | 2007 Rank                                                           | number    | number      |
| Yes      | numeric metric | 2008_rank                                                           | 2008 Rank                                                           | number    | number      |
| Yes      | numeric metric | 2009_rank                                                           | 2009 Rank                                                           | number    | number      |
| Yes      | numeric metric | 2010_rank                                                           | 2010 Rank                                                           | number    | number      |
| Yes      | numeric metric | 2011_rank                                                           | 2011 Rank                                                           | number    | number      |
| Yes      | numeric metric | 2012_rank                                                           | 2012 Rank                                                           | number    | number      |
| Yes      | numeric metric | 2013_rank                                                           | 2013 Rank                                                           | number    | number      |
| Yes      | numeric metric | 2014_rank                                                           | 2014 Rank                                                           | number    | number      |
| Yes      | numeric metric | 2015_rank                                                           | 2015 Rank                                                           | number    | number      |
| Yes      | numeric metric | years_ranked                                                        | Years ranked                                                        | number    | number      |
| Yes      | numeric metric | initial_rank                                                        | Initial rank                                                        | number    | number      |
| Yes      | numeric metric | previous_rank                                                       | Previous rank                                                       | number    | number      |
| No       |                | latest_rank                                                         | Latest rank                                                         | number    | number      |
| Yes      | numeric metric | change_from_initial_rank                                            | Change from initial rank                                            | number    | number      |
| Yes      | numeric metric | change_from_previous_rank                                           | Change from previous rank                                           | number    | number      |
| Yes      | numeric metric | change_compared_to_average_rank_all_years                           | Change compared to average rank (all years)                         | number    | number      |
| Yes      | numeric metric | top_third                                                           | Top third                                                           | number    | number      |
| Yes      | numeric metric | middle_third                                                        | Middle third                                                        | number    | number      |
| Yes      | numeric metric | bottom_third                                                        | Bottom third                                                        | number    | number      |
| Yes      | numeric metric | second_latest_rank                                                  | Second latest rank                                                  | number    | number      |
| Yes      | numeric metric | most_recent_rank_current_metrics                                    | Most Recent Rank (current metrics)                                  | number    | number      |
| Yes      | numeric metric | change_in_rank_from_last_report                                     | Change in rank from last report                                     | number    | number      |
| Yes      | numeric metric | change_in_rank_from_last_report_two_years_ago_to_one_year_ago       | Change in rank from last report (two years ago to one year ago)     | number    | number      |
| Yes      | numeric metric | change_in_rank_from_last_report_three_years_ago_to_two_years_ago    | Change in rank from last report (three years ago to two years ago)  | number    | number      |
| Yes      | numeric metric | change_in_rank_from_last_report_four_years_ago_to_three_years_ago   | Change in rank from last report (four years ago to three years ago) | number    | number      |
| Yes      | numeric metric | two_year_change_in_rank                                             | Two year change in rank                                             | number    | number      |
| Yes      | numeric metric | four_year_change_in_rank                                            | Four year change in rank                                            | number    | number      |
| Yes      | numeric metric | gain_in_rank                                                        | Gain in rank                                                        | number    | number      |
| Yes      | numeric metric | loss_in_rank                                                        | Loss in rank                                                        | number    | number      |
| Yes      | numeric metric | change_in_rank                                                      | Change in rank                                                      | number    | number      |
| Yes      | numeric metric | tier                                                                | Tier                                                                | number    | number      |
| Yes      | series tag     | white_paper_subjects_related_to                                     | White Paper Subjects related to                                     | text      | text        |
| Yes      | numeric metric | variance                                                            | Variance                                                            | number    | number      |
| Yes      | numeric metric | std_dev                                                             | Std Dev                                                             | number    | number      |
| Yes      | numeric metric | 2009_2010                                                           | 2009-2010                                                           | number    | number      |
| Yes      | numeric metric | 2010_2011                                                           | 2010-2011                                                           | number    | number      |
| Yes      | numeric metric | 2011_2012                                                           | 2011-2012                                                           | number    | number      |
| Yes      | numeric metric | average_absolute_change_in_overall_rankings_2009_2010_and_2010_2011 | average absolute change in overall rankings 2009-2010 and 2010-2011 | number    | number      |
| Yes      | numeric metric | average_absolute_change_in_overall_rankings_2010_2011_and_2011_2012 | average absolute change in overall rankings 2010-2011 and 2011-2012 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latest_rank
```

## Data Commands

```ls
series e:dnap-j8yu d:2013-11-15T14:00:30.000Z t:metric_area_our_categorization="Cost of doing business" t:metric="% of labor force that is represented by unions" t:study="Beacon Hill" t:white_paper_subjects_related_to="Competitiveness Study (Jobs Agenda)" m:std_dev=0 m:previous_rank=47 m:change_in_rank_from_last_report_three_years_ago_to_two_years_ago=0 m:2011_rank=47 m:2009_rank=47 m:tier=-1 m:change_in_rank_from_last_report=0 m:2010_2011=0 m:change_in_rank_from_last_report_two_years_ago_to_one_year_ago=0 m:change_from_previous_rank=0 m:average_absolute_change_in_overall_rankings_2009_2010_and_2010_2011=0 m:2010_score=3.49 m:2009_score=3.48 m:2008_rank=47 m:gain_in_rank=0 m:four_year_change_in_rank=-1 m:2012_rank=47 m:change_in_rank=0 m:2008_score=3.38 m:average_absolute_change_in_overall_rankings_2010_2011_and_2011_2012=0 m:2010_rank=47 m:middle_third=0 m:years_ranked=6 m:2011_score=3.35 m:2007_rank=46 m:variance=0 m:two_year_change_in_rank=0 m:loss_in_rank=0 m:change_in_rank_from_last_report_four_years_ago_to_three_years_ago=-1 m:2009_2010=0 m:most_recent_rank_current_metrics=47 m:bottom_third=1 m:2011_2012=0 m:2007_score=3.45 m:change_compared_to_average_rank_all_years=0 m:change_from_initial_rank=-1 m:top_third=0 m:initial_rank=46

series e:dnap-j8yu d:2013-11-15T14:00:30.000Z t:metric_area_our_categorization=Education t:metric="% of population aged 25 and over that graduated fromhigh school" t:study="Beacon Hill" m:std_dev=1.118033988749895 m:previous_rank=14 m:change_in_rank_from_last_report_three_years_ago_to_two_years_ago=-1 m:2011_rank=14 m:2009_rank=13 m:tier=1 m:change_in_rank_from_last_report=1 m:2010_2011=1 m:change_in_rank_from_last_report_two_years_ago_to_one_year_ago=-2 m:change_from_previous_rank=-2 m:average_absolute_change_in_overall_rankings_2009_2010_and_2010_2011=1.5 m:2010_score=5.82 m:2009_score=5.85 m:2008_rank=12 m:gain_in_rank=1 m:four_year_change_in_rank=-5 m:2012_rank=16 m:change_in_rank=1 m:2008_score=5.9 m:2010_rank=15 m:middle_third=0 m:years_ranked=6 m:2011_score=5.81 m:2007_rank=9 m:variance=1 m:two_year_change_in_rank=-1 m:loss_in_rank=0 m:change_in_rank_from_last_report_four_years_ago_to_three_years_ago=-3 m:2009_2010=2 m:most_recent_rank_current_metrics=14 m:bottom_third=0 m:2011_2012=2 m:2007_score=5.96 m:change_compared_to_average_rank_all_years=-3 m:change_from_initial_rank=-7 m:top_third=1 m:initial_rank=9

series e:dnap-j8yu d:2013-11-15T14:00:30.000Z t:metric_area_our_categorization=Workforce t:metric="% of population born abroad" t:study="Beacon Hill" m:std_dev=0.5 m:previous_rank=13 m:change_in_rank_from_last_report_three_years_ago_to_two_years_ago=1 m:2011_rank=13 m:2009_rank=13 m:tier=1 m:change_in_rank_from_last_report=1 m:2010_2011=1 m:change_in_rank_from_last_report_two_years_ago_to_one_year_ago=-1 m:change_from_previous_rank=-1 m:average_absolute_change_in_overall_rankings_2009_2010_and_2010_2011=1 m:2010_score=5.63 m:2009_score=5.66 m:2008_rank=14 m:gain_in_rank=1 m:four_year_change_in_rank=0 m:2012_rank=14 m:change_in_rank=1 m:2008_score=5.64 m:2010_rank=14 m:middle_third=0 m:years_ranked=6 m:2011_score=5.72 m:2007_rank=13 m:variance=0.3333333333333333 m:two_year_change_in_rank=0 m:loss_in_rank=0 m:change_in_rank_from_last_report_four_years_ago_to_three_years_ago=-1 m:2009_2010=1 m:most_recent_rank_current_metrics=13 m:bottom_third=0 m:2011_2012=1 m:2007_score=5.67 m:change_compared_to_average_rank_all_years=-1 m:change_from_initial_rank=-1 m:top_third=1 m:initial_rank=13
```

## Meta Commands

```ls
metric m:2007_score p:double l:"2007 Score" t:dataTypeName=number

metric m:2008_score p:double l:"2008 Score" t:dataTypeName=number

metric m:2009_score p:double l:"2009 Score" t:dataTypeName=number

metric m:2010_score p:double l:"2010 Score" t:dataTypeName=number

metric m:2011_score p:double l:"2011 Score" t:dataTypeName=number

metric m:2012_score p:double l:"2012 Score" t:dataTypeName=number

metric m:2013_score p:double l:"2013 Score" t:dataTypeName=number

metric m:2007_rank p:integer l:"2007 Rank" t:dataTypeName=number

metric m:2008_rank p:integer l:"2008 Rank" t:dataTypeName=number

metric m:2009_rank p:integer l:"2009 Rank" t:dataTypeName=number

metric m:2010_rank p:integer l:"2010 Rank" t:dataTypeName=number

metric m:2011_rank p:integer l:"2011 Rank" t:dataTypeName=number

metric m:2012_rank p:integer l:"2012 Rank" t:dataTypeName=number

metric m:2013_rank p:integer l:"2013 Rank" t:dataTypeName=number

metric m:2014_rank p:integer l:"2014 Rank" t:dataTypeName=number

metric m:2015_rank p:long l:"2015 Rank" t:dataTypeName=number

metric m:years_ranked p:integer l:"Years ranked" t:dataTypeName=number

metric m:initial_rank p:integer l:"Initial rank" t:dataTypeName=number

metric m:previous_rank p:integer l:"Previous rank" t:dataTypeName=number

metric m:change_from_initial_rank p:integer l:"Change from initial rank" t:dataTypeName=number

metric m:change_from_previous_rank p:integer l:"Change from previous rank" t:dataTypeName=number

metric m:change_compared_to_average_rank_all_years p:integer l:"Change compared to average rank (all years)" t:dataTypeName=number

metric m:top_third p:integer l:"Top third" t:dataTypeName=number

metric m:middle_third p:integer l:"Middle third" t:dataTypeName=number

metric m:bottom_third p:integer l:"Bottom third" t:dataTypeName=number

metric m:second_latest_rank p:integer l:"Second latest rank" t:dataTypeName=number

metric m:most_recent_rank_current_metrics p:integer l:"Most Recent Rank (current metrics)" t:dataTypeName=number

metric m:change_in_rank_from_last_report p:integer l:"Change in rank from last report" t:dataTypeName=number

metric m:change_in_rank_from_last_report_two_years_ago_to_one_year_ago p:integer l:"Change in rank from last report (two years ago to one year ago)" t:dataTypeName=number

metric m:change_in_rank_from_last_report_three_years_ago_to_two_years_ago p:integer l:"Change in rank from last report (three years ago to two years ago)" t:dataTypeName=number

metric m:change_in_rank_from_last_report_four_years_ago_to_three_years_ago p:integer l:"Change in rank from last report (four years ago to three years ago)" t:dataTypeName=number

metric m:two_year_change_in_rank p:integer l:"Two year change in rank" t:dataTypeName=number

metric m:four_year_change_in_rank p:integer l:"Four year change in rank" t:dataTypeName=number

metric m:gain_in_rank p:integer l:"Gain in rank" t:dataTypeName=number

metric m:loss_in_rank p:integer l:"Loss in rank" t:dataTypeName=number

metric m:change_in_rank p:integer l:"Change in rank" t:dataTypeName=number

metric m:tier p:integer l:Tier t:dataTypeName=number

metric m:variance p:double l:Variance t:dataTypeName=number

metric m:std_dev p:double l:"Std Dev" t:dataTypeName=number

metric m:2009_2010 p:integer l:2009-2010 t:dataTypeName=number

metric m:2010_2011 p:integer l:2010-2011 t:dataTypeName=number

metric m:2011_2012 p:integer l:2011-2012 t:dataTypeName=number

metric m:average_absolute_change_in_overall_rankings_2009_2010_and_2010_2011 p:double l:"average absolute change in overall rankings 2009-2010 and 2010-2011" t:dataTypeName=number

metric m:average_absolute_change_in_overall_rankings_2010_2011_and_2011_2012 p:float l:"average absolute change in overall rankings 2010-2011 and 2011-2012" t:dataTypeName=number

entity e:dnap-j8yu l:"Competitiveness Metrics for Washington's Economy" t:url=https://data.wa.gov/api/views/dnap-j8yu

property e:dnap-j8yu t:meta.view v:id=dnap-j8yu v:category=Economics v:averageRating=0 v:name="Competitiveness Metrics for Washington's Economy"

property e:dnap-j8yu t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:dnap-j8yu t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | study       | metric                                                                        | metric_area_our_categorization  | 2007_score | 2008_score | 2009_score         | 2010_score         | 2011_score         | 2012_score | 2013_score | 2007_rank | 2008_rank | 2009_rank | 2010_rank | 2011_rank | 2012_rank | 2013_rank | 2014_rank | 2015_rank | years_ranked | initial_rank | previous_rank | latest_rank | change_from_initial_rank | change_from_previous_rank | change_compared_to_average_rank_all_years | top_third | middle_third | bottom_third | second_latest_rank | most_recent_rank_current_metrics | change_in_rank_from_last_report | change_in_rank_from_last_report_two_years_ago_to_one_year_ago | change_in_rank_from_last_report_three_years_ago_to_two_years_ago | change_in_rank_from_last_report_four_years_ago_to_three_years_ago | two_year_change_in_rank | four_year_change_in_rank | gain_in_rank | loss_in_rank | change_in_rank | tier | white_paper_subjects_related_to     | variance            | std_dev            | 2009_2010 | 2010_2011 | 2011_2012 | average_absolute_change_in_overall_rankings_2009_2010_and_2010_2011 | average_absolute_change_in_overall_rankings_2010_2011_and_2011_2012 | 
| =========== | =========== | ============================================================================= | =============================== | ========== | ========== | ================== | ================== | ================== | ========== | ========== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ============ | ============ | ============= | =========== | ======================== | ========================= | ========================================= | ========= | ============ | ============ | ================== | ================================ | =============================== | ============================================================= | ================================================================ | ================================================================= | ======================= | ======================== | ============ | ============ | ============== | ==== | =================================== | =================== | ================== | ========= | ========= | ========= | =================================================================== | =================================================================== | 
| 1384524030  | Beacon Hill | % of labor force that is represented by unions                                | Cost of doing business          | 3.45       | 3.38       | 3.48               | 3.49               | 3.35               |            |            | 46        | 47        | 47        | 47        | 47        | 47        |           |           |           | 6            | 46           | 47            | 47          | -1                       | 0                         | 0                                         | 0         | 0            | 1            |                    | 47                               | 0                               | 0                                                             | 0                                                                | -1                                                                | 0                       | -1                       | 0            | 0            | 0              | -1   | Competitiveness Study (Jobs Agenda) | 0                   | 0                  | 0         | 0         | 0         | 0                                                                   | 0                                                                   | 
| 1384524030  | Beacon Hill | % of population aged 25 and over that graduated fromhigh school               | Education                       | 5.96       | 5.9        | 5.85               | 5.82               | 5.81               |            |            | 9         | 12        | 13        | 15        | 14        | 16        |           |           |           | 6            | 9            | 14            | 16          | -7                       | -2                        | -3                                        | 1         | 0            | 0            |                    | 14                               | 1                               | -2                                                            | -1                                                               | -3                                                                | -1                      | -5                       | 1            | 0            | 1              | 1    |                                     | 1                   | 1.1180339887498949 | 2         | 1         | 2         | 1.5                                                                 |                                                                     | 
| 1384524030  | Beacon Hill | % of population born abroad                                                   | Workforce                       | 5.67       | 5.64       | 5.66               | 5.63               | 5.72               |            |            | 13        | 14        | 13        | 14        | 13        | 14        |           |           |           | 6            | 13           | 13            | 14          | -1                       | -1                        | -1                                        | 1         | 0            | 0            |                    | 13                               | 1                               | -1                                                            | 1                                                                | -1                                                                | 0                       | 0                        | 1            | 0            | 1              | 1    |                                     | 0.33333333333333331 | 0.5                | 1         | 1         | 1         | 1                                                                   |                                                                     | 
| 1384524030  | Beacon Hill | % of population enrolled in degree-granting institutions                      | Education                       |            |            | 4.4400000000000004 | 4.43               | 4.4000000000000004 |            |            |           |           | 32        | 32        | 34        | 45        |           |           |           | 4            | 32           | 34            | 45          | -13                      | -11                       | -9                                        | 0         | 0            | 1            |                    | 34                               | -2                              | 0                                                             |                                                                  |                                                                   | -2                      |                          | 0            | -1           | -1             | -1   | Competitiveness Study (Jobs Agenda) | 1.3333333333333335  | 5.4025456962435774 | 0         | 2         | 11        | 1                                                                   |                                                                     | 
| 1384524030  | Beacon Hill | % of population without health insurance                                      | Health, safety, quality of life | 5.68       | 5.63       |                    | 5.52               |                    |            |            | 14        | 15        |           | 14        |           |           |           |           |           | 3            | 14           | 15            | 14          | 0                        | 1                         | 0                                         | 1         | 0            | 0            |                    |                                  |                                 | 1                                                             |                                                                  | -1                                                                |                         |                          |              |              |                |      |                                     |                     | 0                  |           |           |           |                                                                     |                                                                     | 
| 1384524030  | Beacon Hill | % of students at or above proficient in mathematics, grade 4 - public schools | Education                       | 5.62       | 5.62       | 5.46               | 5.47               | 5.58               |            |            | 13        | 13        | 16        | 16        | 13        | 13        |           |           |           | 6            | 13           | 13            | 13          | 0                        | 0                         | 1                                         | 1         | 0            | 0            |                    | 13                               | 3                               | 0                                                             | -3                                                               | 0                                                                 | 3                       | 0                        | 1            | 0            | 1              | 1    |                                     | 3                   | 1.5                | 0         | 3         | 0         | 1.5                                                                 |                                                                     | 
| 1384524030  | Beacon Hill | Academic Science and Engineering R&D per $1,000 GSP                           | Innovation                      |            |            | 4.6100000000000003 | 4.6900000000000004 | 4.5599999999999996 |            |            |           |           | 34        | 31        | 35        | 35        |           |           |           | 4            | 34           | 35            | 35          | -1                       | 0                         | -1                                        | 0         | 0            | 1            |                    | 35                               | -4                              | 3                                                             |                                                                  |                                                                   | -1                      |                          | 0            | -1           | -1             | -1   |                                     | 4.333333333333333   | 1.6393596310755001 | 3         | 4         | 0         | 3.5                                                                 |                                                                     | 
| 1384524030  | Beacon Hill | Air passengers per capita                                                     | Travel/Infrastructure           | 5.14       | 4.96       | 5.25               | 5.26               | 5.28               |            |            | 13        | 19        | 13        | 13        | 13        | 12        |           |           |           | 6            | 13           | 13            | 12          | 1                        | 1                         | 2                                         | 1         | 0            | 0            |                    | 13                               | 0                               | 0                                                             | 6                                                                | -6                                                                | 0                       | 0                        | 0            | 0            | 0              | 1    |                                     | 0.25                | 0.4330127018922193 | 0         | 0         | 1         | 0                                                                   |                                                                     | 
| 1384524030  | Beacon Hill | Air Quality Index                                                             | Environment                     |            | 6.15       | 6.05               | 6.2                | 6.5                |            |            |           | 8         | 10        | 8         | 2         | 4         |           |           |           | 5            | 8            | 2             | 4           | 4                        | -2                        | 2                                         | 1         | 0            | 0            |                    | 2                                | 6                               | 2                                                             | -2                                                               |                                                                   | 8                       |                          | 1            | 0            | 1              | 1    | Clean Economy                       | 17.333333333333329  | 3.1622776601683795 | 2         | 6         | 2         | 4                                                                   |                                                                     | 
| 1384524030  | Beacon Hill | Average rent of 2 bedroom apartment                                           | Economic health                 |            |            | 4.43               | 4.33               | 4.38               |            |            |           |           | 37        | 37        | 37        | 37        |           |           |           | 4            | 37           | 37            | 37          | 0                        | 0                         | 0                                         | 0         | 0            | 1            |                    | 37                               | 0                               | 0                                                             |                                                                  |                                                                   | 0                       |                          | 0            | 0            | 0              | -1   |                                     | 0                   | 0                  | 0         | 0         | 0         | 0                                                                   |                                                                     | 
```