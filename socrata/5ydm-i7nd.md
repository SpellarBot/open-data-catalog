# Lead Risk Assessor and Inspector Licensees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lead-risk-assessor-and-inspector-licensees) |
| Metadata | [Link](https://data.illinois.gov/api/views/5ydm-i7nd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5ydm-i7nd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5ydm-i7nd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5ydm-i7nd |
| Name | Lead Risk Assessor and Inspector Licensees |
| Attribution | IDPH - Division of Environmental Health |
| Category | Public Health |
| Tags | lead, risk assessor, inspector |
| Created | 2015-03-04T20:31:06Z |
| Publication Date | 2017-04-13T16:21:16Z |

## Description

This list contains Lead Risk Assessor and Lead Inspector licensees with their license expiration date and employer information. last updated April 2017

## Columns

```ls
| Included | Schema Type | Field Name | Name                     | Data Type     | Render Type   |
| ======== | =========== | ========== | ======================== | ============= | ============= |
| Yes      | series tag  | last       | Last Name                | text          | text          |
| Yes      | series tag  | first_mid  | First Name               | text          | text          |
| No       |             | address    | Address                  | text          | text          |
| Yes      | series tag  | homecity   | City                     | text          | text          |
| Yes      | series tag  | homestate  | State                    | text          | text          |
| Yes      | series tag  | homezip    | Zip                      | text          | text          |
| Yes      | series tag  | homecounty | County                   | text          | text          |
| Yes      | series tag  | phone      | Phone                    | text          | text          |
| No       |             | iexpire    | Inspector Expiration     | calendar_date | calendar_date |
| Yes      | time        | raexpire   | Risk Assessor Expiration | calendar_date | calendar_date |
| Yes      | series tag  | ename      | Employer Name            | text          | text          |
| No       |             | waddress   | Employer Address         | text          | text          |
| Yes      | series tag  | ecity      | Employer City            | text          | text          |
| Yes      | series tag  | estate     | Employer State           | text          | text          |
| Yes      | series tag  | ezip       | Employer Zip             | text          | text          |
| Yes      | series tag  | wphone     | Employer Phone           | text          | text          |
```

## Time Field

```ls
Value = raexpire
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,iexpire,waddress
```

## Data Commands

```ls
series e:5ydm-i7nd d:2017-04-13T16:11:09.000Z t:ezip=60607 t:homestate=IL t:ecity=Chicago t:first_mid=Sara t:last=Abramowicz t:ename="Environmental Analysis, Inc." t:wphone=3124918800 t:homecity="Burr Ridge" t:homecounty=Cook t:homezip=60527 t:estate=IL m:row_number.5ydm-i7nd=1

series e:5ydm-i7nd d:2018-01-31T00:00:00.000Z t:ezip=60612 t:homestate=IL t:ecity=Chicago t:first_mid=Steven t:last=Abramowicz t:ename="Environmental Analysis Inc" t:wphone="(312) 491-8800" t:homecity="Burr Ridge" t:homecounty=Cook t:homezip=60527 t:estate=IL m:row_number.5ydm-i7nd=2

series e:5ydm-i7nd d:2018-01-31T00:00:00.000Z t:ezip=60604 t:homestate=IL t:ecity=Chicago t:first_mid=Myron t:last=Adams t:ename="D.K. Environmental Systems" t:homecity=Chicago t:homecounty=Cook t:homezip=60604 t:estate=IL m:row_number.5ydm-i7nd=3
```

## Meta Commands

```ls
metric m:row_number.5ydm-i7nd p:long l:"Row Number"

entity e:5ydm-i7nd l:"Lead Risk Assessor and Inspector Licensees" t:attribution="IDPH - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/5ydm-i7nd

property e:5ydm-i7nd t:meta.view v:id=5ydm-i7nd v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/lead-poisoning-prevention v:averageRating=0 v:name="Lead Risk Assessor and Inspector Licensees" v:attribution="IDPH - Division of Environmental Health"

property e:5ydm-i7nd t:meta.view.license v:name="Public Domain"

property e:5ydm-i7nd t:meta.view.owner v:id=6dyi-26tm v:screenName="ken mccann" v:displayName="ken mccann"

property e:5ydm-i7nd t:meta.view.tableauthor v:id=6dyi-26tm v:screenName="ken mccann" v:roleName=publisher v:displayName="ken mccann"
```

## Top Records

```ls
| last       | first_mid   | address | homecity     | homestate | homezip | homecounty | phone | iexpire             | raexpire            | ename                                    | waddress                     | ecity         | estate | ezip  | wphone         | 
| ========== | =========== | ======= | ============ | ========= | ======= | ========== | ===== | =================== | =================== | ======================================== | ============================ | ============= | ====== | ===== | ============== | 
| Abramowicz | Sara        |         | Burr Ridge   | IL        | 60527   | Cook       |       | 2018-01-31T00:00:00 |                     | Environmental Analysis, Inc.             | 348 N Ashland Ave Ste 2C     | Chicago       | IL     | 60607 | 3124918800     | 
| Abramowicz | Steven      |         | Burr Ridge   | IL        | 60527   | Cook       |       |                     | 2018-01-31T00:00:00 | Environmental Analysis Inc               | 1612 W. Fulton St            | Chicago       | IL     | 60612 | (312) 491-8800 | 
| Adams      | Myron       |         | Chicago      | IL        | 60604   | Cook       |       |                     | 2018-01-31T00:00:00 | D.K. Environmental Systems               |                              | Chicago       | IL     | 60604 |                | 
| Adams      | Christopher |         | Macomb       | IL        | 61455   | McDonough  |       |                     | 2018-01-31T00:00:00 | McDonough County Health Department       | 505 East Jackson Street      | Macomb        | IL     | 61455 | (309)-837-9951 | 
| Adams      | Roy         |         | Carterville  | IL        | 62918   | Williamson |       |                     | 2018-01-31T00:00:00 |                                          |                              |               |        |       |                | 
| Aguilera   | Jose        |         | Chicago      | IL        | 60623   | Cook       |       |                     | 2018-01-31T00:00:00 | Environmental Design International, Inc. | 33 W. Monroe St., Ste. #1825 | Chicago       | IL     | 60603 | (312) 345-1400 | 
| Aikman     | Kevin       |         | Batavia      | IL        | 60510   | Kane       |       |                     | 2018-01-31T00:00:00 | United Analytical Services, Inc.         | 1429 Centre Circle Drive     | Downers Grove | IL     | 60515 | (630)-691-8271 | 
| Allison    | Gerald      |         | Polo         | IL        | 61064   | Ogle       |       |                     | 2018-01-31T00:00:00 | Public Health and Safety, Inc.           |                              | Chicago       | IL     | 60607 |                | 
| Alroth     | Bruce       |         | Elmwood Park | IL        | 60707   | Cook       |       |                     | 2018-01-31T00:00:00 | Carnow, Conibear & Associates, Ltd.      | 300 W. Adams, Suite 1200     | Chicago       | IL     | 60606 | 3127622904     | 
| Alvarado   | Juan        |         | Chicago      | IL        | 60607   | Cook       |       | 2018-01-31T00:00:00 |                     | GSG Consultants, Inc.                    | 855 W. Adams St., Ste. #200  | Chicago       | IL     | 60607 | (312)-733-6262 | 
```