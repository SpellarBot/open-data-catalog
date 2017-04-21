# DCLA Cultural Institutions Group Funding

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcla-cultural-institutions-group-funding) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ka27-qx5k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ka27-qx5k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ka27-qx5k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ka27-qx5k |
| Name | DCLA Cultural Institutions Group Funding |
| Attribution | Department of Cultural Affairs (DCLA) |
| Category | City Government |
| Tags | dcla cultural institutions group funding, cig, cultural affairs |
| Created | 2016-08-18T17:49:05Z |
| Publication Date | 2016-08-18T17:58:48Z |

## Description

Operating and energy support funding provided to members of the cultural institution group (CIG).

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag     | cultural_institutions_group_cig | Cultural Institutions Group (CIG) | text      | text        |
| Yes      | time           | fiscal_year_fy                  | Fiscal Year (FY)                  | number    | number      |
| Yes      | numeric metric | operating_support               | Operating Support                 | money     | money       |
| Yes      | numeric metric | energy_support                  | Energy Support                    | money     | money       |
```

## Time Field

```ls
Value = fiscal_year_fy
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ka27-qx5k d:2014-01-01T00:00:00.000Z t:cultural_institutions_group_cig="American Museum of Natural History" m:operating_support=8483800 m:energy_support=7611998

series e:ka27-qx5k d:2014-01-01T00:00:00.000Z t:cultural_institutions_group_cig="Bronx County Historical Society" m:operating_support=155178 m:energy_support=16172

series e:ka27-qx5k d:2014-01-01T00:00:00.000Z t:cultural_institutions_group_cig="Bronx Museum of the Arts" m:operating_support=579384 m:energy_support=212629
```

## Meta Commands

```ls
metric m:operating_support p:integer l:"Operating Support" t:dataTypeName=money

metric m:energy_support p:integer l:"Energy Support" t:dataTypeName=money

entity e:ka27-qx5k l:"DCLA Cultural Institutions Group Funding" t:attribution="Department of Cultural Affairs (DCLA)" t:url=https://data.cityofnewyork.us/api/views/ka27-qx5k

property e:ka27-qx5k t:meta.view v:id=ka27-qx5k v:category="City Government" v:averageRating=0 v:name="DCLA Cultural Institutions Group Funding" v:attribution="Department of Cultural Affairs (DCLA)"

property e:ka27-qx5k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ka27-qx5k t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| cultural_institutions_group_cig    | fiscal_year_fy | operating_support | energy_support | 
| ================================== | ============== | ================= | ============== | 
| American Museum of Natural History | 2014           | 8483800           | 7611998        | 
| Bronx County Historical Society    | 2014           | 155178            | 16172          | 
| Bronx Museum of the Arts           | 2014           | 579384            | 212629         | 
| Brooklyn Academy of Music          | 2014           | 2006587           | 864833         | 
| Brooklyn Botanic Garden            | 2014           | 3404959           | 572883         | 
| Brooklyn Children's Museum         | 2014           | 1642175           | 251497         | 
| Brooklyn Museum                    | 2014           | 5598637           | 2177447        | 
| Carnegie Hall                      | 2014           | 479835            | 1274240        | 
| David H. Koch Theater              | 2014           | 1060530           | 1257852        | 
| El Museo del Barrio                | 2014           | 444474            | 205065         | 
```