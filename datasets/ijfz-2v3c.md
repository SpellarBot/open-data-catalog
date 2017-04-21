# Baltimore City Employee Salaries 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-employee-salaries-2011-8a95e) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/ijfz-2v3c) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/ijfz-2v3c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/ijfz-2v3c/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | ijfz-2v3c |
| Name | Baltimore City Employee Salaries 2011 |
| Attribution | Mayors Office |
| Category | City Government |
| Tags | salary, city employee |
| Created | 2011-06-17T22:49:08Z |
| Publication Date | 2011-06-17T22:49:08Z |

## Description

This database captures gross salary from July 1, 2010 through May 24, 2011 and includes only those employees who were employed on May 24, 2011

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | series tag     | name         | Name         | text          | text          |
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
series e:ijfz-2v3c d:1979-10-24T00:00:00.000Z t:jobtitle="Facilities/Office Services II" t:agencyid=A03031 t:name="Aaron,Patricia G" t:agency="OED-Employment Dev" m:grosspay=45505.94 m:annualsalary=50845

series e:ijfz-2v3c d:2006-09-25T00:00:00.000Z t:jobtitle="ASSISTANT STATE'S ATTORNEY" t:agencyid=A29005 t:name="Aaron,Petra L" t:agency="States Attorneys Office" m:grosspay=51588.89 m:annualsalary=56595

series e:ijfz-2v3c d:2009-07-23T00:00:00.000Z t:jobtitle=EPIDEMIOLOGIST t:agencyid=A65026 t:name="Abaineh,Yohannes T" t:agency="HLTH-Health Department" m:grosspay=50633.26 m:annualsalary=56500
```

## Meta Commands

```ls
metric m:annualsalary p:integer l:AnnualSalary d:"Annual salary is projected over the full fiscal year. Contractual, temp, part-time or summer clerks/fellows, annual salary is the equivalent full-time annual salary. Comp & leave time excluded." t:dataTypeName=money

metric m:grosspay p:double l:GrossPay d:"Gross salary includes overtime, furloughs, adjustments. Contractual, temp, part-time or summer clerks/fellows, gross reflects actual amounts paid according to terms of employment. Comp & leave time excluded." t:dataTypeName=money

entity e:ijfz-2v3c l:"Baltimore City Employee Salaries 2011" t:attribution="Mayors Office" t:url=https://data.baltimorecity.gov/api/views/ijfz-2v3c

property e:ijfz-2v3c t:meta.view v:id=ijfz-2v3c v:category="City Government" v:averageRating=0 v:name="Baltimore City Employee Salaries 2011" v:attribution="Mayors Office"

property e:ijfz-2v3c t:meta.view.owner v:id=kuy5-a8rf v:profileImageUrlMedium=/api/users/kuy5-a8rf/profile_images/THUMB v:profileImageUrlLarge=/api/users/kuy5-a8rf/profile_images/LARGE v:screenName=BmoreDevLead v:profileImageUrlSmall=/api/users/kuy5-a8rf/profile_images/TINY v:displayName=BmoreDevLead

property e:ijfz-2v3c t:meta.view.tableauthor v:id=kuy5-a8rf v:profileImageUrlMedium=/api/users/kuy5-a8rf/profile_images/THUMB v:profileImageUrlLarge=/api/users/kuy5-a8rf/profile_images/LARGE v:screenName=BmoreDevLead v:profileImageUrlSmall=/api/users/kuy5-a8rf/profile_images/TINY v:displayName=BmoreDevLead
```

## Top Records

```ls
| name                  | jobtitle                      | agencyid | agency                   | hiredate            | annualsalary | grosspay | 
| ===================== | ============================= | ======== | ======================== | =================== | ============ | ======== | 
| Aaron,Patricia G      | Facilities/Office Services II | A03031   | OED-Employment Dev       | 1979-10-24T00:00:00 | 50845        | 45505.94 | 
| Aaron,Petra L         | ASSISTANT STATE'S ATTORNEY    | A29005   | States Attorneys Office  | 2006-09-25T00:00:00 | 56595        | 51588.89 | 
| Abaineh,Yohannes T    | EPIDEMIOLOGIST                | A65026   | HLTH-Health Department   | 2009-07-23T00:00:00 | 56500        | 50633.26 | 
| Abdal-Rahim,Naim A    | EMT Firefighter               | A64063   | Fire Academy Recruits    | 2011-03-30T00:00:00 | 33476        | 3888.95  | 
| Abdi,Ezekiel W        | POLICE OFFICER                | A99398   | Police Department        | 2007-06-14T00:00:00 | 50919        | 51421.73 | 
| Abdul Hamid,Umar      | LIQUOR BOARD INSPECTOR II     | A09001   | Liquor License Board     | 1995-01-17T00:00:00 | 43278        | 39116.93 | 
| Abdul Saboor,Jamillah | OFFICE ASST II                | A75067   | Enoch Pratt Free Library | 2009-07-27T00:00:00 | 26388        | 23758.19 | 
| Abdul-Jabbar,Bushra A | SOCIAL SERVICES COORDINATOR   | A65201   | HLTH-Health Department   | 2008-04-14T00:00:00 | 38582        | 31096.45 | 
| Abdullah,Beverly A    | TYPIST III                    | A06004   | Housing & Community Dev  | 1986-12-01T00:00:00 | 34453        | 31273.03 | 
| Abdullahi,Sharon M    | 911 OPERATOR                  | A99371   | Police Department        | 2004-06-10T00:00:00 | 37677        | 36844.61 | 
```