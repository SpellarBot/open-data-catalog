# Youth Tobacco Survey (YTS) Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/youth-tobacco-survey-yts-data-78590) |
| Metadata | [Link](https://data.cdc.gov/api/views/4juz-x2tp) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/4juz-x2tp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/4juz-x2tp/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 4juz-x2tp |
| Name | Youth Tobacco Survey (YTS) Data |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Survey Data |
| Tags | osh, office on smoking and health, state system, tobacco, survey, youth, middle school, high school, tobacco use, cigarette, cigarette use, smoking, smoking status, smoker, current, frequent, ever... |
| Created | 2014-06-03T15:46:39Z |
| Publication Date | 2017-03-15T15:23:49Z |

## Description

1999-2015.  Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  YTS Data.  The YTS was developed to provide states with comprehensive data on both middle school and high school students regarding tobacco use, exposure to environmental tobacco smoke, smoking cessation, school curriculum, minors' ability to purchase or otherwise obtain tobacco products, knowledge and attitudes about tobacco, and familiarity with pro-tobacco and anti-tobacco media messages.  The YTS uses a two-stage cluster sample design to produce representative samples of students in middle schools (grades 6?8) and high schools (grades 9?12).  The data for the STATE System were extracted from Youth Tobacco Surveys from participating states.  Tobacco topics included are cigarette smoking prevalence, cigarette smoking frequency, smokeless tobacco products prevalence and quit attempts.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | YEAR                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | topictype                  | TopicType                  | text      | text        |
| Yes      | series tag     | topicdesc                  | TopicDesc                  | text      | text        |
| Yes      | series tag     | measuredesc                | MeasureDesc                | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | response                   | Response                   | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | data_value_std_err         | Data_Value_Std_Err         | number    | number      |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | gender                     | Gender                     | text      | text        |
| Yes      | series tag     | race                       | Race                       | text      | text        |
| Yes      | series tag     | age                        | Age                        | text      | text        |
| Yes      | series tag     | education                  | Education                  | text      | text        |
| Yes      | series tag     | topictypeid                | TopicTypeId                | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | measureid                  | MeasureId                  | text      | text        |
| Yes      | series tag     | stratificationid1          | StratificationID1          | text      | text        |
| Yes      | series tag     | stratificationid2          | StratificationID2          | text      | text        |
| Yes      | series tag     | stratificationid3          | StratificationID3          | text      | text        |
| Yes      | series tag     | stratificationid4          | StratificationID4          | text      | text        |
| Yes      | series tag     | submeasureid               | SubMeasureID               | text      | text        |
| No       |                | displayorder               | DisplayOrder               | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote,displayorder
```

## Data Commands

```ls
series e:4juz-x2tp d:2015-01-01T00:00:00.000Z t:stratificationid4=1EDU t:locationdesc=Arizona t:locationabbr=AZ t:stratificationid3=6RAC t:topicid=106BEH t:stratificationid2=8AGE t:stratificationid1=1GEN t:measuredesc="Smoking Status" t:measureid=166SSA t:topicdesc="Cigarette Use (Youth)" t:education="Middle School" t:race="All Races" t:response=Current t:age="All Ages" t:topictype="Tobacco Use ? Survey Data" t:gender=Overall t:submeasureid=YTS07 t:datasource=YTS t:topictypeid=BEH m:data_value_std_err=1.5 m:high_confidence_limit=6.1 m:sample_size=1377 m:data_value=3.2 m:low_confidence_limit=0.3

series e:4juz-x2tp d:2015-01-01T00:00:00.000Z t:stratificationid4=1EDU t:locationdesc=Arizona t:locationabbr=AZ t:stratificationid3=6RAC t:topicid=106BEH t:stratificationid2=8AGE t:stratificationid1=2GEN t:measuredesc="Smoking Status" t:measureid=166SSA t:topicdesc="Cigarette Use (Youth)" t:education="Middle School" t:race="All Races" t:response=Current t:age="All Ages" t:topictype="Tobacco Use ? Survey Data" t:gender=Male t:submeasureid=YTS07 t:datasource=YTS t:topictypeid=BEH m:data_value_std_err=1.5 m:high_confidence_limit=6.2 m:sample_size=700 m:data_value=3.2 m:low_confidence_limit=0.3

series e:4juz-x2tp d:2015-01-01T00:00:00.000Z t:stratificationid4=1EDU t:locationdesc=Arizona t:locationabbr=AZ t:stratificationid3=6RAC t:topicid=106BEH t:stratificationid2=8AGE t:stratificationid1=3GEN t:measuredesc="Smoking Status" t:measureid=166SSA t:topicdesc="Cigarette Use (Youth)" t:education="Middle School" t:race="All Races" t:response=Current t:age="All Ages" t:topictype="Tobacco Use ? Survey Data" t:gender=Female t:submeasureid=YTS07 t:datasource=YTS t:topictypeid=BEH m:data_value_std_err=1.6 m:high_confidence_limit=6.1 m:sample_size=671 m:data_value=3.1 m:low_confidence_limit=0.1
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:"Value of the data" t:dataTypeName=number

metric m:data_value_std_err p:float l:Data_Value_Std_Err d:"Confidence interval lower limit" t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit d:"Confidence interval upper limit" t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size d:"Sample size" t:dataTypeName=number

entity e:4juz-x2tp l:"Youth Tobacco Survey (YTS) Data" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/4juz-x2tp

property e:4juz-x2tp t:meta.view v:id=4juz-x2tp v:category="Survey Data" v:attributionLink=http://www.cdc.gov/tobacco/data_statistics/surveys/yts/index.htm v:averageRating=0 v:name="Youth Tobacco Survey (YTS) Data" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:4juz-x2tp t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:4juz-x2tp t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:4juz-x2tp t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | topictype                 | topicdesc             | measuredesc                                               | datasource | response | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote                                                     | data_value_std_err | low_confidence_limit | high_confidence_limit | sample_size | gender  | race      | age      | education     | topictypeid | topicid | measureid | stratificationid1 | stratificationid2 | stratificationid3 | stratificationid4 | submeasureid | displayorder | 
| ==== | ============ | ============ | ========================= | ===================== | ========================================================= | ========== | ======== | =============== | =============== | ========== | ========================== | ======================================================================= | ================== | ==================== | ===================== | =========== | ======= | ========= | ======== | ============= | =========== | ======= | ========= | ================= | ================= | ================= | ================= | ============ | ============ | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cessation (Youth)     | Percent of Current Smokers Who Want to Quit               | YTS        |          | %               | Percentage      |            | *                          | Data in these cells have been suppressed because of a small sample size |                    |                      |                       |             | Overall | All Races | All Ages | Middle School | BEH         | 105BEH  | 170CES    | 1GEN              | 8AGE              | 6RAC              | 1EDU              | YTS01        | 1            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cessation (Youth)     | Percent of Current Smokers Who Want to Quit               | YTS        |          | %               | Percentage      |            | *                          | Data in these cells have been suppressed because of a small sample size |                    |                      |                       |             | Male    | All Races | All Ages | Middle School | BEH         | 105BEH  | 170CES    | 2GEN              | 8AGE              | 6RAC              | 1EDU              | YTS02        | 2            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cessation (Youth)     | Percent of Current Smokers Who Want to Quit               | YTS        |          | %               | Percentage      |            | *                          | Data in these cells have been suppressed because of a small sample size |                    |                      |                       |             | Female  | All Races | All Ages | Middle School | BEH         | 105BEH  | 170CES    | 3GEN              | 8AGE              | 6RAC              | 1EDU              | YTS03        | 3            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cessation (Youth)     | Quit Attempt in Past Year Among Current Cigarette Smokers | YTS        |          | %               | Percentage      |            | *                          | Data in these cells have been suppressed because of a small sample size |                    |                      |                       |             | Overall | All Races | All Ages | Middle School | BEH         | 105BEH  | 169QUA    | 1GEN              | 8AGE              | 6RAC              | 1EDU              | YTS04        | 4            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cessation (Youth)     | Quit Attempt in Past Year Among Current Cigarette Smokers | YTS        |          | %               | Percentage      |            | *                          | Data in these cells have been suppressed because of a small sample size |                    |                      |                       |             | Male    | All Races | All Ages | Middle School | BEH         | 105BEH  | 169QUA    | 2GEN              | 8AGE              | 6RAC              | 1EDU              | YTS05        | 5            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cessation (Youth)     | Quit Attempt in Past Year Among Current Cigarette Smokers | YTS        |          | %               | Percentage      |            | *                          | Data in these cells have been suppressed because of a small sample size |                    |                      |                       |             | Female  | All Races | All Ages | Middle School | BEH         | 105BEH  | 169QUA    | 3GEN              | 8AGE              | 6RAC              | 1EDU              | YTS06        | 6            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cigarette Use (Youth) | Smoking Status                                            | YTS        | Current  | %               | Percentage      | 3.2        |                            |                                                                         | 1.5                | 0.3                  | 6.1                   | 1377        | Overall | All Races | All Ages | Middle School | BEH         | 106BEH  | 166SSA    | 1GEN              | 8AGE              | 6RAC              | 1EDU              | YTS07        | 7            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cigarette Use (Youth) | Smoking Status                                            | YTS        | Current  | %               | Percentage      | 3.2        |                            |                                                                         | 1.5                | 0.3                  | 6.2                   | 700         | Male    | All Races | All Ages | Middle School | BEH         | 106BEH  | 166SSA    | 2GEN              | 8AGE              | 6RAC              | 1EDU              | YTS07        | 7            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cigarette Use (Youth) | Smoking Status                                            | YTS        | Current  | %               | Percentage      | 3.1        |                            |                                                                         | 1.6                | 0.1                  | 6.1                   | 671         | Female  | All Races | All Ages | Middle School | BEH         | 106BEH  | 166SSA    | 3GEN              | 8AGE              | 6RAC              | 1EDU              | YTS07        | 7            | 
| 2015 | AZ           | Arizona      | Tobacco Use ? Survey Data | Cigarette Use (Youth) | Smoking Status                                            | YTS        | Ever     | %               | Percentage      | 12.5       |                            |                                                                         | 2.7                | 7.2                  | 17.9                  | 1331        | Overall | All Races | All Ages | Middle School | BEH         | 106BEH  | 166SSA    | 1GEN              | 8AGE              | 6RAC              | 1EDU              | YTS08        | 8            | 
```