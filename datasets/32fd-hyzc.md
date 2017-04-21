# CDC STATE System Tobacco Legislation - Smokefree Indoor Air

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-smokefree-indoor-air-50be7) |
| Metadata | [Link](https://data.cdc.gov/api/views/32fd-hyzc) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/32fd-hyzc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/32fd-hyzc/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 32fd-hyzc |
| Name | CDC STATE System Tobacco Legislation - Smokefree Indoor Air |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, smokefree indoor air |
| Created | 2014-07-15T18:29:00Z |
| Publication Date | 2017-02-16T17:22:39Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC).  State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation ? Smokefree Indoor Air. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include information related to state legislation on smokefree indoor air in areas such as: Bars, Commercial Day Care Centers, Government Multi-Unit Housing, Government Worksites, Home-Based Day Care Centers, Hotels and Motels, Personal Vehicles, Private Multi-Unit Housing, Private Worksites, Restaurants, Bingo Halls, Casinos, Enclosed Arenas, Grocery Stores, Hospitals, Hospital Campuses, Malls, Mental Health Outpatient and Residential Facilities, Prisons, Public Transportation, Racetrack Casinos, Substance Abuse Outpatient and Residential Facilities.

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
series e:32fd-hyzc d:2015-10-05T06:30:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=600LEG t:provisiondesc="Type of Restriction in Private Worksite Vehicle" t:measureid=605PWK t:measuredesc="Private Worksites" t:provisiongroupdesc=Vehicles t:provisiongroupid=30GRP t:provisionvalue="No Provision" t:provisionid=34 t:topicdesc="Legislation - Smokefree Indoor Air" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:32fd-hyzc d:2015-10-05T06:30:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=600LEG t:provisiondesc="License Suspension or Revocation" t:measureid=620HDC t:measuredesc="Home-based Day Care Centers" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Provision" t:provisionid=76 t:topicdesc="Legislation - Smokefree Indoor Air" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:32fd-hyzc d:2015-10-05T06:30:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=600LEG t:provisiondesc="Weight Requirement of Child (lbs)" t:measureid=642PVE t:measuredesc="Personal Vehicles" t:provisiongroupdesc="Additional Requirements" t:provisiongroupid=20GRP t:provisionvalue="No Provision" t:provisionid=107 t:topicdesc="Legislation - Smokefree Indoor Air" t:datatype=Pounds t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:32fd-hyzc l:"CDC STATE System Tobacco Legislation - Smokefree Indoor Air" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/32fd-hyzc

property e:32fd-hyzc t:meta.view v:id=32fd-hyzc v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem/ v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Smokefree Indoor Air" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:32fd-hyzc t:meta.view.license v:name="Public Domain"

property e:32fd-hyzc t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:32fd-hyzc t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:32fd-hyzc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topicdesc                          | measuredesc                 | datasource | provisiongroupdesc      | provisiondesc                                                              | provisionvalue              | citation                                 | provisionaltvalue | datatype | comments | enacted_date        | effective_date      | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============ | ================================== | =========================== | ========== | ======================= | ========================================================================== | =========================== | ======================================== | ================= | ======== | ======== | =================== | =================== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Private Worksites           | OSH        | Vehicles                | Type of Restriction in Private Worksite Vehicle                            | No Provision                |                                          | 0                 | Ranking  |          |                     |                     | 35           | LEG         | 600LEG  | 605PWK    | 30GRP            | 34          | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Home-based Day Care Centers | OSH        | Penalties               | License Suspension or Revocation                                           | No Provision                |                                          | 0                 | Ranking  |          |                     |                     | 80           | LEG         | 600LEG  | 620HDC    | 60GRP            | 76          | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Personal Vehicles           | OSH        | Additional Requirements | Weight Requirement of Child (lbs)                                          | No Provision                |                                          | 0                 | Pounds   |          |                     |                     | 30           | LEG         | 600LEG  | 642PVE    | 20GRP            | 107         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Private Worksites           | OSH        | Enforcement             | Enforcement Authority                                                      | Yes                         | ALA. CODE ? 22-15A-8(a)                  | 2                 | Yes/No   |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 50           | LEG         | 600LEG  | 605PWK    | 50GRP            | 26          | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Commercial Day Care Centers | OSH        | Vehicles                | Level of Offense                                                           | No Provision                |                                          | 0                 | Ranking  |          |                     |                     | 35           | LEG         | 600LEG  | 615CDC    | 30GRP            | 64          | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Restaurants                 | OSH        | Enforcement             | Enforcement (Type)                                                         | Department of Public Health | ALA. CODE ?? 22-15A-8(a) and 22-15A-3(3) | 0                 |          |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 35           | LEG         | 600LEG  | 610RES    | 50GRP            | 43          | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Government Worksites        | OSH        | Vehicles                | Level of Offense                                                           | No Provision                |                                          | 0                 | Ranking  |          |                     |                     | 55           | LEG         | 600LEG  | 600GWK    | 30GRP            | 19          | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Private Multi-Unit Housing  | OSH        | Restrictions            | Type of Restriction in Lobby and Common Area of Private Multi-Unit Housing | Designated Areas            | ALA. CODE ? 22-15A-6                     | 3                 | Ranking  |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 5            | LEG         | 600LEG  | 602PMH    | 10GRP            | 125         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Home-based Day Care Centers | OSH        | Penalties               | Penalty to Business                                                        | Yes                         | ALA. CODE ? 22-15A-8(b)                  | 2                 | Yes/No   |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 55           | LEG         | 600LEG  | 620HDC    | 60GRP            | 71          | 
| 2015 | 3       | AL           | Alabama      | Legislation - Smokefree Indoor Air | Government Worksites        | OSH        | Penalties               | Penalty to Business (Type)                                                 | Civil Penalty               | ALA. CODE ? 22-15A-8(b)                  | 0                 |          |          | 2003-06-19T00:00:00 | 2003-09-01T00:00:00 | 80           | LEG         | 600LEG  | 600GWK    | 60GRP            | 13          | 
```