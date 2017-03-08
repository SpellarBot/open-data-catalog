# CDC STATE System E-Cigarette Legislation - Youth Access

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/8zea-kwnt/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/cdc-state-system-e-cigarette-legislation-youth-access-69fa9)
* [Metadata URL](https://data.cdc.gov/api/views/8zea-kwnt)
* Id = 8zea-kwnt
* Name = CDC STATE System E-Cigarette Legislation - Youth Access
* Attribution = Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health
* [Attribution Link](http://www.cdc.gov/STATESystem)
* Category = Legislation
* Tags = [osh, state system, legislation, policy, youth access, e-cigarette]
* Created = 2015-05-04T14:09:53Z
* Publication Date = 2017-02-16T17:15:19Z
* Rows Updated = 2017-03-01T17:36:11Z

## Description

1995-2016. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. E-Cigarette Legislation?Youth Access. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies.  Data are reported on a quarterly basis. Data include information related to restrictions, enforcement and penalties associated with the sale of e-cigarettes to youth through retail sales and vending machines.

## Columns

```ls
| Name               | Field Name         | Data Type | Render Type | Schema Type    | Included | 
| ================== | ================== | ========= | =========== | ============== | ======== | 
| YEAR               | year               | number    | number      | time           | Yes      | 
| Quarter            | quarter            | number    | number      | numeric metric | Yes      | 
| LocationAbbr       | locationabbr       | text      | text        | series tag     | Yes      | 
| LocationDesc       | locationdesc       | text      | text        | series tag     | Yes      | 
| TopicDesc          | topicdesc          | text      | text        | series tag     | Yes      | 
| MeasureDesc        | measuredesc        | text      | text        | series tag     | Yes      | 
| DataSource         | datasource         | text      | text        | series tag     | Yes      | 
| ProvisionGroupDesc | provisiongroupdesc | text      | text        | series tag     | Yes      | 
| ProvisionDesc      | provisiondesc      | text      | text        | series tag     | Yes      | 
| ProvisionValue     | provisionvalue     | text      | text        | series tag     | Yes      | 
| Citation           | citation           | text      | text        | series tag     | Yes      | 
| ProvisionAltValue  | provisionaltvalue  | number    | number      | numeric metric | Yes      | 
| DataType           | datatype           | text      | text        | series tag     | Yes      | 
| Comments           | comments           | text      | text        | series tag     | Yes      | 
| Enacted_Date       | enacted_date       | text      | text        | series tag     | Yes      | 
| Effective_Date     | effective_date     | text      | text        | series tag     | Yes      | 
| DisplayOrder       | displayorder       | number    | text        |                | No       | 
| TopicTypeId        | topictypeid        | text      | text        | series tag     | Yes      | 
| TopicId            | topicid            | text      | text        | series tag     | Yes      | 
| MeasureId          | measureid          | text      | text        | series tag     | Yes      | 
| ProvisionGroupID   | provisiongroupid   | text      | text        | series tag     | Yes      | 
| ProvisionID        | provisionid        | text      | number      | series tag     | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = displayorder
Annotation Fields = 
```

## Data Commands

```ls
series e:8zea-kwnt d:1995-01-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:topicid=1045LEG t:provisiondesc="Restriction on Access" t:measureid=1024EVM t:measuredesc="E-Cigarette Vending Machines" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=495 t:topicdesc="Legislation - E-Cigarette - Youth Access" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0 m:quarter=4

series e:8zea-kwnt d:2006-01-01T00:00:00.000Z t:locationabbr=MT t:locationdesc=Montana t:topicid=1045LEG t:provisiondesc="Maximum Penalty ($)" t:measureid=1024EVM t:measuredesc="E-Cigarette Vending Machines" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Provision" t:provisionid=506 t:topicdesc="Legislation - E-Cigarette - Youth Access" t:datatype=Money t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0 m:quarter=4

series e:8zea-kwnt d:2008-01-01T00:00:00.000Z t:locationabbr=DC t:locationdesc="District of Columbia" t:topicid=1045LEG t:provisiondesc="Minimum Penalty ($)" t:measureid=1024EVM t:measuredesc="E-Cigarette Vending Machines" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Provision" t:provisionid=505 t:topicdesc="Legislation - E-Cigarette - Youth Access" t:datatype=Money t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0 m:quarter=1
```

## Meta Commands

```ls
metric m:quarter p:integer l:Quarter d:Quarter t:dataTypeName=number

metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:8zea-kwnt l:"CDC STATE System E-Cigarette Legislation - Youth Access" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/8zea-kwnt

property e:8zea-kwnt t:meta.view d:2017-03-08T01:45:57.299Z v:id=8zea-kwnt v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem v:averageRating=0 v:name="CDC STATE System E-Cigarette Legislation - Youth Access" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:8zea-kwnt t:meta.view.license d:2017-03-08T01:45:57.299Z v:name="Public Domain"

property e:8zea-kwnt t:meta.view.owner d:2017-03-08T01:45:57.299Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:8zea-kwnt t:meta.view.tableauthor d:2017-03-08T01:45:57.299Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:8zea-kwnt t:meta.view.metadata.custom_fields.common_core d:2017-03-08T01:45:57.299Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```