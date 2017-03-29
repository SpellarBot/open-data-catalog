# flu-clinic-test

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/flu-clinic-test) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fqyg-zgdm) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fqyg-zgdm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fqyg-zgdm/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fqyg-zgdm |
| Name | flu-clinic-test |
| Created | 2016-08-16T19:32:26Z |
| Publication Date | 2016-08-16T19:51:01Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | site_name    | Site Name    | text          | text          |
| Yes      | time        | clinic_date  | Clinic Date  | calendar_date | calendar_date |
| Yes      | series tag  | clinic_hours | Clinic Hours | text          | text          |
| Yes      | series tag  | clinic_room  | Clinic Room  | text          | text          |
```

## Time Field

```ls
Value = clinic_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fqyg-zgdm d:2015-10-28T00:00:00.000Z t:clinic_hours="7-8  a.m." t:site_name=Brightwater t:clinic_room="""Q"" room" m:row_number.fqyg-zgdm=1

series e:fqyg-zgdm d:2015-10-15T00:00:00.000Z t:clinic_hours="11 am - noon" t:site_name=Elections t:clinic_room="Large Conf Room" m:row_number.fqyg-zgdm=2

series e:fqyg-zgdm d:2015-09-28T00:00:00.000Z t:clinic_hours="2 - 4:30 p.m." t:site_name="North Transit Base" t:clinic_room=Classrooms m:row_number.fqyg-zgdm=3
```

## Meta Commands

```ls
metric m:row_number.fqyg-zgdm p:long l:"Row Number"

entity e:fqyg-zgdm l:flu-clinic-test t:url=https://data.kingcounty.gov/api/views/fqyg-zgdm

property e:fqyg-zgdm t:meta.view v:id=fqyg-zgdm v:averageRating=0 v:name=flu-clinic-test

property e:fqyg-zgdm t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:fqyg-zgdm t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| site_name                     | clinic_date         | clinic_hours  | clinic_room                                                   | 
| ============================= | =================== | ============= | ============================================================= | 
| Brightwater                   | 2015-10-28T00:00:00 | 7-8 a.m.      | "Q" room                                                      | 
| Elections                     | 2015-10-15T00:00:00 | 11 am - noon  | Large Conf Room                                               | 
| North Transit Base            | 2015-09-28T00:00:00 | 2 - 4:30 p.m. | Classrooms                                                    | 
| Chinook                       | 2015-09-30T00:00:00 | 8am - 4pm     | Room 121/123                                                  | 
| South Treatment Plant         | 2015-10-21T00:00:00 | 6 - 8:30 a.m  | Cedar River Training Room, 1st Floor, Administration Building | 
| KC Environmental Lab          | 2015-10-27T00:00:00 | 8-10 am       | EAST Large Conf. Room                                         | 
| Renton Roads                  | 2015-10-08T00:00:00 | 6:30am- 10 am | Building C, Gabion Room                                       | 
| Atlantic/Central Transit Base | 2015-10-20T00:00:00 | 6-10 a.m.     | 2nd Floor Class Room                                          | 
| King Street Center            | 2015-10-06T00:00:00 | 8 am - 4 pm   | 8th Floor Conference Center                                   | 
| Regional Justice Center       | 2015-10-01T00:00:00 | 9:30am - 2 pm | Community Room                                                | 
```