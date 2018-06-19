# CDC STATE System E-Cigarette Legislation - Tax

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-e-cigarette-legislation-tax) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/kwbr-syv2) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/kwbr-syv2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/kwbr-syv2/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | kwbr-syv2 |
| Name | CDC STATE System E-Cigarette Legislation - Tax |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | osh, state system, legislation, policy, tax, e-cigarette |
| Created | 2015-05-04T13:31:44Z |
| Publication Date | 2017-02-16T17:16:49Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  E-Cigarette Legislation?Tax. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include state excise taxes on e-cigarettes and tax stamps.

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
series e:kwbr-syv2 d:1995-10-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:topicid=1040LEG t:provisiondesc="E-Cigarette Tax" t:measureid=1001ETR t:measuredesc=E-Cigarette t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=450 t:topicdesc="Legislation - E-Cigarette - Tax" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:kwbr-syv2 d:2012-10-01T00:00:00.000Z t:locationabbr=KY t:locationdesc=Kentucky t:topicid=1040LEG t:provisiondesc="Tax Stamp Required" t:measureid=1023CET t:measuredesc="Tax Stamp" t:provisiongroupdesc=Requirements t:provisiongroupid=12GRP t:provisionvalue="No Provision" t:provisionid=477 t:topicdesc="Legislation - E-Cigarette - Tax" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:kwbr-syv2 d:2006-10-01T00:00:00.000Z t:locationabbr=SC t:locationdesc="South Carolina" t:topicid=1040LEG t:provisiondesc="Barcode/Scannable Code Required" t:measureid=1023CET t:measuredesc="Tax Stamp" t:provisiongroupdesc=Requirements t:provisiongroupid=12GRP t:provisionvalue="No Provision" t:provisionid=478 t:topicdesc="Legislation - E-Cigarette - Tax" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0
```

## Meta Commands

```ls
metric m:provisionaltvalue p:double l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:kwbr-syv2 l:"CDC STATE System E-Cigarette Legislation - Tax" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/kwbr-syv2

property e:kwbr-syv2 t:meta.view v:id=kwbr-syv2 v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem v:averageRating=0 v:name="CDC STATE System E-Cigarette Legislation - Tax" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:kwbr-syv2 t:meta.view.license v:name="Public Domain"

property e:kwbr-syv2 t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:kwbr-syv2 t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:kwbr-syv2 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc   | topicdesc                       | measuredesc | datasource | provisiongroupdesc | provisiondesc                   | provisionvalue | citation | provisionaltvalue | datatype | comments | enacted_date | effective_date | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============== | =============================== | =========== | ========== | ================== | =============================== | ============== | ======== | ================= | ======== | ======== | ============ | ============== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 1995 | 4       | AK           | Alaska         | Legislation - E-Cigarette - Tax | E-Cigarette | OSH        | Restrictions       | E-Cigarette Tax                 | No Provision   |          | 0                 | Yes/No   |          |              |                | 1            | LEG         | 1040LEG | 1001ETR   | 10GRP            | 450         | 
| 2012 | 4       | KY           | Kentucky       | Legislation - E-Cigarette - Tax | Tax Stamp   | OSH        | Requirements       | Tax Stamp Required              | No Provision   |          | 0                 | Ranking  |          |              |                | 1            | LEG         | 1040LEG | 1023CET   | 12GRP            | 477         | 
| 2006 | 4       | SC           | South Carolina | Legislation - E-Cigarette - Tax | Tax Stamp   | OSH        | Requirements       | Barcode/Scannable Code Required | No Provision   |          | 0                 | Ranking  |          |              |                | 2            | LEG         | 1040LEG | 1023CET   | 12GRP            | 478         | 
| 2007 | 2       | AZ           | Arizona        | Legislation - E-Cigarette - Tax | Tax Stamp   | OSH        | Requirements       | Other Requirements              | No Provision   |          | 0                 | Ranking  |          |              |                | 4            | LEG         | 1040LEG | 1023CET   | 12GRP            | 480         | 
| 2001 | 4       | KY           | Kentucky       | Legislation - E-Cigarette - Tax | E-Cigarette | OSH        | Restrictions       | Type of Tax                     | No Provision   |          | 0                 |          |          |              |                | 4            | LEG         | 1040LEG | 1001ETR   | 10GRP            | 453         | 
| 2011 | 4       | TX           | Texas          | Legislation - E-Cigarette - Tax | Tax Stamp   | OSH        | Requirements       | Barcode/Scannable Code Required | No Provision   |          | 0                 | Ranking  |          |              |                | 2            | LEG         | 1040LEG | 1023CET   | 12GRP            | 478         | 
| 2007 | 2       | CT           | Connecticut    | Legislation - E-Cigarette - Tax | Tax Stamp   | OSH        | Requirements       | Barcode/Scannable Code Required | No Provision   |          | 0                 | Ranking  |          |              |                | 2            | LEG         | 1040LEG | 1023CET   | 12GRP            | 478         | 
| 2013 | 2       | OK           | Oklahoma       | Legislation - E-Cigarette - Tax | Tax Stamp   | OSH        | Requirements       | Tax Stamp Required              | No Provision   |          | 0                 | Ranking  |          |              |                | 1            | LEG         | 1040LEG | 1023CET   | 12GRP            | 477         | 
| 2008 | 2       | IN           | Indiana        | Legislation - E-Cigarette - Tax | Tax Stamp   | OSH        | Requirements       | Barcode/Scannable Code Required | No Provision   |          | 0                 | Ranking  |          |              |                | 2            | LEG         | 1040LEG | 1023CET   | 12GRP            | 478         | 
| 2013 | 3       | WV           | West Virginia  | Legislation - E-Cigarette - Tax | E-Cigarette | OSH        | Restrictions       | Percent Value                   | No Provision   |          | 0                 | Number   |          |              |                | 3            | LEG         | 1040LEG | 1001ETR   | 10GRP            | 452         | 
```