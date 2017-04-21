# Baltimore City Employee Salaries FY2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-employee-salaries-fy2013-0706d) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/59xj-us3u) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/59xj-us3u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/59xj-us3u/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 59xj-us3u |
| Name | Baltimore City Employee Salaries FY2013 |
| Attribution | Mayor's Office |
| Category | City Government |
| Tags | salary, city employee |
| Created | 2013-08-26T19:42:02Z |
| Publication Date | 2014-04-04T00:26:02Z |

## Description

This database captures gross salary from July 1, 2012 through June 30, 2013 and includes only those employees who were employed on June 30, 2013

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type     | Render Type   |
| ======== | ============== | ========== | ========= | ============= | ============= |
| Yes      | series tag     | name       | NAME      | text          | text          |
| Yes      | series tag     | jobtitle   | JOBTITLE  | text          | text          |
| Yes      | series tag     | deptid     | DEPTID    | text          | text          |
| Yes      | series tag     | descr      | DESCR     | text          | text          |
| Yes      | time           | hire_dt    | HIRE_DT   | calendar_date | calendar_date |
| Yes      | numeric metric | annual_rt  | ANNUAL_RT | money         | money         |
| Yes      | numeric metric | gross      | Gross     | money         | money         |
```

## Time Field

```ls
Value = hire_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:59xj-us3u d:2013-02-04T00:00:00.000Z t:jobtitle="AUDITOR TRAINEE" t:deptid=A24002 t:name=AKROFI,BERNARD t:descr="COMP-Audits (002)" m:gross=14387.3 m:annual_rt=37407

series e:59xj-us3u d:2013-06-19T00:00:00.000Z t:jobtitle="AIDE BLUE CHIP" t:deptid=W02278 t:name="Aaron,Keairah T" t:descr="Youth Summer  (278)" m:annual_rt=11310

series e:59xj-us3u d:2013-06-10T00:00:00.000Z t:jobtitle="AIDE BLUE CHIP" t:deptid=W02200 t:name="Aaron,Keontae E" t:descr="Youth Summer  (200)" m:annual_rt=11310
```

## Meta Commands

```ls
metric m:annual_rt p:double l:ANNUAL_RT t:dataTypeName=money

metric m:gross p:double l:Gross t:dataTypeName=money

entity e:59xj-us3u l:"Baltimore City Employee Salaries FY2013" t:attribution="Mayor's Office" t:url=https://data.baltimorecity.gov/api/views/59xj-us3u

property e:59xj-us3u t:meta.view v:id=59xj-us3u v:category="City Government" v:averageRating=0 v:name="Baltimore City Employee Salaries FY2013" v:attribution="Mayor's Office"

property e:59xj-us3u t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:59xj-us3u t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:59xj-us3u t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| name                | jobtitle                      | deptid | descr                         | hire_dt             | annual_rt | gross    | 
| =================== | ============================= | ====== | ============================= | =================== | ========= | ======== | 
| AKROFI,BERNARD      | AUDITOR TRAINEE               | A24002 | COMP-Audits (002)             | 2013-02-04T00:00:00 | 37407.00  | 14387.30 | 
| Aaron,Keairah T     | AIDE BLUE CHIP                | W02278 | Youth Summer (278)            | 2013-06-19T00:00:00 | 11310.00  |          | 
| Aaron,Keontae E     | AIDE BLUE CHIP                | W02200 | Youth Summer (200)            | 2013-06-10T00:00:00 | 11310.00  |          | 
| Aaron,Patricia G    | Facilities/Office Services II | A03031 | OED-Employment Dev (031)      | 1979-10-24T00:00:00 | 51862.00  | 51771.01 | 
| Aaron,Petra L       | ASSISTANT STATE'S ATTORNEY    | A29005 | States Attorneys Office (005) | 2006-09-25T00:00:00 | 64000.00  | 63909.03 | 
| Abaineh,Yohannes T  | EPIDEMIOLOGIST                | A65026 | HLTH-Health Department (026)  | 2009-07-23T00:00:00 | 57900.00  | 57428.85 | 
| Abbey,Emmanuel      | CONTRACT SERV SPEC II         | A40001 | M-R Info Technology (001)     | 2013-05-01T00:00:00 | 52000.00  | 3477.00  | 
| Abdal-Rahim,Naim A  | EMT FIREFIGHTER               | A64120 | Fire Department (120)         | 2011-03-30T00:00:00 | 40650.00  | 44159.59 | 
| Abdi,Ezekiel W      | POLICE SERGEANT               | A99123 | Police Department (123)       | 2007-06-14T00:00:00 | 68847.00  | 66496.24 | 
| Abdul Adl,Attrice A | RADIO DISPATCHER SHERIFF      | A38410 | Sheriff's Office (410)        | 1999-09-02T00:00:00 | 41194.00  | 46254.02 | 
```