# Lobbyist Data - Employers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-employers) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/dmeb-2zra) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/dmeb-2zra/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/dmeb-2zra/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | dmeb-2zra |
| Name | Lobbyist Data - Employers |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | ethics, lobbyists |
| Created | 2015-06-09T22:21:28Z |
| Publication Date | 2015-10-20T21:01:58Z |

## Description

Employers of registered lobbyists as reported in the Lobbyist Statement of Registration. Due to requirements for lobbyists to re-register, the importance of showing year for most lobbying-related data, and some employers being reported by multiple lobbyists, the same employer often will have multiple records
See http://www.cityofchicago.org/city/en/depts/ethics/provdrs/lobby.html for more information on the Board of Ethics' role in regulating and reporting on lobbying in Chicago.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| No       |             | year         | Year         | number        | number        |
| Yes      | series tag  | employer_id  | EMPLOYER_ID  | text          | number        |
| Yes      | series tag  | name         | NAME         | text          | text          |
| No       |             | address_1    | ADDRESS_1    | text          | text          |
| No       |             | address_2    | ADDRESS_2    | text          | text          |
| Yes      | series tag  | city         | CITY         | text          | text          |
| Yes      | series tag  | state        | STATE        | text          | text          |
| Yes      | series tag  | zip          | ZIP          | text          | text          |
| Yes      | series tag  | country      | COUNTRY      | text          | text          |
| Yes      | series tag  | phone        | PHONE        | text          | text          |
| Yes      | series tag  | fax          | FAX          | text          | text          |
| Yes      | time        | created_date | CREATED_DATE | calendar_date | calendar_date |
| Yes      | series tag  | active       | ACTIVE       | text          | text          |
```

## Time Field

```ls
Value = created_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2,year
```

## Data Commands

```ls
series e:dmeb-2zra d:2015-06-15T13:59:07.000Z t:zip=60603 t:employer_id=4818 t:phone=312-920-1500 t:name="Lighten-Gale LLC" t:state=Il t:active=Y t:country="United States" t:city=Chicago m:row_number.dmeb-2zra=1

series e:dmeb-2zra d:2015-06-15T13:59:07.000Z t:zip=60602 t:employer_id=4099 t:phone=312-701-0221 t:fax=312-658-0464 t:name="Nicolay & Dart LLC" t:state=IL t:active=Y t:country="United States" t:city=Chicago m:row_number.dmeb-2zra=2

series e:dmeb-2zra d:2015-06-15T13:59:07.000Z t:zip=60602 t:employer_id=4099 t:phone=312-701-0221 t:fax=312-658-0464 t:name="Nicolay & Dart LLC" t:state=IL t:active=Y t:country="United States" t:city=Chicago m:row_number.dmeb-2zra=3
```

## Meta Commands

```ls
metric m:row_number.dmeb-2zra p:long l:"Row Number"

entity e:dmeb-2zra l:"Lobbyist Data - Employers" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/dmeb-2zra

property e:dmeb-2zra t:meta.view v:id=dmeb-2zra v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Employers" v:attribution="City of Chicago"

property e:dmeb-2zra t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:dmeb-2zra t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| year | employer_id | name                         | address_1                     | address_2  | city    | state | zip   | country       | phone        | fax          | created_date        | active | 
| ==== | =========== | ============================ | ============================= | ========== | ======= | ===== | ===== | ============= | ============ | ============ | =================== | ====== | 
| 2011 | 4818        | Lighten-Gale LLC             | 39 S. LaSalle St., Ste. 808   |            | Chicago | Il    | 60603 | United States | 312-920-1500 |              |                     | Y      | 
| 2012 | 4099        | Nicolay & Dart LLC           | 33 N. Dearborn St. Ste.2200   |            | Chicago | IL    | 60602 | United States | 312-701-0221 | 312-658-0464 |                     | Y      | 
| 2011 | 4099        | Nicolay & Dart LLC           | 33 N. Dearborn St. Ste.2200   |            | Chicago | IL    | 60602 | United States | 312-701-0221 | 312-658-0464 |                     | Y      | 
| 2013 | 7141        | Carol Ronen                  | 6033 N. Sheridan Rd           |            | Chicago | IL    | 60660 | United States | 773-919-4240 |              | 2013-01-09T00:00:00 | Y      | 
| 2011 | 4687        | Thompson Coburn LLP          | 55 E Monroe - 40th Floor      |            | Chicago | IL    | 60603 | United States | 312-580-2228 | 312-580-2201 |                     | Y      | 
| 2011 | 4186        | Foley & Lardner, LLP         | 321 N Clark St. #2800         |            | Chicago | IL    | 60610 | United States | 312-832-4500 | 312-832-4700 |                     | Y      | 
| 2012 | 4202        | K & L Gates LLP              |                               |            |         |       |       | United States |              |              |                     | Y      | 
| 2011 | 4202        | K & L Gates LLP              |                               |            |         |       |       | United States |              |              |                     | Y      | 
| 2012 | 4368        | DLA Piper US LLP             | 203 N. LaSalle St. Suite 1900 |            | Chicago | IL    | 60601 | United States | 312-368-4000 | 312-236-7516 |                     | Y      | 
|      | 6642        | Carpenter Lipps & Leland LLP | 180 N. LaSalle Street         | Suite 2640 | Chicago | IL    | 60601 | United States | 3127772824   |              | 2012-11-15T00:00:00 | Y      | 
```