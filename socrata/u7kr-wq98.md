# School Health Index Case Studies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-health-index-case-studies-d039a) |
| Metadata | [Link](https://data.mo.gov/api/views/u7kr-wq98) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/u7kr-wq98/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/u7kr-wq98/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | u7kr-wq98 |
| Name | School Health Index Case Studies |
| Category | Health |
| Created | 2016-03-10T22:01:37Z |
| Publication Date | 2016-04-07T19:55:30Z |

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | county                       | County                       | text      | text        |
| Yes      | series tag     | school_name                  | School Name                  | text      | text        |
| Yes      | numeric metric | student_population           | Student Population           | number    | number      |
| Yes      | numeric metric | school_year                  | School Year                  | number    | text        |
| Yes      | series tag     | community_partner            | Community Partner            | text      | text        |
| Yes      | series tag     | school_health_and_safety     | School Health and Safety     | text      | text        |
| Yes      | series tag     | health_promotion_for_staff   | Health Promotion for Staff   | text      | text        |
| Yes      | series tag     | health_education             | Health Education             | text      | text        |
| Yes      | series tag     | counseling_services          | Counseling Services          | text      | text        |
| Yes      | series tag     | nutrition_services           | Nutrition Services           | text      | text        |
| Yes      | series tag     | physical_education           | Physical Education           | text      | text        |
| Yes      | series tag     | family_community_involvement | Family/Community Involvement | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u7kr-wq98 d:2016-03-11T07:05:40.000Z t:community_partner="Polk County Health Center" t:school_name="Humansville R-IV School District (Elementary)" t:county=Polk t:health_promotion_for_staff="Develop and adopt worksite breastfeeding policy; Implement a worksite wellness campaign and promote fitness facility for staff" m:student_population=190 m:school_year=2015

series e:u7kr-wq98 d:2016-03-23T12:33:58.000Z t:community_partner="Polk County Health Center" t:school_name="Bolivar R-I School District (Intermediate, Middle, High School)" t:county=Polk t:physical_education="Alternative discipline ideas introduced to faculty removing the practice of no recess as discipline (intermediate school); Advocate for additional recess time for all elementary grade levels" t:school_health_and_safety="Healthier snacks (bags of carrots with side of dressing & bag of grapes) added to concessions stands" t:health_promotion_for_staff="Implement a staff worksite wellness campaign with incentives (middle school)" m:student_population=2060 m:school_year=2015

series e:u7kr-wq98 d:2016-03-23T12:56:00.000Z t:community_partner="Reynolds County Health Center" t:family_community_involvement="Enhance communication channels (newsletters & website) about school wellness events" t:school_name="Bunker R-III School District" t:county=Reynolds t:physical_education="Incorporate brain breaks in the classroom; Add ""Extra Recess"" as good student incentive/reward; Incorporate intramural activities for High School" t:nutrition_services="Implement Smarter Lunchroom ideas (attractive serving bowls for fruit in more strategic easy to reach locations)" m:student_population=260 m:school_year=2015
```

## Meta Commands

```ls
metric m:student_population p:integer l:"Student Population" t:dataTypeName=number

metric m:school_year p:integer l:"School Year" t:dataTypeName=number

entity e:u7kr-wq98 l:"School Health Index Case Studies" t:url=https://data.mo.gov/api/views/u7kr-wq98

property e:u7kr-wq98 t:meta.view v:id=u7kr-wq98 v:category=Health v:averageRating=0 v:name="School Health Index Case Studies"

property e:u7kr-wq98 t:meta.view.owner v:id=63ti-ur4n v:screenName="Department of Health" v:displayName="Department of Health"

property e:u7kr-wq98 t:meta.view.tableauthor v:id=63ti-ur4n v:screenName="Department of Health" v:roleName=editor v:displayName="Department of Health"
```

## Top Records

```ls
| :updated_at | county   | school_name                                                     | student_population | school_year | community_partner                | school_health_and_safety                                                                                                                                                                                                             | health_promotion_for_staff                                                                                                     | health_education                                                                                                                                                                         | counseling_services                                                                | nutrition_services                                                                                                                                                                                                             | physical_education                                                                                                                                                                             | family_community_involvement                                                        | 
| =========== | ======== | =============================================================== | ================== | =========== | ================================ | ==================================================================================================================================================================================================================================== | ============================================================================================================================== | ======================================================================================================================================================================================== | ================================================================================== | ============================================================================================================================================================================================================================== | ============================================================================================================================================================================================== | =================================================================================== | 
| 1457679940  | Polk     | Humansville R-IV School District (Elementary)                   | 190                | 2015        | Polk County Health Center        |                                                                                                                                                                                                                                      | Develop and adopt worksite breastfeeding policy; Implement a worksite wellness campaign and promote fitness facility for staff |                                                                                                                                                                                          |                                                                                    |                                                                                                                                                                                                                                |                                                                                                                                                                                                |                                                                                     | 
| 1458736438  | Polk     | Bolivar R-I School District (Intermediate, Middle, High School) | 2060               | 2015        | Polk County Health Center        | Healthier snacks (bags of carrots with side of dressing & bag of grapes) added to concessions stands                                                                                                                                 | Implement a staff worksite wellness campaign with incentives (middle school)                                                   |                                                                                                                                                                                          |                                                                                    |                                                                                                                                                                                                                                | Alternative discipline ideas introduced to faculty removing the practice of no recess as discipline (intermediate school); Advocate for additional recess time for all elementary grade levels |                                                                                     | 
| 1458737760  | Reynolds | Bunker R-III School District                                    | 260                | 2015        | Reynolds County Health Center    |                                                                                                                                                                                                                                      |                                                                                                                                |                                                                                                                                                                                          |                                                                                    | Implement Smarter Lunchroom ideas (attractive serving bowls for fruit in more strategic easy to reach locations)                                                                                                               | Incorporate brain breaks in the classroom; Add "Extra Recess" as good student incentive/reward; Incorporate intramural activities for High School                                              | Enhance communication channels (newsletters & website) about school wellness events | 
| 1458737871  | Mercer   | North Mercer R-III School District (High School)                | 100                | 2015        | Mercer County Health Department  | Offer student non-food incentives as rewards for good behavior over food incentives; Add healthier vending aligned with smart snacks; Promote school districts tobacco-free campus policy and support tobacco-free student advocates | Implement an informal agreement between employees/employer for lactation support.                                              |                                                                                                                                                                                          |                                                                                    |                                                                                                                                                                                                                                |                                                                                                                                                                                                |                                                                                     | 
| 1459952588  | Jackson  | St John LaLande Catholic School                                 | 305                | 2015        | Jackson County Health Department | Update school wellness policy; Add healthier concessions                                                                                                                                                                             | Develop & adopt worksite breastfeeding policy; Incorporate worksite wellness programming from health insurance company.        | Incorporate brain breaks in the classroom; Seek & implement quality physical education curricula (Spark); In SY 2016-2017, recess time will be scheduled from 2 days to 5 days per week. | Allocate funding and hire part-time counselor to start SY 2016-2017.               | Commit to a school lunch survey and begin incorporating changes as allowed.; Offer tastings from schoolyard garden; Partnered with HyVee to purchase at cost produce for before and after school, Snack Shack and concessions. |                                                                                                                                                                                                |                                                                                     | 
| 1460033699  | Greene   | Walnut Grove R-V School District (Elementary)                   | 160                | 2015        | Polk County Health Center        |                                                                                                                                                                                                                                      | Develop and adopt worksite breastfeeding policy; Implement a fitness/weight loss challenge                                     |                                                                                                                                                                                          | Provide financial resources for students to access milk in an after-school program | Market salad bar through Rainbow Day Events to increase student participation; Nursing Service and Nutrition Service collaborate on a staff safety training (choking, defense food policy, medical emergencies/food allergies) |                                                                                                                                                                                                |                                                                                     | 
```