# Fire Calls for Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-calls-for-service-3ab5b) |
| Metadata | [Link](https://data.illinois.gov/api/views/tp88-ynix) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/tp88-ynix/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/tp88-ynix/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | tp88-ynix |
| Name | Fire Calls for Service |
| Attribution | City of Rockford |
| Category | Public Safety |
| Tags | fire |
| Created | 2013-01-17T17:39:34Z |
| Publication Date | 2013-01-17T17:41:15Z |

## Description

2000 - 2012 calls for service for Rockford Fire Departmetn

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                     | Data Type | Render Type |
| ======== | ============== | ========================== | ======================== | ========= | =========== |
| Yes      | time           | year                       | Year                     | number    | number      |
| Yes      | numeric metric | fire                       | Fire                     | number    | number      |
| Yes      | numeric metric | ems_amp_search_and_rescue  | EMS & Search and Rescue  | number    | number      |
| Yes      | numeric metric | hazardous_condition        | Hazardous Condition      | number    | number      |
| Yes      | numeric metric | service_good_intent_call   | Service/Good Intent Call | number    | number      |
| Yes      | numeric metric | false_alarm_amp_false_call | False Alarm & False Call | number    | number      |
| Yes      | series tag     | other_incident_type        | Other Incident Type      | text      | number      |
| Yes      | numeric metric | total                      | Total                    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tp88-ynix d:2000-01-01T00:00:00.000Z t:other_incident_type=93 m:total=16853 m:hazardous_condition=408 m:false_alarm_amp_false_call=1427 m:service_good_intent_call=1239 m:fire=880 m:ems_amp_search_and_rescue=12806

series e:tp88-ynix d:2001-01-01T00:00:00.000Z t:other_incident_type=104 m:total=17549 m:hazardous_condition=476 m:false_alarm_amp_false_call=1341 m:service_good_intent_call=1337 m:fire=964 m:ems_amp_search_and_rescue=13327

series e:tp88-ynix d:2002-01-01T00:00:00.000Z t:other_incident_type=88 m:total=17662 m:hazardous_condition=403 m:false_alarm_amp_false_call=1365 m:service_good_intent_call=1347 m:fire=949 m:ems_amp_search_and_rescue=13510
```

## Meta Commands

```ls
metric m:fire p:integer l:Fire t:dataTypeName=number

metric m:ems_amp_search_and_rescue p:integer l:"EMS &amp; Search and Rescue" t:dataTypeName=number

metric m:hazardous_condition p:integer l:"Hazardous Condition" t:dataTypeName=number

metric m:service_good_intent_call p:integer l:"Service/Good Intent Call" t:dataTypeName=number

metric m:false_alarm_amp_false_call p:integer l:"False Alarm &amp; False Call" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:tp88-ynix l:"Fire Calls for Service" t:attribution="City of Rockford" t:url=https://data.illinois.gov/api/views/tp88-ynix

property e:tp88-ynix t:meta.view v:id=tp88-ynix v:category="Public Safety" v:averageRating=0 v:name="Fire Calls for Service" v:attribution="City of Rockford"

property e:tp88-ynix t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:tp88-ynix t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| year | fire | ems_amp_search_and_rescue | hazardous_condition | service_good_intent_call | false_alarm_amp_false_call | other_incident_type | total | 
| ==== | ==== | ========================= | =================== | ======================== | ========================== | =================== | ===== | 
| 2000 | 880  | 12806                     | 408                 | 1239                     | 1427                       | 93                  | 16853 | 
| 2001 | 964  | 13327                     | 476                 | 1337                     | 1341                       | 104                 | 17549 | 
| 2002 | 949  | 13510                     | 403                 | 1347                     | 1365                       | 88                  | 17662 | 
| 2003 | 913  | 14115                     | 595                 | 1452                     | 1293                       | 130                 | 18498 | 
| 2004 | 814  | 14631                     | 408                 | 1364                     | 1283                       | 96                  | 18596 | 
| 2005 | 796  | 15277                     | 346                 | 1488                     | 1403                       | 137                 | 19447 | 
| 2006 | 751  | 16133                     | 457                 | 1778                     | 1606                       | 215                 | 20940 | 
| 2007 | 872  | 17119                     | 760                 | 2071                     | 1897                       | 148                 | 22867 | 
| 2008 | 821  | 18232                     | 728                 | 1881                     | 1859                       | 114                 | 23635 | 
| 2009 | 815  | 18384                     | 684                 | 1827                     | 1827                       | 125                 | 23662 | 
```