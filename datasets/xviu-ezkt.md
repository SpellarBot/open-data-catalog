# 911 Calls for Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calls-for-service) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/xviu-ezkt) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/xviu-ezkt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/xviu-ezkt/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | xviu-ezkt |
| Name | 911 Calls for Service |
| Attribution | Baltimore Police Department |
| Category | Public Safety |
| Tags | 911, calls for service, emergency, non-emergency |
| Created | 2015-07-13T16:04:40Z |
| Publication Date | 2016-03-14T14:23:28Z |

## Description

Emergency and Non-Emergency calls to 911

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | time        | calldatetime     | callDateTime     | calendar_date | calendar_date |
| Yes      | series tag  | priority         | priority         | text          | text          |
| Yes      | series tag  | district         | district         | text          | text          |
| Yes      | series tag  | description      | description      | text          | text          |
| Yes      | series tag  | callnumber       | callNumber       | text          | text          |
| Yes      | series tag  | incidentlocation | incidentLocation | text          | text          |
| Yes      | series tag  | location         | location         | text          | text          |
```

## Time Field

```ls
Value = calldatetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:xviu-ezkt d:2015-07-13T10:41:00.000Z t:location=(39.2899299,-76.6123462) t:description="SEE TEXT" t:priority=Medium t:callnumber=P151941002 t:incidentlocation="0 N CALVERT ST" t:district=CD m:row_number.xviu-ezkt=1

series e:xviu-ezkt d:2015-07-13T10:47:00.000Z t:location=(39.2906737,-76.6071600) t:description="911/NO  VOICE" t:priority=Medium t:callnumber=P151941003 t:incidentlocation="600 E FAYETTE ST" t:district=CD m:row_number.xviu-ezkt=2

series e:xviu-ezkt d:2015-07-13T10:42:00.000Z t:location=(39.2898910,-76.6120720) t:description="911/NO  VOICE" t:priority=Medium t:callnumber=P151941004 t:incidentlocation="200 E BALTIMORE ST" t:district=CD m:row_number.xviu-ezkt=3
```

## Meta Commands

```ls
metric m:row_number.xviu-ezkt p:long l:"Row Number"

entity e:xviu-ezkt l:"911 Calls for Service" t:attribution="Baltimore Police Department" t:url=https://data.baltimorecity.gov/api/views/xviu-ezkt

property e:xviu-ezkt t:meta.view v:id=xviu-ezkt v:category="Public Safety" v:attributionLink=https://www.baltimorepolice.org/ v:averageRating=0 v:name="911 Calls for Service" v:attribution="Baltimore Police Department"

property e:xviu-ezkt t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:xviu-ezkt t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:xviu-ezkt t:meta.view.tableauthor v:id=n22b-663u v:screenName=hchudson_bmore v:displayName=hchudson_bmore
```

## Top Records

```ls
| calldatetime        | priority | district | description      | callnumber | incidentlocation         | location                 | 
| =================== | ======== | ======== | ================ | ========== | ======================== | ======================== | 
| 2015-07-13T10:41:00 | Medium   | CD       | SEE TEXT         | P151941002 | 0 N CALVERT ST           | (39.2899299,-76.6123462) | 
| 2015-07-13T10:47:00 | Medium   | CD       | 911/NO VOICE     | P151941003 | 600 E FAYETTE ST         | (39.2906737,-76.6071600) | 
| 2015-07-13T10:42:00 | Medium   | CD       | 911/NO VOICE     | P151941004 | 200 E BALTIMORE ST       | (39.2898910,-76.6120720) | 
| 2015-07-13T10:45:00 | Low      | CD       | PRKG COMPLAINT   | P151941005 | 800 PARK AV              | (39.2985163,-76.6184754) | 
| 2015-07-13T10:46:00 | Medium   | SW       | AUTO THEFT       | P151941006 | 3500 CLIFTON AV          | (39.3112130,-76.6763150) | 
| 2015-07-13T10:47:00 | Medium   | ND       | FAMILY DISTURB   | P151941007 | 2700 N CALVERT ST        | (39.3208510,-76.6147390) | 
| 2015-07-13T10:46:00 | High     | WD       | SILENT ALARM     | P151941008 | 2100 W NORTH AV          | (39.3097096,-76.6513109) | 
| 2015-07-13T10:49:00 | Low      | SW       | AUTO ACCIDENT    | P151941010 | 3100 WILKENS AV          | (39.2756929,-76.6664179) | 
| 2015-07-13T10:48:00 | Medium   | NE       | FAMILY DISTURB   | P151941011 | 4800 GILRAY DR           | (39.3483090,-76.5768440) | 
| 2015-07-13T10:49:00 | Medium   | ND       | NARCOTICSOutside | P151941012 | W GARRISON AV/PIMLICO RD | (39.349653,-76.669145)   | 
```