# CDC STATE System Tobacco Legislation - Licensure

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-licensure) |
| Metadata | [Link](https://data.cdc.gov/api/views/eb4y-d4ic) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/eb4y-d4ic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/eb4y-d4ic/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | eb4y-d4ic |
| Name | CDC STATE System Tobacco Legislation - Licensure |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, licensure |
| Created | 2014-07-15T17:37:50Z |
| Publication Date | 2017-02-16T17:21:28Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation?Licensure. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies.  Data are reported on a quarterly basis. Data include information related to requirements, restrictions and penalties associated with holding a retail license to sell tobacco products over-the-counter and through vending machines.

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
series e:eb4y-d4ic d:2014-08-24T00:00:00.000Z t:locationabbr=IL t:locationdesc=Illinois t:citation="35 ILL. COMP. STAT. ANN. 130/3-10" t:topicid=604LEG t:provisiondesc="Penalty to Business (Type)" t:measureid=640LOC t:measuredesc=Over-the-Counter t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="Class 4 Misdemeanor; Fine" t:provisionid=169 t:topicdesc="Legislation - Licensure" t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:eb4y-d4ic d:2014-08-24T00:00:00.000Z t:locationabbr=IL t:locationdesc=Illinois t:citation="35 ILL. COMP. STAT. ANN. 130/4G" t:topicid=604LEG t:provisiondesc="Renewal Frequency (Years)" t:measureid=640LOC t:measuredesc=Over-the-Counter t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue=1 t:provisionid=173 t:topicdesc="Legislation - Licensure" t:datatype=Years t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=1

series e:eb4y-d4ic d:2014-08-24T00:00:00.000Z t:locationabbr=IL t:locationdesc=Illinois t:citation="35 ILL. COMP. STAT. ANN. 130/4G" t:topicid=604LEG t:provisiondesc="Includes Cigarettes" t:measureid=640LOC t:measuredesc=Over-the-Counter t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue=Yes t:provisionid=172 t:topicdesc="Legislation - Licensure" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=2
```

## Meta Commands

```ls
metric m:provisionaltvalue p:double l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:eb4y-d4ic l:"CDC STATE System Tobacco Legislation - Licensure" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/eb4y-d4ic

property e:eb4y-d4ic t:meta.view v:id=eb4y-d4ic v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem/ v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Licensure" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:eb4y-d4ic t:meta.view.license v:name="Public Domain"

property e:eb4y-d4ic t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:eb4y-d4ic t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:eb4y-d4ic t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topicdesc               | measuredesc      | datasource | provisiongroupdesc      | provisiondesc                   | provisionvalue            | citation                          | provisionaltvalue | datatype | comments | enacted_date        | effective_date      | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============ | ======================= | ================ | ========== | ======================= | =============================== | ========================= | ================================= | ================= | ======== | ======== | =================== | =================== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Penalties               | Penalty to Business (Type)      | Class 4 Misdemeanor; Fine | 35 ILL. COMP. STAT. ANN. 130/3-10 | 0                 |          |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 20           | LEG         | 604LEG  | 640LOC    | 60GRP            | 169         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Restrictions            | Renewal Frequency (Years)       | 1                         | 35 ILL. COMP. STAT. ANN. 130/4G   | 1                 | Years    |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 65           | LEG         | 604LEG  | 640LOC    | 10GRP            | 173         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Restrictions            | Includes Cigarettes             | Yes                       | 35 ILL. COMP. STAT. ANN. 130/4G   | 2                 | Yes/No   |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 50           | LEG         | 604LEG  | 640LOC    | 10GRP            | 172         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Restrictions            | License Required                | Yes                       | 35 ILL. COMP. STAT. ANN. 130/4G   | 2                 | Yes/No   |          | 2014-08-26T00:00:00 | 2016-01-01T00:00:00 | 45           | LEG         | 604LEG  | 640LOC    | 10GRP            | 175         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Additional Requirements | License Fee Required            | Yes                       | 35 ILL. COMP. STAT. ANN. 130/4G   | 2                 | Yes/No   |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 15           | LEG         | 604LEG  | 640LOC    | 20GRP            | 165         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Restrictions            | Renewal Required                | Yes                       | 35 ILL. COMP. STAT. ANN. 130/4G   | 2                 | Yes/No   |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 60           | LEG         | 604LEG  | 640LOC    | 10GRP            | 174         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Penalties               | Maximum Penalty to Business ($) | 5000                      | 35 ILL. COMP. STAT. ANN. 130/3-10 | 5000              | Money    |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 25           | LEG         | 604LEG  | 640LOC    | 60GRP            | 166         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Additional Requirements | Minimum License Fee ($)         | 75                        | 35 ILL. COMP. STAT. ANN. 130/4G   | 75                | Money    |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 20           | LEG         | 604LEG  | 640LOC    | 20GRP            | 164         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Penalties               | Minimum Penalty to Business ($) | No Minimum                | 35 ILL. COMP. STAT. ANN. 130/3-10 | 0                 | Money    |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 20           | LEG         | 604LEG  | 640LOC    | 60GRP            | 167         | 
| 2016 | 1       | IL           | Illinois     | Legislation - Licensure | Over-the-Counter | OSH        | Additional Requirements | Maximum License Fee ($)         | 75                        | 35 ILL. COMP. STAT. ANN. 130/4G   | 75                | Money    |          | 2014-08-24T00:00:00 | 2016-01-01T00:00:00 | 30           | LEG         | 604LEG  | 640LOC    | 20GRP            | 163         | 
```