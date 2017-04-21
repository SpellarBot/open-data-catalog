# Baltimore City Employee Salaries FY2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-employee-salaries-fy2015) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/nsfe-bg53) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/nsfe-bg53/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/nsfe-bg53/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | nsfe-bg53 |
| Name | Baltimore City Employee Salaries FY2015 |
| Attribution | Mayor's Office |
| Category | City Government |
| Tags | salaries, employees |
| Created | 2015-07-30T11:30:39Z |
| Publication Date | 2015-07-30T11:33:58Z |

## Description

This database captures gross salary from July 1, 2014 through June 30, 2015 and includes only those employees who were employed on June 30, 2015

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | series tag     | name         | name         | text          | text          |
| Yes      | series tag     | jobtitle     | JobTitle     | text          | text          |
| Yes      | series tag     | agencyid     | AgencyID     | text          | text          |
| Yes      | series tag     | agency       | Agency       | text          | text          |
| Yes      | time           | hiredate     | HireDate     | calendar_date | calendar_date |
| Yes      | numeric metric | annualsalary | AnnualSalary | money         | money         |
| Yes      | numeric metric | grosspay     | GrossPay     | money         | money         |
```

## Time Field

```ls
Value = hiredate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:nsfe-bg53 d:1979-10-24T00:00:00.000Z t:jobtitle="Facilities/Office Services II" t:agencyid=A03031 t:name="Aaron,Patricia G" t:agency="OED-Employment Dev (031)" m:grosspay=53626.04 m:annualsalary=55314

series e:nsfe-bg53 d:2006-09-25T00:00:00.000Z t:jobtitle="ASSISTANT STATE'S ATTORNEY" t:agencyid=A29045 t:name="Aaron,Petra L" t:agency="States Attorneys Office (045)" m:grosspay=73000.08 m:annualsalary=74000

series e:nsfe-bg53 d:2009-07-23T00:00:00.000Z t:jobtitle=EPIDEMIOLOGIST t:agencyid=A65026 t:name="Abaineh,Yohannes T" t:agency="HLTH-Health Department (026)" m:grosspay=64403.84 m:annualsalary=64500
```

## Meta Commands

```ls
metric m:annualsalary p:double l:AnnualSalary d:"Annual salary is projected over the full fiscal year. Contractual, temp, part-time or summer clerks/fellows, annual salary is the equivalent full-time annual salary. Comp & leave time excluded." t:dataTypeName=money

metric m:grosspay p:double l:GrossPay d:"Gross salary includes overtime, furloughs, adjustments. Contractual, temp, part-time or summer clerks/fellows, gross reflects actual amounts paid according to terms of employment. Comp & leave time excluded." t:dataTypeName=money

entity e:nsfe-bg53 l:"Baltimore City Employee Salaries FY2015" t:attribution="Mayor's Office" t:url=https://data.baltimorecity.gov/api/views/nsfe-bg53

property e:nsfe-bg53 t:meta.view v:id=nsfe-bg53 v:category="City Government" v:averageRating=0 v:name="Baltimore City Employee Salaries FY2015" v:attribution="Mayor's Office"

property e:nsfe-bg53 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:nsfe-bg53 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:nsfe-bg53 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| name                 | jobtitle                      | agencyid | agency                        | hiredate            | annualsalary | grosspay | 
| ==================== | ============================= | ======== | ============================= | =================== | ============ | ======== | 
| Aaron,Patricia G     | Facilities/Office Services II | A03031   | OED-Employment Dev (031)      | 1979-10-24T00:00:00 | 55314.00     | 53626.04 | 
| Aaron,Petra L        | ASSISTANT STATE'S ATTORNEY    | A29045   | States Attorneys Office (045) | 2006-09-25T00:00:00 | 74000.00     | 73000.08 | 
| Abaineh,Yohannes T   | EPIDEMIOLOGIST                | A65026   | HLTH-Health Department (026)  | 2009-07-23T00:00:00 | 64500.00     | 64403.84 | 
| Abbene,Anthony M     | POLICE OFFICER                | A99005   | Police Department (005)       | 2013-07-24T00:00:00 | 46309.00     | 59620.16 | 
| Abbey,Emmanuel       | CONTRACT SERV SPEC II         | A40001   | M-R Info Technology (001)     | 2013-05-01T00:00:00 | 60060.00     | 54059.60 | 
| Abbott-Cole,Michelle | CONTRACT SERV SPEC II         | A90005   | TRANS-Traffic (005)           | 2014-11-28T00:00:00 | 42702.00     | 20250.80 | 
| Abdal-Rahim,Naim A   | EMT Firefighter Suppression   | A64120   | Fire Department (120)         | 2011-03-30T00:00:00 | 62175.00     | 83757.48 | 
| Abdi,Ezekiel W       | POLICE SERGEANT               | A99127   | Police Department (127)       | 2007-06-14T00:00:00 | 77343.00     | 92574.91 | 
| Abdul Adl,Attrice A  | RADIO DISPATCHER SHERIFF      | A38410   | Sheriff's Office (410)        | 1999-09-02T00:00:00 | 44548.00     | 55943.29 | 
| Abdul Aziz,Hajr E    | LIFEGUARD I                   | P04002   | R&P-Recreation (part-time) (  | 2014-06-18T00:00:00 | 18408.00     | 1051.25  | 
```