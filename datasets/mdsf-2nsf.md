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

## Description

Connecticut’s Next Generation Accountability System is a broad set of 12 indicators that help tell the story of how well a school is preparing its students for success in college, careers and life. The new system moves beyond test scores and graduation rates and instead provides a more holistic, multifactor perspective of district and school performance and incorporates student growth over time.

The 12 Indicators include:
1. Academic achievement status measured by state assessments
2. Academic growth
3. Assessment participation rate
4. Chronic absenteeism
5. Preparation for postsecondary and career readiness – coursework
6. Preparation for postsecondary and career readiness – exams
7. Graduation – on track in ninth grade
8. Graduation – four-year adjusted cohort graduation rate – all students
9. Graduation – six-year adjusted cohort graduation rate – high needs
10. Postsecondary entrance rate – all students (college enrollment)
11. Physical fitness
12. Arts access

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                                 | Data Type | Render Type |
| ======== | ============== | ================================================== | ==================================================== | ========= | =========== |
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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mdsf-2nsf d:2014-01-01T00:00:00.000Z t:school_low_grade=District t:district_code=10011 t:school_orgtype=District t:category=DistrictTot t:district_name="Andover School District" t:school_name=District_0000000 t:school_code=0 m:ind3ela_hn_rate=100 m:ind1sci_all_possiblepoints=100 m:ind4hnrate=3.7 m:ind1_math_nhn_rate=75 m:threshold_mean_ela=17.3 m:ind1math_all_rate=76.4 m:ind1math_all_possiblepoints=100 m:threshold_mean_sci=17.2 m:threshold_mean_math=19.6 m:ind1sci_all_rate=64 m:ind4hnpossiblepoints=50 m:ind11participationrate=97.6 m:ind3ela_all_rate=98.8 m:ind1_ela_hn_rate=74.4 m:ind11possiblepoints=50 m:ind4points=50 m:total_points=618.9 m:ind1sci_hn_possiblepoints=0 m:ind1math_hn_rate=67.2 m:ind11points=44.7 m:ind4possiblepoints=50 m:ind1mathgap=7.8 m:ind1math_hn_possiblepoints=100 m:total_possible_points=650 m:ind1sci_nhn_rate=71.1 m:ind4rate=1.2 m:ind1_ela_nhn_rate=75 m:ind1math_all_points=100 m:ind3math_all_rate=98.8 m:ind3sci_all_rate=100 m:ind1math_hn_points=89.6 m:ind1_ela_all_rate=82.9 m:ind3partrateflag=0 m:ind11fitnessrate=67.1 m:ind4hnpoints=50 m:of_distinctions=0 m:achievement_gap_flag=0 m:ind1_ela_hn_points=99.2 m:accountability_index=95.2 m:ind1elagap=0.6 m:ind1_ela_all_possiblepoints=100 m:ind1sci_all_points=85.4 m:ind1ela_hn_possiblepoints=100 m:ind3math_hn_rate=100 m:ind1_ela_all_points=100

series e:mdsf-2nsf d:2014-01-01T00:00:00.000Z t:school_low_grade=PK t:district_code=10011 t:school_orgtype="Public Schools" t:category=SchoolTot t:district_name="Andover School District" t:school_name="Andover Elementary School_0010111" t:school_title_i_type="Targeted Assistance" t:school_code=10111 m:ind3ela_hn_rate=100 m:ind1sci_all_possiblepoints=100 m:ind4hnrate=3.7 m:ind1_math_nhn_rate=75 m:threshold_mean_ela=16.8 m:ind1math_all_rate=76.4 m:ind1math_all_possiblepoints=100 m:threshold_mean_sci=17.3 m:threshold_mean_math=19.5 m:ind1sci_all_rate=64 m:ind4hnpossiblepoints=50 m:ind11participationrate=97.6 m:ind3ela_all_rate=98.8 m:ind1_ela_hn_rate=74.4 m:ind11possiblepoints=50 m:ind4points=50 m:school_high_grade=6 m:total_points=618.9 m:ind1sci_hn_possiblepoints=0 m:school_of_distintion_highest_performing_high_needs=1 m:ind1math_hn_rate=67.2 m:ind11points=44.7 m:ind4possiblepoints=50 m:ind1math_hn_possiblepoints=100 m:ind1mathgap=7.8 m:total_possible_points=650 m:ind1sci_nhn_rate=71.1 m:ind4rate=1.2 m:ind1_ela_nhn_rate=75 m:ind1math_all_points=100 m:ind3math_all_rate=98.8 m:ind3sci_all_rate=100 m:ind1math_hn_points=89.6 m:ind1_ela_all_rate=82.9 m:ind3partrateflag=0 m:ind11fitnessrate=67.1 m:school_of_distinction_highest_performing_overall=1 m:ind4hnpoints=50 m:of_distinctions=2 m:achievement_gap_flag=0 m:ind1_ela_hn_points=99.2 m:accountability_index=95.2 m:ind1elagap=0.6 m:ind1_ela_all_possiblepoints=100 m:ind1sci_all_points=85.4 m:ind1ela_hn_possiblepoints=100 m:ind3math_hn_rate=100 m:ind1_ela_all_points=100

series e:mdsf-2nsf d:2014-01-01T00:00:00.000Z t:school_low_grade=District t:district_code=20011 t:school_orgtype=District t:category=DistrictTot t:district_name="Ansonia School District" t:school_name=District_0000000 t:school_code=0 m:ind3ela_hn_rate=98.8 m:ind1sci_all_possiblepoints=100 m:ind8rate=76.4 m:ind7points=47.2 m:ind1_math_nhn_rate=60.3 m:ind12possiblepoints=50 m:ind1math_all_rate=51.7 m:ind1math_all_possiblepoints=100 m:threshold_mean_sci=17.2 m:ind8points=81.3 m:ind7pointspossible=50 m:ind7rate=88.8 m:ind4points=27.4 m:ind11possiblepoints=50 m:ind1sci_hn_possiblepoints=100 m:ind1math_hn_rate=48.5 m:ind4possiblepoints=50 m:ind1math_hn_possiblepoints=100 m:total_possible_points=1250 m:ind6points=13.9 m:ind1sci_nhn_rate=55.4 m:ind1sci_hn_rate=43.6 m:ind4rate=16.3 m:ind10possiblepoints=100 m:ind1_ela_nhn_rate=70.5 m:ind1math_all_points=69 m:ind5rate=75.9 m:ind3sci_all_rate=97.1 m:ind1_ela_all_rate=60.7 m:ind9pointspossible=100 m:ind11fitnessrate=38 m:ind4hnpoints=21.3 m:of_distinctions=0 m:grad6yrratenhn=91.9 m:ind1_ela_hn_points=76.2 m:ind1elagap=13.3 m:ind1sci_all_points=62.4 m:ind3math_hn_rate=98.2 m:ind9rate=79.7 m:ind5possiblepoints=50 m:ind4hnrate=19.3 m:threshold_mean_grad=15.2 m:ind1sci_hn_points=58.1 m:threshold_mean_ela=17.3 m:gradgapflag=0 m:threshold_mean_math=19.6 m:ind1sci_all_rate=46.8 m:ind4hnpossiblepoints=50 m:ind11participationrate=85.5 m:ind6rate=20.9 m:ind3ela_all_rate=98.6 m:ind1_ela_hn_rate=57.1 m:grad6yrhnnhndiff=12.2 m:ind6possiblepoints=50 m:total_points=862.4 m:ind10rate=59.4 m:ind5points=50 m:ind11points=12.7 m:ind1mathgap=11.8 m:ind8pointspossible=100 m:ind12points=33.1 m:ind3sci_hn_rate=96.7 m:ind3math_all_rate=98.4 m:ind1scigap=11.8 m:ind1math_hn_points=64.7 m:ind3partrateflag=0 m:ind12rate=39.8 m:grad6yrratehn=79.7 m:achievement_gap_flag=0 m:ind10points=79.2 m:accountability_index=69 m:ind1_ela_all_possiblepoints=100 m:ind1ela_hn_possiblepoints=100 m:ind1_ela_all_points=80.9 m:ind9points=84.8
```

## Meta Commands

```ls
metric m:school_high_grade p:integer l:"School High Grade" t:dataTypeName=number

metric m:total_points p:float l:"Total Points" t:dataTypeName=number

metric m:total_possible_points p:integer l:"Total Possible Points" t:dataTypeName=number

metric m:accountability_index p:float l:"Accountability Index" t:dataTypeName=number

metric m:achievement_gap_flag p:integer l:"Achievement Gap Flag" t:dataTypeName=number

metric m:ind1_ela_all_rate p:float l:"Ind1 ELA_All_Rate" t:dataTypeName=number

metric m:ind1_ela_all_points p:float l:"Ind1 ELA_All_Points" t:dataTypeName=number

metric m:ind1_ela_all_possiblepoints p:float l:"Ind1 ELA_All_PossiblePoints" t:dataTypeName=number

metric m:ind1_ela_hn_rate p:float l:"Ind1 ELA_HN_Rate" t:dataTypeName=number

metric m:ind1_math_nhn_rate p:float l:"Ind1 Math_NHN_Rate" t:dataTypeName=number

metric m:ind1_ela_nhn_rate p:float l:"Ind1 ELA_NHN_Rate" t:dataTypeName=number

metric m:ind1_ela_hn_points p:float l:"Ind1 ELA_HN_Points" t:dataTypeName=number

metric m:ind1ela_hn_possiblepoints p:float l:Ind1ELA_HN_PossiblePoints t:dataTypeName=number

metric m:ind1math_all_rate p:float l:Ind1Math_All_Rate t:dataTypeName=number

metric m:ind1math_all_points p:float l:Ind1Math_All_Points t:dataTypeName=number

metric m:ind1math_all_possiblepoints p:float l:Ind1Math_All_PossiblePoints t:dataTypeName=number

metric m:ind1math_hn_rate p:float l:Ind1Math_HN_Rate t:dataTypeName=number

metric m:ind1math_hn_points p:float l:Ind1Math_HN_Points t:dataTypeName=number

metric m:ind1math_hn_possiblepoints p:float l:Ind1Math_HN_PossiblePoints t:dataTypeName=number

metric m:ind1sci_all_rate p:float l:Ind1Sci_All_Rate t:dataTypeName=number

metric m:ind1sci_all_points p:float l:Ind1Sci_All_Points t:dataTypeName=number

metric m:ind1sci_all_possiblepoints p:float l:Ind1Sci_All_PossiblePoints t:dataTypeName=number

metric m:ind1sci_hn_rate p:float l:Ind1Sci_HN_Rate t:dataTypeName=number

metric m:ind1sci_nhn_rate p:float l:Ind1Sci_NHN_Rate t:dataTypeName=number

metric m:ind1sci_hn_points p:float l:Ind1Sci_HN_Points t:dataTypeName=number

metric m:ind1sci_hn_possiblepoints p:float l:Ind1Sci_HN_PossiblePoints t:dataTypeName=number

metric m:ind1elagap p:float l:Ind1ELAGap t:dataTypeName=number

metric m:ind1mathgap p:float l:Ind1MathGap t:dataTypeName=number

metric m:ind1scigap p:float l:Ind1SciGap t:dataTypeName=number

metric m:ind3partrateflag p:integer l:Ind3PartRateFlag t:dataTypeName=number

metric m:ind3ela_all_rate p:float l:Ind3ELA_All_Rate t:dataTypeName=percent

metric m:ind3ela_hn_rate p:float l:Ind3ELA_HN_Rate t:dataTypeName=percent

metric m:ind3math_all_rate p:float l:Ind3Math_All_Rate t:dataTypeName=percent

metric m:ind3math_hn_rate p:float l:Ind3Math_HN_Rate t:dataTypeName=percent

metric m:ind3sci_all_rate p:float l:Ind3Sci_All_Rate t:dataTypeName=percent

metric m:ind3sci_hn_rate p:float l:Ind3Sci_HN_Rate t:dataTypeName=percent

metric m:ind4rate p:float l:Ind4Rate t:dataTypeName=percent

metric m:ind4points p:float l:Ind4Points t:dataTypeName=number

metric m:ind4possiblepoints p:float l:Ind4PossiblePoints t:dataTypeName=number

metric m:ind4hnrate p:float l:Ind4HNRate t:dataTypeName=percent

metric m:ind4hnpoints p:float l:Ind4HNPoints t:dataTypeName=number

metric m:ind4hnpossiblepoints p:float l:Ind4HNPossiblePoints t:dataTypeName=number

metric m:ind5rate p:float l:Ind5Rate t:dataTypeName=percent

metric m:ind5points p:float l:Ind5Points t:dataTypeName=number

metric m:ind5possiblepoints p:float l:Ind5PossiblePoints t:dataTypeName=number

metric m:ind6rate p:float l:Ind6Rate t:dataTypeName=percent

metric m:ind6points p:float l:Ind6Points t:dataTypeName=number

metric m:ind6possiblepoints p:float l:Ind6PossiblePoints t:dataTypeName=number

metric m:ind7rate p:float l:Ind7Rate t:dataTypeName=percent

metric m:ind7points p:float l:Ind7points t:dataTypeName=number

metric m:ind7pointspossible p:float l:Ind7PointsPossible t:dataTypeName=number

metric m:ind8rate p:float l:Ind8Rate t:dataTypeName=percent

metric m:ind8points p:float l:Ind8Points t:dataTypeName=number

metric m:ind8pointspossible p:float l:Ind8PointsPossible t:dataTypeName=number

metric m:ind9rate p:float l:Ind9Rate t:dataTypeName=percent

metric m:ind9points p:float l:Ind9Points t:dataTypeName=number

metric m:ind9pointspossible p:float l:Ind9PointsPossible t:dataTypeName=number

metric m:gradgapflag p:integer l:GradGapFlag t:dataTypeName=number

metric m:ind10rate p:float l:Ind10Rate t:dataTypeName=percent

metric m:ind10points p:float l:Ind10Points t:dataTypeName=number

metric m:ind10possiblepoints p:float l:Ind10PossiblePoints t:dataTypeName=number

metric m:ind11fitnessrate p:float l:Ind11FitnessRate t:dataTypeName=percent

metric m:ind11participationrate p:float l:Ind11ParticipationRate t:dataTypeName=percent

metric m:ind11points p:float l:Ind11Points t:dataTypeName=number

metric m:ind11possiblepoints p:float l:Ind11PossiblePoints t:dataTypeName=number

metric m:ind12rate p:float l:Ind12Rate t:dataTypeName=percent

metric m:ind12points p:float l:Ind12Points t:dataTypeName=number

metric m:ind12possiblepoints p:float l:Ind12PossiblePoints t:dataTypeName=number

metric m:grad6yrratehn p:float l:Grad6YrRateHN t:dataTypeName=percent

metric m:grad6yrratenhn p:float l:Grad6YrRateNHN t:dataTypeName=percent

metric m:grad6yrhnnhndiff p:float l:Grad6YrHNNHNDiff t:dataTypeName=percent

metric m:threshold_mean_ela p:float l:Threshold_Mean_ELA t:dataTypeName=number

metric m:threshold_mean_math p:float l:Threshold_Mean_Math t:dataTypeName=number

metric m:threshold_mean_sci p:float l:Threshold_Mean_Sci t:dataTypeName=number

metric m:threshold_mean_grad p:float l:Threshold_Mean_Grad t:dataTypeName=number

metric m:state_category p:integer l:"State Category" t:dataTypeName=number

metric m:of_distinctions p:integer l:"# of Distinctions" t:dataTypeName=number

metric m:school_of_distinction_highest_performing_overall p:integer l:"School of Distinction - Highest Performing Overall" t:dataTypeName=number

metric m:school_of_distintion_highest_performing_high_needs p:integer l:"School of Distintion - Highest Performing High Needs" t:dataTypeName=number

entity e:mdsf-2nsf l:"State Department of Education Next Generation School Accountability data 2014-2015" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/mdsf-2nsf

property e:mdsf-2nsf t:meta.view v:id=mdsf-2nsf v:category=Education v:attributionLink="http://www.sde.ct.gov/sde/cwp/view.asp?a=2683&Q=334346" v:averageRating=0 v:name="State Department of Education Next Generation School Accountability data 2014-2015" v:attribution="State Department of Education"

property e:mdsf-2nsf t:meta.view.license v:name="Public Domain"

property e:mdsf-2nsf t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:displayName="Tyler Kleykamp"

property e:mdsf-2nsf t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| district_name           | district_code | school_name                       | school_code | school_orgtype | school_low_grade | school_high_grade | school_title_i_type | category    | total_points | total_possible_points | accountability_index | achievement_gap_flag | ind1_ela_all_rate | ind1_ela_all_points | ind1_ela_all_possiblepoints | ind1_ela_hn_rate | ind1_math_nhn_rate | ind1_ela_nhn_rate | ind1_ela_hn_points | ind1ela_hn_possiblepoints | ind1math_all_rate | ind1math_all_points | ind1math_all_possiblepoints | ind1math_hn_rate | ind1math_hn_points | ind1math_hn_possiblepoints | ind1sci_all_rate | ind1sci_all_points | ind1sci_all_possiblepoints | ind1sci_hn_rate | ind1sci_nhn_rate | ind1sci_hn_points | ind1sci_hn_possiblepoints | ind1elagap | ind1mathgap | ind1scigap | ind3partrateflag | ind3ela_all_rate | ind3ela_hn_rate | ind3math_all_rate | ind3math_hn_rate | ind3sci_all_rate | ind3sci_hn_rate | ind4rate | ind4points | ind4possiblepoints | ind4hnrate | ind4hnpoints | ind4hnpossiblepoints | ind5rate | ind5points | ind5possiblepoints | ind6rate | ind6points | ind6possiblepoints | ind7rate | ind7points | ind7pointspossible | ind8rate | ind8points | ind8pointspossible | ind9rate | ind9points | ind9pointspossible | gradgapflag | ind10rate | ind10points | ind10possiblepoints | ind11fitnessrate | ind11participationrate | ind11points | ind11possiblepoints | ind12rate | ind12points | ind12possiblepoints | grad6yrratehn | grad6yrratenhn | grad6yrhnnhndiff | threshold_mean_ela | threshold_mean_math | threshold_mean_sci | threshold_mean_grad | classification | state_category | of_distinctions | school_of_distinction_highest_performing_overall | school_of_distintion_highest_performing_high_needs | 
| ======================= | ============= | ================================= | =========== | ============== | ================ | ================= | =================== | =========== | ============ | ===================== | ==================== | ==================== | ================= | =================== | =========================== | ================ | ================== | ================= | ================== | ========================= | ================= | =================== | =========================== | ================ | ================== | ========================== | ================ | ================== | ========================== | =============== | ================ | ================= | ========================= | ========== | =========== | ========== | ================ | ================ | =============== | ================= | ================ | ================ | =============== | ======== | ========== | ================== | ========== | ============ | ==================== | ======== | ========== | ================== | ======== | ========== | ================== | ======== | ========== | ================== | ======== | ========== | ================== | ======== | ========== | ================== | =========== | ========= | =========== | =================== | ================ | ====================== | =========== | =================== | ========= | =========== | =================== | ============= | ============== | ================ | ================== | =================== | ================== | =================== | ============== | ============== | =============== | ================================================ | ================================================== | 
| Andover School District | 10011         | District_0000000                  | 0           | District       | District         |                   |                     | DistrictTot | 618.9        | 650                   | 95.2                 | 0                    | 82.9              | 100.0               | 100.0                       | 74.4             | 75.0               | 75.0              | 99.2               | 100.0                     | 76.4              | 100.0               | 100.0                       | 67.2             | 89.6               | 100.0                      | 64.0             | 85.4               | 100.0                      |                 | 71.1             |                   | 0.0                       | 0.6        | 7.8         |            | 0                | 98.8             | 100.0           | 98.8              | 100.0            | 100.0            |                 | 1.2      | 50.0       | 50.0               | 3.7        | 50.0         | 50.0                 |          |            |                    |          |            |                    |          |            |                    |          |            |                    |          |            |                    |             |           |             |                     | 67.1             | 97.6                   | 44.7        | 50.0                |           |             |                     |               |                |                  | 17.3               | 19.6                | 17.2               |                     |                |                | 0               |                                                  |                                                    | 
| Andover School District | 10011         | Andover Elementary School_0010111 | 10111       | Public Schools | PK               | 6                 | Targeted Assistance | SchoolTot   | 618.9        | 650                   | 95.2                 | 0                    | 82.9              | 100.0               | 100.0                       | 74.4             | 75.0               | 75.0              | 99.2               | 100.0                     | 76.4              | 100.0               | 100.0                       | 67.2             | 89.6               | 100.0                      | 64.0             | 85.4               | 100.0                      |                 | 71.1             |                   | 0.0                       | 0.6        | 7.8         |            | 0                | 98.8             | 100.0           | 98.8              | 100.0            | 100.0            |                 | 1.2      | 50.0       | 50.0               | 3.7        | 50.0         | 50.0                 |          |            |                    |          |            |                    |          |            |                    |          |            |                    |          |            |                    |             |           |             |                     | 67.1             | 97.6                   | 44.7        | 50.0                |           |             |                     |               |                |                  | 16.8               | 19.5                | 17.3               |                     |                |                | 2               | 1                                                | 1                                                  | 
| Ansonia School District | 20011         | District_0000000                  | 0           | District       | District         |                   |                     | DistrictTot | 862.4        | 1250                  | 69.0                 | 0                    | 60.7              | 80.9                | 100.0                       | 57.1             | 60.3               | 70.5              | 76.2               | 100.0                     | 51.7              | 69.0                | 100.0                       | 48.5             | 64.7               | 100.0                      | 46.8             | 62.4               | 100.0                      | 43.6            | 55.4             | 58.1              | 100.0                     | 13.3       | 11.8        | 11.8       | 0                | 98.6             | 98.8            | 98.4              | 98.2             | 97.1             | 96.7            | 16.3     | 27.4       | 50.0               | 19.3       | 21.3         | 50.0                 | 75.9     | 50.0       | 50.0               | 20.9     | 13.9       | 50.0               | 88.8     | 47.2       | 50.0               | 76.4     | 81.3       | 100.0              | 79.7     | 84.8       | 100.0              | 0           | 59.4      | 79.2        | 100.0               | 38.0             | 85.5                   | 12.7        | 50.0                | 39.8      | 33.1        | 50.0                | 79.7          | 91.9           | 12.2             | 17.3               | 19.6                | 17.2               | 15.2                |                |                | 0               |                                                  |                                                    | 
| Ansonia School District | 20011         | Mead School_0020311               | 20311       | Public Schools | PK               | 6                 | Schoolwide          | SchoolTot   | 496.3        | 750                   | 66.2                 | 0                    | 61.3              | 81.8                | 100.0                       | 58.5             | 60.5               | 69.6              | 78.0               | 100.0                     | 53.3              | 71.0                | 100.0                       | 50.8             | 67.7               | 100.0                      | 50.5             | 67.3               | 100.0                      | 47.4            | 58.3             | 63.2              | 100.0                     | 11.1       | 9.8         | 10.9       | 0                | 99.7             | 99.6            | 99.7              | 99.6             | 100.0            | 100.0           | 14.5     | 30.9       | 50.0               | 18.3       | 23.4         | 50.0                 |          |            |                    |          |            |                    |          |            |                    |          |            |                    |          |            |                    |             |           |             |                     | 38.8             | 88.7                   | 12.9        | 50.0                |           |             |                     |               |                |                  | 16.8               | 19.5                | 17.3               |                     |                |                | 0               |                                                  |                                                    | 
| Ansonia School District | 20011         | Prendergast School_0020811        | 20811       | Public Schools | K                | 6                 | Schoolwide          | SchoolTot   | 534.0        | 750                   | 71.2                 | 0                    | 62.8              | 83.7                | 100.0                       | 59.5             | 62.7               | 71.1              | 79.4               | 100.0                     | 55.4              | 73.9                | 100.0                       | 52.6             | 70.1               | 100.0                      | 46.5             | 62.0               | 100.0                      | 43.8            | 55.3             | 58.4              | 100.0                     | 11.5       | 10.1        | 11.5       | 0                | 99.7             | 100.0           | 99.7              | 100.0            | 97.8             | 97.2            | 9.4      | 41.3       | 50.0               | 11.8       | 36.4         | 50.0                 |          |            |                    |          |            |                    |          |            |                    |          |            |                    |          |            |                    |             |           |             |                     | 43.3             | 91.1                   | 28.9        | 50.0                |           |             |                     |               |                |                  | 16.8               | 19.5                | 17.3               |                     |                |                | 0               |                                                  |                                                    | 
| Ansonia School District | 20011         | Ansonia Middle School_0025111     | 25111       | Public Schools | PK               | 8                 | Schoolwide          | SchoolTot   | 493.3        | 800                   | 61.7                 | 0                    | 56.5              | 75.3                | 100.0                       | 53.0             | 57.4               | 68.0              | 70.6               | 100.0                     | 47.2              | 63.0                | 100.0                       | 44.1             | 58.8               | 100.0                      | 46.0             | 61.3               | 100.0                      | 43.7            | 52.7             | 58.2              | 100.0                     | 15.1       | 13.3        | 9.1        | 0                | 98.0             | 97.7            | 98.0              | 97.7             | 97.7             | 97.6            | 17.0     | 26.0       | 50.0               | 18.9       | 22.3         | 50.0                 |          |            |                    |          |            |                    | 92.4     | 49.2       | 50.0               |          |            |                    |          |            |                    |             |           |             |                     | 26.1             | 74.9                   | 8.7         | 50.0                |           |             |                     |               |                |                  | 16.8               | 19.5                | 17.3               |                     |                |                | 0               |                                                  |                                                    | 
| Ansonia School District | 20011         | Ansonia High School_0026111       | 26111       | Public Schools | 9                | 12                |                     | SchoolTot   | 890.9        | 1250                  | 71.3                 | 0                    | 70.1              | 93.5                | 100.0                       | 66.0             | 60.9               | 75.0              | 88.0               | 100.0                     | 53.8              | 71.8                | 100.0                       | 48.3             | 64.4               | 100.0                      | 48.2             | 64.3               | 100.0                      | 42.9            | 56.5             | 57.2              | 100.0                     | 9.0        | 12.7        | 13.7       | 1                | 93.8             | 95.3            | 92.1              | 89.2             | 95.1             | 93.1            | 21.6     | 16.8       | 50.0               | 25.7       | 8.7          | 50.0                 | 80.2     | 50.0       | 50.0               | 22.1     | 14.8       | 50.0               | 88.8     | 47.2       | 50.0               | 80.0     | 85.1       | 100.0              | 80.3     | 85.4       | 100.0              | 0           | 59.4      | 79.2        | 100.0               | 44.9             | 96.9                   | 29.9        | 50.0                | 41.7      | 34.7        | 50.0                | 80.3          | 91.9           | 11.6             | 16.8               | 19.5                | 17.3               | 12.6                |                |                | 0               |                                                  |                                                    | 
| Ashford School District | 30011         | District_0000000                  | 0           | District       | District         |                   |                     | DistrictTot | 632.1        | 800                   | 79.0                 | 0                    | 72.0              | 96.0                | 100.0                       | 62.8             | 67.1               | 75.0              | 83.7               | 100.0                     | 61.7              | 82.3                | 100.0                       | 53.9             | 71.8               | 100.0                      | 54.2             | 72.2               | 100.0                      | 47.1            | 60.1             | 62.8              | 100.0                     | 12.2       | 13.2        | 13.0       | 0                | 99.6             | 100.0           | 98.4              | 97.2             | 97.7             | 100.0           | 6.8      | 46.3       | 50.0               | 10.0       | 40.0         | 50.0                 |          |            |                    |          |            |                    | 84.8     | 45.1       | 50.0               |          |            |                    |          |            |                    |             |           |             |                     | 47.9             | 98.6                   | 31.9        | 50.0                |           |             |                     |               |                |                  | 17.3               | 19.6                | 17.2               |                     |                |                | 0               |                                                  |                                                    | 
| Ashford School District | 30011         | Ashford School_0030111            | 30111       | Public Schools | PK               | 8                 | Targeted Assistance | SchoolTot   | 635.3        | 800                   | 79.4                 | 0                    | 72.6              | 96.7                | 100.0                       | 63.9             | 67.1               | 75.0              | 85.2               | 100.0                     | 61.7              | 82.3                | 100.0                       | 53.9             | 71.8               | 100.0                      | 54.6             | 72.8               | 100.0                      | 47.9            | 60.1             | 63.9              | 100.0                     | 11.1       | 13.2        | 12.2       | 0                | 99.6             | 100.0           | 99.6              | 100.0            | 97.7             | 100.0           | 6.9      | 46.1       | 50.0               | 10.3       | 39.5         | 50.0                 |          |            |                    |          |            |                    | 84.8     | 45.1       | 50.0               |          |            |                    |          |            |                    |             |           |             |                     | 47.9             | 100.7                  | 31.9        | 50.0                |           |             |                     |               |                |                  | 16.8               | 19.5                | 17.3               |                     |                |                | 0               |                                                  |                                                    | 
| Avon School District    | 40011         | District_0000000                  | 0           | District       | District         |                   |                     | DistrictTot | 1129.3       | 1250                  | 90.3                 | 1                    | 81.4              | 100.0               | 100.0                       | 62.5             | 75.0               | 75.0              | 83.3               | 100.0                     | 75.9              | 100.0               | 100.0                       | 56.0             | 74.7               | 100.0                      | 68.1             | 90.8               | 100.0                      | 52.2            | 71.3             | 69.5              | 100.0                     | 12.5       | 19.0        | 19.1       | 0                | 99.1             | 98.3            | 99.0              | 98.7             | 99.9             | 100.0           | 3.0      | 50.0       | 50.0               | 7.2        | 45.7         | 50.0                 | 44.8     | 29.8       | 50.0               | 70.2     | 46.8       | 50.0               | 98.2     | 50.0       | 50.0               | 97.4     | 100.0      | 100.0              | 93.2     | 99.1       | 100.0              | 0           | 88.2      | 100.0       | 100.0               | 59.3             | 91.8                   | 39.6        | 50.0                | 64.7      | 50.0        | 50.0                | 93.2          | 94.0           | 0.8              | 17.3               | 19.6                | 17.2               | 15.2                |                |                | 0               |                                                  |                                                    | 
```