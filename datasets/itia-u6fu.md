# CDC STATE System E-Cigarette Legislation - Smokefree Campus

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-e-cigarette-legislation-smokefree-campus-4be2c) |
| Metadata | [Link](https://data.cdc.gov/api/views/itia-u6fu) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/itia-u6fu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/itia-u6fu/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | itia-u6fu |
| Name | CDC STATE System E-Cigarette Legislation - Smokefree Campus |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | osh, state system, legislation, policy, smokefree campus, e-cigarette |
| Created | 2015-05-04T13:44:29Z |
| Publication Date | 2017-02-16T17:14:58Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  E-Cigarette Legislation—Smokefree Campus. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include state smokefree indoor air laws for smokefree campuses in private and public colleges and schools (K-12).

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
| No       |                | displayorder       | DisplayOrder       | number    | text        |
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
series e:itia-u6fu d:1995-10-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:topicid=1043LEG t:provisiondesc="Smokefree Campus" t:measureid=1017PUS t:measuredesc="Public Schools (K-12)" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=525 t:topicdesc="Legislation - E-Cigarette - Smokefree Campus" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:itia-u6fu d:2014-01-01T00:00:00.000Z t:locationabbr=WY t:locationdesc=Wyoming t:topicid=1043LEG t:provisiondesc="Type of Restriction on Bus" t:measureid=1015PRK t:measuredesc="Private Schools (K-12)" t:provisiongroupdesc="Restriction Areas" t:provisiongroupid=15GRP t:provisionvalue="No Provision" t:provisionid=548 t:topicdesc="Legislation - E-Cigarette - Smokefree Campus" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:itia-u6fu d:2004-10-01T00:00:00.000Z t:locationabbr=RI t:locationdesc="Rhode Island" t:topicid=1043LEG t:provisiondesc="Type of Restriction Indoors" t:measureid=1015PRK t:measuredesc="Private Schools (K-12)" t:provisiongroupdesc="Restriction Areas" t:provisiongroupid=15GRP t:provisionvalue="No Provision" t:provisionid=543 t:topicdesc="Legislation - E-Cigarette - Smokefree Campus" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:itia-u6fu l:"CDC STATE System E-Cigarette Legislation - Smokefree Campus" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/itia-u6fu

property e:itia-u6fu t:meta.view v:id=itia-u6fu v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem v:averageRating=0 v:name="CDC STATE System E-Cigarette Legislation - Smokefree Campus" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:itia-u6fu t:meta.view.license v:name="Public Domain"

property e:itia-u6fu t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:itia-u6fu t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:itia-u6fu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc   | topicdesc                                    | measuredesc            | datasource | provisiongroupdesc      | provisiondesc                                | provisionvalue | citation | provisionaltvalue | datatype | comments | enacted_date | effective_date | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============== | ============================================ | ====================== | ========== | ======================= | ============================================ | ============== | ======== | ================= | ======== | ======== | ============ | ============== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 1995 | 4       | AK           | Alaska         | Legislation - E-Cigarette - Smokefree Campus | Public Schools (K-12)  | OSH        | Restrictions            | Smokefree Campus                             | No Provision   |          | 0                 | Ranking  |          |              |                | 1            | LEG         | 1043LEG | 1017PUS   | 10GRP            | 525         | 
| 2014 | 1       | WY           | Wyoming        | Legislation - E-Cigarette - Smokefree Campus | Private Schools (K-12) | OSH        | Restriction Areas       | Type of Restriction on Bus                   | No Provision   |          | 0                 | Ranking  |          |              |                | 7            | LEG         | 1043LEG | 1015PRK   | 15GRP            | 548         | 
| 2004 | 4       | RI           | Rhode Island   | Legislation - E-Cigarette - Smokefree Campus | Private Schools (K-12) | OSH        | Restriction Areas       | Type of Restriction Indoors                  | No Provision   |          | 0                 | Ranking  |          |              |                | 2            | LEG         | 1043LEG | 1015PRK   | 15GRP            | 543         | 
| 2013 | 4       | FL           | Florida        | Legislation - E-Cigarette - Smokefree Campus | Private Schools (K-12) | OSH        | Penalties               | Penalty to School (Type)                     | No Provision   |          | 0                 |          |          |              |                | 14           | LEG         | 1043LEG | 1015PRK   | 60GRP            | 555         | 
| 2014 | 1       | GA           | Georgia        | Legislation - E-Cigarette - Smokefree Campus | Private Colleges       | OSH        | Penalties               | Penalty to User                              | No Provision   |          | 0                 | Ranking  |          |              |                | 12           | LEG         | 1043LEG | 1016PRC   | 60GRP            | 582         | 
| 2008 | 1       | VT           | Vermont        | Legislation - E-Cigarette - Smokefree Campus | Public Colleges        | OSH        | Restriction Areas       | Type of Restriction Indoors                  | No Provision   |          | 0                 | Ranking  |          |              |                | 2            | LEG         | 1043LEG | 1018PUC   | 15GRP            | 560         | 
| 2014 | 4       | MD           | Maryland       | Legislation - E-Cigarette - Smokefree Campus | Public Colleges        | OSH        | Restriction Areas       | Type of Restriction in Dormitories           | No Provision   |          | 0                 | Ranking  |          |              |                | 3            | LEG         | 1043LEG | 1018PUC   | 15GRP            | 561         | 
| 2014 | 4       | SC           | South Carolina | Legislation - E-Cigarette - Smokefree Campus | Public Schools (K-12)  | OSH        | Additional Requirements | E-Cigarette Education Required in Curriculum | No Provision   |          | 0                 | Ranking  |          |              |                | 9            | LEG         | 1043LEG | 1017PUS   | 20GRP            | 533         | 
| 2007 | 4       | MN           | Minnesota      | Legislation - E-Cigarette - Smokefree Campus | Private Schools (K-12) | OSH        | Penalties               | Penalty to School                            | No Provision   |          | 0                 | Ranking  |          |              |                | 13           | LEG         | 1043LEG | 1015PRK   | 60GRP            | 554         | 
| 1999 | 4       | AR           | Arkansas       | Legislation - E-Cigarette - Smokefree Campus | Private Colleges       | OSH        | Enforcement             | Enforcement Authority                        | No Provision   |          | 0                 | Ranking  |          |              |                | 5            | LEG         | 1043LEG | 1016PRC   | 50GRP            | 575         | 
```