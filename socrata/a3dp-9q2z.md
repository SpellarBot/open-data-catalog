# SDOT Traffic Signals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-signals) |
| Metadata | [Link](https://data.seattle.gov/api/views/a3dp-9q2z) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/a3dp-9q2z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/a3dp-9q2z/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | a3dp-9q2z |
| Name | SDOT Traffic Signals |
| Attribution | Seattle Department of Transportation |
| Category | Transportation |
| Tags | traffic, signals, seattle, transportation, vision zero, sdot asset status and condition report, assets |
| Created | 2015-03-19T04:43:14Z |
| Publication Date | 2015-03-19T04:45:47Z |

## Description

Displays the location of traffic signals in the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | numeric metric | compkey                   | COMPKEY                   | number    | number      |
| Yes      | series tag     | comptype                  | COMPTYPE                  | text      | number      |
| Yes      | series tag     | unittype                  | UNITTYPE                  | text      | text        |
| Yes      | series tag     | unitid                    | UNITID                    | text      | text        |
| Yes      | numeric metric | intr_compkey              | INTR_COMPKEY              | number    | number      |
| Yes      | series tag     | intr_unitid               | INTR_UNITID               | text      | text        |
| Yes      | numeric metric | intr_distance             | INTR_DISTANCE             | number    | number      |
| Yes      | numeric metric | description               | DESCRIPTION               | number    | text        |
| Yes      | numeric metric | seg_compkey               | SEG_COMPKEY               | number    | number      |
| Yes      | series tag     | unitdesc                  | UNITDESC                  | text      | text        |
| Yes      | numeric metric | segkey                    | SEGKEY                    | number    | number      |
| Yes      | numeric metric | intkey                    | INTKEY                    | number    | number      |
| Yes      | series tag     | int_unitid                | INT_UNITID                | text      | text        |
| Yes      | series tag     | signal_type               | SIGNAL_TYPE               | text      | text        |
| Yes      | series tag     | signal_maint_dist         | SIGNAL_MAINT_DIST         | text      | text        |
| No       |                | install_date              | INSTALL_DATE              | date      | date        |
| Yes      | series tag     | addby                     | ADDBY                     | text      | text        |
| Yes      | time           | adddttm                   | ADDDTTM                   | date      | date        |
| Yes      | series tag     | modby                     | MODBY                     | text      | text        |
| No       |                | moddttm                   | MODDTTM                   | date      | date        |
| Yes      | series tag     | ownership                 | OWNERSHIP                 | text      | text        |
| Yes      | series tag     | condition                 | CONDITION                 | text      | text        |
| No       |                | condition_assessment_date | CONDITION_ASSESSMENT_DATE | date      | date        |
| Yes      | series tag     | current_status            | CURRENT_STATUS            | text      | text        |
| No       |                | current_status_date       | CURRENT_STATUS_DATE       | date      | date        |
| Yes      | numeric metric | arterial_class            | ARTERIAL_CLASS            | number    | text        |
| Yes      | series tag     | maint_agree               | MAINT_AGREE               | text      | text        |
| Yes      | series tag     | maint_by                  | MAINT_BY                  | text      | text        |
| Yes      | series tag     | int_signal_type_cd        | INT_SIGNAL_TYPE_CD        | text      | text        |
```

## Time Field

```ls
Value = adddttm
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = install_date,moddttm,condition_assessment_date,current_status_date
```

## Data Commands

```ls
series e:a3dp-9q2z d:2005-03-17T17:11:54.000Z t:int_unitid=220105 t:addby=GISADMIN t:condition=POOR t:comptype=74 t:current_status=INSVC t:modby=BACHMAR t:signal_type=SEMI t:unitdesc="15TH AVE NE AND NE 143RD ST" t:unitid=SGL-893 t:ownership=SDOT t:intr_unitid=0 t:int_signal_type_cd=CITY t:objectid=1 t:signal_maint_dist=NORTH m:intr_compkey=0 m:segkey=1 m:description=0 m:arterial_class=1 m:seg_compkey=0 m:intkey=35855 m:intr_distance=0 m:compkey=272905

series e:a3dp-9q2z d:2005-03-17T17:11:54.000Z t:int_unitid=2113 t:addby=GISADMIN t:condition=POOR t:comptype=74 t:current_status=INSVC t:modby=FORSYTB t:signal_type=PRE t:unitdesc="24TH AVE NW AND NW 80TH ST" t:unitid=SGL-241 t:ownership=SDOT t:intr_unitid=0 t:int_signal_type_cd=CITY t:objectid=2 t:signal_maint_dist=NORTH m:intr_compkey=0 m:segkey=1 m:description=0 m:arterial_class=2 m:seg_compkey=0 m:intkey=23872 m:intr_distance=0 m:compkey=272906

series e:a3dp-9q2z d:2005-03-17T17:11:54.000Z t:int_unitid=57338 t:addby=GISADMIN t:condition=FAIR t:comptype=74 t:current_status=INSVC t:modby=FORSYTB t:signal_type=SEMI t:unitdesc="15TH AVE S AND S OREGON ST" t:unitid=SGL-533 t:ownership=SDOT t:intr_unitid=0 t:int_signal_type_cd=CITY t:objectid=3 t:signal_maint_dist=SOUTH m:intr_compkey=0 m:segkey=1 m:description=0 m:arterial_class=2 m:seg_compkey=0 m:intkey=32310 m:intr_distance=0 m:compkey=272907
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:intr_compkey p:integer l:INTR_COMPKEY d:INTR_COMPKEY t:dataTypeName=number

metric m:intr_distance p:integer l:INTR_DISTANCE d:INTR_DISTANCE t:dataTypeName=number

metric m:description p:integer l:DESCRIPTION d:DESCRIPTION t:dataTypeName=number

metric m:seg_compkey p:integer l:SEG_COMPKEY d:SEG_COMPKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:intkey p:integer l:INTKEY d:INTKEY t:dataTypeName=number

metric m:arterial_class p:integer l:ARTERIAL_CLASS d:ARTERIAL_CLASS t:dataTypeName=number

entity e:a3dp-9q2z l:"SDOT Traffic Signals" t:attribution="Seattle Department of Transportation" t:url=https://data.seattle.gov/api/views/a3dp-9q2z

property e:a3dp-9q2z t:meta.view v:id=a3dp-9q2z v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Traffic Signals" v:attribution="Seattle Department of Transportation"

property e:a3dp-9q2z t:meta.view.license v:name="Public Domain"

property e:a3dp-9q2z t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:a3dp-9q2z t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | unittype | unitid   | intr_compkey | intr_unitid | intr_distance | description | seg_compkey | unitdesc                             | segkey | intkey | int_unitid | signal_type | signal_maint_dist | install_date | addby    | adddttm    | modby   | moddttm    | ownership | condition | condition_assessment_date | current_status | current_status_date | arterial_class | maint_agree | maint_by | int_signal_type_cd | 
| ======== | ======= | ======== | ======== | ======== | ============ | =========== | ============= | =========== | =========== | ==================================== | ====== | ====== | ========== | =========== | ================= | ============ | ======== | ========== | ======= | ========== | ========= | ========= | ========================= | ============== | =================== | ============== | =========== | ======== | ================== | 
| 1        | 272905  | 74       |          | SGL-893  | 0            | 0           | 0             | 0           | 0           | 15TH AVE NE AND NE 143RD ST          | 1      | 35855  | 220105     | SEMI        | NORTH             | 825552000    | GISADMIN | 1111079514 | BACHMAR | 1323095369 | SDOT      | POOR      | 1209686400                | INSVC          | 1229299200          | 1              |             |          | CITY               | 
| 2        | 272906  | 74       |          | SGL-241  | 0            | 0           | 0             | 0           | 0           | 24TH AVE NW AND NW 80TH ST           | 1      | 23872  | 2113       | PRE         | NORTH             |              | GISADMIN | 1111079514 | FORSYTB | 1405692042 | SDOT      | POOR      | 1204761600                | INSVC          | 1229299200          | 2              |             |          | CITY               | 
| 3        | 272907  | 74       |          | SGL-533  | 0            | 0           | 0             | 0           | 0           | 15TH AVE S AND S OREGON ST           | 1      | 32310  | 57338      | SEMI        | SOUTH             |              | GISADMIN | 1111079514 | FORSYTB | 1382956164 | SDOT      | FAIR      | 1382918400                | INSVC          | 1382918400          | 2              |             |          | CITY               | 
| 4        | 272908  | 74       |          | SGL-1030 | 0            | 0           | 0             | 0           | 0           | 7TH AVE AND JAMES ST                 | 1      | 29962  | 40760      | FULL        | CENTRAL           | 1233964800   | GISADMIN | 1111079514 | BACHMAR | 1335537124 | SDOT      |           |                           | INSVC          | 1248307200          | 1              |             | SDOT     | STATE              | 
| 5        | 272910  | 74       |          | SGL-425  | 0            | 0           | 0             | 0           | 0           | 28TH AVE E AND E MADISON ST          | 1      | 29253  | 37318      | SEMI        | CENTRAL           |              | GISADMIN | 1111079514 | FORSYTB | 1423640160 | SDOT      | POOR      | 1208736000                | INSVC          | 1229299200          | 2              |             |          | CITY               | 
| 6        | 272911  | 74       |          | SGL-657  | 0            | 0           | 0             | 0           | 0           | DELRIDGE WAY SW AND SW THISTLE ST    | 1      | 34843  | 76111      | SEMI        | SOUTH             |              | GISADMIN | 1111079515 | FORSYTB | 1402384699 | SDOT      | POOR      | 1209081600                | INSVC          | 1229299200          | 1              |             |          | CITY               | 
| 7        | 272912  | 74       |          | SGL-707  | 0            | 0           | 0             | 0           | 0           | 20TH AVE W AND W DRAVUS ST           | 1      | 26472  | 20321      | SEMI        | CENTRAL           | 670550400    | GISADMIN | 1111079515 | TANORIG | 1387546313 | SDOT      | POOR      | 1216252800                | INSVC          | 1229299200          | 1              |             |          | CITY               | 
| 8        | 272913  | 74       |          | SGL-42   | 0            | 0           | 0             | 0           | 0           | 2ND AVE AND CHERRY ST                | 1      | 30355  | 43114      | PRE         | DOWNTOWN          |              | GISADMIN | 1111079515 | BACHMAR | 1356698613 | SDOT      | FAIR      | 1219881600                | INSVC          | 1229299200          | 1              |             |          | CITY               | 
| 9        | 272914  | 74       |          | SGL-839  | 0            | 0           | 0             | 0           | 0           | EASTLAKE AVE E AND E GARFIELD ST     | 1      | 28332  | 30722      | SEMI        | CENTRAL           | 717292800    | GISADMIN | 1111079515 | BACHMAR | 1311334129 | SDOT      | POOR      | 1218412800                | INSVC          | 1229299200          | 1              |             |          | CITY               | 
| 10       | 272915  | 74       |          | SGL-865  | 0            | 0           | 0             | 0           | 0           | RAINIER AVE S AND S MASSACHUSETTS ST | 1      | 31517  | 52504      | SEMI        | SOUTH             | 761356800    | GISADMIN | 1111079516 | BACHMAR | 1363865762 | SDOT      | POOR      | 1217894400                | INSVC          | 1252540800          | 1              |             |          | CITY               | 
```