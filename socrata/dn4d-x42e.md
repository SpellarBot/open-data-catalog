# WQI Parameter Scores 1994-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wqi-parameter-scores-1994-2013-b0941) |
| Metadata | [Link](https://data.wa.gov/api/views/dn4d-x42e) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dn4d-x42e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dn4d-x42e/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dn4d-x42e |
| Name | WQI Parameter Scores 1994-2013 |
| Attribution | Markus Von Prasue, WA State Department of Ecology's River and Stream Monitoring Program |
| Tags | water quality index, 2013 river and stream water quality monitoirng data, ecology |
| Created | 2014-04-25T23:30:12Z |
| Publication Date | 2014-04-29T18:48:26Z |

## Description

Routine freshwater monitoring data collected by the The WA State Department of Ecology's River and Stream Monitoring Program are summarized by a technique called the "Water Quality Index" (WQI). The WQI ranges from 1 (poor quality) to 100 (good quality). The WQI summary does not include non-standard elements like metals. For temperature, pH, oxygen, and fecal coliform bacteria, the WQI is based on criteria in Washington?s Water Quality Standards, WAC 173-201A. For nutrient and sediment measures where standards are not specific, results are based on expected conditions in a given region. Multiple constituents are combined and results aggregated over time to produce a single score for each station and each year. All current long-term Ecology monitoring stations with at least 5 years data are included.  Most stations are located near the mouths of major streams.  These stations integrate upstream water quality and capture large basin-scale trends. However, status and trends at these locations may not reflect status or trends in any particular sub-basin. Scores for individual parameters are presented as Oxygen (Oxy) , pH, temperature (TEMP), total suspended sediment (TSS), turbidity(Turb), nitrogen(TPN), and phosphorus(TP).

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | station      | Station      | text      | text        |
| Yes      | series tag     | station_name | Station Name | text      | text        |
| Yes      | numeric metric | year         | Year         | number    | text        |
| Yes      | numeric metric | overall_wqi  | Overall WQI  | number    | number      |
| Yes      | numeric metric | wqi_fc       | WQI FC       | number    | number      |
| Yes      | numeric metric | wqi_oxy      | WQI Oxy      | number    | number      |
| Yes      | numeric metric | wqi_ph       | WQI pH       | number    | number      |
| Yes      | numeric metric | wqi_tss      | WQI TSS      | number    | number      |
| Yes      | numeric metric | wqi_temp     | WQI Temp     | number    | number      |
| Yes      | numeric metric | wqi_tpn      | WQI TPN      | number    | number      |
| Yes      | numeric metric | wqi_tp       | WQI TP       | number    | number      |
| Yes      | numeric metric | wqi_turb     | WQI Turb     | number    | number      |
```

## Time Field

```ls
Value = 1994
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dn4d-x42e d:1994-01-01T00:00:00.000Z t:station_name="Skokomish R nr Potlatch" t:station=16A070 m:overall_wqi=87 m:wqi_temp=81 m:wqi_tp=84 m:wqi_oxy=85 m:wqi_fc=91 m:year=1996 m:wqi_ph=95 m:wqi_tss=78 m:wqi_tpn=99 m:wqi_turb=69

series e:dn4d-x42e d:1994-01-01T00:00:00.000Z t:station_name="Skokomish R nr Potlatch" t:station=16A070 m:overall_wqi=86 m:wqi_temp=90 m:wqi_tp=72 m:wqi_oxy=84 m:wqi_fc=78 m:year=1997 m:wqi_ph=77 m:wqi_tss=85 m:wqi_tpn=99 m:wqi_turb=80

series e:dn4d-x42e d:1994-01-01T00:00:00.000Z t:station_name="Skokomish R nr Potlatch" t:station=16A070 m:overall_wqi=75 m:wqi_temp=90 m:wqi_tp=71 m:wqi_oxy=79 m:wqi_fc=90 m:year=1998 m:wqi_ph=88 m:wqi_tss=61 m:wqi_tpn=98 m:wqi_turb=49
```

## Meta Commands

```ls
metric m:year p:integer l:Year t:dataTypeName=number

metric m:overall_wqi p:integer l:"Overall WQI" t:dataTypeName=number

metric m:wqi_fc p:integer l:"WQI FC" t:dataTypeName=number

metric m:wqi_oxy p:integer l:"WQI Oxy" t:dataTypeName=number

metric m:wqi_ph p:integer l:"WQI pH" t:dataTypeName=number

metric m:wqi_tss p:integer l:"WQI TSS" t:dataTypeName=number

metric m:wqi_temp p:integer l:"WQI Temp" t:dataTypeName=number

metric m:wqi_tpn p:integer l:"WQI TPN" t:dataTypeName=number

metric m:wqi_tp p:integer l:"WQI TP" t:dataTypeName=number

metric m:wqi_turb p:integer l:"WQI Turb" t:dataTypeName=number

entity e:dn4d-x42e l:"WQI Parameter Scores 1994-2013" t:attribution="Markus Von Prasue, WA State Department of Ecology's River and Stream Monitoring Program" t:url=https://data.wa.gov/api/views/dn4d-x42e

property e:dn4d-x42e t:meta.view v:id=dn4d-x42e v:attributionLink=http://www.ecy.wa.gov/programs/eap/fw_riv/rv_main.html v:averageRating=0 v:name="WQI Parameter Scores 1994-2013" v:attribution="Markus Von Prasue, WA State Department of Ecology's River and Stream Monitoring Program"

property e:dn4d-x42e t:meta.view.owner v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:dn4d-x42e t:meta.view.tableauthor v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```

## Top Records

```ls
| station | station_name            | year | overall_wqi | wqi_fc | wqi_oxy | wqi_ph | wqi_tss | wqi_temp | wqi_tpn | wqi_tp | wqi_turb | 
| ======= | ======================= | ==== | =========== | ====== | ======= | ====== | ======= | ======== | ======= | ====== | ======== | 
| 16A070  | Skokomish R nr Potlatch | 1996 | 87          | 91     | 85      | 95     | 78      | 81       | 99      | 84     | 69       | 
| 16A070  | Skokomish R nr Potlatch | 1997 | 86          | 78     | 84      | 77     | 85      | 90       | 99      | 72     | 80       | 
| 16A070  | Skokomish R nr Potlatch | 1998 | 75          | 90     | 79      | 88     | 61      | 90       | 98      | 71     | 49       | 
| 16A070  | Skokomish R nr Potlatch | 1999 | 87          | 88     | 80      | 88     | 75      | 95       | 100     | 79     | 71       | 
| 16A070  | Skokomish R nr Potlatch | 2000 | 95          | 93     | 86      | 96     | 84      | 90       | 100     | 84     | 87       | 
| 16A070  | Skokomish R nr Potlatch | 2001 | 95          | 94     | 85      | 98     | 100     | 83       | 100     | 90     | 98       | 
| 16A070  | Skokomish R nr Potlatch | 2002 | 94          | 89     | 84      | 94     | 88      | 84       | 100     | 83     | 86       | 
| 16A070  | Skokomish R nr Potlatch | 2003 | 85          | 88     | 85      | 93     | 73      | 86       | 100     | 72     | 67       | 
| 16A070  | Skokomish R nr Potlatch | 2004 | 70          | 84     | 80      | 92     | 56      | 68       | 100     | 45     | 46       | 
| 16A070  | Skokomish R nr Potlatch | 2005 | 67          | 74     | 82      | 92     | 53      | 82       | 98      | 60     | 50       | 
```