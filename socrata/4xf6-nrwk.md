# Global Tobacco Surveillance System (GTSS) - Global Adult Tobacco Survey (GATS)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/global-tobacco-surveillance-system-gtss-global-adult-tobacco-survey-gats) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/4xf6-nrwk) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/4xf6-nrwk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/4xf6-nrwk/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | 4xf6-nrwk |
| Name | Global Tobacco Surveillance System (GTSS) - Global Adult Tobacco Survey (GATS) |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Global Survey Data |
| Tags | tobacco, osh, gtss, gats, adult |
| Created | 2015-03-16T14:43:43Z |
| Publication Date | 2016-12-13T20:49:16Z |

## Description

2008-2012. Centers for Disease Control and Prevention (CDC).   Office on Smoking and Health (OSH) ? Global Tobacco Surveillance System (GTSS) - Global Adult Tobacco Survey (GATS).    The Global Adult Tobacco Survey (GATS) is the global standard to systematically monitor adult tobacco use and track key tobacco control indicators. GATS is a nationally representative household survey of adults 15 years of age or older, using a standard protocol. It is intended to generate comparable data within and across countries. GATS enhances countries' capacity to design, implement and evaluate tobacco control interventions.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | who_region                 | WHO_Region                 | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | country                    | Country                    | text      | text        |
| Yes      | series tag     | surveysite                 | SurveySite                 | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | mpower                     | Mpower                     | text      | text        |
| Yes      | series tag     | indicator                  | Indicator                  | text      | text        |
| Yes      | series tag     | indicator_level            | Indicator_Level            | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | age                        | Age                        | text      | text        |
| Yes      | series tag     | gender                     | Gender                     | text      | text        |
| Yes      | series tag     | residence                  | Residence                  | text      | text        |
| Yes      | series tag     | regionabbr                 | RegionAbbr                 | text      | text        |
| Yes      | series tag     | countryabbr                | CountryAbbr                | text      | text        |
| Yes      | series tag     | surveysiteabbr             | SurveySiteAbbr             | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | mpowerid                   | MpowerID                   | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
| Yes      | series tag     | responseid                 | ResponseID                 | text      | text        |
| Yes      | series tag     | stratificationcategoryid1  | StratificationCategoryID1  | text      | text        |
| Yes      | series tag     | stratificationid1          | StratificationID1          | text      | text        |
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
series e:4xf6-nrwk d:2009-01-01T00:00:00.000Z t:topic="Tobacco Use" t:indicator="Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past" t:surveysite="India - Assam" t:topicid=T06 t:mpowerid=M01 t:stratificationid1=A05 t:regionabbr=SEAR t:countryabbr=in t:indicator_level="Current non-users, formerly occasional" t:country=India t:surveysiteabbr=in003 t:locationid=32 t:indicatorid=Q170 t:stratificationcategoryid1=AGE t:age=65+ t:responseid=ILVL038 t:who_region="South-East Asia Region" t:datavaluetypeid=Prctg t:datasource=GATS t:mpower=Monitor m:high_confidence_limit=8.5 m:sample_size=113 m:data_value=1.3 m:low_confidence_limit=0.2

series e:4xf6-nrwk d:2009-01-01T00:00:00.000Z t:topic="Tobacco Use" t:indicator="Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past" t:surveysite="India - Assam" t:topicid=T06 t:mpowerid=M01 t:stratificationid1=R03 t:regionabbr=SEAR t:countryabbr=in t:indicator_level="Current non-users, formerly occasional" t:country=India t:surveysiteabbr=in003 t:locationid=32 t:residence=Rural t:indicatorid=Q170 t:stratificationcategoryid1=RESIDENCE t:responseid=ILVL038 t:who_region="South-East Asia Region" t:datavaluetypeid=Prctg t:datasource=GATS t:mpower=Monitor m:high_confidence_limit=1.3 m:sample_size=4459 m:data_value=0.9 m:low_confidence_limit=0.6

series e:4xf6-nrwk d:2009-01-01T00:00:00.000Z t:topic="Tobacco Use" t:indicator="Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past" t:surveysite="India - Assam" t:topicid=T06 t:mpowerid=M01 t:stratificationid1=R02 t:regionabbr=SEAR t:countryabbr=in t:indicator_level="Current non-users, formerly occasional" t:country=India t:surveysiteabbr=in003 t:locationid=32 t:residence=Urban t:indicatorid=Q170 t:stratificationcategoryid1=RESIDENCE t:responseid=ILVL038 t:who_region="South-East Asia Region" t:datavaluetypeid=Prctg t:datasource=GATS t:mpower=Monitor m:high_confidence_limit=3.1 m:sample_size=759 m:data_value=1.5 m:low_confidence_limit=0.7
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:"Data Value" t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit d:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit d:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size d:Sample_Size t:dataTypeName=number

entity e:4xf6-nrwk l:"Global Tobacco Surveillance System (GTSS) - Global Adult Tobacco Survey (GATS)" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/4xf6-nrwk

property e:4xf6-nrwk t:meta.view v:id=4xf6-nrwk v:category="Global Survey Data" v:attributionLink=http://nccd.cdc.gov/GTSSData/default/default.aspx v:averageRating=0 v:name="Global Tobacco Surveillance System (GTSS) - Global Adult Tobacco Survey (GATS)" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:4xf6-nrwk t:meta.view.license v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:4xf6-nrwk t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:4xf6-nrwk t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:4xf6-nrwk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | who_region             | datasource | country | surveysite         | topic       | mpower  | indicator                                                                                                                           | indicator_level                        | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote                                      | low_confidence_limit | high_confidence_limit | sample_size | age   | gender | residence | regionabbr | countryabbr | surveysiteabbr | locationid | topicid | mpowerid | indicatorid | responseid | stratificationcategoryid1 | stratificationid1 | datavaluetypeid | 
| ==== | ====================== | ========== | ======= | ================== | =========== | ======= | =================================================================================================================================== | ====================================== | =============== | =============== | ========== | ========================== | ======================================================== | ==================== | ===================== | =========== | ===== | ====== | ========= | ========== | =========== | ============== | ========== | ======= | ======== | =========== | ========== | ========================= | ================= | =============== | 
| 2009 | South-East Asia Region | GATS       | India   | India - Assam      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 1.3        |                            |                                                          | 0.2                  | 8.5                   | 113         | 65+   |        |           | SEAR       | in          | in003          | 32         | T06     | M01      | Q170        | ILVL038    | AGE                       | A05               | Prctg           | 
| 2009 | South-East Asia Region | GATS       | India   | India - Assam      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 0.9        |                            |                                                          | 0.6                  | 1.3                   | 4459        |       |        | Rural     | SEAR       | in          | in003          | 32         | T06     | M01      | Q170        | ILVL038    | RESIDENCE                 | R03               | Prctg           | 
| 2009 | South-East Asia Region | GATS       | India   | India - Assam      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 1.5        |                            |                                                          | 0.7                  | 3.1                   | 759         |       |        | Urban     | SEAR       | in          | in003          | 32         | T06     | M01      | Q170        | ILVL038    | RESIDENCE                 | R02               | Prctg           | 
| 2009 | South-East Asia Region | GATS       | India   | India - Assam      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 0.5        |                            |                                                          | 0.3                  | 0.9                   | 2613        |       | Female |           | SEAR       | in          | in003          | 32         | T06     | M01      | Q170        | ILVL038    | GENDER                    | G02               | Prctg           | 
| 2011 | European Region        | GATS       | Romania | Romania - National | Tobacco Use | Monitor | Percentage of adults who are current smokers of various tobacco products                                                            | Kreteks                                | %               | Percentage      |            | ?                          | No Data Available. Indicator was not included in survey. |                      |                       |             |       | Total  |           | EUR        | ro          | ro100          | 450        | T06     | M01      | Q157        | ILVL063    | GENDER                    | G9901             | Prctg           | 
| 2009 | South-East Asia Region | GATS       | India   | India - Assam      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 1.4        |                            |                                                          | 0.9                  | 2.2                   | 2605        |       | Male   |           | SEAR       | in          | in003          | 32         | T06     | M01      | Q170        | ILVL038    | GENDER                    | G01               | Prctg           | 
| 2009 | South-East Asia Region | GATS       | India   | India - Assam      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 1          |                            |                                                          | 0.7                  | 1.4                   | 5218        |       | Total  |           | SEAR       | in          | in003          | 32         | T06     | M01      | Q170        | ILVL038    | GENDER                    | G9901             | Prctg           | 
| 2009 | South-East Asia Region | GATS       | India   | India - Bihar      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 4.4        |                            |                                                          | 2.7                  | 7                     | 521         | 15-24 |        |           | SEAR       | in          | in034          | 57         | T06     | M01      | Q170        | ILVL038    | AGE                       | A02               | Prctg           | 
| 2009 | South-East Asia Region | GATS       | India   | India - Bihar      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 3.6        |                            |                                                          | 2.3                  | 5.4                   | 1070        | 25-44 |        |           | SEAR       | in          | in034          | 57         | T06     | M01      | Q170        | ILVL038    | AGE                       | A03               | Prctg           | 
| 2009 | South-East Asia Region | GATS       | India   | India - Bihar      | Tobacco Use | Monitor | Percentage of adults who currently do not use smokeless tobacco, and have never used smokeless tobacco on a daily basis in the past | Current non-users, formerly occasional | %               | Percentage      | 2.5        |                            |                                                          | 1.3                  | 5                     | 566         | 45-64 |        |           | SEAR       | in          | in034          | 57         | T06     | M01      | Q170        | ILVL038    | AGE                       | A04               | Prctg           | 
```