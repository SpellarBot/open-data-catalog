# Global Tobacco Surveillance System (GTSS) - Global Health Professions Student Survey (GHPSS)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/global-tobacco-surveillance-system-gtss-global-health-professions-student-survey-ghpss-9e453) |
| Metadata | [Link](https://data.cdc.gov/api/views/x6ag-8y7r) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/x6ag-8y7r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/x6ag-8y7r/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | x6ag-8y7r |
| Name | Global Tobacco Surveillance System (GTSS) - Global Health Professions Student Survey (GHPSS) |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Global Survey Data |
| Tags | tobacco, osh, gtss, ghpss, students |
| Created | 2015-03-16T15:00:03Z |
| Publication Date | 2016-12-14T02:18:57Z |

## Description

2005-2011. The World Health Organization, CDC, and the Canadian Public Health Association, developed the GHPSS to collect data on tobacco use and cessation counseling among health professional students in all WHO member states. GHPSS is a standardized school-based survey of third-year students pursuing advanced degrees in dentistry, medicine, nursing, or pharmacy. It is conducted in schools during regular class sessions. GHPSS follows an anonymous, self-administered format for data collection. GHPSS uses a core questionnaire on demographics, prevalence of cigarette smoking and other tobacco use, knowledge and attitudes about tobacco use, exposure to secondhand smoke, desire for smoking cessation, and training received regarding patient counseling on smoking cessation techniques. Questionnaires are translated into local languages as needed. GHPSS has a standardized methodology for selecting participating schools and classes and uniform data processing procedures.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | who_region                 | WHO_Region                 | text      | text        |
| Yes      | series tag     | datasource                 | Datasource                 | text      | text        |
| Yes      | series tag     | country                    | Country                    | text      | text        |
| Yes      | series tag     | surveysite                 | SurveySite                 | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | mpower                     | Mpower                     | text      | text        |
| Yes      | series tag     | indicator                  | Indicator                  | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | discipline                 | Discipline                 | text      | text        |
| Yes      | series tag     | gender                     | Gender                     | text      | text        |
| Yes      | series tag     | regionabbr                 | RegionAbbr                 | text      | text        |
| Yes      | series tag     | countryabbr                | CountryAbbr                | text      | text        |
| Yes      | series tag     | surveysiteabbr             | SurveySiteAbbr             | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | mpowerid                   | MpowerID                   | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
| Yes      | series tag     | stratificationid1          | StratificationID1          | text      | text        |
| Yes      | series tag     | stratificationid2          | StratificationID2          | text      | text        |
| Yes      | series tag     | datavaluetypeid            | DataValueTypeID            | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_type,data_value_unit,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:x6ag-8y7r d:2005-01-01T00:00:00.000Z t:topic=Cessation t:surveysite="India - National" t:indicator="Percentage of current smokers who reported they wanted to stop smoking now" t:mpowerid=M02 t:topicid=T01 t:stratificationid2=G9901 t:stratificationid1=D02 t:regionabbr=SEAR t:countryabbr=in t:country=India t:surveysiteabbr=in100 t:locationid=386 t:indicatorid=Q101 t:gender=Total t:who_region="South-East Asia Region" t:discipline=Medical t:datavaluetypeid=Prctg t:datasource=GHPSS t:mpower=Offer m:high_confidence_limit=85.4 m:sample_size=100 m:data_value=71.8 m:low_confidence_limit=52.7

series e:x6ag-8y7r d:2005-01-01T00:00:00.000Z t:topic=Prevalence t:surveysite="Albania - National" t:indicator="Percentage of health professions students who used tobacco products other than cigarettes on at least 1 day during the month" t:mpowerid=M01 t:topicid=T03 t:stratificationid2=G01 t:stratificationid1=D03 t:regionabbr=EUR t:countryabbr=al t:country=Albania t:surveysiteabbr=al100 t:locationid=314 t:indicatorid=Q117 t:gender=Male t:who_region="European Region" t:discipline=Nursing t:datavaluetypeid=Prctg t:datasource=GHPSS t:mpower=Monitor m:high_confidence_limit=4.7 m:sample_size=73 m:data_value=2.1 m:low_confidence_limit=0.9

series e:x6ag-8y7r d:2005-01-01T00:00:00.000Z t:topic=Prevalence t:surveysite="Albania - National" t:indicator="Percentage of health professions students who used tobacco products other than cigarettes on at least 1 day during the month" t:mpowerid=M01 t:topicid=T03 t:stratificationid2=G01 t:stratificationid1=D04 t:regionabbr=EUR t:countryabbr=al t:country=Albania t:surveysiteabbr=al100 t:locationid=314 t:indicatorid=Q117 t:gender=Male t:who_region="European Region" t:discipline=Pharmacy t:datavaluetypeid=Prctg t:datasource=GHPSS t:mpower=Monitor m:sample_size=13 m:data_value=0
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:double l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:x6ag-8y7r l:"Global Tobacco Surveillance System (GTSS) - Global Health Professions Student Survey (GHPSS)" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/x6ag-8y7r

property e:x6ag-8y7r t:meta.view v:id=x6ag-8y7r v:category="Global Survey Data" v:attributionLink=http://nccd.cdc.gov/GTSSData/default/default.aspx v:averageRating=0 v:name="Global Tobacco Surveillance System (GTSS) - Global Health Professions Student Survey (GHPSS)" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:x6ag-8y7r t:meta.view.license v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:x6ag-8y7r t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:x6ag-8y7r t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:x6ag-8y7r t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | who_region             | datasource | country | surveysite         | topic                           | mpower  | indicator                                                                                                                     | data_value_type | data_value_unit | data_value         | data_value_footnote_symbol | data_value_footnote | low_confidence_limit | high_confidence_limit | sample_size | discipline | gender | regionabbr | countryabbr | surveysiteabbr | locationid | topicid | mpowerid | indicatorid | stratificationid1 | stratificationid2 | datavaluetypeid | 
| ==== | ====================== | ========== | ======= | ================== | =============================== | ======= | ============================================================================================================================= | =============== | =============== | ================== | ========================== | =================== | ==================== | ===================== | =========== | ========== | ====== | ========== | =========== | ============== | ========== | ======= | ======== | =========== | ================= | ================= | =============== | 
| 2005 | South-East Asia Region | GHPSS      | India   | India - National   | Cessation                       | Offer   | Percentage of current smokers who reported they wanted to stop smoking now                                                    | Percentage      | %               | 71.8               |                            |                     | 52.7                 | 85.4                  | 100         | Medical    | Total  | SEAR       | in          | in100          | 386        | T01     | M02      | Q101        | D02               | G9901             | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Prevalence                      | Monitor | Percentage of health professions students who used tobacco products other than cigarettes on at least 1 day during the month  | Percentage      | %               | 2.1                |                            |                     | 0.9                  | 4.7                   | 73          | Nursing    | Male   | EUR        | al          | al100          | 314        | T03     | M01      | Q117        | D03               | G01               | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Prevalence                      | Monitor | Percentage of health professions students who used tobacco products other than cigarettes on at least 1 day during the month  | Percentage      | %               | 0                  |                            |                     |                      |                       | 13          | Pharmacy   | Male   | EUR        | al          | al100          | 314        | T03     | M01      | Q117        | D04               | G01               | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Prevalence                      | Monitor | Percentage of health professions students who used tobacco products other than cigarettes on at least 1 day during the month  | Percentage      | %               | 2.2000000000000002 |                            |                     | 0.8                  | 6                     | 51          | Dental     | Total  | EUR        | al          | al100          | 314        | T03     | M01      | Q117        | D01               | G9901             | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Prevalence                      | Monitor | Percentage of health professions students who used tobacco products other than cigarettes on at least 1 day during the month  | Percentage      | %               | 1.5                |                            |                     | 1                    | 2.2000000000000002    | 133         | Medical    | Total  | EUR        | al          | al100          | 314        | T03     | M01      | Q117        | D02               | G9901             | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Prevalence                      | Monitor | Percentage of health professions students who used tobacco products other than cigarettes on at least 1 day during the month  | Percentage      | %               | 1.5                |                            |                     | 0.9                  | 2.4                   | 332         | Nursing    | Total  | EUR        | al          | al100          | 314        | T03     | M01      | Q117        | D03               | G9901             | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Prevalence                      | Monitor | Percentage of health professions students who used tobacco products other than cigarettes on at least 1 day during the month  | Percentage      | %               | 1.9                |                            |                     | 1.1000000000000001   | 3.3                   | 51          | Pharmacy   | Total  | EUR        | al          | al100          | 314        | T03     | M01      | Q117        | D04               | G9901             | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Factors Influencing Tobacco Use | Protect | Percentage of health professions students who reported that their school has a ban on smoking in school buildings and clinics | Percentage      | %               | 13.1               |                            |                     | 9.6999999999999993   | 17.399999999999999    | 23          | Pharmacy   | Total  | EUR        | al          | al100          | 314        | T02     | M03      | Q108        | D04               | G9901             | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Factors Influencing Tobacco Use | Protect | Percentage of health professions students who reported that their school has a ban on smoking in school buildings and clinics | Percentage      | %               | 24.1               |                            |                     | 20.7                 | 27.7                  | 219         | Nursing    | Total  | EUR        | al          | al100          | 314        | T02     | M03      | Q108        | D03               | G9901             | Prctg           | 
| 2005 | European Region        | GHPSS      | Albania | Albania - National | Factors Influencing Tobacco Use | Protect | Percentage of health professions students who reported that their school has a ban on smoking in school buildings and clinics | Percentage      | %               | 14.1               |                            |                     | 12.1                 | 16.399999999999999    | 82          | Medical    | Total  | EUR        | al          | al100          | 314        | T02     | M03      | Q108        | D02               | G9901             | Prctg           | 
```