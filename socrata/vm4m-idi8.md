# CDC Best Practices for Comprehensive Tobacco Control Programs - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-best-practices-for-comprehensive-tobacco-control-programs-2014-23fdf) |
| Metadata | [Link](https://data.cdc.gov/api/views/vm4m-idi8) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vm4m-idi8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vm4m-idi8/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vm4m-idi8 |
| Name | CDC Best Practices for Comprehensive Tobacco Control Programs - 2014 |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Funding |
| Tags | centers for disease control and prevention, osh, office on smoking and health, best practices, best practices for comprehensive tobacco control programs, tobacco, administration and management, ce... |
| Created | 2014-05-07T17:24:05Z |
| Publication Date | 2017-02-06T17:26:57Z |

## Description

2014. Centers for Disease Control and Prevention (CDC). Best Practices for Comprehensive Tobacco Control Programs. Funding. CDC's Best Practices for Comprehensive Tobacco Control Programs is an evidence-based guide to help states plan and establish effective tobacco control programs to prevent and reduce tobacco use.  These data update Best Practices for Comprehensive Tobacco Control Programs?2007.  Data are reported at total and per capita funding levels. Data include recommended and minimum total funding levels for state programs, in addition to funding breakdowns by intervention areas such as: State and Community Interventions, Mass-Reach Health Communication Interventions, Cessation Interventions, Surveillance and Evaluation, and Infrastructure, Administration, and Management.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | time           | year              | Year              | number    | number      |
| Yes      | series tag     | locationabbr      | LocationAbbr      | text      | text        |
| Yes      | series tag     | locationdesc      | LocationDesc      | text      | text        |
| Yes      | series tag     | intervention_area | Intervention Area | text      | text        |
| Yes      | series tag     | funding_type1     | Funding Type1     | text      | text        |
| Yes      | series tag     | funding_type2     | Funding Type2     | text      | text        |
| Yes      | numeric metric | amount            | Amount            | number    | number      |
| No       |                | data_value_unit   | Data_Value_Unit   | text      | text        |
| Yes      | series tag     | source            | Source            | text      | text        |
| Yes      | series tag     | topictypeid       | TopicTypeId       | text      | text        |
| Yes      | series tag     | topicid           | TopicId           | text      | text        |
| Yes      | series tag     | measureid         | MeasureId         | text      | text        |
| Yes      | series tag     | submeasureid      | SubMeasureID      | text      | text        |
| No       |                | displayorder      | DisplayOrder      | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,displayorder
```

## Data Commands

```ls
series e:vm4m-idi8 d:2014-01-01T00:00:00.000Z t:funding_type1="Total (Millions)" t:locationabbr=US t:locationdesc="United States" t:funding_type2=Recommended t:topicid=400FND t:source="Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014." t:measureid=402CDT2 t:intervention_area="Infrastructure, Administration, and Management" t:submeasureid=INTA002 t:topictypeid=FND m:amount=143.7

series e:vm4m-idi8 d:2014-01-01T00:00:00.000Z t:funding_type1="Per Capita" t:locationabbr=AL t:locationdesc=Alabama t:funding_type2=Recommended t:topicid=400FND t:source="Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014." t:measureid=402CDT2 t:intervention_area="Mass-Reach Health Communication Interventions" t:submeasureid=INTA003 t:topictypeid=FND m:amount=1.24

series e:vm4m-idi8 d:2014-01-01T00:00:00.000Z t:funding_type1="Per Capita" t:locationabbr=AL t:locationdesc=Alabama t:funding_type2=Recommended t:topicid=400FND t:source="Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014." t:measureid=402CDT2 t:intervention_area="Cessation Interventions" t:submeasureid=INTA001 t:topictypeid=FND m:amount=5.1
```

## Meta Commands

```ls
metric m:amount p:float l:Amount d:"Amount of funding" t:dataTypeName=number

entity e:vm4m-idi8 l:"CDC Best Practices for Comprehensive Tobacco Control Programs - 2014" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/vm4m-idi8

property e:vm4m-idi8 t:meta.view v:id=vm4m-idi8 v:category=Funding v:attributionLink=http://www.cdc.gov/tobacco/stateandcommunity/best_practices/ v:averageRating=0 v:name="CDC Best Practices for Comprehensive Tobacco Control Programs - 2014" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:vm4m-idi8 t:meta.view.license v:name="Public Domain"

property e:vm4m-idi8 t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:vm4m-idi8 t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:vm4m-idi8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc  | intervention_area                              | funding_type1    | funding_type2 | amount | data_value_unit | source                                                                                                        | topictypeid | topicid | measureid | submeasureid | displayorder | 
| ==== | ============ | ============= | ============================================== | ================ | ============= | ====== | =============== | ============================================================================================================= | =========== | ======= | ========= | ============ | ============ | 
| 2014 | US           | United States | Infrastructure, Administration, and Management | Total (Millions) | Recommended   | 143.7  | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA002      | 02           | 
| 2014 | AL           | Alabama       | Mass-Reach Health Communication Interventions  | Per Capita       | Recommended   | 1.24   | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA003      | 03           | 
| 2014 | AL           | Alabama       | Cessation Interventions                        | Per Capita       | Recommended   | 5.1    | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA001      | 01           | 
| 2014 | AL           | Alabama       | Surveillance and Evaluation                    | Per Capita       | Recommended   | 1.01   | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA005      | 05           | 
| 2014 | AL           | Alabama       | Infrastructure, Administration, and Management | Per Capita       | Recommended   | 0.5    | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA002      | 02           | 
| 2014 | AL           | Alabama       | Total Program Costs                            | Per Capita       | Minimum       | 8.11   | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA006      | 06           | 
| 2014 | AL           | Alabama       | State and Community Interventions              | Per Capita       | Minimum       | 2.99   | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA004      | 04           | 
| 2014 | AL           | Alabama       | Mass-Reach Health Communication Interventions  | Per Capita       | Minimum       | 0.87   | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA003      | 03           | 
| 2014 | AL           | Alabama       | Cessation Interventions                        | Per Capita       | Minimum       | 3.19   | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA001      | 01           | 
| 2014 | AL           | Alabama       | Surveillance and Evaluation                    | Per Capita       | Minimum       | 0.71   | $               | Centers for Disease Control and Prevention. Best Practices for Comprehensive Tobacco Control Programs ? 2014. | FND         | 400FND  | 402CDT2   | INTA005      | 05           | 
```