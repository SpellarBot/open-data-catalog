# Global Tobacco Surveillance System (GTSS) - Global Youth Tobacco Survey (GYTS)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/global-tobacco-surveillance-system-gtss-global-youth-tobacco-survey-gyts) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/57qw-ifet) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/57qw-ifet/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/57qw-ifet/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | 57qw-ifet |
| Name | Global Tobacco Surveillance System (GTSS) - Global Youth Tobacco Survey (GYTS) |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Global Survey Data |
| Tags | tobacco, osh, gtss, gyts, youth, global |
| Created | 2015-03-16T15:05:39Z |
| Publication Date | 2016-12-14T01:12:45Z |

## Description

1999-2011. The GYTS is a school-based survey that collects data on students aged 13?15 years using a standardized methodology for constructing the sample frame, selecting schools and classes, and processing data. The GYTS surveillance system is intended to enhance the capacity of countries to design, implement, and evaluate tobacco control and prevention programs. Funding for the GYTS has been provided by the Canadian Public Health Association, National Cancer Institute, United Nations Children Emergency Fund, and the World Health Organization?Tobacco Free Initiative.

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
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | gender                     | Gender                     | text      | text        |
| Yes      | series tag     | regionabbr                 | RegionAbbr                 | text      | text        |
| Yes      | series tag     | countryabbr                | CountryAbbr                | text      | text        |
| Yes      | series tag     | surveysiteabbr             | SurveySiteAbbr             | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | mpowerid                   | MpowerID                   | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
| Yes      | series tag     | stratificationid           | StratificationID           | text      | text        |
| Yes      | series tag     | datavaluetypeid            | DataValueTypeID            | text      | text        |
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
series e:57qw-ifet d:1999-01-01T00:00:00.000Z t:topic=Access/Availability t:indicator="Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store" t:surveysite="South Africa - National" t:mpowerid=M99 t:topicid=T05 t:regionabbr=AFR t:countryabbr=sf t:country="South Africa" t:surveysiteabbr=sf100 t:stratificationid=G03 t:locationid=458 t:indicatorid=Q09 t:gender=Boy t:who_region="African Region" t:datavaluetypeid=Prctg t:datasource=GYTS m:high_confidence_limit=69.6 m:sample_size=180 m:data_value=61.6 m:low_confidence_limit=53

series e:57qw-ifet d:1999-01-01T00:00:00.000Z t:topic=Access/Availability t:indicator="Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store" t:surveysite="South Africa - National" t:mpowerid=M99 t:topicid=T05 t:regionabbr=AFR t:countryabbr=sf t:country="South Africa" t:surveysiteabbr=sf100 t:stratificationid=G04 t:locationid=458 t:indicatorid=Q09 t:gender=Girl t:who_region="African Region" t:datavaluetypeid=Prctg t:datasource=GYTS m:high_confidence_limit=58.9 m:sample_size=207 m:data_value=49.5 m:low_confidence_limit=40.1

series e:57qw-ifet d:1999-01-01T00:00:00.000Z t:topic=Access/Availability t:indicator="Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store" t:surveysite="South Africa - National" t:mpowerid=M99 t:topicid=T05 t:regionabbr=AFR t:countryabbr=sf t:country="South Africa" t:surveysiteabbr=sf100 t:stratificationid=G9901 t:locationid=458 t:indicatorid=Q09 t:gender=Total t:who_region="African Region" t:datavaluetypeid=Prctg t:datasource=GYTS m:high_confidence_limit=61.6 m:sample_size=399 m:data_value=54.8 m:low_confidence_limit=47.8
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit d:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:double l:High_Confidence_Limit d:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size d:Sample_Size t:dataTypeName=number

entity e:57qw-ifet l:"Global Tobacco Surveillance System (GTSS) - Global Youth Tobacco Survey (GYTS)" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/57qw-ifet

property e:57qw-ifet t:meta.view v:id=57qw-ifet v:category="Global Survey Data" v:attributionLink=http://nccd.cdc.gov/GTSSData/default/default.aspx v:averageRating=0 v:name="Global Tobacco Surveillance System (GTSS) - Global Youth Tobacco Survey (GYTS)" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:57qw-ifet t:meta.view.license v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:57qw-ifet t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:57qw-ifet t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData
```

## Top Records

```ls
| year | who_region     | datasource | country      | surveysite              | topic                                        | mpower  | indicator                                                                                                                                                                                                                   | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote | low_confidence_limit | high_confidence_limit | sample_size | gender | regionabbr | countryabbr | surveysiteabbr | locationid | topicid | mpowerid | indicatorid | stratificationid | datavaluetypeid | 
| ==== | ============== | ========== | ============ | ======================= | ============================================ | ======= | =========================================================================================================================================================================================================================== | =============== | =============== | ========== | ========================== | =================== | ==================== | ===================== | =========== | ====== | ========== | =========== | ============== | ========== | ======= | ======== | =========== | ================ | =============== | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Access/Availability                          |         | Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store                                                                                                                  | %               | Percentage      | 61.6       |                            |                     | 53                   | 69.6                  | 180         | Boy    | AFR        | sf          | sf100          | 458        | T05     | M99      | Q09         | G03              | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Access/Availability                          |         | Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store                                                                                                                  | %               | Percentage      | 49.5       |                            |                     | 40.1                 | 58.9                  | 207         | Girl   | AFR        | sf          | sf100          | 458        | T05     | M99      | Q09         | G04              | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Access/Availability                          |         | Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store                                                                                                                  | %               | Percentage      | 54.8       |                            |                     | 47.8                 | 61.6                  | 399         | Total  | AFR        | sf          | sf100          | 458        | T05     | M99      | Q09         | G9901            | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Access/Availability                          |         | Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store and that they were not refused purchase of cigarettes because of their age during the month preceding the survey | %               | Percentage      | 72.5       |                            |                     | 56.7                 | 84.2                  | 95          | Boy    | AFR        | sf          | sf100          | 458        | T05     | M99      | Q10         | G03              | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Access/Availability                          |         | Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store and that they were not refused purchase of cigarettes because of their age during the month preceding the survey | %               | Percentage      | 84.4       |                            |                     | 76.2                 | 90.2                  | 97          | Girl   | AFR        | sf          | sf100          | 458        | T05     | M99      | Q10         | G04              | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Access/Availability                          |         | Percentage of current smokers who reported they usually got their cigarettes by purchasing them in a store and that they were not refused purchase of cigarettes because of their age during the month preceding the survey | %               | Percentage      | 77.2       |                            |                     | 67.1                 | 84.8                  | 195         | Total  | AFR        | sf          | sf100          | 458        | T05     | M99      | Q10         | G9901            | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Cessation                                    | Offer   | Percentage of current smokers who reported they wanted to stop smoking now                                                                                                                                                  | %               | Percentage      | 72.6       |                            |                     | 60.9                 | 81.9                  | 123         | Boy    | AFR        | sf          | sf100          | 458        | T01     | M02      | Q08         | G03              | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Cessation                                    | Offer   | Percentage of current smokers who reported they wanted to stop smoking now                                                                                                                                                  | %               | Percentage      | 65.3       |                            |                     | 53.7                 | 75.2                  | 140         | Girl   | AFR        | sf          | sf100          | 458        | T01     | M02      | Q08         | G04              | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Cessation                                    | Offer   | Percentage of current smokers who reported they wanted to stop smoking now                                                                                                                                                  | %               | Percentage      | 69.1       |                            |                     | 61.2                 | 76                    | 270         | Total  | AFR        | sf          | sf100          | 458        | T01     | M02      | Q08         | G9901            | Prctg           | 
| 1999 | African Region | GYTS       | South Africa | South Africa - National | Exposure to indirect pro-tobacco advertising | Enforce | Percentage of students who reported having an object with a tobacco company logo on it                                                                                                                                      | %               | Percentage      | 19.1       |                            |                     | 13.4                 | 26.6                  | 1029        | Boy    | AFR        | sf          | sf100          | 458        | T07     | M04      | Q06         | G03              | Prctg           | 
```