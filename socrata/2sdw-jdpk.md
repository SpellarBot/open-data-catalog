# Mayor's Office of Housing and Community Development Bond Issuances

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mayors-office-of-housing-and-community-development-bond-issuances) |
| Metadata | [Link](https://data.sfgov.org/api/views/2sdw-jdpk) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/2sdw-jdpk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/2sdw-jdpk/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 2sdw-jdpk |
| Name | Mayor's Office of Housing and Community Development Bond Issuances |
| Attribution | Mayor's Office of Housing and Community Development |
| Category | Housing and Buildings |
| Tags | bond issuances, affordable housing |
| Created | 2016-06-14T17:56:36Z |
| Publication Date | 2016-06-15T19:32:23Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | project_id                 | Project ID                 | text          | number        |
| Yes      | series tag     | project_name               | Project Name               | text          | text          |
| Yes      | series tag     | bond_id                    | Bond ID                    | text          | text          |
| Yes      | series tag     | name_of_bond_issuance      | Name of Bond Issuance      | text          | text          |
| Yes      | time           | date_initial_bond_issuance | Date Initial Bond Issuance | calendar_date | calendar_date |
| Yes      | numeric metric | approved_issuance_amount   | Approved Issuance Amount   | money         | money         |
| Yes      | series tag     | issuing_agency             | Issuing Agency             | text          | text          |
```

## Time Field

```ls
Value = date_initial_bond_issuance
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2sdw-jdpk d:1988-12-31T00:00:00.000Z t:project_name="Geary Courtyard" t:issuing_agency=MOHCD t:project_id=338 t:bond_id=48 t:name_of_bond_issuance="1988B Geary Courtyard" m:approved_issuance_amount=18000000

series e:2sdw-jdpk d:2013-12-03T00:00:00.000Z t:project_name="Tenderloin Family Housing" t:issuing_agency=MOHCD t:project_id=152 t:bond_id=79 t:name_of_bond_issuance="2013C MF 201 Turk - Tenderloin Family" m:approved_issuance_amount=21103611

series e:2sdw-jdpk d:1998-12-01T00:00:00.000Z t:project_name="Mariposa Gardens" t:issuing_agency=SFRA t:project_id=299 t:bond_id=39 t:name_of_bond_issuance="1998E 1998F Mariposa Gardens Apts" m:approved_issuance_amount=4485000
```

## Meta Commands

```ls
metric m:approved_issuance_amount p:double l:"Approved Issuance Amount" t:dataTypeName=money

entity e:2sdw-jdpk l:"Mayor's Office of Housing and Community Development Bond Issuances" t:attribution="Mayor's Office of Housing and Community Development" t:url=https://data.sfgov.org/api/views/2sdw-jdpk

property e:2sdw-jdpk t:meta.view v:id=2sdw-jdpk v:category="Housing and Buildings" v:attributionLink=http://sf-moh.org/ v:averageRating=0 v:name="Mayor's Office of Housing and Community Development Bond Issuances" v:attribution="Mayor's Office of Housing and Community Development"

property e:2sdw-jdpk t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:2sdw-jdpk t:meta.view.owner v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:displayName="Charlie MacNulty"

property e:2sdw-jdpk t:meta.view.tableauthor v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:roleName=editor v:displayName="Charlie MacNulty"
```

## Top Records

```ls
| project_id | project_name                            | bond_id | name_of_bond_issuance                      | date_initial_bond_issuance | approved_issuance_amount | issuing_agency | 
| ========== | ======================================= | ======= | ========================================== | ========================== | ======================== | ============== | 
| 338        | Geary Courtyard                         | 48      | 1988B Geary Courtyard                      | 1988-12-31T00:00:00        | 18000000.00              | MOHCD          | 
| 152        | Tenderloin Family Housing               | 79      | 2013C MF 201 Turk - Tenderloin Family      | 2013-12-03T00:00:00        | 21103611.00              | MOHCD          | 
| 299        | Mariposa Gardens                        | 39      | 1998E 1998F Mariposa Gardens Apts          | 1998-12-01T00:00:00        | 4485000.00               | SFRA           | 
| 368        | Tower 737 (aka Post St Towers)          | 49      | 2000A Post Street Towers                   | 2000-12-31T00:00:00        | 17000000.00              | MOHCD          | 
| 385        | City Heights Apts (aka Avalon Nob Hill) | 3       | 1997A City Heights / Avalon Nob Hill       | 1997-07-29T00:00:00        | 20800000.00              | MOHCD          | 
| 385        | City Heights Apts (aka Avalon Nob Hill) | 90      | 1988A V MF City Heights - Sutter/Post Apts | 1988-04-08T00:00:00        | 21500000.00              | MOHCD          | 
| 1003       | SOMA Residences                         | 13      | 1998C 1998D SOMA Apts / 1045 Mission       | 1998-12-31T00:00:00        | 30000000.00              | SFRA           | 
| 1005       | Laurel Gardens Apartments               | 78      | 1998B Laurel Gardens Apts                  | 2007-10-01T00:00:00        | 357000.00                | SFRA           | 
| 1005       | Laurel Gardens Apartments               | 12      | 1998A Laurel Gardens Apts                  | 2007-10-01T00:00:00        | 1759000.00               | SFRA           | 
| 1043       | Golden Gate Apartments                  | 14      | 1999A and B Golden Gate Apts               | 1999-06-01T00:00:00        | 6752611.00               | SFRA           | 
```