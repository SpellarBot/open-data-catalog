# CDC STATE System Tobacco Legislation - Preemption Summary

## Dataset

* [Dataset URL](https://chronicdata.cdc.gov/api/views/hj2x-85ya/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-preemption-summary)
* [Metadata URL](https://chronicdata.cdc.gov/api/views/hj2x-85ya)
* Id = hj2x-85ya
* Name = CDC STATE System Tobacco Legislation - Preemption Summary
* Attribution = Office of Smoking and Health (OSH)
* [Attribution Link](http://www.cdc.gov/tobacco/statesystem)
* Category = Legislation
* Tags = [tobacco, osh, state system, legislation, policy, preemption]
* Created = 2014-12-16T18:54:59Z
* Publication Date = 2017-02-07T18:35:59Z
* Rows Updated = 2017-02-07T18:35:35Z

## Description

1995-2016. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation?Preemption. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include information related to summary state preemption of more stringent local laws on advertising, smokefree indoor air, youth access and licensure.

## Columns

```ls
| Name                 | Field Name           | Data Type | Render Type | Schema Type    | Included | 
| ==================== | ==================== | ========= | =========== | ============== | ======== | 
| YEAR                 | year                 | number    | number      | time           | Yes      | 
| Quarter              | quarter              | number    | number      | numeric metric | Yes      | 
| LocationAbbr         | locationabbr         | text      | text        | series tag     | Yes      | 
| LocationDesc         | locationdesc         | text      | text        | series tag     | Yes      | 
| TopicTypeDesc        | topictypedesc        | text      | text        | series tag     | Yes      | 
| TopicDesc            | topicdesc            | text      | text        | series tag     | Yes      | 
| MeasureDesc          | measuredesc          | text      | text        | series tag     | Yes      | 
| Smokefree_Indoor_Air | smokefree_indoor_air | text      | text        | series tag     | Yes      | 
| Youth_Access         | youth_access         | text      | text        | series tag     | Yes      | 
| Advertising          | advertising          | text      | text        | series tag     | Yes      | 
| Licensure            | licensure            | text      | text        | series tag     | Yes      | 
| Preemption           | preemption           | text      | text        | series tag     | Yes      | 
| PreemptionAltValue   | preemptionaltvalue   | number    | number      | numeric metric | Yes      | 
| TopicTypeId          | topictypeid          | text      | text        | series tag     | Yes      | 
| TopicId              | topicid              | text      | number      | series tag     | Yes      | 
| MeasureId            | measureid            | text      | text        | series tag     | Yes      | 
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
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:hj2x-85ya d:1996-01-01T00:00:00.000Z t:locationabbr=NV t:locationdesc=Nevada t:topicid=630 t:topictypedesc=Legislation t:measureid=667COMB t:measuredesc="Smokefree Indoor Air, Youth Access, Advertising, Licensure ? OSH" t:advertising=Yes t:topicdesc=Preemption t:youth_access=Yes t:smokefree_indoor_air=Yes t:licensure=No t:preemption="Preemption for three policies" t:topictypeid=LEG m:preemptionaltvalue=3 m:quarter=4

series e:hj2x-85ya d:1997-01-01T00:00:00.000Z t:locationabbr=NV t:locationdesc=Nevada t:topicid=630 t:topictypedesc=Legislation t:measureid=667COMB t:measuredesc="Smokefree Indoor Air, Youth Access, Advertising, Licensure ? OSH" t:advertising=Yes t:topicdesc=Preemption t:youth_access=Yes t:smokefree_indoor_air=Yes t:licensure=No t:preemption="Preemption for three policies" t:topictypeid=LEG m:preemptionaltvalue=3 m:quarter=4

series e:hj2x-85ya d:1998-01-01T00:00:00.000Z t:locationabbr=NV t:locationdesc=Nevada t:topicid=630 t:topictypedesc=Legislation t:measureid=667COMB t:measuredesc="Smokefree Indoor Air, Youth Access, Advertising, Licensure ? OSH" t:advertising=Yes t:topicdesc=Preemption t:youth_access=Yes t:smokefree_indoor_air=Yes t:licensure=No t:preemption="Preemption for three policies" t:topictypeid=LEG m:preemptionaltvalue=3 m:quarter=4
```

## Meta Commands

```ls
metric m:quarter p:integer l:Quarter d:Quarter t:dataTypeName=number

metric m:preemptionaltvalue p:integer l:PreemptionAltValue d:"Alternate numeric value for non-numeric preemption value; used for mapping and graphing" t:dataTypeName=number

entity e:hj2x-85ya l:"CDC STATE System Tobacco Legislation - Preemption Summary" t:attribution="Office of Smoking and Health (OSH)" t:url=https://chronicdata.cdc.gov/api/views/hj2x-85ya

property e:hj2x-85ya t:meta.view d:2017-03-07T17:27:52.256Z v:id=hj2x-85ya v:category=Legislation v:attributionLink=http://www.cdc.gov/tobacco/statesystem v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Preemption Summary" v:attribution="Office of Smoking and Health (OSH)"

property e:hj2x-85ya t:meta.view.license d:2017-03-07T17:27:52.256Z v:name="Public Domain"

property e:hj2x-85ya t:meta.view.owner d:2017-03-07T17:27:52.256Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:hj2x-85ya t:meta.view.tableauthor d:2017-03-07T17:27:52.256Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:hj2x-85ya t:meta.view.metadata.custom_fields.common_core d:2017-03-07T17:27:52.256Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:029
```