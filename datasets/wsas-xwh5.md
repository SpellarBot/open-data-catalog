# Behavioral Risk Factor Data: Tobacco Use (2011 to present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-data-tobacco-use-2011-to-present) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/wsas-xwh5) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/wsas-xwh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/wsas-xwh5/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | wsas-xwh5 |
| Name | Behavioral Risk Factor Data: Tobacco Use (2011 to present) |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Survey Data |
| Tags | osh, office on smoking and health, state system, tobacco, survey, behavioral, risk, surveillance, tobacco use, cigarette, cigarette use, adult, smoking, smoking status, smoker, current, former, ne... |
| Created | 2014-06-03T17:16:51Z |
| Publication Date | 2017-02-06T16:36:48Z |

## Description

2011-2015. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  BRFSS Survey Data.  The BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. The data for the STATE System were extracted from the annual BRFSS surveys from participating states.  Tobacco topics included are cigarette smoking status, cigarette smoking prevalence by demographics, cigarette smoking frequency, and quit attempts. NOTE: these data are not to be compared with BRFSS data collected 2010 and prior, as the methodologies were changed. Please refer to the FAQs / Methodology sections for more details.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | YEAR                       | text      | text        |
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
series e:wsas-xwh5 d:2014-01-01T00:00:00.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=5RAC t:topicid=100BEH t:stratificationid2=8AGE t:stratificationid1=1GEN t:measuredesc="Current Smoking ? (2 yrs ? Race/Ethnicity)" t:measureid=112CS2 t:topicdesc="Cigarette Use (Adults)" t:education="All Grades" t:race=White t:age="All Ages" t:gender=Overall t:topictype="Tobacco Use ? Survey Data" t:submeasureid=BRF34 t:datasource=BRFSS t:topictypeid=BEH m:data_value_std_err=0.6 m:high_confidence_limit=23.1 m:sample_size=11114 m:data_value=21.9 m:low_confidence_limit=20.7

series e:wsas-xwh5 d:2014-01-01T00:00:00.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=1RAC t:topicid=100BEH t:stratificationid2=8AGE t:stratificationid1=1GEN t:measuredesc="Current Smoking ? (2 yrs ? Race/Ethnicity)" t:measureid=112CS2 t:topicdesc="Cigarette Use (Adults)" t:education="All Grades" t:race="African American" t:age="All Ages" t:gender=Overall t:topictype="Tobacco Use ? Survey Data" t:submeasureid=BRF30 t:datasource=BRFSS t:topictypeid=BEH m:data_value_std_err=1 m:high_confidence_limit=22 m:sample_size=4016 m:data_value=20.1 m:low_confidence_limit=18.2

series e:wsas-xwh5 d:2014-01-01T00:00:00.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=4RAC t:topicid=100BEH t:stratificationid2=8AGE t:stratificationid1=1GEN t:measuredesc="Current Smoking ? (2 yrs ? Race/Ethnicity)" t:measureid=112CS2 t:topicdesc="Cigarette Use (Adults)" t:education="All Grades" t:race=Hispanic t:age="All Ages" t:gender=Overall t:topictype="Tobacco Use ? Survey Data" t:submeasureid=BRF33 t:datasource=BRFSS t:topictypeid=BEH m:data_value_std_err=4 m:high_confidence_limit=27.2 m:sample_size=164 m:data_value=19.4 m:low_confidence_limit=11.6
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Value of the data" t:dataTypeName=number

metric m:data_value_std_err p:float l:Data_Value_Std_Err d:"Standard Error for the data value" t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit d:"Confidence interval lower limit" t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit d:"Confidence interval upper limit" t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size d:"Sample size" t:dataTypeName=number

entity e:wsas-xwh5 l:"Behavioral Risk Factor Data: Tobacco Use (2011 to present)" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/wsas-xwh5

property e:wsas-xwh5 t:meta.view v:id=wsas-xwh5 v:category="Survey Data" v:attributionLink=http://www.cdc.gov/brfss/ v:averageRating=0 v:name="Behavioral Risk Factor Data: Tobacco Use (2011 to present)" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:wsas-xwh5 t:meta.view.license v:name="Public Domain"

property e:wsas-xwh5 t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:wsas-xwh5 t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:wsas-xwh5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year      | locationabbr | locationdesc | topictype                 | topicdesc              | measuredesc                                | datasource | response | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote | data_value_std_err | low_confidence_limit | high_confidence_limit | sample_size | gender  | race                          | age      | education  | topictypeid | topicid | measureid | stratificationid1 | stratificationid2 | stratificationid3 | stratificationid4 | submeasureid | displayorder | 
| ========= | ============ | ============ | ========================= | ====================== | ========================================== | ========== | ======== | =============== | =============== | ========== | ========================== | =================== | ================== | ==================== | ===================== | =========== | ======= | ============================= | ======== | ========== | =========== | ======= | ========= | ================= | ================= | ================= | ================= | ============ | ============ | 
| 2014-2015 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 21.9       |                            |                     | 0.6                | 20.7                 | 23.1                  | 11114       | Overall | White                         | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 5RAC              | 6EDU              | BRF34        | 34           | 
| 2014-2015 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 20.1       |                            |                     | 1                  | 18.2                 | 22                    | 4016        | Overall | African American              | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 1RAC              | 6EDU              | BRF30        | 30           | 
| 2014-2015 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 19.4       |                            |                     | 4                  | 11.6                 | 27.2                  | 164         | Overall | Hispanic                      | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 4RAC              | 6EDU              | BRF33        | 33           | 
| 2014-2015 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 13.9       |                            |                     | 3.4                | 7.2                  | 20.6                  | 170         | Overall | Asian/Pacific Islander        | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 3RAC              | 6EDU              | BRF32        | 32           | 
| 2014-2015 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 36.5       |                            |                     | 7.2                | 22.4                 | 50.6                  | 114         | Overall | American Indian/Alaska Native | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 2RAC              | 6EDU              | BRF31        | 31           | 
| 2014-2015 | AK           | Alaska       | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 16.7       |                            |                     | 0.8                | 15.2                 | 18.2                  | 5656        | Overall | White                         | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 5RAC              | 6EDU              | BRF34        | 34           | 
| 2014-2015 | AK           | Alaska       | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 19.5       |                            |                     | 4.9                | 9.8                  | 29.2                  | 106         | Overall | African American              | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 1RAC              | 6EDU              | BRF30        | 30           | 
| 2014-2015 | AK           | Alaska       | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 16.8       |                            |                     | 3.5                | 10                   | 23.6                  | 224         | Overall | Hispanic                      | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 4RAC              | 6EDU              | BRF33        | 33           | 
| 2014-2015 | AK           | Alaska       | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 24         |                            |                     | 2.2                | 19.7                 | 28.3                  | 648         | Overall | Asian/Pacific Islander        | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 3RAC              | 6EDU              | BRF32        | 32           | 
| 2014-2015 | AK           | Alaska       | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking ? (2 yrs ? Race/Ethnicity) | BRFSS      |          | %               | Percentage      | 33         |                            |                     | 3                  | 27                   | 39                    | 616         | Overall | American Indian/Alaska Native | All Ages | All Grades | BEH         | 100BEH  | 112CS2    | 1GEN              | 8AGE              | 2RAC              | 6EDU              | BRF31        | 31           | 
```