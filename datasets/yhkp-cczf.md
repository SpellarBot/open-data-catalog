# CDC STATE System Tobacco Legislation - Smokefree Campus

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-smokefree-campus-04c1d) |
| Metadata | [Link](https://data.cdc.gov/api/views/yhkp-cczf) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/yhkp-cczf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/yhkp-cczf/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | yhkp-cczf |
| Name | CDC STATE System Tobacco Legislation - Smokefree Campus |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, smokefree campus |
| Created | 2014-07-15T18:09:58Z |
| Publication Date | 2017-02-16T17:21:22Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC).  State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation ? Smokefree Campuses. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include state smokefree indoor air policies in areas such as: Smokefree campuses for private and public colleges and schools (K-12).

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
| No       |                | enacted_date       | Enacted_Date       | calendar_date | calendar_date |
| Yes      | time           | effective_date     | Effective_Date     | calendar_date | calendar_date |
| No       |                | displayorder       | DisplayOrder       | number        | number        |
| Yes      | series tag     | topictypeid        | TopicTypeId        | text          | text          |
| Yes      | series tag     | topicid            | TopicId            | text          | text          |
| Yes      | series tag     | measureid          | MeasureId          | text          | text          |
| Yes      | series tag     | provisiongroupid   | ProvisionGroupID   | text          | text          |
| Yes      | series tag     | provisionid        | ProvisionID        | text          | number        |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = enacted_date,displayorder,year,quarter
```

## Data Commands

```ls
series e:yhkp-cczf d:2015-10-05T11:17:09.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=800LEG t:provisiondesc="Tobacco Education Required in Curriculum" t:measureid=805PRK t:measuredesc="Private Schools (K-12)" t:provisiongroupdesc="Additional Requirements" t:provisiongroupid=20GRP t:provisionvalue="No Provision" t:provisionid=292 t:topicdesc="Legislation - Smokefree Campus" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:yhkp-cczf d:2015-10-05T11:17:09.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=800LEG t:provisiondesc="Penalty to Smoker" t:measureid=810PUC t:measuredesc="Public Colleges" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Provision" t:provisionid=312 t:topicdesc="Legislation - Smokefree Campus" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:yhkp-cczf d:2003-09-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:citation="ALA. CODE ? 22-15A-8(b)" t:topicid=800LEG t:provisiondesc="Penalty to School" t:measureid=805PRK t:measuredesc="Private Schools (K-12)" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue=Yes t:provisionid=286 t:topicdesc="Legislation - Smokefree Campus" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=2
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:yhkp-cczf l:"CDC STATE System Tobacco Legislation - Smokefree Campus" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/yhkp-cczf

property e:yhkp-cczf t:meta.view v:id=yhkp-cczf v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem/ v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Smokefree Campus" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:yhkp-cczf t:meta.view.license v:name="Public Domain"

property e:yhkp-cczf t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:yhkp-cczf t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:yhkp-cczf t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topicdesc                      | measuredesc            | datasource | provisiongroupdesc      | provisiondesc                            | provisionvalue              | citation                 | provisionaltvalue | datatype | comments | enacted_date        | effective_date      | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============ | ============================== | ====================== | ========== | ======================= | ======================================== | =========================== | ======================== | ================= | ======== | ======== | =================== | =================== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Private Schools (K-12) | OSH        | Additional Requirements | Tobacco Education Required in Curriculum | No Provision                |                          | 0                 | Yes/No   |          |                     |                     | 9            | LEG         | 800LEG  | 805PRK    | 20GRP            | 292         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Public Colleges        | OSH        | Penalties               | Penalty to Smoker                        | No Provision                |                          | 0                 | Yes/No   |          |                     |                     | 12           | LEG         | 800LEG  | 810PUC    | 60GRP            | 312         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Private Schools (K-12) | OSH        | Penalties               | Penalty to School                        | Yes                         | ALA. CODE ? 22-15A-8(b)  | 2                 | Yes/No   |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 13           | LEG         | 800LEG  | 805PRK    | 60GRP            | 286         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Public Schools (K-12)  | OSH        | Enforcement             | Enforcement (Type)                       | Department of Public Health | ALA. CODE ? 22-15A-8(a)  | 0                 |          |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 11           | LEG         | 800LEG  | 815PUS    | 50GRP            | 272         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Public Colleges        | OSH        | Penalties               | Maximum Penalty ($)                      | No Provision                |                          | 0                 |          |          |                     |                     | 11           | LEG         | 800LEG  | 810PUC    | 60GRP            | 308         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Private Colleges       | OSH        | Enforcement             | Signage Required                         | No Provision                |                          | 0                 | Yes/No   |          |                     |                     | 7            | LEG         | 800LEG  | 800PRC    | 50GRP            | 295         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Private Schools (K-12) | OSH        | Penalties               | Maximum Penalty ($)                      | 50                          | ALA. CODE ? 22-15A-8(b)  | 50                | Money    |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 16           | LEG         | 800LEG  | 805PRK    | 60GRP            | 284         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Private Schools (K-12) | OSH        | Restriction Areas       | Type of Restriction Outdoors             | No Provision                |                          | 0                 | Ranking  |          |                     |                     | 4            | LEG         | 800LEG  | 805PRK    | 15GRP            | 283         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Private Colleges       | OSH        | Restriction Areas       | Type of Restriction Outdoors             | No Provision                |                          | 0                 | Ranking  |          |                     |                     | 4            | LEG         | 800LEG  | 800PRC    | 15GRP            | 303         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Campus | Private Schools (K-12) | OSH        | Restriction Areas       | Type of Restriction Indoors              | Designated Areas            | ALA. CODE ? 22-15A-6(11) | 3                 | Ranking  |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 2            | LEG         | 800LEG  | 805PRK    | 15GRP            | 281         | 
```