# OMD Employees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/omd-employees) |
| Metadata | [Link](https://data.oregon.gov/api/views/p65y-ar9u) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/p65y-ar9u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/p65y-ar9u/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | p65y-ar9u |
| Name | OMD Employees |
| Attribution | Oregon Military Department |
| Category | Administrative |
| Tags | directory |
| Created | 2016-08-11T17:51:32Z |
| Publication Date | 2016-08-31T17:21:21Z |

## Description

List of employees and associated meta data that will be used to generate agency, department, office, and section directories.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | firstname      | FirstName      | text          | text          |
| Yes      | series tag  | lastname       | LastName       | text          | text          |
| Yes      | series tag  | description    | Description    | text          | text          |
| Yes      | series tag  | emailaddress   | EmailAddress   | text          | text          |
| Yes      | series tag  | department     | Department     | text          | text          |
| Yes      | series tag  | company        | Company        | text          | text          |
| Yes      | series tag  | pobox          | POBox          | text          | text          |
| Yes      | series tag  | phonenumber    | PhoneNumber    | text          | text          |
| Yes      | series tag  | city           | City           | text          | text          |
| Yes      | series tag  | ismanager      | ismanager      | text          | text          |
| Yes      | time        | lastupdatedate | LastUpdateDate | calendar_date | calendar_date |
```

## Time Field

```ls
Value = lastupdatedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:p65y-ar9u d:2017-01-11T09:20:00.000Z t:phonenumber=5413179623x247 t:emailaddress=jcalice@state.or.us t:department=YCP t:description=ISS5 t:company="Oregon Military Department" t:lastname=Calice t:ismanager=no t:firstname=James m:row_number.p65y-ar9u=1

series e:p65y-ar9u d:2017-01-11T09:20:00.000Z t:phonenumber=503-584-3567 t:emailaddress=rbaugh@state.or.us t:department=AGI t:company="Oregon Military Department" t:lastname=Baugh t:ismanager=no t:firstname=Robert m:row_number.p65y-ar9u=2

series e:p65y-ar9u d:2017-01-11T09:20:00.000Z t:phonenumber=503-584-3595 t:emailaddress=bruce.davidson@state.or.us t:department=AGI-IT t:company="Oregon Military Department" t:lastname=Davidson t:ismanager=no t:firstname=Bruce m:row_number.p65y-ar9u=3
```

## Meta Commands

```ls
metric m:row_number.p65y-ar9u p:long l:"Row Number"

entity e:p65y-ar9u l:"OMD Employees" t:attribution="Oregon Military Department" t:url=https://data.oregon.gov/api/views/p65y-ar9u

property e:p65y-ar9u t:meta.view v:id=p65y-ar9u v:category=Administrative v:averageRating=0 v:name="OMD Employees" v:attribution="Oregon Military Department"

property e:p65y-ar9u t:meta.view.owner v:id=8s57-cjqm v:profileImageUrlMedium=/api/users/8s57-cjqm/profile_images/THUMB v:profileImageUrlLarge=/api/users/8s57-cjqm/profile_images/LARGE v:screenName="Joseph Cunningham" v:profileImageUrlSmall=/api/users/8s57-cjqm/profile_images/TINY v:displayName="Joseph Cunningham"

property e:p65y-ar9u t:meta.view.tableauthor v:id=8s57-cjqm v:profileImageUrlMedium=/api/users/8s57-cjqm/profile_images/THUMB v:profileImageUrlLarge=/api/users/8s57-cjqm/profile_images/LARGE v:screenName="Joseph Cunningham" v:profileImageUrlSmall=/api/users/8s57-cjqm/profile_images/TINY v:roleName=editor v:displayName="Joseph Cunningham"
```

## Top Records

```ls
| firstname | lastname       | description           | emailaddress                       | department | company                    | pobox        | phonenumber    | city  | ismanager | lastupdatedate      | 
| ========= | ============== | ===================== | ================================== | ========== | ========================== | ============ | ============== | ===== | ========= | =================== | 
| James     | Calice         | ISS5                  | jcalice@state.or.us                | YCP        | Oregon Military Department |              | 5413179623x247 |       | no        | 2017-01-11T09:20:00 | 
| Robert    | Baugh          |                       | rbaugh@state.or.us                 | AGI        | Oregon Military Department |              | 503-584-3567   |       | no        | 2017-01-11T09:20:00 | 
| Bruce     | Davidson       |                       | bruce.davidson@state.or.us         | AGI-IT     | Oregon Military Department |              | 503-584-3595   |       | no        | 2017-01-11T09:20:00 | 
| Micah     | Norene         |                       | Micah.Norene@state.or.us           | AGI-IT     | Oregon Military Department |              | 503-584-3567   |       | no        | 2017-01-11T09:20:00 | 
| Bryce     | Dohrman        | Controller            | Bryce.E.Dohrman@state.or.us        | AGC        | Oregon Military Department | PO Box 14350 | (503) 584-3874 | Salem | no        | 2017-01-11T09:20:00 | 
| Deborah   | Anderson       | Accounting Technician | Deborah.P.Anderson@state.or.us     | AGC        | Oregon Military Department | PO Box 14350 | (503) 584-3933 | Salem | no        | 2017-01-11T09:20:00 | 
| Sean      | McCormick      | Comptroller           | Sean.M.McCormick@state.or.us       | AGC        | Oregon Military Department |              | (503) 584-3875 | Salem | yes       | 2017-01-11T09:20:00 | 
| Vicki     | Neuenschwander | Accountant 3          | Vicki.L.Neuenschwander@state.or.us | AGC        | Oregon Military Department |              | (503) 584-3501 | Salem | no        | 2017-01-11T09:20:00 | 
| Susan     | Oliveira       | Accountant 3          | Susan.L.Oliveira@state.or.us       | AGC        | Oregon Military Department | PO Box 14350 | (503) 584-3878 | Salem | no        | 2017-01-11T09:20:00 | 
| Deborah   | Stratman       | Assistant Comptroller | Deborah.P.Stratman@state.or.us     | AGC        | Oregon Military Department | PO Box 14350 | (503) 584-3873 | Salem | no        | 2017-01-11T09:20:00 | 
```