# Public Health Statistics- Selected public health indicators by Chicago community area

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-selected-public-health-indicators-by-chicago-community-area-f2a90) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/iqnk-2tcu) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/iqnk-2tcu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/iqnk-2tcu/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | iqnk-2tcu |
| Name | Public Health Statistics- Selected public health indicators by Chicago community area |
| Attribution | Illinois Department of Public Health (IDPH) and U.S. Census Bureau |
| Category | Health & Human Services |
| Created | 2012-05-18T18:25:32Z |
| Publication Date | 2013-06-04T18:23:42Z |

## Description

This dataset contains a selection of 27 indicators of public health significance by Chicago community area, with the most updated information available. The indicators are rates, percents, or other measures related to natality, mortality, infectious disease, lead poisoning, and economic status.  See the full description at https://data.cityofchicago.org/api/assets/2107948F-357D-4ED7-ACC2-2E9266BBFFA2.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| No       | time           | :updated_at                                | updated_at                                 | meta_data | meta_data   |
| Yes      | series tag     | community_area                             | Community Area                             | text      | text        |
| Yes      | series tag     | community_area_name                        | Community Area Name                        | text      | text        |
| Yes      | numeric metric | birth_rate                                 | Birth Rate                                 | number    | text        |
| Yes      | numeric metric | general_fertility_rate                     | General Fertility Rate                     | number    | text        |
| Yes      | numeric metric | low_birth_weight                           | Low Birth Weight                           | number    | text        |
| Yes      | numeric metric | prenatal_care_beginning_in_first_trimester | Prenatal Care Beginning in First Trimester | number    | number      |
| Yes      | numeric metric | preterm_births                             | Preterm Births                             | number    | text        |
| Yes      | numeric metric | teen_birth_rate                            | Teen Birth Rate                            | number    | number      |
| Yes      | numeric metric | assault_homicide                           | Assault (Homicide)                         | number    | text        |
| Yes      | numeric metric | breast_cancer_in_females                   | Breast cancer in females                   | number    | number      |
| Yes      | numeric metric | cancer_all_sites                           | Cancer (All Sites)                         | number    | text        |
| Yes      | numeric metric | colorectal_cancer                          | Colorectal Cancer                          | number    | number      |
| Yes      | numeric metric | diabetes_related                           | Diabetes-related                           | number    | text        |
| Yes      | numeric metric | firearm_related                            | Firearm-related                            | number    | number      |
| Yes      | numeric metric | infant_mortality_rate                      | Infant Mortality Rate                      | number    | number      |
| Yes      | numeric metric | lung_cancer                                | Lung Cancer                                | number    | number      |
| Yes      | numeric metric | prostate_cancer_in_males                   | Prostate Cancer in Males                   | number    | number      |
| Yes      | numeric metric | stroke_cerebrovascular_disease             | Stroke (Cerebrovascular Disease)           | number    | number      |
| Yes      | numeric metric | childhood_blood_lead_level_screening       | Childhood Blood Lead Level Screening       | number    | number      |
| Yes      | numeric metric | childhood_lead_poisoning                   | Childhood Lead Poisoning                   | number    | number      |
| Yes      | numeric metric | gonorrhea_in_females                       | Gonorrhea in Females                       | number    | number      |
| Yes      | numeric metric | gonorrhea_in_males                         | Gonorrhea in Males                         | number    | text        |
| Yes      | numeric metric | tuberculosis                               | Tuberculosis                               | number    | number      |
| Yes      | numeric metric | below_poverty_level                        | Below Poverty Level                        | number    | number      |
| Yes      | numeric metric | crowded_housing                            | Crowded Housing                            | number    | number      |
| Yes      | numeric metric | dependency                                 | Dependency                                 | number    | number      |
| Yes      | numeric metric | no_high_school_diploma                     | No High School Diploma                     | number    | number      |
| Yes      | numeric metric | per_capita_income                          | Per Capita Income                          | number    | number      |
| Yes      | numeric metric | unemployment                               | Unemployment                               | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:iqnk-2tcu d:2013-05-30T07:08:51.000Z t:community_area_name="Rogers Park" t:community_area=1 m:prenatal_care_beginning_in_first_trimester=73 m:cancer_all_sites=176.9 m:unemployment=7.5 m:childhood_lead_poisoning=0.5 m:below_poverty_level=22.7 m:per_capita_income=23714 m:prostate_cancer_in_males=21.7 m:teen_birth_rate=40.8 m:dependency=28.8 m:no_high_school_diploma=18.1 m:general_fertility_rate=62 m:gonorrhea_in_females=322.5 m:firearm_related=5.2 m:diabetes_related=77.1 m:infant_mortality_rate=6.4 m:low_birth_weight=11 m:preterm_births=11.2 m:colorectal_cancer=25.3 m:childhood_blood_lead_level_screening=364.7 m:assault_homicide=7.7 m:tuberculosis=11.4 m:lung_cancer=36.7 m:birth_rate=16.4 m:breast_cancer_in_females=23.3 m:stroke_cerebrovascular_disease=33.7 m:gonorrhea_in_males=423.3 m:crowded_housing=7.9

series e:iqnk-2tcu d:2013-05-30T07:08:51.000Z t:community_area_name="West Ridge" t:community_area=2 m:prenatal_care_beginning_in_first_trimester=71.1 m:cancer_all_sites=155.9 m:unemployment=7.9 m:childhood_lead_poisoning=1 m:below_poverty_level=15.1 m:per_capita_income=21375 m:prostate_cancer_in_males=14.2 m:teen_birth_rate=29.9 m:dependency=38.3 m:no_high_school_diploma=19.6 m:general_fertility_rate=83.3 m:gonorrhea_in_females=141 m:firearm_related=3.7 m:diabetes_related=60.5 m:infant_mortality_rate=5.1 m:low_birth_weight=8.1 m:preterm_births=8.3 m:colorectal_cancer=17.3 m:childhood_blood_lead_level_screening=331.4 m:assault_homicide=5.8 m:tuberculosis=8.9 m:lung_cancer=36 m:birth_rate=17.3 m:breast_cancer_in_females=20.2 m:stroke_cerebrovascular_disease=34.7 m:gonorrhea_in_males=205.7 m:crowded_housing=7

series e:iqnk-2tcu d:2013-05-30T07:08:51.000Z t:community_area_name=Uptown t:community_area=3 m:prenatal_care_beginning_in_first_trimester=77.7 m:cancer_all_sites=183.3 m:unemployment=7.7 m:childhood_lead_poisoning=0.5 m:below_poverty_level=22.7 m:per_capita_income=32355 m:prostate_cancer_in_males=25.2 m:teen_birth_rate=35.1 m:dependency=22.2 m:no_high_school_diploma=13.6 m:general_fertility_rate=50.5 m:gonorrhea_in_females=170.8 m:firearm_related=4.6 m:diabetes_related=80 m:infant_mortality_rate=6.5 m:low_birth_weight=8.3 m:preterm_births=10.3 m:colorectal_cancer=20.5 m:childhood_blood_lead_level_screening=353.7 m:assault_homicide=5.4 m:tuberculosis=13.6 m:lung_cancer=50.5 m:birth_rate=13.1 m:breast_cancer_in_females=21.3 m:stroke_cerebrovascular_disease=41.7 m:gonorrhea_in_males=468.7 m:crowded_housing=4.6
```

## Meta Commands

```ls
metric m:birth_rate p:float l:"Birth Rate" t:dataTypeName=number

metric m:general_fertility_rate p:float l:"General Fertility Rate" t:dataTypeName=number

metric m:low_birth_weight p:float l:"Low Birth Weight" t:dataTypeName=number

metric m:prenatal_care_beginning_in_first_trimester p:float l:"Prenatal Care Beginning in First Trimester" t:dataTypeName=number

metric m:preterm_births p:float l:"Preterm Births" t:dataTypeName=number

metric m:teen_birth_rate p:float l:"Teen Birth Rate" t:dataTypeName=number

metric m:assault_homicide p:float l:"Assault (Homicide)" t:dataTypeName=number

metric m:breast_cancer_in_females p:float l:"Breast cancer in females" t:dataTypeName=number

metric m:cancer_all_sites p:float l:"Cancer (All Sites)" t:dataTypeName=number

metric m:colorectal_cancer p:float l:"Colorectal Cancer" t:dataTypeName=number

metric m:diabetes_related p:float l:Diabetes-related t:dataTypeName=number

metric m:firearm_related p:float l:Firearm-related t:dataTypeName=number

metric m:infant_mortality_rate p:float l:"Infant Mortality Rate" t:dataTypeName=number

metric m:lung_cancer p:float l:"Lung Cancer" t:dataTypeName=number

metric m:prostate_cancer_in_males p:float l:"Prostate Cancer in Males" t:dataTypeName=number

metric m:stroke_cerebrovascular_disease p:float l:"Stroke (Cerebrovascular Disease)" t:dataTypeName=number

metric m:childhood_blood_lead_level_screening p:float l:"Childhood Blood Lead Level Screening" t:dataTypeName=number

metric m:childhood_lead_poisoning p:float l:"Childhood Lead Poisoning" t:dataTypeName=number

metric m:gonorrhea_in_females p:float l:"Gonorrhea in Females" t:dataTypeName=number

metric m:tuberculosis p:float l:Tuberculosis t:dataTypeName=number

metric m:below_poverty_level p:float l:"Below Poverty Level" t:dataTypeName=number

metric m:crowded_housing p:float l:"Crowded Housing" t:dataTypeName=number

metric m:dependency p:float l:Dependency t:dataTypeName=number

metric m:no_high_school_diploma p:float l:"No High School Diploma" t:dataTypeName=number

metric m:per_capita_income p:integer l:"Per Capita Income" t:dataTypeName=number

metric m:unemployment p:double l:Unemployment t:dataTypeName=number

entity e:iqnk-2tcu l:"Public Health Statistics- Selected public health indicators by Chicago community area" t:attribution="Illinois Department of Public Health (IDPH) and U.S. Census Bureau" t:url=https://data.cityofchicago.org/api/views/iqnk-2tcu

property e:iqnk-2tcu t:meta.view v:id=iqnk-2tcu v:category="Health & Human Services" v:averageRating=100 v:name="Public Health Statistics- Selected public health indicators by Chicago community area" v:attribution="Illinois Department of Public Health (IDPH) and U.S. Census Bureau"

property e:iqnk-2tcu t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:iqnk-2tcu t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| :updated_at | community_area | community_area_name | birth_rate | general_fertility_rate | low_birth_weight | prenatal_care_beginning_in_first_trimester | preterm_births | teen_birth_rate | assault_homicide | breast_cancer_in_females | cancer_all_sites | colorectal_cancer | diabetes_related | firearm_related | infant_mortality_rate | lung_cancer | prostate_cancer_in_males | stroke_cerebrovascular_disease | childhood_blood_lead_level_screening | childhood_lead_poisoning | gonorrhea_in_females | gonorrhea_in_males | tuberculosis | below_poverty_level | crowded_housing | dependency | no_high_school_diploma | per_capita_income | unemployment | 
| =========== | ============== | =================== | ========== | ====================== | ================ | ========================================== | ============== | =============== | ================ | ======================== | ================ | ================= | ================ | =============== | ===================== | =========== | ======================== | ============================== | ==================================== | ======================== | ==================== | ================== | ============ | =================== | =============== | ========== | ====================== | ================= | ============ | 
| 1369897731  | 1              | Rogers Park         | 16.4       | 62                     | 11               | 73                                         | 11.2           | 40.8            | 7.7              | 23.3                     | 176.9            | 25.3              | 77.1             | 5.2             | 6.4                   | 36.7        | 21.7                     | 33.7                           | 364.7                                | 0.5                      | 322.5                | 423.3              | 11.4         | 22.7                | 7.9             | 28.8       | 18.1                   | 23714             | 7.5          | 
| 1369897731  | 2              | West Ridge          | 17.3       | 83.3                   | 8.1              | 71.1                                       | 8.3            | 29.9            | 5.8              | 20.2                     | 155.9            | 17.3              | 60.5             | 3.7             | 5.1                   | 36          | 14.2                     | 34.7                           | 331.4                                | 1                        | 141                  | 205.7              | 8.9          | 15.1                | 7               | 38.3       | 19.6                   | 21375             | 7.9          | 
| 1369897731  | 3              | Uptown              | 13.1       | 50.5                   | 8.3              | 77.7                                       | 10.3           | 35.1            | 5.4              | 21.3                     | 183.3            | 20.5              | 80               | 4.6             | 6.5                   | 50.5        | 25.2                     | 41.7                           | 353.7                                | 0.5                      | 170.8                | 468.7              | 13.6         | 22.7                | 4.6             | 22.2       | 13.6                   | 32355             | 7.7          | 
| 1369897731  | 4              | Lincoln Square      | 17.1       | 61                     | 8.1              | 80.5                                       | 9.7            | 38.4            | 5                | 21.7                     | 153.2            | 8.6               | 55.4             | 6.1             | 3.8                   | 43.1        | 27.6                     | 36.9                           | 273.3                                | 0.4                      | 98.8                 | 195.5              | 8.5          | 9.5                 | 3.1             | 25.6       | 12.5                   | 35503             | 6.8          | 
| 1369897731  | 5              | North Center        | 22.4       | 76.2                   | 9.1              | 80.4                                       | 9.8            | 8.4             | 1                | 16.6                     | 152.1            | 26.1              | 49.8             | 1               | 2.7                   | 42.4        | 15.1                     | 41.6                           | 178.1                                | 0.9                      | 85.4                 | 188.6              | 1.9          | 7.1                 | 0.2             | 25.5       | 5.4                    | 51615             | 4.5          | 
| 1369897731  | 6              | Lake View           | 13.5       | 38.7                   | 6.3              | 79.1                                       | 8.1            | 15.8            | 1.4              | 20.1                     | 126.9            | 13                | 38.5             | 1.8             | 2.2                   | 32.5        | 17                       | 24.4                           | 179.2                                | 0.4                      | 81.8                 | 357.6              | 3.2          | 10.5                | 1.2             | 16.5       | 2.9                    | 58227             | 4.7          | 
| 1369897731  | 7              | Lincoln Park        | 13.2       | 38.7                   | 6.6              | 75.7                                       | 7.8            | 2.1             | 0.7              | 23.7                     | 152.9            | 16.7              | 50.1             | 2.3             | 2.4                   | 40          | 27.3                     | 35.3                           | 173.3                                | 0.6                      | 50.3                 | 93.1               | 1.2          | 11.8                | 0.6             | 20.4       | 4.3                    | 71403             | 4.5          | 
| 1369897731  | 8              | Near North Side     | 10.7       | 35.9                   | 8.6              | 69.7                                       | 9.6            | 34              | 3.7              | 24                       | 142.7            | 15.1              | 27               | 3.2             | 6.5                   | 33.6        | 15.1                     | 22                             | 311.2                                | 0.1                      | 244.4                | 235.8              | 5.5          | 13.4                | 2               | 23.3       | 3.4                    | 87163             | 5.2          | 
| 1369897731  | 9              | Edison Park         | 11.3       | 59.5                   | 7.9              | 86.6                                       | 12.6           | 3.9             | 0                | 13.8                     | 189.7            | 15.1              | 53               | 7.1             | 4.6                   | 45.2        | 28                       | 38.9                           | 134.7                                | 0                        |                      | .                  | 1.8          | 5.1                 | 0.6             | 36.6       | 8.5                    | 38337             | 7.4          | 
| 1369897731  | 10             | Norwood Park        | 10.4       | 59.6                   | 4.9              | 89.4                                       | 8.3            | 3.4             | 4.7              | 20.7                     | 180.8            | 18.9              | 47.3             | 8.7             | 4.4                   | 44.5        | 26.4                     | 45.2                           | 163.1                                | 0                        |                      | .                  | 1.6          | 5.9                 | 2.3             | 40.6       | 13.5                   | 31659             | 7.3          | 
```