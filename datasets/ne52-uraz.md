# CDC STATE System E-Cigarette Legislation - Licensure

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-e-cigarette-legislation-licensure-6c23d) |
| Metadata | [Link](https://data.cdc.gov/api/views/ne52-uraz) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/ne52-uraz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/ne52-uraz/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | ne52-uraz |
| Name | CDC STATE System E-Cigarette Legislation - Licensure |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | osh, state system, legislation, policy, licensure, e-cigarette |
| Created | 2015-05-04T14:15:15Z |
| Publication Date | 2017-02-16T17:16:27Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  E-Cigarette Legislation?Licensure. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies.  Data are reported on a quarterly basis. Data include information related to requirements, restrictions and penalties associated with holding a retail license to sell e-cigarettes over-the-counter and through vending machines.

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
series e:ne52-uraz d:1995-10-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:topicid=1044LEG t:provisiondesc="License Required" t:measureid=1019LOC t:measuredesc=Over-the-Counter t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=759 t:topicdesc="Legislation - E-Cigarette - Licensure" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:ne52-uraz d:2013-10-01T00:00:00.000Z t:locationabbr=SC t:locationdesc="South Carolina" t:topicid=1044LEG t:provisiondesc="Penalty to Business (Type)" t:measureid=1020LVM t:measuredesc="Vending Machines" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Provision" t:provisionid=782 t:topicdesc="Legislation - E-Cigarette - Licensure" t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:ne52-uraz d:2010-10-01T00:00:00.000Z t:locationabbr=CO t:locationdesc=Colorado t:topicid=1044LEG t:provisiondesc="Penalty to Business" t:measureid=1019LOC t:measuredesc=Over-the-Counter t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Provision" t:provisionid=768 t:topicdesc="Legislation - E-Cigarette - Licensure" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:ne52-uraz l:"CDC STATE System E-Cigarette Legislation - Licensure" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/ne52-uraz

property e:ne52-uraz t:meta.view v:id=ne52-uraz v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem v:averageRating=0 v:name="CDC STATE System E-Cigarette Legislation - Licensure" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:ne52-uraz t:meta.view.license v:name="Public Domain"

property e:ne52-uraz t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:ne52-uraz t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:ne52-uraz t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc   | topicdesc                             | measuredesc      | datasource | provisiongroupdesc      | provisiondesc                   | provisionvalue | citation | provisionaltvalue | datatype | comments | enacted_date | effective_date | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============== | ===================================== | ================ | ========== | ======================= | =============================== | ============== | ======== | ================= | ======== | ======== | ============ | ============== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 1995 | 4       | AK           | Alaska         | Legislation - E-Cigarette - Licensure | Over-the-Counter | OSH        | Restrictions            | License Required                | No Provision   |          | 0                 | Yes/No   |          |              |                | 1            | LEG         | 1044LEG | 1019LOC   | 10GRP            | 759         | 
| 2013 | 4       | SC           | South Carolina | Legislation - E-Cigarette - Licensure | Vending Machines | OSH        | Penalties               | Penalty to Business (Type)      | No Provision   |          | 0                 |          |          |              |                | 13           | LEG         | 1044LEG | 1020LVM   | 60GRP            | 782         | 
| 2010 | 4       | CO           | Colorado       | Legislation - E-Cigarette - Licensure | Over-the-Counter | OSH        | Penalties               | Penalty to Business             | No Provision   |          | 0                 | Yes/No   |          |              |                | 10           | LEG         | 1044LEG | 1019LOC   | 60GRP            | 768         | 
| 2006 | 2       | CT           | Connecticut    | Legislation - E-Cigarette - Licensure | Over-the-Counter | OSH        | Penalties               | Penalty to Business (Type)      | No Provision   |          | 0                 |          |          |              |                | 11           | LEG         | 1044LEG | 1019LOC   | 60GRP            | 769         | 
| 2012 | 3       | LA           | Louisiana      | Legislation - E-Cigarette - Licensure | Vending Machines | OSH        | Additional Requirements | Fee per Machine Maximum ($)     | No Provision   |          | 0                 | Money    |          |              |                | 4            | LEG         | 1044LEG | 1020LVM   | 20GRP            | 773         | 
| 1995 | 4       | TX           | Texas          | Legislation - E-Cigarette - Licensure | Over-the-Counter | OSH        | Additional Requirements | Minimum License Fee ($)         | No Provision   |          | 0                 | Money    |          |              |                | 6            | LEG         | 1044LEG | 1019LOC   | 20GRP            | 764         | 
| 2006 | 2       | HI           | Hawaii         | Legislation - E-Cigarette - Licensure | Over-the-Counter | OSH        | Penalties               | Minimum Penalty to Business ($) | No Provision   |          | 0                 | Money    |          |              |                | 9            | LEG         | 1044LEG | 1019LOC   | 60GRP            | 767         | 
| 2013 | 4       | OK           | Oklahoma       | Legislation - E-Cigarette - Licensure | Vending Machines | OSH        | Additional Requirements | Fee per Machine Maximum ($)     | No Provision   |          | 0                 | Money    |          |              |                | 4            | LEG         | 1044LEG | 1020LVM   | 20GRP            | 773         | 
| 2015 | 1       | MS           | Mississippi    | Legislation - E-Cigarette - Licensure | Over-the-Counter | OSH        | Additional Requirements | License Fee Required            | No Provision   |          | 0                 | Yes/No   |          |              |                | 4            | LEG         | 1044LEG | 1019LOC   | 20GRP            | 762         | 
| 2007 | 2       | TX           | Texas          | Legislation - E-Cigarette - Licensure | Vending Machines | OSH        | Penalties               | Penalty to Business (Type)      | No Provision   |          | 0                 |          |          |              |                | 13           | LEG         | 1044LEG | 1020LVM   | 60GRP            | 782         | 
```