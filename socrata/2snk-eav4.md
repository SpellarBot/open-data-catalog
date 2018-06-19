# CDC STATE System Tobacco Legislation - Smokefree Indoor Air Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-smokefree-indoor-air-summary) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/2snk-eav4) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/2snk-eav4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/2snk-eav4/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | 2snk-eav4 |
| Name | CDC STATE System Tobacco Legislation - Smokefree Indoor Air Summary |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, smokefree indoor air |
| Created | 2014-12-16T19:00:43Z |
| Publication Date | 2017-02-16T17:16:10Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation ? Smokefree Indoor Air. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include information related to state legislation on comprehensive smokefree indoor air in private worksites, restaurants, and bars.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       |                | year                | YEAR                | number    | number      |
| No       |                | quarter             | Quarter             | number    | number      |
| Yes      | series tag     | locationabbr        | LocationAbbr        | text      | text        |
| Yes      | series tag     | locationdesc        | LocationDesc        | text      | text        |
| Yes      | series tag     | topictypedesc       | TopicTypeDesc       | text      | text        |
| Yes      | series tag     | topicdesc           | TopicDesc           | text      | text        |
| Yes      | series tag     | measuredesc         | MeasureDesc         | text      | text        |
| Yes      | series tag     | private_worksites   | Private_Worksites   | text      | text        |
| Yes      | series tag     | restaurants         | Restaurants         | text      | text        |
| Yes      | series tag     | bars                | Bars                | text      | text        |
| Yes      | series tag     | type_of_restriction | Type_Of_Restriction | text      | text        |
| Yes      | numeric metric | summaryaltvalue     | SummaryAltValue     | number    | number      |
| Yes      | series tag     | topictypeid         | TopicTypeId         | text      | text        |
| Yes      | series tag     | topicid             | TopicId             | text      | number      |
| Yes      | series tag     | measureid           | MeasureId           | text      | text        |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = year,quarter
```

## Data Commands

```ls
series e:2snk-eav4 d:2012-01-01T00:00:00.000Z t:locationabbr=OR t:locationdesc=Oregon t:private_worksites=Banned t:topicid=600 t:topictypedesc=Legislation t:measureid=600COMB t:measuredesc="Private Worksites, Restaurants, Bars - OSH" t:bars=Banned t:topicdesc="Smokefree Indoor Air" t:type_of_restriction="100 % smokefree in three locations" t:restaurants=Banned t:topictypeid=LEG m:summaryaltvalue=3

series e:2snk-eav4 d:2007-07-01T00:00:00.000Z t:locationabbr=NJ t:locationdesc="New Jersey" t:private_worksites=Banned t:topicid=600 t:topictypedesc=Legislation t:measureid=600COMB t:measuredesc="Private Worksites, Restaurants, Bars - OSH" t:bars=Banned t:topicdesc="Smokefree Indoor Air" t:type_of_restriction="100 % smokefree in three locations" t:restaurants=Banned t:topictypeid=LEG m:summaryaltvalue=3

series e:2snk-eav4 d:2013-04-01T00:00:00.000Z t:locationabbr=MA t:locationdesc=Massachusetts t:private_worksites=Banned t:topicid=600 t:topictypedesc=Legislation t:measureid=600COMB t:measuredesc="Private Worksites, Restaurants, Bars - OSH" t:bars=Banned t:topicdesc="Smokefree Indoor Air" t:type_of_restriction="100 % smokefree in three locations" t:restaurants=Banned t:topictypeid=LEG m:summaryaltvalue=3
```

## Meta Commands

```ls
metric m:summaryaltvalue p:integer l:SummaryAltValue d:"Alternate numeric value for non-numeric Type of Restriction value; used for mapping and graphing" t:dataTypeName=number

entity e:2snk-eav4 l:"CDC STATE System Tobacco Legislation - Smokefree Indoor Air Summary" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/2snk-eav4

property e:2snk-eav4 t:meta.view v:id=2snk-eav4 v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem/ v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Smokefree Indoor Air Summary" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:2snk-eav4 t:meta.view.license v:name="Public Domain"

property e:2snk-eav4 t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:2snk-eav4 t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:2snk-eav4 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc  | topictypedesc | topicdesc            | measuredesc                                | private_worksites | restaurants      | bars             | type_of_restriction                                   | summaryaltvalue | topictypeid | topicid | measureid | 
| ==== | ======= | ============ | ============= | ============= | ==================== | ========================================== | ================= | ================ | ================ | ===================================================== | =============== | =========== | ======= | ========= | 
| 2012 | 1       | OR           | Oregon        | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | Banned            | Banned           | Banned           | 100 % smokefree in three locations                    | 3               | LEG         | 600     | 600COMB   | 
| 2007 | 3       | NJ           | New Jersey    | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | Banned            | Banned           | Banned           | 100 % smokefree in three locations                    | 3               | LEG         | 600     | 600COMB   | 
| 2013 | 2       | MA           | Massachusetts | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | Banned            | Banned           | Banned           | 100 % smokefree in three locations                    | 3               | LEG         | 600     | 600COMB   | 
| 2006 | 4       | FL           | Florida       | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | Banned            | Banned           | None             | 100 % smokefree in two locations                      | 2               | LEG         | 600     | 600COMB   | 
| 2013 | 1       | MN           | Minnesota     | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | Banned            | Banned           | Banned           | 100 % smokefree in three locations                    | 3               | LEG         | 600     | 600COMB   | 
| 2007 | 2       | NE           | Nebraska      | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | Designated Areas  | Designated Areas | Designated Areas | No Law, designated areas, or separate ventilation Law | 0               | LEG         | 600     | 600COMB   | 
| 2014 | 4       | MS           | Mississippi   | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | No Provision      | No Provision     | No Provision     | No Law, designated areas, or separate ventilation Law | 0               | LEG         | 600     | 600COMB   | 
| 2013 | 2       | FL           | Florida       | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | Banned            | Banned           | None             | 100 % smokefree in two locations                      | 2               | LEG         | 600     | 600COMB   | 
| 2009 | 2       | NY           | New York      | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | Banned            | Banned           | Banned           | 100 % smokefree in three locations                    | 3               | LEG         | 600     | 600COMB   | 
| 2013 | 1       | MS           | Mississippi   | Legislation   | Smokefree Indoor Air | Private Worksites, Restaurants, Bars - OSH | No Provision      | No Provision     | No Provision     | No Law, designated areas, or separate ventilation Law | 0               | LEG         | 600     | 600COMB   | 
```