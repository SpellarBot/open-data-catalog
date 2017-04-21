# Baltimore City Employee Salaries FY2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-employee-salaries-fy2012-36e83) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/7ymi-bvp3) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/7ymi-bvp3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/7ymi-bvp3/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 7ymi-bvp3 |
| Name | Baltimore City Employee Salaries FY2012 |
| Attribution | Mayor's Office |
| Category | City Government |
| Tags | salary, city employee |
| Created | 2012-08-08T14:36:27Z |
| Publication Date | 2014-03-27T23:42:50Z |

## Description

This database captures gross salary from July 1, 2011 through June 30, 2012 and includes only those employees who were employed on June 30, 2012

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
series e:7ymi-bvp3 d:1979-10-24T00:00:00.000Z t:jobtitle="Facilities/Office Services II" t:agencyid=A03031 t:name="Aaron,Patricia G" t:agency="OED-Employment Dev" m:grosspay=52247.39 m:annualsalary=51862

series e:7ymi-bvp3 d:2006-09-25T00:00:00.000Z t:jobtitle="ASSISTANT STATE'S ATTORNEY" t:agencyid=A29005 t:name="Aaron,Petra L" t:agency="States Attorneys Office" m:grosspay=59026.81 m:annualsalary=64000

series e:7ymi-bvp3 d:2009-07-23T00:00:00.000Z t:jobtitle=EPIDEMIOLOGIST t:agencyid=A65026 t:name="Abaineh,Yohannes T" t:agency="HLTH-Health Department" m:grosspay=57129.79 m:annualsalary=57900
```

## Meta Commands

```ls
metric m:annualsalary p:integer l:AnnualSalary d:"Annual salary is projected over the full fiscal year. Contractual, temp, part-time or summer clerks/fellows, annual salary is the equivalent full-time annual salary. Comp & leave time excluded." t:dataTypeName=money

metric m:grosspay p:double l:GrossPay d:"Gross salary includes overtime, furloughs, adjustments. Contractual, temp, part-time or summer clerks/fellows, gross reflects actual amounts paid according to terms of employment. Comp & leave time excluded." t:dataTypeName=money

entity e:7ymi-bvp3 l:"Baltimore City Employee Salaries FY2012" t:attribution="Mayor's Office" t:url=https://data.baltimorecity.gov/api/views/7ymi-bvp3

property e:7ymi-bvp3 t:meta.view v:id=7ymi-bvp3 v:category="City Government" v:averageRating=0 v:name="Baltimore City Employee Salaries FY2012" v:attribution="Mayor's Office"

property e:7ymi-bvp3 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:7ymi-bvp3 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:7ymi-bvp3 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| name                  | jobtitle                      | agencyid | agency                   | hiredate            | annualsalary | grosspay | 
| ===================== | ============================= | ======== | ======================== | =================== | ============ | ======== | 
| Aaron,Patricia G      | Facilities/Office Services II | A03031   | OED-Employment Dev       | 1979-10-24T00:00:00 | 51862        | 52247.39 | 
| Aaron,Petra L         | ASSISTANT STATE'S ATTORNEY    | A29005   | States Attorneys Office  | 2006-09-25T00:00:00 | 64000        | 59026.81 | 
| Abaineh,Yohannes T    | EPIDEMIOLOGIST                | A65026   | HLTH-Health Department   | 2009-07-23T00:00:00 | 57900        | 57129.79 | 
| Abdal-Rahim,Naim A    | EMT FIREFIGHTER               | A64215   | Fire Department          | 2011-03-30T00:00:00 | 34146        | 35537.88 | 
| Abdi,Ezekiel W        | POLICE OFFICER                | A99398   | Police Department        | 2007-06-14T00:00:00 | 58244        | 62669.25 | 
| Abdul Adl,Attrice A   | RADIO DISPATCHER SHERIFF      | A38410   | Sheriff's Office         | 1999-09-02T00:00:00 | 41194        | 46699.58 | 
| Abdul Hamid,Umar      | LIQUOR BOARD INSPECTOR II     | A09001   | Liquor License Board     | 1995-01-17T00:00:00 | 44143        | 44637.76 | 
| Abdul Saboor,Jamillah | SECRETARY II                  | A75054   | Enoch Pratt Free Library | 2009-07-27T00:00:00 | 31741        | 29474.61 | 
| Abdul Wali,Tasneem K  | AIDE BLUE CHIP                | W02129   | Youth Summer             | 2008-06-21T00:00:00 | 11310        | 619.89   | 
| Abdul-Jabbar,Bushra A | SOCIAL SERVICES COORDINATOR   | A65201   | HLTH-Health Department   | 2008-04-14T00:00:00 | 39354        | 35000.24 | 
```