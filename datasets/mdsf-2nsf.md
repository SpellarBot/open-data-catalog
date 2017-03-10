# State Department of Education Next Generation School Accountability data 2014-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-department-of-education-next-generation-school-accountability-data-2014-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/mdsf-2nsf) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/mdsf-2nsf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/mdsf-2nsf/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | mdsf-2nsf |
| Name | State Department of Education Next Generation School Accountability data 2014-2015 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, accountability |
| Created | 2016-03-03T14:59:32Z |
| Publication Date | 2016-03-03T19:55:18Z |
| Rows Updated | 2016-03-03T19:52:26Z |

## Description

Connecticut?s Next Generation Accountability System is a broad set of 12 indicators that help tell the story of how well a school is preparing its students for success in college, careers and life. The new system moves beyond test scores and graduation rates and instead provides a more holistic, multifactor perspective of district and school performance and incorporates student growth over time.

The 12 Indicators include:
1. Academic achievement status measured by state assessments
2. Academic growth
3. Assessment participation rate
4. Chronic absenteeism
5. Preparation for postsecondary and career readiness ? coursework
6. Preparation for postsecondary and career readiness ? exams
7. Graduation ? on track in ninth grade
8. Graduation ? four-year adjusted cohort graduation rate ? all students
9. Graduation ? six-year adjusted cohort graduation rate ? high needs
10. Postsecondary entrance rate ? all students (college enrollment)
11. Physical fitness
12. Arts access

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                                 | Data Type | Render Type |
| ======== | ============== | ================================================== | ==================================================== | ========= | =========== |
| No       | time           | :updated_at                                        | updated_at                                           | meta_data | meta_data   |
| Yes      | series tag     | district_name                                      | District Name                                        | text      | text        |
| Yes      | series tag     | district_code                                      | District Code                                        | text      | number      |
| Yes      | series tag     | school_name                                        | School Name                                          | text      | text        |
| Yes      | series tag     | school_code                                        | School Code                                          | text      | number      |
| Yes      | series tag     | school_orgtype                                     | School OrgType                                       | text      | text        |
| Yes      | series tag     | school_low_grade                                   | School Low Grade                                     | text      | text        |
| Yes      | numeric metric | school_high_grade                                  | School High Grade                                    | number    | number      |
| Yes      | series tag     | school_title_i_type                                | School Title I Type                                  | text      | text        |
| Yes      | series tag     | category                                           | Category                                             | text      | text        |
| Yes      | numeric metric | total_points                                       | Total Points                                         | number    | number      |
| Yes      | numeric metric | total_possible_points                              | Total Possible Points                                | number    | number      |
| Yes      | numeric metric | accountability_index                               | Accountability Index                                 | number    | number      |
| Yes      | numeric metric | achievement_gap_flag                               | Achievement Gap Flag                                 | number    | number      |
| Yes      | numeric metric | ind1_ela_all_rate                                  | Ind1 ELA_All_Rate                                    | number    | number      |
| Yes      | numeric metric | ind1_ela_all_points                                | Ind1 ELA_All_Points                                  | number    | number      |
| Yes      | numeric metric | ind1_ela_all_possiblepoints                        | Ind1 ELA_All_PossiblePoints                          | number    | number      |
| Yes      | numeric metric | ind1_ela_hn_rate                                   | Ind1 ELA_HN_Rate                                     | number    | number      |
| Yes      | numeric metric | ind1_math_nhn_rate                                 | Ind1 Math_NHN_Rate                                   | number    | number      |
| Yes      | numeric metric | ind1_ela_nhn_rate                                  | Ind1 ELA_NHN_Rate                                    | number    | number      |
| Yes      | numeric metric | ind1_ela_hn_points                                 | Ind1 ELA_HN_Points                                   | number    | number      |
| Yes      | numeric metric | ind1ela_hn_possiblepoints                          | Ind1ELA_HN_PossiblePoints                            | number    | number      |
| Yes      | numeric metric | ind1math_all_rate                                  | Ind1Math_All_Rate                                    | number    | number      |
| Yes      | numeric metric | ind1math_all_points                                | Ind1Math_All_Points                                  | number    | number      |
| Yes      | numeric metric | ind1math_all_possiblepoints                        | Ind1Math_All_PossiblePoints                          | number    | number      |
| Yes      | numeric metric | ind1math_hn_rate                                   | Ind1Math_HN_Rate                                     | number    | number      |
| Yes      | numeric metric | ind1math_hn_points                                 | Ind1Math_HN_Points                                   | number    | number      |
| Yes      | numeric metric | ind1math_hn_possiblepoints                         | Ind1Math_HN_PossiblePoints                           | number    | number      |
| Yes      | numeric metric | ind1sci_all_rate                                   | Ind1Sci_All_Rate                                     | number    | number      |
| Yes      | numeric metric | ind1sci_all_points                                 | Ind1Sci_All_Points                                   | number    | number      |
| Yes      | numeric metric | ind1sci_all_possiblepoints                         | Ind1Sci_All_PossiblePoints                           | number    | number      |
| Yes      | numeric metric | ind1sci_hn_rate                                    | Ind1Sci_HN_Rate                                      | number    | number      |
| Yes      | numeric metric | ind1sci_nhn_rate                                   | Ind1Sci_NHN_Rate                                     | number    | number      |
| Yes      | numeric metric | ind1sci_hn_points                                  | Ind1Sci_HN_Points                                    | number    | number      |
| Yes      | numeric metric | ind1sci_hn_possiblepoints                          | Ind1Sci_HN_PossiblePoints                            | number    | number      |
| Yes      | numeric metric | ind1elagap                                         | Ind1ELAGap                                           | number    | number      |
| Yes      | numeric metric | ind1mathgap                                        | Ind1MathGap                                          | number    | number      |
| Yes      | numeric metric | ind1scigap                                         | Ind1SciGap                                           | number    | number      |
| Yes      | numeric metric | ind3partrateflag                                   | Ind3PartRateFlag                                     | number    | number      |
| Yes      | numeric metric | ind3ela_all_rate                                   | Ind3ELA_All_Rate                                     | percent   | percent     |
| Yes      | numeric metric | ind3ela_hn_rate                                    | Ind3ELA_HN_Rate                                      | percent   | percent     |
| Yes      | numeric metric | ind3math_all_rate                                  | Ind3Math_All_Rate                                    | percent   | percent     |
| Yes      | numeric metric | ind3math_hn_rate                                   | Ind3Math_HN_Rate                                     | percent   | percent     |
| Yes      | numeric metric | ind3sci_all_rate                                   | Ind3Sci_All_Rate                                     | percent   | percent     |
| Yes      | numeric metric | ind3sci_hn_rate                                    | Ind3Sci_HN_Rate                                      | percent   | percent     |
| Yes      | numeric metric | ind4rate                                           | Ind4Rate                                             | percent   | percent     |
| Yes      | numeric metric | ind4points                                         | Ind4Points                                           | number    | number      |
| Yes      | numeric metric | ind4possiblepoints                                 | Ind4PossiblePoints                                   | number    | number      |
| Yes      | numeric metric | ind4hnrate                                         | Ind4HNRate                                           | percent   | percent     |
| Yes      | numeric metric | ind4hnpoints                                       | Ind4HNPoints                                         | number    | number      |
| Yes      | numeric metric | ind4hnpossiblepoints                               | Ind4HNPossiblePoints                                 | number    | number      |
| Yes      | numeric metric | ind5rate                                           | Ind5Rate                                             | percent   | percent     |
| Yes      | numeric metric | ind5points                                         | Ind5Points                                           | number    | number      |
| Yes      | numeric metric | ind5possiblepoints                                 | Ind5PossiblePoints                                   | number    | number      |
| Yes      | numeric metric | ind6rate                                           | Ind6Rate                                             | percent   | percent     |
| Yes      | numeric metric | ind6points                                         | Ind6Points                                           | number    | number      |
| Yes      | numeric metric | ind6possiblepoints                                 | Ind6PossiblePoints                                   | number    | number      |
| Yes      | numeric metric | ind7rate                                           | Ind7Rate                                             | percent   | percent     |
| Yes      | numeric metric | ind7points                                         | Ind7points                                           | number    | number      |
| Yes      | numeric metric | ind7pointspossible                                 | Ind7PointsPossible                                   | number    | number      |
| Yes      | numeric metric | ind8rate                                           | Ind8Rate                                             | percent   | percent     |
| Yes      | numeric metric | ind8points                                         | Ind8Points                                           | number    | number      |
| Yes      | numeric metric | ind8pointspossible                                 | Ind8PointsPossible                                   | number    | number      |
| Yes      | numeric metric | ind9rate                                           | Ind9Rate                                             | percent   | percent     |
| Yes      | numeric metric | ind9points                                         | Ind9Points                                           | number    | number      |
| Yes      | numeric metric | ind9pointspossible                                 | Ind9PointsPossible                                   | number    | number      |
| Yes      | numeric metric | gradgapflag                                        | GradGapFlag                                          | number    | number      |
| Yes      | numeric metric | ind10rate                                          | Ind10Rate                                            | percent   | percent     |
| Yes      | numeric metric | ind10points                                        | Ind10Points                                          | number    | number      |
| Yes      | numeric metric | ind10possiblepoints                                | Ind10PossiblePoints                                  | number    | number      |
| Yes      | numeric metric | ind11fitnessrate                                   | Ind11FitnessRate                                     | percent   | percent     |
| Yes      | numeric metric | ind11participationrate                             | Ind11ParticipationRate                               | percent   | percent     |
| Yes      | numeric metric | ind11points                                        | Ind11Points                                          | number    | number      |
| Yes      | numeric metric | ind11possiblepoints                                | Ind11PossiblePoints                                  | number    | number      |
| Yes      | numeric metric | ind12rate                                          | Ind12Rate                                            | percent   | percent     |
| Yes      | numeric metric | ind12points                                        | Ind12Points                                          | number    | number      |
| Yes      | numeric metric | ind12possiblepoints                                | Ind12PossiblePoints                                  | number    | number      |
| Yes      | numeric metric | grad6yrratehn                                      | Grad6YrRateHN                                        | percent   | percent     |
| Yes      | numeric metric | grad6yrratenhn                                     | Grad6YrRateNHN                                       | percent   | percent     |
| Yes      | numeric metric | grad6yrhnnhndiff                                   | Grad6YrHNNHNDiff                                     | percent   | percent     |
| Yes      | numeric metric | threshold_mean_ela                                 | Threshold_Mean_ELA                                   | number    | number      |
| Yes      | numeric metric | threshold_mean_math                                | Threshold_Mean_Math                                  | number    | number      |
| Yes      | numeric metric | threshold_mean_sci                                 | Threshold_Mean_Sci                                   | number    | number      |
| Yes      | numeric metric | threshold_mean_grad                                | Threshold_Mean_Grad                                  | number    | number      |
| Yes      | series tag     | classification                                     | Classification                                       | text      | text        |
| Yes      | numeric metric | state_category                                     | State Category                                       | number    | number      |
| Yes      | numeric metric | of_distinctions                                    | # of Distinctions                                    | number    | number      |
| Yes      | numeric metric | school_of_distinction_highest_performing_overall   | School of Distinction - Highest Performing Overall   | number    | number      |
| Yes      | numeric metric | school_of_distintion_highest_performing_high_needs | School of Distintion - Highest Performing High Needs | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mdsf-2nsf d:2016-03-03T06:59:44.000Z t:school_low_grade=District t:district_code=10011 t:school_orgtype=District t:category=DistrictTot t:district_name="Andover School District" t:school_name=District_0000000 t:school_code=0 m:ind3ela_hn_rate=100 m:ind1sci_all_possiblepoints=100 m:ind4hnrate=3.7 m:ind1_math_nhn_rate=75 m:threshold_mean_ela=17.3 m:ind1math_all_rate=76.4 m:ind1math_all_possiblepoints=100 m:threshold_mean_sci=17.2 m:threshold_mean_math=19.6 m:ind1sci_all_rate=64 m:ind4hnpossiblepoints=50 m:ind11participationrate=97.6 m:ind3ela_all_rate=98.8 m:ind1_ela_hn_rate=74.4 m:ind11possiblepoints=50 m:ind4points=50 m:total_points=618.9 m:ind1sci_hn_possiblepoints=0 m:ind1math_hn_rate=67.2 m:ind11points=44.7 m:ind4possiblepoints=50 m:ind1mathgap=7.8 m:ind1math_hn_possiblepoints=100 m:total_possible_points=650 m:ind1sci_nhn_rate=71.1 m:ind4rate=1.2 m:ind1_ela_nhn_rate=75 m:ind1math_all_points=100 m:ind3math_all_rate=98.8 m:ind3sci_all_rate=100 m:ind1math_hn_points=89.6 m:ind1_ela_all_rate=82.9 m:ind3partrateflag=0 m:ind11fitnessrate=67.1 m:ind4hnpoints=50 m:of_distinctions=0 m:achievement_gap_flag=0 m:ind1_ela_hn_points=99.2 m:accountability_index=95.2 m:ind1elagap=0.6 m:ind1_ela_all_possiblepoints=100 m:ind1sci_all_points=85.4 m:ind1ela_hn_possiblepoints=100 m:ind3math_hn_rate=100 m:ind1_ela_all_points=100

series e:mdsf-2nsf d:2016-03-03T06:59:44.000Z t:school_low_grade=PK t:district_code=10011 t:school_orgtype="Public Schools" t:category=SchoolTot t:district_name="Andover School District" t:school_name="Andover Elementary School_0010111" t:school_title_i_type="Targeted Assistance" t:school_code=10111 m:ind3ela_hn_rate=100 m:ind1sci_all_possiblepoints=100 m:ind4hnrate=3.7 m:ind1_math_nhn_rate=75 m:threshold_mean_ela=16.8 m:ind1math_all_rate=76.4 m:ind1math_all_possiblepoints=100 m:threshold_mean_sci=17.3 m:threshold_mean_math=19.5 m:ind1sci_all_rate=64 m:ind4hnpossiblepoints=50 m:ind11participationrate=97.6 m:ind3ela_all_rate=98.8 m:ind1_ela_hn_rate=74.4 m:ind11possiblepoints=50 m:ind4points=50 m:school_high_grade=6 m:total_points=618.9 m:ind1sci_hn_possiblepoints=0 m:school_of_distintion_highest_performing_high_needs=1 m:ind1math_hn_rate=67.2 m:ind11points=44.7 m:ind4possiblepoints=50 m:ind1math_hn_possiblepoints=100 m:ind1mathgap=7.8 m:total_possible_points=650 m:ind1sci_nhn_rate=71.1 m:ind4rate=1.2 m:ind1_ela_nhn_rate=75 m:ind1math_all_points=100 m:ind3math_all_rate=98.8 m:ind3sci_all_rate=100 m:ind1math_hn_points=89.6 m:ind1_ela_all_rate=82.9 m:ind3partrateflag=0 m:ind11fitnessrate=67.1 m:school_of_distinction_highest_performing_overall=1 m:ind4hnpoints=50 m:of_distinctions=2 m:achievement_gap_flag=0 m:ind1_ela_hn_points=99.2 m:accountability_index=95.2 m:ind1elagap=0.6 m:ind1_ela_all_possiblepoints=100 m:ind1sci_all_points=85.4 m:ind1ela_hn_possiblepoints=100 m:ind3math_hn_rate=100 m:ind1_ela_all_points=100

series e:mdsf-2nsf d:2016-03-03T06:59:44.000Z t:school_low_grade=District t:district_code=20011 t:school_orgtype=District t:category=DistrictTot t:district_name="Ansonia School District" t:school_name=District_0000000 t:school_code=0 m:ind3ela_hn_rate=98.8 m:ind1sci_all_possiblepoints=100 m:ind8rate=76.4 m:ind7points=47.2 m:ind1_math_nhn_rate=60.3 m:ind12possiblepoints=50 m:ind1math_all_rate=51.7 m:ind1math_all_possiblepoints=100 m:threshold_mean_sci=17.2 m:ind8points=81.3 m:ind7pointspossible=50 m:ind7rate=88.8 m:ind4points=27.4 m:ind11possiblepoints=50 m:ind1sci_hn_possiblepoints=100 m:ind1math_hn_rate=48.5 m:ind4possiblepoints=50 m:ind1math_hn_possiblepoints=100 m:total_possible_points=1250 m:ind6points=13.9 m:ind1sci_nhn_rate=55.4 m:ind1sci_hn_rate=43.6 m:ind4rate=16.3 m:ind10possiblepoints=100 m:ind1_ela_nhn_rate=70.5 m:ind1math_all_points=69 m:ind5rate=75.9 m:ind3sci_all_rate=97.1 m:ind1_ela_all_rate=60.7 m:ind9pointspossible=100 m:ind11fitnessrate=38 m:ind4hnpoints=21.3 m:of_distinctions=0 m:grad6yrratenhn=91.9 m:ind1_ela_hn_points=76.2 m:ind1elagap=13.3 m:ind1sci_all_points=62.4 m:ind3math_hn_rate=98.2 m:ind9rate=79.7 m:ind5possiblepoints=50 m:ind4hnrate=19.3 m:threshold_mean_grad=15.2 m:ind1sci_hn_points=58.1 m:threshold_mean_ela=17.3 m:gradgapflag=0 m:threshold_mean_math=19.6 m:ind1sci_all_rate=46.8 m:ind4hnpossiblepoints=50 m:ind11participationrate=85.5 m:ind6rate=20.9 m:ind3ela_all_rate=98.6 m:ind1_ela_hn_rate=57.1 m:grad6yrhnnhndiff=12.2 m:ind6possiblepoints=50 m:total_points=862.4 m:ind10rate=59.4 m:ind5points=50 m:ind11points=12.7 m:ind1mathgap=11.8 m:ind8pointspossible=100 m:ind12points=33.1 m:ind3sci_hn_rate=96.7 m:ind3math_all_rate=98.4 m:ind1scigap=11.8 m:ind1math_hn_points=64.7 m:ind3partrateflag=0 m:ind12rate=39.8 m:grad6yrratehn=79.7 m:achievement_gap_flag=0 m:ind10points=79.2 m:accountability_index=69 m:ind1_ela_all_possiblepoints=100 m:ind1ela_hn_possiblepoints=100 m:ind1_ela_all_points=80.9 m:ind9points=84.8
```

## Meta Commands

```ls
metric m:school_high_grade p:integer l:"School High Grade" t:dataTypeName=number

metric m:total_points l:"Total Points" t:dataTypeName=number

metric m:total_possible_points p:integer l:"Total Possible Points" t:dataTypeName=number

metric m:accountability_index l:"Accountability Index" t:dataTypeName=number

metric m:achievement_gap_flag p:integer l:"Achievement Gap Flag" t:dataTypeName=number

metric m:ind1_ela_all_rate l:"Ind1 ELA_All_Rate" t:dataTypeName=number

metric m:ind1_ela_all_points l:"Ind1 ELA_All_Points" t:dataTypeName=number

metric m:ind1_ela_all_possiblepoints l:"Ind1 ELA_All_PossiblePoints" t:dataTypeName=number

metric m:ind1_ela_hn_rate l:"Ind1 ELA_HN_Rate" t:dataTypeName=number

metric m:ind1_math_nhn_rate l:"Ind1 Math_NHN_Rate" t:dataTypeName=number

metric m:ind1_ela_nhn_rate l:"Ind1 ELA_NHN_Rate" t:dataTypeName=number

metric m:ind1_ela_hn_points l:"Ind1 ELA_HN_Points" t:dataTypeName=number

metric m:ind1ela_hn_possiblepoints l:Ind1ELA_HN_PossiblePoints t:dataTypeName=number

metric m:ind1math_all_rate l:Ind1Math_All_Rate t:dataTypeName=number

metric m:ind1math_all_points l:Ind1Math_All_Points t:dataTypeName=number

metric m:ind1math_all_possiblepoints l:Ind1Math_All_PossiblePoints t:dataTypeName=number

metric m:ind1math_hn_rate l:Ind1Math_HN_Rate t:dataTypeName=number

metric m:ind1math_hn_points l:Ind1Math_HN_Points t:dataTypeName=number

metric m:ind1math_hn_possiblepoints l:Ind1Math_HN_PossiblePoints t:dataTypeName=number

metric m:ind1sci_all_rate l:Ind1Sci_All_Rate t:dataTypeName=number

metric m:ind1sci_all_points l:Ind1Sci_All_Points t:dataTypeName=number

metric m:ind1sci_all_possiblepoints l:Ind1Sci_All_PossiblePoints t:dataTypeName=number

metric m:ind1sci_hn_rate l:Ind1Sci_HN_Rate t:dataTypeName=number

metric m:ind1sci_nhn_rate l:Ind1Sci_NHN_Rate t:dataTypeName=number

metric m:ind1sci_hn_points l:Ind1Sci_HN_Points t:dataTypeName=number

metric m:ind1sci_hn_possiblepoints l:Ind1Sci_HN_PossiblePoints t:dataTypeName=number

metric m:ind1elagap l:Ind1ELAGap t:dataTypeName=number

metric m:ind1mathgap l:Ind1MathGap t:dataTypeName=number

metric m:ind1scigap l:Ind1SciGap t:dataTypeName=number

metric m:ind3partrateflag p:integer l:Ind3PartRateFlag t:dataTypeName=number

metric m:ind4points l:Ind4Points t:dataTypeName=number

metric m:ind4possiblepoints l:Ind4PossiblePoints t:dataTypeName=number

metric m:ind4hnpoints l:Ind4HNPoints t:dataTypeName=number

metric m:ind4hnpossiblepoints l:Ind4HNPossiblePoints t:dataTypeName=number

metric m:ind5points l:Ind5Points t:dataTypeName=number

metric m:ind5possiblepoints l:Ind5PossiblePoints t:dataTypeName=number

metric m:ind6points l:Ind6Points t:dataTypeName=number

metric m:ind6possiblepoints l:Ind6PossiblePoints t:dataTypeName=number

metric m:ind7points l:Ind7points t:dataTypeName=number

metric m:ind7pointspossible l:Ind7PointsPossible t:dataTypeName=number

metric m:ind8points l:Ind8Points t:dataTypeName=number

metric m:ind8pointspossible l:Ind8PointsPossible t:dataTypeName=number

metric m:ind9points l:Ind9Points t:dataTypeName=number

metric m:ind9pointspossible l:Ind9PointsPossible t:dataTypeName=number

metric m:gradgapflag p:integer l:GradGapFlag t:dataTypeName=number

metric m:ind10points l:Ind10Points t:dataTypeName=number

metric m:ind10possiblepoints l:Ind10PossiblePoints t:dataTypeName=number

metric m:ind11points l:Ind11Points t:dataTypeName=number

metric m:ind11possiblepoints l:Ind11PossiblePoints t:dataTypeName=number

metric m:ind12points l:Ind12Points t:dataTypeName=number

metric m:ind12possiblepoints l:Ind12PossiblePoints t:dataTypeName=number

metric m:threshold_mean_ela l:Threshold_Mean_ELA t:dataTypeName=number

metric m:threshold_mean_math l:Threshold_Mean_Math t:dataTypeName=number

metric m:threshold_mean_sci l:Threshold_Mean_Sci t:dataTypeName=number

metric m:threshold_mean_grad l:Threshold_Mean_Grad t:dataTypeName=number

metric m:state_category p:integer l:"State Category" t:dataTypeName=number

metric m:of_distinctions p:integer l:"# of Distinctions" t:dataTypeName=number

metric m:school_of_distinction_highest_performing_overall p:integer l:"School of Distinction - Highest Performing Overall" t:dataTypeName=number

metric m:school_of_distintion_highest_performing_high_needs p:integer l:"School of Distintion - Highest Performing High Needs" t:dataTypeName=number

entity e:mdsf-2nsf l:"State Department of Education Next Generation School Accountability data 2014-2015" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/mdsf-2nsf

property e:mdsf-2nsf t:meta.view d:2017-03-10T16:05:55.737Z v:id=mdsf-2nsf v:category=Education v:attributionLink="http://www.sde.ct.gov/sde/cwp/view.asp?a=2683&Q=334346" v:averageRating=0 v:name="State Department of Education Next Generation School Accountability data 2014-2015" v:attribution="State Department of Education"

property e:mdsf-2nsf t:meta.view.license d:2017-03-10T16:05:55.737Z v:name="Public Domain"

property e:mdsf-2nsf t:meta.view.owner d:2017-03-10T16:05:55.737Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"

property e:mdsf-2nsf t:meta.view.tableauthor d:2017-03-10T16:05:55.737Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"
```