# Tobacco Use Supplement to the Current Population Survey (TUS-CPS) Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tobacco-use-supplement-to-the-current-population-survey-tus-cps-data-245a5) |
| Metadata | [Link](https://data.cdc.gov/api/views/4y6p-yphk) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/4y6p-yphk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/4y6p-yphk/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 4y6p-yphk |
| Name | Tobacco Use Supplement to the Current Population Survey (TUS-CPS) Data |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Survey Data |
| Tags | osh, office on smoking and health, state system, tobacco, survey, tobacco use, cigarette, cigarette use, cigar, cigar use, pipe, smokeless tobacco products, adult, smoking, smoking status, smoker,... |
| Created | 2014-06-03T15:58:40Z |
| Publication Date | 2017-03-15T15:23:24Z |

## Description

1992-1993, 1995-1996, 1998-1999, 2001-2002, 2003, 2006-2007, 2010-2011.   Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  TUS-CPS Survey Data.  The Current Population Survey is a monthly survey of about 50,000 households conducted by the Bureau of the Census for the Bureau of Labor Statistics. The survey has been conducted for more than 50 years. Estimates obtained from the CPS include employment, unemployment, earnings, hours of work, and other indicators. Supplemental surveys include questions about a variety of topics, including an annual social and economic supplement, school enrollment, work schedules, voting and registration, job tenure and occupational mobility, food security, and tobacco use.

The data for the STATE System were obtained through the Tobacco Use Supplement to the Current Population Survey (TUS-CPS).  Tobacco topics included are cigarette smoking status, cigarette smoking prevalence by demographics, cigarette smoking frequency, cigarette consumption, quit attempts, cigar use, pipe use, smokeless tobacco use, and smokefree rules/policies in homes and worksites.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | year                       | YEAR                       | text      | text        |
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
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote,displayorder
```

## Data Commands

```ls
series e:4y6p-yphk d:2016-06-21T09:51:47.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=6RAC t:topicid=101BEH t:stratificationid2=8AGE t:stratificationid1=3GEN t:measuredesc="Percent of Former Smokers Among Ever Smokers" t:measureid=168QUP t:topicdesc="Cessation (Adults)" t:education="All Grades" t:race="All Races" t:age="All Ages" t:gender=Female t:topictype="Tobacco Use ? Survey Data" t:year=2003 t:submeasureid=TUS07 t:datasource=TUS-CPS t:topictypeid=BEH m:data_value_std_err=3.1 m:high_confidence_limit=45.7 m:sample_size=478 m:data_value=39.7 m:low_confidence_limit=33.7

series e:4y6p-yphk d:2016-06-21T09:51:47.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=6RAC t:topicid=101BEH t:stratificationid2=8AGE t:stratificationid1=2GEN t:measuredesc="Percent of Former Smokers Among Ever Smokers" t:measureid=168QUP t:topicdesc="Cessation (Adults)" t:education="All Grades" t:race="All Races" t:age="All Ages" t:gender=Male t:topictype="Tobacco Use ? Survey Data" t:year=2003 t:submeasureid=TUS06 t:datasource=TUS-CPS t:topictypeid=BEH m:data_value_std_err=2.6 m:high_confidence_limit=57.2 m:sample_size=578 m:data_value=52.1 m:low_confidence_limit=47

series e:4y6p-yphk d:2016-06-21T09:51:47.000Z t:stratificationid4=6EDU t:locationdesc=Alabama t:locationabbr=AL t:stratificationid3=6RAC t:topicid=101BEH t:stratificationid2=8AGE t:stratificationid1=1GEN t:measuredesc="Percent of Former Smokers Among Ever Smokers" t:measureid=168QUP t:topicdesc="Cessation (Adults)" t:education="All Grades" t:race="All Races" t:age="All Ages" t:gender=Overall t:topictype="Tobacco Use ? Survey Data" t:year=2003 t:submeasureid=TUS05 t:datasource=TUS-CPS t:topictypeid=BEH m:data_value_std_err=2 m:high_confidence_limit=50.9 m:sample_size=1056 m:data_value=47 m:low_confidence_limit=43.1
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:"Value of the data" t:dataTypeName=number

metric m:data_value_std_err p:float l:Data_Value_Std_Err d:"Standard Error for the data value" t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit d:"Confidence interval lower limit" t:dataTypeName=number

metric m:high_confidence_limit p:double l:High_Confidence_Limit d:"Confidence interval upper limit" t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size d:"Sample size" t:dataTypeName=number

entity e:4y6p-yphk l:"Tobacco Use Supplement to the Current Population Survey (TUS-CPS) Data" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/4y6p-yphk

property e:4y6p-yphk t:meta.view v:id=4y6p-yphk v:category="Survey Data" v:attributionLink=http://appliedresearch.cancer.gov/tus-cps/ v:averageRating=0 v:name="Tobacco Use Supplement to the Current Population Survey (TUS-CPS) Data" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:4y6p-yphk t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:4y6p-yphk t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:4y6p-yphk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| :updated_at | year | locationabbr | locationdesc | topictype                 | topicdesc          | measuredesc                                                 | datasource | response | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote | data_value_std_err | low_confidence_limit | high_confidence_limit | sample_size | gender  | race      | age      | education  | topictypeid | topicid | measureid | stratificationid1 | stratificationid2 | stratificationid3 | stratificationid4 | submeasureid | displayorder | 
| =========== | ==== | ============ | ============ | ========================= | ================== | =========================================================== | ========== | ======== | =============== | =============== | ========== | ========================== | =================== | ================== | ==================== | ===================== | =========== | ======= | ========= | ======== | ========== | =========== | ======= | ========= | ================= | ================= | ================= | ================= | ============ | ============ | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cessation (Adults) | Percent of Former Smokers Among Ever Smokers                | TUS-CPS    |          | %               | Percentage      | 39.7       |                            |                     | 3.1                | 33.7                 | 45.7                  | 478         | Female  | All Races | All Ages | All Grades | BEH         | 101BEH  | 168QUP    | 3GEN              | 8AGE              | 6RAC              | 6EDU              | TUS07        | 7            | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cessation (Adults) | Percent of Former Smokers Among Ever Smokers                | TUS-CPS    |          | %               | Percentage      | 52.1       |                            |                     | 2.6                | 47                   | 57.2                  | 578         | Male    | All Races | All Ages | All Grades | BEH         | 101BEH  | 168QUP    | 2GEN              | 8AGE              | 6RAC              | 6EDU              | TUS06        | 6            | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cessation (Adults) | Percent of Former Smokers Among Ever Smokers                | TUS-CPS    |          | %               | Percentage      | 47         |                            |                     | 2                  | 43.1                 | 50.9                  | 1056        | Overall | All Races | All Ages | All Grades | BEH         | 101BEH  | 168QUP    | 1GEN              | 8AGE              | 6RAC              | 6EDU              | TUS05        | 5            | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cessation (Adults) | Quit Attempt in Past Year Among Every Day Cigarette Smokers | TUS-CPS    |          | %               | Percentage      | 26.8       |                            |                     | 3.9                | 19.2                 | 34.4                  | 237         | Female  | All Races | All Ages | All Grades | BEH         | 101BEH  | 168QUA    | 3GEN              | 8AGE              | 6RAC              | 6EDU              | TUS10        | 10           | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cessation (Adults) | Quit Attempt in Past Year Among Every Day Cigarette Smokers | TUS-CPS    |          | %               | Percentage      | 29.2       |                            |                     | 3.7                | 22                   | 36.4                  | 222         | Male    | All Races | All Ages | All Grades | BEH         | 101BEH  | 168QUA    | 2GEN              | 8AGE              | 6RAC              | 6EDU              | TUS09        | 9            | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cessation (Adults) | Quit Attempt in Past Year Among Every Day Cigarette Smokers | TUS-CPS    |          | %               | Percentage      | 28.1       |                            |                     | 2.7                | 22.9                 | 33.3                  | 459         | Overall | All Races | All Ages | All Grades | BEH         | 101BEH  | 168QUA    | 1GEN              | 8AGE              | 6RAC              | 6EDU              | TUS08        | 8            | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigar Use (Adults) | Smoking Status                                              | TUS-CPS    | Current  | %               | Percentage      | 0.3        |                            |                     | 0.2                | 0                    | 0.6                   | 1864        | Female  | All Races | All Ages | All Grades | BEH         | 103BEH  | 170SSA    | 3GEN              | 8AGE              | 6RAC              | 6EDU              | TUS11        | 11           | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigar Use (Adults) | Smoking Status                                              | TUS-CPS    | Current  | %               | Percentage      | 4.1        |                            |                     | 0.6                | 2.9                  | 5.3                   | 1529        | Male    | All Races | All Ages | All Grades | BEH         | 103BEH  | 170SSA    | 2GEN              | 8AGE              | 6RAC              | 6EDU              | TUS11        | 11           | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigar Use (Adults) | Smoking Status                                              | TUS-CPS    | Current  | %               | Percentage      | 2.1        |                            |                     | 0.3                | 1.5                  | 2.7                   | 3393        | Overall | All Races | All Ages | All Grades | BEH         | 103BEH  | 170SSA    | 1GEN              | 8AGE              | 6RAC              | 6EDU              | TUS11        | 11           | 
| 1466502707  | 2003 | AL           | Alabama      | Tobacco Use ? Survey Data | Cigar Use (Adults) | Smoking Status                                              | TUS-CPS    | Former   | %               | Percentage      | 1.8        |                            |                     | 0.4                | 1.1                  | 2.5                   | 1864        | Female  | All Races | All Ages | All Grades | BEH         | 103BEH  | 170SSA    | 3GEN              | 8AGE              | 6RAC              | 6EDU              | TUS12        | 12           | 
```