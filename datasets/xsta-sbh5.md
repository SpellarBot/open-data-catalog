# CDC STATE System Tobacco Legislation - Preemption

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-preemption-ba3c9) |
| Metadata | [Link](https://data.cdc.gov/api/views/xsta-sbh5) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/xsta-sbh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/xsta-sbh5/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | xsta-sbh5 |
| Name | CDC STATE System Tobacco Legislation - Preemption |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, preemption |
| Created | 2014-07-15T17:57:18Z |
| Publication Date | 2017-02-16T17:21:41Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation?Preemption. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies.  Data are reported on a quarterly basis. Data include information related to statutory state preemption of more stringent local laws on advertising, smokefree indoor air, youth access and licensure.

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
series e:xsta-sbh5 d:2009-08-07T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=630LEG t:provisiondesc="Bars - Summary Preemption" t:measureid=667PRI t:measuredesc="Preemption on Smokefree Indoor Air" t:provisiongroupdesc=Bars t:provisiongroupid=21GRP t:provisionvalue=No t:provisionid=439 t:topicdesc="Legislation - Preemption" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=1

series e:xsta-sbh5 d:2015-10-05T11:17:19.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=630LEG t:provisiondesc=Promotion t:measureid=632PRA t:measuredesc="Preemption on Advertising" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=229 t:topicdesc="Legislation - Preemption" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:xsta-sbh5 d:2009-08-07T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:citation="Gann v. City of Gulf Shores, 29 So.3d 244 (2009)." t:topicid=630LEG t:provisiondesc="Bars - Case Law Preemption" t:measureid=667PRI t:measuredesc="Preemption on Smokefree Indoor Air" t:provisiongroupdesc=Bars t:provisiongroupid=21GRP t:provisionvalue=No t:provisionid=436 t:topicdesc="Legislation - Preemption" t:datatype=Yes/No t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=1
```

## Meta Commands

```ls
metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:xsta-sbh5 l:"CDC STATE System Tobacco Legislation - Preemption" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/xsta-sbh5

property e:xsta-sbh5 t:meta.view v:id=xsta-sbh5 v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem/ v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Preemption" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:xsta-sbh5 t:meta.view.license v:name="Public Domain"

property e:xsta-sbh5 t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:xsta-sbh5 t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:xsta-sbh5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topicdesc                | measuredesc                        | datasource | provisiongroupdesc   | provisiondesc                               | provisionvalue                                                                                                                                                                                                            | citation                                          | provisionaltvalue | datatype | comments | enacted_date        | effective_date      | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============ | ======================== | ================================== | ========== | ==================== | =========================================== | ========================================================================================================================================================================================================================= | ================================================= | ================= | ======== | ======== | =================== | =================== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Smokefree Indoor Air | OSH        | Bars                 | Bars - Summary Preemption                   | No                                                                                                                                                                                                                        |                                                   | 1                 | Yes/No   |          | 2003-06-19T00:00:00 | 2009-08-07T00:00:00 | 100          | LEG         | 630LEG  | 667PRI    | 21GRP            | 439         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Advertising          | OSH        | Restrictions         | Promotion                                   | No Provision                                                                                                                                                                                                              |                                                   | 0                 | Yes/No   |          |                     |                     | 5            | LEG         | 630LEG  | 632PRA    | 10GRP            | 229         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Smokefree Indoor Air | OSH        | Bars                 | Bars - Case Law Preemption                  | No                                                                                                                                                                                                                        | Gann v. City of Gulf Shores, 29 So.3d 244 (2009). | 1                 | Yes/No   |          | 2003-06-19T00:00:00 | 2009-08-07T00:00:00 | 80           | LEG         | 630LEG  | 667PRI    | 21GRP            | 436         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Smokefree Indoor Air | OSH        | Restaurants          | Restaurants - Summary Preemption            | No                                                                                                                                                                                                                        |                                                   | 1                 | Yes/No   |          | 2003-09-01T00:00:00 | 2003-09-01T00:00:00 | 70           | LEG         | 630LEG  | 667PRI    | 24GRP            | 434         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Smokefree Indoor Air | OSH        | Private Worksites    | Private worksites - Statutory Preemption    | No                                                                                                                                                                                                                        | ALA. CODE ? 22-15A-10                             | 1                 | Yes/No   |          | 2003-09-01T00:00:00 | 2003-09-01T00:00:00 | 25           | LEG         | 630LEG  | 667PRI    | 23GRP            | 425         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Smokefree Indoor Air | OSH        | Private Worksites    | Private worksites - Case Law Preemption     | No                                                                                                                                                                                                                        | Gann v. City of Gulf Shores, 2009 WL 2415223      | 1                 | Yes/No   |          | 2003-09-01T00:00:00 | 2003-09-01T00:00:00 | 30           | LEG         | 630LEG  | 667PRI    | 23GRP            | 426         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Smokefree Indoor Air | OSH        | Government Worksites | Government worksites - Statutory Preemption | No                                                                                                                                                                                                                        | ALA. CODE ? 22-15A-10                             | 1                 | Yes/No   |          | 2003-09-01T00:00:00 | 2003-09-01T00:00:00 | 1            | LEG         | 630LEG  | 667PRI    | 22GRP            | 420         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Smokefree Indoor Air | OSH        | Restaurants          | Restaurants - Case Summary Text             | The Court of Criminal Appeals found that an ordinance banning smoking in bars was not in conflict with the Clean Indoor Air Act which exempted bars and lounges, but authorized additional forums to smoking prohibition. |                                                   | 0                 |          |          | 2003-09-01T00:00:00 | 2003-09-01T00:00:00 | 65           | LEG         | 630LEG  | 667PRI    | 24GRP            | 433         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Smokefree Indoor Air | OSH        | Private Worksites    | Private worksites - Case Summary Text       | The Court of Criminal Appeals found that an ordinance banning smoking in bars was not in conflict with the Clean Indoor Air Act which exempted bars and lounges, but authorized additional forums to smoking prohibition. |                                                   | 0                 |          |          | 2003-09-01T00:00:00 | 2003-09-01T00:00:00 | 40           | LEG         | 630LEG  | 667PRI    | 23GRP            | 428         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Preemption | Preemption on Advertising          | OSH        | Restrictions         | Other                                       | No Provision                                                                                                                                                                                                              |                                                   | 0                 | Yes/No   |          |                     |                     | 20           | LEG         | 630LEG  | 632PRA    | 10GRP            | 228         | 
```