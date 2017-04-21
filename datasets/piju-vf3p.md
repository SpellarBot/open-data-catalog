# CDC STATE System E-Cigarette Legislation - Preemption

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-e-cigarette-legislation-preemption-0ece7) |
| Metadata | [Link](https://data.cdc.gov/api/views/piju-vf3p) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/piju-vf3p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/piju-vf3p/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | piju-vf3p |
| Name | CDC STATE System E-Cigarette Legislation - Preemption |
| Attribution | ? Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | osh, state system, legislation, policy, preemption, e-cigarette |
| Created | 2015-05-04T14:12:39Z |
| Publication Date | 2017-02-16T17:15:38Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  E-Cigarette Legislation?Preemption. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies.  Data are reported on a quarterly basis. Data include information related to statutory state preemption of more stringent local laws on advertising, smokefree indoor air, youth access and licensure.

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
series e:piju-vf3p d:1995-10-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:topicid=1046LEG t:provisiondesc="Government worksites - Statutory Preemption" t:measureid=1022PRI t:measuredesc="Preemption on Smokefree Indoor Air" t:provisiongroupdesc="Government Worksites" t:provisiongroupid=22GRP t:provisionvalue="No Provision" t:provisionid=730 t:topicdesc="Legislation - E-Cigarette - Preemption" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:piju-vf3p d:2008-04-01T00:00:00.000Z t:locationabbr=VT t:locationdesc=Vermont t:topicid=1046LEG t:provisiondesc=Promotion t:measureid=1026PRA t:measuredesc="Preemption on Advertising" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=752 t:topicdesc="Legislation - E-Cigarette - Preemption" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:piju-vf3p d:1996-10-01T00:00:00.000Z t:locationabbr=PA t:locationdesc=Pennsylvania t:topicid=1046LEG t:provisiondesc=Promotion t:measureid=1026PRA t:measuredesc="Preemption on Advertising" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=752 t:topicdesc="Legislation - E-Cigarette - Preemption" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:piju-vf3p l:"CDC STATE System E-Cigarette Legislation - Preemption" t:attribution="? Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/piju-vf3p

property e:piju-vf3p t:meta.view v:id=piju-vf3p v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem v:averageRating=0 v:name="CDC STATE System E-Cigarette Legislation - Preemption" v:attribution="? Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:piju-vf3p t:meta.view.license v:name="Public Domain"

property e:piju-vf3p t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:piju-vf3p t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:piju-vf3p t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc  | topicdesc                              | measuredesc                        | datasource | provisiongroupdesc   | provisiondesc                               | provisionvalue | citation | provisionaltvalue | datatype | comments | enacted_date | effective_date | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============= | ====================================== | ================================== | ========== | ==================== | =========================================== | ============== | ======== | ================= | ======== | ======== | ============ | ============== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 1995 | 4       | AK           | Alaska        | Legislation - E-Cigarette - Preemption | Preemption on Smokefree Indoor Air | OSH        | Government Worksites | Government worksites - Statutory Preemption | No Provision   |          | 0                 | Yes/No   |          |              |                | 1            | LEG         | 1046LEG | 1022PRI   | 22GRP            | 730         | 
| 2008 | 2       | VT           | Vermont       | Legislation - E-Cigarette - Preemption | Preemption on Advertising          | OSH        | Restrictions         | Promotion                                   | No Provision   |          | 0                 | Yes/No   |          |              |                | 1            | LEG         | 1046LEG | 1026PRA   | 10GRP            | 752         | 
| 1996 | 4       | PA           | Pennsylvania  | Legislation - E-Cigarette - Preemption | Preemption on Advertising          | OSH        | Restrictions         | Promotion                                   | No Provision   |          | 0                 | Yes/No   |          |              |                | 1            | LEG         | 1046LEG | 1026PRA   | 10GRP            | 752         | 
| 2013 | 3       | NH           | New Hampshire | Legislation - E-Cigarette - Preemption | Preemption on Youth Access         | OSH        | Restrictions         | Vending Machines                            | No Provision   |          | 0                 | Yes/No   |          |              |                | 3            | LEG         | 1046LEG | 1025PRY   | 10GRP            | 758         | 
| 1999 | 4       | NE           | Nebraska      | Legislation - E-Cigarette - Preemption | Preemption on Smokefree Indoor Air | OSH        | Private Worksites    | Private worksites - Case Holding Date(s)    | No Provision   |          | 0                 | Number   |          |              |                | 10           | LEG         | 1046LEG | 1022PRI   | 23GRP            | 737         | 
| 2011 | 4       | GA           | Georgia       | Legislation - E-Cigarette - Preemption | Preemption on Advertising          | OSH        | Restrictions         | Display                                     | No Provision   |          | 0                 | Yes/No   |          |              |                | 2            | LEG         | 1046LEG | 1026PRA   | 10GRP            | 753         | 
| 2007 | 3       | PA           | Pennsylvania  | Legislation - E-Cigarette - Preemption | Preemption on Smokefree Indoor Air | OSH        | Bars                 | Bars - Case Summary Text                    | No Provision   |          | 0                 |          |          |              |                | 15           | LEG         | 1046LEG | 1022PRI   | 21GRP            | 748         | 
| 2011 | 3       | KY           | Kentucky      | Legislation - E-Cigarette - Preemption | Preemption on Smokefree Indoor Air | OSH        | Private Worksites    | Private worksites - Case Law Preemption     | No Provision   |          | 0                 | Yes/No   |          |              |                | 5            | LEG         | 1046LEG | 1022PRI   | 23GRP            | 736         | 
| 2005 | 4       | MS           | Mississippi   | Legislation - E-Cigarette - Preemption | Preemption on Smokefree Indoor Air | OSH        | Bars                 | Bars - Case Law Preemption                  | No Provision   |          | 0                 | Yes/No   |          |              |                | 5            | LEG         | 1046LEG | 1022PRI   | 21GRP            | 746         | 
| 2008 | 2       | MN           | Minnesota     | Legislation - E-Cigarette - Preemption | Preemption on Smokefree Indoor Air | OSH        | Restaurants          | Restaurants - Statutory Preemption          | No Provision   |          | 0                 | Yes/No   |          |              |                | 1            | LEG         | 1046LEG | 1022PRI   | 24GRP            | 740         | 
```