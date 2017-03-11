# Seattle Center Emergency Services Unit 2016 Incident Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-center-emergency-services-unit-2016-incident-report) |
| Metadata | [Link](https://data.seattle.gov/api/views/wgrr-kk3q) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/wgrr-kk3q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/wgrr-kk3q/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | wgrr-kk3q |
| Name | Seattle Center Emergency Services Unit 2016 Incident Report |
| Attribution | Seattle Center |
| Category | City Business |
| Tags | seattle center, esu, incidents |
| Created | 2017-02-01T21:34:22Z |
| Publication Date | 2017-02-01T21:40:38Z |
| Rows Updated | 2017-02-01T21:34:39Z |

## Description

This dataset provides summary tallies by day for the different types of incidents the Seattle Center Emergency Services unit responds to.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | ld_entdate                 | LD_EntDate                 | calendar_date | calendar_date |
| Yes      | numeric metric | ld_publiccontactassistance | LD_PublicContactAssistance | number        | number        |
| Yes      | numeric metric | ld_radioassist             | LD_RadioAssist             | number        | number        |
| Yes      | numeric metric | ld_keyassist               | LD_KeyAssist               | number        | number        |
| Yes      | numeric metric | ld_escort                  | LD_Escort                  | number        | number        |
| Yes      | numeric metric | ld_alarm                   | LD_Alarm                   | number        | number        |
| Yes      | numeric metric | ld_rulesviolation          | LD_RulesViolation          | number        | number        |
| Yes      | numeric metric | ld_suspiciousincident      | LD_SuspiciousIncident      | number        | number        |
| Yes      | numeric metric | ld_lostfound               | LD_LostFound               | number        | number        |
| Yes      | numeric metric | ld_alcoholdrug             | LD_AlcoholDrug             | number        | number        |
| Yes      | series tag     | ld_injuryfirstaid          | LD_InjuryFirstAid          | text          | number        |
| Yes      | numeric metric | ld_skateboardroller        | LD_SkateboardRoller        | number        | number        |
| Yes      | numeric metric | ld_keycorerequest          | LD_KeyCoreRequest          | number        | number        |
| Yes      | numeric metric | ld_parkingcit              | LD_ParkingCit              | number        | number        |
| Yes      | numeric metric | ld_autoassist              | LD_AutoAssist              | number        | number        |
| Yes      | numeric metric | ld_carprowl                | LD_CarProwl                | number        | number        |
| Yes      | numeric metric | ld_vandalismproperty       | LD_VandalismProperty       | number        | number        |
| Yes      | numeric metric | ld_sexoffense              | LD_SexOffense              | number        | number        |
| Yes      | numeric metric | ld_firearson               | LD_FireArson               | number        | number        |
| Yes      | numeric metric | ld_homicide                | LD_Homicide                | number        | number        |
| Yes      | numeric metric | ld_rape                    | LD_Rape                    | number        | number        |
| Yes      | numeric metric | ld_robbery                 | LD_Robbery                 | number        | number        |
| Yes      | numeric metric | ld_assault                 | LD_Assault                 | number        | number        |
| Yes      | numeric metric | ld_burglary                | LD_Burglary                | number        | number        |
| Yes      | numeric metric | ld_autotheft               | LD_AutoTheft               | number        | number        |
| Yes      | numeric metric | ld_theft                   | LD_Theft                   | number        | number        |
| Yes      | numeric metric | ld_lostfoundchild          | LD_LostFoundChild          | number        | number        |
| Yes      | numeric metric | ld_idbadge                 | LD_IDBadge                 | number        | number        |
| Yes      | numeric metric | ld_graffiti                | LD_Graffiti                | number        | number        |
| Yes      | numeric metric | ld_leashlaw                | LD_LeashLaw                | number        | number        |
| Yes      | numeric metric | ld_other                   | LD_Other                   | number        | number        |
| Yes      | numeric metric | ld_karesponse              | LD_KAResponse              | number        | number        |
| Yes      | numeric metric | ld_disturbance             | LD_Disturbance             | number        | number        |
| Yes      | numeric metric | ld_centerschool            | LD_CenterSchool            | number        | number        |
```

## Time Field

```ls
Value = ld_entdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:wgrr-kk3q d:2016-01-01T00:00:00.000Z t:ld_injuryfirstaid=0 m:ld_karesponse=0 m:ld_escort=0 m:ld_keyassist=0 m:ld_lostfoundchild=0 m:ld_centerschool=0 m:ld_carprowl=0 m:ld_theft=0 m:ld_leashlaw=0 m:ld_disturbance=0 m:ld_idbadge=0 m:ld_keycorerequest=0 m:ld_sexoffense=0 m:ld_vandalismproperty=0 m:ld_firearson=0 m:ld_skateboardroller=0 m:ld_autoassist=0 m:ld_alcoholdrug=0 m:ld_radioassist=0 m:ld_lostfound=0 m:ld_parkingcit=0 m:ld_graffiti=0 m:ld_homicide=0 m:ld_alarm=0 m:ld_suspiciousincident=0 m:ld_other=0 m:ld_rape=0 m:ld_assault=0 m:ld_autotheft=0 m:ld_publiccontactassistance=0 m:ld_burglary=0 m:ld_robbery=0 m:ld_rulesviolation=0

series e:wgrr-kk3q d:2016-01-01T00:00:00.000Z t:ld_injuryfirstaid=0 m:ld_karesponse=0 m:ld_escort=0 m:ld_keyassist=0 m:ld_lostfoundchild=0 m:ld_centerschool=0 m:ld_carprowl=0 m:ld_theft=0 m:ld_leashlaw=0 m:ld_disturbance=0 m:ld_idbadge=0 m:ld_keycorerequest=0 m:ld_sexoffense=0 m:ld_vandalismproperty=0 m:ld_firearson=0 m:ld_skateboardroller=0 m:ld_autoassist=0 m:ld_alcoholdrug=0 m:ld_radioassist=0 m:ld_lostfound=0 m:ld_parkingcit=0 m:ld_graffiti=0 m:ld_homicide=0 m:ld_alarm=0 m:ld_suspiciousincident=0 m:ld_other=6 m:ld_rape=0 m:ld_assault=0 m:ld_autotheft=0 m:ld_publiccontactassistance=0 m:ld_burglary=0 m:ld_robbery=0 m:ld_rulesviolation=0

series e:wgrr-kk3q d:2016-01-01T00:00:00.000Z t:ld_injuryfirstaid=0 m:ld_karesponse=0 m:ld_escort=0 m:ld_keyassist=0 m:ld_lostfoundchild=0 m:ld_centerschool=0 m:ld_carprowl=0 m:ld_theft=0 m:ld_leashlaw=0 m:ld_disturbance=0 m:ld_idbadge=0 m:ld_keycorerequest=0 m:ld_sexoffense=0 m:ld_vandalismproperty=0 m:ld_firearson=0 m:ld_skateboardroller=0 m:ld_autoassist=0 m:ld_alcoholdrug=0 m:ld_radioassist=0 m:ld_lostfound=0 m:ld_parkingcit=0 m:ld_graffiti=0 m:ld_homicide=0 m:ld_alarm=0 m:ld_suspiciousincident=0 m:ld_other=0 m:ld_rape=0 m:ld_assault=0 m:ld_autotheft=0 m:ld_publiccontactassistance=0 m:ld_burglary=0 m:ld_robbery=0 m:ld_rulesviolation=0
```

## Meta Commands

```ls
metric m:ld_publiccontactassistance p:integer l:LD_PublicContactAssistance t:dataTypeName=number

metric m:ld_radioassist p:integer l:LD_RadioAssist t:dataTypeName=number

metric m:ld_keyassist p:integer l:LD_KeyAssist t:dataTypeName=number

metric m:ld_escort p:integer l:LD_Escort t:dataTypeName=number

metric m:ld_alarm p:integer l:LD_Alarm t:dataTypeName=number

metric m:ld_rulesviolation p:integer l:LD_RulesViolation t:dataTypeName=number

metric m:ld_suspiciousincident p:integer l:LD_SuspiciousIncident t:dataTypeName=number

metric m:ld_lostfound p:integer l:LD_LostFound t:dataTypeName=number

metric m:ld_alcoholdrug p:integer l:LD_AlcoholDrug t:dataTypeName=number

metric m:ld_skateboardroller p:integer l:LD_SkateboardRoller t:dataTypeName=number

metric m:ld_keycorerequest p:integer l:LD_KeyCoreRequest t:dataTypeName=number

metric m:ld_parkingcit p:integer l:LD_ParkingCit t:dataTypeName=number

metric m:ld_autoassist p:integer l:LD_AutoAssist t:dataTypeName=number

metric m:ld_carprowl p:integer l:LD_CarProwl t:dataTypeName=number

metric m:ld_vandalismproperty p:integer l:LD_VandalismProperty t:dataTypeName=number

metric m:ld_sexoffense p:integer l:LD_SexOffense t:dataTypeName=number

metric m:ld_firearson p:integer l:LD_FireArson t:dataTypeName=number

metric m:ld_homicide p:integer l:LD_Homicide t:dataTypeName=number

metric m:ld_rape p:integer l:LD_Rape t:dataTypeName=number

metric m:ld_robbery p:integer l:LD_Robbery t:dataTypeName=number

metric m:ld_assault p:integer l:LD_Assault t:dataTypeName=number

metric m:ld_burglary p:integer l:LD_Burglary t:dataTypeName=number

metric m:ld_autotheft p:integer l:LD_AutoTheft t:dataTypeName=number

metric m:ld_theft p:integer l:LD_Theft t:dataTypeName=number

metric m:ld_lostfoundchild p:integer l:LD_LostFoundChild t:dataTypeName=number

metric m:ld_idbadge p:integer l:LD_IDBadge t:dataTypeName=number

metric m:ld_graffiti p:integer l:LD_Graffiti t:dataTypeName=number

metric m:ld_leashlaw p:integer l:LD_LeashLaw t:dataTypeName=number

metric m:ld_other p:integer l:LD_Other t:dataTypeName=number

metric m:ld_karesponse p:integer l:LD_KAResponse t:dataTypeName=number

metric m:ld_disturbance p:integer l:LD_Disturbance t:dataTypeName=number

metric m:ld_centerschool p:integer l:LD_CenterSchool t:dataTypeName=number

entity e:wgrr-kk3q l:"Seattle Center Emergency Services Unit 2016 Incident Report" t:attribution="Seattle Center" t:url=https://data.seattle.gov/api/views/wgrr-kk3q

property e:wgrr-kk3q t:meta.view v:id=wgrr-kk3q v:category="City Business" v:attributionLink=http://www.seattlecenter.com v:averageRating=0 v:name="Seattle Center Emergency Services Unit 2016 Incident Report" v:attribution="Seattle Center"

property e:wgrr-kk3q t:meta.view.license v:name="Public Domain"

property e:wgrr-kk3q t:meta.view.owner v:id=wy9h-7767 v:screenName="Wells, Denise" v:roleName=publisher v:displayName="Wells, Denise"

property e:wgrr-kk3q t:meta.view.tableauthor v:id=wy9h-7767 v:screenName="Wells, Denise" v:roleName=publisher v:displayName="Wells, Denise"
```