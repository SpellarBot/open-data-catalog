# Top Ten Elevator Offenders

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-ten-elevator-offenders-22a18) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/u3bu-v2bf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/u3bu-v2bf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/u3bu-v2bf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | u3bu-v2bf |
| Name | Top Ten Elevator Offenders |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | dob, department of buildings, buildings, disciplinary actions, electrician, plumber, master plumber, architect, engineer, surrender of privileges, elevator, offender, 2010, 2011, clean web |
| Created | 2011-10-11T00:51:45Z |
| Publication Date | 2013-06-21T20:50:10Z |

## Description

Top Ten Elevator Offenders

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | owner          | Owner          | text      | text        |
| Yes      | series tag  | street_address | Street Address | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u3bu-v2bf d:2011-10-10T17:51:50.000Z t:owner="Heights Inter-Neighborhood HDF" t:street_address="1694 Davidson Ave" m:row_number.u3bu-v2bf=1

series e:u3bu-v2bf d:2011-10-10T17:51:50.000Z t:owner="129-135 Ridge Street, HDFC" t:street_address="129 Ridge Street" m:row_number.u3bu-v2bf=2

series e:u3bu-v2bf d:2011-10-10T17:51:50.000Z t:owner="1627-1635 Amsterdam Avenue LLC" t:street_address="476 West 141 Street" m:row_number.u3bu-v2bf=3
```

## Meta Commands

```ls
metric m:row_number.u3bu-v2bf p:long l:"Row Number"

entity e:u3bu-v2bf l:"Top Ten Elevator Offenders" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/u3bu-v2bf

property e:u3bu-v2bf t:meta.view v:id=u3bu-v2bf v:category="Housing & Development" v:averageRating=0 v:name="Top Ten Elevator Offenders" v:attribution="Department of Buildings (DOB)"

property e:u3bu-v2bf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:u3bu-v2bf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | owner                                              | street_address        | 
| =========== | ================================================== | ===================== | 
| 1318269110  | Heights Inter-Neighborhood HDF                     | 1694 Davidson Ave     | 
| 1318269110  | 129-135 Ridge Street, HDFC                         | 129 Ridge Street      | 
| 1318269110  | 1627-1635 Amsterdam Avenue LLC                     | 476 West 141 Street   | 
| 1318269110  | 941 Intervale Realty                               | 941 Intervale Avenue  | 
| 1318269110  | Thermald Realty Associates LLP                     | 91 East Third Street  | 
| 1318269110  | Fulton Park Site 4 Houses, Inc.                    | 1711 Fulton Street    | 
| 1318269110  | 100 Audubon Holdings, LP                           | 551 West 170th Street | 
| 1318269110  | Tivoli Towers Housing Co.                          | 49 Crown Street       | 
| 1318269110  | Harlem River Park Houses aka River Park Associates | 10 Richman Plaza      | 
| 1318269110  | 885 Third Owner LLC                                | 885 Third Avenue      | 
```