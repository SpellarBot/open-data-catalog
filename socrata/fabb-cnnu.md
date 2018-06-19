# Baton Rouge Crime Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baton-rouge-crime-incidents) |
| Metadata | [Link](https://data.brla.gov/api/views/fabb-cnnu) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/fabb-cnnu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/fabb-cnnu/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | fabb-cnnu |
| Name | Baton Rouge Crime Incidents |
| Attribution | Baton Rouge Police Department |
| Category | Public Safety |
| Tags | police, crime, brpd |
| Created | 2015-01-26T20:29:13Z |
| Publication Date | 2015-09-17T01:58:19Z |

## Description

Crimes reported in Baton Rouge and handled by the Baton Rouge Police Department. Crimes include Burglaries (Vehicle, Residential and Non-residential), Robberies (Individual and Business), Theft, Narcotics, Vice Crimes, Assault, Nuisance, Battery, Firearm, Homicides, Criminal Damage to Property, Sexual Assaults and Juvenile.   In order to protect the privacy of sexual assault victims and juvenile victims, these incidents are not geocoded and will not be mapped. 

Please see the disclaimer in the Attachments section of the About page.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | file_number       | FILE NUMBER       | text          | number        |
| No       |             | offense_date      | OFFENSE DATE      | calendar_date | calendar_date |
| No       |             | offense_time      | OFFENSE TIME      | text          | text          |
| Yes      | series tag  | crime             | CRIME             | text          | text          |
| Yes      | series tag  | a_c               | COMMITTED         | text          | text          |
| Yes      | series tag  | offense           | OFFENSE           | text          | text          |
| Yes      | series tag  | offense_desc      | OFFENSE DESC      | text          | text          |
| No       |             | address           | ADDRESS           | text          | text          |
| Yes      | series tag  | st_number         | ST NUMBER         | text          | number        |
| Yes      | series tag  | st_dir            | ST DIR            | text          | text          |
| Yes      | series tag  | st_name           | ST NAME           | text          | text          |
| Yes      | series tag  | st_type           | ST TYPE           | text          | text          |
| Yes      | series tag  | city              | CITY              | text          | text          |
| Yes      | series tag  | state             | STATE             | text          | text          |
| Yes      | series tag  | zip               | ZIP               | text          | text          |
| Yes      | series tag  | district          | DISTRICT          | text          | text          |
| Yes      | series tag  | zone              | ZONE              | text          | text          |
| Yes      | series tag  | subzone           | SUBZONE           | text          | text          |
| Yes      | series tag  | complete_district | COMPLETE DISTRICT | text          | text          |
```

## Time Field

```ls
Value = offense_date-offense_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss-HHmm
```

## Series Fields

```ls
Excluded Fields = address,offense_time,offense_date
```

## Data Commands

```ls
series e:fabb-cnnu d:2011-12-09T14:50:00.000Z t:a_c=COMMITTED t:subzone=2 t:file_number=1100128240 t:st_number=7234 t:state=LA t:st_name=AIRLINE t:city="BATON ROUGE" t:complete_district=1F2 t:offense_desc="UNAU USE OF MOTOR VEHICLE" t:crime=THEFT t:st_type=HW t:district=1 t:offense=14:68.4 t:zone=F m:row_number.fabb-cnnu=1

series e:fabb-cnnu d:2014-04-23T12:00:00.000Z t:a_c=COMMITTED t:subzone=1 t:file_number=1400033343 t:st_number=5900 t:state=LA t:st_name=PEERLESS t:city="BATON ROUGE" t:complete_district=4D1 t:offense_desc=BATT/SIMPLE/CC t:crime=BATTERY t:st_type=ST t:district=4 t:offense=13:35 t:zone=D m:row_number.fabb-cnnu=2

series e:fabb-cnnu d:2012-07-01T14:00:00.000Z t:zip=70815 t:a_c=COMMITTED t:subzone=3 t:file_number=1200069358 t:st_number=10250 t:state=LA t:st_name="PLAZA AMERICANA" t:city="BATON ROUGE" t:complete_district=3C3 t:offense_desc=THEFT/MISD/CC t:crime=THEFT t:st_type=DR t:district=3 t:offense=13:67 t:zone=C m:row_number.fabb-cnnu=3
```

## Meta Commands

```ls
metric m:row_number.fabb-cnnu p:long l:"Row Number"

entity e:fabb-cnnu l:"Baton Rouge Crime Incidents" t:attribution="Baton Rouge Police Department" t:url=https://data.brla.gov/api/views/fabb-cnnu

property e:fabb-cnnu t:meta.view v:id=fabb-cnnu v:category="Public Safety" v:attributionLink=http://brgov.com/dept/brpd v:averageRating=0 v:name="Baton Rouge Crime Incidents" v:attribution="Baton Rouge Police Department"

property e:fabb-cnnu t:meta.view.license v:name="Public Domain"

property e:fabb-cnnu t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:fabb-cnnu t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| file_number | offense_date        | offense_time | crime                       | a_c       | offense  | offense_desc               | address                   | st_number | st_dir | st_name         | st_type | city        | state | zip   | district | zone | subzone | complete_district | 
| =========== | =================== | ============ | =========================== | ========= | ======== | ========================== | ========================= | ========= | ====== | =============== | ======= | =========== | ===== | ===== | ======== | ==== | ======= | ================= | 
| 1100128240  | 2011-12-09T00:00:00 | 1450         | THEFT                       | COMMITTED | 14:68.4  | UNAU USE OF MOTOR VEHICLE  | 7234 AIRLINE HW           | 7234      |        | AIRLINE         | HW      | BATON ROUGE | LA    |       | 1        | F    | 2       | 1F2               | 
| 1400033343  | 2014-04-23T00:00:00 | 1200         | BATTERY                     | COMMITTED | 13:35    | BATT/SIMPLE/CC             | 5900 PEERLESS ST          | 5900      |        | PEERLESS        | ST      | BATON ROUGE | LA    |       | 4        | D    | 1       | 4D1               | 
| 1200069358  | 2012-07-01T00:00:00 | 1400         | THEFT                       | COMMITTED | 13:67    | THEFT/MISD/CC              | 10250 PLAZA AMERICANA DR  | 10250     |        | PLAZA AMERICANA | DR      | BATON ROUGE | LA    | 70815 | 3        | C    | 3       | 3C3               | 
| 1400004385  | 2014-01-16T00:00:00 | 1215         | BATTERY                     | COMMITTED | 13:35    | BATT/SIMPLE/CC             | 964 N 48TH                | 964       | N      | 48TH            |         | BATON ROUGE | LA    | 70802 |          |      |         |                   | 
| 1600115877  | 2016-11-21T00:00:00 | 0930         | CRIMINAL DAMAGE TO PROPERTY | COMMITTED | 14:56    | CRIM DAM TO PROP/SIMPLE    | 5950 ST GERARD AV         | 5950      |        | ST GERARD       | AV      | BATON ROUGE | LA    | 70805 | 4        | F    | 2       | 4F2               | 
| 1600076910  | 2016-08-01T00:00:00 | 1345         | BATTERY                     | COMMITTED | 13:35    | BATT/SIMPLE/CC             | 11111 COURSEY BL          | 11111     |        | COURSEY         | BL      | BATON ROUGE | LA    | 70816 | 3        | C    | 3       | 3C3               | 
| 1100008268  | 2011-01-25T00:00:00 | 1203         | THEFT                       | COMMITTED | 14:72.2  | MONETARY INSTRUMENT ABUSE  | 3121 S SHERWOOD FOREST BL | 3121      | S      | SHERWOOD FOREST | BL      | BATON ROUGE | LA    |       | 3        | F    | 2       | 3F2               | 
| 1600037073  | 2016-04-14T00:00:00 | 1418         | THEFT                       | COMMITTED | 13:67    | THEFT/MISD/CC              | 2520 PLANK RD             | 2520      |        | PLANK           | RD      | BATON ROUGE | LA    | 70805 | 1        | B    | 2       | 1B2               | 
| 1200107899  | 2012-10-15T00:00:00 | 0900         | THEFT                       | COMMITTED | 13:67    | THEFT/MISD/CC              | 4414 TUPELLO ST           | 4414      |        | TUPELLO         | ST      | BATON ROUGE | LA    | 70808 | 2        | D    | 3       | 2D3               | 
| 1400066360  | 2014-07-31T00:00:00 | 2158         | INDIVIDUAL ROBBERY          | COMMITTED | 14:64/AG | ROBB/FIREARM MISCELLANEOUS | 12289 FLORIDA BL          | 12289     |        | FLORIDA         | BL      | BATON ROUGE | LA    | 70815 | 3        | D    | 2       | 3D2               | 
```