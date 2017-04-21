# King County Flu Clinic Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-flu-clinic-schedule-2015) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fp46-im6z) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fp46-im6z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fp46-im6z/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fp46-im6z |
| Name | King County Flu Clinic Schedule |
| Tags | king county flu clinic, king county flu clinic schedule, king county flu schedule |
| Created | 2015-08-20T23:59:49Z |
| Publication Date | 2016-09-20T16:19:10Z |

## Description

Please note! Times, locations and dates are subject to change. We will keep up-to-date, but do look for signs at your worksite.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | site_name    | Site Name    | text          | text          |
| Yes      | time        | clinic_date  | Clinic Date  | calendar_date | calendar_date |
| Yes      | series tag  | clinic_hours | Clinic Hours | text          | text          |
| Yes      | series tag  | clinic_room  | Clinic Room  | text          | text          |
| Yes      | series tag  | site_contact | Site Contact | text          | text          |
```

## Time Field

```ls
Value = clinic_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fp46-im6z d:2016-09-26T00:00:00.000Z t:site_contact="Imelda Ngonevolalath
263-9338" t:clinic_hours="7 - 10 a.m." t:site_name="East Transit Base" t:clinic_room="Classrooms A & B" m:row_number.fp46-im6z=1

series e:fp46-im6z d:2016-09-28T00:00:00.000Z t:site_contact="Monique Stream, 477-7293" t:clinic_hours="6:30-10 a.m." t:site_name="Ryerson Transit Base" t:clinic_room="Classroom 203 A, 2nd floor" m:row_number.fp46-im6z=2

series e:fp46-im6z d:2016-10-13T00:00:00.000Z t:site_contact="Karen Yoshioka 477-7116" t:clinic_hours="8-10 am" t:site_name="KC Environmental Lab" t:clinic_room="EAST Large Conf. Room" m:row_number.fp46-im6z=3
```

## Meta Commands

```ls
metric m:row_number.fp46-im6z p:long l:"Row Number"

entity e:fp46-im6z l:"King County Flu Clinic Schedule" t:url=https://data.kingcounty.gov/api/views/fp46-im6z

property e:fp46-im6z t:meta.view v:id=fp46-im6z v:averageRating=0 v:name="King County Flu Clinic Schedule"

property e:fp46-im6z t:meta.view.owner v:id=niwt-u6t9 v:screenName=christimasi v:displayName=christimasi

property e:fp46-im6z t:meta.view.tableauthor v:id=niwt-u6t9 v:screenName=christimasi v:roleName=designer v:displayName=christimasi
```

## Top Records

```ls
| site_name                  | clinic_date         | clinic_hours  | clinic_room                                                   | site_contact                  | 
| ========================== | =================== | ============= | ============================================================= | ============================= | 
| East Transit Base          | 2016-09-26T00:00:00 | 7 - 10 a.m.   | Classrooms A & B                                              | Imelda Ngonevolalath 263-9338 | 
| Ryerson Transit Base       | 2016-09-28T00:00:00 | 6:30-10 a.m.  | Classroom 203 A, 2nd floor                                    | Monique Stream, 477-7293      | 
| KC Environmental Lab       | 2016-10-13T00:00:00 | 8-10 am       | EAST Large Conf. Room                                         | Karen Yoshioka 477-7116       | 
| Airport                    | 2016-10-19T00:00:00 | 10 -11 am     | Airport Terminal, Room 110                                    | Debbie Crosier 296-7436       | 
| Admin                      | 2016-09-21T00:00:00 | 9am - 3pm     | Training Room 5th Floor                                       | Greg Felton, 477-3240         | 
| South Treatment Plant      | 2016-10-06T00:00:00 | 6:30-8:30 a.m | Cedar River Training Room, 1st Floor, Administration Building | Jana Buss, 684-2447           | 
| Cedar Hills                | 2016-09-27T00:00:00 | 1-3 p.m.      | Conference Room C                                             | Annette Attianese 205-7143    | 
| West Point Treatment Plant | 2016-10-11T00:00:00 | 6-8 am        | Administration Building Conference Rooms                      | Christine Oro 263-3805        | 
| Elections                  | 2016-10-05T00:00:00 | 11 am - noon  | Alvine Conf Room                                              | Susan Southard 206-477-4277   | 
| King Street Center         | 2016-09-27T00:00:00 | 8 am - 4 pm   | 8th Floor Conference Center                                   | Chris Zanassi 477-4541        | 
```