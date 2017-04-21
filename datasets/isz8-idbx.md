# CDC STATE System Tobacco Legislation - Fire Safety

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-fire-safety-31b2f) |
| Metadata | [Link](https://data.cdc.gov/api/views/isz8-idbx) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/isz8-idbx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/isz8-idbx/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | isz8-idbx |
| Name | CDC STATE System Tobacco Legislation - Fire Safety |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, fire safety |
| Created | 2014-07-14T18:23:06Z |
| Publication Date | 2017-02-16T17:15:52Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation ? Fire-Safety. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include fire-safe cigarette restrictions, enforcement, and penalties.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| No       |                | year               | Year               | number        | number        |
| No       |                | quarter            | Quarter            | number        | number        |
| Yes      | series tag     | locationabbr       | LocationAbbr       | text          | text          |
| Yes      | series tag     | locationdesc       | LocationDesc       | text          | text          |
| Yes      | series tag     | topicdesc          | TopicDesc          | text          | text          |
| Yes      | series tag     | measuredesc        | MeasureDesc        | text          | text          |
| Yes      | series tag     | datasource         | DataSource         | text          | text          |
| Yes      | series tag     | provisiongroupdesc | ProvisionGroupDesc | text          | text          |
| Yes      | series tag     | provisiondesc      | ProvisionDesc      | text          | text          |
| Yes      | series tag     | provisionvalue     | ProvisionValue     | text          | text          |
| Yes      | series tag     | citation           | Citation           | text          | text          |
| Yes      | numeric metric | provisionaltvalue  | ProvisionAltValue  | number        | number        |
| Yes      | series tag     | datatype           | DataType           | text          | text          |
| Yes      | series tag     | comments           | Comments           | text          | text          |
| Yes      | time           | enacted_date       | Enacted_Date       | calendar_date | calendar_date |
| No       |                | effective_date     | Effective_Date     | calendar_date | calendar_date |
| No       |                | displayorder       | DisplayOrder       | number        | number        |
| Yes      | series tag     | topictypeid        | TopicTypeId        | text          | text          |
| Yes      | series tag     | topicid            | TopicId            | text          | text          |
| Yes      | series tag     | measureid          | MeasureId          | text          | text          |
| Yes      | series tag     | provisiongroupid   | ProvisionGroupID   | text          | text          |
| Yes      | series tag     | provisionid        | ProvisionID        | text          | number        |
```

## Time Field

```ls
Value = enacted_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = effective_date,displayorder,year,quarter
```

## Data Commands

```ls
series e:isz8-idbx d:2009-05-21T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:citation="ALA. CODE ? 8-17-275" t:topicid=603LEG t:provisiondesc="Manufacturer Minimum Penalty ($)" t:measureid=644FIR t:measuredesc="Fire-Safe Cigarettes" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Minimum" t:provisionid=253 t:topicdesc="Legislation - Fire Safety" t:datatype=Money t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:isz8-idbx d:2009-05-21T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:citation="ALA. CODE ? 8-17-274" t:topicid=603LEG t:provisiondesc="Fire-Safe Cigarettes Labeling Requirement" t:measureid=644FIR t:measuredesc="Fire-Safe Cigarettes" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue=Yes t:provisionid=248 t:topicdesc="Legislation - Fire Safety" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=2

series e:isz8-idbx d:2009-05-21T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:citation="ALA. CODE ? 8-17-275" t:topicid=603LEG t:provisiondesc="Penalty to Retailer (Type)" t:measureid=644FIR t:measuredesc="Fire-Safe Cigarettes" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="Civil Penalty" t:provisionid=256 t:topicdesc="Legislation - Fire Safety" t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:isz8-idbx l:"CDC STATE System Tobacco Legislation - Fire Safety" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/isz8-idbx

property e:isz8-idbx t:meta.view v:id=isz8-idbx v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem/ v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Fire Safety" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:isz8-idbx t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:isz8-idbx t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:isz8-idbx t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topicdesc                 | measuredesc          | datasource | provisiongroupdesc | provisiondesc                             | provisionvalue                                                                                                                              | citation             | provisionaltvalue | datatype | comments | enacted_date        | effective_date      | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============ | ========================= | ==================== | ========== | ================== | ========================================= | =========================================================================================================================================== | ==================== | ================= | ======== | ======== | =================== | =================== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Penalties          | Manufacturer Minimum Penalty ($)          | No Minimum                                                                                                                                  | ALA. CODE ? 8-17-275 | 0                 | Money    |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 45           | LEG         | 603LEG  | 644FIR    | 60GRP            | 253         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Restrictions       | Fire-Safe Cigarettes Labeling Requirement | Yes                                                                                                                                         | ALA. CODE ? 8-17-274 | 2                 | Yes/No   |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 20           | LEG         | 603LEG  | 644FIR    | 10GRP            | 248         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Penalties          | Penalty to Retailer (Type)                | Civil Penalty                                                                                                                               | ALA. CODE ? 8-17-275 | 0                 |          |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 60           | LEG         | 603LEG  | 644FIR    | 60GRP            | 256         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Penalties          | Manufacturer Maximum Penalty ($)          | 100                                                                                                                                         | ALA. CODE ? 8-17-275 | 100               | Money    |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 50           | LEG         | 603LEG  | 644FIR    | 60GRP            | 254         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Penalties          | Penalty to Manufacturer                   | Yes                                                                                                                                         | ALA. CODE ? 8-17-275 | 2                 | Yes/No   |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 35           | LEG         | 603LEG  | 644FIR    | 60GRP            | 251         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Restrictions       | Fire-Safe Cigarettes                      | Yes                                                                                                                                         | ALA. CODE ? 8-17-272 | 2                 | Yes/No   |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 5            | LEG         | 603LEG  | 644FIR    | 10GRP            | 245         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Enforcement        | Enforcement (Type)                        | Attorney General, Department of Revenue, the State Fire Marshal, their duly authorized representatives, and other law enforcement personnel | ALA. CODE ? 8-17-277 | 0                 |          |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 30           | LEG         | 603LEG  | 644FIR    | 50GRP            | 250         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Enforcement        | Enforcement Authority                     | Yes                                                                                                                                         | ALA. CODE ? 8-17-277 | 2                 | Yes/No   |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 25           | LEG         | 603LEG  | 644FIR    | 50GRP            | 249         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Restrictions       | Fire-Safe Cigarettes Standard             | Yes                                                                                                                                         | ALA. CODE ? 8-17-272 | 2                 | Yes/No   |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 10           | LEG         | 603LEG  | 644FIR    | 10GRP            | 246         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Fire Safety | Fire-Safe Cigarettes | OSH        | Penalties          | Penalty to Manufacturer (Type)            | Civil Penalty                                                                                                                               | ALA. CODE ? 8-17-275 | 0                 |          |          | 2009-05-21T00:00:00 | 2010-01-01T00:00:00 | 40           | LEG         | 603LEG  | 644FIR    | 60GRP            | 252         | 
```