# CDC STATE System E-Cigarette Legislation - Smokefree Indoor Air

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-e-cigarette-legislation-smokefree-indoor-air) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/wan8-w4er) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/wan8-w4er/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/wan8-w4er/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | wan8-w4er |
| Name | CDC STATE System E-Cigarette Legislation - Smokefree Indoor Air |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | osh, state system, legislation, policy, smokefree indoor air, e-cigarette |
| Created | 2015-05-04T13:26:14Z |
| Publication Date | 2017-02-16T17:14:34Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC).  State Tobacco Activities Tracking and Evaluation (STATE) System.  E-Cigarette Legislation?Smokefree Indoor Air. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include information related to state legislation on smokefree indoor air in areas such as: Bars, Commercial Day Care Centers, Government Multi-Unit Housing, Government Worksites, Home-Based Day Care Centers, Hotels and Motels, Personal Vehicles, Private Multi-Unit Housing, Private Worksites, Restaurants, Bingo Halls, Casinos, Enclosed Arenas, Grocery Stores, Hospitals, Hospital Campuses, Malls, Mental Health Outpatient and Residential Facilities, Prisons, Public Transportation, Racetrack Casinos, Substance Abuse Outpatient and Residential Facilities.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       |                | year               | YEAR               | number    | number      |
| No       |                | quarter            | Quarter            | number    | number      |
| Yes      | series tag     | locationabbr       | LocationAbbr       | text      | text        |
| Yes      | series tag     | locationdesc       | LocationDesc       | text      | text        |
| Yes      | series tag     | topicdesc          | TopicDesc          | text      | text        |
| Yes      | series tag     | measuredesc        | MeasureDesc        | text      | text        |
| Yes      | series tag     | datasource         | DataSource         | text      | text        |
| Yes      | series tag     | provisiongroupdesc | ProvisionGroupDesc | text      | text        |
| Yes      | series tag     | provisiondesc      | ProvisionDesc      | text      | text        |
| Yes      | series tag     | provisionvalue     | ProvisionValue     | text      | text        |
| Yes      | series tag     | citation           | Citation           | text      | text        |
| Yes      | numeric metric | provisionaltvalue  | ProvisionAltValue  | number    | number      |
| Yes      | series tag     | datatype           | DataType           | text      | text        |
| Yes      | series tag     | comments           | Comments           | text      | text        |
| No       |                | enacted_date       | Enacted_Date       | text      | text        |
| No       |                | effective_date     | Effective_Date     | text      | text        |
| No       |                | displayorder       | DisplayOrder       | number    | number      |
| Yes      | series tag     | topictypeid        | TopicTypeId        | text      | text        |
| Yes      | series tag     | topicid            | TopicId            | text      | text        |
| Yes      | series tag     | measureid          | MeasureId          | text      | text        |
| Yes      | series tag     | provisiongroupid   | ProvisionGroupID   | text      | text        |
| Yes      | series tag     | provisionid        | ProvisionID        | text      | number      |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = enacted_date,effective_date,displayorder,year,quarter
```

## Data Commands

```ls
series e:wan8-w4er d:1995-10-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:topicid=1042LEG t:provisiondesc="Type of Restriction in Bar (Summary)" t:measureid=1013BAR t:measuredesc=Bars t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=583 t:topicdesc="Legislation - E-Cigarette - Smokefree Indoor Air" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:wan8-w4er d:1998-10-01T00:00:00.000Z t:locationabbr=ID t:locationdesc=Idaho t:topicid=1042LEG t:provisiondesc="Restriction in Effect at All Times" t:measureid=1009HDC t:measuredesc="Home-based Day Care Centers" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=632 t:topicdesc="Legislation - E-Cigarette - Smokefree Indoor Air" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:wan8-w4er d:2007-10-01T00:00:00.000Z t:locationabbr=LA t:locationdesc=Louisiana t:topicid=1042LEG t:provisiondesc="Enforcement (Type)" t:measureid=1006PWK t:measuredesc="Private Worksites" t:provisiongroupdesc=Enforcement t:provisiongroupid=50GRP t:provisionvalue="No Provision" t:provisionid=693 t:topicdesc="Legislation - E-Cigarette - Smokefree Indoor Air" t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:wan8-w4er l:"CDC STATE System E-Cigarette Legislation - Smokefree Indoor Air" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/wan8-w4er

property e:wan8-w4er t:meta.view v:id=wan8-w4er v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem v:averageRating=0 v:name="CDC STATE System E-Cigarette Legislation - Smokefree Indoor Air" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:wan8-w4er t:meta.view.license v:name="Public Domain"

property e:wan8-w4er t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:wan8-w4er t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:wan8-w4er t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topicdesc                                        | measuredesc                        | datasource | provisiongroupdesc      | provisiondesc                              | provisionvalue | citation | provisionaltvalue | datatype | comments | enacted_date | effective_date | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============ | ================================================ | ================================== | ========== | ======================= | ========================================== | ============== | ======== | ================= | ======== | ======== | ============ | ============== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 1995 | 4       | AK           | Alaska       | Legislation - E-Cigarette - Smokefree Indoor Air | Bars                               | OSH        | Restrictions            | Type of Restriction in Bar (Summary)       | No Provision   |          | 0                 | Ranking  |          |              |                | 1            | LEG         | 1042LEG | 1013BAR   | 10GRP            | 583         | 
| 1998 | 4       | ID           | Idaho        | Legislation - E-Cigarette - Smokefree Indoor Air | Home-based Day Care Centers        | OSH        | Restrictions            | Restriction in Effect at All Times         | No Provision   |          | 0                 | Ranking  |          |              |                | 2            | LEG         | 1042LEG | 1009HDC   | 10GRP            | 632         | 
| 2007 | 4       | LA           | Louisiana    | Legislation - E-Cigarette - Smokefree Indoor Air | Private Worksites                  | OSH        | Enforcement             | Enforcement (Type)                         | No Provision   |          | 0                 |          |          |              |                | 11           | LEG         | 1042LEG | 1006PWK   | 50GRP            | 693         | 
| 2009 | 2       | IA           | Iowa         | Legislation - E-Cigarette - Smokefree Indoor Air | Private Multi-Unit Housing         | OSH        | Enforcement             | Enforcement (Type)                         | No Provision   |          | 0                 |          |          |              |                | 4            | LEG         | 1042LEG | 1005PMH   | 50GRP            | 676         | 
| 2006 | 3       | WI           | Wisconsin    | Legislation - E-Cigarette - Smokefree Indoor Air | Home-based Day Care Centers        | OSH        | Penalties               | License Suspension or Revocation           | No Provision   |          | 0                 | Ranking  |          |              |                | 16           | LEG         | 1042LEG | 1009HDC   | 60GRP            | 646         | 
| 2012 | 3       | LA           | Louisiana    | Legislation - E-Cigarette - Smokefree Indoor Air | Commercial Day Care Centers        | OSH        | Restrictions            | Type of Restriction in Commercial Day Care | No Provision   |          | 0                 | Ranking  |          |              |                | 1            | LEG         | 1042LEG | 1008CDC   | 10GRP            | 595         | 
| 2005 | 4       | NE           | Nebraska     | Legislation - E-Cigarette - Smokefree Indoor Air | Restaurants                        | OSH        | Additional Requirements | Minimum Seating Capacity                   | No Provision   |          | 0                 | Ranking  |          |              |                | 6            | LEG         | 1042LEG | 1007RES   | 20GRP            | 705         | 
| 2010 | 1       | MT           | Montana      | Legislation - E-Cigarette - Smokefree Indoor Air | Restaurants                        | OSH        | Penalties               | Penalty to User                            | No Provision   |          | 0                 | Ranking  |          |              |                | 16           | LEG         | 1042LEG | 1007RES   | 60GRP            | 715         | 
| 2007 | 4       | MS           | Mississippi  | Legislation - E-Cigarette - Smokefree Indoor Air | Personal Vehicles                  | OSH        | Penalties               | Penalty to Driver                          | No Provision   |          | 0                 | Ranking  |          |              |                | 10           | LEG         | 1042LEG | 1012PVE   | 60GRP            | 669         | 
| 2002 | 4       | OH           | Ohio         | Legislation - E-Cigarette - Smokefree Indoor Air | Smokefree Indoor Air ? Other Sites | OSH        | Restriction Areas       | Hospitals                                  | No Provision   |          | 0                 | Ranking  |          |              |                | 5            | LEG         | 1042LEG | 1011SIO   | 15GRP            | 720         | 
```