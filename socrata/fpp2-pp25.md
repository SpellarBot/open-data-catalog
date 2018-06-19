# Behavioral Risk Factor Data: Tobacco Use (2010 And Prior)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-data-tobacco-use-2010-and-prior) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/fpp2-pp25) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/fpp2-pp25/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/fpp2-pp25/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | fpp2-pp25 |
| Name | Behavioral Risk Factor Data: Tobacco Use (2010 And Prior) |
| Attribution | Centers for Disease Control and Prevention; National Center for Chronic Disease Prevention and Health Promotion; Office on Smoking and Health |
| Category | Survey Data |
| Tags | osh, office on smoking and health, state system, tobacco, survey, behavioral, risk, surveillance, tobacco use, cigarette, cigarette use, adult, smoking, smoking status, smoker, current, former, ne... |
| Created | 2014-09-08T12:56:24Z |
| Publication Date | 2015-11-18T10:39:29Z |

## Description

1996-2010. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  BRFSS Survey Data.  The BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. The data for the STATE System were extracted from the annual BRFSS surveys from participating states.  Tobacco topics included are cigarette smoking status, cigarette smoking prevalence by demographics, cigarette smoking frequency, and quit attempts.  NOTE:  these data are not to be compared with BRFSS data collected 2011 and forward, as the methodologies were changed.  Please refer to the FAQs / Methodology sections for more details.

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
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:fpp2-pp25 d:2010-01-01T00:00:00.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=6RAC t:topicid=100BEH t:stratificationid2=8AGE t:stratificationid1=3GEN t:measuredesc="Quit Attempt in Past Year Among Every Day Cigarette Smokers" t:measureid=167QUA t:topicdesc="Cessation (Adults)" t:education="All Grades" t:race="All Races" t:age="All Ages" t:gender=Female t:topictype="Tobacco Use ? Survey Data" t:datasource=BRFSS t:topictypeid=BEH m:data_value_std_err=2.6 m:high_confidence_limit=58.4 m:sample_size=659 m:data_value=53.3 m:low_confidence_limit=48.2

series e:fpp2-pp25 d:2010-01-01T00:00:00.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=6RAC t:topicid=100BEH t:stratificationid2=8AGE t:stratificationid1=3GEN t:measuredesc="Current Smoking" t:measureid=110CSA t:topicdesc="Cigarette Use (Adults)" t:education="All Grades" t:race="All Races" t:age="All Ages" t:gender=Female t:topictype="Tobacco Use ? Survey Data" t:datasource=BRFSS t:topictypeid=BEH m:data_value_std_err=0.8 m:high_confidence_limit=20.2 m:sample_size=5234 m:data_value=18.7 m:low_confidence_limit=17.2

series e:fpp2-pp25 d:2010-01-01T00:00:00.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=6RAC t:topicid=100BEH t:stratificationid2=5AGE t:stratificationid1=1GEN t:measuredesc="Current Smoking" t:measureid=110CSA t:topicdesc="Cigarette Use (Adults)" t:education="All Grades" t:race="All Races" t:age="18 to 44 Years" t:gender=Female t:topictype="Tobacco Use ? Survey Data" t:datasource=BRFSS t:topictypeid=BEH m:data_value_std_err=1.4 m:high_confidence_limit=21.3 m:sample_size=1197 m:data_value=18.6 m:low_confidence_limit=15.9
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:data_value_std_err p:float l:Data_Value_Std_Err t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:fpp2-pp25 l:"Behavioral Risk Factor Data: Tobacco Use (2010 And Prior)" t:attribution="Centers for Disease Control and Prevention; National Center for Chronic Disease Prevention and Health Promotion; Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/fpp2-pp25

property e:fpp2-pp25 t:meta.view v:id=fpp2-pp25 v:category="Survey Data" v:attributionLink=http://www.cdc.gov/brfss/ v:averageRating=0 v:name="Behavioral Risk Factor Data: Tobacco Use (2010 And Prior)" v:attribution="Centers for Disease Control and Prevention; National Center for Chronic Disease Prevention and Health Promotion; Office on Smoking and Health"

property e:fpp2-pp25 t:meta.view.license v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:fpp2-pp25 t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:fpp2-pp25 t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:fpp2-pp25 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | topictype                 | topicdesc              | measuredesc                                                 | datasource | response | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote | data_value_std_err | low_confidence_limit | high_confidence_limit | sample_size | gender  | race             | age                | education  | topictypeid | topicid | measureid | stratificationid1 | stratificationid2 | stratificationid3 | stratificationid4 | 
| ==== | ============ | ============ | ========================= | ====================== | =========================================================== | ========== | ======== | =============== | =============== | ========== | ========================== | =================== | ================== | ==================== | ===================== | =========== | ======= | ================ | ================== | ========== | =========== | ======= | ========= | ================= | ================= | ================= | ================= | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cessation (Adults)     | Quit Attempt in Past Year Among Every Day Cigarette Smokers | BRFSS      |          | %               | Percentage      | 53.3       |                            |                     | 2.6                | 48.2                 | 58.4                  | 659         | Female  | All Races        | All Ages           | All Grades | BEH         | 100BEH  | 167QUA    | 3GEN              | 8AGE              | 6RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 18.7       |                            |                     | 0.8                | 17.2                 | 20.2                  | 5234        | Female  | All Races        | All Ages           | All Grades | BEH         | 100BEH  | 110CSA    | 3GEN              | 8AGE              | 6RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 18.6       |                            |                     | 1.4                | 15.9                 | 21.3                  | 1197        | Female  | All Races        | 18 to 44 Years     | All Grades | BEH         | 100BEH  | 110CSA    | 1GEN              | 5AGE              | 6RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 21.5       |                            |                     | 0.9                | 19.7                 | 23.3                  | 5349        | Overall | White            | All Ages           | All Grades | BEH         | 100BEH  | 110CSA    | 1GEN              | 8AGE              | 5RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 21.8       |                            |                     | 6.4                | 9.2                  | 34.4                  | 104         | Overall | Hispanic         | All Ages           | All Grades | BEH         | 100BEH  | 110CSA    | 1GEN              | 8AGE              | 4RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 10.3       |                            |                     | 0.8                | 8.7                  | 11.9                  | 2733        | Overall | All Races        | 65 Years and Older | All Grades | BEH         | 100BEH  | 110CSA    | 1GEN              | 4AGE              | 6RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 21.9       |                            |                     | 0.8                | 20.4                 | 23.4                  | 7624        | Overall | All Races        | All Ages           | All Grades | BEH         | 100BEH  | 110CSA    | 1GEN              | 8AGE              | 6RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 22.8       |                            |                     | 1.7                | 19.5                 | 26.1                  | 1856        | Overall | African American | All Ages           | All Grades | BEH         | 100BEH  | 110CSA    | 1GEN              | 8AGE              | 1RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 24.3       |                            |                     | 1.1                | 22.2                 | 26.4                  | 3097        | Overall | All Races        | 45 to 64 Years     | All Grades | BEH         | 100BEH  | 110CSA    | 1GEN              | 3AGE              | 6RAC              | 6EDU              | 
| 2010 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigarette Use (Adults) | Current Smoking                                             | BRFSS      |          | %               | Percentage      | 25.5       |                            |                     | 1.4                | 22.8                 | 28.2                  | 2390        | Male    | All Races        | All Ages           | All Grades | BEH         | 100BEH  | 110CSA    | 2GEN              | 8AGE              | 6RAC              | 6EDU              | 
```