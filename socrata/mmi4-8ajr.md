# State Specific Influenza Vaccination Coverage Among Women With Live Birth- PRAMS, 2009-10 Influenza Season

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-specific-influenza-vaccination-coverage-among-women-with-live-birth-prams-2009-10-in-c941c) |
| Metadata | [Link](https://data.cdc.gov/api/views/mmi4-8ajr) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/mmi4-8ajr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/mmi4-8ajr/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | mmi4-8ajr |
| Name | State Specific Influenza Vaccination Coverage Among Women With Live Birth- PRAMS, 2009-10 Influenza Season |
| Attribution | PRAMS |
| Category | Pregnancy & Vaccination |
| Tags | prams, flu shot, pregnant women, immunization |
| Created | 2013-06-19T14:27:03Z |
| Publication Date | 2013-06-19T14:47:20Z |

## Description

For more information about the Pregnancy Risk Assessment Monitoring System please visit http://www.cdc.gov/prams/. See http://www.cdc.gov/mmwr/preview/mmwrhtml/mm6107a1.htm?s_cid=mm6107a1_e for the MMWR article.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | state        | State        | text      | text        |
| Yes      | numeric metric | seasonal_n   | Seasonal n   | number    | number      |
| Yes      | numeric metric | seasonal     | Seasonal %   | percent   | percent     |
| Yes      | series tag     | seasonal_ci  | Seasonal CI  | text      | text        |
| Yes      | numeric metric | 2009_h1n1_n  | 2009 H1N1 n  | number    | number      |
| Yes      | numeric metric | 2009_h1n1    | 2009 H1N1 %  | percent   | percent     |
| Yes      | series tag     | 2009_h1n1_ci | 2009 H1N1 CI | text      | text        |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mmi4-8ajr d:2009-01-01T00:00:00.000Z t:seasonal_ci=?3.9 t:state="Rhode Island" t:2009_h1n1_ci=?3.9 m:seasonal=63.7 m:2009_h1n1=62.9 m:2009_h1n1_n=823 m:seasonal_n=821

series e:mmi4-8ajr d:2009-01-01T00:00:00.000Z t:seasonal_ci=?4.1 t:state=Texas t:2009_h1n1_ci=?4.0 m:seasonal=44.9 m:2009_h1n1=40.4 m:2009_h1n1_n=909 m:seasonal_n=898

series e:mmi4-8ajr d:2009-01-01T00:00:00.000Z t:seasonal_ci=?3.1 t:state="New York" t:2009_h1n1_ci=?3.0 m:seasonal=50.5 m:2009_h1n1=38.4 m:2009_h1n1_n=1617 m:seasonal_n=1587
```

## Meta Commands

```ls
metric m:seasonal_n p:integer l:"Seasonal n" t:dataTypeName=number

metric m:seasonal p:float l:"Seasonal %" t:dataTypeName=percent

metric m:2009_h1n1_n p:integer l:"2009 H1N1 n" t:dataTypeName=number

metric m:2009_h1n1 p:float l:"2009 H1N1 %" t:dataTypeName=percent

entity e:mmi4-8ajr l:"State Specific Influenza Vaccination Coverage Among Women With Live Birth- PRAMS, 2009-10 Influenza Season" t:attribution=PRAMS t:url=https://data.cdc.gov/api/views/mmi4-8ajr

property e:mmi4-8ajr t:meta.view v:id=mmi4-8ajr v:category="Pregnancy & Vaccination" v:attributionLink=http://www.cdc.gov/prams/ v:averageRating=0 v:name="State Specific Influenza Vaccination Coverage Among Women With Live Birth- PRAMS, 2009-10 Influenza Season" v:attribution=PRAMS

property e:mmi4-8ajr t:meta.view.owner v:id=tcys-idpb v:screenName="Helen Ding" v:displayName="Helen Ding"

property e:mmi4-8ajr t:meta.view.tableauthor v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:roleName=publisher v:displayName=CDC

property e:mmi4-8ajr t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state        | seasonal_n | seasonal | seasonal_ci | 2009_h1n1_n | 2009_h1n1 | 2009_h1n1_ci | 
| ============ | ========== | ======== | =========== | =========== | ========= | ============ | 
| Rhode Island | 821        | 63.7     | ?3.9        | 823         | 62.9      | ?3.9         | 
| Texas        | 898        | 44.9     | ?4.1        | 909         | 40.4      | ?4.0         | 
| New York     | 1587       | 50.5     | ?3.1        | 1617        | 38.4      | ?3.0         | 
| Lousianna    | 540        | 39.6     | ?5.2        | 546         | 28.8      | ?4.8         | 
| Nebraska     | 1198       | 65.4     | ?3.2        | 1207        | 56.5      | ?3.3         | 
| Oklahoma     | 1432       | 49.1     | ?4.4        | 1453        | 33.0      | ?4.2         | 
| Maine        | 709        | 64.0     | ?4.0        | 709         | 58.5      | ?4.1         | 
| New Jersey   | 1053       | 36.8     | ?3.2        | 1073        | 32.2      | ?3.0         | 
| Missouri     | 973        | 42.8     | ?3.7        | 983         | 38.2      | ?3.6         | 
| Hawaii       | 974        | 50.3     | ?4.0        | 987         | 44.9      | ?4.0         | 
```