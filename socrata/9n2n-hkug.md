# Directory of Tennis Permit Fees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-tennis-permit-fees-f77de) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9n2n-hkug) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9n2n-hkug/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9n2n-hkug/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9n2n-hkug |
| Name | Directory of Tennis Permit Fees |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Recreation |
| Tags | dpr, recreation, park, tennis, permit, fee, healthy living |
| Created | 2013-01-24T19:03:36Z |
| Publication Date | 2013-06-21T20:28:33Z |

## Description

Fee details for obtaining Tennis Permits

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | age                  | Age                  | text      | text        |
| Yes      | numeric metric | fee                  | Fee                  | money     | text        |
| Yes      | numeric metric | duplicate_permit_fee | Duplicate Permit Fee | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9n2n-hkug d:2013-01-24T11:03:38.000Z t:age="Adults (ages 18-61)" m:fee=200 m:duplicate_permit_fee=15

series e:9n2n-hkug d:2013-01-24T11:03:38.000Z t:age="Senior Citizens (ages 62 and over)" m:fee=20 m:duplicate_permit_fee=15

series e:9n2n-hkug d:2013-01-24T11:03:38.000Z t:age="Juniors (ages 17 and under)" m:fee=10 m:duplicate_permit_fee=6
```

## Meta Commands

```ls
metric m:fee p:long l:Fee t:dataTypeName=money

metric m:duplicate_permit_fee p:long l:"Duplicate Permit Fee" t:dataTypeName=money

entity e:9n2n-hkug l:"Directory of Tennis Permit Fees" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/9n2n-hkug

property e:9n2n-hkug t:meta.view v:id=9n2n-hkug v:category=Recreation v:attributionLink=https://www.nycgovparks.org/permits/tennis-permits v:averageRating=0 v:name="Directory of Tennis Permit Fees" v:attribution="Department of Parks and Recreation (DPR)"

property e:9n2n-hkug t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9n2n-hkug t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | age                                                  | fee  | duplicate_permit_fee | 
| =========== | ==================================================== | ==== | ==================== | 
| 1359025418  | Adults (ages 18-61)                                  | $200 | $15                  | 
| 1359025418  | Senior Citizens (ages 62 and over)                   | $20  | $15                  | 
| 1359025418  | Juniors (ages 17 and under)                          | $10  | $6                   | 
| 1359025418  | Single-Play Tickets (all ages, no photograph needed) | $15  |                      | 
```