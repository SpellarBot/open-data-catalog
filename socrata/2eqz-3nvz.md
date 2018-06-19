# Lobbyist Data - Lobbyist, Employer, Client Combinations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-employer-client-combinations) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2eqz-3nvz) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2eqz-3nvz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2eqz-3nvz/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2eqz-3nvz |
| Name | Lobbyist Data - Lobbyist, Employer, Client Combinations |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | ethics, lobbyists |
| Created | 2015-06-10T21:27:46Z |
| Publication Date | 2015-10-20T22:04:15Z |

## Description

Each unique combination of a lobbyist, his/her employer, and a client of that employer.  This dataset can be used to see relationships between these three entities.  Each has a separate dataset with more detailed information about each lobbyist, employer, or client. See http://www.cityofchicago.org/city/en/depts/ethics/provdrs/lobby.html for more information on the Board of Ethics' role in regulating and reporting on lobbying in Chicago.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| Yes      | time        | year                    | Year                    | number    | number      |
| Yes      | series tag  | lobbyist_id             | LOBBYIST_ID             | text      | number      |
| Yes      | series tag  | employer_id             | EMPLOYER_ID             | text      | number      |
| Yes      | series tag  | client_id               | CLIENT_ID               | text      | number      |
| Yes      | series tag  | lobbyist_salutation     | LOBBYIST_SALUTATION     | text      | text        |
| Yes      | series tag  | lobbyist_first_name     | LOBBYIST_FIRST_NAME     | text      | text        |
| Yes      | series tag  | lobbyist_middle_initial | LOBBYIST_MIDDLE_INITIAL | text      | text        |
| Yes      | series tag  | lobbyist_last_name      | LOBBYIST_LAST_NAME      | text      | text        |
| Yes      | series tag  | lobbyist_suffix         | LOBBYIST_SUFFIX         | text      | text        |
| Yes      | series tag  | employer_name           | EMPLOYER_NAME           | text      | text        |
| Yes      | series tag  | client_name             | CLIENT_NAME             | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:2eqz-3nvz l:"Lobbyist Data - Lobbyist, Employer, Client Combinations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/2eqz-3nvz

property e:2eqz-3nvz t:meta.view v:id=2eqz-3nvz v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Lobbyist, Employer, Client Combinations" v:attribution="City of Chicago"

property e:2eqz-3nvz t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:2eqz-3nvz t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| year | lobbyist_id | employer_id | client_id | lobbyist_salutation | lobbyist_first_name | lobbyist_middle_initial | lobbyist_last_name | lobbyist_suffix | employer_name          | client_name                        | 
| ==== | =========== | =========== | ========= | =================== | =================== | ======================= | ================== | =============== | ====================== | ================================== | 
| 2011 | 6448        | 4357        | 12296     | Mr                  | Richard             | R                       | Boykin             |                 | Barnes & Thormburg LLP | Youth Connection Charter School    | 
| 2011 | 6450        | 4359        | 12300     | Mr                  | John                | J                       | George             |                 | Daley and George LLP   | Chicago University Commons LLC     | 
| 2011 | 6450        | 4359        | 13615     | Mr                  | John                | J                       | George             |                 | Daley and George LLP   | Boyce-II, LLC                      | 
| 2011 | 6450        | 4359        | 13618     | Mr                  | John                | J                       | George             |                 | Daley and George LLP   | Fourth Presbyterian Church         | 
| 2011 | 6450        | 4359        | 13620     | Mr                  | John                | J                       | George             |                 | Daley and George LLP   | Orchard Heritage Inc               | 
| 2011 | 6450        | 4359        | 13624     | Mr                  | John                | J                       | George             |                 | Daley and George LLP   | Behringer Harvard Burnham LLC      | 
| 2011 | 6450        | 4359        | 13635     | Mr                  | John                | J                       | George             |                 | Daley and George LLP   | SF CH I, LLC                       | 
| 2011 | 6454        | 4363        | 12350     | Mr                  | Thomas              | R                       | Donovan            |                 | Donovan Group LLC      | Quantum Crossings, LLC             | 
| 2011 | 6455        | 4364        | 12359     | Mr                  | John                | J                       | Kelly, Jr.         |                 | ALL-CIRCO, Inc.        | Kinder Morgan Energy Partners      | 
| 2011 | 6458        | 4367        | 12372     | Mr                  | Richard             |                         | Klawiter           |                 | DLA Piper US LLP       | Preservation of Affordable Housing | 
```