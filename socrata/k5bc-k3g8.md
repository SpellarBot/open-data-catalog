# DASH - Youth Risk Behavior Surveillance System (YRBSS): Middle School

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dash-youth-risk-behavior-surveillance-system-yrbss-middle-school-11a0a) |
| Metadata | [Link](https://data.cdc.gov/api/views/k5bc-k3g8) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/k5bc-k3g8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/k5bc-k3g8/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | k5bc-k3g8 |
| Name | DASH - Youth Risk Behavior Surveillance System (YRBSS): Middle School |
| Category | Youth Risk Behaviors |
| Tags | youth online, risk behavior, survey, middle school, yrbs |
| Created | 2016-08-29T13:51:01Z |
| Publication Date | 2016-08-29T16:21:58Z |

## Description

1991-2015. Middle School Dataset. The Youth Risk Behavior Surveillance System (YRBSS) monitors six categories of priority health behaviors 
among youth and young adults: 1) behaviors that contribute to unintentional injuries and violence; 2) tobacco use; 3) alcohol and 
other drug use; 4) sexual behaviors related to unintended pregnancy and sexually transmitted infections (STIs), including human 
immunodeficiency virus (HIV) infection; 5) unhealthy dietary behaviors; and 6) physical inactivity. In addition, YRBSS monitors 
the prevalence of obesity and asthma and other priority health behaviors.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | time           | year                                    | YEAR                                    | number    | number      |
| Yes      | series tag     | locationabbr                            | LocationAbbr                            | text      | text        |
| Yes      | series tag     | locationdesc                            | LocationDesc                            | text      | text        |
| Yes      | series tag     | datasource                              | DataSource                              | text      | text        |
| Yes      | series tag     | topic                                   | Topic                                   | text      | text        |
| Yes      | series tag     | subtopic                                | Subtopic                                | text      | text        |
| Yes      | series tag     | shortquestiontext                       | ShortQuestionText                       | text      | text        |
| Yes      | series tag     | greater_risk_question                   | Greater_Risk_Question                   | text      | text        |
| Yes      | series tag     | description                             | Description                             | text      | text        |
| No       |                | data_value_unit                         | Data_Value_Unit                         | text      | text        |
| No       |                | data_value_type                         | Data_Value_Type                         | text      | text        |
| Yes      | numeric metric | greater_risk_data_value                 | Greater_Risk_Data_Value                 | number    | number      |
| No       |                | greater_risk_data_value_footnote_symbol | Greater_Risk_Data_Value_Footnote_Symbol | text      | text        |
| No       |                | greater_risk_data_value_footnote        | Greater_Risk_Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | greater_risk_low_confidence_limit       | Greater_Risk_Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | greater_risk_high_confidence_limit      | Greater_Risk_High_Confidence_Limit      | number    | number      |
| Yes      | series tag     | lesser_risk_question                    | Lesser_Risk_Question                    | text      | text        |
| Yes      | numeric metric | lesser_risk_data_value                  | Lesser_Risk_Data_Value                  | number    | number      |
| No       |                | lesser_risk_data_value_footnote_symbol  | Lesser_Risk_Data_Value_Footnote_Symbol  | text      | text        |
| No       |                | lesser_risk_data_value_footnote         | Lesser_Risk_Data_Value_Footnote         | text      | text        |
| Yes      | numeric metric | lesser_risk_low_confidence_limit        | Lesser_Risk_Low_Confidence_Limit        | number    | number      |
| Yes      | numeric metric | lesser_risk_high_confidence_limit       | Lesser_Risk_High_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | sample_size                             | Sample_Size                             | number    | number      |
| Yes      | series tag     | sex                                     | Sex                                     | text      | text        |
| Yes      | series tag     | race                                    | Race                                    | text      | text        |
| Yes      | series tag     | grade                                   | Grade                                   | text      | text        |
| Yes      | series tag     | topicid                                 | TopicId                                 | text      | text        |
| Yes      | series tag     | subtopicid                              | SubTopicID                              | text      | text        |
| Yes      | series tag     | questioncode                            | QuestionCode                            | text      | text        |
| Yes      | series tag     | locationid                              | LocationId                              | text      | text        |
| Yes      | series tag     | stratid1                                | StratID1                                | text      | text        |
| Yes      | series tag     | stratid2                                | StratID2                                | text      | text        |
| Yes      | series tag     | stratid3                                | StratID3                                | text      | text        |
| Yes      | series tag     | stratificationtype                      | StratificationType                      | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,greater_risk_data_value_footnote_symbol,greater_risk_data_value_footnote,lesser_risk_data_value_footnote_symbol,lesser_risk_data_value_footnote
```

## Data Commands

```ls
series e:k5bc-k3g8 d:2007-01-01T00:00:00.000Z t:topic="Tobacco Use" t:stratid3=G17 t:locationdesc="West Virginia" t:locationabbr=WV t:subtopic="Cigarette Use" t:sex=Total t:topicid=TUS01 t:stratid1=S1 t:stratid2=R16 t:stratificationtype=State t:shortquestiontext="Current daily cigarette use" t:greater_risk_question="Currently smoked cigarettes daily" t:race="Multiple Race" t:subtopicid=CIG01 t:questioncode=QNDAYCIG t:lesser_risk_question="Did not currently smoke cigarettes daily" t:locationid=54 t:description="on all 30 days during the 30 days before the survey" t:grade=6th t:datasource=YRBSS m:sample_size=18

series e:k5bc-k3g8 d:2005-01-01T00:00:00.000Z t:topic="Tobacco Use" t:stratid3=G17 t:locationdesc="San Francisco, CA" t:locationabbr=SF t:subtopic="Cigarette Use" t:sex=Total t:topicid=TUS01 t:stratid1=S1 t:stratid2=R16 t:stratificationtype=Local t:shortquestiontext="Current daily cigarette use" t:greater_risk_question="Currently smoked cigarettes daily" t:race="Multiple Race" t:subtopicid=CIG01 t:questioncode=QNDAYCIG t:lesser_risk_question="Did not currently smoke cigarettes daily" t:locationid=104 t:description="on all 30 days during the 30 days before the survey" t:grade=6th t:datasource=YRBSS m:sample_size=42

series e:k5bc-k3g8 d:2013-01-01T00:00:00.000Z t:topic="Tobacco Use" t:stratid3=G17 t:locationdesc="South Carolina" t:locationabbr=SC t:subtopic="Cigarette Use" t:sex=Total t:topicid=TUS01 t:stratid1=S1 t:stratid2=R16 t:stratificationtype=State t:shortquestiontext="Current daily cigarette use" t:greater_risk_question="Currently smoked cigarettes daily" t:race="Multiple Race" t:subtopicid=CIG01 t:questioncode=QNDAYCIG t:lesser_risk_question="Did not currently smoke cigarettes daily" t:locationid=45 t:description="on all 30 days during the 30 days before the survey" t:grade=6th t:datasource=YRBSS m:sample_size=39
```

## Meta Commands

```ls
metric m:greater_risk_data_value p:double l:Greater_Risk_Data_Value t:dataTypeName=number

metric m:greater_risk_low_confidence_limit p:double l:Greater_Risk_Low_Confidence_Limit t:dataTypeName=number

metric m:greater_risk_high_confidence_limit p:double l:Greater_Risk_High_Confidence_Limit t:dataTypeName=number

metric m:lesser_risk_data_value p:double l:Lesser_Risk_Data_Value t:dataTypeName=number

metric m:lesser_risk_low_confidence_limit p:double l:Lesser_Risk_Low_Confidence_Limit t:dataTypeName=number

metric m:lesser_risk_high_confidence_limit p:double l:Lesser_Risk_High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:k5bc-k3g8 l:"DASH - Youth Risk Behavior Surveillance System (YRBSS): Middle School" t:url=https://data.cdc.gov/api/views/k5bc-k3g8

property e:k5bc-k3g8 t:meta.view v:id=k5bc-k3g8 v:category="Youth Risk Behaviors" v:averageRating=0 v:name="DASH - Youth Risk Behavior Surveillance System (YRBSS): Middle School"

property e:k5bc-k3g8 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:k5bc-k3g8 t:meta.view.owner v:id=fjjr-gap9 v:screenName="The Su" v:lastNotificationSeenAt=1492539263 v:displayName="The Su"

property e:k5bc-k3g8 t:meta.view.tableauthor v:id=fjjr-gap9 v:screenName="The Su" v:roleName=administrator v:lastNotificationSeenAt=1492539263 v:displayName="The Su"

property e:k5bc-k3g8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=CDCINFO@CDC.GOV v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc      | datasource | topic       | subtopic      | shortquestiontext           | greater_risk_question             | description                                         | data_value_unit | data_value_type | greater_risk_data_value | greater_risk_data_value_footnote_symbol | greater_risk_data_value_footnote   | greater_risk_low_confidence_limit | greater_risk_high_confidence_limit | lesser_risk_question                     | lesser_risk_data_value | lesser_risk_data_value_footnote_symbol | lesser_risk_data_value_footnote    | lesser_risk_low_confidence_limit | lesser_risk_high_confidence_limit | sample_size | sex   | race          | grade | topicid | subtopicid | questioncode | locationid | stratid1 | stratid2 | stratid3 | stratificationtype | 
| ==== | ============ | ================= | ========== | =========== | ============= | =========================== | ================================= | =================================================== | =============== | =============== | ======================= | ======================================= | ================================== | ================================= | ================================== | ======================================== | ====================== | ====================================== | ================================== | ================================ | ================================= | =========== | ===== | ============= | ===== | ======= | ========== | ============ | ========== | ======== | ======== | ======== | ================== | 
| 2007 | WV           | West Virginia     | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 18          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 54         | S1       | R16      | G17      | State              | 
| 2005 | SF           | San Francisco, CA | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 42          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 104        | S1       | R16      | G17      | Local              | 
| 2013 | SC           | South Carolina    | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 39          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 45         | S1       | R16      | G17      | State              | 
| 2001 | WY           | Wyoming           | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 28          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 56         | S1       | R16      | G17      | State              | 
| 2013 | SF           | San Francisco, CA | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 51          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 104        | S1       | R16      | G17      | Local              | 
| 2001 | WV           | West Virginia     | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 17          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 54         | S1       | R16      | G17      | State              | 
| 1997 | SF           | San Francisco, CA | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 0           | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 104        | S1       | R16      | G17      | Local              | 
| 2013 | TN           | Tennessee         | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 67          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 47         | S1       | R16      | G17      | State              | 
| 2013 | WY           | Wyoming           | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 25          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 56         | S1       | R16      | G17      | State              | 
| 2001 | SF           | San Francisco, CA | YRBSS      | Tobacco Use | Cigarette Use | Current daily cigarette use | Currently smoked cigarettes daily | on all 30 days during the 30 days before the survey | %               | Percentage      |                         | N/A                                     | < 100 respondents for the subgroup |                                   |                                    | Did not currently smoke cigarettes daily |                        | N/A                                    | < 100 respondents for the subgroup |                                  |                                   | 36          | Total | Multiple Race | 6th   | TUS01   | CIG01      | QNDAYCIG     | 104        | S1       | R16      | G17      | Local              | 
```