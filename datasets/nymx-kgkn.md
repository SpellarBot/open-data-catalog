# Jail Population By County: Beginning 1997

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jail-population-by-county-beginning-1997) |
| Metadata | [Link](https://data.ny.gov/api/views/nymx-kgkn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nymx-kgkn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nymx-kgkn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nymx-kgkn |
| Name | Jail Population By County: Beginning 1997 |
| Attribution | New York State Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | jail population, jail census |
| Created | 2013-03-01T17:42:35Z |
| Publication Date | 2016-04-27T22:04:37Z |

## Description

A file containing the average daily census for county for each year displayed (e.g., daily counts are averaged and then divided by the number of days reported for that year).  The population report categorizes inmates by type of offender and includes:  Sentenced, Civil, Federal, Technical Parole Violators, State Readies and Other Unsentenced.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | facility_name              | Facility Name              | text      | text        |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | numeric metric | census                     | Census                     | number    | number      |
| Yes      | numeric metric | sentenced                  | Sentenced                  | number    | number      |
| Yes      | numeric metric | civil                      | Civil                      | number    | number      |
| Yes      | numeric metric | federal                    | Federal                    | number    | number      |
| Yes      | numeric metric | technical_parole_violators | Technical Parole Violators | number    | number      |
| Yes      | numeric metric | state_readies              | State Readies              | number    | number      |
| Yes      | numeric metric | other_unsentenced          | Other Unsentenced          | number    | number      |
| Yes      | numeric metric | boarded_out                | Boarded Out                | number    | number      |
| Yes      | numeric metric | boarded_in                 | Boarded In                 | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nymx-kgkn d:1997-01-01T00:00:00.000Z t:facility_name="Albany County Jail" m:census=730 m:federal=62 m:state_readies=23 m:boarded_in=15 m:sentenced=268 m:civil=0 m:boarded_out=4 m:other_unsentenced=324 m:technical_parole_violators=56

series e:nymx-kgkn d:1998-01-01T00:00:00.000Z t:facility_name="Albany County Jail" m:census=714 m:federal=64 m:state_readies=45 m:boarded_in=30 m:sentenced=231 m:civil=0 m:boarded_out=4 m:other_unsentenced=309 m:technical_parole_violators=65

series e:nymx-kgkn d:1999-01-01T00:00:00.000Z t:facility_name="Albany County Jail" m:census=761 m:federal=51 m:state_readies=49 m:boarded_in=30 m:sentenced=266 m:civil=0 m:boarded_out=4 m:other_unsentenced=327 m:technical_parole_violators=68
```

## Meta Commands

```ls
metric m:census p:integer l:Census t:dataTypeName=number

metric m:sentenced p:integer l:Sentenced t:dataTypeName=number

metric m:civil p:integer l:Civil t:dataTypeName=number

metric m:federal p:integer l:Federal t:dataTypeName=number

metric m:technical_parole_violators p:integer l:"Technical Parole Violators" t:dataTypeName=number

metric m:state_readies p:integer l:"State Readies" t:dataTypeName=number

metric m:other_unsentenced p:integer l:"Other Unsentenced" t:dataTypeName=number

metric m:boarded_out p:integer l:"Boarded Out" t:dataTypeName=number

metric m:boarded_in p:integer l:"Boarded In" t:dataTypeName=number

entity e:nymx-kgkn l:"Jail Population By County: Beginning  1997" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/nymx-kgkn

property e:nymx-kgkn t:meta.view v:id=nymx-kgkn v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/crimnet/ojsa/jail_pop_y.pdf v:averageRating=0 v:name="Jail Population By County: Beginning  1997" v:attribution="New York State Division of Criminal Justice Services"

property e:nymx-kgkn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nymx-kgkn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nymx-kgkn t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| facility_name      | year | census | sentenced | civil | federal | technical_parole_violators | state_readies | other_unsentenced | boarded_out | boarded_in | 
| ================== | ==== | ====== | ========= | ===== | ======= | ========================== | ============= | ================= | =========== | ========== | 
| Albany County Jail | 1997 | 730    | 268       | 0     | 62      | 56                         | 23            | 324               | 4           | 15         | 
| Albany County Jail | 1998 | 714    | 231       | 0     | 64      | 65                         | 45            | 309               | 4           | 30         | 
| Albany County Jail | 1999 | 761    | 266       | 0     | 51      | 68                         | 49            | 327               | 4           | 30         | 
| Albany County Jail | 2000 | 710    | 230       | 0     | 53      | 48                         | 17            | 363               | 1           | 22         | 
| Albany County Jail | 2001 | 750    | 185       | 0     | 57      | 46                         | 5             | 457               | 2           | 7          | 
| Albany County Jail | 2002 | 892    | 211       | 0     | 54      | 45                         | 11            | 571               | 2           | 54         | 
| Albany County Jail | 2003 | 892    | 211       | 0     | 54      | 45                         | 11            | 571               | 2           | 54         | 
| Albany County Jail | 2004 | 870    | 206       | 0     | 62      | 55                         | 12            | 536               | 1           | 92         | 
| Albany County Jail | 2005 | 786    | 170       | 0     | 67      | 65                         | 13            | 472               | 1           | 60         | 
| Albany County Jail | 2006 | 831    | 169       | 0     | 66      | 61                         | 21            | 514               | 1           | 42         | 
```