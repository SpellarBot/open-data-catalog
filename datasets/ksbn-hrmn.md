# January 2015 FMU Monthly Report WQ EX Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/january-2015-fmu-monthly-report-wq-ex-data) |
| Metadata | [Link](https://data.wa.gov/api/views/ksbn-hrmn) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ksbn-hrmn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ksbn-hrmn/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ksbn-hrmn |
| Name | January 2015 FMU Monthly Report WQ EX Data |
| Attribution | WA Department of Ecology River and Stream Monitoring |
| Created | 2015-03-17T19:03:04Z |
| Publication Date | 2015-05-19T21:14:46Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | parameter  | Parameter | text      | text        |
| Yes      | numeric metric | centeral   | Central   | percent   | percent     |
| Yes      | numeric metric | eastern    | Eastern   | percent   | percent     |
| Yes      | numeric metric | northwest  | Northwest | percent   | percent     |
| Yes      | numeric metric | southwest  | Southwest | percent   | percent     |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ksbn-hrmn d:2015-01-01T00:00:00.000Z t:parameter="Monthly Average" m:southwest=0 m:northwest=0.2 m:centeral=0 m:eastern=0

series e:ksbn-hrmn d:2015-01-01T00:00:00.000Z t:parameter="5 Yr January Average" m:southwest=1.9 m:northwest=13.8 m:centeral=2.2 m:eastern=7.28
```

## Meta Commands

```ls
metric m:centeral p:float l:Central t:dataTypeName=percent

metric m:eastern p:float l:Eastern t:dataTypeName=percent

metric m:northwest p:float l:Northwest t:dataTypeName=percent

metric m:southwest p:float l:Southwest t:dataTypeName=percent

entity e:ksbn-hrmn l:"January 2015 FMU Monthly Report WQ EX Data" t:attribution="WA Department of Ecology River and Stream Monitoring" t:url=https://data.wa.gov/api/views/ksbn-hrmn

property e:ksbn-hrmn t:meta.view v:id=ksbn-hrmn v:attributionLink=http://www.ecy.wa.gov/programs/eap/fw_riv/rv_main.html v:averageRating=0 v:name="January 2015 FMU Monthly Report WQ EX Data" v:attribution="WA Department of Ecology River and Stream Monitoring"

property e:ksbn-hrmn t:meta.view.owner v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:ksbn-hrmn t:meta.view.tableauthor v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```

## Top Records

```ls
| parameter            | centeral | eastern | northwest | southwest | 
| ==================== | ======== | ======= | ========= | ========= | 
| Monthly Average      | 0.0      | 0.0     | 0.2       | 0.0       | 
| 5 Yr January Average | 2.2      | 7.28    | 13.8      | 1.9       | 
```