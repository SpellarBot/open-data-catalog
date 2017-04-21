# CDC STATE System Tobacco Legislation - Youth Access

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-youth-access) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/hgv5-3wrn) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/hgv5-3wrn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/hgv5-3wrn/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | hgv5-3wrn |
| Name | CDC STATE System Tobacco Legislation - Youth Access |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, youth access |
| Created | 2014-07-14T21:18:49Z |
| Publication Date | 2017-02-16T17:21:29Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation?Youth Access. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies.  Data are reported on a quarterly basis. Data include information related to restrictions, enforcement and penalties associated with the sale of cigarettes to youth through retail sales and vending machines.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| No       |                | year               | YEAR               | number        | number        |
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
series e:hgv5-3wrn d:1911-03-24T00:00:00.000Z t:locationabbr=CA t:locationdesc=California t:citation="CAL. PEN. CODE ? 308(a) and CAL. BUS. & PROF. CODE ? 22958(a)" t:topicid=606LEG t:provisiondesc="Penalty to Business" t:measureid=628YAC t:measuredesc="Cigarette Sales" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue=Yes t:provisionid=201 t:topicdesc="Legislation - Youth Access" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=2

series e:hgv5-3wrn d:1997-06-23T00:00:00.000Z t:locationabbr=NH t:locationdesc="New Hampshire" t:citation="N.H. REV. STAT. ANN. ? 126-K:4(II)" t:topicid=606LEG t:provisiondesc="Penalty to Business (Type)" t:measureid=628YAC t:measuredesc="Cigarette Sales" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="Civil Infraction; fine" t:provisionid=194 t:topicdesc="Legislation - Youth Access" t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:hgv5-3wrn d:1903-04-08T00:00:00.000Z t:locationabbr=NE t:locationdesc=Nebraska t:citation="NEB. REV. STAT. ? 28-1419" t:topicid=606LEG t:provisiondesc="Minimum Age (Years)" t:measureid=628YAC t:measuredesc="Cigarette Sales" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue=18 t:provisionid=203 t:topicdesc="Legislation - Youth Access" t:datatype=Years t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=18
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:hgv5-3wrn l:"CDC STATE System Tobacco Legislation - Youth Access" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/hgv5-3wrn

property e:hgv5-3wrn t:meta.view v:id=hgv5-3wrn v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem/ v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Youth Access" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:hgv5-3wrn t:meta.view.license v:name="Public Domain"

property e:hgv5-3wrn t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:hgv5-3wrn t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:hgv5-3wrn t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc  | topicdesc                  | measuredesc                | datasource | provisiongroupdesc | provisiondesc                | provisionvalue         | citation                                                      | provisionaltvalue | datatype | comments | enacted_date        | effective_date      | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============= | ========================== | ========================== | ========== | ================== | ============================ | ====================== | ============================================================= | ================= | ======== | ======== | =================== | =================== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 2015 | 1       | CA           | California    | Legislation - Youth Access | Cigarette Sales            | OSH        | Penalties          | Penalty to Business          | Yes                    | CAL. PEN. CODE ? 308(a) and CAL. BUS. & PROF. CODE ? 22958(a) | 2                 | Yes/No   |          | 1911-03-24T00:00:00 |                     | 5            | LEG         | 606LEG  | 628YAC    | 60GRP            | 201         | 
| 2015 | 1       | NH           | New Hampshire | Legislation - Youth Access | Cigarette Sales            | OSH        | Penalties          | Penalty to Business (Type)   | Civil Infraction; fine | N.H. REV. STAT. ANN. ? 126-K:4(II)                            | 0                 |          |          | 1997-06-23T00:00:00 | 1998-01-01T00:00:00 | 15           | LEG         | 606LEG  | 628YAC    | 60GRP            | 194         | 
| 2015 | 1       | NE           | Nebraska      | Legislation - Youth Access | Cigarette Sales            | OSH        | Restrictions       | Minimum Age (Years)          | 18                     | NEB. REV. STAT. ? 28-1419                                     | 18                | Years    |          | 1903-04-08T00:00:00 | 1903-07-07T00:00:00 | 70           | LEG         | 606LEG  | 628YAC    | 10GRP            | 203         | 
| 2015 | 1       | MA           | Massachusetts | Legislation - Youth Access | Cigarette Sales            | OSH        | Penalties          | Penalty to Youth (Type)      | No Provision           |                                                               | 0                 |          |          |                     |                     | 40           | LEG         | 606LEG  | 628YAC    | 60GRP            | 197         | 
| 2015 | 1       | NV           | Nevada        | Legislation - Youth Access | Cigarette Vending Machines | OSH        | Penalties          | Penalty to Business (Type)   | Civil penalty; Fine    | NEV. REV. STAT. ? 202.2493(2)                                 | 0                 |          |          | 2007-10-01T00:00:00 | 2007-10-01T00:00:00 | 5            | LEG         | 606LEG  | 629YAV    | 60GRP            | 211         | 
| 2015 | 1       | MA           | Massachusetts | Legislation - Youth Access | Cigarette Sales            | OSH        | Penalties          | Maximum Penalty to Youth ($) | No Provision           |                                                               | 0                 | Money    |          |                     |                     | 50           | LEG         | 606LEG  | 628YAC    | 60GRP            | 198         | 
| 2015 | 1       | IA           | Iowa          | Legislation - Youth Access | Cigarette Sales            | OSH        | Penalties          | Penalty to Youth             | Yes                    | IOWA CODE ?? 453A.3 and ? 805.8C                              | 2                 | Yes/No   |          | 1959-05-07T00:00:00 | 1959-07-04T00:00:00 | 35           | LEG         | 606LEG  | 628YAC    | 60GRP            | 200         | 
| 2015 | 1       | NE           | Nebraska      | Legislation - Youth Access | Cigarette Sales            | OSH        | Enforcement        | Enforcement Authority        | No Provision           |                                                               | 0                 | Yes/No   |          |                     |                     | 5            | LEG         | 606LEG  | 628YAC    | 50GRP            | 191         | 
| 2015 | 1       | AR           | Arkansas      | Legislation - Youth Access | Cigarette Vending Machines | OSH        | Restrictions       | Locking Device               | No Provision           |                                                               | 0                 | Yes/No   |          |                     |                     | 20           | LEG         | 606LEG  | 629YAV    | 10GRP            | 218         | 
| 2015 | 1       | VT           | Vermont       | Legislation - Youth Access | Cigarette Vending Machines | OSH        | Enforcement        | Enforcement (Type)           | Liquor Control Board   | VT. STAT. ANN. tit. 7, ? 1008                                 | 0                 |          |          | 1991-06-21T00:00:00 | 1992-05-01T00:00:00 | 10           | LEG         | 606LEG  | 629YAV    | 50GRP            | 210         | 
```