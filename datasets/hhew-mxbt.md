# Healthy People 2020 Tobacco Use Objectives

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/healthy-people-2020-tobacco-use-objectives-71bdc) |
| Metadata | [Link](https://data.cdc.gov/api/views/hhew-mxbt) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hhew-mxbt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hhew-mxbt/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hhew-mxbt |
| Name | Healthy People 2020 Tobacco Use Objectives |
| Category | Healthy People 2020 |
| Tags | department of health and human services, centers for disease control and prevention, osh, office on smoking and health, healthy people 2020, leading health indicator |
| Created | 2014-06-05T12:01:47Z |
| Publication Date | 2016-10-21T13:20:39Z |

## Description

U.S. Department of Health and Human Services (HHS). Centers for Disease Control and Prevention (CDC). Healthy People 2020 Tobacco Use Objectives. Healthy People 2020. Healthy People 2020 provides a framework for action to reduce tobacco use to the point that it is no longer a public health problem for the Nation. This dataset includes information related to the Healthy People 2020 Tobacco Use objectives, operational definitions, baselines, and targets. Baseline years may vary by objective. Targets represented correspond to the year 2020.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | topic_area               | Topic Area               | text          | text          |
| Yes      | series tag     | key_area                 | Key Area                 | text          | text          |
| Yes      | series tag     | objective_number         | Objective Number         | text          | text          |
| Yes      | series tag     | leading_health_indicator | Leading Health Indicator | text          | text          |
| Yes      | series tag     | developmental            | Developmental            | text          | text          |
| Yes      | series tag     | main_objective_text      | Main Objective Text      | text          | text          |
| Yes      | series tag     | specific_objective_text  | Specific Objective Text  | text          | text          |
| Yes      | numeric metric | target                   | Target                   | number        | number        |
| Yes      | numeric metric | baseline                 | Baseline                 | number        | number        |
| No       |                | symbol                   | Symbol                   | text          | text          |
| Yes      | series tag     | units                    | Units                    | text          | text          |
| Yes      | series tag     | baseline_statement       | Baseline Statement       | text          | text          |
| Yes      | time           | baseline_year            | Baseline Year            | calendar_date | calendar_date |
| Yes      | series tag     | targetsettingmethodology | TargetSettingMethodology | text          | text          |
| Yes      | series tag     | datasource               | DataSource               | text          | text          |
| Yes      | series tag     | objective_details        | Objective Details        | text          | text          |
```

## Time Field

```ls
Value = baseline_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = symbol
```

## Data Commands

```ls
series e:hhew-mxbt d:2008-01-01T00:00:00.000Z t:objective_details=http://www.healthypeople.gov/node/5287/data_details t:main_objective_text="Reduce tobacco use by adults" t:topic_area="Tobacco Use" t:leading_health_indicator="LHI: Leading Health Indicators are a subset of Healthy People 2020 objectives selected to communicate high-priority health issues." t:targetsettingmethodology="Retain Healthy People 2010 target of 12 percent" t:key_area="Tobacco Use Prevalence" t:objective_number=TU-1.1 t:baseline_statement="20.6 percent of adults aged 18 years and older were current cigarette smokers in 2008 (age adjusted to the year 2000 standard population)" t:specific_objective_text="Reduce cigarette smoking by adults" t:datasource="National Health Interview Survey (NHIS), CDC, NCHS" t:units=Percent m:target=12 m:baseline=20.6

series e:hhew-mxbt d:2005-01-01T00:00:00.000Z t:objective_details=http://www.healthypeople.gov/node/5288/data_details t:main_objective_text="Reduce tobacco use by adults" t:topic_area="Tobacco Use" t:targetsettingmethodology="2 percentage point improvement" t:key_area="Tobacco Use Prevalence" t:objective_number=TU-1.2 t:baseline_statement="2.3 percent of adults aged 18 years and older were current users of snuff or chewing tobacco products in 2005 (age adjusted to the year 2000 standard population)" t:specific_objective_text="Reduce use of smokeless tobacco products by adults" t:datasource="National Health Interview Survey (NHIS), CDC, NCHS" t:units=Percent m:target=0.3 m:baseline=2.3

series e:hhew-mxbt d:2005-01-01T00:00:00.000Z t:objective_details=http://www.healthypeople.gov/node/5289/data_details t:main_objective_text="Reduce tobacco use by adults" t:topic_area="Tobacco Use" t:targetsettingmethodology="2 percentage point improvement" t:key_area="Tobacco Use Prevalence" t:objective_number=TU-1.3 t:baseline_statement="2.2 percent of adults aged 18 years and older were current cigar smokers in 2005 (age adjusted to the year 2000 standard population)" t:specific_objective_text="Reduce use of cigars by adults" t:datasource="National Health Interview Survey (NHIS), CDC, NCHS" t:units=Percent m:target=0.2 m:baseline=2.2
```

## Meta Commands

```ls
metric m:target p:double l:Target t:dataTypeName=number

metric m:baseline p:float l:Baseline t:dataTypeName=number

entity e:hhew-mxbt l:"Healthy People 2020 Tobacco Use Objectives" t:url=https://data.cdc.gov/api/views/hhew-mxbt

property e:hhew-mxbt t:meta.view v:id=hhew-mxbt v:category="Healthy People 2020" v:averageRating=0 v:name="Healthy People 2020 Tobacco Use Objectives"

property e:hhew-mxbt t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:hhew-mxbt t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:hhew-mxbt t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| topic_area  | key_area               | objective_number | leading_health_indicator                                                                                                           | developmental | main_objective_text                                                                | specific_objective_text                                                                                        | target | baseline           | symbol | units   | baseline_statement                                                                                                                                                                         | baseline_year       | targetsettingmethodology                        | datasource                                                    | objective_details                                   | 
| =========== | ====================== | ================ | ================================================================================================================================== | ============= | ================================================================================== | ============================================================================================================== | ====== | ================== | ====== | ======= | ========================================================================================================================================================================================== | =================== | =============================================== | ============================================================= | =================================================== | 
| Tobacco Use | Tobacco Use Prevalence | TU-1.1           | LHI: Leading Health Indicators are a subset of Healthy People 2020 objectives selected to communicate high-priority health issues. |               | Reduce tobacco use by adults                                                       | Reduce cigarette smoking by adults                                                                             | 12     | 20.6               | %      | Percent | 20.6 percent of adults aged 18 years and older were current cigarette smokers in 2008 (age adjusted to the year 2000 standard population)                                                  | 2008-01-01T00:00:00 | Retain Healthy People 2010 target of 12 percent | National Health Interview Survey (NHIS), CDC, NCHS            | http://www.healthypeople.gov/node/5287/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-1.2           |                                                                                                                                    |               | Reduce tobacco use by adults                                                       | Reduce use of smokeless tobacco products by adults                                                             | 0.3    | 2.2999999999999998 | %      | Percent | 2.3 percent of adults aged 18 years and older were current users of snuff or chewing tobacco products in 2005 (age adjusted to the year 2000 standard population)                          | 2005-01-01T00:00:00 | 2 percentage point improvement                  | National Health Interview Survey (NHIS), CDC, NCHS            | http://www.healthypeople.gov/node/5288/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-1.3           |                                                                                                                                    |               | Reduce tobacco use by adults                                                       | Reduce use of cigars by adults                                                                                 | 0.2    | 2.2000000000000002 | %      | Percent | 2.2 percent of adults aged 18 years and older were current cigar smokers in 2005 (age adjusted to the year 2000 standard population)                                                       | 2005-01-01T00:00:00 | 2 percentage point improvement                  | National Health Interview Survey (NHIS), CDC, NCHS            | http://www.healthypeople.gov/node/5289/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-2.1           |                                                                                                                                    |               | Reduce tobacco use by adolescents                                                  | Reduce use of tobacco products by adolescents (past month)                                                     | 21     | 26                 | %      | Percent | 26.0 percent of adolescents in grades 9 through 12 used cigarettes, chewing tobacco, snuff, or cigars in the past 30 days in 2009                                                          | 2009-01-01T00:00:00 | Retain Healthy People 2010 target               | Youth Risk Behavior Surveillance System (YRBSS), CDC, NCCDPHP | http://www.healthypeople.gov/node/5341/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-2.2           | LHI: Leading Health Indicators are a subset of Healthy People 2020 objectives selected to communicate high-priority health issues. |               | Reduce tobacco use by adolescents                                                  | Reduce use of cigarettes by adolescents (past month)                                                           | 16     | 19.5               | %      | Percent | 19.5 percent of adolescents in grades 9 through 12 smoked cigarettes in the past 30 days in 2009                                                                                           | 2009-01-01T00:00:00 | Retain Healthy People 2010 target of 16 percent | Youth Risk Behavior Surveillance System (YRBSS), CDC, NCCDPHP | http://www.healthypeople.gov/node/5342/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-2.3           |                                                                                                                                    |               | Reduce tobacco use by adolescents                                                  | Reduce use of smokeless tobacco products by adolescents (past month)                                           | 6.9    | 8.9                | %      | Percent | 8.9 percent of adolescents in grades 9 through 12 used smokeless (chewing tobacco or snuff) tobacco products in the past 30 days in 2009                                                   | 2009-01-01T00:00:00 | 2 percentage point improvement                  | Youth Risk Behavior Surveillance System (YRBSS), CDC, NCCDPHP | http://www.healthypeople.gov/node/5343/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-2.4           |                                                                                                                                    |               | Reduce tobacco use by adolescents                                                  | Reduce use of cigars by adolescents (past month)                                                               | 8      | 14                 | %      | Percent | 14.0 percent of adolescents in grades 9 through 12 smoked cigars in the past 30 days in 2009                                                                                               | 2009-01-01T00:00:00 | Retain Healthy People 2010 target of 8 percent  | Youth Risk Behavior Surveillance System (YRBSS), CDC, NCCDPHP | http://www.healthypeople.gov/node/5344/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-3.1           |                                                                                                                                    |               | Reduce the initiation of tobacco use among children, adolescents, and young adults | Reduce the initiation of the use of tobacco products by children and adolescents aged 12 to 17 years           | 5.8    | 7.8                | %      | Percent | 7.8 percent of children and adolescents aged 12 to 17 years who had not previously used tobacco products in their lifetime first used tobacco products in the past 12 months in 2008       | 2008-01-01T00:00:00 | 2 percentage point improvement                  | National Survey on Drug Use and Health (NSDUH), SAMHSA        | http://www.healthypeople.gov/node/5350/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-3.2           |                                                                                                                                    |               | Reduce the initiation of tobacco use among children, adolescents, and young adults | Reduce the initiation of the use of cigarettes by children and adolescents aged 12 to 17 years                 | 4.3    | 6.3                | %      | Percent | 6.3 percent of children and adolescents aged 12 to 17 years who had not previously smoked cigarettes in their lifetime first smoked cigarettes in the past 12 months in 2008               | 2008-01-01T00:00:00 | 2 percentage point improvement                  | National Survey on Drug Use and Health (NSDUH), SAMHSA        | http://www.healthypeople.gov/node/5351/data_details | 
| Tobacco Use | Tobacco Use Prevalence | TU-3.3           |                                                                                                                                    |               | Reduce the initiation of tobacco use among children, adolescents, and young adults | Reduce the initiation of the use of smokeless tobacco products by children and adolescents aged 12 to 17 years | 0.6    | 2.6                | %      | Percent | 2.6 percent of children and adolescents aged 12 to 17 years who had not previously used smokeless tobacco in their lifetime first used smokeless tobacco in the previous 12 months in 2008 | 2008-01-01T00:00:00 | 2 percentage point improvement                  | National Survey on Drug Use and Health (NSDUH), SAMHSA        | http://www.healthypeople.gov/node/5352/data_details | 
```