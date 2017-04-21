# SSMMA Police Calls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-police-calls-d218d) |
| Metadata | [Link](https://data.illinois.gov/api/views/9rx9-mrti) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9rx9-mrti/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9rx9-mrti/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9rx9-mrti |
| Name | SSMMA Police Calls |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | emergency response, police |
| Created | 2012-11-27T21:01:55Z |
| Publication Date | 2012-11-27T21:03:02Z |

## Description

This dataset aggregates Police Calls for Service from communities who wish to make the data publicly accessible

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| No       |             | x               | X               | number        | number        |
| No       |             | y               | Y               | number        | number        |
| Yes      | series tag  | arc_addres      | ARC_Addres      | text          | text          |
| Yes      | series tag  | arc_city        | ARC_City        | text          | text          |
| Yes      | series tag  | incident_i      | Incident_I      | text          | text          |
| Yes      | time        | incident_d      | Incident_D      | calendar_date | calendar_date |
| Yes      | series tag  | ucr_type        | UCR_Type        | text          | text          |
| Yes      | series tag  | municipality    | Municipality    | text          | text          |
| Yes      | series tag  | premise_na      | Premise_Na      | text          | text          |
| Yes      | series tag  | incident_number | Incident_Number | text          | text          |
| No       |             | date_and_time   | Date_and_Time   | text          | text          |
| Yes      | series tag  | location_1      | Location 1      | text          | text          |
| No       |             | location_2      | Location 2      | text          | text          |
```

## Time Field

```ls
Value = incident_d
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = x,y,date_and_time,location_2
```

## Data Commands

```ls
series e:9rx9-mrti d:2012-01-17T00:00:00.000Z t:arc_addres="22363 Governors Hwy" t:incident_i=RP:P12-00393 t:ucr_type="1310 : Criminal Damage To Property" t:arc_city="Richton Park" t:premise_na="CUDDLE TIME DAY CARE" t:municipality="Richton Park" t:location_1="22363 Governors Hwy
Illinois" m:row_number.9rx9-mrti=1

series e:9rx9-mrti d:2012-01-31T00:00:00.000Z t:arc_addres="22315  Governors Hwy" t:incident_i=RP:P12-00760 t:ucr_type="0810 : Theft Under $500" t:arc_city="Richton Park" t:premise_na="INSTANT TAX-FOR EYAK" t:municipality="Richton Park" t:location_1="22315 Governors Hwy
Illinois" m:row_number.9rx9-mrti=2

series e:9rx9-mrti d:2012-02-29T00:00:00.000Z t:arc_addres="22315  Governors Hwy" t:incident_i=RP:P12-01526 t:ucr_type="1130 : Fraud" t:arc_city="Richton Park" t:premise_na="INSTANT TAX SERVICE" t:municipality="Richton Park" t:location_1="22315 Governors Hwy
Illinois" m:row_number.9rx9-mrti=3
```

## Meta Commands

```ls
metric m:row_number.9rx9-mrti p:long l:"Row Number"

entity e:9rx9-mrti l:"SSMMA Police Calls" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/9rx9-mrti

property e:9rx9-mrti t:meta.view v:id=9rx9-mrti v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Police Calls" v:attribution="South Suburban Mayors and Managers Association"

property e:9rx9-mrti t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:9rx9-mrti t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:9rx9-mrti t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| x                   | y                  | arc_addres          | arc_city     | incident_i   | incident_d          | ucr_type                           | municipality | premise_na           | incident_number | date_and_time | location_1                   | location_2                                        | 
| =================== | ================== | =================== | ============ | ============ | =================== | ================================== | ============ | ==================== | =============== | ============= | ============================ | ================================================= | 
| -87.712867000000003 | 41.482968          | 22363 Governors Hwy | Richton Park | RP:P12-00393 | 2012-01-17T00:00:00 | 1310 : Criminal Damage To Property | Richton Park | CUDDLE TIME DAY CARE |                 |               | 22363 Governors Hwy Illinois | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712867000000003 | 41.483758999999999 | 22315 Governors Hwy | Richton Park | RP:P12-00760 | 2012-01-31T00:00:00 | 0810 : Theft Under $500            | Richton Park | INSTANT TAX-FOR EYAK |                 |               | 22315 Governors Hwy Illinois | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712867000000003 | 41.483758999999999 | 22315 Governors Hwy | Richton Park | RP:P12-01526 | 2012-02-29T00:00:00 | 1130 : Fraud                       | Richton Park | INSTANT TAX SERVICE  |                 |               | 22315 Governors Hwy Illinois | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712867000000003 | 41.483758999999999 | 22315 Governors Hwy | Richton Park | RP:P12-02368 | 2012-03-27T00:00:00 | 1130 : Fraud                       | Richton Park | INSTANT TAX SERVICE  |                 |               | 22315 Governors Hwy Illinois | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712867000000003 | 41.483758999999999 | 22315 Governors Hwy | Richton Park | RP:P12-02370 | 2012-03-27T00:00:00 | 1130 : Fraud                       | Richton Park | INSTANT TAX SERVICE  |                 |               | 22315 Governors Hwy Illinois | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712252000000007 | 41.484293000000001 | 3941 Sauk Trl       | Richton Park | RP:P12-04266 | 2012-05-24T00:00:00 | 0820 : Theft Over $500             | Richton Park | ATHENS KING OF GYROS |                 |               | 3941 Sauk Trl Illinois       | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712252000000007 | 41.484293000000001 | 3941 Sauk Trail     | Richton Park | RP:P12-04982 | 2012-06-12T00:00:00 | 1310 : Criminal Damage To Property | Richton Park | ATHENS KING OF GYROS |                 |               | 3941 Sauk Trail Illinois     | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712867000000003 | 41.482968          | 22363 Governors Hwy | Richton Park | RP:P12-00393 | 2012-01-17T00:00:00 | 1310 : Criminal Damage To Property | Richton Park | CUDDLE TIME DAY CARE |                 |               | 22363 Governors Hwy Illinois | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712867000000003 | 41.483758999999999 | 22315 Governors Hwy | Richton Park | RP:P12-00760 | 2012-01-31T00:00:00 | 0810 : Theft Under $500            | Richton Park | INSTANT TAX-FOR EYAK |                 |               | 22315 Governors Hwy Illinois | Illinois (40.485010000411364, -88.99770999971656) | 
| -87.712867000000003 | 41.483758999999999 | 22315 Governors Hwy | Richton Park | RP:P12-01526 | 2012-02-29T00:00:00 | 1130 : Fraud                       | Richton Park | INSTANT TAX SERVICE  |                 |               | 22315 Governors Hwy Illinois | Illinois (40.485010000411364, -88.99770999971656) | 
```