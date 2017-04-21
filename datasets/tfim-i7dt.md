# IPTV Educational Services Outreach Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iptv-educational-services-outreach-events) |
| Metadata | [Link](https://data.iowa.gov/api/views/tfim-i7dt) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tfim-i7dt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tfim-i7dt/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tfim-i7dt |
| Name | IPTV Educational Services Outreach Events |
| Attribution | Iowa Public Television |
| Category | Education |
| Tags | school, students, teachers, learning |
| Created | 2015-12-31T20:07:31Z |
| Publication Date | 2017-03-01T23:19:41Z |

## Description

This data catalogs Iowa Public Television's Education Services Division staff engagement with Iowa teachers, students, caregivers and parents using PBS Learning Media, Classroom Connections, Ready for School or Ready to Learn materials and programming starting in July 2010 through the current month.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name              | Data Type     | Render Type   |
| ======== | ============== | =============== | ================= | ============= | ============= |
| Yes      | time           | event_date      | Event Date        | calendar_date | calendar_date |
| No       |                | event_end_date  | Event End Date    | calendar_date | calendar_date |
| Yes      | series tag     | event           | Event             | text          | text          |
| Yes      | series tag     | location        | Building          | text          | text          |
| Yes      | series tag     | city            | City              | text          | text          |
| Yes      | series tag     | zip_code        | Zip Code          | text          | text          |
| Yes      | series tag     | topic           | Topic             | text          | text          |
| Yes      | numeric metric | reached_present | # Reached Present | number        | number        |
| Yes      | numeric metric | total_reach     | # Total Reach     | number        | number        |
```

## Time Field

```ls
Value = event_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = event_end_date
```

## Data Commands

```ls
series e:tfim-i7dt d:2017-02-28T00:00:00.000Z t:topic="PBS/Tech Resources" t:zip_code=50613 t:location="AEA 267" t:event="Technology Curriculum Leaders Group" t:city="Cedar Falls" m:reached_present=11

series e:tfim-i7dt d:2017-02-27T00:00:00.000Z t:topic="Learning Media" t:zip_code=52501 t:location=GPAEA t:event="Great Prairie AEA - Curriculum Dir. meeting" t:city=Ottumwa m:reached_present=27

series e:tfim-i7dt d:2017-02-16T00:00:00.000Z t:topic=Literacy t:zip_code=52206 t:location="Atkins Elementary School" t:event="Literacy Day" t:city=Atkins m:reached_present=364
```

## Meta Commands

```ls
metric m:reached_present p:integer l:"# Reached Present" t:dataTypeName=number

metric m:total_reach p:integer l:"# Total Reach" t:dataTypeName=number

entity e:tfim-i7dt l:"IPTV Educational Services Outreach Events" t:attribution="Iowa Public Television" t:url=https://data.iowa.gov/api/views/tfim-i7dt

property e:tfim-i7dt t:meta.view v:id=tfim-i7dt v:category=Education v:attributionLink=http://iptv.org v:averageRating=0 v:name="IPTV Educational Services Outreach Events" v:attribution="Iowa Public Television"

property e:tfim-i7dt t:meta.view.owner v:id=anvk-s2q4 v:profileImageUrlMedium=/api/users/anvk-s2q4/profile_images/THUMB v:profileImageUrlLarge=/api/users/anvk-s2q4/profile_images/LARGE v:screenName="Iowa Public Television" v:profileImageUrlSmall=/api/users/anvk-s2q4/profile_images/TINY v:displayName="Iowa Public Television"

property e:tfim-i7dt t:meta.view.tableauthor v:id=anvk-s2q4 v:profileImageUrlMedium=/api/users/anvk-s2q4/profile_images/THUMB v:profileImageUrlLarge=/api/users/anvk-s2q4/profile_images/LARGE v:screenName="Iowa Public Television" v:profileImageUrlSmall=/api/users/anvk-s2q4/profile_images/TINY v:roleName=editor v:displayName="Iowa Public Television"
```

## Top Records

```ls
| event_date          | event_end_date      | event                                          | location                                         | city       | zip_code | topic                                             | reached_present | total_reach | 
| =================== | =================== | ============================================== | ================================================ | ========== | ======== | ================================================= | =============== | =========== | 
|                     |                     | Event                                          | Building                                         | City       | Zip Code | Topic                                             |                 |             | 
| 2017-07-10T00:00:00 | 2017-07-11T00:00:00 | Teaching and Learning Conference               | DMACC Ankeny Campus                              | Ankeny     | 50023    | Educational Resources                             |                 |             | 
| 2017-10-02T00:00:00 |                     | Iowa Council for Social Studies                | Prairie Meadows Conference Center                | Altoona    | 50009    | IPTV/PBS SS resources                             |                 |             | 
| 2017-06-27T00:00:00 | 2017-06-28T00:00:00 | Iowa Reading Conference                        | Scheman                                          | Ames       | 50014    |                                                   |                 |             | 
| 2017-06-19T00:00:00 | 2017-06-20T00:00:00 | Iowa Social Studies Best Practices Institute   | State Historical Building                        | Des Moines | 50322    | Iowa Pathways, PBS LM, Mission US, NewsHour Extra |                 |             | 
| 2017-06-05T00:00:00 | 2017-06-08T00:00:00 | Odd Squad Camp                                 | Storm Lake Elementary                            | Storm Lake | 50588    | Odd Squad                                         |                 |             | 
| 2017-05-11T00:00:00 |                     | Family Creative Learning Event                 | Storm Lake Public Library                        | Storm Lake | 50588    | Scratch Jr.                                       |                 |             | 
| 2017-05-08T00:00:00 |                     | National History Day in Iowa state contest     | Iowa Events Center                               | Des Moines | 50322    | Judge for National History Day state projects     |                 |             | 
| 2017-05-08T00:00:00 |                     | Family Creative Learning Event                 | Storm Lake Public Library                        | Storm Lake | 50588    | Scratch Jr.                                       |                 |             | 
| 2017-05-08T00:00:00 |                     | 2017 Student Tech Fairs - Central Fair (Judge) | Ballroom and Great Hall at Iowa State University | Ames       | 50011    | Judge for student's technology projects.          |                 |             | 
```