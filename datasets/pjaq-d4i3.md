# OIS Dataset 2006-15 - Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ois-dataset-2006-15-incidents) |
| Metadata | [Link](https://data.austintexas.gov/api/views/pjaq-d4i3) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/pjaq-d4i3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/pjaq-d4i3/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | pjaq-d4i3 |
| Name | OIS Dataset 2006-15 - Incidents |
| Category | Public Safety |
| Tags | police, ois, shooting |
| Created | 2016-06-16T17:03:25Z |
| Publication Date | 2016-06-16T17:58:15Z |

## Description

This report reflects all officer-involved shootings that occurred from 2006 through 2015 in Austin. It includes incidents in which APD or non-APD officers fired their weapons within the city of Austin as well as incidents in which APD officers fired their weapons outside the city of Austin.
Officer-involved shootings are defined as:
? an incident in which an officer fired his/her firearm intentionally at a subject;
? an incident in which an officer fired his/her firearm unintentionally and struck a subject; or
? an incident in which an officer used a less-lethal firearm, struck the subject, and contributed to the subject?s death.

AUSTIN POLICE DEPARTMENT DATA DISCLAIMER
1. The data provided are for informational use only and may differ from official APD crime data.
2. APD?s crime database is continuously updated, so reports run at different times may produce different results.  Care should be taken when comparing against other reports as different data collection methods and different data sources may have been used.
3. The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type     | Render Type   |
| ======== | ============== | ================================= | =================================== | ============= | ============= |
| Yes      | series tag     | case                              | Case #                              | text          | text          |
| Yes      | time           | date                              | Date                                | calendar_date | calendar_date |
| No       |                | day_of_week                       | Day of Week                         | text          | text          |
| Yes      | series tag     | time                              | Time                                | text          | text          |
| Yes      | series tag     | day_part                          | Day Part                            | text          | text          |
| Yes      | series tag     | premise_category                  | Premise Category                    | text          | text          |
| Yes      | series tag     | inside_outside                    | Inside / Outside                    | text          | text          |
| Yes      | series tag     | subject_weapon                    | Subject Weapon                      | text          | text          |
| Yes      | numeric metric | number_of_officer_shooters        | Number of Officer Shooters          | number        | number        |
| Yes      | series tag     | call_type_categories              | Call Type Categories                | text          | text          |
| Yes      | numeric metric | officers_present_when_shots_fired | # Officers Present When Shots Fired | number        | number        |
| Yes      | numeric metric | hits                              | # Hits                              | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = day_of_week
```

## Data Commands

```ls
series e:pjaq-d4i3 d:2015-07-05T00:00:00.000Z t:call_type_categories="shots fired" t:time=4:54 t:subject_weapon=rifle t:inside_outside=Inside t:day_part=night t:case="15-1860826
15-5029094
15-5030656" t:premise_category=Business m:hits=10 m:number_of_officer_shooters=1 m:officers_present_when_shots_fired=3

series e:pjaq-d4i3 d:2013-07-26T00:00:00.000Z t:call_type_categories=onscene t:time=16:10 t:subject_weapon=none t:inside_outside=Outside t:day_part=Evening t:case="13-5033792
13-2071392" t:premise_category="Under Bridge" m:hits=1 m:number_of_officer_shooters=1 m:officers_present_when_shots_fired=1

series e:pjaq-d4i3 d:2012-04-05T00:00:00.000Z t:call_type_categories="traffic stop" t:time=18:40 t:subject_weapon="mic cord" t:inside_outside=Outside t:day_part=Evening t:case="12-5016942
12-0961610" t:premise_category=Yard/Courtyard m:hits=3 m:number_of_officer_shooters=1 m:officers_present_when_shots_fired=1
```

## Meta Commands

```ls
metric m:number_of_officer_shooters p:integer l:"Number of Officer Shooters" t:dataTypeName=number

metric m:officers_present_when_shots_fired p:integer l:"# Officers Present When Shots Fired" t:dataTypeName=number

metric m:hits p:integer l:"# Hits" t:dataTypeName=number

entity e:pjaq-d4i3 l:"OIS Dataset 2006-15 - Incidents" t:url=https://data.austintexas.gov/api/views/pjaq-d4i3

property e:pjaq-d4i3 t:meta.view v:id=pjaq-d4i3 v:category="Public Safety" v:averageRating=0 v:name="OIS Dataset 2006-15 - Incidents"

property e:pjaq-d4i3 t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:pjaq-d4i3 t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| case                             | date                | day_of_week | time  | day_part | premise_category | inside_outside | subject_weapon | number_of_officer_shooters | call_type_categories | officers_present_when_shots_fired | hits | 
| ================================ | =================== | =========== | ===== | ======== | ================ | ============== | ============== | ========================== | ==================== | ================================= | ==== | 
| 15-1860826 15-5029094 15-5030656 | 2015-07-05T00:00:00 | Sun         | 4:54  | night    | Business         | Inside         | rifle          | 1                          | shots fired          | 3                                 | 10   | 
| 13-5033792 13-2071392            | 2013-07-26T00:00:00 | Fri         | 16:10 | Evening  | Under Bridge     | Outside        | none           | 1                          | onscene              | 1                                 | 1    | 
| 12-5016942 12-0961610            | 2012-04-05T00:00:00 | Thur        | 18:40 | Evening  | Yard/Courtyard   | Outside        | mic cord       | 1                          | traffic stop         | 1                                 | 3    | 
| 13-5052096 13-3141499            | 2013-11-10T00:00:00 | Sun         | 21:17 | Evening  | Yard/Courtyard   | Inside         | gun            | 2                          | check welfare        | 9                                 | 1    | 
| 12-5043966 12-2691696            | 2012-09-25T00:00:00 | Tues        | 20:39 | Evening  | Parking Lot      | Outside        | gun            | 1                          | stolen vehicle       | 2                                 | 1    | 
| 13-5039952 13-2430035            | 2013-08-31T00:00:00 | Sat         | 0:13  | Night    | Parking Lot      | Outside        | vehicle        | 1                          | burglary             | 1                                 | 5    | 
| 13-5021565 13-1370254            | 2013-05-17T00:00:00 | Fri         | 3:27  | Night    | Yard/Courtyard   | Outside        | gun            | 1                          | shots fired          | 3                                 | 0    | 
| 14-3320160 14-5052475            | 2014-11-28T00:00:00 | Fri         | 2:22  | Night    | Street           | Outside        | rifle          | 1                          | shots fired          | 10                                | 1    | 
| 15-0381788 15-5005471 15-5006662 | 2015-02-08T00:00:00 | Sun         | 12:09 | night    | Yard/Courtyard   | Outside        | rifle          | 1                          | shots fired          | 26                                | 1    | 
| 15-1440098 15-5022158            | 2015-05-24T00:00:00 | Sun         | 1:14  | night    | Yard/Courtyard   | Outside        | gun            | 2                          | disturbance          | 3                                 | 3    | 
```