# SDOT Traffic Circles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-traffic-circles) |
| Metadata | [Link](https://data.seattle.gov/api/views/35iz-msg7) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/35iz-msg7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/35iz-msg7/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 35iz-msg7 |
| Name | SDOT Traffic Circles |
| Category | Transportation |
| Tags | sdot asset status and condition report, assets |
| Created | 2016-04-22T18:32:32Z |
| Publication Date | 2016-04-22T18:33:59Z |

## Description

Displays the location of traffic circles in the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | numeric metric | compkey                   | COMPKEY                   | number    | number      |
| Yes      | series tag     | comptype                  | COMPTYPE                  | text      | number      |
| Yes      | series tag     | condition                 | CONDITION                 | text      | text        |
| No       |                | condition_assessment_date | CONDITION_ASSESSMENT_DATE | date      | date        |
| Yes      | series tag     | current_status            | CURRENT_STATUS            | text      | text        |
| Yes      | time           | current_status_date       | CURRENT_STATUS_DATE       | date      | date        |
| No       |                | install_date              | INSTALL_DATE              | date      | date        |
| Yes      | series tag     | install_purpose           | INSTALL_PURPOSE           | text      | text        |
| Yes      | numeric metric | intkey                    | INTKEY                    | number    | number      |
| Yes      | series tag     | landscaping               | LANDSCAPING               | text      | text        |
| Yes      | series tag     | maintained_by             | MAINTAINED_BY             | text      | text        |
| Yes      | series tag     | maintenance_agreement     | MAINTENANCE_AGREEMENT     | text      | text        |
| Yes      | series tag     | no_land_reason            | NO_LAND_REASON            | text      | text        |
| Yes      | series tag     | overridecomment           | OVERRIDECOMMENT           | text      | text        |
| Yes      | series tag     | overrideyn                | OVERRIDEYN                | text      | text        |
| Yes      | series tag     | ownership                 | OWNERSHIP                 | text      | text        |
| No       |                | ownership_date            | OWNERSHIP_DATE            | date      | date        |
| Yes      | series tag     | primarydistrictcd         | PRIMARYDISTRICTCD         | text      | text        |
| Yes      | series tag     | sdot_initiated            | SDOT_INITIATED            | text      | text        |
| Yes      | series tag     | secondarydistrictcd       | SECONDARYDISTRICTCD       | text      | text        |
| Yes      | series tag     | sewer_access_cover        | SEWER_ACCESS_COVER        | text      | text        |
| Yes      | numeric metric | trcsize                   | TRCSIZE                   | number    | number      |
| Yes      | series tag     | survey_monument           | SURVEY_MONUMENT           | text      | text        |
| Yes      | series tag     | trcshape                  | TRCSHAPE                  | text      | text        |
| Yes      | series tag     | unitdesc                  | UNITDESC                  | text      | text        |
| Yes      | series tag     | unitid                    | UNITID                    | text      | text        |
| Yes      | series tag     | unittype                  | UNITTYPE                  | text      | text        |
```

## Time Field

```ls
Value = current_status_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = condition_assessment_date,install_date,ownership_date
```

## Data Commands

```ls
series e:35iz-msg7 d:2009-10-14T00:00:00.000Z t:condition=GOOD t:maintained_by=SDOT t:landscaping=Y t:comptype=16 t:sewer_access_cover=N t:current_status=INSVC t:unitdesc="38TH AVE SW AND SW DAKOTA ST" t:trcshape=CRC t:unitid=TRC-601 t:ownership=SDOT t:sdot_initiated=N t:survey_monument=N t:overrideyn=N t:primarydistrictcd=DISTRICT1 t:objectid=1 t:unittype=TRC m:trcsize=0 m:intkey=31889 m:compkey=509338

series e:35iz-msg7 d:2009-10-14T00:00:00.000Z t:condition=GOOD t:maintained_by=SDOT t:landscaping=Y t:comptype=16 t:sewer_access_cover=N t:current_status=INSVC t:unitdesc="8TH AVE NE AND NE 81ST ST" t:trcshape=CRC t:unitid=TRC-784 t:ownership=SDOT t:sdot_initiated=N t:survey_monument=N t:overrideyn=N t:primarydistrictcd=DISTRICT4 t:objectid=2 t:unittype=TRC m:trcsize=16 m:intkey=24389 m:compkey=508937

series e:35iz-msg7 d:2009-10-14T00:00:00.000Z t:condition=GOOD t:maintained_by=SDOT t:landscaping=Y t:comptype=16 t:sewer_access_cover=N t:current_status=INSVC t:unitdesc="25TH AVE S AND S GRAND ST" t:trcshape=OTHER t:unitid=TRC-422 t:ownership=SDOT t:sdot_initiated=N t:survey_monument=N t:overrideyn=N t:primarydistrictcd=DISTRICT3 t:objectid=3 t:unittype=TRC m:trcsize=0 m:intkey=31416 m:compkey=509329
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:intkey p:integer l:INTKEY d:INTKEY t:dataTypeName=number

metric m:trcsize p:integer l:TRCSIZE d:TRCSIZE t:dataTypeName=number

entity e:35iz-msg7 l:"SDOT Traffic Circles" t:url=https://data.seattle.gov/api/views/35iz-msg7

property e:35iz-msg7 t:meta.view v:id=35iz-msg7 v:category=Transportation v:averageRating=0 v:name="SDOT Traffic Circles"

property e:35iz-msg7 t:meta.view.license v:name="Public Domain"

property e:35iz-msg7 t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:35iz-msg7 t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | condition | condition_assessment_date | current_status | current_status_date | install_date | install_purpose | intkey | landscaping | maintained_by | maintenance_agreement | no_land_reason | overridecomment | overrideyn | ownership | ownership_date | primarydistrictcd | sdot_initiated | secondarydistrictcd | sewer_access_cover | trcsize | survey_monument | trcshape | unitdesc                      | unitid   | unittype | 
| ======== | ======= | ======== | ========= | ========================= | ============== | =================== | ============ | =============== | ====== | =========== | ============= | ===================== | ============== | =============== | ========== | ========= | ============== | ================= | ============== | =================== | ================== | ======= | =============== | ======== | ============================= | ======== | ======== | 
| 1        | 509338  | 16       | GOOD      | 1252972800                | INSVC          | 1255478400          | 958435200    |                 | 31889  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT1         | N              |                     | N                  | 0       | N               | CRC      | 38TH AVE SW AND SW DAKOTA ST  | TRC-601  | TRC      | 
| 2        | 508937  | 16       | GOOD      | 1249257600                | INSVC          | 1255478400          | 669427200    |                 | 24389  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT4         | N              |                     | N                  | 16      | N               | CRC      | 8TH AVE NE AND NE 81ST ST     | TRC-784  | TRC      | 
| 3        | 509329  | 16       | GOOD      | 1253491200                | INSVC          | 1255478400          | 1044835200   |                 | 31416  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT3         | N              |                     | N                  | 0       | N               | OTHER    | 25TH AVE S AND S GRAND ST     | TRC-422  | TRC      | 
| 4        | 509639  | 16       | GOOD      | 1252972800                | INSVC          | 1255478400          | 930614400    |                 | 37684  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT5         | N              |                     | N                  | 0       | N               | CRC      | 32ND AVE NE AND NE 86TH ST    | TRC-542  | TRC      | 
| 5        | 509211  | 16       | GOOD      | 1252886400                | INSVC          | 1255478400          | 863654400    |                 | 27904  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT7         | N              |                     | N                  | 0       | N               | CRC      | 9TH AVE W AND W HALLADAY ST   | TRC-816  | TRC      | 
| 6        | 509485  | 16       | GOOD      | 1253750400                | INSVC          | 1255478400          | 761961600    |                 | 33817  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT1         | N              |                     | N                  | 0       | N               | CRC      | 39TH AVE SW AND SW WEBSTER ST | TRC-622  | TRC      | 
| 7        | 509294  | 16       | FAIR      | 1253491200                | INSVC          | 1255478400          | 341625600    |                 | 30761  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT3         | N              |                     | N                  | 0       | N               | CRC      | 16TH AVE S AND S KING ST      | TRC-217  | TRC      | 
| 8        | 509458  | 16       | GOOD      | 1252540800                | INSVC          | 1255478400          | 799977600    |                 | 29002  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT3         | N              |                     | N                  | 0       | N               | CRC      | 10TH AVE E AND E MERCER ST    | TRC-101  | TRC      | 
| 9        | 509728  | 16       | GOOD      | 1249257600                | INSVC          | 1255478400          | 637200000    |                 | 28979  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT3         | N              |                     | N                  | 0       | N               | CRC      | HARVARD AVE E AND E ALOHA ST  | TRC-969  | TRC      | 
| 10       | 509767  | 16       | GOOD      | 1253750400                | INSVC          | 1255478400          |              |                 | 29857  | Y           | SDOT          |                       |                |                 | N          | SDOT      |                | DISTRICT3         | N              |                     | N                  | 0       | N               | CRC      | SUMMIT AVE AND E OLIVE ST     | TRC-1060 | TRC      | 
```